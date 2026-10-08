# Java III – Klinika e CSS

## Pershkrimi
Ne kete detyre kam kriju nje afishe per Klubin e Debatit duke perdor HTML dhe CSS. Afishja pershtatet edhe ne telefon.

## Fajllat
- `index.html` – Struktura e afishes.
- `style.css` – Dizajni, ngjyrat dhe pershtatja per telefon.
- `gabime.css` – Gabimet ne CSS dhe korrigjimet e tyre.
- `Zgjidhja reference.png` – Foto reference e detyres.
- `Udhezimet per detyren e javes III-te.md` – Udhezimet e profesorit.

## Cka kam realizu?
- Kam kriju afishen me titull, date, vend dhe link per regjistrim.
- Kam perdor CSS te jashtem dhe variabla per ngjyra.
- Kam shtu 3 etiketa me stile te ndryshme.
- Kam rregullu konfliktet ne CSS pa `!important`.
- Kam shtu fokus te dukshem me tastin Tab.
- E kam pershtat afishen per ekran 360px.

## Reflektimi
Problemi kryesor ka qene te selektoret `#poster` dhe `.poster`.

Selektori `#poster` kishte perparesi sepse ID ka specifike me te larte se klasa. Kjo shkaktonte probleme me ngjyren e tekstit dhe gjeresine.

E kam rregullu duke i nda vetite e CSS-it, pa kriju konflikte.

## Box Model
Kam perdor `box-sizing: border-box`, qe do te thote se gjeresia e elementit perfshin edhe padding dhe border.

Kjo ndihmon qe afishja mos me dal jashte ekranit.

## Testimi
E kam kontrollu afishen per ekran 360px dhe fokusin me tastin Tab.
