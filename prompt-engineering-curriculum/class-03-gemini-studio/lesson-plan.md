# Class 3: Detailed Lesson Plan

## 90-Minute Session: Gemini AI Studio Deep Dive + Meta-Prompting

### Pre-Class Setup (15 minutes before start)

**Technology Check:**
- [ ] Gemini AI Studio (aistudio.google.com) loaded and ready
- [ ] At least 2 example system instruction configurations pre-built
- [ ] Screen sharing/projector tested
- [ ] Regular Gemini (gemini.google.com) also available for comparison
- [ ] Student access to AI Studio verified (or sign-up process ready)
- [ ] Example meta-prompts prepared

**Materials Ready:**
- [ ] System instruction templates printed or shared digitally
- [ ] Model comparison guide accessible
- [ ] Prompt library organization template
- [ ] Meta-prompting examples
- [ ] Student homework from Classes 1 and 2 reviewed
- [ ] Troubleshooting guide for common AI Studio issues

**Room Setup:**
- [ ] Students need devices with screens large enough for AI Studio interface
- [ ] Backup plan ready if students can't access AI Studio immediately

---

## Minute-by-Minute Breakdown

### 0:00-0:05 | Welcome & Review (5 min)

**Objective:** Connect Class 3 to previous learning and establish the "building systems" mindset

**Script/Talking Points:**
> "Welcome back! In Class 1, you learned to write effective prompts. In Class 2, you learned advanced techniques for complex problems. Today's the game-changer: you're going to learn how to BUILD SYSTEMS that work for you every single day, across all your subjects."

**Activities:**

1. **Quick Review** (2 min)
   - "Who's been using the techniques from Classes 1 and 2?"
   - "What's the most helpful prompt you've created so far?"
   - "Have you found yourself writing the SAME type of prompt over and over?"

2. **The Repetition Problem** (2 min)
   - "Raise your hand if you've typed the same role and context multiple times"
   - "What if you could save that perfect prompt setup and reuse it?"
   - "What if the AI could help you CREATE better prompts?"

3. **Today's Big Idea** (1 min)
   **From one-time prompts → reusable systems**

   - AI Studio = The advanced interface
   - System instructions = Persistent AI behavior
   - Meta-prompting = Prompts that create prompts
   - Prompt libraries = Your personal toolkit

**Check for Understanding:**
- "What's the difference between using a prompt once vs. building a system?"

**Differentiation Notes:**
- 7th grade: Emphasize "like saving your favorite settings in a game"
- 11th grade: "Like creating functions instead of repeating code"

---

### 0:05-0:20 | Gemini AI Studio Tour (15 min)

**Objective:** Students understand AI Studio's interface and key features

**Key Concept:** AI Studio gives you control over how the AI behaves, not just what it responds to

#### Part 1: Regular Gemini vs. AI Studio (4 min)

**Live Comparison:**

1. **Show Regular Gemini** (gemini.google.com)
   - Simple chat interface
   - Each conversation starts fresh
   - Great for quick questions
   - No control over model selection
   - Can't save configurations

2. **Show AI Studio** (aistudio.google.com)
   - Advanced configuration options
   - System instructions panel
   - Model selector (Pro, Flash, Flash-Lite)
   - Saved chat library
   - Structured output options
   - Temperature and safety settings

**Ask:** "When might you want the advanced features?"

**Examples:**
- Building reusable homework helpers
- Creating consistent study tools
- Working with long documents
- Needing specific response formats

---

#### Part 2: Interface Walkthrough (5 min)

**Guided Tour** (screen share and narrate):

**Left Sidebar:**
- "Chat" button - Start new conversations
- "Saved chats" - Access previous conversations
- "Prompt library" - Where you'll save your best prompts

**Main Chat Area:**
- Text input box (same as regular Gemini)
- Chat history
- Response quality (thumbs up/down)

**Right Panel (The Power Zone):**
- **System instructions** - Set persistent AI behavior
- **Model selection** - Choose Pro, Flash, or Flash-Lite
- **Run settings**:
  - Temperature (creativity vs. consistency)
  - Safety settings
  - Response length preferences
- **Advanced settings**:
  - JSON mode for structured outputs
  - Long context handling
  - Multimodal inputs

**Walk students through:** "Where is the system instructions box? Where do you select models?"

---

#### Part 3: Model Selection Guide (3 min)

