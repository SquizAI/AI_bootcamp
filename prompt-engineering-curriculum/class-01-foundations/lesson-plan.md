# Class 1: Detailed Lesson Plan

## 90-Minute Session: Foundations + Role-Based Prompting

### Pre-Class Setup (15 minutes before start)

**Technology Check:**
- [ ] Projector/screen sharing tested and working
- [ ] Google Gemini loaded and logged in
- [ ] Backup examples prepared and accessible
- [ ] Student devices ready with Gemini access
- [ ] Internet connection verified

**Materials Ready:**
- [ ] Slides.md content prepared for presentation
- [ ] Prompt templates accessible for sharing
- [ ] Example homework scenarios ready
- [ ] Student examples ready to show
- [ ] Note-taking method prepared (digital doc or whiteboard)

---

## Minute-by-Minute Breakdown

### 0:00-0:05 | Welcome & Introduction (5 min)

**Objective:** Set the tone, establish learning goals, address concerns

**Script/Talking Points:**
> "Welcome! Today you're learning a skill that will make AI tools actually useful for your learning. By the end of class, you'll be able to get better help with your homework than you ever thought possible—and you'll understand what you're learning, not just get answers."

**Activities:**
1. **Welcome** (1 min)
   - Introduce yourself and the class series
   - Quick overview: 4 classes, hands-on, immediately useful

2. **Poll the Room** (2 min)
   - "How many of you have used ChatGPT or Gemini before?"
   - "How many felt like the AI didn't really understand what you needed?"
   - "How many have had it give you an unhelpful or wrong answer?"

3. **Set Expectations** (2 min)
   - This is about learning skills, not just getting answers
   - We'll practice with your real homework
   - Mistakes are part of learning—prompts rarely work perfectly the first time
   - Questions are welcome throughout

**Differentiation Notes:**
- Younger students: Emphasize "learning superpower"
- Older students: Discuss efficiency and deeper understanding
- All ages: Address academic integrity upfront

---

### 0:05-0:15 | What is Prompt Engineering? (10 min)

**Objective:** Students understand what prompt engineering is and why it matters

**Key Concept:** Prompt engineering is how you communicate with AI to get useful results. Better prompts = better help.

**Activities:**

1. **The Bad Prompt Demo** (3 min)
   - Open Gemini on screen
   - Type a vague prompt: "help with math"
   - Show the generic, unhelpful response
   - Ask: "What's wrong with this interaction?"
   - Capture student observations

2. **The Good Prompt Demo** (3 min)
   - Type an improved prompt:
   ```
   I'm a 9th grade student learning quadratic equations. I understand how to solve them using the quadratic formula, but I don't understand WHY the formula works or where it comes from. Can you explain the concept behind the quadratic formula without just showing me how to use it?
   ```
   - Show the much better response
   - Ask: "What made this prompt better?"

3. **Define Prompt Engineering** (2 min)
   - "Prompt engineering is the practice of crafting effective instructions for AI"
   - It's a skill you can learn and improve
   - It works across all AI tools, not just Gemini
   - The better your prompts, the better your learning

4. **Why It Matters** (2 min)
   - Saves time—get good help faster
   - Deeper understanding—AI can adapt to your level
   - Works for any subject
   - Makes AI actually useful instead of frustrating

**Check for Understanding:**
- "In your own words, what is prompt engineering?"
- "Why do you think the second prompt worked better?"

**Differentiation:**
- 7th grade: Use simpler math example (fractions or percentages)
- 11th grade: Use more complex example (calculus or advanced chemistry)

---

### 0:15-0:25 | Anatomy of a Good Prompt (10 min)

**Objective:** Students can identify and use the four components of effective prompts

**Key Concept:** Every effective prompt has four parts: Role, Context, Task, and Format

**Activities:**

1. **Introduce the Four Components** (4 min)

   Display and explain:

   **ROLE:** Who should the AI be?
   - "Act as a biology teacher"
   - "You are an expert writing tutor"
   - "Pretend you're a patient math coach"

   **CONTEXT:** What does the AI need to know?
   - Your grade level
   - What you already understand
   - What you're struggling with
   - The specific topic

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

2. **Dissect the Good Prompt** (3 min)

   Show the earlier good prompt again and label parts:
   ```
   [CONTEXT] I'm a 9th grade student learning quadratic equations.
   [CONTEXT] I understand how to solve them using the quadratic formula,
   [CONTEXT] but I don't understand WHY the formula works or where it comes from.
   [TASK] Can you explain the concept behind the quadratic formula
   [FORMAT] without just showing me how to use it?
   ```

   Note: No explicit role (but "explain" implies teacher/tutor role)

