# AI-Powered Productivity Workflow

## Project Purpose

This repository documents the setup and configuration of AI-assisted development tools as part of the 100Hires portfolio project.

The objective was to create a working development environment using Cursor, Claude Code, Codex, Git, and GitHub while documenting the setup process, challenges encountered, and lessons learned.

---

## Tools Installed

- Cursor IDE
- Claude Code
- OpenAI Codex
- Git
- GitHub
- GitHub Desktop

---

## Setup Process

### Step 1: Installing Cursor IDE

I downloaded and installed Cursor IDE successfully. After installation, I verified that the editor launched correctly and was able to open project folders.

### Step 2: Installing Claude Code

I installed Claude Code and attempted to verify the installation using PowerShell.

Initially, PowerShell blocked script execution because Windows execution policies were restricting local scripts.

**Solution:**

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

After updating the execution policy, Claude Code installed correctly and the version command worked successfully.

### Step 3: Setting Up Claude Authentication

When launching Claude Code, the browser did not automatically open for authentication.

Claude provided a login URL in the terminal. I manually opened the URL, logged into my Claude account, and completed the authentication process successfully.

### Step 4: Installing OpenAI Codex

I downloaded the Codex application from OpenAI.

Initially, I searched for a Codex extension inside Cursor but could not find one.

After further investigation, I learned that Codex is provided as a separate application rather than a Cursor extension.

I installed Codex, authenticated successfully, and verified that it was working properly.

### Step 5: Creating a GitHub Repository

I created a public GitHub repository named:

**ai-powered-productivity-workflow**

The repository will be used to track setup progress and future project work.

### Step 6: Opening the Repository in Cursor

I opened the repository in Cursor and created the project documentation files.

The following files were created:

- README.md
- LESSONS_LEARNED.md
- SETUP_LOG.md

### Step 7: Initializing Git

When checking repository status, Git returned:

> fatal: not a git repository

This occurred because Git had not yet been initialized in the project folder.

**Solution:**

```bash
git init
```

I then verified the repository status successfully.

### Step 8: Creating the First Commit

I staged all files and created the first commit.

Commands used:

```bash
git add .
git commit -m "Initial setup"
```

### Step 9: Publishing to GitHub

While attempting to push from the terminal, GitHub rejected authentication because password authentication is no longer supported.

**Solution:**

Connected the repository through GitHub Desktop and authenticated using my GitHub account.

---

## Challenges Encountered


| Issue                                                  | Solution                           |
| ------------------------------------------------------ | ---------------------------------- |
| PowerShell blocked Claude scripts                      | Updated execution policy           |
| Browser did not automatically open during Claude login | Opened authentication URL manually |
| Could not find Codex extension in Cursor               | Installed Codex separately         |
| Git repository was not initialized                     | Used `git init`                    |
| GitHub authentication failed                           | Connected through GitHub Desktop   |


---

## Key Learnings

- AI development tools evolve rapidly and installation methods can change over time.
- Troubleshooting requires documentation, research, and testing.
- Git and GitHub are essential tools for version control and project management.
- Authentication and environment configuration are common setup challenges.
- Documenting problems and solutions is an important part of professional software development.

---

## Current Status

✅ Cursor Installed

✅ Claude Code Installed

✅ OpenAI Codex Installed

✅ GitHub Repository Created

✅ Git Repository Initialized

✅ Initial Documentation Completed  

✅Repository Connected to Github Desktop

✅ Ready for the Next Project Stage