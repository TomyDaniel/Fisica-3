# Fisica 3

## Ondas: Fundamentos

El estudio matemático de las ondas se efectúa empleando funciones escalares o vectoriales $\psi(\vec{r},t)$, donde $\vec{r}$ es el vector posición de un punto cualquiera del espacio, *t* el instante de tiempo y $\psi$, evaluada en ($\vec{r}$,t) es una magnitud asociada a la naturaleza de la onda. En el caso electromagnético puede ser el vector campo eléctrico $\vec{E}$ o magnético $\vec{B}$.

Estas funciones se denominan "funciones de onda". Son soluciones particulares de ciertas ecuaciones a derivadas parciales.

### La Ecuación Diferencial de Onda

La ecuación fundamental que describe la propagación de una onda en una dimensión (dirección *x*) con velocidad *v* es la **ecuación de D'Alembert**:

$$ \frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} $$

Cualquier función de la forma $f(x \pm vt)$ es una solución, lo que representa una perturbación que viaja sin deformarse. La onda armónica sinusoidal es una solución particular y muy importante de esta ecuación.

### Ondas transversales y longitudinales

-   **Onda transversal:** La perturbación de las partículas del medio es **perpendicular** a la dirección de propagación ($\vec{v}$). Ejemplo: ondas en una cuerda, ondas electromagnéticas en el vacío.
-   **Onda longitudinal:** La perturbación de las partículas del medio es **paralela** a la dirección de propagación ($\vec{v}$). Ejemplo: el sonido en un gas o líquido.

En un sólido elástico se pueden dar ambos tipos, según como se lo perturbe.

### Ecuación de la Onda Armónica

La forma matemática de una onda sinusoidal que viaja en la dirección x es:

$$ y(x,t) = A \cdot sen(k \cdot x \pm w \cdot t + \varphi) $$

Donde:
- **A**: Amplitud (máxima elongación).
- **k**: Número de onda ($k = 2\pi/\lambda$).
- **w**: Frecuencia angular ($\omega = 2\pi/T = 2\pi f$).
- **φ**: Fase inicial o constante de fase.
- El signo `±` indica el sentido de propagación: `-` para el sentido +x, `+` para el sentido -x.

**Relaciones fundamentales:**

1.  $x = v \cdot t$ (Movimiento del frente de onda)
2.  $\lambda = v \cdot T$ (Longitud de onda)
3.  $f = \frac{1}{T}$ (Frecuencia y período)
4.  $v = \frac{\lambda}{T} = \lambda \cdot f$ (Velocidad de propagación)
5.  $k \cdot \lambda = 2\pi$
6.  $\omega \cdot T = 2\pi$
7.  **Velocidad de fase:** $v = \frac{\omega}{k}$

## Propagación de Ondas en Medios

La velocidad de una onda depende de las propiedades del medio en el que se propaga.

-   **Cuerdas:** Depende de la tensión (T) y la densidad lineal de masa ($\mu$).
    -   $v = \sqrt{\frac{T}{\mu}}$, con $\mu = \frac{m}{L}$

-   **Sólidos:** Depende del módulo elástico y la densidad ($\rho$) del material.
    -   **Ondas Longitudinales:** $v = \sqrt{\frac{E}{\rho}}$ (con *E* = Módulo de Young).
    -   **Ondas Transversales:** $v = \sqrt{\frac{G}{\rho}}$ (con *G* = Módulo de Corte o Cizalla).

### Energía y Potencia de una Onda

Las ondas transportan energía sin transportar materia. Para una onda armónica en una cuerda, la **potencia media** transmitida es:

$$ P_{media} = \frac{1}{2} \mu \omega^2 A^2 v $$

**Puntos clave:**
-   La potencia es proporcional al **cuadrado de la amplitud ($A^2$)**.
-   La potencia es proporcional al **cuadrado de la frecuencia ($\omega^2$)**.

Para ondas tridimensionales (ej. sonido), se define la **Intensidad (I)**:

$$ I = \frac{Potencia}{Área} $$

Para una fuente puntual que emite uniformemente, la intensidad disminuye con el cuadrado de la distancia: $I \propto \frac{1}{r^2}$.

## Superposición de Ondas

### Principio de Superposición

Cuando dos o más ondas coinciden en un punto del espacio, la elongación resultante es la **suma algebraica** de las elongaciones individuales.

$$ y_{total}(\vec{r},t) = \sum_{i} y_i(\vec{r},t) $$

Este principio es la base para entender los fenómenos de interferencia.

### Interferencia

Es el resultado de la superposición de dos o más ondas. Consideremos dos ondas con la misma amplitud, frecuencia y número de onda, pero desfasadas por un ángulo $\varphi$:

-   $y_1 = A \cdot sen(k \cdot x - w \cdot t + \varphi)$
-   $y_2 = A \cdot sen(k \cdot x - w \cdot t)$

La onda resultante $y_t = y_1 + y_2$ es:

-   $y_t = \left[ 2 \cdot A \cdot cos\left(\frac{\varphi}{2}\right) \right] \cdot sen\left(k \cdot x - w \cdot t + \frac{\varphi}{2}\right)$

