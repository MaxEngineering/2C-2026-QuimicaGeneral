# SERIE 1 — Resuelta paso a paso

**Química General — ECyT / UNSAM · 2C 2026**
**Tema:** Átomos, iones y configuración electrónica

> Estructura atómica · Cuantización de la energía · Orbitales atómicos · Números cuánticos · Estructura electrónica · Fenómenos de emisión y absorción atómica · Iones más estables para elementos representativos según CEE · Iones más estables para elementos de transición.

**Cómo usar este archivo:** cada ejercicio tiene el **procedimiento** desarrollado (para que veas de dónde sale cada número) y, cuando el enunciado pide justificar, un bloque **📝 Respuesta tipo parcial** con la redacción que conviene escribir en el examen.

**Datos que se usan en toda la serie:**

| Constante | Valor |
|---|---|
| h (Planck) | 6,63×10⁻³⁴ J·s |
| c (luz) | 3,0×10⁸ m/s |
| N_A (Avogadro) | 6,022×10²³ 1/mol |
| h·c | 1,989×10⁻²⁵ J·m |

---
---

# PROBLEMAS PARA DISCUTIR EN CLASE

---

## Ejercicio 1 — Átomos de carbono alineados

> Sabiendo que el diámetro de un átomo de carbono es de 1,54 Å, indicar cuántos átomos se deben alinear para alcanzar una distancia de 0,2 mm (ancho de un trazo de lápiz).

### Procedimiento

**Paso 1 — Pasar todo a la misma unidad (metros).**

$$0,2\ \text{mm} = 0,2\times10^{-3}\ \text{m} = 2\times10^{-4}\ \text{m}$$

$$1,54\ \text{Å} = 1,54\times10^{-10}\ \text{m} \qquad (1\ \text{Å} = 10^{-10}\ \text{m})$$

**Paso 2 — Dividir la distancia total por el diámetro de un átomo.**

$$n = \frac{d_{\text{total}}}{d_{\text{átomo}}} = \frac{2\times10^{-4}\ \text{m}}{1,54\times10^{-10}\ \text{m}}$$

$$n = 1,2987\times10^{6}$$

### ✅ Respuesta

$$\boxed{n \approx 1,3\times10^{6}\ \text{átomos de carbono}}$$

**Un millón trescientos mil átomos** para cubrir el ancho de un trazo de lápiz.

> 💡 **Chequeo de sentido común:** el resultado es adimensional (metros/metros), como corresponde a un "cuántos caben". Si te da con unidades, te equivocaste.

---

## Ejercicio 2 — Espectro de emisión del hidrógeno

> Se presenta una porción del espectro de emisión del hidrógeno obtenido al pasar la luz de una lámpara de descarga de hidrógeno a través de un prisma (líneas a 410, 434, 486 y 656 nm).

### a) ¿Qué información se obtiene con este experimento?

📝 **Respuesta tipo parcial**

> Se obtiene el **espectro de emisión atómico del hidrógeno**, que es un **espectro de líneas discretas** y no un espectro continuo. De él se extrae:
>
> 1. Que la energía de los electrones en el átomo está **CUANTIZADA**: si el electrón pudiera tener cualquier energía, emitiría todas las longitudes de onda y se vería un espectro continuo. Como sólo aparecen cuatro líneas, sólo existen ciertos **niveles de energía permitidos**, y por lo tanto sólo ciertas diferencias de energía posibles entre ellos.
> 2. Los **valores de esas diferencias de energía**: cada línea corresponde a una transición electrónica entre dos niveles, con ΔE = hν = hc/λ.
> 3. La **identidad del elemento**: el patrón de líneas es único para cada elemento (funciona como una "huella digital"), lo que permite identificar átomos desconocidos mediante análisis espectroscópico.

**Detalle de las líneas (serie de Balmer, todas terminan en n = 2):**

| λ | Color | Transición |
|---|---|---|
| 656 nm | Rojo | n = 3 → n = 2 |
| 486 nm | Verde-turquesa | n = 4 → n = 2 |
| 434 nm | Azul | n = 5 → n = 2 |
| 410 nm | Violeta | n = 6 → n = 2 |

---

### b) Energía por mol para las líneas roja (656 nm) y verde (486 nm)

### Procedimiento

**Paso 1 — Energía de UN fotón:**

$$E_{\text{fotón}} = h\nu = \frac{hc}{\lambda}$$

**Paso 2 — Energía de UN MOL de fotones** (multiplicar por Avogadro):

$$E_{\text{mol}} = \frac{hc}{\lambda}\cdot N_A$$

**Paso 3 — Pasar λ a metros:** 1 nm = 10⁻⁹ m

---

**🔴 Línea roja — λ = 656 nm = 6,56×10⁻⁷ m**

$$E_{\text{fotón}} = \frac{6,63\times10^{-34}\ \text{J·s}\;\times\;3,0\times10^{8}\ \text{m/s}}{6,56\times10^{-7}\ \text{m}} = \frac{1,989\times10^{-25}}{6,56\times10^{-7}} = 3,03\times10^{-19}\ \text{J}$$

$$E_{\text{mol}} = 3,03\times10^{-19}\ \text{J} \times 6,022\times10^{23}\ \tfrac{1}{\text{mol}} = 1,83\times10^{5}\ \text{J/mol}$$

$$\boxed{E_{656} \approx 182{,}5\ \text{kJ/mol}}$$

---

**🟢 Línea verde — λ = 486 nm = 4,86×10⁻⁷ m**

$$E_{\text{fotón}} = \frac{1,989\times10^{-25}}{4,86\times10^{-7}} = 4,09\times10^{-19}\ \text{J}$$

$$E_{\text{mol}} = 4,09\times10^{-19} \times 6,022\times10^{23} = 2,46\times10^{5}\ \text{J/mol}$$

$$\boxed{E_{486} \approx 246{,}5\ \text{kJ/mol}}$$

> *(La guía da 182,4 y 246,4 kJ/mol. La diferencia en la última cifra viene del redondeo de h y N_A — es irrelevante.)*

### ✅ ¿Cuál es la de mayor energía?

$$\boxed{\text{La línea VERDE (486 nm), con 246,5 kJ/mol}}$$

📝 **Respuesta tipo parcial**

> La transición de mayor energía es la de la **línea verde (486 nm)**. Como
> $$E = \frac{hc}{\lambda}$$
> la energía es **inversamente proporcional a la longitud de onda**: a **menor λ, mayor E**. Como 486 nm < 656 nm, la línea verde corresponde a un fotón más energético.
>
> Físicamente esto es coherente: la línea verde proviene de la transición n=4→2 y la roja de n=3→2. El salto desde n=4 es más grande, por lo que libera más energía.

---

### c) Comparación con la energía para cargar un celular (15 Wh)

### Procedimiento

**Paso 1 — Pasar 15 Wh a joules.**

El watt-hora es potencia × tiempo. Como 1 W = 1 J/s y 1 h = 3600 s:

$$15\ \text{Wh} = 15\ \text{W} \times 3600\ \text{s} = 54.000\ \text{J} = 54\ \text{kJ}$$

**Paso 2 — Comparar.**

| Magnitud | Energía |
|---|---|
| 1 fotón rojo (656 nm) | 3,03×10⁻¹⁹ J |
| 1 **mol** de fotones rojos | 182,5 kJ |
| 1 **mol** de fotones verdes | 246,5 kJ |
| **Cargar el celular** | **54 kJ** |

**Paso 3 — Cuántos moles de fotones harían falta.**

$$n = \frac{54\ \text{kJ}}{182,5\ \text{kJ/mol}} = 0,30\ \text{mol de fotones rojos}$$

$$n = \frac{54\ \text{kJ}}{246,5\ \text{kJ/mol}} = 0,22\ \text{mol de fotones verdes}$$

En número de fotones:

$$0,30\ \text{mol} \times 6,022\times10^{23} = 1,8\times10^{23}\ \text{fotones rojos}$$

### ✅ Respuesta

📝 **Respuesta tipo parcial**

> La energía de **un solo fotón** es de ~3×10⁻¹⁹ J, un valor **despreciable** frente a los 54.000 J que hacen falta para cargar el celular: se necesitarían del orden de **1,8×10²³ fotones** (≈ 0,3 mol).
>
> Sin embargo, la energía de **un mol** de esos mismos fotones (182,5 kJ) es del orden de **3,4 veces MAYOR** que la energía de la carga (54 kJ). Es decir: alcanzaría con **0,3 mol de fotones rojos** (o 0,22 mol de verdes) para cargarlo.
>
> **Conclusión:** las transiciones electrónicas individuales manejan energías minúsculas, pero como en cualquier muestra macroscópica hay del orden de 10²³ átomos, la energía total involucrada es perfectamente comparable a la de un proceso cotidiano.

