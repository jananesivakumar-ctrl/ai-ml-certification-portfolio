# Upload This Portfolio to GitHub

Suggested repository name: `ai-ml-project-portfolio`

Suggested description:

> Seven Python projects covering data analysis, machine learning, computer vision, retail prediction and deployment, and retrieval-augmented question answering.

1. Extract the downloaded ZIP on your computer.
2. Create a new GitHub repository using the name above. If you want it visible to recruiters and collaborators, choose Public. Leave automatic README and license creation unchecked because this package already includes a README.
3. On the empty repository page, click “uploading an existing file.” For an existing repository, use Add file → Upload files.
4. Open the extracted `ai-ml-project-portfolio` folder. Drag its README.md, projects folder, and other contents into the upload area. Upload the contents, rather than the outer folder or ZIP, so the main README appears at the repository root.
5. Use `Add AI and machine learning project portfolio` as the commit message, and select Commit changes.
6. Open the repository and check that each project link leads to its folder.

## Before Publishing

- Revoke or rotate the Hugging Face tokens present in the original SuperKart export. They have been replaced in this package, but the original credentials may still be active.
- Add original `.ipynb` notebooks when available. Place each in its matching project folder; do not rename an HTML file to `.ipynb`.
- Keep datasets separate unless you have permission to redistribute them.
- Add public demo links only for deployments that you have checked are working.

## What Was Prepared

Seven HTML reports were renamed to `report.html` within separate project folders. Hugging Face token strings were removed from the SuperKart copy, and personal workstation usernames in file paths were replaced. Source attachments were not modified. The project READMEs summarize the supplied work; saved results were not re-run.

The Medical Assistant export has inconsistent narrative/model names; its README uses the model specified in the code. The Personal Loan, EasyVisa, and SuperKart READMEs explain test-set involvement in model selection.
