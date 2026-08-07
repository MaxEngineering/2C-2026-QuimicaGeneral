# 🧪 MACHETE — Química General (ECyT / UNSAM · 2C 2026)

> Resumen operativo de toda la materia. Sólo lo que hay que saber para resolver.
> Para la explicación desarrollada diapositiva por diapositiva ver `Clase1/Clase1-Explicacion-Completa.md`.

**Contenido actual:** Clase 1 (Átomo y configuración electrónica) · Clase 2 (Uniones químicas, Lewis y geometría)

---

## 📑 Índice

- [0. Constantes y unidades](#0-constantes-y-unidades)
- [1. Estructura atómica](#1-estructura-atómica)
- [2. Luz y energía cuantizada](#2-luz-y-energía-cuantizada)
- [3. Números cuánticos](#3-números-cuánticos)
- [4. Configuración electrónica](#4-configuración-electrónica-ce)
- [5. Iones](#5-iones)
- [6. Tabla periódica y valencia](#6-tabla-periódica-y-valencia)
- [7. Estructuras de Lewis](#7-estructuras-de-lewis)
- [8. Cargas formales](#8-cargas-formales)
- [9. Resonancia](#9-resonancia)
- [10. Geometría molecular — TRePEV](#10-geometría-molecular--trepev)
- [11. Errores típicos](#11-errores-típicos)
- [12. Modelos atómicos — línea histórica](#12-modelos-atómicos--línea-histórica)

---

## 0. Constantes y unidades

| Constante | Símbolo | Valor |
|---|---|---|
| Velocidad de la luz | c | 3×10⁸ m/s |
| Constante de Planck | h | 6,626×10⁻³⁴ J·s |
| Carga elemental | e | 1,6×10⁻¹⁹ C |
| Masa del protón | mₚ | 1,673×10⁻²⁴ g ≈ 1 uma |
| Masa del neutrón | mₙ | 1,675×10⁻²⁴ g ≈ 1 uma |
| Masa del electrón | mₑ | 9,1×10⁻²⁸ g ≈ 0 |
| 1 uma | | 1,66×10⁻²⁴ g = masa(¹²C)/12 |

**Prefijos y escalas**

| Unidad | Equivalencia |
|---|---|
| 1 nm | 10⁻⁹ m = 10 Å |
| 1 Å | 10⁻¹⁰ m = 0,1 nm |
| 1 µm | 10⁻⁶ m = 1000 nm |

**Tamaños de referencia:** átomo ≈ 0,5–5 Å · molécula chica (CO, H₂O) ≈ 0,5 nm · ADN (ancho) ≈ 2 nm · célula ≈ 5–50 µm

**Relación átomo/núcleo:** átomo 10⁻⁸ cm / núcleo 10⁻¹³ cm = **10⁵** → el átomo es 100.000 veces más grande que su núcleo → **es casi todo vacío**.

**mₚ / mₑ ≈ 1840** → toda la masa está en el núcleo.

---

## 1. Estructura atómica

| Partícula | Dónde | Carga | Masa |
|---|---|---|---|
| **protón** | núcleo | +1 | ≈1 uma |
| **neutrón** | núcleo | 0 | ≈1 uma |
| **electrón** | orbitales | −1 | ≈0 (1/1840) |

$$Z = \text{n° atómico} = \text{n° de PROTONES} \qquad A = \text{n° másico} = Z + N$$

- **Z define el elemento.** Si cambia Z, cambia el elemento.
- **Átomo neutro:** n° electrones = Z
- **Isótopos:** mismo Z, distinto N (distinta masa). Por eso las masas atómicas son decimales.
- El núcleo se mantiene unido por la **fuerza nuclear fuerte** (no eléctrica ni gravitatoria; muy intensa, de cortísimo alcance).

---

## 2. Luz y energía cuantizada

$$\boxed{c = \lambda\,\nu} \qquad \boxed{E = h\nu = \frac{hc}{\lambda}} \qquad \boxed{\Delta E = h\nu}$$

| Magnitud | Símbolo | Unidad |
|---|---|---|
| Longitud de onda | λ | m (o nm) |
| Frecuencia | ν | Hz = 1/s |
| Energía | E | J |

**Reglas de lectura:**

$$\lambda \downarrow \;\Longleftrightarrow\; \nu \uparrow \;\Longleftrightarrow\; E \uparrow$$

> **Azul (400 nm) tiene MÁS energía que rojo (700 nm).**

**Espectro EM** (de más a menos energía): γ → Rayos X → UV → **VISIBLE (400–700 nm)** → IR → Microondas → Radio

**Visible:** 400 nm azul · 500 nm verde · 600 nm amarillo/naranja · 700 nm rojo

### Absorción y emisión

| | Qué pasa | Energía |
|---|---|---|
| **Absorción** | e⁻ sube de nivel | El átomo **toma** energía |
| **Emisión** | e⁻ baja de nivel | El átomo **libera** un fotón |

**Espectro de líneas:** un gas excitado emite **sólo ciertas λ** (rayas discretas), no un continuo. Es la **prueba experimental de que la energía está cuantizada**.

**Cada elemento tiene un espectro único** → se usa como "huella digital" para identificar elementos (espectroscopía).

**Analogía de la escalera:** el e⁻ sólo puede estar en escalones (niveles), nunca en el medio. Al bajar devuelve exactamente la energía que le costó subir → fotón de λ definida → raya espectral.

---

## 3. Números cuánticos

**Cada electrón tiene un juego ÚNICO de 4 números cuánticos (n, ℓ, mℓ, mₛ).**

| N° | Símbolo | Valores permitidos | Determina |
|---|---|---|---|
| Principal | **n** | 1, 2, 3, … (nunca 0) | **ENERGÍA** / nivel / tamaño |
| Momento angular | **ℓ** | **0 a n−1** | **FORMA** (subnivel) |
| Magnético | **mℓ** | **−ℓ a +ℓ** | **ORIENTACIÓN** |
| Spin | **mₛ** | **+½ o −½** | Giro del e⁻ |

### Tabla maestra (memorizar)

| ℓ | Subnivel | mℓ | **Orbitales (2ℓ+1)** | **e⁻ máx** | Existe desde |
|---|---|---|---|---|---|
| 0 | **s** | 0 | **1** | **2** | n ≥ 1 |
| 1 | **p** | −1,0,+1 | **3** | **6** | n ≥ 2 |
| 2 | **d** | −2…+2 | **5** | **10** | n ≥ 3 |
| 3 | **f** | −3…+3 | **7** | **14** | n ≥ 4 |

**Por capa:** orbitales = **n²** · electrones = **2n²** → 2, 8, 18, 32

⚠️ **NO existen:** 1p, 2d, 3f (violan ℓ ≤ n−1).

### Formas

- **s** → esfera (1 orientación)
- **p** → doble lóbulo sobre cada eje: pₓ, p_y, p_z (3 orientaciones, perpendiculares)
- **d** → 4 tréboles + 1 con anillo (d_z²) — metales de transición
- **f** → formas complejas — lantánidos y actínidos

**Orbital ≠ Órbita.** Órbita = trayectoria (Bohr, obsoleto). **Orbital = región de probabilidad** (Ψ², ~90%).

**Orbitales degenerados** = misma energía (los 3 p entre sí, los 5 d entre sí).

---

## 4. Configuración electrónica (CE)

### Las 3 reglas

| # | Regla | Enunciado |
|---|---|---|
| **1** | **Aufbau** | Se llenan **de menor a mayor energía** (regla de las diagonales) |
| **2** | **Pauli** | Máximo **2 e⁻ por orbital**, con **spines opuestos ↑↓**. Se cumple **SIEMPRE** |
| **3** | **Hund** | En orbitales **degenerados**: primero **uno en cada uno** (↑ ↑ ↑), después se aparea |

Dentro de un nivel: **Eₛ < E_p < E_d < E_f**

### Regla de las diagonales

```
1s
2s  2p
3s  3p  3d
4s  4p  4d  4f
5s  5p  5d  5f
6s  6p  6d
7s  7p
```
Diagonales de arriba-derecha → abajo-izquierda:

$$\boxed{1s\;2s\;2p\;3s\;3p\;\mathbf{4s\;3d}\;4p\;5s\;4d\;5p\;6s\;4f\;5d\;6p\;7s\;5f\;6d\;7p}$$

⚠️ **El 4s va ANTES que el 3d** (por **apantallamiento**: los e⁻ internos escudan la carga nuclear, y el 4s penetra más que el 3d).

### Método (5 pasos)

1. Buscá **Z** en la tabla → si es neutro, ésos son los electrones.
2. Si es ion: **e⁻ = Z − carga**.
3. Recorré las diagonales llenando: s→2, p→6, d→10, f→14.
4. Parás cuando se acaban los electrones (el último subnivel puede quedar incompleto).
5. ✅ **VERIFICÁ: la suma de los superíndices debe dar el n° de electrones.**

### Las 3 formas de escribir (ejemplo Br, Z=35)

| Forma | Escritura |
|---|---|
| **CE completa** | 1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d¹⁰ 4p⁵ |
| **CE abreviada** (gas noble) | **[Ar]** 4s² 3d¹⁰ 4p⁵ |
| **CEE** (externa / valencia) | **4s² 4p⁵** → 7 e⁻ de valencia |

⚠️ **La CEE lleva sólo los e⁻ de MAYOR n.** El 3d¹⁰ **no** entra en la CEE del Br (n=3 < 4).

**Gases nobles de referencia:** [He]=2 · [Ne]=10 · [Ar]=18 · [Kr]=36 · [Xe]=54 · [Rn]=86

### Estado fundamental vs excitado

- **Fundamental:** cumple las 3 reglas → mínima energía. Es la que se pide por defecto.
- **Excitado:** cualquier otra distribución (un e⁻ "subido"). **Pauli igual se cumple siempre.**

### 2° período (para verificar Hund)

| Elem | Z | CE | 2p |
|---|---|---|---|
| Li | 3 | [He]2s¹ | |
| Be | 4 | [He]2s² | |
| B | 5 | [He]2s²2p¹ | ↑ _ _ |
| C | 6 | [He]2s²2p² | ↑ ↑ _ |
| N | 7 | [He]2s²2p³ | ↑ ↑ ↑ ← máx. desapareados |
| O | 8 | [He]2s²2p⁴ | ↑↓ ↑ ↑ ← recién acá aparea |
| F | 9 | [He]2s²2p⁵ | ↑↓ ↑↓ ↑ |
| Ne | 10 | [He]2s²2p⁶ | ↑↓ ↑↓ ↑↓ ← **octeto** |

---

## 5. Iones

| Ion | Carga | Cómo se forma |
|---|---|---|
| **CATIÓN** | **+** | **PIERDE** electrones |
| **ANIÓN** | **−** | **GANA** electrones |

$$\boxed{\text{n° de } e^- = Z - \text{carga}}$$

**Ejemplos (Li, Z=3 — siempre 3 protones):**

| Especie | e⁻ | CE |
|---|---|---|
| Li⁺ | 3−(+1) = 2 | 1s² ← igual al He |
| Li | 3 | 1s² 2s¹ |
| Li⁻ | 3−(−1) = 4 | 1s² 2s² |

⚠️ **El n° de PROTONES nunca cambia.** Sólo cambian los electrones.

⚠️ En **metales de transición**, al formar cationes se sacan primero los e⁻ de **mayor n** (el 4s antes que el 3d), aunque el 4s se haya llenado primero.
Ej.: Fe (Z=26) = [Ar]4s²3d⁶ → **Fe²⁺ = [Ar]3d⁶** (se van los 4s).

---

## 6. Tabla periódica y valencia

> ### 🔑 **N° de grupo (I a VIII) = cantidad de electrones de valencia**

| Grupo | N° IUPAC | Nombre | CEE | e⁻ val. | Tiende a |
|---|---|---|---|---|---|
| **I** | 1 | Alcalinos | ns¹ | 1 | ceder 1 → **+1** |
| **II** | 2 | Alcalinotérreos | ns² | 2 | ceder 2 → **+2** |
| **III** | 13 | Térreos (B, Al) | ns²np¹ | 3 | ceder 3 → **+3** |
| **IV** | 14 | Carbonoideos | ns²np² | 4 | compartir |
| **V** | 15 | Nitrogenoideos | ns²np³ | 5 | captar 3 → **−3** |
| **VI** | 16 | Anfígenos | ns²np⁴ | 6 | captar 2 → **−2** |
| **VII** | 17 | Halógenos | ns²np⁵ | 7 | captar 1 → **−1** |
| **VIII** | 18 | Gases nobles | ns²np⁶ | 8 | **nada (inertes)** |

**Con numeración IUPAC (1–18):**
- Bloque **s** (grupos 1–2): e⁻ valencia = **G**
- Bloque **p** (grupos 13–18): e⁻ valencia = **G − 10**

**Bloques = subnivel que se está llenando:**

| Bloque | Subnivel | Columnas |
|---|---|---|
| s | ns | 2 |
| p | np | 6 |
| d | (n−1)d | 10 |
| f | (n−2)f | 14 |

**Reglas:**
- **Misma columna (grupo)** → misma CEE → **misma química**
- **Misma fila (período)** → mismo n de la capa externa

### 💡 La idea central de toda la materia

> **Las configuraciones de capa llena (`ns² np⁶`, gas noble) son estables.**
> **Todo átomo tiende a alcanzarlas**, y para eso: **cede** e⁻ (→ catión), **capta** e⁻ (→ anión) o los **comparte** (→ enlace covalente).
> **Sólo los electrones de valencia (capa externa) hacen química.**

---

## 7. Estructuras de Lewis

**Teoría de Lewis:** *"los átomos COMparten PAres de electrones de VALENcia"* (**CO-VALENTE**).

### Símbolo de Lewis

Símbolo del elemento + **un punto por cada electrón de valencia**, colocados alrededor (primero uno por lado, después se aparean).

```
Li·   ·Be·   ·B·   ·C·   ·N:   :O:   :F:   :Ne:
                    ·      ·     ··    ··    ··
CEE: 2s¹  2s²  2s²2p¹ 2s²2p² 2s²2p³ 2s²2p⁴ 2s²2p⁵ 2s²2p⁶
```

### Regla del octeto

> **Cada átomo busca tener 8 electrones de valencia** (`ns² np⁶`), contando **pares de enlace + pares libres**.
>
> **8 electrones = 4 pares** alrededor de cada átomo.

**Excepciones (hay que saberlas):**

| Caso | Qué pasa | Ejemplos |
|---|---|---|
| **H** | Forma **dueto** (2 e⁻, 1 par) | H₂, H₂O, NH₃ |
| **Deficientes** (grupo 13) | Menos de 8 e⁻ | **BF₃**, BeCl₂, AlCl₃ |
| **Octeto expandido** | Más de 8 e⁻ (usa orbitales d) — **sólo período ≥ 3** | **SF₄**, SF₆, PCl₅, XeF₄ |
| **N° impar de e⁻** | Queda un e⁻ desapareado — **nunca cumple octeto** | **NO** (11 e⁻) |

### Vocabulario

- **Par de enlace:** par de e⁻ compartido entre dos átomos → se dibuja como **línea** (fórmula desarrollada)
- **Par libre / no compartido / solitario:** par de e⁻ que queda en un solo átomo → se dibuja como **dos puntos**
- **Enlace simple** = 1 par compartido (F—F)
- **Enlace doble** = 2 pares compartidos (O=O)
- **Enlace triple** = 3 pares compartidos (N≡N)

### 📝 MÉTODO PASO A PASO

**Paso 1 — Contar electrones de valencia totales**

$$e^-_{\text{totales}} = \sum (\text{e}^- \text{de valencia de cada átomo}) \;+\; \text{carga negativa} \;-\; \text{carga positiva}$$

- **Anión** (carga −) → **SUMÁS** 1 e⁻ por cada carga negativa
- **Catión** (carga +) → **RESTÁS** 1 e⁻ por cada carga positiva

$$\text{pares} = \frac{e^-_{\text{totales}}}{2}$$

*(si el total es impar → hay ⌊n/2⌋ pares + 1 e⁻ desapareado)*

**Paso 2 — Elegir el átomo central**

- El **menos electronegativo** / **más electropositivo** (al que le faltan más electrones)
- ⚠️ **H y F SIEMPRE van en la periferia**, nunca en el centro
- El resto se coloca alrededor

**Paso 3 — Formar las uniones simples**

Una línea (= 1 par) entre el central y cada periférico. **Descontá** los pares usados.

**Paso 4 — Completar el octeto de los átomos PERIFÉRICOS**

Poné pares libres (dos puntitos) alrededor de cada periférico hasta llegar a 8 e⁻. (El H ya está lleno con su enlace.) **Descontá.**

**Paso 5 — Los pares que sobren van al átomo CENTRAL**

**Paso 6 — Verificar el octeto del CENTRAL**

⚠️ **Si al central le falta para el octeto:** pasá un **par libre de un periférico** (el menos electronegativo, si hay opciones) a **doble o triple enlace** con el central.

**Paso 7 — Resonancia**

Si hay más de una estructura válida (que difieren sólo en dónde están los electrones, no en la conectividad), dibujá **todas**, unidas por **flechas de doble punta ↔**.

**Paso 8 — Iones**

Encerrar toda la estructura entre **corchetes** con la **carga como superíndice** afuera.

### ✅ Ejemplos resueltos

**NH₃ (amoníaco)**
| Paso | |
|---|---|
| Central | **N** (H siempre periférico) |
| e⁻ valencia | N = 5, H = 1×3 = 3 → **8 e⁻ = 4 pares** |
| Uniones | 3 enlaces N—H → usa 3 pares, **queda 1** |
| Periféricos | H completos (dueto) ✓ |
| Central | N tiene 6 e⁻ → le falta 1 par → **se le pone el par que sobra** |
| **Resultado** | H—N(:)—H con H abajo → **N con 1 par libre**, octeto ✓ |

**SO₃²⁻ (ion sulfito)**
| Paso | |
|---|---|
| Central | **S** |
| e⁻ valencia | S = 6, O = 6×3 = 18, **carga 2− → +2** |
| Total | 6 + 18 + 2 = **26 e⁻ = 13 pares** |
| Uniones | 3 enlaces S—O → usa 3, **quedan 10** |
| Reparto | 3 pares libres en cada O (9) + 1 par al S |
| **Resultado** | Todos con octeto ✓ → **entre corchetes con 2−** |

**SO₂ (dióxido de azufre)**
| Paso | |
|---|---|
| Central | **S** |
| e⁻ valencia | S = 6, O = 6×2 = 12 → **18 e⁻ = 9 pares** |
| Uniones | 2 enlaces → **quedan 7** |
| Periféricos | 3 pares en cada O (6) → **queda 1** al S |
| Chequeo | S tiene sólo 6 e⁻ ❌ |
| **Corrección** | Un par libre de un O pasa a **doble enlace** → **O=S—O** ✓ |
| Extra | Tiene **resonancia** (el doble puede estar de cualquier lado) |

**BF₃ (excepción — deficiente)**
| | |
|---|---|
| e⁻ valencia | B = 3, F = 7×3 = 21 → **24 e⁻ = 12 pares** |
| Resultado | 3 enlaces B—F + 3 pares libres en cada F |
| **B queda con 6 e⁻** | ❌ octeto — **pero ésta es la estructura correcta** |
| Por qué | El B es **deficiente de electrones** (ácido de Lewis). Las cargas formales desaconsejan el doble enlace |

**SF₄ (excepción — octeto expandido)**
| | |
|---|---|
| e⁻ valencia | S = 6, F = 7×4 = 28 → **34 e⁻ = 17 pares** |
| Resultado | 4 enlaces S—F + 3 pares en cada F + **1 par libre en el S** |
| **S queda con 10 e⁻** | Válido: el S es del **período 3**, puede expandir el octeto usando orbitales d |

**NO (n° impar)**
| | |
|---|---|
| e⁻ valencia | N = 5, O = 6 → **11 e⁻ = 5 pares + 1 e⁻ suelto** |
| Consecuencia | **Nunca se puede cumplir el octeto en todos los átomos** |

---

## 8. Cargas formales

**Para qué sirve:** cuando hay varias estructuras de Lewis posibles, decidir **cuál es la más representativa**.

$$\boxed{CF = e^-_{\text{valencia}} - e^-_{\text{libres}} - N_{\text{enlaces}}}$$

donde:
- **e⁻ valencia** = los del átomo aislado (= n° de grupo)
- **e⁻ libres** = electrones en pares no compartidos (se cuentan **de a uno**: un par libre = 2)
- **N enlaces** = cantidad de **enlaces** (líneas) que salen del átomo — un doble cuenta 2, un triple cuenta 3

### Reglas de control

| # | Regla |
|---|---|
| 1 | En **moléculas neutras**, la suma de todas las CF debe dar **0** |
| 2 | En **iones**, la suma de las CF debe dar **la carga del ion** |

### Reglas para elegir la mejor estructura

| # | Criterio |
|---|---|
| 3 | **Mínima separación de cargas** (CF lo más cercanas a 0 posible) |
| 4 | Las cargas **negativas** van sobre los átomos **más electronegativos** |
| 5 | Las cargas **positivas** van sobre los átomos **menos electronegativos** |
| 6 | Cargas del **mismo signo en átomos adyacentes** son poco probables |

### Ejemplo resuelto: ion tiocianato SCN⁻

Tres estructuras posibles:

| Átomo | (a) N≡C—S | (b) N=C=S | (c) N—C≡S |
|---|---|---|---|
| **N** | 5−6−1 = **−2** | 5−4−2 = **−1** | 5−2−3 = **0** |
| **C** | 4−0−4 = **0** | 4−0−4 = **0** | 4−0−4 = **0** |
| **S** | 6−2−3 = **+1** | 6−4−2 = **0** | 6−6−1 = **−1** |
| **Suma** | −1 ✓ | −1 ✓ | −1 ✓ |

**¿Cuál gana? La (b)** — porque:
- Tiene la **menor separación de cargas** (regla 3): sólo una CF distinta de cero.
- La carga negativa está sobre el **N**, que es más electronegativo que el C y el S (regla 4).

---

## 9. Resonancia

> **Cuando una molécula se puede describir con varias estructuras de Lewis que difieren SÓLO en la ubicación de los electrones (NO en la conectividad de los átomos), esas estructuras se llaman ESTRUCTURAS DE RESONANCIA.**

**Cómo se escriben:** todas dibujadas, unidas por **flechas de doble punta ↔**, y si es un ion, cada una entre corchetes con su carga.

**Qué es realmente:** la molécula real **NO** oscila entre las estructuras. La molécula real es un **HÍBRIDO DE RESONANCIA** — un promedio ponderado, una única especie intermedia. Las estructuras individuales son una limitación del modelo de Lewis, no algo que exista físicamente.

**Cuál pesa más:** la que tenga las **cargas formales más bajas** (ver sección 8).

**Ejemplos del curso:**

- **NO₃⁻ (ion nitrato):** 3 estructuras equivalentes (el doble enlace N=O rota entre los tres oxígenos). Los tres enlaces N—O son en realidad **idénticos**, intermedios entre simple y doble.
- **SO₂:** 2 estructuras (O=S—O ↔ O—S=O).
- **SCN⁻:** 3 estructuras (ver sección 8).

**Cómo se pasa de una a otra:** moviendo un **par libre** de un átomo periférico para formar un enlace múltiple, y "empujando" el par del enlace múltiple hacia el otro átomo (las flechas curvas ↷ indican el movimiento de pares de electrones).

---

## 10. Geometría molecular — TRePEV

**TRePEV = Teoría de Repulsión de Pares de Electrones de Valencia** (VSEPR en inglés).

> **Los pares de electrones de valencia alrededor del átomo central se REPELEN entre sí, y se ubican lo más ALEJADOS posible para minimizar esa repulsión.** Eso determina la geometría.

### Postulados

1. Se cuentan los **grupos electrónicos** alrededor del átomo central (pares libres **+** enlaces).
2. Se repelen → se orientan a la **máxima distancia posible** → máxima estabilidad.
3. Los **pares libres repelen MÁS** que los pares de enlace → **ocupan más espacio** → **cierran los ángulos**.
4. Un enlace **simple, doble o triple cuenta como UN SOLO grupo** a los fines de la geometría.

### 📝 Método

1. Dibujá la **estructura de Lewis**.
2. Contá los **grupos electrónicos** alrededor del central (enlaces múltiples = 1 grupo).
3. Con ese número obtenés la **GEOMETRÍA ELECTRÓNICA**.
4. **Ignorá** los pares libres (mirá sólo dónde están los átomos) → **GEOMETRÍA MOLECULAR**.

> ⚠️ **La distinción geometría ELECTRÓNICA vs MOLECULAR es lo que más se pregunta.**
> **Electrónica** = disposición de **todos** los grupos (incluye pares libres).
> **Molecular** = forma que dibujan **sólo los átomos**.
> **Si NO hay pares libres, las dos coinciden.**

### Tabla A — SIN pares libres (electrónica = molecular)

| Grupos | Geometría (elec. y mol.) | Ángulo | Ejemplos |
|---|---|---|---|
| **2** | **Lineal** | 180° | BeCl₂, HgCl₂, CO₂ |
| **3** | **Plana triangular** (trigonal plana) | 120° | BF₃ |
| **4** | **Tetraédrica** | 109,5° | CH₄, NH₄⁺, CCl₄ |
| **5** | **Bipiramidal trigonal** | 90° y 120° | PCl₅ |
| **6** | **Octaédrica** | 90° | SF₆ |

### Tabla B — CON pares libres

Notación: **A** = central · **B** = átomo unido · **E** = par libre

| Clase | Grupos totales | Enlazantes | Libres | Geom. ELECTRÓNICA | **Geom. MOLECULAR** | Ejemplo |
|---|---|---|---|---|---|---|
| **AB₂E** | 3 | 2 | 1 | Plana trigonal | **Angular** | SO₂ |
| **AB₃E** | 4 | 3 | 1 | Tetraédrica | **Piramidal trigonal** | NH₃ |
| **AB₂E₂** | 4 | 2 | 2 | Tetraédrica | **Angular** | H₂O |
| **AB₄E** | 5 | 4 | 1 | Bipiramidal trigonal | **Sube y baja** (balancín) | SF₄ |
| **AB₃E₂** | 5 | 3 | 2 | Bipiramidal trigonal | **Forma de T** | ClF₃ |
| **AB₂E₃** | 5 | 2 | 3 | Bipiramidal trigonal | **Lineal** | I₃⁻ |
| **AB₅E** | 6 | 5 | 1 | Octaédrica | **Pirámide cuadrada** | BrF₅ |
| **AB₄E₂** | 6 | 4 | 2 | Octaédrica | **Plana cuadrada** | XeF₄ |

### 🎯 El ejemplo que hay que saber sí o sí: CH₄ vs NH₃ vs H₂O

| | **CH₄** | **NH₃** | **H₂O** |
|---|---|---|---|
| Átomos unidos | 4 H | 3 H | 2 H |
| Pares libres | 0 | 1 | 2 |
| **Grupos totales** | **4** | **4** | **4** |
| **Geom. ELECTRÓNICA** | **Tetraédrica** | **Tetraédrica** | **Tetraédrica** |
| **Geom. MOLECULAR** | **Tetraédrica** | **Piramidal trigonal** | **Angular** |
| **Ángulo** | **109,5°** | **107,3°** | **104,5°** |

**Las tres tienen la MISMA geometría electrónica (tetraédrica) pero DISTINTA geometría molecular.**

**Por qué se achica el ángulo:** cada par libre que se agrega repele más fuerte que un enlace y **comprime** los ángulos restantes. Por eso: 109,5° (0 pares libres) → 107,3° (1 par) → 104,5° (2 pares).

---

## 11. Errores típicos

| ❌ Error | ✅ Correcto |
|---|---|
| Decir "órbita" | **Orbital** (región de probabilidad, no trayectoria) |
| Escribir 1p, 2d, 3f | No existen: **ℓ ≤ n−1** |
| Poner 3d antes que 4s | **4s se llena primero** (diagonales) |
| Meter el 3d¹⁰ en la CEE del Br | La **CEE lleva sólo el n MÁXIMO** |
| Cambiar Z al hacer un ion | **Z (protones) NUNCA cambia**; cambian los electrones |
| Restar e⁻ para un anión | Anión = **SUMA** e⁻ · Catión = **RESTA** e⁻ |
| Aparear en el 2p antes de llenar los 3 | **Hund**: primero uno en cada orbital |
| Contar un doble enlace como 2 grupos en TRePEV | Enlace múltiple = **1 solo grupo** |
| Confundir geometría electrónica con molecular | **Molecular ignora los pares libres** |
| Poner H o F como átomo central | **H y F SIEMPRE periféricos** |
| Forzar el octeto en BF₃ | El **B es deficiente**: se queda con 6 e⁻ |
| Olvidar los corchetes y la carga en un ion | **[ … ]²⁻** |
| No verificar la suma de superíndices en la CE | **Debe dar el n° de electrones** |
| Pensar que la resonancia oscila | Es un **híbrido**, una sola especie promedio |

---

## 12. Modelos atómicos — línea histórica

| Año | Quién | Aporte | Falla |
|---|---|---|---|
| ~450 a.C. | Demócrito | Idea de "átomo" (indivisible) | Filosófica, sin evidencia |
| **1803** | **Dalton** | Teoría atómica con evidencia | Cree el átomo indivisible; ignora isótopos |
| **1897** | **Thomson** | **Electrón** (tubo de rayos catódicos) | — |
| 1904 | Thomson | Modelo "budín de pasas" | Refutado por Rutherford |
| **1900** | **Planck** | Energía **cuantizada** (E = hν) | — |
| **1911** | **Rutherford** | **Núcleo** (lámina de oro); átomo casi vacío | El e⁻ debería caer; no explica espectros |
| 1919 | Rutherford | **Protón** | — |
| **1913** | **Bohr** | **Niveles cuantizados**; explica el espectro del H | **Sólo sirve para el H**; no explica intensidades |
| **1924** | **de Broglie** | **Dualidad onda-partícula** (λ = h/mv) | — |
| **1926** | **Heisenberg** | **Principio de incertidumbre** | Elimina el concepto de órbita |
| **1926** | **Schrödinger** | Ecuación de onda → **orbitales** (Ψ²) | **MODELO ACTUAL** ✓ |
| 1932 | Chadwick | **Neutrón** | — |

### Experimentos clave

| Experimento | Quién | Qué demostró |
|---|---|---|
| **Tubo de rayos catódicos** | Thomson | Existen partículas negativas (electrones) en toda la materia |
| **Lámina de oro** | Rutherford | El átomo es casi vacío con un núcleo denso y positivo |
| **Espectros de emisión** | — | La energía del electrón está **cuantizada** |
| **Difracción de electrones** | Davisson-Germer | El electrón se comporta como **onda** |

---

## 📌 Fórmulas — todas juntas

$$c = \lambda\nu \qquad E = h\nu = \frac{hc}{\lambda} \qquad \Delta E = h\nu \qquad \lambda = \frac{h}{mv}$$

$$A = Z + N \qquad e^- = Z - \text{carga} \qquad \Delta x\cdot\Delta p \geq \frac{h}{4\pi}$$

$$\text{orbitales por subnivel} = 2\ell+1 \qquad \text{orbitales por capa} = n^2 \qquad e^-_{\text{máx por capa}} = 2n^2$$

$$CF = e^-_{\text{valencia}} - e^-_{\text{libres}} - N_{\text{enlaces}}$$

$$e^-_{\text{Lewis}} = \textstyle\sum e^-_{\text{valencia}} + \text{carga}^- - \text{carga}^+ \qquad \text{pares} = \frac{e^-_{\text{totales}}}{2}$$
