Notebooky na matematiku.
Výpočty jsou defaultně přesné, pro nepřesné výpočty buď zadat čísla s desetinnou tečkou nebo na konec napsat `// N`
Gró:
- `x = 1` - proměnná
	- středník na konci -> nevypsat hodnotu
- `funkce[x_, y_] := x / y` -> deklarace funkce
	- parametry musí končit podtržítkem!
- `Plot[Sin[x], {x, 0, 2Pi}` -> vykreslit graf
	- Barva: PlotStyle
	- Pojmenovat osy: AxesLabel

# Seznamy
- složené závorky: `{prvek1, prvek2}`
- indexy v `[[1]]` a indexuje se od 1 (záporné od konce)
	- vnořené indexy **oddělené čárkou!!**
- vtipný funkce nad seznamy:
	- `Flatten[]`
	- `Append[]`
	- `First[]`

# Řešení rovnic
- funkce `Solve[{rovnice1, rovnice2}, {promenne}]`
## Diferenciální rovnice
- pro **diferenciální rovnice** - `DSolve[{rovnice1, rovnice2}, {dFunkce}, parametr]`
	- vznikne konstanta (po integraci)
- můžeme přidat počáteční podmínku: `DSolve[{r1, pp1}, {dFunkce}, parametr]`
- numerické řešení:
	- `NDSolve`- `DSolve[{rovnice1, rovnice2}, {dFunkce}, {parametr, od, do}]`
	- vznikne interpolační funkce
# Pravidla
- `def = {x -> 2, y -> 1, z -> 4}`
- něco jako dictionary
- můžu dosadit do rovnice: `rce /. def`
# Matice
- `matice = {{3, 12, 5}, {7, 9, 1}, {22, 11, 10}}`

# Derivace a integrály
- `fce'[]`
- `Integrate[fce, podle]`
# Boolovská algebra
- `a && b || c`