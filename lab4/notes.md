# Lab 4 Notes: Git & GitHub

**Q1.** `--global` saves the name and email for every Git repository on my computer, in my user-level config file. Without it, the setting would only apply to the current repository.

**Q2.** A hidden folder called `.git` appeared, because `ls` doesn't show files starting with a dot. It's where Git stores the repository's whole history: commits, branches, tags and settings.

**Q3.** Git offered to track my lab folders and files (the lab notebooks, README.md and the week folders). It also listed things I didn't write, like the `.venv/` folder, which is thousands of files of other people's code.

**Q4.** After creating `.gitignore`, `.venv/` (and things like `__pycache__/` and `.DS_Store`) disappeared from the untracked list. Git now ignores them.

**Q5.** `.gitignore` should be committed. It's part of the project's setup, so anyone who clones the repo gets the same ignore rules.

**Q6.** README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the working directory into the staging area.

**Q7.** Git printed the branch, the commit's short hash and the message "Lab work so far", then a summary of how many files changed and how many lines were inserted, with a "create mode" line for each new file.

**Q8.** They're the short commit hash, the start of the commit's unique ID (SHA). You use it to refer to that exact commit, for example to view it or go back to it.

**Q9.** Edit the files, then `git status` to check, `git add` to stage, and `git commit` to save a snapshot.

**Q10.** GitHub automatically shows `README.md` on the repository's front page, so it's the first thing visitors read. The standard name and its place at the top level let tools and people find it immediately.

**Q11.** `gh auth login` signed me in through the browser and saved a login token on my computer. Git uses that token for HTTPS pushes, so I'm not asked for a password.

**Q12.** The file list and my README, displayed as formatted text. GitHub always renders the README.md from the top folder as the repository's homepage.

**Q13.** No. `git log --oneline` showed the same commits. Pushing only uploaded a copy of my history to GitHub, and at most the log now also shows `origin/main`.

**Q14.** A private repository exists on GitHub and is backed up there, but only I and the people I invite (like the TAs) can see it. If it didn't exist on GitHub, the work would only be on my laptop: nobody else could see it, and it wouldn't be backed up anywhere.
