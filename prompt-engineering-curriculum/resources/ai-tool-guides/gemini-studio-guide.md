# Complete Guide to Google AI Studio for Students

## Table of Contents
- [What is AI Studio?](#what-is-ai-studio)
- [AI Studio vs Regular Gemini](#ai-studio-vs-regular-gemini)
- [How to Access and Set Up](#how-to-access-and-set-up)
- [Understanding the Interface](#understanding-the-interface)
- [System Instructions Explained](#system-instructions-explained)
- [Saving and Reusing Prompts](#saving-and-reusing-prompts)
- [Model Selection Guide](#model-selection-guide)
- [Structured Outputs and JSON](#structured-outputs-and-json)
- [Building Prompt Templates](#building-prompt-templates)
- [Step-by-Step Walkthrough](#step-by-step-walkthrough)
- [Advanced Features](#advanced-features)
- [Best Practices](#best-practices)
- [Common Use Cases](#common-use-cases)

---

## What is AI Studio?

Google AI Studio is an advanced interface for interacting with Gemini models. Think of it as a "developer's playground" or "power user's toolkit" for working with AI. While the regular Gemini interface is like using a calculator app, AI Studio is like having a scientific calculator with programmable functions.

**Key Characteristics:**
- More control over AI behavior
- Ability to save and reuse prompts
- Advanced configuration options
- Structured output capabilities
- Prompt template creation
- API code generation

**Who should use AI Studio:**
- Students working on complex, repeated tasks
- Those who need consistent AI behavior
- Anyone building prompt templates
- Students learning about AI and prompt engineering
- Those who need structured outputs (JSON, specific formats)

---

## AI Studio vs Regular Gemini

### Regular Gemini (gemini.google.com)
**Best for:**
- Quick questions
- One-off conversations
- General studying
- Casual use
- Mobile access

**Characteristics:**
- Simple, chat-focused interface
- Conversation history
- Easy to use
- Limited customization
- Good for beginners

### AI Studio (aistudio.google.com)
**Best for:**
- Repeated similar tasks
- Custom AI behaviors
- Structured outputs
- Prompt engineering
- Template building

**Characteristics:**
- Advanced configuration
- Prompt saving and sharing
- System instructions
- Model parameter controls
- JSON output support
- API code generation

**Simple Analogy:**
- **Regular Gemini** = Text messaging with an AI
- **AI Studio** = Customizable AI workshop where you build specialized tools

---

## How to Access and Set Up

### Initial Access

1. **Visit AI Studio**
   - Go to: [aistudio.google.com](https://aistudio.google.com)
   - Sign in with your Google account

2. **First-Time Setup**
   - Review terms of service
   - Grant necessary permissions
   - Familiarize yourself with the interface

3. **Browser Recommendations**
   - Chrome (recommended for best experience)
   - Firefox, Safari, Edge also supported
   - Enable JavaScript and cookies

### Account Considerations

**Free Tier:**
- Available to all Google account holders
- Generous usage limits for students
- Access to all Gemini models
- No credit card required

**Usage Limits:**
- Rate limits on requests per minute
- Daily request quotas
- Resets every 24 hours
- Sufficient for most student needs

---

## Understanding the Interface

### Main Dashboard

**Screenshot description**: The AI Studio dashboard shows three main sections: prompt library on the left, workspace in the center, and configuration panel on the right.

### Left Panel: Prompt Library
- **My Prompts**: Your saved prompts
- **Starred**: Frequently used prompts
- **Recent**: Recently accessed prompts
- **Search**: Find specific prompts
- **New Prompt Button**: Create new prompts

### Center Panel: Workspace
- **Prompt Editor**: Where you write and edit prompts
- **Test Input Area**: Where you provide input
- **Response Area**: Where AI outputs appear
- **Run Button**: Execute your prompt
- **Example Outputs**: Previous test runs

### Right Panel: Configuration
- **Model Selection**: Choose which Gemini model
- **System Instructions**: Set AI behavior
- **Parameters**: Adjust temperature, top-k, top-p
- **Output Format**: Configure response structure
- **Safety Settings**: Content filtering controls

### Top Bar
- **Project Name**: Current project title
- **Save**: Save your prompt
- **Share**: Share with others
- **Get Code**: Generate API code
- **Settings**: General settings

---

## System Instructions Explained

### What Are System Instructions?

System instructions are **persistent instructions** that define how the AI should behave throughout the entire conversation. Think of them as the AI's "personality settings" or "operating manual."

**Regular Gemini:**
```
You: "Act as a biology tutor and explain photosynthesis."
Gemini: [Explains photosynthesis as a tutor]
You: "Now explain cellular respiration."
Gemini: [May or may not maintain tutor persona]
```

**AI Studio with System Instructions:**
```
System Instruction: "You are a biology tutor specializing in making complex concepts simple for high school students."

You: "Explain photosynthesis."
Gemini: [Explains as tutor]
You: "Now explain cellular respiration."
Gemini: [Still maintains tutor persona automatically]
```

### How to Write Effective System Instructions

#### Basic Template
```
You are a [role] who [specific expertise].

Your responses should:
- [Characteristic 1]
- [Characteristic 2]
- [Characteristic 3]

When answering questions:
- [Guideline 1]
- [Guideline 2]
```

#### Example: Study Helper
```
You are a patient study assistant for college students.

Your responses should:
- Break complex concepts into simple steps
- Use analogies and real-world examples
- Check for understanding before moving on
- Encourage critical thinking

When answering questions:
- First assess what the student already knows
- Provide explanations rather than direct answers
- Offer practice problems after explanations
- Be encouraging and supportive
```

#### Example: Code Review Assistant
```
You are an experienced programming mentor who helps students learn good coding practices.

Your responses should:
- Review code for bugs and inefficiencies
- Explain the reasoning behind suggestions
- Follow industry best practices
- Be constructive and educational

When reviewing code:
- Point out specific issues with line references
- Explain why something is a problem
- Suggest improvements with examples
- Highlight what the student did well
```

#### Example: Research Assistant
```
You are a research assistant helping students with academic projects.

Your responses should:
- Provide well-organized information
- Cite general knowledge appropriately
- Suggest credible sources for further reading
- Help structure research logically

When assisting with research:
- Break topics into subtopics
- Identify key concepts to investigate
- Suggest search strategies
- Help organize findings into coherent outlines
```

### Best Practices for System Instructions

1. **Be Specific**
   - Vague: "Be helpful"
   - Better: "Provide step-by-step explanations with examples"

2. **Define the Role Clearly**
   - Include expertise level
   - Specify teaching/communication style
   - Define the audience (students, beginners, etc.)

3. **Set Response Patterns**
   - Desired format
   - Level of detail
   - Tone and style

4. **Include Constraints**
   - What to avoid
   - Length limitations
   - Required elements

5. **Test and Iterate**
   - Test with various inputs
   - Refine based on outputs
   - Save multiple versions

---

## Saving and Reusing Prompts

### Why Save Prompts?

**Scenario:** You need to summarize research articles weekly for your psychology class. Instead of rewriting instructions each time:

1. Create the perfect prompt once
2. Save it in AI Studio
3. Reuse it whenever needed
4. Get consistent results every time

### How to Save a Prompt

1. **Create Your Prompt**
   - Write system instructions
   - Add example inputs/outputs
   - Configure settings

2. **Test Thoroughly**
   - Try with multiple inputs
   - Ensure consistent quality
   - Refine as needed

3. **Save the Prompt**
   - Click "Save" button
   - Name it descriptively
   - Add tags for organization
   - Include description of purpose

4. **Access Anytime**
   - Find in "My Prompts"
   - Click to load
   - Modify if needed
   - Use with new inputs

### Organizing Your Prompts

**Naming Convention:**
```
[Subject] - [Purpose] - [Version]
Examples:
- Biology - Study Guide Generator - v2
- Python - Code Review - Final
- History - Essay Outliner - Draft
```

**Use Tags:**
- Subject area (biology, math, english)
- Task type (summarize, explain, generate)
- Difficulty (intro, intermediate, advanced)

**Create Collections:**
- Organize by class/subject
- Group by assignment type
- Separate by semester

---

## Model Selection Guide

### Available Models in AI Studio

#### Gemini 2.5 Pro
**Technical Specs:**
- Context window: 2 million tokens
- Best reasoning capability
- Highest quality outputs
- Slower response time

**When to Use:**
- Analyzing long documents (research papers, books)
- Complex problem-solving
- Advanced code generation
- Multi-document comparison
- Detailed research synthesis

**Student Use Cases:**
```
✓ Analyzing multiple research papers for literature review
✓ Complex mathematical proofs
✓ Advanced coding projects
✓ Thesis development
✓ Comprehensive exam preparation
```

#### Gemini 2.5 Flash
**Technical Specs:**
- Context window: 1 million tokens
- Fast response time
- Good reasoning capability
- Balanced performance

**When to Use:**
- Most everyday tasks
- Quick assignments
- Standard homework help
- General studying
- Rapid iterations

**Student Use Cases:**
```
✓ Study guide generation
✓ Practice problem creation
✓ Quick explanations
✓ Essay outlining
✓ Code debugging
✓ Flashcard creation
```

#### Gemini Flash-Lite
**Technical Specs:**
- Fastest response time
- Smaller context window
- Good for simple tasks
- Most cost-effective

**When to Use:**
- Simple queries
- Quick definitions
- Basic fact-checking
- Rapid testing of prompts

**Student Use Cases:**
```
✓ Vocabulary definitions
✓ Quick fact checks
✓ Simple calculations
✓ Brief summaries
✓ Testing prompt ideas
```

### Model Selection Decision Tree

```
START: What's your task?

├─ Need to analyze 50+ pages of text?
│  └─ Use GEMINI 2.5 PRO
│
├─ Complex reasoning or advanced coding?
│  └─ Use GEMINI 2.5 PRO
│
├─ Standard homework/study task?
│  └─ Use GEMINI 2.5 FLASH
│
├─ Quick question or simple task?
│  └─ Use GEMINI FLASH-LITE
│
└─ Not sure?
   └─ Start with GEMINI 2.5 FLASH
      (upgrade if needed)
```

### How to Switch Models

1. **In AI Studio:**
   - Look at right panel
   - Find "Model" dropdown
   - Select desired model
   - Re-run your prompt

2. **Testing Across Models:**
   - Save your prompt
   - Run with Flash
   - Compare with Pro
   - Choose best for task

---

## Structured Outputs and JSON

### What Are Structured Outputs?

Structured outputs are responses formatted in specific, predictable ways (like JSON, tables, or templates) rather than free-form text.

**Unstructured Output:**
```
The capital of France is Paris. France is in Europe and Paris
is known for the Eiffel Tower. The population is around 2.2 million.
```

**Structured Output (JSON):**
```json
{
  "country": "France",
  "capital": "Paris",
  "continent": "Europe",
  "landmark": "Eiffel Tower",
  "population": 2200000
}
```

### Why Use Structured Outputs?

**Benefits for Students:**
1. **Consistency**: Same format every time
2. **Organization**: Easy to read and use
3. **Processing**: Can import into spreadsheets/databases
4. **Integration**: Can use with other tools
5. **Clarity**: Information clearly labeled

### How to Create Structured Outputs

#### Method 1: Specify in Prompt

```
Create a JSON object with the following structure for each historical event:
{
  "event_name": "string",
  "date": "YYYY-MM-DD",
  "location": "string",
  "significance": "string",
  "key_figures": ["string", "string"]
}

Event: The signing of the Declaration of Independence
```

#### Method 2: Use Response Schema (Advanced)

In AI Studio, you can define a JSON schema for responses:

```json
{
  "type": "object",
  "properties": {
    "event_name": {
      "type": "string",
      "description": "Name of the historical event"
    },
    "date": {
      "type": "string",
      "format": "date"
    },
    "location": {
      "type": "string"
    },
    "significance": {
      "type": "string"
    },
    "key_figures": {
      "type": "array",
      "items": {
        "type": "string"
      }
    }
  },
  "required": ["event_name", "date", "significance"]
}
```

### Practical Structured Output Examples

#### Example 1: Study Guide Template

**Prompt:**
```
Generate a study guide in the following JSON format:

{
  "topic": "string",
  "key_concepts": [
    {
      "concept": "string",
      "definition": "string",
      "example": "string"
    }
  ],
  "practice_questions": ["string"],
  "resources": ["string"]
}

Topic: Photosynthesis
```

**Use:** Import into note-taking apps, create flashcards, organize study materials

#### Example 2: Assignment Tracker

**Prompt:**
```
Organize my assignments in this JSON structure:

{
  "assignments": [
    {
      "course": "string",
      "title": "string",
      "due_date": "YYYY-MM-DD",
      "priority": "high|medium|low",
      "estimated_hours": number,
      "tasks": ["string"]
    }
  ]
}

[List your assignments here]
```

**Use:** Import into project management tools, create calendars

#### Example 3: Research Notes

**Prompt:**
```
Extract information from this article into:

{
  "article_info": {
    "title": "string",
    "author": "string",
    "year": number,
    "source": "string"
  },
  "main_arguments": [
    {
      "argument": "string",
      "evidence": ["string"],
      "counter_arguments": ["string"]
    }
  ],
  "key_quotes": [
    {
      "quote": "string",
      "page": number,
      "context": "string"
    }
  ],
  "connections": ["string"]
}

[Paste article]
```

**Use:** Organize research, create bibliographies, synthesize sources

### Working with JSON in AI Studio

1. **Enable JSON Mode**
   - Go to configuration panel
   - Select "JSON" output format
   - Define schema (optional)

2. **Validate Output**
   - Use JSON validator tools
   - Check for completeness
   - Verify structure matches needs

3. **Export and Use**
   - Copy JSON output
   - Import into spreadsheets
   - Use with other applications
   - Process with scripts

---

## Building Prompt Templates

### What Is a Prompt Template?

A prompt template is a reusable prompt structure with placeholders that you fill in each time. Think of it like a form or Mad Libs for AI prompts.

**Template:**
```
Explain {{CONCEPT}} to a {{EDUCATION_LEVEL}} student using {{TEACHING_METHOD}}.
Include:
- Simple definition
- Real-world analogy
- {{NUMBER}} examples
- Common misconceptions
```

**Filled In:**
```
Explain "quantum entanglement" to a high school student using visual analogies.
Include:
- Simple definition
- Real-world analogy
- 3 examples
- Common misconceptions
```

### Why Use Templates?

1. **Consistency**: Same quality every time
2. **Efficiency**: Don't rewrite prompts
3. **Scalability**: Use across many topics
4. **Sharing**: Easy to share with classmates
5. **Improvement**: Refine once, benefit always

### How to Build Effective Templates

#### Step 1: Identify Repetitive Tasks

**Questions to ask:**
- What do I do repeatedly?
- What follows a similar pattern?
- What takes time to write out each time?

**Examples:**
- Summarizing research articles
- Creating study guides
- Generating practice problems
- Analyzing historical events
- Reviewing code

#### Step 2: Define the Structure

**Basic Template Structure:**
```
[System Instructions]
↓
[Task Description]
↓
[Required Elements]
↓
[Format Specification]
↓
[Input Placeholder]
```

#### Step 3: Create Variables

**Variables to consider:**
- {{TOPIC}} - What you're studying
- {{LEVEL}} - Difficulty or education level
- {{FORMAT}} - How you want output
- {{LENGTH}} - How long the response
- {{STYLE}} - Tone or approach
- {{EXAMPLES}} - Number of examples

#### Step 4: Test and Refine

1. Test with various inputs
2. Check output quality
3. Identify improvements
4. Update template
5. Save refined version

### Example Templates for Students

#### Template 1: Literature Analysis

```
System Instructions:
You are a literature professor helping students analyze texts deeply.

Analyze the following passage from "{{WORK_TITLE}}" by {{AUTHOR}}:

Focus on:
1. Literary devices (identify at least {{NUMBER}})
2. Themes and symbolism
3. Character development
4. Historical context
5. Author's purpose

Provide analysis at a {{LEVEL}} level.

Format your response as:
- Overview
- Detailed analysis of each focus area
- Synthesis and conclusion
- Discussion questions

Passage:
{{TEXT}}
```

**Use cases:**
- Essay preparation
- Class discussion prep
- Exam studying
- Paper research

#### Template 2: Math Problem Generator

```
System Instructions:
You are a math tutor creating practice problems for students.

Generate {{NUMBER}} practice problems on {{TOPIC}} at {{DIFFICULTY}} level.

For each problem:
1. State the problem clearly
2. Provide step-by-step solution
3. Explain the reasoning for each step
4. Include a similar practice problem (solution hidden)

Format:
Problem 1: [statement]
Solution 1: [steps with explanations]
Practice: [similar problem]

Problem 2: [statement]
...

Topic: {{TOPIC}}
Specific focus: {{FOCUS_AREA}}
Related concepts to include: {{CONCEPTS}}
```

**Use cases:**
- Test preparation
- Homework practice
- Skill building
- Self-assessment

#### Template 3: Study Guide Generator

```
System Instructions:
You are creating comprehensive study materials for students.

Create a study guide for {{TOPIC}} covering {{SUBTOPICS}}.

Include:
1. Key Concepts & Definitions ({{NUM_CONCEPTS}} concepts)
2. Visual Organizers (describe {{NUM_VISUALS}} charts/diagrams)
3. Summary Notes ({{LENGTH}} paragraphs)
4. Practice Questions ({{NUM_QUESTIONS}} questions with answers)
5. Memory Aids (mnemonics, acronyms)
6. Common Mistakes to Avoid ({{NUM_MISTAKES}})

Target Level: {{EDUCATION_LEVEL}}
Learning Style: {{LEARNING_STYLE}}

Format output in clear sections with headers.

Source Material:
{{CONTENT}}
```

**Use cases:**
- Exam preparation
- Review sessions
- Quick reference
- Sharing with study groups

#### Template 4: Research Summary

```
System Instructions:
You are a research assistant helping students process academic sources.

Summarize the following research article:

Extract:
1. Research Question/Hypothesis
2. Methodology ({{DETAIL_LEVEL}} detail)
3. Key Findings ({{NUM_FINDINGS}} main findings)
4. Implications
5. Limitations
6. Future Research Directions

Additional focus: {{SPECIFIC_FOCUS}}

Format as:
- Citation (APA format)
- Executive Summary ({{SUMMARY_LENGTH}} words)
- Detailed Sections (above items)
- Personal notes section for: {{NOTE_FOCUS}}

Article:
{{ARTICLE_TEXT}}
```

**Use cases:**
- Literature reviews
- Research projects
- Article databases
- Class presentations

#### Template 5: Code Review

```
System Instructions:
You are a programming instructor reviewing student code.

Review the following {{LANGUAGE}} code:

Evaluate:
1. Correctness - Does it work as intended?
2. Efficiency - Can it be optimized?
3. Readability - Is it well-organized and commented?
4. Best Practices - Does it follow {{LANGUAGE}} conventions?
5. Potential Bugs - What could go wrong?

Focus especially on: {{FOCUS_AREAS}}

Provide:
- Summary assessment
- Specific issues with line numbers
- Suggested improvements with examples
- Positive feedback on good practices
- Learning resources for improvements

Code:
{{CODE}}

Intended functionality:
{{DESCRIPTION}}
```

**Use cases:**
- Assignment review before submission
- Learning best practices
- Debugging help
- Skill improvement

### Advanced Template Features

#### Conditional Logic in Prompts

```
System Instructions: You are a {{ROLE}}.

{{IF BEGINNER}}
Use simple language and provide step-by-step guidance.
Include many examples and avoid jargon.
{{ENDIF}}

{{IF ADVANCED}}
Use technical terminology and assume prerequisite knowledge.
Focus on nuances and advanced applications.
{{ENDIF}}

Task: {{TASK}}
```

#### Template Chaining

**Template 1: Initial Analysis**
```
Analyze {{TOPIC}} and identify the {{NUM}} most important subtopics to explore.
```

**Template 2: Deep Dive** (using output from Template 1)
```
For subtopic "{{SUBTOPIC}}" from {{TOPIC}}, provide:
- Detailed explanation
- Examples
- Connections to other subtopics
```

#### Multi-Step Templates

```
Step 1 - Brainstorm:
Generate {{NUM}} ideas for {{PROJECT_TYPE}} on {{TOPIC}}

Step 2 - Evaluate:
For each idea, assess:
- Feasibility
- Learning value
- Resource requirements
- Uniqueness

Step 3 - Develop:
For the top idea, create:
- Detailed project plan
- Timeline
- Required resources
- Expected outcomes
```

---

## Step-by-Step Walkthrough

### Walkthrough 1: Creating Your First Custom Prompt

**Scenario:** You need to regularly summarize psychology research articles for class.

#### Step 1: Access AI Studio
1. Go to aistudio.google.com
2. Sign in with Google account
3. Click "New Prompt"

#### Step 2: Write System Instructions
```
You are a psychology research assistant helping students understand academic papers.

Your summaries should:
- Be clear and concise
- Highlight key methodology
- Explain findings in plain language
- Connect to broader psychological concepts
- Be appropriate for undergraduate students
```

#### Step 3: Create the Prompt Template
```
Summarize the following psychology research article:

Extract:
1. Research question and hypothesis
2. Methodology and sample size
3. Key findings (main results)
4. Implications for psychology
5. Limitations of the study

Format in clear sections with bullet points.

Article:
{{PASTE_ARTICLE_HERE}}
```

#### Step 4: Test with Real Article
1. Paste an actual article from your class
2. Click "Run"
3. Review the output
4. Assess quality and completeness

#### Step 5: Refine as Needed
**If output is too brief:**
```
Provide detailed explanations for each section (150-200 words each).
```

**If output is too technical:**
```
Use language appropriate for students new to research methods.
Define any technical terms.
```

#### Step 6: Save the Prompt
1. Click "Save"
2. Name: "Psychology - Research Article Summary"
3. Add tags: psychology, research, summary
4. Add description: "Summarizes psych research papers for class"

#### Step 7: Use Regularly
- Open saved prompt
- Paste new article
- Get consistent summaries
- Build article database

### Walkthrough 2: Building a Study Session Assistant

**Scenario:** You want AI to guide you through focused study sessions.

#### Step 1: Define Your Study Method

**Pomodoro-inspired approach:**
- 25-minute focused segments
- Review, practice, assess
- Progressive difficulty

#### Step 2: Create System Instructions
```
You are a study session facilitator using active learning techniques.

Your role:
- Guide students through structured study sessions
- Progressively increase difficulty
- Check understanding before advancing
- Provide encouragement and feedback
- Adapt to student responses

Teaching style:
- Ask questions before explaining
- Use Socratic method
- Provide hints, not answers
- Celebrate progress
```

#### Step 3: Structure the Session
```
Study Session: {{TOPIC}}
Duration: {{MINUTES}} minutes
Current knowledge level: {{LEVEL}}

Session structure:

**Phase 1: Warm-up (5 minutes)**
- Review key concepts
- Ask 3 diagnostic questions
- Identify knowledge gaps

**Phase 2: Deep dive (15 minutes)**
- Focus on identified gaps
- Provide explanations with examples
- Check understanding with problems

**Phase 3: Practice (10 minutes)**
- Generate practice problems
- Provide immediate feedback
- Adjust difficulty based on performance

**Phase 4: Wrap-up (5 minutes)**
- Summarize key takeaways
- Suggest next study session focus
- Provide motivation

Begin Phase 1 now.
```

#### Step 4: Test the Flow
1. Run with a topic you're studying
2. Actually go through the session
3. Take notes on what works/doesn't
4. Time each phase

#### Step 5: Refine Based on Experience
**Possible improvements:**
- Adjust timing
- Add more/fewer questions
- Change difficulty progression
- Modify tone and encouragement style

#### Step 6: Create Variations
Save different versions for:
- Quick review (15 minutes)
- Deep study (60 minutes)
- Exam prep (focus on assessment)
- Different subjects (adjust examples/style)

### Walkthrough 3: Setting Up a Code Debugging Assistant

**Scenario:** You need help debugging code but want to learn, not just get answers.

#### Step 1: Design the Interaction
```
Goals:
- Help identify bugs
- Explain why bugs occur
- Teach debugging strategies
- Don't just give answers
```

#### Step 2: Write System Instructions
```
You are a patient programming mentor who helps students debug code through guided discovery.

Your approach:
- Never immediately show the bug
- Ask diagnostic questions first
- Guide student to find issues themselves
- Explain underlying concepts
- Teach debugging strategies

When student shares code:
1. Ask what they expect vs. what happens
2. Guide them through systematic troubleshooting
3. Ask targeted questions about suspicious areas
4. If they're stuck, give small hints
5. Once bug is found, explain why it happened
6. Suggest similar issues to watch for
```

#### Step 3: Create Debug Template
```
Language: {{LANGUAGE}}
Student level: {{LEVEL}}

Code to debug:
{{CODE}}

Expected behavior:
{{EXPECTED}}

Actual behavior:
{{ACTUAL}}

What student has tried:
{{ATTEMPTS}}

Begin by asking diagnostic questions about the code.
```

#### Step 4: Test with Real Bug
1. Use code you've already debugged
2. Pretend you don't know the bug
3. Follow the AI's guidance
4. See if it helps you find it

#### Step 5: Adjust Teaching Style
**If too much hand-holding:**
```
Give fewer hints. Make questions more open-ended.
```

**If too cryptic:**
```
After 3 wrong guesses, provide more specific guidance.
```

#### Step 6: Add Features
```
After debugging:
- Explain the bug type (syntax, logic, runtime)
- Show how to prevent similar bugs
- Generate a similar exercise for practice
- Provide resources for learning more
```

---

## Advanced Features

### 1. Parameter Tuning

In the configuration panel, you can adjust model parameters:

#### Temperature (0.0 - 2.0)
**What it does:** Controls randomness/creativity

- **Low (0.0 - 0.3):** Predictable, consistent, factual
  - **Use for:** Math problems, facts, code

- **Medium (0.4 - 0.7):** Balanced
  - **Use for:** Most tasks, explanations, studying

- **High (0.8 - 2.0):** Creative, varied, exploratory
  - **Use for:** Brainstorming, creative writing, ideation

**Example:**
```
Temperature 0.1: "The capital of France is Paris."
Temperature 1.5: "Paris, the City of Light and France's magnificent capital..."
```

#### Top-P (Nucleus Sampling)
**What it does:** Alternative way to control randomness

- Default: 0.95 (good for most uses)
- Lower (0.5-0.8): More focused responses
- Higher (0.95-1.0): More diverse possibilities

#### Top-K
**What it does:** Limits vocabulary choices

- Default: 40 (balanced)
- Lower: More predictable
- Higher: More vocabulary variety

**When to adjust:**
- Most students can leave these at default
- Experiment if outputs are too repetitive or too scattered

### 2. Safety Settings

Control content filtering levels:

- **Block none:** Minimal filtering
- **Block few:** Light filtering
- **Block some:** Moderate filtering (default)
- **Block most:** Strong filtering

**For students:**
- Default settings are usually appropriate
- Adjust if legitimate educational content is blocked
- Never compromise safety for convenience

### 3. Context Caching (Advanced)

**What it is:** Reusing large context across multiple requests

**Use case:**
You have a 50-page textbook chapter you'll ask multiple questions about.

**Setup:**
1. Upload/paste chapter once
2. Enable caching
3. Ask multiple questions
4. AI remembers chapter without re-uploading

**Benefits:**
- Faster responses
- More efficient
- Better for long documents

### 4. Fewshot Prompting

**What it is:** Providing examples to guide output format

**Template:**
```
Generate vocabulary flashcards in this format:

Example 1:
Front: "Photosynthesis"
Back: "Process by which plants convert light energy into chemical energy"
Memory Tip: "Photo = light, synthesis = making. Plants make food from light!"
Related: cellular respiration, chloroplast

Example 2:
Front: "Mitosis"
Back: "Cell division resulting in two identical daughter cells"
Memory Tip: "Mitosis = my-toe-sis. Like one toe splitting into two identical toes!"
Related: meiosis, cell cycle

Now create flashcards for: {{TOPIC}}
```

**Why it works:**
- Shows exact format desired
- Demonstrates style and detail level
- Results in consistent outputs

### 5. Chain-of-Thought Configuration

**Built into prompt:**
```
Think through this step-by-step:

1. First, identify what type of problem this is
2. Then, determine what information we have
3. Next, figure out what we need to find
4. Then, choose the appropriate method
5. Finally, solve and verify

Problem: {{PROBLEM}}
```

**In system instructions:**
```
Always show your reasoning process step-by-step before providing answers.
```

### 6. Multi-Turn Conversations

**Setup conversations that build:**

**Turn 1:**
```
I'm going to share a research article. Please read and identify the 5 main arguments.

[Article]
```

**Turn 2:**
```
For each argument, what evidence does the author provide?
```

**Turn 3:**
```
Now identify potential counter-arguments to each.
```

**Turn 4:**
```
Based on this analysis, help me outline a response paper.
```

---

## Best Practices

### 1. Version Control for Prompts

**Keep track of iterations:**
```
Biology Study Guide v1 - Initial version
Biology Study Guide v2 - Added practice questions
Biology Study Guide v3 - Improved format
Biology Study Guide Final - Semester ready
```

**Document changes:**
```
Version 3 changes:
- Increased practice questions from 5 to 10
- Added visual diagram descriptions
- Improved mnemonic devices
- Added connection to previous topics
```

### 2. Test Before Trusting

**Testing protocol:**
1. Test with 3-5 different inputs
2. Verify accuracy of information
3. Check format consistency
4. Assess usefulness
5. Refine based on results

### 3. Combine with Other Tools

**AI Studio + Other Tools:**
- Export JSON to spreadsheets
- Copy structured data to note apps
- Generate content for flashcard apps
- Create imports for bibliography managers

### 4. Collaborate Safely

**Sharing prompts with classmates:**
- Remove personal information
- Check if sharing is allowed
- Give credit to creators
- Contribute improvements back

### 5. Document Your Workflow

**Keep a "prompt journal":**
```
Date: [Date]
Assignment: [What for]
Prompt used: [Name/description]
What worked: [Successes]
What didn't: [Problems]
Improvements: [Ideas for next time]
```

### 6. Regular Review and Updates

**Monthly review:**
- Which prompts do you use most?
- Which need improvement?
- What new needs have emerged?
- Are there new features to leverage?

---

## Common Use Cases

### Use Case 1: Weekly Assignment Workflow

**Setup:**
1. Create "Weekly Assignment Template"
2. Save separate prompts for each step
3. Use consistently each week

**Workflow:**
```
Monday: Use "Reading Summary" prompt for assigned chapters
Tuesday: Use "Concept Mapper" to connect ideas
Wednesday: Use "Practice Problem Generator" for homework
Thursday: Use "Study Guide Builder" for quiz prep
Friday: Use "Weekly Review" to consolidate learning
```

### Use Case 2: Research Paper Pipeline

**Phase 1: Topic Development**
- Prompt: "Research Topic Brainstorm"
- Output: Potential topics with research questions

**Phase 2: Literature Review**
- Prompt: "Article Summarizer"
- Output: Structured summaries of sources

**Phase 3: Outline Creation**
- Prompt: "Research Paper Outliner"
- Output: Detailed outline with source integration

**Phase 4: Draft Review**
- Prompt: "Argument Strength Analyzer"
- Output: Feedback on logic and evidence

### Use Case 3: Exam Preparation System

**3 Weeks Before:**
- Prompt: "Comprehensive Study Plan Generator"
- Create master study schedule

**2 Weeks Before:**
- Prompt: "Practice Exam Generator"
- Create multiple practice tests

**1 Week Before:**
- Prompt: "Weak Area Identifier"
- Focus on gaps in knowledge

**Day Before:**
- Prompt: "Quick Review Generator"
- Create condensed study guide

### Use Case 4: Programming Project Assistant

**Planning Phase:**
- Prompt: "Project Planner"
- Output: Requirements, timeline, milestones

**Development Phase:**
- Prompt: "Code Review Assistant"
- Regular feedback on code quality

**Debugging Phase:**
- Prompt: "Debug Guide"
- Systematic troubleshooting help

**Documentation Phase:**
- Prompt: "Documentation Generator"
- Create code comments and README

---

## Troubleshooting

### Issue: Outputs Are Inconsistent

**Solutions:**
- Lower temperature setting
- Add more specific instructions
- Provide more examples
- Use stricter output format

### Issue: Too Slow for Quick Tasks

**Solutions:**
- Switch to Flash model
- Reduce output length requirements
- Simplify system instructions
- Use Flash-Lite for simple queries

### Issue: Can't Find Saved Prompts

**Solutions:**
- Use search function
- Check sorting/filtering
- Use tags systematically
- Create collections/folders

### Issue: Output Format Breaks

**Solutions:**
- Use JSON schema for structure
- Provide clearer format examples
- Add format validation in prompt
- Use few-shot examples

---

## Getting Started Checklist

**Day 1:**
- [ ] Create AI Studio account
- [ ] Explore interface
- [ ] Try basic prompt
- [ ] Save your first prompt

**Week 1:**
- [ ] Create 3 useful templates
- [ ] Test different models
- [ ] Organize with tags
- [ ] Share one prompt with classmate

**Month 1:**
- [ ] Build prompt library for classes
- [ ] Experiment with system instructions
- [ ] Try structured outputs
- [ ] Refine based on use

**Semester:**
- [ ] Regular prompt maintenance
- [ ] Share successful prompts
- [ ] Learn advanced features
- [ ] Help other students

---

## Resources and Next Steps

### Learn More
- Google AI Studio Documentation
- Prompt engineering guides
- Your school's AI use workshops
- Online communities and forums

### Practice Projects
1. Build a complete study system for one class
2. Create a research pipeline for papers
3. Design a code learning assistant
4. Develop a creative writing workshop

### Share and Collaborate
- Create prompt libraries with classmates
- Contribute to class prompt collections
- Give feedback on others' prompts
- Document success stories

---

## Conclusion

AI Studio is a powerful tool that rewards investment in learning. The time you spend creating good prompts and templates pays off through:

- More efficient studying
- Better quality work
- Deeper understanding
- Consistent results
- Shareable resources

**Remember:**
- Start simple, build complexity gradually
- Test thoroughly before relying on prompts
- Share successes with others
- Always use ethically and within academic guidelines
- Keep learning and refining

**The goal isn't to have AI do your work—it's to have AI help you work better, learn deeper, and achieve more.**

---

*Last updated: October 2025*
*For questions about this guide, contact your course instructor.*
