# Advanced Prompt Templates

Reusable templates for multi-step, few-shot, and constraint-based prompting. Copy and customize these for your needs.

---

## Template 1: Multi-Step Problem Solving

Use this template when you need to break down a complex problem into manageable steps.

```
I need help solving [TYPE OF PROBLEM] about [TOPIC].

Context: [Brief background about what you're working on]
Goal: [What you're trying to achieve]
Level: [7th/9th/11th grade or college]

Please help me work through this step by step:

Step 1: [First thing you need to do]
- What should I understand or identify?
- What questions should I ask?
- How do I know if I'm right?

Step 2: [Second thing you need to do]
- What's the next piece?
- What should I calculate/analyze/create?

Step 3: [Subsequent steps as needed]
- Continue the progression

Step [Final]: [Checking or interpreting results]
- How do I verify my answer?
- What does this mean in context?
- Why is this the answer?

Please show all work clearly and explain each step.
```

**When to Use:**
- Math problems (algebra, calculus, geometry)
- Science explanations (how processes work)
- Research projects (finding, evaluating, synthesizing information)
- Writing analysis (interpreting literature, arguments)
- History research (understanding causes, effects, significance)

**Example:**
```
I need help understanding how to find the derivative of a function.

Context: I'm in calculus and learning derivatives for the first time.
Goal: Understand both what a derivative IS and how to CALCULATE it.
Level: 11th grade AP Calculus

Please help me work through this step by step:

Step 1: Conceptual understanding
- What is a derivative? (What does it measure?)
- Why do we need derivatives?
- How does this relate to slopes and rates of change?

Step 2: Limit definition
- What is the limit definition of a derivative?
- Why is this the mathematical foundation?

Step 3: Power rule
- What is the power rule for derivatives?
- Why does this rule work?

Step 4: Practice
- Show me how to find the derivative of x^3 using the limit definition
- Then show how to use the power rule on the same problem
- Explain why both methods give the same answer

Step 5: Verification
- How do I know if my derivative is correct?
- What would a wrong answer look like?
```

---

## Template 2: Few-Shot Example Format

Use this template when you want the AI to follow a specific format or pattern.

```
I want you to [TASK] in a specific format. Here are examples:

Example 1:
[INPUT or Context for Example 1]
→
[OUTPUT showing exactly what you want - this is your model]

Example 2:
[INPUT or Context for Example 2]
→
[OUTPUT following the same pattern as Example 1]

Example 3:
[INPUT or Context for Example 3]
→
[OUTPUT following the same pattern]

Now please do the same for:
[YOUR NEW REQUEST]

Remember to:
- Follow the exact format shown
- Match the length and detail of the examples
- Keep the same tone/style as examples
- Include all elements that appeared in examples
```

**When to Use:**
- Creating summaries in a specific style
- Solving similar problems (math, coding)
- Analyzing texts (literary analysis, source evaluation)
- Identifying patterns (parts of speech, logical fallacies, etc.)
- Creating specific content types (study cards, outlines, etc.)

**Example:**
```
I want you to create discussion questions from text passages in a specific format.

Example 1:
Passage: "The frontier was not empty wilderness waiting to be civilized. Rather,
it was home to millions of Native Americans with complex societies, economies, and
governance systems."

Questions:
Q1: What does this passage challenge about the traditional frontier narrative?
Q2: How might understanding Native American societies change our interpretation
of westward expansion?
Q3: What evidence would support or refute the claim in this passage?

Example 2:
Passage: "Photosynthesis occurs through two main stages: light-dependent reactions
that require sunlight, and light-independent reactions (the Calvin Cycle) that
occur regardless of light."

Questions:
Q1: Why is the distinction between light-dependent and light-independent reactions
important?
Q2: What would happen to photosynthesis if only one stage failed?
Q3: How do these two stages work together to create glucose?

Example 3:
Passage: "Elizabeth Bennet's initial prejudice against Mr. Darcy stems not from
evidence but from her wounded pride when he slights her at their first meeting."

Questions:
Q1: How does Austen show that Bennet's judgment is based on emotion, not reason?
Q2: What does this reveal about the dangers of first impressions?
Q3: How does this initial prejudice drive the plot forward?

Now create discussion questions for this passage:
[YOUR PASSAGE HERE]
```

