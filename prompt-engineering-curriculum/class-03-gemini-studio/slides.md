# Class 3: Gemini AI Studio Deep Dive + Meta-Prompting

---

## Gemini AI Studio Deep Dive + Meta-Prompting

From Using Prompts → Building Systems

Topics covered:
- Navigate Gemini AI Studio
- Create reusable prompt systems
- Use meta-prompting to create better prompts
- Build personal prompt library

---

## The Journey So Far

**Class 1: Foundations**
- The four components (Role, Context, Task, Format)
- Role-based prompting
- Context engineering

**Class 2: Advanced Techniques**
- Multi-step prompting
- Few-shot prompting
- Negative prompting and constraints

**Class 3 (Today): Building Systems**
- Moving from one-off prompts to reusable tools
- Creating personal AI learning toolkit

---

## The Repetition Problem

Common issue:
Repeatedly typing the same information:
- "Act as a math tutor..."
- "I'm a 9th grader learning..."
- "Don't give me the answer, guide my thinking..."

**Solution:** Save and systematize

Benefits:
- AI remembers preferences
- Build SYSTEMS instead of one-off prompts

---

## The Shift

**FROM:**
Individual prompts for individual problems
"Help me with this specific question"

**TO:**
Reusable systems for ongoing learning
"Here's my personal learning assistant for all algebra"

**Evolution:**
Consumer → Creator
User → Builder
Prompt → System

---

## What is Gemini AI Studio?

**Regular Gemini** (gemini.google.com)
- Simple chat interface
- Great for quick questions
- Each chat starts fresh
- No configuration options

**AI Studio** (aistudio.google.com)
- Advanced configuration
- System instructions
- Model selection
- Saved prompts and chats
- Structured outputs
- Long context (1M tokens)

**Analogy:** Gemini = Calculator | AI Studio = Scientific Calculator with programmable memory

---

## When to Use What?

**Use Regular Gemini for:**
- Quick questions
- Casual conversations
- Simple lookups
- One-off help

**Use AI Studio for:**
- Building reusable homework helpers
- Creating study systems
- Consistent assistance across subjects
- Long document analysis
- Specific response formats

---

## AI Studio Interface Components

**Left Sidebar:**
- New chat
- Saved chats
- Prompt library

**Main Area:**
- Chat interface
- Message history

**Right Panel (Configuration Zone):**
- System instructions
- Model selector
- Temperature & settings
- Advanced options (JSON mode, etc.)

---

## The Three Gemini 2.5 Models

**Gemini 2.5 Pro**
- Most powerful reasoning
- Best for complex analysis
- Slower but deepest
- Use for: Hard problems, essay analysis, research

**Gemini 2.5 Flash** (Most Common)
- Fast and capable
- Great balance
- Use for: Most homework, explanations, practice

**Gemini 2.5 Flash-Lite**
- Fastest responses
- Good for simple tasks
- Use for: Quick facts, vocabulary, simple questions

**Tip:** Start with Flash, move to Pro when stuck

---

## System Instructions Explained

**What are they?**
Special prompts that apply to EVERY message in the conversation

**What do they do?**
- Define the AI's persistent role
- Set lasting guidelines
- Establish constraints
- Save you from repeating yourself

**Analogy:**
Regular prompt = Give directions for one trip
System instruction = Program your GPS preferences for all trips

---

## Without System Instructions

Every message needs context:

```
You: "Help me with algebra"
AI: [generic response]

You: "I'm 9th grade, use Socratic method, don't give answers"
AI: [adjusts]

You: "Next problem"
AI: [might forget the approach]

You: [remind AI again]
```

**Issue:** Frustrating and repetitive

---

## With System Instructions

Set once, works forever:

**System Instruction:**
"You are a patient algebra tutor for 9th graders. Use Socratic questioning. Never give direct answers. Guide thinking with questions."

```
You: "Help with this: 2x + 5 = 13"
AI: [Socratic questions, grade-appropriate]

You: "Now this: 3x - 7 = 20"
AI: [same approach, automatically]

You: "And this..."
AI: [continues consistently]
```

**Result:** Consistent and efficient

---

## Anatomy of System Instructions

**5 Key Components:**

1. **Role & Expertise**
   - Who should the AI be?

2. **Audience & Context**
   - Who are you? (grade, background)

3. **Approach & Methodology**
   - How should the AI help?

4. **Persistent Constraints**
   - What should NEVER happen?

5. **Format Preferences** (optional)
   - Response structure and style

---

## System Instruction Example

```
You are an expert biology tutor for 10th grade students.

You work with students learning foundational biology concepts.

Your teaching approach:
- Start with what students know
- Use real-world analogies
- Build understanding step-by-step
- Encourage connections

Constraints:
- Never provide complete homework answers
- Ask students to explain their thinking
- Keep at 10th grade reading level
- Use gender-neutral language

Format:
- Clear section headers
- Concrete examples
- Check understanding with questions
```

