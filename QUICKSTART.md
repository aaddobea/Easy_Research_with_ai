# Quick Start Guide

Welcome to Awesome AI Research Writing! This guide will help you get started in just a few minutes.

## What's Inside?

This repository contains two main components:

### Part I: Prompt Templates
A collection of carefully crafted prompts for common research writing tasks:
- **Translation** (Chinese ↔ English)
- **Polishing** (making writing more fluent and academic)
- **Shortening/Expanding** (adjusting text length while preserving meaning)
- **Logic checking** (validating argument consistency)
- **Removing AI flavor** (making AI-assisted writing sound more natural)
- **Creating figures and captions** (visualization and documentation)
- **Experiment analysis** (deriving insights from data)
- **Paper review** (critical evaluation from reviewer perspective)

### Part II: Agent Skills
Guidelines for using advanced AI agent features in tools like Cursor and Claude Code for structured paper writing workflows.

## Getting Started (3 Steps)

### Step 1: Choose Your Task
Look at the table of contents in README.md. Find the prompt category that matches what you need.

**Examples:**
- Translating a Chinese abstract to English? → Use [Chinese to English](#chinese-to-english)
- Polishing English writing? → Use [Polish Expressions (English Papers)](#polish-expressions-english-papers)
- Creating a table from experimental results? → Use [Experiment Analysis](#experiment-analysis)

### Step 2: Copy and Adapt the Prompt
1. Find the prompt template you need
2. Copy the entire prompt code block (everything in the ````markdown ... ````)
3. Open your preferred large language model (ChatGPT, Claude, Gemini, etc.)
4. Paste the prompt into the chat
5. Replace the `[Input]` section with your actual content

### Step 3: Use and Refine
- Review the model's output
- If not satisfied, adjust the input or add clarifications
- Save good results for future reference

## Common Use Cases

### Scenario 1: Writing Your First Research Paper Draft
1. Use [Polish Expressions](#polish-expressions-english-papers) to improve initial paragraphs
2. Use [Logic Checking](#logic-checking) to verify argument flow
3. Use [Generate Figure Captions](#generate-figure-captions) for your figures
4. Use [Experiment Analysis](#experiment-analysis) to write results sections

### Scenario 2: Translating a Paper Section
1. Use [Chinese to English](#chinese-to-english) or [English to Chinese](#english-to-chinese) as needed
2. Use [Remove AI Flavor](#remove-ai-flavor-latex-english) to make it sound natural
3. Use [Polish Expressions](#polish-expressions-english-papers) for final touches

### Scenario 3: Preparing for Submission
1. Use [Shortening](#shortening) if you need to reduce word count
2. Use [Remove AI Flavor](#remove-ai-flavor-latex-english) before final submission
3. Use [Review Paper from Reviewer Perspective](#review-paper-from-reviewer-perspective) to anticipate critiques

## Tips for Best Results

### For LaTeX Documents
- Properly escape special characters (%, _, &)
- Keep mathematical formulas in $ symbols
- Copy entire code blocks into the prompt

### For Word Documents
- Use Word-compatible prompts (marked with "Word" in title)
- Output clean text without Markdown formatting
- Paste directly without additional formatting

### General Tips
- **Read the constraints carefully** - they define what the model should do
- **Be specific in your input** - vague inputs lead to vague outputs
- **Test with different models** - results vary between different LLMs
- **Iterate** - if the output isn't quite right, refine your input and try again
- **Save what works** - keep prompts that work well for future use

## Using Agent Skills

If you use Cursor or Claude Code, you can leverage Agent Skills for more powerful workflows:

1. Install OpenSkills (requires Node.js 20.6+)
   ```bash
   npm i -g openskills
   ```

2. Install research-related skills
   ```bash
   npx openskills install zechenzhangAGI/AI-research-SKILLs
   ```

3. In Cursor/Claude Code, describe your task naturally:
   - "Help me write a paper for ICML using this research"
   - "Create a booktabs table with these results"
   - "Generate a LaTeX template for NeurIPS"

See Part II of README.md for detailed skills documentation.

## Recommended LLMs (as of 2024)

For different tasks:
- **General writing**: Gemini-3-pro/flash, Claude-4.5
- **Code generation**: Claude-4.5, Cursor Composer
- **Complex analysis**: Claude-4.5, GPT-4

Performance varies—test with your actual content to find the best fit.

## Troubleshooting

**Q: The output doesn't match my expectations**
- A: Review the constraints section of the prompt. Make sure your input includes all necessary context.

**Q: The result sounds "AI-like"**
- A: Use the [Remove AI Flavor](#remove-ai-flavor-latex-english) prompt on the output.

**Q: Special characters are breaking the formatting**
- A: Make sure to escape special characters (%, _, &) in your input and check the output.

**Q: I get different results each time**
- A: This is normal! LLMs have some randomness. You can:
  - Run again and pick the best output
  - Refine your input for more consistent results
  - Try different models

## Next Steps

1. **Start with one task** that matches your immediate need
2. **Test the prompt** with your actual content
3. **Refine as needed** based on results
4. **Build your collection** of working prompts
5. **Share improvements** back to the community!

## Contributing

Found a better version of a prompt? Have a new use case? Please contribute!
See CONTRIBUTING.md for guidelines.

## Resources

- [Original Chinese Repository](https://github.com/Leey21/awesome-ai-research-writing)
- [OpenSkills Documentation](https://github.com/numman-ali/openskills)
- [Cursor Agent Skills Docs](https://cursor.com/docs/context/skills)
- [ArXiv Translator Skill](https://github.com/Leey21/arxiv-translator)

---

**Happy writing! If you have questions, open an issue on GitHub.**
