# Resume

This repository contains the LaTeX source for my resume.

## Contents

- `Nahid_Hasan_Sagar_Resume.tex` - main LaTeX source
- `Nahid_Hasan_Sagar_Resume.pdf` - compiled resume output
- `Nahid_Hasan_Sagar_Resume.aux`, `.fdb_latexmk`, `.fls`, `.log`, `.out`, `.synctex.gz` - build artifacts

## Requirements

To build the resume locally, install a LaTeX distribution such as:

- [MacTeX](https://tug.org/mactex/)
- [TeX Live](https://www.tug.org/texlive/)

The document uses these common packages:

- `geometry`
- `hyperref`
- `fontawesome5`
- `tabularx`
- `titlesec`
- `enumitem`
- `microtype`
- `xurl`
- `newtxtext`

## Build

From the repository root, run:

```bash
latexmk -pdf Nahid_Hasan_Sagar_Resume.tex
```

This produces `Nahid_Hasan_Sagar_Resume.pdf` in the same directory.

If you want a clean rebuild, use:

```bash
latexmk -pdf -g Nahid_Hasan_Sagar_Resume.tex
```

## Notes

- The resume header includes clickable links for email, phone, LinkedIn, and GitHub.
- Font Awesome icons are used for the contact section.
- The repository is set up as a simple one-file LaTeX project, so no extra build system is required.
