# 1er Parcial QG — 2C 2024 · Tema 1 — Resuelto

**Química General — ECyT / UNSAM**
**Archivo original:** `Parciales/1parcial/QG P1 2C 2024.pdf`

> ⚠️ **Ojo con este PDF:** no es un parcial en blanco. Es el escaneo de un parcial **ya resuelto a mano** (alumna: Camaguí, Muriel Zoe) y **corregido por el docente** (se ven los ✓ y un ✗). Los enunciados impresos están completos, pero las respuestas que se ven son las de ella.
> Este archivo tiene **mi resolución hecha de cero**, y al final de cada punto una nota **🖊️ Lo que puso ella** cuando difiere o cuando la corrección aporta algo.

> Cada punto tiene el **razonamiento**, la **cuenta** y un bloque **📝 Respuesta tipo parcial** con lo que va en la hoja.

| Problema | Puntos | Tema |
|---|---|---|
| **1** | 25 | Configuración electrónica · diagrama de energía · isoelectrónicos · fundamental/excitado/imposible |
| **2** | 25 | Lewis · resonancia · TRePEV · polaridad |
| **3** | 25 | % m/m y % m/V desde molaridad + densidad · diluciones |
| **4** | 25 | Mezcla de soluciones + sólido · curva de solubilidad (tabla) |

📌 **Los cuatro problemas valen 25.** Ninguno pesa más que otro: si te trabás, saltá.

📌 **Lo que NO entra en este parcial** (y sí entraba en el de 2025): espectroscopia / cálculo de $E = hc/\lambda$, fuerzas intermoleculares y orden de temperaturas de ebullición. Acá la polaridad se pide **sola**, sin llegar a T_eb. **No te confíes: el de 2025 pedía las dos cosas.**

---

## ⚠️ Este parcial NO te da los Mr como dato

A diferencia del otro parcial de 2C 2024 (el del 29/08, que lista `DATOS: Mr(H) = 1; Mr(C) = 12; Mr(O) = 16` al pie de cada problema), **acá no hay ninguna línea de DATOS**. O te dejan la tabla periódica, o los tenés que saber:

```
Na = 23     O = 16     H = 1     S = 32     C = 12

→ NaOH             = 23 + 16 + 1          =  40 g/mol      (P3)
→ Na₂SO₄           = 2(23) + 32 + 4(16)   = 142 g/mol      (P4a)  ⚠️ el ×2 del Na
→ NaAc = CH₃COONa  = 2(12)+3(1)+2(16)+23  =  82 g/mol      (sólo si querés dar moles)
```

### ¿Y dónde hace falta realmente el Mr?

En **tres lugares nada más**. El resto del parcial sale sin tocar una masa molar:

| Punto | ¿Necesita Mr? | Por qué |
|---|---|---|
| **P1** (todo) | ❌ **no** | Es contar electrones |
| **P2** (todo) | ❌ **no** | Lewis, geometría, polaridad |
| **P3a** — % m/m y % m/V | ✅ **SÍ** | La molaridad da **moles**, el porcentaje pide **gramos**. El Mr **es** ese puente: no hay forma de esquivarlo |
| **P3b** — masa en 50 mL | ✅ **SÍ** | Piden **masa**. Si pidieran moles serían 0,125 mol, sin Mr |
| **P3c** — los 200 mL | ❌ **no** | $C_1V_1 = C_2V_2$ es pura proporción |
| **P3d** — los 0,02 M | ❌ **no** | Ídem: dilución 1:25 |
| **P4a** — el balance de soluto | ❌ **no** | Cierra **todo en moles**: 0,3 − 0,025 − 0,1125 = **0,1625 mol** |
| **P4a** — pesar el sólido | ✅ **SÍ** | Sólo el último paso: 0,1625 mol × 142 = 23,075 g. **Una balanza pesa gramos, no moles** |
| **P4b** y **P4c** | ❌ **no** | La tabla de solubilidad está en **g/100 g de agua** y las respuestas son gramos (60, 144, 36): proporción de masas y nada más |

💡 **La lectura útil de esto:** si te quedás trabado porque no te acordás un Mr, **no abandones el problema**. Planteá todo en **moles**, dejá la conversión final indicada (`m = 0,1625 mol × Mr`) y seguí. En el P4 completo y en el P3c-d el Mr **ni aparece**.

⚠️ **De los tres, el que más se cae es el Na₂SO₄:** si te olvidás el ×2 del sodio te da 119 g/mol y el error se arrastra a todo el P4a.

---
---

# PROBLEMA 1 (25 puntos)

## Enunciado

> **a)** Considerar la siguiente configuración electrónica para un átomo de un elemento X y responder las siguientes consignas **justificando adecuadamente** cada una de ellas:
>
> $$\text{CE(X)} = 1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{10}\,4p^4$$
>
> **i)** Indique la configuración electrónica externa (CEE), grupo y periodo que ocupa en tabla periódica.
> **ii)** Complete el diagrama de energía correspondiente al elemento X e indique la identidad del elemento.
>
> **b)** El anión Y⁻ es isoelectrónico con el gas noble (Z = 10). Hallar la CEE del elemento como anión y en su estado fundamental.
>
> **c)** Indicar cuáles de las siguientes configuraciones electrónicas representan el **estado fundamental** de un átomo, cuáles un **estado excitado** y cuáles **no pueden representar ningún estado**.
>
> **i)** $1s^2\,2s^2\,2p_y^2\,2p_z^1\,2p_x^2$ · **ii)** $1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{11}$ · **iii)** $1s^2\,2s^2\,2p^5\,3s^2$

---

## 1a-i) CEE, grupo y período

### La CEE

**Regla:** la CEE lleva **sólo los electrones del nivel de n MÁXIMO**. Acá el n máximo es **4**:

```
1s² 2s² 2p⁶ 3s² 3p⁶  4s²   3d¹⁰   4p⁴
└─────────────────┘  └─┬─┘ └──┬─┘ └─┬┘
    n = 1, 2, 3        n=4    n=3   n=4
                              ↑
                     ⚠️ el 3d NO va en la CEE
```

$$\boxed{\text{CEE(X)} = 4s^2\,4p^4}$$

⚠️ **El error clásico es escribir `4s² 3d¹⁰ 4p⁴`.** El 3d tiene **n = 3**, no 4. Se llena *después* del 4s por energía, pero es un nivel **interno**. Está completo (d¹⁰) y no participa de la química del elemento.

### El período

**El período = el n más alto que aparece.** Acá n = 4:

$$\boxed{\text{Período} = 4}$$

### El grupo

Es un elemento del **bloque p** (el último subnivel que se llena es un p). Para el bloque p:

$$\text{Grupo} = 12 + (\text{e}^-\text{ en } np) = 12 + 4 = \mathbf{16}$$

O, equivalente y más rápido de recordar: **electrones de la CEE = 2 + 4 = 6 → grupo VIA = grupo 16 IUPAC** (los calcógenos, la familia del oxígeno).

$$\boxed{\text{Grupo} = 16\ (\text{VIA})}$$

💡 **Chequeo:** grupo 16 significa **6 electrones de valencia** → le faltan 2 para el octeto → forma aniones **X²⁻**. Es la familia O, S, Se, Te. Coherente con lo que va a salir en el ítem ii.

> 📝 **Respuesta tipo parcial**
>
> La **CEE** contiene únicamente los electrones del nivel de **mayor n**, que acá es n = 4. El subnivel 3d, aunque se llena después del 4s, corresponde a **n = 3** y es un nivel **interno completo**, por lo que **no forma parte de la CEE**:
>
> $$\text{CEE(X)} = \mathbf{4s^2\,4p^4}$$
>
> El **período** es el mayor valor de n → **período 4**.
>
> El elemento pertenece al **bloque p** (termina en 4p) y tiene **6 electrones en la CEE** (2 + 4), por lo que está en el **grupo 16 (VIA)**.

---

## 1a-ii) Diagrama de energía e identidad del elemento

### La identidad: contar electrones

La CE está dada para un **átomo** (no un ion) → es **eléctricamente neutro** → $\#e^- = \#p^+ = Z$.

```
1s²  →   2
2s²  →   2
2p⁶  →   6
3s²  →   2
3p⁶  →   6
4s²  →   2
3d¹⁰ →  10
4p⁴  →   4
─────────
TOTAL:  34 electrones
```

$$\boxed{Z = 34 \;\Longrightarrow\; \textbf{Se (Selenio)}}$$

💡 **Chequeo doble:** grupo 16, período 4 → bajás por la columna: O (8) → S (16) → **Se (34)**. Cierra.

### El diagrama de energía

⚠️ **Dos cosas se corrigen acá, y son las que valen los puntos:**
1. **El orden energético**, que NO es el orden de n: … 4s **antes** de 3d, y 3d **antes** de 4p.
2. **La regla de Hund** en el 4p: los 4 electrones se reparten **primero de a uno** en los tres orbitales, y sólo el cuarto aparea.

```
 Energía
    ▲
    │
    │   4p   ┌────┬────┬────┐
    │        │ ↑↓ │ ↑  │ ↑  │   ← 4 e⁻: 1 par + 2 DESAPAREADOS  ⭐
    │        └────┴────┴────┘
    │
    │   3d   ┌────┬────┬────┬────┬────┐
    │        │ ↑↓ │ ↑↓ │ ↑↓ │ ↑↓ │ ↑↓ │   ← 10 e⁻, completo
    │        └────┴────┴────┴────┴────┘
    │
    │   4s   ┌────┐
    │        │ ↑↓ │
    │        └────┘
    │
    │   3p   ┌────┬────┬────┐
    │        │ ↑↓ │ ↑↓ │ ↑↓ │
    │        └────┴────┴────┘
    │
    │   3s   ┌────┐
    │        │ ↑↓ │
    │        └────┘
    │
    │   2p   ┌────┬────┬────┐
    │        │ ↑↓ │ ↑↓ │ ↑↓ │
    │        └────┴────┴────┘
    │
    │   2s   ┌────┐
    │        │ ↑↓ │
    │        └────┘
    │
    │   1s   ┌────┐
    └────────│ ↑↓ │
             └────┘
```

