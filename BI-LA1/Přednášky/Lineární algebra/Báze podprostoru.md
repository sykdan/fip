- O souboru vektorů ($x_1$, $x_2$ ... $x_m$) řekneme, že generuje [[podprostor]] $P \subset \subset T^n$ , pokud platí, že [[Lineární obal]]
$$ \langle x_{1}, x_2 ..., x_{m} \rangle = P $$
- pokud je podprostor celým vektorovým prostorem, můžeme zjednodušeně říct, že soubor vektorů generuje celý vektorový prostor 
- soubor vektorů je **báze podprostoru** P, pokud:
	- je lineárně nezávislý
	- generuje podprostor P
- jak zjistit, jestli soubor vektorů generuje podprostor P:
	1. hledáme, jestli pro každý vektor v podprostoru P existuje sada koeficientů, které když vynásobíme se souborem vektorů a sečteme, se mu rovnají
	2. rovnici tvaru $\alpha_1 x_{1} + \alpha_{2} x_{2} + ... + \alpha_{m} x_{m} = v$ převedeme do [[SLR (Soustava lineárních rovnic)]] a pomocí GEM převedeme do HST
	3. zjistíme počet řešení pro libovolné parametry z v
# Standardní báze
- pro $R^2$ -> (1, 0), (0, 1)
- pro $R^3$ -> (1, 0, 0), (0, 1, 0), (0, 0, 1)
# Existence báze
- podprostor {$\theta$} nemá bázi
- všechny báze podprostoru P mají tolik prvků, jakou má P dimenzi![[Pasted image 20241030121428.png]]
# Jak zjistit bázi
- z každého generujícího souboru můžeme vybrat takové vektory, které tvoří bázi
- každý lineárně nezávislý soubor můžeme doplnit na bázi