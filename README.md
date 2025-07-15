# Visualización Cuántica del Átomo de Hidrógeno

En este cuaderno de Jupyter, se exploran aspectos fundamentales del átomo de hidrógeno, específicamente su función de onda y las órbitas electrónicas asociadas a los diferentes estados cuánticos. Utilizando bibliotecas como **Matplotlib**, **Seaborn** y **SciPy**, se realizan cálculos y visualizaciones para representar gráficamente tanto las probabilidades de encontrar un electrón en una región específica del espacio como las trayectorias de su órbita en diferentes niveles de energía.

---

La ecuación de la función de onda del átomo de hidrógeno es:

$$
\psi_{n,l,m}(r, \theta, \varphi) = \sqrt{\left( \frac{2}{n b_r} \right)^3 \frac{(n - l - 1)!}{2n[(n + l)!]}} e^{-r/nb_r} \left( \frac{2r}{n b_r} \right)^l L_{n-l-1}^{2l+1} · Y_l^m (\theta, \varphi)
$$

donde:
- \( {n, l, m} \) son los números cuánticos,
- \( r \), \( \theta \), y \( \varphi \) son las coordenadas esféricas,
- \( b_r \) es el radio de Bohr,
- \( L_{n-l-1}^{2l+1} \) es un polinomio de Laguerre,
- \( Y_l^m (\theta, \varphi) \) es una función esférica armónica.


---

<p align="center">
  <img src="media/all_states.png" alt="Banner" width="100%" />
</p>

---


<br>

Para más información, visita:
- [Descripción de la función de onda del átomo de hidrógeno](https://en.wikipedia.org/wiki/Hydrogen_atom#Wavefunction)
- [Visualización de las órbitas electrónicas del átomo de hidrógeno](https://en.wikipedia.org/wiki/Hydrogen_atom#Visualizing_the_hydrogen_electron_orbitals)