# Class 1: Foundations + Role-Based Prompting

---

## Prompt Engineering for Students

**Class 1: Foundations + Role-Based Prompting**

Skills covered:
- Making AI useful for learning
- Techniques for real homework
- Immediately applicable methods

---

## The Frustration Cycle

Common AI interaction problems:
1. Vague question asked
2. Generic, unhelpful answer received
3. User frustration
4. Time wasted or task abandoned

---

## Example: The Vague Prompt

**Prompt:**
```
help with math
```

**AI Response:**
- Generic overview of math help
- Not specific to the problem
- Doesn't know user's level
- Not actionable

**Problem:** Insufficient specificity and context

---

## Example: The Effective Prompt

**Prompt:**
```
I'm a 9th grade student learning quadratic equations.
I understand how to solve them using the quadratic
formula, but I don't understand WHY the formula works
or where it comes from. Can you explain the concept
behind the quadratic formula without just showing me
how to use it?
```

**AI Response:**
- Tailored to user's level
- Addresses specific confusion
- Explains concepts, not just procedures
- Actionable and helpful

**Improvement factors:** Specificity, context, clear task definition

---

## What is Prompt Engineering?

**Definition:** The practice of crafting effective instructions for AI tools to get useful, accurate, and helpful responses.

**Core concepts:**
- Asking better questions
- Speaking AI's language
- Expert communication
- AI as learning partner

---

## Benefits

**Efficiency:**
- Faster help
- Less frustration
- More efficient studying

**Understanding:**
- AI adapts to your level
- Explanations match your comprehension
- Supports thinking, not just answers

**Versatility:**
- Any subject
- Any assignment
- Any AI tool

---

## Anatomy of a Good Prompt

### The Four Components (R.C.T.F.)

1. **ROLE** - Who should the AI be?
2. **CONTEXT** - What does the AI need to know?
3. **TASK** - What exactly do you want?
4. **FORMAT** - How should the response be structured?

---

## Component 1: ROLE

**Who should the AI be?**

Examples:
- "Act as a biology teacher..."
- "You are an expert writing tutor..."
- "Pretend you're a patient math coach..."

**Impact of roles:**
- Shapes AI's expertise
- Affects tone and approach
- Guides entire response
- Makes help more relevant

---

## Component 2: CONTEXT

**What does the AI need to know?**

Include:
- Your grade level
- What you already understand
- What you're struggling with
- The specific topic
- Assignment requirements

**Example:**
"I'm a 10th grader studying photosynthesis. I understand evaporation and condensation, but I'm confused about precipitation..."

---

## Component 3: TASK

**What exactly do you want?**

Be specific:
- Explain a concept
- Check my understanding
- Provide practice problems
- Give feedback on my work
- Help me outline an essay
- Break down a complex problem

**Comparison:**
- Vague: "help me"
- Specific: "explain why this concept works"

---

## Component 4: FORMAT

**How should the response be structured?**

Options:
- Step-by-step explanation
- Bullet points
- Questions to test understanding
- Analogies or examples
- Simple language
- Comparison chart

**Examples:**
- "Explain using an everyday analogy"
- "Give me 3 practice problems with explanations"

---

## Putting It All Together

### Labeled Example

```
[CONTEXT] I'm a 9th grade student learning quadratic equations.
[CONTEXT] I understand how to solve them using the quadratic formula,
[CONTEXT] but I don't understand WHY the formula works or where it comes from.
[TASK] Can you explain the concept behind the quadratic formula
[FORMAT] without just showing me how to use it?
```

**Note:** Role is implied (teacher/tutor)

---

## Practice: Identify the Components

```
Act as a history teacher helping a 10th grader. I'm writing
an essay about the causes of World War I. I know about the
assassination of Archduke Franz Ferdinand, but my teacher
says that's just the spark, not the underlying causes. Can you
explain the deeper causes in a way that helps me understand
how they all connected, maybe using a metaphor or analogy?
```