La nueva amplitud $A' = 2 \cdot A \cdot cos(\frac{\varphi}{2})$ depende del desfase.

-   **Interferencia Constructiva (Amplitud máxima):** Ocurre cuando las ondas están en fase.
    -   $\frac{\varphi}{2} = n \cdot \pi \implies \varphi = 2n\pi$, con $n = 0, 1, 2, ...$
-   **Interferencia Destructiva (Amplitud mínima/nula):** Ocurre cuando están en oposición de fase.
    -   $\frac{\varphi}{2} = (2n + 1) \cdot \frac{\pi}{2} \implies \varphi = (2n+1)\pi$, con $n = 0, 1, 2, ...$

### Ondas Estacionarias

Se producen por la superposición de dos ondas armónicas idénticas que se propagan en **sentidos contrarios**, típicamente por la reflexión de una onda en un extremo.

-   $y_1 = A \cdot sen(k \cdot x - w \cdot t)$ (Incidente)
-   $y_2 = A \cdot sen(k \cdot x + w \cdot t)$ (Reflejada)

La suma $y = y_1 + y_2$ da como resultado:

-   $y(x,t) = \left[ 2 \cdot A \cdot sen(k \cdot x) \right] \cdot cos(w \cdot t)$

Interpretación: Cada punto *x* oscila con una frecuencia $\omega$ y una amplitud $A(x) = 2 \cdot A \cdot sen(k \cdot x)$ que depende de su posición.
-   **Nodos:** Puntos que no oscilan ($A(x)=0$). Ocurren cuando $sen(kx) = 0$.
-   **Antinodos:** Puntos que oscilan con máxima amplitud ($A(x)=2A$). Ocurren cuando $sen(kx) = \pm 1$.

Para una cuerda de longitud L fija en ambos extremos, las condiciones de borde imponen que solo ciertas longitudes de onda (y frecuencias) son posibles (modos normales):

-   $\lambda_n = \frac{2 \cdot L}{n}$ (Longitudes de onda permitidas)
-   $f_n = \frac{v}{\lambda_n} = n \cdot \left(\frac{v}{2L}\right) = n \cdot f_1$ (Frecuencias permitidas o armónicos)
    -   $f_1 = \frac{v}{2L} = \frac{1}{2L}\sqrt{\frac{T}{\mu}}$ es la **frecuencia fundamental**.

## Otros Fenómenos Ondulatorios

### Reflexión y Transmisión

Cuando una onda encuentra una frontera entre dos medios, parte se refleja y parte se transmite.
-   **Reflexión en un extremo fijo:** El pulso reflejado se **invierte** (sufre un desfase de $\pi$ rad).
-   **Reflexión en un extremo libre:** El pulso reflejado **no se invierte**.

### Pulsaciones (Batidos)

Es una interferencia en el **tiempo**. Ocurre al superponer dos ondas de frecuencias ligeramente diferentes ($f_1 \approx f_2$). La onda resultante tiene una amplitud que varía periódicamente.

-   **Frecuencia de la pulsación (beat):** Es la frecuencia con la que se oye la variación de intensidad.
    $$ f_{pulso} = |f_1 - f_2| $$

### Efecto Doppler

Es el cambio aparente en la frecuencia de una onda debido al movimiento relativo entre la fuente y el observador.

La fórmula general para la frecuencia percibida por el observador ($f_o$) es:
$$ f_o = f_f \left( \frac{v \pm v_o}{v \mp v_f} \right) $$
Donde:
-   $f_f$: Frecuencia emitida por la fuente.
-   $v$: Velocidad de la onda en el medio.
-   $v_o$: Velocidad del observador.
-   $v_f$: Velocidad de la fuente.

**Regla de los signos:**
-   Usar el signo de **arriba** en el numerador ($+v_o$) y denominador ($-v_f$) para **ACERCAMIENTO**.
-   Usar el signo de **abajo** en el numerador ($-v_o$) y denominador ($+v_f$) para **ALEJAMIENTO**.

---

## Ondas Sonoras

El sonido es el ejemplo más importante de una **onda mecánica longitudinal**. Se propaga a través de un medio material (sólido, líquido o gas) mediante la compresión y rarefacción de las partículas de dicho medio.

### Ondas de Desplazamiento y de Presión

Una onda sonora se puede describir de dos maneras complementarias:

1.  **Onda de Desplazamiento:** Describe el desplazamiento de las partículas del medio respecto a su posición de equilibrio.
    $$ s(x,t) = s_{max} \cdot cos(k \cdot x - \omega \cdot t) $$
    Donde $s_{max}$ es la amplitud máxima de desplazamiento.

2.  **Onda de Presión:** Describe la variación de la presión en el medio respecto a la presión de equilibrio. La compresión de las partículas causa un aumento de presión, y la rarefacción una disminución.
    $$ \Delta P(x,t) = \Delta P_{max} \cdot sen(k \cdot x - \omega \cdot t) $$
    Donde $\Delta P_{max}$ es la amplitud máxima de presión, relacionada con la amplitud de desplazamiento por: $\Delta P_{max} = \rho \cdot v \cdot \omega \cdot s_{max}$.

