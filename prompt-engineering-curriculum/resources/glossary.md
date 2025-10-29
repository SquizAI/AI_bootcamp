# Prompt Engineering Glossary for Students

A comprehensive guide to terms and concepts you'll encounter when working with AI tools like Google Gemini.

---

## Core Concepts

### Prompt Engineering
**Definition:** The skill of writing clear, effective instructions (prompts) to get the best responses from AI tools.

**Why It Matters:** Just like asking a good question gets a better answer from a teacher, a well-designed prompt gets much better results from AI. Poor prompts lead to vague, unhelpful, or incorrect responses.

**Simple Example:**
```
Poor prompt: "Tell me about cells"
Better prompt: "I'm a 9th grader learning about cells. Explain the difference between plant and animal cells using a comparison table, and tell me why each difference matters."

The better prompt specifies: who you are, what you need, how you want it presented, and what level of detail you need.
```

**In Practice:** Prompt engineering is not about tricking AI - it's about communicating clearly what you need. It's a skill that improves with practice.

---

### Context Engineering
**Definition:** Providing relevant background information in your prompt so the AI understands your situation and can tailor its response.

**Why It Matters:** Without context, AI gives generic answers. With context, it can adjust for your grade level, what you already know, and what you're trying to accomplish.

**Simple Example:**
```
Without context: "Explain photosynthesis"
Result: Gets a college-level textbook explanation

With context: "I'm a 7th grader learning photosynthesis for the first time. I understand that plants need sunlight and water, but I don't understand what's actually happening inside the plant. Use an everyday analogy to explain."
Result: Gets an age-appropriate explanation building on what you know
```

**What to Include as Context:**
- Your grade level
- What you already know
- What confuses you
- What you'll use this for (test, essay, understanding)
- Any specific requirements

---

### Role-Based Prompting
**Definition:** Asking the AI to take on a specific role or persona (like a tutor, editor, or expert) to shape how it responds.

**Why It Matters:** Different roles lead to different styles of response. A "tutor" will explain and ask questions, while a "study partner" might quiz you or discuss ideas.

**Simple Example:**
```
Without role: "Help me with this math problem"
Might get: Direct solution

With role: "Act as a math tutor who helps students learn by asking guiding questions. I'm stuck on this algebra problem: [problem]. Don't solve it for me, but help me figure out the next step."
Gets: Questions that help you think through it yourself
```

**Common Useful Roles:**
- Subject tutor (explains concepts)
- Study coach (helps you organize learning)
- Writing editor (gives feedback on your writing)
- Socratic teacher (asks questions to develop thinking)
- Peer study partner (discusses ideas with you)

---

### Few-Shot Learning / Few-Shot Prompting
**Definition:** Showing the AI a few examples of what you want before asking it to do something similar.

**Why It Matters:** Examples teach the AI the pattern or style you're looking for, leading to more consistent, useful results.

**Simple Example:**
```
Zero examples (might not get the format you want):
"Create study questions on the Civil War"

Few-shot (2-3 examples):
"Create study questions on the Civil War in this format:

Example 1: What were the economic differences between North and South? (Tests: understanding of causes)
Example 2: How did the Emancipation Proclamation change the war's purpose? (Tests: cause and effect)

Now create 5 more questions following this same format about other aspects of the Civil War."
```

**When to Use:**
- Creating practice problems in a specific format
- Getting vocabulary definitions in a consistent style
- Generating examples that match your teacher's expectations
- Any time you want consistent formatting

---

### Zero-Shot Prompting
**Definition:** Asking the AI to do something without providing any examples, relying on clear instructions alone.

**Why It Matters:** This is the default way of prompting. It works well when your request is straightforward and doesn't need specific formatting.

**Simple Example:**
```
"Explain Newton's three laws of motion in simple terms for a 9th grade physics student."

This is zero-shot because you're not showing examples - just asking clearly for what you need.
```

**When It Works Best:**
- Explaining concepts
- Answering questions
- General brainstorming
- Simple, straightforward requests

