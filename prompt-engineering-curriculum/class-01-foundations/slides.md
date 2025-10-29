# Class 1: Foundations + Role-Based Prompting
## Presentation Slides

---

## Slide 1: Welcome!

# Prompt Engineering for Students

**Class 1: Foundations + Role-Based Prompting**

Today you'll learn:
- How to make AI actually useful for learning
- Techniques that work with your real homework
- Skills you can use immediately

---

## Slide 2: Quick Poll

### Have you used AI tools before?

**Show of hands:**
- Used ChatGPT or Gemini?
- Felt like AI didn't understand what you needed?
- Got an unhelpful or wrong answer?

**Today we fix that!**

---

## Slide 3: What We'll Cover Today

### 90-Minute Agenda

1. What is prompt engineering?
2. Anatomy of a good prompt
3. Role-based prompting
4. Live demonstrations
5. Context engineering
6. **Hands-on practice with YOUR homework**

---

## Slide 4: The Problem

### The Frustration Cycle

1. Ask AI a vague question
2. Get a generic, unhelpful answer
3. Get frustrated
4. Give up or waste time

**Sound familiar?**

---

## Slide 5: Bad Prompt Demo

### Example: The Vague Prompt

**Prompt:**
```
help with math
```

**AI Response:**
- Generic overview of math help
- Not specific to your problem
- Doesn't know your level
- Not actually helpful

**What's wrong here?**

---

## Slide 6: Good Prompt Demo

### Example: The Effective Prompt

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
- Tailored to your level
- Addresses your specific confusion
- Explains concepts, not just procedures
- Actually helpful!

**What made this better?**

---

## Slide 7: What is Prompt Engineering?

### Definition

**Prompt Engineering** is the practice of crafting effective instructions for AI tools to get useful, accurate, and helpful responses.

### Think of it as:
- Learning to ask better questions
- Speaking AI's language
- Becoming an expert communicator
- Getting AI to be your learning partner

---

## Slide 8: Why This Matters

### The Benefits

**Saves Time**
- Get good help faster
- Less frustration
- More efficient studying

**Deeper Understanding**
- AI adapts to your level
- Explains in ways you understand
- Helps you think, not just get answers

**Works for Everything**
- Any subject
- Any assignment
- Any AI tool

---

## Slide 9: Anatomy of a Good Prompt

### The Four Components

Every effective prompt has:

1. **ROLE** - Who should the AI be?
2. **CONTEXT** - What does the AI need to know?
3. **TASK** - What exactly do you want?
4. **FORMAT** - How should the response be structured?

**Remember: R.C.T.F.**

---

## Slide 10: Component 1 - ROLE

### Who should the AI be?

**Examples:**
- "Act as a biology teacher..."
- "You are an expert writing tutor..."
- "Pretend you're a patient math coach..."

**Why roles matter:**
- Shapes the AI's expertise
- Affects tone and approach
- Guides the entire response
- Makes help more relevant

---

## Slide 11: Component 2 - CONTEXT

### What does the AI need to know?

**Include:**
- Your grade level
- What you already understand
- What you're struggling with
- The specific topic
- Assignment requirements

**Example:**
"I'm a 10th grader studying photosynthesis. I understand evaporation and condensation, but I'm confused about precipitation..."

---

## Slide 12: Component 3 - TASK

### What exactly do you want?

**Be specific:**
- Explain a concept
- Check my understanding
- Provide practice problems
- Give feedback on my work
- Help me outline an essay
- Break down a complex problem

**Vague:** "help me"
**Specific:** "explain why this concept works"

---

## Slide 13: Component 4 - FORMAT

### How should the response be structured?

**Options:**
- Step-by-step explanation
- Bullet points
- Questions to test understanding
- Analogies or examples
- Simple language
- Comparison chart

**Example:**
"Explain using an everyday analogy"
"Give me 3 practice problems with explanations"

---

## Slide 14: Putting It All Together

### Labeled Example

```
[CONTEXT] I'm a 9th grade student learning quadratic equations.
[CONTEXT] I understand how to solve them using the quadratic
formula,
[CONTEXT] but I don't understand WHY the formula works or
where it comes from.
[TASK] Can you explain the concept behind the quadratic formula
[FORMAT] without just showing me how to use it?
```

**Note:** Role is implied (teacher/tutor)

---

## Slide 15: Practice Identification

### Find the Components

