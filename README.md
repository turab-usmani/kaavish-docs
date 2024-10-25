# Kaavish Documents / Templates

This repository contains templates for various documents that are used in the Kaavish project.

## Proposal Template

The [proposal template](/ProposalTemplate/) is a LaTeX document that can be used to write a proposal for the project. It includes sections for the project title, group members, project description, project objectives, project scope, project deliverables, project timeline, and project budget.

Please make the following edits in `main.tex` only:

- edit information about group members in the preamble
- enter appropriate content for each section in the body

`main.tex` is to be compiled using a LaTeX compiler. It automatically includes  the other `.tex` files in this repository. There should not be any need to edit those files or to compile them separately.

## Report Template

The [Report Template](/Report-Template/) is a LaTeX document that can be used to write a report for the project. `report.tex` is the master file which includes other files. Chapters are to be stored in the `chapters` folder and images in the `images` folder. References are listed in `references.bib`. Their citation and printing in handled using the `biblatex` package.
