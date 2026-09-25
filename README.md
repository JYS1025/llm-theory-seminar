# LLM Theory Seminar

An eight-week seminar on the mathematical and computational foundations of modern large language models, with technical study notes available in both Korean and English.

## Seminar Schedule

| Week | Topic | Study Notes | Slides | Video |
|:---:|---|---|:---:|:---:|
| 01 | Gradient Flow & Edge of Stability | [KOR PDF](materials/KOR/gradient_flow_edge_of_stability_notes.pdf) · [ENG PDF](materials/ENG/week1_gradient_flow_edge_of_stability_en.pdf) | Coming soon | Coming soon |
| 02 | Mean-Field Theory & Infinite-Width Dynamics | [KOR PDF](materials/KOR/mean_field_infinite_width_notes.pdf) · [ENG PDF](materials/ENG/week2_mean_field_infinite_width_en.pdf) | Coming soon | Coming soon |
| 03 | Neural Tangent Kernel, Lazy Training & Feature Learning | [KOR PDF](materials/KOR/ntk_lazy_feature_learning_notes.pdf) · [ENG PDF](materials/ENG/week3_ntk_lazy_feature_learning_en.pdf) | Coming soon | Coming soon |
| 04 | Transformer Expressivity | [KOR PDF](materials/KOR/transformer_expressivity_notes.pdf) · [ENG PDF](materials/ENG/week4_transformer_expressivity_en.pdf) | Coming soon | Coming soon |
| 05 | Transformer Computational Theory | [KOR PDF](materials/KOR/transformer_computational_theory_notes.pdf) · [ENG PDF](materials/ENG/week5_transformer_computational_theory_en.pdf) | Coming soon | Coming soon |
| 06 | In-Context Learning Theory | [KOR PDF](materials/KOR/in_context_learning_theory_notes.pdf) · [ENG PDF](materials/ENG/week6_in_context_learning_theory_en.pdf) | Coming soon | Coming soon |
| 07 | Chain-of-Thought & Reasoning Complexity | [KOR PDF](materials/KOR/chain_of_thought_reasoning_complexity_notes.pdf) · [ENG PDF](materials/ENG/week7_chain_of_thought_reasoning_complexity_en.pdf) | Coming soon | Coming soon |
| 08 | Length & Algorithmic Generalization | [KOR PDF](materials/KOR/length_algorithmic_generalization_notes.pdf) · [ENG PDF](materials/ENG/week8_length_algorithmic_generalization_en.pdf) | Coming soon | Coming soon |

> Replace each `Coming soon` entry with a Markdown link when the corresponding slides or recording becomes available.

## Overview

This seminar develops a theory-oriented view of large language models, progressing from optimization dynamics and infinite-width neural networks to Transformer expressivity, computational complexity, in-context learning, reasoning, and length generalization.

The notes are designed for graduate-level study and research presentations. They emphasize mathematical assumptions, derivations, theorem statements, proof sketches, and the distinction between representability, learnability, and observed empirical behavior.

## Repository Structure

```text
llm-theory-seminar/
├── README.md
├── materials/
│   ├── KOR/          # Korean notes (.tex and .pdf)
│   └── ENG/          # English notes (.tex and .pdf)
├── slides/           # Presentation slides (optional)
└── assets/           # Images and other repository assets (optional)
```

## Materials

| Language | Directory | Formats | Description |
|---|---|:---:|---|
| Korean | [`materials/KOR`](materials/KOR) | `.tex`, `.pdf` | Korean technical study notes for Weeks 1–8 |
| English | [`materials/ENG`](materials/ENG) | `.tex`, `.pdf` | English technical study notes for Weeks 1–8 |

The PDF links in the seminar schedule use repository-relative paths and work directly when this file is placed at the repository root.

## Build

The notes are intended to be compiled with XeLaTeX. Run the compiler twice so that the table of contents and cross-references are resolved correctly.

```bash
cd materials/KOR   # or materials/ENG
xelatex <filename>.tex
xelatex <filename>.tex
```

A TeX distribution with the fonts and packages referenced by each source file is required. Korean documents additionally require a Korean-capable XeLaTeX font setup.

## References & Disclaimer

Primary references are listed in the bibliography of each week's notes. Consult the original papers for authoritative theorem statements, assumptions, notation, and citations.

These materials were prepared for educational and seminar use. They may contain interpretation, reconstructed derivations, or simplifications and should not be treated as a substitute for the cited sources. If you find an error or have a suggested correction, please open an issue or submit a pull request.