**Dato que suelen pedir de yapa:** el Se queda con **2 electrones desapareados** → es **paramagnético**.

> 📝 **Respuesta tipo parcial**
>
> Como la configuración corresponde a un **átomo neutro**, la cantidad de electrones iguala a Z. Sumando: 2+2+6+2+6+2+10+4 = **34 electrones** → **Z = 34** → el elemento es el **selenio (Se)**.
>
> El diagrama se completa respetando el **orden creciente de energía** (1s < 2s < 2p < 3s < 3p < **4s < 3d < 4p**), el **principio de exclusión de Pauli** (máximo 2 e⁻ por orbital, con espines opuestos) y la **regla de Hund** en el subnivel 4p: de los 4 electrones, **tres entran desapareados y con el mismo espín** en los tres orbitales p y el cuarto aparea a uno de ellos, quedando **2 electrones desapareados** (el Se es paramagnético).

🖊️ **Lo que puso ella:** lo mismo (34 e⁻, Se) y el docente le puso ✓. En su diagrama el 4p está como `↑↓ ↑ ↑`, que es lo correcto.

---

## 1b) El anión Y⁻ isoelectrónico con el gas noble Z = 10

### Paso 1 — identificar el gas noble

$$Z = 10 \;\Longrightarrow\; \textbf{Ne (Neón)}$$

### Paso 2 — "isoelectrónico" = misma cantidad de electrones

$$\#e^-(\mathrm{Y}^-) = \#e^-(\mathrm{Ne}) = 10$$

```
CE(Y⁻)  = 1s² 2s² 2p⁶          (10 e⁻)
CEE(Y⁻) = 2s² 2p⁶              ← n máximo = 2
```

### Paso 3 — el átomo NEUTRO tiene un electrón MENOS

⚠️ **Acá está la trampa.** El Y⁻ **ganó** un electrón. El átomo neutro Y tiene:

$$\#e^-(\mathrm{Y}) = 10 - 1 = 9 \;\Longrightarrow\; Z(\mathrm{Y}) = 9 \;\Longrightarrow\; \textbf{F (Flúor)}$$

```
CE(Y)  = 1s² 2s² 2p⁵           (9 e⁻)
CEE(Y) = 2s² 2p⁵               ← 7 e⁻ de valencia → grupo 17
```

💡 **Chequeo:** el F es del **grupo 17** (halógenos), le falta **1** electrón para el octeto → forma **F⁻** con facilidad, y ese F⁻ es isoelectrónico con el Ne. Todo consistente.

> 📝 **Respuesta tipo parcial**
>
> El gas noble con Z = 10 es el **neón**. Isoelectrónico significa **igual número de electrones**, entonces Y⁻ tiene **10 electrones**:
>
> $$\text{CE}(\mathrm{Y}^-) = 1s^2\,2s^2\,2p^6 \qquad\Longrightarrow\qquad \text{CEE}(\mathrm{Y}^-) = \mathbf{2s^2\,2p^6}$$
>
> El anión se formó **ganando un electrón**, por lo que el **átomo neutro en su estado fundamental** tiene 9 electrones (Z = 9, **flúor**):
>
> $$\text{CE}(\mathrm{Y}) = 1s^2\,2s^2\,2p^5 \qquad\Longrightarrow\qquad \text{CEE}(\mathrm{Y}) = \mathbf{2s^2\,2p^5}$$
>
> Coherente: el F es del **grupo 17**, tiene 7 e⁻ de valencia y le falta uno para completar el octeto.

🖊️ **Lo que puso ella:** las cuatro configuraciones bien (✓ del docente), pero **no escribió que el elemento es el flúor**. El enunciado no lo pide con esas palabras, pero **nombralo igual**: es gratis y demuestra que entendiste.

---

## 1c) Fundamental / excitado / imposible

**El método, en tres preguntas y en este orden:**

```
1. ¿Viola Pauli o la capacidad del subnivel?   (s≤2, p≤6, d≤10, f≤14)
        SÍ → NINGÚN ESTADO. Terminaste.
        NO ↓
2. Contá los e⁻ → identificá el elemento → escribí SU estado fundamental.
3. ¿Coincide?   SÍ → FUNDAMENTAL      NO → EXCITADO
```

---

### i) $1s^2\,2s^2\,2p_y^2\,2p_z^1\,2p_x^2$

**Paso 1 — capacidades:** cada orbital p lleva máximo 2 e⁻. Acá: py con 2, pz con 1, px con 2. ✓ **Nada violado.**

**Paso 2 — contar:** 2 + 2 + 2 + 1 + 2 = **9 electrones** → **Z = 9 → F (flúor)**.

**Paso 3 — ¿es el fundamental del F?** El fundamental del F es $1s^2\,2s^2\,2p^5$. Y ese $2p^5$, repartido por **Hund**, es:

```
2p:  ┌────┬────┬────┐
     │ ↑↓ │ ↑↓ │ ↑  │    dos orbitales apareados + uno con 1 e⁻
     └────┴────┴────┘
       py   px   pz
```

Que es exactamente $2p_y^2\,2p_x^2\,2p_z^1$. **Coincide.**

$$\boxed{\text{i) ESTADO FUNDAMENTAL (flúor)}}$$

💡 **Por qué no importa cuál orbital queda con 1 e⁻:** los tres orbitales p son **degenerados** (misma energía). Que el desapareado sea el pz, el px o el py da lo mismo — no cambia la energía, así que sigue siendo el fundamental. **No lo marques como excitado por eso.**

⚠️ Y fijate el guiño del parcial: es **el mismo flúor** del ítem 1b. Los ítems están enganchados.

---

### ii) $1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{11}$

**Paso 1 — capacidades.** El subnivel **d** tiene **5 orbitales** → máximo $5 \times 2 = \mathbf{10}$ electrones.

$$3d^{11} \;\Longrightarrow\; \text{11 electrones en 5 orbitales} \;\Longrightarrow\; \textbf{IMPOSIBLE}$$

Habría un orbital con 3 electrones → dos de ellos tendrían los **cuatro números cuánticos iguales** → **viola el principio de exclusión de Pauli**.

$$\boxed{\text{ii) NO REPRESENTA NINGÚN ESTADO}}$$

⚠️ **Ni fundamental ni excitado.** Un estado excitado sigue siendo un estado **posible** (electrones promovidos a niveles más altos). Esto no existe: ningún átomo, en ninguna condición, puede tener 11 e⁻ en un 3d.

---

### iii) $1s^2\,2s^2\,2p^5\,3s^2$

**Paso 1 — capacidades:** $2p^5 \le 6$ ✓, $3s^2 \le 2$ ✓. **Nada violado** → es un estado posible.

**Paso 2 — contar:** 2 + 2 + 5 + 2 = **11 electrones** → **Z = 11 → Na (sodio)**.

**Paso 3 — el fundamental del Na:**

$$\text{CE}(\mathrm{Na})_{\text{fund}} = 1s^2\,2s^2\,2p^6\,3s^1$$

**No coincide.** Comparadas:

```
FUNDAMENTAL:       1s² 2s² 2p⁶ 3s¹     ← el 2p LLENO, 1 e⁻ en 3s
EL DEL ENUNCIADO:  1s² 2s² 2p⁵ 3s²     ← falta 1 e⁻ en 2p, sobra 1 en 3s
                            └──┬──┘
                   un electrón SALTÓ de 2p a 3s
```

Un electrón fue promovido del **2p** (más bajo) al **3s** (más alto) → **absorbió energía**.

$$\boxed{\text{iii) ESTADO EXCITADO (sodio)}}$$

💡 **El olfato para detectarlo sin contar:** si ves un **hueco en un subnivel interno** mientras hay electrones más arriba, es excitado. Un subnivel de menor energía **nunca** queda incompleto en el estado fundamental.

> 📝 **Respuesta tipo parcial**
>
> | Ítem | e⁻ | Elemento | Clasificación | Justificación |
> |---|---|---|---|---|
> | **i)** $1s^2 2s^2 2p_y^2 2p_z^1 2p_x^2$ | 9 | **F** | **FUNDAMENTAL** | Es $2p^5$ distribuido según **Hund** (2 orbitales apareados + 1 con un solo e⁻). Los tres orbitales p son degenerados, así que da igual cuál queda semilleno |
> | **ii)** $\ldots 4s^2\,3d^{11}$ | — | — | **NINGÚN ESTADO** | El subnivel **d** tiene 5 orbitales → **máximo 10 e⁻**. Con 11 habría un orbital con 3 e⁻ → **viola el principio de Pauli** |
> | **iii)** $1s^2 2s^2 2p^5 3s^2$ | 11 | **Na** | **EXCITADO** | El fundamental del Na es $1s^2 2s^2 2p^6 3s^1$. Acá un electrón fue **promovido de 2p a 3s**, dejando incompleto un subnivel de menor energía teniendo ocupado uno superior |

🖊️ **Lo que puso ella:** los tres bien, con ✓. Su justificación del ii) fue *"no es posible tener 11 e⁻ en el orbital 3d"* — correcta en el fondo, pero **decí "en el SUBNIVEL 3d, que tiene 5 orbitales y admite 10 e⁻, porque violaría Pauli"**. La palabra "Pauli" es la que buscan.

---
---

# PROBLEMA 2 (25 puntos)

## Enunciado

> **a)** Dibujar las estructuras de Lewis y representar las resonancias en caso de ser necesario, de los siguientes compuestos: **CO₃²⁻ ; BrF₅ ; H₂S ; SiH₄**
>
> **b)** Seleccionar **dos** de los compuestos del ítem anterior y representar, según el modelo de **TREPEV**, su geometría electrónica y molecular (nombrar geometría e indicar ángulos).
>
> **c)** En base a los compuestos del punto 2, indicar si los mismos son polares o no. ¿Cómo será el momento dipolar? ¿Tiene sentido clasificar como polar o no polar todos estos compuestos? ¿En qué casos no?