**Nota clave:** La onda de presión está **desfasada 90° ($\pi/2$)** respecto a la onda de desplazamiento. La máxima presión (compresión) ocurre donde el desplazamiento de las partículas es cero.

### Velocidad del Sonido

La velocidad del sonido depende de las propiedades elásticas e inerciales del medio.

-   **En Gases:** Depende de la temperatura (T), la masa molar (M) y la naturaleza del gas ($\gamma$, coeficiente adiabático).
    -   $v = \sqrt{\frac{\gamma \cdot R \cdot T}{M}}$ (donde R es la constante de los gases ideales).

-   **En Líquidos:** Depende del módulo de compresibilidad (B) y la densidad ($\rho$).
    -   $v = \sqrt{\frac{B}{\rho}}$

-   **En Sólidos (varillas):** Depende del módulo de Young (E) y la densidad ($\rho$).
    -   $v = \sqrt{\frac{E}{\rho}}$

### Intensidad y Nivel de Sonido (Decibeles)

La energía que transporta una onda sonora se mide con la **Intensidad (I)**, que es la potencia por unidad de área.

$$ I = \frac{Potencia}{Área} = \frac{1}{2} \rho v (\omega s_{max})^2 = \frac{\Delta P_{max}^2}{2 \rho v} $$

Debido al amplio rango del oído humano, se usa una escala logarítmica para medir el **Nivel de Intensidad Sonora ($\beta$)** en decibeles (dB).

$$ \beta (dB) = 10 \cdot \log_{10}\left(\frac{I}{I_0}\right) $$

Donde $I_0 = 10^{-12} \text{ W/m}^2$ es el umbral de audición humano.

### Ondas de Choque

Cuando una fuente de sonido se mueve a una velocidad mayor que la velocidad del sonido en el medio ($v_f > v_{sonido}$), se forma una **onda de choque**. Es una acumulación de frentes de onda en una superficie cónica, lo que produce un aumento abrupto de la presión (estampido sónico).

---

## Ondas Electromagnéticas (Luz)

A diferencia de las ondas mecánicas, las ondas electromagnéticas **no requieren un medio material** para propagarse. Consisten en campos eléctricos ($\vec{E}$) y magnéticos ($\vec{B}$) oscilantes y perpendiculares entre sí, y a su vez, perpendiculares a la dirección de propagación. Por lo tanto, son **ondas transversales**.

### Velocidad y Espectro Electromagnético

-   **Velocidad en el vacío:** Todas las ondas electromagnéticas viajan a la velocidad de la luz, $c \approx 3 \times 10^8 \text{ m/s}$.
-   **Velocidad en un medio:** La velocidad disminuye según el índice de refracción (n) del medio: $v = \frac{c}{n}$.

El **espectro electromagnético** clasifica estas ondas según su frecuencia (f) o longitud de onda ($\lambda$), ya que $c = \lambda \cdot f$. De menor a mayor frecuencia (y energía):

Ondas de radio → Microondas → Infrarrojo → **Luz Visible** → Ultravioleta → Rayos X → Rayos Gamma

### Energía e Intensidad (Vector de Poynting)

La energía de una onda electromagnética es transportada por los campos E y B. El flujo de energía por unidad de área y tiempo se describe mediante el **Vector de Poynting ($\vec{S}$)**:

$$ \vec{S} = \frac{1}{\mu_0} (\vec{E} \times \vec{B}) $$

La magnitud de $\vec{S}$ es la potencia por unidad de área, y su dirección es la de propagación de la onda. La **intensidad (I)** de la onda es el valor promedio del módulo de $\vec{S}$:

$$ I = S_{prom} = \frac{E_{max} B_{max}}{2\mu_0} = \frac{E_{max}^2}{2\mu_0 c} $$

Desde una perspectiva cuántica, la energía de la luz está cuantizada en paquetes llamados **fotones**. La energía de un fotón es directamente proporcional a su frecuencia:

$$ E = h \cdot f = \frac{h \cdot c}{\lambda} $$
Donde $h$ es la constante de Planck $ 6.626 \times 10^{-34} \text { J s} $

### Comparación: Ondas Sonoras vs. Ondas Electromagnéticas

| Característica         | Ondas Sonoras                                   | Ondas Electromagnéticas (Luz)                     |
| ---------------------- | ----------------------------------------------- | ------------------------------------------------- |
| **Naturaleza**         | Mecánica, Longitudinal                          | Electromagnética, Transversal                     |
| **Medio de propagación** | Necesita un medio material (sólido, líq., gas)  | No necesita medio, puede viajar en el vacío       |
| **Velocidad**          | Depende del medio (ej. ~343 m/s en aire)        | Constante en el vacío ($c \approx 3 \times 10^8$ m/s) |
| **Fenómeno físico**    | Compresión y rarefacción de partículas          | Oscilación de campos eléctricos y magnéticos      |
| **Polarización**       | No es posible (por ser longitudinal)            | Es posible (por ser transversal)                  |

---

---

## Interferencia y Difracción de la Luz

Estos fenómenos son la evidencia más fuerte del comportamiento ondulatorio de la luz y son una consecuencia directa del principio de superposición.

### Interferencia por Doble Rendija (Experimento de Young)

