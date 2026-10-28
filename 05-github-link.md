# Assignment 5 - GitHub repository link

## What is GitHub?

GitHub is a website where I can save my Git repository online. This way my work is safe, and my teacher can open it with a link.

## Steps I followed to upload (push) my work

**Step 1: Make an empty repository on GitHub**
1. I went to github.com and logged in.
2. I clicked **New repository**.
3. I named it `html-css-assignments`.
4. I left it empty (I did not tick "Add a README", because I already made one on my computer).
5. I clicked **Create repository**.

**Step 2: Connect my folder to GitHub**

In the VS Code terminal, inside my project folder, I typed:
```bash
git remote add origin https://github.com/<your-Bhoomi>/html-css-assignments.git
git branch -M main
git push -u origin main
```
- `git remote add origin ...` tells Git the address of my online repository.
- `git branch -M main` makes sure my branch is named "main".
- `git push -u origin main` uploads my files and commits to GitHub.

**Step 3: Check that it worked**

I refreshed my GitHub page and confirmed that all my files and commits are there.

## Optional: show my work as a website for free

I went to **Settings -> Pages**, chose **Branch: main** and **/root**, and clicked **Save**. After a few minutes my pages are live at:

`https://<your-Bhoomi>.github.io/html-css-assignments/`

## Submission

**Repository link:** `https://github.com/<your-username>/html-css-assignments`
