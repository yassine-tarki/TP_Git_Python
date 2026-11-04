# My Study Assistant (Lab 1: Python and Git)

## Introduction

- **Lab title:** Lab 1 – My Study Assistant, a small Python program built with Git and GitHub.
- **Purpose of the program:** The program talks to a student. It says hello and asks a few simple questions about the study session.
- **Role of main.py:** main.py is the only code file. It holds the whole program. You run this file to start the program.

## Versions V1 to V4

I wrote the same main.py four times. Each time I added one new thing.

| Version | What changed | Where I worked |
|---|---|---|
| V1 | The first version. It shows a welcome message. | On my computer only |
| V2 | The program now asks for the user's first name. I sent this version to GitHub for the first time. | My computer, then GitHub |
| V3 | The subject was added on GitHub. I then brought it to my computer with `git pull`. | GitHub, then my computer |
| V4 | The program now asks for the study time. I sent the new version to GitHub with `git push`. | My computer, then GitHub |

V4 is the final version.

## How to run the program

**What you need**

- Python, installed on your computer
- Visual Studio Code
- The folder `TP_Git_Python` (it holds main.py)

**Steps**

1. Open the folder `TP_Git_Python` in Visual Studio Code.
2. Open the terminal: Terminal > New Terminal.
3. Type this command and press Enter:

```
py main.py
```

On some Windows computers this command does not work. If so, use this one:

```
python main.py
```

**What the program asks (V4)**

1. Your first name
2. The subject you want to study
3. The study time, in minutes

## Git commands used

| Command | What it does | How I used it in Lab 1 |
|---|---|---|
| `git init` | Starts Git in the folder. | I ran it once at the start, so Git could follow my project. |
| `git add` | Chooses the files to save next. | I used it after each change to main.py. |
| `git commit` | Saves the chosen files as one step, with a short note. | I made a commit for each version. |
| `git push` | Sends my commits to GitHub. | I used it in V2 (first time) and in V4. |
| `git pull` | Brings the new changes from GitHub to my computer. | I used it in V3, to get the subject added on GitHub. |
