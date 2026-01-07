# Resume

LaTeX resume source file with PDF conversion script.

## Files

- `matt_mcmanus_pristine_v2_1page.tex` - Clean, versatile resume format
- `convert_resume.py` - Python script to compile LaTeX to PDF

## Compiling to PDF

### Using the Python Script (Recommended)

```bash
# Convert the resume
python convert_resume.py

# Clean up auxiliary files after conversion
python convert_resume.py --clean
```

The script automatically runs pdflatex twice for proper reference resolution.

### Manual Compilation

```bash
pdflatex matt_mcmanus_pristine_v2_1page.tex
pdflatex matt_mcmanus_pristine_v2_1page.tex
```

## Requirements

- Python 3.7+ (for the conversion script)
- pdflatex (part of TeX Live or MiKTeX)
- Required LaTeX packages: geometry, enumitem, hyperref, titlesec, fontenc, inputenc
