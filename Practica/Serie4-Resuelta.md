# SERIE 4 — Resuelta paso a paso

**Química General — ECyT / UNSAM · 2C 2026**
**Tema:** Soluciones

> Visión microscópica de la solubilidad · Densidad · Concentración · % m/m y % m/V · Molaridad · Fracción molar · Dependencia de la solubilidad con la temperatura · Diluciones · Factor de dilución · Técnicas de preparación de soluciones y diluciones.

**Cómo usar este archivo:** cada ejercicio tiene el **procedimiento** desarrollado, la **cuenta** con los números puestos y, cuando el enunciado pide justificar, un bloque **📝 Respuesta tipo parcial** listo para copiar.

> 📖 **Teoría:** `Clase6(5nohay)/Clase6-Explicacion-Completa.md` · **Machete:** secciones **15 a 18** de `MACHETE.md`.
> ⚠️ **La guía saltea el ejercicio 6.** No falta nada: la numeración va 5 → 7.
> 🔴 **Ojo con las respuestas de la guía.** Hay **6 respuestas mal** en el original. Están marcadas con 🔴 en cada ejercicio y listadas juntas al final, en **Erratas de la guía**.

---
---

# 📋 Datos que se usan en toda la serie

## 🔑 El método, de punta a punta

Toda esta serie es **una sola cadena**, siempre la misma. Si te trabás, es porque te falta un eslabón:

```
              × δ_sc              × %m/m            ÷ Mr            ÷ V_sc(L)
   V_sc  ─────────────►  m_sc  ─────────────►  m_sto  ─────────►  n_sto  ─────────►  M
                          │
                          │  − m_sto
                          ▼
                        m_sv  ───────────────►  molalidad = n_sto / m_sv(kg)
                                                y  g sto / 100 g sv
```

**Las tres preguntas que hay que hacerse SIEMPRE, en este orden:**

| # | Pregunta | Por qué importa |
|---|---|---|
| **1** | ¿El dato está referido a **SOLUCIÓN** o a **SOLVENTE**? | % m/m, % m/V, M, ppm, x → **solución** · molalidad y "g/100 g de agua" → **solvente** |
| **2** | ¿Me dan **masa** o **volumen**? | Si tengo que cruzar de uno al otro **necesito la densidad**. Sin δ no hay puente |
| **3** | ¿Qué se **conserva** en la operación? | Diluir / mezclar / agregar agua → se conservan **MOLES** y **MASAS**. Evaporar → se conservan los **MOLES de soluto** |

⚠️ **El 90 % de los errores de esta serie es confundir "en 200 cm³ de agua" con "hasta 200 cm³ de solución".**
- **"EN 200 cm³ de agua"** → esos 200 g son de **SOLVENTE**. La solución pesa más y ocupa otro volumen.
- **"HASTA 200 cm³"** → esos 200 cm³ son de **SOLUCIÓN**. Ya está todo adentro.

## Masas molares (con la tabla periódica de la cátedra)

| Compuesto | Cuenta | Mr (g/mol) |
|---|---|---|
| **H₂O** | 2(1,008) + 16,00 | **18,02** |
| **NaCl** | 22,99 + 35,45 | **58,44** |
| **NaOH** | 22,99 + 16,00 + 1,008 | **40,00** |
| **HCl** | 1,008 + 35,45 | **36,46** |
| **HNO₃** | 1,008 + 14,01 + 48,00 | **63,02** |
| **H₂SO₄** | 2(1,008) + 32,06 + 64,00 | **98,08** |
| **KCl** | 39,10 + 35,45 | **74,55** |
| **KBr** | 39,10 + 79,90 | **119,00** |
| **KNO₃** | 39,10 + 14,01 + 48,00 | **101,11** |
| **K₂SO₄** | 2(39,10) + 32,06 + 64,00 | **174,26** |
| **AgNO₃** | 107,87 + 14,01 + 48,00 | **169,88** |
| **FeCl₃** | 55,85 + 3(35,45) | **162,20** |
| **Fe(NO₃)₃** | 55,85 + 3(62,01) | **241,88** |
| **CuSO₄** | 63,55 + 32,06 + 64,00 | **159,61** |
| **MnSO₄** | 54,94 + 32,06 + 64,00 | **151,00** |
| **Na₂SO₄** | 2(22,99) + 32,06 + 64,00 | **142,04** |
| **NaF** | 22,99 + 19,00 | **41,99** |
| **Na₂PO₃F** | 2(22,99) + 30,97 + 48,00 + 19,00 | **143,95** |
| **Sacarosa C₁₂H₂₂O₁₁** | 12(12,01) + 22(1,008) + 11(16,00) | **342,30** |
| **Glucosa C₆H₁₂O₆** | 6(12,01) + 12(1,008) + 6(16,00) | **180,16** |
| **Etanol C₂H₅OH** | 2(12,01) + 6(1,008) + 16,00 | **46,07** |

💡 **Truco de la sal:** para pasar de una sal a la masa de **UN ion**, usá la fracción de masa:

$$\boxed{m_{ion} = m_{sal}\cdot\frac{n_{iones}\cdot Ar_{ion}}{Mr_{sal}}}$$

📝 NaCl → Na: $\frac{22{,}99}{58{,}44} = \mathbf{0{,}3934}$ · Na₂SO₄ → Na: $\frac{2\times 22{,}99}{142{,}04} = \mathbf{0{,}3237}$ · NaF → F: $\frac{19{,}00}{41{,}99} = \mathbf{0{,}4525}$

## ⭐ La tabla de unidades (va de memoria al parcial)

| Unidad | Fórmula | Denominador | Unidades obligadas |
|---|---|---|---|
| **% m/m** | $\dfrac{m_{sto}}{m_{sc}}\cdot 100$ | Solución | Las **mismas** arriba y abajo |
| **% m/V** | $\dfrac{m_{sto}}{V_{sc}}\cdot 100$ | Solución | **g** y **cm³ (mL)** |
| **% V/V** | $\dfrac{V_{sto}}{V_{sc}}\cdot 100$ | Solución | Las mismas |
| **M** (molaridad) | $\dfrac{n_{sto}}{V_{sc}}$ | Solución | mol y **LITROS** ⚠️ |
| **m** (molalidad) | $\dfrac{n_{sto}}{m_{sv}}$ | ⚠️ **SOLVENTE** | mol y **kg** |
| **x** (fracción molar) | $\dfrac{n_{sto}}{n_{sto}+n_{sv}}$ | Totales | mol · queda entre **0 y 1** |
| **ppm** | $\dfrac{m_{sto}}{m_{sc}}\cdot 10^6$ | Solución | Las mismas |
| **ppb** | $\dfrac{m_{sto}}{m_{sc}}\cdot 10^9$ | Solución | Las mismas |

$$\boxed{1\ \% = 10\,000\ \text{ppm}} \qquad \boxed{1\ \text{ppm} = 1000\ \text{ppb}} \qquad \boxed{\text{ppm} \approx \tfrac{\text{mg}_{sto}}{\text{L}_{sc}}}\ \text{(sólo en agua diluida)}$$

## Datos sueltos que aparecen en la serie

| Dato | Valor |
|---|---|
| δ del **agua** | **1,00 g/mL** (si el problema no dice otra cosa, **usala**) |
| δ del **etanol** | 0,7893 g/cm³ |
| 1 L de agua | **55,5 mol** ⚠️ *no* es despreciable en la fracción molar |
| 1 dm³ | 1 L = 1000 cm³ = 1000 mL |
| ppm de un metal pesado en agua | ≈ mg/L (la solución es **casi agua pura**) |

---
---

# PROBLEMAS PARA DISCUTIR EN CLASE

---

## Ejercicio 1 — Visión microscópica de la disolución (completar)

### Las respuestas

| Hueco | Respuesta |
|---|---|
| La disgregación de la red es resultado de fuerzas… | **ATRACTIVAS** |
| Son más sensibles las especies situadas en… | la **SUPERFICIE** de la red |
| a) Se encuentran ______ ligadas a las demás | **MENOS** |
| b) Resultan ______ accesibles al disolvente | **MÁS** |
| Cuanto más dividido está el sólido, ______ superficie de contacto | **MAYOR** |
| … y por tanto ______ será la velocidad de disolución | **MAYOR** |

### Por qué

**El primer hueco es el que se erra.** Uno tiende a poner "repulsivas" porque la red **se rompe**, y romper suena a repeler. **Está al revés.**

Disolver un sólido es una **competencia entre dos atracciones**:

| Atracción | Entre quiénes | Qué hace |
|---|---|---|
| **Soluto – soluto** | ion⁺ ↔ ion⁻ de la red (ion–ion, 250 kJ/mol) | **Mantiene** la red armada. Hay que **vencerla** (cuesta energía, endotérmico) |
| **Soluto – solvente** | ion ↔ dipolo del H₂O (ion–dipolo, 15 kJ/mol) | **Arranca** la partícula de la red y la **solvata** (libera energía, exotérmico) |

El agua **no empuja** al ion hacia afuera: lo **tira** hacia sí. El ion sale de la red porque el conjunto de moléculas de agua que lo rodea lo atrae **más** de lo que la red lo retiene. Por eso la fuerza responsable de la disgregación es **atractiva** — y es la **soluto–solvente**.

$$\Delta H_{sol} = \underbrace{\Delta H_{red}}_{>0,\ \text{romper}} + \underbrace{\Delta H_{solv}}_{<0,\ \text{formar}}$$

**Por qué la superficie.** Un ion en el **interior** tiene vecinos en las 6 direcciones → está retenido por 6 atracciones y, además, **el agua no lo alcanza**. Un ion de un **vértice** o una **arista** tiene 3 vecinos y está expuesto:

```
   INTERIOR                      SUPERFICIE
   ┌───┬───┬───┐                 ← el agua llega
   │ + │ − │ + │              ┌───┬───┬───┐
   ├───┼───┼───┤              │ + │ − │ + │  ← 3 vecinos, expuesto
   │ − │ ⊕ │ − │   ⊕ tiene    ├───┼───┼───┤
   ├───┼───┼───┤   6 vecinos  │ − │ + │ − │
   │ + │ − │ + │   y NO se    └───┴───┴───┘
   └───┴───┴───┘   moja
```

**Por qué el grado de división.** Moler el sólido **no cambia** la solubilidad (cuánto se disuelve como máximo, que es **termodinámica**): cambia la **velocidad** (**cinética**), porque aumenta la relación **superficie/volumen**. Un cubo de 1 cm tiene 6 cm² de superficie; partido en cubitos de 1 mm son 1000 cubitos con **60 cm²**: diez veces más frente de ataque con la misma masa.

⚠️ **La trampa clásica del parcial:** *"si molés el azúcar, ¿se disuelve más?"* → **NO. Se disuelve más RÁPIDO.** El máximo lo fija la **solubilidad**, que depende sólo de la naturaleza del par soluto/solvente y de la **temperatura**.

> 📝 **Respuesta tipo parcial**
> La disgregación de la red es resultado de fuerzas **atractivas**: son las interacciones **soluto–solvente** (ion–dipolo, para una sal en agua) las que arrancan las partículas de la red venciendo las interacciones **soluto–soluto** que la mantenían unida. Las especies de la **superficie** son las más sensibles porque están **menos** ligadas (tienen menos vecinos que una del interior) y son **más** accesibles al disolvente. Al dividir el sólido aumenta la superficie de contacto y por lo tanto la **velocidad** de disolución — no la solubilidad, que es independiente del tamaño de partícula.

---

## Ejercicio 2 — ¿Qué especies hay en la solución?

**La pregunta real es: ¿el soluto se DISOCIA o no?** Y eso lo decide el **tipo de unión del soluto**.

| Tipo de soluto | ¿Qué queda en solución? |
|---|---|
| **Iónico** soluble | **IONES separados y solvatados** — ⚠️ ya **no existe** la "molécula" |
| **Molecular** (covalente) | **MOLÉCULAS enteras**, sólo rodeadas de solvente |
| **Ácido/base fuerte** | Iones (H₃O⁺ / OH⁻ + contraión) |

### a) Cloruro de sodio en agua

| Especie | Cómo está |
|---|---|
| **Na⁺(ac)** | **hidratado**: ~6 H₂O apuntándole con el **O** (δ⁻) |
| **Cl⁻(ac)** | **hidratado**: ~6 H₂O apuntándole con los **H** (δ⁺) |
| **H₂O** | en enorme exceso, en su red de puentes de H |

$$\text{NaCl}_{(s)} \xrightarrow{\ \text{H}_2\text{O}\ } \text{Na}^+_{(ac)} + \text{Cl}^-_{(ac)}$$

```
        H   H                       H       H
         \ /                         \     /
          O                           O   O
          |                            \ /
   H₂O — Na⁺ — OH₂              H — O — Cl⁻ — O — H
          |                            / \
          O                           H   H
         / \
        H   H
   el O (δ−) apunta          los H (δ+) apuntan
      al CATIÓN                  al ANIÓN
```

❌ **NO hay moléculas de NaCl en solución.** Es el error más marcado en los parciales. El NaCl sólido **ni siquiera es molecular**: es una **red cristalina** de iones. Al disolverse, la red se desarma en iones sueltos.
- Interacción que manda: **ion–dipolo** (15 kJ/mol).
- Consecuencia medible: **la solución CONDUCE la electricidad** (electrolito fuerte).

### b) I₂ en CCl₄

| Especie | Estado |
|---|---|
| **I₂** | moléculas **enteras**, diatómicas |
| **CCl₄** | moléculas enteras |

- Los dos son **no polares** (I₂ homonuclear, μ = 0; CCl₄ tetraédrico simétrico, μ = 0).
- Interacción única: **London**, entre dos especies muy polarizables (I₂ tiene 106 e⁻, CCl₄ tiene 74 e⁻) → **London fuerte**, por eso disuelve bien.
- ❌ **NO hay iones I⁻.** Romper el enlace I–I es romper un **covalente** (~150 kJ/mol): eso no lo hace un solvente.
- **NO conduce** la electricidad.
- 💡 Es el ejemplo canónico de **"lo semejante disuelve a lo semejante"**: el I₂ es casi insoluble en agua y muy soluble en CCl₄.

### c) N₂ en agua

| Especie | Estado |
|---|---|
| **N₂** | moléculas enteras, **poquísimas** |
| **H₂O** | todo el resto |

- El N₂ es **no polar** y tiene un **triple enlace** (945 kJ/mol): no se disocia ni reacciona.
- Interacción: **dipolo–dipolo inducido** (el H₂O polar induce un dipolo en el N₂). Es **la más débil de la tabla** (< 1 kJ/mol).
- Por eso la solubilidad del N₂ en agua es bajísima: **~0,02 g/L a 20 °C**.
- Es un **gas**: su solubilidad **BAJA** al subir la T y **SUBE** con la presión (**ley de Henry**, $S = k_H\cdot P$).
- 📡 **Aplicación:** ésta es la causa del **síndrome de descompresión** en buceo. A 40 m la presión es ~5 atm y se disuelve 5 veces más N₂ en sangre; si el buzo sube rápido, la presión cae, el N₂ deja de ser soluble y **burbujea dentro del cuerpo**.

> 📝 **Respuesta tipo parcial**
> a) Iones **Na⁺(ac)** y **Cl⁻(ac)** hidratados, más H₂O. El NaCl es iónico: se disocia por completo y **no quedan moléculas de NaCl**. Interacción ion–dipolo; la solución conduce.
> b) Moléculas de **I₂** y de **CCl₄**, ambas enteras. Los dos son no polares: sólo hay fuerzas de **London**. No hay iones y no conduce.
> c) Moléculas de **N₂** (muy pocas) y H₂O. El N₂ es no polar y su enlace triple no se rompe: sólo interacción **dipolo–dipolo inducido**, la más débil, de ahí la solubilidad casi nula.

