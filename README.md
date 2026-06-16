# Estadística Bayesiana

Trabajos y notas para la clase de **Estadística Bayesiana**  
UAEMex Valle de México · 2025  
Ximena Quintanar Leal

---

## Contenido

| Archivo | Tema | Fuente |
|---|---|---|
| [`Introduccion_EB.ipynb`](Introduccion_EB.ipynb) | Fundamentos del enfoque bayesiano, Teorema de Bayes, prior/posterior, distribuciones conjugadas | Clase |
| [`Teorema_LC.ipynb`](Teorema_LC.ipynb) | Teorema del Límite Central, convergencia en distribución, conexión con posteriors asintóticos | Clase |
| [`Replica_Teorema_LC.ipynb`](Replica_Teorema_LC.ipynb) | Réplica práctica del TLC mediante simulación (promedio de dados) | Clase |
| [`Guia_Martingalas_Tiempo_Discreto.ipynb`](Guia_Martingalas_Tiempo_Discreto.ipynb) | Martingalas en tiempo discreto, caminata aleatoria, urna de Pólya, tiempos de paro | Galindo §8 |
| [`Metropolis_Hastings.ipynb`](Metropolis_Hastings.ipynb) | Algoritmo MCMC Metrópolis–Hastings, inferencia bayesiana, convergencia a π | Galindo §11.9 |
| [`HMM_Filtrado_Bayesiano.ipynb`](HMM_Filtrado_Bayesiano.ipynb) | Cadenas de Markov Ocultas, filtrado bayesiano secuencial, cambio de medida | Galindo §11.4 |
| [`Cambio_de_Medida_Radon_Nikodym.ipynb`](Cambio_de_Medida_Radon_Nikodym.ipynb) | Teorema de Radon–Nikodym, identidad E_Q[X] = E_P[XZ], selección como cambio de medida | Galindo §1–7 |

---

## Temas cubiertos

**Fundamentos bayesianos**
- Inferencia bayesiana vs. frecuentista
- Distribución a priori, verosimilitud y distribución a posteriori
- Familias conjugadas: Beta-Binomial, Gamma-Poisson, Normal-Normal
- Teorema de Bernstein–von Mises y aproximaciones asintóticas del posterior

**Teoría de la probabilidad**
- Teorema del Límite Central y desigualdad de Berry-Esseen
- Martingalas en tiempo discreto: definición, propiedades, convergencia
- Tiempos de paro y Teorema de Paro Opcional
- Cambio de medida y Teorema de Radon–Nikodym

**Métodos computacionales**
- Algoritmo de Metrópolis–Hastings (MCMC)
- Cadenas de Markov Ocultas y algoritmo de filtrado hacia adelante
- Simulación y verificación numérica del TLC

---

## Requisitos

```bash
pip install numpy scipy matplotlib nbformat
```

---

> Notas basadas en el curso y en: Galindo, C. *Cambio de medida en probabilidad y análisis estocástico*.

*Actuaria · UAEMex Valle de México*
