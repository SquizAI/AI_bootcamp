# Class 3: Gemini AI Studio Deep Dive + Meta-Prompting

## Presentation Slides

---

## Slide 1: Welcome to Class 3

**Gemini AI Studio Deep Dive + Meta-Prompting**

From Using Prompts → Building Systems

**Today You'll Learn:**
- Navigate Gemini AI Studio like a pro
- Create reusable prompt systems
- Use meta-prompting to create better prompts
- Build your personal prompt library

---

## Slide 2: The Journey So Far

**Class 1:** Foundations
- The four components (Role, Context, Task, Format)
- Role-based prompting
- Context engineering

**Class 2:** Advanced Techniques
- Multi-step prompting
- Few-shot prompting
- Negative prompting and constraints

**Class 3 (Today):** Building Systems
- Moving from one-off prompts to reusable tools
- Creating your personal AI learning toolkit

---

## Slide 3: The Repetition Problem

**Have you noticed?**

You keep typing the same things:
- "Act as a math tutor..."
- "I'm a 9th grader learning..."
- "Don't give me the answer, guide my thinking..."

**Every. Single. Time.**

**What if you could save that?**

What if the AI remembered your preferences?

What if you could build SYSTEMS instead of one-off prompts?

---

## Slide 4: Today's Big Idea

**FROM:**
Individual prompts for individual problems
"Help me with this specific question"

**TO:**
Reusable systems for ongoing learning
"Here's my personal learning assistant for all algebra"

**The Shift:**
Consumer → Creator
User → Builder
Prompt → System

---

## Slide 5: What is Gemini AI Studio?

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

**Think:** Gemini = Calculator | AI Studio = Scientific Calculator with programmable memory

---

## Slide 6: When to Use What?

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

**Today = AI Studio Deep Dive**

---

## Slide 7: AI Studio Interface Tour

**Left Sidebar:**
- New chat
- Saved chats
- Prompt library

**Main Area:**
- Chat interface (familiar!)
- Message history

**Right Panel (THE POWER ZONE):**
- System instructions ⭐
- Model selector ⭐
- Temperature & settings
- Advanced options (JSON mode, etc.)

---

## Slide 8: The Three Gemini 2.5 Models

**Gemini 2.5 Pro**
- Most powerful reasoning
- Best for complex analysis
- Slower but deepest
- Use for: Hard problems, essay analysis, research

**Gemini 2.5 Flash** ⭐ Most Common
- Fast and capable
- Great balance
- Use for: Most homework, explanations, practice

**Gemini 2.5 Flash-Lite**
- Fastest responses
- Good for simple tasks
- Use for: Quick facts, vocabulary, simple questions

**Pro tip:** Start with Flash, move to Pro when stuck

---

## Slide 9: System Instructions Explained

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

## Slide 10: Without System Instructions

**Every message needs context:**

```
You: "Help me with algebra"
AI: [generic response]

You: "I'm 9th grade, use Socratic method, don't give answers"
AI: [adjusts]

You: "Next problem"
AI: [might forget the approach]

You: [remind AI again]
```

**Frustrating! Repetitive!**

---

## Slide 11: With System Instructions

**Set once, works forever:**

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

**Consistent! Efficient!**

---

## Slide 12: Anatomy of System Instructions

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

## Slide 13: System Instruction Example