Este experimento demuestra que la luz puede interferir consigo misma. Cuando una onda de luz monocromática (una sola longitud de onda, $\lambda$) pasa a través de dos rendijas muy estrechas y cercanas, las rendijas actúan como dos fuentes de ondas coherentes. Estas ondas se superponen y crean un patrón de franjas brillantes y oscuras en una pantalla lejana.

La condición para que ocurra interferencia constructiva o destructiva en un punto P de la pantalla depende de la **diferencia de camino** ($\delta$) recorrido por las ondas desde cada rendija hasta P.

Si *d* es la distancia entre las rendijas y $\theta$ es el ángulo al punto P:
-   **Diferencia de camino:** $\delta = d \cdot sen(\theta)$

Las condiciones son:
-   **Interferencia Constructiva (Franjas Brillantes / Máximos):** La diferencia de camino es un múltiplo entero de la longitud de onda.
    $$ d \cdot sen(\theta) = m \cdot \lambda \quad (m = 0, \pm 1, \pm 2, ...) $$
-   **Interferencia Destructiva (Franjas Oscuras / Mínimos):** La diferencia de camino es un múltiplo semientero de la longitud de onda.
    $$ d \cdot sen(\theta) = \left(m + \frac{1}{2}\right) \cdot \lambda \quad (m = 0, \pm 1, \pm 2, ...) $$
Donde *m* se conoce como el **orden** de la franja.

![alt text](img\DobleRendija.png)

### Difracción por una Sola Rendija

Cuando una onda pasa a través de una abertura o rodea un obstáculo, se extiende o "dobla". Este fenómeno se llama difracción. Es, en esencia, la interferencia de las infinitas ondas puntuales (principio de Huygens) que atraviesan la abertura.

Para una sola rendija de ancho *a*, se observa un patrón con un máximo central muy brillante y ancho, flanqueado por máximos secundarios mucho más débiles y mínimos de intensidad cero.

-   **Condición para los Mínimos de Intensidad (Franjas Oscuras):**
    $$ a \cdot sen(\theta) = m \cdot \lambda \quad (m = \pm 1, \pm 2, \pm 3, ...) $$
    **Nota importante:** La fórmula es similar a la de los máximos en la doble rendija, pero aquí describe los **mínimos**. El valor $m=0$ se excluye porque corresponde al máximo central.

El resultado (constructivo o destructivo) depende de dos factores:
1.  **La diferencia de camino óptico:** La onda que se refleja en la superficie inferior viaja una distancia extra. Si el espesor de la película es *e* y su índice de refracción es *n*, la diferencia de camino es aproximadamente $2ne$.
2.  **El desfase por reflexión:** Ocurre un desfase de media longitud de onda ($\pi$ radianes) si la luz se refleja en la interfaz con un medio de **mayor** índice de refracción.

![alt text](img\RendijaSimple.png)

#### Casos comunes:

**Caso 1: Un solo desfase de $\pi$ en la reflexión**
(Ej: una película de aceite ($n_{aceite} > n_{aire}$) sobre agua ($n_{aceite} > n_{agua}$)). La reflexión aire-aceite sufre un desfase, pero la reflexión aceite-agua no.

-   **Interferencia Constructiva (Máximo reflejo):**
    $$ 2ne = \left(m + \frac{1}{2}\right)\lambda $$
-   **Interferencia Destructiva (Mínimo reflejo / Antirreflectante):**
    $$ 2ne = m\lambda $$

**Caso 2: Cero o dos desfases de $\pi$ en la reflexión**
(Ej: una película antirreflectante ($n_{película}$) sobre un lente ($n_{lente}$), con $n_{aire} < n_{película} < n_{lente}$). Ambas reflexiones (aire-película y película-lente) ocurren hacia un medio más denso, causando dos desfases que efectivamente se cancelan entre sí.

-   **Interferencia Constructiva (Máximo reflejo):**
    $$ 2ne = m\lambda $$
-   **Interferencia Destructiva (Mínimo reflejo):**
    $$ 2ne = \left(m + \frac{1}{2}\right)\lambda $$

En ambas situaciones, $m=0, 1, 2, ...$ y $\lambda$ es la longitud de onda en el vacío.

### Interferencia en Películas Delgadas

Este fenómeno es responsable de los colores iridiscentes que se ven en las burbujas de jabón, las manchas de aceite sobre el agua o los recubrimientos antirreflectantes de las lentes. Ocurre por la superposición de las ondas de luz reflejadas en las superficies superior e inferior de una película delgada.

Para analizar la interferencia, debemos considerar **dos factores clave**:

1.  **La diferencia de camino óptico:** La onda que se refleja en la superficie inferior viaja una distancia extra. Si el espesor de la película es *t* y su índice de refracción es *n*, esta diferencia de camino es **2nt**.
2.  **Los cambios de fase por reflexión:** Este es el factor más importante y modifica las condiciones de interferencia.

> **Regla del Cambio de Fase por Reflexión:**
> - Cuando una onda de luz que viaja por un medio se refleja en la frontera con un medio de índice de refracción **MAYOR** (pasa de `n_menor` a `n_mayor`), sufre un **cambio de fase de 180° (π radianes)**. Esto equivale a "invertir" la onda, o añadir media longitud de onda ($\lambda/2$) a su recorrido.
> - Si se refleja en la frontera con un medio de índice de refracción **MENOR** (pasa de `n_mayor` a `n_menor`), **NO hay cambio de fase**.

