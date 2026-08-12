# 🧪 MACHETE — Química General (ECyT / UNSAM · 2C 2026)

> Resumen operativo de toda la materia. Sólo lo que hay que saber para resolver.
> Para la explicación desarrollada diapositiva por diapositiva:
> `Clase1/Clase1-Explicacion-Completa.md` · `Clase2/Clase2-Explicacion-Completa.md` · `Clase3/Clase3-Explicacion-Completa.md` · `Extra/Nomenclatura-Explicacion-Completa.md`

**Contenido actual:** Clase 1 (Átomo y configuración electrónica) · Clase 2 (Uniones químicas, Lewis y geometría) · **Clase 3 (Polaridad, geometría y fuerzas intermoleculares)** · Nomenclatura (nº de oxidación y nombres) · Series 1 y 2 (métodos de cálculo)

> **Series resueltas:** `Practica/Serie1-Resuelta.md` · `Practica/Serie2-Resuelta.md`
> **Profundizaciones:** `Clase1/Clase1-Espectroscopia-Profundizacion.md` · `Clase1/Clase1-TablaPeriodica-Profundizacion.md` · `Clase2/Clase2-TiposDeUnion-Profundizacion.md`

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
- [11. Polaridad y momento dipolar](#11-polaridad-y-momento-dipolar)
- [12. Interacciones intermoleculares](#12-interacciones-intermoleculares)
- [13. Estados de agregación y propiedades físicas](#13-estados-de-agregación-y-propiedades-físicas)
- [14. Número de oxidación](#14-número-de-oxidación)
- [15. Nomenclatura inorgánica](#15-nomenclatura-inorgánica)
- [16. Errores típicos](#16-errores-típicos)
- [17. Modelos atómicos — línea histórica](#17-modelos-atómicos--línea-histórica)

---

## 🗺️ La RUTA DE ESTUDIO (el mapa de toda la materia)

$$\text{Átomos} \Rightarrow \text{Molécula} \Rightarrow \text{Lewis} \Rightarrow \text{TRePEV} \Rightarrow \boxed{\text{POLAR o NO POLAR}} \Rightarrow \text{Fuerzas intermoleculares} \Rightarrow \boxed{\text{T}_f,\ \text{T}_{eb},\ \text{estado}}$$

| Paso | Herramienta | Sección |
|---|---|---|
| 1. Átomos → configuración electrónica | Diagonales | **4** |
| 2. ¿Qué tipo de enlace? | ΔEN + metal/no metal + Katelaar | **7** |
| 3. Estructura de Lewis | Método de 8 pasos | **7** |
| 4. Geometría electrónica y molecular | TRePEV | **10** |
| 5. ¿Polar o no polar? | Suma vectorial de μ | **11** |
| 6. ¿Qué fuerza intermolecular actúa? | Matriz Q/μ/α | **12** |
| 7. T_f, T_eb, estado, solubilidad | E_c vs E_p | **13** |

⚠️ **Cada eslabón necesita el anterior. Éste es el formato del ejercicio integrador del parcial.**

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
| **N° de Avogadro** | **N_A** | **6,022×10²³ 1/mol** |
| 1 uma | | 1,66×10⁻²⁴ g = masa(¹²C)/12 |
| **h·c** (producto útil) | | **1,989×10⁻²⁵ J·m** |

**Conversiones que aparecen en la práctica**

| De | A | Cómo |
|---|---|---|
| Wh | J | **× 3600** (1 Wh = 3600 J) |
| J/fotón | J/mol | **× N_A** |
| nm | m | × 10⁻⁹ |
| Å | m | × 10⁻¹⁰ |

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

### ⚠️ Energía POR MOL (lo que casi siempre piden)

$$\boxed{E_{\text{mol}} = \frac{hc}{\lambda}\cdot N_A}$$

**Método:**
1. λ a **metros** (nm → ×10⁻⁹)
2. E de **un fotón**: E = hc/λ (da ~10⁻¹⁹ J)
3. **× N_A** → J/mol
4. **/1000** → kJ/mol

**Orden de magnitud para chequear:** en el visible, E_fotón ≈ 3–5×10⁻¹⁹ J y E_mol ≈ **180–300 kJ/mol**. Si te da muy distinto, revisá las unidades de λ.

**Valores de referencia (salen en la Serie 1):**

| λ | Color | E_mol |
|---|---|---|
| 656 nm | rojo (H, n=3→2) | 182,4 kJ/mol |
| 589 nm | amarillo (Na, 3p→3s) | 203,3 kJ/mol |
| 486 nm | verde (H, n=4→2) | 246,4 kJ/mol |

### Comparar transiciones (sin calcular)

Si todas las transiciones **terminan en el mismo nivel**, manda el nivel de partida:

$$n_{\text{inicial}} \uparrow \;\Rightarrow\; \Delta E \uparrow \;\Rightarrow\; \lambda \downarrow$$

⚠️ En el **átomo de hidrógeno** la energía depende **sólo de n** (no de ℓ) → 6s, 6p y 6d tienen la misma energía. En polielectrónicos **no**.

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

### 🔗 ISOELECTRÓNICOS

> **Dos especies son isoelectrónicas cuando tienen la MISMA cantidad de electrones** (y por lo tanto **idéntica CE**), aunque tengan **distinto Z**.

**Método:** contar electrones con `e⁻ = Z − carga` y comparar.

⚠️ **Cuidado con el signo al despejar Z:**

$$Z = e^- + \text{carga}$$

- Ion **negativo** → el átomo neutro tiene **MENOS** electrones que el ion (X³⁻ con 18 e⁻ → Z = 15)
- Ion **positivo** → el átomo neutro tiene **MÁS** electrones que el ion (M⁺ con 18 e⁻ → Z = 19)

**Serie isoelectrónica con Ar (18 e⁻):** S²⁻ · Cl⁻ · **Ar** · K⁺ · Ca²⁺ · Sc³⁺
**Serie isoelectrónica con Kr (36 e⁻):** Br⁻ · **Kr** · Rb⁺ · Sr²⁺
**Serie isoelectrónica con Ne (10 e⁻):** N³⁻ · O²⁻ · F⁻ · **Ne** · Na⁺ · Mg²⁺ · Al³⁺

⚠️ Isoelectrónico **NO** significa "mismo elemento". K⁺, Ar y S²⁻ tienen 19, 18 y 16 **protones**.

### Ion más estable — criterio

| Tipo de elemento | Criterio |
|---|---|
| **Representativos** (s y p) | El que alcanza la **capa llena del gas noble más cercano** cediendo/captando **la menor cantidad** de e⁻. **Uno solo por elemento.** |
| **Transición** (d) | **NO sirve la CEE.** Forman **varios** estados de oxidación. Se sacan primero los **ns**, después los **(n−1)d**. Son extra estables las configuraciones **d⁵** y **d¹⁰** |

**Ejemplos:**

| Elemento | Ion(es) estable(s) | CE del ion | Por qué |
|---|---|---|---|
| Ba (Z=56) | **Ba²⁺** | [Xe] | capa llena |
| F (Z=9) | **F⁻** | [Ne] | octeto |
| Al (Z=13) | **Al³⁺** | [Ne] | capa llena |
| S (Z=16) | **S²⁻** | [Ar] | octeto |
| Fe (Z=26) | **Fe²⁺** y **Fe³⁺** | [Ar]3d⁶ · **[Ar]3d⁵** | Fe³⁺ tiene **d⁵** (semicapa llena) |
| Zn (Z=30) | **Zn²⁺** | [Ar]3d¹⁰ | **d¹⁰** (capa d llena) |
| Pb (Z=82) | **Pb²⁺** (> Pb⁴⁺) | [Xe]4f¹⁴5d¹⁰6s² | **efecto del par inerte**: el 6s² cuesta arrancarlo |

### ⚠️ Excepciones a la regla de las diagonales

Las configuraciones **d⁵** y **d¹⁰** tienen estabilidad extra: si se alcanzan promoviendo **un** electrón del ns al (n−1)d, el átomo lo hace.

| Elemento | Z | Esperado | **Real** |
|---|---|---|---|
| **Cr** | 24 | [Ar] 4s² 3d⁴ | **[Ar] 3d⁵ 4s¹** |
| **Cu** | 29 | [Ar] 4s² 3d⁹ | **[Ar] 3d¹⁰ 4s¹** |

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

### 📝 Cómo sacar PERÍODO y GRUPO de una CE

| Dato | Cómo |
|---|---|
| **Z / elemento** | **Sumar TODOS los superíndices**, incluido el gas noble del corchete |
| **Período** | El **n MÁXIMO** de la configuración |
| **Grupo — representativos** (s, p) | Cantidad de e⁻ de la **CEE** |
| **Grupo — transición** (d) | ⚠️ **e⁻ del ns + e⁻ del (n−1)d** (¡NO la CEE sola!) |

**Ejemplos:**

| CE | Z | Elemento | Período | Grupo |
|---|---|---|---|---|
| [Xe] 4f¹⁴ 5d¹⁰ 6s² 6p² | 82 | **Pb** | 6 | 14 (CEE = 6s²6p² → 4 e⁻) |
| [Ar] 3d⁵ 4s² | 25 | **Mn** | 4 | 7 (2+5, **transición**) |
| [Ar] 4s² 3d² | 22 | **Ti** | 4 | 4 (2+2, **transición**) |
| [Kr] 4d¹⁰ 5s² 5p⁶ | 54 | **Xe** | 5 | 18 (octeto) |

⚠️ **El He es la excepción:** CEE = **1s²** (no ns²np⁶), pero igual es gas noble del **grupo 18**, porque con 2 e⁻ ya completa la capa n=1 (en n=1 no existe subnivel p).
⚠️ **El H** tiene CE de alcalino (1s¹) pero **es un no metal**. Forma H⁺ y también H⁻.

### Grupo según el bloque (IUPAC 1–18)

| Bloque | Grupo | Ejemplo |
|---|---|---|
| **s** | e⁻ del **ns** | Mg [Ne]3s² → **2** |
| **p** | **10 +** (e⁻ ns + np) | Cl [Ne]3s²3p⁵ → 10+7 = **17** |
| **d** | e⁻ **ns + (n−1)d** | Mn [Ar]4s²3d⁵ → 2+5 = **7** · Cu [Ar]3d¹⁰4s¹ → 1+10 = **11** |

### Longitud de los períodos y bloques

| Período | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| Se llena | 1s | 2s2p | 3s3p | 4s **3d** 4p | 5s **4d** 5p | 6s **4f** 5d 6p | 7s **5f** 6d 7p |
| **Elementos** | **2** | **8** | **8** | **18** | **18** | **32** | **32** |

**Ancho de los bloques:** s = 2 · p = 6 · d = 10 · f = 14 (son las capacidades de cada subnivel).
⚠️ Bloque **d** llena **(n−1)d** · bloque **f** llena **(n−2)f** → **el período NO es el número del subnivel que se llena** (el Ti llena 3d pero está en el período 4).

### CE desde la posición (atajo)

1. **Gas noble del período anterior** entre corchetes.
2. Recorrer el período agregando los subniveles que cruzás.

Ej. **Se** (período 4, grupo 16): [Ar] + 4s² (bloque s) + 3d¹⁰ (bloque d) + 4p⁴ (4ª columna del bloque p) = **[Ar]4s²3d¹⁰4p⁴** ✓ (18+2+10+4 = 34)

**CEE directa:** bloque s → ns^G · bloque p → **ns² np^(G−12)**

### 📈 Tendencias periódicas

$$Z_{ef} = Z - S \qquad \begin{cases} \to \text{período} & Z_{ef} \textbf{ AUMENTA} \\ \downarrow \text{grupo} & \text{manda la DISTANCIA} \end{cases}$$

| Propiedad | **→** (período) | **↓** (grupo) | Máximo |
|---|---|---|---|
| **Radio atómico** | ↓ **baja** | ↑ **sube** | Cs / Fr |
| **Energía de ionización** | ↑ sube | ↓ baja | He / F |
| **Afinidad electrónica** | ↑ sube | ↓ baja | Cl / F |
| **Electronegatividad** | ↑ sube | ↓ baja | **F = 4,0** |
| **Carácter metálico** | ↓ **baja** | ↑ **sube** | Cs / Fr |

🔑 **Regla:** casi todo crece hacia **arriba y a la derecha** (hacia el F) — **menos radio y carácter metálico**, que crecen **abajo y a la izquierda** (hacia el Fr).

**Radio iónico:** catión **<** átomo neutro **<** anión
**Serie isoelectrónica** (mismos e⁻): más **Z** → **más chico**
$$\text{N}^{3-} > \text{O}^{2-} > \text{F}^- > \text{Ne} > \text{Na}^+ > \text{Mg}^{2+} > \text{Al}^{3+}$$

**Reactividad — ojo que va al revés:**

| Grupo | Al bajar | Más reactivo |
|---|---|---|
| **1 (alcalinos)** — ceden | **MÁS** reactivo | Cs, Fr (abajo) |
| **17 (halógenos)** — captan | **MENOS** reactivo | **F** (arriba) |

**Anomalías de EI:** **Be→B** baja (el e⁻ del B sale de un 2p, más energético) · **N→O** baja (el 4° e⁻ p del O se aparea → repulsión)

> Desarrollo completo en `Clase1/Clase1-TablaPeriodica-Profundizacion.md`

### 💡 La idea central de toda la materia

> **Las configuraciones de capa llena (`ns² np⁶`, gas noble) son estables.**
> **Todo átomo tiende a alcanzarlas**, y para eso: **cede** e⁻ (→ catión), **capta** e⁻ (→ anión) o los **comparte** (→ enlace covalente).
> **Sólo los electrones de valencia (capa externa) hacen química.**

---

## 7. Estructuras de Lewis

### ⚠️ ANTES DE EMPEZAR: ¿corresponde hacer Lewis?

> **Lewis y TRePEV son SÓLO para compuestos COVALENTES = NO METAL + NO METAL.**

| Combinación | Unión | ¿Lewis? | ¿TRePEV? |
|---|---|---|---|
| **No metal + No metal** | **Covalente** (comparten) | ✅ **SÍ** | ✅ SÍ |
| **Metal + No metal** | **Iónica** (transfieren) | ❌ No | ❌ No |
| **Metal + Metal** | **Metálica** (deslocalizan) | ❌ No | ❌ No |

**No metales:** H, C, N, O, F, P, S, Cl, Se, Br, I + gases nobles (arriba a la derecha) · **Metaloides** que se tratan como no metales: **B, Si**

**Criterio de fondo — diferencia de electronegatividad:**

$$\Delta EN = |EN_A - EN_B| \qquad \begin{cases} \approx 0 & \text{covalente NO polar} \\ 0{,}4 - 1{,}7 & \text{covalente POLAR} \\ > 1{,}7 & \textbf{IÓNICO} \end{cases}$$

**EN de memoria:** F 4,0 · O 3,5 · N y Cl 3,0 · Br 2,8 · C, I, S 2,5 · H, P 2,1 · B 2,0 · Si, Be, Al 1,5 · Mg 1,2 · Li, Ca 1,0 · Na, Ba 0,9 · K 0,8

⚠️ **Excepciones aparentes:** **BeCl₂, AlCl₃, HgCl₂** tienen metal pero son **covalentes** (ΔEN = 1,5 · 1,5 · 1,1 → todos < 1,7). Por eso aparecen en las tablas de TRePEV.

⚠️ **Al revés:** el **HF** tiene ΔEN = 1,9 (> 1,7) pero es **covalente**, porque el H no es un metal. Cuando los dos criterios discrepan, **gana metal/no metal**.

🔑 **Iones poliatómicos (SO₄²⁻, NO₃⁻, NH₄⁺, CO₃²⁻): por dentro son COVALENTES** → sí se les hace Lewis, entre corchetes con la carga. Lo que es iónico es la unión de ese ion con su contraión (en NaNO₃, el Na⁺ con el NO₃⁻).

### 🔺 Triángulo de Arkel–Katelaar — el criterio COMPLETO (hacen falta 2 números)

**ΔEN solo NO alcanza.** Hacen falta **dos** coordenadas:

$$\Delta EN = |EN_A - EN_B| \qquad\qquad EN_{prom} = \frac{EN_A + EN_B}{2}$$

$$\boxed{\begin{cases} \Delta EN \text{ GRANDE (arriba)} & \to \textbf{IÓNICO} \\ \Delta EN \approx 0 \;+\; EN_{prom} \textbf{ BAJA} & \to \textbf{METÁLICO} \\ \Delta EN \approx 0 \;+\; EN_{prom} \textbf{ ALTA} & \to \textbf{COVALENTE} \\ \text{intermedio, } EN_{prom} \text{ alta} & \to \text{covalente POLAR} \end{cases}}$$

**Por qué hace falta el segundo eje:**

| Par | ΔEN | EN_prom | Tipo |
|---|---|---|---|
| **Cs—Cs** | 0 | **0,7** | **METÁLICO** |
| **F—F** | 0 | **4,0** | **COVALENTE** |

Los dos tienen **ΔEN = 0** y son cosas distintas. Con un solo eje son indistinguibles.

**Vértices del triángulo:** Cs (metálico) · F₂ (covalente) · **CsF** (iónico, el ΔEN máximo posible = 4,0 − 0,7 = **3,3**). Puntos de referencia: MgO (iónico) · SiO₂ (covalente). La cuña entre metálico e iónico es la **fase de Zintl** (no se evalúa).

⚠️ **Es un triángulo y no un cuadrado** porque ΔEN y EN_prom **no son independientes**: si EN_prom = 4,0 los dos átomos tienen que ser F → ΔEN = 0 forzosamente. El ΔEN máximo se da con EN_prom en el medio.

💡 **No hay tres cajones, hay un CONTINUO.** Un enlace es "75 % iónico y 25 % covalente"; los tres nombres son sólo los **vértices**.

### ⚙️ Enlace metálico — modelo del mar de electrones

Cada átomo **suelta sus e⁻ de valencia** al conjunto → red de **cationes** bañada en un **"mar" de electrones deslocalizados** que pertenecen a todo el metal.

Ej. **Na** (1s² 2s² 2p⁶ **3s¹**): quedan Na⁺ (núcleo + 10 e⁻ internos) + el **3s¹** al mar.

| Propiedad metálica | Por qué |
|---|---|
| **Conductividad eléctrica** | Los e⁻ del mar están **libres para moverse** |
| **Conductividad térmica** | Los mismos e⁻ transportan energía cinética |
| **Maleabilidad / ductilidad** | Se pueden **deslizar planos** de cationes: el mar se reacomoda y la unión no se rompe |

⚠️ **Contraste con el iónico:** en un cristal iónico, deslizar un plano pone + frente a + → **se parte**. Los iónicos son **frágiles**, los metales **maleables**.

> Desarrollo completo en `Clase2/Clase2-TiposDeUnion-Profundizacion.md` y `Clase3/Clase3-Explicacion-Completa.md`

---

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

| Átomo | (a) N—C≡S | (b) N=C=S | (c) N≡C—S |
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

## 11. Polaridad y momento dipolar

### Polaridad de un ENLACE

$$\Delta EN = |EN_A - EN_B| \qquad \begin{cases} \approx 0 & \text{covalente NO polar} \\ 0{,}4-1{,}7 & \text{covalente POLAR (}\delta^+ / \delta^-) \\ > 1{,}7 & \text{IÓNICO} \end{cases}$$

$$\delta^+ \to \text{átomo MENOS electronegativo} \qquad\qquad \delta^- \to \text{átomo MÁS electronegativo}$$

### ➡️ Convención del vector μ (se pregunta)

| Propiedad | Regla |
|---|---|
| **Dirección** | Paralela a la línea internuclear (a lo largo del enlace) |
| **Sentido** | **DEL δ⁺ AL δ⁻** → apunta al átomo **más electronegativo** |
| **Módulo** | ∝ δ × distancia |

⚠️ En **física** el momento dipolar se define al revés (del − al +). En **química** —y en este curso— es **del + al −**.

### Momento dipolar

$$\boxed{\mu = q \cdot d} \qquad\qquad 1\ \text{D} = 3{,}336\times10^{-30}\ \text{C·m}$$

**Por qué existe el debye:** 1 carga elemental separada 1 Å da 1,6×10⁻²⁹ C·m = **4,8 D**. La unidad está calibrada para que los dipolos reales den números de 0 a 5.

**Valores de referencia:**

| Molécula | μ (D) | | Molécula | μ (D) |
|---|---|---|---|---|
| Cl₂, N₂, CO₂, CCl₄, BF₃, SF₆ | **0** | | HCl | **1,08** |
| CO | 0,11 | | NH₃ | **1,47** |
| HI | 0,44 | | HF | 1,82 |
| HBr | 0,79 | | **H₂O** | **1,85** |
| CH₂Cl₂ | 1,60 | | HCN | 2,98 |

$$\% \text{ carácter iónico} = \frac{\mu_{\text{experimental}}}{\mu_{\text{teórico (cargas} \pm 1)}}\times 100$$

**Ejemplo (HCl, d = 1,27 Å):** μ_teór = 1,6×10⁻¹⁹ × 1,27×10⁻¹⁰ = 2,03×10⁻²⁹ C·m = **6,1 D**. Con μ_exp = 1,8 D → **30% iónico** → δ = **±0,30**.

### ⭐ Polaridad de una MOLÉCULA

$$\boxed{\vec{\mu}_{\text{molécula}} = \sum \vec{\mu}_{\text{enlaces}}} \qquad \text{(suma VECTORIAL)}$$

> **NO POLAR** si la geometría es **simétrica** Y **todos los sustituyentes son iguales** → los vectores se cancelan.

| Situación | Polaridad |
|---|---|
| Diatómica **homo**nuclear (N₂, O₂, Cl₂) | **NO polar** |
| Diatómica **hetero**nuclear (CO, HCl) | **POLAR** |
| Geometría simétrica + sustituyentes iguales | **NO polar** |
| **Pares libres** en el central que rompen la simetría | **POLAR** |
| **Sustituyentes distintos** (CH₃F, CH₂Cl₂, CHCl₃) | **POLAR** |

### ⭐ TABLA MAESTRA — polaridad por geometría (hay que saberla toda)

Notación: **A** = central · **B** = sustituyente · **B′** = sustituyente distinto · **E** = par libre

| Grupos | Clase | Geom. MOLECULAR | Ejemplos | **¿Polar?** |
|---|---|---|---|---|
| 1 | **AB** | Lineal | Cl₂, N₂ / **HCl, CO** | **No** / **Sí** |
| 2 | **AB₂** | Lineal | CO₂, CS₂, BeCl₂, HgCl₂ | **No** |
| 2 | **ABB′** | Lineal | **HCN**, OCS | **Sí** |
| 3 | **AB₃** | Plana trigonal | **BF₃**, BCl₃, SO₃, CO₃²⁻ | **No** |
| 3 | **AB₂B′** | Plana trigonal | COCl₂, HCHO | **Sí** |
| 3 | **AB₂E** | **Angular** | **SO₂**, O₃, NO₂⁻ | **Sí** |
| 4 | **AB₄** | Tetraédrica | **CH₄, CCl₄**, SiF₄, NH₄⁺, SO₄²⁻ | **No** |
| 4 | **AB₃B′** | Tetraédrica | CH₃Cl, CHCl₃ | **Sí** |
| 4 | **AB₂B′₂** | Tetraédrica | **CH₂Cl₂** | **Sí** |
| 4 | **AB₃E** | **Pirámide trigonal** | **NH₃**, PCl₃, H₃O⁺ | **Sí** |
| 4 | **AB₂E₂** | **Angular** | **H₂O**, H₂S, SCl₂ | **Sí** |
| 5 | **AB₅** | Bipirámide trigonal | **PCl₅**, PF₅ | **No** |
| 5 | **AB₄E** | **Balancín** (sube y baja) | **SF₄** | **Sí** |
| 5 | **AB₃E₂** | **Forma de T** | **ClF₃**, BrF₃ | **Sí** |
| 5 | **AB₂E₃** | **Lineal** | **XeF₂**, I₃⁻ | **No** ⚠️ |
| 6 | **AB₆** | Octaédrica | **SF₆**, PF₆⁻ | **No** |
| 6 | **AB₅E** | **Pirámide cuadrada** | **BrF₅**, IF₅ | **Sí** |
| 6 | **AB₄E₂** | **Plana cuadrada** | **XeF₄**, ICl₄⁻ | **No** ⚠️ |

$$\boxed{\text{NO POLAR} \iff \text{geometría SIMÉTRICA} \;\textbf{Y}\; \text{sustituyentes TODOS IGUALES}}$$

💡 **Atajo:** las geometrías moleculares **no polares** (con sustituyentes iguales) son **seis**:
**lineal · plana trigonal · tetraédrica · bipirámide trigonal · octaédrica · plana cuadrada**
Las **polares** son **cinco**: **angular · pirámide trigonal · balancín · forma de T · pirámide cuadrada**

### 📝 Algoritmo de polaridad (6 pasos)

```
1. Lewis → contar grupos electrónicos y pares libres del central
2. Grupos → geometría ELECTRÓNICA
3. Ignorar pares libres → geometría MOLECULAR
4. ¿Hay enlaces polares (ΔEN ≠ 0)?   NO → NO POLAR (fin)
5. ¿Sustituyentes TODOS iguales?     NO → POLAR (fin)
6. ¿Vectores simétricamente distribuidos?  SÍ → NO POLAR | NO → POLAR
```

### ⚠️ Reglas de posición de los pares libres (necesarias para los pasos 3 y 6)

| Geometría electrónica | Dónde va el par libre |
|---|---|
| **Bipirámide trigonal** (5) | **SIEMPRE ECUATORIAL** (2 vecinos a 90° en vez de 3) |
| **Octaédrica** (6), 2 pares | **TRANS** (a 180°, opuestos) → plana cuadrada |

⚠️ **Enlaces polares ≠ molécula polar.** El **BF₃** tiene los enlaces más polares de la práctica (ΔEN = 2,0) y es **NO POLAR** (trigonal plana simétrica). Igual el **CO₂**, **CCl₄**, **SF₆**, **XeF₄**, **PF₅**.

⚠️ **"Pares libres" NO implica polar.** **XeF₂** (3 pares libres) y **XeF₄** (2 pares libres) son **NO POLARES**, porque los pares quedan **simétricamente distribuidos entre sí** (3 a 120° en el ecuador / 2 a 180° trans). Lo que importa no es *cuántos* pares libres hay, sino *si desbalancean*.

⚠️ **Contar enlaces polares no responde nada:** 2 en el no polar CO₂ y 2 en el polar H₂O; 3 en el no polar BF₃ y 3 en el polar NH₃. **Sólo la geometría decide.**

⚠️ **CO₂ vs H₂O:** misma cantidad de átomos, resultado opuesto. Lo que decide son **los pares libres del átomo central**: CO₂ (0 libres → lineal → **no polar**) vs H₂O (2 libres → angular → **POLAR**).

⚠️ **CCl₄ vs CH₂Cl₂:** los dos tetraédricos, pero el CCl₄ tiene **4 sustituyentes iguales** (no polar) y el CH₂Cl₂ **dos tipos distintos** (**polar**).

💡 **Uso inverso:** si te dan μ ≠ 0, podés **descartar geometrías simétricas**. Ej.: el H₂S tiene μ = 0,97 D → **no puede ser lineal** → es **angular**.

---

## 12. Interacciones intermoleculares

### ⚠️ Primero: INTRA ≠ INTER (no confundir nunca)

| | Qué une | Magnitud | Se rompe al |
|---|---|---|---|
| **INTRAmolecular** = **enlace químico** | Átomos **dentro** de la molécula | **150–1000 kJ/mol** | Hacer una **reacción química** |
| **INTERmolecular** = **interacción** | Moléculas **entre sí** | **< 1 – 250 kJ/mol** | **Fundir / hervir** |

⚠️ Al **hervir agua NO se rompe ningún enlace O—H**: la molécula queda entera en el vapor. Se rompen las **uniones H entre moléculas**. Hervir agua: ~41 kJ/mol · romper un O—H: ~460 kJ/mol.

### Los 3 personajes

| Personaje | Símbolo | Qué tiene |
|---|---|---|
| **Ion** (atómico o **poliatómico**: SO₄²⁻, NH₄⁺) | **Q** | Carga **neta entera** |
| **Molécula polar** | **μ** | Dipolo **permanente** |
| **Molécula no polar** | **α** | **Nada** hasta que se lo inducen |

### La matriz — todas las combinaciones posibles (son 6, no hay más)

| | Ion (Q) | Polar (μ) | No polar (α) |
|---|---|---|---|
| **Ion (Q)** | ion–ion | ion–dipolo | ion–dip. inducido |
| **Polar (μ)** | — | dipolo–dipolo (**+ unión H**) | dipolo–dip. inducido |
| **No polar (α)** | — | — | **London** |

🔑 **Cada interacción = producto de las magnitudes de los dos participantes.** Si te acordás de esto, deducís la columna "depende de" sin memorizarla.

### ⭐ TABLA DE MAGNITUDES (memorizar el ORDEN)

| Familia | Interacción | Depende de | **Magnitud** | Alcance | Ejemplo |
|---|---|---|---|---|---|
| **Electrostática** | **Ion – Ion** | $Q_1Q_2$ | **250 kJ/mol** | $1/d$ | NaCl, LiF |
| **Unión H** | **Puente hidrógeno** | — | **20 kJ/mol** | **direccional** | H₂O/H₂O |
| **Electrostática** | **Ion – Dipolo** | $Q_1\mu_2$ | **15 kJ/mol** | $1/d^2$ | Na⁺/H₂O, Na⁺/HCl |
| **Inductiva** | **Ion – Dip. inducido** | $Q_1\alpha_2$ | **10 kJ/mol** | $1/d^4$ | Na⁺/Cl₂ |
| **Dispersiva** | **London** (= van der Waals) | $\alpha_1\alpha_2$ | **5 kJ/mol** | **$1/d^6$** | Cl₂/Cl₂, Br₂/Br₂ |
| **Electrostática** | **Dipolo – Dipolo** | $\mu_1\mu_2$ | **0,6 kJ/mol** | $1/d^3$ | HCl/HCl |
| **Inductiva** | **Dip. – Dip. inducido** | $\mu_1\alpha_2$ | **< 1 kJ/mol** | — | HCl/Cl₂ |

**Referencias para comparar:** agitación térmica a 25 °C ≈ **2,5 kJ/mol** (RT) · enlace covalente **150–1000 kJ/mol**

⚠️ **London (5) es MÁS fuerte que dipolo–dipolo (0,6).** Contraintuitivo y es la clave de media práctica: en moléculas medianas o grandes **London domina sobre la polaridad**.

⚠️ **London es la ÚNICA fuerza entre especies no polares** (frase textual del docente), pero **actúa en TODAS las sustancias**, polares incluidas.

📌 **Nomenclatura:** en sentido estricto "**van der Waals**" abarca las tres débiles (Keesom = dipolo–dipolo · Debye = inductivas · **London** = dispersivas). El docente lo usa como sinónimo de **London**.

### 🔵 Unión hidrógeno — los DOS requisitos

$$\boxed{\text{Unión H} \iff \begin{cases} \text{un } \mathbf{H} \text{ unido a } \mathbf{F,\,O,\,N} & \text{(DADOR)} \\ \text{un } \mathbf{F,\,O,\,N} \text{ con } \mathbf{par\ libre} & \text{(ACEPTOR)} \end{cases}}$$

**Sólo F, O, N** (mnemotecnia: "**FON**"). Es un **dipolo–dipolo de intensidad anormalmente alta** (~33× uno común), **direccional**.

**Por qué es tan fuerte:** ① ΔEN enorme (O—H = 1,4 · F—H = 1,9) ② el **H no tiene electrones internos** → queda un protón casi desnudo, carga muy concentrada, se acerca muchísimo ③ hay un **par libre** esperando en una dirección definida.

| Sustancia | ¿Unión H entre sus moléculas? | Por qué |
|---|---|---|
| **H₂O** | ✅ **Sí — 4 por molécula** (2 dadores + 2 aceptores) | la campeona |
| **NH₃** · **HF** | ✅ Sí (1 dador cada una) | |
| **CH₃OH**, alcoholes, ácidos, aminas | ✅ Sí | tienen O—H o N—H |
| **CH₃OCH₃** (éter) | ❌ **No consigo mismo** | aceptor ✓ pero **sin dador** (sí hace unión H **con agua**) |
| **CH₄** | ❌ No | el H está unido a **C** (EN 2,5, insuficiente) |
| **HCl** | ❌ No | el Cl es **muy grande**, carga dispersa |

**Distancias en el agua:** enlace covalente O—H = **0,101 nm** · puente H·····O = **0,175 nm** (**1,7× más largo** → interacción real pero más débil que un enlace; se dibuja con **puntos**).

### 💧 Las anomalías del agua (todas por unión H)

| Sustancia | Mr | T_eb | ¿Unión H? |
|---|---|---|---|
| CH₄ | 16 | **−161 °C** | No |
| NH₃ | 17 | −33 °C | Sí |
| **H₂O** | **18** | **+100 °C** | **Sí (4/molécula)** |
| HF | 20 | +20 °C | Sí |
| H₂S | 34 | −60 °C | No |

⚠️ El H₂O tiene casi la misma Mr que el CH₄ y hierve **261 °C más arriba**. El H₂S es **el doble** de pesado y hierve 160 °C **más abajo**. **Sólo la unión H lo explica.**

| Anomalía | Valor | Consecuencia |
|---|---|---|
| **T_eb altísima** | 100 °C | El agua es **líquida** en la Tierra |
| **Calor específico altísimo** | 4,18 J/g·K | El mar regula el clima |
| **Tensión superficial alta** | 72 mN/m | Capilaridad |
| **🧊 Hielo MENOS denso que el agua** | **0,917** vs 1,000 g/cm³ | **FLOTA** |

**Por qué el hielo flota:** cada H₂O hace **4 uniones H tetraédricas** (rígidas y direccionales) → red **abierta** con huecos hexagonales → menos denso. Los lagos se congelan **de arriba hacia abajo** y los peces sobreviven. Densidad máxima del agua a **4 °C**. Al congelarse **se expande ~9 %**.

**Por qué el agua gana al HF** (que tiene más ΔEN): el agua hace **4 uniones H por molécula** (2 H + 2 pares libres); el HF sólo **1** (3 pares libres pero **un solo H**).

**El agua es líquida y no sólida** porque los puentes son **transitorios**: se rompen y forman ~10¹² veces/s.

**ADN:** A–T = **2** puentes · G–C = **3** puentes → un ADN rico en **G–C** cuesta más separar (T_m mayor).

### 🌀 London y polarizabilidad (α)

**α = capacidad de deformar la nube electrónica** ante un dipolo o una carga.

$$\boxed{\alpha \uparrow \iff \text{n° de } e^- \uparrow \iff \text{Mr} \uparrow \;\Longrightarrow\; \text{London} \uparrow \;\Longrightarrow\; \text{T}_{eb},\,\text{T}_f \uparrow}$$

**Mecanismo de London (3 pasos):** ① fluctuación **espontánea** de la nube → **dipolo instantáneo** (~10⁻¹⁵ s) ② **induce** un dipolo complementario en el vecino ③ se **atraen**. El efecto neto promediado es **siempre atractivo**.

**Los 3 factores que determinan London, en orden de importancia:**

$$1.\ \textbf{n° de electrones (Mr)} \qquad 2.\ \textbf{FORMA (superficie de contacto)} \qquad 3.\ \text{difusividad de la nube}$$

| Serie | Orden de T_eb | Factor |
|---|---|---|
| He < Ne < Ar < Kr < Xe | ↑ | ① más e⁻ |
| **F₂ (gas) < Cl₂ (gas) < Br₂ (líq.) < I₂ (sól.)** | ↑ | ① 18 → 34 → 70 → 106 e⁻ |
| CH₄ < C₂H₆ < C₃H₈ < C₄H₁₀ | ↑ | ① más e⁻ |
| HCl < HBr < HI (**sin** el HF) | ↑ | ① gana London a la polaridad |
| **n-pentano (36°) > isopentano (28°) > neopentano (10°)** | ↓ | ② **misma Mr**, más ramificado = **menos contacto** |

🔑 **Regla de la forma:** **a igual Mr y polaridad, la molécula MÁS ALARGADA hierve MÁS ALTO.** Ramificar **baja** el punto de ebullición (se acerca a la esfera → menos superficie de contacto). Funciona porque London decae con **1/d⁶** → sólo contribuye lo que está casi en contacto.

⚠️ **No digas "el I₂ es sólido porque es más pesado".** Decí "**porque tiene más electrones → más polarizable → más London**". La masa molar es un **indicador**, no la causa.

### ⚙️ Las dos inductivas

| Interacción | Inductor | Magnitud | Ejemplo de la vida real |
|---|---|---|---|
| **Ion – dipolo inducido** | Carga **entera** | ~10 kJ/mol | I₂ en solución de KI |
| **Dipolo – dipolo inducido** | Carga **parcial** | **< 1 kJ/mol** | **O₂ y N₂ disueltos en agua** (los peces respiran) |

**Mecanismo:** la carga/dipolo **deforma** la nube de la molécula no polar → aparece un dipolo **que no existía** → se atraen. Si sacás el inductor, **desaparece** (a diferencia de un dipolo permanente).

### 🧂 Ion–dipolo: por qué la sal se disuelve en agua

Cada ion queda rodeado por una **esfera de solvatación (hidratación)**:

| Ion | Qué le apunta |
|---|---|
| **Catión** (Na⁺) | el **O** del agua (δ−) |
| **Anión** (Cl⁻) | los **H** del agua (δ+) |

La **energía de hidratación** compensa la **energía de red**. Si gana o empata → se disuelve. Si la red es demasiado fuerte (CaCO₃, AgCl) → **no** se disuelve.

⚠️ **Ion–ion depende MUCHO de la carga** ($Q_1Q_2$): NaCl (+1)(−1) funde a **801 °C** · **MgO** (+2)(−2) funde a **2852 °C**.

---

## 13. Estados de agregación y propiedades físicas

### El criterio

$$\boxed{\begin{cases} E_c > E_p & \to \textbf{GAS} \\ E_c \approx E_p & \to \textbf{LÍQUIDO} \\ E_c < E_p & \to \textbf{SÓLIDO} \end{cases}}$$

| | Qué la produce | ¿Depende de T? | Qué "quiere" |
|---|---|---|---|
| **E cinética** | Agitación térmica ($E_c \propto T$, **lineal**) | **SÍ** | **Separar** |
| **E potencial** | **Fuerzas intermoleculares** | **NO** (1ª aprox.) | **Juntar** |

**Hay DOS maneras de cambiar el estado:**

| Camino | Qué cambia | Ejemplo |
|---|---|---|
| **Cambiar T** (mismo material) | E_c | Hielo → agua → vapor |
| **Cambiar la sustancia** (misma T) | E_p | **F₂, Cl₂, Br₂, I₂ todos a 25 °C** → gas, gas, líquido, sólido |

### ⭐ MÉTODO para ordenar puntos de ebullición / fusión

```
1. ¿Es IÓNICO / METÁLICO / COVALENTE DE RED (diamante, SiO₂, Si)?
      → SÓLIDO, T_f altísima (fin)
2. Es MOLECULAR. ¿Alguna tiene UNIÓN H?
      → ésa va más arriba (a Mr comparable)
3. ¿Masas molares MUY distintas?
      SÍ → manda la MASA MOLAR / n° de e⁻ (London)
      NO → manda la POLARIDAD (dipolo-dipolo)
4. ¿Misma Mr y misma polaridad?
      → manda la FORMA (más alargada = más alto)
```

### ⚠️ Las tres trampas clásicas (y cómo se resuelven)

| Comparación | Resultado | Por qué |
|---|---|---|
| **HCl (−85 °C) < HI (−35 °C)** | El **menos** polar hierve más alto | HI es **mucho más grande** → gana **London** |
| **CH₃OH (65 °C) < CCl₄ (77 °C)** | El que tiene **unión H** hierve más **bajo** | CCl₄ tiene **74 e⁻** vs 18 → gana **London** |
| **H₂O (100 °C) ⋙ H₂S (−60 °C)** | El **más liviano** hierve más alto | El agua tiene **unión H** |

🔑 **La moraleja de las tres: la unión H y la polaridad ganan "A IGUAL TAMAÑO", no en términos absolutos.** Siempre chequeá primero si las masas molares son comparables.

### Ejemplo integrador resuelto — ordenar CH₄, CH₃OH, CCl₄

| | **CH₄** | **CH₃OH** | **CCl₄** |
|---|---|---|---|
| Geom. molecular | Tetraédrica | Tetraédrica (C) + angular (O) | Tetraédrica |
| Sustituyentes | 4 iguales | **distintos** | 4 iguales |
| **Polaridad** | **NO polar** | **POLAR** | **NO polar** |
| ¿Unión H? | No | **SÍ** | No |
| e⁻ totales | 10 | 18 | **74** |
| **Fuerzas** | Sólo **London** (chico) | **Unión H** + dip–dip + London | Sólo **London** (grande) |
| **T_eb** | **−161 °C** | **+65 °C** | **+77 °C** |

**Orden: CH₄ ⟨ CH₃OH ⟨ CCl₄** — el CCl₄ gana al metanol **aunque el metanol tenga unión H**, porque tiene 4× más electrones.

---

## 14. Número de oxidación

> **Representa el nº de electrones que un átomo pone en juego al formar un compuesto.**

$$\text{n° de oxidación} = \begin{cases} \textbf{SIGNO} & \to \text{ELECTRONEGATIVIDAD (quién le gana a quién)} \\ \textbf{VALOR} & \to \text{CANTIDAD DE ENLACES} \end{cases}$$

⚠️ **Es RELATIVO, no fijo.** El mismo Cl: **−1** con Na · **+1** con O · **0** con otro Cl.
⚠️ **No es lo mismo que los e⁻ de valencia.** El Cl tiene 7 e⁻ de valencia pero nº ox −1 en el NaCl.
⚠️ **No es lo mismo que la carga formal** (sección 8): la CF reparte el par por la mitad, el nº de ox se lo da entero al más electronegativo.

### Las 6 reglas (de memoria)

| # | Regla | Valor | Excepciones |
|---|---|---|---|
| **1** | **Sustancia simple** (Cl₂, O₂, N₂, Fe, Na) | **0** | ninguna |
| **2** | **F** combinado | **−1** | **ninguna** (es el más E_N) |
| **3** | **O** combinado | **−2** | **peróxidos (O—O) → −1** · con F → positivo · O₂ → 0 |
| **4** | **H** combinado | **+1** | **hidruros metálicos (Metal+H) → −1** · H₂ → 0 |
| **5** | **Ion monoatómico** | **= su carga** | ninguna |
| **6** | **Suma** | $\sum(\text{atomicidad}\times\text{n° ox}) = \text{carga neta}$ | compuesto neutro → **0** |

**Grupo 1 → +1 · Grupo 2 → +2.** Los demás **van de dato** en el parcial.

### Método

Asignás los que sabés (reglas 1–5) y **despejás el que falta** con la regla 6.

| Compuesto | Cuenta | Resultado |
|---|---|---|
| H₂S | 2(+1) + S = 0 | S = **−2** |
| Fe₂O₃ | 2Fe + 3(−2) = 0 | Fe = **+3** |
| **SO₄²⁻** | S + 4(−2) = **−2** | S = **+6** |
| HNO₃ | (+1) + N + 3(−2) = 0 | N = **+5** |
| CaH₂ | (+2) + 2H = 0 | H = **−1** (hidruro) |
| H₂O₂ | 2(+1) + 2O = 0 | O = **−1** (peróxido) |

✅ **Chequeo:** el valor que te dé tiene que **estar entre los datos**. Si no está, la cuenta está mal.

### Escritura de la fórmula

> Los símbolos van de izquierda a derecha en orden de **E_N CRECIENTE**: CaCl₂ · H₂O · CO₂ · **HCl** (H a la izq.) vs **LiH** (H a la der.)

---

## 15. Nomenclatura inorgánica

**Tres sistemas** — se usan **Stock** y **Tradicional**. ⚠️ **NO se mezclan** en un mismo nombre.

### Clasificación (primer paso siempre)

| Tipo | Composición | Iónico/Molecular |
|---|---|---|
| **Sal binaria** | Metal + NoMetal | Iónico |
| **Óxido** | **O** + otro | Iónico (metal) / Molecular (no metal) |
| **Hidrácido** | **H + NoMetal** | Molecular |
| **Hidruro** | **Metal + H** | Iónico |
| **Hidróxido** | Metal + **(OH)** | Iónico |
| **Oxoácido** | **H + NoMetal + O** | Molecular |
| **Oxosal** | **Metal + NoMetal + O** | Iónico |

### Nombres

| Tipo | **Stock** | **Tradicional** |
|---|---|---|
| **Sal binaria** | NoMetal-**uro** de Metal (nº ox) | NoMetal-**uro** Metal-sufijo |
| **Óxido** | Óxido de Elemento (nº ox) | Óxido prefijo-Elem-sufijo |
| **Hidrácido** | NoMetal-**uro** de hidrógeno | **ácido** NoMetal-**hídrico** |
| **Hidruro** | Hidr-**uro** de Metal (nº ox) | Hidr-**uro** Metal-sufijo |
| **Hidróxido** | Hidróxido de Metal (nº ox) | Hidróxido Metal-sufijo |
| **Oxoácido** | NoMetal-**ato** (nº ox) de hidrógeno | **ácido** prefijo-Elem-sufijo |
| **Oxosal** | NoMetal-**ato** (nº ox) de metal | prefijo-Elem-sufijo **de metal** |

### Prefijos y sufijos — según CUÁNTOS nº ox tenga el elemento

| Cantidad | De menor a mayor |
|---|---|
| **1** | **nada** (fluoruro de calcio, hidruro de calcio) |
| **2** | -**oso** · -**ico** |
| **3** | **hipo**--**oso** · -**oso** · -**ico** |
| **4** | **hipo**--**oso** · -**oso** · -**ico** · **per**--**ico** |

⚠️ El sufijo indica **posición relativa**, no un número fijo: "-ico" es +2 en el Cu y +5 en el I.

### 🧠 Regla de oro

$$\boxed{\textbf{OSO chiquITO} \qquad \textbf{pICO de pATO}}$$
$$\text{ácido -OSO} \to \text{sal -ITO} \qquad \text{ácido -ICO} \to \text{sal -ATO}$$

| Sufijo | Compuesto | ¿Tiene O? |
|---|---|---|
| **-uro** | Sal binaria / hidrácido | ❌ **NO** |
| **-ito / -ato** | Oxosal | ✅ **SÍ** |

### Serie modelo del cloro (reconstruila para cualquier halógeno)

| Nº ox | Oxoácido | Oxosal de Na |
|---|---|---|
| **−1** | HCl — ácido clor**hídrico** | NaCl — clor**uro** de sodio |
| **+1** | HClO — ácido **hipo**clor**oso** | NaClO — **hipo**clor**ito** (¡lavandina!) |
| **+3** | HClO₂ — ácido clor**oso** | NaClO₂ — clor**ito** |
| **+5** | HClO₃ — ácido clór**ico** | NaClO₃ — clor**ato** |
| **+7** | HClO₄ — ácido **per**clór**ico** | NaClO₄ — **per**clor**ato** |

### 📝 Método para FORMULAR (nombre → fórmula)

1. **Clasificá** por el nombre (sufijo, palabra "ácido"/"óxido"/"hidruro"/"hidróxido").
2. **Deducí el nº de ox** del elemento central (por el prefijo/sufijo o el romano).
3. **Asigná** los conocidos: O = −2 · H = +1 (o −1 si hay metal) · metal según grupo.
4. **Planteá** $\sum(\text{atomicidad}\times\text{n° ox}) = 0$ y despejá los subíndices.
5. **Verificá** que dé 0.

💡 **Truco del intercambio:** el nº de ox de uno pasa como subíndice del otro, cruzado y sin signo. Hg⁺¹ + O⁻² → **Hg₂O**.

**Ejemplos:** sulfito de magnesio → **MgSO₃** · ácido perclórico → **HClO₄** · óxido de mercurio(I) → **Hg₂O** · hidruro de potasio → **KH** · cloruro ferroso → **FeCl₂**

### Nombres propios (memoria)

**H₂O** agua · **NH₃** amoníaco · **PH₃** fosfina · **AsH₃** arsina · **SiH₄** silano

> Desarrollo completo en `Extra/Nomenclatura-Explicacion-Completa.md`

---

## 16. Errores típicos

| ❌ Error | ✅ Correcto |
|---|---|
| Decir "órbita" | **Orbital** (región de probabilidad, no trayectoria) |
| Escribir 1p, 2d, 3f | No existen: **ℓ ≤ n−1** |
| Poner 3d antes que 4s | **4s se llena primero** (diagonales) |
| Meter el 3d¹⁰ en la CEE del Br | La **CEE lleva sólo el n MÁXIMO** |
| Cambiar Z al hacer un ion | **Z (protones) NUNCA cambia**; cambian los electrones |
| Restar e⁻ para un anión | Anión = **SUMA** e⁻ · Catión = **RESTA** e⁻ |
| Olvidarse de multiplicar por N_A cuando piden "por mol" | E_mol = (hc/λ)·**N_A** |
| Sacar el grupo de un metal de transición sólo de la CEE | Transición: **grupo = ns + (n−1)d** |
| Decir que una violación de Hund es "imposible" | Viola **Pauli** → imposible · viola **Aufbau/Hund** → **excitado** |
| Dibujar el 3p como [↑↓][ ][ ] en el fundamental | **Hund**: [↑][↑][ ] |
| Pensar que "isoelectrónico" = mismo elemento | Misma cantidad de **e⁻**, distinto **Z** |
| Escribir Cr = [Ar]4s²3d⁴ o Cu = [Ar]4s²3d⁹ | **Excepciones**: Cr = [Ar]3d⁵4s¹ · Cu = [Ar]3d¹⁰4s¹ |
| Buscar UN solo ion estable para un metal de transición | Forman **varios** (Fe²⁺ y Fe³⁺) |
| Poner CEE(He) = 1s²2s²2p⁶ | **CEE(He) = 1s²** — igual es gas noble |
| Aparear en el 2p antes de llenar los 3 | **Hund**: primero uno en cada orbital |
| Contar un doble enlace como 2 grupos en TRePEV | Enlace múltiple = **1 solo grupo** |
| Confundir geometría electrónica con molecular | **Molecular ignora los pares libres** |
| Poner H o F como átomo central | **H y F SIEMPRE periféricos** |
| Hacer Lewis de un compuesto con Na, K, Ca… | Ésos son **IÓNICOS** — Lewis es sólo para **no metal + no metal** |
| Creer que existe "la molécula de NaCl" | En iónico **no hay moléculas**: hay red cristalina. NaCl es una **unidad fórmula** |
| Decir "los covalentes funden bajo" a secas | Vale para los **moleculares**. Los **de red** (diamante, SiO₂, Si) funden altísimo |
| Buscar geometría TRePEV de un compuesto iónico | No tiene: no hay molécula ni átomo central |
| Decir que el radio **aumenta** a lo largo del período | **DISMINUYE**: Z_ef ↑ comprime la misma capa (aunque haya más e⁻) |
| Poner al Ti en el período 3 porque llena el 3d | **Período = n máximo** (4s) → período **4** |
| Creer que los halógenos son más reactivos abajo | Al revés: **F** es el más reactivo. Alcalinos sí van al revés (Cs) |
| Ordenar la tabla por masa atómica | Se ordena por **Z**. Por masa se invierten Ar/K, Co/Ni y Te/I |
| Mezclar Stock y Tradicional | "Óxido plúmb**ico**" **o** "óxido de plomo **(IV)**", nunca los dos juntos |
| Confundir nº de oxidación con e⁻ de valencia | El Cl tiene **7** e⁻ de valencia pero nº ox **−1** en el NaCl |
| Igualar la Σ de nº de ox a 0 en un **ion** | En SO₄²⁻ la suma da **−2**, no 0 |
| Confundir **hidrácido** con **hidruro** | H+NoMetal → hidrácido (H = **+1**) · Metal+H → hidruro (H = **−1**) |
| Confundir **-uro** con **-ito/-ato** | **-uro** = SIN oxígeno · **-ito/-ato** = CON oxígeno |
| Poner sufijo con un solo nº de ox | "Fluor**uro de calcio**", no "fluoruro cálcico" |
| Usar O = −2 en un **peróxido** | En el grupo O—O el oxígeno es **−1** (H₂O₂) |
| Escribir Co(OH)₂ sin paréntesis | **Co(OH)₂**, nunca "CoOH₂" |
| Decir que el **CO₂ es polar** porque sus enlaces lo son | Lineal simétrica → los vectores **se cancelan** → **NO polar** |
| Decir que el **BF₃ es polar** (ΔEN = 2,0!) | Trigonal plana simétrica → **NO polar** |
| Forzar el octeto en el **NO** | 11 e⁻ (**impar**) → imposible: es un **radical** |
| Poner el H sobre el N en el **HNO₃** | En los oxoácidos el **H va sobre un O** |
| Dar una sola geometría en moléculas con varios centros | CH₃OH: C **tetraédrico** + O **angular** |
| Sumar los μ de enlace como números | Es una suma **VECTORIAL** |
| Forzar el octeto en BF₃ | El **B es deficiente**: se queda con 6 e⁻ |
| Olvidar los corchetes y la carga en un ion | **[ … ]²⁻** |
| No verificar la suma de superíndices en la CE | **Debe dar el n° de electrones** |
| Pensar que la resonancia oscila | Es un **híbrido**, una sola especie promedio |
| Usar sólo ΔEN para clasificar el enlace | Hacen falta **ΔEN + EN_promedio** (Katelaar). Cs—Cs y F—F tienen los dos ΔEN = 0 |
| Dibujar el vector μ del δ⁻ al δ⁺ | Convención química: **del δ⁺ al δ⁻** (apunta al más electronegativo) |
| "Si hay pares libres, la molécula es polar" | **XeF₂ (3 pares) y XeF₄ (2 pares) son NO polares**: quedan simétricos |
| Poner el par libre **axial** en bipirámide trigonal | Van **SIEMPRE ECUATORIAL** (2 vecinos a 90° en vez de 3) |
| Poner los 2 pares libres **cis** en octaédrica | Van **TRANS** (180°) → **plana cuadrada** |
| Contar enlaces polares para decidir la polaridad | No sirve: 2 en CO₂ (no polar) y 2 en H₂O (polar). **Sólo la geometría decide** |
| Decir que al hervir agua se rompen los enlaces O—H | Se rompen las **uniones H INTERmoleculares**; la molécula queda entera |
| "Más polar ⇒ hierve más alto", a secas | Sólo **a masa molar comparable**. **HCl (−85°) < HI (−35°)** lo rompe |
| Creer que dipolo–dipolo > London | **London (5) > dipolo–dipolo (0,6) kJ/mol** |
| Decir que el CH₄ hace uniones H (¡tiene 4 H!) | El H tiene que estar unido a **F, O o N**. El C no alcanza |
| Decir que el HCl hace uniones H (Cl tiene EN 3,0) | El Cl es **muy grande**: la carga queda dispersa |
| Decir que el éter CH₃OCH₃ hace unión H consigo mismo | Tiene **aceptor** pero **NO dador** (ningún H sobre el O). Con agua **sí** |
| "El I₂ es sólido porque es más pesado" | Porque tiene **más e⁻ → más polarizable → más London** |
| Decir que London actúa **sólo** entre no polares | Actúa en **todas**; es la **única** entre no polares |
| Olvidar la **forma** al comparar isómeros | Pentano (36 °C) vs neopentano (10 °C): **misma Mr**, distinta superficie de contacto |
| Decir que el hielo es más denso que el agua | **MENOS** denso (0,917) → **flota**. Red tetraédrica abierta por unión H |
| Confundir E cinética con E potencial | **E_c ∝ T** (separa) · **E_p = fuerzas intermoleculares** (junta), ~indep. de T |

---

## 17. Modelos atómicos — línea histórica

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

$$A = Z + N \qquad e^- = Z - \text{carga} \qquad Z = e^- + \text{carga} \qquad \Delta x\cdot\Delta p \geq \frac{h}{4\pi}$$

$$E_{\text{mol}} = \frac{hc}{\lambda}\cdot N_A \qquad 1\ \text{Wh} = 3600\ \text{J}$$

$$\text{orbitales por subnivel} = 2\ell+1 \qquad \text{orbitales por capa} = n^2 \qquad e^-_{\text{máx por capa}} = 2n^2$$

$$CF = e^-_{\text{valencia}} - e^-_{\text{libres}} - N_{\text{enlaces}}$$

$$e^-_{\text{Lewis}} = \textstyle\sum e^-_{\text{valencia}} + \text{carga}^- - \text{carga}^+ \qquad \text{pares} = \frac{e^-_{\text{totales}}}{2}$$

$$\sum (\text{atomicidad} \times \text{n° de oxidación}) = \text{carga neta} \qquad \Delta EN = |EN_A - EN_B|$$

$$\mu = q\cdot d \qquad 1\ \text{D} = 3{,}336\times10^{-30}\ \text{C·m} \qquad \%\text{ iónico} = \frac{\mu_{\exp}}{\mu_{\text{teór}}}\times100 \qquad \vec{\mu}_{\text{mol}} = \textstyle\sum \vec{\mu}_{\text{enlaces}}$$

$$\Delta EN = |EN_A - EN_B| \qquad EN_{prom} = \frac{EN_A + EN_B}{2} \qquad \text{(las 2 coordenadas del triángulo de Katelaar)}$$

$$E_{\text{ion-ion}} \propto \frac{Q_1Q_2}{d} \quad E_{\text{ion-}\mu} \propto \frac{Q_1\mu_2}{d^2} \quad E_{\mu\text{-}\mu} \propto \frac{\mu_1\mu_2}{d^3} \quad E_{\text{ion-}\alpha} \propto \frac{Q_1\alpha_2}{d^4} \quad E_{\text{London}} \propto \frac{\alpha_1\alpha_2}{d^6}$$

$$E_c \propto T \qquad\qquad \begin{cases} E_c > E_p & \to \text{GAS} \\ E_c \approx E_p & \to \text{LÍQUIDO} \\ E_c < E_p & \to \text{SÓLIDO}\end{cases} \qquad\qquad RT_{25°C} \approx 2{,}5\ \text{kJ/mol}$$

$$\alpha \uparrow \iff n_{e^-} \uparrow \iff M_r \uparrow \;\Longrightarrow\; \text{London} \uparrow \;\Longrightarrow\; T_{eb} \uparrow$$
