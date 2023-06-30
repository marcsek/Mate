Koncept: [[Derivácie]]
Témy:
- [[#Derivácie jednoduchých funkcií]]
</br>
### Derivácie jednoduchých funkcií
---
Hlavne zamerané na použivanie [[Derivácie#Elementárne funckie|známych funckií]] a [[Derivácie#Algebraické pravidlá (pravidlá derivovania)|algebralických pravidiel]].
</br>
##### Príklad č. 1
---

$f(x) = 5x^3 - 7x^2 + 8x -14$
$f'(x) = ?$

*Riešenie:*
$$f'(x) = \frac{d}{dx}(5x^3 - 7x^2 + 8x -14)$$
$$f'(x)=\frac{d}{dx}(5x^3)+\frac{d}{dx}(-7x^2)+\frac{d}{dx}(8x)+\frac{d}{dx}(-14)$$
$$f'(x)=5\frac{d}{dx}(x^3)-7\frac{d}{dx}(x^2)+8\frac{d}{dx}(8x)+0$$
$$f'(x)=15x^2-14x+8$$
</br>
##### Príklad č. 2
---

$f(x) = \frac{2}{\sqrt{x}}$
$f'(x)=?$

*Riešenie:*
$$f'(x) = \frac{d}{dx}\left(\frac{2}{\sqrt{x}}\right)$$
$$f'(x) = \frac{d}{dx}\left(2x^{-\frac{1}{2}}\right)$$
$$f'(x) = 2\frac{d}{dx}\left(x^{-\frac{1}{2}}\right)$$
$$f'(x) = 2\left(-\frac{1}{2}\right)x^{-\frac{3}{2}}$$
$$f'(x) = -x^{-\frac{3}{2}}$$
$$f'(x) = -\frac{1}{\sqrt{x^3}}$$
$$f'(x) = -\frac{1}{x\sqrt{x}}$$
</br>
##### Príklad č. 3
---

$f(x) = \frac{x \sqrt[3]{x}}{\sqrt{x^3}}$
$f'(x) = ?$

*Riešenie:*
$$f'(x) = \frac{d}{dx}\left(\frac{x \sqrt[3]{x}}{\sqrt{x^3}}\right)$$
$$f'(x) = \frac{d}{dx}\left(x \cdot x^{\frac{1}{3}}\cdot x^{-\frac{3}{2}}\right)$$
$$f'(x) = \frac{d}{dx}\left(x^{-\frac{1}{6}}\right)$$
$$f'(x) = \left(-\frac{1}{6}\right)x^{-\frac{7}{6}}$$

$$f'(x) = -\frac{1}{6\sqrt[6]{x^7}}$$
</br>
##### Príklad č.4
---

$f(x)=\frac{2x-1}{2x+1}$
$f'(x)=?$

*Riešenie:*
$$f'(x)=\frac{d}{dx}\left(\frac{2x-1}{2x+1}\right)$$
$$f'(x)=\frac{(2x-1)'\cdot(2x+1)-(2x-1)\cdot(2x+1)'}{(2x+1)^2}$$
$$f'(x)=\frac{2\cdot(2x+1)-(2x-1)\cdot2}{(2x+1)^2}$$
$$f'(x)=\frac{4}{(2x+1)^2}$$
</br>
##### Príklad č. 5
---

$f(x)=\frac{e^x-1}{e^x}$
$f'(x)=?$

*Riešenie:*
$$f'(x)=\frac{d}{dx}\left(\frac{e^x-1}{e^x}\right)$$
$$f'(x)=\frac{(e^x-1)' \cdot e^x - (e^x-1)\cdot(e^x)'}{(e^x)^2}$$
$$f'(x)=\frac{e^x\cdot e^x - e^x\cdot e^x+e^x}{(e^x)^2}$$
$$f'(x)=\frac{e^{2x} - e^{2x}+e^x}{e^{2x}}$$
$$f'(x)=\frac{1}{e^{x}}$$
$$f'(x)={e^{-x}}$$
</br>
##### Príklad č. 6
---

$f(\theta) = \sin2\theta$
$f'(\theta) = ?$

*Riešenie:*
$$f'(\theta) = \frac{d}{d\theta}(\sin2\theta)$$
$$f'(\theta) = \frac{d}{d\theta}(2\sin \theta \cdot \cos \theta)$$
$$f'(\theta) = 2\frac{d}{d\theta}(\sin \theta \cdot \cos \theta)$$
$$f'(\theta) = 2((\sin \theta)' \cdot \cos \theta + \sin \theta \cdot (\cos \theta)')$$
$$f'(\theta) = 2(\cos \theta \cdot \cos \theta + \sin \theta \cdot (-1)\sin \theta)$$
$$f'(\theta) = 2(\cos^2 \theta - \sin^2 \theta)$$
$$f'(\theta) = 2\cos 2\theta$$
</br>
##### Príklad č. 7
---

$f(\theta) = \tan \theta$
$f'(\theta) = ?$

*Riešenie:*
$$f'(\theta)=\frac{d}{dx}(\tan \theta)$$
$$f'(\theta)=\frac{d}{dx}\left(\frac{\sin \theta}{\cos\theta}\right)$$
$$f'(\theta)=\frac{(\sin \theta)'\cdot \cos \theta - \sin \theta \cdot (\cos \theta)'}{\cos^2\theta}$$
$$f'(\theta)=\frac{\cos \theta\cdot \cos \theta + \sin \theta \cdot \sin \theta}{\cos^2\theta}$$
$$f'(\theta)=\frac{1}{\cos^2\theta}$$
$$f'(\theta)={\sec^2\theta}$$
</br>
##### Príklad č 8
---

$f(x) = x^2 \ln{x}$
$f'(x) = ?$

*Riešenie:*
$$f'(x)=\frac{d}{dx}\left(x^2 \ln{x}\right)$$
$$f'(x)=(x^2)' \cdot \ln{x} + x^2 \cdot (\ln{x})'$$
$$f'(x)=2x \cdot \ln{x} + x^2 \cdot x^{-1}$$
$$f'(x)=2x \cdot \ln{x} + x$$
$$f'(x)=x\left(2\ln{x} + 1\right)$$
</br>
##### Príklad č. 9
---

$f(x) = 4^x - x^4$
$f'(x) = ?$

*Riešenie:*
$$f'(x) = \frac{d}{dx}\left(4^x-x^4\right)$$
$$f'(x) = \frac{d}{dx}\left(4^x-x^4\right)$$
$$f'(x) = \frac{d}{dx}\left(4^x\right)+ \frac{d}{dx}\left(-x^4\right)$$
$$f'(x) = \ln{4}\cdot4^x -4x^3$$
$$f'(x) = 4^x \cdot\ln{4} -4x^3$$