---

## 2a) Las cuatro estructuras de Lewis

**El recuento de electrones de valencia, todo junto (hacé esto primero, siempre):**

| Especie | Cuenta | e⁻ totales | pares |
|---|---|---|---|
| **CO₃²⁻** | C(4) + 3×O(6) + **2 por la carga −2** | **24** | **12** |
| **BrF₅** | Br(7) + 5×F(7) | **42** | **21** |
| **H₂S** | 2×H(1) + S(6) | **8** | **4** |
| **SiH₄** | Si(4) + 4×H(1) | **8** | **4** |

⚠️ **El anión SUMA, el catión RESTA.** El CO₃²⁻ suma 2. Es el error nº 1 de este punto.

---

### CO₃²⁻ — anión carbonato · ⭐ el único con resonancia

**Átomo central:** el **C** (menos electronegativo que el O y con 4 valencias).

```
        ⎡      O      ⎤ 2−
        ⎢      ‖      ⎥
        ⎢ ⁻O — C — O⁻ ⎥        3 enlaces σ  +  1 enlace π
        ⎣             ⎦
```

**El recuento, átomo por átomo:**

| Átomo | Pares libres | Enlaces | e⁻ alrededor |
|---|---|---|---|
| **C** | 0 | 3σ + 1π = 8 e⁻ | **8** ✓ octeto |
| **O** (doble) | 2 pares (4 e⁻) | doble (4 e⁻) | **8** ✓ |
| **O⁻** (simples, ×2) | 3 pares (6 e⁻) | simple (2 e⁻) | **8** ✓ |

```
Verificación: 6 e⁻ (3σ) + 2 e⁻ (1π) + 4 + 6 + 6 (pares libres) = 24 ✓
```

**Cargas formales** ($CF = e^-_{val} - e^-_{libres} - \tfrac{1}{2}e^-_{enlazantes}$):

```
C:          4 − 0 − 8/2 = 0
O (doble):  6 − 4 − 4/2 = 0
O (simple): 6 − 6 − 2/2 = −1     (los dos)
                        ───────
                  suma = −2  ✓  coincide con la carga del anión
```

**⭐ RESONANCIA: SÍ, 3 estructuras equivalentes.** Los tres oxígenos son **idénticos**: el doble enlace puede estar en cualquiera de los tres.

```
   ⎡     O     ⎤2−     ⎡     O⁻    ⎤2−     ⎡     O⁻    ⎤2−
   ⎢     ‖     ⎥       ⎢     |     ⎥       ⎢     |     ⎥
   ⎢ ⁻O— C —O⁻ ⎥  ↔    ⎢ ⁻O— C = O ⎥  ↔    ⎢  O= C —O⁻ ⎥
   ⎣           ⎦       ⎣           ⎦       ⎣           ⎦
```

⚠️ **La flecha es ↔ (doble punta), no ⇄.** No son moléculas que se transforman una en otra: la molécula real es **una sola**, el **híbrido de resonancia**, con los **tres enlaces C–O idénticos** (orden de enlace 1,33) y la carga −2 **repartida** (−⅔ en cada O).

💡 **Cómo justificarlo en la hoja:** *"experimentalmente los tres enlaces C–O tienen la misma longitud, intermedia entre C–O simple y C=O; una sola estructura de Lewis no puede describir eso, por lo que hace falta el conjunto de resonancias"*.

---

### BrF₅ — pentafluoruro de bromo · ⭐ octeto expandido

**Átomo central:** el **Br** (menos electronegativo; ⚠️ **el F nunca es central**).

```
              F
              |
       F ─────Br───── F         los 4 F basales en un plano,
              |  ⟍              el 5º F arriba (axial)
              F    F
              |
            ⟨:⟩  ← 1 PAR LIBRE en la 6ª posición del octaedro
```

Más claro, como octaedro:

```
   posición 1 (arriba):   F
   posiciones 2-5 (plano): F, F, F, F
   posición 6 (abajo):    PAR LIBRE  ⭐
```

**El recuento:**

```
5 enlaces Br—F:         10 e⁻
Br con 1 par libre:      2 e⁻
5 F × 3 pares libres:   30 e⁻
                        ─────
                        42 ✓
```

$$\boxed{\text{e}^-\text{ alrededor del Br} = 10 + 2 = \mathbf{12} \quad \text{⚠️ OCTETO EXPANDIDO}}$$

**Por qué puede:** el **Br es del período 4** → tiene **orbitales d disponibles** → aloja más de 8 electrones. Es un **hipervalente**, como el IF₃ o el ClF₅.

**Cargas formales:** Br = 7 − 2 − 5 = **0** · F = 7 − 6 − 1 = **0** (los cinco) → suma **0** ✓

**Resonancia: NO.** No hay enlaces múltiples ni cargas para deslocalizar.

---

### H₂S — sulfuro de hidrógeno

**Átomo central:** el **S** (⚠️ **el H nunca es central**: sólo forma 1 enlace).

```
          ¨
        ⟩ S ⟨          el S con 2 PARES LIBRES
         ╱   ⟍
        H     H
```

**El recuento:**

```
2 enlaces S—H:        4 e⁻
S con 2 pares libres: 4 e⁻
                      ────
                      8 ✓
```

$$\boxed{\text{e}^-\text{ alrededor del S} = 4 + 4 = \mathbf{8} \quad\text{(octeto completo)}}$$

**Cargas formales:** S = 6 − 4 − 2 = **0** · H = 1 − 0 − 1 = **0** → suma 0 ✓

**Resonancia: NO.**

💡 **Es el análogo del agua** con S en lugar de O. Misma estructura de Lewis, misma geometría.

---

### SiH₄ — silano

**Átomo central:** el **Si** (grupo 14, 4 valencias).

```
              H
              |
        H ─── Si ─── H          4 enlaces simples
              |                 SIN pares libres
              H
```

**El recuento:** los 8 electrones se usan **enteros** en los 4 enlaces. **No sobra nada.**

$$\boxed{\text{e}^-\text{ alrededor del Si} = \mathbf{8} \quad\text{(octeto completo)}}$$

**Cargas formales:** Si = 4 − 0 − 4 = **0** · H = 1 − 0 − 1 = **0** → suma 0 ✓

**Resonancia: NO.** Es el análogo del CH₄.

> 📝 **Respuesta tipo parcial — resumen de 2a**
>
> | Especie | e⁻ val. | Central | Pares libres del central | e⁻ del central | ¿Resonancia? |
> |---|---|---|---|---|---|
> | **CO₃²⁻** | 24 | C | 0 | **8** (octeto) | **SÍ — 3 estructuras** |
> | **BrF₅** | 42 | Br | **1** | **12** (expandido) | no |
> | **H₂S** | 8 | S | **2** | **8** (octeto) | no |
> | **SiH₄** | 8 | Si | 0 | **8** (octeto) | no |
>
> El **CO₃²⁻ es el único que requiere resonancia**: los tres oxígenos son equivalentes y experimentalmente los tres enlaces C–O tienen igual longitud (intermedia entre simple y doble), lo que una única estructura de Lewis no puede representar.

🖊️ **Lo que puso ella:** los cuatro recuentos correctos (12, 21, 4 y 4 pares) y las 3 resonancias del carbonato. **Escribió `Sn = 4 e⁻ valencia` donde iba `Si`** — un lapsus de tipeo, pero el Sn (estaño) es otro elemento. ⚠️ **Cuidado con Si / Sn en la hoja.**

---

## 2b) TREPEV — geometría electrónica y molecular

**El enunciado pide DOS.** Están las cuatro acá abajo; para elegir, la jugada es agarrar **una donde GE = GM y una donde GE ≠ GM**, porque es justo lo que el docente quiere ver que distinguís.

**El método, en una línea:**

$$\text{GE} = \text{pares de enlace} + \text{pares libres} \qquad\qquad \text{GM} = \text{sólo los átomos unidos}$$

⚠️ **Los pares libres ocupan lugar y empujan MÁS que los enlaces** → cierran los ángulos.

---

### CO₃²⁻ · ⭐ el caso GE = GM

```
Pares de enlace alrededor del C: 3    (el doble enlace cuenta como UNO)
Pares libres:                    0
                                ───
Total de dominios:               3   → AX₃
```

| | |
|---|---|
| **Geometría electrónica** | **Trigonal plana** (plana triangular) |
| **Geometría molecular** | **Trigonal plana** |
| **Ángulos O–C–O** | **120°** |

```
            O
            ‖
            C            los 4 átomos en un MISMO PLANO
          ╱   ⟍
       O   120°  O
```

**Por qué GE = GM:** el C **no tiene pares libres**. Cuando no hay pares libres, la geometría molecular es la misma que la electrónica y los ángulos son los **ideales**.

⚠️ **El doble enlace no agrega un dominio.** Un enlace doble o triple cuenta como **una sola** región de densidad electrónica. Si contás 4 dominios te da tetraédrica y está mal.

---

### H₂S · ⭐ el caso GE ≠ GM

```
Pares de enlace alrededor del S: 2
Pares libres:                    2
                                ───
Total de dominios:               4   → AX₂E₂
```

| | |
|---|---|
| **Geometría electrónica** | **Tetraédrica** |
| **Geometría molecular** | **Angular** (o "en V", "bent") |
| **Ángulo H–S–H** | **menor a 109,5°** |

```
         ⟨:⟩   ⟨:⟩        ← los 2 pares libres
           ⟍  ╱
             S
           ╱   ⟍
        H         H
           <109,5°
```

**Por qué se cierra el ángulo:** los **2 pares libres** están más cerca del núcleo y ocupan más volumen angular que los pares de enlace, así que **comprimen** a los dos H.

