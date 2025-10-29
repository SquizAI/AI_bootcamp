# Session 2: Multi-Step & Advanced Prompting Techniques

## 90-Minute Learning Session

### Before You Start (Setup)

**What You'll Need:**
- Computer or device with internet access
- Access to Gemini 2.5 Flash or Pro (gemini.google.com)
- Your prompts from Session 1
- Actual homework with complex problems
- Note-taking method
- About 90 minutes of focused time

**Preparation:**
- Review the four components (R.C.T.F.) from Session 1
- Bring homework that has multi-step or complex requirements
- Have examples ready where you need specific formatting

---

## Session Overview

By the end of this session, you'll be able to:
- Break down complex problems using multi-step prompting
- Teach AI your preferred formats using few-shot examples
- Set boundaries with negative prompting and constraints
- Combine all techniques for sophisticated prompting

---

## 0:00-0:05 | Review & Introduction (5 min)

### Connect to Session 1

Last session you learned:
- Role-based prompting
- Context engineering
- The four components (R.C.T.F.)

**Key question:** What happens when you have a REALLY complex problem? Like a multi-part essay, or a math problem with 5 steps?

### Today's Challenge

You'll learn techniques for complex, sophisticated work:
- **Multi-step prompting** - Break down complex problems
- **Few-shot prompting** - Teach AI with examples
- **Negative prompting** - Tell AI what NOT to do
- **Combining techniques** - Use multiple strategies together

### Important Context

Gemini 2.5 can handle massive complexity—it can process a million tokens, which is basically an entire textbook. Today you'll learn to use that power effectively.

---

## 0:05-0:20 | Multi-Step (Chain-of-Thought) Prompting (15 min)

### Concept: Multi-step prompting breaks down complex problems

When a problem has multiple parts or requires sequential thinking, guide the AI through each step explicitly.

### The Problem with Simple Prompts

**Complex problem:** "Analyze the causes and effects of the Industrial Revolution on modern society, comparing economic, social, and environmental impacts."

**Simple prompt:**
```
Explain the Industrial Revolution's impact on modern society.
```

**Result:** Generic, unfocused, misses the complexity

**Key question:** What's wrong with this approach for a complex essay?

### The Multi-Step Solution

**Multi-step prompting** = Breaking a complex task into smaller, sequential steps and explicitly asking the AI to do each step.

### Two Approaches

**Approach 1: All steps in one prompt**
```
I need to write an essay analyzing the Industrial Revolution's impact on modern society.

Step 1: First, identify the three main economic changes from the Industrial Revolution.

Step 2: Then, identify three major social changes.

Step 3: Finally, identify three environmental impacts.

Step 4: For each category (economic, social, environmental), explain how those changes still affect us today.

Walk me through each step one at a time, and help me understand the connections.
```

**Approach 2: Prompt chaining (separate prompts)**
```
Prompt 1: "Help me identify the three most significant economic changes from the Industrial Revolution."
[Use response]

Prompt 2: "Now, using those economic changes, explain how each one specifically impacts modern economic systems today."
[Use response]

Prompt 3: "Next step: social changes..."
```

### When to Use Multi-Step

Use multi-step prompting when:
- Problem has distinct phases or parts
- Each step depends on the previous step
- You need to build understanding progressively
- The problem is too complex for one answer

**Examples by subject:**
- **Math:** "First factor, then apply formula, then simplify, then check"
- **Writing:** "First outline, then thesis, then body structure, then evidence selection"
- **Science:** "First hypothesis, then variables, then procedure, then analysis plan"
- **History:** "First identify causes, then effects, then connections, then modern implications"

### Practice: Build a Multi-Step Prompt

**Scenario:** "Write a lab report on our photosynthesis experiment."

**Multi-step structure:**
```
Act as a science teacher helping with lab reports.

I need to write a lab report on our photosynthesis experiment where we tested how different light colors affect plant growth.

Please guide me through this step-by-step:

Step 1: Help me write a clear hypothesis based on what we tested.

Step 2: Help me identify the independent variable, dependent variable, and control variables.

Step 3: Guide me in organizing my observations into a results section.

Step 4: Help me analyze what the results mean and whether they support my hypothesis.

Don't write it for me—help me think through each step.
```