---

## Ejercicio 3 — % m/m y g de soluto / 100 g de solvente

> 2 sobrecitos de 6,25 g de sacarosa **en 200 cm³ de agua**.

### Datos y la trampa

| Dato | Valor | ¿De qué es? |
|---|---|---|
| Sacarosa | 2 × 6,25 = **12,5 g** | **SOLUTO** |
| Agua | 200 cm³ × 1,00 g/cm³ = **200 g** | ⚠️ **SOLVENTE**, no solución |

⚠️ Dice **"en 200 cm³ de agua"**. Esos 200 g son de **agua sola**. La solución pesa **más**:

$$m_{sc} = m_{sto} + m_{sv} = 12{,}5 + 200 = \mathbf{212{,}5\ g}$$

*(las masas **sí** son aditivas — los volúmenes no)*

### a) % m/m

$$\%\tfrac{m}{m} = \frac{m_{sto}}{m_{sc}}\cdot 100 = \frac{12{,}5}{212{,}5}\cdot 100 = \boxed{5{,}88\ \%\ \text{m/m}}$$

### b) Masa de azúcar cada 100 g de **solvente**

Regla de tres directa sobre el **agua**:

$$\frac{12{,}5\ \text{g azúcar}}{200\ \text{g agua}} = \frac{x}{100\ \text{g agua}} \;\Rightarrow\; x = \boxed{6{,}25\ \text{g / 100 g de agua}}$$

### ⚠️ Lo que hay que entender de este ejercicio

Las **dos respuestas describen la misma solución** y sin embargo dan distinto (5,88 vs 6,25). No hay error: **cambia el denominador**.

| Unidad | Denominador | Valor |
|---|---|---|
| % m/m | **solución** (212,5 g) | 5,88 |
| g/100 g sv | **solvente** (200 g) | 6,25 |

$$\boxed{\%\tfrac{m}{m} \;<\; \tfrac{g\ sto}{100\ g\ sv}\quad \text{SIEMPRE}}\qquad\text{porque } m_{sc} > m_{sv}$$

**Para pasar de una a la otra sin rehacer todo:**

$$\%\tfrac{m}{m} = \frac{g/100\,g\,sv}{100 + g/100\,g\,sv}\cdot 100 = \frac{6{,}25}{106{,}25}\cdot 100 = 5{,}88\ ✓$$

💡 Y **ésta es la unidad de las tablas de solubilidad** (ver ejercicio 20a): siempre por **100 g de solvente**.

---

## Ejercicio 4 — % m/m + densidad → masa

> Etanol en agua, **10 % m/m**, δ = 0,983 g/cm³. ¿Cuántos g de etanol hay en **7,5 dm³**?

### El razonamiento

Me dan **volumen** y me piden **masa de soluto**. El % m/m está en masas → **hay que cruzar V → m, y ese puente es la densidad**.

```
V_sc = 7,5 dm³  ──× δ──►  m_sc  ──× 10 %──►  m_etanol
```

| Paso | Cuenta | Resultado |
|---|---|---|
| **1.** Unidades | 7,5 dm³ = 7,5 L = **7500 cm³** | 7500 cm³ |
| **2.** Masa de solución | $m_{sc} = V\cdot\delta = 7500 \times 0{,}983$ | **7372,5 g** |
| **3.** Masa de soluto | $m_{sto} = 7372{,}5 \times 0{,}10$ | $\boxed{737{,}3\ \text{g de etanol}}$ |

### Todo junto

$$m_{sto} = V_{sc}\cdot\delta_{sc}\cdot\frac{\%m/m}{100} = 7500 \times 0{,}983 \times 0{,}10 = \mathbf{737{,}3\ g}$$

⚠️ **El error clásico:** hacer $7500 \times 0{,}10 = 750$ g. Eso es tomar 1 cm³ = 1 g, o sea suponer δ = 1. La solución **no es agua**: pesa 0,983 g por cm³ porque el etanol es más liviano. **Si el problema te da la densidad, es porque hay que usarla.**

💡 **Chequeo de coherencia:** δ = 0,983 < 1 → la solución pesa **menos** que el agua → el resultado tiene que dar **menos** que 750 g. Y 737,3 < 750 ✓

**De yapa, la molaridad** (no la piden, pero sale en dos pasos): $n = 737{,}3/46{,}07 = 16{,}0$ mol en 7,5 L → **2,13 M**.

---

## Ejercicio 5 — Densidad y molaridad · efecto de evaporar

> 200 cm³ de solución de **FeCl₃ al 25 % m/m**, con **61,7 g** de sal.

| Dato | Valor |
|---|---|
| V_sc | 200 cm³ |
| m_sto (FeCl₃) | 61,7 g |
| % m/m | 25 % |
| Mr FeCl₃ | 55,85 + 3(35,45) = **162,20 g/mol** |

### a) Densidad y molaridad

**Densidad.** El 25 % m/m me da la masa de **solución** a partir de la de soluto:

$$m_{sc} = \frac{m_{sto}}{\%m/m}\cdot 100 = \frac{61{,}7}{25}\cdot 100 = 246{,}8\ \text{g}$$

$$\delta = \frac{m_{sc}}{V_{sc}} = \frac{246{,}8\ \text{g}}{200\ \text{cm}^3} = \boxed{1{,}234\ \text{g/cm}^3}$$

**Molaridad.**

$$n = \frac{61{,}7}{162{,}20} = 0{,}3804\ \text{mol} \qquad M = \frac{0{,}3804\ \text{mol}}{0{,}200\ \text{L}} = \boxed{1{,}90\ \text{M}}$$

⚠️ **200 cm³ = 0,200 L.** La molaridad va en **litros**, siempre. Si dividís por 200 te da 1,9×10⁻³ y el resultado queda mil veces chico.

### b) Se evapora hasta V = 125 cm³

**La pregunta clave: ¿qué se conserva al evaporar?**

| Magnitud | ¿Cambia? | Por qué |
|---|---|---|
| **moles de soluto** | ❌ **NO** | La sal no se evapora: se va **sólo el agua** |
| masa de solución | ✓ baja | Se fue solvente |
| volumen | ✓ baja | 200 → 125 cm³ |
| **molaridad** | ✓ **SUBE** | Mismos moles, menos volumen |

$$M_2 = \frac{n_{sto}}{V_2} = \frac{0{,}3804}{0{,}125} = \boxed{3{,}04\ \text{M}}$$

### El atajo (concentrar es una dilución al revés)

$$M_1 V_1 = M_2 V_2 \;\Rightarrow\; M_2 = M_1\cdot\frac{V_1}{V_2} = 1{,}90 \times \frac{200}{125} = 1{,}90 \times 1{,}6 = \mathbf{3{,}04\ M}\ ✓$$

⚠️ **$C_0V_0 = C_FV_F$ NO es sólo para diluir.** Vale siempre que los **moles de soluto se conserven**: diluir (V sube, C baja) o **concentrar por evaporación** (V baja, C sube). Es la misma ecuación.

💡 **Chequeo:** el volumen se redujo a 125/200 = 0,625 de lo que era → la concentración tiene que **subir** en la proporción inversa (1,6). Y 1,90 × 1,6 = 3,04 ✓

---

## Ejercicio 7 — De la masa de sal a todas las unidades

> Solución **10 % m/m** de NaCl, **δ = 1,05 g/cm³**, partiendo de **42 g** de sal.

*(⚠️ La guía saltea el 6 — no falta nada.)*

### El orden en que salen las cosas

```
42 g NaCl ──10 %──► m_sc = 420 g ──− 42──► m_sv = 378 g      (a)
                        │
                        └──÷ δ──► V_sc = 400 mL               (b)
                                     │
                                     └──► % m/V  y  M         (c)
```

### a) Masa de solvente

$$m_{sc} = \frac{42}{0{,}10} = 420\ \text{g} \qquad\Rightarrow\qquad m_{sv} = m_{sc} - m_{sto} = 420 - 42 = \boxed{378\ \text{g de H}_2\text{O}}$$

💡 **Interpretación del 10 % m/m:** de cada 100 g de solución, 10 g son sal y **90 g son agua**. Entonces por cada gramo de sal van **9 g de agua**: 42 × 9 = 378 ✓ (la cuenta mental).

### b) Volumen final

$$V_{sc} = \frac{m_{sc}}{\delta} = \frac{420\ \text{g}}{1{,}05\ \text{g/cm}^3} = \boxed{400\ \text{cm}^3 = 400\ \text{mL}}$$

⚠️ Fijate que **378 g de agua ocupan 378 mL, pero la solución final ocupa 400 mL** — no 378. Los volúmenes **no son aditivos** y además el soluto ocupa lugar. Por eso en el laboratorio se **enrasa al final**, después de disolver.

### c) % m/V y molaridad

$$\%\tfrac{m}{V} = \frac{42\ \text{g}}{400\ \text{cm}^3}\cdot 100 = \boxed{10{,}5\ \%\ \text{m/V}}$$

$$n = \frac{42}{58{,}44} = 0{,}7187\ \text{mol} \qquad M = \frac{0{,}7187}{0{,}400\ \text{L}} = \boxed{1{,}80\ \text{M}}$$

### ⭐ Las dos relaciones que conviene saber de memoria

$$\boxed{\%\tfrac{m}{V} = \%\tfrac{m}{m}\cdot\delta_{sc}\left(\tfrac{g}{mL}\right)} \qquad 10 \times 1{,}05 = 10{,}5\ ✓$$

$$\boxed{M = \frac{\%\tfrac{m}{m}\cdot\delta_{sc}\cdot 10}{Mr}} \qquad \frac{10\times 1{,}05\times 10}{58{,}44} = 1{,}80\ ✓$$

⚠️ **Corolario que se pregunta:** si **δ > 1** entonces **% m/V > % m/m**; si **δ < 1** (alcoholes) es al revés; y si **δ = 1** son **iguales**. Por eso en soluciones acuosas muy diluidas los dos números casi coinciden.

---

## Ejercicio 8 — Una solución, cinco unidades

> **250 cm³** de H₂SO₄ **0,526 M**, δ_sn = **1,0317 g/cm³**.

### a) Masa de soluto

$$n = M\cdot V(L) = 0{,}526 \times 0{,}250 = 0{,}1315\ \text{mol}$$
$$m = n\cdot Mr = 0{,}1315 \times 98{,}08 = \boxed{12{,}90\ \text{g de H}_2\text{SO}_4}$$

### b) Las cuatro unidades restantes

**Lo primero, SIEMPRE: armar la tabla de masas de la solución.** Con eso las cuatro salen solas.

| Magnitud | Cuenta | Valor |
|---|---|---|
| $V_{sc}$ | dato | 250 cm³ |
| $m_{sc}$ | $250 \times 1{,}0317$ | **257,93 g** |
| $m_{sto}$ | parte (a) | **12,90 g** |
| $m_{sv}$ (agua) | $257{,}93 - 12{,}90$ | **245,03 g** |
| $n_{sto}$ | parte (a) | 0,1315 mol |
| $n_{sv}$ | $245{,}03 / 18{,}02$ | **13,60 mol** |

**i) % m/m** — sobre la **solución**:
$$\frac{12{,}90}{257{,}93}\cdot 100 = \boxed{5{,}00\ \%\ \text{m/m}}$$

**ii) g de H₂SO₄ / 100 g de agua** — sobre el **solvente**:
$$\frac{12{,}90}{245{,}03}\cdot 100 = \boxed{5{,}26\ \text{g / 100 g H}_2\text{O}}$$

**iii) g de H₂SO₄ / dm³ de solución** — es el **% m/V × 10**:
$$\frac{12{,}90\ \text{g}}{0{,}250\ \text{L}} = \boxed{51{,}6\ \text{g/L}}$$

💡 Atajo: $g/L = M\cdot Mr = 0{,}526 \times 98{,}08 = 51{,}6$ ✓

**iv) Fracción molar del ácido:**
$$x_{H_2SO_4} = \frac{n_{sto}}{n_{sto}+n_{sv}} = \frac{0{,}1315}{0{,}1315 + 13{,}60} = \frac{0{,}1315}{13{,}73} = \boxed{9{,}58\times 10^{-3}}$$

> 🔴 **Errata menor de la guía:** figura **9,46×10⁻³**. Rehaciendo con Mr(H₂SO₄) = 98,08 y Mr(H₂O) = 18,02 da **9,58×10⁻³**. La diferencia (1,2 %) viene del redondeo de la masa de agua. **El método es lo que importa**: si en el parcial te da 9,5–9,6×10⁻³, está bien.

### ⚠️ Los dos errores mortales de la fracción molar

| ❌ Error | ✅ Correcto |
|---|---|
| Usar la **masa** de agua en el denominador | Hay que pasarla a **MOLES**: ÷ 18,02 |
| Poner en el denominador sólo $n_{sv}$ | Van **los dos**: $n_{sto} + n_{sv}$ |

💡 **Chequeo de magnitud:** en una solución acuosa diluida, x_soluto es **chiquísimo** (10⁻² a 10⁻⁴), porque **1 L de agua son ~55 mol** y el soluto casi nunca pasa de 1 mol. Si te da 0,3 o 0,5, revisá: seguro pusiste masas en lugar de moles.

**Verificación:** $x_{sv} = 13{,}60/13{,}73 = 0{,}990$ y $0{,}00958 + 0{,}990 = 1{,}00$ ✓

---

## Ejercicio 9 — Dilución 1:25 (jugo)

> Jugo concentrado: **125 g de sacarosa cada 100 mL de solución**. Se preparan **5 L** de jugo bebible con dilución **1:25**.

### Qué significa "1:25"

> **1:n → 1 volumen de solución concentrada llevado a *n* volúmenes TOTALES.**

$$\boxed{C_{final} = \frac{C_{inicial}}{n}} \qquad\qquad \boxed{V_{concentrado} = \frac{V_{final}}{n}}$$

⚠️ **1:25 NO es "1 parte de jugo + 25 de agua"** (eso sería 1:26). Es **1 parte de jugo completada hasta 25 partes** → 1 de jugo + 24 de agua.

### a) Concentración en el jugo bebible

Concentración del concentrado, en % m/V:

$$\%\tfrac{m}{V}_{conc} = \frac{125\ \text{g}}{100\ \text{mL}}\cdot 100 = 125\ \%\ \text{m/V}$$

Diluyo 1:25 → divido por 25:

$$\%\tfrac{m}{V}_{bebible} = \frac{125}{25} = \boxed{5\ \%\ \text{m/V}}$$

Y la molaridad (5 g cada 100 mL = **50 g/L**):

$$M = \frac{50\ \text{g/L}}{342{,}30\ \text{g/mol}} = \boxed{0{,}15\ \text{M}}$$

💡 Fijate que **5 % m/V es justo la concentración del suero glucosado**. Un jugo comercial tiene, en azúcar, lo mismo que un suero.

### b) Volumen de concentrado

$$V_{conc} = \frac{V_{final}}{25} = \frac{5\ \text{L}}{25} = \boxed{0{,}2\ \text{L} = 200\ \text{mL}}$$

**Verificación con $C_0V_0 = C_FV_F$:**
$$125\ \% \times 0{,}2\ \text{L} = 25 \qquad 5\ \% \times 5\ \text{L} = 25\ ✓$$

**Cómo se hace:** poner **200 mL** de concentrado en un recipiente de 5 L y **completar con agua hasta 5 L** — no "agregarle 5 L de agua" (eso daría 5,2 L).

