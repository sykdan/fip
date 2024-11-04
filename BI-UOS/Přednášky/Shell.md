- = interpret příkazů
- běží v **terminálu**  - příkazem `tty` vypsat který soubor mu přináleží
	- `echo ahoj > /dev/pts/<cislo>` - vypsání do **cizího terminálu**
# Interpretace příkazů
- `prikaz` - příkaz
- `prikaz &` - asynchronní příkaz (na pozadí)
- `prikaz ; dalsiprikaz` - sekvence příkazů, postupně
- `prikaz && dalsiprikaz` - sekvence příkazů, postupně, ale pokud nějaký selže, tak se ostatní nespustí
- `prikaz || dalsiprikaz` - sekvence příkazů, postupně, ale pokud první selže, tak se spustí ten druhý
- `prikaz -p` - **krátký přepínač**
	- `prikaz -p 40`, `prikaz -p40` - **s parametrem**
- `prikaz --param` - **dlouhý přepínač** 
## Quoting
- ruší význam následujícího metaznaku
- např. `echo hondota \$HOME je $HOME` -> `hodnota $HOME je /home/volt`
- můžeme vyrušit enter a psát příkazy na víc řádek
## Subshelly, dělení příkazů
- obalením příkazu do **kulatých závorek** se příkaz spustí v subshellu (např. `ps ; (ps ; ps)`)
- obalením příkazu do **složených závorek** se příkaz spustí v současném shellu
	- v bashi a nových shellech lze do složených závorek psát sekvence, které budou expandovány:
		- `echo {soubor1,soubor2,soubor3}.{txt,jpg,rst}`
		- `echo {1..10}`, `echo {1..10..2}`
## Pathname expansion
- některé znaky mají speciální význam
- `?` - jeden znak
- `*` - neomezeně znaků
# Proměnné
- definice proměnných: $
	- $0 - název programu/skriptu
	- $1.. - parametry
		- `'mam $100'` -> mam $100, `"mam $100"` -> mam 00
			- `$1` se interpretuje jako proměnná
			- proměnná s názvem 100 -> `${100}`
	- $HOME - domovský adresář
# Vstup a výstup
- vstup (`stdin`) - **file descriptor 0**
- výstup (`stdout`) - **fd 1**
	- přesměrování přes > - např. `date > out.txt`, příp. >> pro připojení (append)
	- příp. `date 1> out.txt` - pouze výstup
	- `|` -> posílá výstup jinému příkazu
- chybový výstup (`stderr`) - **fd 2**
	- chybu lze přesměrovat např. s `date 2> out.txt`
	- `|&` -> posílá chybový výstup jinému příkazu
- exit code - 0 je úspěch, 1-255 je chyba
	- získat proměnnou `$?`