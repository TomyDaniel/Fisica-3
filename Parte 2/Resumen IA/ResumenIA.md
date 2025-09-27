### **1. Relatividad Especial**

La Teoría de la Relatividad Especial, propuesta por Albert Einstein en 1905, surge como una solución a las contradicciones entre la mecánica de Newton y la teoría electromagnética de Maxwell. Su objetivo es describir el movimiento de los cuerpos en **sistemas de referencia inerciales** (aquellos que se mueven a velocidad constante uno respecto del otro).

#### **Postulados Fundamentales**

1.  **Principio de Relatividad**: "Las leyes de la física son las mismas en todos los sistemas de referencia inerciales". Esto implica que no existe un experimento que pueda determinar si un sistema está en "reposo absoluto" o en movimiento uniforme. Las leyes físicas son **invariantes**.
2.  **Principio de la Constancia de la Velocidad de la Luz**: "La velocidad de la luz en el vacío (*c*) es una constante universal, independiente del movimiento de la fuente o del observador". Este postulado rompe radicalmente con la intuición clásica.

#### **Transformaciones de Coordenadas: De Galileo a Lorentz**

*   **Transformación de Galileo (Física Clásica)**:
    *   `x' = x - Vt`
    *   `t' = t`
    *   **Explicación**: La física clásica asume un tiempo universal y absoluto (`t' = t`). Para saber la posición de un objeto en un sistema en movimiento (S'), simplemente se toma su posición en el sistema en reposo (S) y se le resta la distancia que el sistema S' ha recorrido (`Vt`). Esto funciona bien a bajas velocidades, pero es incompatible con el segundo postulado de la relatividad.

*   **Transformación de Lorentz**: Para que la velocidad de la luz sea constante para todos, el espacio y el tiempo deben estar interrelacionados.
    *   **Factor de Lorentz (γ)**: `γ = 1 / √(1 - v²/c²)`
        *   **Explicación**: Este es el factor de corrección relativista. Para velocidades bajas (`v << c`), `γ` es prácticamente 1, y las ecuaciones se parecen a las clásicas. Conforme la velocidad `v` se acerca a `c`, `γ` tiende a infinito.
    *   **Transformaciones de coordenadas**:
        *   `x' = γ(x - vt)`
        *   `t' = γ(t - vx/c²)`
    *   **Explicación**: Estas son las transformaciones correctas. La coordenada temporal `t'` ya no es igual a `t`, sino que depende también de la posición `x`. Esto significa que la simultaneidad es relativa: dos eventos que son simultáneos para un observador pueden no serlo para otro. El espacio y el tiempo forman una única entidad llamada **espacio-tiempo**.

#### **Consecuencias Fundamentales de la Relatividad**

*   **Dilatación del Tiempo**: `Δt' = γΔt`
    *   **Explicación**: Un intervalo de tiempo medido en un sistema en reposo (`Δt`, conocido como "tiempo propio") siempre es el intervalo más corto posible. Para cualquier otro observador que vea ese sistema en movimiento, el tiempo parecerá transcurrir más lentamente, midiendo un intervalo `Δt'` más largo. En resumen: "los relojes en movimiento se atrasan".

*   **Contracción de la Longitud**: `Δx' = Δx / γ`
    *   **Explicación**: La longitud de un objeto medida en su propio sistema de reposo (`Δx`, "longitud propia") es la máxima longitud posible. Para un observador que ve el objeto moverse, su longitud en la dirección del movimiento se medirá como más corta (`Δx'`).

#### **Dinámica Relativista: Masa, Energía y Momento**

*   **Energía Total (E)**: `E = γm₀c²`
    *   **Explicación**: Esta es la famosa ecuación de Einstein en su forma completa. La energía total de un objeto depende de su velocidad a través del factor `γ`.
*   **Energía en Reposo**: Si `v=0`, entonces `γ=1`, y la fórmula se reduce a `E₀ = m₀c²`. Esto revela que la masa es una forma de energía. Un objeto tiene una enorme cantidad de energía intrínseca simplemente por tener masa.
*   **Energía Cinética (Ec)**: `Ec = E - E₀ = (γ - 1)m₀c²`
    *   **Explicación**: La energía cinética ya no es `½mv²`. Es la diferencia entre la energía total del objeto en movimiento y su energía en reposo.
*   **Invariante Energía-Momento**: `E² - (pc)² = (m₀c²)²`
    *   **Explicación**: Mientras que la energía `E` y el momento `p` de una partícula dependen del observador, esta combinación `E² - (pc)²` es un **invariante relativista**. Su valor es el mismo en todos los sistemas inerciales y es una propiedad fundamental de la partícula, relacionada directamente con su masa en reposo `m₀`.

### **2. Mecánica Cuántica**

La mecánica cuántica es la teoría que describe la naturaleza a escalas atómicas y subatómicas. Su idea central es que propiedades físicas como la energía, el momento y el momento angular están **cuantizadas**, es decir, restringidas a valores discretos.

#### **Principios Fundamentales**

*   **Hipótesis de Planck (Cuantización)**: `E = hν`
    *   **Explicación**: Max Planck propuso que la energía no se emite ni se absorbe de forma continua, sino en "paquetes" discretos llamados **cuantos** o **fotones**. La energía `E` de un fotón es directamente proporcional a su frecuencia `ν`, donde `h` es la constante de Planck.
*   **Dualidad Onda-Partícula (De Broglie)**: `λ = h / p`
    *   **Explicación**: Louis de Broglie postuló que no solo la luz, sino toda la materia, presenta esta dualidad. Cualquier partícula con un momento lineal `p` tiene asociada una longitud de onda `λ`. Los electrones, por ejemplo, pueden difractarse como las ondas.

#### **Fenómenos Cuánticos Clave**

*   **Efecto Fotoeléctrico**: `E_ke = hν - φ`
    *   **Explicación**: Cuando un fotón de energía `hν` incide sobre un metal, puede arrancar un electrón. Para ello, debe superar la "función trabajo" (`φ`), que es la energía mínima que liga al electrón con el metal. La energía sobrante se convierte en la energía cinética (`E_ke`) del electrón. Esto demuestra la naturaleza de partícula de la luz: un único fotón interactúa con un único electrón.
*   **Efecto Compton**: `Δλ = λ' - λ₀ = (h / m₀c)(1 - cosφ)`
    *   **Explicación**: Este fenómeno describe la colisión entre un fotón y un electrón. El fotón cede parte de su energía al electrón y emerge con una longitud de onda mayor (`λ'`). El cambio en la longitud de onda (`Δλ`) depende del ángulo de dispersión `φ`, tratando al fotón como una partícula con momento, lo que refuerza la idea de la dualidad.
*   **Principio de Incertidumbre de Heisenberg**:
    *   `Δx · Δp ≥ ħ/2` (donde `ħ = h/2π`)
    *   **Explicación**: Este principio no se refiere a la calidad de los instrumentos de medida, sino que es una limitación fundamental de la naturaleza. Es imposible conocer simultáneamente y con precisión infinita la posición (`x`) y el momento (`p`) de una partícula. Cuanto más precisamente se determina una, más incierta se vuelve la otra.

#### **El Átomo de Bohr**

*   **Niveles de Energía**: `E_n = -13.6 eV / n²` (para el Hidrógeno)
    *   **Explicación**: Bohr aplicó las ideas cuánticas al átomo. Postuló que los electrones no pueden orbitar a cualquier distancia del núcleo, sino solo en **órbitas estacionarias** con niveles de energía discretos y cuantizados, definidos por el número cuántico principal `n`. El signo negativo indica que el electrón está ligado al núcleo.
*   **Transiciones Electrónicas**: Un electrón emite un fotón de energía `E = hν = E_i - E_f` cuando "cae" de un nivel de energía superior (`E_i`) a uno inferior (`E_f`), explicando los espectros de emisión atómicos.

### **3. Núcleo Atómico y Radioactividad**

Esta rama de la física se centra en el núcleo, compuesto por protones y neutrones (colectivamente llamados nucleones), unidos por la **fuerza nuclear fuerte**.

#### **Estructura y Estabilidad Nuclear**

*   **Energía de Enlace Nuclear (Binding Energy)**: `E_B = Δm c²`
    *   **Explicación**: La masa de un núcleo es siempre *menor* que la suma de las masas de los protones y neutrones que lo componen. Esta diferencia, llamada **defecto de masa (`Δm`)**, se convierte en la energía que mantiene unido al núcleo. Para separar el núcleo en sus componentes, se debe suministrar esta cantidad de energía `E_B`. Una reacción nuclear es espontánea si libera energía (`Q>0`), lo que ocurre cuando los productos son más estables (tienen mayor energía de enlace).

#### **Radioactividad: El Decaimiento de Núcleos Inestables**

La radioactividad es el proceso por el cual un núcleo inestable emite partículas para transformarse en uno más estable.

*   **Decaimiento Alfa (α)**: Emisión de un núcleo de Helio (`²⁴He`). Es una partícula masiva y con mucha carga, por lo que tiene un alto poder de ionización pero bajo poder de penetración (es detenida por una hoja de papel).
*   **Decaimiento Beta (β⁻)**: Un neutrón se convierte en un protón, emitiendo un electrón (`e⁻`) y un antineutrino. Los electrones emitidos tienen mayor poder de penetración que las partículas alfa, pero menor poder de ionización.
*   **Decaimiento Gamma (γ)**: Emisión de un fotón de muy alta energía. No cambia la composición del núcleo, solo lo lleva de un estado excitado a uno de menor energía. Los rayos gamma son muy penetrantes.

#### **Cinética de la Desintegración Radioactiva**

*   **Ley de Desintegración**: `N(t) = N₀ e^(-λt)`
    *   **Explicación**: La desintegración es un proceso probabilístico. No se puede saber cuándo decaerá un núcleo individual, pero para una población grande, el número de núcleos (`N`) que quedan sin decaer disminuye exponencialmente con el tiempo (`t`). `N₀` es el número inicial de núcleos y `λ` es la **constante de desintegración**, que representa la probabilidad de decaimiento por unidad de tiempo.
*   **Período de Semidesintegración o Vida Media (T½)**: `T½ = ln(2) / λ`
    *   **Explicación**: Es el tiempo que tarda la mitad de una muestra radiactiva en desintegrarse. Es una medida más intuitiva de la rapidez con la que decae un isótopo.
*   **Actividad (A)**: `A(t) = λN(t) = A₀ e^(-λt)`
    *   **Explicación**: La actividad es la tasa de desintegraciones por segundo, lo que se mide en la práctica (en unidades de Becquerel, Bq). La actividad también disminuye exponencialmente con el tiempo.