### ⚠️ Diluciones en serie

$$\boxed{\text{factor total} = n_1 \times n_2 \times \dots}$$

Dos diluciones **1:10** seguidas dan **1:100**, no 1:20. Es la base de las curvas de calibración y de todo el trabajo con patrones.

---

## Ejercicio 10 — Preparar por dilución desde una solución madre

> Preparar **1,00 L** de HCl **6,00 % m/m** (δ = 1,0278 g/cm³) a partir de HCl **2,87 M**.

### El problema en una línea

Las dos concentraciones están en **unidades distintas** (% m/m y M). **Hay que llevarlas a una misma moneda: los MOLES.**

| Paso | Cuenta | Resultado |
|---|---|---|
| **1.** Masa de la solución que quiero | $1000\ \text{cm}^3 \times 1{,}0278$ | 1027,8 g |
| **2.** Masa de HCl que necesito | $1027{,}8 \times 0{,}0600$ | **61,67 g** |
| **3.** Moles que necesito | $61{,}67 / 36{,}46$ | **1,691 mol** |
| **4.** Volumen de la madre que los contiene | $1{,}691 / 2{,}87$ | $\boxed{0{,}589\ \text{L} = 589\ \text{mL}}$ |

> 📝 **Respuesta tipo parcial**
> 1. Calcular la masa de HCl necesaria: $m = V_{sc}\cdot\delta_{sc}\cdot\%m/m = 1000 \times 1{,}0278 \times 0{,}06 = 61{,}67$ g, que son $n = 61{,}67/36{,}46 = 1{,}691$ mol.
> 2. El volumen de solución madre que aporta esos moles es $V_0 = n/M_0 = 1{,}691/2{,}87 = 0{,}589$ L.
> 3. **Medir 589 mL** de la solución 2,87 M con probeta/pipeta y volcarlos en un **matraz aforado de 1,00 L** que ya tenga un poco de agua destilada.
> 4. **Completar con agua destilada hasta el aforo** y **homogeneizar** invirtiendo el matraz varias veces.
> ⚠️ **Nunca** agregar 1 L de agua a los 589 mL: el volumen final sería ~1,589 L y la concentración quedaría mal. Se **enrasa** hasta 1 L.
> ⚠️ **Seguridad con ácidos:** el ácido **sobre** el agua, nunca al revés (la dilución de ácidos es muy exotérmica y puede proyectar salpicaduras).

### La molaridad final, de control

$$M_F = \frac{1{,}691\ \text{mol}}{1{,}00\ \text{L}} = 1{,}69\ \text{M} \qquad\Rightarrow\qquad V_0 = \frac{M_F V_F}{M_0} = \frac{1{,}69\times 1{,}00}{2{,}87} = 0{,}589\ \text{L}\ ✓$$

💡 Se puede resolver **todo** con $C_0V_0=C_FV_F$, siempre que primero conviertas el 6,00 % m/m a **1,69 M**. Ése es el único trabajo real del ejercicio.

---

## Ejercicio 11 — Mezcla de dos soluciones del MISMO soluto

> 100 cm³ de HNO₃ **0,25 M** + 500 cm³ de HNO₃ **1,25 M**. Volúmenes aditivos.

### El método (vale para toda mezcla del mismo soluto)

```
1. moles de cada una:   n = M · V(L)
2. SUMAR los moles      (los moles SÍ son aditivos)
3. SUMAR los volúmenes  (sólo si el problema dice "aditivos")
4. M_final = n_total / V_total
```

| Solución | V (L) | M | n = M·V |
|---|---|---|---|
| A | 0,100 | 0,25 | 0,0250 mol |
| B | 0,500 | 1,25 | 0,6250 mol |
| **Mezcla** | **0,600** | **?** | **0,6500 mol** |

$$M_F = \frac{0{,}6500\ \text{mol}}{0{,}600\ \text{L}} = \boxed{1{,}08\ \text{M}}$$

### ⭐ La fórmula general (memorizala, sale en el parcial)

$$\boxed{M_F = \frac{M_1V_1 + M_2V_2}{V_1+V_2}}$$

Es un **promedio pesado por el volumen**. Como B aporta 5 veces más volumen que A, el resultado queda **mucho más cerca de 1,25 que de 0,25**.

### ⚠️ Los dos errores clásicos

| ❌ Error | Por qué está mal |
|---|---|
| Promediar las molaridades: $(0{,}25+1{,}25)/2 = 0{,}75$ | Ignora que hay **5 veces más** de la solución concentrada |
| Sumar las molaridades: $0{,}25+1{,}25 = 1{,}50$ | Las concentraciones son **intensivas**: **NO se suman** |

💡 **Chequeo obligatorio:** el resultado **tiene que quedar entre las dos concentraciones de partida**. $0{,}25 < 1{,}08 < 1{,}25$ ✓ Si te da afuera de ese rango, la cuenta está mal, sin excepción.

⚠️ **Esto vale porque es el MISMO soluto.** Si mezclás soluciones de solutos **distintos**, cada uno se diluye por su cuenta y hay que calcular **una concentración para cada uno** — ver ejercicio 13 de "fuera de clase".

---

## Ejercicio 12 — ppm de metales pesados en agua potable

> Límites del **CAA**: As 0,01 ppm · Cd 0,005 ppm · Pb 0,05 ppm · Hg 0,001 ppm.

### i) ppm → % m/m

Las dos son fracciones de masa sobre **solución**: sólo cambia el factor.

$$\text{ppm} = \frac{m_{sto}}{m_{sc}}\cdot 10^6 \qquad \%\tfrac{m}{m} = \frac{m_{sto}}{m_{sc}}\cdot 10^2 \qquad\Rightarrow\qquad \boxed{\%\tfrac{m}{m} = \frac{\text{ppm}}{10^4}}$$

| Elemento | Límite (ppm) | % m/m |
|---|---|---|
| **As** (arsénico) | 0,01 | **1×10⁻⁶ %** |
| **Cd** (cadmio) | 0,005 | **5×10⁻⁷ %** |
| **Pb** (plomo) | 0,05 | **5×10⁻⁶ %** |
| **Hg** (mercurio) | 0,001 | **1×10⁻⁷ %** |

### ii) ppm → molaridad · **la aproximación**

**Ésta es la pregunta central del ejercicio.** ppm es una relación **masa/masa**; molaridad es **mol/volumen**. Para cruzar de una a la otra **hace falta la densidad de la solución**… y el enunciado **no la da**.

$$\boxed{\text{APROXIMACIÓN: } \delta_{sc} \approx \delta_{H_2O} = 1{,}00\ \text{g/mL}}$$

Con eso **1 kg de solución ocupa 1 L** y entonces:

$$1\ \text{ppm} = \frac{1\ \text{g}}{10^6\ \text{g sc}} = \frac{1\ \text{g}}{10^6\ \text{mL}} = \frac{1\ \text{mg}}{1\ \text{L}} \qquad\Rightarrow\qquad \boxed{\text{ppm} \equiv \tfrac{\text{mg}}{\text{L}}}$$

$$M = \frac{\text{ppm}\times 10^{-3}\ \text{g/L}}{Ar}$$

| Elemento | mg/L | Ar (g/mol) | M |
|---|---|---|---|
| **As** | 0,01 | 74,92 | **1,3×10⁻⁷ M** |
| **Cd** | 0,005 | 112,41 | **4,4×10⁻⁸ M** |
| **Pb** | 0,05 | 207,2 | **2,4×10⁻⁷ M** |
| **Hg** | 0,001 | 200,59 | **5,0×10⁻⁹ M** |

### 🔴 Errata de la guía (ésta es grosa)

Las respuestas impresas **no corresponden a los límites del enunciado**: corresponden a **otros valores** (As 0,05 · Cd 0,01 · Pb 0,05 · Hg 0,002 ppm). Probablemente actualizaron el enunciado y no rehicieron las respuestas.

| Elemento | Respuesta de la guía | Sale con… | El enunciado dice |
|---|---|---|---|
| As | 5×10⁻⁶ % ; 6,7×10⁻⁷ M | 0,05 ppm | **0,01 ppm** → 1×10⁻⁶ % ; 1,3×10⁻⁷ M |
| Cd | 1×10⁻⁶ % ; 8,9×10⁻⁸ M | 0,01 ppm | **0,005 ppm** → 5×10⁻⁷ % ; 4,4×10⁻⁸ M |
| Pb | 5×10⁻⁶ % ; 2,4×10⁻⁷ M | 0,05 ppm | **0,05 ppm** ✓ **coincide** |
| Hg | 2×10⁻⁷ % ; 1×10⁻⁸ M | 0,002 ppm | **0,001 ppm** → 1×10⁻⁷ % ; 5,0×10⁻⁹ M |

**Lo que se evalúa es el método y la justificación de la aproximación**, no estos cuatro números. Hacelo con los datos del enunciado.

> 📝 **Respuesta tipo parcial (la justificación)**
> Para pasar de ppm (relación **masa/masa**) a molaridad (relación **mol/volumen**) hace falta la **densidad de la solución**, que no está dada. Se aproxima **δ_sc ≈ 1,00 g/mL**, la del agua pura.
> **Justificación:** las concentraciones son del orden de **10⁻⁶ %**, es decir, el soluto representa **menos de una millonésima** de la masa total. La solución es, a todos los efectos, **agua pura**: su densidad difiere de 1,00 g/mL mucho menos que el error de cualquier medición. Con esa aproximación 1 kg de solución = 1 L, y por lo tanto **1 ppm = 1 mg/L**.
> ⚠️ **Esta aproximación NO vale** para soluciones concentradas: un HCl 37 % tiene δ = 1,19 g/mL, y usar 1,00 daría un error del 19 %.

💡 **Para dimensionar cuánto es 1 ppm:** 1 mm en 1 km · 1 segundo cada 11,5 días · una gota en una bañera llena. Que un límite legal esté en 0,001 ppm (**1 ppb**) da idea de lo tóxico que es el mercurio.

---

## Ejercicio 13 — Aguas minerales y el sodio (comparar etiquetas)

> Máximo **1700 mg de Na/día**; con los alimentos ya consume **1500 mg**. Bebe **2 L de agua/día**.

### Paso 1 — El presupuesto disponible

$$m_{Na}^{disponible} = 1700 - 1500 = \mathbf{200\ mg\ de\ Na/día}$$

En **2 L** de agua eso fija un límite de concentración:

$$\boxed{C_{max} = \frac{200\ \text{mg}}{2\ \text{L}} = 100\ \tfrac{\text{mg Na}}{\text{L}}}$$

### Paso 2 — Llevar TODAS las etiquetas a mg de **Na⁺** por litro

⚠️ **Acá está toda la dificultad:** cada marca informa en una unidad distinta y **dos de ellas informan la SAL, no el sodio**. Hay que extraer el Na con la fracción de masa.

| Marca | Etiqueta | Conversión | **mg Na/L** |
|---|---|---|---|
| **Eco de los Alpes** | 160 mg Na/L | ya está | **160** |
| **Villa del Norte** | 41 mg Na / 250 mL | $41\times 4$ | **164** |
| **SSEVI** | 700 **ppb** de Na | $700/1000$ ppm = 0,7 mg/L | **0,70** |
| **Ser o no Ser** | 20 ppm NaCl + 70 ppm Na₂SO₄ | ver abajo | **30,5** |
| **Villavicente** | 210 mg **NaCl**/L | $210\times\frac{22{,}99}{58{,}44}$ | **82,6** |
| **Sierra de las madres** | 160 ppm Na | 1 ppm = 1 mg/L | **160** |

**La cuenta de "Ser o no Ser"** (dos sales: se **suman** los aportes de Na):

$$\text{de NaCl: } 20\ \tfrac{mg}{L}\times\frac{22{,}99}{58{,}44} = 7{,}87\ \tfrac{mg\ Na}{L}$$
$$\text{de Na}_2\text{SO}_4: 70\ \tfrac{mg}{L}\times\frac{2\times 22{,}99}{142{,}04} = 70\times 0{,}3237 = 22{,}66\ \tfrac{mg\ Na}{L}$$
$$\text{Total} = 7{,}87 + 22{,}66 = \mathbf{30{,}53\ \tfrac{mg\ Na}{L}}$$

⚠️ El Na₂SO₄ tiene **2 Na por unidad fórmula** — si ponés uno solo te da la mitad.

### Paso 3 — Comparar con el límite de 100 mg Na/L

| Marca | mg Na/L | Na en 2 L | ¿Sirve? |
|---|---|---|---|
| Eco de los Alpes | 160 | **320 mg** | ❌ se pasa |
| Villa del Norte | 164 | **328 mg** | ❌ se pasa |
| **SSEVI** | 0,70 | **1,4 mg** | ✓ **SÍ** |
| **Ser o no Ser** | 30,5 | **61 mg** | ✓ **SÍ** |
| **Villavicente** | 82,6 | **165 mg** | ✓ **SÍ** |
| Sierra de las madres | 160 | **320 mg** | ❌ se pasa |

$$\boxed{\text{Puede comprar: SSEVI, Ser o no Ser o Villavicente}}$$

### ⚠️ Las tres trampas

| Trampa | Detalle |
|---|---|
| **ppb ≠ ppm** | 700 ppb = **0,7** ppm, no 700. Factor **1000**. Es la marca más "segura" por lejos |
| **NaCl ≠ Na** | 210 mg de **NaCl** son sólo **82,6 mg de Na** (el 39,3 %). Si tomás 210 como si fuera Na, descartás Villavicente por error |
| **Villa del Norte no viene por litro** | Informa cada **250 mL**: hay que multiplicar por **4**, no usar 41 tal cual |

💡 **Villavicente es la de "casi": 165 de los 200 mg disponibles.** Entra, pero sin margen.

---

## Ejercicio 14 — Solubilidad · escalar y saturar

> Solubilidad del **AgNO₃** a 18 °C: **211,6 g en 100 mL de agua**.

### a) Máximo disoluble en 400 mL de agua

La solubilidad es una **propiedad intensiva**: es una **proporción**. Escalarla es una regla de tres.

$$\frac{211{,}6\ \text{g}}{100\ \text{mL}} = \frac{x}{400\ \text{mL}} \qquad\Rightarrow\qquad x = 211{,}6\times 4 = \boxed{846{,}4\ \text{g}}$$

### b) Cuánto agregar a 1 L de agua para saturarla

$$1\ \text{L} = 1000\ \text{mL} \qquad x = 211{,}6\times 10 = \boxed{2116\ \text{g} = 2{,}116\ \text{kg}}$$

### ⚠️ Lo que hay que fijar

| Punto | Detalle |
|---|---|
| La solubilidad va sobre el **SOLVENTE** | "100 mL **de agua**", no de solución. Los 846,4 g van **en** 400 mL de agua, y la solución final ocupa **bastante más** que 400 mL |
| **Sin temperatura no significa nada** | El mismo AgNO₃ a 100 °C tiene S ≈ 950 g/100 g. Un valor de solubilidad **siempre** viene con su T |
| El AgNO₃ es **rarísimamente soluble** | 211,6 g en 100 mL: la solución saturada es **más de dos tercios de sal en masa** |
| Si el enunciado da mL de agua | Podés usar **1 mL ≈ 1 g**. Si diera δ (ej. 0,99868 a 18 °C): $400\times 0{,}99868 = 399{,}5$ g → 845,3 g. La diferencia es del 0,1 % |

### 🔑 El método de "¿se disuelve todo?" (para el 15 y todos los de curvas)

