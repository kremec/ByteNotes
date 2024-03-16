Topics: [[Izjave]]
- - -
==Pravilen sklep==: Zaporedje izjavnih izrazov $A_1,A_2, \ ... \ ,A_n,B$ s predpostavkami $A_1,A_2, \ ... \ ,A_n$ in zaključkom $B$, če je zaključek $B$ resničen pri vseh naborih vrednosti izjavnih spremenljivk, pri katerih so resnične vse predpostavke
Izrek: $A_1,A_2, \ ... \ ,A_n \models B \ \iff \ (A_1,A_2, \ ... \ ,A_n) \implies B \ je \ tavtologija$

==Nepravilen sklep== dokažemo s protiprimerom - podamo nabor vrednosti izjavnih spremenljivk, pri katerem so vse predpostavke resnične in zaključek neresničen
### Pravila sklepanja
==Modus Ponens (MP)==: $A,A \implies B \ \models \ B$
==Modus Tollens (MT)==: $A \implies B, \neg B \ \models \ \neg A$
==Hipotetični silogizem (HS)==: $A \implies B, B \implies C \ \models \ A \implies C$
==Disjunktivni silogizem (DS)==: $A \lor B, \neg A \ \models \ B$
==Združitev (Zd)==: $A,B \ \models \ A \land B$
==Poenostavitev (Po)==: $A \land B \ \models \ A,B$
==Pridružitev (Pr)==: $A \models A \lor B$

Pravilnost sklepa dokažemo tako, da sestavimo zaporedje izjavnih izrazov, za vsak člen pa velja:
1. $C_i$ je ena od predpostavk
2. $C_i$ je tavtologija
3. $C_i$ je enakovreden enemu od predhodnih izrazov v zaporedju
4. $C_i$ logično sledi iz predhodnih izrazov po enem od osnovnih pravil sklepov

==Pogojni sklep (PS)==: uporabljamo, kadar ima zaključek sklepa obliko implikacije
$$A_1,A_2, \ ... \ ,A_k \ \models \ B \implies C \ \ n.t. \ ko \ \ A_1,A_2, \ ... \ ,A_k,B \ \models \ C$$
==Sklep s protislovjem (RA)==: lahko uporabljamo kadarkoli
$$A_1,A_2, \ ... \ ,A_k \ \models \ B \ \ n.t. \ ko \ \ A_1,A_2, \ ... \ ,A_k,\neg B \ \models \ 0$$
==Analiza primerov (AP)==: lahko uporabljamo, kadar ima ena od predpostavk obliko disjunkcije
$$A_1,A_2, \ ... \ ,A_k,B_1 \lor B_2 \ \models \ C \ \ n.t. \ ko \ \ A_1,A_2, \ ... \ ,A_k,B_1 \ \models \ C \ \ in \ \ A_1,A_2, \ ... \ ,A_k,B_2 \ \models \ C$$
