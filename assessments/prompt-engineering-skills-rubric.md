# Master Prompt Engineering Skills Rubric

## Overview

This rubric evaluates student mastery of prompt engineering skills across all techniques taught in the AI Academy curriculum. Use this tool to assess overall progress, identify growth areas, and celebrate achievements.

**Purpose:** Comprehensive evaluation of prompt engineering competencies
**Audience:** Educators, students, parents
**Use:** Formative and summative assessment throughout the curriculum

---

## Assessment Framework

### Performance Levels

| Level | Description | Indicator |
|-------|-------------|-----------|
| **4 - Advanced** | Exceptional mastery; creates sophisticated prompts independently | Exceeds expectations; teaches others |
| **3 - Proficient** | Strong understanding; applies techniques effectively | Meets expectations; works independently |
| **2 - Developing** | Growing skills; needs occasional guidance | Approaching expectations; improving steadily |
| **1 - Beginning** | Early understanding; needs structured support | Building foundations; requires assistance |

---

## Skill Areas & Criteria

### 1. Role-Based Prompting

**What We're Evaluating:** Ability to assign effective roles to AI to get expert-level assistance

#### Performance Indicators

**Level 4 - Advanced**
- Creates nuanced, multi-layered roles tailored to specific needs
- Combines multiple expert perspectives in a single prompt
- Explains why specific roles produce better results
- Adapts roles based on subject complexity and learning goals

**Example:**
```
"Act as both a chemistry teacher and a science writer. Explain chemical
bonding using analogies that connect to everyday life. Approach this as
if you're helping a 10th grader who learns best through stories and
visual comparisons."
```

**Level 3 - Proficient**
- Consistently assigns appropriate roles for different subjects
- Includes specific role characteristics (teaching style, expertise level)
- Adjusts roles when initial responses don't meet needs
- Uses roles across multiple subjects effectively

**Example:**
```
"Act as a patient algebra teacher who uses step-by-step explanations.
Help me understand how to solve quadratic equations."
```

**Level 2 - Developing**
- Uses basic roles with prompting or templates
- Understands concept but needs examples to guide role selection
- Sometimes forgets to include role in prompts
- Roles may be generic rather than tailored

**Example:**
```
"You are a teacher. Explain photosynthesis to me."
```

**Level 1 - Beginning**
- Rarely includes roles in prompts
- Unclear on how roles improve responses
- Needs significant guidance to identify appropriate roles
- May skip this step entirely

**Example:**
```
"What is photosynthesis?"
```

**Success Indicators:**
- [ ] Assigns roles in 80%+ of prompts
- [ ] Roles match subject and learning need
- [ ] Can explain role selection reasoning
- [ ] Helps peers choose effective roles

---

### 2. Context Engineering

**What We're Evaluating:** Providing relevant background information that helps AI understand the learning situation

#### Performance Indicators

**Level 4 - Advanced**
- Provides comprehensive, relevant context without overloading
- Anticipates what information AI needs before being asked
- Includes learning preferences, prior knowledge, and specific gaps
- Balances detail with clarity—context is focused and purposeful

**Example:**
```
"I'm in 11th grade AP Biology, currently studying cellular respiration.
I understand glycolysis well, but I'm confused about the electron
transport chain, specifically how ATP is produced. I'm a visual learner
and prefer diagrams or analogies over pure text descriptions. I have a
test Friday covering the entire respiration process."
```

**Level 3 - Proficient**
- Regularly includes grade level and subject
- Mentions current understanding level
- States specific area of confusion or need
- Context is clear and relevant

**Example:**
```
"I'm a 9th grader learning about World War II in history class. I
understand the basic timeline but don't get why the US entered the war.
Can you explain the reasons?"
```

**Level 2 - Developing**
- Includes some context but may miss key details
- Context may be too vague or too detailed
- Inconsistently provides learning level or specific needs
- Can add context when reminded

**Example:**
```
"I'm learning about WWII. Why did the US join?"
```

**Level 1 - Beginning**
- Provides minimal or no context
- Doesn't understand what information is helpful
- Asks questions without setting up the learning situation
- Needs structured prompts to include context

**Example:**
```
"Explain WWII."
```

**Success Indicators:**
- [ ] Includes context in 75%+ of prompts
- [ ] Context helps AI personalize response
- [ ] Identifies and shares specific learning gaps
- [ ] Adjusts context detail based on complexity

---

