# Követelmények segítség - specifikáció

## Prioritásszintek

Tipikus prioritás szintek követelményekben (hasonlóan a rizikó megbecsüléséhez, és a követelmény nem teljesülése által okozott feltételezett hozzájárulás a működésképtelenséghez):
- Minimális: a követelmény teljesülésének nincs ráhatása a rendszer működőképességére
- Alacsony: a követelmény nem teljesülése esetén kisebb problémák (pl. kezelhetőségi, kényelmi) lépnek fel
- Közepes: a követelmény nem teljesülése esetén jelentős problémák léphetnek fel, amelyek a rendszer bizonyos funkcionalitását jelentősen korlátozzák
- Magas: a követelmény nem teljesülése esetén a rendszer működőképtelenné válhat, teljes funkciók válnak elérhetetlenné
- Kritikus: a követelmény nem telejsülése esetén a rendszer működésképtelen, funkcióit, az elvárásokat egyáltalán nem teljesíti (GO-NOGO követelmény)

## Követelménytáblázat példa (2 db követelmény)

| Köv. ID  | Megnevezés    | Leírás| Prioritás |
|--------- |---------------|-------|-----------|
| REQ.01   | PalyaBetoltes | A pálya mindig betölthető a pálya elején | Magas |
| REQ.02   | MozogJatekos  | A karakter játék közben mindig képes mozogni | Kritikus |