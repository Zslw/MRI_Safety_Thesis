# MRI Safety Thesis: Translational Force Assessment of Retained Epicardial Leads

This repository contains the ongoing LaTeX-based thesis work for a Master’s degree in Medical Physics. The research aims to develop and validate a method to assess MRI-induced translational forces on retained epicardial leads using a custom-built solenoid and pendulum test rig.

---

## 📁 Project Structure

- `main.tex`: Main LaTeX document that compiles the full thesis.
- `references.bib`: Bibliography database in BibTeX format.
- `Introduction.tex`: Introduction chapter.
- `Mats and Meths.tex`: Main methods and materials file.
- `glossary.tex`: Glossary entries.
- `main.pdf`: Last compiled version (may be outdated).

### 🔬 Experimental Components

- `Assests/`: All images, plots, and engineering drawings.
- `MatsNMets/`: Subsections of the Methods, including:
  - Magnetic field generation
  - Torque testing
  - Translational force derivation
- `Appendices/`: Supplemental material, calibration, and engineering diagrams.
- `LitRev/`: Literature review content covering:
  - MRI safety principles
  - Epicardial lead considerations
- `Formalities/`: Front matter such as cover, abstract, and acknowledgments.

---

## 🧪 Research Focus

**Objective**:  
To experimentally determine the translational forces acting on retained epicardial leads in an MRI environment and propose a standardized measurement approach.

**Core Elements**:
- Solenoid-based field simulation
- 3D-printed pendulum apparatus
- High-resolution displacement tracking
- Field strength variation and correlation to force
- ASTM and AAPM standard references

---

## ⚙️ Compiling the Thesis

You’ll need a full LaTeX environment (TeX Live recommended) with these packages: `graphicx`, `pdfpages`, `xcolor`, `amsmath`, `siunitx`, `biblatex`, etc.

**To compile:**

```bash
latexmk -pdf main.tex
```

or manually:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

This is a work in progress. The layout and content may shift as the research develops. Contributions or feedback welcome via GitHub Issues.


## Author
Daniel Juárez Luna
Master’s Student in Medical Physics
Creighton University
📧 danieljuarezluna@creighton.edu


---

## License
This repository is for academic use. Please request permission before redistribution or citation.
