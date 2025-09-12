git clone https://github.com/mattpe/git-intro.git
cd git-intro
git remote remove origin
git remote add origin https://github.com/CHchisho/git-intro
git remote -v
git push -u origin main
git add notes.md
git status
git commit -m "Add notes.md"
git push origin main