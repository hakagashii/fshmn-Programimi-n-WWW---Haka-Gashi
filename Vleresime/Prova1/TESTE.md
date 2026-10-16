# Testet - Gr.4

| Testi | Pritja | Rezultati nga kontrolli i kodit |
|---|---|---|
| 360 px | Tri burime njera poshte tjetres, pa scroll horizontal | CSS ka nje kolone; permbajtja lejohet me u thy ne rreshta. | W
| 1000 px | I pari ne krejt rreshtin, dy tjeret nga gjysma | Media query krijon 2 kolona dhe article i pare shtrihet ne te dyjat. |W
| Menuja dhe Me shume | Linkat shkojne te ID e sakta | `#burimet` dhe `#ndihma` ekzistojne ne HTML. | W
| Tab / Enter | Fokusi shihet dhe linkat aktivizohen | W`:focus-visible` ka outline; linkat jane elemente `a` me href. |
| Tekst i gjate | Qendron brenda kutise | `white-space: normal` dhe `overflow-wrap: anywhere` e thyejne tekstin. |W

Shenim: Kontrolli eshte bere ne kod. Provoje edhe ne browser me DevTools ne 360px dhe 1000px para dorezimit.