3. **Practice Identification** (3 min)

   Show another prompt and have students identify components:
   ```
   Act as a history teacher helping a 10th grader. I'm writing an essay about the causes of World War I. I know about the assassination of Archduke Franz Ferdinand, but my teacher says that's just the spark, not the underlying causes. Can you explain the deeper causes in a way that helps me understand how they all connected, maybe using a metaphor or analogy?
   ```

   Ask students to identify:
   - Role: History teacher
   - Context: 10th grade, essay assignment, knows about assassination, needs deeper understanding
   - Task: Explain deeper causes and their connections
   - Format: Use metaphor or analogy

**Check for Understanding:**
- "What are the four components of a good prompt?"
- "Which component tells the AI who to be?"
- "Why do you think context is important?"

**Teaching Tip:** Write R.C.T.F. on the board as an acronym students can remember

---

### 0:25-0:40 | Role-Based Prompting Explained (15 min)

**Objective:** Students master role-based prompting and understand when to use different roles

**Key Concept:** Assigning AI a specific role shapes its entire response—knowledge, tone, approach, and helpfulness

**Activities:**

1. **Why Roles Matter** (3 min)
   - When you assign a role, the AI adopts that expertise and teaching style
   - Different roles for different needs
   - You can be creative with roles
   - Roles can be combined

2. **Common Roles for Learning** (4 min)

   Present and explain:

   **Subject Expert Roles:**
   - "Act as a [subject] teacher for [grade level]"
   - "You are a [subject] tutor"
   - "Pretend you're a professor of [subject]"

   **Learning Support Roles:**
   - "Act as a patient study partner"
   - "You are a encouraging learning coach"
   - "Pretend you're a peer who's really good at [subject]"

   **Specialized Roles:**
   - "Act as a Socratic teacher who asks questions rather than giving answers"
   - "You are a writing editor focused on clarity"
   - "Pretend you're a test prep tutor"

3. **Live Comparison Demo** (5 min)

   **Scenario:** Explaining photosynthesis

   **Prompt 1** (No role):
   ```
   Explain photosynthesis
   ```
   Show result—probably textbook-like

   **Prompt 2** (Generic teacher role):
   ```
   Act as a biology teacher and explain photosynthesis to a 7th grader
   ```
   Show result—more appropriate level

   **Prompt 3** (Specific role):
   ```
   Act as a biology teacher who uses everyday analogies. I'm a 7th grader learning about photosynthesis. I understand that plants need sunlight and water, but I don't get what's actually happening in the plant. Explain photosynthesis using an analogy to something I'd recognize from daily life.
   ```
   Show result—much more engaging and understandable

   **Discuss:** "Which explanation helped you understand best? Why?"

4. **Choosing the Right Role** (3 min)

   **Decision Guide:**
   - Need concept explained? → Subject teacher/tutor
   - Working on writing? → Writing coach/editor
   - Studying for test? → Test prep tutor
   - Want to think it through? → Socratic teacher
   - Need encouragement? → Patient coach/supportive partner
   - Want peer perspective? → Peer who excels at subject

   **Pro Tip:** You can always refine the role in follow-up prompts!

**Check for Understanding:**
- "What's an example of a role that would help with math homework?"
- "When might you want a Socratic teacher instead of a regular teacher?"
- "Can you think of a creative role for [student's current subject]?"

**Differentiation:**
- 7th grade: Focus on teacher/tutor/peer roles
- 9th grade: Introduce Socratic method concept
- 11th grade: Discuss combining roles and creating custom expert personas

---

### 0:40-0:55 | Live Demonstrations with Student Subjects (15 min)

**Objective:** Students see prompting techniques applied to their actual coursework

**Key Concept:** These techniques work for real homework, right now

**Activities:**

1. **Gather Student Scenarios** (3 min)
   - Ask: "What are you currently learning in your classes?"
   - Collect 3-4 diverse examples:
     - Math problem or concept
     - Science topic
     - History/social studies question
     - Writing assignment
   - Write them on board/screen

2. **Live Prompt Building** (10 min)

   For each scenario (2-3 min each):

   **Process:**
   a. Start with student's basic question
   b. Ask class: "What role should we use?"
   c. Ask class: "What context does the AI need?"
   d. Build the prompt together live
   e. Run it in Gemini
   f. Evaluate the response
   g. Refine if needed

   **Example Scenario:** "I don't understand slope in algebra"

   **Build together:**
   ```
   [ROLE] Act as a patient math tutor
   [CONTEXT] I'm an 8th grader learning about slope in algebra.
   [CONTEXT] I know slope has something to do with lines going up or down,
   [CONTEXT] but I don't understand what the numbers mean or how to calculate it.
   [TASK] Explain what slope really means conceptually,
   [FORMAT] then show me a simple example with an explanation of each step.
   ```

   Run it and discuss the response.

3. **Refinement Practice** (2 min)
   - Show how to refine based on AI response
   - If too complex: "Explain that more simply"
   - If too simple: "Can you go deeper into [specific part]?"
   - If wrong format: "Can you show that as [desired format]?"

