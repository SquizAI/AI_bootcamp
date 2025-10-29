# Class 2: Multi-Step & Advanced Prompting Techniques

**AI Academy AI Skills Camp**
90-Minute Session | Grades 7, 9, 11

---

# Class 1 Review: The Foundations

Core concepts learned:
- Role-based prompting
- Context engineering
- The four components (Role, Context, Task, Format)
- Basic prompt structure

**Today:** Advanced techniques for complex tasks

---

# Complex Problem Challenge

### When simple prompts aren't enough

Examples of complexity:
- Multi-part essay with analysis from different angles
- Math problem with 5+ sequential steps
- Research project requiring multiple sources
- Lab report with hypothesis, procedure, analysis, and conclusion

**Solution:** Advanced prompting techniques

---

# Class 2 Overview

## Four Advanced Techniques

1. **Multi-Step Prompting** - Break down complexity
2. **Few-Shot Prompting** - Teach with examples
3. **Negative Prompting** - Set boundaries
4. **Combining Techniques** - Maximum power

**Goal:** Handle sophisticated academic work while maintaining learning integrity

---

# Gemini 2.5 Capabilities (October 2025)

Current model features:
- **1 million token context window** (entire textbook capacity)
- Structured outputs (JSON, tables, formatted data)
- Multimodal understanding (text + images)
- Native reasoning and analysis

**Requirement:** Advanced techniques to utilize full capabilities

---

# SECTION 1: Multi-Step Prompting

**Breaking Down Complexity**

---

# The Problem with Simple Prompts

**Complex Assignment:**
> "Analyze the causes and effects of the Industrial Revolution on modern society, comparing economic, social, and environmental impacts."

**Simple Prompt:**
```
Explain the Industrial Revolution's impact on modern society.
```

**Result:** Generic, unfocused, misses the complexity

---

# Assignment Requirements Analysis

Assignment requires:
1. Identifying causes AND effects
2. Analyzing MULTIPLE categories (economic, social, environmental)
3. Connecting past to present
4. Making comparisons

**Issue:** One simple prompt cannot guide all requirements effectively

---

# Multi-Step Prompting Concept

**Definition:** Breaking a complex task into smaller, sequential steps and explicitly asking the AI to do each step.

**Benefits:**
- AI handles each piece with focus
- User maintains control over the process
- Builds understanding progressively
- Prevents overwhelming responses

---

# Multi-Step Approach 1: All Steps in One Prompt

```
I need to write an essay analyzing the Industrial Revolution's
impact on modern society.

Step 1: First, identify the three main economic changes from
the Industrial Revolution.

Step 2: Then, identify three major social changes.

Step 3: Finally, identify three environmental impacts.

Step 4: For each category (economic, social, environmental),
explain how those changes still affect us today.

Walk me through each step one at a time, and help me
understand the connections.
```

---

# Multi-Step Approach 2: Prompt Chaining

**Separate Sequential Prompts**

**Prompt 1:**
```
Help me identify the three most significant economic changes
from the Industrial Revolution.
```

**Wait for response, then...**

**Prompt 2:**
```
Now, using those economic changes, explain how each one
specifically impacts modern economic systems today.
```

**Continue the chain for remaining steps**

---

# When to Use Multi-Step Prompting

**Use when:**
- Problem has distinct phases or parts
- Each step depends on the previous step
- Need to build understanding progressively
- Problem too complex for one answer

**Examples by subject:**
- **Math:** Factor, then apply formula, then simplify, then check
- **Writing:** Outline, then thesis, then structure, then evidence
- **Science:** Hypothesis, then variables, then procedure, then analysis
- **History:** Causes, then effects, then connections, then implications

---

# Multi-Step Example: Science Lab Report

**Assignment:** "Write a lab report on our photosynthesis experiment."

