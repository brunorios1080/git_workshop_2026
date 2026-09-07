# Quick fixes

- **Where do I type commands?** In Codespaces, choose **Terminal → New Terminal**.
- **Codespaces won't start?** Use the [browser shortcut](browser-shortcut.md).
- **File not found?** Replace `YOUR-USERNAME` with your actual username, and check the file is saved inside `students/` with the same name as in your command.
- **Nothing to commit?** Save your profile in the editor and run `git status`. You may already have committed it.
- **Branch already exists?** Run `git switch profile/YOUR-USERNAME` to return to it.
- **Push denied?** Make sure your Codespace was opened from your own fork. Ask the instructor for help, or use the browser shortcut in your fork.
- **PR points to my fork?** Change the base repository to `brunorios1080/git_workshop_2026` and the base branch to `main`. Use **compare across forks** if needed.
- **No compare banner?** Open **Pull requests → New pull request**, enable **compare across forks**, and select your fork and profile branch as the head.

Curious? `git status` shows your current branch and pending changes; `git log --oneline -5` shows your latest commits. Press `q` if a long view opens.

[Back to the activity](../README.md)
