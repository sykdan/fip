= interpet příkazů
# Interpretace příkazů
- `prikaz` - příkaz
- `prikaz &` - asynchronní příkaz (na pozadí)
- `prikaz ; dalsiprikaz` - sekvence příkazů, postupně
- `prikaz & dalsiprikaz` - sekvence příkazů, postupně, ale pokud nějaký selže, tak se ostatní nespustí
# Proměnné
- definice proměnných: $
	- $0 - název programu/skriptu
	- $1.. - parametry
	- $HOME - domovský adresár- neustále čteme vstup a
# Vstup a výstup
- vstup (stdin) - file descriptor 0
- výstup (stdout) - fd 1
	- přesměrování přes > - např. `date > out.txt`, příp. >> pro připojení (append)
	- příp. `date 1> out.txt` - pouze výstup
- chybový výstup (stderr) - fd 2
	- chybu lze přesměrovat např. s `date 2> out.txt`