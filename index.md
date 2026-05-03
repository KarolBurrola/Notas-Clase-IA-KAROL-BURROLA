---
layout: null
---
<meta charset="UTF-8">
<title>Notas de Inteligencia Artificial</title>
<style>
  * {
    box-sizing: border-box;
  }
  
  body {
    margin: 0;
    padding: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
    background-color: #f6f7ff;
    color: #2e2a5a;
  }

  .distribucion {
    display: flex;
    min-height: 100vh;
    width: 100vw;
  }

  .barra-lateral {
    width: 260px;
    min-width: 260px;
    background: linear-gradient(180deg, #eef0ff, #f7f8ff);
    padding: 28px 20px;
    border-right: 5px solid #6c5ce7;
    height: 100vh;
    position: sticky;
    top: 0;
  }

  .barra-lateral h2 {
    color: #5b4cf0;
    font-size: 22px;
    margin-bottom: 22px;
    margin-top: 0;
  }

  .barra-lateral strong {
    display: block;
    margin-bottom: 12px;
    color: #4a43b8;
  }

  .barra-lateral a {
    display: block;
    padding: 12px 16px;
    margin-bottom: 12px;
    border-radius: 14px;
    text-decoration: none;
    color: #3f3a8a;
    background-color: #ecebff;
    font-weight: 500;
    transition: all 0.2s ease;
  }

  .barra-lateral a:hover {
    background-color: #dcd9ff;
  }

  .contenido {
    flex: 1;
    padding: 45px;
    max-width: calc(100vw - 260px);
  }

  .panel {
    display: none;
  }

  .panel:target {
    display: block;
  }

  #inicio {
    display: block;
  }

  .panel:target ~ #inicio {
    display: none;
  }

  .tarjeta {
    background-color: #ffffff;
    border-radius: 22px;
    padding: 36px;
    box-shadow: 0 15px 40px rgba(92, 79, 230, 0.18);
    width: 100%;
  }

  .titulo {
    font-size: 34px;
    color: #5b4cf0;
    margin-bottom: 12px;
    margin-top: 0;
  }

  .subtitulo {
    color: #6b65c6;
    margin-bottom: 28px;
  }

  .objetivo {
    margin-top: 32px;
    padding: 26px;
    border-radius: 18px;
    background-color: #f0efff;
    border-left: 7px solid #6c5ce7;
  }

  .boton-pdf {
    margin-top: 28px;
    display: inline-block;
    padding: 10px 22px;
    background-color: #6c5ce7;
    color: white;
    border-radius: 12px;
    text-decoration: none;
    font-size: 15px;
    font-weight: 500;
    transition: all 0.2s ease;
  }

  .boton-pdf:hover {
    background-color: #5b4cf0;
    box-shadow: 0 4px 12px rgba(108, 92, 231, 0.4);
  }

  .notas-texto {
    line-height: 1.6;
    font-size: 17px;
  }
  .notas-texto h1, .notas-texto h2 {
    color: #5b4cf0;
    margin-top: 30px;
  }
  .notas-texto h3 {
    color: #6c5ce7;
    font-size: 1.25em;
    margin-top: 25px;
    margin-bottom: 10px;
  }
  .notas-texto h1 {
    text-align: center;
    border-bottom: 2px solid #ecebff;
    padding-bottom: 15px;
    margin-bottom: 30px;
    font-size: 2.2em;
  }
  .notas-texto h2 {
    background-color: #f0efff;
    padding: 10px 15px;
    border-radius: 8px;
    border-left: 6px solid #6c5ce7;
    font-size: 1.5em;
    margin-bottom: 15px;
  }
  .notas-texto ul {
    margin-bottom: 20px;
    padding-left: 25px;
  }
  .notas-texto li {
    margin-bottom: 5px;
  }
  .notas-texto hr {
    border: none;
    height: 2px;
    background: linear-gradient(to right, transparent, #dcd9ff, transparent);
    margin: 30px auto;
  }
</style>

<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    }
  };
</script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<div class="distribucion">

<div class="barra-lateral">
  <h2>Índice del Curso</h2>
  <strong>Contenido: </strong>
  <a href="#notas11">Notas 1.1 (Fotos)</a>
  <a href="#notas12">Notas 1.2 (Texto)</a>
  <a href="#inicio">Volver al Inicio</a>
</div>

<div class="contenido">

<div id="notas11" class="panel">
  <div class="tarjeta">
    <div class="titulo">Notas 1.1 - Apuntes tomados a mano en clase</div>
    <p>Haz clic en el botón para ver mis notas en formato PDF.</p>
    <a href="./notas/notas_ia_completas.pdf" class="boton-pdf">Abrir PDF</a>
  </div>
