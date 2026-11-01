# Lab 2: Assignment 02 Pushing and Cloning

## Files
- `index.html` — combined page containing the tasks for this lab.
- `style.css` — CSS rules used by the page.
- `images/` — place any instructor-provided images here.
- `images/screenshot.png` — replace the placeholder with your actual browser screenshot.

## Tasks included
- Git terminal tasks (see instructions below).

## How to run
1. Open `index.html` in a browser, or use VS Code Live Server.
2. Check the layout and interactions.
3. Take a screenshot of the page and save it as `images/screenshot.png`.
4. Replace `YOUR_ROLL_NUMBER` with your actual roll number.


## Git terminal instructions

# Assignment 2: Pushing and Cloning a Repository

Run these commands from the `html-lab` folder created in Assignment 1.

## Task 1
```powershell
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
```

## Task 2
Check the current branch:
```powershell
git branch
```
If it is `main`:
```powershell
git push origin main
```
If it is `master`:
```powershell
git push origin master
```

## Task 3
```powershell
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline
```

**Note:** This assignment uses a local bare repository, not GitHub. Capture your own terminal output for submission.
