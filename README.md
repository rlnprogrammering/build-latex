# build-latex
Overleaf is down the day before exam deadline? gg

## How to use:
1. Fork the repository and clone the repository on your pc.
2. Copy the source code of your latex project into the report folder.
3. Push the changes to your branch or main (both should work).
4. A workflow will start under Actions and when done, a PDF of your project will be put in the `build/` folder

**Note:** This will only work if you have a main.tex file in your project like this:
```markdown
report/
├── bibliography.bib
├── build/
├── Images/
├── main.tex
├── preamble.tex
└── src/
```
