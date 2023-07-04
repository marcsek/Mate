_Integral (z angl.)_
Príklady: 
</br>
### Definícia integrálu
---
**Integrál** je spolu s [[Derivácie|deriváciou]] najdôležitejší pojem matematickej analýzy. Pojem integrálu je zovšeobecnením pojmov ako plocha, objem, súčet či suma. Integrovanie je opačná operácia k [[Derivácie#Výpočty derivacií|derivovaniu]] (antiderivative z angl.).
</br>
![[Int_Der.png|center|half]]

### Neučitý integrál
---
Hľadanie neurčitého integrálu (primitívnej funkcie) je opačný proces k určovaniu derivácie. Pri výpočte sa vychádza zo známych integrálov.

$$\int{f(x)dx = F(x)+c}$$
Funkcia $F$ sa nazýva primitívna funkcia k funkcii $f$ na otvorenom intervale $I$, ak platí $F'=f$ na intervale $I$. Taktiež $dx$ značí, poďla akej premennej derivujeme.

Súčasťou integrácie je vzďy aj konštanta $c$. Keďže po integrácí nedostávame konkrétnu funkciu, ale všetky funckie ktoré su posunuté o ľubovoľné reálne číslo.
</br>
### Určitý  integrál
---
Jednoducho povedané, určitý integrál nezápornej funkcie $f(x)$ medzi nejakými dvoma bodmi $a, b$ je rovný ploche obrazca ohraničeného priamkami $x = a, x = b$, osou $x$ a krivkou definovanou funkciou $f$.

$$\int_{a}^{b}f(x)dx= F(b) - F(a)$$
</br>
### Výpočty integrálov
---
##### Tabuľkové vzorce integrálov
Tieto vzorce vznikajú z opačného použitia [[Derivácie#Elementárne funckie|vzorcov pre derivácie]]. Umožňujú riešiť základnú integráciu.

| Elementárne funckie  | Funkcia | Integrácia |
| - | - | - |
|Konštanta|$\int {a} \ dx$|$ax + C$|
|Mocnina|$\int {x^n} \ dx$|$\frac{x^{n+1}}{n+1} + C$|
|Exponent|$\int{a^x}\ dx$|$\frac{a^x}{\ln{a}}+C$|
||$\int {x^{-1}} \ dx$|$\ln{\mid x\mid}+C$|
||$\int{e^x \ dx}$|$e^x + C$|
|Goniometria|$\int\sin{x}\ dx$|$-\cos{x}+C$|
||$\int\cos{x}\ dx$|$\sin{x}+C$|
||$\int\csc^2{x}\ dx$|$-\cot{x}+C$|
||$\int\sec^2{x}\ dx$|$\tan{x}+C$|

##### Metódy integrácie
- **Násobenie konštantou**: $\int c f(x) \ dx = c\int {f(x) \ dx}$
- **Pravidlo súčtu**: $\int(f + g) \ dx = \int f \ dx + \int g \ dx$
- **Pravidlo rozdielu**: $\int(f + g) \ dx = \int f \ dx + \int g \ dx$
- **[[#Metóda per partes]]**
- **Substitučná metóda**

##### Metóda per partes

Per partes sa využíva na integrovanie súčinu funkcií. Integrovanie touto metódou sa v preklade nazýva aj **integrovanie (integrácia) po častiach**.

Základné pravidlo je takéto:
$$\int u'(x) v(x) \ dx = u(x)v(x)- \int u(x)v'(x) \ dx $$
Video rozoberajúce túto metodú a konkrétne využitia tejto metódy: [Metoda per partes (MAT - Integrální počet - integrace)](https://youtu.be/gZvICMtNbeQ)