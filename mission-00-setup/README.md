# Mission 0 — Create Your GitHub Workspace

## 1. Task / objective

Create the local assignment project with the required name and folder structure, prepare the root README, create a matching public GitHub repository, and publish the setup files.

## 2. Work completed

- Prepared the local project folder `digital-detective-8078` and the required mission folders.
- Added a root README with an assignment overview and links to the mission READMEs.
- Created the mission README files, the `evidence/` folder, and the `number_converter.py` placeholder.
- Created the public GitHub repository with the same name and pushed the initial project structure.

## 3. Commands / tools used

- `python3 --version` — checked that Python is available; it reports Python 3.13.15.
- `git --version` — checked Git; it reports Git 2.50.1 (Apple Git-155).
- `git init -b main` — initialized Git in the assignment folder on the `main` branch.
- `git add --all` — staged the setup files.
- `git commit` — saved the initial setup as a Git commit.
- `git remote add origin` — connected the local project to the GitHub repository.
- `git push -u origin main` — published the `main` branch to GitHub.
- GitHub — created and checked the public repository.
- Visual Studio Code — used as the project text editor.

## 4. My understanding

A Git repository keeps track of a project's files and their change history. GitHub stores an online copy that can be shared and accessed from the web. Organizing the assignment by mission keeps each mission's notes and files together, makes the repository easier to navigate, and lets each completed mission have its own commit.

## 5. Difficulties faced

Git initially detected the Desktop folder as the repository, which could have included unrelated Desktop files. The local project folder was also named `diwali`, which did not match the required repository name.

## 6. How I resolved them

Renamed the project folder to `digital-detective-8078` and initialized Git inside that folder. I checked the staged files before committing to make sure the commit contained the assignment files only.

## 7. Evidence / files

- Root project overview and mission links: [`README.md`](../README.md)
- Mission folders and their README files: `mission-00-setup/` through `mission-08-final-report/`
- Number converter placeholder: `mission-05-numbers-data/number_converter.py`
- Public repository: [AbhirupKarmakar/digital-detective-8078](https://github.com/AbhirupKarmakar/digital-detective-8078)

## 8. Commit details

- Initial structure commit: `Set up Digital Detective mission structure`
- Mission 0 documentation commit: `Complete repository setup and document Mission 0`
- The Mission 0 documentation commit has been pushed to the public GitHub repository.