---

## Ejercicio 3 — Transiciones electrónicas en el hidrógeno

> ¿Cuál de las siguientes transiciones produce la emisión de luz de **menor longitud de onda**? ¿Cuál corresponde a la de **menor energía**? Justifique.
> a) 6s → 2p  b) 5s → 2p  c) 4s → 2p  d) 3s → 2p

### Procedimiento

**Paso 1 — Reconocer la clave:** en el **átomo de hidrógeno** (un solo electrón) la energía depende **SÓLO de n**, no de ℓ. Por eso 6s, 5s, 4s y 3s se pueden tratar directamente como los niveles n = 6, 5, 4 y 3, y el 2p como n = 2.

**Paso 2 — Todas las transiciones terminan en el mismo nivel (n=2)**, así que el que manda es el nivel de partida:

$$\Delta E = E_{\text{inicial}} - E_{\text{final}}$$

Cuanto **más alto** el nivel de partida, **mayor** el ΔE liberado.

$$\Delta E_{6\to2} > \Delta E_{5\to2} > \Delta E_{4\to2} > \Delta E_{3\to2}$$

**Paso 3 — Traducir energía a longitud de onda:**

$$\lambda = \frac{hc}{\Delta E} \qquad \Longrightarrow \qquad \Delta E \uparrow \;\Rightarrow\; \lambda \downarrow$$

### ✅ Respuestas

| Pregunta | Opción |
|---|---|
| **Menor longitud de onda** | **a) 6s → 2p** |
| **Menor energía** | **d) 3s → 2p** |

📝 **Respuesta tipo parcial**

> Todas las transiciones terminan en el mismo nivel (n = 2), por lo que la energía emitida depende únicamente del nivel de partida.
>
> **a) 6s → 2p** es la de **menor longitud de onda**: parte del nivel más alto (n = 6), por lo que es el salto de **mayor ΔE**, y como λ = hc/ΔE, a mayor energía corresponde **menor λ**.
>
> **d) 3s → 2p** es la de **menor energía**: parte del nivel más bajo de los cuatro (n = 3), por lo que es el salto más chico y libera el fotón menos energético (el de mayor λ).
>
> *(En el átomo de hidrógeno la energía depende sólo del número cuántico principal n, no de ℓ; por eso alcanza con comparar 6 > 5 > 4 > 3.)*

> ⚠️ **La trampa del ejercicio:** "menor longitud de onda" y "menor energía" son **opuestos**. Si contestás lo mismo en las dos, seguro está mal una.

---

## Ejercicio 4 — Tachar lo que NO corresponde

### a) La mecánica cuántica (~~es~~ / **no es**) una herramienta apropiada para describir las propiedades de la materia a nivel atómico.

✅ **Queda: "ES"** → se tacha **"no es"**

> La mecánica cuántica **es** la herramienta apropiada. Es justamente el modelo que logra explicar los espectros de emisión, la estabilidad del átomo y la estructura electrónica, cosas que la física clásica no puede.

---

### b) Los electrones (**son** / ~~no son~~) considerados como partículas en el marco de la mecánica cuántica.

✅ **Queda: "NO SON"** → se tacha **"son"**

📝 **Respuesta tipo parcial**

> En el marco de la mecánica cuántica los electrones **NO son considerados simplemente como partículas**. Presentan un **comportamiento dual onda-partícula** (de Broglie, 1924): tienen masa y carga como una partícula, pero también exhiben fenómenos ondulatorios como la difracción, y se describen matemáticamente mediante una **función de onda Ψ**.
>
> Además, por el **principio de incertidumbre de Heisenberg** no es posible determinar simultáneamente su posición y su momento, de modo que no se les puede asignar una trayectoria definida como a una partícula clásica. Sólo se puede hablar de la **probabilidad** (Ψ²) de encontrarlos en cierta región del espacio.

---

### c) Un orbital (~~es~~ / **no es**) la trayectoria descripta por un electrón alrededor del núcleo de un átomo.

✅ **Queda: "NO ES"** → se tacha **"es"**

📝 **Respuesta tipo parcial**

> Un orbital **NO es** una trayectoria. La idea de trayectoria (órbita) pertenece al **modelo de Bohr**, que quedó descartado por el principio de incertidumbre de Heisenberg.
>
> Un **orbital** es la **región del espacio alrededor del núcleo donde existe una alta probabilidad (≈90%) de encontrar al electrón**. Matemáticamente es la función de onda Ψ del electrón, y su cuadrado Ψ² representa la densidad de probabilidad o densidad electrónica.

> ⚠️ **ÓRBITA ≠ ORBITAL.** Es el error conceptual más penalizado de toda la unidad.

---

## Ejercicio 5 — Identificar los orbitales de las imágenes

### Procedimiento

Reconocer la **forma** para identificar el subnivel (ℓ), y la **orientación respecto de los ejes** para identificar mℓ:

| Forma | Subnivel |
|---|---|
| Esfera | **s** (ℓ = 0) |
| 2 lóbulos sobre un eje | **p** (ℓ = 1) |
| 4 lóbulos (trébol) o 2 lóbulos + anillo | **d** (ℓ = 2) |

### ✅ Respuestas

| | Qué se ve | Orbital |
|---|---|---|
| **a)** | Dos lóbulos enfrentados alineados con el eje **z** (uno arriba, otro abajo del origen), con signos opuestos de la función de onda (colores distintos) | **p_z** |
| **b)** | Cuatro lóbulos en el plano xy, ubicados **entre** los ejes (en las diagonales) | **d_xy** |
| **c)** | Una esfera centrada en el origen | **s** (1s, 2s, 3s… según el tamaño) |

**Aclaraciones que conviene poner:**

- En **a)** los dos colores indican el **signo de la función de onda Ψ** (positivo y negativo en cada lóbulo), no dos orbitales distintos. Entre los dos lóbulos hay un **nodo** en el núcleo.
- En **b)**, la diferencia entre **d_xy** y **d_x²−y²** está en la orientación: si los lóbulos están **entre** los ejes → **d_xy**; si están **sobre** los ejes → **d_x²−y²**.
- En **c)** no se puede decir *cuál* orbital s es (1s, 2s, 3s) mirando sólo la superficie límite: todos son esferas y sólo se diferencian por el **tamaño** y por la cantidad de **nodos internos**.

---

## Ejercicio 6 — Diagrama de orbitales en cajas

> Indicar el nombre de cada orbital del diagrama de energías, la máxima cantidad de electrones que podrían colocarse, y a qué elemento neutro corresponde el diagrama completo.

### Procedimiento

**Paso 1 — Identificar cada nivel por la CANTIDAD DE CAJAS.** La cantidad de cajas es la cantidad de orbitales del subnivel:

| Cajas | Subnivel |
|---|---|
| 1 | **s** |
| 3 | **p** |
| 5 | **d** |
| 7 | **f** |

**Paso 2 — Ordenar de abajo (menor energía) hacia arriba** siguiendo la regla de las diagonales:

$$1s < 2s < 2p < 3s < 3p < 4s < 3d < 4p$$

⚠️ Fijate que el **4s queda por DEBAJO del 3d** en el diagrama — es exactamente lo que muestra el dibujo y lo que predice la regla de las diagonales.

### ✅ Identificación de los orbitales (de abajo hacia arriba)

| Posición | Cajas | **Orbital** | e⁻ máx |
|---|---|---|---|
| 1 (más bajo) | 1 | **1s** | 2 |
| 2 | 1 | **2s** | 2 |
| 3 | 3 | **2p** | 6 |
| 4 | 1 | **3s** | 2 |
| 5 | 3 | **3p** | 6 |
| 6 | 1 | **4s** | 2 |
| 7 | 5 | **3d** | 10 |
| 8 (más alto) | 3 | **4p** | 6 |
| | **18 orbitales** | | **36 e⁻** |

### ✅ Máxima cantidad de electrones

$$\text{18 orbitales} \times 2\ \tfrac{e^-}{\text{orbital}} = \boxed{36\ \text{electrones}}$$

*(Por el principio de exclusión de Pauli: máximo 2 electrones por orbital, con spines opuestos.)*

### ✅ ¿A qué elemento corresponde?

Si el diagrama está **completo** (todos los orbitales llenos) y el átomo es **neutro**, entonces tiene 36 electrones y por lo tanto **Z = 36**.

$$\boxed{\text{KRIPTÓN (Kr, Z = 36)}}$$

$$\text{CE(Kr)} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{10}\,4p^6$$

📝 **Respuesta tipo parcial**

