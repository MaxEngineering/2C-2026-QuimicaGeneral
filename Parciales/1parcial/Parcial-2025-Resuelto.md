# 1er Parcial QG — 31 de marzo de 2025 — Resuelto

**Química General — ECyT / UNSAM**
**Archivo original:** `Parciales/1parcial/1er Parcial QG 1C 2025.pdf`

> Cada punto tiene el **razonamiento**, la **cuenta** y un bloque **📝 Respuesta tipo parcial** con lo que va en la hoja.

| Problema | Puntos | Tema |
|---|---|---|
| **1** | 25 | Espectroscopia · configuración electrónica · tabla periódica |
| **2** | 35 | Lewis · geometría · polaridad · fuerzas intermoleculares · solubilidad |
| **3** | 20 | Densidad de solución · diluciones |
| **4** | 20 | Mezcla de soluciones · iones · curvas de solubilidad |

⚠️ **El Problema 2 vale 35 puntos: es más de un tercio del parcial.** Si andás corto de tiempo, priorizalo.

---
---

# PROBLEMA 1 (25 puntos)

## 1a-i) Asignar las transiciones a las líneas del espectro del helio

> Líneas: **402,6 nm** (violeta) · **441,1 nm** (azul) · **492,2 nm** (azul-verde) · **706,5 nm** (rojo)
> Transiciones: **a)** 3s→2p · **b)** 5s→2p · **c)** 6s→2p · **d)** 4s→2p

### El razonamiento (una sola idea)

**Las cuatro transiciones terminan en el mismo nivel (2p).** Entonces lo único que las diferencia es **de dónde salen**. Y cuanto más alto arranca el electrón, **más grande es el salto**:

```
   6s ────────┐
   5s ──────┐ │
   4s ────┐ │ │
   3s ──┐ │ │ │        salto más grande  →  MÁS energía
        │ │ │ │                          →  MENOS λ  (más violeta)
        ▼ ▼ ▼ ▼
   2p ──────────
```

Y la relación energía–longitud de onda es **inversa**:

$$E = \frac{h\cdot c}{\lambda} \qquad\Longrightarrow\qquad \boxed{E \uparrow \;\Longleftrightarrow\; \lambda \downarrow}$$

Entonces basta con **ordenar**: el salto más grande va con la longitud de onda **más chica**.

### La asignación

| λ | Color | Transición | Salto | E (kJ/mol) |
|---|---|---|---|---|
| **402,6 nm** | violeta | **c) 6s→2p** | el **más grande** | 297,5 |
| **441,1 nm** | azul | **b) 5s→2p** | ↓ | 271,5 |
| **492,2 nm** | azul-verde | **d) 4s→2p** | ↓ | 243,4 |
| **706,5 nm** | rojo | **a) 3s→2p** | el **más chico** | 169,5 |

💡 **Chequeo con el color, sin hacer cuentas:** el **violeta es el extremo de alta energía** del visible y el **rojo el de baja**. El orden del arcoíris (rojo → naranja → amarillo → verde → azul → violeta) es de **menor a mayor** energía. Si tu asignación pone el salto más grande en el rojo, está al revés.

> 📝 **Respuesta tipo parcial**
>
> Las cuatro transiciones terminan en el **mismo nivel (2p)**, así que la diferencia de energía depende **sólo del nivel de partida**: cuanto **mayor** es *n* inicial, **mayor** es ΔE. Como $E = hc/\lambda$, a **mayor energía corresponde menor longitud de onda**.
>
> Ordenando de mayor a menor salto:
>
> | λ | Transición |
> |---|---|
> | **402,6 nm** (violeta, la de más energía) | **6s → 2p** |
> | **441,1 nm** (azul) | **5s → 2p** |
> | **492,2 nm** (azul-verde) | **4s → 2p** |
> | **706,5 nm** (rojo, la de menos energía) | **3s → 2p** |

## 1a-ii) Energía de la transición de 492,2 nm, en kJ/mol

**Paso 1 — λ a metros.** Las constantes están en SI:

```
λ = 492,2 nm = 492,2 × 10⁻⁹ m = 4,922 × 10⁻⁷ m
```

⚠️ **Si dejás los nm te da 10⁹ veces mal.** Es el error nº 1 de este ejercicio.

**Paso 2 — energía de UN fotón:**

```
E = h·c/λ = (6,63×10⁻³⁴ J·s × 3×10⁸ m/s) / 4,922×10⁻⁷ m

E = 1,989×10⁻²⁵ / 4,922×10⁻⁷  =  4,04×10⁻¹⁹ J
```

**Paso 3 — pasar a un MOL.** Los 4,04×10⁻¹⁹ J son de **un solo átomo**:

```
E_mol = 4,04×10⁻¹⁹ J × 6,022×10²³ mol⁻¹ = 2,43×10⁵ J/mol
```

**Paso 4 — a kJ/mol** (lo que piden):

```
2,43×10⁵ J/mol ÷ 1000 = 243,4 kJ/mol
```

💡 **Chequeo de magnitud:** las transiciones electrónicas caen siempre en **cientos de kJ/mol** (el orden de un enlace químico). Si te da 10⁻¹⁹, te olvidaste de N_A; si te da 10⁵, te olvidaste de pasar a kJ.

⚠️ **El enunciado no da N_A.** Hay que saberlo: **6,022×10²³ mol⁻¹**.

> 📝 **Respuesta tipo parcial**
>
> λ = 492,2 nm = 4,922×10⁻⁷ m
>
> $E = \dfrac{hc}{\lambda} = \dfrac{6{,}63\times10^{-34}\,\text{J·s} \times 3\times10^{8}\,\text{m/s}}{4{,}922\times10^{-7}\,\text{m}} = \mathbf{4{,}04\times10^{-19}\ J}$ (por átomo)
>
> Para un mol multiplico por el número de Avogadro:
>
> $E_{mol} = 4{,}04\times10^{-19}\ \text{J} \times 6{,}022\times10^{23}\ \text{mol}^{-1} = 2{,}43\times10^{5}\ \text{J/mol} = \mathbf{243{,}4\ kJ/mol}$

---

## 1b) Configuración electrónica externa (CEE) y estados excitados

> **Aluminio (Al, Z = 14)** y **Berilio (Be, Z = 4)**

### 🔴 Errata del enunciado

**El aluminio es Z = 13, no 14.** El Z = 14 corresponde al **silicio**. El símbolo (Al) y el nombre (Aluminio) coinciden entre sí, así que **el que está mal es el número**.

| Con Z = 13 (**Al**, lo correcto) | Con Z = 14 (sería **Si**) |
|---|---|
| 1s² 2s² 2p⁶ 3s² **3p¹** | 1s² 2s² 2p⁶ 3s² **3p²** |
| CEE = **3s² 3p¹** | CEE = 3s² 3p² |

👉 **En el parcial:** resolvelo con **Z = 13** y **aclarálo en la hoja** en una línea. Eso te cubre.

### i) Las CEE

