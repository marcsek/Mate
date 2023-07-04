Koncept: [[Integrály]]
Témy: 
- [[#Jednoduché neurčité integrály]]
</br>
### Jednoduché neurčité integrály 
---
Hlavne zamerané na použivanie [[Integrály#Tabuľkové vzorce integrálov|tabuľkových vzorcov]] a [[Integrály#Metódy integrácie|jednoduchých metód integrácie]].
</br>
##### Príklad č. 1
---

$\int \left( 3x^2-6x+3 \right) \ dx =$ ?

_Riešenie:_
$$\int3x^2 \ dx \ + \int-6x \ dx \ + \int3\ dx $$
$$3 \frac{x^{2+1}}{2+1} - 6\frac{x^{1+1}}{1+1}+3\frac{x^{0+1}}{0+1} + C$$
$$x^3 - 3x^2 + 3x + C$$
</br>
##### Príklad č. 2
---

$\int{\left(\frac{\sqrt[3]{4x}}{6}+\sqrt{\frac{1}{x^4}}\right)}\ dx =$ ?

_Riešenie:_
$$\int\frac{\sqrt[3]{4x}}{6}\ dx + \int \sqrt{\frac{1}{x^4}} \ dx$$
$$\frac{\sqrt[3]{4}}{6}\int{x^{\frac{1}{3}}}\ dx + \int \frac{1}{x^2}\ dx$$
$$\frac{\sqrt[3]{4}}{6} \cdot \frac{3x^{\frac{4}{3}}}{4} - x^{-1} + C$$
$$\frac{\sqrt[3]{4x^4}}{8} - \frac{1}{x} + C$$
</br>
##### Príklad č. 3
---

$\int \left( \sqrt{x} + \sqrt[5]{x} + \sqrt[9]{x} \right) \ dx=$ ?

_Riešenie:_
$$\int\frac{\sqrt[3]{4x}}{6}\ dx + \int \sqrt{\frac{1}{x^4}} \ dx$$


$$\int x^{\frac{1}{2}} \ dx + \int x^{\frac{1}{5}} \ dx + \int x^{\frac{1}{9}} \ dx$$
$$\frac{2x^\frac{3}{2}}{3} + \frac{5x^{\frac{6}{5}}}{6} + \frac{9x^{\frac{10}{9}}}{10} + C$$
</br>
##### Príklad č. 4
---

$\int\left( \sqrt[3]{x\sqrt{x}} + \sqrt[6]{x^5 \sqrt{x^4}} \right) \ dx=$ ?

_Riešenie:_
$$\int x^{\frac{1}{3}} x^{\frac{1}{6}} \ dx + \int x^{\frac{5}{6}}x^{\frac{1}{3}} \ dx$$
$$\int x^{\frac{1}{2}} \ dx + \int x^{\frac{7}{6}} \ dx$$
$$\frac{2x^{\frac{3}{2}}}{3} + \frac{6x^{\frac{13}{6}}}{13} + C$$
</br>
##### Príklad č. 5
---

$\int \left( \pi^2 + e - \sqrt{2} \right) \ dx=$ ?

_Riešenie:_
$$\int \pi^2 \ dx + \int e \ dx + \int -\sqrt{2} \ dx$$
$$\pi^2x + ex - \sqrt{2}x + C$$
$$\left(\pi^2 + e - \sqrt{2}\right)x + C$$
</br>
##### Príklad č. 6
---

$\int \left( 1-x^e + e^x - e^e \right) \ dx=$ ?

_Riešenie:_

$$\int 1 \ dx + \int -x^e \ dx + \int e^x \ dx + \int -e^e \ dx$$
$$x - \frac{x^e+1}{e+1} + e^x - e^ex + C$$
</br>
##### Príklad č. 7
---

$\int \left( \frac{1}{\cos^2x} - \frac{1}{\sin^2x}\right) \ dx =$ ?

_Riešenie:_

$$\int \frac{1}{\cos^2x} \ dx + \int -\frac{1}{\sin^2x} \ dx$$
$$\int \sec^2x \ dx + \int -\csc^2x \ dx$$
$$\tan^2x + \cot^2x + C$$