---

## Template 3: Constraints-Based Prompt

Use this template when you need to specify what you DON'T want or set clear boundaries.

```
I'm working on [TASK/ASSIGNMENT]. I need your help, with clear boundaries.

WHAT I WILL do myself:
- [Your responsibility]
- [Your responsibility]
- [Your responsibility]

WHAT I NEED YOUR HELP WITH:
- [Specific type of help needed]
- [Specific type of help needed]

WHAT I DON'T WANT:
- Don't [be specific about what not to do]
- Don't [be specific about what not to do]
- Don't [be specific about what not to do]

[PROVIDE YOUR WORK OR QUESTION HERE]

When helping me:
- [Specific instruction: ask questions instead of giving answers]
- [Specific instruction: explain why, not just what]
- [Specific instruction: point out instead of fix]
```

**When to Use:**
- Maintaining academic integrity
- Getting feedback on your own work
- Learning something, not just getting answers
- Setting up a productive working relationship with AI
- Creating outputs that remain your own

**Example:**
```
I'm writing an analytical essay on [NOVEL]. I need help thinking it through,
with clear boundaries.

WHAT I WILL do myself:
- Read the novel and take my own notes
- Develop my own thesis statement
- Write all paragraphs in my own words
- Interpret and analyze the text

WHAT I NEED YOUR HELP WITH:
- Understanding complex passages
- Identifying themes I might have missed
- Evaluating whether my evidence supports my claims
- Reviewing my writing and suggesting improvements

WHAT I DON'T WANT:
- Don't write any part of my essay
- Don't give me a thesis statement I can copy
- Don't interpret scenes for me
- Don't paraphrase quotes (I'll do that)

Here's the prompt for my essay:
[ESSAY PROMPT]

Here's my current thesis:
[YOUR THESIS]

Here's my first body paragraph:
[YOUR PARAGRAPH]

When you respond:
- Point out where my evidence is strong
- Ask me "How do you know that?" when I make claims without support
- Suggest areas where I need more evidence
- Help me see assumptions I'm making
```

---

## Template 4: Multi-Step + Few-Shot Combined

Use this template when you want to combine step-by-step with example-based guidance.

```
I'm learning to [SKILL/CONCEPT]. I want to understand the process AND see it in action.

Here are examples of the pattern I want to follow:

Example 1:
[Input/Problem]
Step 1: [What example does at this step]
Step 2: [What example does at this step]
[Final Output]

Example 2:
[Input/Problem]
Step 1: [What example does at this step]
Step 2: [What example does at this step]
[Final Output]

Example 3:
[Input/Problem]
Step 1: [What example does at this step]
Step 2: [What example does at this step]
[Final Output]

Now help me work through this problem following the same pattern:
[YOUR NEW PROBLEM]

After showing me the steps, explain:
- Why we did Step 1 first
- How Step 2 built on Step 1
- Why this approach works
```

**When to Use:**
- Learning a process by seeing it applied
- Understanding why steps happen in that order
- Connecting abstract method to concrete examples
- Developing procedural knowledge (how-to skills)