### 3. Multi-Step Prompting

**What We're Evaluating:** Breaking complex problems into manageable sequential steps

#### Performance Indicators

**Level 4 - Advanced**
- Independently breaks down complex challenges into logical sequences
- Creates multi-step strategies for different types of problems
- Builds on previous steps effectively—each prompt references prior responses
- Recognizes when multi-step approach is needed vs. single prompt

**Example:**
```
Step 1: "List the main themes in The Great Gatsby and briefly define each."
Step 2: "Now, for the theme of 'The American Dream,' find 3 specific
quotes from the text that illustrate it."
Step 3: "Explain how these quotes work together to show Fitzgerald's
critique of the American Dream."
```

**Level 3 - Proficient**
- Breaks problems into 2-3 clear steps
- Each step has a defined purpose
- Follows logical sequence most of the time
- Uses multi-step approach when prompted or for familiar problems

**Example:**
```
Step 1: "What are the steps to solve a quadratic equation by factoring?"
Step 2: "Now walk me through solving x² + 5x + 6 = 0 using those steps."
```

**Level 2 - Developing**
- Can create steps with guidance or templates
- Steps may not always build logically on each other
- Sometimes tries to solve everything in one prompt
- Learning to recognize when multi-step is beneficial

**Example:**
```
"First explain photosynthesis. Then tell me about cellular respiration."
(Steps exist but don't build on each other)
```

**Level 1 - Beginning**
- Doesn't break down complex problems
- Attempts to solve everything at once
- Unclear on concept of sequential prompting
- Needs direct instruction for each step

**Example:**
```
"Tell me everything about the Civil War."
```

**Success Indicators:**
- [ ] Recognizes complex problems requiring multiple steps
- [ ] Creates logical sequences independently
- [ ] Each step builds on previous responses
- [ ] Knows when single vs. multi-step is appropriate

---

### 4. Few-Shot Prompting

**What We're Evaluating:** Using examples to guide AI toward desired response style or format

#### Performance Indicators

**Level 4 - Advanced**
- Creates effective examples that clearly demonstrate desired output
- Uses 2-3 examples showing patterns AI should follow
- Examples are diverse enough to cover variations
- Explains how examples improve AI responses

**Example:**
```
"I need help creating thesis statements. Here are examples of strong
thesis statements I like:

Example 1: 'While social media connects people globally, its impact on
mental health, particularly among teenagers, reveals the need for better
digital literacy education.'

Example 2: 'Shakespeare's use of supernatural elements in Macbeth serves
not merely as plot devices but as manifestations of the characters'
internal moral conflicts.'

Now help me write a thesis statement about climate change with similar
depth and structure."
```

**Level 3 - Proficient**
- Provides 1-2 relevant examples to guide AI
- Examples match the task reasonably well
- Uses examples when response quality matters
- Can identify good examples from their own work or class materials

**Example:**
```
"I need to summarize articles for history class. Here's an example of
how I should do it: [example summary]. Now help me summarize this new
article in the same style."
```

**Level 2 - Developing**
- Understands concept of using examples
- Examples may be too vague or not quite match the task
- Needs help selecting or creating good examples
- Uses examples inconsistently

**Example:**
```
"Here's a good sentence: [example]. Help me write more like this."
(Single example without clear pattern)
```

**Level 1 - Beginning**
- Rarely or never uses examples
- Doesn't see how examples improve results
- Unclear on what makes a good example
- Needs direct instruction to include examples

**Example:**
```
"Write a good thesis statement about climate change."
(No examples provided)
```

**Success Indicators:**
- [ ] Uses examples when precision matters
- [ ] Examples clearly show desired format or style
- [ ] Provides 2-3 examples to establish patterns
- [ ] Selects relevant examples independently

---

### 5. Negative Prompting & Constraints

**What We're Evaluating:** Telling AI what NOT to do to ensure learning-focused responses

#### Performance Indicators

**Level 4 - Advanced**
- Strategically uses constraints to guide learning process
- Combines positive instructions with appropriate limitations
- Understands when constraints prevent shortcuts vs. enable learning
- Creates nuanced constraints that shape response without being restrictive

**Example:**
```
"Help me understand the steps to solve this calculus problem, but don't
give me the final answer. Show me the first step, wait for my attempt,
then guide me through step 2. Don't do any calculations for me—instead
ask questions that lead me to figure it out. Avoid using technical terms
without explaining them first."
```