Components:
- **Role:** Act as a history teacher helping a 10th grader
- **Context:** Writing essay about WWI causes, knows about assassination, need underlying causes
- **Task:** Explain the deeper causes and their connections
- **Format:** Using a metaphor or analogy

---

## Role-Based Prompting

**Effects of role assignment:**
- AI adopts field's expertise
- Appropriate teaching style
- Suitable tone
- Relevant knowledge

Different roles = different help

---

## Common Learning Roles

### Subject Expert Roles
- "Act as a [subject] teacher for [grade level]"
- "You are a [subject] tutor"
- "Pretend you're a professor of [subject]"

### Learning Support Roles
- "Act as a patient study partner"
- "You are an encouraging learning coach"
- "Pretend you're a peer who's really good at [subject]"

### Specialized Roles
- "Act as a Socratic teacher who asks questions rather than giving answers"
- "You are a writing editor focused on clarity"
- "Pretend you're a test prep tutor"

---

## Role Comparison

### Scenario: Explain Photosynthesis

**Version 1 - No Role:**
"Explain photosynthesis"

**Version 2 - Generic Role:**
"Act as a biology teacher and explain photosynthesis to a 7th grader"

**Version 3 - Specific Role:**
"Act as a biology teacher who uses everyday analogies. I'm a 7th grader learning about photosynthesis. I understand that plants need sunlight and water, but I don't get what's actually happening in the plant. Explain photosynthesis using an analogy to something I'd recognize from daily life."

**Effectiveness:** Increases with role specificity

---

## Choosing the Right Role

### Decision Guide

| Need | Role |
|------|------|
| Concept explained | Subject teacher/tutor |
| Working on writing | Writing coach/editor |
| Studying for test | Test prep tutor |
| Want to think it through | Socratic teacher |
| Need encouragement | Patient coach/supportive partner |
| Want peer perspective | Peer who excels at subject |

---

## Context Engineering

**Context = background information the AI needs**

Include:
- Your grade/age level
- What you already know
- What you don't understand
- Your learning style preferences
- Assignment requirements
- Constraints or limitations

**Principle:** More context = more relevant help

---

## Why Context Matters

**Without proper context:**
- AI makes wrong assumptions
- Responses too basic or too advanced
- Generic, not personalized
- May not match assignment requirements

**With good context:**
- Tailored to your exact level
- Addresses your specific confusion
- Matches what you need
- Saves time and frustration

---

## Context Comparison

### Minimal Context
```
Act as a writing tutor. Help me with my essay
about climate change.
```

### Rich Context
```
Act as a writing tutor for high school students.
I'm a 10th grader writing a 5-paragraph persuasive
essay about climate change solutions. I've already
written my introduction and conclusion, but my body
paragraphs feel weak and repetitive. I need help
making my arguments stronger and more varied. Can
you suggest strategies for strengthening body
paragraphs without rewriting them for me?
```

**Result:** Rich context produces significantly more useful responses

---

## The Context Checklist

Before prompting, consider:

- [ ] What's my grade level?
- [ ] What have I already learned about this?
- [ ] What specifically am I struggling with?
- [ ] What kind of help do I need?
- [ ] Are there any requirements I need to mention?
- [ ] Do I want to understand concepts or practice skills?

**Guideline:** More context is usually better than less

---

## Adding Context - Practice

### Transform This Prompt

**Basic:**
```
Explain the water cycle
```

**Context to add:**
- Grade level?
- What you already know?
- Why you're learning it?
- Specific confusing part?
- How you learn best?

---

## Adding Context - Improved Version

```
Act as a science teacher. I'm a 6th grader learning
about the water cycle for an upcoming test. I understand
evaporation and condensation, but I'm confused about
precipitation and collection—I don't see how they're
different. Can you explain those two parts clearly and
show how they connect to the parts I already understand?
```