</div>

<div id="notas12" class="panel">
<div class="tarjeta notas-texto" markdown="1">

# Resumen de Apuntes del Curso de Inteligencia Artificial

A continuación, se presenta una agenda detallada de los temas cubiertos en el curso de Inteligencia Artificial.

## I. Introducción a la Inteligencia Artificial

### Definición de Inteligencia Artificial
* Sistemas que piensan como humanos.
* Sistemas que actúan como humanos.
* Sistemas que piensan racionalmente.
* Sistemas que actúan racionalmente.

### Conceptos Fundamentales
* Ciencia vs. Ingeniería: La ciencia explica los porqués, mientras que la ingeniería aplica conocimientos científicos para resolver problemas.
* Racionalidad: Definida como la maximización de la esperanza de una utilidad futura.

### El Agente Inteligente
* Definición: Entidad que se comunica con un entorno o ambiente mediante sensores y actuadores.
* Estructura PEAS: Performance (Medida de desempeño), Entorno, Actuadores y Sensores.

## II. Modelado de Problemas y Entornos

### Espacio de Estados ($S$)
* Definición formal: $S = (S_1, S_2, ..., S_n) \in D_1 \times D_2 \times ... \times D_n$.
* Ejemplos de modelado: Problema del viajero (Permutaciones), Clasificación de imágenes (Pixeles $RGB$), Torres de Hanoi, Misioneros y caníbales, y Helicóptero (Variables continuas).

### Clasificación de Modelos / Entornos
* Estáticos vs. Dinámicos: Los dinámicos dependen del estado anterior ($S_{k+1} = f(S_k, a_k)$), los estáticos se resuelven directo.
* Discretos vs. Continuos: Cardinalidad finita vs. infinita.
* Deterministas vs. Estocásticos: Conocimiento exacto del futuro vs. incertidumbre (probabilidades).
* Totalmente Observables vs. Parcialmente Observables: Conocimiento completo del estado actual vs. necesidad de inferencia a partir de percepciones ($P_k = g(X_k)$).
* Episódicos: Donde hay forma de haber aprendizaje.

### Agente Reflejo vs. Agente Racional
* Un agente racional no es necesariamente perfecto.
* Agente reflejo actúa basado solo en la percepción actual ($a_t = f(P_t)$ o $a_t = f(P_t, X_t)$ si mantiene estado interno).
* Ejemplo: Vacuum cleaner world (Mundo de la aspiradora).

## III. Resolución de Problemas mediante Búsqueda

### Definición Formal de Problema de Búsqueda
* Espacio de estados $S$ y Estado inicial $S_0$.
* Conjunto de estados finales $S_f \subseteq S$.
* Acciones legales $A(s) \subseteq A$.
* Función sucesor: $Succ(S, A) \rightarrow S$.
* Costo local: $\text{costo\_local}(S, A) \rightarrow \mathbb{R}^+$.

### El Objetivo (Plan)
* Encontrar una secuencia de transiciones desde $S_0$ hasta un estado en $S_f$ tal que la suma de los costos locales sea mínima.

### Implementación Computacional
* Clase abstracta SearchPb (métodos a implementar: acciones, sucesor, terminal).
* Estructura de NodoSearch (estado, acción, padre, costo, profundidad).
* Estructura general de algoritmos de búsqueda: Uso de frontera.

### Algoritmos de Búsqueda No Informada
* Búsqueda en Anchura (BFS): Usa una cola. Complejidad temporal y espacial $O(b^d)$ (donde $b$ es el factor de ramificación y $d$ la profundidad). Óptimo solo si los costos son iguales ($C_l=1$).
* Búsqueda en Profundidad (DFS): Usa una pila. Peligro de ciclos infinitos.
* Búsqueda por Profundidad Iterativa (IDS): Combina eficiencia de memoria de DFS con la completitud de BFS.

### Algoritmos de Búsqueda Informada
* Uso de Heurísticas ($h(n)$): Estimación del costo desde el estado actual a la meta (basado en un problema relajado).
* Admisibilidad: Una heurística es admisible si nunca sobreestima el costo real para llegar a la meta ($h(n) \le g^*(n)$).
* Dominancia: Si $h_2(n) \ge h_1(n)$ y ambas son admisibles, $h_2$ domina a $h_1$ (es mejor).
* Búsqueda de Costo Uniforme (UCS): Ordena frontera por costo acumulado ($g(n)$).
* Búsqueda Codiciosa (Greedy): Ordena frontera solo por heurística ($h(n)$). Rápida pero no garantiza optimalidad.
* Algoritmo A*: Ordena frontera por $f(n) = g(n) + h(n)$. Si $h(n)$ es admisible, A* es óptimo.