```
1. Pasar el SOLVENTE a gramos          (con δ, si viene en volumen)
2. Escalar la solubilidad:   máx = S × (m_solvente / 100)
3. Comparar con lo que quiero disolver:
      cantidad ≤ máx  →  se disuelve TODO      → INSATURADA (o saturada justa)
      cantidad >  máx →  se disuelven "máx"    → SATURADA + precipitado
                         precipitado = cantidad − máx   ⚠️ ¡NO te olvides de restar!
```

---

## Ejercicio 15 — Cuánto queda sin disolver

> S(KNO₃, 30 °C) = **40 g en 100 g de agua**. Agregamos **170 g** de KNO₃ a **300 mL** de agua.

| Paso | Cuenta | Resultado |
|---|---|---|
| **1.** Solvente a gramos | 300 mL × 1,00 g/mL | **300 g de agua** |
| **2.** Máximo disoluble | $40 \times \dfrac{300}{100} = 40\times 3$ | **120 g** |
| **3.** Comparar | 170 g **>** 120 g | **satura y sobra** |
| **4.** Precipitado | $170 - 120$ | $\boxed{50\ \text{g sin disolver}}$ |

### Cómo queda el vaso

```
        ┌─────────────┐
        │             │
        │  SOLUCIÓN   │  ← 120 g de KNO₃ disueltos en 300 g de agua
        │  SATURADA   │     (SATURADA: c = S, equilibrio dinámico)
        │             │
        │▒▒▒▒▒▒▒▒▒▒▒▒▒│  ← 50 g de KNO₃ sólido en el fondo
        └─────────────┘        (cuerpo de fondo)
```

⚠️ El sistema es **HETEROGÉNEO: 2 fases** (líquida + sólida), 2 componentes.
⚠️ La solución de arriba es **SATURADA**, **no sobresaturada**. El exceso **precipita**: por definición, en equilibrio no puede quedar más de S disuelto.
⚠️ **Agitar no ayuda.** Agitar aumenta la **velocidad** con que se llega al equilibrio, no el **máximo**. Por eso el enunciado dice "agitando": para que sepas que ya se alcanzó el equilibrio y los 50 g son realmente el sobrante.

### El equilibrio dinámico que hay detrás

$$\text{KNO}_3(s) \xrightleftharpoons[\text{cristalización}]{\text{disolución}} \text{K}^+_{(ac)} + \text{NO}_3^-{}_{(ac)}$$

Los 50 g del fondo **no están quietos**: se disuelven y recristalizan **a la misma velocidad**. El neto es cero, por eso la masa del fondo no cambia.

💡 **Cómo disolver los 50 g restantes:** **calentar**. A 45 °C el KNO₃ tiene S ≈ 70 g/100 g → máximo = 210 g > 170 → se disuelve todo. Y si después enfriás **despacio** hasta 30 °C podés obtener una solución **sobresaturada** (metaestable): 170 g disueltos donde el equilibrio sólo admite 120.

---

## Ejercicio 16 — Lectura de curvas de solubilidad

### El gráfico, transcripto a tabla

Diez curvas de **solubilidad (g/100 g de agua) vs temperatura (°C)**. Valores aproximados leídos del gráfico:

| Sustancia | 0 °C | 20 °C | 40 °C | 60 °C | 80 °C | 100 °C | Forma |
|---|---|---|---|---|---|---|---|
| **NH₄NO₃** | ~118 | ~150 | *(fuera de escala)* | | | | ⬆ **empinadísima** |
| **Glucosa** | ~35 | ~65 | ~145 | | | | ⬆ empinadísima |
| **CH₃CO₂Na** | ~36 | ~46 | ~65 | ~139 | | | ⬆ salto brusco ~58 °C |
| **NaNO₃** | ~72 | ~88 | ~104 | ~124 | ~148 | ~180 | ⬆ fuerte |
| **LiCl** | ~70 | ~84 | ~92 | ~100 | ~114 | ~128 | ⬆ suave |
| **KBr** | ~53 | ~65 | ~76 | ~85 | ~95 | ~104 | ⬆ moderada |
| **NH₄Cl** | ~29 | ~37 | ~46 | ~55 | ~66 | ~77 | ⬆ moderada |
| **CuSO₄** | ~14 | **~20** | ~29 | **~40** | ~55 | ~75 | ⬆ moderada |
| **NaCl** | 35,7 | 36,0 | 36,6 | 37,3 | 38,4 | **39,8** | ➡ **casi plana** |
| **Ce₂(SO₄)₃** | ~20 | ~10 | ~3 | ~2 | ~2 | ~2 | ⬇ **BAJA** ⚠️ |

⚠️ **El criterio de "sensible a T" es la PENDIENTE, no la altura.** Una sustancia puede ser muy soluble y nada sensible (el NaNO₃ está altísimo pero el NH₄NO₃ sube más rápido), o poco soluble y muy sensible.

### a) La MENOS sensible a la temperatura

$$\boxed{\text{NaCl (cloruro de sodio)}}$$

Su curva es **prácticamente horizontal**: de 35,7 a 39,8 g/100 g entre 0 y 100 °C. Son **4 g en 100 grados** — un aumento del 11 % en todo el rango.

💡 **Por eso se cocina con sal y no se nota diferencia entre agua fría y caliente**, y por eso las salinas funcionan **evaporando** agua, no enfriándola: enfriar el agua de mar casi no precipita NaCl.
💡 Es también la razón por la que el NaCl es el patrón de "sal común": su solubilidad es **robusta** frente a la temperatura ambiente.

### b) La MÁS sensible a la temperatura

$$\boxed{\text{NH}_4\text{NO}_3\ \text{(nitrato de amonio)}}$$

Es la curva de mayor **pendiente**: ya arranca en ~118 g/100 g a 0 °C y se va **fuera de escala antes de los 20 °C**. La **glucosa** le pisa los talones (de ~35 a ~145 g entre 0 y 40 °C).

⚠️ **Si en el parcial te dan otro gráfico**, el criterio es siempre el mismo: **la que sube más empinada**, no la que está más arriba.

⚠️ **Caso aparte, y es el que más se pregunta:** el **Ce₂(SO₄)₃** es la **única cuya solubilidad BAJA** con la temperatura (de ~20 a ~2 g/100 g). Es la **excepción** del gráfico. Casi todos los sólidos iónicos tienen disolución **endotérmica** (S sube con T); el sulfato de cerio la tiene **exotérmica**, y se comporta como un **gas**.

### c) Solubilidad del CuSO₄

$$S(20\ °\text{C}) \approx \boxed{20\ \text{g/100 g de agua}} \qquad S(60\ °\text{C}) \approx \boxed{40\ \text{g/100 g de agua}}$$

💡 Se **duplica** en 40 grados.

### d) 40 g de CuSO₄ en 100 g de agua a 70 °C, y después enfriando a 20 °C

**A 70 °C:** interpolando entre 60 (40 g) y 80 (55 g), $S(70) \approx 47$ g/100 g.

$$40\ \text{g} \;<\; 47\ \text{g} \qquad\Rightarrow\qquad \boxed{\text{se disuelve TODO} \;\rightarrow\; \text{solución INSATURADA}}$$

Queda margen para ~7 g más. El sistema es **homogéneo, 1 fase**.

**Al enfriar a 20 °C:** ahora $S(20) = 20$ g/100 g, pero hay **40 g** disueltos.

$$m_{precipitado} = 40 - 20 = \boxed{20\ \text{g de CuSO}_4\ \text{cristalizan}}$$

Y arriba queda una solución **SATURADA** con 20 g disueltos. El sistema pasa a ser **heterogéneo, 2 fases**.

```
      70 °C                              20 °C
   ┌─────────┐                       ┌─────────┐
   │ 40 g    │   ── enfriar ──►      │ 20 g    │  ← SATURADA
   │ disuelt.│                       │ disuelt.│
   │INSATURADA                       │▒▒▒▒▒▒▒▒▒│  ← 20 g de cristales
   └─────────┘                       └─────────┘     azules de CuSO₄
```

⚠️ **Si enfriás MUY despacio y sin perturbar**, podés obtener una solución **SOBRESATURADA** (los 40 g siguen disueltos a 20 °C, donde el equilibrio sólo admite 20). Es **metaestable**: alcanza un golpecito o un cristalito de siembra para que precipite **todo el exceso de golpe**. Ése es el principio de las **bolsitas de calor** de acetato de sodio y de la **miel que cristaliza**.

💡 **Esto es exactamente la RECRISTALIZACIÓN**, la técnica de purificación más usada del laboratorio: disolver en caliente hasta saturar, enfriar despacio, y los cristales que caen son del compuesto puro (las impurezas, mucho más diluidas, se quedan en solución).

### e) CuSO₄ que se disuelve en 278 g de agua a 60 °C

Escalar la solubilidad al solvente que hay:

$$m_{max} = S \times \frac{m_{sv}}{100} = 40 \times \frac{278}{100} = 40\times 2{,}78 = \boxed{111{,}2\ \text{g de CuSO}_4}$$

⚠️ **Las curvas están SIEMPRE por 100 g de solvente.** Si el enunciado da otra cantidad, **hay que escalar**. Éste es el paso que más se olvida.

> 📝 **Respuesta tipo parcial (a y b)**
> La sensibilidad a la temperatura se mide por la **pendiente** de la curva, no por su altura. La **menos** sensible es el **NaCl**, cuya curva es casi horizontal (35,7 → 39,8 g/100 g entre 0 y 100 °C). La **más** sensible es el **NH₄NO₃**, la de mayor pendiente, que se sale de la escala antes de los 20 °C. Caso especial: el **Ce₂(SO₄)₃** es el único cuya solubilidad **disminuye** al aumentar T, porque su disolución es **exotérmica** — se comporta como un gas.

---

## Ejercicio 17 — Mezcla, iones en solución y preparación

> Botella A: **230 mL** de Fe(NO₃)₃ **0,138 M**. Botella B: **261 mL** de Fe(NO₃)₃ **0,205 M**.
> Se mezclan en C. δ de todas las soluciones = **1,16 g/cm³**.
> Mr Fe(NO₃)₃ = 55,85 + 3(14,01 + 48,00) = **241,88 g/mol**

### a) Concentración en la botella C

**Molaridad** — mismo soluto, así que se suman moles y volúmenes:

| Botella | V (L) | M | n = M·V |
|---|---|---|---|
| A | 0,230 | 0,138 | **0,03174 mol** |
| B | 0,261 | 0,205 | **0,05351 mol** |
| **C** | **0,491** | ? | **0,08525 mol** |

$$M_C = \frac{0{,}08525\ \text{mol}}{0{,}491\ \text{L}} = \boxed{0{,}174\ \text{M}}$$

💡 **Chequeo:** $0{,}138 < 0{,}174 < 0{,}205$ ✓ (queda en el medio, un poco corrido hacia B porque B aporta más volumen).

**% m/m** — acá entra la **densidad**, que es para lo que la dieron:

| Paso | Cuenta | Resultado |
|---|---|---|
| Masa de soluto | $0{,}08525 \times 241{,}88$ | **20,62 g** |
| Masa de solución | $491\ \text{cm}^3 \times 1{,}16$ | **569,6 g** |
| % m/m | $\dfrac{20{,}62}{569{,}6}\cdot 100$ | $\boxed{3{,}62\ \%\ \text{m/m}}$ |

*(la guía dice 3,63 %: diferencia de redondeo en la Mr, es lo mismo)*

### b) Concentración de los IONES

**Ésta es la parte conceptual.** El Fe(NO₃)₃ es una **sal iónica**: en agua se **disocia por completo**.

$$\text{Fe(NO}_3)_3 \xrightarrow{\ \text{H}_2\text{O}\ } \text{Fe}^{3+}_{(ac)} + \mathbf{3}\ \text{NO}_3^-{}_{(ac)}$$

**La estequiometría de la disociación es la que manda:**

| Ion | Relación | Concentración |
|---|---|---|
| **Fe³⁺** | 1 por unidad fórmula | $1\times 0{,}174 = \boxed{0{,}174\ \text{M}}$ |
| **NO₃⁻** | **3** por unidad fórmula | $3\times 0{,}174 = \boxed{0{,}522\ \text{M}}$ |

⚠️ **El error garantizado:** poner $[\text{NO}_3^-] = 0{,}174$ M. El subíndice **3** de la fórmula **multiplica** la concentración del anión. La fórmula te dice cuántos iones salen por cada unidad que se disuelve.

⚠️ **Y el error contrario:** dividir por 3. No: la sal **libera** 3 nitratos, no los reparte.

**Verificación por electroneutralidad** (siempre tiene que dar):
$$\sum(\text{carga}\times\text{conc.}) = (+3)(0{,}174) + (-1)(0{,}522) = 0{,}522 - 0{,}522 = 0\ ✓$$

**La tablita general que hay que tener:**

| Sal 0,1 M | Cationes | Aniones | Total de iones |
|---|---|---|---|
| NaCl | Na⁺ 0,1 M | Cl⁻ 0,1 M | 0,2 M |
| CaCl₂ | Ca²⁺ 0,1 M | Cl⁻ **0,2 M** | 0,3 M |
| **Fe(NO₃)₃** | Fe³⁺ 0,1 M | NO₃⁻ **0,3 M** | 0,4 M |
| Al₂(SO₄)₃ | Al³⁺ **0,2 M** | SO₄²⁻ **0,3 M** | 0,5 M |

### c) Preparar 0,5 L de solución 0,200 M

$$n = M\cdot V = 0{,}200 \times 0{,}5 = 0{,}100\ \text{mol}$$
$$m = n\cdot Mr = 0{,}100 \times 241{,}88 = \boxed{24{,}19\ \text{g de Fe(NO}_3)_3}$$

> 🔴 **Errata de la guía:** figura **29,19 g**. Es un **error de tipeo** (2**9** por 2**4**). La cuenta es directa: $0{,}5\times 0{,}200\times 241{,}88 = 24{,}19$ g. Para que dieran 29,19 g la Mr tendría que ser 291,9 g/mol, y el Fe(NO₃)₃ anhidro pesa **241,88**.

**La fórmula maestra para preparar desde el sólido:**

$$\boxed{m_{sto} = M \cdot V_{sc}(\text{L}) \cdot Mr}$$

---

## Ejercicio 18 — Preparación en el laboratorio (procedimiento)

> Preparar **1,00 L** de NaOH **1,50 M**. Material: 1 kg de NaOH en granallas, balanza, matraces de 1,00 L, agua destilada, vasos de precipitados, probetas y pipetas.
> Mr NaOH = 22,99 + 16,00 + 1,008 = **40,00 g/mol**

### a) Desde el soluto sólido — **método gravimétrico + volumétrico**

**La cuenta:**

$$m = M\cdot V(\text{L})\cdot Mr = 1{,}50 \times 1{,}00 \times 40{,}00 = \boxed{60{,}0\ \text{g de NaOH}}$$