**Level 3 - Proficient**
- Regularly includes "don't give me the answer" or similar constraints
- Uses constraints to maintain learning focus
- Constraints are clear and purposeful
- Balances what AI should and shouldn't do

**Example:**
```
"Explain the causes of the French Revolution without just giving me a
list. Help me understand the connections between causes, but don't write
my essay for me."
```

**Level 2 - Developing**
- Sometimes includes basic constraints
- May need reminding to add "don't solve it for me" type instructions
- Constraints may be too vague or too restrictive
- Learning when constraints are helpful

**Example:**
```
"Help me with this problem but don't do all the work."
```

**Level 1 - Beginning**
- Rarely uses constraints
- Often gets complete answers when seeking understanding
- Doesn't see value in limiting AI responses
- Needs guidance to include constraints

**Example:**
```
"Solve this problem for me."
```

**Success Indicators:**
- [ ] Includes constraints to prevent answer-giving
- [ ] Constraints support learning rather than just getting work done
- [ ] Balances guidance with independence
- [ ] Uses constraints to stay academically honest

---

### 6. Task Clarity & Specificity

**What We're Evaluating:** Stating clear, specific requests that produce useful responses

#### Performance Indicators

**Level 4 - Advanced**
- Tasks are precisely defined with measurable outcomes
- Includes success criteria within the prompt
- Specifies format, depth, and approach desired
- Anticipates ambiguity and clarifies preemptively

**Example:**
```
"Create a 3-column study guide for the water cycle: Column 1 should list
each stage (evaporation, condensation, precipitation, collection).
Column 2 should have a simple definition in 10 words or less. Column 3
should include a real-world example I'd observe in daily life. Use
language appropriate for a 7th grader."
```

**Level 3 - Proficient**
- Tasks are clear and specific
- Includes desired format or approach
- Requests are realistic and achievable
- Minimal follow-up needed to get useful response

**Example:**
```
"Explain the water cycle in 3-4 paragraphs. Include all the main stages
and how they connect. Use simple language I can understand."
```

**Level 2 - Developing**
- Tasks are somewhat clear but may lack specificity
- May need to rephrase or clarify after initial response
- Sometimes requests too much or too little
- Learning to be more precise

**Example:**
```
"Tell me about the water cycle and make it easy to understand."
```

**Level 1 - Beginning**
- Tasks are vague or unclear
- Often gets responses that don't meet needs
- Doesn't specify format or approach
- Needs help defining what they want

**Example:**
```
"What's the water cycle?"
```

**Success Indicators:**
- [ ] First response usually meets needs
- [ ] Includes format specifications when relevant
- [ ] Requests are appropriately scoped
- [ ] Minimal clarification needed

---

### 7. Response Evaluation & Iteration

**What We're Evaluating:** Assessing AI output quality and refining prompts to improve results

#### Performance Indicators

**Level 4 - Advanced**
- Critically evaluates responses against learning goals
- Identifies specific improvements needed
- Refines prompts systematically based on gaps
- Knows when response is "good enough" vs. needs iteration
- Can articulate what changed and why it improved results

**Example Iteration:**
```
Original: "Explain Newton's Laws."
Response: [Gets too technical]

Refined: "I'm a 9th grader just starting physics. Explain Newton's Three
Laws using examples from sports or everyday activities. For each law,
give one simple explanation and one real-world example I can visualize."
Response: [Much better, includes examples, appropriate level]

Reflection: "I added my grade level, requested specific examples from
familiar contexts, and asked for a structured format. This helped me
get explanations I could actually understand and remember."
```

**Level 3 - Proficient**
- Evaluates whether response answers the question
- Modifies prompts when first response isn't helpful
- Can identify 2-3 specific problems with unhelpful responses
- Usually gets satisfactory results within 2-3 attempts

**Example Iteration:**
```
Original: "Help with my essay."
Response: [Too vague, AI doesn't know what to do]

Refined: "Help me create an outline for my essay about renewable energy.
I need 3 main points with 2 supporting details each."
Response: [Better, usable outline provided]
```

**Level 2 - Developing**
- Recognizes when response isn't helpful but may not know why
- Can make basic adjustments with prompting
- May give up after one attempt
- Needs guidance to identify specific improvements

**Example Iteration:**
```
Original: "Explain this."
Response: [Confused AI response]

Refined: "Explain this problem better."
Response: [Still not ideal]

(Needs help making more specific improvements)
```

