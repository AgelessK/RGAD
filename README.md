# Recursive Generative-Adversarial Delegation (RGAD)

*An interdisciplinary synthesis for human-governed multi-agent AI systems.*

This repository contains the preprint, LaTeX source, and supplementary material for the paper *Recursive Generative-Adversarial Delegation: An Interdisciplinary Synthesis for Human-Governed Multi-Agent AI Systems*.

## Quick links

- **Paper (PDF):** [RGAD-preprint.pdf](./RGAD-preprint.pdf)
- **LaTeX source:** [RGAD-preprint.tex](./RGAD-preprint.tex)
- **Bibliography:** [references.bib](./references.bib)
- **Blog post:** [blog-post.md](./blog-post.md)

## What this paper proposes

Multi-agent AI systems increasingly take the form of recursive delegation hierarchies under human oversight — a topology already developed in iterated amplification and factored cognition, hierarchical multi-agent system taxonomies, and production manager-worker frameworks such as MetaGPT and CrewAI. This paper proposes the Recursive Generative-Adversarial Delegation (RGAD) framework not as a structural discovery but as an interdisciplinary synthesis lens over these architectures, integrating Generative Adversarial Networks, Hegelian dialectics, AI debate, actor-critic LLM patterns, and human–machine communication theory.

The paper's central structural claim is the **Generator-Validator coupling thesis**: at any single agent, validation competence is functionally inseparable from sustained generative engagement, because the discriminative judgments a Validator must make depend on the active generative activity that knows what a good candidate looks like. We propose this thesis as a structural-causal generalization of older empirical and philosophical traditions — Goodall's Theory of Expert Leadership, Polanyi's tacit-knowledge framework, and the software-engineering code-review literature — extended to AI delegation in the new cost regime, where generative AI has collapsed the cost of generation while leaving validation roughly unchanged.

Asymmetric delegation (outsourcing generation while nominally retaining validation) therefore atrophies discriminative competence specifically. The coupling thesis relocates the critical infrastructure of human-governed AI from human authority to the **engaged human mind**: the cognitive activity of sustained generative participation, which is what makes apex-level discriminative competence possible at all.

A practitioner-facing shorthand for the structural problem the paper identifies: **the Validator Trap** — where cheap generation drives delegation, and delegation severs the engagement that validation depends on.

## Keywords

Multi-agent AI systems · Recursive delegation · Generator-Validator coupling · Engaged human mind · Validator Trap · Cognitive scaffolding · Human oversight · AI deskilling · Critical infrastructure

## Citing this work

If you cite this preprint, please use:

```bibtex
@misc{kao2026rgad,
  author = {Kao, Ageless},
  title  = {Recursive Generative-Adversarial Delegation: An Interdisciplinary Synthesis for Human-Governed Multi-Agent AI Systems},
  year   = {2026},
  howpublished = {Preprint},
  note   = {\url{https://github.com/AgelessK/RGAD}}
}
```

## Building the paper from source

The paper is written in LaTeX with `natbib` for author-year citations and `plainnat` as the bibliography style. To rebuild the PDF from source:

```bash
pdflatex RGAD-preprint.tex
bibtex RGAD-preprint
pdflatex RGAD-preprint.tex
pdflatex RGAD-preprint.tex
```

Requires a TeX Live distribution with `pdflatex`, `bibtex`, and the standard `natbib` package. The bibliography style file `plainnat.bst` ships with TeX Live by default.

## Repository structure

```
RGAD/
├── README.md                    This file
├── LICENSE                      Creative Commons Attribution 4.0
├── RGAD-preprint.pdf            The paper (compiled PDF)
├── RGAD-preprint.tex            LaTeX source
├── references.bib               BibTeX bibliography (35 entries)
└── blog-post.md                 Blog post (social-ready, ~1,200 words)
```

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt the material for any purpose, including commercially, with appropriate attribution.

## Author

**Ageless Kao**
Group Product Manager, TrendAI, Trend Micro Inc.
Ottawa, Canada
[ageless_kao@trendmicro.com](mailto:ageless_kao@trendmicro.com)

## Acknowledgments

This paper was developed in extended dialogue with Claude (Anthropic), accessed via TrendAI's Claude for Enterprise license, used as a research and editorial scaffold rather than as a substitute for the author's own thinking. While TrendAI provides the licensed AI tool, the work was not commissioned by, reviewed by, or written on behalf of TrendAI or Trend Micro Inc. See the *Acknowledgments* and *Statements and Declarations* sections in the paper for the full disclosure of the working model, AI assistance, and competing interests.

## Status

This work is a preprint, not yet peer-reviewed. Comments, critiques, and engagement are welcome — please open an issue or contact the author by email.