```
You are an expert biology tutor for 10th grade students.

You work with students learning foundational biology
concepts.

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

## Slide 14: Building Subject-Specific Systems

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

## Slide 15: Saving & Organizing

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

## Slide 16: What is Meta-Prompting?

**Meta-Prompting:**
Using AI to help you create, improve, or analyze prompts

**The Levels:**
- Level 1: Use AI to solve problems
- Level 2: Use AI to help you learn
- Level 3: Use AI to help you use AI better ⭐ META!

**Why it's powerful:**
- AI understands effective prompts
- Can design prompts for specific situations
- Identifies weaknesses
- Generates templates

**You're becoming a Level 3 user!**

---

## Slide 17: Types of Meta-Prompts

**Type 1: Prompt Generation**
"Help me create a prompt for [situation]"

**Type 2: Prompt Improvement**
"This prompt works okay, but can you make it better?"

**Type 3: Template Creation**
"Create a reusable template for [task]"

**Type 4: Prompt Diagnosis**
"This prompt didn't work. What went wrong?"

---

## Slide 18: Meta-Prompt Example 1 - Generation

**You want to create a chemistry homework helper.**

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

**Result:** AI generates a ready-to-use system instruction!

---

## Slide 19: Meta-Prompt Example 2 - Improvement

**Your prompt is okay but not great.**

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

## Slide 20: Meta-Prompt Example 3 - Template

**You need reusable prompts for similar tasks.**

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

**Result:** Fill-in-the-blank template for all poems!

---

## Slide 21: The Meta-Prompting Workflow

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

## Slide 22: Building Your Prompt Library

**What is a prompt library?**
Your organized collection of reusable prompts and system instructions

**Why build one?**
- Save time (no recreation)
- Improve consistency
- Build on success
- Easy to share
- Track what works

**Think:** Toolbox where you know exactly which tool to grab for each job

---

## Slide 23: Library Organization - Method 1

**By Subject:**

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

## Slide 24: Library Organization - Method 2

**By Purpose/Function:**

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

## Slide 25: Documenting Your Prompts

**For each prompt, document:**

**Essential:**
- Name (descriptive!)
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

## Slide 26: Documentation Template

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

## Slide 27: Your Starter Library

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

**Start here, expand over time!**

---

## Slide 28: Building vs. Using - The Shift

**Before (Classes 1-2):**
- Create prompts for immediate needs
- Solve one problem at a time
- Focus on the homework in front of you

**Now (Class 3):**
- Build systems for ongoing needs
- Create tools that work repeatedly
- Focus on infrastructure for all future work

**This is a MAJOR upgrade in how you work with AI!**

---

## Slide 29: The Power of Systems

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

## Slide 30: Hands-On Practice - What You'll Do

**Exercise 1: Create System Instructions (7 min)**
Build 2-3 subject-specific systems, test, save

**Exercise 2: Meta-Prompting Practice (6 min)**
Use meta-prompting to create or improve a prompt

**Exercise 3: Build Your Library (7 min)**
Start organizing your personal prompt collection

**Goal:** Leave today with working systems you'll actually use

---

## Slide 31: Practice Tips

**Do:**
- Test everything with real homework
- Start simple, refine later
- Save what works
- Delete what doesn't
- Ask for help when stuck
- Experiment and iterate

**Don't:**
- Aim for perfection
- Create prompts you won't use
- Copy without customizing
- Give up after first try
- Overcomplicate

**Remember: Good enough systems you use > Perfect systems you don't**

---

## Slide 32: Common Challenges & Solutions

**"System instruction isn't working"**
→ Too long? Too vague? Test with specific examples

**"I don't know what prompts to create"**
→ What homework do you have this week? Start there

**"Can't access AI Studio"**
→ Create system instructions in regular Gemini, save externally

**"My library feels overwhelming"**
→ Start with 3 prompts. Add more gradually

**"Responses still aren't helpful"**
→ Use meta-prompting to diagnose the problem!

---

## Slide 33: Academic Integrity Reminder

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

**Build systems that make you smarter!**

---

## Slide 34: Real Student Success Stories

**Example 1: Math Student**
"I built a system instruction for calculus. Now instead of struggling alone for an hour, I get unstuck in 10 minutes AND understand what I'm doing. My test scores went up."

**Example 2: English Student**
"My essay brainstorming prompt saves me 30 minutes every time I have a writing assignment. I have better ideas and they're actually my own ideas, just better organized."

**Example 3: Multi-Subject Student**
"I have 6 saved systems in AI Studio, one for each class. It's like having a personal tutor for every subject who knows exactly how I learn."

**This could be you!**

---

## Slide 35: Homework - Build Your System

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

---

## Slide 36: Homework - Continued

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

## Slide 37: Preview - Class 4

**Next Class: Integration & Application**

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

## Slide 38: Key Takeaways

**Today you learned:**

1. **AI Studio** gives you advanced control
2. **System instructions** create persistent AI behavior
3. **Meta-prompting** helps you create better prompts
4. **Prompt libraries** organize your toolkit
5. **Building systems** is more powerful than using prompts

**The Shift:**
You're not just an AI user anymore.
You're an AI system builder.

**That's a serious upgrade!**

---

## Slide 39: Before You Go

**Three Things to Remember:**

1. **Start small**
   3-5 core prompts, expand over time

2. **Test everything**
   Only save what actually works for you

3. **Keep learning**
   Your best system is the one you'll refine next week

**Your prompt library is a living toolkit, not a one-time project.**

---

## Slide 40: You're Ready!

**You now have the skills to:**
- Navigate AI Studio confidently
- Create reusable learning systems
- Use meta-prompting to improve your prompts
- Build and maintain a personal prompt library
- Transform how you use AI for learning

**Class 1:** Learned to prompt
**Class 2:** Learned advanced techniques
**Class 3:** Learned to build systems

**Next:** Bring it all together for real-world success!

**Questions?**

---

## Additional Slides for Q&A or Extension

---

## Extension Slide 1: Advanced Features Preview

**JSON Mode / Structured Outputs**
Get responses in consistent, parseable formats

**Long Context Window**
Process entire textbooks (1M tokens)

**Multimodal**
Upload and analyze images, diagrams, videos

**Vibe Code**
Creative coding assistance

**Temperature Control**
Adjust creativity vs. consistency

**We focused on foundations today. Explore these as you advance!**

---

## Extension Slide 2: Optimization Tips

**System Instruction Optimization:**
- Be specific, not verbose
- Test with edge cases
- Update based on real use
- Version control (keep old versions)
- A/B test different approaches

**Library Management:**
- Review quarterly, delete unused
- Note most-used prompts
- Create variations for similar tasks
- Share with study partners
- Cross-reference related prompts

---

## Extension Slide 3: Collaboration Ideas

**With Study Partners:**
- Share effective system instructions
- Co-create prompts for shared classes
- Peer review each other's libraries
- Troubleshoot together
- Build class-wide prompt collection

**With Teachers:**
- Ask if they have recommendations
- Share what's working (with permission)
- Align with class expectations
- Get feedback on academic integrity
- Contribute to school AI guidelines

---

## Extension Slide 4: Model Selection Deep Dive

**When to use Pro:**
- Complex multi-part problems
- Deep analysis needed
- Research synthesis
- When Flash gives superficial answers
- Final paper review

**When to use Flash:** (Most Common)
- Regular homework help
- Study sessions
- Practice problems
- Concept explanations
- Test prep

**When to use Flash-Lite:**
- Quick factual lookups
- Vocabulary definitions
- Simple calculations
- When speed matters most
- Preliminary exploration

**Pro Tip:** Start with Flash, escalate to Pro if needed

---

## Extension Slide 5: Troubleshooting System Instructions

**Too Long?**
- Break into shorter, focused systems
- Remove redundant information
- Keep under 500 words if possible

**Too Vague?**
- Add specific examples of desired behavior
- Define key terms
- Be explicit about constraints

**Not Working?**
- Test with very specific questions
- Use meta-prompting to diagnose
- Start from scratch with clearer intent
- Check if regular prompting would work better

---

## Extension Slide 6: Your AI Learning Journey

**Phase 1 (Classes 1-2):** Learning to Communicate
Understanding how to talk to AI effectively

**Phase 2 (Class 3 - Today):** Building Infrastructure
Creating systems and tools

**Phase 3 (Class 4 - Next):** Integration & Mastery
Combining everything for real-world excellence

**Phase 4 (Beyond):** Continuous Improvement
Refining your practice over time

**You're in Phase 2. Almost there!**

---

## Backup Slide: If AI Studio Access Fails

**Don't worry! You can still build systems.**

**Alternative Approach:**
1. Create system instructions in a Google Doc
2. Use meta-prompting in regular Gemini
3. Save prompts in your preferred note-taking app
4. Copy/paste system instructions at start of chats
5. Set up AI Studio access later

**The concepts matter more than the tool.**
**You're learning system thinking—that's what counts.**

---

**End of Slide Deck**

---

## Presentation Notes for Teachers

### Timing Guide
- Slides 1-10: First 20 minutes (intro + AI Studio tour)
- Slides 11-20: Next 15 minutes (system instructions)
- Slides 21-30: Next 15 minutes (meta-prompting + libraries)
- Slides 31-40: Final 20 minutes (practice + homework)
- Extension slides: Use as needed for questions or advanced students

### Interactive Moments
- Slide 3: Show of hands - who's retyped the same prompt?
- Slide 8: Quick poll - which model have you used?
- Slide 16: Define "meta" together
- Slide 27: Students identify their core 5

### Live Demos
- Slide 11: Show without system instructions
- Slide 12: Show with system instructions (same questions)
- Slide 18: Run meta-prompt for generation
- Slide 19: Run meta-prompt for improvement

### Customization Notes
- Add your own examples in slides 18-20
- Replace slide 34 with your students' success stories (with permission)
- Adjust slide 27 (starter library) based on your students' subjects
- Add school-specific resources to extension slides

### Pacing Tips
- Can skip extension slides if short on time
- Slides 23-26 can be condensed if students grasp organization quickly
- Extend hands-on practice time by cutting presentation if needed
- Backup slide useful if tech issues arise

### Differentiation
- 7th grade: Spend more time on slides 11-15 (system instructions), provide templates
- 9th grade: Standard pace through all slides
- 11th grade: Faster through basics, extend time on slides 16-20 (meta-prompting)