$$\text{repulsión: } \ \text{PL–PL} > \text{PL–PE} > \text{PE–PE}$$

📌 **El valor experimental del H₂S es 92°** (bastante más cerrado que el 104,5° del H₂O). TREPEV te da la **dirección** correcta (< 109,5°), no el número exacto. En el parcial: **poné "< 109,5°"** y si querés agregá el dato experimental.

---

### BrF₅ (por si la elegís)

```
Pares de enlace: 5      Pares libres: 1      Total: 6   → AX₅E
```

| | |
|---|---|
| **Geometría electrónica** | **Octaédrica** |
| **Geometría molecular** | **Pirámide de base cuadrada** |
| **Ángulos** | **F–Br–F basales = 90°** · **axial–basal < 90° (≈85°)** |

**Por qué:** el par libre ocupa un vértice del octaedro y **empuja los 4 F basales hacia arriba**, cerrando el ángulo axial–basal por debajo de 90°.

---

### SiH₄ (por si la elegís)

```
Pares de enlace: 4      Pares libres: 0      Total: 4   → AX₄
```

| | |
|---|---|
| **Geometría electrónica** | **Tetraédrica** |
| **Geometría molecular** | **Tetraédrica** |
| **Ángulo H–Si–H** | **109,5°** (el ideal, exacto) |

**Sin pares libres → GE = GM y ángulo ideal.**

> 📝 **Respuesta tipo parcial — tabla de 2b**
>
> | Especie | Dominios | GE | GM | Ángulos | ¿GE = GM? |
> |---|---|---|---|---|---|
> | **CO₃²⁻** | 3 σ + 0 PL | **Trigonal plana** | **Trigonal plana** | **120°** | **SÍ** (no hay pares libres) |
> | **H₂S** | 2 σ + 2 PL | **Tetraédrica** | **Angular** | **< 109,5°** (exp. 92°) | **NO** (2 pares libres) |
> | **BrF₅** | 5 σ + 1 PL | Octaédrica | Pirámide base cuadrada | 90° y < 90° | NO |
> | **SiH₄** | 4 σ + 0 PL | Tetraédrica | Tetraédrica | 109,5° | SÍ |
>
> La regla: **la GM se obtiene "borrando" los pares libres de la GE**, y cada par libre **cierra** los ángulos respecto del valor ideal porque repele más que un par de enlace (PL–PL > PL–PE > PE–PE).

🖊️ **Lo que puso ella:** eligió **CO₃²⁻ y H₂S** — la elección correcta, justo el par que muestra los dos casos. Escribió *"como el carbono no tiene ningún par de electrones libre, entonces GE = GM"*, que es exactamente la justificación que piden. En el H₂S puso el ángulo **109,5°** y se lo aceptaron con ✓, pero lo prolijo es **"< 109,5°"**.

---

## 2c) Polaridad y momento dipolar · ⭐ el punto conceptual del parcial

**El método, en dos pasos:**

```
1. ¿Los enlaces son polares?     → ΔEN entre los átomos
2. ¿Se CANCELAN los vectores μ?  → depende de la GEOMETRÍA MOLECULAR (¡no de la electrónica!)

   simétrica (todos los sustituyentes iguales
   y distribuidos parejo)  →  Σμ = 0  →  NO POLAR
   asimétrica              →  Σμ ≠ 0  →  POLAR
```

---

### SiH₄ — **NO POLAR** (μ = 0)

```
ΔEN(Si–H) = 2,20 − 1,90 = 0,30      → enlaces LEVEMENTE polares
Geometría molecular: TETRAÉDRICA, los 4 sustituyentes IGUALES
```

```
              H
              |            los 4 vectores μ apuntan a los
        H ─── Si ─── H     vértices de un tetraedro regular
              |            → se anulan de a pares
              H

              Σμ = 0
```

$$\boxed{\text{SiH}_4: \ \mu = 0 \ \Longrightarrow \ \textbf{NO POLAR}}$$

**La justificación completa:** los cuatro enlaces son **idénticos** (mismo átomo, misma ΔEN, misma longitud) y la geometría tetraédrica los distribuye de forma **perfectamente simétrica**, así que la **suma vectorial** de los cuatro momentos dipolares de enlace **es cero**. La molécula tiene enlaces polares pero **es no polar**.

⚠️ **"Enlace polar" ≠ "molécula polar".** Este es el ejemplo canónico. Igual que el CH₄ y el CCl₄.

---

### H₂S — **POLAR** (μ ≠ 0)

```
ΔEN(S–H) = 2,58 − 2,20 = 0,38       → enlaces polares (el S atrae más)
Geometría molecular: ANGULAR → ASIMÉTRICA
```

```
         ⟨:⟩   ⟨:⟩
           ⟍  ╱
             S              los 2 vectores μ NO son opuestos:
           ╱ ⟍ ⟍            forman ángulo → tienen RESULTANTE
        H      H  ⟍
                    ⟍  μ resultante ≠ 0  (apunta del S hacia afuera,
                        por la bisectriz)
```

$$\boxed{\text{H}_2\text{S}: \ \mu \neq 0 \ \Longrightarrow \ \textbf{POLAR}} \qquad (\mu_{exp} \approx 0{,}97\ \text{D})$$

**La justificación:** la geometría **angular** hace que los dos vectores μ **no se cancelen**; además los **2 pares libres** concentran densidad electrónica en un lado, lo que **refuerza** el momento dipolar en la dirección de la bisectriz.

📌 **Es menos polar que el agua** (μ_H₂O = 1,85 D) porque la ΔEN del S–H (0,38) es mucho menor que la del O–H (1,24).

---

### BrF₅ — **POLAR** (μ ≠ 0)

```
ΔEN(Br–F) = 3,98 − 2,96 = 1,02      → enlaces MUY polares
Geometría molecular: PIRÁMIDE DE BASE CUADRADA → ASIMÉTRICA
```

```
              F  ↑ μ del F axial
              |
       F ─────Br───── F      los 4 F basales se cancelan entre sí
              |               (están simétricos en el plano)
              F
            ⟨:⟩              pero el F AXIAL no tiene con quién
                             cancelarse: en la posición opuesta
                             hay un PAR LIBRE, no un F

                             → Σμ ≠ 0, sobre el eje axial
```

$$\boxed{\text{BrF}_5: \ \mu \neq 0 \ \Longrightarrow \ \textbf{POLAR}} \qquad (\mu_{exp} \approx 1{,}51\ \text{D})$$

💡 **El razonamiento en una frase:** *"si en la sexta posición del octaedro hubiera un F (o sea, si fuera BrF₆), la molécula sería octaédrica simétrica y no polar. Pero ahí hay un par libre, que rompe la simetría"*. **Comparalo con el SF₆, que es no polar** — es la comparación que gana el punto.

---

### CO₃²⁻ — ⚠️ **acá NO tiene sentido la pregunta**

**Esto es lo que el parcial está preguntando** con *"¿Tiene sentido clasificar como polar o no polar todos estos compuestos? ¿En qué casos no?"*. La respuesta es **el carbonato**, y hay que decir **por qué**:

**Razón 1 — es un ION, no una molécula neutra.** El CO₃²⁻ tiene **carga neta −2**. La clasificación polar / no polar describe cómo se distribuye la carga en una especie **globalmente neutra**: una molécula polar tiene un extremo con carga **parcial** δ⁺ y otro con δ⁻, sumando cero. Un anión **no tiene un extremo positivo**: es negativo en todas partes.

**Razón 2 — el momento dipolar de un ion no está bien definido.** Para una especie con carga neta, el valor de μ **depende del punto respecto del cual se calcula** (del origen de coordenadas elegido). No es una propiedad intrínseca de la especie, como sí lo es para una molécula neutra.

**Razón 3 — lo que sí se puede decir, y conviene decirlo:** por su **simetría trigonal plana** (los tres O equivalentes a 120°), las contribuciones de los tres enlaces C–O **se cancelan entre sí**. Y en cuanto a cómo interactúa, el CO₃²⁻ **no forma fuerzas dipolo–dipolo**: forma **interacciones ION–DIPOLO** (con el agua) e **iónicas** (con cationes, tipo Na₂CO₃ o CaCO₃), que son **mucho más intensas**.

$$\boxed{\text{CO}_3^{2-}: \text{ no corresponde clasificarlo como polar / no polar — es un ANIÓN}}$$

⚠️ **No contestes "no polar porque es simétrico" y listo.** La simetría es cierta, pero la pregunta apunta a otra cosa: a que la categoría **no aplica**. Si sólo decís "no polar", perdés el punto conceptual.

> 📝 **Respuesta tipo parcial — 2c completo**
>
> | Especie | Enlaces | GM | Simetría | μ | Clasificación |
> |---|---|---|---|---|---|
> | **SiH₄** | polares (ΔEN 0,30) | tetraédrica | **simétrica** | **μ = 0** | **NO POLAR** |
> | **H₂S** | polares (ΔEN 0,38) | angular | asimétrica | **μ ≠ 0** (≈0,97 D) | **POLAR** |
> | **BrF₅** | muy polares (ΔEN 1,02) | pirámide base cuadrada | asimétrica | **μ ≠ 0** (≈1,51 D) | **POLAR** |
> | **CO₃²⁻** | polares | trigonal plana | simétrica | **no definido** | ⚠️ **no aplica: es un anión** |
>
> **Sobre el momento dipolar:** la polaridad de una molécula es la **suma vectorial** de los momentos dipolares de sus enlaces, y por eso depende de la **geometría MOLECULAR** (no de la electrónica). El SiH₄ tiene enlaces polares y sin embargo μ = 0, porque los cuatro vectores se anulan por simetría. En el H₂S la geometría angular impide la cancelación. En el BrF₅ los cuatro F basales se cancelan entre sí, pero el F axial queda sin compensar (enfrente tiene un **par libre**, no un átomo), de modo que hay resultante sobre el eje axial — a diferencia del SF₆, que es octaédrico simétrico y no polar.
>
> **No tiene sentido clasificar al CO₃²⁻.** Es un **anión con carga neta −2**, no una especie neutra: la clasificación polar / no polar describe la **distribución interna** de la carga en una especie globalmente neutra (δ⁺ en un extremo, δ⁻ en el otro). Además, el **momento dipolar de un ion depende del origen de coordenadas** que se elija, así que no es una propiedad intrínseca. Lo que corresponde decir del CO₃²⁻ es que interactúa por **fuerzas ión–dipolo** (con solventes polares) e **iónicas** (con cationes), no por dipolo–dipolo.

