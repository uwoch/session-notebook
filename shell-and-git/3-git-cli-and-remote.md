- versteckte Ordner anzeigen lassen = ls -a
- Git Ordner anlegen = git init (verstecke Repo anlegen) 
- touch .gitignore, Dateien, die nicht versioniert werden sollen, z.B. .ds_store dort 
reinschreiben, mit nano
- git status = um zu sehen ob Dateien gestaged, committed sind
- git add . = gesamter Inhalt eines Ordners wird gestaged
- git commit -m „Kommentar“ = Commit
- git push -u origin main (beim 1. Mal, dann nur noch push oder pull)

——
echo "# demo-for-github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/uwoch/demo-for-github.git
git push -u origin main
…or push an existing repository from the command line

git remote add origin https://github.com/uwoch/demo-for-github.git
git branch -M main
git push -u origin main
——
remote Repo auf GitHub, lokal auf unserem Rechner 
