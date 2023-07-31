# 👾 How to make a Pull Request
Navigate to our GitHub page(opens in a new tab). Click on the Fork button at the top right corner.

Clone your forked repo to work with it locally:

git clone https://github.com/github-username/Rath.git
# Clone your repo
git remote -v
# Check if the upstream repo has been configured.
git remote add upstream https://github.com/Kanaries/Rath.git
# If not, add the upstream remote manually.
cd Rath

Create a branch
git fetch upstream
git checkout master
git rebase upstream/master
git push origin master
# Keep your local fork up to date.
git checkout -b branch-name

Commit and push changes to GitHub
git status
# Check what codes your've changed.
git add
# Check what files you've added to the git branch.
git commit -m "Your remarks"
# Commit
git push origin branch-name
# Push your branch to the repo's remote name.

Open a pull request on GitHub
Visit your repo's GitHub page. Click on the "Compare&pull request" button at the top of the page.

Don't forget to provide the necessary information for your Pull Request! You will be notified via email once the PR request has been approved.
