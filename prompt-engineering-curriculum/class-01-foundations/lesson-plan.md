# Session 1: Foundations + Role-Based Prompting

## 90-Minute Learning Session

### Before You Start (Setup)

**What You'll Need:**
- Computer or device with internet access
- Access to Google Gemini (gemini.google.com)
- Note-taking method (digital or paper)
- Your actual homework or study materials
- About 90 minutes of focused time

**Optional:**
- Printouts of prompt templates (available in resources folder)
- Second screen or split-screen for following along

---

## Session Overview

By the end of this session, you'll be able to:
- Write effective prompts using the four-component framework
- Use role-based prompting to get better help from AI
- Add relevant context that makes responses useful for YOUR situation
- Apply these techniques to real homework immediately

---

## 0:00-0:05 | Introduction (5 min)

### What This Session Covers

You're about to learn a skill that makes AI tools actually useful for learning. Instead of getting generic, unhelpful responses, you'll learn how to get AI to give you the specific help you need for your level and situation.

**Important:** This is about learning skills and understanding concepts, not just getting answers. These techniques help you learn better and faster.

### Key Points

- You'll learn **4 classes** of prompt engineering techniques
- Everything you learn works across all AI tools (ChatGPT, Gemini, Claude, etc.)
- You'll practice with your real homework today
- Prompts rarely work perfectly the first time—iteration is part of learning
- Questions and experimentation are encouraged

---

## 0:05-0:15 | What is Prompt Engineering? (10 min)

### Concept: Communication with AI

Prompt engineering is how you communicate with AI to get useful results. Better prompts = better help.

### See the Difference

**Example 1: Vague Prompt**
```
help with math
```

**Response:** Generic, unhelpful—AI doesn't know what you need

**Example 2: Effective Prompt**
```
I'm a 9th grade student learning quadratic equations. I understand how to solve them using the quadratic formula, but I don't understand WHY the formula works or where it comes from. Can you explain the concept behind the quadratic formula without just showing me how to use it?
```

**Response:** Much more targeted and helpful

**Key question:** What made the second prompt better?

### Why Prompt Engineering Matters

- **Saves time** - Get good help faster
- **Deeper understanding** - AI can adapt to your exact level
- **Works for any subject** - Apply to math, science, history, writing, anything
- **Makes AI useful** - Turns frustrating experiences into helpful ones

### Definition

**Prompt engineering** is the practice of crafting effective instructions for AI. It's a skill you can learn and improve with practice.

---

## 0:15-0:25 | Anatomy of a Good Prompt (10 min)

### Concept: The Four Components

Every effective prompt has four parts: **Role, Context, Task, and Format** (R.C.T.F.)

### The Components

**ROLE:** Who should the AI be?
- "Act as a biology teacher"
- "You are an expert writing tutor"
- "Pretend you're a patient math coach"

**CONTEXT:** What does the AI need to know?
- Your grade level
- What you already understand
- What you're struggling with
- The specific topic
- Why you're learning it

**TASK:** What exactly do you want?
- Explain a concept
- Check your understanding
- Provide practice problems
- Give feedback on your work

**FORMAT:** How should the response be structured?
- Step-by-step explanation
- Bullet points
- Questions to test understanding
- Analogies or examples

### Example Breakdown

Here's how the components appear in a prompt:

```
[CONTEXT] I'm a 9th grade student learning quadratic equations.
[CONTEXT] I understand how to solve them using the quadratic formula,
[CONTEXT] but I don't understand WHY the formula works or where it comes from.
[TASK] Can you explain the concept behind the quadratic formula
[FORMAT] without just showing me how to use it?
```

Note: No explicit role stated, but "explain" implies a teacher/tutor role

### Practice: Identify Components

Look at this prompt and identify each component:

```
Act as a history teacher helping a 10th grader. I'm writing an essay about the causes of World War I. I know about the assassination of Archduke Franz Ferdinand, but my teacher says that's just the spark, not the underlying causes. Can you explain the deeper causes in a way that helps me understand how they all connected, maybe using a metaphor or analogy?
```

**Components:**
- **Role:** History teacher
- **Context:** 10th grade, essay assignment, knows about assassination, needs deeper understanding
- **Task:** Explain deeper causes and their connections
- **Format:** Use metaphor or analogy

**Memory tip:** R.C.T.F. = Role, Context, Task, Format

---

## 0:25-0:40 | Role-Based Prompting (15 min)