**Teaching Tips:**
- Use real student homework when possible
- If response isn't good, show how to fix the prompt—this is valuable learning!
- Celebrate when prompts work well
- Move quickly to show variety

**Check for Understanding:**
- "What did we do to make that prompt work?"
- "How could we improve this prompt even more?"

---

### 0:55-1:10 | Context Engineering Basics (15 min)

**Objective:** Students understand how to provide helpful context and why it matters

**Key Concept:** Context is what makes AI responses relevant to YOUR specific situation

**Activities:**

1. **What is Context?** (3 min)

   **Context is background information the AI needs:**
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

2. **Context Comparison Demo** (5 min)

   **Scenario:** Help with an essay

   **Minimal Context:**
   ```
   Act as a writing tutor. Help me with my essay about climate change.
   ```
   Show result—probably generic, may not match needs

   **Rich Context:**
   ```
   Act as a writing tutor for high school students. I'm a 10th grader writing a 5-paragraph persuasive essay about climate change solutions. I've already written my introduction and conclusion, but my body paragraphs feel weak and repetitive. I need help making my arguments stronger and more varied. Can you suggest strategies for strengthening body paragraphs without rewriting them for me?
   ```
   Show result—much more targeted help

   **Discuss differences**

3. **The Context Checklist** (4 min)

   **Before prompting, ask yourself:**
   - [ ] What's my grade level?
   - [ ] What have I already learned about this?
   - [ ] What specifically am I struggling with?
   - [ ] What kind of help do I need? (explanation, practice, feedback, etc.)
   - [ ] Are there any requirements I need to mention? (word count, specific format, teacher expectations)
   - [ ] Do I want to understand concepts or practice skills?

   **Pro Tips:**
   - More context is usually better than less
   - But keep it relevant—don't include unnecessary details
   - You can add context in follow-up messages
   - Context builds throughout a conversation

4. **Practice: Adding Context** (3 min)

   Show basic prompt, have students suggest context to add:

   **Basic:**
   ```
   Explain the water cycle
   ```

   **Ask class:** "What context would make this more helpful?"

   **Collect suggestions:**
   - Grade level
   - What they already know
   - Why they're learning it (test, project, etc.)
   - Specific part that's confusing
   - How they learn best

   **Build improved version together:**
   ```
   Act as a science teacher. I'm a 6th grader learning about the water cycle for an upcoming test. I understand evaporation and condensation, but I'm confused about precipitation and collection—I don't see how they're different. Can you explain those two parts clearly and show how they connect to the parts I already understand?
   ```

**Check for Understanding:**
- "Why is context important?"
- "What's an example of useful context for [subject]?"
- "Can you have too much context?"

**Differentiation:**
- 7th grade: Focus on grade level and "what I know vs. don't know"
- 9th grade: Add learning style preferences
- 11th grade: Include assignment requirements and academic goals

---

### 1:10-1:35 | Hands-On Practice Time (25 min)

**Objective:** Students apply all learned techniques to their real homework

**Key Concept:** Learning by doing—this is where skills solidify

**Setup (2 min):**
- Students should have Gemini open
- Bring actual homework or study materials
- Have prompt templates accessible
- Encourage experimentation

**Activities:**

**Individual Practice** (20 min)

Students work through exercises at their own pace:

1. **Exercise Set 1: Role-Based Prompts** (7-8 min)
   - Choose a subject you're studying
   - Select an appropriate role
   - Write a complete prompt with role, context, task, format
   - Test it in Gemini
   - Evaluate the response
   - Refine and try again if needed

   **Success = getting a response that helps you understand something**

2. **Exercise Set 2: Context Engineering** (7-8 min)
   - Take a question from your homework
   - Write a prompt with rich context
   - Test it
   - Compare to what you would have asked before this class

   **Success = getting specifically tailored help**

3. **Exercise Set 3: Multiple Subjects** (5-6 min)
   - Try prompts for 2-3 different subjects
   - Notice how roles and context change
   - Save the prompts that work well

   **Success = having prompts for multiple classes**

**Teacher During This Time:**
- Circulate and observe student work
- Help students who are stuck
- Celebrate good prompts loudly
- Troubleshoot issues
- Take notes on common challenges
- Collect examples of great student prompts

**Extension for Fast Finishers:**
- Help a classmate improve their prompt
- Try a Socratic teacher role
- Create a prompt template for future use
- Test the same question with different roles

**Sharing Time** (3 min)
- Ask 2-3 volunteers to share a prompt that worked well
- Display it on screen
- Briefly discuss what made it effective
- Encourage peer recognition

