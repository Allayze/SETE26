# SETE 2026 — AI Agents 101: What Every Systems Engineer Needs to Know

Interactive tutorial by Fabrice Theodore, CPEng | Allayze

[![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Allayze/SETE26/main)

## Licence and Usage

These materials are provided for personal learning and reference. You are welcome to revisit the notebooks and share the GitHub link with colleagues. Any commercial use, reproduction, or adaptation of this material — including use in internal training programmes, client deliverables, or derivative works — requires prior written permission. Contact: fabrice.theodore@allayze.com.au

## Quick Start

### Option A: Google Colab (recommended)

1. Download each `.ipynb` file from this repo
2. Go to [colab.research.google.com](https://colab.research.google.com)
3. File > Upload notebook > select the downloaded file
4. Enter the API key provided in the session
5. Run cells top to bottom with Shift + Enter

### Option B: Binder (if Colab is blocked)

1. Click the **Launch in Binder** badge above
2. Wait 1-2 minutes for the environment to build
3. Click on the notebook you want to open
4. Enter the API key provided in the session
5. Run cells top to bottom with Shift + Enter

## Notebooks

| Notebook | Topic | Duration |
|----------|-------|----------|
| Notebook 1 — The Power of the API | What a single API call can (and cannot) do | Hour 1 |
| Notebook 2 — Building a Real Agent | The DeepAgents harness: AGENT.md, SKILL.md, tools, memory | Hour 2 |
| **Hour 3 — Build Your Own Agent** (pick one per group) | | |
| Notebook 3A — The Traceability Tax | Requirements traceability agent (worked example) | Hour 3 |
| Notebook 3B — The Compliance Marathon | Compliance verification agent (scaffolded) | Hour 3 |
| Notebook 3C — The Test Evidence Hunt | Test evidence collection agent (scaffolded) | Hour 3 |

## API Key

During the live session, a shared API key will be provided. After the tutorial, you can get your own key to keep experimenting:

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Create a free account (no credit card required for the free tier)
3. Navigate to **API Keys** and click **Create Key**
4. Copy the key and paste it into the first cell of any notebook:

```python
API_KEY = "sk-ant-your-key-here"
```

The free tier includes enough credits to run through all three notebooks multiple times. For pricing details, see [anthropic.com/pricing](https://www.anthropic.com/pricing).

## Requirements

All dependencies are installed automatically when you run the first cell of each notebook. If using Binder, they are pre-installed via `requirements.txt`.

## Presentation Slides

The tutorial slides are available in this repo: [Scenario_Introduction_Slides.pptx](Scenario_Introduction_Slides.pptx)

For the full presentation deck, contact Fabrice directly.

## About Allayze

[Allayze](https://allayze.com) is a systems engineering and AI consultancy that helps defence, transport, and aerospace organisations adopt AI agents for document-heavy, standards-driven engineering work.

We build multi-agent platforms that handle the 60% of SE effort that goes to requirements review, traceability maintenance, compliance checking, and test evidence compilation — so your engineers can focus on judgment, trade-offs, and risk decisions.

**What we offer:**

- AI agent strategy and proof-of-concept builds for your engineering workflows
- On-premise deployment for classified and sensitive environments
- Training and workshops tailored to your team's domain and toolchain

## Contact

Fabrice Theodore, CPEng NER MIEAust | INCOSE ASEP
Director and Founder, Allayze
[allayze.com](https://allayze.com) | [LinkedIn](https://www.linkedin.com/in/fabricetheodore/)