> 📝 **Respuesta tipo parcial — procedimiento**
> 1. **Calcular:** $m = M\cdot V\cdot Mr = 1{,}50\ \tfrac{mol}{L}\times 1{,}00\ L\times 40{,}00\ \tfrac{g}{mol} = \mathbf{60{,}0\ g}$ de NaOH.
> 2. **Pesar** 60,0 g de granallas en la **balanza**, sobre un **vaso de precipitados** (⚠️ nunca sobre el platillo directamente: el NaOH lo ataca).
> 3. **Disolver** en el vaso con **~300–500 mL de agua destilada**, agitando con varilla, **sin llegar al volumen final**.
> 4. **Dejar enfriar** a temperatura ambiente.
> 5. **Trasvasar cuantitativamente** al **matraz aforado de 1,00 L**: volcar el contenido y **enjuagar el vaso 2–3 veces** con agua destilada, agregando cada enjuague al matraz (así no queda soluto en el vaso).
> 6. **Enrasar** con agua destilada hasta el aforo, mirando el **menisco por su parte inferior y a la altura de los ojos** (para evitar el error de **paralaje**).
> 7. **Tapar y homogeneizar** invirtiendo el matraz varias veces.
>
> ⚠️ **Cuidados específicos del NaOH:**
> - Es **higroscópico y delicuescente**: absorbe humedad del aire. Hay que pesarlo **rápido** y con el frasco bien cerrado; si no, "pesás agua".
> - Su disolución es **fuertemente EXOTÉRMICA**: la solución se calienta mucho. Por eso se disuelve en el **vaso** y se **espera a que enfríe** antes de enrasar. Si enrasás en caliente, al enfriarse el volumen se contrae y la concentración queda **mayor** que la buscada.
> - Es **cáustico**: guantes y antiparras.

⚠️ **Los tres errores de procedimiento que se preguntan:**

| ❌ Error | Por qué está mal |
|---|---|
| Disolver **directamente en el matraz aforado** | Se calienta (el vidrio aforado no está calibrado en caliente) y no se puede agitar bien |
| Agregar el sólido y **enrasar a 1 L, y recién ahí disolver** | Los volúmenes **no son aditivos**: al disolverse el volumen cambia y el aforo queda mal |
| "Disolver 60 g **en** 1 L de agua" | Eso da **más** de 1 L de solución. Hay que llevar **hasta** 1,00 L |

### b) 1,00 L de NaOH 0,100 M por dilución de la anterior

$$C_0V_0 = C_FV_F \;\Rightarrow\; V_0 = \frac{C_FV_F}{C_0} = \frac{0{,}100\ \text{M}\times 1{,}00\ \text{L}}{1{,}50\ \text{M}} = 0{,}0667\ \text{L} = \boxed{66{,}7\ \text{mL}}$$

> 📝 **Respuesta tipo parcial — procedimiento**
> 1. **Medir 66,7 mL** de la solución 1,50 M preparada en (a), con **probeta y pipeta** (por ejemplo, 60 mL con probeta + 6,7 mL con pipeta, o directamente con una probeta de 100 mL si la precisión pedida lo permite).
> 2. Volcarlos en un **matraz aforado de 1,00 L** que ya tenga algo de agua destilada.
> 3. **Enrasar** con agua destilada hasta el aforo.
> 4. **Homogeneizar** por inversión.
>
> ⚠️ El agua a agregar es $1000 - 66{,}7 = 933{,}3$ mL **como referencia**, pero **no se mide el agua**: se enrasa al aforo, porque los volúmenes no son aditivos.

💡 **Chequeo:** el factor de dilución es $1{,}50/0{,}100 = 15$, o sea **1:15**. Y $1000/15 = 66{,}7$ mL ✓

⚠️ **Por qué se prefiere diluir en vez de pesar 4,0 g de NaOH:** pesar 4 g en una balanza común arrastra un error relativo grande, y con el NaOH higroscópico es peor. **Medir un volumen de una solución madre bien preparada es más exacto.** Ése es el sentido de trabajar con soluciones stock.

---

## Ejercicio 19 — Diluir una solución MOLAL

> **600 g** de una solución **2,50 m** de K₂SO₄. ¿Qué masa de agua hay que agregar para que quede **1,50 m**?
> Mr K₂SO₄ = 2(39,10) + 32,06 + 64,00 = **174,26 g/mol**

### ⚠️ Por qué NO se puede usar C₀V₀ = C_F V_F

La molalidad va sobre la **masa de SOLVENTE**, no sobre el volumen de solución. $C_0V_0 = C_FV_F$ **no aplica**. Lo que sí se conserva es:

$$\boxed{\text{los MOLES de soluto no cambian: sólo agrego agua}}$$

### Paso 1 — Descomponer los 600 g en soluto + solvente

Por **definición de molalidad**, 2,50 m significa **2,50 mol de K₂SO₄ por kg de agua**. Armemos la "porción unidad":

| Por cada 1 kg de agua | Cuenta | Masa |
|---|---|---|
| Soluto | $2{,}50\ \text{mol}\times 174{,}26$ | 435,65 g |
| Solvente | — | 1000 g |
| **Solución** | | **1435,65 g** |

Ahora escalo a los 600 g que tengo (regla de tres):

$$m_{sv} = 600 \times \frac{1000}{1435{,}65} = \mathbf{417{,}9\ g\ de\ agua}$$
$$m_{sto} = 600 - 417{,}9 = \mathbf{182{,}1\ g\ de\ K}_2\text{SO}_4$$

**Verificación:** $n = 182{,}1/174{,}26 = 1{,}045$ mol y $1{,}045/0{,}4179\ \text{kg} = 2{,}50$ m ✓

### Paso 2 — Cuánta agua se necesita para 1,50 m

Los moles no cambian: $n = 1{,}045$ mol.

$$m_{sv}^{final} = \frac{n}{m_{final}} = \frac{1{,}045\ \text{mol}}{1{,}50\ \text{mol/kg}} = 0{,}6965\ \text{kg} = 696{,}5\ \text{g}$$

### Paso 3 — El agua a AGREGAR (⚠️ la resta que se olvida)

$$m_{H_2O\ agregada} = 696{,}5 - 417{,}9 = \boxed{278{,}6\ \text{g de H}_2\text{O}}$$

> 🔴 **La guía dice 280,2 g.** Con Mr(K₂SO₄) = 174,26 la cuenta da **278,6 g**; la diferencia (0,6 %) es redondeo de la masa molar. Cualquiera de los dos está bien si el desarrollo es correcto.

### ⭐ El atajo (y la idea que hay que llevarse)

Como los moles se conservan, la **masa de solvente es inversamente proporcional a la molalidad**:

$$\boxed{m_{sv}^{final} = m_{sv}^{inicial}\cdot\frac{m_{inicial}}{m_{final}}}$$

$$m_{sv}^{final} = 417{,}9 \times \frac{2{,}50}{1{,}50} = 417{,}9 \times 1{,}667 = 696{,}5\ \text{g} \qquad\Rightarrow\qquad \Delta = 278{,}6\ \text{g}\ ✓$$

⚠️ **Los tres errores de este ejercicio:**

| ❌ Error | ✅ Correcto |
|---|---|
| Tomar los 600 g como si fueran **solvente** | Son de **SOLUCIÓN**. Hay que descomponerlos primero |
| Usar $C_0V_0=C_FV_F$ | No vale: la molalidad no va sobre volumen de solución |
| Contestar **696,5 g** | Ésa es el agua **TOTAL** al final. Piden la que hay que **AGREGAR**: hay que **restar** la que ya había |

---

## Ejercicio 20 — Dos preguntas conceptuales (van al parcial)

### a) ¿Por qué las tablas de solubilidad se expresan por masa de solvente?

> 📝 **Respuesta tipo parcial**
> Por **tres razones**, todas del mismo orden de importancia:
>
> **1. La masa NO depende de la temperatura; el volumen SÍ.** La solubilidad se mide **a una temperatura determinada** y las tablas comparan distintas temperaturas. Si la expresáramos por volumen, el número cambiaría con T por **dos causas mezcladas**: porque realmente se disuelve más soluto **y** porque el líquido se **dilata**. Al usar masa, el único efecto que queda es el químico, que es el que interesa. *(Es la misma razón por la que las propiedades coligativas se trabajan en molalidad y no en molaridad.)*
>
> **2. Los volúmenes no son aditivos.** El volumen de la **solución** no es el del solvente más el del soluto (1 L de agua + 1 L de etanol = 1,93 L, no 2 L), y encima depende de **cuánto soluto** haya disuelto. La masa, en cambio, **sí es aditiva y exacta**: $m_{sc} = m_{sto} + m_{sv}$ siempre.
>
> **3. Es la magnitud que se necesita en la práctica.** El dato útil es "cuánto soluto puedo meter en la cantidad de agua que tengo". La **masa de solvente** es un dato fijo y conocido antes de disolver nada; el **volumen de solución** recién se conoce **después**, y depende del propio resultado que estoy buscando — sería una definición circular.
>
> Por eso la unidad estándar es **g de soluto / 100 g de solvente**.

⚠️ **Corolario práctico** (sale en todos los ejercicios de curvas): si el enunciado te da el solvente en **mL**, lo primero que hay que hacer es **pasarlo a gramos con la densidad** antes de escalar la solubilidad.

### b) ¿Cuándo conviene molalidad y cuándo molaridad?

> 📝 **Respuesta tipo parcial**
>
> | | **Molaridad (M)** | **Molalidad (m)** |
> |---|---|---|
> | Definición | mol sto / **L de solución** | mol sto / **kg de SOLVENTE** |
> | ¿Depende de T? | **SÍ** (el volumen se dilata) | **NO** (las masas no cambian con T) |
> | Cómo se prepara | Matraz aforado (rápido) | Pesando los dos componentes |
> | Cuándo conviene | **Trabajo de laboratorio a T constante**: estequiometría en solución, titulaciones, pH, preparar y diluir. Se **mide un volumen con una pipeta**, que es rápido y directo | **Cuando la temperatura varía o es la variable del problema**: propiedades **coligativas** (ascenso ebulloscópico, descenso crioscópico, presión osmótica), tablas de solubilidad, trabajo a T no ambiente |
>
> **En una línea:** la **molaridad** es la unidad **operativa del laboratorio** (medir volúmenes es lo más práctico que hay); la **molalidad** es la unidad **físicamente robusta** (no cambia con la temperatura), y por eso es la que aparece en cualquier expresión donde T sea protagonista.
>
> **Ejemplo concreto:** una solución 1,00 M a 20 °C ya no es exactamente 1,00 M a 80 °C — el líquido se dilató, hay los mismos moles en más volumen. Una solución 1,00 m **sigue siendo 1,00 m a cualquier temperatura**, porque ni los moles ni la masa de agua cambiaron.

💡 **Regla mnemotécnica:** *molaridad = **matraz** (volumen) · molalidad = **balanza** (masa)*. Y: **la M mira el termómetro, la m no.**

⚠️ En **soluciones acuosas diluidas** los dos números casi coinciden (porque 1 L de solución ≈ 1 kg de agua). La diferencia se vuelve importante en soluciones **concentradas** o con solventes de δ ≠ 1.

---
---

# PARA TRABAJAR FUERA DE CLASE

---

## Ejercicio 1 (casa) — Diluir una solución dada en % m/m

> **10,0 g** de solución **40 % m/m** de NaOH, diluidos con agua **hasta que el volumen es 0,5 dm³**.

### La clave

⚠️ **"Hasta que el volumen de la solución es 0,5 dm³"** → los 0,5 L son de **SOLUCIÓN FINAL**. Y el soluto **no cambia** al diluir.

$$m_{NaOH} = 10{,}0 \times 0{,}40 = \mathbf{4{,}0\ g} \qquad\text{(esto se conserva)}$$

### i) % m/V

$$\%\tfrac{m}{V} = \frac{4{,}0\ \text{g}}{500\ \text{cm}^3}\cdot 100 = \boxed{0{,}8\ \%\ \text{m/V}}$$

### ii) Molaridad

$$n = \frac{4{,}0}{40{,}00} = 0{,}100\ \text{mol} \qquad M = \frac{0{,}100}{0{,}500\ \text{L}} = \boxed{0{,}2\ \text{M}}$$

💡 **Chequeo con la relación general** ($\%m/V = M\cdot Mr/10$): $0{,}2\times 40/10 = 0{,}8$ ✓

⚠️ **Los 10,0 g iniciales y el 40 % son un dato "de paso":** sirven **sólo** para sacar los 4,0 g de soluto. Una vez que los tenés, olvidate de la solución original.

---

## Ejercicio 2 (casa) — Dilución directa

> ¿Cuántos cm³ de HNO₃ **3,0 M** para preparar **2,0 dm³** de solución **0,05 M**?

$$V_0 = \frac{C_FV_F}{C_0} = \frac{0{,}05\ \text{M}\times 2000\ \text{cm}^3}{3{,}0\ \text{M}} = \boxed{33{,}3\ \text{cm}^3}$$

💡 **Las unidades de volumen se cancelan:** podés trabajar en cm³ de punta a punta, no hace falta pasar a litros. Sólo tienen que ser **las mismas** de los dos lados.

**Procedimiento:** medir 33,3 cm³ con pipeta, volcar en matraz de 2,0 L y **enrasar** (no agregar 2 L de agua).

---

## Ejercicio 3 (casa) — Dilución, despejando el volumen final

> ¿Qué volumen de solución 0,01 M se obtiene diluyendo **25 cm³** de H₂SO₄ **0,25 M**?

$$V_F = \frac{C_0V_0}{C_F} = \frac{0{,}25\times 25}{0{,}01} = \boxed{625\ \text{cm}^3}$$

💡 **Chequeo por el factor:** $0{,}25/0{,}01 = 25$, o sea una dilución **1:25**. Y $25\ \text{cm}^3\times 25 = 625$ ✓

⚠️ Agua a agregar: $625 - 25 = 600$ cm³. **El volumen final NO es el agua agregada.**

---

## Ejercicio 4 (casa) — Diluir AGREGANDO agua (no enrasando) → molalidad

> **10,0 g** de solución **40 % m/m** de NaOH **+ 500 cm³ de agua**.

### ⚠️ La diferencia con el ejercicio 1

| Ejercicio 1 | Ejercicio 4 |
|---|---|
| "diluir **hasta** 0,5 dm³" | "diluir **por el agregado de** 500 cm³ de agua" |
| Conozco el **V final de solución** | Conozco la **masa de agua agregada** |
| Sale **M** y **% m/V** | Sale **% m/m** y **molalidad** |

**En este caso NO conozco el volumen final** (los volúmenes no son aditivos), así que **no puedo calcular la molaridad**. Pero sí conozco todas las **masas**.

### El balance de masas

| Componente | Cuenta | Masa |
|---|---|---|
| NaOH (soluto) | $10{,}0\times 0{,}40$ | **4,0 g** |
| Agua que ya venía | $10{,}0 - 4{,}0$ | **6,0 g** |
| Agua agregada | $500\ \text{cm}^3\times 1{,}00$ | **500 g** |
| **Agua TOTAL (solvente)** | $6{,}0 + 500$ | **506 g** |
| **Solución** | $4{,}0 + 506$ | **510 g** |

⚠️ **No te olvides de los 6,0 g de agua que ya estaban en la solución original.** Es el error de este ejercicio.

### i) % m/m

$$\frac{4{,}0}{510}\cdot 100 = \boxed{0{,}78\ \%\ \text{m/m}}$$

### ii) Molalidad

$$n_{NaOH} = \frac{4{,}0}{40{,}00} = 0{,}100\ \text{mol} \qquad m = \frac{0{,}100\ \text{mol}}{0{,}506\ \text{kg}} = \boxed{0{,}198\ \text{m}}$$

⚠️ **La molalidad va sobre el SOLVENTE (0,506 kg), no sobre la solución (0,510 kg).** Si usás 0,510 te da 0,196: parece igual, pero está mal conceptualmente y en soluciones concentradas la diferencia es enorme.

---

## Ejercicio 5 (casa) — Enfriar una solución saturada

> **1500 g** de KBr en **2 L de agua** a 80 °C, se enfría a 20 °C. S(KBr, 20 °C) = **65 g/100 g de agua**.

