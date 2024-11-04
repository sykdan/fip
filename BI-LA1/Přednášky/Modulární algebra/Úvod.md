- zápis: Rovnice nad R, nad C -> v reálných/komplexních číslech

dle teorie LA platí:
# Lingebra nad celými čísly nefunguje!

Mějme rovnici:
$$3x = 7$$
Triviální postup je většinou: "vydělit obě strany třemi", nad R je řešení: $\frac{7}{3}$
Ale jak na to jinak? Provedeme ==**řadu ekvivalentních úvah**==:
- Místo toho "existence inverzního prvku" $3^{-1}$:
$$3^{-1} (3x) = 3^{-1} * 7$$
- Roznásobíme vlevo -> Asociativita násobení (a\*b) \* c = a\*b\*c 
$$(3^{-1}*3)x = 3^{-1} * 7$$
$$1x = 3^{-1} * 7$$
- O jedničce můžeme říct, že je **neutrální vůči násobení**:
$$x = 3^{-1} * 7$$
Zjistili jsme ale jen, že **neexistuje jiné řešení** = ta poslední rovnice je ekvivalentní k té první. Jestli je řešení  $\frac{7}{3}$ zjistíme až po dosazení.

Místo toho mějme rovnici s parametrem:
$$3x = b$$
Úpravami zjistíme, že je právě jedno řešení:
$$x = \frac{b}{3}$$

A ještě jednou pro:
$$ax = b$$
Úpravou bychom *mohli* přijít k řešení:
$$x = \frac{b}{a}$$
Ale pokud $a=0$, tato úprava nedává smysl.

## Co jsme pro tento postup potřebovali?
- že množina reálných čísel R je uzavřená vůči násobení, tudíž $(a \in R) * (b \in R) = (ab \in R)$
- že násobení je asociativní
- že jednička je neutrální vůči násobení
- že každé nenulové číslo má inverzi
- komutativita