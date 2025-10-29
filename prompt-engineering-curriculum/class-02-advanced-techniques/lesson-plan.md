# Class 2: Detailed Lesson Plan

## 90-Minute Session: Multi-Step & Advanced Prompting Techniques

### Pre-Class Setup (15 minutes before start)

**Technology Check:**
- [ ] Gemini 2.5 Flash or Pro loaded and ready
- [ ] Screen sharing/projector tested
- [ ] Example complex problems prepared
- [ ] Student homework from Class 1 reviewed
- [ ] Comparison examples ready (simple vs advanced)

**Materials Ready:**
- [ ] Complex homework problems (math, science, writing)
- [ ] Few-shot example sets prepared
- [ ] Before/after prompt comparisons
- [ ] Template handouts (optional)

---

## Minute-by-Minute Breakdown

### 0:00-0:05 | Review & Introduction (5 min)

**Objective:** Connect to Class 1, set expectations for advanced techniques

**Activities:**

1. **Quick Review** (2 min)
   - "Last class: role-based prompting, context engineering, the four components"
   - "Who used those techniques on real homework? What worked?"
   - Quick show of hands for success stories

2. **The Challenge** (2 min)
   - "What happens when you have a REALLY complex problem?"
   - "Like a multi-part essay, or a math problem with 5 steps?"
   - "Today: techniques for complex, sophisticated work"

3. **Class 2 Overview** (1 min)
   - Multi-step prompting (break down complex problems)
   - Few-shot prompting (teach AI with examples)
   - Negative prompting (tell AI what NOT to do)
   - Combining all techniques

**Quick Context:**
> "We're using Gemini 2.5, which can handle WAY more complexity than you might think—it can process a million tokens, which is basically an entire textbook. Today you'll learn to use that power."

---

### 0:05-0:20 | Multi-Step (Chain-of-Thought) Prompting (15 min)

**Objective:** Students understand and can apply multi-step prompting to break down complex problems

**Key Concept:** When a problem has multiple parts or requires sequential thinking, guide the AI through each step explicitly.

#### Part 1: The Problem with Simple Prompts (3 min)

**Demo: The Failing Prompt**

Show a complex problem with a simple prompt that fails:

**Problem:** "Analyze the causes and effects of the Industrial Revolution on modern society, comparing economic, social, and environmental impacts."

**Simple Prompt:**
```
Explain the Industrial Revolution's impact on modern society.
```

**Show result:** Generic, unfocused, misses the complexity

**Ask class:** "What's wrong with this approach for a complex essay?"

---

#### Part 2: Introducing Multi-Step Prompting (5 min)

**Concept Explanation:**

Multi-step prompting = Breaking a complex task into smaller, sequential steps and explicitly asking the AI to do each step.

**Two Approaches:**

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

**Show both in action** with Gemini 2.5

---

#### Part 3: When to Use Multi-Step (3 min)

**Use multi-step prompting when:**
- Problem has distinct phases or parts
- Each step depends on the previous step
- You need to build understanding progressively
- The problem is too complex for one answer

**Examples by subject:**
- **Math:** "First factor, then apply formula, then simplify, then check"
- **Writing:** "First outline, then thesis, then body structure, then evidence selection"
- **Science:** "First hypothesis, then variables, then procedure, then analysis plan"
- **History:** "First identify causes, then effects, then connections, then modern implications"

---

#### Part 4: Building a Multi-Step Prompt Together (4 min)

**Class Activity:**

Pick a student's actual homework problem (or prepared example).

**Example:** "Write a lab report on our photosynthesis experiment."

**Build together:**
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

**Test in Gemini and show result**

**Ask:** "How is this different from just asking 'help me write my lab report'?"

---

**Check for Understanding:**
- "What makes a good candidate for multi-step prompting?"
- "Name the two approaches we learned"
- "When would you chain separate prompts vs. putting all steps in one?"

---

### 0:20-0:35 | Few-Shot Prompting (15 min)

**Objective:** Students can create effective few-shot prompts with appropriate examples

**Key Concept:** Showing the AI examples of what you want is often MORE effective than explaining in words.

#### Part 1: Zero-Shot vs Few-Shot Comparison (5 min)