**Level 1 - Beginning**
- Accepts first response even if not helpful
- Doesn't attempt to improve prompts
- Unclear how to evaluate response quality
- May blame AI rather than prompt

**Example:**
```
Original: "Tell me about science."
Response: [Way too broad]
Student: "This doesn't help. The AI is bad."
(Doesn't attempt to refine)
```

**Success Indicators:**
- [ ] Evaluates responses critically
- [ ] Identifies specific needed improvements
- [ ] Refines prompts systematically
- [ ] Persists through 2-3 iterations if needed
- [ ] Reflects on what changes worked and why

---

### 8. Ethical Use & Academic Integrity

**What We're Evaluating:** Using AI as a learning tool while maintaining academic honesty

#### Performance Indicators

**Level 4 - Advanced**
- Consistently uses AI for understanding, not just answers
- Independently cites AI assistance appropriately
- Helps peers understand ethical boundaries
- Advocates for responsible AI use in academic settings
- Can articulate the difference between learning support and shortcuts

**Example Approach:**
```
Before AI: Attempts problem independently, identifies specific confusion
With AI: "I tried solving this equation and got stuck at the factoring
step. Don't solve it for me—explain what I should look for when
factoring and guide me to the next step."
After AI: Completes problem independently using guidance learned
On Assignment: Notes "Used AI to understand factoring strategy"
```

**Level 3 - Proficient**
- Uses AI to understand concepts, not skip learning
- Follows classroom AI use policies
- Cites AI when contributing to submitted work
- Can explain why certain uses would be inappropriate
- Seeks clarification when unsure about boundaries

**Example Approach:**
```
Appropriate: "Help me understand this chapter by asking me questions
about the main themes."
Appropriate: "I wrote this paragraph. Help me identify where my argument
is weak."
Cites: Mentions AI help on assignment when applicable
```

**Level 2 - Developing**
- Generally uses AI appropriately with occasional missteps
- Sometimes uncertain about when citation is needed
- May be tempted to use AI for shortcuts
- Needs occasional reminders about policies
- Learning to distinguish help from doing work

**Example Approach:**
```
Sometimes: Gets help understanding but might copy phrasing directly
Inconsistent: Not always sure when to cite AI assistance
Learning: Beginning to see value of understanding over answers
```

**Level 1 - Beginning**
- May use AI to complete work rather than learn
- Unclear on academic integrity boundaries
- Doesn't recognize importance of citing AI
- Needs frequent guidance on appropriate use
- May see AI as answer generator rather than learning partner

**Example Approach:**
```
Problematic: "Write my essay about the Civil War."
Problematic: "Solve all these math problems for me."
Doesn't cite: Submits AI-generated content as own work
```

**Success Indicators:**
- [ ] Consistently uses AI for learning, not shortcuts
- [ ] Cites AI assistance when required
- [ ] Follows school/class AI policies
- [ ] Can explain ethical boundaries
- [ ] Demonstrates learning from AI interaction, not just completion

---

### 9. Cross-Subject Application

**What We're Evaluating:** Transferring prompt engineering skills across different academic subjects

#### Performance Indicators

**Level 4 - Advanced**
- Seamlessly adapts techniques across all subjects
- Recognizes which techniques work best for different subjects
- Creates subject-specific prompt libraries
- Explains how prompt strategies vary by discipline
- Teaches others about subject-specific approaches

**Example:**
```
Math: "Act as a math tutor. Guide me through solving this equation
step-by-step, checking my work at each stage."

English: "Act as a writing coach. Help me analyze the symbolism in this
poem by asking me questions about the imagery and themes."

History: "Act as a historian. Help me understand the causes of WWI by
connecting economic, political, and social factors."

(Recognizes math needs procedural guidance, English needs analytical
questioning, history needs connection-building)
```

**Level 3 - Proficient**
- Uses prompt engineering in 3+ different subjects
- Adjusts approach somewhat for different subject types
- Has favorite prompts for main subjects
- Successfully transfers core techniques across subjects

**Example:**
```
Uses role-based prompting in math, science, and English
Adjusts context for different subject needs
Recognizes some subjects need different approaches
Applies learned techniques in new subjects
```

**Level 2 - Developing**
- Uses prompts mainly in 1-2 favorite subjects
- May struggle to adapt techniques to new subjects
- Techniques work better in some subjects than others
- Learning to recognize subject-specific needs