> El diagrama contiene 18 orbitales (1s, 2s, 2p×3, 3s, 3p×3, 4s, 3d×5, 4p×3). Por el **principio de exclusión de Pauli** entran como máximo 2 electrones por orbital, de modo que la capacidad total es de **36 electrones**.
>
> Si el diagrama está completamente lleno y el átomo es neutro, la cantidad de electrones es igual al número atómico: **Z = 36**, que corresponde al **kriptón (Kr)**, un gas noble. Esto es coherente: al completar el 4p el átomo alcanza la configuración externa **4s² 4p⁶** (octeto), que es la configuración estable característica de los gases nobles.

---

## Ejercicio 7 — Relacionar los esquemas de orbitales con el diagrama de cajas

### Procedimiento

Cada **grupo de cajas** del ejercicio 6 se corresponde con el **conjunto de orbitales de esa forma** que se muestran en las figuras. La cantidad de dibujos debe coincidir con la cantidad de cajas.

### ✅ Correspondencia

| Figuras del ejercicio 7 | Cuántas son | Cajas del ejercicio 6 |
|---|---|---|
| **Esferas 1s, 2s, 3s, 4s** (4 esferas de tamaño creciente) | 1 cada una | Las **4 cajas individuales**: 1s, 2s, 3s, 4s |
| **pₓ, p_y, p_z** (3 lóbulos dobles sobre cada eje) | 3 | Cada uno de los **3 grupos de 3 cajas**: 2p, 3p y 4p |
| **d_z², d_x²−y², d_zx, d_yz, d_xy** (5 orbitales) | 5 | El único **grupo de 5 cajas**: 3d |

### Observaciones que conviene agregar

- **Las esferas s crecen de tamaño** (1s < 2s < 3s < 4s) porque al aumentar n el electrón está, en promedio, **más lejos del núcleo** y tiene **más energía**. La forma no cambia: siempre son esferas.
- **Los 3 orbitales p son idénticos entre sí** en forma y energía (están **degenerados**), y sólo difieren en su orientación espacial: apuntan sobre los ejes x, y y z, perpendiculares entre sí.
- **Los 5 orbitales d también están degenerados** entre sí.
- Las figuras muestran **la forma de un solo subnivel**; el mismo juego de 3 orbitales p sirve para el 2p, el 3p y el 4p — sólo cambia el tamaño.
- ⚠️ Los orbitales **f** no aparecen en las figuras porque **no hay ningún grupo de 7 cajas** en el diagrama del ejercicio 6 (el kriptón no llega a llenar orbitales f).

---

## Ejercicio 8 — Fundamental, excitado o imposible

> Indicar cuáles configuraciones representan el **estado fundamental**, cuáles un **estado excitado** y cuáles **no pueden representar ningún estado**. Asignar las válidas a los elementos correspondientes.

### Procedimiento — los 3 filtros, en este orden

| # | Filtro | Si falla… |
|---|---|---|
| **1** | **Pauli** — máx. 2 e⁻ por orbital, 6 por subnivel p, 10 por d | ❌ **IMPOSIBLE** (no existe ningún estado así) |
| **2** | **Aufbau** — se llenan de menor a mayor energía | ⚠️ **EXCITADO** |
| **3** | **Hund** — en orbitales degenerados, primero uno en cada uno | ⚠️ **EXCITADO** |

Si cumple los tres → **FUNDAMENTAL**.
Para asignar el elemento: **sumar los superíndices** → ése es Z (si es neutro).

### ✅ Tabla de respuestas

| | Configuración | e⁻ (=Z) | Estado | Elemento | Por qué |
|---|---|---|---|---|---|
| **a)** | 1s² | 2 | ✅ **FUNDAMENTAL** | **He** | Cumple las 3 reglas |
| **b)** | 1s² 2p¹ | 3 | ⚠️ **EXCITADO** | **Li** | Viola **Aufbau**: el 2s tiene menos energía que el 2p y está vacío. El fundamental es 1s² 2s¹ |
| **c)** | 1s³ | — | ❌ **IMPOSIBLE** | — | Viola **Pauli**: en el orbital 1s entran máximo 2 e⁻ (no hay un tercer juego de números cuánticos disponible) |
| **d)** | 1s¹ 2s¹ | 2 | ⚠️ **EXCITADO** | **He** | Viola **Aufbau**: el 1s está a medio llenar y ya hay un e⁻ en el 2s. El fundamental es 1s² |
| **e)** | 1s² 2s¹ | 3 | ✅ **FUNDAMENTAL** | **Li** | Cumple las 3 reglas |
| **f)** | 1s² 2s² 2pₓ¹ 2p_y¹ | 6 | ✅ **FUNDAMENTAL** | **C** | Cumple **Hund**: los 2 e⁻ p van en orbitales distintos |
| **g)** | 1s² 2s² 2pₓ² | 6 | ⚠️ **EXCITADO** | **C** | Viola **Hund**: aparea los 2 e⁻ en el mismo orbital p habiendo 2 orbitales p vacíos. Pauli sí se cumple, así que el estado existe, pero no es el de mínima energía |
| **h)** | 1s² 2s² 2pₓ¹ 2p_z¹ | 6 | ✅ **FUNDAMENTAL** | **C** | Igual que f): los 2 e⁻ p en orbitales distintos. Cuál de los tres p se ocupe es **indistinto** (están degenerados) |
| **i)** | 1s² 2s² 2pₓ² 2p_y¹ 2p_z¹ | 8 | ✅ **FUNDAMENTAL** | **O** | Con 4 e⁻ en el 2p, primero uno en cada orbital (Hund) y el cuarto obligadamente aparea |

📝 **Respuesta tipo parcial (para la c)**

> La configuración **1s³ es imposible**: viola el **principio de exclusión de Pauli**. El orbital 1s queda definido por los números cuánticos n=1, ℓ=0, mℓ=0, y el único número que puede diferenciar a dos electrones dentro de él es el spin, que sólo admite dos valores (+½ y −½). Por lo tanto **caben como máximo 2 electrones** y un tercero tendría necesariamente los cuatro números cuánticos iguales a alguno de los otros dos.

📝 **Respuesta tipo parcial (para la g)**

> **1s² 2s² 2pₓ²** corresponde a un **estado excitado** del carbono. No viola Pauli (hay 2 electrones en un orbital con spines opuestos), pero **viola la regla de Hund**: habiendo tres orbitales 2p degenerados, la configuración de menor energía es la que tiene el **mayor número de electrones desapareados**, es decir 2pₓ¹ 2p_y¹. Aparearlos en el mismo orbital aumenta la repulsión electrostática y por lo tanto la energía.

> ⚠️ **La distinción clave del ejercicio:** violar **Pauli** → **imposible** (el estado no existe). Violar **Aufbau o Hund** → **excitado** (el estado existe, pero tiene más energía que el fundamental).

---

## Ejercicio 9 — CE y CEE

> Escribir la **configuración electrónica (CE)** e indicar la **configuración electrónica externa (CEE)**.

### Procedimiento

1. **Z = cantidad de electrones** (átomo neutro).
2. Llenar siguiendo las **diagonales**: 1s 2s 2p 3s 3p **4s 3d** 4p…
3. Capacidades: s→2, p→6, d→10, f→14.
4. ✅ Verificar que **la suma de los superíndices dé Z**.
5. Para la **CEE**: quedarse **sólo con los electrones de MAYOR n**.

---

### a) Ne (Z = 10)

$$\text{CE} = 1s^2\,2s^2\,2p^6 \qquad (2+2+6 = 10\ ✓)$$

$$\boxed{\text{CEE} = 2s^2\,2p^6} \quad \text{→ 8 e}^-\text{ de valencia}$$

*Octeto completo → gas noble.*

---

### b) Na (Z = 11)

$$\text{CE} = 1s^2\,2s^2\,2p^6\,3s^1 = [\text{Ne}]\,3s^1 \qquad (2+2+6+1 = 11\ ✓)$$

$$\boxed{\text{CEE} = 3s^1} \quad \text{→ 1 e}^-\text{ de valencia}$$

---

### c) Cl (Z = 17)

$$\text{CE} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^5 = [\text{Ne}]\,3s^2\,3p^5 \qquad (2+2+6+2+5 = 17\ ✓)$$

$$\boxed{\text{CEE} = 3s^2\,3p^5} \quad \text{→ 7 e}^-\text{ de valencia}$$

---

### d) Ti (Z = 22)

$$\text{CE} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^2 = [\text{Ar}]\,4s^2\,3d^2$$

$$(2+2+6+2+6+2+2 = 22\ ✓)$$

$$\boxed{\text{CEE} = 4s^2} \quad \text{→ 2 e}^-\text{ externos}$$

> ⚠️ **Ojo con el Ti — es la trampa del ejercicio.** El **3d² NO va en la CEE**, aunque se haya llenado después que el 4s. La CEE incluye **únicamente los electrones de mayor n**, y acá n máximo = 4. Los electrones 3d (n=3) quedan como **internos**.
>
> Éste es el mismo caso que el Br del apunte de clase, donde el 3d¹⁰ tampoco entra en la CEE.