**Multi-Step Prompt:**
```
Act as a science teacher helping with lab reports.

I need to write a lab report on our photosynthesis experiment
where we tested how different light colors affect plant growth.

Please guide me through this step-by-step:

Step 1: Help me write a clear hypothesis based on what we tested.

Step 2: Help me identify the independent variable, dependent
variable, and control variables.

Step 3: Guide me in organizing my observations into a results
section.

Step 4: Help me analyze what the results mean and whether they
support my hypothesis.

Don't write it for me—help me think through each step.
```

---

# Multi-Step: Key Takeaways

**Remember:**
- Number your steps clearly (Step 1, Step 2, etc.)
- Make steps sequential and logical
- Each step should build on the previous
- Can do all in one prompt OR chain separate prompts
- Always include role and context too

**Principle:** Multi-step transforms complex into manageable

---

# SECTION 2: Few-Shot Prompting

**Teaching AI Through Examples**

---

# The Power of Examples

## Comparison

**Option A:** "Summarize this article in a concise style focusing on key facts"

**Option B:** "Summarize like this example:
WHAT: Solar efficiency up 20%. WHO: MIT team. WHY: Makes solar competitive with fossil fuels."

**Observation:** Examples often communicate more effectively than explanations

---

# Zero-Shot vs Few-Shot

## Zero-Shot Prompting
No examples provided—only instructions

```
Summarize this article about climate change in a concise
style focusing on key facts.

[article text]
```

## Few-Shot Prompting
Examples included to show the pattern

```
Summarize in this format:

Example 1: [article] → [specific format summary]
Example 2: [article] → [specific format summary]

Now summarize: [your article]
```

---

# Few-Shot Demonstration

**Zero-Shot:**
```
Summarize this article in a concise style focusing on key facts.
```

**Result:** Variable format, may miss requirements

**Few-Shot:**
```
I want you to summarize articles in this specific style.
Here are two examples:

Example 1:
Article: [renewable energy article]
Summary: WHAT: Solar panel efficiency increased 20%.
WHO: Research team at MIT. WHY IT MATTERS: Lower costs
make solar competitive with fossil fuels.

Example 2:
Article: [ocean temperatures article]
Summary: WHAT: Ocean temps rose 0.5°C since 2000.
WHO: NOAA scientists. WHY IT MATTERS: Threatens coral
reefs and marine ecosystems.

Now, please summarize this article in the same format:
[your article about climate change]
```

**Result:** Precisely formatted, consistent structure

---

# Google's Official Recommendation

## From Google Documentation (October 2025)

> "Few-shot prompts are **highly recommended** and often more effective than zero-shot. We recommend to always include few-shot examples in your prompts."

**Why Examples Work Better:**
1. AI identifies patterns better than interpreting instructions
2. Shows format, tone, depth, and style simultaneously
3. Reduces ambiguity
4. More consistent results across multiple uses

---

# The Few-Shot Formula

## Standard Structure

```
[Context/Instruction]

Example 1:
[Input] → [Desired Output]

Example 2:
[Input] → [Desired Output]

Example 3 (optional):
[Input] → [Desired Output]

Now, apply the same pattern:
[Your actual input]
```

**Function:** Examples teach the AI your desired outcome

---

# Rules for Good Few-Shot Examples

## DO:
- Use 2-4 examples (2-3 usually optimal)
- Keep formatting absolutely consistent
- Make examples similar to your actual task
- Show positive patterns (what TO do)
- Include variety in content but consistency in structure

## DON'T:
- Include too many examples (causes overfitting)
- Mix formats between examples
- Show what NOT to do in examples
- Use examples too different from your task

---

# Few-Shot Example: Math Work Checker

**Task:** Getting AI to check math work in specific format

```
Check my math work and respond in this format:

Example:
Problem: Solve: 2x + 5 = 13
Student work:
2x + 5 = 13
2x = 8
x = 4

Response:
✓ CORRECT
Steps: All steps shown correctly
Answer: x = 4 is correct
Next practice: Try one with subtraction on both sides

Example:
Problem: Solve: 3x - 7 = 20
Student work:
3x - 7 = 20
3x = 27
x = 3

Response:
✗ ERROR at final step
Steps: You correctly added 7 to get 3x = 27
Mistake: 27 ÷ 3 = 9, not 3
Correct answer: x = 9
Next practice: Double-check your division

Now check my work:
Problem: [your actual problem]
Student work: [your work]
```

