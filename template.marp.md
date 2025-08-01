---
marp: true
math: mathjax
title: Raport z projektu
size: 16:9
paginate: true
mermaid: true
transition: fade
theme: gaia
# theme: uncover
backgroundImage: url("page-background.png")
footer: "**Raport SJU**"
style: |
  @import url('https://unpkg.com/tailwindcss@^2/dist/utilities.min.css');
---

# Projekt - Sieć Jako Usługa

## Przebieg projektu


Decyzja podjęta na robienie projektu lokalnie.
- Instalacja wszystkich potrzebnych programów: Docker, WSL. Używany był już program git bash.
- Uruchomienie budowania obrazu, wejście do kontenera
'docker run -it --rm -v .:/home/vscode/workspace sjuprojekt bash'

---

## Przebieg projektu

- dodanie pakietów do Dockerfile i zbudowanie obrazu
- Utworzenie pliku .devcontainer/devcontainer.json
![w:600](devcont.png)
- dodanie odpowiednich rozszerzeń do VS Code

---

## Przebieg projektu

- utworzenie release
![w:400](testy.png)
- utworzenie pliku test.py
- docker-publish.yml oraz modyfikacja pliku
---

- zmiana wpisu image na taki, który wskazuje na nowo zbudowany obraz
- umieszczenie notatnika używanego z przedmiotu Kwantowe Systemy Teleinformatyki
- dodanie biblioteki do Dockerfile, aby umożliwić działanie notatnika

---
# Przebieg
![w:600](mermaid.png)

---

##  Podsumowanie
Projekt został wykonany pomyślnie, lecz na przestrzeni robienia projektu napotkane zostało kilka problemów, które następnie zostały rozwiązane. Największym problemem na początku była obsługa Dockera w Codespaces, stąd użyto lokalnej formy wykonania projektu. 

Jakub Zarębski