**Example:**
```
Strong in math prompting, still developing science prompts
Uses same basic prompt structure for all subjects
Needs examples to apply techniques in new subjects
```

**Level 1 - Beginning**
- Limited application across subjects
- Doesn't transfer skills to new contexts
- May only use prompts when specifically assigned
- Needs guidance for each new subject application

**Example:**
```
Only uses prompts in one class
Doesn't see connections across subjects
Requires new instruction for each subject
```

**Success Indicators:**
- [ ] Uses prompt engineering in 3+ subjects
- [ ] Adapts techniques to subject requirements
- [ ] Recognizes subject-specific strategies
- [ ] Independently transfers skills to new subjects

---

### 10. Prompt Library Development

**What We're Evaluating:** Building and maintaining a personal collection of effective prompts

#### Performance Indicators

**Level 4 - Advanced**
- Maintains organized, comprehensive prompt library
- Creates custom templates for personal learning needs
- Regularly updates and refines saved prompts
- Shares effective prompts with peers
- Documents why prompts work and when to use them

**Example Library Organization:**
```
My Prompt Library/
├── Math/
│   ├── Algebra problem-solving guide
│   ├── Geometry proof helper
│   └── Word problem breakdown template
├── English/
│   ├── Essay thesis development
│   ├── Literary analysis question prompts
│   └── Grammar explanation template
├── Science/
│   ├── Lab report review checklist
│   ├── Concept connection builder
│   └── Study guide creator
└── Notes/
    ├── What works best for visual learning
    ├── Prompts for test prep
    └── Quick reference favorites

Each entry includes:
- The prompt text
- When to use it
- Example results
- Refinement notes
```

**Level 3 - Proficient**
- Has a collection of 10+ saved prompts
- Organized by subject or purpose
- Regularly uses saved prompts
- Occasionally adds new prompts
- Can find and reuse prompts when needed

**Example Library:**
```
Saved Prompts:
- Math help template (used weekly)
- Essay brainstorming prompt (used for each essay)
- History timeline creator (used monthly)
- Science vocabulary builder (used for new units)
- General study guide maker (used before tests)

Basic organization, accessible, frequently referenced
```

**Level 2 - Developing**
- Has saved a few prompts (3-5)
- May or may not organize them
- Sometimes remembers to use saved prompts
- Adding to library gradually
- Collection is somewhat random

**Example Library:**
```
A few prompts saved in notes or doc:
- One math prompt that worked well
- One prompt for English from class
- Maybe one or two others

Not organized, doesn't always remember to check them
```

**Level 1 - Beginning**
- No systematic prompt collection
- Recreates prompts each time
- Hasn't started organizing successful prompts
- May not see value in saving prompts

**Example:**
```
Doesn't save prompts
Starts from scratch each time
No organized collection
```

**Success Indicators:**
- [ ] Maintains collection of 10+ prompts
- [ ] Organized by subject or purpose
- [ ] Regularly uses and updates library
- [ ] Documents why prompts are effective
- [ ] Shares useful prompts with others

---

## Scoring Guide

### Overall Performance Levels

**Advanced (36-40 points)**
- Masters all core techniques independently
- Creates sophisticated, effective prompts consistently
- Teaches and helps others develop skills
- Uses AI ethically and strategically as a learning partner
- Demonstrates expertise across all subject areas

**Proficient (27-35 points)**
- Strong skills in all core techniques
- Creates effective prompts independently
- Applies techniques across multiple subjects
- Uses AI appropriately and ethically
- Reliable, consistent performance

**Developing (18-26 points)**
- Growing skills with occasional guidance needed
- Creates basic effective prompts
- Applying techniques in some subjects
- Learning ethical use practices
- Showing steady improvement

**Beginning (10-17 points)**
- Building foundational understanding
- Needs structured support and examples
- Limited independent application
- Developing awareness of ethical use
- Early stages of skill development

### Score Calculation

Rate each of the 10 skill areas (1-4), then total:
- **40 points possible** (10 areas × 4 points maximum)
- **30 points = proficient** (75% mastery)
- **35 points = strong proficient** (87.5% mastery)
- **36+ points = advanced** (90%+ mastery)

---

## Using This Rubric

### For Formative Assessment (During Learning)

1. **Select 3-4 focus areas** based on recent instruction
2. **Observe student work** during practice activities
3. **Provide specific feedback** tied to performance indicators
4. **Set growth goals** for next lesson or week
5. **Celebrate progress** in specific skill areas

