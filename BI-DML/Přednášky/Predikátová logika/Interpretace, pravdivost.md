- pokud L je jazyk predikátové logiky, tak interpretace jazyka L každá volba neprázdné množiny univerza (U) a přiřazení významů prvkům jazyka L
- kroky:
	1. Každému symbolu pro konstantu přiřadím prvek. (U je univerzum lidí, K je Krel, který pochází z univerza U)
	2. každému funkčnímu symbolu přiřadím funkci (např. `s(k, l)` -> `k * l`)
	3. každému predikátovému symbolu relaci na univerzum U
- formule v interpretaci - formule nahrazená podle těchto kroků
- kontext - každé přiřazení konkrétních prvků U a všechny proměnné v jazyce L
- pokud nahradíme v F všechny volné proměnné dle daného kontextu, mluvíme o **formuli v interpretaci v kontextu**
- Příklad interpretace: ![[Pasted image 20241015151415.png]]
# Pravdivost
- predikátová formule je pravdivá v interpretaci, pokud je v této interpretaci pravdivá v libovolném kontextu
- **tautologie** -> platí v libovolné interpretaci (a kontextu)
- **splnitelná** -> právě když existuje interpretace a kontext, ve kterých je pravdivá
- **kontradikce** -> když není pravdivá v žádné interpretaci a žádném kontextu