# AI vs. Human Knowledge Work — Sector Prioritization Matrix

A strategic assessment tool visualizing which knowledge work sectors are most impacted by AI, featuring an interactive prioritization matrix with job sector bubbles positioned by AI capability and knowledge intensity.

## Overview

This project presents a sector prioritization matrix that helps organizations understand which knowledge work domains are most susceptible to AI automation. The visualization plots various job sectors on a two-axis matrix:

- **X-Axis**: Knowledge Intensity — how much specialized knowledge a role requires
- **Y-Axis**: AI Capability — current AI systems' ability to perform the work

### Quadrants

The matrix is divided into four strategic quadrants:

| Quadrant | Description |
|----------|-------------|
| **Transform Now** | High AI capability + High knowledge intensity — Immediate disruption expected |
| **AI Augment** | High AI capability + Low knowledge intensity — Human-AI collaboration likely |
| **Human Primarily** | Low AI capability + High knowledge intensity — Human expertise remains essential |
| **Monitor** | Low AI capability + Low knowledge intensity — Watch for emerging AI developments |

## Features

- **Interactive Bubble Matrix**: Each bubble represents a job sector, sized by market value
- **Hover Tooltips**: Detailed information appears on hover, showing the most capable AI model for each sector
- **Color-Coded Sectors**: Job sectors are color-coded by industry (Retail, Manufacturing, Professional Services, etc.)
- **AI Model Tracking**: Shows adoption rates for leading AI models (GPT-4, Claude, Gemini, etc.)
- **Strategic Findings**: Key insights about AI's impact on knowledge work
- **Action Priorities**: Recommended actions organized by urgency (Now, Next, Later)

## Data Sources

- **GDP Valuation**: GDPval-AA (February 2026)
- **Compensation Data**: BLS OES 2024
- **GDP Figures**: BEA Q2 2024

## Usage

Simply open [`index.html`](index.html) in a web browser to view the interactive matrix. No build step or server required.

## Project Structure

```text
ai-vs-human-knowledge-work/
├── index.html              # Main visualization file
├── .github/
│   └── workflows/
│       └── pages.yml       # GitHub Pages deployment workflow
└── README.md               # This file
```

## Deployment

This project is configured for GitHub Pages deployment. The workflow in [`.github/workflows/pages.yml`](.github/workflows/pages.yml) automatically deploys the visualization when changes are pushed to the main branch.

## License

CONFIDENTIAL — Revolt BI Strategic Assessment

---

*For questions or additional information about this strategic assessment, contact Revolt BI.*
