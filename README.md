To jest plik README.md o nauce gita
Tutaj bede wpisywac komendy dotyczace podstaw gita
# utworzenie nowego folderu
mkdir -p workspace/nauka_gita
cd workspace/nauka_gita

# konfiguracja gita
git config -l
git config --global user.name "AleksandraKusz"

# Nie lubimy spamow
git config --gloal user.email "aleksandrakusz@mail.com"

# spwadzamy wlasciwa sciezke
pwd
# powinnismy zobaczyc sciezke koncaca sie  nauka_gita

# tworzymy repozytorium (inicjalizujemy gita)
git init

# repozytorium ma swoj plik konfiguracyjny
cat .git/config
# tworzymy plik README.md
touch README.md
# otiweramy edytor np. atom lub nano w katalogu glownym
# repozytorium
atom .
nano README.md# nauka_gita

# dodaje nowe
hejka

# jak poradzic sobie z tokenem by byl zapamietany 
git config 
# mozemy prjekt skolonowac, kod pobieramy na inny komputer