**¿Qué es la CEE?** Los electrones del **último nivel** (el *n* más alto). Son los **electrones de valencia**, los que participan de los enlaces.

**Aluminio (Z = 13):**

```
CE completa:  1s² 2s² 2p⁶ 3s² 3p¹        (2+2+6+2+1 = 13 ✓)
                            └────┬────┘
CEE:  3s² 3p¹     → 3 e⁻ de valencia → grupo 13, período 3
```

**Berilio (Z = 4):**

```
CE completa:  1s² 2s²                     (2+2 = 4 ✓)
                  └─┬─┘
CEE:  2s²         → 2 e⁻ de valencia → grupo 2, período 2
```

### ii) Un estado excitado para cada uno

**Qué es un estado excitado:** la **misma cantidad de electrones**, pero con alguno **promovido** a un subnivel de mayor energía, dejando un hueco abajo. Tiene que ser **legal** (respetar s≤2, p≤6, d≤10) — si no, sería *imposible*, no *excitado*.

**Aluminio** — promuevo un electrón del 3s al 3p:

```
BASAL:     1s² 2s² 2p⁶ 3s² 3p¹
EXCITADO:  1s² 2s² 2p⁶ 3s¹ 3p²        13 e⁻ ✓  ·  3s incompleto con e⁻ en 3p
                          └── hueco
```

**Berilio** — promuevo un electrón del 2s al 2p:

```
BASAL:     1s² 2s²
EXCITADO:  1s² 2s¹ 2p¹                 4 e⁻ ✓  ·  2s incompleto con e⁻ en 2p
                └── hueco
```

⚠️ **Las dos cosas que se controlan:**
1. **Mismo número de electrones** que el basal (si cambia, es otro elemento o un ion).
2. Que **no viole ninguna capacidad** (si el subnivel se pasa del máximo, es **imposible**, no excitado).

> 📝 **Respuesta tipo parcial**
>
> *(Aclaración: el Aluminio tiene **Z = 13**; el enunciado indica 14, que corresponde al Si. Resuelvo con Z = 13.)*
>
> **i)** Al (Z = 13): 1s² 2s² 2p⁶ 3s² 3p¹ → **CEE = 3s² 3p¹** (3 e⁻ de valencia)
> Be (Z = 4): 1s² 2s² → **CEE = 2s²** (2 e⁻ de valencia)
>
> **ii)** Un estado excitado se obtiene **promoviendo un electrón a un subnivel superior**, manteniendo la misma cantidad total de electrones y sin violar ninguna capacidad:
>
> Al: **1s² 2s² 2p⁶ 3s¹ 3p²** — un electrón pasó del 3s al 3p (13 e⁻ ✓, el 3s queda incompleto).
> Be: **1s² 2s¹ 2p¹** — un electrón pasó del 2s al 2p (4 e⁻ ✓, el 2s queda incompleto).

---

## 1c) Grupo y período a partir de la CEE

> **A:** 1s² 2s² 2p⁴
> **B:** 1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d¹⁰ 4p⁶ 5s² 4d¹⁰ 5p⁶ 6s²

### 🔑 Las dos reglas

$$\boxed{\text{PERÍODO} = \text{el } n \text{ MÁS ALTO que aparece}}$$

$$\boxed{\text{GRUPO} = \text{electrones del último nivel } (s + p) \;\;/\;\; \text{o } s + d \text{ si es de transición}}$$

### Elemento A: 1s² 2s² 2p⁴

```
n más alto = 2                        → PERÍODO 2
electrones en n=2:  2s² 2p⁴ = 2+4 = 6 → 6 e⁻ de valencia → GRUPO 16
Z = 2+2+4 = 8                         → OXÍGENO
```

### Elemento B

**Contamos los electrones:**

```
1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d¹⁰ 4p⁶ 5s² 4d¹⁰ 5p⁶ 6s²
 2 + 2 + 6 + 2 + 6 + 2 + 10 + 6 + 2 + 10 + 6 + 2  =  56    → BARIO (Ba)
```

**Período:** el *n* más alto que aparece es **6** (en el 6s²) → **PERÍODO 6**

**Grupo:** el último nivel es el 6, y ahí sólo hay **6s²** → **2 e⁻ de valencia** → **GRUPO 2** (alcalinotérreo)

⚠️ **La trampa está acá.** El 4d¹⁰ y el 5p⁶ **no cuentan** para el grupo: pertenecen a niveles **4 y 5**, no al 6. Sólo cuenta lo que está en el **último nivel**.

⚠️ **Y ojo con el orden de llenado vs. el nivel:** el 4d se **llena** después del 5s, pero sigue siendo del **nivel 4**. Para el período mirás el número, no el orden.

> 📝 **Respuesta tipo parcial**
>
> El **período** es el mayor valor de *n* que aparece; el **grupo** sale de los electrones del **último nivel**.
>
> **A) 1s² 2s² 2p⁴** — el *n* más alto es **2** → **período 2**. En ese nivel hay 2s² 2p⁴ = **6 electrones** → **grupo 16**. (Z = 8: es el **oxígeno**.)
>
> **B) …5p⁶ 6s²** — el *n* más alto es **6** → **período 6**. En ese nivel sólo hay **6s²** = **2 electrones** → **grupo 2**. (Z = 56: es el **bario**.) Los subniveles 4d¹⁰ y 5p⁶ **no cuentan** para el grupo porque corresponden a niveles inferiores.

---
---
# PROBLEMA 2 (35 puntos)

> **Datos del enunciado:** Na y K (grupo 1); C y Si (grupo 14); N (grupo 15); O y Se (grupo 16); F, Cl y I (grupo 17).

⚠️ **El grupo te da los electrones de valencia**, que es lo que necesitás para Lewis. Grupo 1 → 1 e⁻ · 14 → 4 · 15 → 5 · 16 → 6 · 17 → 7.

## 2a) Estructuras de Lewis + electrones alrededor del átomo central

### 🔑 El método (6 pasos, siempre igual)

```
1. Contar e⁻ de VALENCIA totales   (+1 por carga −  ·  −1 por carga +)
2. Átomo CENTRAL = el MENOS electronegativo (nunca el H)
3. Unir con enlaces simples
4. Repartir el resto como pares libres, completando primero los EXTERNOS
5. ¿Al central le falta octeto? → enlaces MÚLTIPLES
6. Cargas formales:  CF = valencia − libres − enlazantes/2
```

---

### i) NH₄⁺ — catión amonio

**Electrones de valencia** (⚠️ el catión **RESTA**):

```
N:  5
4 H: 4 × 1 = 4
carga +1:  −1
──────────────
TOTAL:  8 e⁻  =  4 pares
```

**Estructura:**

```
              ⎡    H    ⎤ ⁺
              ⎢    |    ⎥
              ⎢ H— N —H ⎥        4 enlaces simples
              ⎢    |    ⎥        SIN pares libres
              ⎣    H    ⎦
```

**Los 8 electrones se usan enteros en los 4 enlaces. No sobra nada para pares libres.**