## IV. Juegos y Teoría de Decisiones con Adversarios (Multi-Agente)

### Tipos de Juegos
* De suma cero (competencia pura: lo que uno gana, el otro lo pierde).
* Suma general (utilidades independientes).
* Juegos de equipo.
* Entornos: Deterministas vs. Estocásticos, Turnos vs. Simultáneos, Información perfecta vs. Imperfecta.

### Juegos Deterministas de Dos Jugadores (Suma Cero)
* Algoritmo Minimax: Se asume juego óptimo del adversario. Nodo MAX maximiza el valor; nodo MIN minimiza el valor. Implementación como funciones recursivas.
* Poda Alfa-Beta ($\alpha-\beta$): Optimización de Minimax. Permite saltar la evaluación de ramas que no cambiarán la decisión final. $\alpha$: Mejor opción para MAX en el camino. $\beta$: Mejor opción para MIN en el camino.
* Negamax: Variante de Minimax para simplificar código ($max(x,y) = -min(-x,-y)$).

## V. Cadenas de Markov y Procesos de Decisión de Markov (MDP)

### Cadenas de Markov
* Entornos discretos, dinámicos, estocásticos y conocidos.
* Propiedad de Markov: El estado futuro depende solo del estado presente, no de la historia pasada ($Pr(y_T \mid y_{0:T-1}) \equiv Pr(y_T \mid y_{T-1})$).
* Matriz de transición y cálculo de probabilidades futuras ($P(X_t) = A^t P(X_{t0})$).

### Procesos de Decisión de Markov (MDP)
* Modelo matemático para toma de decisiones secuenciales bajo incertidumbre.
* Componentes: Estados ($S$), Acciones ($A$), Función de Transición ($T(s, a, s')$), Función de Recompensa ($r(s, a, s')$), Factor de Descuento ($\gamma$).
* Objetivo: Encontrar una Política ($\Pi: S \rightarrow A$) que maximice la esperanza de la recompensa total futura ($E^\Pi[R_T]$).

### Funciones de Valor y Ecuaciones de Bellman
* Función de Valor de Estado ($V^\Pi(s)$): Esperanza de recompensa siguiendo la política $\Pi$ desde el estado $s$.
* Función de Valor de Estado-Acción ($Q^\Pi(s, a)$): Esperanza de recompensa tomando la acción $a$ en el estado $s$ y luego siguiendo la política $\Pi$.
* Ecuación de Optimalidad de Bellman: Relación recursiva para encontrar el valor óptimo.
$$V^{\ast}(s) = \max_a \left( \sum_{s' \in S} T(s,a,s') [r(s,a,s') + \gamma V^{\ast}(s')] \right)$$

### Resolución de MDPs (Programación Dinámica)
* Iteración de Valores (Value Iteration): Actualización iterativa de la función de valor $V(s)$ hasta la convergencia.
* Iteración de Políticas (Policy Iteration): Evaluación de una política y posterior mejora iterativa.

## VI. Aprendizaje por Refuerzo (Reinforcement Learning - RL)

### Contexto
* Se aplica cuando el modelo del entorno (las probabilidades de transición $T$ y las recompensas $r$) es desconocido. El agente debe aprender interactuando (MDPsim).