### For Summative Assessment (End of Unit/Course)

1. **Evaluate all 10 skill areas** using multiple evidence sources
2. **Calculate overall score** and determine performance level
3. **Provide comprehensive feedback** with specific examples
4. **Identify strengths** to celebrate and build on
5. **Set future goals** for continued growth

### Evidence Sources

Collect evidence from multiple sources:
- [ ] Class exercises and practice activities
- [ ] Homework assignments with prompts and responses
- [ ] Student prompt library
- [ ] Self-assessment reflections
- [ ] Peer teaching or helping instances
- [ ] Final project work
- [ ] Class discussions and explanations

### Feedback Guidelines

**Be Specific:**
Instead of: "Good job on prompts."
Try: "Your role-based prompts for history class include specific context about your grade level and what you've already learned. This helps AI personalize responses perfectly for your needs."

**Be Growth-Oriented:**
Instead of: "You need to improve context."
Try: "You're including basic context like grade level. Next, try adding what you already understand and where you're confused. This helps AI target exactly what you need."

**Celebrate Progress:**
Instead of: "You're at Level 2."
Try: "You've moved from rarely using constraints to including them in half your prompts. Let's work on making those constraints more specific to get even better learning-focused responses."

---

## Student Reflection Questions

After being assessed, students should reflect on:

1. **Strengths:** Which skill areas are my strongest? What am I doing well?

2. **Growth:** Which areas have improved most since I started? What helped me improve?

3. **Challenges:** Which techniques do I find most difficult? Why might that be?

4. **Application:** Which skills do I use most in my actual schoolwork? Why?

5. **Goals:** What specific skills do I want to improve? How will I practice?

6. **Impact:** How has prompt engineering changed my learning experience?

---

## Growth Tracking

Use this section to track progress over time:

### Assessment 1 (Baseline)
**Date:** _______________
**Overall Score:** _____ / 40
**Performance Level:** _______________
**Top Strengths:**
**Growth Areas:**
**Goals Set:**

### Assessment 2 (Mid-Course)
**Date:** _______________
**Overall Score:** _____ / 40
**Performance Level:** _______________
**Top Strengths:**
**Growth Areas:**
**Goals Set:**
**Progress on Previous Goals:**

### Assessment 3 (Final)
**Date:** _______________
**Overall Score:** _____ / 40
**Performance Level:** _______________
**Top Strengths:**
**Growth Areas:**
**Goals Set:**
**Progress on Previous Goals:**

### Overall Growth Summary
**Starting Level:** _______________
**Ending Level:** _______________
**Points Gained:** _______________
**Most Improved Area:**
**Biggest Success:**
**Future Goals:**

---

## Notes for Educators

### Assessment Tips

1. **Don't assess everything at once** - Focus on 3-4 skills per class/unit
2. **Use authentic work** - Assess actual homework prompts, not artificial exercises
3. **Observe over time** - Single instances don't show true skill level
4. **Consider growth** - Improvement matters as much as current level
5. **Be consistent** - Use the same indicators across all students

### Differentiation

**For Struggling Students:**
- Focus on fewer skills at a time
- Provide more structured templates and examples
- Celebrate small improvements
- Offer additional practice opportunities
- Use peer mentoring

**For Advanced Students:**
- Encourage teaching others
- Challenge with complex, multi-subject applications
- Focus on sophisticated combination techniques
- Develop specialized prompt libraries
- Create original templates

### Common Pitfalls to Avoid

- Assessing too early before students have practiced
- Focusing only on prompt structure, ignoring effectiveness
- Not considering context of use (subject, assignment type)
- Penalizing experimentation and iteration
- Failing to acknowledge growth and improvement

---

## Alignment with Learning Objectives

This rubric directly assesses the curriculum's core learning objectives:

✓ Craft effective prompts that elicit helpful, accurate responses
✓ Apply role-based prompting across subjects
✓ Break complex problems into manageable steps
✓ Provide clear context to AI tools
✓ Use few-shot prompting with examples
✓ Build personal prompt libraries
✓ Use AI ethically and appropriately
✓ Combine multiple techniques effectively

---

**Version:** 1.0
**Last Updated:** October 2024
**Next Review:** End of curriculum cycle

**Questions or feedback about this rubric?** Contact the curriculum developer or share suggestions for improvement.
