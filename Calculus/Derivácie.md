_Derivatives (z angl.)_
*Príklady: [[Derivácie - Príklady]]*
</br>
### Definícia derivácie
---

Derivácia nejakej funckie je zmena tejto funckie v pomere k zmene v premennej/premenných. Koncept derivácie sa dá intrepretovať rôznymi spôsobmi, napríklad v prípade dvojrozmerného grafu funkcie f(x), je derivácia tejto funkcie v ľubovoľnom bode (v ktorom existuje) rovná smernici dotyčnice tohto grafu.

```desmos-graph 
grid=false
height=300
---
 f(x)=2\sin(x)|black
 g(x)=\frac{d}{dx}(f(x))|hidden
 y=\g(2)(x-2)+f(2)|#8B6CEF
```
*tieto koncepty sú dobre vysvetlené vo videu [The paradox of the derivative](https://youtu.be/9vKqVkMQHKk)*

Historické definície vyjadrovali deriváciu ako pomer, v akom rast nejakej premennej _y_ zodpovedá zmene inej premennej _x_ _(rise over run)_. Spočiatku sa používal symbol ∆ (delta z greč.):
$$
\frac{\Delta y}{\Delta x}
$$
Derivácia je teda vlastne hodnota podielu pre $\Delta x$ blížiacu sa k $0$. Aby sme toto dokázali vyjadriť, používame nasledujúcu definíciu:
$$\frac{dy}{dx}$$
čo označuje pomer dvoch nekonečne malých hodnôt (*číta sa dy poďla dx*).

Neskôr sa však táto definícia ukázala ako nedostatočne presná a bola nahradená dnes najbežnejšou formou derivácie: 

$$
f'(x)=\lim_{h \to \infty}\frac{f(x + h) - f(x)}{h}
$$
označuje sa niekoľkými spôsobmi:
- <font size=4>$f'(x)$</font> <font size=2>_(derivácia funkcie $f$ ktorá závisí od premennej x)_</font>
- <font size=4>$\frac{d}{dx}f(x)$</font> <font size=2>(_derivácia funkcie f(x) podľa premennej x_)</font>
- <font size=4>$\frac{df}{dx}$</font> <font size=2>(_d f podľa d x_)</font>
</br>
### Výpočty derivacií
___
Principiálne základnou technikou je výpočet priamo z definície, čiže dosadením príslušnej funkcie do definujúcej limity a výpočtom tejto limity. Tento spôsob je však zvyčajne (až na veľmi jednoduché funkcie) dosť komplikovaný a v praxi sa nepoužíva. Namiesto toho sa derivácie funkcií počítajú zo známych derivácií niekoľko [[#Elementárne funckie|základných funckií]] a jednoduchých [[#Algebraické pravidlá (pravidlá derivovania)|algebraických pravidiel]] pre ich skladanie a ďalšie úpravy.

##### Elementárne funckie
| Elementárne funckie  | Funkcia | Derivácia |
| - | - | - |
| Konštanta | $f(x) = c$ | $f'(x) = 0$ |
| Lineárna | $f(x) = x$ | $f'(x)= 1$ |
| | $f(x)=ax$ | $f'(x)=a$ |
| Exponent | $f(x) = x^n$ | $f'(x)= nx^{n-1}$ |
| Mocnina |  $f(x)=c^x$ | $f'(x) = c^x \ln c$|
| Logaritmus |  $f(x)=\log_a x$ | $f'(x) =\frac {1} {x\cdot\ln a}$|  
| |  $f(x)=\ln x$ | $f'(x) = \frac{1}{x}$|  
| Goniometria |  $f(x)=\sin{x}$ | $f'(x)=\cos{x}$|
| |  $f(x)=\cos{x}$ | $f'(x)=-\sin{x}$|
| |  $f(x)=\tan{x}$ | $f'(x)=\frac{1}{\cos^2{x}}$|
| |  $f(x)=\cot{x}$ | $f'(x)=-\frac{1}{\sin^2{x}}$|

##### Algebraické pravidlá (pravidlá derivovania)
Zo známych derivácií elementárnych funkcií sa derivácie zložitejších funkcií zostavujú tak, že sa zložitejšie funkcie rozložia na jednoduchšie pomocou jednoduchých algebrických pravidiel, ktoré pre výpočet derivácií platia:

- **Linearita derivácie**: $(af + bg)' = af' + bg'$ pre ľubovoľne funckie $f, g$ a konštanty $a, b$.
	- Zjednodušene: $(f + g)' = f' + g'$
- **Derivácia rozdielu**: $(f - g)' = f' - g'$  pre ľubovoľné funkcie $f, g$
- **Derivácia súčinu**: $(fg)' = f'g + fg'$ pre ľubovoľné funkcie $f, g$
- **Derivácia podielu**: $\left(\frac{f}{g}\right)'= \frac{f'g - fg'}{g^2}$ pre ľubovoľne funckie $f,g$
- **Derivácia zloženej funkcie**: $f \circ g = (f' \circ g) \times g'$
	- Ekvivalent: $f(g(x)) = f'(g(x))g'(x)$

Dobré videá na odôvodnenie týchto vzťahov [Power Rule through geometry](https://youtu.be/S0_qX4VJhMQ), [Visualizing the chain rule and product rule](https://youtu.be/YG15m2VwSjA), [What's so special about Euler's number e?](https://youtu.be/m2MIpDrF7Es).

Stránka na prehľad týchto vzťahov: [mathisfun.com](https://www.mathsisfun.com/calculus/derivatives-rules.html)