**Teaching Tips:**
- Don't let students get stuck on one prompt too long—move on and iterate
- Emphasize that "good enough" prompts are fine—perfect is the enemy of done
- Make sure everyone gets at least one successful prompt
- Watch for students doing more complex work and highlight them

**Troubleshooting Common Issues:**

**"It's giving me the answer"**
→ Add: "Don't solve this for me, help me understand how to solve it"

**"The response is too complicated"**
→ Add: "Explain this like I'm [age/grade]" or "Use simpler language"

**"It's not understanding my question"**
→ Add more context about what specifically you need

**"I don't know what to ask"**
→ Use the templates as starting points

---

### 1:35-1:40 | Wrap-Up & Homework (5 min)

**Objective:** Solidify learning and set up practice between classes

**Activities:**

1. **Quick Recap** (2 min)

   **Ask students:**
   - "What's one thing you learned today?"
   - "What's one thing you'll do differently when using AI now?"

   **Reinforce key points:**
   - Four components: Role, Context, Task, Format
   - Role-based prompting assigns expertise
   - Context makes responses relevant to you
   - Prompting is a skill that improves with practice

2. **Introduce Homework** (2 min)

   **Assignment: "Prompt Engineering in Action"**

   Over the next week:
   1. Choose 3 different subjects you're currently studying
   2. Create a role-based prompt for each subject using today's techniques
   3. Test each prompt in Google Gemini
   4. Screenshot or copy both the prompt and response
   5. Write 2-3 sentences about what worked and what didn't
   6. Come to Class 2 ready to share one example

   **Expected time:** 20-30 minutes

   **Tips:**
   - Use real homework—this isn't extra work, it's making your homework easier
   - Don't worry about perfect prompts—focus on learning what works
   - Save prompts that work well for future use
   - If something doesn't work, try to figure out why

3. **Preview Class 2** (1 min)
   - Next class: Advanced techniques
   - Multi-step prompting for complex problems
   - Few-shot prompting with examples
   - Negative prompting for constraints
   - Building on today's foundation

4. **Questions & Dismissal** (< 1 min)
   - Quick questions only (detailed questions via email/office hours)
   - Remind about homework
   - Thank students for participation

**Post-Class:**
- Save any particularly good student prompts as examples for future classes
- Note what worked well and what to adjust
- Prepare follow-up resources for students who struggled
- Update student-examples folder with anonymized examples

---

## Assessment Checkpoints Throughout Class

**During Activities (informal assessment):**
- Monitor student responses during discussions
- Observe prompt quality during hands-on practice
- Note which concepts cause confusion
- Check that students can identify prompt components

**End of Class (quick check):**
- Students should be able to:
  - [ ] Name the four components of a good prompt
  - [ ] Write a role-based prompt
  - [ ] Add relevant context to a prompt
  - [ ] Get a helpful response from Gemini on their own

**Homework (formal assessment):**
- Evidence of applying techniques to multiple subjects
- Quality of reflection on what worked/didn't work
- Readiness to share and discuss in Class 2

---

## Materials to Share with Students

**After class, provide:**
- [ ] Link to prompt-templates folder
- [ ] Summary of four components (R.C.T.F.)
- [ ] Role selection guide
- [ ] Context checklist
- [ ] Homework instructions
- [ ] Your contact info for questions

**Optional:**
- Record the live demonstrations for students to review
- Create a shared document for students to post their best prompts
- Set up a discussion board for prompt troubleshooting

---

## Differentiation Notes by Grade Level

### 7th Grade Modifications
- Use more straightforward examples
- Provide more structured templates
- Allow extra time for hands-on practice
- Partner students for support
- Focus on concrete, familiar subjects

### 9th Grade Approach
- Balance structure with independence
- Encourage experimentation
- Introduce light theoretical discussion
- Allow peer teaching opportunities
- Use grade-appropriate complexity in examples

### 11th Grade Extensions
- Move faster through basics
- Encourage sophisticated prompt design
- Discuss meta-cognition and learning science
- Challenge them to create original templates
- Connect to college and career readiness

---

## Backup Plans

**If technology fails:**
- Have printed examples of prompts and responses
- Do a "think-pair-share" prompt-writing exercise on paper
- Discuss and plan prompts to try later
- Use the time for deeper discussion of concepts

**If students finish early:**
- Advanced role combinations
- Create templates for classmates
- Help peers troubleshoot
- Explore different types of tasks (summarize, analyze, create practice problems)

**If running out of time:**
- Priority: Ensure role-based prompting is solid
- Can skip some demos and assign as homework
- Can shorten hands-on time to 15 min minimum
- Must keep wrap-up and homework explanation

**If running ahead:**
- Preview multi-step prompting from Class 2
- Do additional live demonstrations
- Have students present their work
- Create class prompt library document

---

**You're ready to teach! Remember: The goal is for students to leave with prompts that actually help them learn. Prioritize hands-on practice and real homework applications.**
