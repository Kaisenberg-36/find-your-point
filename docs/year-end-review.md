# Year-end review: find the point in a year of work

Use find-your-point to turn scattered work records into an evidence-grounded annual review or year-end presentation. Start with materials and an audience; the agent helps discover what is worth communicating and shape the narrative.

**Bring the materials. Keep the judgment accountable. Own the editable result.**

## What to bring

A useful first try is one project or workstream:

- Project updates, milestones, or delivery records.
- Results, metrics, feedback, or decisions with dates and enough context to interpret them.
- The intended audience and occasion, if known.
- The period covered and any files the agent should exclude.

Use files your agent can read and that you are authorized to share with it. You do not need to pre-summarize them or invent an outline. If a key fact is missing, the agent should explain the gap rather than manufacture impact.

## Install and start

Follow the [installation and dependency instructions](USAGE.md). The installation command is:

```sh
npx skills add Kaisenberg-36/find-your-point
```

Then give your agent a folder and a task:

> Use find-your-point for my year-end review. Read the authorized materials in [folder] for [audience], covering [period]. Work out what deserves attention, which contributions and changes are supported, and what remains uncertain. Propose a clear point and organize an editable HTML briefing around what this audience needs to understand. Save it in outputs/year-end-review/. Ask only when a consequential decision cannot be resolved from the materials.

For a small first run, name one project or workstream. Once the result is useful, you can ask the agent to include more material.

### 中文：年终总结、年度工作总结与述职汇报

把资料交给 Agent，不必先整理成流水账或 PPT 大纲。可以这样提出任务：

> 使用 find-your-point 帮我准备年终汇报。读取 [资料文件夹] 中获准使用的材料，时间范围是 [时间]，受众是 [受众]。先找出值得沟通的贡献、变化、问题和依据，再围绕受众需要理解的重点组织表达。不要把完成的活动直接当成业绩，也不要夸大个人贡献或把相关性当成因果。需要我决定的重要方向再问我。请交付可编辑的 HTML 汇报，保存到 outputs/year-end-review/。

Replace the brackets with your context. The Chinese prompt is an alternative way to invoke the same workflow, not a separate product.

## What makes a useful review

The goal is to connect work with its meaning for this audience:

| Starting material | Question the briefing should help answer |
|---|---|
| A long activity list | Which work mattered to the stated purpose, and why? |
| A reported improvement | Is the comparison valid, and what does the evidence support? |
| Several teams' contributions | What can fairly be attributed to this person or team? |
| Mixed results or unfinished work | What was learned, what remains unresolved, and what deserves attention? |

These are reasoning questions, not mandatory chapters. A review can honestly report limited impact or incomplete evidence. Proposed goals or recommendations should fit the user's authorized scope.

## What you receive

A local HTML briefing with its editable companion files and handoff instructions. Open `outputs/year-end-review/index.html` and keep the complete folder.

You can ask the agent to revise emphasis, wording, or structure. If the evidence or reporting period changes, it must also review the conclusions that depended on them.

**Current format:** HTML. This workflow can help with PPT / PowerPoint content planning, but native `.pptx` export is not included.

**Current maturity:** Experimental Alpha. The published demonstration is a synthetic business-review example, not a tested year-end-review benchmark or a customer case. Quality across new tasks and agents still needs real-world feedback.

## Preview before using your files

[Download the example ZIP](https://github.com/Kaisenberg-36/find-your-point/archive/refs/heads/main.zip), extract it, and open `examples/integrated-task-slice-en/index.html`. Keep the extracted folder together. Viewing the included example needs only a browser, without an AI account or build step.

[Back to the project](../README.md) · [Setup and troubleshooting](USAGE.md) · [Share feedback](https://github.com/Kaisenberg-36/find-your-point/issues)
