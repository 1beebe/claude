# AI Architect Program: Brain + Hands Demo

Demo from February 6, 2026 workshop illustrating how AI agents work: the LLM (brain) orchestrates tools and skills (hands) to accomplish tasks.

## The Demonstration

**Task:** Create a survey insights report from program feedback data

**Architecture Components:**
- **Brain (LLM):** Claude reasoning through the task
- **Hands (Tools):** bash_tool, create_file, present_files for executing work
- **Knowledge (Skills):** frontend-design skill providing design expertise

---

## Example 1: Without Skill Guidance
**Prompt:** 
> I have survey data from my AI program. Create a one-page insights report with key metrics and visualizations.

**What happened:** Brain used tools (Python for analysis, HTML for output) but no design skill → generic result

[View Output](report-V1.html) | [Preview](https://1beebe.github.io/claude/report-V1.html)

---

## Example 2: With Skill Guidance
**Prompt:** 
> can you call the frontend-design skill and do it again?

**What happened:** Brain read skill file first, then used same tools → distinctive, intentional design

[View Output](report-V2.html) | [Preview](https://yourusername.github.io/claude/report-V2.html)

---

## Example 3: Taking It to the Next Level
**Prompt:**
> provide a high level summary of how to turn this workflow into an agent. present the summary in an HTML report

**What happened:** Brain applied architectural thinking - showing how to transform this manual workflow into an automated agent system. Demonstrates moving from "using AI" to "building with AI."

[View Output](agent-workflow-guide.html) | [Preview](https://yourusername.github.io/claude/agent-workflow-guide.html)

---

## Key Takeaway
The brain (LLM) stays the same. The hands (tools) stay the same. But adding **skills** (knowledge bases) transforms output quality. And understanding this architecture lets you build agents that work autonomously - that's the next level.

*AI Architect Program| February 2026*