$$\boxed{\text{e}^-\text{ alrededor del N} = \mathbf{8} \quad\text{(octeto completo)}}$$

**Cargas formales:**

```
N:  5 − 0 − 8/2 = 5 − 0 − 4 = +1
H:  1 − 0 − 2/2 = 0          (los cuatro)

suma = +1  ✓  coincide con la carga del catión
```

💡 **De dónde sale el 4º enlace:** el N aporta su par libre completo a un H⁺ que no trae electrones. Es un **enlace dativo** (o coordinado). Una vez formado es **idéntico a los otros tres**: los cuatro enlaces N–H son iguales.

**Sin resonancia** (los 4 H son equivalentes y no hay enlaces múltiples).

---

### ii) NaNO₂ — nitrito de sodio

**Paso 0 — ¿iónico o covalente?** El **Na es un metal** (grupo 1) y el resto no metales → **compuesto IÓNICO**.

```
NaNO₂   →   Na⁺  +  NO₂⁻
```

⚠️ **NO se dibuja un enlace Na—O.** Se dibuja el catión **suelto** y el anión **entre corchetes con su carga**.

**Electrones de valencia del anión NO₂⁻** (⚠️ el anión **SUMA**):

```
N:   5
2 O: 2 × 6 = 12
carga −1:  +1
──────────────
TOTAL:  18 e⁻  =  9 pares
```

**Estructura:**

```
                ⎡  ¨       ¨¨ ⎤ ⁻
   Na⁺   +      ⎢ :O — N = O  ⎥         el N con 1 par libre
                ⎣  ¨¨  ¨      ⎦
```

**El recuento:**

| Átomo | Pares libres | Enlaces | Total |
|---|---|---|---|
| **N** | 1 par (2 e⁻) | simple (2) + doble (4) = 6 | **8** ✓ |
| **O** (doble) | 2 pares (4) | doble (4) | **8** ✓ |
| **O** (simple) | 3 pares (6) | simple (2) | **8** ✓ |

```
Electrones: 2 + 4 (enlaces) + 2 + 4 + 6 (pares libres) = 18 ✓
```

$$\boxed{\text{e}^-\text{ alrededor del N} = \mathbf{8} \quad\text{(octeto completo)}}$$

**Cargas formales:**

```
N:        5 − 2 − 6/2 = 0
O (doble): 6 − 4 − 4/2 = 0
O (simple):6 − 6 − 2/2 = −1

suma = −1  ✓  coincide con NO₂⁻
```

**⭐ RESONANCIA: SÍ, 2 estructuras.** Los dos oxígenos son **equivalentes**: el doble enlace puede estar en cualquiera de los dos.

```
   ⎡  ¨       ¨¨⎤⁻          ⎡ ¨¨       ¨ ⎤⁻
   ⎢ :O — N = O ⎥    ↔     ⎢  O = N — O: ⎥
   ⎣  ¨¨  ¨     ⎦           ⎣      ¨  ¨¨ ⎦
```

⚠️ La flecha es **↔** (doble punta), no ⇄. En la molécula real los **dos enlaces N–O son idénticos** (intermedios entre simple y doble) y la carga −1 está **repartida** (−½ en cada O).

---

### iii) IF₃ — trifluoruro de iodo

**Átomo central:** el **I** (EN 2,5 contra F 4,0). ⚠️ **El F nunca es central.**

**Electrones de valencia:**

```
I:   7
3 F: 3 × 7 = 21
──────────────
TOTAL:  28 e⁻  =  14 pares
```

**Estructura:**

```
              :F:
               |
      ⟨PL⟩ — I — F:            I con 2 pares libres
      ⟨PL⟩    |   ¨¨
              F:
              ¨¨
```

**El recuento:**

```
3 enlaces I—F:        6 e⁻
3 F × 3 pares libres: 18 e⁻
I con 2 pares libres:  4 e⁻
                      ────
                      28 ✓
```

$$\boxed{\text{e}^-\text{ alrededor del I} = 4 + 6 = \mathbf{10} \quad\text{⚠️ OCTETO EXPANDIDO}}$$

**Por qué puede:** el **I es del período 5** → tiene **orbitales d disponibles** → puede alojar más de 8 electrones.

**Cargas formales:** I = 7 − 4 − 3 = **0** · F = 7 − 6 − 1 = **0** (los tres) → suma 0 ✓

---

### iv) ClF₅ — pentafluoruro de cloro

**Átomo central:** el **Cl** (EN 3,0 contra F 4,0).

**Electrones de valencia:**

```
Cl:  7
5 F: 5 × 7 = 35
──────────────
TOTAL:  42 e⁻  =  21 pares
```

**Estructura:**

```
              F
              |
        F  ─  Cl  ─  F           Cl con 1 par libre
           ╱  |   ╲
          F   |    F
            ⟨PL⟩
```

**El recuento:**

```
5 enlaces Cl—F:       10 e⁻
5 F × 3 pares libres: 30 e⁻
Cl con 1 par libre:    2 e⁻
                      ────
                      42 ✓
```

$$\boxed{\text{e}^-\text{ alrededor del Cl} = 2 + 10 = \mathbf{12} \quad\text{⚠️ OCTETO EXPANDIDO}}$$

**Por qué puede:** el **Cl es del período 3** → tiene orbitales 3d disponibles.

**Cargas formales:** Cl = 7 − 2 − 5 = **0** · F = **0** (los cinco) → suma 0 ✓

---

### v) H₂SeO₃

**Átomo central:** el **Se** (EN más baja que O). Es un **oxoácido**, así que:

$$\boxed{\text{los H van sobre los OXÍGENOS, nunca sobre el átomo central}}$$

**Electrones de valencia:**

```
2 H: 2 × 1 = 2
Se:  6
3 O: 3 × 6 = 18
──────────────
TOTAL:  26 e⁻  =  13 pares
```

**Estructura:**

```
                  O
                  ‖
        H — O — Se — O — H          Se con 1 par libre
                  |
                ⟨PL⟩
```

**El recuento:**

| Átomo | Pares libres | Enlaces | Total |
|---|---|---|---|
| **Se** | 1 par (2) | 2 simples (4) + 1 doble (4) = 8 | **10** ⚠️ |
| **O** (=) | 2 pares (4) | doble (4) | **8** ✓ |
| **O** (–H) | 2 pares (4) | 2 simples (4) | **8** ✓ |
| **H** | 0 | simple (2) | **2** ✓ (dueto) |

```
Electrones: 8 (Se) + 4 (O–H) enlaces = 12 ... + 2 (Se) + 4 (O=) + 8 (2 OH) = 26 ✓
```

$$\boxed{\text{e}^-\text{ alrededor del Se} = 2 + 8 = \mathbf{10} \quad\text{⚠️ OCTETO EXPANDIDO}}$$

**Cargas formales:** Se = 6 − 2 − 4 = **0** · todos los O = **0** · H = **0** → suma 0 ✓

