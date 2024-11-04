# Úplný disjunktivní normální tvar
- **minterm** = implikant, který obsahuje **každou** prvotní formuli **právě jednou**
	- $A \wedge B \wedge \neg C$ je minterm
	- $A \wedge B$, $A \wedge A \wedge B \wedge C$ nejsou mintermy
- ÚDNT **je minterm** nebo **disjunkce různých** mintermů
- **nelze** sestrojit **ÚDNT pro kontradikci**
	- $\bot$ je symbol pro **prázdný ÚDNT**
- pravdivostní tabulka:
	- máme tolik **pravdivostních hodnot**, kolik je **mintermů**
	- v takovém případě je vždy pravdivý **právě jeden minterm**
# Konjukntivní normální tvar
- **maxterm** - klausule, která obsahuje **každou** prvotní formuli **právě jednou**
- ÚKNT je **maxterm** nebo **konjunkce různých** maxtermů
- **nelze** sestrojit **ÚKNT pro tautologii**
	- $\top$ je symbol pro **prázdný ÚKNT**
- pravdivostní tabulka:
	- máme tolik **NEpravdivostních hodnot**, kolik je maxtermů
	- v takovém případě je vždy NEpravdivý **právě jeden maxterm**

---
- ke každé výrokové formuli existuje **jednoznačný** ekvivalent v ÚDNT a ÚKNT
- pokud máme formule A a B a jejich ÚDNT A ÚKNT, tak:
	- pokud ÚDNT A a ÚDNT B mají stejné mintermy, pak A == B
	- pokud ÚKNT A a ÚKNT B mají stejné maxtermy, pak A == B