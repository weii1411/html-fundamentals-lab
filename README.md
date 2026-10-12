# WD-Lab01 — HTML Fundamentals & Document Structure

## Project Overview

This project contains the HTML reconstruction exercises for Part 1 and a personalized portfolio website for Part 2 of WD-Lab01.

## Project Contents

- `index.html`: Personal portfolio website (Part 2).
- `01-heading-hierarchy.html`: B1 — Heading Hierarchy.
- `02-academic-information.html`: B2 — Academic Information.
- `03-favorite-websites.html`: B3 — Favorite Websites.
- `04-article-poem.html`: B4 — Article and Image.
- `05-image-text.html`: B5 — Image and Text Demonstration.
- `06-topic-page.html`: B6 — Topic Page: Exploring Space.
- `reconstruction.html`: Index page linking to all six reconstruction exercises.
- `images/`: Images and other visual resources used by the portfolio and reconstruction pages.

## Technologies and Scope

- HTML5 only.
- Semantic HTML elements, headings, paragraphs, lists, links, images, tables, and forms.
- No CSS, JavaScript, backend, or database functionality is required for this lab.
- The contact form is a static HTML demonstration. It does not send or store messages.

## Running the Project with XAMPP

1. Place the `html-fundamentals-lab` folder in `C:\xampp\htdocs\`.
2. Open the XAMPP Control Panel and start Apache.
3. Open the portfolio in a browser:

   `http://localhost/html-fundamentals-lab/`

4. Use the navigation links on the portfolio to explore its sections.
5. Open the six reconstruction exercises through the links in the Projects section or visit:

   `http://localhost/html-fundamentals-lab/reconstruction.html`

6. Check that all images load and that internal and external links work as expected.

## Validation Checklist

- [ ] The portfolio opens correctly on localhost.
- [ ] All six reconstruction pages open correctly.
- [ ] Images have valid paths and meaningful `alt` text.
- [ ] Internal navigation links point to existing section IDs.
- [ ] The skills and learning-plan tables display their headers and data.
- [ ] Form labels are associated with their corresponding input fields.
- [ ] The static contact form displays correctly.
- [ ] The source files are committed and pushed to GitHub.

## Git and GitHub

Run Git commands from the project directory.

```bash
git status
git add .
git commit -m "feat: complete WD Lab01 assignment"
git branch -M main
git remote -v
git push -u origin main
```

If GitHub authentication is required, sign in using the configured Git credential manager or GitHub CLI.

## Submission Notes

The written report is submitted separately from the website source files. It should include the required student information, environment setup, reconstruction evidence, portfolio changes, HTML explanations, functional evidence, Git/GitHub evidence, interview answers, and self-assessment checklist.

Before submission, verify the repository contents, test the pages on localhost, and capture the screenshots required by the lab instructions.