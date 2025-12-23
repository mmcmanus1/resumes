# Resume Collection

This repository contains LaTeX source files and compiled PDFs for various resume versions, organized by focus area.

## Directory Structure

```
resumes/
├── finance/          # Finance-focused resume
├── tech/             # Technology-focused resume
├── research/         # Research-focused resume
└── general/          # General-purpose resume variants
```

## Resume Versions

### Finance
- **matt_mcmanus_finance_perfect_v2_1page** - Optimized for finance and quantitative trading roles

### Tech
- **matt_mcmanus_tech_perfect_v2_1page** - Tailored for software engineering and technical positions

### Research
- **matt_mcmanus_research_perfect_v2_1page** - Emphasizes research experience and academic achievements

### General
- **matt_mcmanus_pristine_v2_1page** - Clean, versatile format suitable for various industries
- **matt_mcmanus_ultra_clean_v2_1page** - Minimalist design with optimal whitespace
- **matt_mcmanus_exceptional_spacing_v2_1page** - Carefully balanced spacing for readability

## Compiling LaTeX Files

To compile a `.tex` file into a PDF:

```bash
pdflatex filename.tex
```

For best results, you may need to run pdflatex twice to properly resolve references:

```bash
pdflatex filename.tex
pdflatex filename.tex
```

## Requirements

- pdflatex (part of TeX Live or MiKTeX)
- Required LaTeX packages (typically included in standard distributions):
  - geometry
  - enumitem
  - hyperref
  - titlesec
  - fontenc
  - inputenc

## Usage

1. Choose the appropriate resume version for your target role
2. Edit the `.tex` file to update content as needed
3. Compile using pdflatex
4. Use the generated PDF for applications

## Version Information

All resumes are version 2, single-page format (`v2_1page`), optimized for ATS (Applicant Tracking Systems) and professional presentation.
