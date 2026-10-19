# Project Template

This repository is a starting point for a student data-science project. It
provides a proposal, a Quarto presentation, and a place to document project
data. Graduate students should also complete the written report template.

## Start a project

Create a new repository from this template so your project has its own Git
history. Keep the repository private or public according to the course
instructions. Replace the prompts in the templates with your own work, and
remove instructions that do not apply.

Undergraduate projects do not require a written report. Remove the `report/`
folder from an undergraduate project repository. Graduate students should keep
it and complete `report/report.qmd`.

## Project files

- `proposal/` contains the project proposal and its references.
- `presentation/` contains the final presentation source.
- `data/` contains small, shareable project data and documentation.
- `report/` contains the graduate written-report template.
- `references.bib` stores BibTeX entries used by the proposal and report.
- `apa.csl` formats citations and references in APA style.

Keep an original data file unchanged. Document its source, collection date,
coverage, units, and license in `data/README.md`. Do not commit private,
sensitive, or restricted data. For large files, document how to access the data
and keep it outside Git unless the source permits redistribution and the course
instructions allow it.

Use relative paths in code and documents so collaborators can reproduce the
project from a fresh checkout. Keep analysis code with the document that
explains it or in a clearly named source file.

## License

The template text and structure are licensed under
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). The APA
citation style file has its own license notice. This template does not choose a
license for student-created work or third-party data; document applicable
licenses and permissions for each project.
