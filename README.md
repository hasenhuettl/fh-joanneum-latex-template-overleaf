# fh-joanneum-latex-template-vscode
Latex Template for Master Thesis at the Master Program Information Management of FH JOANNEUM Graz. Includes `.vscode` settings for writing thesis with Visual Studio Code.
## Prerequisites
- TexLive installed
- vsCode with extensions
  - [James-Yu.latex-workshop](https://github.com/James-Yu/LaTeX-Workshop)
  - streetsidesoftware.code-spell-checker
  - streetsidesoftware.code-spell-checker-german
- Carlito ([fonts-crosextra-carlito](https://packages.debian.org/stable/fonts/fonts-crosextra-carlito)) as replacement for Calibri on Linux systems

## Use
Adjust Thesis settings in `masterthesis.tex`. `*.tex` files from `chapters` folder are included in `masterthesis.tex`.

Build document with <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>b</kbd>.

Auto-Build `onFileChange` is enabled via `.vscode/settings.json`

Checkout [latex-workshop wiki](https://github.com/James-Yu/LaTeX-Workshop/wiki) for more settings


