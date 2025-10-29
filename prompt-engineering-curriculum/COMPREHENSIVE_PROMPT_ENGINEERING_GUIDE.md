# Comprehensive Guide to Prompt Engineering Techniques
## A Complete Reference for Student Assessment and Meta-Prompt Tutoring

### Document Purpose
This guide provides a comprehensive taxonomy of prompt engineering techniques suitable for middle and high school student assessment. Each technique includes definitions, use cases, examples, and common student mistakes.

---

## Table of Contents
1. [Basic Prompt Types](#1-basic-prompt-types)
2. [Advanced Techniques](#2-advanced-techniques)
3. [Context Engineering Approaches](#3-context-engineering-approaches)
4. [Role-Based Prompting](#4-role-based-prompting)
5. [Constraint-Based Prompting](#5-constraint-based-prompting)
6. [Multi-Step Reasoning Prompts](#6-multi-step-reasoning-prompts)
7. [Creative vs Analytical Prompts](#7-creative-vs-analytical-prompts)
8. [Combined Techniques](#8-combined-techniques)

---

## 1. Basic Prompt Types

### 1.1 Instruction Prompts

**Definition:** Direct commands or requests that ask the AI to perform a specific action.

**When to Use:**
- When you need a straightforward task completed
- When the desired outcome is clear and simple
- For basic explanations or definitions
- As building blocks for more complex prompts

**Example:**
```
Explain the Pythagorean theorem in simple terms.
```

**Common Student Mistakes:**
- Being too vague ("explain math")
- Forgetting to specify the audience level
- Not indicating desired depth or format
- Assuming AI knows their background knowledge

**Better Version:**
```
Explain the Pythagorean theorem to a 9th grade student who understands basic algebra. Include why it's useful and give one practical example.
```

---

### 1.2 Question Prompts

**Definition:** Prompts structured as questions to elicit information, explanations, or analysis.

**When to Use:**
- When seeking specific information
- To test understanding of a concept
- To generate discussion points
- For clarification on complex topics

**Example:**
```
What are the main causes of the American Civil War?
```

**Common Student Mistakes:**
- Asking yes/no questions when they want detailed answers
- Not providing context about their knowledge level
- Asking multiple unrelated questions at once
- Not specifying the type of answer they want (brief, detailed, etc.)

**Better Version:**
```
What are the main causes of the American Civil War? I'm a 10th grader writing an essay and I already know about slavery, but my teacher said there were economic and political causes too. Can you explain how these different causes connected?
```

---

### 1.3 Completion Prompts

**Definition:** Prompts that provide the beginning of content and ask AI to continue or complete it.

**When to Use:**
- When you need help continuing a thought or narrative
- For brainstorming and idea generation
- To see alternative ways to complete something
- When you're stuck in writing or problem-solving

**Example:**
```
I started my essay with "The Industrial Revolution changed society in three major ways..." but I'm not sure how to continue. Help me complete this introduction.
```

**Common Student Mistakes:**
- Not providing enough initial content for context
- Using this to have AI write their entire assignment
- Not specifying the desired tone or direction
- Forgetting to mention length or format constraints

**Better Version:**
```
I started my essay introduction with "The Industrial Revolution changed society in three major ways..." I want to mention economic, social, and technological changes. Help me complete the next 2-3 sentences that preview these points without going into detail yet. Keep the tone academic but not overly formal.
```

---

### 1.4 Comparison Prompts

**Definition:** Requests that ask AI to compare and contrast multiple concepts, ideas, or approaches.

**When to Use:**
- When studying differences and similarities
- For decision-making between options
- To deepen understanding of concepts
- When preparing for essay questions about comparison

**Example:**
```
Compare photosynthesis and cellular respiration.
```

**Common Student Mistakes:**
- Not specifying what aspects to compare
- Forgetting to mention their grade level
- Not indicating if they want similarities, differences, or both
- Missing an opportunity to show what they already understand

**Better Version:**
```
Compare photosynthesis and cellular respiration in terms of inputs, outputs, and where they happen in the cell. I'm a 7th grader and I understand they're opposites somehow, but I get confused about which does what. Create a simple comparison that helps me remember the difference.
```

---

### 1.5 Explanation Prompts

**Definition:** Requests for AI to clarify, elaborate on, or make sense of a concept or process.

**When to Use:**
- When learning new material
- When something is confusing in readings or lectures
- To break down complex concepts
- To understand the "why" behind facts

**Example:**
```
Explain how the water cycle works.
```

**Common Student Mistakes:**
- Not mentioning what specifically confuses them
- Forgetting to provide their current level of understanding
- Not requesting appropriate explanation style (analogy, step-by-step, etc.)
- Being too broad without focusing on their actual confusion

**Better Version:**
```
Explain how the water cycle works. I'm a 6th grader and I understand evaporation (water going up) and rain (water coming down), but I don't understand what happens in between. Why do clouds form? Use an analogy if possible to help me remember.
```

---

### 1.6 Summarization Prompts

**Definition:** Requests for AI to condense longer content into key points or brief overviews.

**When to Use:**
- When reviewing material for tests
- To extract main ideas from readings
- To create study guides
- When time is limited

**Example:**
```
Summarize Chapter 5 of my biology textbook.
```

**Common Student Mistakes:**
- Not specifying desired length of summary
- Forgetting to mention what aspects are most important
- Not providing the actual text or clear reference
- Not indicating purpose (quiz prep, essay research, etc.)

**Better Version:**
```
I need to summarize the key concepts from my biology chapter on genetics for a quiz tomorrow. Focus on Mendelian genetics, Punnett squares, and dominant/recessive traits. Keep it to 5-7 bullet points I can memorize.
```

---

### 1.7 Generation Prompts

**Definition:** Requests for AI to create new content such as examples, practice problems, or ideas.

**When to Use:**
- When you need practice problems
- For brainstorming ideas
- To see examples of concepts
- When creating study materials

**Example:**
```
Generate practice problems for algebra.
```

**Common Student Mistakes:**
- Being too vague about difficulty level
- Not specifying the type or quantity needed
- Forgetting to mention which specific topics to cover
- Not indicating if they want solutions included

**Better Version:**
```
Generate 5 practice problems for solving two-step algebraic equations (like 2x + 3 = 11). Make them medium difficulty for an 8th grader. Include the problems first, then solutions at the end so I can try them myself.
```

---

## 2. Advanced Techniques

### 2.1 Zero-Shot Prompting

**Definition:** Prompting the AI without providing any examples, relying solely on instructions and the AI's training.

**When to Use:**
- For well-understood, common tasks
- When you can't easily create examples
- For exploratory questions
- When the task is straightforward

**Example:**
```
Act as a biology tutor. Explain cellular respiration to a 10th grade student using an analogy to something in everyday life.
```

**Common Student Mistakes:**
- Using zero-shot when few-shot would be more effective
- Not being detailed enough in instructions
- Forgetting role, context, or format specifications
- Expecting AI to read their mind about desired output

**Better Version:**
```
Act as a biology tutor who specializes in making complex concepts relatable. I'm a 10th grader preparing for a test on cellular respiration. I understand it makes energy, but I don't understand the steps. Explain the process using an analogy to a factory or power plant - something I can visualize. Break it down into 3-4 main steps.
```

---

### 2.2 Few-Shot Prompting

**Definition:** Providing 2-4 examples of the pattern or format you want AI to follow, then asking it to apply the same pattern to your task.

**When to Use:**
- When you need a very specific format
- When instructions alone don't capture what you want
- For consistent output structure
- When the desired pattern is easier to show than explain
- **Google recommends using few-shot examples whenever possible for best results**

**Example:**
```
I want you to check my math work in this format:

Example 1:
Problem: 3x + 5 = 14
Student work: 3x = 9, x = 3
Feedback: Correct! All steps shown properly.

Example 2:
Problem: 2x - 6 = 10
Student work: 2x = 4, x = 2
Feedback: Error - you forgot to add 6 to both sides. Should be 2x = 16, so x = 8.

Now check my work:
Problem: 5x + 3 = 23
Student work: 5x = 20, x = 4
```

**Common Student Mistakes:**
- Including too many examples (more than 4-5)
- Making examples inconsistent in format
- Using examples too different from actual task
- Not making the pattern obvious enough
- Mixing what to do and what not to do in examples

**Better Version with Consistent Formatting:**
```
Check my Spanish vocabulary practice using this exact format:

Example:
Spanish: el gato
Student translation: the dog
Feedback: ✗ Incorrect. "Gato" means "cat." Try again.

Example:
Spanish: la casa
Student translation: the house
Feedback: ✓ Correct! Perfect translation.

Now check mine:
Spanish: el libro
Student translation: [my answer]
```

---

### 2.3 Multi-Shot Prompting

**Definition:** An extension of few-shot prompting using multiple examples (typically 5+) to show more complex patterns or variations.

**When to Use:**
- For highly specific or complex formats
- When showing variety within a pattern
- For nuanced task requirements
- When few-shot isn't capturing the full pattern

**Example:**
```
Grade my essay thesis statements using these examples:

Example 1:
Thesis: "Technology is important."
Grade: D - Too vague, no specific claim

Example 2:
Thesis: "Social media affects teenagers."
Grade: C - Better but still unclear how

Example 3:
Thesis: "Social media has increased teenage anxiety by creating constant comparison."
Grade: B - Specific but needs broader significance

Example 4:
Thesis: "Social media platforms have fundamentally altered teenage mental health by promoting constant comparison, reducing face-to-face interaction, and creating addictive feedback loops."
Grade: A - Specific, clear, arguable, significant

Example 5:
Thesis: "Social media is bad for everyone and should be banned."
Grade: C - Strong claim but too absolute and simplistic

Now grade my thesis: [student's thesis]
```

**Common Student Mistakes:**
- Using too many similar examples
- Not showing enough variety
- Making examples too long or complex
- Losing consistency across many examples
- Using multi-shot when few-shot would suffice

---

### 2.4 Chain-of-Thought (CoT) Prompting

**Definition:** Explicitly asking AI to show its reasoning process step-by-step before reaching a conclusion.

**When to Use:**
- For complex problem-solving
- When you need to understand the reasoning
- For math and logic problems
- To catch errors in reasoning
- When learning HOW to think through problems

**Example:**
```
Solve this word problem and show your reasoning step-by-step:

"Sarah has 3 times as many books as Tom. Together they have 48 books. How many books does each person have?"

Think through each step:
1. What do we know?
2. What variables can we set up?
3. What equation represents the situation?
4. How do we solve it?
5. Does the answer make sense?
```

**Common Student Mistakes:**
- Not being explicit about wanting step-by-step reasoning
- Skipping the verification step
- Not asking AI to explain WHY each step works
- Using CoT for simple problems that don't need it
- Forgetting to ask AI to check if answer makes sense

**Better Version:**
```
I need help solving this word problem, but don't just give me the answer. Show me your complete chain of thought:

Problem: "A rectangle's length is 5 cm more than its width. The perimeter is 46 cm. Find the dimensions."

Please think through this step-by-step:
1. First, identify what we know and what we're looking for
2. Set up variables (explain your choice)
3. Write the equations based on the given information
4. Show the solving process with explanation for each step
5. Check if your answer makes logical sense

I'm a 9th grader learning algebra, so explain each step clearly.
```

---

### 2.5 Self-Consistency Prompting

**Definition:** Asking AI to solve a problem multiple ways or from multiple angles to verify the answer is consistent.

**When to Use:**
- For high-stakes problems where accuracy matters
- When learning multiple solution methods
- To verify complex calculations
- When understanding different approaches to same problem

**Example:**
```
Solve this quadratic equation using three different methods and verify they all get the same answer:

x² + 5x + 6 = 0

Method 1: Factoring
Method 2: Quadratic formula
Method 3: Completing the square

Show all work for each method and confirm the solutions match.
```

**Common Student Mistakes:**
- Not specifying which different methods to use
- Accepting first answer without verification
- Not comparing results between methods
- Using this for every simple problem (overkill)

**Better Version:**
```
I need to solve x² - 4x - 5 = 0 and I want to verify my answer is correct by using two different methods:

1. First solve by factoring (show all steps)
2. Then solve using the quadratic formula (show all steps)
3. Verify both methods give the same x values
4. Graph or explain why both answers make sense

I'm learning quadratics and want to make sure I understand multiple approaches. I'm an 11th grader in Algebra 2.
```

---

### 2.6 Tree of Thoughts Prompting

**Definition:** Exploring multiple reasoning paths or solution branches, then evaluating which path is best.

**When to Use:**
- For open-ended problems with multiple approaches
- When brainstorming strategies
- For complex decision-making
- When learning to evaluate different solutions

**Example:**
```
I need to write an essay arguing whether schools should have uniforms. Help me explore different argumentative approaches:

Branch 1: Focus on equality and reducing economic differences
Branch 2: Focus on safety and identification
Branch 3: Focus on academic focus vs. distraction

For each branch:
1. What would the main argument be?
2. What evidence would support it?
3. What are the strengths of this approach?
4. What are the weaknesses?

Then help me decide which approach would make the strongest essay.
```

**Common Student Mistakes:**
- Not exploring enough distinct branches
- Not evaluating which path is best
- Getting overwhelmed with too many options
- Not having criteria for choosing best path
- Using this for problems with one clear solution path

**Better Version:**
```
I have to solve this problem: "Design a school fundraiser that could raise $5,000." Help me think through different possible approaches before choosing one:

Option A: Large event (like a carnival)
Option B: Ongoing sales (like selling items)
Option C: Sponsorship/donations
Option D: Multiple small events

For each option, analyze:
- Feasibility for high school students
- Potential to reach $5,000 goal
- Required resources
- Potential challenges
- Timeline needed

Then recommend which option or combination makes most sense and why.
```

---

### 2.7 Socratic Prompting

**Definition:** Requesting that AI guide learning through questions rather than giving direct answers, promoting critical thinking.

**When to Use:**
- When you want to figure things out yourself
- To develop deeper understanding
- For test preparation
- When trying to identify gaps in knowledge
- To prevent AI from doing work for you

**Example:**
```
Act as a Socratic tutor. I'm trying to understand why the American Revolution happened, but don't tell me the answer directly. Instead, ask me questions that help me think through the causes myself.

I know there was taxation without representation, but I don't fully understand why that was such a big deal.

Guide me with questions, not answers.
```

**Common Student Mistakes:**
- Getting frustrated when AI asks questions instead of giving answers
- Not engaging seriously with the questions posed
- Forgetting to specify what they already know
- Not requesting questions appropriate to their level
- Using this when they actually need direct explanations first

**Better Version:**
```
Act as a Socratic tutor helping a 10th grader understand photosynthesis conceptually.

What I currently know:
- Plants use sunlight somehow
- They need water and CO2
- They make oxygen and sugar

What I don't understand:
- Why they need those specific things
- What the sunlight actually does
- How it all works together

Ask me questions that help me figure out the process myself. If I'm stuck, give me a small hint, then ask another question. Don't explain it directly unless I really can't figure it out.
```

---

### 2.8 Analogical Prompting

**Definition:** Requesting explanations using analogies, metaphors, or comparisons to familiar concepts.

**When to Use:**
- For abstract or complex concepts
- When struggling with unfamiliar material
- To create memorable understanding
- For visual and concrete learners

**Example:**
```
Explain how the internet works using an analogy to something I encounter in everyday life. I'm a 7th grader and I don't understand what servers, routers, and IP addresses do.
```

**Common Student Mistakes:**
- Not specifying what analogies they'd relate to
- Accepting surface-level analogies without deep understanding
- Not asking AI to explain how the analogy maps to reality
- Using analogies as complete understanding (they're starting points)

**Better Version:**
```
I'm a 7th grader learning about how the internet works and I'm confused about servers, routers, and IP addresses.

Explain these using an analogy to either:
- The postal system
- A school or library system
- A road/highway system

Whichever analogy works best. Then help me understand:
1. What each part of the internet matches in the analogy
2. Where the analogy works really well
3. Where the analogy breaks down (what's different in reality)
```

---

## 3. Context Engineering Approaches

### 3.1 Background Context

**Definition:** Providing personal information about your knowledge level, learning style, and situation.

**When to Use:**
- At the start of any interaction
- When beginning a new topic
- To get appropriately leveled responses
- To make AI responses relevant to you specifically

**Example:**
```
I'm a 9th grade student who is generally strong in English but struggles with analyzing poetry. I understand basic literary devices like metaphor and simile, but I have trouble identifying themes and deeper meanings. I learn best with concrete examples.
```

**Components to Include:**
- Grade level / age
- General skill level in subject
- Specific strengths and weaknesses
- Learning style preferences
- Relevant background knowledge

**Common Student Mistakes:**
- Providing too little context (AI makes wrong assumptions)
- Including irrelevant personal information
- Not updating context as conversation continues
- Being too modest or too confident about skill level

**Better Example:**
```
Context about me:
- 11th grader in AP Chemistry
- Strong in math, understand calculations well
- Struggle with conceptual understanding and "why" things happen
- Need to see real-world applications to understand
- Currently learning about equilibrium reactions
- Understand Le Chatelier's Principle in theory but can't apply it to problems
```

---

### 3.2 Task Context

**Definition:** Information about the specific assignment, project, or goal you're working toward.

**When to Use:**
- When working on specific assignments
- To align AI help with teacher expectations
- When you need to meet certain requirements
- To ensure appropriate depth and format

**Example:**
```
Task context:
- Writing a 5-paragraph persuasive essay
- Topic: Should school start times be later for high school?
- Audience: My English teacher and classmates
- Must include: thesis statement, 3 supporting arguments with evidence, acknowledgment of counterarguments, conclusion
- Due in 3 days
- Currently stuck on: finding credible evidence for my arguments
```

**Components to Include:**
- Type of assignment
- Specific requirements
- Due date / timeline
- What part you're working on
- What you've already completed
- Grading criteria if known

**Common Student Mistakes:**
- Not mentioning specific requirements
- Forgetting to explain what they've already done
- Not clarifying what help they need vs. what they'll do themselves
- Missing teacher's specific expectations

---

### 3.3 Constraint Context

**Definition:** Explicit boundaries, limitations, or requirements that shape the help you need.

**When to Use:**
- To maintain academic integrity
- When following specific teacher instructions
- To practice specific skills
- To focus AI on relevant information only

**Example:**
```
Constraints for this task:
- Must only use information from chapters 7-9 of our textbook (don't reference outside sources)
- Must be at 10th grade vocabulary level (our teacher checks for this)
- Need to show my work, not just get answers
- Can't use a calculator for this assignment
- Essay must be exactly 500-600 words
```

**Common Student Mistakes:**
- Not being clear about academic integrity boundaries
- Forgetting specific teacher restrictions
- Not explaining what they can vs. cannot use
- Being too restrictive (preventing helpful assistance)

---

### 3.4 Temporal Context

**Definition:** Information about timing, deadlines, and where you are in the learning process.

**When to Use:**
- When time affects depth of response needed
- For study planning
- To prioritize information
- When cramming vs. deep learning

**Example:**
```
Temporal context:
- Test is tomorrow morning at 8 AM
- Currently 7 PM - have about 2 hours to study
- Teacher said test covers chapters 5-7, with emphasis on chapter 6
- We've been learning this for 2 weeks, but I missed 3 classes due to illness
- This is a major test worth 20% of our grade
```

**Common Student Mistakes:**
- Not mentioning how much time they have
- Forgetting to prioritize most important material
- Not indicating whether this is initial learning or review
- Missing information about what's already been covered

---

### 3.5 Resource Context

**Definition:** Information about materials, tools, and resources available or required for the task.

**When to Use:**
- When specific resources must or cannot be used
- For research projects
- When materials matter for approach
- To align help with available tools

**Example:**
```
Resource context:
- Have access to: our textbook, class notes, school library database
- Required to use: at least 3 peer-reviewed sources
- Cannot use: Wikipedia or general websites
- Have available: scientific calculator (not graphing)
- Time in library: 2 hours today after school
```

**Common Student Mistakes:**
- Not mentioning required vs. optional resources
- Forgetting about available tools
- Not clarifying what resources they've already used
- Missing restrictions on sources

---

### 3.6 Collaborative Context

**Definition:** Information about who else is involved and how that affects the task.

**When to Use:**
- For group projects
- When teacher has specific expectations
- When working with tutors or parents
- To clarify your specific role

**Example:**
```
Collaborative context:
- This is a group project with 3 other students
- My specific role: research and write the introduction section
- Others are covering: methods, results, conclusion
- Need my part to be: 300-400 words, match academic tone
- Working together on: overall thesis and key arguments
- Meeting tomorrow to combine our sections
```

**Common Student Mistakes:**
- Not clarifying their specific responsibility
- Asking AI to do group members' parts
- Not mentioning need for consistency with others' work
- Forgetting collaborative deadlines

---

### 3.7 Emotional/Motivational Context

**Definition:** Information about feelings, confidence level, and motivation that may affect learning.

**When to Use:**
- When frustrated or confused
- To get encouraging support
- When anxiety affects learning
- To shape tone of responses

**Example:**
```
Emotional context:
- Really stressed about this test - it's my weakest subject
- Failed the last quiz and need to do well this time
- Usually understand in class but get confused doing homework alone
- Worried I'm not good at math generally
- Need explanations that build confidence, not just correct answers
```

**Common Student Mistakes:**
- Being too vulnerable or sharing truly personal issues (AI isn't therapy)
- Not mentioning when they need encouraging tone
- Hiding confusion (preventing AI from adjusting approach)
- Not asking for confidence-building help when needed

---

## 4. Role-Based Prompting

### 4.1 Subject Expert Roles

**Definition:** Assigning AI the role of a teacher, tutor, or expert in a specific subject area.

**When to Use:**
- For subject-specific help
- To get appropriately leveled explanations
- When you need expert knowledge
- For most academic questions

**Examples:**
```
"Act as a biology teacher for 10th graders"
"You are a chemistry tutor specializing in organic chemistry"
"Pretend you're a history professor expert in World War II"
"Take on the role of a math teacher who's really good at explaining algebra"
```

**Grade-Level Variations:**
- 7th grade: "Act as a patient [subject] teacher who uses lots of examples"
- 9th grade: "Act as a [subject] tutor who explains concepts clearly"
- 11th grade: "Act as a [subject] professor who challenges thinking"

**Common Student Mistakes:**
- Not specifying grade level expertise
- Forgetting to mention teaching approach needed
- Using generic "teacher" without subject specification
- Not adjusting role if first attempt doesn't work

---

### 4.2 Learning Support Roles

**Definition:** Roles focused on how to learn rather than just content expertise.

**When to Use:**
- When struggling with study skills
- For organization and planning
- When you need encouragement
- To develop learning strategies

**Examples:**
```
"Act as a study skills coach"
"You are an encouraging learning mentor"
"Pretend you're a time management advisor for students"
"Take the role of a supportive tutor who helps students build confidence"
```

**Common Student Mistakes:**
- Not specifying what kind of support they need
- Expecting content help from a coaching role
- Not mentioning specific learning challenges
- Forgetting to ask for practical strategies

---

### 4.3 Socratic Teacher Roles

**Definition:** Roles where AI guides learning through questions rather than answers.

**When to Use:**
- When you want to figure things out yourself
- To develop critical thinking
- For test preparation
- To avoid AI doing work for you

**Examples:**
```
"Act as a Socratic teacher who guides me with questions, not answers"
"You are a philosophy professor who teaches through dialogue"
"Pretend you're a tutor who helps students discover answers themselves"
"Take the role of a questioning mentor who never gives direct answers"
```

**Common Student Mistakes:**
- Getting frustrated when AI asks questions
- Not engaging thoughtfully with questions
- Using this when they actually need explanations first
- Not specifying what they already know

---

### 4.4 Writing Coach Roles

**Definition:** Roles focused specifically on writing improvement and feedback.

**When to Use:**
- For essay writing and revision
- When working on writing skills
- To get feedback on drafts
- For grammar and style help

**Examples:**
```
"Act as a high school English teacher reviewing essay drafts"
"You are a writing coach focused on thesis development"
"Pretend you're an editor helping improve essay structure"
"Take the role of a writing tutor specializing in persuasive arguments"
```

**Common Student Mistakes:**
- Asking AI to write for them instead of coach
- Not specifying what aspect of writing needs help
- Not providing their actual draft
- Expecting AI to just fix errors vs. teach improvement

---

### 4.5 Test Prep Tutor Roles

**Definition:** Roles specifically designed for assessment preparation and review.

**When to Use:**
- When studying for tests or quizzes
- For practice problem generation
- To review material systematically
- To identify knowledge gaps

**Examples:**
```
"Act as a test prep tutor for my biology midterm"
"You are a quiz maker who creates practice problems"
"Pretend you're a study guide creator"
"Take the role of a tutor who specializes in test-taking strategies"
```

**Common Student Mistakes:**
- Not specifying what test covers
- Forgetting to mention test format
- Not asking for strategic advice
- Using for memorization only vs. understanding

---

### 4.6 Peer Roles

**Definition:** Roles where AI acts as a knowledgeable classmate rather than authority figure.

**When to Use:**
- When formal teaching feels intimidating
- For collaborative study simulation
- To practice explaining concepts
- When you want casual tone

**Examples:**
```
"Act as a classmate who's really good at chemistry"
"You are a study partner helping me review"
"Pretend you're a fellow student explaining this concept"
"Take the role of a friend who excels at math"
```

**Common Student Mistakes:**
- Not recognizing peer role may be less accurate
- Using this for complex topics needing expert help
- Expecting too casual/informal responses
- Not setting academic boundaries

---

### 4.7 Specialized Roles

**Definition:** Unique or creative role assignments for specific needs or approaches.

**When to Use:**
- When standard roles don't fit
- For creative problem-solving
- To see different perspectives
- For engaging, memorable learning

**Examples:**
```
"Act as a detective helping me solve this word problem"
"You are a sports coach applying training principles to study habits"
"Pretend you're a game show host quizzing me on history"
"Take the role of a scientist peer-reviewing my lab report"
"Act as a debate coach preparing me for argument construction"
```

**Common Student Mistakes:**
- Getting too creative and confusing the AI
- Using novelty roles without clear purpose
- Not explaining how the role should help
- Forgetting to include standard role elements (level, expertise)

---

### 4.8 Multiple Role Combinations

**Definition:** Combining multiple roles to get multi-faceted support.

**When to Use:**
- For complex tasks needing different expertise
- When you need multiple perspectives
- For comprehensive feedback
- To separate different types of help

**Examples:**
```
"Act as both a history teacher (for content accuracy) and a writing coach (for essay structure)"

"First respond as a math tutor helping me solve this problem, then as a test prep coach suggesting similar practice problems"

"You are a science teacher who also coaches debate - help me create a scientifically accurate argument"
```

**Common Student Mistakes:**
- Combining too many roles and confusing purpose
- Not being clear which role does what
- Expecting AI to switch roles without being told
- Creating conflicting role expectations

---

## 5. Constraint-Based Prompting

### 5.1 Academic Integrity Constraints

**Definition:** Boundaries that ensure AI helps with learning rather than doing work for the student.

**When to Use:**
- Always, to maintain ethical AI use
- For homework assignments
- When developing skills
- To align with school policies

**Examples:**
```
"Don't give me the answer - help me figure it out"
"Explain the concept but don't solve the problem for me"
"Guide my thinking with questions, don't do my work"
"Help me understand, don't write my essay"
"Show me how to approach this, don't complete it"
```

**Key Variations:**
- "Don't write my thesis - help me develop one"
- "Don't solve the equation - walk me through the steps"
- "Don't summarize the book - help me analyze specific passages"
- "Don't give me answers for my worksheet - explain the concepts"

**Common Student Mistakes:**
- Not including these constraints when they should
- Being unclear about what help is vs. isn't okay
- Accepting direct answers when they should be learning
- Not following their school's AI use policies

---

### 5.2 Scope Constraints

**Definition:** Boundaries that limit content to specific topics, chapters, or areas.

**When to Use:**
- When assignment has specific scope
- To avoid overwhelming detail
- When focusing on particular subtopic
- To match course coverage

**Examples:**
```
"Only use information from chapters 5-7"
"Focus exclusively on the economic causes, not social or political"
"Stay within 8th grade curriculum - don't introduce advanced concepts"
"Limit explanation to Newton's first and second laws only"
"Only discuss the European theater, not Pacific"
```

**Common Student Mistakes:**
- Not specifying exact scope of assignment
- Forgetting chapter or unit boundaries
- Not mentioning what topics to avoid
- Setting scope too narrow and missing important connections

---

### 5.3 Format Constraints

**Definition:** Requirements for how responses should be structured or presented.

**When to Use:**
- When format matters for assignment
- To get digestible information
- For specific study needs
- To match output to purpose

**Examples:**
```
"Respond in exactly 3 bullet points"
"Keep your explanation under 100 words"
"Use only complete paragraphs, no bullet points"
"Format as a numbered step-by-step list"
"Present information in a table with columns for [specific categories]"
"Write in the form of questions and answers"
```

**Common Student Mistakes:**
- Not specifying format when it matters
- Being too rigid about format when flexibility helps
- Forgetting format requirements from teacher
- Not matching format to purpose

---

### 5.4 Depth/Complexity Constraints

**Definition:** Specifications about how detailed or simple responses should be.

**When to Use:**
- To match current understanding level
- When time is limited
- To prevent overwhelming detail
- To challenge deeper thinking

**Examples for Limiting Depth:**
```
"Keep this at a basic level - I'm just learning"
"Don't go into advanced details - just main concepts"
"Explain simply without technical jargon"
"Give me the overview first, not exhaustive details"
```

**Examples for Increasing Depth:**
```
"Don't oversimplify - I need the full complexity"
"Go deeper into the mechanism, not just what happens"
"Include the advanced concepts - I can handle it"
"Explain the nuances, not just basic facts"
```

**Common Student Mistakes:**
- Not indicating appropriate complexity level
- Asking for simple when they need detailed
- Requesting advanced when they need foundations
- Not adjusting depth based on AI response

---

### 5.5 Language/Vocabulary Constraints

**Definition:** Requirements about word choice, terminology, and language complexity.

**When to Use:**
- To ensure understanding
- When vocabulary level matters
- For accessibility
- To match assignment requirements

**Examples:**
```
"Use 9th grade vocabulary level"
"Define any technical terms you use"
"Don't use jargon - explain in everyday language"
"Keep language formal and academic"
"Use conversational tone, not textbook language"
```

**Common Student Mistakes:**
- Not specifying appropriate vocabulary level
- Accepting unfamiliar terms without asking for definitions
- Not adjusting when language is too complex or too simple
- Forgetting teacher's language expectations

---

### 5.6 Time-Based Constraints

**Definition:** Limitations related to length, duration, or time investment for responses.

**When to Use:**
- When time is limited
- To get focused information
- For quick review
- To prevent excessive detail

**Examples:**
```
"I only have 20 minutes - give me the essentials"
"Keep this brief - 2-3 sentences maximum"
"Give me a 5-minute explanation"
"Create a study guide I can review in 30 minutes"
"Limit to 3 main points I can memorize quickly"
```

**Common Student Mistakes:**
- Not mentioning time limitations
- Requesting too much for available time
- Not prioritizing most important information
- Forgetting to ask for quick review vs. deep learning

---

### 5.7 Source/Resource Constraints

**Definition:** Requirements about what resources can or cannot be referenced.

**When to Use:**
- When assignment specifies sources
- For research papers
- To match course materials
- To ensure appropriate references

**Examples:**
```
"Only reference information from our textbook"
"Use peer-reviewed scientific sources only"
"Don't cite Wikipedia or general websites"
"Base explanation on primary sources, not secondary"
"Only use resources available through school library"
```

**Common Student Mistakes:**
- Not mentioning source restrictions
- Accepting citations they can't verify
- Forgetting to specify type of sources needed
- Not knowing which sources are acceptable

---

### 5.8 Perspective Constraints

**Definition:** Limitations on viewpoint, bias, or approach to content.

**When to Use:**
- For balanced analysis
- When considering multiple perspectives
- To avoid bias in learning
- For critical thinking development

**Examples:**
```
"Present both sides of this issue objectively"
"Don't show bias toward either political perspective"
"Focus on scientific consensus, not fringe theories"
"Include multiple cultural perspectives, not just Western"
"Acknowledge limitations of this approach"
```

**Common Student Mistakes:**
- Not requesting balanced perspectives
- Accepting single viewpoint as complete truth
- Not questioning bias in responses
- Forgetting to consider multiple angles

---

### 5.9 Output Quantity Constraints

**Definition:** Specific limits on amount of content generated.

**When to Use:**
- To prevent overwhelming information
- When assignment has limits
- To focus AI output
- To make information manageable

**Examples:**
```
"Give exactly 5 examples"
"Create 3 practice problems, no more"
"List the top 4 causes"
"Provide 2-3 supporting details for each point"
"Generate 10 flashcard questions"
```

**Common Student Mistakes:**
- Not specifying quantity when it matters
- Accepting too much or too little output
- Not aligning quantity with assignment requirements
- Forgetting about practical limits

---

## 6. Multi-Step Reasoning Prompts

### 6.1 Sequential Step Prompts

**Definition:** Breaking down complex tasks into ordered steps that must be completed in sequence.

**When to Use:**
- For problems with clear step-by-step procedures
- When learning a process
- For complex calculations
- When order matters crucially

**Example:**
```
Help me solve this chemistry stoichiometry problem step-by-step:

"How many grams of water form when 2.5 moles of hydrogen react completely with oxygen?"

Please work through this in order:
Step 1: Write the balanced chemical equation
Step 2: Identify what we know and what we're looking for
Step 3: Set up the mole ratio
Step 4: Calculate moles of water produced
Step 5: Convert moles to grams
Step 6: Check if the answer makes sense

Walk me through each step with explanations.
```

**Common Student Mistakes:**
- Skipping steps or combining them
- Not making steps clear and distinct
- Not indicating which step confuses them
- Trying to parallel process sequential tasks
- Not including verification steps

---

### 6.2 Parallel Processing Prompts

**Definition:** Breaking tasks into parts that can be worked on simultaneously or in any order.

**When to Use:**
- When components are independent
- For brainstorming multiple aspects
- When order doesn't matter
- For comprehensive coverage

**Example:**
```
I need to prepare for my history essay on the Industrial Revolution. Help me work on these aspects simultaneously:

Aspect A: Identify 3 major economic changes
Aspect B: Identify 3 major social changes
Aspect C: Identify 3 environmental impacts

For each aspect, provide:
- Brief description of each change
- One specific historical example
- Connection to modern day

I'll work on all three aspects at once to build my understanding.
```

**Common Student Mistakes:**
- Using parallel structure for sequential tasks
- Not making components truly independent
- Forgetting to synthesize components later
- Not clarifying all parts need completion

---

### 6.3 Conditional Step Prompts

**Definition:** Steps that vary based on outcomes of previous steps, with "if-then" logic.

**When to Use:**
- When approach depends on interim results
- For troubleshooting and problem-solving
- When learning decision-making
- For adaptive procedures

**Example:**
```
Help me solve this algebra problem with conditional steps:

"Solve for x: ax + b = c"

Step 1: Check what type of equation this is
Step 2: IF there's a coefficient (a), then divide it out
       IF there's no coefficient, move to next step
Step 3: IF there's a constant term (b), then subtract it
       IF no constant, you're done
Step 4: Check your answer by substituting back

Guide me through this logic with an actual problem.
```

**Common Student Mistakes:**
- Not making conditions clear
- Forgetting to specify what triggers each path
- Not covering all possible conditions
- Making logic too complex to follow

---

### 6.4 Iterative Prompts

**Definition:** Prompts that repeat similar steps with refinement or different inputs.

**When to Use:**
- For practice and mastery
- When refining work
- For progressive difficulty
- To develop consistency

**Example:**
```
Help me practice solving quadratic equations iteratively:

Round 1: Give me a simple quadratic (like x² + 5x + 6 = 0)
Let me try solving it
Check my work and give feedback

Round 2: Based on my performance, give me a similar problem
Let me solve it applying what I learned
Check and provide more specific feedback

Round 3: Increase difficulty slightly
Continue until I can solve 3 in a row correctly

Track my progress and adjust difficulty accordingly.
```

**Common Student Mistakes:**
- Not planning number of iterations
- Not building on previous rounds
- Skipping the refinement aspect
- Not having clear completion criteria

---

### 6.5 Hierarchical Step Prompts

**Definition:** Organizing steps in levels, with main steps containing substeps.

**When to Use:**
- For complex multi-level tasks
- When organization matters
- For big projects with parts
- To show relationships between steps

**Example:**
```
Help me write my research paper using hierarchical steps:

Phase 1: Research
  1.1: Identify 3 main questions to answer
  1.2: Find 5 credible sources
  1.3: Take organized notes
  1.4: Identify key quotes and data

Phase 2: Planning
  2.1: Create thesis statement
  2.2: Outline main arguments
  2.3: Match evidence to arguments
  2.4: Plan counterargument section

Phase 3: Drafting
  3.1: Write introduction
  3.2: Write body paragraphs
  3.3: Write conclusion
  3.4: Add citations

Guide me through each phase and substep.
```

**Common Student Mistakes:**
- Making hierarchy too shallow or too deep
- Not showing relationships between levels
- Mixing hierarchical levels
- Not completing one phase before moving to next

---

### 6.6 Diagnostic/Assessment Prompts

**Definition:** Steps that identify gaps, test understanding, then provide targeted help.

**When to Use:**
- Before studying for tests
- To identify what you don't know
- For personalized learning
- To use study time efficiently

**Example:**
```
Help me diagnose my understanding of cellular respiration:

Step 1: Quick Assessment
Ask me 5 questions covering main concepts
Range from basic to more complex

Step 2: Analysis
Based on my answers, identify:
- What I understand well
- What I partially understand
- What I'm missing completely

Step 3: Targeted Explanation
Focus detailed explanation on my weak areas
Skip or review only what I already know

Step 4: Verification
Give me practice problems specifically on weak areas
Confirm understanding improved
```

**Common Student Mistakes:**
- Not being honest in assessment phase
- Skipping diagnostic and jumping to study
- Not focusing on identified gaps
- Rushing through verification

---

### 6.7 Building/Construction Prompts

**Definition:** Steps that progressively build toward a final product or complete understanding.

**When to Use:**
- When creating something complex
- To build understanding layer by layer
- For projects and papers
- When foundations are crucial

**Example:**
```
Help me build my understanding of the scientific method from ground up:

Foundation: Start with the basic concept and purpose
Layer 1: Add the main steps of the method
Layer 2: Explain what happens in each step and why
Layer 3: Show how steps connect and flow
Layer 4: Apply to an actual experiment example
Layer 5: Practice identifying steps in real scenarios

Build each layer on the previous one, checking understanding before adding next layer.
```

**Common Student Mistakes:**
- Trying to build without foundation
- Skipping layers
- Not checking stability before adding more
- Building too slowly and losing momentum

---

### 6.8 Comparison/Analysis Prompts

**Definition:** Multi-step approaches to systematically compare and contrast concepts.

**When to Use:**
- For compare/contrast essays
- When learning similar concepts
- To understand differences
- For analytical thinking

**Example:**
```
Help me compare photosynthesis and cellular respiration systematically:

Step 1: List basic purpose of each process
Step 2: Compare inputs required for each
Step 3: Compare outputs produced by each
Step 4: Compare where each occurs in cells
Step 5: Compare energy flow direction
Step 6: Analyze how they're related/opposite
Step 7: Synthesize into overall comparison

Walk through each step with clear contrasts.
```

**Common Student Mistakes:**
- Not comparing same aspects for each
- Describing one then other without connecting
- Not having clear comparison criteria
- Missing synthesis at the end

---

## 7. Creative vs Analytical Prompts

### 7.1 Creative Prompts

**Definition:** Prompts that encourage imaginative thinking, generation of new ideas, and original solutions.

**When to Use:**
- For brainstorming and ideation
- When multiple solutions exist
- For creative writing or projects
- To think outside conventional approaches
- When innovation is valued

**Characteristics of Creative Prompts:**
- Open-ended questions
- Multiple possible answers
- Emphasis on novelty and originality
- "What if" scenarios
- Divergent thinking
- Generation over evaluation

**Examples:**

**Creative Writing:**
```
Help me brainstorm unique ways to open my short story about a teenager who discovers they can time travel. Don't give me clichés - suggest 5 creative, unexpected opening scenes that would immediately hook readers. Consider different tones: mysterious, humorous, dramatic, eerie.
```

**Problem Solving:**
```
Act as a creative thinking coach. I need to design a fundraiser for my club. Instead of typical bake sales or car washes, help me generate 10 innovative fundraising ideas that would appeal to high school students and could realistically raise $1000. Think outside the box!
```

**Academic Creative:**
```
I'm writing an essay about the water cycle, but my teacher wants creative approaches. Help me think of 5 unusual analogies or perspectives for explaining the water cycle - like viewing it from a water molecule's perspective, or comparing it to other cycles in nature. Make them memorable and educational.
```

**Art/Design:**
```
Help me brainstorm creative ways to represent the concept of "identity" in a visual art project. Generate 8-10 abstract and concrete ideas using different mediums (painting, sculpture, photography, mixed media). Think symbolically and metaphorically.
```

**Common Student Mistakes:**
- Settling for first idea without exploration
- Being too conventional or safe
- Not providing enough context for relevant creativity
- Asking for quantity without quality criteria
- Not specifying constraints that would focus creativity
- Accepting generic "creative" suggestions

**Better Creative Prompt Structure:**
```
Act as [creative role - designer, writer, innovator].

My creative challenge: [specific goal]

Parameters:
- Must fit within: [realistic constraints]
- Target audience: [who it's for]
- Tone/style: [desired feel]
- Available resources: [what you have to work with]

Generate [number] creative options that:
✓ Are original and unexpected
✓ Are feasible given my constraints
✓ Would be memorable/impactful
✓ Fit my specific needs

For each idea, briefly explain why it could work well.
```

---

### 7.2 Analytical Prompts

**Definition:** Prompts that require systematic examination, logical reasoning, and evidence-based conclusions.

**When to Use:**
- For critical thinking tasks
- When examining arguments or evidence
- For scientific or mathematical problems
- When objective evaluation is needed
- For breaking down complex ideas

**Characteristics of Analytical Prompts:**
- Focused questions with specific answers
- Emphasis on logic and evidence
- Breaking down into components
- Evaluation and judgment
- Convergent thinking
- Analysis over generation

**Examples:**

**Literary Analysis:**
```
Act as a literature teacher. Help me analyze the symbolism of the green light in "The Great Gatsby."

Analyze:
1. What does the green light literally represent in the story?
2. What deeper meanings/themes does it symbolize?
3. What specific textual evidence supports each interpretation?
4. How does this symbol connect to Gatsby's character development?
5. How does Fitzgerald use this symbol differently in beginning vs. end?

Provide evidence-based analysis, not opinions.
```

**Scientific Analysis:**
```
Help me analyze the results of our plant growth experiment:

Data:
- Control group (regular water): avg 12cm growth
- Group A (sugar water): avg 8cm growth
- Group B (salt water): avg 3cm growth
- Group C (vinegar): avg 5cm growth

Analyze:
1. What patterns do you see in the data?
2. What might explain these results scientifically?
3. Do results support or refute the hypothesis that additives increase growth?
4. What are alternative explanations?
5. What are limitations of this analysis?
```

**Historical Analysis:**
```
Act as a history professor. Help me analyze the causes of World War I using this framework:

For each potential cause (nationalism, imperialism, alliance system, assassination):
1. Analyze: How did this factor create tension?
2. Evidence: What specific historical examples demonstrate this?
3. Evaluate: How significant was this cause compared to others?
4. Connect: How did this cause interact with other factors?

Provide analytical thinking, not just descriptions.
```

**Argument Analysis:**
```
Help me analyze this argument about school uniforms:

Argument: "Schools should require uniforms because they reduce bullying and improve focus."

Analyze:
1. What is the main claim?
2. What assumptions underlie this argument?
3. What evidence would be needed to support this claim?
4. What counterarguments exist?
5. What are the logical strengths and weaknesses?
6. Is this argument valid/sound? Why or why not?
```

**Common Student Mistakes:**
- Being too subjective or opinion-based
- Not requiring evidence or reasoning
- Accepting surface-level analysis
- Not breaking down into components
- Forgetting to evaluate and judge
- Not asking for specific analytical framework

**Better Analytical Prompt Structure:**
```
Act as [analytical role - critic, scientist, philosopher].

My analytical task: [what needs analysis]

Analyze systematically:
1. [Component 1]: What is it? How does it work?
2. [Component 2]: What evidence exists?
3. [Relationships]: How do parts connect?
4. [Evaluation]: What's the significance/quality?
5. [Conclusion]: What can we conclude based on evidence?

Use [specific framework/criteria] for analysis.
Provide evidence and reasoning for each point.
Identify assumptions and limitations.
```

---

### 7.3 Hybrid Creative-Analytical Prompts

**Definition:** Prompts that combine creative thinking with analytical rigor, requiring both imagination and critical evaluation.

**When to Use:**
- For complex projects requiring both skills
- When innovation needs feasibility analysis
- For research with creative application
- In real-world problem-solving

**Examples:**

**Science Project:**
```
Help me design an innovative science fair project about renewable energy:

Creative Phase:
- Generate 5 original experiment ideas (not common projects)
- Think of creative ways to demonstrate concepts
- Consider unusual angles or applications

Analytical Phase:
- Evaluate feasibility of each idea
- Analyze what resources/time each requires
- Assess scientific validity and learning value
- Compare which would best demonstrate principles

Then recommend top 2 options with rationale for each.
```

**Essay Development:**
```
I need both creative and analytical help for my essay on climate change:

Creative Component:
- Suggest 3 unique angles or perspectives (not the obvious ones)
- Think of compelling ways to open the essay
- Generate creative analogies for complex concepts

Analytical Component:
- Evaluate which angle has strongest evidence available
- Analyze potential counterarguments to each approach
- Assess which would be most persuasive to audience
- Determine logical structure for chosen angle
```

**Problem Solving:**
```
Our school wants to reduce plastic waste in the cafeteria:

Creative Brainstorming:
- Generate 10 innovative solutions (beyond obvious recycling)
- Think of ways to make change appealing to students
- Consider unique incentive systems

Critical Analysis:
- Evaluate cost-effectiveness of each solution
- Analyze potential barriers to implementation
- Assess realistic impact of each option
- Recommend top 3 with evidence-based reasoning
```

**Common Student Mistakes:**
- Doing only creative or only analytical part
- Not integrating both modes of thinking
- Applying analysis too early (killing creativity)
- Not applying enough analysis (impractical ideas)
- Not showing how creative and analytical connect

---

### 7.4 Divergent vs Convergent Thinking Prompts

**Divergent (Creative):**
```
"Generate as many different solutions as possible"
"Think of multiple perspectives on this issue"
"Brainstorm various interpretations"
"What are all the possible approaches?"
```

**Convergent (Analytical):**
```
"Which solution is most effective based on evidence?"
"Narrow down to the best interpretation"
"Evaluate and select the optimal approach"
"What is THE answer given this data?"
```

**Combined:**
```
"First, generate 10 possible solutions (divergent), then analyze each using specific criteria and select the best 2 (convergent)"
```

---

## 8. Combined Techniques

### 8.1 Role + Context + Multi-Step

**When to Use:** For comprehensive help on complex, sequential tasks

**Example:**
```
Act as a biology tutor for 10th graders.

Context: I'm studying for a test on cellular respiration tomorrow. I understand glycolysis but get confused about the Krebs cycle and electron transport chain. I learn best with visual descriptions and analogies.

Multi-step approach:
Step 1: First, give me a simple overview of all three stages
Step 2: Then, explain the Krebs cycle using an analogy
Step 3: Next, explain electron transport chain in visual terms
Step 4: Finally, show me how all three stages connect and build on each other

Don't just list facts - help me understand the flow and purpose.
```

---

### 8.2 Few-Shot + Constraints + Role

**When to Use:** When you need specific format with boundaries

**Example:**
```
Act as a Spanish teacher checking homework.

Check my translations using this exact format:

Example 1:
Spanish: "El perro es grande"
Student translation: "The dog is big"
Feedback: ✓ Correct! Perfect translation.

Example 2:
Spanish: "La casa es roja"
Student translation: "The house is red"
Feedback: ✓ Correct! Well done.

Example 3:
Spanish: "El gato come pescado"
Student translation: "The cat drink fish"
Feedback: ✗ Error - "come" means "eats" not "drinks", and pescado is "fish" (correct) but you need "eats fish" not "drink fish"

Important constraints:
- Check my translation, don't give me the answer first
- Point out errors but let me correct them
- Focus on grammar and vocabulary accuracy

Now check my work:
Spanish: "Los estudiantes leen libros"
Student translation: "The students reads books"
```

---

### 8.3 Socratic + Multi-Step + Context

**When to Use:** When you want to discover understanding through guided steps

**Example:**
```
Act as a Socratic tutor helping me understand photosynthesis.

Context: I'm a 7th grader. I know plants use sunlight and make oxygen, but I don't understand HOW or WHY the sun matters.

Guide me through discovery in steps:

Step 1: Ask me questions about what I think energy is and where it comes from
Step 2: Based on my answers, ask questions connecting energy to plants
Step 3: Guide me to discover what the sunlight actually DOES
Step 4: Help me figure out why plants need water and CO2 specifically
Step 5: Let me synthesize the full process myself

Don't explain directly - only through questions. If I'm completely stuck, give a tiny hint and ask another question.
```

---

### 8.4 Chain-of-Thought + Few-Shot + Constraints

**When to Use:** For complex problem-solving with specific format and full reasoning

**Example:**
```
Help me solve word problems showing complete reasoning:

Example format:
Problem: "A train travels 120 miles in 2 hours. How fast is it going?"

Reasoning:
1. IDENTIFY: What do I know? Distance = 120 miles, Time = 2 hours
2. IDENTIFY: What am I finding? Speed (rate)
3. RECALL: Formula - Speed = Distance ÷ Time
4. SUBSTITUTE: Speed = 120 ÷ 2
5. CALCULATE: Speed = 60
6. CHECK: Does this make sense? 60 mph is reasonable for a train ✓
Answer: 60 miles per hour

Constraints:
- Show all reasoning steps like the example
- Don't skip the "does this make sense" check
- Explain WHY you chose each formula or approach
- Help me develop this process, don't just give answers

Now apply this process to my problem:
"Sarah saves $15 per week. She wants to buy a bike that costs $195. How many weeks until she can buy it?"
```

---

### 8.5 Tree of Thoughts + Role + Constraints

**When to Use:** For exploring multiple solution paths with expert guidance

**Example:**
```
Act as a writing coach helping me choose an essay approach.

Essay topic: "Is social media harmful or beneficial for teenagers?"

Explore different argument structures:

Path A: Focus on mental health impacts
- What would this argument emphasize?
- What evidence would I need?
- Strengths of this approach?
- Weaknesses or gaps?

Path B: Focus on social connection vs isolation
- What would this argument emphasize?
- What evidence would I need?
- Strengths of this approach?
- Weaknesses or gaps?

Path C: Focus on information access and misinformation
- What would this argument emphasize?
- What evidence would I need?
- Strengths of this approach?
- Weaknesses or gaps?

Constraint: Don't write the essay for me - help me evaluate which path would make the strongest argument for a 10th grade persuasive essay.

Then recommend which path or combination would work best and why.
```

---

### 8.6 All Core Components Combined

**The Ultimate Comprehensive Prompt Structure:**

```
[ROLE] Act as [specific role with expertise and approach]

[BACKGROUND CONTEXT]
- Grade/level
- What I know already
- What I don't understand
- How I learn best

[TASK CONTEXT]
- Specific assignment details
- Requirements and constraints
- Due date/timeline
- What part I need help with

[TECHNIQUE SELECTION]
Choose based on task:
- Multi-step if sequential
- Few-shot if format-specific
- Chain-of-thought if reasoning important
- Socratic if I should discover it myself

[CONSTRAINTS]
Academic integrity: [what not to do]
Scope: [what to include/exclude]
Format: [how to present]
Depth: [appropriate complexity]
Time: [any time limitations]

[SPECIFIC REQUEST]
Exactly what I need help with

[FORMAT PREFERENCE]
How I want the response structured
```

**Complete Example:**
```
Act as a chemistry tutor who uses analogies and visual descriptions.

Background Context:
- I'm an 11th grader in AP Chemistry
- I understand basic atomic structure and electron shells
- I'm confused about molecular orbital theory and hybridization
- I learn best when I can visualize concepts

Task Context:
- Studying for a unit test on chemical bonding
- Test covers Lewis structures, VSEPR, and molecular orbitals
- Test is in 2 days
- I'm specifically stuck on sp, sp2, sp3 hybridization

Multi-step approach:
Step 1: First, explain the concept of hybridization using a simple analogy
Step 2: Show how to determine hybridization for a molecule
Step 3: Walk through examples with sp, sp2, and sp3
Step 4: Give me practice identifying hybridization

Constraints:
- Don't give me answers to identify - ask me questions to guide my thinking
- Use analogies that relate to everyday objects I'd know
- Keep at AP Chem level - I can handle technical terms if explained
- Focus only on hybrid orbitals, not molecular orbital theory yet
- I have about 45 minutes to work on this topic right now

Format:
Break explanations into short paragraphs with analogies
Use "Think of it like..." for conceptual explanations
Include 3-4 practice problems at the end for me to try
```

---

## Assessment Guidelines

### Evaluating Student Prompt Quality

**Beginner Level (Grade: Basic)**
- Includes role and basic context
- States the task clearly
- Uses simple, direct language
- May lack constraints or format specification

**Intermediate Level (Grade: Proficient)**
- Includes role, context, task, and format (R.C.T.F.)
- Adds relevant constraints
- Uses one advanced technique appropriately
- Shows understanding of when different prompts work better

**Advanced Level (Grade: Exemplary)**
- Masterfully combines multiple techniques
- Perfectly calibrated context and constraints
- Creative and effective role assignment
- Demonstrates meta-awareness of prompting strategies
- Iterates and improves prompts based on results

### Common Assessment Errors

**What NOT to Penalize:**
- Verbose prompts (if all information is relevant)
- Multiple attempts/iterations (this shows learning)
- Different approaches than taught (if effective)
- Creative role or technique combinations

**What TO Penalize:**
- Prompts asking AI to do student's work
- Missing critical context
- Vague or unclear requests
- No evidence of learning from prompt results
- Ignoring academic integrity constraints

---

## Meta-Prompting Guide

### Teaching Students to Create Their Own Prompt Systems

**Meta-Prompt Template:**
```
Help me design a reusable prompt template for [specific type of task].

The template should:
- Be fillable for different [topics/problems]
- Include role, context, task, and format
- Have appropriate constraints built in
- Work for [grade level]
- Help with [specific learning goal] not just getting answers

Show me:
1. The template with [blanks] to fill in
2. An example of it filled in for [specific example]
3. Guidance on how to customize it for different situations
```

---

## Conclusion

This comprehensive guide covers all major prompt engineering techniques appropriate for middle and high school student assessment. Each technique can be adapted for different grade levels, subjects, and learning goals.

**Key Principles Across All Techniques:**

1. **Clarity over brevity** - Detailed prompts get better results
2. **Context is crucial** - AI needs to know your situation
3. **Iteration is normal** - Prompts rarely perfect on first try
4. **Ethics matter** - Use AI to learn, not to cheat
5. **Combinations are powerful** - Real tasks need multiple techniques
6. **Practice builds skill** - Prompting improves with experience

**For Educators:**
Use this guide to:
- Design comprehensive assessments
- Create rubrics for prompt evaluation
- Develop progressive skill-building curricula
- Identify student understanding levels
- Generate teaching examples

**For Students:**
Use this guide to:
- Understand what makes prompts effective
- Choose appropriate techniques for tasks
- Improve your AI interaction skills
- Develop meta-cognitive awareness
- Become an expert prompt engineer

---

**Document Version:** 1.0
**Last Updated:** October 2025
**Aligned With:** Google Gemini 2.5, Current Prompt Engineering Best Practices
**Target Audience:** Grades 7-12 Students and Educators
