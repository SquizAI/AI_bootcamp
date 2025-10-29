# 🎓 AI Academy: Prompt Engineering Skills Camp

> Teaching middle and high school students to harness AI as a powerful learning partner through effective prompt engineering

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Grade Levels](https://img.shields.io/badge/Grades-7%2C%209%2C%2011-blue)](https://github.com)
[![AI Tool](https://img.shields.io/badge/Primary%20Tool-Google%20Gemini-4285F4)](https://gemini.google.com)

---

## 🎯 What is This?

This comprehensive curriculum teaches students in grades 7-11 how to effectively use AI tools—particularly Google Gemini and Gemini AI Studio—as learning partners for their actual coursework. Students learn practical prompt engineering techniques they can apply immediately to improve their studying, problem-solving, and understanding across all subjects.

**Key Focus:** Using AI to *understand* concepts, not just get answers.

---

## ✨ What Makes This Special

🧠 **Immediately Practical** - Students apply techniques to real homework from day one

📚 **Comprehensive Coverage** - Role-based prompting, context engineering, multi-step techniques, few-shot examples, and more

🎓 **Differentiated** - Content adapted for 7th, 9th, and 11th graders

⚖️ **Ethics-First** - Academic integrity woven throughout every lesson

🛠️ **Ready to Teach** - Complete lesson plans, slides, exercises, and assessments

🔄 **Claude Code Enhanced** - Includes specialized AI agents and skills for curriculum development

---

## 📖 Course Structure

### 4-Class Series (90 minutes each)

| Class | Focus | Key Techniques |
|-------|-------|----------------|
| **Class 1** | Foundations + Role-Based Prompting | Prompt anatomy (R.C.T.F.), role assignment, basic context |
| **Class 2** | Advanced Techniques | Multi-step prompting, few-shot examples, constraints |
| **Class 3** | Gemini AI Studio Deep Dive | System instructions, meta-prompting, prompt libraries |
| **Class 4** | Integration & Application | Combining techniques, real projects, sustainable systems |

---

## 🚀 Quick Start

### For Educators

1. **Clone this repository**
   ```bash
   git clone https://github.com/SquizAI/AI_bootcamp.git
   cd AI_bootcamp
   ```

2. **Review the curriculum**
   - Start with [`prompt-engineering-curriculum/README.md`](prompt-engineering-curriculum/README.md)
   - Check out [`prompt-engineering-curriculum/class-01-foundations/lesson-plan.md`](prompt-engineering-curriculum/class-01-foundations/lesson-plan.md)

3. **Prepare to teach**
   - All slides are in markdown (ready to present or convert)
   - Exercises are hands-on and immediately useful
   - Assessments include rubrics and self-evaluation tools

### For Students

1. **Start with Class 1**
   - Learn the foundations even if you've used AI before
   - Practice with your actual homework
   - Build your personal prompt library

2. **Try it immediately**
   - Open [Google Gemini](https://gemini.google.com)
   - Use the templates in [`prompt-engineering-curriculum/class-01-foundations/prompt-templates/`](prompt-engineering-curriculum/class-01-foundations/prompt-templates/)
   - Apply to your real schoolwork

---

## 📁 Repository Structure

```
AI_bootcamp/
├── README.md                           # You are here
├── LICENSE                             # MIT License
├── .gitignore                          # Standard gitignore
│
├── .claude/                            # Claude Code configuration
│   ├── agents/                         # Specialized AI subagents
│   │   ├── lesson-planner.md          # Curriculum development
│   │   ├── slide-designer.md          # Presentation creation
│   │   ├── assessment-builder.md      # Evaluation tools
│   │   ├── github-stylist.md          # Repository formatting
│   │   └── prompt-engineer.md         # Prompt design expert
│   └── skills/                         # Claude Code skills
│       ├── lesson-creator/            # Auto-create lessons
│       ├── slide-builder/             # Auto-create slides
│       ├── assessment-creator/        # Auto-create rubrics
│       ├── github-formatter/          # Auto-format for GitHub
│       └── teaching-prep/             # Auto-prep teaching materials
│
├── prompt-engineering-curriculum/      # Main curriculum
│   ├── README.md                       # Curriculum overview
│   ├── class-01-foundations/          # Class 1 materials
│   │   ├── README.md
│   │   ├── lesson-plan.md             # Minute-by-minute guide
│   │   ├── slides.md                  # Complete slide deck
│   │   ├── exercises/                 # Hands-on activities
│   │   ├── prompt-templates/          # Reusable templates
│   │   └── student-examples/          # Example work
│   ├── class-02-advanced-techniques/   # Class 2 materials
│   ├── class-03-gemini-studio/         # Class 3 materials
│   ├── class-04-integration/           # Class 4 materials
│   ├── resources/                      # Shared resources
│   └── assessments/                    # Evaluation tools
│       ├── README.md
│       ├── prompt-engineering-skills-rubric.md
│       ├── class-01-exit-assessment.md
│       ├── final-project-rubric.md
│       └── student-self-assessment.md
│
└── docs/                               # Claude Code documentation
    ├── cc_github.md                    # GitHub Actions guide
    ├── cc_skills.md                    # Skills documentation
    └── cc_subagents.md                 # Subagents guide
```

---

## 🎓 Learning Objectives

By completing this curriculum, students will be able to:

✅ Craft effective prompts using the R.C.T.F. framework (Role, Context, Task, Format)

✅ Apply role-based prompting to get expert-level help in any subject

✅ Break complex problems into manageable steps using multi-step prompting

✅ Provide clear context to AI tools for more relevant assistance

✅ Use few-shot prompting to guide AI responses with examples

✅ Navigate and utilize Gemini AI Studio for advanced applications

✅ Build personal prompt libraries for specific learning needs

✅ Use AI ethically and appropriately as a learning enhancement tool

✅ Combine multiple techniques to tackle challenging academic work

---

## 🛠️ Tools Used

### Primary Tools
- **[Google Gemini](https://gemini.google.com)** - Free AI assistant for everyday homework help
- **[Gemini AI Studio](https://aistudio.google.com)** - Advanced features with system instructions

### Supplementary Tools
- **NotebookLM** - AI-powered research and note-taking
- **Image Generation Tools** - Visual learning aids (optional)

### Development Tools (For Educators Using Claude Code)
- **Claude Code** - AI-powered curriculum development
- **Custom Subagents** - Specialized AI assistants for lesson planning, assessment design, etc.
- **Skills** - Automated curriculum development workflows

---

## 🤖 Claude Code Integration

This repository includes powerful Claude Code tools for educators:

### Subagents (Specialized AI Assistants)
Located in `.claude/agents/`:
- **lesson-planner** - Creates detailed, minute-by-minute lesson plans
- **slide-designer** - Builds professional presentation slides
- **assessment-builder** - Develops rubrics and evaluation tools
- **github-stylist** - Formats content for professional GitHub presentation
- **prompt-engineer** - Designs effective example prompts and templates

### Skills (Automated Workflows)
Located in `.claude/skills/`:
- **lesson-creator** - Auto-generate complete lesson plans
- **slide-builder** - Auto-create presentation decks
- **assessment-creator** - Auto-generate evaluation rubrics
- **exercise-builder** - Create hands-on student activities
- **github-formatter** - Apply professional GitHub styling
- **curriculum-reviewer** - Comprehensive quality review
- **teaching-prep** - Package all materials for a class session

See [docs/cc_subagents.md](docs/cc_subagents.md) and [docs/cc_skills.md](docs/cc_skills.md) for details.

---

## 📊 Assessment Tools

Comprehensive evaluation toolkit includes:

- **Master Skills Rubric** - Evaluates all 10 core prompt engineering skills
- **Class Exit Assessments** - Quick checks after each session
- **Final Project Rubric** - For culminating prompt library or case study
- **Student Self-Assessment** - Ongoing reflection and growth tracking

All assessments are growth-oriented, measuring application (not just knowledge) with clear criteria and examples.

See [`assessments/README.md`](assessments/README.md) for complete details.

---

## ⚖️ Academic Integrity & Ethical Use

**Important:** This curriculum emphasizes using AI as a learning partner, not a shortcut.

Students are taught to:
- Use AI to understand concepts, not just get answers
- Always cite when AI helps with submitted work
- Follow school academic integrity policies
- Understand the difference between learning assistance and cheating
- Develop their own thinking skills alongside AI use

**For Educators:** Each class includes discussion points about appropriate AI use. Establish clear guidelines for AI use in your classroom.

---

## 🤝 Contributing

We welcome contributions from educators, students, and AI enthusiasts!

**Ways to contribute:**
- Share anonymized student examples of successful prompts
- Suggest improvements to exercises or activities
- Add subject-specific guides
- Report issues or unclear instructions
- Help translate materials to other languages

Please open an issue or pull request to get started.

---

## 📄 License

This curriculum is released under the **MIT License**, making it free to use, modify, and distribute for educational purposes.

See [LICENSE](LICENSE) for full details.

---

## 📧 Contact & Support

- **Questions about the curriculum:** [Open an issue](https://github.com/SquizAI/AI_bootcamp/issues)
- **Feedback or suggestions:** Share your experiences via issues or discussions
- **Collaboration inquiries:** Reach out via GitHub

---

## 🙏 Acknowledgments

This curriculum was developed for real middle and high school students learning to harness AI as a powerful learning tool. Special thanks to all the students who tested these materials and provided feedback.

Built with [Claude Code](https://claude.com/claude-code) using custom AI agents and skills for curriculum development.

---

## 🎯 Ready to Get Started?

**Students:** Head to [Class 1: Foundations](prompt-engineering-curriculum/class-01-foundations/README.md) and begin your prompt engineering journey!

**Educators:** Check out the [Class 1 Lesson Plan](prompt-engineering-curriculum/class-01-foundations/lesson-plan.md) for a complete teaching guide.

**Curriculum Developers:** Explore the [Claude Code tools](docs/) to see how AI agents helped build this curriculum.

---

**Let's teach the next generation to use AI effectively, ethically, and as a true learning partner!** 🚀