🖊️ **Lo que puso ella:** los cuatro casos bien resueltos, incluido el conceptual: *"no tiene sentido hablar de polaridad con CO₃²⁻ porque al tener una carga negativa es un anión; las moléculas polares se basan en tener una carga parcial negativa y una positiva. CO₃²⁻ es una molécula con carga neta negativa"*. **Es la respuesta que buscaban.** Sacó 25/25 en este problema.

---
---

# PROBLEMA 3 (25 puntos)

## Enunciado

> A partir de una solución de **NaOH 2,5 M** cuya **densidad es 1,110 g/mL**, indique:
>
> **a)** Su concentración expresada como **% m/m** y **% m/V**.
> **b)** La **masa de soluto** que se encuentra disuelta en **50 mL** de solución.
> **c)** Explique **cómo prepararía 1 L de una solución 0,5 M** a partir de la solución anterior y la **cantidad de agua** necesaria. **Esquematice el material** utilizado para la preparación.
> **d)** Se toma una **alícuota de 10 mL** de la solución preparada en c), se la introduce en un **matraz de 250 mL** y se lleva a volumen con agua destilada. **Calcular la molaridad resultante.**

---

## Lo primero, siempre: la masa molar

$$M_r(\text{NaOH}) = 23\ (\mathrm{Na}) + 16\ (\mathrm{O}) + 1\ (\mathrm{H}) = \mathbf{40\ g/mol}$$

💡 **El NaOH tiene Mr = 40. Memorizalo**: aparece en todos los parciales y en la mitad de los ejercicios de la Serie 4.

---

## 3a) % m/m y % m/V

### La estrategia: pararse en 1 LITRO de solución

**Por qué 1 L:** la molaridad ya está expresada **por litro**. Si tomás justo 1 L, la cuenta de moles es directa y la densidad te da la masa de solución de una.

```
BASE DE CÁLCULO: 1 L = 1000 mL de solución
```

**Paso 1 — masa de SOLUTO en ese litro** (de la molaridad):

$$n_{sto} = 2{,}5\ \frac{\text{mol}}{\text{L}} \times 1\ \text{L} = 2{,}5\ \text{mol}$$

$$m_{sto} = 2{,}5\ \text{mol} \times 40\ \frac{\text{g}}{\text{mol}} = \mathbf{100\ g\ de\ NaOH}$$

**Paso 2 — masa de SOLUCIÓN en ese litro** (de la densidad):

$$m_{sc} = V_{sc} \cdot \delta = 1000\ \text{mL} \times 1{,}110\ \frac{\text{g}}{\text{mL}} = \mathbf{1110\ g\ de\ solución}$$

⚠️ **La densidad SIEMPRE es de la solución**, nunca del soluto ni del solvente. Es el puente masa ↔ volumen.

**Paso 3 — los dos porcentajes:**

$$\% \frac{m}{V} = \frac{m_{sto}}{V_{sc}} \cdot 100 = \frac{100\ \text{g}}{1000\ \text{mL}} \cdot 100 = \boxed{10\ \%\ m/V}$$

$$\% \frac{m}{m} = \frac{m_{sto}}{m_{sc}} \cdot 100 = \frac{100\ \text{g}}{1110\ \text{g}} \cdot 100 = 9{,}009\ldots = \boxed{9{,}01\ \%\ m/m}$$

### El atajo (para chequear, o si vas corto de tiempo)

$$\%\frac{m}{V} = \frac{M \cdot M_r}{10} = \frac{2{,}5 \times 40}{10} = 10\ \% \quad ✓$$

$$\%\frac{m}{m} = \frac{\%m/V}{\delta_{sc}} = \frac{10}{1{,}110} = 9{,}01\ \% \quad ✓$$

💡 **Chequeo de coherencia sin hacer cuentas:** como $\delta_{sc} = 1{,}110 > 1$, tenés **más gramos que mililitros** de solución → el denominador del %m/m es más grande → **% m/m < % m/V**. Y da 9,01 < 10 ✓. **Si te queda %m/m > %m/V con una densidad mayor a 1, está mal.**

> 📝 **Respuesta tipo parcial**
>
> Tomo como base de cálculo **1 L de solución**.
>
> - Moles de soluto: $n = 2{,}5\ \text{mol/L} \times 1\ \text{L} = 2{,}5\ \text{mol}$
> - Masa de soluto: $m_{sto} = 2{,}5\ \text{mol} \times 40\ \text{g/mol} = \mathbf{100\ g}$
> - Masa de solución: $m_{sc} = 1000\ \text{mL} \times 1{,}110\ \text{g/mL} = \mathbf{1110\ g}$
>
> $$\%\frac{m}{V} = \frac{100\ \text{g}}{1000\ \text{mL}}\cdot 100 = \mathbf{10\ \%\ m/V}$$
>
> $$\%\frac{m}{m} = \frac{100\ \text{g}}{1110\ \text{g}}\cdot 100 = \mathbf{9{,}01\ \%\ m/m}$$
>
> Es consistente que **% m/m < % m/V** porque la densidad de la solución es **mayor que 1 g/mL**.

🖊️ **Lo que puso ella:** 10 % m/V y 9 % m/m, con ✓. Resolvió todo con reglas de tres sin usar las fórmulas — perfectamente válido y suele ser más rápido.

---

## 3b) Masa de soluto en 50 mL de solución

**Directo por la molaridad** (o por regla de tres desde el ítem a):

$$n = 2{,}5\ \frac{\text{mol}}{\text{L}} \times 0{,}050\ \text{L} = 0{,}125\ \text{mol}$$

$$m_{sto} = 0{,}125\ \text{mol} \times 40\ \frac{\text{g}}{\text{mol}} = \boxed{5\ \text{g de NaOH}}$$

**Por regla de tres, si preferís:**

```
1000 mL de sc  →  100 g de NaOH
  50 mL de sc  →     x = 100 × 50/1000 = 5 g
```

⚠️ **Pasá los mL a L antes de multiplicar por la molaridad.** Si usás 50 en lugar de 0,050 te da **1000 veces más**.

💡 **Chequeo:** 50 mL es 1/20 de litro → 100 g / 20 = 5 g ✓

> 📝 **Respuesta tipo parcial**
>
> $$n_{sto} = M \cdot V = 2{,}5\ \text{mol/L} \times 0{,}050\ \text{L} = 0{,}125\ \text{mol}$$
> $$m_{sto} = 0{,}125\ \text{mol} \times 40\ \text{g/mol} = \mathbf{5\ g\ de\ NaOH}$$
>
> (Equivalente: la solución es 10 % m/V, o sea 10 g cada 100 mL → en 50 mL hay 5 g.)

---

## 3c) Preparar 1 L de solución 0,5 M por dilución

### La idea: en una dilución los MOLES DE SOLUTO NO CAMBIAN

Sólo agregás solvente. Entonces:

$$\boxed{n_i = n_f \;\Longrightarrow\; C_i \cdot V_i = C_f \cdot V_f}$$

### Paso 1 — cuánto volumen de la solución concentrada hace falta

```
C_i = 2,5 M       (la solución del enunciado)
C_f = 0,5 M       (la que quiero)
V_f = 1000 mL     (el volumen final que quiero)
V_i = ?
```

$$V_i = \frac{C_f \cdot V_f}{C_i} = \frac{0{,}5\ \text{M} \times 1000\ \text{mL}}{2{,}5\ \text{M}} = \boxed{200\ \text{mL de solución 2,5 M}}$$

**Verificación por moles** (hacela siempre, son 5 segundos):

```
moles que necesito:  0,5 mol/L × 1 L      = 0,5 mol   (= 20 g de NaOH)
moles en 200 mL:     2,5 mol/L × 0,200 L  = 0,5 mol  ✓
```

### Paso 2 — la cantidad de agua

$$V_{agua} = V_f - V_i = 1000\ \text{mL} - 200\ \text{mL} = \boxed{\approx 800\ \text{mL de agua destilada}}$$

⚠️ **Acá hay que declarar una suposición, y el enunciado la está buscando:** para restar volúmenes hay que **suponer que los volúmenes son aditivos**. En rigor no lo son (las interacciones soluto–solvente cambian el volumen total). Por eso, **en la práctica no se miden los 800 mL**: se agrega agua **hasta el aforo** del matraz de 1 L.

💡 **El factor de dilución:** $\frac{2{,}5}{0{,}5} = 5$ → es una **dilución 1:5** (1 volumen de concentrada + agua hasta completar 5 volúmenes).

### Paso 3 — el procedimiento y el material (esto vale puntos)

```
    ┌──────────────┐          ┌──────────────┐          ┌──────────────┐
    │              │          │   ╲      ╱   │          │   ╲      ╱   │
    │  ░░░░░░░░░░  │  ──────► │    ╲    ╱    │  ──────► │    ╲    ╱    │
    │  ░ 2,5 M  ░  │  200 mL  │     ╲__╱     │  + H₂O   │     ╲__╱     │
    │  ░░░░░░░░░░  │          │   ──┼─── ← aforo        │   ──┼───     │
    └──────────────┘          │     │        │          │  ░░░│░░░     │
      solución madre          │     │        │          │  ░ 0,5 M ░   │
      (vaso / frasco)         └─────┴────────┘          └─────┴────────┘
                              matraz aforado 1 L         SOLUCIÓN FINAL
                                                            1 L, 0,5 M

              ↑
        con PIPETA AFORADA + pera de goma
        (2 cargas de 100 mL, o probeta de 250 mL)
```

