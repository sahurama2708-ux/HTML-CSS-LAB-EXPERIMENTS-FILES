# Lab 1: Assignment 01 Starting a Git Repository

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

# Assignment 1: Starting a Git Repository

These tasks are terminal/Git activities. Run them in PowerShell or the VS Code terminal.

## Task 1
```powershell
mkdir html-lab
cd html-lab
git init
git config --local user.name "Rama Sahu"
git config --local user.email "YOUR_EMAIL@example.com"
git config user.name
git config user.email
```

## Task 2
Create `index.html` in this folder with:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Lab Home</title>
</head>
<body>
  <h1>Welcome to My HTML Lab</h1>
</body>
</html>
```
Then run:
```powershell
git status
git add index.html
git commit -m "Add home page"
```

## Task 3
Add this below the h1 in `index.html`:
```html
<h2>Next Meeting</h2>
```
Then run:
```powershell
git add index.html
git commit -m "Add next meeting heading"
git log --oneline
```

**Submission:** Capture your own terminal output for each task. Do not submit fabricated terminal screenshots.