---

# Few-Shot: Key Takeaways

**Remember:**
- 2-3 examples is the sweet spot
- Consistency is CRITICAL
- Format matters more than expected
- Examples replace lengthy explanations
- Test and refine your examples

**Principle:** Show, don't just tell

---

# SECTION 3: Negative Prompting & Constraints

**Setting Boundaries**

---

# The Problem

**Prompt:**
```
Act as a biology tutor. Help me understand cellular respiration.
```

**Possible Unwanted Results:**
- Gives complete answer
- Writes out whole process
- Explains at wrong level
- Goes off on tangents

**Issue:** Without boundaries, AI may help inappropriately

---

# The Solution: Constraints

**Definition:** Constraints = Telling the AI what NOT to do or setting specific boundaries

**Purpose:**
- Maintain academic integrity (help learning, not cheating)
- Control response format and length
- Keep focus narrow
- Match your grade level

**Advantage:** Negative prompting often clearer than describing all positive requirements

---

# Type 1: Academic Integrity Constraints

## Maintain Learning Focus

Examples:
```
"Don't give me the answer directly—help me figure it out"

"Don't solve this for me—guide my thinking with questions"

"Explain the concept, but don't do my work"

"Help me understand the process, not just the solution"
```

**Function:** Keep you in the learning driver's seat

---

# Type 2: Format Constraints

## Control Output Structure

Examples:
```
"Keep your response under 100 words"

"Don't use bullet points—write in paragraphs"

"Respond in exactly 3 sentences"

"Don't include code—just explain conceptually"

"Use a table format, not prose"
```

**Function:** Match format to assignment needs

---

# Type 3: Scope Constraints

## Stay Focused

Examples:
```
"Don't go into advanced calculus—keep it at algebra level"

"Stay focused only on the European theater—don't discuss
the Pacific"

"Cover only chapters 5-7, not the entire unit"

"Don't branch into related topics—just answer the specific
question"
```

**Function:** Prevents information overload

---

# Type 4: Style Constraints

## Match Your Level

Examples:
```
"Don't use technical jargon—explain like I'm a 7th grader"

"Don't oversimplify—I need the full complexity"

"Use formal academic language, not casual tone"

"Explain with analogies, not abstract definitions"
```

**Function:** Get responses at appropriate level

---

# Strategic Placement of Constraints

## At the Beginning (Sets Expectations)
```
Act as a tutor who NEVER gives direct answers, only guides
thinking through questions.

I need help with...
```

## At the End (Reinforces)
```
[your main prompt]

Important constraints:
- Don't solve the problem for me
- Don't use vocabulary above 9th grade level
- Keep response under 150 words
```

## Embedded Throughout
```
Help me understand photosynthesis (explain the concept,
don't just list steps) by breaking it down (into 3-4 main
phases, not exhaustive detail) in a way I can remember
(using analogy or metaphor, not technical descriptions).
```

---

# Combining Constraints with Other Techniques

**Multi-step + Few-shot + Constraints:**

```
I want you to check my essay thesis statements using this format:

Example:
Thesis: "Technology is important in modern life."
Feedback: TOO VAGUE. Specify which technology and what aspect.
Better: "Social media has changed how teenagers maintain friendships."

Example:
Thesis: "Hamlet explores revenge, madness, and mortality through
the protagonist's internal conflict."
Feedback: STRONG. Specific, focused, arguable, and clear.

Now check my thesis—but DON'T rewrite it for me, just tell me
what's weak and what would make it stronger:

My thesis: [your thesis]
```

---

# Constraints: Key Takeaways

**Remember:**
- Four types: Academic integrity, Format, Scope, Style
- Place strategically (beginning, end, embedded)
- Be explicit and direct
- Constraints protect your learning
- Can combine with all other techniques

