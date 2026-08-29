# Ejercicio Tipo Parcial — Resuelto paso a paso

**Química General — ECyT / UNSAM · 2C 2026 · 1er Parcial**
**Archivo original:** `Parciales/1parcial/EjTipo parcial.pdf`

> **Cómo usar este archivo:** cada punto tiene el **razonamiento** (por qué se hace lo que se hace), la **cuenta** con los números puestos, y un bloque **📝 Respuesta tipo parcial** con lo que hay que escribir en la hoja. Lo que va entre 📝 es lo que se corrige; el resto es para que entiendas de dónde sale.

## 🗺️ Qué evalúa cada problema

| Problema | Tema | De dónde sale |
|---|---|---|
| **1** | Espectroscopia · configuración electrónica · iones | Clase 1 · Serie 1 |
| **2** | Lewis · cargas formales · resonancia | Clase 2 · Serie 2 |
| **3** | Lewis con excepciones al octeto | Clase 2 · Serie 2 |
| **4** | Soluciones · diluciones · solubilidad | Clase 6 · Serie 4 |

⚠️ **El parcial es acumulativo y en orden cronológico.** El Problema 4 vale tanto como los otros tres y es el más mecánico: **si andás corto de tiempo, empezá por el 4**.

---
---

# PROBLEMA 1

## 1a) Espectroscopia — línea de emisión a 410 nm

**Datos:** N_A = 6,02×10²³ · h = 6,63×10⁻³⁴ J·s · c = 3,0×10⁸ m/s · 1 Hz = 1 s⁻¹

### El razonamiento

Un átomo excitado **emite un fotón** al volver a un estado de menor energía. Ese fotón se lleva **exactamente** la diferencia de energía entre los dos estados:

```
    ────────  estado excitado
        │
        │  ΔE  ──────►  fotón de 410 nm
        ▼
    ────────  estado fundamental

        ΔE = E_fotón = h · ν
```

Por eso la pregunta "¿cuál es la diferencia de energía?" se contesta calculando **la energía del fotón**. Son el mismo número.

### i) Frecuencia y energía

**Paso 1 — pasar la longitud de onda a metros.** Las constantes están en el SI, así que λ tiene que estar en metros:

```
λ = 410 nm = 410 × 10⁻⁹ m = 4,10 × 10⁻⁷ m
```

⚠️ **Éste es el error nº 1 del ejercicio.** Si dejás 410 nm te da todo 10⁹ veces mal.

**Paso 2 — frecuencia**, con `c = λ · ν`:

```
ν = c / λ = (3,0 × 10⁸ m/s) ÷ (4,10 × 10⁻⁷ m)

ν = 7,32 × 10¹⁴ Hz
```

Fijate las unidades: `(m/s) ÷ m = 1/s = s⁻¹ = Hz` ✓

**Paso 3 — energía del fotón**, con `E = h · ν`:

```
E = 6,63 × 10⁻³⁴ J·s × 7,32 × 10¹⁴ s⁻¹

E = 4,85 × 10⁻¹⁹ J
```

💡 **Atajo (una sola cuenta):** combinando las dos fórmulas, `E = hc/λ`:

```
E = (6,63×10⁻³⁴ × 3,0×10⁸) / 4,10×10⁻⁷ = 1,989×10⁻²⁵ / 4,10×10⁻⁷ = 4,85×10⁻¹⁹ J ✓
```

El producto **h·c = 1,989×10⁻²⁵ J·m** conviene tenerlo anotado: ahorra un paso.

### ii) Energía por mol

**El razonamiento:** los 4,85×10⁻¹⁹ J son de **UN solo átomo**. Para pasar a un mol hay que multiplicar por Avogadro, que es cuántos átomos hay en un mol:

```
E_mol = E × N_A = 4,85×10⁻¹⁹ J × 6,02×10²³ 1/mol

E_mol = 2,92 × 10⁵ J/mol = 292 kJ/mol
```

💡 **Chequeo de magnitud:** las transiciones electrónicas dan siempre **cientos de kJ/mol** — del orden de la energía de un enlace químico (150–1000 kJ/mol). Si te da 10⁻¹⁹ J/mol, te olvidaste de multiplicar por N_A.

> 📝 **Respuesta tipo parcial**
>
> **i)** Paso λ a metros: λ = 410 nm = 4,10×10⁻⁷ m.
>
> Frecuencia: ν = c/λ = (3,0×10⁸ m/s)/(4,10×10⁻⁷ m) = **7,32×10¹⁴ Hz**
>
> Energía del fotón: E = h·ν = 6,63×10⁻³⁴ J·s × 7,32×10¹⁴ s⁻¹ = **4,85×10⁻¹⁹ J**
>
> Como la energía del fotón emitido es exactamente la diferencia entre los dos niveles, **ΔE = 4,85×10⁻¹⁹ J**.
>
> **ii)** Esa energía corresponde a **un** átomo. Para un mol multiplico por N_A:
>
> E_mol = 4,85×10⁻¹⁹ J × 6,02×10²³ mol⁻¹ = **2,92×10⁵ J/mol = 292 kJ/mol**

💡 **Detalle fino (por si lo preguntan):** los 410 nm son luz **violeta** y en realidad corresponden a la **serie de Balmer** (n=6 → n=2), que termina en el **primer estado excitado**, no en el fundamental. El enunciado lo simplifica. Para la cuenta no cambia nada: la energía del fotón siempre es la diferencia entre **los dos niveles involucrados**.

---

## 1b) Configuraciones electrónicas: basal, excitada o imposible

### El método — tres preguntas, siempre en este orden

```
1. ¿VIOLA una regla?   (capacidad de subnivel, o subnivel inexistente)
      SÍ → IMPOSIBLE. Contar los e⁻ y escribir la basal de ese elemento.
2. ¿Respeta el orden de llenado (diagonales)?
      SÍ → BASAL
      NO → EXCITADA   (los e⁻ son válidos, pero están "arriba" de donde deberían)
```

**Las capacidades, que hay que tener de memoria:**

| Subnivel | s | p | d | f |
|---|---|---|---|---|
| **Máximo de e⁻** | **2** | **6** | **10** | **14** |

**Y el orden de llenado (diagonales):**

```
1s 2s 2p 3s 3p 4s 3d 4p 5s 4d 5p 6s 4f 5d 6p 7s 5f 6d
```

⚠️ **La clave de todo el ejercicio:** *"imposible"* es que **rompa una regla** (3s³, 6p⁷). *"Excitada"* es que sea **legal pero desordenada** — un electrón que saltó a un subnivel más alto dejando un hueco abajo.

### I) 1s² 2s² 2p⁶ 3s² 3p⁶ 4s¹

```
e⁻ totales = 2+2+6+2+6+1 = 19  →  Z = 19 = POTASIO (K)
```

- Ningún subnivel excedido ✓
- ¿Sigue las diagonales? 1s→2s→2p→3s→3p→**4s** ✓ (después del 3p va el **4s**, no el 3d)

$$\boxed{\textbf{BASAL}}$$

💡 Es justamente el caso que muestra por qué el 4s se llena antes que el 3d.

### II) 1s² 2s¹ 2p⁶ 3s³

```
                        └── 3s³  ⚠️  el subnivel s admite MÁXIMO 2 e⁻
```

$$\boxed{\textbf{IMPOSIBLE}}$$

**La basal:** cuento los electrones tal como están escritos y armo la configuración correcta.

```
e⁻ totales = 2+1+6+3 = 12  →  Z = 12 = MAGNESIO (Mg)

Basal:  1s² 2s² 2p⁶ 3s²      (= [Ne] 3s²)
```

⚠️ Fijate que **también** el 2s¹ estaba mal (debería ser 2s²), pero con encontrar **una** violación ya alcanza para declararla imposible.

### III) 1s² 2s² 2p⁶ 3s¹ 3p⁵

```
e⁻ totales = 2+2+6+1+5 = 16  →  Z = 16 = AZUFRE (S)
```

- ¿Capacidades? 3s¹ (≤2 ✓) · 3p⁵ (≤6 ✓) → **es legal**
- ¿Orden? El 3s tiene **un hueco** (3s¹) y sin embargo hay electrones en el 3p. Un electrón del 3s **saltó** al 3p.

```
   3p ─ ↑↓ ↑  ↑            3p ─ ↑↓ ↑  ↑  ↑
   3s ─ ↑           ←→     3s ─ ↑↓
   
     EXCITADA                  BASAL
```

$$\boxed{\textbf{EXCITADA}}$$

**La basal del S:** `1s² 2s² 2p⁶ 3s² 3p⁴` (= [Ne] 3s² 3p⁴)

### IV) [Ar] 4s² 4p⁶

```
e⁻ totales = 18 + 2 + 6 = 26  →  Z = 26 = HIERRO (Fe)
```

