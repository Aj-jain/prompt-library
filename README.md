# Prompt Library

A curated collection of prompts for various tasks and purposes. This library is organized by category and designed to be easily searchable and reusable across different projects.

## 📋 Table of Contents

- [Directory Structure](#directory-structure)
- [How to Use](#how-to-use)
- [Naming Convention](#naming-convention)
- [Categories](#categories)
- [Contributing](#contributing)

## 📁 Directory Structure

```
prompt-library/
├── README.md
├── .gitignore
├── code-review/              # Prompts for code review tasks
├── documentation/            # Prompts for documentation writing
├── debugging/                # Prompts for troubleshooting and debugging
├── brainstorming/            # Prompts for ideation and creative thinking
├── technical-writing/        # Prompts for technical content
├── data-analysis/            # Prompts for data-related tasks
├── development/              # Prompts for coding and development
└── general/                  # General-purpose prompts
```

## 🚀 How to Use

### 1. Finding a Prompt

Browse the directories based on your task category. Each prompt file contains:
- **Title**: Clear description of the prompt's purpose
- **Context**: When and how to use the prompt
- **Template**: The actual prompt with placeholders (in `{curly braces}`)
- **Example**: A sample use case
- **Notes**: Additional tips and variations

### 2. Using a Prompt

1. Navigate to the relevant category folder
2. Open the prompt file (`.md` format)
3. Copy the prompt template
4. Replace placeholders (`{like_this}`) with your specific content
5. Paste into your AI tool (ChatGPT, Claude, etc.)

### 3. Customizing

Feel free to:
- Adapt prompts to your specific needs
- Combine multiple prompts for complex tasks
- Create variations for different contexts
- Test and refine for best results

## 📝 Naming Convention

Prompts follow this naming structure:

```
{category}_{task-type}_{specificity}.md
```

### Examples:
- `code-review_pr-analysis_performance.md` — Code review prompt focused on performance analysis
- `documentation_api_quickstart.md` — Documentation prompt for API quickstart guides
- `debugging_error-trace_javascript.md` — Debugging prompt for JavaScript error traces
- `brainstorming_feature-ideas_saas.md` — Brainstorming prompt for SaaS feature ideas
- `general_summary_technical.md` — General summary prompt for technical content

### Naming Guidelines:
- Use **lowercase** with **hyphens** for separators
- Be **specific** about the task type
- Keep filenames **concise** but descriptive
- Use `.md` extension for all prompt files

## 🏷️ Categories

| Category | Purpose | Examples |
|----------|---------|----------|
| **code-review** | Code review and analysis | PR analysis, performance review, security check |
| **documentation** | Writing and structuring docs | API docs, user guides, tutorials |
| **debugging** | Troubleshooting and fixing issues | Error analysis, bug investigation |
| **brainstorming** | Ideation and creative thinking | Feature ideas, solutions, design concepts |
| **technical-writing** | Technical content creation | Blog posts, whitepapers, case studies |
| **data-analysis** | Data interpretation and insights | Report generation, trend analysis |
| **development** | Coding and implementation | Code generation, refactoring, architecture |
| **general** | Multi-purpose prompts | Summaries, outlines, research |

## 🤝 Contributing

To add a new prompt:

1. Choose the appropriate category (or create one if needed)
2. Follow the naming convention
3. Use the standard prompt template format
4. Include clear context, examples, and notes
5. Test the prompt before committing
6. Create a branch and submit your changes

### Prompt Template

```markdown
# [Prompt Title]

## Purpose
Brief description of what this prompt does and when to use it.

## Context
Details about:
- Best use cases
- Prerequisites
- Intended audience

## Template

[Your prompt here with {placeholders} for variables]

## Example

**Input:**
{Sample input with values filled in}

**Output:**
{Expected output}

## Notes
- Tip 1
- Tip 2
- Variations or similar prompts

## Tags
`tag1` `tag2` `tag3`
```

## 📚 Quick Links

- [Code Review Prompts](./code-review/)
- [Documentation Prompts](./documentation/)
- [Debugging Prompts](./debugging/)
- [Brainstorming Prompts](./brainstorming/)
- [Technical Writing Prompts](./technical-writing/)
- [Data Analysis Prompts](./data-analysis/)
- [Development Prompts](./development/)
- [General Prompts](./general/)

## 📖 Version History

- **v1.0.0** (Initial) — Repository setup and initial structure

---

**Happy prompting!** 🎯