**Los pasos, para escribir en la hoja:**

1. **Medir 200 mL** de la solución de NaOH 2,5 M con **pipeta aforada** (dos cargas de 100 mL) usando **pera de goma** — ⚠️ **nunca pipetear con la boca**, y menos NaOH, que es cáustico.
2. **Transferir** al **matraz aforado de 1000 mL**, que ya tiene un poco de agua destilada en el fondo.
3. **Agregar agua destilada** agitando suavemente, hasta cerca del aforo.
4. **Completar hasta el aforo gota a gota** (con pipeta o gotero), leyendo el **menisco a la altura de los ojos**, por la parte **inferior** del menisco.
5. **Tapar y homogeneizar** invirtiendo el matraz varias veces.
6. **Trasvasar** a un frasco **rotulado** (NaOH 0,5 M, fecha).

| Material | Para qué |
|---|---|
| **Pipeta aforada** (100 mL ×2) o **probeta de 250 mL** | Medir los 200 mL de solución madre |
| **Pera de goma / propipeta** | Aspirar sin usar la boca |
| **Matraz aforado de 1000 mL** ⭐ | **El que define el volumen final** |
| **Frasco lavador con agua destilada** | Llevar a volumen |
| **Frasco + rótulo** | Guardar la solución |

⚠️ **El material clave es el MATRAZ AFORADO de 1 L.** Si decís "vaso de precipitados" o "probeta" para el volumen final, perdés el punto: sólo el matraz aforado tiene la precisión para fijar un volumen exacto. **Aforado > graduado** cuando querés **un** volumen; graduado cuando querés **varios**.

> 📝 **Respuesta tipo parcial**
>
> En una **dilución los moles de soluto se conservan**, así que $C_i V_i = C_f V_f$:
>
> $$V_i = \frac{0{,}5\ \text{M} \times 1000\ \text{mL}}{2{,}5\ \text{M}} = \mathbf{200\ mL\ de\ la\ solución\ 2{,}5\ M}$$
>
> Verificación: $2{,}5\ \text{mol/L} \times 0{,}200\ \text{L} = 0{,}5\ \text{mol} = 0{,}5\ \text{mol/L} \times 1\ \text{L}$ ✓ (20 g de NaOH).
>
> **Agua necesaria:** $1000 - 200 = \mathbf{800\ mL}$, **suponiendo volúmenes aditivos**. En la práctica no se miden: se lleva a volumen hasta el aforo.
>
> **Procedimiento:** medir 200 mL de la solución madre con **pipeta aforada** y **pera de goma**, transferir a un **matraz aforado de 1000 mL** con algo de agua destilada, completar con agua destilada **hasta el aforo** (menisco a la altura de los ojos), tapar y homogeneizar por inversión. Es una **dilución 1:5**.

🖊️ **Lo que puso ella:** V₁ = 200 mL y 800 mL de agua, con ✓, y aclaró explícitamente *"como no se sabe la densidad de la sc₂ suponemos V aditivos"* — **muy bien**, esa aclaración es la que el docente quiere leer.

---

## 3d) Alícuota de 10 mL a matraz de 250 mL

**Es otra dilución.** Misma fórmula, ahora partiendo de la solución **0,5 M** preparada en c):

```
C_i = 0,5 M       V_i = 10 mL
C_f = ?           V_f = 250 mL     ← el volumen del MATRAZ (se lleva a volumen)
```

$$C_f = \frac{C_i \cdot V_i}{V_f} = \frac{0{,}5\ \text{M} \times 10\ \text{mL}}{250\ \text{mL}} = \boxed{0{,}02\ \text{M}}$$

**Chequeo por moles:**

```
moles en la alícuota:  0,5 mol/L × 0,010 L = 0,005 mol   (= 0,2 g de NaOH)
en 250 mL:             0,005 mol / 0,250 L = 0,02 mol/L  ✓
```

**El factor de dilución:**

$$f = \frac{V_f}{V_i} = \frac{250}{10} = 25 \;\Longrightarrow\; \text{dilución } \mathbf{1{:}25} \;\Longrightarrow\; \frac{0{,}5}{25} = 0{,}02\ \text{M} \ ✓$$

⚠️ **"Se lleva a volumen" significa que el volumen FINAL es el del matraz (250 mL)**, no 250 + 10. La alícuota ya está **incluida** dentro de los 250 mL.

💡 **El resultado se puede ver sin calculadora:** diluir 1:25 es dividir por 25. 0,5/25 = 0,02.

📌 **La cadena completa del problema 3, para tener perspectiva:**

$$2{,}5\ \text{M} \ \xrightarrow[\text{1:5}]{\ 200\,\text{mL} \to 1\,\text{L}\ } \ 0{,}5\ \text{M} \ \xrightarrow[\text{1:25}]{\ 10\,\text{mL} \to 250\,\text{mL}\ } \ 0{,}02\ \text{M}$$

**Dilución total: 1:125** ($2{,}5 / 0{,}02 = 125 = 5 \times 25$) ✓

> 📝 **Respuesta tipo parcial**
>
> La alícuota se lleva a volumen en el matraz, así que $V_f = 250$ mL (la alícuota está incluida):
>
> $$C_f = \frac{C_i V_i}{V_f} = \frac{0{,}5\ \text{M} \times 10\ \text{mL}}{250\ \text{mL}} = \mathbf{0{,}02\ M}$$
>
> Verificación por moles: en 10 mL de la solución 0,5 M hay $0{,}005$ mol, que en 250 mL dan $0{,}005/0{,}250 = 0{,}02$ mol/L ✓. Es una **dilución 1:25**.

🖊️ **Lo que puso ella:** 0,02 M por los **dos caminos** (fórmula de dilución y balance de masa de soluto), con ✓. Buena práctica: si te sobra tiempo, verificá por el otro método.

---
---

# PROBLEMA 4 (25 puntos)

## Enunciado

> **a)** Se precisa preparar **1 L de una solución de Na₂SO₄ 0,3 M**. Para ello se emplean dos soluciones existentes de dicha sal: **a) 100 mL 0,25 M** y **b) 250 mL 0,45 M**, y la cantidad necesaria del **sólido (Na₂SO₄(s))**. Calcule cómo lo hace e **indique qué suposiciones realiza**.
>
> **b)** En un vaso conteniendo **300 g de agua** se agregan **180 g de acetato de sodio (NaAc)**. La solubilidad del NaAc es:
>
> | T (°C) | 20 | 30 | 40 | 50 | 60 |
> |---|---|---|---|---|---|
> | **S (g/100 g agua)** | 48 | 55 | 68 | 85 | 110 |
>
> **i)** Indique a qué temperatura podría disolver completamente la sal.
>
> **c)** Si luego el sistema se enfría hasta **20 °C**, responda:
> **i)** ¿qué cantidad de sal queda disuelta? · **ii)** ¿Cuánto sólido precipita?

---

## 4a) Mezclar dos soluciones + agregar sólido

### La masa molar primero

$$M_r(\text{Na}_2\text{SO}_4) = 2 \times 23 + 32 + 4 \times 16 = 46 + 32 + 64 = \mathbf{142\ g/mol}$$

⚠️ **Cuidado con el subíndice 2 del Na.** Si pones 23 en lugar de 46 te da 119 y arrastrás el error a todo el problema.

### La estrategia: BALANCE DE MOLES DE SOLUTO

$$\boxed{n_{\text{necesarios}} = n_A + n_B + n_{\text{sólido}}}$$

**Paso 1 — cuántos moles necesito en total:**

$$n_{total} = 0{,}3\ \frac{\text{mol}}{\text{L}} \times 1\ \text{L} = 0{,}3\ \text{mol} \;\Longrightarrow\; m = 0{,}3 \times 142 = \mathbf{42{,}6\ g}$$

**Paso 2 — cuántos moles aporta cada solución:**

| Solución | V | C | $n = C \cdot V$ | masa |
|---|---|---|---|---|
| **A** | 100 mL = 0,100 L | 0,25 M | **0,0250 mol** | 3,55 g |
| **B** | 250 mL = 0,250 L | 0,45 M | **0,1125 mol** | 15,975 g |
| | | | **Σ = 0,1375 mol** | **19,525 g** |

**Paso 3 — lo que falta lo pone el sólido:**

$$n_{sólido} = 0{,}3 - 0{,}1375 = \mathbf{0{,}1625\ mol}$$

$$m_{sólido} = 0{,}1625\ \text{mol} \times 142\ \frac{\text{g}}{\text{mol}} = \boxed{23{,}075\ \text{g de Na}_2\text{SO}_4\ (s)}$$

**O directo por masas:** $42{,}6 - 19{,}525 = 23{,}075$ g ✓

### El volumen de agua

$$V_{agua} = 1000 - 100 - 250 = \boxed{\approx 650\ \text{mL}}$$

⚠️⚠️ **ACÁ ESTÁ EL ✗ DE LA CORRECCIÓN.** El docente le tachó justamente el `V_agua = 650 mL` "de cajita". Por qué el 650 mL es delicado:

```
V_A + V_B + V_agua = V_final     ← esta igualdad ignora DOS cosas:

   1. que los volúmenes NO son estrictamente aditivos
   2. que los 23 g de sólido disuelto TAMBIÉN aportan volumen
```

**Cómo se contesta bien** (y de paso responde el *"indique qué suposiciones realiza"*):

