# USF Guest Lecture: Governing Generative and Agentic AI

This repository contains the full teaching package for Dr. Adnan Masood's October 9, 2025 guest lecture at the University of South Florida on governing generative and agentic AI systems. The material blends conceptual framing, quantitative fairness tooling, regulatory guidance, and classroom exercises that can be reused for graduate-level instruction or corporate workshops on responsible AI.

## Contents

### Slide Decks
- **PDF slide exports** (`slides/*.pdf`) covering the complete lecture, including governance taxonomy, fairness metrics, observability patterns, regulatory timelines, role-based responsibilities, and the capstone class exercise.
- **LaTeX beamer sources** (`slides/tex/*.tex`) used to generate the slides. The main deck is `AI_Governance_Guest_Lecture_Masood.tex`, which defines reusable macros for "term triads" (term, definition, intuition), fairness metric summaries, horror-story caselets, and control mappings.

### Interactive Classroom Tools
- **AI Regulatory Navigator** (`AI Regulatory Navigator.html`): a single-page tool that lets students select an industry, map AI use cases to applicable regulations, and test their understanding via a short quiz.
- **RuleScope: The Applied AI Law Challenge** (`RuleScope The Applied AI Law Challenge v2.html`): an immersive scenario-based exercise that asks learners to connect AI deployments with multi-jurisdictional legal obligations, recommended controls, and common pitfalls.
- **AI Governance Control Explorer** (`governance-controls-navigator.html`): a catalogue browser for preventive, detective, and corrective controls that can be filtered by lifecycle stage, control owner, or risk theme.

### Reference Material
- **`Global AI Governance - How EU, U.S., Ch...pdf`**: companion reading on emerging global regulatory regimes.
- **`UST Intro - AI Governance - Dr. Adnan Masood.pptx`**: an introductory slide deck suitable for warm-up sessions or executive briefings.
- **`LICENSE`**: licensing terms for reusing the teaching assets.

## Using the Materials

1. **View the slides**: open the PDF decks directly, or build from source with a LaTeX distribution (`pdflatex` recommended) if you wish to customize content.
2. **Run the interactive tools**: open the HTML files in a modern browser. All dependencies are bundled inline, so no build step is required.
3. **Adapt for your course or workshop**: the beamer sources expose macros for agenda building, fairness metric explanations, agentic AI risk scenarios, and role-specific playbooks. Duplicate and tailor sections as needed.
4. **Stay aligned with policy**: use the interactive navigators to map your organization's AI use cases to obligations, then cross-reference with the control explorer to draft implementation roadmaps.

## Contributing

Issues and pull requests are welcome for improvements such as updated regulatory content, new classroom exercises, or tooling enhancements. Please maintain the existing structure so that lecture facilitators can quickly find slides, interactive assets, and reference documents.

## License

See [`LICENSE`](LICENSE) for details on permitted use of the course material.