```
Act as a history teacher helping a 10th grader. I'm writing
an essay about the causes of World War I. I know about the
assassination of Archduke Franz Ferdinand, but my teacher
says that's just the spark, not the underlying causes. Can you
explain the deeper causes in a way that helps me understand
how they all connected, maybe using a metaphor or analogy?
```

**Can you identify:**
- Role?
- Context?
- Task?
- Format?

---

## Slide 16: Identification - Answer

```
[ROLE] Act as a history teacher helping a 10th grader.
[CONTEXT] I'm writing an essay about the causes of World War I.
[CONTEXT] I know about the assassination of Archduke Franz
Ferdinand,
[CONTEXT] but my teacher says that's just the spark, not the
underlying causes.
[TASK] Can you explain the deeper causes in a way that helps
me understand how they all connected,
[FORMAT] maybe using a metaphor or analogy?
```

---

## Slide 17: Role-Based Prompting

### The Power of Roles

**When you assign a role, the AI adopts:**
- That field's expertise
- An appropriate teaching style
- A suitable tone
- Relevant knowledge

**Different roles = different help**

---

## Slide 18: Common Learning Roles

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

## Slide 19: Role Comparison Demo

### Scenario: Explain Photosynthesis

**Version 1 - No Role:**
"Explain photosynthesis"

**Version 2 - Generic Role:**
"Act as a biology teacher and explain photosynthesis to a 7th grader"

**Version 3 - Specific Role:**
"Act as a biology teacher who uses everyday analogies. I'm a 7th grader learning about photosynthesis. I understand that plants need sunlight and water, but I don't get what's actually happening in the plant. Explain photosynthesis using an analogy to something I'd recognize from daily life."

**Which works best?**

---

## Slide 20: Choosing the Right Role

### Decision Guide

**Need concept explained?** → Subject teacher/tutor

**Working on writing?** → Writing coach/editor

**Studying for test?** → Test prep tutor

**Want to think it through?** → Socratic teacher

**Need encouragement?** → Patient coach/supportive partner

**Want peer perspective?** → Peer who excels at subject

---

## Slide 21: Context Engineering

### What is Context?

**Context is background information the AI needs to help YOU specifically:**
- Your grade/age level
- What you already know
- What you don't understand
- Your learning style preferences
- The assignment requirements
- Constraints or limitations

**More context = more relevant help**

---

## Slide 22: Why Context Matters

### The Difference Context Makes

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

## Slide 23: Context Comparison

### Minimal vs. Rich Context

**Minimal:**
```
Act as a writing tutor. Help me with my essay
about climate change.
```

**Rich:**
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

**Notice the difference in responses!**

---

## Slide 24: The Context Checklist

### Before Prompting, Ask Yourself:

- [ ] What's my grade level?
- [ ] What have I already learned about this?
- [ ] What specifically am I struggling with?
- [ ] What kind of help do I need?
- [ ] Are there any requirements I need to mention?
- [ ] Do I want to understand concepts or practice skills?

**Pro Tip:** More context is usually better than less!

---

## Slide 25: Adding Context - Practice

### Transform This Prompt

**Basic:**
```
Explain the water cycle
```

**What context would help?**
- Grade level?
- What you already know?
- Why you're learning it?
- Specific confusing part?
- How you learn best?

---

## Slide 26: Adding Context - Answer

### Improved Version

```
Act as a science teacher. I'm a 6th grader learning
about the water cycle for an upcoming test. I understand
evaporation and condensation, but I'm confused about
precipitation and collection—I don't see how they're
different. Can you explain those two parts clearly and
show how they connect to the parts I already understand?
```

**Much more helpful!**

---

## Slide 27: Live Demonstrations

### Your Turn to Guide!

**We'll build prompts together for:**
- Math problems you're working on
- Science topics you're studying
- History questions you have
- Writing assignments you're doing

**Process:**
1. Share what you're learning
2. Choose a role together
3. Add context together
4. Run the prompt
5. See the result!

---

## Slide 28: Refining Prompts

### When the Response Isn't Perfect

**Too complicated?**
→ "Explain that more simply" or "Use language for a [grade] grader"

**Too simple?**
→ "Can you go deeper into [specific part]?"

**Wrong format?**
→ "Can you show that as [desired format]?"

**Doesn't answer your question?**
→ Add more context about what you specifically need

**First prompts rarely perfect—refine and iterate!**

---

## Slide 29: Common Mistakes to Avoid

### Don't:

❌ Be too vague - "help with homework"
❌ Leave out your grade level
❌ Ask for answers without understanding
❌ Forget to specify what you already know
❌ Give up after one attempt

### Do:

✅ Be specific about what you need
✅ Include your level and context
✅ Ask for explanations and understanding
✅ Tell AI what you know and don't know
✅ Refine prompts based on responses

---

## Slide 30: Hands-On Practice Time!

### Your Turn! (25 minutes)

**Bring out your actual homework!**

**Exercise 1:** Role-Based Prompts (7-8 min)
- Choose a subject
- Create a complete prompt
- Test in Gemini
- Refine if needed

**Exercise 2:** Context Engineering (7-8 min)
- Use a real homework question
- Write with rich context
- Compare to your old approach

**Exercise 3:** Multiple Subjects (5-6 min)
- Try 2-3 different subjects
- Save prompts that work!

---

## Slide 31: Success Criteria

### You're Succeeding If:

✅ You get a response that helps you understand something

✅ The AI's response is at your level

✅ You can refine prompts when needed

✅ You have at least one prompt that really works for you

**Don't aim for perfect—aim for helpful!**

---

## Slide 32: Quick Recap

### What We Learned Today

**Four Components:** Role, Context, Task, Format

**Role-Based Prompting:** Assign AI expertise

**Context Engineering:** Make responses relevant to YOU

**Practice:** The more you prompt, the better you get

**Key Insight:** This works with your real homework, right now!

---

## Slide 33: Homework Assignment

### "Prompt Engineering in Action"

**Over the next week:**

1. Choose **3 different subjects** you're currently studying
2. Create a **role-based prompt** for each using today's techniques
3. **Test each prompt** in Google Gemini
4. **Screenshot or copy** both prompt and response
5. Write **2-3 sentences** about what worked and what didn't
6. Come to Class 2 **ready to share** one example

**Expected time:** 20-30 minutes

**This isn't extra work—use it FOR your homework!**

---

## Slide 34: Homework Tips

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

## Slide 35: Preview - Class 2

### What's Next?

**Class 2: Advanced Techniques**
- Multi-step prompting for complex problems
- Few-shot prompting with examples
- Negative prompting and constraints
- Combining techniques
- More hands-on practice!

**Building on today's foundation**

---

## Slide 36: Remember

### The Goal

**AI is your learning partner, not your replacement**

You're developing skills that will:
- Make studying more efficient
- Deepen your understanding
- Work across all subjects
- Serve you for years to come

**You're not just getting answers—you're becoming a better learner**

---

## Slide 37: Academic Integrity

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

**When in doubt, ask your teacher!**

---

## Slide 38: Questions?

### Before You Go

**Quick questions now**

**Longer questions:**
- Email me
- Office hours
- Discussion board

**Remember:**
- Homework due before Class 2
- Bring examples to share
- Keep practicing with real work

---

## Slide 39: You've Got This!

### Key Takeaway

**You just learned a skill that will make learning easier, more efficient, and more effective.**

**Start using it TODAY with your homework!**

### Resources Shared:
- Prompt templates
- Context checklist
- Role selection guide
- Exercise files

**See you in Class 2!**

---

## Slide 40: Quick Reference

### Prompt Template

```
[ROLE] Act as a [subject] teacher/tutor for [grade level]

[CONTEXT] I'm learning about [topic]. I understand [what
you know], but I'm confused about [what you don't know].

[TASK] Can you explain [specific question or concept]

[FORMAT] using [preferred format: analogy, steps, examples,
etc.]?
```

**Copy this! Customize it! Use it!**

---

# End of Slides

## Presenter Notes

### Timing Guide
- Slides 1-8: 15 minutes (intro and what is PE)
- Slides 9-16: 10 minutes (anatomy of prompts)
- Slides 17-20: 15 minutes (role-based prompting)
- Slides 21-26: 15 minutes (context engineering)
- Slides 27-28: 15 minutes (live demos - not on slides, showing Gemini)
- Slides 29-31: 25 minutes (hands-on practice)
- Slides 32-40: 5 minutes (wrap-up)

### Demonstration Slides
Slides 27-28 are cues to switch from slides to live Gemini demonstrations. Have Gemini ready to go in another window.

### Adaptation Tips
- Add your own examples relevant to your students
- Insert school-specific academic integrity policies
- Customize homework submission methods
- Adjust timing based on your class pace
- Add or remove slides as needed

### Visual Suggestions
If converting to presentation software:
- Use large, readable fonts
- Add visual examples of prompts
- Include screenshots of Gemini responses
- Use color coding for the four components
- Add icons or emoji sparingly for visual interest
- Keep text minimal—slides are talking points, not scripts