Analicemos los dos escenarios posibles basados en esta regla.

#### Escenario A: Un solo cambio de fase de 180°

Esto ocurre cuando solo una de las dos reflexiones (la superior o la inferior) invierte la fase.
*   **Ejemplo típico:** Una película de aceite (`n ≈ 1.5`) sobre agua (`n ≈ 1.33`), rodeada de aire (`n = 1`).
    -   Reflexión 1 (aire → aceite): Ocurre de `n_menor` a `n_mayor`. **Hay un desfase de 180°**.
    -   Reflexión 2 (aceite → agua): Ocurre de `n_mayor` a `n_menor`. **No hay desfase**.

Como el desfase de 180° equivale a sumar $\lambda/2$ al camino, las condiciones de interferencia se invierten:

-   **Interferencia Constructiva (Máximo reflejo):** La diferencia de camino `2nt` debe compensar el desfase para que las ondas estén en fase.
    $$ 2nt = \left(m + \frac{1}{2}\right)\lambda $$
-   **Interferencia Destructiva (Mínimo reflejo / Antirreflectante):** La diferencia de camino `2nt` debe ser un múltiplo entero para que, sumado al desfase, las ondas estén en oposición.
    $$ 2nt = m\lambda $$

#### Escenario B: Cero o dos cambios de fase de 180°

Esto ocurre cuando ninguna de las reflexiones invierte la fase, o cuando ambas lo hacen (los dos desfases de 180° se cancelan entre sí).
*   **Ejemplo típico:** Una capa antirreflectante de MgF₂ (`n ≈ 1.38`) sobre un lente de vidrio (`n ≈ 1.52`), rodeada de aire (`n=1`).
    -   Reflexión 1 (aire → MgF₂): Ocurre de `n_menor` a `n_mayor`. **Hay un desfase de 180°**.
    -   Reflexión 2 (MgF₂ → vidrio): También ocurre de `n_menor` a `n_mayor`. **Hay otro desfase de 180°**.

Como los dos desfases se anulan, el resultado depende únicamente de la diferencia de camino óptico `2nt`.

-   **Interferencia Constructiva (Máximo reflejo):**
    $$ 2nt = m\lambda $$
-   **Interferencia Destructiva (Mínimo reflejo):**
    $$ 2nt = \left(m + \frac{1}{2}\right)\lambda $$

En todas las fórmulas, $m = 0, 1, 2, ...$ y $\lambda$ es la longitud de onda de la luz en el vacío.

![alt text](img\PeliculasDelgadas.png)

---

### Red de Difracción

Una red de difracción es un componente óptico que consiste en un gran número de rendijas o ranuras paralelas, equidistantes y muy juntas (típicamente cientos o miles por milímetro). Funciona como una generalización del experimento de la doble rendija, pero la interferencia de un número masivo de fuentes coherentes produce un patrón mucho más nítido y definido.

Cuando una onda de luz monocromática incide sobre la red, cada rendija actúa como una fuente de ondas. La superposición de todas estas ondas produce un patrón de interferencia con **máximos principales** extremadamente brillantes y agudos, separados por regiones amplias de oscuridad casi total.

#### Condición para los Máximos Principales

La condición para que ocurra una interferencia constructiva (máximos principales o líneas brillantes) es idéntica a la del experimento de la doble rendija. La diferencia es que, para una red, estos máximos son mucho más intensos y estrechos.

$$ d \cdot sen(\theta) = m \cdot \lambda \quad (m = 0, \pm 1, \pm 2, ...) $$

Donde:
-   **d**: Es la **distancia entre rendijas adyacentes**. Si la red se describe por su número de líneas por unidad de longitud (N), entonces $d = 1/N$. Por ejemplo, para una red de 500 líneas/mm, $d = 1 / (500 \text{ líneas/mm}) = 2 \times 10^{-6} \text{ m}$.
-   **θ**: Es el ángulo de difracción en el que se observa el máximo.
-   **m**: Es el **orden del máximo** o del espectro.
-   **λ**: Es la longitud de onda de la luz.

#### Características del Patrón de una Red de Difracción

1.  **Máximo Central (m=0):** Corresponde a $\theta=0$. Todas las longitudes de onda pasan sin desviarse, creando una línea central brillante. Si la luz es blanca, esta línea es blanca.
2.  **Máximos de Órdenes Superiores (m = ±1, ±2, ...):** Para órdenes distintos de cero, el ángulo $\theta$ **depende de la longitud de onda ($\lambda$)**. Esto significa que la luz de diferentes colores se difracta en diferentes ángulos.
    -   La luz violeta (menor $\lambda$) se desvía menos.
    -   La luz roja (mayor $\lambda$) se desvía más.
    Este efecto convierte a la red en una herramienta poderosa para separar la luz en sus colores componentes, un fenómeno llamado **dispersión**.

