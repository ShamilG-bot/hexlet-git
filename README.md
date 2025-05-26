git init
echo 'Hello, Hexlet!' > README.md
echo 'Haskell Curry' > PEOPLE.md
git add .
git commit -m "Добавил README и PEOPLE"
git branch -M main
git remote add origin https://github.com/ТВОЙ_НИК/hexlet-git.git
git push -u origin main