**When to Switch to Few-Shot:**
- Need specific formatting
- Want consistent style across multiple responses
- Teacher has specific expectations for format

---

### Chain-of-Thought / Multi-Step Prompting
**Definition:** Asking the AI to break down complex problems into steps and show its reasoning process, or structuring your prompt to work through something step-by-step.

**Why It Matters:** For complex topics, step-by-step reasoning leads to better, more accurate answers and helps you understand the thinking process.

**Simple Example:**
```
Without chain-of-thought:
"What's the answer to this word problem: Sarah has 3 times as many books as Michael. Together they have 48 books. How many does each have?"
Might get: Just the final answer

With chain-of-thought:
"Walk me through solving this word problem step-by-step, explaining your thinking at each stage:
Sarah has 3 times as many books as Michael. Together they have 48 books. How many does each have?

Please:
1. Identify what we know
2. Identify what we're trying to find
3. Set up the equation
4. Solve step-by-step
5. Check if the answer makes sense"

Gets: Full reasoning process you can learn from
```

**When to Use:**
- Complex math or science problems
- Multi-part questions
- When you need to understand the process, not just the answer
- Planning essays or projects

---

### Meta-Prompting
**Definition:** Using AI to help you write better prompts, or asking AI to design prompts for specific purposes.

**Why It Matters:** If you're not getting good results, AI can help you improve your prompting strategy.

**Simple Example:**
```
Meta-prompt:
"I'm trying to get help studying for biology tests, but my prompts aren't working well. Help me design a better prompt template for getting study support on biology topics. I'm in 10th grade and I learn best from examples and analogies."

This asks the AI to help you create better prompts for future use.
```

**Practical Uses:**
- "Help me write a prompt to get essay feedback without having AI rewrite my work"
- "Design a prompt template I can reuse for math homework help"
- "I asked [previous prompt] but got [unhelpful response]. How can I improve my prompt?"

---

### System Instructions
**Definition:** Permanent instructions or settings that apply to all your conversations with an AI, setting default behaviors.

**Why It Matters:** Instead of repeating the same context every time, you can set it once and have it apply to all interactions.

**Simple Example:**
In Google AI Studio, you might set system instructions like:
```
"I am a 10th grade student. When I ask for help:
- Explain concepts at my level
- Don't solve homework for me; guide me to solve it
- Use real-world analogies
- Ask me questions to check my understanding
- Point out when I'm on the wrong track without giving away answers"
```

Now every conversation will follow these guidelines without you restating them.

**Where to Use System Instructions:**
- Google AI Studio (can set persistent instructions)
- When you have consistent needs across many conversations
- Setting your "learning mode" preferences

**Note:** Regular Gemini chat doesn't have persistent system instructions, but AI Studio does.

---

### Temperature
**Definition:** A setting that controls how creative or predictable AI responses are. Lower temperature = more focused and consistent; higher temperature = more creative and varied.

**Why It Matters:** For studying and homework, you usually want lower temperature (more accurate, factual). For creative writing or brainstorming, higher temperature can help.

**Simple Example:**
```
Low temperature (0.2-0.4):
Q: "What is photosynthesis?"
A: Consistent, accurate, textbook-style explanation

High temperature (0.8-1.0):
Q: "Write a creative story about a magical forest"
A: More varied, creative, unexpected story elements
```

**When to Adjust:**
- **Low temperature** (factual mode): Math help, science explanations, test prep, grammar checking
- **High temperature** (creative mode): Story writing, brainstorming, creative project ideas

**Note:** Most student uses work fine with default temperature. This is more advanced.

---

### Token
**Definition:** Small chunks that AI breaks text into for processing. Think of tokens as pieces of words, words, or parts of words.

**Why It Matters:** AI has limits on how many tokens it can handle at once (its "context window"). This affects how much you can include in a prompt.

**Simple Example:**
The sentence "I'm learning about cells" might be broken into tokens like:
["I", "'m", "learning", "about", "cells"]