⚠️ **Por qué se expande el octeto.** Existe una alternativa que **respeta** el octeto (Se con 3 enlaces simples y un O⁻), pero da **CF: Se = +1 y O = −1**. Como el **Se es del período 4** y puede expandir, se prefiere la estructura con **todas las cargas formales en cero**.

💡 **Errata menor del enunciado:** lo llama *"ácido selénico"*, pero con **Se = +4** (hacé la cuenta: 2(+1) + Se + 3(−2) = 0) el nombre correcto es **ácido selenioso**. El *selénico* es el **H₂SeO₄** (Se = +6). No cambia nada del ejercicio.

---

### 📋 Resumen del 2a — que es lo que piden explícitamente

| | e⁻ de valencia | Central | **e⁻ alrededor del central** | Situación |
|---|---|---|---|---|
| **NH₄⁺** | 8 | N | **8** | octeto normal |
| **NO₂⁻** | 18 | N | **8** | octeto normal · **2 resonancias** |
| **IF₃** | 28 | I | **10** | ⚠️ **expandido** (período 5) |
| **ClF₅** | 42 | Cl | **12** | ⚠️ **expandido** (período 3) |
| **H₂SeO₃** | 26 | Se | **10** | ⚠️ **expandido** (período 4) |

---

## 2b) Geometrías, ángulos y esquema

### El método

```
1. Contar GRUPOS = enlaces + pares libres    (doble o triple = UN grupo)
2. Nº de grupos      →  GEOMETRÍA ELECTRÓNICA
3. Borrar los pares libres  →  GEOMETRÍA MOLECULAR
4. Pares libres  →  ACHICAN el ángulo  (<)
```

| | Grupos | Pares libres | **Geom. ELECTRÓNICA** | **Geom. MOLECULAR** | **Ángulo** |
|---|---|---|---|---|---|
| **NH₄⁺** | 4 | 0 | tetraédrica | **tetraédrica** | **109,5°** |
| **NO₂⁻** | 3 | 1 | trigonal plana | **angular** | **<120°** *(≈115°)* |
| **IF₃** | 5 | 2 | bipiramidal trigonal | **forma de T** | **<90° · <180°** |
| **ClF₅** | 6 | 1 | octaédrica | **pirámide de base cuadrada** | **<90° · <180°** |
| **H₂SeO₃** | 4 | 1 | tetraédrica | **piramidal trigonal** | **<109,5°** |

### Los esquemas

```
  NH₄⁺  tetraédrica              NO₂⁻  angular
                                        ⟨PL⟩
        H                                 |
        |                                 N
        N                                ╱ ╲
       ╱|╲                              O   O
      H H H          109,5°                     <120°


  IF₃  forma de T                ClF₅  pirámide de base cuadrada

        F                                  F
        |                                  |
 ⟨PL⟩ — I — F                        F ─── Cl ─── F
 ⟨PL⟩   |                               ╱  |  ╲
        F                              F   |   F
                                         ⟨PL⟩
   <90° y <180°                        <90° y <180°


  H₂SeO₃  piramidal trigonal (alrededor del Se)

           ⟨PL⟩
             |
             Se
            ╱|╲
      HO   O  OH        <109,5°
```

⚠️ **En el IF₃ los 2 pares libres van a posiciones ECUATORIALES** (tienen 2 vecinos a 90° en vez de 3). Por eso quedan los 3 F formando una T.
⚠️ **La forma de T no tiene ángulo de ~120°:** los pares libres ocupan dos de las tres posiciones ecuatoriales, así que no quedan dos átomos ecuatoriales entre los cuales medir.

---

## 2c) ¿Son polares?

### El criterio

$$\boxed{\text{NO POLAR} \iff \text{geometría SIMÉTRICA \textbf{y} sustituyentes TODOS IGUALES}}$$

Si hay **pares libres en el central** o **sustituyentes distintos**, los dipolos **no se cancelan** → **POLAR**.

| | Geometría molecular | ¿Simétrica? | ¿Sustituyentes iguales? | **Resultado** |
|---|---|---|---|---|
| **NH₄⁺** | tetraédrica | ✅ sí | ✅ 4 H | **μ = 0** *(ver nota)* |
| **NaNO₂** | — | — | — | **compuesto IÓNICO** |
| **IF₃** | forma de T | ❌ **no** (2 PL) | sí | **POLAR** |
| **ClF₅** | pirámide b. cuadrada | ❌ **no** (1 PL) | sí | **POLAR** |
| **H₂SeO₃** | piramidal trigonal | ❌ **no** (1 PL) | ❌ (O y OH) | **POLAR** |

⚠️ **NH₄⁺ — la sutileza.** Su **geometría es perfectamente simétrica**, así que los 4 dipolos N–H **se cancelan** y el momento dipolar es **cero**. Pero **es un CATIÓN**: tiene carga neta +1, así que interactúa fortísimo con el agua por **ion–dipolo**. No confundir "μ = 0" con "no interactúa".

⚠️ **NaNO₂ — no es una molécula.** Es un **compuesto iónico**: red de Na⁺ y NO₂⁻. No tiene sentido preguntarse si "la molécula" es polar, porque **no hay molécula**. El **anión NO₂⁻ sí es angular** (y por lo tanto tiene dipolo), pero el compuesto se describe por su **carácter iónico**.

> 📝 **Respuesta tipo parcial**
>
> **NH₄⁺:** geometría **tetraédrica simétrica** con cuatro sustituyentes iguales → los momentos dipolares de los enlaces **se cancelan**: **μ = 0**. No obstante, es un **catión**, con carga neta +1.
>
> **NaNO₂:** compuesto **IÓNICO** (Na⁺ + NO₂⁻); no corresponde hablar de polaridad molecular. El anión NO₂⁻ es angular y sí posee momento dipolar.
>
> **IF₃, ClF₅ y H₂SeO₃: POLARES.** En los tres el átomo central tiene **pares libres**, que rompen la simetría (forma de T, pirámide de base cuadrada y piramidal trigonal respectivamente): los dipolos de enlace **no se cancelan** y queda un **momento dipolar neto**. En el H₂SeO₃ se suma que los sustituyentes son distintos (=O y –OH).

---

## 2d) Ordenar por punto de ebullición creciente

> **CCl₄** (tetracloruro de carbono) · **CH₄** (metano) · **CH₂Cl₂** (diclorometano) · **CH₃OH** (metanol)

### El análisis, uno por uno

| | Geometría | ¿Polar? | ¿Unión H? | e⁻ (≈ α) | Fuerzas |
|---|---|---|---|---|---|
| **CH₄** | tetraédrica simétrica | ❌ no | ❌ | **10** | sólo **London** (débil) |
| **CH₃OH** | — | ✅ sí | ✅ **SÍ** (O–H) | **18** | **unión H** + dipolo + London |
| **CH₂Cl₂** | tetraédrica **asimétrica** | ✅ sí | ❌ | **42** | dipolo–dipolo + **London** |
| **CCl₄** | tetraédrica simétrica | ❌ no | ❌ | **74** | **sólo London, pero enorme** |

