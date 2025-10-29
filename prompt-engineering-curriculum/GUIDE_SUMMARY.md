# Quick Reference: Prompt Engineering Techniques

## Overview
This is a quick-reference companion to the Comprehensive Prompt Engineering Guide. Use this for rapid lookup and assessment planning.

---

## 1. BASIC PROMPT TYPES (7 Types)

| Type | Use When | Key Element |
|------|----------|-------------|
| **Instruction** | Need direct task completion | Clear command |
| **Question** | Seeking specific information | Well-formed question |
| **Completion** | Need help continuing work | Sufficient starting content |
| **Comparison** | Understanding differences/similarities | Clear comparison criteria |
| **Explanation** | Learning new concepts | Specific confusion stated |
| **Summarization** | Condensing information | Desired length/focus |
| **Generation** | Creating practice/examples | Quantity and difficulty specified |

---

## 2. ADVANCED TECHNIQUES (8 Types)

| Technique | Definition | Best For |
|-----------|------------|----------|
| **Zero-Shot** | No examples, just instructions | Common, straightforward tasks |
| **Few-Shot** | 2-4 examples showing pattern | Specific formats, recommended by Google |
| **Multi-Shot** | 5+ examples for complex patterns | Nuanced, varied outputs |
| **Chain-of-Thought** | Show reasoning step-by-step | Complex problem-solving |
| **Self-Consistency** | Multiple solution methods | Verification and accuracy |
| **Tree of Thoughts** | Explore multiple paths | Open-ended problems |
| **Socratic** | Guide through questions | Self-discovery learning |
| **Analogical** | Use familiar comparisons | Abstract concepts |

---

## 3. CONTEXT ENGINEERING (7 Approaches)

| Context Type | What to Include |
|--------------|-----------------|
| **Background** | Grade level, knowledge, learning style |
| **Task** | Assignment details, requirements, timeline |
| **Constraint** | Boundaries and limitations |
| **Temporal** | Time available, deadlines, urgency |
| **Resource** | Available materials and tools |
| **Collaborative** | Group roles, coordination needs |
| **Emotional** | Confidence level, frustration, motivation |

---

## 4. ROLE-BASED PROMPTING (8 Categories)

| Role Type | Example Roles | Purpose |
|-----------|---------------|---------|
| **Subject Expert** | Biology teacher, Math tutor | Content knowledge |
| **Learning Support** | Study coach, Learning mentor | Skills and strategies |
| **Socratic Teacher** | Questioning tutor | Self-discovery |
| **Writing Coach** | Essay editor, Writing tutor | Composition improvement |
| **Test Prep** | Quiz maker, Study guide creator | Assessment preparation |
| **Peer** | Study partner, Knowledgeable classmate | Casual learning |
| **Specialized** | Debate coach, Lab reviewer | Specific expertise |
| **Combined** | Teacher + Coach | Multiple perspectives |

---

## 5. CONSTRAINT-BASED PROMPTING (9 Types)

| Constraint | Purpose | Example |
|------------|---------|---------|
| **Academic Integrity** | Maintain ethical learning | "Don't solve for me - guide my thinking" |
| **Scope** | Limit content boundaries | "Only chapters 5-7" |
| **Format** | Structure output | "Respond in 3 bullet points" |
| **Depth** | Control complexity | "Keep at 9th grade level" |
| **Language** | Vocabulary level | "Define technical terms" |
| **Time-Based** | Manage length/duration | "Brief 5-minute explanation" |
| **Source/Resource** | Reference requirements | "Only peer-reviewed sources" |
| **Perspective** | Viewpoint balance | "Present both sides objectively" |
| **Quantity** | Limit amount | "Exactly 5 examples" |

---

## 6. MULTI-STEP REASONING (8 Approaches)