- ¿Capacidades? 4s² ✓ · 4p⁶ ✓ → **legal**
- ¿Orden? ⚠️ Después del **4s** viene el **3d**, no el 4p. Los 6 electrones están en el 4p con el **3d completamente vacío**.

$$\boxed{\textbf{EXCITADA}}$$

**La basal del Fe:** `[Ar] 4s² 3d⁶`

⚠️ **Ésta es la trampa del ejercicio.** Como no viola ninguna capacidad, muchos la marcan "basal". El error está en el **orden**: se salteó todo el bloque d.

### V) [Xe] 6s² 5d⁸ 6p⁷

```
                         └── 6p⁷  ⚠️  el subnivel p admite MÁXIMO 6 e⁻
```

$$\boxed{\textbf{IMPOSIBLE}}$$

**La basal:**

```
e⁻ totales = 54 + 2 + 8 + 7 = 71  →  Z = 71 = LUTECIO (Lu)

Basal:  [Xe] 6s² 4f¹⁴ 5d¹        (54 + 2 + 14 + 1 = 71 ✓)
```

⚠️ Acá el 6p⁷ es la violación evidente, pero además **faltaba llenar el 4f**, que va antes del 5d.

### 📋 El resumen

| | e⁻ | Elemento | Estado | Basal correcta |
|---|---|---|---|---|
| **I** | 19 | K | ✅ **BASAL** | — |
| **II** | 12 | Mg | ❌ **IMPOSIBLE** (3s³ > 2) | 1s² 2s² 2p⁶ 3s² |
| **III** | 16 | S | ⚡ **EXCITADA** (hueco en 3s) | 1s² 2s² 2p⁶ 3s² 3p⁴ |
| **IV** | 26 | Fe | ⚡ **EXCITADA** (3d vacío) | [Ar] 4s² 3d⁶ |
| **V** | 71 | Lu | ❌ **IMPOSIBLE** (6p⁷ > 6) | [Xe] 6s² 4f¹⁴ 5d¹ |

> 📝 **Respuesta tipo parcial**
>
> **I) BASAL.** 19 e⁻ (K). Respeta capacidades y el orden de llenado: tras el 3p⁶ corresponde el 4s.
>
> **II) IMPOSIBLE.** El subnivel **s admite como máximo 2 electrones** y figura **3s³**. Son 12 e⁻ → Mg. Basal: **1s² 2s² 2p⁶ 3s²**.
>
> **III) EXCITADA.** Las capacidades se respetan, pero el **3s quedó incompleto (3s¹)** mientras hay electrones en el 3p: un electrón saltó del 3s al 3p. Son 16 e⁻ → S. Basal: **1s² 2s² 2p⁶ 3s² 3p⁴**.
>
> **IV) EXCITADA.** No viola capacidades, pero **después del 4s corresponde llenar el 3d**, que está vacío, y hay 6 e⁻ en el 4p. Son 26 e⁻ → Fe. Basal: **[Ar] 4s² 3d⁶**.
>
> **V) IMPOSIBLE.** El subnivel **p admite como máximo 6 electrones** y figura **6p⁷** (además falta llenar el 4f). Son 71 e⁻ → Lu. Basal: **[Xe] 6s² 4f¹⁴ 5d¹**.

---

## 1c) Iones isoelectrónicos

> Q pierde 4 e⁻ y forma un ion **isoelectrónico** con R²⁻. R tiene Z = 16 y A = 32.

### Qué significa "isoelectrónico"

> **Isoelectrónico = MISMA cantidad de electrones.** Nada más. Son átomos o iones distintos (distinto Z, distinto núcleo) que casualmente tienen el mismo número de electrones, y por lo tanto **la misma configuración electrónica**.

⚠️ **El dato A = 32 es de relleno.** El número másico cuenta protones + neutrones, y acá sólo importan los **electrones**. Meterlo en la cuenta es un error clásico.

### El camino

```
   R (Z=16)  ──gana 2 e⁻──►  R²⁻  ═══ isoelectrónico ═══  Q⁴⁺  ◄──pierde 4 e⁻──  Q
      16 e⁻                  18 e⁻                       18 e⁻                  ? e⁻
```

**Paso 1 — electrones de R²⁻.** R tiene Z = 16 → es el **azufre (S)**, con 16 e⁻ neutro. Como el anión tiene carga **−2**, **ganó** 2 electrones:

```
e⁻(R²⁻) = 16 + 2 = 18 e⁻
```

**Paso 2 — Q⁴⁺ tiene los mismos 18 e⁻** (eso dice "isoelectrónico"):

```
e⁻(Q⁴⁺) = 18
```

**Paso 3 — volver al átomo neutro.** El Q⁴⁺ se formó **perdiendo** 4 electrones, así que el neutro tenía 4 más:

```
e⁻(Q) = 18 + 4 = 22   →   Z = 22 = TITANIO (Ti)
```

⚠️ **El signo es la trampa.** Un catión **perdió** electrones → para volver al neutro hay que **sumarlos**. Si restás te da 14 (Si) y queda todo mal.

$$\boxed{\text{carga} = Z - e^- \qquad\Longrightarrow\qquad e^- = Z - \text{carga}}$$

### Las configuraciones

**Del ion Q⁴⁺** (18 e⁻ — misma que Ar, S²⁻, Cl⁻, K⁺, Ca²⁺):

```
1s² 2s² 2p⁶ 3s² 3p⁶        = [Ar]
```

**Del elemento Q** (22 e⁻, titanio):

```
1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d²    = [Ar] 4s² 3d²
```

⚠️ **De dónde salen los electrones al ionizar:** el Ti⁴⁺ pierde **primero los 2 del 4s** y después **los 2 del 3d**. Aunque el 4s se **llena** antes, se **vacía** primero — porque una vez ocupado, el 4s queda por encima del 3d en energía. Es la regla que más se pregunta de los metales de transición.

> 📝 **Respuesta tipo parcial**
>
> R tiene Z = 16 (azufre). El anión **R²⁻ ganó 2 electrones**: tiene 16 + 2 = **18 e⁻**.
>
> Por ser **isoelectrónico**, Q⁴⁺ también tiene **18 e⁻**. Como se formó **perdiendo** 4 electrones, el átomo neutro Q tiene 18 + 4 = **22 e⁻**, o sea **Z = 22: titanio (Ti)**.
>
> **C.E. del ion Q⁴⁺ (18 e⁻):** 1s² 2s² 2p⁶ 3s² 3p⁶ = **[Ar]**
> **C.E. del elemento Q (22 e⁻):** 1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d² = **[Ar] 4s² 3d²**
>
> *(El dato A = 32 no interviene: el número másico no afecta la cantidad de electrones.)*

---
---
# PROBLEMA 2

## 2a) Lewis de NaCN y CCl₂O

**Datos de electronegatividad:** Na 0,93 · C 2,55 · O 3,50 · N 3,04 · Cl 3,16

### 🔑 El método de Lewis, en 6 pasos (usalo siempre igual)

```
1. Contar los electrones de VALENCIA totales
      (+ 1 por cada carga negativa · − 1 por cada positiva)
2. Elegir el átomo CENTRAL: el MENOS electronegativo (nunca el H)
3. Unir todo con enlaces simples
4. Repartir los electrones que sobran como pares libres,
   completando primero los átomos EXTERNOS
5. Si al central le falta octeto → formar ENLACES MÚLTIPLES
6. Calcular CARGAS FORMALES y verificar que la suma dé la carga del compuesto
```

**La fórmula de la carga formal:**

```
CF = e⁻ de valencia − e⁻ libres − (e⁻ enlazantes ÷ 2)
```

En palabras: *"con cuántos electrones vino el átomo, menos con cuántos se quedó"*. Los pares libres son **todos suyos**; de los compartidos le toca **la mitad**.

---

### NaCN — cianuro de sodio

**Paso 1 — ¿es iónico o covalente?**

```
ΔEN(Na–C) = 2,55 − 0,93 = 1,62
```

El Na es un **metal** (grupo 1) y el resto son **no metales**. Entonces el compuesto es **iónico**: el sodio **cede** su electrón y no comparte nada.

⚠️ **Por eso NO se dibuja "Na–C≡N" con una rayita.** Se dibuja el **catión suelto** y el **anión entre corchetes**:

```
NaCN   →   Na⁺  +  CN⁻
```

**Paso 2 — Lewis del anión CN⁻.** Los electrones de valencia:

```
C:  4 e⁻   (grupo 14)
N:  5 e⁻   (grupo 15)
carga −1: +1 e⁻
────────────────
TOTAL:  10 e⁻  =  5 pares
```

⚠️ **La carga negativa SUMA electrones.** Es el paso que más se olvida en los aniones.

**Paso 3 — probar.** Con un enlace simple C–N y pares libres no alcanza el octeto para los dos. Con **triple enlace** sí:

```
              ⎡           ⎤ ⁻
              ⎢  :C ≡ N:  ⎥
              ⎣           ⎦

  Na⁺   +   [ :C≡N: ]⁻
```

**El recuento:**

| | Pares libres | Enlace | Total alrededor |
|---|---|---|---|
| **C** | 1 par (2 e⁻) | triple (6 e⁻) | **8** ✓ octeto |
| **N** | 1 par (2 e⁻) | triple (6 e⁻) | **8** ✓ octeto |

```
Electrones usados: 6 (triple) + 2 + 2 (pares libres) = 10 ✓
```

**Paso 4 — cargas formales:**

```
C:   4 − 2 − 6/2  =  4 − 2 − 3  =  −1
N:   5 − 2 − 6/2  =  5 − 2 − 3  =   0
Na:  1 − 0 − 0    =  +1
```

**Verificación:** la suma de las CF del anión debe dar su carga.

```
(−1) + 0 = −1  ✓   coincide con CN⁻
(+1) + (−1) = 0 ✓   el compuesto NaCN es neutro
```

💡 **Por qué la carga negativa queda en el C y no en el N:** el C tiene 4 e⁻ de valencia y el N tiene 5. Con la misma "vecindad" (1 par libre + 1 triple enlace), al C le sobra un electrón respecto de lo que trajo. Es coherente con que el CN⁻ **se une a los metales por el carbono**.

**¿Hay resonancia?** **No.** Las alternativas (doble o simple enlace) dejan a algún átomo **sin octeto** y con cargas formales peores. La estructura del triple enlace es la única razonable.

---

### CCl₂O — fosgeno

**Paso 1 — átomo central.** El **menos electronegativo**: C (2,55) contra Cl (3,16) y O (3,50). Además el C es el que **más enlaces forma** (4).

```
Central: CARBONO
```

**Paso 2 — electrones de valencia:**

```
C:      4 e⁻          (grupo 14)
2 Cl:   7 × 2 = 14 e⁻ (grupo 17)
O:      6 e⁻          (grupo 16)
──────────────────────
TOTAL:  24 e⁻  =  12 pares
```

**Paso 3 — armar.** Con 3 enlaces simples el C se queda con 6 e⁻ (le falta octeto), así que hay que hacer **un doble enlace**. Va con el **oxígeno**, no con el Cl:

```
              :O:
               ‖
      :Cl — C — Cl:
       ¨         ¨
```

*(cada Cl con 3 pares libres, el O con 2 pares libres)*

**El recuento:**

| | Pares libres | Enlaces | Total |
|---|---|---|---|
| **C** | 0 | doble (4) + 2 simples (4) = 8 | **8** ✓ |
| **O** | 2 pares (4 e⁻) | doble (4 e⁻) | **8** ✓ |
| **Cl** (×2) | 3 pares (6 e⁻) | simple (2 e⁻) | **8** ✓ |

```
Electrones: 8 (enlaces) + 4 (O) + 12 (2 Cl) = 24 ✓
```

**Paso 4 — cargas formales:**

```
C:   4 − 0 − 8/2  =  4 − 0 − 4  =  0
O:   6 − 4 − 4/2  =  6 − 4 − 2  =  0
Cl:  7 − 6 − 2/2  =  7 − 6 − 1  =  0     (los dos)
```

$$\boxed{\text{TODAS las cargas formales son CERO}}$$

**Verificación:** 0 + 0 + 0 + 0 = 0 ✓ (molécula neutra)

💡 **Cuando todas las CF dan cero, la estructura es la mejor posible.** No hay nada que optimizar.

**¿Por qué el doble enlace va con el O y no con un Cl?**

```
  Con C=O :  todas las CF = 0                        ✅
  Con C=Cl:  Cl daría +1  y  O daría −1              ❌
```

Poner **+1 sobre el cloro** (EN 3,16) es malo: es un átomo muy electronegativo, "no quiere" carga positiva. Además el O del grupo 16 forma dobles enlaces con naturalidad y el Cl del 17 no.

**¿Hay resonancia?** **No.** Como la estructura con C=O ya tiene **todas las CF en cero**, cualquier alternativa es peor y no contribuye de forma significativa. **No se escriben estructuras de resonancia.**

> 📝 **Respuesta tipo parcial**
>
> **NaCN.** El Na es un metal y ΔEN(Na–C) = 2,55 − 0,93 = 1,62: el compuesto es **iónico**. Se representa como **Na⁺ + [C≡N]⁻**, sin enlace covalente Na–C.
>
> Para el anión CN⁻: 4 + 5 + 1 (carga) = **10 e⁻ de valencia**. Con un **triple enlace** y un par libre en cada átomo, ambos completan octeto y se usan los 10 e⁻.
>
> Cargas formales: **C = −1** (4 − 2 − 3), **N = 0** (5 − 2 − 3), **Na = +1**. Suman −1 en el anión y 0 en el compuesto ✓
>
> **No hay resonancia:** cualquier otra distribución deja átomos sin octeto y con cargas formales mayores.
>
> **CCl₂O.** El átomo central es el **C**, por ser el **menos electronegativo** (2,55). Electrones de valencia: 4 + 2(7) + 6 = **24 e⁻**.
>
> Estructura: **C unido por doble enlace al O y por enlaces simples a los dos Cl**; el O con 2 pares libres y cada Cl con 3 pares libres. Todos los átomos cumplen el octeto y se usan los 24 e⁻.
>
> Cargas formales: **C = 0, O = 0, Cl = 0** (las cuatro nulas), que suman 0 ✓
>
> **No hay resonancia significativa:** la estructura con C=O ya tiene todas las cargas formales en cero. Alternativas con C=Cl darían Cl = +1 y O = −1, desfavorable porque el Cl es más electronegativo que el C.

---

## 2b) Verdadero o Falso

### i) *"Los átomos del segundo periodo como el O, el N y el F pueden expandir octeto."*

$$\boxed{\textbf{FALSO}}$$

**La justificación (esto es lo que se corrige):**

Expandir el octeto significa alojar **más de 8 electrones** alrededor de un átomo. Para eso hacen falta **orbitales d disponibles**, y los orbitales d **aparecen recién a partir de n = 3**.

```
n = 2  →  subniveles disponibles:  2s , 2p       →  2 + 6 = MÁXIMO 8 e⁻
n = 3  →  subniveles disponibles:  3s , 3p , 3d  →  2 + 6 + 10 = hasta 18 e⁻
                                        └── acá aparece el d
```

Los elementos del **2º período** (Li a Ne) sólo tienen **2s y 2p**: físicamente **no tienen dónde poner** un noveno electrón.

| Puede expandir | No puede expandir |
|---|---|
| **P, S, Cl, Br, I, Xe** (período ≥ 3) | **B, C, N, O, F** (período 2) |
| PCl₅ (10 e⁻) · SF₆ (12) · XeF₄ (12) | ❌ NF₅ y OF₄ **no existen** |

💡 **Contraejemplo útil:** existe el **PCl₅** pero **no existe el NCl₅**, aunque P y N son del mismo grupo. La única diferencia es el período: el P es del 3 y el N del 2.

⚠️ **Ojo con no confundir:** el 2º período sí tiene la excepción **contraria** — el **octeto incompleto** (B y Be, como el BF₃ con 6 e⁻). Eso es *tener menos* de 8, que sí se puede. Lo que no se puede es tener *más*.

> 📝 **Respuesta tipo parcial**
>
> **FALSO.** Para expandir el octeto un átomo necesita **orbitales d disponibles**, y éstos existen recién **a partir del nivel n = 3**. Los elementos del segundo período sólo disponen de los subniveles **2s y 2p**, que alojan como máximo **8 electrones**. Por eso el O, el N y el F **nunca** superan el octeto. La expansión sólo es posible desde el **tercer período** en adelante (P, S, Cl, Xe: PCl₅, SF₆, XeF₄). Prueba de ello es que existe el PCl₅ pero **no** el NCl₅, siendo P y N del mismo grupo.

### ii) *"El átomo central suele ser el más electronegativo y con menor radio atómico."*

$$\boxed{\textbf{FALSO}}$$

**Está al revés en las dos cosas.** El átomo central suele ser el **MENOS electronegativo** y el de **MAYOR radio**.

**Por qué el menos electronegativo:**

El átomo central es el que **comparte electrones con varios vecinos a la vez**. El más electronegativo es el que **más los atrae hacia sí**: tiende a quedarse con los electrones en un solo enlace y ubicarse en la **periferia**, no a repartirse.

**Por qué el de mayor radio:**

Un átomo grande tiene **más lugar físico** alrededor para acomodar varios sustituyentes, con menos repulsión entre ellos.

**Los ejemplos del propio parcial lo confirman:**