### El orden

$$\boxed{\text{CH}_4 \;<\; \text{CH}_2\text{Cl}_2 \;<\; \text{CH}_3\text{OH} \;<\; \text{CCl}_4}$$

```
CH₄        −161 °C
CH₂Cl₂       40 °C
CH₃OH        65 °C
CCl₄         77 °C
```

### La justificación (esto es lo que se corrige)

**1. CH₄ es el más bajo** — no polar, sólo London, y con apenas **10 electrones** es la molécula **menos polarizable** del grupo.

**2. CH₂Cl₂ (40 °C) sube mucho respecto del CH₄** — al reemplazar 2 H por 2 Cl la molécula pasa a ser **polar** (la geometría tetraédrica deja de ser simétrica porque los sustituyentes son distintos) y sobre todo **cuadruplica los electrones** (10 → 42), lo que dispara las fuerzas de London.

**3. CH₃OH (65 °C) supera al CH₂Cl₂ teniendo menos de la mitad de electrones (18 vs 42)** — porque tiene **UNIÓN HIDRÓGENO** (H unido a O). La unión H (~20 kJ/mol) le gana a la combinación dipolo–dipolo + London del CH₂Cl₂.

**4. ⚠️ CCl₄ (77 °C) es el MÁS ALTO, y no tiene unión H ni es polar** — porque con **74 electrones** sus fuerzas de **London** son tan grandes que superan a la unión hidrógeno del metanol.

$$\boxed{\text{London (5 kJ/mol) es MÁS fuerte que dipolo–dipolo (0,6 kJ/mol)}}$$

⚠️ **Éste es EL par que hay que tener de memoria:** **CCl₄ (77 °C) > CH₃OH (65 °C)**. Es el contraejemplo de "unión H ⇒ hierve más alto", que **sólo vale a masa/tamaño comparable**. Cuando la diferencia de polarizabilidad es enorme, **manda London**.

> 📝 **Respuesta tipo parcial**
>
> **Orden creciente: CH₄ < CH₂Cl₂ < CH₃OH < CCl₄**
>
> - **CH₄** (−161 °C): tetraédrica **simétrica**, **no polar**; sólo fuerzas de **London**, y con **10 e⁻** es la menos polarizable → el más bajo.
> - **CH₂Cl₂** (40 °C): sustituyentes distintos ⇒ **polar**; dipolo–dipolo **+ London** con **42 e⁻**.
> - **CH₃OH** (65 °C): tiene **H unido a O** ⇒ **UNIÓN HIDRÓGENO**, la más fuerte de las fuerzas moleculares; supera al CH₂Cl₂ pese a tener menos electrones (18 vs 42).
> - **CCl₄** (77 °C): **no polar y sin unión H**, pero con **74 electrones** sus fuerzas de **London** son tan intensas que **superan a la unión hidrógeno** del metanol.
>
> La conclusión general: **London es más fuerte que dipolo–dipolo**, y cuando la diferencia de polarizabilidad es grande, **domina sobre la unión hidrógeno**.

---

## 2e) ¿Cuál es más soluble en agua: KF, SiF₄ o I₂?

### La regla

$$\boxed{\text{LO SEMEJANTE DISUELVE A LO SEMEJANTE}}$$

El **agua es polar** y hace **uniones hidrógeno** entre sí. Para que algo se disuelva, las interacciones **soluto–agua** que se forman tienen que **compensar** las que hay que romper.

### El análisis

| | Tipo de sustancia | Interacción con el agua | Magnitud |
|---|---|---|---|
| **KF** | **IÓNICO** (K grupo 1 + F grupo 17) | **ion–dipolo** | **15 kJ/mol** |
| **SiF₄** | molecular **no polar** *(tetraédrica simétrica)* | dipolo–dipolo inducido | **< 1 kJ/mol** |
| **I₂** | molecular **no polar** *(homonuclear)* | dipolo–dipolo inducido | **< 1 kJ/mol** |

$$\boxed{\text{El más soluble en agua es el } \mathbf{KF}}$$

### Por qué

**El KF es iónico:** en agua se **disocia** en K⁺ y F⁻, y cada ion queda **hidratado** por moléculas de agua que lo rodean orientando su dipolo hacia él. Esa interacción **ion–dipolo (15 kJ/mol)** es lo bastante fuerte como para compensar la energía de red que hay que vencer.

```
        H   H                          H
         \ /                            \
          O                              O — H
          |                              |
   H₂O — K⁺ — OH₂            H — O — H···F⁻···H — O — H
          |                              |
          O                              O — H
         / \                            /
        H   H                          H
     ion–dipolo                     ion–dipolo
```

**El SiF₄ y el I₂ son no polares.** Aunque los enlaces **Si–F** son muy polares (ΔEN grande), la geometría **tetraédrica simétrica** hace que los cuatro dipolos **se cancelen**: μ = 0. Y el I₂ es homonuclear, así que también μ = 0. Con el agua sólo pueden hacer **dipolo–dipolo inducido**, la interacción **más débil de la tabla** — no alcanza para romper la red de puentes de hidrógeno del agua.

> 📝 **Respuesta tipo parcial**
>
> El **más soluble en agua es el KF**.
>
> El KF es un compuesto **iónico** (K, grupo 1, metal + F, grupo 17, no metal): en agua se **disocia** en K⁺ y F⁻, que quedan **hidratados** mediante interacciones **ion–dipolo** (~15 kJ/mol), suficientemente intensas para compensar la energía de red.
>
> El **SiF₄** es molecular y, aunque sus enlaces Si–F son polares, su geometría **tetraédrica simétrica** hace que los dipolos **se cancelen** (μ = 0). El **I₂** es homonuclear y también **no polar**. Ambos sólo pueden interactuar con el agua por **dipolo–dipolo inducido**, la más débil de las interacciones, incapaz de compensar la ruptura de las uniones hidrógeno del agua. Por eso son **prácticamente insolubles**.
>
> Aplica el criterio **"lo semejante disuelve a lo semejante"**: el agua, polar, disuelve especies iónicas o polares, no las no polares.

---
---
# PROBLEMA 3 (20 puntos)

## 3a) Densidad de una solución de HCl

> HCl **2,9 % m/m**, **0,820 M**. Calcular la densidad en g/cm³.
> Ar(Cl) = 35,5 · Ar(H) = 1

### El razonamiento

Me dan **dos concentraciones de la misma solución** y me piden la densidad. La densidad es justamente **el puente** entre una unidad basada en **masa** (% m/m) y una basada en **volumen** (M): por eso el problema cierra.

$$\boxed{M = \frac{\%m/m \cdot \delta_{sc} \cdot 10}{Mr}} \qquad\Longrightarrow\qquad \boxed{\delta_{sc} = \frac{M \cdot Mr}{\%m/m \cdot 10}}$$

### La cuenta

```
Mr(HCl) = 1 + 35,5 = 36,5 g/mol

δ = (0,820 × 36,5) / (2,9 × 10) = 29,93 / 29 = 1,032 g/cm³
```