> **No hace falta calcular el volumen de agua**, y de hecho no se puede calcular con exactitud sin las densidades. El procedimiento correcto es: volcar las dos soluciones y el sólido en un **matraz aforado de 1 L** y **llevar a volumen** con agua destilada hasta el aforo. Así el volumen final queda **garantizado por el matraz**, sin necesidad de suponer nada.
>
> Si de todas formas se quiere estimar el agua a agregar, son **≈ 650 mL**, y para eso hay que suponer: (1) **volúmenes aditivos**, y (2) que el **sólido no aporta volumen apreciable**.

### Todas las suposiciones (esto es lo que el enunciado pide explícitamente)

| # | Suposición | Por qué hace falta |
|---|---|---|
| 1 | **El soluto se conserva**: los moles de A + los de B + los del sólido = los del final | Es un balance de materia; no hay reacción química, sólo mezcla |
| 2 | **El sólido es puro y anhidro** (no es el decahidrato Na₂SO₄·10H₂O) | Si fuera hidratado, Mr = 322 g/mol y necesitarías **52,3 g**, no 23,1 g. ⭐ Trampa clásica |
| 3 | **Todo el sólido se disuelve** (no se supera la solubilidad) | 42,6 g/L está muy por debajo de la solubilidad del Na₂SO₄ (~195 g/L a 25 °C) ✓ |
| 4 | **Volúmenes aditivos** y **el sólido no aporta volumen** | **Sólo si querés informar los 650 mL.** Si llevás a volumen en matraz aforado, **no la necesitás** |
| 5 | **Misma temperatura** en las tres soluciones y en la final | El volumen depende de T; la molaridad también |

**Verificación final** (hacela: es el chequeo que confirma todo):

```
moles totales = 0,0250 + 0,1125 + 0,1625 = 0,3000 mol
volumen final = 1,000 L
concentración = 0,3000 / 1,000 = 0,300 M  ✓
```

> 📝 **Respuesta tipo parcial**
>
> $M_r(\text{Na}_2\text{SO}_4) = 2(23) + 32 + 4(16) = 142$ g/mol.
>
> **Moles necesarios:** $n = 0{,}3\ \text{M} \times 1\ \text{L} = 0{,}3\ \text{mol}$ (= 42,6 g).
>
> **Aportes de las soluciones existentes:**
> - A: $0{,}25\ \text{M} \times 0{,}100\ \text{L} = 0{,}0250\ \text{mol}$ (3,55 g)
> - B: $0{,}45\ \text{M} \times 0{,}250\ \text{L} = 0{,}1125\ \text{mol}$ (15,975 g)
> - Subtotal: **0,1375 mol (19,525 g)**
>
> **Sólido a agregar:**
> $$n = 0{,}3 - 0{,}1375 = 0{,}1625\ \text{mol} \;\Longrightarrow\; m = 0{,}1625 \times 142 = \mathbf{23{,}075\ g\ de\ Na_2SO_4(s)}$$
>
> **Procedimiento:** trasvasar los 100 mL de A y los 250 mL de B a un **matraz aforado de 1000 mL**, agregar los 23,075 g de sólido, disolver agitando y **llevar a volumen** con agua destilada hasta el aforo. Homogeneizar por inversión.
>
> **Suposiciones:** (1) el soluto se conserva (no hay reacción, sólo mezcla); (2) el sólido es **puro y anhidro** — si fuera el decahidrato Na₂SO₄·10H₂O habría que usar Mr = 322 g/mol y pesar 52,3 g; (3) todo el sólido se disuelve (42,6 g/L está muy por debajo de la solubilidad del Na₂SO₄); (4) las tres soluciones están a la **misma temperatura**. **No es necesario calcular el volumen de agua**, ya que se lleva a volumen en el matraz aforado; si se quisiera estimarlo serían ≈ 650 mL, pero eso exige suponer además **volúmenes aditivos** y volumen despreciable del sólido.

🖊️ **Lo que puso ella:** los 23,075 g **correctos** (✓ del docente), y aclaró *"como no sabemos las densidades de ninguna de las tres soluciones suponemos que son volúmenes aditivos"*. El docente le **tachó con ✗** el recuadro `V_AGUA (necesario) = 650 mL`. La lectura más probable es la de arriba: el volumen de agua no es un dato que se calcule, se **lleva a volumen**. ⚠️ **No podemos saber con certeza qué objetó el docente** (no dejó comentario escrito), pero si el punto pide "qué suposiciones realiza", la respuesta segura es **mencionar el matraz aforado y no comprometerse con un número de mL de agua**.

---

## 4b) ¿A qué temperatura se disuelve todo?

### Paso 1 — traducir el problema a las unidades de la tabla

La tabla está en **g de sal / 100 g de AGUA** (⚠️ agua, no solución). Entonces hay que preguntar: *¿cuántos gramos de sal por cada 100 g de agua hay en este vaso?*

```
300 g de agua  →  180 g de NaAc
100 g de agua  →  x
```

$$x = \frac{180 \times 100}{300} = \boxed{60\ \text{g de NaAc / 100 g de agua}}$$

⚠️ **Este es el paso que la gente saltea.** No podés comparar 180 g con los números de la tabla: la tabla está normalizada a **100 g de agua**.

### Paso 2 — buscar en la tabla dónde S ≥ 60

| T (°C) | S (g/100 g agua) | ¿Alcanza para 60? |
|---|---|---|
| 20 | 48 | ❌ no (48 < 60) |
| **30** | **55** | ❌ **no** (55 < 60) |
| **40** | **68** | ✅ **sí** (68 > 60) |
| 50 | 85 | ✅ sí |
| 60 | 110 | ✅ sí |

$$\text{La temperatura buscada está } \boxed{\text{entre 30 y 40 °C}}$$

### Paso 3 — la temperatura mínima, por interpolación lineal (el plus)

Entre 30 y 40 °C la solubilidad sube de 55 a 68 g/100 g:

$$\text{pendiente} = \frac{68 - 55}{40 - 30} = \frac{13\ \text{g}}{10\ °\text{C}} = 1{,}3\ \frac{\text{g}}{°\text{C}}$$

$$T = 30 + \frac{60 - 55}{1{,}3} = 30 + 3{,}85 = \boxed{\approx 33{,}8\ °\text{C} \approx 34\ °\text{C}}$$

$$\boxed{T_{mín} \approx 34\ °\text{C} \ \text{(a 40 °C ya seguro se disuelve todo)}}$$

💡 **En el parcial:** con decir **"entre 30 y 40 °C, y a 40 °C con seguridad"** ya te lo aceptan (a ella le pusieron ✓ con eso). La interpolación es el plus que muestra que sabés leer la curva. **Aclarala como aproximada**: la solubilidad no es exactamente lineal con T.

⚠️ **Lo que NO hay que contestar:** "a 30 °C". A 30 °C sólo entran 55 g/100 g = 165 g en los 300 g de agua → quedan **15 g sin disolver**. Fijate que **hacia arriba** siempre es más seguro.

> 📝 **Respuesta tipo parcial**
>
> Primero llevo la mezcla a la unidad de la tabla (g de sal por 100 g de **agua**):
>
> $$\frac{180\ \text{g NaAc}}{300\ \text{g agua}} \times 100 = \mathbf{60\ g\ NaAc\ /\ 100\ g\ agua}$$
>
> Busco en la tabla la temperatura a la cual $S \geq 60$: a **30 °C** la solubilidad es 55 g/100 g (**insuficiente**) y a **40 °C** es 68 g/100 g (**suficiente**). Por lo tanto la sal se disuelve completamente **a partir de una temperatura entre 30 y 40 °C**, y con certeza **a 40 °C o más**.
>
> Interpolando linealmente entre esos dos puntos ($1{,}3$ g por °C):
>
> $$T_{mín} = 30\ °\text{C} + \frac{60-55}{1{,}3} \approx \mathbf{34\ °C}$$
>
> (valor aproximado, ya que la solubilidad no varía exactamente en forma lineal con la temperatura).

---

## 4c) Enfriar a 20 °C

### i) ¿Cuánta sal queda disuelta?

**A 20 °C la solubilidad es el techo: 48 g / 100 g de agua.** Y el agua sigue siendo 300 g (enfriar no cambia el solvente).

```
100 g de agua  →  48 g de NaAc  (máximo, solución saturada)
300 g de agua  →  x
```

$$x = 48 \times 3 = \boxed{144\ \text{g de NaAc disueltos}}$$

**En moles**, si lo piden: $M_r(\text{NaAc} = \text{CH}_3\text{COONa}) = 2(12) + 3(1) + 2(16) + 23 = 82$ g/mol

$$n = \frac{144\ \text{g}}{82\ \text{g/mol}} = 1{,}76\ \text{mol}$$

⚠️ **La solubilidad es un TECHO, no una cantidad fija.** A 20 °C, por más sal que haya en el vaso, no se disuelven más de 144 g. Lo que sobra queda como sólido en el fondo.

### ii) ¿Cuánto sólido precipita?

$$m_{precipitado} = m_{total} - m_{disuelto} = 180 - 144 = \boxed{36\ \text{g de NaAc precipitan}}$$

**En moles:** $36 / 82 = 0{,}44$ mol.

**El estado final del sistema:**

```
    ┌──────────────┐
    │░░░░░░░░░░░░░░│   ← SOLUCIÓN SATURADA a 20 °C
    │░ 144 g NaAc ░│      (300 g agua + 144 g NaAc disueltos)
    │░ disueltos  ░│
    │▓▓▓▓▓▓▓▓▓▓▓▓▓▓│   ← 36 g de NaAc SÓLIDO en el fondo
    └──────────────┘

    SISTEMA HETEROGÉNEO, 2 FASES:
      · fase líquida: solución saturada
      · fase sólida:  el precipitado (36 g)
```

💡 **El chequeo obvio:** 144 + 36 = 180 ✓ (la sal no desaparece, se reparte entre disuelta y precipitada).

📌 **Por qué precipita al enfriar:** para casi todas las sales la **solubilidad crece con T** (la disolución es endotérmica). Al bajar de ~34 °C a 20 °C el techo baja de 60 a 48 g/100 g, y el excedente **cristaliza**. Es exactamente el principio de la **recristalización**, la técnica que se usa para purificar sólidos.