| Molécula | Central | EN del central | EN de los externos |
|---|---|---|---|
| **CCl₂O** *(2a)* | **C** 2,55 | el más bajo | Cl 3,16 · O 3,50 |
| **NOF** *(3iii)* | **N** 3,04 | el más bajo | O 3,50 · F 4,0 |
| **IO₃⁻** *(3iv)* | **I** 2,5 | el más bajo | O 3,5 |
| SO₂ | **S** 2,5 | el más bajo | O 3,5 |

⚠️ **Excepciones que conviene nombrar:**
- **El H NUNCA es central** (sólo forma 1 enlace), aunque su EN (2,1) sea baja.
- En los **oxoácidos** el H va sobre el **oxígeno**, no sobre el átomo central: HNO₂ es H–O–N=O.

> 📝 **Respuesta tipo parcial**
>
> **FALSO.** Es exactamente al revés: el átomo central suele ser el **menos electronegativo** y el de **mayor radio atómico**.
>
> El átomo central debe **compartir electrones con varios átomos simultáneamente**; el más electronegativo tiende a **atraer** los electrones hacia sí y a ubicarse en la **periferia**, formando un solo enlace. Además, un **radio mayor** deja más espacio para acomodar varios sustituyentes con menor repulsión.
>
> Se verifica en los compuestos de este mismo parcial: en **CCl₂O** el central es el **C** (EN 2,55), el menos electronegativo frente al Cl (3,16) y al O (3,50); en **NOF** el central es el **N** (3,04) frente al O (3,50) y al F (4,0).
>
> **Excepción:** el **hidrógeno nunca es átomo central**, porque forma un solo enlace.

---
---

# PROBLEMA 3 — Lewis con excepciones al octeto

**Datos del parcial:**

| | Al | O | H | N | C | Cl | I | S | F |
|---|---|---|---|---|---|---|---|---|---|
| **Z** | 13 | 8 | 1 | 7 | 6 | 17 | 53 | 16 | 9 |
| **EN** | 1,5 | 3,5 | 2,1 | 3,0 | 2,5 | 3,0 | 2,5 | 2,5 | 4,0 |
| **Grupo** | 13 | 16 | 1 | 15 | 14 | 17 | 17 | 16 | 17 |
| **Período** | 3 | 2 | 1 | 2 | 2 | 3 | 5 | 3 | 2 |

⚠️ **El período está en los datos por una razón:** es lo que decide **quién puede expandir octeto**. Fijate que el **I es del período 5** — eso va a ser la clave del punto iv).

**Electrones de valencia = número de grupo** (para los grupos principales; en los grupos 13–18 se resta 10):

```
Al → grupo 13 → 3 e⁻      C  → grupo 14 → 4 e⁻      N → grupo 15 → 5 e⁻
O,S → grupo 16 → 6 e⁻     Cl,I,F → grupo 17 → 7 e⁻  H → 1 e⁻
```

---

## i) HNO₂ — ácido nitroso

**Paso 1 — electrones de valencia:**

```
H:  1 e⁻
N:  5 e⁻
2 O: 6 × 2 = 12 e⁻
─────────────────
TOTAL: 18 e⁻ = 9 pares
```

**Paso 2 — la conectividad (acá está la gracia).** Es un **oxoácido**, y en los oxoácidos:

$$\boxed{\text{El H va SIEMPRE sobre un OXÍGENO, nunca sobre el átomo central}}$$

```
   ✅  H — O — N = O          ❌  H — N(O)(O)
```

**Por qué:** el enlace **O–H** es mucho más estable que el N–H, y es el que explica que el compuesto sea **ácido** (libera H⁺ rompiendo el O–H). Todos los oxoácidos son así: H₂SO₄ es (HO)₂SO₂, HNO₃ es HO–NO₂.

**Paso 3 — la estructura:**

```
        ¨
   H — O — N = O
        ¨       ¨¨
```

- **O puente:** 2 pares libres + enlace a H + enlace a N
- **N:** 1 par libre + simple al O + doble al otro O
- **O terminal:** 2 pares libres + doble enlace

**El recuento:**

| Átomo | Pares libres | Enlaces | Total |
|---|---|---|---|
| **H** | 0 | 1 simple (2 e⁻) | **2** ✓ *(dueto)* |
| **O** (puente) | 2 (4 e⁻) | 2 simples (4 e⁻) | **8** ✓ |
| **N** | 1 (2 e⁻) | simple + doble (6 e⁻) | **8** ✓ |
| **O** (terminal) | 2 (4 e⁻) | doble (4 e⁻) | **8** ✓ |

```
Electrones: 2 + 2 + 4 (enlaces) + 4 + 2 + 4 (pares libres) = 18 ✓
```

**Paso 4 — cargas formales:**

```
H:          1 − 0 − 2/2 = 0
O (puente): 6 − 4 − 4/2 = 0
N:          5 − 2 − 6/2 = 0
O (term.):  6 − 4 − 4/2 = 0
```

$$\boxed{\text{Todas CERO}} \qquad \text{suma} = 0 \ ✓ \text{(molécula neutra)}$$

**¿Resonancia?** **No.** Los dos oxígenos **no son equivalentes**: uno tiene el H y el otro no. No se puede intercambiar el doble enlace entre ellos sin mover el hidrógeno, que es otra molécula.

⚠️ **Contrastalo con el NO₂⁻** (el anión, sin H): ahí los dos O **sí** son equivalentes y **sí hay resonancia**. La diferencia la hace el H.

---

## ii) AlCl₃ — cloruro de aluminio

**Paso 1 — electrones de valencia:**

```
Al:   3 e⁻   (grupo 13)  ⚠️  sólo TRES
3 Cl: 7 × 3 = 21 e⁻
──────────────────
TOTAL: 24 e⁻ = 12 pares
```

**Paso 2 — armar con enlaces simples:**

```
          :Cl:
           ¨|
    :Cl — Al — Cl:
     ¨¨         ¨¨
```

*(cada Cl con 3 pares libres, el Al sin pares libres)*

**El recuento:**

| Átomo | Pares libres | Enlaces | Total |
|---|---|---|---|
| **Al** | 0 | 3 simples (6 e⁻) | **6** ⚠️ **NO llega al octeto** |
| **Cl** (×3) | 3 (6 e⁻) | simple (2 e⁻) | **8** ✓ |

```
Electrones: 6 (enlaces) + 18 (3 Cl × 6) = 24 ✓  — no sobra ninguno
```

**Paso 3 — la justificación (esto es lo que piden).**

El Al queda con **6 electrones**: es un caso de **OCTETO INCOMPLETO** (o *especie deficiente en electrones*).

$$\boxed{\text{El Al es del grupo 13: tiene sólo 3 e}^-\text{ de valencia y forma 3 enlaces} \to \text{6 e}^-}$$

⚠️ **Y no se arregla.** Se podría pensar en hacer un doble enlace Al=Cl para completarle el octeto, pero mirá qué pasa con las cargas formales:

```
   Con 3 enlaces simples:   Al = 3 − 0 − 3 = 0     Cl = 7 − 6 − 1 =  0    ✅ todas cero
   Con un doble Al=Cl:      Al = 3 − 0 − 4 = −1    Cl = 7 − 4 − 2 = +1    ❌
```

Poner **+1 sobre un cloro** (EN 3,0) y **−1 sobre el aluminio** (EN 1,5) va **en contra de la electronegatividad**: el átomo más electronegativo tendría la carga positiva. Es peor. Se deja el octeto incompleto.

**Cargas formales:**

```
Al:  3 − 0 − 6/2 = 0
Cl:  7 − 6 − 2/2 = 0    (los tres)
```

Suma = 0 ✓

💡 **Los tres casos de octeto incompleto que hay que conocer:** **BF₃** y **AlCl₃** (6 e⁻, grupo 13) y **BeCl₂** (4 e⁻, grupo 2). Son ácidos de Lewis: "buscan" un par de electrones, y por eso el AlCl₃ es un catalizador tan usado.

---

## iii) NOF — fluoruro de nitrosilo

**Paso 1 — átomo central.** El **menos electronegativo**: N (3,0) contra O (3,5) y F (4,0).

```
Central: NITRÓGENO
```

⚠️ **El F NUNCA es central.** Es el elemento más electronegativo de la tabla y forma **un solo enlace**, siempre.

**Paso 2 — electrones de valencia:**

```
N: 5 e⁻
O: 6 e⁻
F: 7 e⁻
──────────
TOTAL: 18 e⁻ = 9 pares
```

**Paso 3 — la estructura.** Con dos enlaces simples el N queda con 6 e⁻, así que hace un **doble enlace con el O** (no con el F, que es del grupo 17 y forma un solo enlace):

```
        ¨
   :F — N = O
    ¨¨  ¨   ¨¨
```

**El recuento:**

