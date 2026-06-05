# DAX 40 — Trend & denné zmeny

Lokálny / web dashboard pre **nemecký index DAX 40** (Xetra / Deutsche Börse, `^GDAXI`).
Zameraný na **potvrdenie BUY / SELL setupu** cez viacero časových rámcov.

**Live:** https://4damko.github.io/dax-dashboard/

## Čo ukazuje
- DAX live úroveň, denná zmena, deň H/L, 52-týž. rozsah, trend 30D
- **Realizovaná volatilita 30D** (ann.) ako náhrada za strachový index (VDAX je na Yahoo zamrznutý od 2019)
- **Trend podľa rámca** — prepínač 1D / 3D / 7D / 30D / 90D / All + farebný signál HORE/DOLE
- **Zhoda časových rámcov** — koľko rámcov ukazuje rovnaký smer → BUY / SELL / zmiešaný bias
- **Movers** (na vyžiadanie) — top ťahúni / brzdy z 20 hlavných firiem DAX + šírka trhu

## Dáta
Yahoo Finance (index `^GDAXI`) cez verejný reader **r.jina.ai** — bez API kľúča, funguje aj z `file://`.
Posledné dobré dáta sa cachujú lokálne (localStorage) pre prípad výpadku zdroja.

Aktualizuje sa pri každom načítaní / kliknutí na ↻. Len informatívne, nie je to investičné odporúčanie.