| Approach | Structure | Best For |
|----------|-----------|----------|
| **Sequential** | Step 1 → 2 → 3 | Ordered procedures |
| **Parallel** | Steps A, B, C (any order) | Independent components |
| **Conditional** | If X then Y, else Z | Decision-based tasks |
| **Iterative** | Repeat and refine | Practice and mastery |
| **Hierarchical** | Main steps with substeps | Complex projects |
| **Diagnostic** | Assess → Identify → Address | Targeted learning |
| **Building** | Foundation → Layers | Progressive understanding |
| **Comparison** | Systematic contrast | Analytical comparison |

---

## 7. CREATIVE VS ANALYTICAL PROMPTS

### CREATIVE Prompts
**Characteristics:**
- Open-ended questions
- Multiple possible answers
- Emphasis on novelty
- "What if" scenarios
- Divergent thinking

**Use For:**
- Brainstorming
- Creative writing
- Innovation
- Multiple solutions
- Original ideas

**Example Keywords:**
"Generate," "Brainstorm," "Imagine," "Create," "Design," "Innovate"

### ANALYTICAL Prompts
**Characteristics:**
- Focused questions
- Specific answers
- Logic and evidence
- Breaking down components
- Convergent thinking

**Use For:**
- Critical thinking
- Problem-solving
- Evaluation
- Evidence-based conclusions
- Systematic examination

**Example Keywords:**
"Analyze," "Evaluate," "Compare," "Assess," "Examine," "Critique"

### HYBRID Prompts
**Combine both:**
- Generate options (creative)
- Then evaluate them (analytical)
- Innovation with feasibility
- Imagination with rigor

---

## 8. POWERFUL COMBINATIONS

### Most Common Effective Combinations:

**1. Role + Context + Multi-Step**
- Comprehensive sequential help
- Expert guidance through process

**2. Few-Shot + Constraints + Role**
- Specific format with boundaries
- Consistent, bounded output

**3. Socratic + Multi-Step + Context**
- Guided discovery approach
- Self-learning through steps

**4. Chain-of-Thought + Few-Shot**
- Reasoning with examples
- Show process and pattern

**5. Tree of Thoughts + Role + Constraints**
- Explore options with expertise
- Bounded creative problem-solving

---

## THE FOUR CORE COMPONENTS (R.C.T.F.)

Every effective prompt should include:

**R - ROLE**
- Who should AI be?
- What expertise needed?

**C - CONTEXT**
- What does AI need to know?
- What's your situation?

**T - TASK**
- What exactly do you want?
- What's the goal?

**F - FORMAT**
- How should response be structured?
- What form do you need?

---

## ASSESSMENT RUBRIC QUICK REFERENCE

### Beginner (Basic)
- ✓ Includes role and context
- ✓ Clear task statement
- ✗ May lack constraints or format

### Intermediate (Proficient)
- ✓ All four components (R.C.T.F.)
- ✓ Relevant constraints
- ✓ One advanced technique
- ✓ Appropriate technique selection

### Advanced (Exemplary)
- ✓ Multiple techniques combined
- ✓ Perfectly calibrated context
- ✓ Creative role use
- ✓ Meta-awareness of strategies
- ✓ Iteration and improvement

---

## COMMON STUDENT MISTAKES BY CATEGORY

### Basic Prompts
- Too vague or generic
- Missing grade level/context
- No format specification
- Assumes AI knows background

### Advanced Techniques
- Using wrong technique for task
- Inconsistent few-shot examples
- Skipping verification steps
- Not iterating when needed

### Context Engineering
- Too little context provided
- Including irrelevant details
- Not updating context
- Missing critical constraints

### Role-Based
- Generic roles without specificity
- Wrong role for task type
- Not matching role to need
- Forgetting grade-appropriate expertise

### Constraints
- Not including academic integrity bounds
- Too restrictive or too loose
- Burying constraints in text
- Conflicting constraints

### Multi-Step
- Steps not truly sequential
- Skipping verification
- Too many or too few steps
- Missing synthesis

---

## WHEN TO USE WHAT: DECISION TREE