---

## Building Subject-Specific Systems

**Math Helper Example:**

```
You are a patient math tutor for [grade] students.

Help with [course] homework by:
1. Asking what they understand and where they're stuck
2. Breaking problems into manageable steps
3. Guiding with questions, not solving
4. Encouraging work-showing
5. Celebrating progress

Rules:
- NEVER solve problems directly
- Always ask "What's the next step?" before explaining
- If completely stuck, show ONE example, then have them try
- Use encouraging language
- Keep notation clear
```

---

## Saving & Organizing

**How to save system instructions:**

1. Create system instruction
2. Test with real questions
3. If it works well, save the chat
4. Name it descriptively
5. Save to prompt library

**Example names:**
- "Algebra Tutor - Grade 9"
- "Essay Brainstorming Coach"
- "Biology Study Partner - Grade 10"
- "History Document Analyzer"

**Reusing:**
- Open from library
- Click "Use in new chat"
- Start fresh conversation with same setup

---

## What is Meta-Prompting?

**Definition:**
Using AI to help you create, improve, or analyze prompts

**The Levels:**
- Level 1: Use AI to solve problems
- Level 2: Use AI to help you learn
- Level 3: Use AI to help you use AI better (META)

**Why it's powerful:**
- AI understands effective prompts
- Can design prompts for specific situations
- Identifies weaknesses
- Generates templates

---

## Types of Meta-Prompts

**Type 1: Prompt Generation**
"Help me create a prompt for [situation]"

**Type 2: Prompt Improvement**
"This prompt works okay, but can you make it better?"

**Type 3: Template Creation**
"Create a reusable template for [task]"

**Type 4: Prompt Diagnosis**
"This prompt didn't work. What went wrong?"

---

## Meta-Prompt Example 1: Generation

**Goal:** Create a chemistry homework helper

**Meta-Prompt:**
```
I need to create a system instruction for Gemini AI Studio
for chemistry homework. I'm a 10th grader studying chemical
reactions and stoichiometry.

Create a comprehensive system instruction that:
- Establishes AI as chemistry tutor
- Uses guided questioning, not answers
- Includes academic integrity constraints
- Keeps explanations at grade level

Format as a complete system instruction I can copy
into AI Studio.
```

**Result:** AI generates a ready-to-use system instruction

---

## Meta-Prompt Example 2: Improvement

**Goal:** Improve existing prompt

**Meta-Prompt:**
```
I've been using this for history homework:

"Act as a history teacher and help me understand
the causes of the Civil War."

It's sometimes too broad or too simple. Analyze this
prompt and improve it to:
- Get more specific, targeted help
- Ensure 11th grade depth
- Use primary sources when relevant
- Prevent oversimplification
```

**Result:** AI analyzes weaknesses and provides improved version

---

## Meta-Prompt Example 3: Template

**Goal:** Create reusable template

**Meta-Prompt:**
```
I frequently analyze poems in English class. Create a
reusable template I can customize for any poem.

The template should:
- Guide literary analysis (not summarize)
- Cover imagery, metaphor, tone, theme, structure
- Help me develop my own interpretations
- Be appropriate for 9th grade

Format with [BRACKETS] for parts I'll customize.
```

**Result:** Fill-in-the-blank template for all poems

---

## The Meta-Prompting Workflow

**Step 1: Identify the need**
What help do I need repeatedly?

**Step 2: Use meta-prompting**
Ask AI to create the perfect prompt

**Step 3: Test and refine**
Try it, see if it works, improve

**Step 4: Save and reuse**
Add to library, use across subjects

**This is how experts work with AI.**

---

## Building Your Prompt Library

**What is a prompt library?**
Your organized collection of reusable prompts and system instructions

**Why build one?**
- Save time (no recreation)
- Improve consistency
- Build on success
- Easy to share
- Track what works

**Concept:** Toolbox where you know exactly which tool to grab for each job

---

## Library Organization: By Subject

```
My Prompt Library/
├── Math/
│   ├── Algebra Homework Helper
│   ├── Geometry Solver
│   └── Test Practice Generator
├── Science/
│   ├── Biology Explainer
│   ├── Chemistry Lab Guide
│   └── Physics Coach
├── English/
│   ├── Essay Brainstormer
│   ├── Grammar Checker
│   └── Poetry Analyzer
└── History/
    ├── Document Analyzer
    └── Timeline Builder
```

**Use when:** You think "I need help with [subject]"

---

## Library Organization: By Purpose

```
My Prompt Library/
├── Learning & Understanding/
│   ├── Concept Explainer
│   ├── Socratic Questioner
│   └── Analogy Generator
├── Homework Help/
│   ├── Step-by-Step Guide
│   └── Work Checker
├── Writing & Essays/
│   ├── Brainstormer
│   ├── Outline Builder
│   └── Revision Coach
└── Test Prep/
    ├── Practice Generator
    └── Study Guide Creator
```