**Example:**
```
I'm learning to analyze primary sources for history class. I want to see the
process applied AND understand why it works.

Here's how I want to approach primary source analysis:

Example 1 - Letter from a historical figure:
[Copy of letter excerpt]
Step 1: Identify context (Who wrote this? When? Why?)
- Author: Alexander Hamilton
- Date: 1790
- Purpose: Explaining his financial plan to President Washington
- Audience: The President
Step 2: Analyze what the author argues
- Hamilton argues that the national government should take on state debts
- He believes this will strengthen the national economy
Step 3: Interpret beyond the surface
- Why might he emphasize "strength" and "unity"?
- What economic interests is he protecting?
[Source Analysis: This letter reveals how Founding Fathers debated federal
power. Hamilton was trying to centralize power, which worried others...]

Example 2 - Photograph from an event:
[Photo description]
Step 1: Identify context
- Photo: Civil rights march
- Date: 1963
- Location: Washington, D.C.
- Photographer: Unknown
Step 2: Describe what you see
- Thousands of people, Black and white, marching together
- Signs with messages about equality
- Police presence on the sides
Step 3: Interpret beyond the surface
- What does the diversity of participants suggest?
- What does the presence of police suggest?
- What is this image trying to communicate?
[Source Analysis: The mixing of races in the march was revolutionary for its
time. The police presence suggests the event was contested...]

Example 3 - Newspaper article from an earlier era:
[Article excerpt]
Step 1: Identify context
- Newspaper: The Boston Globe
- Date: 1770s
- Topic: Taxes and colonial rights
Step 2: Analyze the language and framing
- Uses words like "tyranny" and "liberty"
- Describes colonists as victims
- Questions British authority
Step 3: Interpret beyond the surface
- Whose perspective is this? Who might disagree?
- What is the author trying to persuade readers to believe?
- What's left out of this account?
[Source Analysis: The newspaper uses charged language to rally support for
independence. This represents one perspective, not objective truth...]

Now analyze this primary source following the same three steps:
[YOUR PRIMARY SOURCE HERE]

After you show me the analysis, explain:
- Why we identify context FIRST (before analyzing)
- How understanding the author's purpose helps interpretation
- Why "reading between the lines" matters
```

---

## Template 5: Subject-Specific Advanced Templates

### Math Problem Solving Template

```
I'm solving [TYPE OF PROBLEM: algebra, geometry, calculus, etc.].

My work so far:
[Show what you've done or where you're stuck]

Please help me by:
Step 1: Check my understanding of the concept
- Does [concept] mean [your understanding]?
- Is [my approach] the right way to solve this?

Step 2: Identify where I'm stuck
- I got to [this point]
- Then I tried [this] but it didn't work
- I'm not sure if [specific question]

Step 3: Guide me to the next step
- What should I try next?
- What property/formula/concept applies here?

Step 4: Verify my answer
- Once I solve it, help me check if my answer makes sense
- Show me what the answer means in context

Don't just give me the answer—help me figure it out. Show work clearly.
```

### Literary Analysis Template

```
I'm analyzing [WORK: novel/poem/short story] for [ASSIGNMENT TYPE].

Text/Passage:
[Include the relevant passage or quote]

My analysis so far:
[What you've noticed, what you're confused about]

Please help me:
Step 1: Understand what's happening in this passage
- What is literally happening? [your answer]
- Is there anything I'm misreading?

Step 2: Analyze the literary techniques
- What techniques does the author use? (Metaphor, imagery, dialogue, etc.)
- Point out one I might have missed

Step 3: Connect technique to meaning
- Why does the author use these techniques?
- What effect do they create for the reader?
- How do they develop the theme?

Step 4: Develop my interpretation
- What is my claim about this passage?
- Is it supported by the evidence I've found?
- What else could someone argue?

Help me think through this—don't write my analysis for me.
```

### Research Project Template

```
I'm researching [TOPIC] for [CLASS/ASSIGNMENT].

What I'm trying to understand:
[Your research question or goal]

Sources I've found:
[List sources and briefly note what each covers]

Here's what I'm confused about:
[Specific questions or confusions]

Please help me:
Step 1: Evaluate my sources
- Are these credible sources?
- What's the perspective of each source?
- What sources am I missing?

Step 2: Understand the information
- What do these sources say about [specific question]?
- How do they agree or disagree?
- What's the mainstream view vs. alternative views?

Step 3: Synthesize information
- How should I organize this information?
- What connections exist between sources?
- What patterns do I see?

Step 4: Develop my own understanding
- Based on these sources, what do I think?
- What questions remain unanswered?
- What would I need to research further?

Help me understand, not give me a report.
```

