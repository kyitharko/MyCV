# MyCV

A clean, modular CV template written in LaTeX.

## Structure

| File | Contents |
|---|---|
| `Main.tex` | Document class, packages, styling, and layout |
| `header.tex` | Name, title, and contact information |
| `education.tex` | Education history |
| `experience.tex` | Work experience |
| `skills.tex` | Technical skills |
| `projects.tex` | Personal and open-source projects |
| `awards.tex` | Awards and certifications |

## Usage

1. Edit each `.tex` file with your own details.
2. Compile with:

```bash
pdflatex Main.tex
```

## Requirements

- A LaTeX distribution: [TeX Live](https://www.tug.org/texlive/) (Linux/Windows) or [MacTeX](https://www.tug.org/mactex/) (macOS)
- Packages used: `geometry`, `titlesec`, `enumitem`, `hyperref`, `xcolor`, `tabularx`, `microtype`