**Live Demo:**

**Scenario:** You want Gemini to summarize articles in a specific style.

**Zero-Shot Attempt:**
```
Summarize this article about climate change in a concise style focusing on key facts.

[article text]
```

**Show result:** Okay, but not exactly what you wanted

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

**Show result:** Much more precisely formatted

**Discussion:** "Notice how the examples SHOWED what I wanted instead of me trying to explain it?"

---

#### Part 2: Google's Recommendation (3 min)

**Important Context:**

Share from research:
> "According to Google's official documentation (updated Oct 2025), few-shot prompts are **highly recommended** and often more effective than zero-shot. The docs literally say: 'We recommend to always include few-shot examples in your prompts.'"

**Why Examples Work:**
1. AI identifies patterns better than interpreting instructions
2. Shows format, tone, depth, style all at once
3. Reduces ambiguity
4. More consistent results

---

#### Part 3: Creating Effective Few-Shot Prompts (4 min)

**The Few-Shot Formula:**

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

**Rules for Good Examples:**

**DO:**
✅ Use 2-4 examples (2-3 usually optimal)
✅ Keep formatting absolutely consistent
✅ Make examples similar to your actual task
✅ Show positive patterns (not anti-patterns)
✅ Include variety in content but consistency in structure

**DON'T:**
❌ Include too many examples (causes overfitting)
❌ Mix formats between examples
❌ Show what NOT to do (show what TO do)
❌ Use examples that are too different from your task

---

#### Part 4: Class Example Building (3 min)

**Activity:** Build a few-shot prompt for a common student task

**Task:** Getting AI to check math work in a specific format

**Build together:**
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

**Test and show result**

---

**Check for Understanding:**
- "How many examples should you typically include?"
- "What's more important: the content of examples or the format consistency?"
- "When might few-shot be better than explaining in words?"

---

### 0:35-0:50 | Negative Prompting & Constraints (15 min)

**Objective:** Students can effectively use negative prompting and constraints to shape responses

**Key Concept:** Sometimes it's clearer to tell the AI what NOT to do than to try to describe everything you DO want.

#### Part 1: The Problem (3 min)

**Demo:**

**Prompt:**
```
Act as a biology tutor. Help me understand cellular respiration.
```

**Show result:** Might give you the complete answer, write out the whole process for you, etc.

**Problem:** "For homework, you don't WANT the full answer—you want help understanding. How do we prevent that?"

**Answer:** Use constraints and negative prompting

---

#### Part 2: Types of Constraints (5 min)

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

**Live Demo:** Show the same prompt with and without constraints

---

#### Part 3: Strategic Placement of Constraints (4 min)

**Where to put constraints:**

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

**Test examples** of each placement style

---

#### Part 4: Combining Constraints with Other Techniques (3 min)

**Powerful Combination:**

Multi-step + Few-shot + Constraints:
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

**Show result** - targeted feedback without doing the work

---

**Check for Understanding:**
- "Name three types of constraints"
- "Why are academic integrity constraints important?"
- "Can you over-constrain a prompt?"

---

### 0:50-1:05 | Combining Techniques (15 min)

**Objective:** Students see how to combine all techniques for sophisticated prompting

**Key Concept:** Real academic work often requires multiple techniques together.

#### Part 1: The Power of Combination (3 min)

**Show progression:**

**Level 1:** Simple prompt
```
Help me with my history essay about WWI causes.
```

**Level 2:** Add role + context
```
Act as a history teacher. I'm a 10th grader writing about WWI causes. I understand the assassination but not the deeper causes. Help me understand.
```

**Level 3:** Add multi-step
```
Act as a history teacher. I'm a 10th grader writing about WWI causes.

Step 1: Help me identify 3 underlying causes
Step 2: Help me understand how they created tension
Step 3: Help me connect them to the assassination trigger
```

**Level 4:** Add few-shot
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

**Level 5:** Add constraints
```
[Everything above]

Important: Don't write the essay for me—help me build my own analysis.
Keep explanations at 10th grade level. Focus only on European theater.
```

**Show how each level improves the response**

---

#### Part 2: Decision Framework (5 min)

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

---

#### Part 3: Real Student Scenarios (5 min)

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

