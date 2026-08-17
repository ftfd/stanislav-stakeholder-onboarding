# Local Workflow

*  Working Tree: Local editing files, not saved in git monitoring.
*  Staging Area: Temporary prepeared for vcs processing files.
*  Repository (Репозиторій / Локальна база даних): .git directory with commits in hashed local history.

---

### Common local history commands


*   `git status` — temporary status of working tree and staging area.
*   `git diff` — difference between changes of working tree and actual staging area.
*   `git diff --staged` — changes, saved in staging area, but not commited.
*   `git log` — list of commits.
*   `git log --oneline` — shorted commits list.

---

### 🛡️ 3. Safe restore


*   `git restore <file_name>` — restores file.
*   `git restore .` — restores actual directory.

*   `git restore --staged <file_name>` — restores file from staging area.

*   `git commit --amend -m "New description"` — rewrite last commit.