---

## Ejercicio 10 — CE de los iones Na⁺ y Cl⁻

### Procedimiento

$$\text{n° de } e^- = Z - \text{carga}$$

Y después se llena normalmente con las diagonales.

---

### Na⁺

- Na tiene **Z = 11** → 11 protones (esto **no cambia nunca**).
- Al ser **catión +1**, perdió 1 electrón: e⁻ = 11 − (+1) = **10 electrones**.

$$\boxed{\text{CE(Na}^+) = 1s^2\,2s^2\,2p^6 = [\text{Ne}]}$$

**Es isoelectrónico con el Neón.**

---

### Cl⁻

- Cl tiene **Z = 17** → 17 protones.
- Al ser **anión −1**, ganó 1 electrón: e⁻ = 17 − (−1) = **18 electrones**.

$$\boxed{\text{CE(Cl}^-) = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6 = [\text{Ar}]}$$

**Es isoelectrónico con el Argón.**

📝 **Respuesta tipo parcial**

> El **Na** (grupo 1, CEE = 3s¹) tiene un único electrón de valencia. Al perderlo forma **Na⁺**, con 10 electrones y configuración **1s² 2s² 2p⁶ = [Ne]**, es decir la configuración de **capa completa del gas noble neón**, que es muy estable. Por eso el Na⁺ es el ion estable del sodio.
>
> El **Cl** (grupo 17, CEE = 3s² 3p⁵) tiene 7 electrones de valencia y le falta **uno** para completar el octeto. Al ganarlo forma **Cl⁻**, con 18 electrones y configuración **1s² 2s² 2p⁶ 3s² 3p⁶ = [Ar]**, la del gas noble argón.
>
> En ambos casos el número de **protones no cambia**: sólo cambia la cantidad de electrones.

---

## Ejercicio 11 — Grupo y período de los elementos de los ejercicios 8 y 9

### Procedimiento

| Dato | Cómo se obtiene |
|---|---|
| **Período** | El valor de **n MÁXIMO** de la configuración |
| **Grupo** (representativos) | La **cantidad de electrones de la CEE** (numeración I–VIII) |
| **Grupo** (IUPAC 1–18) | Bloque s: G = e⁻ CEE · Bloque p: G = e⁻ CEE + 10 |
| **Grupo** (transición) | e⁻ del ns + e⁻ del (n−1)d |

### ✅ Elementos del ejercicio 8

| Elemento | Z | CE (fundamental) | n máx | CEE | **Período** | **Grupo** |
|---|---|---|---|---|---|---|
| **He** | 2 | 1s² | 1 | 1s² | **1** | **18 (VIII A)** — gas noble |
| **Li** | 3 | 1s² 2s¹ | 2 | 2s¹ | **2** | **1 (I A)** — alcalino |
| **C** | 6 | 1s² 2s² 2p² | 2 | 2s² 2p² | **2** | **14 (IV A)** — carbonoideos |
| **O** | 8 | 1s² 2s² 2p⁴ | 2 | 2s² 2p⁴ | **2** | **16 (VI A)** — anfígenos |

> ⚠️ **El He es la excepción de siempre:** su CEE es **1s²** (sólo 2 electrones, no 8), porque en n=1 no existe subnivel p. Igual es gas noble, porque con esos 2 electrones ya tiene la capa n=1 **completa**. Se ubica en el grupo 18 por su comportamiento químico (inerte), no por su cantidad de electrones de valencia.

### ✅ Elementos del ejercicio 9

| Elemento | Z | CE | n máx | CEE | **Período** | **Grupo** |
|---|---|---|---|---|---|---|
| **Ne** | 10 | 1s² 2s² 2p⁶ | 2 | 2s² 2p⁶ | **2** | **18 (VIII A)** — gas noble |
| **Na** | 11 | [Ne] 3s¹ | 3 | 3s¹ | **3** | **1 (I A)** — alcalino |
| **Cl** | 17 | [Ne] 3s² 3p⁵ | 3 | 3s² 3p⁵ | **3** | **17 (VII A)** — halógeno |
| **Ti** | 22 | [Ar] 4s² 3d² | 4 | 4s² | **4** | **4 (IV B)** — metal de transición |

> ⚠️ **Ojo con el Ti:** por ser **metal de transición** (bloque d), el grupo **NO** se saca sólo de la CEE. Se calcula sumando **e⁻ del 4s + e⁻ del 3d = 2 + 2 = 4** → grupo 4 (IV B). Si usaras sólo la CEE (4s² → 2 e⁻) darías mal el grupo.

---

## Ejercicio 12 — Identificar período y grupo a partir de la CE

### Procedimiento

1. **Período** = n máximo.
2. **Sumar TODOS los electrones** (incluido el gas noble del corchete) para obtener **Z** e identificar el elemento.
3. **Grupo:** representativos → e⁻ de la CEE · transición → e⁻ ns + e⁻ (n−1)d.

**Electrones de los gases nobles:** [He]=2 · [Ne]=10 · [Ar]=18 · [Kr]=36 · [Xe]=54 · [Rn]=86

---

### a) [Xe] 4f¹⁴ 5d¹⁰ 6s² 6p²

**Z:** 54 + 14 + 10 + 2 + 2 = **82**

**n máximo = 6** → **Período 6**

**CEE = 6s² 6p²** → 4 electrones externos → **Grupo 14 (IV A)**

$$\boxed{\text{Elemento: PLOMO (Pb, Z = 82) — Período 6, Grupo 14 (IV A)}}$$

*(El 4f¹⁴ y el 5d¹⁰ no entran en la CEE: tienen n = 4 y 5, menores que 6.)*

---

### b) [Ar] 3d⁵ 4s²

**Z:** 18 + 5 + 2 = **25**

**n máximo = 4** → **Período 4**

**Metal de transición** (bloque d) → Grupo = e⁻ 4s + e⁻ 3d = 2 + 5 = **7** → **Grupo 7 (VII B)**

$$\boxed{\text{Elemento: MANGANESO (Mn, Z = 25) — Período 4, Grupo 7 (VII B)}}$$

> 💡 El **3d⁵** es una **semicapa d llena**, configuración de estabilidad extra (por eso el Mn²⁺ y el Fe³⁺, ambos d⁵, son iones muy estables).

---

### c) 1s² 2s² 2p⁶ 3s²

**Z:** 2 + 2 + 6 + 2 = **12**

**n máximo = 3** → **Período 3**

**CEE = 3s²** → 2 electrones externos → **Grupo 2 (II A)**

$$\boxed{\text{Elemento: MAGNESIO (Mg, Z = 12) — Período 3, Grupo 2 (II A)}}$$

---

### d) [Kr] 4d¹⁰ 5s² 5p⁶

**Z:** 36 + 10 + 2 + 6 = **54**

**n máximo = 5** → **Período 5**

**CEE = 5s² 5p⁶** → 8 electrones externos (octeto completo) → **Grupo 18 (VIII A)**

$$\boxed{\text{Elemento: XENÓN (Xe, Z = 54) — Período 5, Grupo 18 (VIII A) — gas noble}}$$

---

### Resumen del ejercicio 12

| | CE | Z | Elemento | Período | Grupo |
|---|---|---|---|---|---|
| a) | [Xe] 4f¹⁴ 5d¹⁰ 6s² 6p² | 82 | **Pb** | 6 | 14 (IV A) |
| b) | [Ar] 3d⁵ 4s² | 25 | **Mn** | 4 | 7 (VII B) |
| c) | 1s² 2s² 2p⁶ 3s² | 12 | **Mg** | 3 | 2 (II A) |
| d) | [Kr] 4d¹⁰ 5s² 5p⁶ | 54 | **Xe** | 5 | 18 (VIII A) |

---

## Ejercicio 13 — Iones de Ba y F, y cuál es el más estable

### Procedimiento

1. Escribir la **CE del átomo neutro** y sacar la **CEE**.
2. Ver **cuántos electrones le sobran o le faltan** para llegar a la configuración de gas noble (`ns² np⁶`).
3. El ion más estable es el que alcanza esa configuración con la **menor transferencia de electrones**.

---

### a) Bario (Ba, Z = 56)

$$\text{CE(Ba)} = [\text{Xe}]\,6s^2 \qquad \text{CEE} = 6s^2 \quad \text{→ Grupo 2, Período 6}$$

**Iones posibles:**

| Ion | e⁻ | CE | ¿Capa llena? |
|---|---|---|---|
| **Ba⁺** | 55 | [Xe] 6s¹ | ❌ No — le queda 1 e⁻ suelto en el 6s |
| **Ba²⁺** | 54 | **[Xe]** | ✅ **SÍ** — isoelectrónico con el xenón |