**Principle:** Constraints = guardrails that keep AI helpful, not harmful

---

# SECTION 4: Combining Techniques

**Maximum Power**

---

# Evolution of Prompt Sophistication

**Level 1: Simple prompt**
```
Help me with my history essay about WWI causes.
```

**Level 2: Add role + context**
```
Act as a history teacher. I'm a 10th grader writing about
WWI causes. I understand the assassination but not the
deeper causes. Help me understand.
```

**Level 3: Add multi-step**
```
Act as a history teacher. I'm a 10th grader writing about
WWI causes.

Step 1: Help me identify 3 underlying causes
Step 2: Help me understand how they created tension
Step 3: Help me connect them to the assassination trigger
```

---

# Evolution Continued

**Level 4: Add few-shot**
```
[Role and context]

Here's the analysis style I need:

Cause: Nationalism
How it created tension: Countries competed for dominance
Connection to war: Made countries willing to fight
Evidence: [examples]

Now help me analyze these causes in that format...
```

**Level 5: Add constraints**
```
[Everything from Levels 1-4]

Important constraints:
- Don't write the essay for me—help me build my own analysis
- Keep explanations at 10th grade level
- Focus only on European theater
- Use historical evidence, not generalizations
```

**Result:** Each layer makes the prompt more powerful and precise

---

# Decision Framework

## How to Choose Which Techniques to Combine

**Start with (almost always):**
1. Role
2. Context

**Add based on task:**
- **Complex/multi-part?** → Multi-step
- **Specific format needed?** → Few-shot
- **Risk of unwanted responses?** → Constraints

**Principle:** Add techniques because they solve a problem, not just because you can

---

# Decision Tree

**Is the Task Simple and Straightforward?**
→ YES: Role + Context + Task might be enough
→ NO: Continue...

**Does It Have Multiple Distinct Steps?**
→ YES: Add multi-step structure

**Do You Need a Specific Format or Style?**
→ YES: Add few-shot examples

**Could AI Give Unhelpful Responses?**
→ YES: Add constraints

---

# Real Scenario 1: Complex Math Problem

**Situation:** "I need help solving a quadratic word problem but I keep getting lost in the setup."

**Suggested Technique Combination:**
- **Role:** Math tutor who uses Socratic method
- **Multi-step:** Break into steps (read, identify variables, set up equation, solve, check)
- **Constraints:** Don't solve for me; ask me questions at each step
- **Few-shot:** Optional—show format of how to identify variables

**Reasoning:** Problem needs structure + learning guidance

---

# Real Scenario 2: Essay Brainstorming

**Situation:** "I need to brainstorm for an argumentative essay on school start times."

**Suggested Technique Combination:**
- **Role:** Writing coach
- **Few-shot:** Show format for argument/counterargument/evidence
- **Multi-step:** First arguments, then counterarguments, then evaluate strength
- **Constraints:** Generate ideas, don't write the essay

**Reasoning:** Needs specific format + process + boundaries

---

# Real Scenario 3: Test Review

**Situation:** "I'm studying for a biology test on ecosystems."

**Suggested Technique Combination:**
- **Role:** Biology tutor + quiz maker
- **Few-shot:** Show question format you want
- **Constraints:** Questions only from chapters 5-7; mix difficulty levels
- **Multi-step:** Optional—organize by topic first

**Reasoning:** Format precision + scope control

---

# Creating Reusable Templates

**Multi-Purpose Study Template:**

```
Act as a [subject] tutor who uses the Socratic method.

I'm studying [topic] for a [test/quiz/exam] covering [specific scope].

Here's the format I want for review questions:

Example:
Q: [Conceptual question]
If I answer: [My attempt]
Your response: [Guide without telling directly]

Generate 5 practice questions following this pattern.

Constraints:
- Difficulty level: [grade-appropriate]
- Only topics from: [chapters/sections]
- Mix conceptual and application questions
- Don't give me answers—help me think through them
```

---

