![[Pasted image 20240930170757.png]]
- Uzel - "Node" v stromu
- V kontextu obvodů to je kus drátu se všemi odbočkami
   ![[Pasted image 20240930171054.png]]
- Mám N uzlů, Nc2 (N nad 2) možných napětí, ale stačí změřit N-1 napětí
- Např. tady stačí změřit jen uAB a uBC a zjistím uAC![[Pasted image 20240930171250.png]]
# Algoritmus pro metodu uzlových napětí
1. Označíme a očíslujeme uzly
2. Označíme dílčí napětí
3. Označíme proudy součástkami
	- u napětí volíme shodně, u součástek libovolně (kdyžtak to vyjde záporně)
4. Napíšeme rovnice pro proudy v uzlech
5. Napíšeme rovnice pro součástky
6. pro kondenzátor a cívku určíme počáteční podmínky; tj. stav v čase 0 - abychom mohli počítat s derivací
## Řešení v Mathematice
- rovnice vypsat do mathematicy
- použít Tanh místo Sin pro obdélníkový tvar funkce
- použít NDSolve
	- vrazit malý `StartingStepSize`
