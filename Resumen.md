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