**Use when:** You think "I need to [do a task]"

---

## Documenting Your Prompts

**For each prompt, document:**

**Essential:**
- Name (descriptive)
- Purpose (when to use)
- Subject/Grade
- The prompt text
- Which model works best

**Optional but helpful:**
- Example use case
- Notes on effectiveness
- When NOT to use it
- Last updated date
- Variations

---

## Documentation Template

```
NAME: Algebra Problem-Solving Coach

PURPOSE: Step-by-step guidance for solving algebra
without giving answers

SUBJECT: Algebra 1 & 2 (Grades 8-10)

MODEL: Gemini 2.5 Flash

SYSTEM INSTRUCTION:
[Full text here]

EXAMPLE USE:
Input: "Help me solve: 3(x + 4) = 2x + 20"
Output: [Shows Socratic approach]

NOTES:
- Great for equations
- Less good for word problems (see other prompt)
- Remind students to show work

LAST UPDATED: October 2025
```

---

## Your Starter Library

**Core 5 for Most Students:**

1. **General Homework Helper**
   Subject expert tutor (one per subject)

2. **Writing Coach**
   Essay and writing support

3. **Test Prep Generator**
   Practice questions and review

4. **Concept Explainer**
   When you don't understand something

5. **Work Checker**
   Feedback without giving answers

**Start here, expand over time**

---

## Building vs. Using - The Shift

**Before (Classes 1-2):**
- Create prompts for immediate needs
- Solve one problem at a time
- Focus on the homework in front of you

**Now (Class 3):**
- Build systems for ongoing needs
- Create tools that work repeatedly
- Focus on infrastructure for all future work

**This is a MAJOR upgrade in how you work with AI**

---

## The Power of Systems

**One-off prompt:**
Takes 3 minutes to write each time
Used once, then forgotten
Inconsistent results
Wasted effort recreating

**System:**
Takes 10 minutes to build once
Used hundreds of times
Consistent, reliable results
Compound returns on effort

**10 minutes now = Hours saved later**

---

## Practice Exercises

**Exercise 1: Create System Instructions (7 min)**
Build 2-3 subject-specific systems, test, save

**Exercise 2: Meta-Prompting Practice (6 min)**
Use meta-prompting to create or improve a prompt

**Exercise 3: Build Your Library (7 min)**
Start organizing your personal prompt collection

**Goal:** Leave today with working systems you'll actually use

---

## Academic Integrity Reminder

**Your systems should help you learn, not shortcut learning.**

**Good system instructions include:**
- "Guide my thinking, don't solve for me"
- "Ask questions rather than giving answers"
- "Help me understand, don't do my work"
- "Explain the concept, then let me practice"

**Remember:**
- AI is a learning partner, not a homework-doing machine
- Understanding > Answers
- Your teacher can tell when you didn't actually learn

**Build systems that make you smarter**

---

## Homework: Build Your System

**Part 1: Expand Library (15-20 min)**
- Create system instructions for 5+ subjects/purposes
- Test with real homework
- Document in your organization system
- Refine based on results

**Part 2: Meta-Prompting Practice (10 min)**
- Choose one not-quite-working prompt
- Use meta-prompting to improve it
- Test the improved version
- Document before/after

**Part 3: Real-World Testing (Ongoing)**
- Use your systems for actual homework this week
- Note what works and what doesn't
- Track time saved
- Come to Class 4 with your best system instruction

**Part 4: Reflection (5 min)**
Write 4-5 sentences:
- Which system was most helpful?
- How did meta-prompting change your approach?
- What will you add next?
- How has your AI relationship changed?

**Total time: 30-35 minutes**

---

## Preview: Class 4

**Integration & Application**

Bring everything together:
- Use ALL techniques for complex projects
- Real-world applications across subjects
- Build your "AI learning partner" methodology
- Ethical use and academic integrity deep dive
- Long-term strategies

**You'll need:**
- Your prompt library from today
- Examples of systems working (or not working)
- Current project or assignment to apply techniques to

---

## Key Takeaways

**Today you learned:**

1. **AI Studio** gives you advanced control
2. **System instructions** create persistent AI behavior
3. **Meta-prompting** helps you create better prompts
4. **Prompt libraries** organize your toolkit
5. **Building systems** is more powerful than using prompts

**The Shift:**
You're not just an AI user anymore.
You're an AI system builder.

---

## Remember

**Three Things:**

1. **Start small**
   3-5 core prompts, expand over time

2. **Test everything**
   Only save what actually works for you

3. **Keep learning**
   Your best system is the one you'll refine next week

**Your prompt library is a living toolkit, not a one-time project.**

---

# End of Slides