### Diferencia Temporal (Temporal Difference - TD)
* Aprendizaje basado en la diferencia entre la estimación actual y una estimación mejorada obtenida tras un paso de interacción.
* Fórmula de actualización general: $\hat{V}^\Pi(s) \leftarrow \hat{V}^\Pi(s) + \alpha [r + \gamma \hat{V}^\Pi(s') - \hat{V}^\Pi(s)]$, donde $\alpha$ es la tasa de aprendizaje.

### Algoritmos de Control en RL
* SARSA (On-policy): Aprende la función $Q$ evaluando la política actual que está siguiendo el agente. Actualización: $Q(s, a) \leftarrow Q(s, a) + \alpha [r + \gamma Q(s', a') - Q(s, a)]$, donde $a'$ se selecciona usando la misma política.
* Q-Learning (Off-policy): Aprende la función $Q$ óptima independientemente de la política exploratoria seguida por el agente. Actualización: $Q(s, a) \leftarrow Q(s, a) + \alpha [r + \gamma \max_{a'} Q(s', a') - Q(s, a)]$.

### Políticas de Exploración
* $\epsilon$-greedy (Epsilon-Greedy): Con probabilidad $\epsilon$ se toma una acción aleatoria (exploración), con probabilidad $1-\epsilon$ se toma la mejor acción conocida (explotación).

## VII. Aprendizaje Automático: Modelos Predictivos y Supervisados

### Definición Formal
* Encontrar una función parametrizada $h^*$ dentro de un espacio de hipótesis $\mathcal{H}$ que aproxime lo mejor posible a una función desconocida $f: X \rightarrow Y$, a partir de una muestra de datos $D$.

### Métricas de Error (Función de Pérdida - Loss Function)
* Error en la muestra ($E_{in}$) vs. Error fuera de la muestra ($E_{out}$). El objetivo es $E_{in} \approx E_{out} \approx 0$.
* Para Regresión ($Y \in \mathbb{R}$): Error Cuadrático Medio (MSE).
* Para Clasificación ($Y \in \{-1, 1\}$): Error de clasificación ($0$ si es igual, $1$ si es distinto).

### Modelos Lineales
* Regresión Lineal: Hipótesis $\hat{y} = w^T X + b$. Solución analítica con seudoinversa $\Theta^* = (X_e^T X_e)^{-1} X_e^T Y$.
* Clasificación Binaria (Perceptrón - PLA): Hipótesis $h_{\Theta} = sign(w^T X + b)$.
* Regresión Logística: Transforma clasificación a regresión estimando probabilidades usando la función sigmoide ($\sigma(z) = \frac{1}{1+e^{-z}}$).

### Optimización de Modelos
* Descenso de Gradiente: Algoritmo iterativo para encontrar el mínimo de la función de pérdida. Regla de actualización: $\Theta \leftarrow \Theta - \eta \nabla E_{in}(\Theta)$, donde $\eta$ es la tasa de aprendizaje.
* Expansión Polinomial: Transformación del espacio de entrada original $X$ a un espacio de mayor dimensión $\Phi(X)$ para permitir fronteras de decisión no lineales.
* Regularización: Técnica para evitar el sobreajuste penalizando modelos demasiado complejos. Restricción de norma $L_2$ (Ridge) o $L_1$ (Lasso).

## VIII. Aprendizaje Automático: Árboles de Decisión y Ensambles

### Árboles de Decisión
* Divide el espacio de características con reglas recursivas.
* Entropía: Medida de impureza o desorden en los datos ($Entropia = - \sum p \log_2(p)$).
* Ganancia de Información: Criterio para elegir qué característica usar para dividir un nodo. Se busca la división que reduzca más la entropía.

### Métodos de Ensamble (Bagging)
* Concepto: Juntar múltiples clasificadores débiles (ej. árboles sencillos) para crear un modelo robusto.
* Bagging reduce la varianza en conjuntos de datos ruidosos.

## IX. Optimización (Búsquedas Locales)

### Propósito
* Encontrar máximos o mínimos globales o locales de una función objetivo $f(x)$ en espacios de búsqueda continuos o combinatorios donde los algoritmos exactos son ineficientes.

### Algoritmos
* Búsqueda Aleatoria: Explora estados al azar, guardando el mejor encontrado.
* Descenso de Colinas (Hill Climbing): Evalúa los vecinos del estado actual y se mueve al vecino con mejor costo. Se detiene al llegar a un mínimo o máximo local.
* Temple Simulado (Simulated Annealing): Variante de descenso de colinas que permite movimientos hacia estados peores con cierta probabilidad para escapar de óptimos locales.
* Algoritmos Genéticos: Inspirados en la evolución. Maneja una población de soluciones. Operadores incluyen Función de Adaptación (Fitness), Selección (Ruleta, Torneo), Cruza (Crossover), Mutación y Elitismo.

<hr>
<p style="text-align: right; font-size: 0.85em; color: #8c85d8; margin-top: 30px;">
  <em>Apuntes elaborados con ayuda de Gemini</em>
</p>

</div>
</div>

<div id="inicio">
<div class="tarjeta">
<div class="titulo">Notas de Inteligencia Artificial</div>
<div class="subtitulo">Por: Karol Burrola Torres</div>

<div class="objetivo">
<strong>Objetivo:</strong> Comprender los conceptos fundamentales del curso de Inteligencia Artificial organizándolos por medio de notas, apuntes y material de apoyo
</div>
</div>
</div>

</div>
</div>