That's roughly 5 tokens. Generally:
- 1 token ≈ 4 characters in English
- 100 words ≈ 75 tokens (roughly)

**Practical Implications:**
- Don't paste your entire 10-page essay for feedback - summarize or work section by section
- If you get "context limit" errors, shorten your prompt
- For long research papers, work in sections rather than all at once

**You Usually Don't Need to Think About This Unless:**
- Working with very long texts
- Getting error messages about length
- Using advanced features with token limits

---

### Constraints / Negative Prompting
**Definition:** Explicitly telling the AI what NOT to do or what to avoid in its response.

**Why It Matters:** Sometimes it's easier to get what you want by ruling out what you don't want.

**Simple Example:**
```
Without constraints:
"Help me with my essay about climate change"
Might get: Complete essay written for you (academic dishonesty!)

With constraints:
"Help me brainstorm ideas for my climate change essay. DO NOT write the essay for me or write full paragraphs. Instead, ask me questions, suggest angles to explore, and help me develop MY ideas."
```

**Common Useful Constraints:**
- "Don't solve this for me, guide me to solve it"
- "Don't use vocabulary above 9th grade level"
- "Don't just summarize - help me analyze"
- "Avoid technical jargon unless you explain it"
- "Don't write full sentences for my essay - give me structures and ideas"

**When to Use:**
- You keep getting answers instead of guidance
- Responses are too simple or too complex
- AI is doing too much of your work
- You want to avoid specific approaches

---

### Prompt Chaining
**Definition:** Using multiple connected prompts in sequence, where each prompt builds on the previous response.

**Why It Matters:** Complex tasks work better as a series of focused prompts rather than one giant prompt.

**Simple Example:**
```
Chain for Essay Writing:

Prompt 1: "I need to write an essay on [topic]. Help me brainstorm 3-4 potential thesis statements."
[Review responses, choose one]

Prompt 2: "I've chosen this thesis: [your choice]. Help me outline the main points I should cover in each body paragraph."
[Work through outline]

Prompt 3: "Here's my first body paragraph: [paste]. Give me feedback on its structure and how well it supports my thesis."
[Refine each paragraph]

This breaks the process into manageable steps, each building on the last.
```

**When to Use Prompt Chaining:**
- Large projects (essays, research papers, presentations)
- Multi-step problem solving
- When you need to make decisions between steps
- Learning complex topics (overview → details → practice → assessment)

**Benefits:**
- More focused responses at each stage
- You stay in control of the direction
- Easier to correct if something goes wrong
- Natural pauses to think and learn

---

## Google Gemini Models

### Gemini 2.5 Flash
**What It Is:** Google's fast, efficient AI model designed for quick responses and everyday tasks.

**Best For:**
- Quick homework questions
- Explaining concepts
- Generating practice problems
- Study help
- Most student tasks

**Characteristics:**
- Very fast responses
- Good at following instructions
- Handles most school subjects well
- Free tier available
- Best balance of speed and quality for students

**When to Use:**
- Daily homework help
- Studying for tests
- Understanding concepts
- General writing assistance
- Most of your school work

---

### Gemini 2.5 Pro
**What It Is:** Google's most capable model, designed for complex reasoning and in-depth analysis.

**Best For:**
- Complex research projects
- Advanced problem-solving
- Detailed analysis
- Multi-step reasoning
- Advanced coursework

**Characteristics:**
- Slower than Flash but more thorough
- Better at complex reasoning
- Handles nuanced questions well
- More detailed responses
- May require paid tier

**When to Use:**
- Research papers with complex analysis
- Advanced math or science problems
- Deep literary analysis
- When Flash's response isn't detailed enough
- College prep or AP-level work

**Note:** For most middle and high school work, Flash is perfectly sufficient and recommended due to speed.

---

### Gemini 2.5 Flash-Lite (Experimental)
**What It Is:** An even faster, lighter version of Flash for simple tasks.

