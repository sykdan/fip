- $\bot \models A$ 
- $\top \models A$
- $\neg (A \Leftrightarrow B)$ -> $\neg (A \Rightarrow B \wedge B \Rightarrow A)$ -> $(A \wedge \neg B) \vee (B \wedge \neg A)$ 
- Zákon vyloučení sporu: $A \wedge \neg A$  je kontradikce
- Zákon vyloučení třetího: $A \vee \neg A$ je tautologie
- Zákon dvojí negace: $\neg \neg A \Leftrightarrow A$ 
- Zákon identity: A a tautologie -> A, A nebo kontradikce -> A (nepřispějí do porovnání, analogie A a tautologie == "A * 1 = 1")
- Zákon anihilace
# Algebraické vlastnosti spojek
- #Komutativní zákony: Zaměnitelnost u AND a OR, u ekvivalence ($\wedge, \vee, \Leftrightarrow$)
- #Asociativní zákony: u AND a OR můžeme přeházet závorky,
  stejně tak i u ekvivalence ($\wedge, \vee, \Leftrightarrow$)
	- znaménko musí být stejné
	- platí i pro víc závorek
- #Distributivní zákony: $A \wedge (B \vee C)$ -> $(A \wedge B) \vee (A \wedge C)$ 
	- AND analogický k násobení, OR analogický k sčítání
	- $A \vee (B \wedge C)$ -> $(A \vee B) \wedge (A \vee C)$ 
	- platí pro víc (m * n prvků), 
- #Absorpce: $A \wedge (A \vee B)$ -> $A$, $A \vee (A \wedge B)$ -> $A$
- De #Morganovy zákony (roznásobování negace) -> `!(a && B) == !a || !b` 
