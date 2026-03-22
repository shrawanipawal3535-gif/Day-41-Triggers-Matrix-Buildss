# Day-41-Triggers-Matrix-Buildss

## Task 1: Trigger on Pull Request

Create .github/workflows/pr-check.yml

Trigger it only when a pull request is opened or updated against main

Add a step that prints: PR check running for branch: <branch name>

Create a new branch, push a commit, and open a PR

Watch the workflow run automatically

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1d049095-1242-456d-870c-9dfef000d31f" /> <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1a7e97f0-8523-473e-99e1-cb01200b4a3f" /> <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/2121801f-9970-4c6c-900f-2ab4378a6647" />

## Task 2: Scheduled Trigger

Add a schedule: trigger to any workflow using cron syntax

Set it to run every day at midnight UTC

Write in your notes: What is the cron expression for every Monday at 9 AM?

## Task 3: Manual Trigger

Create .github/workflows/manual.yml with a workflow_dispatch: trigger

Add an input that asks for an environment name (staging/production)

Print the input value in a step

Go to the Actions tab → find the workflow → click Run workflow

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7e2b5fed-f45b-4c61-888f-b3ba9c9354a3" />

## Task 4: Matrix Builds

Create .github/workflows/matrix.yml that:

Uses a matrix strategy to run the same job across:

Python versions: 3.10, 3.11, 3.12

Each job installs Python and prints the version

Watch all 3 run in parallel

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/38da730b-8de7-4784-a0cd-59650fd21f6b" />

## Task 5: Exclude & Fail-Fast

In your matrix, exclude one specific combination (e.g., Python 3.10 on Windows)

Set fail-fast: false — trigger a failure in one job and observe what happens to the rest




