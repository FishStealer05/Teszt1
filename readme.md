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
további terminál parancsok
git pull   origin main friss repo lekérdezése
git remote -v  távoli repo lekérdezése aktuális távoli repo lekérdezése
git status # change stage commit, 
állapotának lekérdezése
cd #Change Directory 
mkdir # MAke Directory 
cd.. egy mappával lejjebb lép
cd  <directory name>
  rmdir <directory name>  # remove directory
  ls #list könytár listázása
  git config global list  # globális  beállítások listázása