### Writing/Essay Template

```
I'm writing [ESSAY TYPE] about [TOPIC].

My thesis/main idea:
[What you're arguing]

My outline or current draft:
[Show your structure or paragraphs]

Areas where I need feedback:
[What specific aspects concern you]

Please help me:
Step 1: Is my argument clear and specific?
- Can you state back to me what I'm arguing?
- Is it specific or too vague?
- Could I make it stronger?

Step 2: Do I support my argument?
- Where do I have evidence? Where am I just asserting?
- Is my evidence relevant to my claim?
- Do I need stronger evidence?

Step 3: Is my writing clear?
- Are there places where I lost you?
- Do my paragraphs connect logically?
- Does my conclusion follow from my evidence?

Step 4: What's working well?
- What's my strongest point?
- What sentence/passage stands out?
- What should I keep and build on?

Give honest feedback—point out gaps, ask questions, don't rewrite for me.
```

---

## Template 6: Combining All Techniques (Advanced)

Use this when you want maximum clarity and support for complex work.

```
I'm working on [ASSIGNMENT/PROJECT]. I want structured help maintaining academic integrity.

CONTEXT
Topic: [What you're working on]
Goal: [What you're trying to learn/accomplish]
My role: [What you'll do yourself]
Your role: [How you'll support my thinking]

CONSTRAINTS (What I don't want)
- Don't [specific thing]
- Don't [specific thing]
- Keep responses focused on [specific area]

STEP-BY-STEP PROCESS
Here's how I want to work through this:

Step 1: [Your first task - what you need help understanding]
Example of clarity I'm aiming for:
[Show what good understanding looks like]

Step 2: [Your second task - analysis or application]
Example of what I'm trying to create:
[Show what good work looks like]

Step 3: [Your third task - synthesis or evaluation]
Help me think about:
[Specific questions I should be asking]

EXAMPLES (If format is important)
Example 1: [Show expected format/style]
Example 2: [Show expected format/style]
Example 3: [Show expected format/style]

HOW TO HELP ME
When you respond, please:
- Start by asking me questions to check my understanding
- Point out gaps in my thinking without giving answers
- Suggest where I should look for information
- Help me evaluate my own ideas
- Show me WHY something works, not just that it does

[YOUR WORK/QUESTION HERE]
```

---

## Quick Reference: When to Use Each Template

| Template | Best For | Example Use |
|----------|----------|-------------|
| Multi-Step | Complex problems, processes | Math, science, research |
| Few-Shot | Pattern recognition, format | Writing styles, analysis formats |
| Constraints | Maintaining integrity, clear boundaries | Homework help, feedback |
| Combined Multi+Few | Learning procedures through examples | Data analysis, essay structure |
| Subject-Specific | Discipline-specific challenges | Math, literature, research |
| All Combined | Complex projects needing maximum support | Major essays, research papers |

---

## Template Customization Tips

1. **Add specificity:** Replace [BRACKETS] with your actual assignment/topic
2. **Adjust complexity:** Use simpler language for 7th grade, more sophisticated for 11th
3. **Shorten if needed:** Use only the steps that matter for your task
4. **Add constraints:** Include explicit "don't" instructions for academic integrity
5. **Include examples:** Better to show what you want than describe it
6. **Be honest:** Tell the AI your skill level and what you're struggling with
7. **Iterate:** If the first response isn't quite right, clarify and ask again

---

## How to Know if Your Template is Working

Good signs:
- AI response matches the format you specified
- Complexity matches what you asked for
- You understand each part of the response
- The response helps you learn/do better work
- You can do similar tasks independently next time

Signs to revise:
- Response is too complex or too simple
- Format doesn't match your examples
- You're getting answers when you wanted guidance
- The response doesn't address what you actually needed
- Boundaries aren't being respected

If revising: Be specific about what's wrong. "This is still too simple" works better than "I don't like it."

