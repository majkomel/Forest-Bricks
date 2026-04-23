# 🧱 Bricks Game

Preprosta arkadna igra v slogu Brick Breaker, narejena z uporabo JavaScripta in HTML5 canvasa.

## 🎮 Opis

Igralec upravlja ploščico na dnu zaslona in odbija žogico, da uniči vse opeke. Med igro se lahko pojavijo nevarne kače, ki padajo proti ploščici.

Če kača zadene ploščico ali žogica pade mimo → igra se konča.

## 🕹️ Kontrole

- ⬅️ Leva puščica – premik levo  
- ➡️ Desna puščica – premik desno  
- ⏎ Enter – začetek / pavza  
- R – restart igre  

## ⚙️ Funkcionalnosti

- Canvas rendering
- Sistem opek (grid)
- Fizika odboja žogice
- Točkovanje
- Stopnje (difficulty scaling)
- Naključni spawn ovir (kače)
- Timer
- Win / Game Over popup

## 🧠 Mehanika igre

- Začetek:
  - počasnejša žogica
  - širša ploščica

- Pri 20 točkah:
  - hitrejša žogica
  - manjša ploščica
  - višja stopnja

- Ob uničenju opeke:
  - možnost, da pade kača

- Konec igre:
  - kača zadene ploščico
  - žogica pade na tla

- Zmaga:
  - uničene vse opeke (120 točk)

## 📊 Točkovanje

- Stopnja 1 → +1 točka
- Stopnja 2 → +5 točk