| Átomo | Pares libres | Enlaces | Total |
|---|---|---|---|
| **F** | 3 (6 e⁻) | simple (2 e⁻) | **8** ✓ |
| **N** | 1 (2 e⁻) | simple + doble (6 e⁻) | **8** ✓ |
| **O** | 2 (4 e⁻) | doble (4 e⁻) | **8** ✓ |

```
Electrones: 2 + 4 (enlaces) + 6 + 2 + 4 (pares libres) = 18 ✓
```

**Paso 4 — cargas formales:**

```
N:  5 − 2 − 6/2 = 0
O:  6 − 4 − 4/2 = 0
F:  7 − 6 − 2/2 = 0
```

$$\boxed{\text{Todas CERO}} \qquad \text{suma} = 0 \ ✓$$

**¿Resonancia?** **No.** El O y el F no son intercambiables, y la estructura ya tiene todas las CF en cero.

⚠️ **Por qué el doble enlace va con el O y no con el F:**

```
   N=O :  el O es del grupo 16, le faltan 2 e⁻ → forma dobles con naturalidad   ✅
   N=F :  el F es del grupo 17, le falta 1 e⁻ → SÓLO forma enlaces simples      ❌
```

**El flúor forma un enlace simple y nada más. Nunca dobles, nunca es central.** Es la regla más segura de todo Lewis.

---

## iv) IO₃⁻ — ion iodato

> **Éste es el ejercicio "difícil" del problema**, y por eso el enunciado te da el **período del I (5)**.

### 🔴 Errata de tipeo del enunciado (mirala antes de empezar)

En el PDF está escrito **`IO 3-` con el 3 en SUPERÍNDICE**, o sea que se lee **IO³⁻**. Comparando la posición vertical de los caracteres en esa misma línea se ve que es un error puntual:

| En el PDF | Posición del número | Qué es |
|---|---|---|
| HNO**2** | 4,7 pt por **debajo** de la línea base | subíndice ✓ |
| AlCl**3** | 4,7 pt por **debajo** | subíndice ✓ |
| IO **3-** | 1,3 pt por **encima** | ⚠️ **superíndice** |

**Pero el compuesto es el IODATO, IO₃⁻.** Probá la otra lectura y vas a ver por qué:

```
Si fuera IO³⁻ :  e⁻ de valencia = 7 (I) + 6 (O) + 3 (carga) = 16 e⁻

  con enlace simple I–O  (I con 4 pares libres, O con 3):
      I:  7 − 8 − 2/2 = −2      ⚠️
      O:  6 − 6 − 2/2 = −1           suma = −3 ✓ pero el I en −2

  con enlace doble I=O   (I con 4 pares libres, O con 2):
      I:  7 − 8 − 4/2 = −3      ⚠️⚠️
      O:  6 − 4 − 4/2 =  0           suma = −3 ✓ pero el I en −3
```

En las dos versiones **el iodo carga con −2 o −3**, y eso contradice la electronegatividad: el I (2,5) es **menos** electronegativo que el O (3,5), así que no puede quedarse con el grueso de la carga negativa.

**Y además el IO³⁻ no existe.** Los oxoaniones reales del iodo son **IO⁻** (hipoiodito), **IO₂⁻** (iodito), **IO₃⁻** (iodato) y **IO₄⁻** (periodato).

**Tres señales más de que es iodato:**

1. El enunciado da el **período del I (5)**, dato que sólo sirve para justificar la **expansión de octeto** — lo que hace falta en el IO₃⁻ para bajar la CF del I de +2 a 0. En el IO³⁻ el problema sería el contrario.
2. Pide **resonancia**: el IO₃⁻ tiene 3 estructuras equivalentes. Con un solo oxígeno no habría ninguna.
3. Los cuatro compuestos del problema cubren **un caso cada uno**: octeto normal (HNO₂), **incompleto** (AlCl₃), normal con doble enlace (NOF) y **expandido** (IO₃⁻). Sin el iodato falta la expansión.

💡 Lo más probable es que se haya tipeado `IO₃⁻` seleccionando "3−" junto y aplicando superíndice a los dos caracteres.

**En el parcial:** si te aparece así, resolvelo como **iodato** y **aclarás en la hoja** que interpretás el 3 como subíndice. Eso te cubre.

**Paso 1 — átomo central.** El **menos electronegativo**: I (2,5) contra O (3,5).

```
Central: IODO
```

**Paso 2 — electrones de valencia:**

```
I:   7 e⁻   (grupo 17)
3 O: 6 × 3 = 18 e⁻
carga −1:   +1 e⁻      ⚠️  el anión SUMA
─────────────────────
TOTAL: 26 e⁻ = 13 pares
```

**Paso 3 — primera versión: todo con enlaces simples.**

```
          ⎡    :O:  ⎤ ⁻
          ⎢     |   ⎥
          ⎢ :O — I — O: ⎥        con un par libre sobre el I
          ⎣     ¨   ⎦
```

Todos cumplen octeto y se usan los 26 e⁻. **Pero mirá las cargas formales:**

```
I:  7 − 2 − 6/2  =  7 − 2 − 3  =  +2      ⚠️
O:  6 − 6 − 2/2  =  6 − 6 − 1  =  −1      (los tres)

suma = (+2) + 3(−1) = −1  ✓  da la carga, pero los valores son ALTOS
```

⚠️ **Una CF de +2 es una señal de alarma.** La regla es: **la mejor estructura es la que tiene las cargas formales más cercanas a cero**.

**Paso 4 — segunda versión: expandir el octeto del I.**

Acá entra el dato del período. El **I es del período 5**, así que **tiene orbitales d disponibles** y **puede alojar más de 8 electrones**. Convierto dos enlaces simples en dobles:

```
          ⎡     :O:      ⎤ ⁻
          ⎢      ‖       ⎥
          ⎢  O = I — O:  ⎥        el I con 1 par libre
          ⎣      ¨   ¨¨  ⎦
```

*(dos O con doble enlace y 2 pares libres cada uno; un O con enlace simple y 3 pares libres)*

**El recuento:**

| Átomo | Pares libres | Enlaces | Total |
|---|---|---|---|
| **I** | 1 (2 e⁻) | 2 dobles (8) + 1 simple (2) = 10 e⁻ | **12** ⚠️ **octeto EXPANDIDO** |
| **O** (=, ×2) | 2 (4 e⁻) | doble (4 e⁻) | **8** ✓ |
| **O** (−) | 3 (6 e⁻) | simple (2 e⁻) | **8** ✓ |

```
Electrones: 10 (enlaces) + 2 (I) + 8 (2 O dobles) + 6 (O simple) = 26 ✓
```

**Cargas formales:**

```
I:       7 − 2 − 10/2 =  7 − 2 − 5  =  0     ← ¡bajó de +2 a 0!
O (=):   6 − 4 − 4/2  =  6 − 4 − 2  =  0     (los dos)
O (−):   6 − 6 − 2/2  =  6 − 6 − 1  = −1

suma = 0 + 0 + 0 + (−1) = −1  ✓  coincide con IO₃⁻
```

$$\boxed{\text{Ésta es la estructura CORRECTA: cargas formales mínimas}}$$

**La comparación, que es lo que hay que justificar:**

| Estructura | CF del I | CF de los O | ¿Cuál es mejor? |
|---|---|---|---|
| 3 enlaces simples | **+2** | −1, −1, −1 | ❌ cargas altas |
| **2 dobles + 1 simple** | **0** | 0, 0, −1 | ✅ **la buena** |

**Paso 5 — ¿resonancia? SÍ.** 🔑

El oxígeno que lleva el enlace simple y la carga −1 **puede ser cualquiera de los tres**. Son **equivalentes**, así que hay **3 estructuras de resonancia**:

```
  ⎡  O          O:⁻        O   ⎤⁻
  ⎢  ‖           |          ‖   ⎥
  ⎢ O=I—O:⁻  ↔  O=I=O   ↔  ⁻:O—I=O ⎥
  ⎣                              ⎦
```

⚠️ **La flecha de resonancia es ↔ (doble punta), NO ⇄.** No son moléculas que se interconvierten: la real es un **híbrido** de las tres, con la carga **repartida** (−1/3 en cada O) y los tres enlaces I–O **idénticos**, intermedios entre simple y doble.

---

## 📋 Resumen del Problema 3

| | e⁻ val. | Central | Estructura | Situación del central | CF |
|---|---|---|---|---|---|
| **HNO₂** | 18 | N | H–O–N=O | octeto normal | todas **0** |
| **AlCl₃** | 24 | Al | 3 simples | ⚠️ **octeto INCOMPLETO** (6 e⁻) | todas **0** |
| **NOF** | 18 | N | F–N=O | octeto normal | todas **0** |
| **IO₃⁻** | 26 | I | 2 dobles + 1 simple | ⚠️ **octeto EXPANDIDO** (12 e⁻) | I = 0, un O = −1 |