### Concept: Assigning Expertise

Assigning AI a specific role shapes its entire response—knowledge level, tone, approach, and teaching style.

### Why Roles Matter

When you assign a role, the AI adopts that expertise and teaching style. Different roles work for different needs, and you can be creative with combinations.

### Common Roles for Learning

**Subject Expert Roles:**
- "Act as a [subject] teacher for [grade level]"
- "You are a [subject] tutor"
- "Pretend you're a professor of [subject]"

**Learning Support Roles:**
- "Act as a patient study partner"
- "You are an encouraging learning coach"
- "Pretend you're a peer who's really good at [subject]"

**Specialized Roles:**
- "Act as a Socratic teacher who asks questions rather than giving answers"
- "You are a writing editor focused on clarity"
- "Pretend you're a test prep tutor"

### Demonstration: Role Comparison

**Scenario:** Explaining photosynthesis

**Prompt 1** (No role):
```
Explain photosynthesis
```
Result: Probably textbook-like and generic

**Prompt 2** (Generic teacher role):
```
Act as a biology teacher and explain photosynthesis to a 7th grader
```
Result: More appropriate level

**Prompt 3** (Specific role):
```
Act as a biology teacher who uses everyday analogies. I'm a 7th grader learning about photosynthesis. I understand that plants need sunlight and water, but I don't get what's actually happening in the plant. Explain photosynthesis using an analogy to something I'd recognize from daily life.
```
Result: Much more engaging and understandable

**Key question:** Which explanation helps you understand best? Why?

### Choosing the Right Role

**Decision Guide:**
- Need concept explained? → Subject teacher/tutor
- Working on writing? → Writing coach/editor
- Studying for test? → Test prep tutor
- Want to think it through? → Socratic teacher
- Need encouragement? → Patient coach/supportive partner
- Want peer perspective? → Peer who excels at subject

**Tip:** You can always refine the role in follow-up prompts!

---

## 0:40-0:55 | Live Practice with Your Subjects (15 min)

### Concept: These techniques work for real homework, right now

### Exercise: Build Prompts for Your Work

**Step 1: Identify Your Need (2 min)**
- What are you currently learning in your classes?
- What homework or study material do you have right now?
- Pick 2-3 topics where you need help

**Step 2: Build a Prompt Together (10 min)**

For each topic, follow this process:

**Example: "I don't understand slope in algebra"**

**Build your prompt:**
```
[ROLE] Act as a patient math tutor
[CONTEXT] I'm an 8th grader learning about slope in algebra.
[CONTEXT] I know slope has something to do with lines going up or down,
[CONTEXT] but I don't understand what the numbers mean or how to calculate it.
[TASK] Explain what slope really means conceptually,
[FORMAT] then show me a simple example with an explanation of each step.
```

**Test it:** Copy this into Gemini and see the response

**Step 3: Refine Based on Response (3 min)**

If the response isn't quite right:
- Too complex? → "Explain that more simply"
- Too simple? → "Can you go deeper into [specific part]?"
- Wrong format? → "Can you show that as [desired format]?"

### Practice Tips

- Use REAL homework when possible
- If prompts don't work perfectly, that's normal—refine them
- Save prompts that work well for future use
- Try different roles to see what works best for you

---

## 0:55-1:10 | Context Engineering (15 min)

### Concept: Context makes AI responses relevant to YOUR specific situation

Context is background information the AI needs to give you helpful, personalized responses.

### What is Context?

**Context includes:**
- Your grade/age level
- What you already know
- What you don't understand
- Your learning style preferences
- The assignment requirements
- Constraints or limitations

**Why context matters:**
- AI doesn't know you automatically
- Wrong assumptions = unhelpful responses
- More context = more relevant help
- Context prevents AI from doing work for you

### Demonstration: Context Comparison

**Scenario:** Help with an essay

**Minimal Context:**
```
Act as a writing tutor. Help me with my essay about climate change.
```
Result: Probably generic, may not match your needs

**Rich Context:**
```
Act as a writing tutor for high school students. I'm a 10th grader writing a 5-paragraph persuasive essay about climate change solutions. I've already written my introduction and conclusion, but my body paragraphs feel weak and repetitive. I need help making my arguments stronger and more varied. Can you suggest strategies for strengthening body paragraphs without rewriting them for me?
```
Result: Much more targeted help

### The Context Checklist

