# Meet the Class 👋

**10 minutes. One profile. Your first contribution to a shared project.**

Add your name, major, and hobbies to our class directory. Practice the same workflow from the slides: **branch → edit → add → commit → push → pull request**.

## 1. Fork and open in Codespaces · 2 min

Sign in to GitHub. Click **Fork → Create fork** at the top of this repo. Keep the repository name `git_workshop_2026`.

In **your fork**, click **Code → Codespaces → Create codespace on main**. When it opens, use **Terminal → New Terminal** if the terminal isn't visible.

> Open your Codespace before the timer starts if possible. Launch time varies. If Codespaces is unavailable, use the [browser shortcut](docs/browser-shortcut.md).

## 2. Make a branch and profile · 3 min

Replace `YOUR-USERNAME` with your GitHub username in both commands:

```bash
git switch -c profile/YOUR-USERNAME
cp templates/profile.md students/YOUR-USERNAME.md
```

Open your new file under `students/` in the left sidebar, fill it in, and save:

```markdown
# Hi, I'm Maya!

- Major or interest: Computer science
- Three hobbies: Drawing, gaming, hiking
- Favorite snack: Popcorn
```

Use a first name or nickname and share only what you're comfortable making public. See an [example](examples/maya.md).

## 3. Commit and push · 2 min

Replace `YOUR-USERNAME` with the same username:

```bash
git add students/YOUR-USERNAME.md
git commit -m "Add my class profile"
git push -u origin profile/YOUR-USERNAME
```

**Commit** saves your change in your Codespace. **Push** uploads your branch to your fork on GitHub.

## 4. Open a pull request · 2 min

Go back to your fork on GitHub and click **Compare & pull request**. If the banner isn't there, select **Contribute → Open pull request**. You can also use **Pull requests → New pull request → compare across forks**.

Check these choices:

- **Base repository:** `brunorios1080/git_workshop_2026`, branch `main`.
- **Head repository:** your fork, branch `profile/YOUR-USERNAME`.

Use a title like **Add Maya's profile**, check **Files changed**, then click **Create pull request**. This asks the instructor to add your profile to the shared repo.

## 5. Meet a classmate · 1 min

Open [the class pull requests](https://github.com/brunorios1080/git_workshop_2026/pulls). Read someone's profile and leave a friendly comment, such as “I like hiking too!”

The instructor will merge a few PRs live. Refresh [students/](students/) on the class repo to see the profiles appear. Other PRs can be merged after the activity.

**You're done when your PR is open and you've commented on a classmate's contribution.**

---

Teaching this? See the [one-page instructor guide](docs/instructor-guide.md) and [slide-ready activity text](docs/demo-slide.md). Stuck? Check the [quick fixes](docs/quick-fixes.md).