**Try it:** Test this structure with your own complex homework

**Key question:** How is this different from just asking "help me write my lab report"?

---

## 0:20-0:35 | Few-Shot Prompting (15 min)

### Concept: Showing examples is often MORE effective than explaining in words

Few-shot prompting = Teaching AI what you want by showing examples rather than describing it.

### Zero-Shot vs Few-Shot Comparison

**Scenario:** You want Gemini to summarize articles in a specific style.

**Zero-Shot Attempt:**
```
Summarize this article about climate change in a concise style focusing on key facts.

[article text]
```
**Result:** Okay, but not exactly what you wanted

**Few-Shot Attempt:**
```
I want you to summarize articles in this specific style. Here are two examples:

Example 1:
Article: [article about renewable energy]
Summary: WHAT: Solar panel efficiency increased 20%. WHO: Research team at MIT. WHY IT MATTERS: Lower costs make solar competitive with fossil fuels.

Example 2:
Article: [article about ocean temperatures]
Summary: WHAT: Ocean temps rose 0.5°C since 2000. WHO: NOAA scientists. WHY IT MATTERS: Threatens coral reefs and marine ecosystems.

Now, please summarize this article in the same format:
[article text about climate change]
```
**Result:** Much more precisely formatted

**Key insight:** The examples SHOWED what you wanted instead of trying to explain it.

### Google's Recommendation

According to Google's official documentation (updated October 2025):

**"We recommend to always include few-shot examples in your prompts."**

### Why Examples Work

1. AI identifies patterns better than interpreting instructions
2. Shows format, tone, depth, style all at once
3. Reduces ambiguity
4. More consistent results

### The Few-Shot Formula

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

### Rules for Good Examples

**DO:**
- Use 2-4 examples (2-3 usually optimal)
- Keep formatting absolutely consistent
- Make examples similar to your actual task
- Show positive patterns (not anti-patterns)
- Include variety in content but consistency in structure

**DON'T:**
- Include too many examples (causes overfitting)
- Mix formats between examples
- Show what NOT to do (show what TO do)
- Use examples that are too different from your task

### Practice: Build a Few-Shot Prompt

**Task:** Getting AI to check math work in a specific format

```
Check my math work and respond in this format:

Example:
Problem: Solve: 2x + 5 = 13
Student work:
2x + 5 = 13
2x = 8
x = 8/2
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
✗ ERROR at Step 2
Steps: You added 7 instead of subtracting. Should be 3x = 27.
Correct answer: x = 9
Next practice: Be careful with your arithmetic when moving terms

Now check my work:
Problem: [student's actual problem]
Student work: [their work]
```

**Try it:** Create 2-3 examples for a task you need help with

---

## 0:35-0:50 | Negative Prompting & Constraints (15 min)

### Concept: Sometimes it's clearer to tell AI what NOT to do

Negative prompting = Telling the AI what NOT to do, rather than trying to describe everything you DO want.

### The Problem

**Prompt:**
```
Act as a biology tutor. Help me understand cellular respiration.
```

**Result:** Might give you the complete answer, write out the whole process for you, etc.

**Question:** For homework, you don't WANT the full answer—you want help understanding. How do we prevent that?

**Answer:** Use constraints and negative prompting

### Types of Constraints

**1. Academic Integrity Constraints**

These keep you learning rather than cheating:
```
"Don't give me the answer directly—help me figure it out"
"Don't solve this for me—guide my thinking with questions"
"Explain the concept, but don't do my work"
```

**2. Format Constraints**
```
"Keep your response under 100 words"
"Don't use bullet points—write in paragraphs"
"Respond in exactly 3 sentences"
```

**3. Scope Constraints**
```
"Don't go into advanced calculus—keep it at algebra level"
"Stay focused only on [specific aspect]—don't branch into related topics"
```

**4. Style Constraints**
```
"Don't use technical jargon—explain like I'm a 7th grader"
"Don't oversimplify—I need the full complexity"
```

