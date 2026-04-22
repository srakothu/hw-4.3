Final verification includes checking that both main and dev branches are visible in the public repo.
# Plan Document

## 1. Project Plan

### Goals
- Recreate and maintain a reproducible Quarto report for HW 4.3.
- Keep the report aligned with the submitted PDF.
- Make sure the final repo includes both the source QMD and output PDF.

### Needs
- Quarto
- R and required packages
- `calcium.csv`
- the HW 4.3 PDF
- a public GitHub repository

### Steps
1. Place `hw_4_3_rakothu.qmd`, `HW_4.3.pdf`, and `calcium.csv` in the repo.
2. Check that all file paths are relative.
3. Render the QMD to PDF locally.
4. Review the output for tables, figures, captions, and appendix sections.
5. Commit the final working files and verify the repo is complete.

## 2. Repo Setup and Maintenance Plan

### Goals
- Show clear evidence of version control workflow.
- Keep the main branch current.
- Maintain a repo that is easy for the grading team to inspect.

### Needs
- a `main` branch
- a `dev` branch
- at least two issues
- meaningful commits
- at least one pull request
- a public repo URL

### Steps
1. Create the public repo and push the starting files.
2. Create a `dev` branch and do edits there.
3. Open at least two GitHub issues tied to the work.
4. Make several small commits with meaningful messages.
5. Open a pull request from `dev` into `main`.
6. Merge the pull request and confirm `main` is up to date.
7. Double-check that the repo contains the PDF, QMD, README, PLAN, and `calcium.csv`.
