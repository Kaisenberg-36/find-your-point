# Find-your-Point

**Stop making slides. Start making your point.**

### You bring the materials. Not the answers.

You did the work. You may not yet know what it adds up to—or what is worth telling your audience.

Find-your-Point is an **AI agent skill for document analysis, insight discovery, and presentation storytelling**. It reads your materials, connects the evidence, proposes meaningful angles, and organizes a briefing around what your audience needs to understand. Bring the goals and context you already have; the agent asks for your input when an important direction or necessary judgment cannot be resolved from the materials.

```sh
npx skills add Kaisenberg-36/find-your-point
```

[Try it with your agent](#install--try) · [See the example](#same-materials-better-judgment-better-narrative) · [Setup](docs/USAGE.md)

## Think before presenting

| If this sounds familiar… | What Find-your-Point helps you do |
|---|---|
| “I did so much. How do I show what mattered?” | Find supported contributions and explain their significance, rather than turn an activity list into slides. |
| “There is too much material. I don't know where to start.” | Discover the important relationships and shape the narrative around your audience, without asking you to prepare the answers first. |
| “The AI sounds confident. Can I trust its conclusion?” | Trace important claims to their sources, separate facts from interpretations, and keep missing evidence visible for review. |
| “I need to reuse this after the presentation.” | Keep editable files and the source and decision context needed to revise or hand off the work with an agent. |

A template-first workflow asks **“Which section does this belong in?”**  
Find-your-Point starts with **“What do these materials actually support—and why should this audience care?”**

## Same materials. Better judgment. Better narrative.

*An existing synthetic business-review example, not a customer result.*

A template-first report might follow:

**Background → Complaint Trends → Root Causes → Action Plan**

But did complaints actually increase?

- **The totals cannot establish growth.** May counts complaints; June and July include inquiries too.
- **A useful change is still visible.** A separate, consistently defined complaint-only table shows delivery-delay share rising from 31% to 42%, and system-use share falling from 24% to 18%. Shares do not establish category counts.
- **The explanation remains open.** Delivery and product-use records provide different clues, without proving either a single cause or a combined explanation.

The briefing now has a point: **the complaint mix changed; overall growth and its causes remain unresolved.**

That finding shapes the reading path: **Observation → Separate Clues → Supported Synthesis.**

**1. Establish what can actually be compared.**

![Observation: mixed ticket totals and a comparable complaint-category table](docs/assets/demo-observed.png)

<details>
<summary>2. Examine the delivery and product-use clues separately</summary>

![Separate clues: delivery and product-use evidence with their missing links](docs/assets/demo-clues.png)

The two lines of evidence stay distinct; reading them in sequence does not turn them into a causal chain.

</details>

<details>
<summary>3. Bring the supported findings and unresolved questions together</summary>

![Supported synthesis: the mix shifted, while overall growth and causes remain unresolved](docs/assets/demo-synthesis.png)

The audience gets an analysis they can discuss and review, with the uncertainty attached to the conclusions it affects.

</details>

[Read the synthetic materials](examples/integrated-task-slice/source-packet.md) and [counting-basis correction](examples/integrated-task-slice/source-revision.md).  
**Open the working example:** [download the ZIP](https://github.com/Kaisenberg-36/find-your-point/archive/refs/heads/main.zip), extract it, and open `examples/integrated-task-slice-en/index.html`. Keep the folder together. Viewing needs only a browser.

## Install & try

Run the installation command above in your project and choose your agent. Use a supported Agent Skills-compatible host with file access and the [setup requirements](docs/USAGE.md). Installation has been checked for Codex, Claude Code, Cursor, and OpenCode.

Then give it one small material folder:

> Use find-your-point. Read [folder], help me find what is worth communicating to [audience], and create an editable HTML briefing in outputs/first-briefing/.

No prepared outline is needed. If the audience or goal is unclear, say what you know and let the agent help you clarify it.

Useful for **work summaries, year-end reviews, project retrospectives, business analysis, strategy updates, and executive briefings**. For a year end review or annual review, [start with this guide](docs/year-end-review.md).

中文：工作总结、年终汇报、述职汇报、项目复盘、材料分析与 PPT 内容梳理。[中文首次请求](docs/year-end-review.md#中文年终总结年度工作总结与述职汇报)。

## Yours to keep working with

Open `outputs/first-briefing/index.html` and keep its complete folder: HTML, editable content, styles, scripts, and handoff notes with necessary source context. Ask your agent to revise the message, incorporate new evidence, or adapt it for another audience. Changed evidence means reviewing the conclusions built on it—not just updating a number.

**Experimental Alpha:** editable local HTML and agent-assisted revision are available; quality across tasks and agents is still being explored. Full visual Evidence Mode, seamless cross-agent continuation, richer editing, print/PDF, and advanced visual craft remain in development. Native PPTX export is not included. Source tracing supports review; it does not independently verify source truth.

[Setup & troubleshooting](docs/USAGE.md) · [Feedback](https://github.com/Kaisenberg-36/find-your-point/issues) · [Contribute](CONTRIBUTING.md) · [MIT License](LICENSE)

If the skill helps, a star would be great.
