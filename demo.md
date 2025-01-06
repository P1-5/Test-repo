## this is sample file 
echo "# Test-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/P1-5/Test-repo.git
git push -u origin main