---

#### Part 4: Template Building (2 min)

"You can create TEMPLATES that combine techniques:"

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

**Check for Understanding:**
- "Which techniques do you ALWAYS include?"
- "How do you decide which techniques to combine?"
- "Can you have too many techniques in one prompt?"

---

### 1:05-1:25 | Hands-On Practice (20 min)

**Objective:** Students apply all techniques to real homework

**Setup:**

Students work individually, teacher circulates to help.

**Exercise Progression:**

#### Exercise Set 1: Multi-Step (6-7 min)
Choose a complex assignment and write a multi-step prompt:
- Identify the distinct phases
- Write clear step labels
- Add role and context
- Test in Gemini 2.5
- Refine based on response

#### Exercise Set 2: Few-Shot (6-7 min)
Take a task where format matters:
- Create 2-3 examples showing desired format
- Ensure consistent structure
- Add your actual task
- Test and observe pattern recognition

#### Exercise Set 3: Combined Techniques (6-7 min)
Choose your most complex current assignment:
- Decide which techniques it needs
- Build a sophisticated prompt combining:
  - Role + Context
  - Multi-step OR Few-shot (or both)
  - Relevant constraints
- Test and document what works

**Success = Getting responses that actually help you learn and complete complex work**

**Teacher Activities:**
- Circulate and assist
- Highlight great examples
- Help troubleshoot
- Collect examples of excellent prompts
- Encourage peer helping

**For Fast Finishers:**
- Create a reusable template for common assignments
- Help a classmate refine their prompt
- Try prompt chaining across multiple conversations
- Experiment with different example quantities

---

### 1:25-1:30 | Wrap-Up & Homework (5 min)

**Quick Recap (2 min)**

Ask students:
- "What's one technique you'll definitely use this week?"
- "What surprised you about advanced prompting?"

Reinforce:
- Multi-step breaks down complexity
- Few-shot teaches patterns
- Constraints maintain learning
- Combining techniques = power

---

**Introduce Homework (2 min)**

**"Advanced Techniques in Action"**

Due before Class 3:

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

**Time estimate:** 30-40 minutes

---

**Preview Class 3 (1 min)**

Next class:
- Gemini AI Studio deep dive
- System instructions and saved prompts
- Meta-prompting (prompts that create prompts!)
- Building your personal prompt library

"All the techniques you learned today can be SAVED and REUSED in AI Studio. Next week you'll build systems, not just prompts."

---

**Questions** (optional if time)

---

## Post-Class Notes

**Document:**
- Which techniques resonated most with students?
- Common challenges encountered?
- Great student-created prompts to use as future examples
- Techniques that need more practice time

**Follow-up:**
- Share template doc with combined techniques
- Post resources for additional practice
- Offer office hours for homework help
- Prep Class 3 materials

---

## Differentiation Notes

### 7th Grade Adaptations
- Focus on 2-3 step prompts (not complex chains)
- Use 2 examples for few-shot
- Simpler constraints
- More structured templates
- More time for practice

### 9th Grade Approach
- 3-5 step prompts
- 2-4 examples for few-shot
- Multiple constraints
- Some template building
- Balance of guidance and independence

### 11th Grade Extensions
- Complex prompt chains
- Optimal example selection strategies
- Sophisticated constraint combinations
- Independent template creation
- Meta-discussions about prompt engineering theory

---

## Troubleshooting Guide

**"My multi-step prompt isn't working"**
- Check: Are steps truly sequential or actually parallel tasks?
- Try: Breaking into separate chained prompts
- Fix: Make step labels more explicit

**"Few-shot examples aren't being followed"**
- Check: Is formatting exactly consistent across all examples?
- Try: Starting with just 2 examples, very clearly formatted
- Fix: Make the pattern more obvious

**"Constraints are being ignored"**
- Check: Are constraints buried in middle of long prompt?
- Try: Placing constraints at the beginning or end
- Fix: Make them more explicit and direct

**"Combining too many techniques is confusing"**
- Start: With role + context + ONE advanced technique
- Build: Add complexity gradually
- Remember: Simple prompts that work > complex prompts that fail

---

**You're ready to teach! Remember: These techniques transform students from AI users into AI power users.**