> 📝 **Respuesta tipo parcial**
>
> **i)** A 20 °C la solubilidad del NaAc es **48 g / 100 g de agua**. El sistema tiene 300 g de agua (el enfriamiento no modifica la masa de solvente), entonces la máxima cantidad que puede permanecer disuelta es:
>
> $$m_{disuelta} = 48\ \frac{\text{g}}{100\ \text{g agua}} \times 300\ \text{g agua} = \mathbf{144\ g\ de\ NaAc}$$
>
> (equivalen a $144/82 = 1{,}76$ mol). La solución resultante está **saturada**.
>
> **ii)** El excedente cristaliza:
>
> $$m_{precipitado} = 180\ \text{g} - 144\ \text{g} = \mathbf{36\ g\ de\ NaAc\ sólido}$$
>
> El sistema final es **heterogéneo, con 2 fases**: la solución saturada y el precipitado. Chequeo: 144 + 36 = 180 g ✓.

🖊️ **Lo que puso ella:** 144 g disueltos y 36 g precipitados, con ✓. Le faltó decir que el sistema queda **heterogéneo / la solución queda saturada** — es la clase de frase que suma medio punto y sale gratis.

---
---

# 📋 TODAS LAS RESPUESTAS, JUNTAS

| Punto | Respuesta |
|---|---|
| **1a-i** | **CEE = 4s² 4p⁴** · **grupo 16** · **período 4** (el 3d¹⁰ NO va en la CEE) |
| **1a-ii** | 34 e⁻ → **Z = 34 → Se (selenio)**. Diagrama con 4s < 3d < 4p y **Hund en 4p** (↑↓ ↑ ↑) → 2 e⁻ desapareados |
| **1b** | Anión: **CEE = 2s² 2p⁶** · Neutro: **CEE = 2s² 2p⁵** → el elemento es el **F (flúor, Z = 9)** |
| **1c** | i) **FUNDAMENTAL** (F, es 2p⁵ por Hund) · ii) **NINGÚN ESTADO** (3d¹¹ viola Pauli) · iii) **EXCITADO** (Na, e⁻ promovido 2p→3s) |
| **2a** | e⁻ de valencia: CO₃²⁻ **24** · BrF₅ **42** · H₂S **8** · SiH₄ **8**. e⁻ del central: 8 / **12 (expandido)** / 8 / 8. **Resonancia sólo en CO₃²⁻ (3 estructuras)** |
| **2b** | CO₃²⁻ **trigonal plana / trigonal plana, 120°** · H₂S **tetraédrica / angular, < 109,5°** · BrF₅ octaédrica / pirámide base cuadrada, 90° y <90° · SiH₄ tetraédrica / tetraédrica, 109,5° |
| **2c** | **SiH₄ NO POLAR (μ = 0)** · **H₂S POLAR** · **BrF₅ POLAR** · **CO₃²⁻: no aplica, es un ANIÓN** (μ de un ion depende del origen; interactúa por ión–dipolo) |
| **3a** | **10 % m/V** y **9,01 % m/m** |
| **3b** | **5 g de NaOH** |
| **3c** | **200 mL** de la solución 2,5 M + agua hasta 1 L (**≈800 mL**, suponiendo V aditivos). **Matraz aforado de 1 L** + pipeta aforada + pera. Dilución **1:5** |
| **3d** | **0,02 M** (dilución **1:25**) |
| **4a** | **23,075 g de Na₂SO₄(s)** (0,1625 mol). Llevar a volumen en **matraz aforado de 1 L**; el agua es ≈650 mL **sólo si suponés V aditivos** |
| **4b** | La mezcla es **60 g/100 g agua** → se disuelve todo **entre 30 y 40 °C** (interpolando: **≈34 °C**) |
| **4c** | **144 g quedan disueltos** (solución saturada) y **precipitan 36 g**. Sistema **heterogéneo, 2 fases** |

---

# 🚨 LAS 12 TRAMPAS DE ESTE PARCIAL

| # | Dónde | La trampa | Cómo evitarla |
|---|---|---|---|
| 1 | **1a-i** | Meter el **3d¹⁰** en la CEE | La CEE lleva **sólo el n MÁXIMO**. El 3d es n = 3 → interno |
| 2 | **1a-ii** | Poner el **4p antes del 3d** en el diagrama, o llenar el 4p sin Hund | Orden: **4s < 3d < 4p**. Y en el 4p: **↑↓ ↑ ↑**, nunca ↑↓ ↑↓ |
| 3 | **1b** | Dar la CEE del **anión** cuando piden la del neutro (o al revés) | El anión Y⁻ **ganó** un e⁻ → el neutro tiene **9**, no 10 → es **F**, no Ne |
| 4 | **1c-i** | Marcarlo **excitado** porque el desapareado está en el pz | Los tres orbitales p son **degenerados**: da igual cuál queda semilleno |
| 5 | **1c-ii** | Decir "excitado" | Un excitado es un estado **posible**. 3d¹¹ **no existe** → ningún estado (Pauli) |
| 6 | **2a** | **Restar** los 2 e⁻ de la carga del CO₃²⁻ | **El anión SUMA** (24 e⁻, no 20). El catión resta |
| 7 | **2a** | Forzar el octeto en el Br | **Período 4 → orbitales d → expande** a 12 e⁻ |
| 8 | **2b** | Contar el doble enlace del CO₃²⁻ como **2 dominios** | Un enlace múltiple = **1 sola** región → 3 dominios → trigonal plana, no tetraédrica |
| 9 | **2c** | Contestar "**CO₃²⁻ es no polar porque es simétrico**" | La pregunta apunta a que **la categoría NO APLICA**: es un **anión con carga neta** |
| 10 | **2c** | Decir que el SiH₄ es polar "porque los enlaces son polares" | **Enlace polar ≠ molécula polar.** La geometría tetraédrica **cancela** los 4 vectores |
| 11 | **4a** | Usar **Mr = 119** para el Na₂SO₄ (olvidar el ×2 del Na) | $2(23) + 32 + 4(16) = \mathbf{142}$ |
| 12 | **4b** | Comparar los **180 g** directo con la tabla | La tabla es **por 100 g de AGUA**: primero normalizá → **60 g/100 g** |

**Bonus (el ✗ de la corrección):** en **4a**, presentar el **volumen de agua (650 mL) como un resultado calculado**. El volumen final lo fija el **matraz aforado**; el agua no se calcula, se agrega hasta el aforo. Si igual lo informás, decí explícitamente que supones **volúmenes aditivos** y **volumen despreciable del sólido**.

---

# 🎯 Comparación con los otros parciales del repo

| Tema | **Este (2C 2024 T1)** | 1C 2025 | EjTipo |
|---|---|---|---|
| **Espectroscopia / $E=hc/\lambda$** | ❌ no entra | ✅ asignar transiciones + kJ/mol | ✅ ν, E, kJ/mol |
| **Configuración electrónica** | ✅ **CEE + grupo/período + diagrama de energía** | ✅ CEE + excitados | ✅ basal/excitada/imposible |
| **Diagrama de energía dibujado** | ⭐ **SÍ (único de los tres)** | no | no |
| **Isoelectrónicos** | ✅ (Y⁻ con Ne) | no | ✅ |
| **Lewis** | ✅ 4 compuestos + resonancia | ✅ 5 compuestos | ✅ 4 compuestos |
| **Resonancia** | ⭐ **sí (CO₃²⁻)** | ✅ (NO₂⁻) | ✅ |
| **TRePEV con ángulos** | ✅ | ✅ | no |
| **Polaridad** | ⭐ **sí, y el caso conceptual del ION** | ✅ | no |
| **Fuerzas intermoleculares / T_eb** | ❌ **no entra** | ⭐ sí | no |
| **Soluciones (%, M, densidad)** | ✅ | ✅ | ✅ |
| **Diluciones** | ⭐ **dos en cadena (1:5 y 1:25)** | ✅ | ✅ |
| **Material de laboratorio / esquema** | ⭐ **SÍ, lo piden explícito** | no | no |
| **Mezcla de soluciones + sólido** | ⭐ **SÍ (con "qué suposiciones")** | ✅ iones en solución | no |
| **Curvas de solubilidad** | ✅ tabla (interpolar) | ✅ gráfico (g/L) | ✅ % m/m_sv |

⚠️ **Las dos diferencias grandes de este parcial:**
1. **Pide dibujar el diagrama de energía y el material de laboratorio.** Los otros dos no. Practicá el dibujo, no sólo la cuenta.
2. **Te pregunta "qué suposiciones realiza"** (4a) y **"¿tiene sentido clasificar…?"** (2c). Son **preguntas conceptuales con trampa** donde la respuesta correcta es *"acá la categoría no aplica"* o *"esto no se calcula, se lleva a volumen"*. **Ese tipo de pregunta es el que más gente pierde.**

📌 **Hacé los tres.** Entre este y el de 2025 queda cubierta toda la materia del 1er parcial.

---

> **Teoría:** `Clase1/` (C.E., tabla periódica) · `Clase2/` (Lewis, TRePEV) · `Clase3/` (polaridad) · `Clase6(5nohay)/` (soluciones)
> **Machete:** secciones **4–6** (C.E., iones, grupo/período) · **7–11** (Lewis, resonancia, TRePEV, polaridad) · **16–18** (concentración, diluciones, solubilidad)
> **Series:** `Practica/Serie1-Resuelta.md` · `Serie2-Resuelta.md` · `Serie3-Resuelta.md` · `Serie4-Resuelta.md`
> **Geometrías:** `Practica/TablaGeometrias-Completa.md`
> **Otros parciales:** `Parciales/1parcial/Parcial-2025-Resuelto.md` · `Parciales/1parcial/EjTipoParcial-Resuelto.md`
