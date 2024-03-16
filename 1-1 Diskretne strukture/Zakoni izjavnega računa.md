Topics: [[Izjave]]
- - -
1. Zakon dvojne negacije:  $$\begin{aligned} \neg\neg A &\sim A \end{aligned}$$
2. Idempotenca: $$\begin{aligned} A \land A &\sim A \\ A \lor A &\sim A \end{aligned}$$
3. Komutativnost: $$\begin{aligned} A \land B &\sim B \land A \\ A \lor B &\sim B \lor A \\ A \iff B &\sim B \iff A \end{aligned}$$
4. Asociativnost: $$\begin{aligned} (A \land B) \land C &\sim A \land (B \land C) \\ (A \lor B) \lor C &\sim A \lor (B \lor C) \\ (A \iff B) \iff C &\sim A \iff (B \iff C) \end{aligned}$$
5. Absorpcija: $$\begin{aligned} A \land (A \lor B) &\sim A \\ A \lor (A \land B) &\sim A \end{aligned}$$
6. Distributivnost: $$\begin{aligned} (A \lor B) \land C &\sim (A \land C) \lor (B \land C) \\ (A \land B) \lor C &\sim (A \lor C) \land (B \lor C) \end{aligned}$$
7. de Morganova zakona: $$\begin{aligned} \neg(A \lor B) &\sim \neg A \land \neg B \\ \neg(A \land B) &\sim \neg A \lor \neg B \end{aligned}$$
8. Kontrapozicija: $$\begin{aligned} A \implies B &\sim \neg B \implies A \end{aligned}$$
9. Lastnosti 0 in 1: $$\begin{aligned} A \implies A &\sim 1 \\ A \iff A &\sim 1 \\ A \lor \neg A &\sim 1 \\ A \land \neg A &\sim 0 \end{aligned}$$
10. Še lastnosti 0 in 1: $$\begin{aligned} A \land 0 &\sim 0 \\ A \lor 0 &\sim A \\ A \land 1 &\sim A \\ A \lor 1 &\sim 1 \\ A \implies 0 &\sim \neg A \\ 0 \implies A &\sim 1 \\ A \implies 1 &\sim 1 \\ 1 \implies A &\sim A \end{aligned}$$
11. Lastnosti implikacije: $$\begin{aligned} A \implies B &\sim \neg A \lor B \\ \neg (A \implies B) &\sim A \land \neg B \end{aligned}$$
12. Lastnosti ekvivalence: $$\begin{aligned} A \iff B &\sim (A \implies B) \land (B \implies A) \\ A \iff B &\sim (A \land B) \lor (\neg A \land \neg B) \\ \neg (A \iff B) &\sim \neg A \iff B \end{aligned}$$
13. Ekskluzivna disjunkcija: $$\begin{aligned} A \veebar B &\sim \neg(A \iff B) \\ A \veebar B &\sim B \veebar A \\ (A \veebar B) \veebar C &\sim A \veebar (B \veebar C) \end{aligned}$$
14. Shefferjev veznik: $$\begin{aligned} A \uparrow B &\sim \neg(A \land B) \\ A \uparrow B &\sim B \uparrow A \end{aligned}$$
15. Pierceov veznik: $$\begin{aligned} A \downarrow B &\sim \neg(A \lor B) \\ A \downarrow B &\sim B \downarrow A \end{aligned}$$
Dualne zakone dobimo z zamenjavo konjunkcije in disjunkcije ter 0 in 1 v (večini) zakonov

Izraz $A_1 \veebar A_2 \veebar \ ... \ \veebar A_n$  je (ne glede na postavitev oklepajev) resničen, ko je liho mnogo členov resničnih.

==Osnovna konjunkcija/disjunkcija==: konjunkcija/disjunkcija izjavnih spremenljivk in/ali njihovih negacij
==Disjunktivna Normalna Oblika (DNO)==: disjunkcija osnovnih konjunkcij
==Konjunktivna Normalna Oblika (KNO)==: konjunkcija osnovnih disjunkcij
Vsak izjavni izraz ima DNO in KNO

==Poln nabor izjavnih veznikov==: družina izjavnih veznikov N, če za vsak izjavni izraz A obstaja enakovreden izjavni izraz B, ki vsebuje samo veznike iz N.
Primeri: {$\neg,\land,\lor$}, {$\neg,\land$}, {$\neg,\lor$}, {$\neg,\implies$}, {$0,\implies$}, {$\uparrow$}, {$\downarrow$}
Dokaz polnosti nabora izjavnih veznikov: vsak veznik iz že znanega polnega nabora izrazimo samo z uporabo veznikov testiranega nabora