**The Three Gemini 2.5 Models:**

**Display comparison:**

| Model | Best For | Speed | Use When |
|-------|----------|-------|----------|
| **2.5 Pro** | Complex reasoning, detailed analysis | Slower | Essay analysis, difficult problems, research |
| **2.5 Flash** | Most homework help | Fast | General studying, most subjects |
| **2.5 Flash-Lite** | Simple questions | Fastest | Quick facts, vocabulary, simple questions |

**Live Demonstration:**
Ask the same question to all three models:

**Question:** "Explain the concept of photosynthesis and how it connects to cellular respiration."

**Show:**
- Pro: Deep, detailed explanation with connections
- Flash: Solid explanation, good balance
- Flash-Lite: Quick, simplified answer

**Discuss:** "Which would you use for what type of homework?"

---

#### Part 4: Key Features Overview (3 min)

**Highlight these AI Studio capabilities:**

**1. System Instructions (today's focus)**
- Persistent prompts that apply to every message
- Save you from repeating context
- Create consistent AI behavior

**2. Saved Configurations**
- Save your system instructions + model choice
- Create templates for different subjects
- Reuse successful setups

**3. Long Context Window**
- Can process 1 million tokens
- Upload entire chapters or articles
- Great for research and analysis

**4. Structured Outputs (advanced)**
- Get responses in JSON format
- Useful for consistent formatting
- We'll touch on this briefly

**5. Multimodal**
- Upload images, diagrams, charts
- AI can analyze and explain visual content
- Great for science, math, history

**For today, we're focusing on #1 and #2** - the foundation of building systems.

---

**Check for Understanding:**
- "Which model would you use for studying for a difficult test?"
- "Where in AI Studio do you set system instructions?"
- "What's one advantage of AI Studio over regular Gemini?"

**Teaching Tip:** Have students open AI Studio and locate key features as you discuss them.

---

### 0:20-0:35 | System Instructions Deep Dive (15 min)

**Objective:** Students can create effective system instructions for different subjects

**Key Concept:** System instructions are like "programming" the AI's role and behavior for an entire conversation—or even multiple conversations.

#### Part 1: What Are System Instructions? (4 min)

**Explanation:**

System instructions are special prompts that:
- Apply to EVERY message in the conversation
- Define the AI's persistent role, expertise, and approach
- Set constraints and guidelines upfront
- Save you from repeating yourself
- Can be saved and reused

**Analogy:**
> "Think of regular prompts as giving someone specific directions for one trip. System instructions are like installing a GPS with your preferences already set—it knows your preferred routes, avoids highways, and always gives you time estimates. It applies those preferences to every trip."

**Live Demo:**

**Without System Instructions:**
```
Regular chat:
User: "Help me with algebra"
AI: [generic response]
User: "I'm a 9th grader and I want Socratic questions, not answers"
AI: [adjusts]
User: "Now help with the next problem"
AI: [might forget the approach]
User: [has to remind AI again]
```

**With System Instructions:**
```
System Instruction: "You are a patient algebra tutor for 9th grade students. Use the Socratic method—guide students with questions rather than giving answers. Keep explanations at grade level. Encourage showing work."

User: "Help me with this equation: 2x + 5 = 13"
AI: [Socratic response with questions]
User: "Now this one: 3x - 7 = 20"
AI: [continues same approach automatically]
```

**Show the difference live in AI Studio**

---

#### Part 2: Anatomy of Good System Instructions (5 min)

**The System Instruction Formula:**

**Core Components:**

1. **Role & Expertise**
   - Who should the AI be?
   - What expertise do they have?

2. **Audience & Context**
   - Who are you (grade level, background)?
   - What's the general purpose?

3. **Approach & Methodology**
   - How should the AI teach/help?
   - What teaching philosophy?

4. **Persistent Constraints**
   - What should AI NEVER do?
   - What guidelines must always apply?

5. **Format Preferences** (optional)
   - Preferred response structure
   - Length, style, tone

**Example Breakdown:**

```
You are an expert biology tutor specializing in high school students. [ROLE]

You work with 10th graders who are learning foundational biology concepts. [AUDIENCE]

Your teaching approach is to:
- Start with what students already know
- Use real-world analogies and examples
- Build understanding step-by-step
- Encourage students to make connections [METHODOLOGY]

Important constraints:
- Never provide complete answers to homework problems
- Always ask students to explain their thinking
- Keep explanations at 10th grade reading level
- Use gender-neutral language [CONSTRAINTS]

Format your responses with:
- Clear section headers
- Concrete examples
- Questions to check understanding [FORMAT]
```

**Show this in AI Studio** and test with a few biology questions

---

#### Part 3: Building Subject-Specific Systems (4 min)

**Class Activity: Build Together**

**Pick a student's subject** (math, history, English, science)

**Example: Math Homework Helper**

**Build live with class input:**

```
You are a patient and encouraging math tutor for [grade level] students.

You help students with [specific math course] homework by:
1. First asking students what they understand and where they're stuck
2. Breaking problems into smaller, manageable steps
3. Guiding with questions rather than solving problems directly
4. Encouraging students to show their work
5. Celebrating progress and effort

Important rules:
- NEVER solve problems for students—guide them to solve on their own
- Always ask "What do you think the next step is?" before explaining
- If a student is completely stuck, show ONE similar example, then have them try
- Use encouraging language and positive reinforcement
- Keep mathematical notation clear and properly formatted

When a student gets stuck:
- Ask what they've tried already
- Help them identify which concept or formula might apply
- Break the problem into smaller parts
- Guide them through reasoning, not just calculation
```

**Ask class:** "What should we add? What's missing?"

**Test the system instruction** with a sample math problem

---

#### Part 4: Saving and Organizing (2 min)

**Show students how to:**

1. **Save a system instruction:**
   - Write system instruction
   - Test it with a few messages
   - If it works well, name the chat
   - Save it to "Prompt library" with descriptive name
   - Example names: "Algebra Tutor - Grade 9", "Essay Brainstorming Coach", "Biology Study Partner"

2. **Reuse a system instruction:**
   - Open saved prompt from library
   - Click "Use in new chat"
   - System instruction carries over
   - Start new conversation with same setup

3. **Modify as needed:**
   - Can edit system instructions during conversation
   - Can create variations for different needs
   - Build a collection over time

**Show the workflow** in AI Studio

---

**Check for Understanding:**
- "What goes in system instructions vs. regular messages?"
- "Why save system instructions instead of retyping them?"
- "What's one system instruction you'd create for your homework?"

**Differentiation:**
- 7th grade: Provide template with blanks to fill
- 9th grade: Provide example, have them create similar
- 11th grade: Create from scratch with guidelines

---

### 0:35-0:50 | Meta-Prompting Strategies (15 min)

**Objective:** Students can use meta-prompting to create better prompts and prompt systems

**Key Concept:** Instead of just using AI to solve problems, use AI to help you communicate with AI better!

#### Part 1: What is Meta-Prompting? (3 min)

**Definition:**
Meta-prompting = Using AI to help you create, improve, or analyze prompts

**Why it's powerful:**
- AI understands what makes effective prompts
- Can help you design prompts for specific situations
- Identifies weaknesses in your prompts
- Generates templates for common tasks

**The Meta-Prompt Concept:**
> "Instead of asking: 'Help me with my essay'
> You ask: 'Help me create a prompt that will help me brainstorm for my essay'"

**The Ladder:**
- Level 1: Use AI to solve problems
- Level 2: Use AI to help you learn
- Level 3: Use AI to help you use AI better (META!)

**You're at Level 3 now.**

---

#### Part 2: Types of Meta-Prompts (6 min)

**Type 1: Prompt Generation**

**Use when:** You need to create a prompt for a new situation

**Example:**
```
I need to create a system instruction for Gemini AI Studio that will help me with chemistry homework. I'm a 10th grader studying chemical reactions, stoichiometry, and balancing equations.

Please generate a comprehensive system instruction that:
- Establishes the AI as a chemistry tutor
- Uses guided questioning instead of giving answers
- Includes safety about not doing homework for me
- Keeps explanations at my grade level

Format it as a complete system instruction I can copy directly into AI Studio.
```

**Live demo:** Show the AI generating a system instruction

---

**Type 2: Prompt Improvement**

**Use when:** You have a prompt that kind of works but could be better

**Example:**
```
I've been using this prompt for history homework:

"Act as a history teacher and help me understand the causes of the Civil War."

It's okay, but the responses are sometimes too broad or too simple. Can you analyze this prompt and suggest improvements? Then provide an improved version that:
- Gets more specific, targeted help
- Ensures appropriate depth for 11th grade
- Guides the AI to use primary sources when relevant
- Prevents overly simplistic explanations
```

**Live demo:** Show the AI analyzing and improving a prompt

---

**Type 3: Template Creation**

**Use when:** You need reusable prompts for similar situations

**Example:**
```
I frequently need help analyzing poems in my English class. Create a reusable template prompt that I can use for any poem analysis by filling in specific details.

The template should:
- Guide me through literary analysis (not just summarize)
- Ask about specific elements: imagery, metaphor, tone, theme, structure
- Help me develop my own interpretations
- Be appropriate for 9th grade literature

Format it with [BRACKETS] around the parts I'll customize for each poem.
```

**Live demo:** Show AI creating a fill-in-the-blank template

---

**Type 4: Prompt Diagnosis**

**Use when:** A prompt isn't working and you don't know why

**Example:**
```
I tried this prompt but got unhelpful results:

"Explain photosynthesis"

The AI gave me a super long, detailed explanation with college-level terminology. I just needed a clear, simple explanation for my 7th grade science homework.

What went wrong with my prompt? What should I change to get better results?
```

**Live demo:** Show AI diagnosing the problem (lack of context, no role, no constraints)

---

#### Part 3: Building a Meta-Prompt System (4 min)

**The Meta-Prompt Template for Creating System Instructions:**

**Share with students:**

```
I need to create a system instruction for Gemini AI Studio for [SUBJECT/PURPOSE].

Context about me:
- I'm a [GRADE] grade student
- I'm currently studying [TOPICS]
- My learning style is [VISUAL/STEP-BY-STEP/EXAMPLES-BASED/etc.]
- I need help with [SPECIFIC CHALLENGE]

Please create a comprehensive system instruction that establishes:
1. The AI's role and expertise
2. My grade level and context
3. The teaching approach that works best for me
4. Clear constraints about academic integrity (guide me, don't do work for me)
5. Preferred response format and style

Format the output as a complete system instruction I can paste directly into AI Studio's system instruction field.

After creating it, explain why you made specific choices and suggest when I might want to modify it.
```

**Test this meta-prompt** with a student's subject

---

#### Part 4: The Meta-Prompting Workflow (2 min)

**Share the process:**

**Step 1: Identify the need**
- What type of help do I need repeatedly?
- What prompt would I use over and over?

**Step 2: Use meta-prompting**
- Ask AI to help create the perfect prompt
- Provide context about your needs
- Request specific features

**Step 3: Test and refine**
- Try the generated prompt/system instruction
- See if it produces helpful results
- Ask AI to improve based on what didn't work

**Step 4: Save and reuse**
- Save successful prompts to AI Studio library
- Document what each one is for
- Build your collection over time

**This is how you become a prompt engineering expert.**

---

**Check for Understanding:**
- "What is meta-prompting?"
- "Give an example of when you'd use meta-prompting"
- "How is meta-prompting different from regular prompting?"

**Differentiation:**
- 7th grade: Focus on Type 1 (generation) and Type 3 (templates)
- 9th grade: Include all types, emphasize improvement
- 11th grade: Add diagnosis and optimization strategies

---

### 0:50-1:05 | Building Prompt Libraries (15 min)

**Objective:** Students understand how to organize and maintain effective prompt libraries

**Key Concept:** A well-organized prompt library becomes a powerful personal learning toolkit

#### Part 1: Why Build a Library? (3 min)

**The Problem:**
- You create great prompts, then forget them
- Can't remember which prompt worked for which situation
- Waste time recreating prompts you've already perfected
- Miss opportunities to reuse successful strategies

**The Solution: A Prompt Library**

**What is a prompt library?**
- Organized collection of prompts and system instructions
- Categorized by subject, purpose, or type
- Documented with notes about when to use each
- Regularly updated and refined
- Personal toolkit tailored to YOUR needs

**Benefits:**
- Save time (no recreation)
- Improve consistency
- Build on success
- Easy to share with study partners
- Track what works

**Analogy:**
> "Like having a well-organized toolbox—you know exactly which tool to grab for each job, and you add new tools as you discover needs."

---

#### Part 2: Library Organization Strategies (5 min)

**Method 1: By Subject**

```
My Prompt Library/
├── Math/
│   ├── Algebra Homework Helper
│   ├── Geometry Step-by-Step Solver
│   └── Math Test Practice Generator
├── Science/
│   ├── Biology Concept Explainer
│   ├── Chemistry Lab Report Guide
│   └── Physics Problem-Solving Coach
├── English/
│   ├── Essay Brainstorming Partner
│   ├── Grammar and Style Checker
│   └── Poetry Analysis Guide
└── History/
    ├── Document Analysis Helper
    ├── Timeline Builder
    └── Essay Thesis Developer
```

**When to use:** If you think "I need help with [subject]"

---

**Method 2: By Purpose/Function**

```
My Prompt Library/
├── Learning & Understanding/
│   ├── Concept Explainer (any subject)
│   ├── Socratic Questioner
│   └── Analogy Generator
├── Homework Help/
│   ├── Problem-Solving Guide
│   ├── Step-by-Step Breakdown
│   └── Work Checker
├── Writing & Essays/
│   ├── Brainstorming Partner
│   ├── Thesis Developer
│   ├── Outline Builder
│   └── Revision Coach
├── Test Prep/
│   ├── Practice Question Generator
│   ├── Study Guide Creator
│   └── Concept Reviewer
└── Research/
    ├── Source Analyzer
    ├── Note Organizer
    └── Synthesis Helper
```

**When to use:** If you think "I need to [do a specific task]"

---

**Method 3: Hybrid (Recommended)**

Combine both approaches:
- Main folders by subject
- Sub-folders by purpose within each subject
- Cross-reference where prompts work across subjects

---

**Show example in AI Studio:**
- How to name chats descriptively
- How to use folders/tags if available
- External documentation (Google Doc or Notes app) for prompts used outside AI Studio

---

#### Part 3: Documentation Best Practices (4 min)

**For each prompt in your library, document:**

**Essential Information:**
1. **Name:** Clear, descriptive
2. **Purpose:** When to use this prompt
3. **Subject/Grade:** What it's designed for
4. **The Prompt:** The actual system instruction or prompt text
5. **Model:** Which Gemini model works best

**Optional but Helpful:**
6. **Example Use:** Sample input/output
7. **Notes:** What makes this effective, when it works best, when NOT to use it
8. **Last Updated:** When you last refined it
9. **Variations:** Related prompts for different situations

**Template:**

```
NAME: Algebra Problem-Solving Coach

PURPOSE: Step-by-step guidance for solving algebra equations and word problems without giving direct answers

SUBJECT: Algebra 1 & 2 (Grades 8-10)

MODEL: Gemini 2.5 Flash

SYSTEM INSTRUCTION:
[The full system instruction text]

EXAMPLE USE:
Input: "Help me solve: 3(x + 4) = 2x + 20"
Output: [Shows Socratic questioning approach]

NOTES:
- Works great for equations and inequalities
- Less effective for word problems (see "Algebra Word Problem Helper" instead)
- Students sometimes need reminder to show their work

LAST UPDATED: October 2025

VARIATIONS:
- "Algebra Word Problem Helper" for application problems
- "Algebra Test Prep" for practice question generation
```

---

#### Part 4: Building Your First Library (3 min)

**Class Activity:**

**Students identify 5 prompts to include:**

1. Think about your current classes
2. What types of help do you need most often?
3. What prompts from Classes 1 and 2 worked really well?
4. What new situations require custom prompts?

**Common starter library (customize):**

**Core 5 for Most Students:**
1. **General Homework Helper** - Subject expert tutor (customize per subject)
2. **Writing Coach** - Essay and writing support
3. **Test Prep Generator** - Practice questions and review
4. **Concept Explainer** - When you don't understand something
5. **Work Checker** - Feedback on completed work (without giving answers)

**Choose your organization method** (by subject or by purpose)

**Start documenting** using the template

---

**Check for Understanding:**
- "Why is organization important for a prompt library?"
- "Which organization method would work best for you?"
- "What's one prompt you'd definitely include in your library?"

**Teaching Tip:** Show your own prompt library as an example

---

### 1:05-1:25 | Hands-On Practice Time (20 min)

**Objective:** Students create their personal prompt systems and library

**Key Concept:** Learning by doing—build your actual toolkit now

**Setup (2 min):**
- Students have AI Studio open
- Access to templates and examples
- Note-taking method ready
- Freedom to experiment

**Activities:**

#### Exercise Set 1: Create System Instructions (7 min)

**Task:** Build 2-3 subject-specific system instructions

**Process:**
1. Choose your most important subjects
2. Use meta-prompting OR build from scratch
3. Test each system instruction with actual homework
4. Refine based on responses
5. Save with descriptive names

**Success criteria:**
- System instruction produces helpful responses
- Maintains appropriate constraints (no answer-giving)
- Matches your grade level and learning style
- Named and saved in AI Studio

**Teacher support:**
- Circulate and help troubleshoot
- Highlight excellent examples
- Encourage testing and refinement
- Help students who are stuck

---

#### Exercise Set 2: Meta-Prompting Practice (6 min)

**Task:** Use meta-prompting to create or improve a prompt

**Options:**

**Option A: Create new**
Use the meta-prompt template to generate a system instruction for a subject you haven't covered yet

**Option B: Improve existing**
Take a prompt from Classes 1-2 and use meta-prompting to make it better

**Option C: Generate template**
Create a reusable template for a common task (like essay brainstorming)

**Success criteria:**
- Used meta-prompting effectively
- Generated useful output
- Tested the result
- Saved what works

---

#### Exercise Set 3: Build Your Library (7 min)

**Task:** Start organizing your personal prompt library

**Process:**
1. Decide on organization method (subject vs. purpose)
2. Gather prompts from Classes 1, 2, and today
3. Document each prompt using the template
4. Create structure (folders, doc, or spreadsheet)
5. Include at least 5 prompts

**Where to build:**
- AI Studio saved prompts
- Google Doc
- Notion page
- Notes app
- Spreadsheet
- Whatever works for you!

**Success criteria:**
- Clear organization system
- At least 5 documented prompts
- Includes essential information (name, purpose, prompt text)
- Easy to find and use

---

**For Fast Finishers:**
- Create advanced variations of system instructions
- Build prompts for specific teachers' styles
- Help classmates refine their systems
- Explore structured outputs (JSON mode)
- Test different models for same task

**For Struggling Students:**
- Use provided templates
- Start with just 2-3 prompts
- Focus on one subject
- Work with a partner
- Use meta-prompting to help

---

**Share Time (3 min at end):**
- 2-3 volunteers share a system instruction they created
- What works well about it?
- What did they learn?
- Quick peer feedback

---

**Teaching Tips:**
- Emphasize progress over perfection
- Celebrate creativity and experimentation
- Help students focus on what they'll actually use
- Encourage starting small and building over time
- Document great student examples for future classes

**Troubleshooting:**

**"System instruction isn't working"**
→ Check: Is it too long? Too vague? Test with specific questions

**"I don't know what prompts to create"**
→ Ask: What homework do you have this week? Start there

**"Can't access AI Studio"**
→ Use meta-prompting in regular Gemini to generate system instructions, save externally

**"My library feels overwhelming"**
→ Start with 3 prompts, add more gradually

---

### 1:25-1:30 | Wrap-Up & Homework (5 min)

**Objective:** Synthesize learning and establish ongoing practice

**Activities:**

#### Quick Recap (2 min)

**Ask students:**
- "What's one thing you built today that you'll actually use?"
- "What surprised you about AI Studio?"
- "How is system prompting different from what we did in Classes 1 and 2?"

**Reinforce key concepts:**
- AI Studio = advanced control and reusable systems
- System instructions = persistent AI behavior
- Meta-prompting = using AI to improve your AI use
- Prompt libraries = your personal learning toolkit
- **The shift from using to building is a big deal!**

---

#### Introduce Homework (2.5 min)

**Assignment: "Build Your Prompt System"**

**Due before Class 4:**

**Part 1: Expand Your Library (15-20 min)**
1. Create system instructions for at least 5 subjects/purposes
2. Test each one with real homework this week
3. Document in your chosen organization system
4. Refine based on what works

**Part 2: Meta-Prompting Practice (10 min)**
1. Choose one prompt that's not quite working
2. Use meta-prompting to analyze and improve it
3. Test the improved version
4. Document the before/after

**Part 3: Real-World Testing (Ongoing)**
1. Use your system instructions for actual homework
2. Note what works and what doesn't
3. Track time saved vs. creating new prompts each time
4. Come prepared to share your best system instruction

**Part 4: Reflection (5 min)**
Write 4-5 sentences about:
- Which system instruction was most helpful?
- How did meta-prompting change your approach?
- What will you add to your library next?
- How has your relationship with AI tools changed through these 3 classes?

**Expected time:** 30-35 minutes total

**Tips:**
- Focus on prompts you'll actually use
- Quality over quantity
- Test everything with real homework
- Don't be afraid to iterate and improve
- Save what works, delete what doesn't

---

#### Preview Class 4 (0.5 min)

**Next class: Integration & Application**
- Combining ALL techniques for complex projects
- Real-world applications across subjects
- Building your personal "AI learning partner" system
- Ethical use and academic integrity deep dive
- Long-term strategies for AI-enhanced learning

> "Class 4 is where everything comes together. You'll use the systems you built today in real academic projects. Bring your prompt library—you'll need it!"

---

**Questions & Dismissal** (optional if time)

---

## Post-Class Activities

**For Teachers:**

**Document:**
- Which system instructions resonated most?
- Common challenges with AI Studio access?
- Great student examples to save for future classes
- Meta-prompting strategies that worked best
- Organization methods students preferred

**Follow-up:**
- Share class's best system instructions (anonymized)
- Post additional meta-prompt examples
- Provide troubleshooting guide for common issues
- Prep Class 4 materials focusing on integration
- Create gallery of student prompt libraries (with permission)

**Support:**
- Offer office hours for students refining systems
- Check in on students who struggled with AI Studio access
- Share advanced resources for interested students

---

## Assessment Checkpoints

**During Class (informal):**
- Quality of system instructions created
- Effective use of meta-prompting
- Understanding of when to use which model
- Library organization logical and usable
- Can articulate difference between AI Studio and regular Gemini

**Homework (formal):**
- Library includes 5+ well-documented prompts
- System instructions tested and refined
- Meta-prompting applied effectively
- Reflection shows deeper understanding
- Evidence of real-world application

**Application (ongoing):**
- Students use saved configurations for homework
- Continuing to refine and expand library
- Sharing effective systems with peers
- Ready to integrate in Class 4

---

## Differentiation Summary

### 7th Grade Modifications
- Provide more templates and examples
- Focus on 3-4 core subjects
- Simpler system instructions
- Guided meta-prompting with fill-in templates
- More structured library organization
- Partner work encouraged
- Extra time for practice

### 9th Grade Approach
- Balance templates with independence
- 5-6 subjects in library
- More sophisticated system instructions
- Independent meta-prompting with support
- Choice of organization method
- Peer collaboration
- Standard timing

### 11th Grade Extensions
- Minimal templates, maximum creativity
- 6+ subjects, cross-disciplinary prompts
- Advanced system instructions with complex constraints
- Creative meta-prompting applications
- Sophisticated organization systems
- Explore structured outputs (JSON)
- Discussion of AI behavior and optimization theory
- Fast pace, more depth

---

## Backup Plans

**If AI Studio access fails:**
- Teach concepts using regular Gemini
- Create system instructions externally in docs
- Focus more on meta-prompting
- Build library in Google Doc instead
- Troubleshoot access as homework
- Provide screenshots of AI Studio interface

**If students finish early:**
- Explore structured outputs (JSON mode)
- Create multi-lingual system instructions
- Build cross-subject integrated systems
- Help peers refine their libraries
- Test advanced meta-prompting strategies
- Explore multimodal capabilities

**If running out of time:**
- Priority: System instructions (most important)
- Can reduce meta-prompting depth
- Library building can extend to homework
- Must ensure everyone creates at least one saved system instruction
- Compress sharing time

**If running ahead:**
- Deeper dive into model selection optimization
- Preview Class 4 integration concepts
- Advanced meta-prompting techniques
- Student presentations of systems
- Build collaborative class prompt library

---

## Key Reminders for Teachers

1. **This is a mindset shift** - From using to building. Some students will need help making this leap.

2. **Embrace imperfection** - First prompts won't be perfect. That's the point of iteration.

3. **Make it personal** - The best libraries are tailored to individual needs. Encourage customization.

4. **Test everything** - Every system instruction should be tested with real examples.

5. **Celebrate creativity** - Students will surprise you with innovative systems.

6. **Document successes** - Great student examples become teaching tools for future classes.

7. **Academic integrity** - Reinforce that systems should help learning, not enable shortcuts.

8. **It's a toolkit** - Libraries should grow and evolve over time, not be one-and-done.

---

**You're ready to teach! This class transforms students from AI users into AI system builders—a powerful upgrade in their learning toolkit.**
