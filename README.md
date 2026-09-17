# g-i

Public GitHub repository for this project.

## GitHub CLI

Check the installed CLI and authentication status:

```powershell
gh --version
gh auth status
```

Create a branch, push it, and open a pull request:

```powershell
git switch -c my-change
git add .
git commit -m "Describe the change"
git push -u origin my-change
gh pr create --base main --fill
```
