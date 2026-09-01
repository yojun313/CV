# How to Compile on Overleaf

Overleaf already has `fontawesome5`, `kotex`, and the Noto Sans/Serif CJK KR fonts installed, so no local setup is needed. `main.tex` starts with a `% !TeX program = xelatex` line, so Overleaf auto-selects the XeLaTeX compiler — no manual menu changes needed.

1. Zip this project's files (`main.tex`, `resume.cls`) or push the repo to GitHub.
2. On [Overleaf](https://www.overleaf.com), click **New Project → Upload Project** and upload the zip (or **Import from GitHub**).
3. Click **Recompile**, then use **Download PDF** in the preview pane to get `main.pdf`.
