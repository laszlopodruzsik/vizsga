git clone https://github.com/szpeter992/git-vizsga-0205.git

cd git-vizsga-0205

git checkout -b 'console'

git add . 

git status

git commit -m Hozzáadtam a .gitignore és a README.md fájlt. Az app.js-hez hozzáadtam egy console.log-ot ami akkor jelenik meg ha az oldal betöltődött. A style.css-ben pedig megváltoztattam a háttérszínt.

git remote rm origin

git remote add origin https://github.com/laszlopodruzsik/vizsga.git

git push origin console
