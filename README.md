# sasd-tex-foundation

A curated LaTeX foundation for reusable preambles, style files, macros, templates, and writing conventions — designed for technical documentation, IT handbooks, and structured long-form projects.

## Purpose

This repository collects reusable LaTeX building blocks in a clean and maintainable form.

It is intended as a practical foundation for projects that need more than a one-off document setup:
- shared preambles
- custom style packages
- semantic macros
- consistent box environments
- code and terminal formatting
- structured document conventions

The goal is not to create a flashy framework, but a reliable working base that stays readable over time.

## Scope

This repository is meant for:
- technical documentation
- IT manuals
- developer guides
- project documentation
- structured long-form writing in LaTeX

Typical contents may include:
- reusable `.sty` files
- preamble variants
- macro collections
- example documents
- naming conventions
- layout experiments
- template structures for larger writing projects

## Design Principles

The material in this repository should follow a few simple principles:

- semantic before decorative
- reusable before clever
- explicit before magical
- maintainable before compact
- professional without visual noise

## Suggested Structure

```text
.
├── README.md
├── LICENSE
├── .gitignore
├── examples/
├── styles/
│   └── sasd-itdoc.sty
├── preambles/
│   └── technical-report.tex
└── snippets/
```

## Intended Usage

You can either:
1. copy individual ideas into your own LaTeX project, or
2. reuse style packages and conventions directly as a starting point.

A typical project may then look like this:

```text
main.tex
styles/
  sasd-itdoc.sty
chapters/
  01-introduction.tex
  02-basics.tex
```

and in `main.tex`:

```latex
\usepackage{styles/sasd-itdoc}
```

## Notes

This repository is intentionally conservative in tone and structure.
It should be useful in real work, not only in demonstrations.

## License

MIT License