| Paso | Cuenta | Resultado |
|---|---|---|
| **1.** Solvente a gramos | 2 L = 2000 mL × 1,00 | **2000 g de agua** |
| **2.** Máximo a 20 °C | $65 \times \dfrac{2000}{100} = 65\times 20$ | **1300 g** |
| **3.** Comparar | 1500 > 1300 | precipita |
| **4.** Sin disolver | $1500 - 1300$ | $\boxed{200\ \text{g de KBr}}$ |

⚠️ **El dato "a 80 °C" es contexto, no dato de cálculo.** Sirve para saber que **a 80 °C sí estaba todo disuelto** (S(80 °C) ≈ 95 g/100 g → máximo 1900 g > 1500 ✓). La cuenta se hace **con la solubilidad a la temperatura final**, que es la única que importa.

💡 Éste es el fenómeno de la **cristalización por enfriamiento**: al bajar la temperatura, la solubilidad cae y el exceso de soluto **cae en forma de cristales**. Es como se purifican sólidos en el laboratorio.

---

## Ejercicio 6 (casa) — Escalar la solubilidad hacia abajo

> S(NaCl, 10 °C) = **35,8 g en 100 mL de agua**. ¿Cuánto se disuelve en **80 mL**?

$$m_{max} = 35{,}8 \times \frac{80}{100} = 35{,}8\times 0{,}8 = \boxed{28{,}64\ \text{g}}$$

💡 Es la misma regla de tres del ejercicio 14, pero **hacia abajo**. La solubilidad es **intensiva**: no depende de cuánto solvente haya, es una **proporción**.

⚠️ **El resultado tiene que ser MENOR que 35,8**, porque hay menos agua. Si te da más, invertiste la fracción.

---

## Ejercicio 7 (casa) — Clasificar una solución

> S(MnSO₄, 20 °C) = **7 mg por cada mL de agua**. Un litro de solución contiene **1,22 mol** de MnSO₄. ¿Saturada, sobresaturada o insaturada?
> Mr MnSO₄ = 54,94 + 32,06 + 64,00 = **151,00 g/mol**

### El método: llevar las dos a la MISMA unidad

**La solubilidad, a g/L:**
$$S = 7\ \tfrac{\text{mg}}{\text{mL}} = 7\ \tfrac{\text{g}}{\text{L}}$$

**Lo que hay disuelto, a g/L:**
$$c = 1{,}22\ \tfrac{\text{mol}}{\text{L}} \times 151{,}00\ \tfrac{\text{g}}{\text{mol}} = \mathbf{184{,}2\ \tfrac{\text{g}}{\text{L}}}$$

### La comparación

$$184{,}2\ \tfrac{g}{L} \;\ggg\; 7\ \tfrac{g}{L} \qquad\Rightarrow\qquad c > S \qquad\Rightarrow\qquad \boxed{\text{SOBRESATURADA}}$$

Y no por poco: hay **26 veces más** soluto disuelto del que admite el equilibrio.

### El criterio general (para cualquier ejercicio de este tipo)

| Relación | Tipo | En la curva | ¿Estable? |
|---|---|---|---|
| $c < S$ | **Insaturada** | debajo | ✓ |
| $c = S$ | **Saturada** | sobre la curva | ✓ equilibrio |
| $c > S$ | **Sobresaturada** | arriba | ❌ **metaestable** |

⚠️ **"Sobresaturada" no es "tiene precipitado".** Al revés: en una sobresaturada **está TODO disuelto**, en una situación que no debería poder sostenerse. Es **metaestable**: alcanza un golpe, una impureza o un cristal de siembra para que precipite el exceso (177 g/L, en este caso) de golpe.

⚠️ **La trampa:** comparar 1,22 (mol/L) con 7 (mg/mL) directamente. **Son unidades distintas.** Siempre unificar antes de comparar.

---

## Ejercicio 8 (casa) — Factor de dilución vs. agua a agregar

> Solución **1,20 M** de AgNO₃.

### a) Factor de dilución para llegar a 0,40 M

$$n = \frac{C_{inicial}}{C_{final}} = \frac{1{,}20}{0{,}40} = 3 \qquad\Rightarrow\qquad \boxed{\text{dilución 1:3}}$$

*(1 volumen de solución llevado a **3 volúmenes totales**)*

### b) Agua a agregar a 400 mL (volúmenes aditivos)

$$V_F = V_0\times n = 400\ \text{mL}\times 3 = 1200\ \text{mL}$$

$$V_{agua} = V_F - V_0 = 1200 - 400 = \boxed{800\ \text{mL de agua}}$$

### ⚠️ LA distinción de todo el tema

| | Qué es | Valor acá |
|---|---|---|
| **Factor de dilución (1:3)** | 1 parte de solución **llevada a 3 partes totales** | 3 |
| **Volumen FINAL** | El del matraz | 1200 mL |
| **Agua a AGREGAR** | $V_F - V_0$ | **800 mL** |
| ❌ Lo que **NO** es | "1 parte + 3 de agua" (eso sería 1:4) | ~~1200 mL de agua~~ |

$$\boxed{1{:}n \;\Rightarrow\; \text{1 de solución} + (n-1)\ \text{de agua}}$$

Acá: 1 de solución + **2** de agua → 400 + 800 = 1200 ✓

**Verificación:** $1{,}20\times 400 = 480$ y $0{,}40\times 1200 = 480$ ✓

⚠️ **Ojo:** este cálculo del agua **sólo vale porque el enunciado dice "volúmenes aditivos"**. En la realidad se pone la alícuota en el matraz y **se enrasa a 1200 mL**, sin medir el agua.

---

## Ejercicio 9 (casa) — ⭐ El ejercicio más importante de la serie

> ¿Cuántos gramos de **KCl** hay que agregar a **100 mL de agua** para obtener una solución:
> a) 0,48 m (δ = 1,0207) · b) 10 % m/m (δ = 1,0633) · c) x_KCl = 0,050 (δ = 1,118) · d) 0,34 M (δ = 1,014)?
> Mr KCl = 39,10 + 35,45 = **74,55 g/mol**

**Por qué es el más importante:** es **la misma pregunta cuatro veces**, cambiando sólo la unidad. Si entendés estas cuatro cuentas, entendés toda la serie.

### El dato común

⚠️ **100 mL de agua = 100 g de SOLVENTE.** Es un dato **fijo** en las cuatro partes. Lo que cambia es la unidad en que me piden el resultado.

$$n_{H_2O} = \frac{100}{18{,}02} = 5{,}549\ \text{mol de agua}$$

💡 **Observación clave (y pregunta de parcial):** las densidades de a), b) y c) **son datos de más — no se usan.** Sólo la de (d) hace falta, porque la **molaridad** es la única de las cuatro que necesita un **volumen de solución**. Las otras tres se resuelven **sólo con masas y moles**.

### a) 0,48 m (molalidad) — la más directa

La molalidad va **directo sobre el solvente**, que ya conozco:

$$n_{sto} = m \cdot m_{sv}(\text{kg}) = 0{,}48\ \tfrac{\text{mol}}{\text{kg}} \times 0{,}100\ \text{kg} = 0{,}048\ \text{mol}$$

$$m_{KCl} = 0{,}048 \times 74{,}55 = \boxed{3{,}58\ \text{g}}$$

### b) 10 % m/m — ecuación de una incógnita

$$\frac{x}{x + 100} = 0{,}10 \;\Rightarrow\; x = 0{,}10x + 10 \;\Rightarrow\; 0{,}90x = 10 \;\Rightarrow\; \boxed{x = 11{,}1\ \text{g}}$$

💡 **El atajo:** en un 10 % m/m, de cada 100 g de solución 10 son sal y **90 son agua**. Entonces sal/agua = 10/90 = 1/9:

$$x = \frac{100\ \text{g agua}}{9} = 11{,}1\ \text{g}\ ✓$$

⚠️ El error acá es hacer $100\times 0{,}10 = 10$ g. Eso daría un **9,09 %**, porque los 100 g son de **agua**, no de solución.

### c) x_KCl = 0,050 (fracción molar) — hay que trabajar en MOLES

$$\frac{n}{n + 5{,}549} = 0{,}050 \;\Rightarrow\; n = 0{,}050n + 0{,}2775 \;\Rightarrow\; 0{,}950n = 0{,}2775$$

$$n = 0{,}2921\ \text{mol} \qquad\Rightarrow\qquad m_{KCl} = 0{,}2921\times 74{,}55 = \boxed{21{,}8\ \text{g}}$$

⚠️ **Acá NO se puede trabajar en gramos.** La fracción molar es una relación de **partículas**: hay que pasar los 100 g de agua a **5,549 mol** antes de plantear nada.

💡 Fijate el salto: una fracción molar de **apenas 0,050** (5 partículas de cada 100) exige **21,8 g de sal**, ¡seis veces más que el 0,48 m! Es porque el agua tiene una Mr muy chica: **100 g de agua son muchísimos moles**.

### d) 0,34 M (molaridad) — la única que necesita la densidad

**Por qué es la difícil:** la molaridad va sobre el **volumen de SOLUCIÓN**, y ese volumen **depende de cuánta sal ponga** — que es justamente la incógnita. Hay que plantear la ecuación completa.

Sea $x$ = gramos de KCl:

| Magnitud | En función de x |
|---|---|
| $m_{sc}$ | $x + 100$ |
| $V_{sc}$ (mL) | $\dfrac{x+100}{1{,}014}$ |
| $V_{sc}$ (L) | $\dfrac{x+100}{1014}$ |
| $n_{sto}$ | $\dfrac{x}{74{,}55}$ |

$$M = \frac{n}{V(\text{L})} = \frac{x/74{,}55}{(x+100)/1014} = \frac{1014\,x}{74{,}55\,(x+100)} = 0{,}34$$

$$13{,}602\,x = 0{,}34\,(x+100) \;\Rightarrow\; 13{,}602x - 0{,}34x = 34 \;\Rightarrow\; 13{,}262x = 34$$

$$\boxed{x = 2{,}56\ \text{g de KCl}}$$

**Verificación:** $m_{sc} = 102{,}56$ g → $V = 102{,}56/1{,}014 = 101{,}1$ mL → $n = 2{,}56/74{,}55 = 0{,}0344$ mol → $M = 0{,}0344/0{,}1011 = 0{,}340$ ✓

### 🎯 La comparación final (esto es lo que hay que llevarse)

| Consigna | Masa de KCl | ¿Usa δ? | Se plantea sobre |
|---|---|---|---|
| **0,48 m** | 3,58 g | ❌ no | **solvente**, en moles/kg |
| **0,34 M** | 2,56 g | ✓ **sí** | **solución**, en moles/L |
| **10 % m/m** | 11,1 g | ❌ no | **solución**, en masas |
| **x = 0,050** | 21,8 g | ❌ no | **totales**, en moles |

⚠️ **Los cuatro números son distintos y ninguno está mal.** Describen **cuatro soluciones diferentes**, todas preparadas sobre los mismos 100 mL de agua. Confundir las unidades no es un detalle de forma: **cambia la solución que preparás**.

💡 **La molaridad es la más chica** de las cuatro porque 0,34 mol/L en ~0,1 L son sólo 0,034 mol; **la fracción molar es la más grande** porque el agua aporta 5,5 mol y para llegar al 5 % del total hace falta muchísima sal.

---

## Ejercicio 10 (casa) — % V/V y contracción de volumen

> Etanol (δ = 0,7893 g/cm³) agregado a **700 cm³ de agua** para obtener **10 % v/v**, suponiendo volúmenes aditivos.

### a) Volumen y masa de etanol · composición en masa

**El % V/V va sobre el volumen de SOLUCIÓN**, no sobre el de agua. Con aditividad, $V_{sc} = V_{et} + 700$:

$$\frac{V_{et}}{V_{et}+700} = 0{,}10 \;\Rightarrow\; V_{et} = 0{,}10V_{et} + 70 \;\Rightarrow\; 0{,}90V_{et} = 70$$

$$\boxed{V_{et} = 77{,}8\ \text{cm}^3}$$

⚠️ **El error:** hacer $700\times 0{,}10 = 70$ cm³. Eso daría un 9,09 % v/v, porque los 700 cm³ son de **agua**, no de solución.

**Masa de etanol:**
$$m_{et} = 77{,}8\ \text{cm}^3 \times 0{,}7893\ \tfrac{\text{g}}{\text{cm}^3} = \boxed{61{,}4\ \text{g}}$$

**Composición porcentual en masa:**
$$m_{sc} = 61{,}4 + 700 = 761{,}4\ \text{g} \qquad \%\tfrac{m}{m} = \frac{61{,}4}{761{,}4}\cdot 100 = \boxed{8{,}06\ \%\ \text{m/m}}$$

⚠️ **¡10 % v/v ≠ 10 % m/m!** Da **8,06 %** porque el etanol es **menos denso** que el agua: 77,8 cm³ de etanol pesan menos que 77,8 cm³ de agua. En general:

$$\boxed{\%\tfrac{m}{m} = \%\tfrac{V}{V}\cdot\frac{\delta_{sto}}{\delta_{sc}}} \qquad 10\times\frac{0{,}7893}{0{,}9847} = 8{,}02\ \%\ \text{(≈ ✓)}$$

📡 **Por eso las etiquetas de bebidas alcohólicas dicen "% vol"** (% v/v): una cerveza de "5°" es 5 % v/v, que en masa son ~4 %.

### b) Volumen real vs. volumen aditivo

**Con la densidad real de la solución** (la masa **sí** es aditiva, siempre):

$$V_{sc}^{real} = \frac{m_{sc}}{\delta_{sc}} = \frac{761{,}4\ \text{g}}{0{,}9847\ \text{g/cm}^3} = \boxed{773{,}2\ \text{cm}^3}$$

**Con volúmenes aditivos** (la suposición del punto a):

$$V_{sc}^{aditivo} = 77{,}8 + 700 = \boxed{777{,}8\ \text{cm}^3}$$

### ⭐ La contracción de volumen

$$\Delta V = 773{,}2 - 777{,}8 = \mathbf{-4{,}6\ cm^3} \qquad \frac{4{,}6}{777{,}8} = \mathbf{0{,}6\ \%\ de\ contracción}$$

**Por qué pasa.** Las moléculas de agua y de etanol forman **puentes de hidrógeno entre sí** más eficientemente que cada líquido consigo mismo, y además el etanol tiene una parte no polar que **se acomoda en los huecos** de la red del agua. El resultado: **el conjunto ocupa menos que la suma de las partes**.

$$\boxed{V_{sto} + V_{sv} \neq V_{sc}}\qquad \text{(las MASAS sí son aditivas)}$$

💡 **El caso extremo, que hay que saber:** **1 L de agua + 1 L de etanol = 1,93 L**, no 2 L. Contracción del **3,5 %**.

⚠️ **Por eso en el laboratorio se ENRASA al final** en lugar de medir el agua: es la única manera de garantizar el volumen final de la solución.
⚠️ Fijate que la diferencia acá es de sólo el 0,6 %, y aun así el ejercicio te la hace calcular: en trabajo analítico, 0,6 % es un error grande.

---

## Ejercicio 11 (casa) — Villavicencio: tres unidades y una comparación

> Agua mineral con **272 ppm de ion Na⁺**. Expresar en % m/m, molaridad y fracción molar. Comparar con el agua de mar (0,46 M).

### % m/m

$$\%\tfrac{m}{m} = \frac{272}{10^4} = \boxed{0{,}0272\ \%\ \text{m/m}}$$

### Molaridad

Aproximación estándar (agua muy diluida, δ ≈ 1,00 g/mL): **272 ppm = 272 mg/L**.

