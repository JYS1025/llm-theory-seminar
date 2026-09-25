# LLM Theory Seminar

An eight-week seminar on the mathematical and computational foundations of modern large language models, with technical study notes available in both Korean and English.

## Seminar Schedule

| Week | Topic | Study Notes | Slides | Video |
|:---:|---|---|:---:|:---:|
| 01 | Gradient Flow & Edge of Stability | [KOR PDF](materials/KOR/week01/Week1_Gradient_Flow_Edge_of_Stability_KOR.pdf)<br>[ENG PDF](materials/ENG/week01/Week1_Gradient_Flow_Edge_of_Stability_ENG.pdf) | Coming soon | Coming soon |
| 02 | Mean-Field Theory & Infinite-Width Dynamics | [KOR PDF](materials/KOR/week02/Week2_Mean_Field_Infinite_Width_KOR.pdf)<br>[ENG PDF](materials/ENG/week02/Week2_Mean_Field_Infinite_Width_ENG.pdf) | Coming soon | Coming soon |
| 03 | Neural Tangent Kernel, Lazy Training & Feature Learning | [KOR PDF](materials/KOR/week03/Week3_NTK_Lazy_Feature_Learning_KOR.pdf)<br>[ENG PDF](materials/ENG/week03/Week3_NTK_Lazy_Feature_Learning_ENG.pdf) | Coming soon | Coming soon |
| 04 | Transformer Expressivity | [KOR PDF](materials/KOR/week04/Week4_Transformer_Expressivity_KOR.pdf)<br>[ENG PDF](materials/ENG/week04/Week4_Transformer_Expressivity_ENG.pdf) | Coming soon | Coming soon |
| 05 | Transformer Computational Theory | [KOR PDF](materials/KOR/week05/Week5_Transformer_Computational_Theory_KOR.pdf)<br>[ENG PDF](materials/ENG/week05/Week5_Transformer_Computational_Theory_ENG.pdf) | Coming soon | Coming soon |
| 06 | In-Context Learning Theory | [KOR PDF](materials/KOR/week06/Week6_In_Context_Learning_Theory_KOR.pdf)<br>[ENG PDF](materials/ENG/week06/Week6_In_Context_Learning_Theory_ENG.pdf) | Coming soon | Coming soon |
| 07 | Chain-of-Thought & Reasoning Complexity | [KOR PDF](materials/KOR/week07/Week7_Chain_of_Thought_Reasoning_Complexity_KOR.pdf)<br>[ENG PDF](materials/ENG/week07/Week7_Chain_of_Thought_Reasoning_Complexity_ENG.pdf) | Coming soon | Coming soon |
| 08 | Length & Algorithmic Generalization | [KOR PDF](materials/KOR/week08/Week8_Length_Algorithmic_Generalization_KOR.pdf)<br>[ENG PDF](materials/ENG/week08/Week8_Length_Algorithmic_Generalization_ENG.pdf) | Coming soon | Coming soon |

> Replace each `Coming soon` entry with a Markdown link when the corresponding slides or recording becomes available.

## Overview

This seminar develops a theory-oriented view of large language models, progressing from optimization dynamics and infinite-width neural networks to Transformer expressivity, computational complexity, in-context learning, reasoning, and length generalization.

The notes are designed for graduate-level study and research presentations. They emphasize mathematical assumptions, derivations, theorem statements, proof sketches, and the distinction between representability, learnability, and observed empirical behavior.

## Repository Structure

```text
llm-theory-seminar/
├── README.md
├── materials/
│   ├── KOR/
│   │   ├── week01/   # Korean source and PDF
│   │   ├── week02/
│   │   ├── ...
│   │   └── week08/
│   └── ENG/
│       ├── week01/   # English source and PDF
│       ├── week02/
│       ├── ...
│       └── week08/
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
cd materials/KOR/week01   # or materials/ENG/week01
xelatex <filename>.tex
xelatex <filename>.tex
```

A TeX distribution with the fonts and packages referenced by each source file is required. Korean documents additionally require a Korean-capable XeLaTeX font setup.

## References & Disclaimer

Primary references are listed in the bibliography of each week's notes. Consult the original papers for authoritative theorem statements, assumptions, notation, and citations.

These materials were prepared for educational and seminar use. They may contain interpretation, reconstructed derivations, or simplifications and should not be treated as a substitute for the cited sources. If you find an error or have a suggested correction, please open an issue or submit a pull request.