### Strategic Placement of Constraints

**At the beginning** (sets expectations):
```
Act as a tutor who NEVER gives direct answers, only guides thinking through questions.

I need help with...
```

**At the end** (reinforces):
```
[your main prompt]

Important constraints:
- Don't solve the problem for me
- Don't use vocabulary above 9th grade level
- Keep response under 150 words
```

**Embedded throughout**:
```
Help me understand photosynthesis (explain the concept, don't just list steps)
by breaking it down (into 3-4 main phases, not exhaustive detail) in a way I
can remember (using analogy or metaphor, not technical descriptions).
```

### Combining Constraints with Other Techniques

**Multi-step + Few-shot + Constraints:**
```
I want you to check my essay thesis statements using this format:

Example:
Thesis: "Technology is important in modern life."
Feedback: TOO VAGUE. Specify which technology and what aspect of modern life.
Better: "Social media platforms have fundamentally changed how teenagers form and maintain friendships."

Example:
Thesis: "Shakespeare's Hamlet explores themes of revenge, madness, and mortality through the protagonist's internal conflict and relationships."
Feedback: STRONG. Specific, focused, arguable, and clear.

Now check my thesis—but DON'T rewrite it for me, just tell me what's weak and
what would make it stronger:

My thesis: [student's thesis]
```

**Try it:** Add constraints to prevent getting unhelpful responses

---

## 0:50-1:05 | Combining Techniques (15 min)

### Concept: Real academic work often requires multiple techniques together

### See the Power of Combination

**Level 1: Simple prompt**
```
Help me with my history essay about WWI causes.
```

**Level 2: Add role + context**
```
Act as a history teacher. I'm a 10th grader writing about WWI causes. I understand the assassination but not the deeper causes. Help me understand.
```

**Level 3: Add multi-step**
```
Act as a history teacher. I'm a 10th grader writing about WWI causes.

Step 1: Help me identify 3 underlying causes
Step 2: Help me understand how they created tension
Step 3: Help me connect them to the assassination trigger
```

**Level 4: Add few-shot**
```
[Role and context]

Here's the style of analysis I need:

Cause: Nationalism
How it created tension: Countries competed for dominance, created rival alliances
Connection to war: Made countries more willing to fight for their interests
Evidence: Examples of nationalist tensions

Now help me analyze these causes in that format:
[specific causes to analyze]
```

**Level 5: Add constraints**
```
[Everything above]

Important: Don't write the essay for me—help me build my own analysis.
Keep explanations at 10th grade level. Focus only on European theater.
```

**Key insight:** Each level improves the response

### Decision Framework

**How to choose which techniques to combine:**

**Start with:**
1. Role (almost always)
2. Context (almost always)

**Add based on task:**
- **Complex/multi-part?** → Multi-step
- **Specific format needed?** → Few-shot
- **Risk of unwanted responses?** → Constraints

**Decision Tree:**
```
Is the task simple and straightforward?
  └─ YES → Role + Context + Task might be enough
  └─ NO → Keep going...

Does it have multiple distinct steps?
  └─ YES → Add multi-step structure

Do you need a specific format or style?
  └─ YES → Add few-shot examples

Could AI give unhelpful responses (too detailed, too simple, wrong format)?
  └─ YES → Add constraints
```

### Real Practice Scenarios

**Scenario 1: Complex Math Problem**

"I need help solving a quadratic word problem but I keep getting lost in the setup."

**Suggested combination:**
- Role: Math tutor
- Multi-step: Break into steps (read, identify knowns/unknowns, set up equation, solve, check)
- Constraints: Don't solve for me, ask me questions at each step

---

**Scenario 2: Essay Brainstorming**

"I need to brainstorm for an argumentative essay on school start times."

**Suggested combination:**
- Role: Writing coach
- Few-shot: Show format for argument/counterargument/evidence
- Multi-step: First generate arguments, then counterarguments, then evaluate strength
- Constraints: Generate ideas, don't write the essay

---

**Scenario 3: Test Review**

"I'm studying for a biology test on ecosystems."

