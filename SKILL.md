---
name: awesome-ai-research-writing
description: Use when helping researchers write, translate, polish, shorten, expand, review, de-AI, caption, or structure academic papers in Chinese or English, especially LaTeX and Word manuscript workflows, research figure/table captions, experimental analysis, reviewer-style critique, and model selection for academic writing tasks.
metadata:
  short-description: Academic research writing prompts and workflows
---

# Awesome AI Research Writing

Use this skill for academic research writing support, especially Chinese/English paper drafting and revision. It packages a prompt library and workflow notes collected for research writing tasks.

## Core Workflow

1. Identify the user's manuscript context: language pair, target venue or journal style, source format such as LaTeX or Word, and whether they need translation, polishing, compression, expansion, logic review, captions, experimental analysis, or reviewer-style critique.
2. Read the relevant section in [references/awesome-ai-research-writing.md](references/awesome-ai-research-writing.md) instead of loading the whole reference by default.
3. Adapt the referenced prompt or workflow to the user's exact input. Preserve technical meaning, equations, citations, labels, and formatting constraints unless the user asks to change them.
4. For LaTeX outputs, keep source clean, escape special characters where needed, and avoid adding decorative Markdown.
5. For Word-oriented Chinese outputs, use plain text with appropriate Chinese punctuation and no Markdown formatting.
6. When revising research text, provide the requested final text first, followed by only the checks, translations, or modification logs that the selected workflow calls for.

## Reference Map

Use `rg` against the reference file to jump to the right section:

- `中转英`, `英转中`, `中转中`: translation and rewriting workflows.
- `缩写`, `扩写`: controlled compression and expansion.
- `表达润色`: English or Chinese academic polishing.
- `逻辑检查`: coherence and reasoning checks.
- `去 AI 味`: reduce formulaic AI-style writing for LaTeX or Word.
- `论文架构图`, `实验绘图推荐`: figure planning and experiment visualization.
- `生成图的标题`, `生成表的标题`: figure and table captions.
- `实验分析`: writing experimental analysis.
- `Reviewer 视角`: full-paper critique from a reviewer perspective.
- `模型选择`: model recommendations for research writing workflows.
- `Skills 的配置`, `Skills 总览`, `使用场景与示例 Prompt`: related agent-skill setup and usage examples.

## Bundled Material

- Main reference: [references/awesome-ai-research-writing.md](references/awesome-ai-research-writing.md)
- Supporting images: [images/](images/)