$$M = \frac{0{,}272\ \text{g/L}}{22{,}99\ \text{g/mol}} = \boxed{0{,}0118\ \text{M}}$$

*(La guía escribe "0,0118 **m**". Numéricamente coincide con la molalidad porque la solución es casi agua pura, pero lo que se pide es la **molaridad**, M.)*

### Fracción molar

Trabajo sobre **1 L de solución ≈ 1000 g**:

| Componente | Masa | Moles |
|---|---|---|
| Na⁺ | 0,272 g | $0{,}272/22{,}99 = 0{,}01183$ |
| H₂O | 999,73 g | $999{,}73/18{,}02 = 55{,}48$ |

$$x_{Na^+} = \frac{0{,}01183}{0{,}01183 + 55{,}48} = \boxed{2{,}13\times 10^{-4}}$$

### La comparación con el agua de mar

$$\frac{0{,}46\ \text{M}}{0{,}0118\ \text{M}} = \boxed{39\ \text{veces más concentrada el agua de mar}}$$

> 📝 **Respuesta tipo parcial**
> El agua mineral tiene 0,0118 M de Na⁺ frente a 0,46 M del agua de mar: el mar es **39 veces más concentrado** en sodio. Por eso el agua mineral es bebible y el agua de mar no — beberla **deshidrata**, porque el riñón necesita más agua para excretar esa carga de sal de la que aporta el líquido ingerido.

💡 **Conectá con el ejercicio 13 de clase:** 272 mg/L × 2 L = **544 mg de Na por día**, muy por encima de los 200 mg disponibles del hipertenso. Esta marca **no le serviría**.

---

## Ejercicio 12 (casa) — ppm de flúor en un enjuague bucal

> Cada **100 g** de enjuague: **NaF 100 mg** + **Na₂PO₃F 760 mg**. Calcular el contenido de **flúor** en ppm.
> Mr NaF = **41,99** · Mr Na₂PO₃F = 2(22,99) + 30,97 + 3(16,00) + 19,00 = **143,95**

### La idea

⚠️ **Piden el FLÚOR, no las sales.** Cada sal aporta su parte y los aportes **se suman**. Hay que extraer el F de cada una con la **fracción de masa**.

### Aporte de cada sal

**Del NaF** (1 F por fórmula):
$$m_F = 100\ \text{mg}\times\frac{19{,}00}{41{,}99} = 100\times 0{,}4525 = 45{,}25\ \text{mg de F}$$

**Del Na₂PO₃F** (1 F por fórmula):
$$m_F = 760\ \text{mg}\times\frac{19{,}00}{143{,}95} = 760\times 0{,}1320 = 100{,}31\ \text{mg de F}$$

**Total:**
$$m_F = 45{,}25 + 100{,}31 = \mathbf{145{,}6\ mg\ de\ F\ cada\ 100\ g}$$

### Pasar a ppm

$$\text{ppm} = \frac{m_{sto}}{m_{sc}}\cdot 10^6 = \frac{0{,}1456\ \text{g}}{100\ \text{g}}\cdot 10^6 = \boxed{1456\ \text{ppm} \approx 1450\ \text{ppm}}$$

💡 **Atajo:** 145,6 mg/100 g = 1456 mg/kg, y **1 mg/kg = 1 ppm**. La cuenta es directa.

### ⚠️ Los dos errores

| ❌ Error | Consecuencia |
|---|---|
| Sumar las **sales** (100 + 760 = 860 mg) y pasarlo a ppm | Da 8600 ppm. **Estás contando el Na, el P y el O como si fueran flúor** |
| Usar sólo una de las dos sales | El Na₂PO₃F aporta **más del doble** de F que el NaF, aunque su fracción de F sea menor, porque hay 7,6 veces más masa |

💡 **Dato real:** las pastas dentales adultas tienen **1000–1500 ppm** de F, y las infantiles **500 ppm** (para reducir el riesgo de fluorosis si el chico traga). Este enjuague, con 1456 ppm, está en el rango terapéutico adulto. El flúor previene caries porque convierte la **hidroxiapatita** del esmalte en **fluorapatita**, más resistente al ácido.

---

## Ejercicio 13 (casa) — Mezcla de solutos DISTINTOS

> **100 cm³** de NaCl **0,25 M** (ρ = 1,008 g/cm³) + **300 cm³** de glucosa **1,25 M** (ρ = 1,106 g/cm³).
> Dato para (b): ρ de la mezcla = **1,084 g/cm³**. Mr NaCl = 58,44 · Mr glucosa = 180,16

### ⚠️ La diferencia con el ejercicio 11 de clase

| Ejercicio 11 (clase) | Este ejercicio |
|---|---|
| **MISMO** soluto en las dos | **DISTINTOS** solutos |
| Se suman los moles → **una** concentración | **NO** se suman: cada uno tiene **su propia** concentración |
| Cada solución **concentra** a la otra en ese soluto | Cada solución **DILUYE** a la otra |

**Lo que hay que ver:** para el NaCl, los 300 cm³ de glucosa funcionan como **solvente**. Y viceversa. Cada soluto se **diluye** en el volumen total.

### El balance de masas (siempre primero)

| Componente | Cuenta | Valor |
|---|---|---|
| $n_{NaCl}$ | $0{,}100\ \text{L}\times 0{,}25$ | **0,0250 mol** |
| $m_{NaCl}$ | $0{,}0250\times 58{,}44$ | **1,46 g** |
| $n_{glucosa}$ | $0{,}300\ \text{L}\times 1{,}25$ | **0,375 mol** |
| $m_{glucosa}$ | $0{,}375\times 180{,}16$ | **67,56 g** |
| $m_{sc\,1}$ | $100\times 1{,}008$ | 100,8 g |
| $m_{sc\,2}$ | $300\times 1{,}106$ | 331,8 g |
| **$m_{sc}$ total** | $100{,}8 + 331{,}8$ | **432,6 g** ✓ *(las masas SÍ son aditivas)* |

### a) % m/m de cada soluto **en la mezcla**

$$\%\tfrac{m}{m}_{NaCl} = \frac{1{,}46}{432{,}6}\cdot 100 = \boxed{0{,}338\ \%\ \text{m/m}}$$

$$\%\tfrac{m}{m}_{glucosa} = \frac{67{,}56}{432{,}6}\cdot 100 = \boxed{15{,}6\ \%\ \text{m/m}}$$

> 🔴 **Errata de la guía.** Figuran **1,45 %** y **20,4 %**. Esos son los porcentajes de cada soluto **en su solución de origen**:
> $$\frac{1{,}46}{100{,}8}\cdot 100 = 1{,}45\ \% \qquad \frac{67{,}56}{331{,}8}\cdot 100 = 20{,}4\ \%$$
> Pero el enunciado pide **"en la solución resultante"**, o sea en los **432,6 g de mezcla**. Las respuestas correctas son **0,338 %** y **15,6 %**.
> **Cómo detectarlo solo:** al mezclar, **cada soluto se diluye** → sus porcentajes tienen que **BAJAR**. Los de la guía dan igual o mayores que los originales, lo cual es imposible.

### b) Molaridad de cada soluto en la mezcla

⚠️ **Acá hay que usar la densidad de la MEZCLA**, porque los volúmenes **no son aditivos**:

$$V_{sc} = \frac{m_{sc}}{\delta_{mezcla}} = \frac{432{,}6\ \text{g}}{1{,}084\ \text{g/cm}^3} = 399{,}1\ \text{cm}^3 = 0{,}3991\ \text{L}$$

💡 Fijate: **399,1 mL, no 400 mL**. Hubo una contracción de 0,9 mL. Por eso dan la densidad.

$$M_{NaCl} = \frac{0{,}0250}{0{,}3991} = \boxed{0{,}0626\ \text{M}} \qquad M_{glucosa} = \frac{0{,}375}{0{,}3991} = \boxed{0{,}940\ \text{M}}$$

💡 **Chequeo conceptual:** las dos bajaron respecto del origen (0,25 → 0,063 y 1,25 → 0,94) ✓ **Al mezclar soluciones de solutos distintos, TODAS las concentraciones bajan.** El NaCl bajó a la cuarta parte (pasó de 100 a ~400 mL) y la glucosa a las tres cuartas partes (de 300 a ~400 mL).

---

## Ejercicio 14 (casa) — Preparar con el material que hay

> Preparar **1,5 L** de H₂SO₄ **0,05 M** a partir de H₂SO₄ **12,5 M**.
> Material: matraces de **2 · 1 · 0,5 · 0,25 L** · pipetas de **1, 2 y 5 mL** · probetas de **5, 10, 50 y 100 mL** · balanza · agua destilada.

### a) La cuenta y el problema del material

$$V_0 = \frac{C_FV_F}{C_0} = \frac{0{,}05\ \text{M}\times 1500\ \text{mL}}{12{,}5\ \text{M}} = \boxed{6{,}0\ \text{mL de H}_2\text{SO}_4\ 12{,}5\ \text{M}}$$

⚠️ **El problema: NO hay matraz de 1,5 L.** Ésa es la gracia del ejercicio — hay que resolverlo con lo que hay.

> 📝 **Respuesta tipo parcial — procedimiento**
> Se necesitan **6,0 mL** de la solución 12,5 M. Como no hay matraz de 1,5 L, se prepara en **dos matraces**:
>
> | Matraz | Alícuota de la madre | Cómo medirla |
> |---|---|---|
> | **1,00 L** | $0{,}05\times 1000/12{,}5 = 4{,}0$ mL | pipeta de 2 mL, **dos veces** |
> | **0,50 L** | $0{,}05\times 500/12{,}5 = 2{,}0$ mL | pipeta de 2 mL, una vez |
> | **Total** | **6,0 mL** → **1,5 L** de solución 0,05 M | |
>
> Para cada matraz:
> 1. Poner **agua destilada hasta ~la mitad** del matraz.
> 2. Agregar la alícuota de ácido **con pipeta y propipeta** (⚠️ **nunca pipetear con la boca**).
> 3. **Enrasar** con agua destilada hasta el aforo, leyendo el menisco a la altura de la vista.
> 4. **Homogeneizar** por inversión.
>
> ⚠️ **REGLA DE SEGURIDAD:** el **ÁCIDO SOBRE EL AGUA**, nunca al revés. La dilución del H₂SO₄ es fuertemente **exotérmica**; si se agrega agua sobre el ácido concentrado, el agua hierve al instante y **proyecta ácido**. Por eso el paso 1 (agua primero) no es un detalle: es **el** procedimiento.
>
> **Alternativa:** preparar **2,0 L** en el matraz de 2 L (necesita $0{,}05\times 2000/12{,}5 = 8{,}0$ mL, medibles con la pipeta de 5 + la de 2 + la de 1) y usar 1,5 L. Funciona, pero **desperdicia 0,5 L de solución y reactivo** — la opción de los dos matraces es mejor.

⚠️ **La pipeta, no la probeta.** Para medir 4,0 mL de un ácido 12,5 M hay que usar la **pipeta** (mucho más exacta); la probeta de 5 mL tendría un error relativo enorme sobre un volumen tan chico, y ese error se propaga a toda la solución final.

### b) % m/V de la solución diluida

$$\%\tfrac{m}{V} = \frac{M\cdot Mr}{10} = \frac{0{,}05 \times 98{,}08}{10} = \frac{4{,}904\ \text{g/L}}{10} = \boxed{0{,}49\ \%\ \text{m/V}}$$

*(o directo: 0,05 mol/L × 98,08 g/mol = 4,90 g/L = 0,490 g cada 100 mL = 0,49 % m/V)*

> 🔴 **Errata de la guía:** figura **0,33 % m/V**. Para que diera 0,33 la masa molar del H₂SO₄ tendría que ser ~66 g/mol, y es **98,08**. La respuesta correcta es **0,49 % m/V**.

### c) Densidad a partir de % m/V y % m/m

**La relación es la del ejercicio 7 de clase:**

$$\%\tfrac{m}{V} = \%\tfrac{m}{m}\cdot\delta \qquad\Rightarrow\qquad \boxed{\delta = \frac{\%m/V}{\%m/m}}$$

**Con el dato del enunciado (0,35 % m/m) y el % m/V correcto:**

$$\delta = \frac{0{,}49}{0{,}35} = 1{,}40\ \text{g/mL}$$

> 🔴 **Este resultado es físicamente imposible** — y también lo es el de la guía (0,943 g/mL). Una solución acuosa de H₂SO₄ **0,05 M** es agua con un 0,5 % de ácido: su densidad **tiene que ser ≈ 1,00 g/mL**. Ni 1,40 (más densa que el ácido comercial al 37 %) ni 0,943 (menos densa que el agua pura) tienen sentido.
>
> **De dónde sale el enredo:** el dato "0,35 % m/m" está mal. Para 0,05 M con δ ≈ 1,00, el % m/m correcto es **0,49 %** — igual al % m/V, precisamente porque δ = 1.
>
> **En el parcial:** aplicá la fórmula $\delta = \dfrac{\%m/V}{\%m/m}$ con los datos que te den, **y aclarás si el resultado no es físicamente razonable**. Eso último suma; el número no.

⚠️ **Chequeo de razonabilidad que conviene hacer siempre:** una solución acuosa **diluida** tiene δ entre **0,99 y 1,05 g/mL**. Si te da 1,4 o 0,94, algo está mal en los datos o en la cuenta.

### d) Dilución 1:10 de la solución concentrada

$$M_2 = \frac{M_1}{10} = \frac{12{,}5}{10} = \boxed{1{,}25\ \text{M}}$$

⚠️ **1:10 = 1 volumen llevado a 10 volúmenes totales** (1 de ácido + 9 de agua), **no** 1 + 10.

---

## Ejercicio 15 (casa) — Tabla de solubilidad del CuSO₄

> ⚠️ **Ojo con la unidad: acá la solubilidad viene en g/L, no en g/100 g.** Cambia toda la aritmética: se escala por **litros de agua**, no por centenas de gramos.

| T (°C) | 20 | 30 | 40 | 50 | 60 | 70 | 80 |
|---|---|---|---|---|---|---|---|
| **S (g/L)** | 210 | 245 | 290 | 340 | 400 | 470 | 550 |

### a) CuSO₄ que se disuelve en 5 L de agua a 40 °C

$$m = S(40) \times V = 290\ \tfrac{\text{g}}{\text{L}} \times 5\ \text{L} = \boxed{1450\ \text{g} = 1{,}45\ \text{kg}}$$

### b) ¿A qué temperatura disuelve 500 g en 1 L?

Necesito S = 500 g/L. En la tabla: **470 g/L a 70 °C** y **550 g/L a 80 °C** → está en el medio. **Interpolación lineal:**

$$T = 70 + 10\cdot\frac{500 - 470}{550 - 470} = 70 + 10\cdot\frac{30}{80} = 70 + 3{,}75 = \boxed{\approx 74\ °\text{C}}$$

### c) ¿Cuánto se disuelve en 1 L a 55 °C?

55 °C está justo entre 50 (340) y 60 (400):

$$S(55) = 340 + \frac{400-340}{2} = 340 + 30 = \boxed{370\ \text{g/L}}$$

### d) 1 kg de CuSO₄ en 2 L de agua a 60 °C

| Paso | Cuenta | Resultado |
|---|---|---|
| Máximo disoluble | $400\ \tfrac{\text{g}}{\text{L}}\times 2\ \text{L}$ | **800 g** |
| Comparar | 1000 g **>** 800 g | satura y sobra |
| Sin disolver | $1000 - 800$ | **200 g** |

$$\boxed{\text{Se disuelven 800 g; quedan 200 g de CuSO}_4\ \text{sin disolver en el fondo}}$$

