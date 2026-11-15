# Mission 3 — Understand the Operating System

## Task 3.1 — Explore the operating system

| Information explored | What it tells me | Observation (privacy-safe) |
|---|---|---|
| Operating system | Which system runs the computer | macOS 27.0.1 |
| Current account | Which account is active | The command returned my account name; I have written `[redacted]` here. |
| Storage | How much space is used and available | About 13 GiB used and 808 GiB available (2% used) on the checked volume. |
| System activity | What the computer is doing at that moment | The snapshot showed 810 processes, 3 running, and the CPU mostly idle. These numbers change over time. |

## Task 3.2 — Understand processes

A process is a program that is running. The PID column gives each process a number so it can be identified while it is running. I saw **Brave Browser** and **Terminal** in the process list. Their PID numbers can change, so I did not save them.

## Task 3.3 — Understand paths and permissions

I checked the current folder at the project root and then inside `mission-03-operating-system`. The displayed location changed when I moved into the mission folder.

- **Absolute path:** `/Users/[redacted]/Desktop/digital-detective-8078/mission-03-operating-system/practice-area/permissions.txt` — starts from the root of the computer.
- **Relative path:** `mission-03-operating-system/practice-area/permissions.txt` — starts from the project folder.

I viewed the detailed listing for `practice-area/permissions.txt`. It showed `-rw-r--r--@`. The owner's letters are `rw-`, so the owner can read and write the file, but cannot execute it.

| Permission | Meaning | Example |
|---|---|---|
| `r` — read | Lets a file be opened and read. | Reading a text file. |
| `w` — write | Lets a file be changed. | Editing a text file. |
| `x` — execute | Lets a file run; on a folder, it allows access through it. | Running a script. |

## Task 3.4 — Operating-system responsibilities

| Responsibility | What it does | Example |
|---|---|---|
| Process management | Runs programs and shares processor time between them. | The browser and Terminal can run at the same time. |
| Memory management | Gives programs memory while they run. | A browser uses memory to keep tabs open. |
| Device management | Helps programs use connected hardware. | The computer receives typing from the keyboard. |
| File management | Saves and organizes files and folders. | A README is saved in a mission folder. |
| User interface / shell | Lets me interact with the computer. | I use the desktop or type commands in Terminal. |
| Security and permissions | Controls who can read, change, or run files. | File permissions show whether the owner can edit a file. |

## 1. Task / objective

Explore system information, running processes, storage, paths, file permissions, and operating-system responsibilities.

## 2. Work completed

I checked macOS, account and storage information, observed running processes, checked a practice file's permissions, and completed the operating-system table.

## 3. Commands / tools used

- `sw_vers` — checked the macOS version.
- `id -un` — checked the active account; I redacted its name in these notes.
- `df -h /` — checked used and available storage.
- `top -l 1 -n 0` — viewed a brief system activity snapshot.
- `ps -axo pid,comm` — viewed process IDs and program names.
- `pwd`, `cd` — checked and changed the current location.
- `mkdir -p`, `printf` — made a practice folder and file.
- `ls -l` — checked the practice file's permissions.
- `awk`, `sed` — kept account details out of the notes and output.
- Git — staged, committed, and pushed the completed Mission 3 work.

## 4. My understanding

The operating system runs programs and manages the computer's memory, devices, files, and permissions. A process is a program that is running. Paths show where files are, and permissions show what actions are allowed.

## 5. Difficulties faced

Some command output included my account name, and the system activity numbers changed between observations.

## 6. How I resolved them

I replaced the account name with `[redacted]` and described the activity as a snapshot because those values change.

## 7. Evidence / files

- `practice-area/permissions.txt` — practice file used to view permissions.
- This README contains the privacy-safe observations and tables.

## 8. Commit details

- Commit message: `Document operating system and file management`
- The completed Mission 3 work was pushed to GitHub.
