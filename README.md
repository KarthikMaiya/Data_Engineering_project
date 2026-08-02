# Data_Engineering_project

## Pull dataset and all project files from Adventure Works repo

Use these commands to bring everything from the source repository into this repository (your account):

```bash
# run from this repository root
git remote add upstream-source https://github.com/anshlambaoldgit/Adventure-Works-Data-Engineering-Project.git
git fetch upstream-source
git checkout -B main upstream-source/main
git push -u origin main --force
```

### Notes
- This copies all files, including dataset files, from the source repository.
- If the source default branch is not `main`, replace `upstream-source/main` with the correct branch (for example `upstream-source/master`).