**Suggested combination:**
- Role: Biology tutor + quiz maker
- Few-shot: Show question format you want
- Constraints: Questions only from chapters 5-7, mix of difficulty levels

### Template Building

You can create TEMPLATES that combine techniques:

**Multi-Purpose Study Template:**
```
Act as a [subject] tutor who uses the Socratic method.

I'm studying [topic] for a [test/quiz/exam] covering [specific scope].

Here's the format I want for review questions:

Example:
Q: [Conceptual question]
If I answer: [My attempt]
Your response: [Guide me to correct understanding without telling me directly]

Generate 5 practice questions following this pattern.

Constraints:
- Difficulty level: [grade-appropriate]
- Only topics from: [specific chapters/sections]
- Mix conceptual and application questions
- Don't give me answers—help me think through them
```

---

## 1:05-1:25 | Hands-On Practice (20 min)

### Concept: Apply all techniques to real homework

### Exercise Set 1: Multi-Step (6-7 min)

Choose a complex assignment and write a multi-step prompt:
1. Identify the distinct phases
2. Write clear step labels
3. Add role and context
4. Test in Gemini 2.5
5. Refine based on response

**Success = Getting responses that help you learn and complete complex work**

---

### Exercise Set 2: Few-Shot (6-7 min)

Take a task where format matters:
1. Create 2-3 examples showing desired format
2. Ensure consistent structure
3. Add your actual task
4. Test and observe pattern recognition

**Success = Getting responses in exactly the format you need**

---

### Exercise Set 3: Combined Techniques (6-7 min)

Choose your most complex current assignment:
1. Decide which techniques it needs
2. Build a sophisticated prompt combining:
   - Role + Context
   - Multi-step OR Few-shot (or both)
   - Relevant constraints
3. Test and document what works

**Success = Getting sophisticated, tailored help that maintains learning**

---

### Tips for Practice

- Move quickly through exercises—iteration is key
- Focus on learning what works, not perfection
- Save successful prompts for your library
- Experiment with different combinations

### For Advanced Learners

- Create a reusable template for common assignments
- Try prompt chaining across multiple conversations
- Experiment with different example quantities
- Help others refine their prompts

---

## 1:25-1:30 | Wrap-Up & Practice Assignment (5 min)

### What You Learned Today

- **Multi-step** breaks down complexity
- **Few-shot** teaches patterns through examples
- **Constraints** maintain learning and prevent unwanted responses
- **Combining techniques** = power

### Practice Assignment: "Advanced Techniques in Action"

**Due before Session 3:**

1. **Choose 2 complex problems** from different subjects
2. **Problem 1:** Use multi-step prompting
   - Document each step
   - Screenshot the full conversation
3. **Problem 2:** Use few-shot prompting
   - Create 3 examples
   - Show your actual task
   - Screenshot the conversation
4. **For both:** Add appropriate constraints
5. **Reflection:** 3-4 sentences on:
   - Which technique worked better for which type of problem?
   - What was challenging?
   - What will you do differently next time?

**Expected time:** 30-40 minutes

### What's Next

**Session 3: Gemini AI Studio Deep Dive**
- System instructions and saved prompts
- Meta-prompting (prompts that create prompts!)
- Building your personal prompt library

All the techniques you learned today can be SAVED and REUSED in AI Studio. Next week you'll build systems, not just prompts.

---

## Quick Reference

### Multi-Step Prompting

Break complex tasks into sequential steps:
```
Step 1: [First phase]
Step 2: [Second phase]
Step 3: [Third phase]
```

### Few-Shot Formula

```
Example 1: [Input] → [Output]
Example 2: [Input] → [Output]

Now apply to: [Your task]
```

### Constraint Types

- Academic integrity: "Don't solve for me"
- Format: "Keep under 100 words"
- Scope: "Stay at [grade level]"
- Style: "No technical jargon"

### Decision Framework

1. Always start with Role + Context
2. Complex task? → Add multi-step
3. Specific format? → Add few-shot
4. Need boundaries? → Add constraints

---

**You're ready to tackle complex problems! Remember: Combining techniques lets you handle sophisticated academic work while maintaining true learning.**