⚠️ **El parcial eligió a propósito las dos excepciones al octeto** — una por defecto (AlCl₃) y una por exceso (IO₃⁻). Es lo que se evalúa.

> 📝 **Respuesta tipo parcial**
>
> **i) HNO₂** — 1 + 5 + 2(6) = **18 e⁻ de valencia**. Por ser un **oxoácido**, el H se une a un **oxígeno**, no al átomo central: **H–O–N=O**. El O puente lleva 2 pares libres, el N un par libre y el O terminal 2 pares libres. **Todos cumplen el octeto** y todas las **cargas formales son 0** (suma 0, molécula neutra). **No hay resonancia**, porque los dos oxígenos no son equivalentes: uno lleva el H.
>
> **ii) AlCl₃** — 3 + 3(7) = **24 e⁻ de valencia**. El Al se une por **enlaces simples** a los tres Cl, cada uno con 3 pares libres. El Al queda con **sólo 6 electrones**: es un caso de **octeto incompleto**, porque pertenece al **grupo 13** y sólo dispone de 3 electrones de valencia. Las cargas formales son **todas 0**. No se forma un doble enlace Al=Cl porque generaría CF = +1 sobre el Cl (EN 3,0) y −1 sobre el Al (EN 1,5), en contra de la electronegatividad.
>
> **iii) NOF** — 5 + 6 + 7 = **18 e⁻ de valencia**. El átomo central es el **N**, por ser el **menos electronegativo** (3,0 frente a O 3,5 y F 4,0). Estructura **F–N=O**: el F con 3 pares libres, el N con 1 par libre y el O con 2 pares libres. Todos cumplen octeto y todas las **CF son 0**. El doble enlace va con el **O** y no con el F, porque el flúor (grupo 17) forma **únicamente enlaces simples**.
>
> **iv) IO₃⁻** — 7 + 3(6) + 1 (carga) = **26 e⁻ de valencia**. Central: **I** (EN 2,5, el menor).
> Con tres enlaces simples las cargas formales serían **I = +2** y **O = −1** cada uno. Como el **iodo pertenece al período 5**, dispone de **orbitales d** y **puede expandir el octeto**: formando **dos enlaces dobles y uno simple** el iodo queda con **12 electrones** y las cargas formales bajan a **I = 0**, **O(doble) = 0** y **O(simple) = −1**, que suman −1 ✓. Ésta es la estructura correcta, por tener las **cargas formales mínimas**.
> **Hay 3 estructuras de resonancia**, según cuál de los tres oxígenos equivalentes lleve el enlace simple y la carga negativa.

---
---
# PROBLEMA 4 — Soluciones

> Éste es el problema más largo pero el **más mecánico**: no hay que "darse cuenta" de nada, hay que aplicar la cadena. Si vas corto de tiempo, **empezá por acá**.

## 4a) Ácido fosfórico concentrado

> Solución A: **85 % m/m_sn**, δ = **1,88 g/mL**. Mr(H₃PO₄) = **97,994 g/mol**

⚠️ **Leé bien el subíndice:** dice **% m/m_sn**, o sea masa de soluto sobre masa de **solución**. Es el % m/m de siempre. *(Más adelante, en el punto c), va a aparecer un **% m/m_sv** que es sobre **solvente** — ahí sí cambia todo.)*

### i) Masa de soluto y de solvente en 250 mL

**El razonamiento.** Me dan **volumen** y me piden **masas**. El % m/m está en masas, así que necesito cruzar de volumen a masa: **ése es el trabajo de la densidad**.

```
V_sc = 250 mL  ──× δ──►  m_sc  ──× 85 %──►  m_sto  ──resta──►  m_sv
```

**Paso 1 — masa de solución:**

```
m_sc = V × δ = 250 mL × 1,88 g/mL = 470 g
```

**Paso 2 — masa de soluto** (el 85 % de la solución):

```
m_sto = 470 g × 0,85 = 399,5 g de H₃PO₄
```

**Paso 3 — masa de solvente**, por diferencia:

```
m_sv = m_sc − m_sto = 470 − 399,5 = 70,5 g de H₂O
```

⚠️ **La masa de solvente casi nunca te la dan: se saca restando.** Es directo de `m_sc = m_sto + m_sv`.

💡 **Chequeo:** el 85 % m/m significa que de cada 100 g de solución 85 son ácido y **15 son agua**. Entonces:

```
470 × 0,15 = 70,5 g ✓
```

💡 **Dato de realidad:** en esta solución hay **más ácido que agua** (399,5 g contra 70,5 g). Por eso se le dice "concentrado" — es casi ácido puro.

> 📝 **Respuesta tipo parcial (i)**
>
> Masa de solución: **m_sc = V·δ = 250 mL × 1,88 g/mL = 470 g**
> Masa de soluto: **m_sto = 470 g × 0,85 = 399,5 g de H₃PO₄**
> Masa de solvente: **m_sv = m_sc − m_sto = 470 − 399,5 = 70,5 g de H₂O**

### ii) Dilución 1:4 desde 10 mL

**Qué significa 1:4.**

$$\boxed{1{:}n \;=\; \text{1 volumen de solución llevado a } n \text{ volúmenes TOTALES}}$$

```
   V_final = n × V_inicial = 4 × 10 mL = 40 mL
   C_final = C_inicial ÷ n
```

⚠️ **1:4 NO es "1 parte + 4 de agua"** (eso sería 1:5). Es **1 de solución + 3 de agua**, para llegar a 4 partes en total.

**Paso 1 — el volumen final** (sale directo):

```
V_final = 10 mL × 4 = 40 mL
```

**Paso 2 — la molaridad.** Hay dos caminos; te muestro los dos porque conviene saber el atajo.

---

**CAMINO 1 — por los moles (el más seguro)**

Trabajo con los 10 mL de partida:

```
m_sc  = 10 mL × 1,88 g/mL = 18,8 g
m_sto = 18,8 × 0,85 = 15,98 g de H₃PO₄
n     = 15,98 ÷ 97,994 = 0,1631 mol
```

Esos moles **no cambian al diluir** (sólo agrego agua). Terminan en 40 mL = 0,040 L:

```
M_B = 0,1631 mol ÷ 0,040 L = 4,08 M
```

---

**CAMINO 2 — molaridad de A y dividir por 4 (más rápido)**

Primero la molaridad de la solución concentrada, con la fórmula del rótulo comercial:

```
        % m/m × δ × 10        85 × 1,88 × 10       1598
M_A = ──────────────────  =  ────────────────  =  ────────  =  16,31 M
              Mr                  97,994           97,994
```

Y la dilución 1:4 **divide la concentración por 4**:

```
M_B = 16,31 ÷ 4 = 4,08 M ✓
```

**Los dos caminos dan lo mismo.** El segundo es más rápido si te acordás la fórmula; el primero no requiere memorizar nada.

💡 **De dónde sale el "× 10" de esa fórmula:** viene de combinar `% m/m → g de soluto por 100 g de sc` con `δ → g de sc por mL` y pasar a **litros** (×1000/100 = ×10). Está desarrollada en la sección 16 del machete.

**Verificación cruzada con C₀V₀ = C_F V_F:**

```
16,31 M × 10 mL = 163,1
 4,08 M × 40 mL = 163,2      ✓  (los moles, iguales de los dos lados)
```

> 📝 **Respuesta tipo parcial (ii)**
>
> Una dilución **1:4** significa llevar **1 volumen de solución a 4 volúmenes totales**, por lo tanto:
>
> **V_final = 4 × 10 mL = 40 mL**
>
> Molaridad de la solución A concentrada:
>
> M_A = (%m/m · δ · 10)/Mr = (85 × 1,88 × 10)/97,994 = **16,31 M**
>
> Como al diluir **los moles de soluto no cambian**, la concentración se divide por el factor de dilución:
>
> **M_B = 16,31 M ÷ 4 = 4,08 M**
>
> *Verificación por moles:* en 10 mL de A hay m_sto = 10 × 1,88 × 0,85 = 15,98 g, o sea n = 15,98/97,994 = 0,1631 mol. En 0,040 L: M = 0,1631/0,040 = **4,08 M** ✓

---

## 4b) Etanol y % v/v

> ¿Qué volumen de etanol (δ = 0,79 g/cm³) hay que agregar a **500 cm³ de agua** para obtener una solución **5 % v/v**? Volúmenes aditivos. Mr = 46,07 g/mol

### i) Volumen de etanol

⚠️ **LA trampa del ejercicio, y es la que más se cobra.**

El **% v/v va sobre el volumen de SOLUCIÓN**, no sobre el volumen de agua:

```
              V_soluto
   % v/v = ─────────────── × 100          ← abajo va la SOLUCIÓN
            V_solución
```

❌ **El error:** hacer `500 × 0,05 = 25 cm³`. Eso estaría bien sólo si los 500 cm³ fueran de **solución**, pero son de **agua**.