$$\boxed{\delta = 1{,}03\ \text{g/cm}^3}$$

### Si no te acordás la fórmula — el camino largo

Es el que conviene si dudás. **Tomás 1 litro de solución como base** y calculás todo:

| Paso | Cuenta | Resultado |
|---|---|---|
| 1. Moles en 1 L | $0{,}820\ \text{M} \times 1\ \text{L}$ | 0,820 mol |
| 2. Masa de HCl | $0{,}820 \times 36{,}5$ | **29,93 g** |
| 3. Masa de solución *(el HCl es el 2,9 %)* | $29{,}93 / 0{,}029$ | **1032 g** |
| 4. Densidad | $1032\ \text{g} / 1000\ \text{cm}^3$ | **1,032 g/cm³** |

**Verificación:** $(2{,}9 \times 1{,}032 \times 10)/36{,}5 = 0{,}820$ M ✓

💡 **Chequeo de razonabilidad:** una solución acuosa **diluida** (2,9 %) tiene que dar δ **muy cerca de 1,00 g/mL**, apenas por encima porque el HCl disuelto la hace un poco más densa. **1,03 es perfecto.** Si te hubiera dado 0,94 o 1,40, habría un error.

> 📝 **Respuesta tipo parcial**
>
> La densidad vincula la concentración en masa (% m/m) con la de volumen (M):
>
> $$M = \frac{\%m/m \cdot \delta \cdot 10}{Mr} \quad\Longrightarrow\quad \delta = \frac{M \cdot Mr}{\%m/m \cdot 10}$$
>
> Con Mr(HCl) = 1 + 35,5 = **36,5 g/mol**:
>
> $$\delta = \frac{0{,}820 \times 36{,}5}{2{,}9 \times 10} = \frac{29{,}93}{29} = \mathbf{1{,}03\ g/cm^3}$$
>
> *Verificación tomando 1 L de solución:* contiene 0,820 mol = 29,93 g de HCl; si eso es el 2,9 % en masa, la solución pesa 29,93/0,029 = 1032 g, y δ = 1032 g / 1000 cm³ = **1,032 g/cm³** ✓

---

## 3b) Dos diluciones desde una solución 0,850 M

> Material: un matraz de **50 mL** y uno de **100 mL**.
> **Solución A:** 50 mL de **0,425 M** · **Solución B:** 100 mL de **0,255 M**

### La fórmula y de dónde sale

$$\boxed{C_0 V_0 = C_F V_F}$$

Vale porque **al diluir sólo se agrega solvente: los MOLES de soluto no cambian**. Los dos lados de esa igualdad **son los moles**.

⚠️ **Las unidades se cancelan:** podés trabajar en mL de los dos lados, no hace falta pasar a litros.

### Solución A — 50 mL de 0,425 M

```
V₀ = (C_F × V_F) / C₀ = (0,425 × 50) / 0,850 = 21,25 / 0,850 = 25 mL
```

**Factor de dilución:**

```
f = C₀ / C_F = 0,850 / 0,425 = 2      →   dilución  1:2
```

💡 Se ve a ojo: **0,425 es la mitad de 0,850**, así que hay que diluir a la mitad. Y la mitad de 50 mL es 25 mL ✓

### Solución B — 100 mL de 0,255 M

```
V₀ = (0,255 × 100) / 0,850 = 25,5 / 0,850 = 30 mL
```

**Factor de dilución:**

```
f = 0,850 / 0,255 = 3,33      →   dilución  1:3,33
```

**Verificación:** $V_F/V_0 = 100/30 = 3{,}33$ ✓

### 📋 Resumen

| | Alícuota (V₀) | Matraz (V_F) | Agua a agregar | **Factor** |
|---|---|---|---|---|
| **Solución A** (0,425 M) | **25 mL** | 50 mL | 25 mL | **1:2** |
| **Solución B** (0,255 M) | **30 mL** | 100 mL | 70 mL | **1:3,33** |

⚠️ **"1:2" NO es "1 parte + 2 de agua"** (eso sería 1:3). Es **1 volumen llevado a 2 volúmenes TOTALES** = 1 de solución + 1 de agua.

$$\boxed{1{:}n \;\Rightarrow\; \text{1 de solución} + (n-1)\ \text{de agua}}$$

> 📝 **Respuesta tipo parcial — procedimiento**
>
> Como al diluir **los moles de soluto se conservan**, vale $C_0V_0 = C_FV_F$.
>
> **Solución A (50 mL, 0,425 M):**
> $V_0 = \dfrac{0{,}425 \times 50}{0{,}850} = \mathbf{25\ mL}$ · **factor de dilución = 0,850/0,425 = 1:2**
>
> 1. Medir **25 mL** de la solución 0,850 M con **pipeta** (y propipeta).
> 2. Volcarlos en el **matraz aforado de 50 mL**, que ya tenga algo de agua destilada.
> 3. **Enrasar** con agua destilada hasta el aforo, leyendo el menisco por su parte inferior y a la altura de la vista.
> 4. **Homogeneizar** invirtiendo el matraz varias veces.
>
> **Solución B (100 mL, 0,255 M):**
> $V_0 = \dfrac{0{,}255 \times 100}{0{,}850} = \mathbf{30\ mL}$ · **factor de dilución = 0,850/0,255 = 1:3,33**
>
> Mismo procedimiento: **30 mL** de la solución madre al **matraz de 100 mL** y enrasar.
>
> ⚠️ En ninguno de los dos casos se mide el agua: se **enrasa al aforo**, porque los volúmenes **no son aditivos**.

---
---

# PROBLEMA 4 (20 puntos)

## 4a) Mezcla de dos soluciones — concentración de K⁺

> **300 mL** de KCl al **4 % m/V** + **400 mL** de K₂Cr₂O₇ **0,017 M**. Volúmenes aditivos.
> Ar: Cl = 35,5 · K = 39,1 · Cr = 52,0 · O = 16,0

### ⚠️ La clave del ejercicio

**Los dos solutos son distintos, pero los dos aportan K⁺.** No se trata de una mezcla común: hay que **sumar los moles de potasio que aporta cada uno**.

Y acá está la trampa:

$$\text{KCl} \rightarrow \text{K}^+ + \text{Cl}^- \qquad\qquad \text{K}_2\text{Cr}_2\text{O}_7 \rightarrow \mathbf{2}\,\text{K}^+ + \text{Cr}_2\text{O}_7^{2-}$$

⚠️ **El dicromato aporta DOS K⁺ por unidad fórmula.** El subíndice **multiplica**.

### Masas molares

```
Mr(KCl)      = 39,1 + 35,5                    = 74,6 g/mol
Mr(K₂Cr₂O₇)  = 2(39,1) + 2(52,0) + 7(16,0)
             = 78,2 + 104,0 + 112,0           = 294,2 g/mol
```

### Paso 1 — K⁺ que aporta el KCl

El **4 % m/V** significa **4 g cada 100 mL**:

```
m(KCl) = 4 g/100 mL × 300 mL = 12 g

n(KCl) = 12 / 74,6 = 0,1609 mol

n(K⁺) = 1 × 0,1609 = 0,1609 mol        (1 K por fórmula)
```

### Paso 2 — K⁺ que aporta el K₂Cr₂O₇

```
n(K₂Cr₂O₇) = M × V(L) = 0,017 × 0,400 = 0,0068 mol

n(K⁺) = 2 × 0,0068 = 0,0136 mol        ⚠️ ¡POR DOS!
```

### Paso 3 — sumar y dividir por el volumen total

```
n(K⁺) total = 0,1609 + 0,0136 = 0,1745 mol

V total = 300 + 400 = 700 mL = 0,700 L        (volúmenes aditivos)
```

$$[\text{K}^+] = \frac{0{,}1745\ \text{mol}}{0{,}700\ \text{L}} = \boxed{0{,}249\ \text{M}}$$

### ⚠️ Los cuatro errores de este ejercicio

| ❌ Error | ✅ Correcto |
|---|---|
| Olvidar el **×2** del dicromato | El K₂Cr₂O₇ libera **2 K⁺** por unidad fórmula |
| Interpretar 4 % m/V como 4 g en 300 mL | Es **4 g cada 100 mL** → en 300 mL hay **12 g** |
| Dividir por 300 o por 400 mL | El volumen es el **TOTAL: 700 mL** |
| Dejar el volumen en mL en la molaridad | La **M va en LITROS**: 0,700 L |

💡 **Observación:** el KCl aporta el **92 %** del potasio (0,161 de 0,175 mol) aunque el dicromato tenga dos K por fórmula — porque hay **mucho más KCl** (0,161 mol contra 0,0068 mol).

> 📝 **Respuesta tipo parcial**
>
> Ambas sales aportan K⁺, y hay que considerar la **estequiometría de disociación** de cada una:
>
> $$\text{KCl} \rightarrow \text{K}^+ + \text{Cl}^- \qquad \text{K}_2\text{Cr}_2\text{O}_7 \rightarrow \mathbf{2}\,\text{K}^+ + \text{Cr}_2\text{O}_7^{2-}$$
>
> **Del KCl** — el 4 % m/V son 4 g cada 100 mL:
> $m = 4 \times 3 = 12$ g · $Mr = 39{,}1 + 35{,}5 = 74{,}6$ g/mol · $n = 12/74{,}6 = 0{,}1609$ mol
> $n(\text{K}^+) = 0{,}1609$ mol
>
> **Del K₂Cr₂O₇:**
> $n = 0{,}017 \times 0{,}400 = 0{,}0068$ mol · $n(\text{K}^+) = 2 \times 0{,}0068 = \mathbf{0{,}0136}$ mol
>
> **Total:** $n(\text{K}^+) = 0{,}1609 + 0{,}0136 = 0{,}1745$ mol en $V = 300 + 400 = 700\ \text{mL} = 0{,}700$ L
>
> $$[\text{K}^+] = \frac{0{,}1745}{0{,}700} = \mathbf{0{,}249\ M}$$

---

## 4b) Curvas de solubilidad

### El gráfico, transcripto a tabla

Solubilidad en **g/L** vs temperatura (°C). Valores leídos del gráfico:

| T (°C) | 0 | 10 | 20 | 30 | 40 | 50 | 60 | 70 | 80 | 90 | 100 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| **Pb(NO₃)₂** | 370 | **460** | 555 | 650 | 750 | 845 | 950 | — | — | — | — |
| **KCl** | 270 | 300 | 330 | 355 | 388 | 415 | 448 | 475 | 518 | **548** | 578 |
| **K₂Cr₂O₇** | 55 | 80 | 112 | 165 | 222 | 302 | 380 | 470 | 590 | **698** | 825 |

⚠️ **La unidad es g/L, no g/100 g.** Acá se escala por **litros de agua**, no por centenas de gramos.

💡 **Las tres curvas SUBEN con la temperatura** (son sales, disolución endotérmica). Lo que las diferencia es la **pendiente**: el K₂Cr₂O₇ es de lejos el **más sensible** (de 55 a 825 g/L), y el KCl el **menos** (de 270 a 578).

### i) Temperatura donde el K₂Cr₂O₇ es más soluble que el KCl

**El razonamiento.** A temperatura baja el **KCl es más soluble** (270 vs 55 g/L a 0 °C). Pero el K₂Cr₂O₇ **sube mucho más rápido**, así que en algún punto **lo cruza**:

```
 g/L
 800 ┤                                            K₂Cr₂O₇ ╱
 700 ┤                                                  ╱
 600 ┤                                              ╱
 500 ┤                             ✕ ← se cruzan ~73 °C  ___──── KCl
 400 ┤                  ╱____────────
 300 ┤ KCl ────────
 200 ┤        ╱
 100 ┤   ╱
   0 └─────────────────────────────────────────────────────
     0   10  20  30  40  50  60  70  80  90  100   T (°C)
```

**Se cruzan aproximadamente a los 73 °C** (~490 g/L). **De ahí para arriba, el dicromato gana.**

**Elijo T = 90 °C:**

```
K₂Cr₂O₇  ≈ 700 g/L
KCl      ≈ 550 g/L        →  700 > 550 ✓
```

*(También sirve 80 °C: 590 vs 518 · o 100 °C: 825 vs 578.)*

> 📝 **Respuesta tipo parcial**
>
> A bajas temperaturas el KCl es más soluble, pero la curva del **K₂Cr₂O₇ tiene mucha mayor pendiente** y ambas se **cruzan alrededor de los 73 °C** (~490 g/L). **Por encima de esa temperatura el dicromato de potasio es más soluble que el cloruro de potasio.**
>
> Por ejemplo, a **T = 90 °C**:
> - **K₂Cr₂O₇ ≈ 700 g/L**
> - **KCl ≈ 550 g/L**

### ii) ¿Se disuelven 500 g de Pb(NO₃)₂ en 1 L de agua a 10 °C?

**Paso 1 — leer la solubilidad a 10 °C:**

```
S(Pb(NO₃)₂, 10 °C) ≈ 460 g/L
```

**Paso 2 — máximo que puede disolverse en 1 L:**

```
máx = 460 g/L × 1 L = 460 g
```

**Paso 3 — comparar:**

```
500 g  >  460 g        →   NO se disuelve todo
```

**Paso 4 — la resta (⚠️ el paso que se olvida):**

```
se disuelven:  460 g
precipitan:    500 − 460 = 40 g
```

$$\boxed{\text{NO. Se disuelven} \approx 460\ \text{g y precipitan} \approx 40\ \text{g}}$$

### Cómo queda el sistema

```
        ┌─────────────┐
        │  SOLUCIÓN   │  ← 460 g disueltos en 1 L de agua
        │  SATURADA   │     (está justo en el límite: c = S)
        │▒▒▒▒▒▒▒▒▒▒▒▒▒│  ← 40 g de Pb(NO₃)₂ sin disolver
        └─────────────┘
```

