# MTA-DreamRPG
Gamemod RPG do Multi Theft Auto, napisany języku Lua.
# AUTORZY
- Xantris
- Bone
- Split
- Łukasz "Wielebny" Biegaj
- IQ
- TheNoobisty
- CrosRoad95
- NeX
- Borsuk
- TomeQmix
- Kolciarz
- Lagerek
- Enonek
- Zbigniew "Zbyk.gg" Płachciński
- Chojnas
- Soczek
  I inni 
# LICENCJA
Warunkiem wykorzystania tego kodu jest NIE TWORZENIE serwera o nazwie DreamRPG. Wykorzystaj go swobodnie, ale swoje dzieło nazwij oryginalnie.
# ZAWARTOŚĆ REPOZYTORIUM

W repozytorium znajduje się:
- Kod Lua serwera
- Struktura bazy danych


W repozytorium nie ma:
- Kodu bota discord integrującego z serwerem MTA
- Niektórych modeli budynków
- Panelu WWW gracza
- Zasobu odpowiadającego za Zgłoszenia Frakcyjne

# GDZIE I JAK URUCHOMIĆ SERWER?
Uruchomienie serwera nie wymaga żadnego specjalnego serwera dedykowanego. Aby go uruchomić, wystarczy zwykły hosting. Polecamy:
- Server Project - http://serverproject.pl/

Aby uruchomić serwer należy:
1. Zainstalować serwer MTA w panelu na stronie hostingu
2. Skopiować pliki serwera do katalogu /mods/deathmatch/resources/
4. Zainicjalizować bazę danych plikami zawartymi w sql/schema.sql
5. Zainicjalizować samodzielnie czyste konto w ACL, lub skorzystać z dołączonego pliku opt/internal.db (zastąpić istniejący).
6. Stworzyć własny plik mtaserver.conf lub połączyć istniejący z tym znajdującym się w opt/mtaserver.conf. W pliku tym muszą znaleźć się adresy ip i porty (narzucone przez hosting), zasoby do uruchomienia oraz odwołanie do modułu mta_mysql.
7. Zainstalować serwer, uruchomić, zalogować się, zmienić hasło do ACL
