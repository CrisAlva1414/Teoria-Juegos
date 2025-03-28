# Simulaciones de Teoría de Juegos: Axelrod y Más 🎮

Este repositorio contiene simulaciones en Python de los experimentos clásicos de Robert Axelrod en teoría de juegos, junto con extensiones modernas que exploran herencia genética, orientación espacial y desviaciones basadas en inteligencia artificial (AI). Aquí encontrarás herramientas para entender cómo las estrategias cooperativas y competitivas emergen, evolucionan y se adaptan en entornos dinámicos.

---

## 📜 Orígenes de la Teoría de Juegos

La **teoría de juegos** nace en el siglo XX como un marco matemático para analizar decisiones estratégicas entre agentes racionales. Sus fundamentos se establecieron con los trabajos de **John von Neumann** y **Oskar Morgenstern** en *Theory of Games and Economic Behavior* (1944), y luego con las contribuciones de **John Nash** sobre equilibrios no cooperativos. Axelrod, en los años 80, revolucionó el campo al organizar torneos computacionales donde programas competían en el *Dilema del Prisionero Iterado*, demostrando que estrategias simples como **Tit for Tat** (Toma y Daca) podían fomentar cooperación incluso en entornos egoístas.

---

## 🧩 El Dilema del Prisionero: Cooperación vs. Traición

### La Paradoja Clásica
En el **Dilema del Prisionero**, dos delincuentes son interrogados por separado:
- Si ambos **cooperan** (no delatan), reciben una pena leve.
- Si uno **traiciona** y el otro coopera, el traidor sale libre y el cooperador recibe máxima pena.
- Si ambos traicionan, ambos reciben penas moderadas.

Aunque la cooperación genera el mejor resultado colectivo, el incentivo individual lleva a la traición (equilibrio de Nash). Axelrod demostró que, en interacciones repetidas, estrategias *reciprocantes* como **Tit for Tat** (iniciar cooperando y luego replicar la acción previa del oponente) superan a las puramente egoístas. De forma que, comprendemos que la teoria de juegos tiene mucho que dictar en un entendimiento social a partir de perspectivas sistemicas.

### Crítica al Modelo de Una Sola Interacción
El dilema clásico asume una **única interacción**, lo que favorece la tracción como estrategia dominante. Sin embargo, en la vida real (economía, ecología, redes sociales), las interacciones son **repetidas** y los agentes pueden aprender. Esto permite que estrategias como el perdón (*Tit for Two Tats*) o la tolerancia (*Generous Tit for Tat*) prosperen. Nuestras simulaciones incluyen variantes de múltiples rondas y entornos dinámicos para explorar estos matices, ya que, la ignorancia a la dinamica del juego permite entender como se comportan los usuarios, como ejemplo, tendriamos que a la ultima interaccion, nadie copera. lo cual en el mundo real es imposible comprender cuando sera la ultima interaccion entre dos objetos.

---

## 🤖 Participantes en los Torneos

### Estrategias Clásicas
- **Tit for Tat (TFT)**: Cooperar en la primera ronda, luego imitar la jugada anterior del rival.
- **Always Defect (ALLD)**: Traicionar siempre. Efectivo en una sola ronda, pero fracasa en iteraciones.
- **Random**: Elecciones aleatorias. Sirve como "línea base" caótica.
- **Freeman**: Estrategia hipotética que prioriza la reputación (ej: coopera si el oponente tiene historial cooperativo).

### Nuevos Algoritmos
- **Herencia Genética**: Estrategias que evolucionan mediante selección natural (algoritmos genéticos).
- **Orientación Espacial**: Agentes ubicados en una red (ej: grilla) que solo interactúan con vecinos, simulando efectos geográficos o sociales.
- **AI-Based Players**: Agentes que usan aprendizaje por refuerzo o redes neuronales para adaptar su estrategia en tiempo real.

A modo de conclusion, quiero generar modelos teoricos concretos que se acerquen poco a poco a las dinamicas sociales presentes en el mundo real, con la finalidad de poder concluir ciertos comportamientos acerca la naturaleza, tanto general como humana.
