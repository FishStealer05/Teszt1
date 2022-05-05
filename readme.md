#hello
…or create a new repository on the command line

echo "# Teszt1" >> README.md #fájl léterhozása az első sorba ": #teszt" kerül
git init  a git mappa inicializásálsa 
git add README.md változások mentése
git commit -m "first commit" változtatások jóváhagyása 
git branch -M main a fejlesztéso ág átnevezése main-re 
git remote add origin https://github.com/FishStealer05/Teszt1.git fejlesztési ág feltöltése első alkalommal.
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/FishStealer05/Teszt1.git
git branch -M main
git push -u origin main