Before prompting, ask yourself:
- [ ] What's my grade level?
- [ ] What have I already learned about this?
- [ ] What specifically am I struggling with?
- [ ] What kind of help do I need? (explanation, practice, feedback, etc.)
- [ ] Are there any requirements I need to mention? (word count, format, teacher expectations)
- [ ] Do I want to understand concepts or practice skills?

### Tips for Good Context

- More context is usually better than less
- Keep it relevant—don't include unnecessary details
- You can add context in follow-up messages
- Context builds throughout a conversation

### Practice: Adding Context

**Basic prompt:**
```
Explain the water cycle
```

**Think about:** What context would make this more helpful?

**Suggestions to add:**
- Grade level
- What you already know
- Why you're learning it (test, project, etc.)
- Specific part that's confusing
- How you learn best

**Improved version:**
```
Act as a science teacher. I'm a 6th grader learning about the water cycle for an upcoming test. I understand evaporation and condensation, but I'm confused about precipitation and collection—I don't see how they're different. Can you explain those two parts clearly and show how they connect to the parts I already understand?
```

---

## 1:10-1:35 | Hands-On Practice Time (25 min)

### Concept: Learning by doing—this is where skills solidify

### Your Turn: Apply All Techniques

You now have all the tools. Time to use them with your actual homework.

**Exercise Set 1: Role-Based Prompts (7-8 min)**

1. Choose a subject you're studying
2. Select an appropriate role
3. Write a complete prompt with role, context, task, format
4. Test it in Gemini
5. Evaluate the response
6. Refine and try again if needed

**Success = getting a response that helps you understand something**

---

**Exercise Set 2: Context Engineering (7-8 min)**

1. Take a question from your homework
2. Write a prompt with rich context
3. Test it
4. Compare to what you would have asked before this session

**Success = getting specifically tailored help**

---

**Exercise Set 3: Multiple Subjects (5-6 min)**

1. Try prompts for 2-3 different subjects
2. Notice how roles and context change
3. Save the prompts that work well

**Success = having prompts for multiple classes**

---

### Tips for Practice

- Don't get stuck on one prompt too long—move on and iterate
- "Good enough" prompts are fine—perfect is the enemy of done
- Make sure you get at least one successful prompt
- Experiment and learn what works for you

### Troubleshooting Common Issues

**"It's giving me the answer"**
→ Add: "Don't solve this for me, help me understand how to solve it"

**"The response is too complicated"**
→ Add: "Explain this like I'm [age/grade]" or "Use simpler language"

**"It's not understanding my question"**
→ Add more context about what specifically you need

**"I don't know what to ask"**
→ Use the templates as starting points

---

## 1:35-1:40 | Wrap-Up & Practice Assignment (5 min)

### What You Learned Today

**The four components:** Role, Context, Task, Format (R.C.T.F.)
- Role-based prompting assigns expertise
- Context makes responses relevant to you
- Prompting is a skill that improves with practice

### Practice Assignment: "Prompt Engineering in Action"

**Over the next week:**

1. Choose 3 different subjects you're currently studying
2. Create a role-based prompt for each subject using today's techniques
3. Test each prompt in Google Gemini
4. Screenshot or copy both the prompt and response
5. Write 2-3 sentences about what worked and what didn't
6. Be ready to share one example in Session 2

**Expected time:** 20-30 minutes

**Tips:**
- Use real homework—this isn't extra work, it's making your homework easier
- Don't worry about perfect prompts—focus on learning what works
- Save prompts that work well for future use
- If something doesn't work, try to figure out why

### What's Next

**Session 2: Advanced Techniques**
- Multi-step prompting for complex problems
- Few-shot prompting with examples
- Negative prompting for constraints
- Building on today's foundation

### Resources

All materials from today are available in the course folder:
- Prompt templates
- Role selection guide
- Context checklist
- R.C.T.F. summary

---

## Quick Reference

### The R.C.T.F. Framework

**Role:** Who should the AI be?
**Context:** What does the AI need to know about you and your situation?
**Task:** What exactly do you want the AI to do?
**Format:** How should the response be structured?

### Common Roles

- Subject teacher/tutor
- Patient study partner
- Socratic teacher (asks questions)
- Writing coach
- Test prep tutor
- Encouraging learning coach

### Context Must-Haves

- Grade level
- Current topic
- What you know vs. don't know
- What type of help you need
- Any specific requirements

---

**You're ready to start! Remember: The goal is to get help that makes you learn better. Start practicing with real homework and see how these techniques transform your experience with AI.**