3.  **Aplicación: Espectroscopía:** La capacidad de la red para separar longitudes de onda con alta precisión la convierte en el componente clave de los **espectrómetros**. Estos dispositivos se utilizan para analizar la composición de la luz emitida o absorbida por una sustancia, lo que permite, por ejemplo, determinar la composición química de las estrellas.

#### Comparación de Patrones de Interferencia/Difracción

| Dispositivo                 | Fórmula para MÁXIMOS (Franjas Brillantes)                  | Fórmula para MÍNIMOS (Franjas Oscuras)                             | Apariencia del Patrón                                                                  |
| --------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| **Doble Rendija (Young)**   | $d \cdot sen(\theta) = m \lambda$                          | $d \cdot sen(\theta) = (m + \frac{1}{2})\lambda$                    | Franjas brillantes y oscuras, anchas y de intensidad gradualmente decreciente.         |
| **Una Sola Rendija**        | Máximo central ancho. Los otros no tienen fórmula simple.  | $a \cdot sen(\theta) = m \lambda$  ($m \neq 0$)                     | Un máximo central muy brillante y el doble de ancho que los secundarios, mucho más tenues. |
| **Red de Difracción**       | $d \cdot sen(\theta) = m \lambda$                          | Regiones amplias de oscuridad casi total entre los máximos.        | Líneas muy finas, nítidas y brillantes (máximos) separadas por zonas oscuras.         |

**Nota:** Es crucial no confundir la fórmula de los **mínimos** de la rendija simple ($a \cdot sen(\theta) = m\lambda$) con la de los **máximos** de la doble rendija y la red ($d \cdot sen(\theta) = m\lambda$). Aunque la forma es idéntica, describen fenómenos opuestos y las variables *a* (ancho de rendija) y *d* (distancia entre rendijas) son diferentes.

---

### Principio de Huygens

Antes de analizar la difracción en detalle, es útil introducir el **Principio de Huygens**, que proporciona un modelo conceptual para entender cómo se propagan las ondas.

El principio establece que:
> **Todo punto de un frente de onda puede considerarse como la fuente de nuevas ondas esféricas secundarias (llamadas "wavelets" o frentes de onda secundarios) que se propagan en la misma dirección que la onda original.**

El nuevo frente de onda, en un instante posterior, es la superficie tangente a todas estas ondas secundarias.

Este principio explica de forma intuitiva:
-   **Propagación rectilínea:** En un medio homogéneo, la envolvente de las "wavelets" forma un nuevo frente de onda plano.
-   **Reflexión y Refracción:** Explica cómo los frentes de onda cambian de dirección al encontrar una interfaz.
-   **Difracción:** Explica por qué las ondas se "doblan" al pasar por una abertura. Las "wavelets" generadas en la abertura se propagan en todas direcciones hacia adelante, permitiendo que la onda alcance la región de "sombra" geométrica.

---
*(Esta sección expande y reemplaza la sección "Difracción por una Sola Rendija" existente para mayor detalle)*

### Difracción por una Sola Rendija y sus Consecuencias

Cuando una onda plana atraviesa una rendija de ancho *a*, cada punto dentro de la rendija actúa como una fuente de ondas secundarias (según el Principio de Huygens). La interferencia de estas infinitas fuentes produce un patrón de difracción característico en una pantalla lejana.

El patrón consiste en un **máximo central muy ancho y brillante**, flanqueado por una serie de máximos secundarios, mucho más tenues y estrechos, separados por mínimos de intensidad cero.

-   **Condición para los Mínimos de Intensidad (Franjas Oscuras):**
    El análisis muestra que la interferencia es completamente destructiva en ciertos ángulos. Esto ocurre cuando la rendija puede dividirse en pares de fuentes que se anulan mutuamente. La condición es:
    $$ a \cdot sen(\theta) = m \cdot \lambda \quad (m = \pm 1, \pm 2, \pm 3, ...) $$
    -   **Nota clave:** La fórmula es similar a la de los *máximos* en la doble rendija, pero aquí describe los **mínimos**. El valor $m=0$ se excluye porque corresponde al máximo central, no a un mínimo.

-   **El Máximo Central:**
    Se extiende entre los dos primeros mínimos ($m=1$ y $m=-1$). Su ancho angular es aproximadamente $2\theta_1$, donde $\theta_1$ es el ángulo del primer mínimo ($sen(\theta_1) = \lambda/a$). Esto significa que **cuanto más estrecha es la rendija (*a*), más se ensancha el patrón de difracción**.

#### Consecuencia: Límite de Resolución (Criterio de Rayleigh)

La difracción impone un límite fundamental a la capacidad de cualquier instrumento óptico (como un telescopio, un microscopio o incluso el ojo humano) para distinguir entre dos objetos muy cercanos. Cuando la luz de dos fuentes puntuales pasa a través de una abertura (por ejemplo, la lente de un telescopio), cada una produce su propio patrón de difracción. Si las fuentes están demasiado juntas, sus patrones se superponen tanto que se ven como una sola fuente.

El **Criterio de Rayleigh** establece la condición mínima para poder resolver dos fuentes:
> Dos imágenes son apenas resolubles cuando el centro del máximo central de una imagen coincide con el primer mínimo de la otra.