⚠️ La solución de arriba queda **SATURADA**, **no sobresaturada**. El exceso **precipita**: en equilibrio no puede quedar disuelto más que S.
⚠️ **Sistema HETEROGÉNEO: 2 fases** (líquida + sólida).

💡 **Cómo disolverlo todo:** **calentar**. Con S = 500 g/L alcanza, y según el gráfico eso ocurre a unos **14 °C** — subiendo apenas 4 grados ya entra todo.

> 📝 **Respuesta tipo parcial**
>
> **No, no se disuelven los 500 g.**
>
> Del gráfico, la solubilidad del Pb(NO₃)₂ a **10 °C** es aproximadamente **460 g/L**. En 1 litro de agua, entonces, la masa máxima que puede disolverse es **≈ 460 g**.
>
> Como 500 g > 460 g, la solución se **satura** y el excedente **precipita**:
>
> - **Soluto disuelto ≈ 460 g** (solución **saturada**)
> - **Soluto precipitado ≈ 500 − 460 = 40 g**
>
> El sistema resultante es **heterogéneo (2 fases)**: la solución saturada y el sólido sin disolver.

---
---

# 📋 TODAS LAS RESPUESTAS, JUNTAS

| Punto | Respuesta |
|---|---|
| **1a-i** | 402,6 → **6s→2p** · 441,1 → **5s→2p** · 492,2 → **4s→2p** · 706,5 → **3s→2p** |
| **1a-ii** | E = 4,04×10⁻¹⁹ J → **243,4 kJ/mol** |
| **1b-i** | Al (Z=13): **CEE 3s² 3p¹** · Be: **CEE 2s²** |
| **1b-ii** | Al: **1s² 2s² 2p⁶ 3s¹ 3p²** · Be: **1s² 2s¹ 2p¹** |
| **1c** | A: **grupo 16, período 2** (O) · B: **grupo 2, período 6** (Ba) |
| **2a** | e⁻ alrededor del central: NH₄⁺ **8** · NO₂⁻ **8** (2 resonancias) · IF₃ **10** · ClF₅ **12** · H₂SeO₃ **10** |
| **2b** | tetraédrica 109,5° · angular <120° · forma de T <90°/<180° · pirámide b. cuadrada <90°/<180° · piramidal trigonal <109,5° |
| **2c** | NH₄⁺ **μ = 0** (catión) · NaNO₂ **iónico** · IF₃, ClF₅, H₂SeO₃ **POLARES** |
| **2d** | **CH₄ < CH₂Cl₂ < CH₃OH < CCl₄** |
| **2e** | **KF** (iónico → ion–dipolo) |
| **3a** | **δ = 1,03 g/cm³** |
| **3b** | A: **25 mL**, factor **1:2** · B: **30 mL**, factor **1:3,33** |
| **4a** | **[K⁺] = 0,249 M** |
| **4b-i** | Cruce ≈ **73 °C**. A 90 °C: K₂Cr₂O₇ ≈ **700 g/L** > KCl ≈ **550 g/L** |
| **4b-ii** | **No.** Se disuelven ≈ **460 g**, precipitan ≈ **40 g** |

---

# 🚨 LAS 12 TRAMPAS DE ESTE PARCIAL

| # | Dónde | La trampa | Cómo evitarla |
|---|---|---|---|
| 1 | **1a-i** | Asignar al revés (salto grande ↔ λ grande) | $E = hc/\lambda$: **más energía = MENOS λ**. El violeta es el de más energía |
| 2 | **1a-ii** | Dejar λ en **nm** | Pasala a **metros**: 492,2 nm = 4,922×10⁻⁷ m |
| 3 | **1a-ii** | Olvidar **×N_A** o el ÷1000 | El fotón es de **un átomo**. Y piden **kJ**/mol |
| 4 | **1b** | Usar el **Z = 14** del enunciado | El Al es **Z = 13** (14 es el Si). Aclaralo en la hoja |
| 5 | **1c** | Contar 4d¹⁰ y 5p⁶ para el grupo de B | Sólo cuenta el **último nivel**: 6s² → grupo 2 |
| 6 | **2a-i** | **Sumar** el electrón por la carga + | El **catión RESTA** (8 e⁻, no 10) |
| 7 | **2a-ii** | Dibujar un enlace **Na—O** | El NaNO₂ es **iónico**: Na⁺ + [NO₂]⁻ separados |
| 8 | **2a-iii/iv** | Forzar el octeto en I y Cl | **Períodos 5 y 3** → **expanden**: 10 y 12 e⁻ |
| 9 | **2a-v** | Poner los H sobre el Se | Es un **oxoácido**: los H van **sobre los O** |
| 10 | **2d** | Poner el CH₃OH arriba de todo "porque tiene unión H" | **CCl₄ (77 °C) > CH₃OH (65 °C)**: gana **London** (74 e⁻) |
| 11 | **4a** | Olvidar el **×2** del K₂Cr₂O₇ | Libera **2 K⁺** por unidad fórmula |
| 12 | **4b-ii** | Contestar sólo "no se disuelve" | Hay que dar **cuánto se disuelve Y cuánto precipita** |

---

# 🎯 Comparación con el otro parcial tipo

| Tema | Este (2025) | `EjTipoParcial-Resuelto.md` |
|---|---|---|
| **Espectroscopia** | asignar transiciones + kJ/mol | calcular ν, E y kJ/mol |
| **Config. electrónica** | CEE + excitados + grupo/período | basal/excitada/imposible + isoelectrónicos |
| **Lewis** | 5 compuestos + e⁻ del central | 4 compuestos + cargas formales |
| **Geometría** | ⭐ **sí, con ángulos y esquema** | no |
| **Polaridad** | ⭐ **sí** | no |
| **Fuerzas intermol.** | ⭐ **sí (orden de T_eb)** | no |
| **Solubilidad cualitativa** | ⭐ **sí (KF/SiF₄/I₂)** | no |
| **Soluciones** | densidad + diluciones + iones | % m/m, dilución, % v/v |
| **Curvas de solubilidad** | sí (g/L) | sí (% m/m_sv) |

⚠️ **El de 2025 cubre bastante MÁS materia**: entra toda la Clase 3 (polaridad) y Clase 4 (fuerzas intermoleculares), que el otro no toca. **Hacé los dos.**

---

> **Teoría:** `Clase1/` · `Clase2/` · `Clase3/` · `Clase4/` · `Clase6(5nohay)/`
> **Machete:** secciones 2–6 (espectro, C.E., tabla) · 7–13 (Lewis, TRePEV, polaridad, fuerzas) · 14–19 (soluciones)
> **Series:** `Practica/Serie1-Resuelta.md` · `Serie2-Resuelta.md` · `Serie3-Resuelta.md` · `Serie4-Resuelta.md`
> **Otro parcial:** `Parciales/1parcial/EjTipoParcial-Resuelto.md`
