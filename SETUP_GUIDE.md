# Dhanashri GitHub Profile — Installation Guide

## Why the filename appeared on the profile

The Markdown file was uploaded into the README editor as an attachment. GitHub inserted a clickable line such as:

`Dhanashri4422_Premium_README.md`

The profile repository must contain one root file named exactly:

`README.md`

Its contents must be pasted directly into that file. Do not drag the Markdown file into the text editor.

## Package structure

Upload these files while preserving their paths:

- `README.md`
- `assets/header.gif`
- `assets/backend-flow.gif`
- `assets/recruiter-dashboard.svg`
- `assets/footer.svg`
- `.github/workflows/snake.yml`

## Recommended installation order

1. Upload the `assets` directory.
2. Create `.github/workflows/snake.yml`.
3. Run the snake workflow and confirm the `output` branch is created.
4. Replace the root `README.md` last.

This order prevents a temporary broken snake image.

## Snake workflow

1. Open repository **Settings**.
2. Open **Actions → General**.
3. Under **Workflow permissions**, choose **Read and write permissions** when available.
4. Save.
5. Open the **Actions** tab.
6. Select **Generate Contribution Snake**.
7. Click **Run workflow → Run workflow**.
8. Wait for a green check.
9. Open the branch menu and confirm a branch named `output` exists.
10. Confirm the branch contains:
   - `github-contribution-grid-snake.svg`
   - `github-contribution-grid-snake-dark.svg`

## Important

Do not rename `README.md`.
Do not place `README.md` inside a folder.
Do not upload Markdown as an attachment in the editor.