✅ **Lo correcto:** el volumen de solución es `V_etanol + 500` (nos dicen que los volúmenes son aditivos). Como el volumen de etanol es **la incógnita y aparece de los dos lados**, hay que plantear una **ecuación**:

```
      V_et
  ───────────── = 0,05
   V_et + 500
```

**La despejo:**

```
V_et = 0,05 × (V_et + 500)
V_et = 0,05·V_et + 25
V_et − 0,05·V_et = 25
0,95 · V_et = 25
V_et = 25 ÷ 0,95
```

$$\boxed{V_{etanol} = 26{,}3\ \text{cm}^3}$$

**Verificación:**

```
V_sc = 26,3 + 500 = 526,3 cm³
% v/v = 26,3 / 526,3 × 100 = 5,00 % ✓
```

💡 **De dónde sale el 0,95:** el etanol es el 5 % de la solución, así que **el agua es el 95 %**. Los 500 cm³ de agua **son ese 95 %**. Por eso también se puede hacer directo:

```
V_sc = 500 ÷ 0,95 = 526,3 cm³   →   V_et = 526,3 − 500 = 26,3 cm³ ✓
```

### ii) Masa de etanol

```
m = V × δ = 26,3 cm³ × 0,79 g/cm³ = 20,8 g de etanol
```

### iii) % m/m de la solución

**Paso 1 — masa de agua.** Con δ(H₂O) = 1,00 g/cm³:

```
m_agua = 500 cm³ × 1,00 g/cm³ = 500 g
```

**Paso 2 — masa de solución.** ⚠️ Las **masas SÍ son aditivas** (los volúmenes no, aunque acá el enunciado nos pida suponer que sí):

```
m_sc = 20,8 + 500 = 520,8 g
```

**Paso 3 — el porcentaje:**

```
% m/m = 20,8 / 520,8 × 100 = 3,99 ≈ 4,0 % m/m
```

### ⚠️ Lo que hay que entender de este punto

$$\boxed{5\ \%\ \text{v/v} \;\neq\; 5\ \%\ \text{m/m}} \qquad \text{da } \mathbf{4{,}0\ \%\ m/m}$$

**Por qué.** El etanol es **menos denso** que el agua (0,79 contra 1,00): 26,3 cm³ de etanol **pesan menos** que 26,3 cm³ de agua. Entonces, en masa, "pesa" menos de lo que "ocupa".

```
   % m/m = % v/v × (δ_soluto / δ_solución)
```

Como δ_etanol < δ_solución, el % m/m **queda por debajo** del % v/v.

💡 **Por eso las etiquetas de bebidas alcohólicas dicen "% vol"** (% v/v): una cerveza de "5°" es 5 % v/v, que en masa son ~4 %.

> 📝 **Respuesta tipo parcial**
>
> **i)** El % v/v se define sobre el volumen de **solución**, no sobre el de agua. Con volúmenes aditivos, V_sc = V_et + 500, y planteo:
>
> V_et / (V_et + 500) = 0,05  →  V_et = 0,05·V_et + 25  →  0,95·V_et = 25
>
> **V_etanol = 26,3 cm³**
>
> *(Verificación: 26,3/(26,3+500) × 100 = 5,00 % ✓)*
>
> **ii)** m = V·δ = 26,3 cm³ × 0,79 g/cm³ = **20,8 g de etanol**
>
> **iii)** Masa de agua: 500 cm³ × 1,00 g/cm³ = 500 g. Como las **masas son aditivas**: m_sc = 20,8 + 500 = **520,8 g**.
>
> **% m/m = (20,8 / 520,8) × 100 = 4,0 % m/m**
>
> El % m/m resulta **menor** que el % v/v porque el etanol es **menos denso** que el agua: el mismo volumen aporta menos masa.

---

## 4c) Solubilidad del CaCrO₄ — precipitación al CALENTAR

> S(100 °C) = **3,0 % m/m_sv** · S(0 °C) = **12 % m/m_sv** · Se tienen **520 g de solución saturada a 0 °C**

### ⚠️ Primero: leer bien la unidad

$$\text{S} = 3{,}0\ \%\ m/m_{\mathbf{sv}} \;\longrightarrow\; \textbf{3,0 g de sal cada 100 g de SOLVENTE}$$

El subíndice **sv** cambia todo. **No** es sobre la solución. Es exactamente la unidad de las tablas de solubilidad de siempre (`g/100 g de agua`), sólo que escrita como porcentaje.

⚠️ **Si lo tomás como % m/m de solución te da todo mal.** Es la trampa principal del punto.

### ⚠️ Segundo: este compuesto es RARO

```
   0 °C  →  S = 12 %        ┐
                            │  la solubilidad BAJA al subir la temperatura
 100 °C  →  S =  3 %        ┘
```

**Casi todos los sólidos se disuelven MÁS en caliente. Éste no.** Su disolución es **exotérmica** (como el Ce₂(SO₄)₃ de la Serie 4, ejercicio 16), y por eso **se comporta como un gas**: calentar lo hace precipitar.

💡 Por eso el ejercicio pide la sal que precipita **al calentar** — que suena al revés de lo normal, y está bien.

### Paso 1 — descomponer los 520 g en soluto + solvente

**El razonamiento.** "Solución saturada a 0 °C" significa que está **justo en el límite**: tiene exactamente 12 g de sal por cada 100 g de agua. Armo la "porción unidad":

```
   Por cada 100 g de AGUA  →  hay 12 g de sal
   ────────────────────────────────────────────
   Solución =  12 + 100  =  112 g
```

Ahora escalo a los 520 g que tengo (regla de tres):

```
                   12
   m_sto = 520 × ─────  =  55,71 g de CaCrO₄
                   112

                  100
   m_sv  = 520 × ─────  =  464,29 g de H₂O
                  112
```

**Verificación doble:**

```
55,71 + 464,29 = 520 g ✓         (suman lo que tenía)
55,71 / 464,29 × 100 = 12,0 % ✓  (es la solubilidad a 0 °C)
```

⚠️ **El denominador es 112, no 100 ni 12.** Los 520 g son de **solución**, y la solución es sal **más** agua.

### Paso 2 — cuánto puede quedar disuelto a 100 °C

**La clave: el agua no se va.** Calentar (en recipiente cerrado, que es lo que se supone) **no evapora solvente**, así que:

```
   m_sv = 464,29 g   ← SIGUE SIENDO LA MISMA
```

Escalo la nueva solubilidad a esa cantidad de agua:

```
                    464,29
   máx = 3,0 g × ───────────  =  3,0 × 4,6429  =  13,93 g
                      100
```

### Paso 3 — la resta

```
   tenía disuelto:      55,71 g
   puede quedar:        13,93 g
   ───────────────────────────────
   PRECIPITA:           41,79 g
```

$$\boxed{m_{precipitado} = 55{,}71 - 13{,}93 = \mathbf{41{,}8\ g\ de\ CaCrO_4}}$$

⚠️ **No te olvides de la resta.** El error clásico es contestar "13,93 g" (lo que queda disuelto) en vez de lo que **precipita**.

### ii) Homogéneo o heterogéneo

**El criterio:**

> **Homogéneo** = **1 fase**, las propiedades intensivas son iguales en toda la muestra.
> **Heterogéneo** = **≥ 2 fases**, hay una superficie de discontinuidad (interfaz).

**A 0 °C — HOMOGÉNEO (1 fase)**

La solución está **saturada pero sin cuerpo de fondo**: los 55,71 g de sal están **todos disueltos**. Hay una sola fase líquida.

⚠️ **"Saturada" NO significa "con precipitado".** Significa que está en el límite: no admite **más**, pero lo que tiene está disuelto.

**A 100 °C — HETEROGÉNEO (2 fases)**

Al calentar precipitan 41,8 g. Ahora conviven:

```
        ┌─────────────┐
        │             │
        │  SOLUCIÓN   │  ← fase LÍQUIDA: 13,93 g disueltos
        │  SATURADA   │     en 464,29 g de agua (saturada a 100 °C)
        │             │
        │▒▒▒▒▒▒▒▒▒▒▒▒▒│  ← fase SÓLIDA: 41,8 g de CaCrO₄ precipitado
        └─────────────┘
```

- **Fase líquida:** solución saturada a 100 °C
- **Fase sólida:** el precipitado
- **2 fases** → heterogéneo

💡 **La solución que queda arriba sigue siendo SATURADA** (está en equilibrio con su cuerpo de fondo), sólo que ahora la saturación corresponde a 3 %.