Para una **abertura circular** de diámetro *D* (como una lente), el ángulo mínimo de resolución ($\theta_{min}$) en radianes es:

$$ \theta_{min} = 1.22 \frac{\lambda}{D} $$

-   **Implicaciones:** Para mejorar la resolución (hacer $\theta_{min}$ más pequeño), se necesita un diámetro de apertura *D* más grande (por eso los telescopios son tan grandes) o usar una longitud de onda $\lambda$ más corta (por eso los microscopios electrónicos, que usan electrones con longitudes de onda muy cortas, tienen mayor resolución que los ópticos).

---

## Polarización de la Luz

La polarización es una propiedad de las ondas transversales que describe la orientación de las oscilaciones de la onda. En una onda electromagnética, se refiere a la dirección en la que oscila el vector del campo eléctrico ($\vec{E}$).

-   **Luz no polarizada:** La luz de fuentes comunes (el Sol, una bombilla) es no polarizada. El vector $\vec{E}$ oscila rápidamente en todas las direcciones perpendiculares a la dirección de propagación.
-   **Luz polarizada linealmente:** El vector $\vec{E}$ oscila a lo largo de una única dirección fija.

Existen varios métodos para polarizar la luz, pero los más comunes son mediante filtros polarizadores y por reflexión.

### Ley de Malus

Un filtro polarizador (como el de las gafas de sol polarizadas) tiene un "eje de transmisión" que solo permite pasar el componente del campo eléctrico paralelo a dicho eje.

La **Ley de Malus** describe qué ocurre cuando una luz ya polarizada incide sobre un segundo polarizador (llamado "analizador"). La intensidad de la luz transmitida ($I$) viene dada por:

$$ I = I_0 \cdot \cos^2(\theta) $$

Donde:
-   $I_0$: Es la intensidad de la luz polarizada que incide sobre el analizador.
-   $\theta$: Es el ángulo entre el eje de polarización de la luz incidente y el eje de transmisión del analizador.

**Casos importantes:**
-   Si los ejes son paralelos ($\theta = 0^\circ$), $\cos^2(0) = 1$, y toda la luz pasa ($I=I_0$).
-   Si los ejes son perpendiculares ($\theta = 90^\circ$, polarizadores "cruzados"), $\cos^2(90) = 0$, y no pasa nada de luz ($I=0$).
-   **Importante:** Si la luz incidente sobre el **primer** polarizador es **no polarizada**, la intensidad que sale de él es siempre la mitad de la original: $I_1 = \frac{1}{2} I_{no-polarizada}$.

### Polarización por Reflexión y Ley de Brewster

Cuando la luz no polarizada se refleja en la superficie de un material dieléctrico (como el vidrio o el agua), la luz reflejada está, en general, parcialmente polarizada.

Existe un ángulo de incidencia específico, llamado **ángulo de Brewster ($\theta_B$)**, para el cual la luz reflejada está **100% polarizada linealmente**. La dirección de polarización es paralela a la superficie (horizontal si la superficie es horizontal).

Esto ocurre cuando el rayo reflejado y el rayo refractado son perpendiculares entre sí ($90^\circ$).

La **Ley de Brewster** relaciona este ángulo con los índices de refracción del primer medio ($n_1$) y del segundo medio ($n_2$):

$$ \tan(\theta_B) = \frac{n_2}{n_1} $$

Esta es la razón por la que las gafas de sol polarizadas son tan efectivas para reducir el deslumbramiento (el "glare"). El deslumbramiento es principalmente luz reflejada en superficies horizontales (carreteras, agua), que está polarizada horizontalmente. Las gafas tienen un eje de transmisión vertical, bloqueando esta luz reflejada según la Ley de Malus ($\theta = 90^\circ$).

---

## Transferencia de Calor y Termodinámica

La termodinámica estudia la energía y sus transformaciones, mientras que la transferencia de calor es la ciencia que se ocupa de la **tasa** a la que se intercambia energía térmica entre sistemas debido a una diferencia de temperatura.

### Conceptos Fundamentales

Para entender la transferencia de calor, es crucial diferenciar entre energía interna, temperatura y calor, conceptos regidos por las leyes de la termodinámica.

1.  **Energía Interna (U):** Es la suma de todas las energías microscópicas de las partículas que componen un sistema (energía cinética de traslación, rotación y vibración, y energía potencial de los enlaces). **Es una propiedad del sistema, una función de estado.** Un sistema "tiene" energía interna.

2.  **Temperatura (T):** Es una medida macroscópica de la energía cinética promedio de las partículas de un sistema. La temperatura es la propiedad que determina la dirección del flujo de calor. Dos sistemas en equilibrio térmico tienen la misma temperatura (**Ley Cero de la Termodinámica**).

3.  **Calor (Q):** Se define como la **energía en tránsito** de un sistema a otro (o entre un sistema y su entorno) debido exclusivamente a una diferencia de temperatura.
    -   El calor **no es algo que un cuerpo posee**, sino la energía que se transfiere.
    -   Junto con el trabajo (W), es una de las dos formas de cambiar la energía interna de un sistema cerrado (**Primera Ley de la Termodinámica**: $\Delta U = Q - W$).
    -   El calor fluye espontáneamente desde el cuerpo de mayor temperatura hacia el de menor temperatura, nunca en la dirección opuesta (**Segunda Ley de la Termodinámica**).