# Combining Techniques: Key Takeaways

**Remember:**
- Start with role + context (always)
- Add techniques that solve specific problems
- More isn't always better
- Test and iterate
- Save templates for reuse

**Principle:** Sophisticated prompts = sophisticated results

---

# SECTION 5: Practice Time

**Apply What You've Learned**

---

# Hands-On Practice: Overview

**Three Exercise Sets (20 Minutes Total):**

1. **Multi-Step Prompting** (6-7 min)
2. **Few-Shot Prompting** (6-7 min)
3. **Combined Techniques** (6-7 min)

**Goal:** Get responses that actually help you learn and complete complex work

---

# Exercise Set 1: Multi-Step

**Task (6-7 minutes):**

1. Choose a complex assignment you're currently working on
2. Identify the distinct phases or steps
3. Write a multi-step prompt that:
   - Includes role and context
   - Has clear step labels (Step 1, Step 2, etc.)
   - Makes steps sequential and logical
4. Test in Gemini 2.5
5. Refine based on the response

**Success:** AI walks you through each step clearly

---

# Exercise Set 2: Few-Shot

**Task (6-7 minutes):**

1. Pick a task where format or style matters
2. Create 2-3 examples showing your desired format
3. Ensure consistent structure across all examples
4. Add your actual task at the end
5. Test in Gemini and observe pattern recognition
6. Adjust examples if needed

**Success:** AI follows your pattern precisely

---

# Exercise Set 3: Combined Techniques

**Task (6-7 minutes):**

1. Choose your MOST complex current assignment
2. Decide which techniques it needs
3. Build a sophisticated prompt combining:
   - Role + Context (always)
   - Multi-step OR Few-shot (or both)
   - Relevant constraints
4. Test and document what works
5. Iterate to improve

**Success:** Getting exactly the help you need without academic integrity issues

---

# SECTION 6: Wrap-Up

**Bringing It All Together**

---

# Summary

## Four Advanced Techniques Learned

1. **Multi-step prompting** - Break down complexity
2. **Few-shot prompting** - Teach with examples
3. **Negative prompting** - Set boundaries and constraints
4. **Combining techniques** - Maximize effectiveness

**Key Insight:** Complex academic work requires sophisticated prompting

---

# The Four Core Principles

1. **Multi-step breaks down complexity** into manageable pieces
2. **Few-shot teaches patterns** better than explanations
3. **Constraints maintain learning** and academic integrity
4. **Combining techniques = power** for sophisticated work

**Result:** Equipped to handle complex academic challenges

---

# Homework Assignment

## "Advanced Techniques in Action"

**Due before Class 3:**

1. Choose **2 complex problems** from different subjects
2. **Problem 1:** Use multi-step prompting
   - Document each step
   - Screenshot the full conversation
3. **Problem 2:** Use few-shot prompting
   - Create 3 examples
   - Show your actual task
   - Screenshot the conversation
4. **For both:** Add appropriate constraints

---

# Homework: Reflection Component

**Write 3-4 sentences reflecting on:**
- Which technique worked better for which type of problem?
- What was challenging about using these techniques?
- What will you do differently next time?

**Time estimate:** 30-40 minutes total

**Goal:** Apply these techniques to REAL work and learn from the experience

---

# Preview: Class 3

## Gemini AI Studio Deep Dive

Topics:
- System instructions and saved prompts
- Meta-prompting (prompts that create prompts)
- Building your personal prompt library
- Saving and reusing templates

**Key Concept:**
> "All the techniques you learned today can be SAVED and REUSED in AI Studio. Next week you'll build systems, not just prompts."

---

# Additional Resources

**In this curriculum folder:**
- `/exercises/` - Detailed practice activities
- `/prompt-templates/` - Reusable templates
- `/student-examples/` - Real examples from students

**Online Resources:**
- Google's Gemini documentation (updated Oct 2025)
- Prompt engineering best practices
- AI Studio tutorials

**Keep practicing and refining your skills**

---

# End of Slides
