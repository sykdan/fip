- Dimenze podprostoru P je rovna:
	- nule, pokud neexistuje lineárně nezávislý [[soubor vektorů]] z P o délce 1
		- platí pouze pro podprostor {$\theta$}
	- **d**, pokud existuje **lineárně nezávislý** soubor vektorů z P délky **d**, kde d je nejvyšší možné číslo (tedy soubory o délce > d už jsou **lineárně závislé**)
		- nemůže přesáhnout dimenzi vektorového prostoru n ($T^n$)
- značení: "dim P"
- pozorování:
	- dim $T^n$ = n
	- lineárně nezávislý soubor z $T^n$ může mít maximálně n vektorů

# Tvrzení
- pokud soubor vektorů ($x_1$, $x_2$, ..., $x_m$) generuje podprostor $P \subset \subset T^n$, pak dim P <= m
- tato tvrzení jsou ekvivalentní (pokud platí jedno, platí zbytek):
	- Soubor (x1, . . . , xd) je báze P
	- Soubor (x1, . . . , xd) je lineárně nezávislý
	- Soubor (x1, . . . , xd) generuje P
- pokud P a Q jsou podprostory $T^n$ a $P \subset Q$, potom dim P <= dim Q
	- jinými slovy, "osekáváním" prostoru do podprostorů nezvýší dimenzi, jen sníží