4.  **Estado Estacionario vs. Transitorio:**
    -   **Estado Estacionario:** Las temperaturas en cada punto del sistema no cambian con el tiempo. La tasa de transferencia de calor (H) es constante.
    -   **Estado Transitorio:** Las temperaturas en el sistema varían con el tiempo, mientras el sistema evoluciona hacia el equilibrio térmico.

### Mecanismos de Transferencia de Calor

La energía térmica se transfiere a través de tres mecanismos distintos:

#### 1. Conducción

Es la transferencia de calor por contacto directo a nivel molecular, sin transporte de materia. La energía se propaga por colisiones entre partículas adyacentes. Es el mecanismo dominante en los sólidos.

La tasa de transferencia de calor (potencia térmica o corriente de calor, H) se rige por la **Ley de Fourier**:

$$ H = \frac{dQ}{dt} = -k \cdot A \cdot \frac{dT}{dx} $$

-   **k**: **Conductividad térmica** del material (W/m·K), una propiedad que indica su capacidad para conducir calor.
-   **A**: Área de la sección transversal al flujo.
-   **dT/dx**: **Gradiente de temperatura**. El signo negativo indica que el calor fluye en la dirección en que la temperatura disminuye.

Para una placa de espesor **L** con caras a temperaturas $T_{caliente}$ y $T_{fría}$, la ley se simplifica a:

$$ H = k \cdot A \cdot \frac{T_{caliente} - T_{fría}}{L} $$

#### 2. Convección

Es la transferencia de calor mediante el movimiento macroscópico de un **fluido** (líquido o gas). El fluido transporta la energía interna de un punto a otro.
-   **Convección Natural:** El movimiento del fluido se debe a diferencias de densidad causadas por la temperatura (ej. aire caliente que asciende).
-   **Convección Forzada:** El movimiento es impulsado por un agente externo (ej. un ventilador).

Se modela empíricamente con la **Ley de Enfriamiento de Newton**:

$$ H = h \cdot A \cdot (T_{superficie} - T_{fluido}) $$

-   **h**: **Coeficiente de convección**. No es una propiedad del material, sino que depende de la geometría, la velocidad del fluido y sus propiedades térmicas.

#### 3. Radiación

Es la transferencia de calor mediante **ondas electromagnéticas** (principalmente infrarrojas). No requiere un medio material y puede ocurrir en el vacío. Es el mecanismo por el cual el Sol calienta la Tierra.

La potencia radiada por una superficie se describe por la **Ley de Stefan-Boltzmann**:

$$ P_{emitida} = \epsilon \cdot \sigma \cdot A \cdot T^4 $$

-   **ε**: **Emisividad** de la superficie (0 ≤ ε ≤ 1), indica su eficiencia como emisor de radiación. Un cuerpo negro ideal tiene ε=1.
-   **σ**: Constante de Stefan-Boltzmann ($5.67 \times 10^{-8} \text{ W/m}^2\text{K}^4$).
-   **T**: Temperatura **absoluta** de la superficie (en Kelvin).

La **tasa neta** de transferencia de calor por radiación entre un objeto y su entorno es:

$$ H_{neta} = P_{neta} = \epsilon \cdot \sigma \cdot A \cdot (T_{objeto}^4 - T_{entorno}^4) $$

### Analogía con Circuitos Eléctricos y Resistencia Térmica

El análisis de la conducción en estado estacionario se simplifica enormemente usando una analogía con la Ley de Ohm para circuitos eléctricos.

| Magnitud Eléctrica               | Magnitud Térmica                               |
| -------------------------------- | ---------------------------------------------- |
| **Corriente (I)** = d(carga)/dt   | **Corriente de Calor (H)** = d(energía)/dt   |
| **Diferencia de Potencial (ΔV)** | **Diferencia de Temperatura (ΔT)**             |
| **Resistencia Eléctrica (R)**    | **Resistencia Térmica (R<sub>th</sub>)**       |

La ecuación fundamental del flujo de calor se escribe como:

$$ H = \frac{\Delta T}{R_{th}} $$

Cada capa de material se modela como una resistencia térmica. Para la conducción, esta resistencia es:

$$ R_{th} = \frac{L}{k \cdot A} $$

#### Combinación de Resistencias Térmicas

-   **En Serie (Paredes compuestas):** El calor atraviesa secuencialmente varias capas. El flujo de calor **H es el mismo** en todas. La resistencia total es la suma de las individuales.
    $$ R_{total} = R_1 + R_2 + ... + R_n $$
    $$ H = \frac{\Delta T_{total}}{R_{total}} $$

-   **En Paralelo:** El calor fluye simultáneamente por diferentes caminos. La diferencia de temperatura **ΔT es la misma** para todos. El flujo de calor total **H es la suma** de los flujos.
    $$ \frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + ... + \frac{1}{R_n} $$
    $$ H_{total} = H_1 + H_2 + ... $$

Este modelo permite resolver problemas complejos de aislamiento térmico de forma intuitiva y sistemática.