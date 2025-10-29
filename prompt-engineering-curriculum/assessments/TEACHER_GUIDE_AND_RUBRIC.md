# 📘 Teacher Guide: Meta-Prompt Tutor Assessment

## Overview for Teachers

This assessment uses an **AI tutor embedded in a meta-prompt** that students paste into Google Gemini. The AI acts as an interactive tutor that:
- Explains 7 prompt engineering techniques
- Asks students to create prompts demonstrating each technique
- Evaluates student work in real-time
- Provides feedback and scoring
- Offers revision opportunities
- Generates a final performance report

**Your role:** Verify authenticity, review AI assessments, and provide human oversight.

---

## Table of Contents

1. [Assessment Logistics](#assessment-logistics)
2. [What Each Section Tests](#what-each-section-tests)
3. [Sample Answers by Proficiency Level](#sample-answers-by-proficiency-level)
4. [Rubric Deep Dive](#rubric-deep-dive)
5. [Grading & Verification Process](#grading--verification-process)
6. [Common Student Mistakes](#common-student-mistakes)
7. [Differentiation Strategies](#differentiation-strategies)
8. [Interpreting Results](#interpreting-results)

---

## Assessment Logistics

### Prerequisites
- Students must complete **Class 1** (Foundations + Role-Based Prompting)
- Students should complete **Class 2** (Advanced Techniques)
- Students should understand R.C.T.F. framework

### Time Required
- **In-class administration:** 90-minute block recommended
- **Homework option:** 45-75 minutes at home
- **Fast finishers:** 35-45 minutes
- **Students who revise extensively:** 60-75 minutes

### Materials Needed
- Computer or tablet with internet access
- Google Gemini access (free account)
- Way to save conversation (screenshots or copy/paste)

### Setup Instructions
1. Distribute `STUDENT_QUICK_START_GUIDE.md` before assessment day
2. Review R.C.T.F. framework as a class
3. Demonstrate how to copy and paste the meta-prompt
4. Remind students this is a learning assessment (they get feedback during)
5. Clarify submission requirements (screenshots vs. document)

---

## What Each Section Tests

### Section 1: Role-Based Prompting (15 points)
**Skill Assessed:** Ability to assign specific expert roles with modifiers to shape AI responses

**Key Components to Look For:**
- Clear role assignment ("Act as..." or "You are...")
- Specific modifiers (patient, Socratic, uses analogies, encouraging, etc.)
- Role appropriate to the task
- Role integrated with other prompt elements

**Common Roles Students Should Know:**
- Subject teachers (math teacher, biology tutor, history expert)
- Specific teaching styles (Socratic teacher, step-by-step guide)
- Writing coaches and peer tutors
- Test prep specialists

**Example Strong Response:**
> "Act as a patient 9th grade algebra teacher who specializes in helping students who struggle with word problems..."

**Example Weak Response:**
> "Help me with math"

---

### Section 2: Context Engineering (15 points)
**Skill Assessed:** Providing comprehensive background information for personalized AI responses

**Key Components to Look For:**
1. ✓ Grade/Course Level specified
2. ✓ Current Understanding stated (what they know)
3. ✓ Specific Confusion identified (what they don't know)
4. ✓ Learning Need explained (why they need help)
5. ✓ Learning Preferences included (optional but strong)

**Context Depth Indicators:**
- **Excellent:** All 5 components, highly specific, shows metacognitive awareness
- **Proficient:** 4 components present, reasonably specific
- **Developing:** 2-3 components, somewhat generic
- **Weak:** 1 or fewer components, very vague

**Example Strong Response:**
> "I'm an 11th grader in AP Biology studying cellular respiration. I understand that glucose breaks down and ATP is produced, and I can label the diagrams of glycolysis and the Krebs cycle. However, I'm confused about why the electron transport chain produces so much more ATP than the other stages—I don't understand the mechanism that makes it more efficient. I have a test Friday and need to explain this process, not just memorize it. I learn best when concepts are explained with analogies to systems I already understand."

**Example Weak Response:**
> "I need help with biology homework"

---

### Section 3: Multi-Step (Chain-of-Thought) Prompting (14 points)
**Skill Assessed:** Breaking complex tasks into sequential, logical steps

**Key Components to Look For:**
- 3-5 distinct steps (not just repeated tasks)
- Steps are sequential (order matters)
- Each step has a clear purpose
- Indication of progressive work (not all at once)
- Maintains learning focus (not asking for complete solutions)

**Step Quality Indicators:**
- **Strong steps:** Each builds on previous, distinct purposes, logically sequenced
- **Weak steps:** Repetitive, could be done in any order, vague purposes

**Example Strong Response:**
> "Please help me analyze this historical document using these steps:
> Step 1: Help me identify the author, audience, and time period (without telling me—ask me questions)
> Step 2: Guide me in finding the main argument or purpose
> Step 3: Walk me through identifying bias or perspective
> Step 4: Help me connect this document to the broader historical context
> Please pause after each step for me to respond before moving forward."

**Example Weak Response:**
> "Help me with my history assignment in steps"

---

### Section 4: Few-Shot Prompting (14 points)
**Skill Assessed:** Teaching AI through 2-4 concrete examples showing desired pattern

**Key Components to Look For:**
- 2-4 complete examples (2 minimum, more than 4 is excessive)
- Examples show consistent pattern/format
- Each example is complete (not partial)
- Context explains what the pattern is
- Clear task statement using the pattern

**Example Quality Indicators:**
- **Strong:** Examples are complete, pattern is obvious, format is consistent
- **Weak:** Examples are partial, pattern is unclear, inconsistent format

**Example Strong Response:**
> "I need to create vocabulary study cards with a specific format. Here are 3 examples:
>
> Example 1:
> Word: Catalyst
> Definition: A substance that speeds up a chemical reaction without being consumed
> Example Sentence: The enzyme acted as a catalyst in the digestion process.
> Memory Trick: CAT-alyst → Think of a cat moving quickly
>
> Example 2:
> Word: Synthesis
> Definition: The combination of parts to form a whole
> Example Sentence: Photosynthesis is the synthesis of glucose from carbon dioxide and water.
> Memory Trick: SYN-thesis → SYN = together, putting things together
>
> Example 3:
> Word: Inertia
> Definition: The tendency of an object to resist changes in motion
> Example Sentence: The boulder's inertia made it difficult to push.
> Memory Trick: IN-ertia → IN one place, wants to stay there
>
> Now create study cards in this exact format for: momentum, equilibrium, and velocity."

**Example Weak Response:**
> "Here's an example: Cat = animal. Now do the same for other words."

---

### Section 5: Constraint-Based Prompting (14 points)
**Skill Assessed:** Setting appropriate boundaries and limitations to shape AI responses

**Key Components to Look For:**
- 3-4 meaningful constraints (not just filler)
- Academic integrity constraint included
- Constraints are specific (not vague)
- Constraints serve clear purposes
- Variety of constraint types (format, scope, style, content)

**Constraint Types:**
1. **Academic Integrity** - "Don't solve for me, help me understand"
2. **Format** - "Keep under 200 words" or "Use bullet points only"
3. **Scope** - "Focus only on..." or "Don't go beyond..."
4. **Style** - "Explain like I'm in 8th grade" or "No jargon"
5. **Content** - "Don't include..." or "Avoid discussing..."

**Example Strong Response:**
> "I'm working on an essay thesis and need feedback, BUT:
> - Don't rewrite my thesis—ask questions to help me improve it myself
> - Focus only on thesis strength, not essay structure yet
> - Keep feedback under 150 words
> - Use straightforward language, not college writing terminology
> - Don't suggest ideas I haven't thought of—help me develop MY ideas better"

**Example Weak Response:**
> "Help me but don't make it too long"

---

### Section 6: Creative vs. Analytical Prompting (14 points total: 7 creative + 7 analytical)
**Skill Assessed:** Understanding difference between divergent and convergent thinking modes

**Creative Prompt Indicators:**
- Asks for multiple ideas/possibilities
- Open-ended questions
- Encourages brainstorming
- Values quantity and variety
- Uses exploratory language

**Analytical Prompt Indicators:**
- Asks for evaluation or judgment
- Focused, specific questions
- Encourages logical reasoning
- Values accuracy and soundness
- Uses critical thinking language

**Example Strong CREATIVE Prompt:**
> "Act as a creative writing brainstorming partner. I need to write a science fiction short story for English class. Help me generate ideas by:
> - Suggesting 6-8 different futuristic technology concepts that could be central to a story
> - For each tech concept, brainstorm 3 potential conflicts or problems it could create
> - Suggest unusual character types who would interact with these technologies
> - Propose unexpected plot twists that would surprise readers
> I want lots of wild ideas to choose from—don't worry about whether they're practical!"

**Example Strong ANALYTICAL Prompt:**
> "Act as a logic and critical thinking coach. I created this hypothesis for my science fair project: 'Plants grow better when you talk to them.'
> Please help me analyze this critically by:
> - Evaluating whether my hypothesis is specific and testable
> - Identifying logical flaws in my reasoning
> - Analyzing what confounding variables I need to control
> - Assessing whether 'grow better' is measurable enough
> Help me think like a scientist and identify weaknesses in my approach."

---

### Section 7: Combined Techniques - Capstone (14 points)
**Skill Assessed:** Synthesizing multiple techniques into one sophisticated prompt

**Key Components to Look For:**
- At least 4 of the 7 techniques present
- Techniques work together (not just listed)
- Strategic purpose for each element
- Sophisticated understanding demonstrated
- Would produce highly effective learning experience

**Techniques That Should Be Combined:**
1. Role-based prompting
2. Rich context engineering
3. Multi-step structure OR few-shot examples
4. Meaningful constraints
5. Creative OR analytical approach

**Sophistication Indicators:**
- **Exceptional:** All elements serve strategic purposes, seamless integration, shows mastery
- **Strong:** 4-5 elements present and mostly integrated
- **Adequate:** 3-4 elements present but somewhat disconnected
- **Weak:** 2 or fewer elements, no synthesis

**Example Strong Capstone:**
> "Act as an encouraging AP Statistics tutor who specializes in helping students understand concepts, not just formulas (ROLE).
>
> I'm a 12th grader preparing for my AP exam. I understand how to calculate standard deviation and can plug numbers into the formula. However, I'm confused about what standard deviation actually MEANS—why does it matter? When I see 'SD = 5' vs 'SD = 15,' I don't know how to interpret the difference or what it tells me about the data. My exam is in 2 weeks and I need conceptual understanding, not just formula memorization (CONTEXT).
>
> Please help me through these steps (MULTI-STEP):
> Step 1: Guide me in creating a visual representation of what standard deviation shows (don't draw it for me—ask questions to help me figure it out)
> Step 2: Give me 3 data sets with different standard deviations and help me interpret what each tells us
> Step 3: Help me create a decision rule: when is standard deviation 'high' vs 'low' and why does it matter?
>
> Constraints (CONSTRAINTS):
> - Don't just define the term—help me understand the meaning
> - Explain at AP level but avoid statistics jargon I haven't learned
> - Keep each explanation under 100 words
> - Don't solve problems for me—guide me through reasoning
> - Focus on interpretation, not calculation
>
> I learn best through real-world examples and comparisons."

---

## Sample Answers by Proficiency Level

### Section 1: Role-Based Prompting

**EXCELLENT (14-15 points):**
> "Act as a patient and Socratic 10th grade chemistry teacher who helps students discover answers through guided questions rather than direct explanations. I'm studying chemical reactions and balancing equations. I understand that atoms can't be created or destroyed, but I'm confused about how to know which coefficients to use when balancing equations—I just guess and check randomly. Can you guide me through developing a systematic approach by asking me questions that help me figure it out myself? Please use the balancing equation: __H2 + __O2 → __H2O as our example."

*Why excellent: Specific role with multiple modifiers, clear context (grade, topic, current knowledge, confusion), specific task, format request, maintains learning*

**PROFICIENT (11-13 points):**
> "Act as a helpful biology tutor. I'm in 9th grade learning about photosynthesis. I know it's how plants make food, but I don't understand the difference between the light reactions and the dark reactions. Can you explain this in simple terms with an example?"

*Why proficient: Clear role, context present (grade, topic, confusion), specific task, some format request (simple terms, example), could be more sophisticated*

**DEVELOPING (7-10 points):**
> "Be a math teacher. I need help with fractions. I don't understand how to multiply them. Explain it to me."

*Why developing: Basic role (no modifiers), minimal context (subject, vague confusion), task is clear but basic, no format request, not very specific*

**NEEDS IMPROVEMENT (4-6 points):**
> "Help me understand history homework"

*Why needs improvement: No clear role, no context about level or specific topic, no clear task, no format*

---

### Section 2: Context Engineering

**EXCELLENT (14-15 points):**
> "I'm a 12th grader in AP Calculus AB studying derivatives. I understand the power rule and can take derivatives of polynomial functions like x³ + 2x² - 5. I also understand that derivatives represent rate of change or slope of tangent line. However, I'm struggling with the chain rule—I can identify when I need to use it (when functions are nested), but I mess up the execution and don't know which part to differentiate first. I have a quiz on Friday covering chain rule applications and I need to build confidence in the process, not just memorize examples. I learn best when I can see the step-by-step logic of why each step happens, and I like to practice with problems that gradually increase in difficulty."

*Why excellent: All 5 context components (grade/course, current understanding is detailed, specific confusion clearly identified, learning need with timeline, learning preferences), shows metacognitive awareness, very specific*

**PROFICIENT (11-13 points):**
> "I'm in 10th grade English and we're writing literary analysis essays. I understand that I need a thesis statement and I know it should be arguable. But I'm confused about how to make my thesis sophisticated enough for an A—mine always sound too simple. I have an essay due next week on 'To Kill a Mockingbird' and I need help making my thesis stronger."

*Why proficient: Grade and course present, current knowledge stated, specific confusion identified, learning need with timeline, missing learning preferences but still solid*

**DEVELOPING (7-10 points):**
> "I'm in 9th grade studying World War 2. I understand the basics but I'm confused about some stuff. I have a test coming up and need help."

*Why developing: Grade and subject present, vague current knowledge, very vague confusion ("some stuff"), learning need present but not specific, not enough detail*

**NEEDS IMPROVEMENT (4-6 points):**
> "I need help with chemistry. I don't get it."

*Why needs improvement: Subject mentioned but no grade level, no current understanding stated, confusion too vague, no learning need specified*

---

### Section 3: Multi-Step Prompting

**EXCELLENT (13-14 points):**
> "I need to write a persuasive essay arguing for a school policy change. Please help me develop this through these steps:
>
> Step 1: Guide me through brainstorming 3-4 possible policy changes by asking me questions about problems I notice at school (don't suggest ideas—help me identify my own)
>
> Step 2: Help me evaluate which policy change would be most feasible and impactful by creating a decision matrix together
>
> Step 3: Walk me through crafting a strong thesis statement that includes my policy, the reason for it, and a counter-argument acknowledgment
>
> Step 4: Guide me in outlining three supporting arguments with evidence I already have or can research
>
> Step 5: Help me anticipate counter-arguments and plan rebuttals
>
> Please complete one step at a time and wait for my response before proceeding. I want to develop these ideas myself with your guidance."

*Why excellent: 5 clear sequential steps, each step builds on previous, distinct purposes for each, requests progressive work, maintains learning focus, shows sophistication*

**PROFICIENT (10-12 points):**
> "Help me solve this physics problem about projectile motion in steps:
> Step 1: Help me identify the given information and what I need to find
> Step 2: Guide me in choosing the right equations
> Step 3: Walk me through setting up the problem
> Step 4: Help me solve it
> Wait for me to respond between steps."

*Why proficient: 4 clear steps, sequential, distinct purposes, requests progressive work, maintains some learning focus, could be more sophisticated*

**DEVELOPING (7-9 points):**
> "Please help me with my research paper in these steps:
> 1. Help me find sources
> 2. Help me write my outline
> 3. Help me write the paper
> Do each step one at a time."

*Why developing: 3 steps present, somewhat sequential, but steps are too broad and vague, doesn't show clear progression, could ask AI to do too much*

**NEEDS IMPROVEMENT (4-6 points):**
> "Help me do my homework step by step"

*Why needs improvement: Mentions steps but doesn't define them, no structure, too vague*

---

### Section 4: Few-Shot Prompting

**EXCELLENT (13-14 points):**
> "I'm creating a study guide for my biology test on cell organelles. I want each organelle to have: name, function, analogy to something in a city, and a sketch description. Here are 3 examples of the format:
>
> Example 1:
> **Organelle:** Mitochondria
> **Function:** Produces ATP (energy) through cellular respiration
> **City Analogy:** Power plant - generates electricity (energy) for the whole city
> **Sketch Description:** Oval shape with wavy inner membrane lines (cristae)
>
> Example 2:
> **Organelle:** Nucleus
> **Function:** Contains DNA and controls all cell activities
> **City Analogy:** City Hall - contains the plans (DNA) and controls what happens in the city
> **Sketch Description:** Large circle in center of cell with smaller circle inside (nucleolus)
>
> Example 3:
> **Organelle:** Ribosome
> **Function:** Synthesizes proteins from amino acids
> **City Analogy:** Factory - assembles products (proteins) from raw materials (amino acids)
> **Sketch Description:** Tiny dots scattered throughout cell or attached to ER
>
> Now please create study guide entries in this exact format for: chloroplast, endoplasmic reticulum, and Golgi apparatus."

*Why excellent: Clear context, format explained before examples, 3 complete examples showing consistent pattern, examples demonstrate all components, actual task clearly stated, would produce exactly what student wants*

**PROFICIENT (10-12 points):**
> "I need to practice solving systems of equations. Here are 2 examples of the format I want:
>
> Example 1:
> Problem: 2x + y = 7 and x - y = 2
> Solution: x = 3, y = 1
> Check: 2(3) + 1 = 7 ✓ and 3 - 1 = 2 ✓
>
> Example 2:
> Problem: 3x + 2y = 12 and x + y = 5
> Solution: x = 2, y = 3
> Check: 3(2) + 2(3) = 12 ✓ and 2 + 3 = 5 ✓
>
> Create 5 more practice problems like these with solutions and checks."

*Why proficient: Context present, 2 examples (minimum), examples show consistent pattern, examples are complete, task is clear, could use one more example for strength*

**DEVELOPING (7-9 points):**
> "Here's an example of what I want:
> Word: Happy - Feeling good
> Word: Sad - Feeling bad
> Now do more words like this."

*Why developing: 2 examples present but very simple, pattern is clear but basic, examples lack detail, format is too simple, could be more sophisticated*

**NEEDS IMPROVEMENT (4-6 points):**
> "Here's an example: Dogs are animals. Now give me more examples."

*Why needs improvement: Only 1 example (need 2 minimum), example doesn't show clear pattern, unclear what student wants, no context*

---

### Section 5: Constraint-Based Prompting

**EXCELLENT (13-14 points):**
> "Act as a writing coach for my 11th grade English persuasive essay. I want feedback on my introduction paragraph, BUT please follow these guidelines:
>
> Academic Integrity:
> - Don't rewrite any sentences for me—identify problems and ask questions to help me fix them myself
> - If you notice issues, point them out but let me solve them
>
> Scope Constraints:
> - Focus ONLY on the hook and thesis statement—don't comment on body paragraph ideas yet
> - Limit feedback to 3 main points maximum so I'm not overwhelmed
>
> Format Constraints:
> - Keep total feedback under 200 words
> - Use bullet points for clarity
>
> Style Constraints:
> - Explain in straightforward 11th grade language
> - Don't use college-level writing terminology unless you define it
>
> Content Constraints:
> - Don't suggest arguments I haven't introduced
> - Don't bring up counter-arguments at this stage
>
> Here's my intro paragraph: [student would paste their writing]"

*Why excellent: 5 constraint categories with 2-3 constraints each, academic integrity prioritized, constraints are specific and purposeful, constraints clearly maintain learning while shaping response quality*

**PROFICIENT (10-12 points):**
> "Help me understand photosynthesis but:
> - Don't just give me definitions—help me understand the process
> - Keep explanations under 150 words each
> - Explain at 9th grade biology level
> - Don't include information about cellular respiration yet, just photosynthesis
> I want to understand, not memorize."

*Why proficient: 4-5 constraints present, academic integrity implied, constraints are specific, good variety (content, format, style, learning), could be more sophisticated*

**DEVELOPING (7-9 points):**
> "Help me with my math homework but don't solve it for me. Keep it short and simple. Don't make it too hard to understand."

*Why developing: 3 constraints present, academic integrity included, constraints are somewhat vague ("short," "simple," "too hard"), could be more specific*

**NEEDS IMPROVEMENT (4-6 points):**
> "Help me but make it easy to understand"

*Why needs improvement: Only 1 vague constraint, no academic integrity focus, not specific, wouldn't meaningfully shape AI response*

---

### Section 6: Creative vs. Analytical Prompting

**EXCELLENT CREATIVE (6-7 points):**
> "Act as a creative brainstorming partner for my science fair project. I'm interested in environmental science but haven't picked a specific topic yet. Help me explore possibilities by:
> - Generating 8-10 different environmental issues a high schooler could research
> - For each issue, suggest 3-4 different experimental approaches I could take
> - Brainstorm creative ways to measure or visualize environmental impact
> - Propose unexpected angles or perspectives that would make my project stand out
> - Suggest interdisciplinary connections (how environmental science intersects with technology, social justice, economics, etc.)
> Go wild with ideas—I want quantity and creativity to spark my imagination! No idea is too ambitious at this brainstorming stage."

*Why excellent: Clear creative task (brainstorming), asks for multiple possibilities (8-10 + 3-4 + more), values quantity, encourages wild/creative ideas, divergent thinking language throughout*

**EXCELLENT ANALYTICAL (6-7 points):**
> "Act as a critical thinking coach for my history class. I've written this thesis statement for my essay on the Civil Rights Movement:
>
> 'The Civil Rights Movement succeeded because of Martin Luther King Jr.'s leadership, peaceful protests, and media coverage.'
>
> Please help me analyze this critically by:
> - Evaluating whether my thesis is specific enough and arguable
> - Identifying logical weaknesses in my causal reasoning (am I oversimplifying?)
> - Analyzing what important factors I might be leaving out
> - Assessing whether my three points are equally strong or if one is weaker
> - Reasoning through what counter-arguments a historian might raise
> - Judging whether this thesis would earn a strong grade based on AP History standards
>
> Help me think like a historian and strengthen my analytical reasoning."

*Why excellent: Clear analytical task (evaluation), asks for judgment and critical thinking, focuses on logical reasoning, uses evaluative language ("assess," "analyze," "judge"), convergent thinking focus*

---

**PROFICIENT CREATIVE (5 points):**
> "I need to write a creative short story for English class about 'a character who discovers a hidden talent.' Help me brainstorm by suggesting:
> - 5-6 different character types (different ages, backgrounds)
> - 4-5 different hidden talents they could discover
> - Some interesting settings where this discovery could happen
> - Possible conflicts or obstacles
> I want lots of options to choose from!"

*Why proficient: Creative task, asks for multiple ideas, wants options, divergent thinking, good but less sophisticated than excellent*

**PROFICIENT ANALYTICAL (5 points):**
> "I'm comparing two different methods for solving quadratic equations: factoring vs. quadratic formula. Help me analyze:
> - When is each method more efficient?
> - What are the advantages and disadvantages of each?
> - Which method is more reliable and why?
> - How do I decide which to use on a test?
> Help me think logically about when to use each approach."

*Why proficient: Analytical task, asks for evaluation/comparison, focuses on logical decision-making, good but less sophisticated than excellent*

---

## Rubric Deep Dive

### How the AI Evaluates (and How You Should Too)

For each section, the AI uses this rubric. You should verify its assessments using the same criteria:

#### Component Checklist Method
1. **Identify required components** for that section type
2. **Check each component** - Is it present? Is it detailed or vague? Is it well-executed?
3. **Assess integration** - Do components work together or feel disconnected?
4. **Evaluate specificity** - Is everything concrete or is it generic?
5. **Determine effectiveness** - Would this prompt actually produce the desired result?

#### Scoring Bands

**13-15 points (Excellent):**
- ALL required components present
- Components are DETAILED and SPECIFIC
- Shows SOPHISTICATED understanding
- Components are WELL-INTEGRATED
- Would produce HIGHLY EFFECTIVE AI response
- Little to no improvement needed

**10-12 points (Proficient):**
- MOST required components present
- Components are REASONABLY SPECIFIC
- Shows SOLID understanding
- Components are SOMEWHAT INTEGRATED
- Would produce HELPFUL AI response
- Minor improvements possible

**7-9 points (Developing):**
- SOME components present but INCOMPLETE
- Components are SOMEWHAT VAGUE
- Shows PARTIAL understanding
- Components feel DISCONNECTED
- Would produce OKAY but NOT OPTIMAL response
- Several improvements needed

**4-6 points (Needs Improvement):**
- FEW required components present
- Components are VERY VAGUE
- Shows LIMITED understanding
- Little to no integration
- Would produce POOR QUALITY response
- Major improvements needed

**0-3 points (Insufficient):**
- MISSING most or all required components
- UNCLEAR what student wants
- Shows MINIMAL to NO understanding
- Would NOT produce useful response

---

## Grading & Verification Process

### Step 1: Review for Authenticity

**Red Flags (Possible Cheating or External Help):**
- ⚠️ All prompts are extremely sophisticated but student struggled in class
- ⚠️ Language level significantly above student's usual work
- ⚠️ Prompts use vocabulary from the meta-prompt itself (copying examples)
- ⚠️ Identical or near-identical to another student's work
- ⚠️ Perfect scores on all sections (very rare even for strong students)
- ⚠️ No revisions attempted despite feedback
- ⚠️ Sudden jump from weak to excellent prompts mid-assessment

**Green Flags (Authentic Work):**
- ✅ Prompts relate to topics student is actually studying
- ✅ Language matches student's usual level
- ✅ Shows progression from early to later sections
- ✅ Takes some revision opportunities
- ✅ Makes some mistakes but learns from feedback
- ✅ Scores align with classroom performance

### Step 2: Verify AI Scoring

The AI is generally accurate, but double-check:

**When to Adjust Scores UP (+2 to +5 points):**
- AI undervalued sophisticated technique combinations
- Student demonstrated exceptional metacognitive awareness
- Prompt shows creativity beyond typical student work
- Context was exceptionally rich but AI focused on minor missing element

**When to Adjust Scores DOWN (-2 to -5 points):**
- AI was overly generous with vague prompts
- Required components are technically present but very shallow
- Student copy-pasted template language without customization
- Academic integrity is not maintained (asking AI to do work)

**When to Request Resubmission:**
- Sections are missing or incomplete
- Screenshots are illegible or don't show full conversation
- Evidence of external help (have student redo with supervision)
- Technical errors made assessment unfair

### Step 3: Calculate Final Grade

**Option A: Use AI Score Directly (Recommended for Authentic Work)**
- If work appears authentic and AI assessments are reasonable
- Faster grading process
- Students received feedback throughout, so surprises are minimal

**Option B: Adjust AI Score (For Questionable Cases)**
- Review each section and adjust scores ±2-5 points as needed
- Recalculate total
- Provide written justification for adjustments

**Option C: Weight Rubric (Blend AI + Teacher Assessment)**
- 70% AI score + 30% teacher review = final score
- Allows for human oversight while leveraging AI efficiency

**Option D: Completion Grade (Formative Assessment)**
- Use as learning experience, not performance assessment
- Grade on completion and effort (did they finish all sections?)
- Use results to identify who needs extra support

### Step 4: Provide Additional Feedback (Optional)

Beyond the AI's report, consider adding:
- Teacher observation notes
- Specific praise for growth areas
- Customized practice recommendations
- Connection to class discussions or prior work

---

## Common Student Mistakes

### Section-Specific Mistakes

**Role-Based Prompting:**
- ❌ No role assigned ("Help me with...")
- ❌ Generic role without modifiers ("Be a teacher")
- ❌ Role doesn't match task
- ✅ FIX: "Act as a [specific role] who [modifier 1] and [modifier 2]"

**Context Engineering:**
- ❌ Missing grade level
- ❌ "I don't understand [topic]" (not specific enough)
- ❌ No explanation of what they DO understand
- ✅ FIX: Include all 5 context components with details

**Multi-Step Prompting:**
- ❌ Steps are vague ("Help me understand")
- ❌ Steps could be done in any order (not truly sequential)
- ❌ Asks for everything at once instead of progressively
- ✅ FIX: Number steps, make each distinct and sequential, request pauses

**Few-Shot Prompting:**
- ❌ Only 1 example (need minimum 2)
- ❌ Examples are incomplete or inconsistent
- ❌ Pattern isn't clear from examples
- ✅ FIX: Provide 2-3 complete examples showing consistent format

**Constraint-Based Prompting:**
- ❌ Only 1-2 constraints
- ❌ Vague constraints ("make it simple")
- ❌ No academic integrity constraint
- ✅ FIX: Include 3-4 specific constraints including academic integrity

**Creative vs. Analytical:**
- ❌ Confusing the two (analytical prompt for creative task)
- ❌ Creative prompt uses evaluative language
- ❌ Analytical prompt asks for brainstorming
- ✅ FIX: Match thinking mode to task; use appropriate language

**Capstone (Combined Techniques):**
- ❌ Lists techniques without integrating them
- ❌ Includes only 2-3 techniques
- ❌ Components feel disconnected
- ✅ FIX: Weave techniques together naturally, include 4-5+ techniques

### Universal Mistakes Across All Sections

**Vagueness:**
- Problem: "Help me with math"
- Better: "Help me understand why we multiply by the reciprocal when dividing fractions"

**Missing Academic Integrity:**
- Problem: "Write me an essay about..."
- Better: "Help me develop arguments for my essay about... without writing it for me"

**No Specificity:**
- Problem: "I don't get chemistry"
- Better: "I understand atomic structure but I'm confused about why some elements are more reactive than others"

**Copying Templates Without Customization:**
- Problem: Using exact template language from class
- Better: Adapting template to their actual situation with personal details

---

## Differentiation Strategies

### For Struggling Students

**Before Assessment:**
- Review R.C.T.F. framework one-on-one
- Provide sentence starters for each section
- Allow extra time (take home rather than in-class)
- Permit use of all class notes and templates

**During Assessment:**
- Check in after Section 1 to ensure they understand the process
- Encourage them to take ALL revision opportunities
- Provide a simplified scoring rubric focusing on basic competency

**Modified Version:**
- Reduce to 5 sections (remove Few-Shot and Creative/Analytical)
- Lower point thresholds for each proficiency level
- Provide more structured templates to fill in

**After Assessment:**
- If score is below 70%, offer re-take opportunity with teacher support
- Provide targeted mini-lessons on weak areas
- Pair with peer tutor for practice

### For Advanced Students

**Before Assessment:**
- Challenge them to NOT use templates
- Encourage combining techniques creatively
- Suggest they base all prompts on actual challenging work

**During Assessment:**
- Minimum revision goal (they should be getting it right first try)
- Time challenge (can they complete with high quality in under 40 minutes?)

**Modified Version:**
- Add 8th section: Meta-Prompting (create a prompt that generates prompts)
- Require 5+ techniques in capstone
- Demand real-world application with proof of results
- Higher point thresholds (13+ needed for "proficient")

**After Assessment:**
- If score is 90%+, exempt from future basic prompt practice
- Invite to help create prompt libraries for class
- Challenge them to teach a mini-lesson to peers

### For ELL Students

**Accommodations:**
- Allow use of translation tools
- Focus grading on prompt structure, not language perfection
- Permit responses in home language with translation
- Extend time as needed

**Supports:**
- Provide prompts in both English and home language
- Allow dictation/voice-to-text
- Partner with bilingual peer for clarification

---

## Interpreting Results

### Score Range Meanings

**90-100 (A range):**
- **What it means:** Student has mastered prompt engineering fundamentals and can apply techniques strategically
- **Next steps:** Challenge with advanced applications; use as peer tutor; explore meta-prompting
- **Class performance likely:** Top 10-20% of students

**80-89 (B range):**
- **What it means:** Student has solid understanding of most techniques with minor gaps
- **Next steps:** Targeted practice on 1-2 weak areas; encourage more context depth
- **Class performance likely:** Top 30-50% of students

**70-79 (C range):**
- **What it means:** Student understands basics but struggles with sophistication or integration
- **Next steps:** Review R.C.T.F. framework; practice with templates; focus on specificity
- **Class performance likely:** Middle 50% of students

**60-69 (D range):**
- **What it means:** Student has partial understanding but significant gaps
- **Next steps:** One-on-one review; return to Class 1 materials; focus on role + context
- **Class performance likely:** Bottom 20-30% of students

**Below 60 (F range):**
- **What it means:** Student has not grasped fundamental concepts
- **Next steps:** Immediate intervention; check if they completed prerequisite classes; may need remediation
- **Class performance likely:** Bottom 10% or did not genuinely engage with assessment

### Section-by-Section Analysis

**If student scored HIGH on Sections 1-2 but LOW on Sections 5-7:**
- **Interpretation:** Understands fundamentals but struggles with advanced techniques
- **Action:** Normal progression; provide additional practice on advanced techniques

**If student scored LOW on Sections 1-2 but HIGH on Sections 5-7:**
- **Interpretation:** Unusual pattern; may indicate external help or copying later sections
- **Action:** Verify authenticity; discuss with student

**If student scores DECREASE from Section 1 to Section 7:**
- **Interpretation:** Fatigue, loss of focus, or increasing difficulty
- **Action:** Consider offering break next time; review later sections for understanding

**If student scores INCREASE from Section 1 to Section 7:**
- **Interpretation:** Excellent! Learning during the assessment (ideal outcome)
- **Action:** Celebrate growth mindset; excellent self-teaching

### Class-Wide Data Analysis

Track these metrics across all students:

**Average Score by Section:**
- Identifies which techniques the class struggles with most
- Informs future lesson planning

**Distribution of Scores:**
- Normal distribution expected (most students in 70-85 range)
- Skewed low: Class needs more foundational work
- Skewed high: Class is ready for advanced applications

**Revision Rate:**
- How many students took revision opportunities?
- Low rate may indicate: lack of growth mindset, time pressure, or already strong first attempts
- High rate may indicate: engagement, learning during assessment, or initial confusion

**Time to Complete:**
- Average should be 45-60 minutes
- Much faster: students may be rushing
- Much slower: may need more foundational practice or clarity

---

## FAQ for Teachers

### "Should I let students use notes and templates?"
**YES.** This is open-note. The goal is demonstrating understanding and application, not memorization. Real-world prompt engineering involves referencing resources.

### "What if a student's score from the AI seems wrong?"
Review the prompts yourself using the rubric. The AI is generally accurate but can occasionally:
- Be overly generous with partial attempts
- Undervalue sophisticated synthesis
- Miss context-specific nuances
You have final authority to adjust scores ±10 points.

### "Can students work in pairs?"
**NOT RECOMMENDED.** This is an individual assessment of prompt crafting ability. However, you could:
- Allow peer consultation during revision opportunities only
- Have partners review each other's work AFTER assessment (peer feedback activity)
- Create a separate pair-based project for practice

### "What if Gemini is down or not working?"
**Backup options:**
- Reschedule assessment
- Use a different AI (Claude, ChatGPT) - meta-prompt should work with any
- Teacher-led version: You play the AI tutor role (time-intensive)

### "How do I know students didn't get help from friends/parents?"
Look for:
- Alignment with their typical classroom work
- Progression across sections (should improve or stay consistent, not jump around)
- Personalization to their actual courses and assignments
- Some imperfections (perfect work is suspicious)
If concerned, have student recreate one section under supervision.

### "Should this be graded for completion or performance?"
**RECOMMENDATION:** Performance grade, BUT:
- Weight it appropriately (10-15% of total grade, not 30-40%)
- Allow one retake for students below 70%
- Provide extensive feedback so students can learn
- Consider dropping lowest section score

Alternatively, use as formative assessment (completion grade) and follow up with a performance task.

### "What if most students score below 70%?"
This indicates:
- Class needs more instruction on these techniques
- Assessment may have been given too early
- Students may not have taken it seriously
**Response:** Review low-scoring sections as a class; provide additional practice; consider offering retake after reteaching.

---

## Answer Key Philosophy

**Note:** There are NO "correct answers" in prompt engineering—only more or less effective approaches. This guide provides EXAMPLES of strong work, not THE ONLY right answers.

**Evaluation Focus:**
- Presence and quality of required components
- Specificity vs. vagueness
- Strategic purpose of each element
- Likely effectiveness of the prompt
- Academic integrity maintained

**Student Creativity Encouraged:**
- Different students will write very different prompts
- Multiple approaches can earn full points
- Variety in style and structure is expected and welcomed

---

## Final Implementation Checklist

Before administering this assessment, ensure:

- [ ] Students have completed Classes 1 & 2
- [ ] R.C.T.F. framework has been reviewed
- [ ] Students have access to Gemini
- [ ] You've reviewed the meta-prompt yourself (test it!)
- [ ] Students understand how to save/screenshot conversations
- [ ] Submission process is clearly communicated
- [ ] You've decided on grading approach (AI score vs. adjusted vs. weighted)
- [ ] You've prepared for potential technical issues
- [ ] Students know whether this is graded for completion or performance
- [ ] Timeline and time limits are clear

**During Assessment:**
- [ ] Circulate to monitor engagement
- [ ] Address technical issues only (don't help with content)
- [ ] Note students who seem to struggle for follow-up
- [ ] Remind students to save their work

**After Assessment:**
- [ ] Review for authenticity before grading
- [ ] Verify AI assessments are reasonable
- [ ] Calculate final grades
- [ ] Identify trends for class-wide review
- [ ] Provide personalized next steps for struggling students
- [ ] Celebrate strong examples (with permission)

---

This assessment represents a comprehensive evaluation of prompt engineering skills aligned with your curriculum. Students who score well demonstrate not just memorization of techniques, but strategic application and synthesis—exactly the skills they need for academic success and lifelong learning.

Good luck with implementation! 🎓