$$\boxed{\text{Ion más estable: } \mathbf{Ba^{2+}} \quad \text{CE} = [\text{Xe}] = 1s^2 2s^2 2p^6 3s^2 3p^6 4s^2 3d^{10} 4p^6 5s^2 4d^{10} 5p^6}$$

---

### b) Flúor (F, Z = 9)

$$\text{CE(F)} = 1s^2\,2s^2\,2p^5 \qquad \text{CEE} = 2s^2\,2p^5 \quad \text{→ Grupo 17, Período 2}$$

**Iones posibles:**

| Ion | e⁻ | CE | ¿Capa llena? |
|---|---|---|---|
| **F⁻** | 10 | **1s² 2s² 2p⁶ = [Ne]** | ✅ **SÍ** — isoelectrónico con el neón |
| **F⁺** | 8 | 1s² 2s² 2p⁴ | ❌ No — y encima cuesta muchísima energía |

$$\boxed{\text{Ion más estable: } \mathbf{F^-} \quad \text{CE} = 1s^2\,2s^2\,2p^6 = [\text{Ne}]}$$

📝 **Respuesta tipo parcial**

> **Ba:** su CEE es **6s²**, es decir tiene 2 electrones de valencia (grupo 2). Al ser un metal, tiende a **cederlos**. Perdiendo los 2 electrones del 6s forma el **Ba²⁺**, cuya configuración es **[Xe]**, la del gas noble xenón: capa externa completa (5s² 5p⁶) y por lo tanto muy estable. El Ba⁺ no es estable porque quedaría con un electrón desapareado en el 6s, sin alcanzar la configuración de capa llena.
>
> **F:** su CEE es **2s² 2p⁵**, o sea 7 electrones de valencia (grupo 17): le falta **uno solo** para completar el octeto. Como además es el elemento más electronegativo de la tabla, tiende fuertemente a **captar** ese electrón y formar **F⁻**, con configuración **[Ne]**. La formación de F⁺ es muy desfavorable, ya que implicaría arrancarle un electrón al átomo que más los atrae.
>
> **Criterio general:** el ion más estable de un elemento representativo es el que alcanza la **configuración de capa completa del gas noble más cercano** cediendo o captando la menor cantidad de electrones posible.

---

## Ejercicio 14 — Ion isoelectrónico

> Un átomo del elemento **Q** al ganar 1 electrón forma un ion **isoelectrónico** con el catión **R²⁺**. Sabiendo que **R tiene Z = 38**, indicar la configuración electrónica del ion y del elemento.

### Procedimiento

**Paso 1 — Entender "isoelectrónico":** dos especies son isoelectrónicas cuando tienen **la misma cantidad de electrones** (y por lo tanto la misma configuración electrónica), aunque tengan distinto número de protones.

**Paso 2 — Calcular los electrones de R²⁺.**

R tiene Z = 38 (es el **estroncio, Sr**). Al ser catión 2+ perdió 2 electrones:

$$e^-(R^{2+}) = 38 - 2 = 36\ \text{electrones}$$

**Paso 3 — Q⁻ tiene los mismos electrones.**

$$e^-(Q^-) = 36$$

**Paso 4 — Volver al átomo neutro Q.**

Q ganó 1 electrón para formar Q⁻, así que el átomo neutro tenía uno menos:

$$e^-(Q) = 36 - 1 = 35 \quad \Longrightarrow \quad Z(Q) = 35$$

$$\boxed{Q = \text{BROMO (Br)}}$$

### ✅ Configuraciones

**Del ion Q⁻ (Br⁻), con 36 electrones:**

$$\text{CE(Br}^-) = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{10}\,4p^6 = [\text{Ar}]\,4s^2\,3d^{10}\,4p^6 = \boxed{[\text{Kr}]}$$

**Del elemento Q (Br neutro), con 35 electrones:**

$$\text{CE(Br)} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{10}\,4p^5 = \boxed{[\text{Ar}]\,4s^2\,3d^{10}\,4p^5}$$

$$\text{CEE(Br)} = 4s^2\,4p^5 \quad \text{→ 7 e}^-\text{ de valencia → Grupo 17, Período 4}$$

📝 **Respuesta tipo parcial**

> R tiene Z = 38, por lo que **R²⁺ posee 38 − 2 = 36 electrones**. Como Q⁻ es **isoelectrónico** con R²⁺, también tiene **36 electrones**. Dado que Q⁻ se formó cuando Q **ganó 1 electrón**, el átomo neutro Q tiene **35 electrones**, y por lo tanto **Z(Q) = 35**: se trata del **bromo**.
>
> Esto es químicamente coherente: el Br pertenece al **grupo 17 (halógenos)**, tiene 7 electrones de valencia y le falta uno para completar el octeto, por lo que **efectivamente tiende a ganar 1 electrón** y formar Br⁻, alcanzando la configuración del kriptón.

> 💡 **Nota:** las tres especies **Sr²⁺, Br⁻ y Kr** son isoelectrónicas entre sí (36 electrones cada una), pero **no son el mismo elemento**: tienen 38, 35 y 36 protones respectivamente.

---

## Ejercicio 15

### i. Iones más estables del hierro. ¿Sirve el mismo análisis de la CEE?

**CE del Fe (Z = 26):**

$$\text{CE(Fe)} = [\text{Ar}]\,4s^2\,3d^6$$

**Iones más estables:**

| Ion | e⁻ | CE | Por qué es estable |
|---|---|---|---|
| **Fe²⁺** | 24 | **[Ar] 3d⁶** | Pierde los 2 e⁻ del **4s** (los de mayor n) |
| **Fe³⁺** | 23 | **[Ar] 3d⁵** | Pierde los 2 del 4s **más** 1 del 3d → queda con **semicapa d llena (d⁵)**, que tiene estabilidad extra |

> ⚠️ **Regla clave:** al formar cationes de metales de transición se quitan **PRIMERO los electrones del orbital ns** (mayor n), y recién después los del (n−1)d — **aunque el ns se haya llenado primero** según la regla de las diagonales.

### ✅ ¿Sirve el mismo análisis de la CEE?

$$\boxed{\text{NO}}$$

📝 **Respuesta tipo parcial**

> **No, el análisis de la CEE que se usa para los elementos representativos no sirve para los metales de transición.**
>
> En los **elementos representativos** (bloques s y p), la CEE permite predecir directamente cuál es el ion más estable: el elemento cede o capta los electrones necesarios para alcanzar la **configuración de gas noble** (`ns² np⁶`), y por eso cada grupo forma un único ion característico (grupo 1 → +1, grupo 2 → +2, grupo 17 → −1, etc.).
>
> En los **metales de transición** esto no funciona porque:
>
> 1. Los orbitales **(n−1)d y ns tienen energías muy parecidas**, de modo que los electrones d también pueden participar en la formación de iones.
> 2. Alcanzar la configuración de gas noble exigiría ceder o captar **demasiados electrones** (al Fe le sobrarían 8 o le faltarían 10), lo que es energéticamente inviable.
> 3. Como consecuencia, los metales de transición presentan **varios estados de oxidación estables** en lugar de uno solo (el Fe forma Fe²⁺ y Fe³⁺; el Mn llega a formar hasta Mn⁷⁺).
>
> El criterio que sí aplica es otro: se **remueven primero los electrones del orbital ns** (los de mayor n) y luego los del (n−1)d, y resultan especialmente estables las configuraciones de **subcapa d semillena (d⁵)** y **d completa (d¹⁰)**. Por eso el **Fe³⁺ ([Ar]3d⁵)** es particularmente estable.

---

### ii. Elemento con CE = [Ar] 3d¹⁰ 4s¹

**Paso 1 — Calcular Z:**

$$Z = 18 + 10 + 1 = 29$$

$$\boxed{\text{COBRE (Cu, Z = 29)}}$$

**Paso 2 — Período:** n máximo = 4 → **Período 4**

**Paso 3 — Grupo:** metal de transición → e⁻ 4s + e⁻ 3d = 1 + 10 = 11 → **Grupo 11 (I B)**

### ✅ ¿Por qué no cumple la regla de las diagonales?

📝 **Respuesta tipo parcial**