**Best For:**
- Very quick questions
- Simple definitions
- Fast fact-checking
- When speed is priority

**Characteristics:**
- Fastest responses
- Less complex reasoning
- Good for straightforward questions
- Very resource-efficient

**When to Use:**
- Quick vocabulary lookups
- Simple factual questions
- Fast checks during studying
- When you need speed over depth

**Limitation:** Not ideal for complex explanations or multi-step problems.

---

## Model Comparison for Students

| Task Type | Recommended Model | Why |
|-----------|------------------|-----|
| Daily homework help | Flash | Best balance of speed and quality |
| Quick definitions | Flash-Lite | Fastest for simple questions |
| Complex essay analysis | Pro | Better reasoning for nuanced topics |
| Math problem solving | Flash | Fast and accurate for most levels |
| Advanced calculus/physics | Pro | Handles complex multi-step reasoning |
| Test preparation | Flash | Quick generation of practice materials |
| Research paper planning | Pro | Better at organizing complex ideas |
| Creative writing | Flash | Good creativity, fast generation |
| Quick fact-checking | Flash-Lite | Speed is priority |

---

## Advanced Concepts (Optional)

### Prompt Templates
**Definition:** Reusable prompt structures with blanks you fill in for similar tasks.

**Example Template:**
```
"I'm a [GRADE] student working on [SUBJECT]. I need help understanding [CONCEPT]. I currently know [WHAT YOU KNOW] but I'm confused about [CONFUSION]. Please explain using [METHOD] and give me [EXAMPLE TYPE]."

Fill in the brackets for each use.
```

**Why Useful:** Saves time and ensures consistent quality when you do similar tasks repeatedly.

---

### Iterative Prompting
**Definition:** Refining your prompt based on the response you get, having a back-and-forth conversation to improve results.

**Example:**
```
First try: "Explain the water cycle"
Response: Too basic

Refined: "I understand the basic water cycle stages. Explain how temperature and pressure affect evaporation rates at a 10th grade chemistry level"
Response: Much better!

Further refined: "Can you add a real-world example of how this works in different climates?"
Response: Perfect!
```

**Why It Matters:** Your first prompt rarely gets perfect results. Iteration is normal and expected.

---

### Context Window
**Definition:** The total amount of text (input and output) the AI can consider at once, measured in tokens.

**Why It Matters:** If you exceed this limit, the AI "forgets" earlier parts of the conversation.

**For Students:**
- Gemini has a large context window
- Only matters for very long conversations or documents
- If responses start ignoring earlier instructions, you might have exceeded it
- Solution: Start a new conversation or summarize earlier context

---

## Using This Glossary

### As a Reference
- Look up terms when you encounter them in lessons or readings
- Return to refresh your understanding
- Use when troubleshooting prompt issues

### For Building Skills
- Start with core concepts (Prompt Engineering, Context Engineering, Role-Based Prompting)
- Practice each concept deliberately
- Add advanced concepts as you get comfortable

### When Things Go Wrong
If AI responses aren't helpful, check:
1. Did I provide enough **context**?
2. Did I use **constraints** to guide away from what I don't want?
3. Would a specific **role** help?
4. Should I break this into **multiple prompts** (chaining)?
5. Would **examples** (few-shot) make my needs clearer?

---

## Quick Reference Card

**Essential Elements of a Good Prompt:**
1. **Who you are:** Grade level, subject level
2. **What you need:** Specific task or question
3. **Why you need it:** Context about assignment/purpose
4. **How you want it:** Format, style, depth
5. **What to avoid:** Constraints on the response

**Template to Start With:**
```
"I'm a [grade] student learning [topic]. [Context about what you know and what confuses you]. Help me [specific task]. Please [format/style preferences]. Don't [constraints]."
```

Practice this structure until it becomes natural, then experiment with advanced techniques!

---

*Remember: Prompt engineering is a skill that improves with practice. Don't expect perfection immediately - learn from each interaction and keep refining your approach.*
