touch README.md
ssh -T git@github.com
git init
git add README.md
git commit -m "first commit"
git remote add Run.Mobile.Library https://github.com/runkingzhang/Run.Mobile.Library.git
git push -u Run.Mobile.Library master