> Según la **regla de las diagonales**, la configuración esperada para Z = 29 sería **[Ar] 4s² 3d⁹**. Sin embargo, la configuración real del cobre es **[Ar] 3d¹⁰ 4s¹**.
>
> Esto ocurre porque los orbitales **4s y 3d tienen energías muy cercanas**, y la configuración con la **subcapa d completa (3d¹⁰)** resulta **energéticamente más favorable** que la que tendría el 4s lleno y el 3d incompleto. Por eso un electrón "pasa" del 4s al 3d.
>
> Es una de las **excepciones conocidas** a la regla de las diagonales, junto con el **cromo (Cr, Z = 24)**, que en lugar de [Ar] 4s² 3d⁴ tiene **[Ar] 3d⁵ 4s¹**, alcanzando la **semicapa d llena (d⁵)**.
>
> **Regla general de las excepciones:** las configuraciones **d⁵ (semillena)** y **d¹⁰ (completa)** poseen una estabilidad adicional, y cuando se puede alcanzarlas promoviendo un solo electrón del ns al (n−1)d, el átomo lo hace.

---
---

# PARA TRABAJAR FUERA DE CLASE

---

## Ejercicio 1 — Lámpara de vapor de sodio (λ = 589 nm)

### a) Energía por mol de átomos de sodio

### Procedimiento

$$E_{\text{mol}} = \frac{hc}{\lambda}\cdot N_A$$

**Paso 1 — λ a metros:** 589 nm = 5,89×10⁻⁷ m

**Paso 2 — Energía de un fotón:**

$$E_{\text{fotón}} = \frac{6,63\times10^{-34}\times3,0\times10^{8}}{5,89\times10^{-7}} = \frac{1,989\times10^{-25}}{5,89\times10^{-7}} = 3,377\times10^{-19}\ \text{J}$$

**Paso 3 — Por mol:**

$$E_{\text{mol}} = 3,377\times10^{-19}\times6,022\times10^{23} = 2,033\times10^{5}\ \text{J/mol}$$

### ✅ Respuesta

$$\boxed{E \approx 203{,}3\ \text{kJ/mol}}$$

*(Coincide con la respuesta de la guía.)*

---

### b) ¿Entre qué orbitales atómicos se produce la transición?

**CE del Na (Z = 11):** [Ne] 3s¹ → el electrón de valencia está en el **3s**.

Al excitarse (por la descarga eléctrica de la lámpara), ese electrón sube al **3p**. Al desexcitarse vuelve al 3s y emite el fotón amarillo.

$$\boxed{\text{Transición } 3p \longrightarrow 3s}$$

📝 **Respuesta tipo parcial**

> La configuración electrónica del sodio es **[Ne] 3s¹**: tiene un único electrón de valencia en el orbital **3s**. En la lámpara, la descarga eléctrica **excita** ese electrón promoviéndolo al orbital **3p** (estado excitado: [Ne] 3p¹).
>
> Al **desexcitarse**, el electrón vuelve al 3s y el átomo **emite un fotón** cuya energía es igual a la diferencia entre ambos niveles (ΔE = hν = 3,38×10⁻¹⁹ J), correspondiente a λ = 589 nm, que se percibe como **luz amarilla**.
>
> Esta emisión se conoce como la **línea D del sodio** y es la responsable del color característico del alumbrado público de vapor de sodio y del ensayo a la llama del sodio.

---

## Ejercicio 2 — CE de Ar (Z = 18) y Zr (Z = 40)

### Ar (Z = 18)

$$\text{CE(Ar)} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6 = [\text{Ne}]\,3s^2\,3p^6$$

$$(2+2+6+2+6 = 18\ ✓)$$

$$\text{CEE} = 3s^2\,3p^6 \quad \text{→ octeto → gas noble, Grupo 18, Período 3}$$

### Zr (Z = 40)

Siguiendo las diagonales: 1s 2s 2p 3s 3p **4s 3d** 4p **5s 4d**

$$\text{CE(Zr)} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{10}\,4p^6\,5s^2\,4d^2 = [\text{Kr}]\,5s^2\,4d^2$$

**Verificación:** 2+2+6+2+6+2+10+6+2+2 = **40** ✓

$$\text{CEE} = 5s^2 \quad \text{→ metal de transición, Período 5}$$

**Grupo:** e⁻ 5s + e⁻ 4d = 2 + 2 = **4** → **Grupo 4 (IV B)**

> 💡 El Zr está justo **debajo del Ti** en la tabla (ambos grupo 4, con configuración externa análoga: Ti = [Ar]4s²3d², Zr = [Kr]5s²4d²). Por eso tienen química parecida.

---

## Ejercicio 3 — CE de los iones Zn²⁺ y O²⁻

### Zn²⁺

**CE del Zn neutro (Z = 30):**

$$\text{CE(Zn)} = [\text{Ar}]\,4s^2\,3d^{10} \qquad (18+2+10 = 30\ ✓)$$

**Electrones del Zn²⁺:** 30 − 2 = **28**

⚠️ Al ser metal de transición, se quitan **primero los electrones del 4s**:

$$\boxed{\text{CE(Zn}^{2+}) = [\text{Ar}]\,3d^{10} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,3d^{10}}$$

**Verificación:** 2+2+6+2+6+10 = **28** ✓

> 💡 El Zn²⁺ tiene la **subcapa 3d completa (d¹⁰)**, que es una configuración de estabilidad extra. Por eso el **Zn²⁺ es prácticamente el único ion que forma el cinc** (a diferencia del Fe, que forma dos).

---

### O²⁻

**CE del O neutro (Z = 8):**

$$\text{CE(O)} = 1s^2\,2s^2\,2p^4$$

**Electrones del O²⁻:** 8 − (−2) = **10**

$$\boxed{\text{CE(O}^{2-}) = 1s^2\,2s^2\,2p^6 = [\text{Ne}]}$$

**Isoelectrónico con el neón.** El O pertenece al grupo 16 (CEE = 2s²2p⁴, 6 e⁻ de valencia) y le faltan **2 electrones** para el octeto: por eso gana 2 y forma O²⁻.

---

## Ejercicio 4 — Iones de Pb, S y Al

### a) Plomo (Pb, Z = 82)

$$\text{CE(Pb)} = [\text{Xe}]\,4f^{14}\,5d^{10}\,6s^2\,6p^2 \qquad \text{CEE} = 6s^2\,6p^2 \quad \text{→ Grupo 14, Período 6}$$

**Iones posibles:**

| Ion | e⁻ perdidos | CE |
|---|---|---|
| **Pb²⁺** | los 2 del **6p** | [Xe] 4f¹⁴ 5d¹⁰ **6s²** |
| **Pb⁴⁺** | los 2 del 6p **y** los 2 del 6s | [Xe] 4f¹⁴ 5d¹⁰ |

$$\boxed{\text{Más estable: } \mathbf{Pb^{2+}}}$$

📝 **Respuesta tipo parcial**

> El Pb pertenece al grupo 14 y tiene 4 electrones de valencia (6s² 6p²), por lo que en principio podría formar **Pb²⁺** (perdiendo los 6p²) o **Pb⁴⁺** (perdiendo también los 6s²).
>
> El más estable es el **Pb²⁺**, por el llamado **efecto del par inerte**: en los elementos pesados del bloque p, el par de electrones **ns²** está fuertemente retenido y resulta difícil de arrancar, por lo que el elemento tiende a ceder únicamente los electrones np. Por eso el estado de oxidación +2 predomina sobre el +4 en el plomo.

---

### b) Azufre (S, Z = 16)

$$\text{CE(S)} = [\text{Ne}]\,3s^2\,3p^4 \qquad \text{CEE} = 3s^2\,3p^4 \quad \text{→ Grupo 16, Período 3}$$

Tiene 6 electrones de valencia → le faltan **2** para el octeto.

$$\boxed{\text{Más estable: } \mathbf{S^{2-}} \quad \text{CE} = [\text{Ne}]\,3s^2\,3p^6 = [\text{Ar}]}$$

*Isoelectrónico con el argón.* Ganar 2 electrones es mucho más favorable que perder 6.

---

### c) Aluminio (Al, Z = 13)

$$\text{CE(Al)} = [\text{Ne}]\,3s^2\,3p^1 \qquad \text{CEE} = 3s^2\,3p^1 \quad \text{→ Grupo 13, Período 3}$$

Tiene 3 electrones de valencia → le conviene **perderlos** (ganar 5 sería inviable).

$$\boxed{\text{Más estable: } \mathbf{Al^{3+}} \quad \text{CE} = 1s^2\,2s^2\,2p^6 = [\text{Ne}]}$$

*Isoelectrónico con el neón.*

---

### Resumen del ejercicio 4

| Elemento | Z | CEE | Grupo | **Ion más estable** | CE del ion |
|---|---|---|---|---|---|
| **Pb** | 82 | 6s² 6p² | 14 | **Pb²⁺** | [Xe] 4f¹⁴ 5d¹⁰ 6s² |
| **S** | 16 | 3s² 3p⁴ | 16 | **S²⁻** | [Ar] |
| **Al** | 13 | 3s² 3p¹ | 13 | **Al³⁺** | [Ne] |

---

