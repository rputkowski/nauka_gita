To jest plik readme.md o nauce gita.
Tutaj będą wpisywane komendy dotyczące podstaw gita:
# utworzenie nowego folderu
mkdir -p workspace/nauka_gita
cd workspace/nauka_gita

# konfiguracja gita
git config -l
git config --global user.name "rputkowski"

git remote add origin https://github.com/rputkowski/nauka_gita.gita
git branch -m main
git push -u origin main
git config --global credential.helper store #Now, git will remember your token
