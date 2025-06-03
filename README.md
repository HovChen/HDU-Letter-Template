# HDU-Letter-Template

- **Language**: [English](README.md), [简体中文](README_zh.md)

![Author](https://img.shields.io/badge/Author-Lili_Liang-red)
![Last Commit](https://img.shields.io/github/last-commit/HovChen/HDU-Letter-Template?color=yellow)
![Repo Size](https://img.shields.io/github/repo-size/HovChen/HDU-Letter-Template)
![Language](https://img.shields.io/badge/language-latex-orange)
![License](https://img.shields.io/github/license/HovChen/HDU-Letter-Template?color=green)

This project is a Hangzhou Dianzi University (HDU) letter template based on LaTeX, suitable for formal letters and other document types.

## Project Structure

- `main.tex`: Main LaTeX file, entry point for compilation.
- `letterContent.tex`: Letter content, editable as needed.
- `pic/`: Image resources, including university logo and signature images.
    - `HDU_Logo.png`: HDU logo
    - `HDU_Logo_bg.png`: Logo with background
    - `TOBEsigned.png`: To-be-signed image
    - `signature.png`: Signature image

## Usage

### Local Compilation

1. Install a LaTeX distribution (TeX Live or MiKTeX recommended).
2. Clone or download this repository.
3. Edit `letterContent.tex` to fill in your letter content.
4. In the project root, run:

   ```bash
   xelatex main.tex
   ```

5. The compiled PDF (`main.pdf`) will be generated in the root directory.

### Online Compilation (Overleaf)

1. Visit [Overleaf](https://www.overleaf.com/) and register an account.
2. Create a new project and upload all files from this repo (including `main.tex`, `letterContent.tex`, and all images in `pic/`).
3. Edit `letterContent.tex` as needed.
4. Click "Recompile" to generate the PDF online, no local installation required.

## Notes

- To replace images, simply upload new files to the `pic/` directory.
- To adjust layout or style, modify settings in `main.tex`.

## License

For learning and communication only, commercial use is prohibited.