## Ejercicio 5 — CE, CEE, grupo y período. ¿Cuáles forman iones isoelectrónicos con el Ar?

### Tabla completa

| Elemento | Z | **CE** | **CEE** | **Período** | **Grupo** |
|---|---|---|---|---|---|
| **K** | 19 | [Ar] 4s¹ | 4s¹ | **4** | **1 (I A)** |
| **I** | 53 | [Kr] 5s² 4d¹⁰ 5p⁵ | 5s² 5p⁵ | **5** | **17 (VII A)** |
| **Br** | 35 | [Ar] 4s² 3d¹⁰ 4p⁵ | 4s² 4p⁵ | **4** | **17 (VII A)** |
| **Rb** | 37 | [Kr] 5s¹ | 5s¹ | **5** | **1 (I A)** |
| **S** | 16 | [Ne] 3s² 3p⁴ | 3s² 3p⁴ | **3** | **16 (VI A)** |
| **Mg** | 12 | [Ne] 3s² | 3s² | **3** | **2 (II A)** |

### ¿Cuáles forman iones isoelectrónicos con el argón (Z = 18)?

### Procedimiento

Un ion es isoelectrónico con el Ar si tiene **exactamente 18 electrones**. Se calcula el ion más estable de cada elemento y se cuentan sus electrones:

| Elemento | Z | Ion estable | e⁻ del ion | ¿= 18? |
|---|---|---|---|---|
| **K** | 19 | K⁺ | 19 − 1 = **18** | ✅ **SÍ** |
| I | 53 | I⁻ | 53 + 1 = 54 | ❌ (es [Xe]) |
| Br | 35 | Br⁻ | 35 + 1 = 36 | ❌ (es [Kr]) |
| Rb | 37 | Rb⁺ | 37 − 1 = 36 | ❌ (es [Kr]) |
| **S** | 16 | S²⁻ | 16 + 2 = **18** | ✅ **SÍ** |
| Mg | 12 | Mg²⁺ | 12 − 2 = 10 | ❌ (es [Ne]) |

### ✅ Respuesta

$$\boxed{\text{K}^+ \text{ y } \text{S}^{2-}}$$

📝 **Respuesta tipo parcial**

> Forman iones isoelectrónicos con el argón el **potasio (K⁺)** y el **azufre (S²⁻)**, porque ambos quedan con **18 electrones**, la misma cantidad que tiene el Ar (Z = 18), y por lo tanto con idéntica configuración electrónica: **1s² 2s² 2p⁶ 3s² 3p⁶**.
>
> - El **K** está inmediatamente **después** del Ar en la tabla (Z = 19) y su CEE es 4s¹: al **perder** ese único electrón de valencia queda con 18 e⁻.
> - El **S** está **antes** del Ar (Z = 16) y su CEE es 3s² 3p⁴: al **ganar** 2 electrones completa el octeto y llega a 18 e⁻.
>
> Los demás no lo cumplen: I⁻ y Rb⁺/Br⁻ resultan isoelectrónicos con el Xe y el Kr respectivamente, y el Mg²⁺ con el Ne.
>
> ⚠️ Ser isoelectrónicos **no significa ser el mismo elemento**: K⁺, S²⁻ y Ar tienen 19, 16 y 18 **protones** respectivamente. La cantidad de protones no cambia nunca.

---

## Ejercicio 6 — Diagrama de energías del elemento X

> X tiene CE = 1s² 2s² 2p⁶ 3s² 3p². Escribir el diagrama de energías del estado fundamental.

### Identificación

$$Z = 2+2+6+2+2 = 14 \quad \Longrightarrow \quad \boxed{\text{X = SILICIO (Si)}}$$

**CEE = 3s² 3p²** → 4 e⁻ de valencia → **Grupo 14 (IV A), Período 3**

### ✅ Diagrama de energías (estado fundamental)

```
  Energía
     ↑
     │
 3p  │   ↑ __   ↑ __   __ __        ← Hund: 2 e⁻ DESAPAREADOS, uno en cada orbital
     │  3pₓ    3p_y   3p_z
     │
 3s  │   ↑↓
     │
 2p  │   ↑↓     ↑↓     ↑↓
     │  2pₓ    2p_y   2p_z
     │
 2s  │   ↑↓
     │
 1s  │   ↑↓
     │
```

**Con cajas:**

| Subnivel | Diagrama |
|---|---|
| **3p** | `[↑ ][↑ ][  ]` |
| **3s** | `[↑↓]` |
| **2p** | `[↑↓][↑↓][↑↓]` |
| **2s** | `[↑↓]` |
| **1s** | `[↑↓]` |

### Justificación de cada regla aplicada

| Regla | Dónde se ve |
|---|---|
| **Aufbau** | Se llenó de abajo hacia arriba: 1s → 2s → 2p → 3s → 3p |
| **Pauli** | Ningún orbital tiene más de 2 flechas, y las que están apareadas van en sentido opuesto (↑↓) |
| **Hund** | Los 2 electrones del 3p van **en orbitales distintos y con el mismo spin** (↑ ↑), dejando el tercer orbital 3p vacío. **No** se aparean en 3pₓ² |

> ⚠️ **El error clásico acá** es dibujar el 3p como `[↑↓][  ][  ]`. Eso sería un **estado excitado** (viola Hund), no el fundamental.

**Verificación:** 2 + 2 + 6 + 2 + 2 = **14 electrones** ✓ · **2 electrones desapareados** en el 3p.

---

## Ejercicio 7 — Iones isoelectrónicos con el 3° gas noble

> Los iones X³⁻, Y⁻, M⁺ y P³⁺ son isoelectrónicos con el 3° gas noble (Z = 18). Hallar la CEE de cada uno de los elementos X, Y, M y P, e indicar grupo y período.

### Procedimiento

**Paso 1 — Identificar el gas noble.** Los gases nobles en orden son: He (1°), Ne (2°), **Ar (3°, Z = 18)**, Kr (4°)…

Entonces **los cuatro iones tienen 18 electrones**.

**Paso 2 — Despejar Z de cada elemento neutro** con:

$$e^- = Z - \text{carga} \qquad \Longrightarrow \qquad Z = e^- + \text{carga}$$

**⚠️ Cuidado con los signos:** si el ion es **negativo**, el átomo neutro tiene **menos** electrones que el ion. Si es **positivo**, tiene **más**.

### ✅ Desarrollo

| Ion | e⁻ | Cuenta | **Z** | **Elemento** |
|---|---|---|---|---|
| **X³⁻** | 18 | Z = 18 + (−3) = 18 − 3 | **15** | **P** (fósforo) |
| **Y⁻** | 18 | Z = 18 + (−1) = 18 − 1 | **17** | **Cl** (cloro) |
| **M⁺** | 18 | Z = 18 + (+1) | **19** | **K** (potasio) |
| **P³⁺** | 18 | Z = 18 + (+3) | **21** | **Sc** (escandio) |

### ✅ Tabla de respuestas

| Elemento | Z | CE | **CEE** | **Grupo** | **Período** |
|---|---|---|---|---|---|
| **X = Fósforo (P)** | 15 | [Ne] 3s² 3p³ | **3s² 3p³** | **15 (V A)** | **3** |
| **Y = Cloro (Cl)** | 17 | [Ne] 3s² 3p⁵ | **3s² 3p⁵** | **17 (VII A)** | **3** |
| **M = Potasio (K)** | 19 | [Ar] 4s¹ | **4s¹** | **1 (I A)** | **4** |
| **P = Escandio (Sc)** | 21 | [Ar] 4s² 3d¹ | **4s²** | **3 (III B)** | **4** |

> ⚠️ **Cuidado con la notación del enunciado:** el elemento llamado "**P**" en el problema **no es el fósforo** — es sólo un nombre genérico. Resulta ser el **escandio**. (Y para peor, el elemento "X" **sí** termina siendo el fósforo, cuyo símbolo real es P. Es una coincidencia desafortunada del enunciado.)

**Verificación de coherencia química:**

- **P** (grupo 15, 5 e⁻ de valencia): le faltan 3 para el octeto → gana 3 → **P³⁻** ✓
- **Cl** (grupo 17, 7 e⁻): le falta 1 → gana 1 → **Cl⁻** ✓
- **K** (grupo 1, 1 e⁻): le sobra 1 → pierde 1 → **K⁺** ✓
- **Sc** (grupo 3, transición): pierde los 2 del 4s y el 1 del 3d → **Sc³⁺** ✓ (queda en [Ar])

> 💡 **El Sc es el único de los cuatro que es metal de transición.** Su grupo se calcula como e⁻ 4s + e⁻ 3d = 2 + 1 = 3, y su CEE estricta es sólo **4s²** (el 3d¹ tiene n = 3).

---

