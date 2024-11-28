### Aktualizovana verzia zo srv-mondo01

```bash
mkdir -p work/vita/projekt-abc
cd work/vita/projekt-abc

git init
git status

git remote add origin https://github.com/roman7011/app_python.git

git remote -v
origin  ssh://git@github.com/roman7011/app_python.git (fetch)
origin  ssh://git@github.com/roman7011/app_python.git (push)


# Check SSH access to GITHUB:
git@github.com


vi file.md
vi druhy.md 
git add .

git commit -m "Moj prvy commit"
git branch
git branch -M main

git push -u origin main