La solución de arriba queda **SATURADA**; el sistema es **heterogéneo (2 fases)**.

💡 **Cómo disolverlo todo:** calentar. Con S = 500 g/L bastaría (500 × 2 = 1000 g), y por (b) eso ocurre a **~74 °C**.

### e) ¿Cuánta agua a 40 °C hace falta para disolver 1 kg?

Ahora la incógnita es el **solvente**:

$$V_{agua} = \frac{m_{sto}}{S(40)} = \frac{1000\ \text{g}}{290\ \text{g/L}} = \boxed{3{,}45\ \text{L de agua}}$$

💡 **Chequeo:** $290 \times 3{,}45 = 1000$ g ✓

### 🔑 Las tres preguntas posibles y cómo se despeja cada una

$$\boxed{m_{sto} = S \times V_{sv}}$$

| Incógnita | Despeje | Ejemplo |
|---|---|---|
| **Cuánto soluto** entra | $m = S\cdot V$ | (a), (c) |
| **Cuánto solvente** necesito | $V = m/S$ | (e) |
| **A qué temperatura** | $S = m/V$ → **buscar/interpolar en la tabla** | (b) |

⚠️ **Y la cuarta, la de "¿se disuelve todo?":** comparar $m$ con $S\cdot V$ y **restar** el sobrante (d).

---
---

# 🔴 ERRATAS DE LA GUÍA — todas juntas

**Chequeadas número por número.** Si tu resultado no coincide con la guía, mirá esta tabla antes de volver a hacer la cuenta.

| Ej. | Qué dice la guía | Lo correcto | Qué pasó |
|---|---|---|---|
| **8b** (clase) | $x = 9{,}46\times 10^{-3}$ | $\mathbf{9{,}58\times 10^{-3}}$ | Redondeo de la masa de agua (dif. 1,2 %) |
| **12** (clase) | As 5×10⁻⁶ % / 6,7×10⁻⁷ M · Cd 1×10⁻⁶ % / 8,9×10⁻⁸ M · Hg 2×10⁻⁷ % / 1×10⁻⁸ M | As **1×10⁻⁶ % / 1,3×10⁻⁷ M** · Cd **5×10⁻⁷ % / 4,4×10⁻⁸ M** · Hg **1×10⁻⁷ % / 5,0×10⁻⁹ M** | Las respuestas son de **otros límites** (As 0,05 · Cd 0,01 · Hg 0,002 ppm). Sólo el **Pb coincide** |
| **17c** (clase) | 29,19 g | **24,19 g** | Error de tipeo (2**9** por 2**4**). $0{,}5\times 0{,}2\times 241{,}88 = 24{,}19$ |
| **19** (clase) | 280,2 g H₂O | **278,6 g H₂O** | Redondeo de Mr(K₂SO₄) (dif. 0,6 %) |
| **13a** (casa) | 1,45 % y 20,4 % m/m | **0,338 %** y **15,6 %** | La guía calculó el % en **cada solución de origen**, no en la **mezcla** |
| **14b–c** (casa) | 0,33 % m/V · δ = 0,943 g/mL | **0,49 % m/V** · δ ≈ **1,00 g/mL** | El % m/V está mal y arrastra la densidad. Además, δ = 0,943 para una solución acuosa diluida es **imposible** |

**Erratas menores de notación:**

| Ej. | Detalle |
|---|---|
| **11** (casa) | La guía escribe "0,0118 **m**"; se pide la **molaridad**: **0,0118 M** (coinciden numéricamente porque la solución es casi agua pura) |
| **6** (clase) | **No existe.** La numeración va 5 → 7 |

💡 **La moraleja:** el **chequeo de razonabilidad** vale más que la respuesta impresa. Si el % de un soluto **sube** al diluirlo, o una solución acuosa diluida tiene δ = 0,94, hay un error — sea tuyo o de la guía.

---

# 🎯 Los métodos de la serie, en una página

## 1. Cualquier ejercicio de concentración

```
1. LEER si el dato es de SOLUCIÓN o de SOLVENTE     ("en 200 mL" vs "hasta 200 mL")
2. Armar la TABLA DE MASAS:   m_sto | m_sv | m_sc     (las masas SÍ son aditivas)
3. Si hace falta volumen → usar δ                    (V = m/δ)
4. Si hace falta moles   → usar Mr                   (n = m/Mr)
5. Recién ahí, aplicar la fórmula de la unidad pedida
```

## 2. Diluciones y mezclas

| Situación | Qué se conserva | Ecuación |
|---|---|---|
| **Diluir** (agregar solvente) | moles de soluto | $C_0V_0 = C_FV_F$ |
| **Concentrar** (evaporar) | moles de soluto | $C_0V_0 = C_FV_F$ |
| **Mezclar, MISMO soluto** | moles y volúmenes | $M_F = \dfrac{M_1V_1+M_2V_2}{V_1+V_2}$ |
| **Mezclar, solutos DISTINTOS** | moles de cada uno, por separado | $M_i = \dfrac{n_i}{V_{total}}$ **para cada soluto** |
| **Diluir en MOLALIDAD** | moles de soluto | $m_{sv}^F = m_{sv}^0\cdot\dfrac{m_{molal}^0}{m_{molal}^F}$ |

## 3. Solubilidad — "¿se disuelve todo?"

```
1. Solvente a GRAMOS (o a litros, según la unidad de la tabla)
2. máx = S × (m_solvente/100)     [si S está en g/100 g]
   máx = S × V_solvente           [si S está en g/L]
3. cantidad ≤ máx  →  INSATURADA, se disuelve todo
   cantidad >  máx →  SATURADA + precipitado = cantidad − máx
```

| Relación | Tipo | ¿Estable? |
|---|---|---|
| $c < S$ | **Insaturada** | ✓ |
| $c = S$ | **Saturada** | ✓ equilibrio dinámico |
| $c > S$ | **Sobresaturada** | ❌ metaestable |

## 4. Preparar una solución en el laboratorio

| Punto de partida | Método | Cuenta | Pasos |
|---|---|---|---|
| **Soluto sólido** | Gravimétrico + aforo | $m = M\cdot V(\text{L})\cdot Mr$ | pesar → disolver en **vaso** → enfriar → trasvasar + **enjuagar** → **enrasar** → homogeneizar |
| **Solución madre** | Dilución | $V_0 = \dfrac{C_FV_F}{C_0}$ | agua al matraz → alícuota con **pipeta** → **enrasar** → homogeneizar |

⚠️ **Las cinco reglas de laboratorio que se preguntan:**
1. Se **DISUELVE antes de enrasar**, nunca después (los volúmenes no son aditivos).
2. Se **enjuaga el vaso** 2–3 veces y los enjuagues van al matraz (trasvase cuantitativo).
3. **ÁCIDO SOBRE AGUA**, nunca al revés.
4. **Nunca pipetear con la boca**: propipeta.
5. Menisco por su parte **inferior** y **a la altura de la vista** (error de **paralaje**).

---

# ⚠️ Errores típicos de la Serie 4

| ❌ Error | ✅ Correcto |
|---|---|
| "**en** 200 cm³ de agua" tratado como solución | Son 200 g de **SOLVENTE**. La solución pesa $m_{sto}+200$ |
| "**hasta** 200 cm³" tratado como solvente | Son 200 cm³ de **SOLUCIÓN**. Ya está todo adentro |
| Ignorar la **densidad** cuando el problema la da | Si te dieron δ, es porque hay que **cruzar masa ↔ volumen** |
| Dividir por **200** en vez de por **0,200** en la molaridad | La **M va en LITROS**. Siempre |
| Poner la **masa** de solvente en la fracción molar | Hay que pasarla a **MOLES**: ÷ 18,02 |
| Fracción molar con denominador $n_{sv}$ solo | Van **los dos**: $n_{sto}+n_{sv}$ |
| Molalidad sobre la masa de **solución** | La molalidad va **SOBRE EL SOLVENTE**, en kg |
| Sumar o promediar **molaridades** al mezclar | Sumar **MOLES** y dividir por el **volumen total** |
| $[\text{NO}_3^-] = [\text{Fe(NO}_3)_3]$ | **× 3.** El subíndice de la fórmula **multiplica** al ion |
| "1:25 = 1 parte + 25 de agua" | **1 parte llevada a 25 TOTALES** = 1 + 24 de agua |
| Dos diluciones 1:10 = 1:20 | Los factores se **MULTIPLICAN**: **1:100** |
| Confundir $V_F$ con el agua agregada | Agua agregada $= V_F - V_0$ |
| Contestar el agua **total** cuando piden la **agregada** (ej. 19) | **Restar** la que ya había: $m_{sv}^F - m_{sv}^0$ |
| Volúmenes aditivos por defecto | **NO son aditivos**. 1 L H₂O + 1 L EtOH = **1,93 L**. Sólo si el enunciado lo aclara |
| Olvidarse de **restar** el sobrante en solubilidad | precipitado = cantidad − máx |
| Escalar mal la solubilidad | Las tablas van por **100 g de SOLVENTE** (o por L, ¡leer la unidad!) |
| "Más sensible a T" = la curva más **alta** | Es la de mayor **PENDIENTE**. NaCl es plana; NH₄NO₃ es empinada |
| "Molés el sólido → se disuelve más" | Se disuelve **MÁS RÁPIDO**. El máximo lo fija la **solubilidad** |
| "Sobresaturada = tiene precipitado" | Al revés: está **TODO disuelto**, de forma **metaestable** |
| "Tiré de más → queda sobresaturada" | Queda **SATURADA + precipitado** |
| Tomar **210 mg de NaCl** como 210 mg de Na | × 22,99/58,44 = **82,6 mg de Na** |
| Confundir **ppb con ppm** | 700 ppb = **0,7 ppm**. Factor 1000 |
| ppm → M sin justificar la aproximación | Hay que **decir** que se toma δ_sc ≈ 1,00 g/mL y **por qué** |
| Usar ppm ≈ mg/L en una solución **concentrada** | Sólo vale en **agua muy diluida** (δ ≈ 1) |
| "10 % v/v = 10 % m/m" | Sólo si $\delta_{sto} = \delta_{sc}$. Con etanol: 10 % v/v = **8,06 % m/m** |
| En una mezcla, dar el % de cada soluto en **su** solución de origen | Va sobre la **masa TOTAL de la mezcla**. Al mezclar, **todo se diluye** |
| Enrasar el NaOH **en caliente** | Es **exotérmico**: hay que **esperar a que enfríe** o la concentración queda alta |
| Disolver directo **en el matraz aforado** | Se disuelve en un **vaso** y se trasvasa con enjuagues |
| Agregar **agua sobre el ácido** | **ÁCIDO SOBRE AGUA**. Siempre |

---

# 📌 Fórmulas de la Serie 4 — todas juntas

**Las unidades**

$$\%\tfrac{m}{m} = \frac{m_{sto}}{m_{sc}}100 \quad \%\tfrac{m}{V} = \frac{m_{sto}}{V_{sc}}100 \quad \%\tfrac{V}{V} = \frac{V_{sto}}{V_{sc}}100 \quad M = \frac{n_{sto}}{V_{sc}(L)} \quad m = \frac{n_{sto}}{m_{sv}(kg)} \quad x_{sto} = \frac{n_{sto}}{n_{sto}+n_{sv}}$$

$$\text{ppm} = \frac{m_{sto}}{m_{sc}}10^6 \qquad \text{ppb} = \frac{m_{sto}}{m_{sc}}10^9 \qquad 1\ \% = 10^4\ \text{ppm} = 10^7\ \text{ppb}$$

**Los puentes**

$$\boxed{n = \frac{m}{Mr}} \qquad \boxed{\delta = \frac{m}{V}} \qquad \boxed{m_{sc} = m_{sto}+m_{sv}} \qquad \boxed{V_{sto}+V_{sv} \neq V_{sc}}$$

**Las conversiones entre unidades (ahorran medio ejercicio)**

$$\boxed{\%\tfrac{m}{V} = \%\tfrac{m}{m}\cdot\delta_{sc}\left(\tfrac{g}{mL}\right)} \qquad \boxed{M = \frac{\%\tfrac{m}{m}\cdot\delta_{sc}\cdot 10}{Mr}} \qquad \boxed{\%\tfrac{m}{V} = \frac{M\cdot Mr}{10}}$$

$$\boxed{\delta_{sc} = \frac{\%m/V}{\%m/m}} \qquad \boxed{\%\tfrac{m}{m} = \%\tfrac{V}{V}\cdot\frac{\delta_{sto}}{\delta_{sc}}} \qquad \boxed{\text{ppm} \approx \tfrac{mg}{L}\ \text{(agua diluida)}}$$

**Masa de un ion a partir de la sal**

$$\boxed{m_{ion} = m_{sal}\cdot\frac{n_{iones}\cdot Ar_{ion}}{Mr_{sal}}} \qquad\qquad \boxed{[\text{ion}] = \nu\cdot[\text{sal}]}$$

*(ν = subíndice del ion en la fórmula: Fe(NO₃)₃ 0,174 M → [NO₃⁻] = 3 × 0,174 = 0,522 M)*

**Preparación y diluciones**

$$\boxed{m_{sto} = M\cdot V_{sc}(L)\cdot Mr} \qquad \boxed{C_0V_0 = C_FV_F} \qquad \boxed{V_{agua} = V_F - V_0}$$

$$\boxed{1{:}n \;\Rightarrow\; C_F = \frac{C_0}{n},\quad V_F = n\cdot V_0,\quad \text{1 de sc} + (n-1)\ \text{de agua}} \qquad \boxed{f_{total} = n_1\cdot n_2\cdots}$$

**Mezclas**

$$\boxed{M_F = \frac{M_1V_1+M_2V_2}{V_1+V_2}}\ \text{(mismo soluto)} \qquad\qquad \boxed{M_i = \frac{n_i}{V_{total}}}\ \text{(cada soluto, si son distintos)}$$

**Diluir en molalidad**

$$\boxed{m_{sv}^{final} = m_{sv}^{inicial}\cdot\frac{m_{molal}^{inicial}}{m_{molal}^{final}}} \qquad\qquad \boxed{m_{H_2O\ agregada} = m_{sv}^{final} - m_{sv}^{inicial}}$$

**Solubilidad**

$$\boxed{m_{max} = S\cdot\frac{m_{sv}}{100}}\ \text{[S en g/100 g]} \qquad \boxed{m_{max} = S\cdot V_{sv}}\ \text{[S en g/L]}$$

$$\boxed{m_{precipitado} = m_{agregada} - m_{max}} \qquad \begin{cases} c < S & \text{INSATURADA} \\ c = S & \text{SATURADA} \\ c > S & \text{SOBRESATURADA (metaestable)} \end{cases}$$

$$\boxed{S_{gas} = k_H\cdot P_{gas}}\ \text{(Henry)} \qquad \begin{cases}\text{sólidos: } S\uparrow \text{ con } T\uparrow \ \text{(casi siempre)} \\ \text{gases: } S\downarrow \text{ con } T\uparrow \ \text{(siempre)}\end{cases}$$

**Interpolación lineal en una tabla de solubilidad**

$$\boxed{T = T_1 + (T_2-T_1)\cdot\frac{S - S_1}{S_2 - S_1}}$$

---

> **Última recomendación:** de toda la serie, los tres ejercicios que más rinde tener resueltos de memoria son el **9 de casa** (las cuatro unidades sobre el mismo solvente), el **8 de clase** (una solución expresada de cinco maneras) y el **17 de clase** (mezcla + iones + preparación). Entre esos tres está el 90 % de lo que se puede preguntar de este tema.