## Ejercicio 8 — Los elementos X, Y y W

> - **X** forma aniones estables X²⁻ isoelectrónicos con el Ar (Z = 18)
> - **Y** pertenece al mismo grupo que el Br (Z = 35) y al mismo período que el Si (Z = 14)
> - **W** pertenece al segundo período y forma compuestos iónicos con el Na (Z = 11) del tipo NaW

### Procedimiento

---

**🔹 Elemento X**

X²⁻ es isoelectrónico con el Ar → tiene **18 electrones**.

$$Z(X) = 18 + (-2) = 18 - 2 = 16 \quad \Longrightarrow \quad \boxed{X = \text{AZUFRE (S)}}$$

$$\text{CE(S)} = [\text{Ne}]\,3s^2\,3p^4 \qquad \text{CEE} = 3s^2\,3p^4 \quad \text{→ Grupo 16 (VI A), Período 3}$$

*Coherente: con 6 e⁻ de valencia le faltan 2 para el octeto → forma S²⁻.* ✓

---

**🔹 Elemento Y**

- **Mismo grupo que el Br (Z = 35):** CE(Br) = [Ar] 4s² 3d¹⁰ 4p⁵ → CEE = 4s² 4p⁵ → 7 e⁻ de valencia → **Grupo 17 (halógenos)**.
- **Mismo período que el Si (Z = 14):** CE(Si) = [Ne] 3s² 3p² → n máx = 3 → **Período 3**.

Buscamos el elemento del **grupo 17, período 3** → CEE = **3s² 3p⁵**

$$Z(Y) = 10 + 2 + 5 = 17 \quad \Longrightarrow \quad \boxed{Y = \text{CLORO (Cl)}}$$

---

**🔹 Elemento W**

- **Segundo período** → n máx = 2.
- **Forma NaW**, un compuesto iónico de estequiometría **1:1**. Como el Na forma **Na⁺** (grupo 1), para que el compuesto sea eléctricamente neutro W debe formar un anión de **carga −1**: **W⁻**.
- Un elemento que gana 1 electrón tiene **7 e⁻ de valencia** → **Grupo 17 (halógenos)**.

Grupo 17 + período 2 → CEE = **2s² 2p⁵**

$$Z(W) = 2 + 2 + 5 = 9 \quad \Longrightarrow \quad \boxed{W = \text{FLÚOR (F)}}$$

*Verificación: el compuesto sería **NaF** (fluoruro de sodio), que efectivamente existe y es iónico 1:1.* ✓

---

### ✅ a) Números atómicos

$$\boxed{Z(X) = 16 \quad\quad Z(Y) = 17 \quad\quad Z(W) = 9}$$

### ✅ b) Grupo y período

| Elemento | Z | Símbolo | CE | CEE | **Grupo** | **Período** |
|---|---|---|---|---|---|---|
| **X** | 16 | **S** | [Ne] 3s² 3p⁴ | 3s² 3p⁴ | **16 (VI A)** | **3** |
| **Y** | 17 | **Cl** | [Ne] 3s² 3p⁵ | 3s² 3p⁵ | **17 (VII A)** | **3** |
| **W** | 9 | **F** | 1s² 2s² 2p⁵ | 2s² 2p⁵ | **17 (VII A)** | **2** |

📝 **Respuesta tipo parcial (para W, que es la parte más pensada)**

> El compuesto **NaW** tiene estequiometría **1:1**. Como el sodio pertenece al grupo 1 y forma el catión **Na⁺**, para que el compuesto resulte eléctricamente neutro el elemento W debe formar un anión de carga **−1** (W⁻).
>
> Un elemento que gana **un solo electrón** para completar su octeto tiene **7 electrones de valencia**, es decir pertenece al **grupo 17 (halógenos)**. Como además el enunciado indica que está en el **segundo período**, su configuración electrónica externa es **2s² 2p⁵**, lo que corresponde a **Z = 9: el flúor**. El compuesto en cuestión es el **NaF**.

---

## Ejercicio 9 — CEE genérica de cada grupo

### Procedimiento

La CEE genérica se escribe con **n** en lugar de un número concreto, porque **todos los elementos de un mismo grupo comparten la misma configuración externa** (sólo cambia el nivel n según el período).

### ✅ Respuestas

| | Grupo | **CEE genérica** | e⁻ de valencia |
|---|---|---|---|
| **a)** | **Gases nobles** (18 / VIII A) | **ns² np⁶** | 8 |
| **b)** | **Metales alcalinos** (1 / I A) | **ns¹** | 1 |
| **c)** | **Halógenos** (17 / VII A) | **ns² np⁵** | 7 |
| **d)** | **Metales alcalino térreos** (2 / II A) | **ns²** | 2 |
| **e)** | **Grupo del carbono** (14 / IV A) | **ns² np²** | 4 |
| **f)** | **Grupo del oxígeno** (16 / VI A) | **ns² np⁴** | 6 |
| **g)** | **Metales de transición** (3–12 / B) | **ns² (n−1)d^(1–10)** | variable |
| **h)** | **Lantánidos y actínidos** | **ns² (n−2)f^(1–14)** | variable |

### Aclaraciones importantes

> ⚠️ **a) Gases nobles — la excepción del helio.** La CEE genérica es **ns² np⁶**, pero el **He** no la cumple: su configuración es **1s²**, porque en n = 1 no existe subnivel p. Igual es gas noble porque con esos 2 electrones tiene la capa n = 1 **completa**.

> ⚠️ **g) y h) — cuidado con la CEE estricta.** En los metales de transición y en los lantánidos/actínidos, los orbitales **d** y **f** que se están llenando **NO pertenecen al nivel n máximo**:
> - Metales de transición: se llena el **(n−1)d** mientras el nivel externo es el **ns**. La CEE *estricta* (sólo n máximo) es **ns¹⁻²**.
> - Lantánidos y actínidos: se llena el **(n−2)f**. La CEE estricta es **ns²**.
>
> Por eso **para estos elementos el grupo NO se deduce de la CEE**, sino sumando los electrones **ns + (n−1)d** (ver ejercicios 11, 12b y 15).

### Patrón general (bloques s y p)

| e⁻ de valencia | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|---|---|---|---|---|---|---|---|---|
| **CEE** | ns¹ | ns² | ns²np¹ | ns²np² | ns²np³ | ns²np⁴ | ns²np⁵ | ns²np⁶ |
| **Grupo (romano)** | I A | II A | III A | IV A | V A | VI A | VII A | VIII A |
| **Grupo (IUPAC)** | 1 | 2 | 13 | 14 | 15 | 16 | 17 | 18 |

---
---

# ✅ Verificación con las respuestas de la guía

| Ejercicio | Respuesta de la guía | Lo que dio acá | ¿Coincide? |
|---|---|---|---|
| Clase 1 | 1,3×10⁶ átomos de C | 1,3×10⁶ | ✅ |
| Clase 2b | 182,4 kJ/mol (roja) · 246,4 kJ/mol (verde) | 182,5 · 246,5 | ✅ (redondeo de constantes) |
| Casa 1a | 203,3 kJ/mol | 203,3 | ✅ |

---

# 📌 Resumen de métodos que usa esta serie

| Método | Dónde se usa |
|---|---|
| **Conversión de unidades** (Å, nm, mm → m) | Clase 1, 2, Casa 1 |
| **E = hc/λ** y energía **por mol** (×N_A) | Clase 2, Casa 1 |
| **Wh → J** (× 3600) | Clase 2c |
| **ΔE mayor ⇒ λ menor** | Clase 2b, 3 |
| **Identificar orbitales por su forma** | Clase 5, 7 |
| **Cantidad de cajas → subnivel** (1=s, 3=p, 5=d, 7=f) | Clase 6, 7 |
| **Filtros Pauli / Aufbau / Hund** | Clase 8, Casa 6 |
| **Regla de las diagonales** | Clase 9, 12, 14; Casa 2, 3, 5 |
| **CEE = sólo los e⁻ de n máximo** | Clase 9d, 11, 12 |
| **e⁻ = Z − carga** | Clase 10, 13, 14; Casa 3, 4, 5, 7, 8 |
| **Isoelectrónicos** (misma cantidad de e⁻) | Clase 10, 14; Casa 5, 7, 8 |
| **Grupo = e⁻ de valencia** (representativos) | Clase 11, 12; Casa 5, 7, 8, 9 |
| **Grupo = ns + (n−1)d** (transición) | Clase 11 (Ti), 12b, 15 |
| **Iones de transición: sacar ns primero** | Clase 15; Casa 3 |
| **Estabilidad extra de d⁵ y d¹⁰** | Clase 15 (Fe³⁺, Cu) |
| **Estequiometría iónica → carga → grupo** | Casa 8 (W) |
