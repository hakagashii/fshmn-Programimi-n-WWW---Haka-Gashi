# Java V - Formulari i misionit sekret

## Pergjigjja / realizimi
- Formular semantik me `label` per secilen fushe.
- Pseudonim 3-20 karaktere (`required`, `minlength`, `maxlength`).
- Email me `type="email"` dhe `required`.
- Numri i personave 1-5 me `type="number"`, `min`, `max`, `step`, `required`.
- Kategoria Art/Shkence me `fieldset`, `legend` dhe radio `required`.
- Pranimi i rregullave me checkbox `required`.
- Tabele me `caption`, `th` dhe `scope`, me 3 orare.
- Kalimi ne `pranuar.html` permes `method="get"` pas validimit vendas HTML.
- CSS responsive per ekran te madh dhe telefon.

## Hyrjet / daljet dhe rastet
**Hyrjet:** pseudonimi, email i sajuar, numri i personave, kategoria dhe pranimi i rregullave.
**Dalja:** nese te gjitha fushat jane valide, hapet `pranuar.html` me vlerat ne URL (GET), pa ruajtje ne server.
**Rast normal:** Agjenti07, student@example.org, 3, Art, rregullat e pranuara -> kalon.
**Rast kufitar 1:** pseudonim me 2 karaktere -> nuk kalon.
**Rast kufitar 2:** persona = 0 ose 6 -> nuk kalon.

## Testet e pranimit
1. Kliko butonin me formular bosh: shfletuesi nuk lejon vazhdimin.
2. Fut email jo-valid si `abc` dhe provo: nuk kalon.
3. Fut `0` ose `6` persona: nuk kalon.
4. Mos zgjedh kategorine ose mos prano rregullat: nuk kalon.
5. Ploteso me vlera te sajuara valide: hapet `pranuar.html` dhe parametrat jane ne URL.
6. Kontrollo tabelen: 10:00, 12:00, 14:00 me titujt Ora, Misioni, Vendi.

## Reflektim individual
`required` ne frontend nuk garanton siguri, sepse validimi ne browser mund te anashkalohet, p.sh. duke ndryshuar HTML ose duke derguar kerkesa direkte. Ne nje aplikacion real te dhenat duhet te validohen edhe ne server, te pastrohen/kontrollohen dhe te ruhen me masa te pershtatshme sigurie. GET i shfaq vlerat ne URL, ndaj ne kete detyre perdoren vetem te dhena te sajuara.

## Hapja
Hap `index.html` ne browser. Nuk nevojitet instalim ose server. Projekti permban vetem HTML dhe CSS.