**Improvement:** Specific context enables targeted, useful response

---

## Refining Prompts

### When the Response Isn't Perfect

**Too complicated:**
→ "Explain that more simply" or "Use language for a [grade] grader"

**Too simple:**
→ "Can you go deeper into [specific part]?"

**Wrong format:**
→ "Can you show that as [desired format]?"

**Doesn't answer your question:**
→ Add more context about what you specifically need

**Note:** First prompts rarely perfect—refine and iterate

---

## Common Mistakes to Avoid

### Don't:
- Be too vague - "help with homework"
- Leave out your grade level
- Ask for answers without understanding
- Forget to specify what you already know
- Give up after one attempt

### Do:
- Be specific about what you need
- Include your level and context
- Ask for explanations and understanding
- Tell AI what you know and don't know
- Refine prompts based on responses

---

## Practice Exercises

### Exercise 1: Role-Based Prompts (7-8 min)
- Choose a subject
- Create a complete prompt
- Test in Gemini
- Refine if needed

### Exercise 2: Context Engineering (7-8 min)
- Use a real homework question
- Write with rich context
- Compare to previous approach

### Exercise 3: Multiple Subjects (5-6 min)
- Try 2-3 different subjects
- Save prompts that work

---

## Success Criteria

You're succeeding if:
- You get a response that helps you understand something
- The AI's response is at your level
- You can refine prompts when needed
- You have at least one prompt that really works for you

**Goal:** Helpful, not perfect

---

## Summary

### Key Concepts

**Four Components:** Role, Context, Task, Format (R.C.T.F.)

**Role-Based Prompting:** Assign AI specific expertise

**Context Engineering:** Make responses relevant to YOU

**Practice:** Skill improves with use

**Application:** These techniques work with real homework immediately

---

## Homework Assignment

### "Prompt Engineering in Action"

Over the next week:

1. Choose **3 different subjects** you're currently studying
2. Create a **role-based prompt** for each using today's techniques
3. **Test each prompt** in Google Gemini
4. **Screenshot or copy** both prompt and response
5. Write **2-3 sentences** about what worked and what didn't
6. Come to Class 2 **ready to share** one example

**Expected time:** 20-30 minutes

**Tip:** Use this FOR your homework, not as extra work

---

## Homework Tips

### Making the Most of Practice

**Do:**
- Use real homework assignments
- Experiment with different roles
- Note which prompts work best
- Save successful prompts for future use
- Try to understand WHY something worked or didn't

**Don't:**
- Worry about making prompts perfect
- Use AI to do work instead of understand
- Skip the reflection part
- Wait until right before Class 2

---

## Preview: Class 2

### Advanced Techniques

Class 2 topics:
- Multi-step prompting for complex problems
- Few-shot prompting with examples
- Negative prompting and constraints
- Combining techniques
- More hands-on practice

**Building on today's foundation**

---

## The Goal

**AI is your learning partner, not your replacement**

Skills you're developing:
- Make studying more efficient
- Deepen your understanding
- Work across all subjects
- Serve you for years to come

**Result:** Becoming a better learner, not just getting answers

---

## Academic Integrity

### Using AI Appropriately

**Appropriate:**
- Getting concepts explained
- Checking your understanding
- Generating practice problems
- Getting feedback on your thinking
- Learning more effectively

**Not Appropriate:**
- Having AI write your essays
- Getting answers without understanding
- Submitting AI work as your own
- Bypassing learning requirements

**When in doubt, ask your teacher**

---

## Quick Reference

### Prompt Template

```
[ROLE] Act as a [subject] teacher/tutor for [grade level]

[CONTEXT] I'm learning about [topic]. I understand [what
you know], but I'm confused about [what you don't know].

[TASK] Can you explain [specific question or concept]

[FORMAT] using [preferred format: analogy, steps, examples,
etc.]?
```

**Copy, customize, and use**

---

# End of Slides