```
START: What's your task?

├─ Need to LEARN concept?
│  ├─ Simple concept → Explanation Prompt + Role + Context
│  └─ Complex concept → Multi-Step + Chain-of-Thought
│
├─ Need to CREATE something?
│  ├─ Brainstorming → Creative Prompt + Generation
│  ├─ Specific format → Few-Shot + Format Constraints
│  └─ Complex project → Hierarchical Multi-Step
│
├─ Need to ANALYZE something?
│  ├─ Compare/contrast → Comparison + Analytical
│  ├─ Evaluate argument → Analytical + Chain-of-Thought
│  └─ Break down complex → Multi-Step Analysis
│
├─ Need to PRACTICE?
│  ├─ Math/Science → Generation + Self-Consistency
│  ├─ Test prep → Few-Shot + Iterative
│  └─ Skills development → Socratic + Iterative
│
└─ Need to SOLVE problem?
   ├─ Clear solution path → Sequential Multi-Step
   ├─ Multiple approaches → Tree of Thoughts
   └─ Want to figure out → Socratic + Chain-of-Thought
```

---

## GRADE-LEVEL ADAPTATIONS

### 7th Grade
- Simpler roles and context
- 2-3 steps maximum
- 2 few-shot examples
- Clear, structured constraints
- More scaffolding

### 9th Grade
- Balanced complexity
- 3-5 steps
- 2-4 few-shot examples
- Multiple constraints
- Some independence

### 11th Grade
- Advanced combinations
- Complex multi-step sequences
- Optimal example selection
- Sophisticated constraints
- Meta-cognitive awareness

---

## ETHICAL USE GUIDELINES

### ALWAYS Include:
- "Don't solve for me - help me understand"
- "Guide my thinking, don't give answers"
- "Explain the concept, don't do my work"

### NEVER Ask:
- "Write my essay for me"
- "Solve my homework"
- "Give me answers without explanation"

### GRAY AREA - Clarify:
- Getting examples (OK if you learn from them)
- Checking work (OK if you understand corrections)
- Brainstorming (OK if you develop ideas yourself)

---

## QUICK TEMPLATE LIBRARY

### General Learning Template
```
Act as a [subject] [role] for [grade level].

I'm learning [topic]. I understand [what you know] but
I'm confused about [specific confusion].

[Choose: Multi-step, Few-shot, or Socratic approach]

Don't [academic integrity constraint].
Keep it [depth/language level].
```

### Test Prep Template
```
Act as a test prep tutor.

I have a test on [topic] covering [scope] in [timeframe].

Generate [number] practice [questions/problems]:
- Difficulty: [level]
- Format: [type]
- Focus areas: [specific topics]

Check my answers but help me learn from mistakes.
```

### Essay Help Template
```
Act as a writing coach for [grade level].

I'm writing a [type] essay about [topic].
Requirements: [specific requirements]
Currently working on: [what part]

Help me [specific need] but don't write it for me.
```

### Problem-Solving Template
```
Act as a [subject] tutor.

Problem: [state problem]

Guide me through solving this step-by-step:
1. [First step name]
2. [Second step name]
3. [etc.]

Show reasoning at each step.
Check if answer makes sense at the end.
```

---

## NEXT STEPS FOR STUDENTS

1. **Practice with examples** - Try each technique once
2. **Find your favorites** - What works for your learning style?
3. **Build a library** - Save prompts that work well
4. **Experiment with combos** - Mix techniques creatively
5. **Iterate and improve** - Refine based on results
6. **Share and learn** - Exchange effective prompts with peers
7. **Reflect on process** - Understand WHY prompts work

---

## RESOURCES

- Full Comprehensive Guide: `COMPREHENSIVE_PROMPT_ENGINEERING_GUIDE.md`
- Class Materials: Individual class folders
- Prompt Templates: `prompt-templates/` in each class folder
- Student Examples: `student-examples/` in each class folder

---

**Use This Guide For:**
- Quick reference during practice
- Assessment planning
- Technique selection
- Curriculum development
- Student handouts

**Document Version:** 1.0
**Companion to:** Comprehensive Prompt Engineering Guide
