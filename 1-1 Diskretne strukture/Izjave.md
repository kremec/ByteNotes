Topics: #izjava #izjavni_vezniki
- - -
==Izjava==: stavek, ki je bodisi resničen bodisi neresničen - ima logično vrednost
 - Delitev po vsebini: resnične / neresnične
 - Delitev po obliki: osnovne (npr. "Sije sonce") / sestavljene (npr. "Peter je zunaj in sije sonce")
### Izjavni vezniki
Enomestni (ne) / Dvomestni (in, ali, če ... potem ..., niti ... niti ...)

==Izjavni konstanti==: 0 in 1
==Izjavne spremenljivke==: p, q, r označujejo osnovne izjave

==Resničnostna tabela==: tabela logičnih vrednosti izjavnega izraza za vse nabore logičnih vrednosti izjavnih spremenljivk

==Negacija==: $\neg$
==Konjunkcija==: $\land$
==Disjunkcija==: $\lor$
==Implikacija==: $\implies$
==Ekvivalenca==: $\iff$
==Eksplozivna disjunkcija==: $\veebar$
==Shefferjev veznik==: $\uparrow$
==Pierce-Lukasiewiczev veznik==: $\downarrow$

| $P$ | $Q$ | $\neg P$ | $P \land Q$ | $P \lor Q$ | $P \implies Q$ | $P \iff Q$ | $P \veebar Q$ | $P \uparrow Q$ | $P \downarrow Q$ |
| --- | --- | -------- | ----------- | ---------- | -------------- | ---------- | ------------- | -------------- | ---------------- |
| T   | T   | F        | T           | T          | T              | T          | F             | F              | F                |
| T   | F   | F        | F           | T          | F              | F          | T             | T              | F                |
| F   | T   | T        | F           | T          | T              | F          | T             | T              | F                |
| F   | F   | T        | F           | F          | T              | T          | F             | T              | T                |

Dogovor o prioriteti operatorjev: $$\neg \ \lt \  \land,\uparrow,\downarrow \ \lt \ \lor,\veebar \ \lt \ \implies \ \lt \ \iff$$
==Tavtologija==: izjavni izraz, ki je resničen pri vseh naborih logičnih vrednosti vsebovanih izjavnih spremenljivk (npr. "$1$", "$p \lor \neg p$", "$p \implies (q \implies p)$")
==Protislovje==: izjavni izraz, ki je neresničen pri vseh naborih logičnih vrednosti vsebovanih izjavnih spremenljivk (npr. "$0$", "$p \land \neg p$")

==Enakovredna== izjavna izraza:
- pri vseh naborih logičnih vrednosti izjavnih spremenljivk imata enako vrednost
- izraz $A \iff B$ je tavtologija