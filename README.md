# git config --global user.name Vladimir-1208
git config --global user.email "iva.doi1964@gmail.com"
echo "# Vladimir-1208" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Vladimir-1208/Vladimir-1208.git
git push -u origin main