> 📝 **Respuesta tipo parcial**
>
> **i)** La solubilidad está expresada **por masa de solvente**: 12 % m/m_sv significa **12 g de sal cada 100 g de agua**, o sea 12 g de sal en 112 g de solución.
>
> Descompongo los 520 g de solución saturada a 0 °C:
>
> m_sto = 520 × (12/112) = **55,71 g de CaCrO₄**
> m_sv = 520 × (100/112) = **464,29 g de H₂O**
>
> *(Verificación: 55,71/464,29 × 100 = 12 % ✓)*
>
> Al calentar hasta 100 °C **la masa de solvente no cambia** (no hay evaporación), pero la solubilidad baja a 3,0 g cada 100 g de agua. La máxima masa que puede permanecer disuelta es:
>
> máx = 3,0 × (464,29/100) = **13,93 g**
>
> Por lo tanto precipita:
>
> **m_precipitado = 55,71 − 13,93 = 41,8 g de CaCrO₄**
>
> *(La sal precipita al calentar porque su solubilidad **disminuye** con la temperatura: su disolución es **exotérmica**, a diferencia de la mayoría de las sales.)*
>
> **ii)**
> **A 0 °C: sistema HOMOGÉNEO (1 fase).** La solución está saturada pero **todo el soluto está disuelto**, sin cuerpo de fondo: las propiedades intensivas son uniformes en toda la muestra.
>
> **A 100 °C: sistema HETEROGÉNEO (2 fases).** Coexisten la **fase líquida** (solución saturada, con 13,93 g disueltos) y la **fase sólida** (41,8 g de CaCrO₄ precipitado), separadas por una interfaz.

---
---

# 📋 TODAS LAS RESPUESTAS, JUNTAS

| Punto | Respuesta |
|---|---|
| **1a-i** | ν = **7,32×10¹⁴ Hz** · E = ΔE = **4,85×10⁻¹⁹ J** |
| **1a-ii** | **2,92×10⁵ J/mol = 292 kJ/mol** |
| **1b** | I **basal** (K) · II **imposible** (Mg) · III **excitada** (S) · IV **excitada** (Fe) · V **imposible** (Lu) |
| **1c** | Q = **Ti** (Z=22) · Q⁴⁺ = **[Ar]** · Q = **[Ar] 4s² 3d²** |
| **2a** | NaCN = **Na⁺ + [C≡N]⁻**, CF: C −1, N 0, Na +1 · CCl₂O = **Cl₂C=O**, todas las CF **0** · ninguno con resonancia |
| **2b-i** | **FALSO** — el 2º período no tiene orbitales d |
| **2b-ii** | **FALSO** — el central es el **menos** electronegativo y de **mayor** radio |
| **3-i** | HNO₂ = **H–O–N=O**, todas CF 0, sin resonancia |
| **3-ii** | AlCl₃ = 3 simples, **octeto incompleto** (6 e⁻ en el Al), todas CF 0 |
| **3-iii** | NOF = **F–N=O**, todas CF 0, sin resonancia |
| **3-iv** | IO₃⁻ = 2 dobles + 1 simple, **octeto expandido** (12 e⁻ en el I), CF: I 0, un O −1 · **3 estructuras de resonancia** |
| **4a-i** | m_sc = **470 g** · m_sto = **399,5 g** · m_sv = **70,5 g** |
| **4a-ii** | V_final = **40 mL** · M_B = **4,08 M** *(M_A = 16,31 M)* |
| **4b** | V_etanol = **26,3 cm³** · m = **20,8 g** · **4,0 % m/m** |
| **4c-i** | Precipitan **41,8 g de CaCrO₄** |
| **4c-ii** | 0 °C: **homogéneo** (1 fase) · 100 °C: **heterogéneo** (2 fases) |

---

# 🚨 LAS 12 TRAMPAS DE ESTE PARCIAL

| # | Dónde | La trampa | Cómo evitarla |
|---|---|---|---|
| 1 | **1a** | Dejar λ en **nm** | Pasala a **metros**: 410 nm = 4,10×10⁻⁷ m |
| 2 | **1a-ii** | Olvidar **×N_A** | El fotón es de **un átomo**; el mol necesita Avogadro |
| 3 | **1b-IV** | Marcar **[Ar]4s²4p⁶** como basal | No viola capacidades, pero **se salteó el 3d** → excitada |
| 4 | **1b** | Confundir *imposible* con *excitada* | **Imposible** = rompe una regla (3s³) · **Excitada** = legal pero desordenada |
| 5 | **1c** | Usar el dato **A = 32** | El número másico **no** afecta los electrones. Es relleno |
| 6 | **1c** | **Restar** 4 en vez de sumar | El catión **perdió** e⁻ → el neutro tiene **más** |
| 7 | **2a** | Dibujar **Na–C≡N** con enlace | Es **iónico**: Na⁺ + [C≡N]⁻ por separado |
| 8 | **2a / 3-iv** | Olvidar **+1 e⁻** por la carga negativa | El anión **suma** electrones de valencia |
| 9 | **3-i** | Poner el **H sobre el N** | En los **oxoácidos** el H va sobre un **O** |
| 10 | **3-iv** | Quedarse con los **3 enlaces simples** | Da **CF = +2** en el I. El I es del **período 5**: expande |
| 11 | **4b** | Hacer **500 × 0,05** | El % v/v va sobre la **solución**: hay que plantear la ecuación |
| 12 | **4c** | Tratar el **% m/m_sv** como si fuera de solución | El subíndice **sv** = por **100 g de SOLVENTE** → dividir por **112**, no por 100 |

## 🔴 Errata del enunciado

| Dónde | Qué dice | Qué es | Cómo detectarlo |
|---|---|---|---|
| **3-iv** | **`IO 3-`** con el 3 en **superíndice** (se leería IO³⁻) | **IO₃⁻**, ion **iodato** | El IO³⁻ dejaría al iodo con CF **−2 o −3**, contra la electronegatividad, y **no existe** como especie. Además el enunciado da el **período del I** (para expandir octeto) y pide **resonancia**, que sólo tiene sentido con 3 oxígenos |

---

# 🎯 ESTRATEGIA PARA EL DÍA DEL PARCIAL

## El orden en que conviene atacarlo

```
1º  Problema 4   →  el más MECÁNICO. Aplicás la cadena y sale. No requiere "darte cuenta".
2º  Problema 1   →  cuentas cortas (1a) + reglas de memoria (1b, 1c)
3º  Problema 3   →  Lewis: es método puro, pero lleva tiempo dibujar
4º  Problema 2   →  el V/F del final es rápido; dejalo para cerrar
```

## Los cuatro métodos que hay que tener automatizados

**1. Espectroscopia**
```
λ → (a metros) → ν = c/λ → E = h·ν → ×N_A → E por mol
   atajo:  E = h·c/λ        h·c = 1,989×10⁻²⁵ J·m
```

**2. Configuración electrónica**
```
¿viola capacidad (s≤2, p≤6, d≤10, f≤14)?  → IMPOSIBLE
¿respeta las diagonales?  sí → BASAL  ·  no → EXCITADA
Iones:  catión pierde e⁻ (y los saca primero del s más externo)
        anión gana e⁻
```

**3. Lewis (6 pasos)**
```
1. e⁻ de valencia (± carga)   2. central = menos electronegativo
3. enlaces simples            4. pares libres a los externos
5. ¿falta octeto? → dobles    6. CF = val − libres − enlazantes/2
```

**4. Soluciones (la cadena)**
```
          × δ         × %m/m       ÷ Mr        ÷ V(L)
   V_sc ──────► m_sc ──────► m_sto ─────► n ─────────► M
                 │
                 │ − m_sto
                 ▼
               m_sv ──────► solubilidad, molalidad
```

## Los tres chequeos que salvan puntos

```
1. Cargas formales:  la suma tiene que dar la CARGA del compuesto
2. Electrones:       los usados en el dibujo = los de valencia contados
3. Magnitudes:       E de transición ~ cientos de kJ/mol
                     δ de solución acuosa diluida ~ 1,0 g/mL
                     al mezclar, la concentración queda ENTRE las dos
```

## Lo que se descuenta aunque el número esté bien

- **No justificar** en los V/F (piden "justificar brevemente" — sin justificación no suma)
- **No verificar** las cargas formales cuando el enunciado dice "calcular la carga formal"
- **No escribir las estructuras de resonancia** en el IO₃⁻ (las pide explícitamente)
- **No indicar unidades** en los resultados
- **Mezclar Stock y Tradicional** si aparece nomenclatura

---

> **Teoría de respaldo:** Clase 1 (`Clase1/Clase1-Explicacion-Completa.md`) · Clase 2 (`Clase2/`) · Clase 6 (`Clase6(5nohay)/Clase6-Explicacion-Completa.md`)
> **Machete:** secciones 2–5 (espectroscopia, C.E., iones) · 7–9 (Lewis, CF, resonancia) · 15–19 (soluciones)
> **Series relacionadas:** `Practica/Serie1-Resuelta.md` · `Serie2-Resuelta.md` · `Serie4-Resuelta.md`
