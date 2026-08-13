# SERIE 3 — Resuelta paso a paso

**Química General — ECyT / UNSAM · 2C 2026**
**Tema:** Interacciones intermoleculares

> Interacciones ion–ion, ion–dipolo y dipolo–dipolo · Polarizabilidad · Fuerzas dispersivas o de London · Puentes de hidrógeno · Relación entre fuerzas intermoleculares y puntos de fusión y ebullición · Criterios de solubilidad.

**Cómo usar este archivo:** cada ejercicio tiene el **procedimiento** desarrollado y, cuando el enunciado pide justificar, un bloque **📝 Respuesta tipo parcial** listo para copiar.

> ⚠️ **Esta serie NO se puede hacer sin la Serie 2.** Todo ejercicio arranca igual: **Lewis → TRePEV → ¿polar? → ¿qué fuerza actúa? → propiedad física**. Si no sabés sacar la geometría, no podés contestar nada acá.
> Teoría: `Clase4/Clase4-Explicacion-Completa.md` (polaridad en `Clase3/`).

---

## 📋 Datos que se usan en toda la serie

### 🔑 El método, de punta a punta

```
1. ¿Es IÓNICO / METÁLICO / covalente de red?
       SÍ → ion–ion (250 kJ/mol) → sólido, T_f altísima. FIN.
       NO → es molecular, seguir.
2. Lewis → TRePEV → geometría MOLECULAR
3. ¿μ ≠ 0?  (geometría simétrica + sustituyentes iguales ⇒ μ = 0)
       NO → NO POLAR → sólo LONDON
       SÍ → POLAR → dipolo–dipolo + London
4. ¿Tiene H unido a F, O o N?
       SÍ → sumar UNIÓN HIDRÓGENO (la más fuerte de las moleculares)
5. Para ORDENAR puntos de ebullición:
       a) ¿alguna tiene unión H?  → ésa arriba (a masa comparable)
       b) ¿masas / nº de e⁻ MUY distintos? → manda LONDON
       c) ¿masas parecidas?               → manda la POLARIDAD
       d) ¿todo igual?                    → manda la FORMA
```

⚠️ **London está en TODAS las sustancias moleculares**, polares y no polares. Lo que cambia es si además hay algo más.

### Tabla de magnitudes (hay que saberla de memoria)

| Interacción | Entre quiénes | Depende de | Magnitud |
|---|---|---|---|
| **Ion – Ion** | ion + ion | $Q_1Q_2$ | **250 kJ/mol** |
| **Unión H** | dador F/O/N–H + aceptor F/O/N | — | **20 kJ/mol** |
| **Ion – Dipolo** | ion + polar | $Q_1\mu_2$ | **15 kJ/mol** |
| **Ion – Dipolo inducido** | ion + no polar | $Q_1\alpha_2$ | **10 kJ/mol** |
| **London (dispersivas)** | **todas** | $\alpha_1\alpha_2$ | **5 kJ/mol** |
| **Dipolo – Dipolo** | polar + polar | $\mu_1\mu_2$ | **0,6 kJ/mol** |
| **Dipolo – Dipolo inducido** | polar + no polar | $\mu_1\alpha_2$ | **< 1 kJ/mol** |

Referencia: agitación térmica a 25 °C ≈ **2,5 kJ/mol** · **enlace covalente = 150–1000 kJ/mol**

⚠️ **London (5) > dipolo–dipolo (0,6).** La mitad de esta serie se resuelve con eso.

### Electronegatividades (Pauling)

| F | O | N, Cl | Br | C, I, S, Se | H, P | Si | Ca, K |
|---|---|---|---|---|---|---|---|
| **4,0** | **3,5** | **3,0** | 2,8 | **2,5** | **2,1** | 1,8 | 1,0 / 0,8 |

### Nº de electrones (proxy de la polarizabilidad α)

| Molécula | e⁻ | Molécula | e⁻ | Molécula | e⁻ |
|---|---|---|---|---|---|
| H₂ | 2 | F₂ | 18 | CH₄ | 10 |
| He | 2 | Cl₂ | 34 | SiH₄ | 18 |
| Ar | 18 | Br₂ | 70 | CCl₄ | **74** |
| H₂O / NH₃ | 10 | I₂ | **106** | CH₂Cl₂ | 42 |
| H₂S / PH₃ / HCl | 18 | ICl | 70 | CS₂ | 38 |

### Puntos de ebullición que aparecen en la serie (°C)

| Grupo 14 | | Grupo 15 | | Grupo 16 | | Grupo 17 | |
|---|---|---|---|---|---|---|---|
| CH₄ | **−161** | NH₃ | **−33** | H₂O | **100** | HF | **19,5** |
| SiH₄ | −111 | PH₃ | −87,8 | H₂S | −60 | HCl | −85 |
| GeH₄ | −88 | AsH₃ | −62 | H₂Se | −41 | HBr | −67 |
| SnH₄ | −52 | SbH₃ | −17 | H₂Te | −2 | HI | −35 |

Otros: He −269 · Ar −186 · H₂ −253 · CCl₄ **+77** · CH₂O −19 · CaCl₂ 1935 · NaCl 1465

---
---

# PROBLEMAS PARA DISCUTIR EN CLASE

---

## Ejercicio 1 — Completar con la opción correcta

### a) Las fuerzas de dispersión o de London están presentes en _____ sustancia/s molecular/es

### ✅ Respuesta: **TODAS**

**Por qué.** London nace de los **dipolos instantáneos**: la nube electrónica de cualquier molécula fluctúa a cada instante y, por un momento, queda más densa de un lado que del otro. Ese dipolo transitorio induce otro en la vecina y las dos se atraen. Como **toda** molécula tiene electrones y toda nube electrónica fluctúa, **no existe sustancia molecular sin London**.

⚠️ El error clásico es leer "London = fuerza de las moléculas no polares". Lo correcto es:

| | ¿Tiene London? | ¿Tiene dipolo–dipolo? |
|---|---|---|
| Molécula **no polar** (CH₄, I₂, Ar) | **Sí** — y es la **única** que tiene | No |
| Molécula **polar** (HCl, H₂O) | **Sí** | Sí, además |

En moléculas grandes y polares, London suele ser **más fuerte** que el dipolo–dipolo (5 vs 0,6 kJ/mol).

---

### b) Las fuerzas dipolares sólo existen en sustancias cuyas moléculas son _________

### ✅ Respuesta: **POLARES**

**Por qué.** La interacción dipolo–dipolo es la atracción entre **dipolos permanentes** ($E \propto \mu_1\mu_2/d^3$). Si $\mu = 0$, el producto es cero: no hay nada que interactuar. Y $\mu \ne 0$ es exactamente la definición de molécula polar.

⚠️ Ojo con el orden lógico: **enlaces polares ≠ molécula polar**. El CCl₄ tiene cuatro enlaces C–Cl polares (ΔEN = 0,5) y **no** tiene fuerzas dipolares, porque la geometría tetraédrica cancela los cuatro vectores.

---

### c) Las uniones puente de hidrógeno… H unido a otro átomo muy electronegativo, como ____, ____ y ____

### ✅ Respuesta: **FLÚOR (F), OXÍGENO (O) y NITRÓGENO (N)**

**Por qué son ésos tres y no otros.** Hacen falta las **dos** condiciones a la vez:

| Condición | Qué garantiza |
|---|---|
| **EN muy alta** (F 4,0 · O 3,5 · N 3,0) | El enlace X–H queda muy polarizado: el H queda casi como un protón desnudo (δ⁺ enorme) |
| **Átomo CHICO** (período 2) | La carga δ⁻ queda **concentrada**, no dispersa, y el H puede acercarse mucho |

⚠️ **El Cl tiene EN = 3,0, igual que el N, y NO hace unión H.** Falla la segunda condición: es un átomo grande, la carga negativa queda repartida en un volumen mucho mayor y la atracción se diluye. Por eso el HCl hierve a −85 °C y el HF a +19,5 °C.

**Recordá la regla de los DOS roles:**

$$\boxed{\text{Unión H} \iff \underbrace{\text{H unido a F, O o N}}_{\textbf{DADOR}} \;+\; \underbrace{\text{F, O o N con par libre}}_{\textbf{ACEPTOR}}}$$

Ejemplo de que hace falta el dador: el **éter CH₃OCH₃** tiene O con pares libres (aceptor ✓) pero ningún H sobre el O (dador ❌) → **no hace unión H consigo mismo** (sí con el agua).

---

## Ejercicio 2 — Verdadero o Falso

> *"Las moléculas de SeF₄ y SiF₄ presentan sólo fuerzas de London porque tienen μ = 0."*

### ✅ Respuesta: **FALSO**

El error está en meter las dos moléculas en la misma bolsa. **Parecen gemelas por la fórmula AB₄, pero el átomo central tiene distinta cantidad de electrones de valencia y eso cambia todo.**

### Procedimiento — hay que hacer los dos Lewis

**SiF₄** — Si es del grupo 14 → **4 e⁻ de valencia**

$$e^-_{tot} = 4 + 4\times 7 = 32 \quad\Rightarrow\quad 16 \text{ pares}$$

4 enlaces Si–F (4 pares) + 4 F × 3 pares libres (12 pares) = 16 ✓. **No sobra nada para el Si.**

| | |
|---|---|
| Grupos electrónicos en el central | **4** (4 enlaces + **0** pares libres) |
| Geometría electrónica | Tetraédrica |
| Clase TRePEV | **AB₄** |
| Geometría **molecular** | **Tetraédrica** |
| ¿Sustituyentes iguales? | Sí (4 F) |
| **μ** | **= 0 → NO POLAR** ✓ |

**SeF₄** — Se es del grupo 16 → **6 e⁻ de valencia**

$$e^-_{tot} = 6 + 4\times 7 = 34 \quad\Rightarrow\quad 17 \text{ pares}$$

4 enlaces Se–F (4 pares) + 4 F × 3 pares libres (12 pares) = 16 → **sobra 1 par, que va al Se**.

| | |
|---|---|
| Grupos electrónicos en el central | **5** (4 enlaces + **1 par libre**) |
| Geometría electrónica | **Bipirámide trigonal** (el par libre va en **ECUATORIAL**) |
| Clase TRePEV | **AB₄E** |
| Geometría **molecular** | **BALANCÍN** (*seesaw*) |
| **μ** | **≠ 0 → POLAR** (μ ≈ 1,78 D) |

> El Se es del **período 4** → puede tener **octeto expandido** (10 e⁻ a su alrededor). El Si podría, pero acá no le hace falta.

```
      SiF₄  (tetraédrico)              SeF₄  (balancín)
                                             F
           F                                 |
           |                          F —— Se ·· (par libre ecuatorial)
          Si                                 |  ↘
        / | \                                F    F
      F   F  F                         asimétrico → μ ≠ 0
   μ = 0 (los 4 vectores cancelan)
```

### ✅ Conclusión

| Molécula | Geometría molecular | μ | Interacciones |
|---|---|---|---|
| **SiF₄** | Tetraédrica (AB₄) | **0** | **Sólo London** ✓ |
| **SeF₄** | **Balancín (AB₄E)** | **≠ 0** | **Dipolo–dipolo + London** ❌ |

📝 **Respuesta tipo parcial**

> **FALSO.** La afirmación es correcta para el SiF₄ pero no para el SeF₄.
>
> El **Si** pertenece al grupo 14 y aporta 4 electrones de valencia: en el SiF₄ los 32 electrones totales se agotan en los 4 enlaces y en los pares libres de los flúor, de modo que el átomo central **no queda con pares libres**. Es AB₄, geometría molecular **tetraédrica**, con los cuatro sustituyentes iguales: los cuatro vectores μ de enlace se cancelan y **μ = 0**. Al ser no polar, sus únicas interacciones son las **de London**.
>
> El **Se** pertenece al grupo 16 y aporta 6 electrones de valencia: en el SeF₄ hay 34 electrones totales y, después de armar los 4 enlaces y completar los octetos de los flúor, **sobra un par libre sobre el Se**. Hay entonces **5 grupos electrónicos** (4 enlaces + 1 par libre): geometría electrónica de bipirámide trigonal con el par libre en posición ecuatorial, y geometría molecular de **balancín**. Esa geometría es **asimétrica**, los vectores **no se cancelan** y la molécula resulta **polar (μ ≈ 1,78 D)**.
>
> Por lo tanto el SeF₄ presenta, además de London, **interacciones dipolo–dipolo**.

⚠️ **La trampa del ejercicio:** dos fórmulas con la misma "forma" (AB₄) pero átomos centrales de **grupos distintos**. Nunca deduzcas la geometría de la fórmula: **hacé siempre el Lewis y contá los pares libres del central.**

---

## Ejercicio 3 — Asociar compuestos a sentencias

> **Compuestos:** Dióxido de azufre · CH₂Cl₂ · H₂O · Tricloruro de fósforo · Tetrafluoruro de xenón · SiCl₄ · NH₃

### Paso 0 — Traducir los nombres y armar la tabla completa

| Nombre | Fórmula | Grupos en el central | Clase | Geometría molecular | μ | Interacciones |
|---|---|---|---|---|---|---|
| Dióxido de azufre | **SO₂** | 3 (2 enl. + 1 p.l.) | AB₂E | **Angular** | ≠0 | dip–dip + London |
| Diclorometano | **CH₂Cl₂** | 4 (4 enl.) | AB₂C₂ | **Tetraédrica** | ≠0 | dip–dip + London |
| Agua | **H₂O** | 4 (2 enl. + 2 p.l.) | AB₂E₂ | **Angular** | ≠0 | **unión H** + dip–dip + London |
| Tricloruro de fósforo | **PCl₃** | 4 (3 enl. + 1 p.l.) | AB₃E | **Pirámide trigonal** | ≠0 | dip–dip + London |
| Tetrafluoruro de xenón | **XeF₄** | 6 (4 enl. + 2 p.l.) | AB₄E₂ | **Plana cuadrada** | **0** | **sólo London** |
| Tetracloruro de silicio | **SiCl₄** | 4 (4 enl.) | AB₄ | **Tetraédrica** | **0** | **sólo London** |
| Amoníaco | **NH₃** | 4 (3 enl. + 1 p.l.) | AB₃E | **Pirámide trigonal** | ≠0 | **unión H** + dip–dip + London |

### a) Tetraédrica y **únicamente** interacciones de London

**Candidatos tetraédricos:** CH₂Cl₂ y SiCl₄.
El CH₂Cl₂ tiene **sustituyentes distintos** (2 H + 2 Cl) → los vectores **no** se cancelan → polar → tiene dipolo–dipolo. Queda afuera.

### ✅ **SiCl₄**

AB₄ con los cuatro sustituyentes iguales → geometría tetraédrica **perfecta** → μ = 0 aunque cada enlace Si–Cl sea polar (ΔEN = |1,8 − 3,0| = 1,2). Sin dipolo permanente y sin H sobre F/O/N: **sólo London**.

⚠️ El XeF₄ también tiene μ = 0 y sólo London, pero su geometría es **plana cuadrada**, no tetraédrica. Es el distractor del ítem.

### b) Tetraédrica con dipolo–dipolo **y** London

### ✅ **CH₂Cl₂**

4 grupos, 0 pares libres → tetraédrica. Pero los sustituyentes son **distintos**: los dos vectores C–Cl (ΔEN = 0,5, apuntando al Cl) no tienen con qué cancelarse contra los dos C–H (ΔEN = 0,4, apuntando al C). Resultante **≠ 0** → polar.
Tiene H, pero unidos al **C** → **no hay unión H**. Queda: **dipolo–dipolo + London**. ✓

### c) Pirámide trigonal con puente H + dipolo–dipolo + London

**Candidatos piramidales:** PCl₃ y NH₃.
El **PCl₃ no tiene ningún H** → imposible que haga puente de hidrógeno. Queda afuera.

### ✅ **NH₃**

AB₃E → pirámide trigonal, polar (μ = 1,47 D), con **H unido a N** (dador ✓) y el **par libre del N** como aceptor ✓ → hace **unión hidrógeno**. Y como toda molécula polar, también dipolo–dipolo y London. ✓

### 📊 Resumen de la asociación

| Sentencia | Compuesto |
|---|---|
| a) Tetraédrica + sólo London | **SiCl₄** |
| b) Tetraédrica + dip–dip + London | **CH₂Cl₂** |
| c) Pirámide trigonal + puente H + dip–dip + London | **NH₃** |

**Los cuatro que sobran, y por qué no entran:**

| Compuesto | Por qué no |
|---|---|
| **SO₂** | Es **angular**, no tetraédrica ni piramidal |
| **H₂O** | Hace puente H, pero es **angular**, no piramidal |
| **PCl₃** | Es piramidal, pero **no tiene H** → sin puente H |
| **XeF₄** | Sólo London, pero es **plana cuadrada**, no tetraédrica |

⚠️ **La trampa del ejercicio son los pares "casi":** SiCl₄ vs XeF₄ (los dos no polares, distinta geometría) y NH₃ vs PCl₃ (los dos piramidales, sólo uno con puente H). Los distractores están puestos a propósito.

---

## Ejercicio 4 — Dipolo permanente vs inducido vs transitorio

### ✅ Los tres, en una tabla

| | **Dipolo PERMANENTE** | **Dipolo INDUCIDO** | **Dipolo TRANSITORIO** (instantáneo) |
|---|---|---|---|
| **Qué es** | Separación de carga **fija** de la molécula | Separación de carga **provocada desde afuera** | Separación de carga **espontánea y fugaz** |
| **Causa** | ΔEN entre los átomos **+ geometría asimétrica** | Un **campo eléctrico externo**: un ion vecino o un dipolo permanente vecino | **Fluctuación estadística** de la nube electrónica |
| **¿Necesita algo cerca?** | **No**, existe sola | **Sí** — si se va la fuente, desaparece | **No** |
| **¿Cuánto dura?** | Siempre | Mientras dure el campo | **~10⁻¹⁵ s** (aparece y se va) |
| **De qué depende** | **μ** (momento dipolar) | **α** (polarizabilidad) y la intensidad del campo | **α** |
| **Qué interacción origina** | dipolo–dipolo · ion–dipolo · unión H | ion–dipolo inducido · dipolo–dipolo inducido | **LONDON (dispersivas)** |
| **En qué moléculas** | **Sólo polares** | Cualquiera, sobre todo **no polares grandes** | **Todas** |

### La fórmula que une a los dos últimos con el primero

$$\boxed{\mu_{\text{inducido}} = \alpha \cdot E}$$

El dipolo inducido es **proporcional a la polarizabilidad** de la molécula que se deforma y al **campo** que la deforma. Por eso el I₂ (α enorme, 106 e⁻) se deforma muchísimo y el He (α mínima, 2 e⁻) casi nada.

### Ejemplos

**① Dipolo permanente — HCl**

```
   H —— Cl
  δ+      δ-        μ = 1,08 D  (fijo, siempre está)
   →→→→→→
```
ΔEN = |2,1 − 3,0| = 0,9 y la molécula es diatómica (no hay nada que cancele) → dipolo permanente. Otros: **H₂O** (1,85 D), **NH₃** (1,47 D), **SO₂** (1,63 D).

**② Dipolo inducido — Na⁺ frente a Cl₂**

```
ANTES:      Na⁺        ( Cl—Cl )        nube simétrica, μ = 0
DESPUÉS:    Na⁺  ←   (Cl—Cl)            el catión ATRAE los e⁻ hacia sí
                     δ-    δ+           μ_ind = α·E  ≠ 0  →  se atraen
```
El Cl₂ **por sí solo es no polar**. El campo del Na⁺ le corre la nube y le crea un dipolo. Ésta es la interacción **ion–dipolo inducido** (~10 kJ/mol). Es lo que explica que un gas no polar como el Ar se disuelva **algo** en agua salada, y es el mecanismo del ítem c) del Ejercicio 5.
La versión más débil es **dipolo–dipolo inducido**: el HCl (permanente) induciendo un dipolo en el Cl₂ (< 1 kJ/mol).

**③ Dipolo transitorio — Ar con Ar (o I₂ con I₂)**

```
instante t₁:   (Ar)  la nube se corre sola →  δ- δ+   →  induce en la vecina  δ- δ+  →  ATRACCIÓN
instante t₂:   la fluctuación se invierte, y vuelve a haber atracción
promedio:      el dipolo MEDIO es cero, pero la ENERGÍA de atracción NO
```

Éste es el punto fino: el dipolo instantáneo **promediado en el tiempo da cero**, pero la interacción **no** se promedia a cero, porque el dipolo inducido en la vecina siempre está **correlacionado** con el que lo causó (siempre se orientan de forma atractiva, nunca repulsiva). Por eso London es **siempre atractiva** y está en **todas** las sustancias.

📝 **Respuesta tipo parcial**

> El **dipolo permanente** es una propiedad intrínseca de la molécula: surge de la diferencia de electronegatividad entre los átomos junto con una geometría que no cancela los vectores, y existe de manera continua aunque la molécula esté aislada. Se cuantifica con el momento dipolar μ. Ejemplo: **HCl**, **H₂O**.
>
> El **dipolo inducido** no es propio de la molécula: aparece cuando una especie cargada o un dipolo permanente vecino genera un campo eléctrico que **deforma** su nube electrónica, y desaparece al retirarse esa fuente. Su magnitud es μ_ind = α·E, es decir depende de la **polarizabilidad** de la molécula. Ejemplo: el **Cl₂ frente a un catión Na⁺** (interacción ion–dipolo inducido).
>
> El **dipolo transitorio o instantáneo** también es momentáneo, pero **no requiere ninguna causa externa**: es una fluctuación estadística espontánea de la nube electrónica, que en un instante dado queda asimétrica. Dura del orden de 10⁻¹⁵ s. Ese dipolo instantáneo induce uno correlacionado en la molécula vecina, y esa correlación es el origen de las **fuerzas de London**, presentes en **todas** las sustancias moleculares. Ejemplo: **Ar con Ar**, **I₂ con I₂**.

---

## Ejercicio 5 — Interacciones principales en cada sistema

### 🔎 Cómo se piensa

En un sistema con **una sola** sustancia, la pregunta es qué une esas moléculas entre sí. En una **solución** hay que mirar **tres** pares: soluto–soluto, solvente–solvente y **soluto–solvente** (que es el que decide la solubilidad).

### a) Agua líquida

| | |
|---|---|
| Especies | Sólo H₂O |
| Geometría | **Angular** (AB₂E₂), polar, μ = 1,85 D |
| H sobre O ✓ + par libre en O ✓ | **Hay dador y aceptor** |

### ✅ **UNIÓN HIDRÓGENO** (principal, ~20 kJ/mol) + dipolo–dipolo + London

Cada molécula puede formar hasta **4** uniones H (2 H dadores + 2 pares libres aceptores) → **red tridimensional**. Es lo que explica todas las anomalías del agua: T_eb = 100 °C, calor específico altísimo, y el **hielo menos denso que el agua líquida**.

### b) Argón gaseoso

| | |
|---|---|
| Especies | Átomos de Ar (gas noble, **monoatómico**) |
| ¿Polar? | No tiene enlaces → **no hay μ posible** |

### ✅ **SÓLO LONDON** (dispersivas)

Los átomos de Ar son esferas simétricas. Únicamente los **dipolos instantáneos** los mantienen juntos. Con 18 e⁻ la α es chica → London débil → **T_eb = −186 °C**, por eso es gas.

### c) Solución acuosa de argón

| Par | Interacción |
|---|---|
| H₂O — H₂O (solvente) | **Unión hidrógeno** |
| Ar — Ar (soluto) | London |
| **Ar — H₂O (la que importa)** | **DIPOLO – DIPOLO INDUCIDO** |

### ✅ La interacción soluto–solvente es **dipolo–dipolo inducido**

El agua tiene dipolo **permanente**; el Ar es no polar pero **polarizable**. El campo del dipolo del agua le induce un dipolo al Ar y se atraen — pero es la interacción **más débil de la tabla (< 1 kJ/mol)**.

⚠️ **Consecuencia:** para meter un átomo de Ar entre las aguas hay que **romper uniones H de 20 kJ/mol** y a cambio sólo se ganan **< 1 kJ/mol**. El balance es malísimo → **el argón es prácticamente insoluble en agua**. Éste es exactamente el razonamiento de los ejercicios de solubilidad (10 y 8-de-casa).

### d) Cloruro de sodio sólido

| | |
|---|---|
| Especies | **Na⁺ y Cl⁻** — ΔEN = \|0,9 − 3,0\| = **2,1 > 1,7** → **iónico** |
| ¿Hay moléculas? | **NO.** Es una **red cristalina**; NaCl es fórmula mínima |

### ✅ **ION – ION** (electrostática, ~250 kJ/mol)

$$E \propto \frac{Q_1 \cdot Q_2}{d}$$

La más fuerte de todas las interacciones de la tabla. Cada Na⁺ está rodeado por 6 Cl⁻ y viceversa, en las tres dimensiones. Para fundirlo hay que romper **la red entera** → **T_f = 801 °C**, **T_eb = 1465 °C**.

⚠️ A un sólido iónico **no le preguntes geometría molecular ni polaridad**: no hay molécula.

### e) Solución acuosa de cloruro de sodio

| Par | Interacción |
|---|---|
| H₂O — H₂O | Unión hidrógeno |
| Na⁺ — Cl⁻ | Ion–ion (**se rompe** al disolverse) |
| **Na⁺ — H₂O y Cl⁻ — H₂O** | **ION – DIPOLO** (~15 kJ/mol) |

### ✅ La interacción soluto–solvente es **ION – DIPOLO** (hidratación)

```
      Na⁺  rodeado de aguas:            Cl⁻  rodeado de aguas:
         δ-  O                              δ+  H
             \                                 /
          H   H  ──→ el O (δ-) APUNTA         O ── el H (δ+) APUNTA
                     al catión                 \      al anión
```

Cada ion queda envuelto en una **esfera de hidratación**: las aguas se orientan con el **O (δ⁻) hacia el catión** y con los **H (δ⁺) hacia el anión**. Con ~6 aguas por ion, la suma de esas interacciones de 15 kJ/mol **sí** compensa la ruptura de la red iónica → **el NaCl se disuelve bien en agua**.

### 📊 Resumen del ejercicio 5

| Sistema | Interacción **principal** | Magnitud |
|---|---|---|
| **a)** Agua líquida | **Unión hidrógeno** | 20 kJ/mol |
| **b)** Argón gaseoso | **London** (única) | 5 kJ/mol |
| **c)** Ar(ac) | **Dipolo – dipolo inducido** | < 1 kJ/mol → **casi insoluble** |
| **d)** NaCl sólido | **Ion – ion** | 250 kJ/mol |
| **e)** NaCl(ac) | **Ion – dipolo** | 15 kJ/mol → **muy soluble** |

💡 **Comparar c) con e) es la clave del ejercicio.** Los dos son "algo disuelto en agua", pero uno se disuelve y el otro no. La diferencia es **con qué se paga** la ruptura de las uniones H del agua: con 15 kJ/mol (ion–dipolo) alcanza; con < 1 kJ/mol (dipolo–dipolo inducido) no.

---

## Ejercicio 6 — Orden de T_eb para He, Ar y CH₄

> **Dato:** polarizabilidad **He < Ar < CH₄**

### Procedimiento

**Paso 1 — ¿Son polares?**

| Especie | Estructura | μ |
|---|---|---|
| **He** | Átomo monoatómico | No aplica → **0** |
| **Ar** | Átomo monoatómico | No aplica → **0** |
| **CH₄** | **AB₄ tetraédrica**, 4 sustituyentes iguales | **0** (los 4 vectores cancelan) |

**Las tres son no polares.** No hay dipolo–dipolo, no hay unión H.

**Paso 2 — Entonces la única fuerza es London.**

$$E_{\text{London}} \propto \frac{\alpha_1 \cdot \alpha_2}{d^6}$$

**Paso 3 — London ∝ α, y el enunciado nos regala el orden de α.**

$$\alpha: \;\text{He} < \text{Ar} < \text{CH}_4 \quad\Longrightarrow\quad E_{\text{London}}: \;\text{He} < \text{Ar} < \text{CH}_4$$

**Paso 4 — Más fuerza intermolecular ⇒ más energía para separar las partículas ⇒ mayor T_eb.**

### ✅ Respuesta

$$\boxed{T_{eb}(\text{He}) \;<\; T_{eb}(\text{Ar}) \;<\; T_{eb}(\text{CH}_4)}$$

**Verificación con los valores reales:**

| | α (Å³) | e⁻ | **T_eb (°C)** |
|---|---|---|---|
| **He** | 0,20 | 2 | **−269** |
| **Ar** | 1,64 | 18 | **−186** |
| **CH₄** | 2,59 | 10 | **−161** |

⚠️⚠️ **La trampa escondida de este ejercicio.** Fijate en la columna de electrones: el **CH₄ tiene 10 e⁻ y el Ar tiene 18**. Si hubieras usado el atajo de siempre ("más electrones ⇒ más London") habrías puesto el CH₄ **abajo** del Ar y te equivocabas.

**Por qué falla el atajo acá:** el nº de electrones es sólo un *proxy* de la polarizabilidad. Lo que realmente cuenta es **cuán deformable** es la nube. El Ar tiene sus 18 e⁻ apretados alrededor de un solo núcleo con Z = 18 que los sujeta fuerte; el CH₄ tiene 10 e⁻ pero repartidos en un **volumen molecular mucho mayor**, en enlaces C–H difusos, sujetos por núcleos con Z chico. Nube más grande y más suelta = **más polarizable**.

💡 **Por eso el enunciado te da la polarizabilidad de entrada:** cuando te la dan, **usá α y no el nº de electrones**. El nº de electrones sólo sirve como estimación dentro de una **misma familia** (F₂ < Cl₂ < Br₂ < I₂, o He < Ne < Ar < Kr < Xe).

📝 **Respuesta tipo parcial**

> Las tres especies son **no polares**: el He y el Ar son gases nobles monoatómicos y el CH₄, aunque tiene enlaces C–H levemente polares, posee geometría **tetraédrica** con cuatro sustituyentes iguales, por lo que los vectores de momento dipolar se cancelan y μ = 0.
>
> En consecuencia, la **única** interacción intermolecular presente en las tres es la **dispersiva o de London**, cuya intensidad es proporcional al producto de las polarizabilidades: E ∝ α₁α₂/d⁶.
>
> Como el enunciado indica que α aumenta en el orden **He < Ar < CH₄**, las fuerzas de London aumentan en ese mismo orden, y por lo tanto también la energía necesaria para separar las partículas al pasar al estado gaseoso:
>
> **T_eb(He) < T_eb(Ar) < T_eb(CH₄)** (−269 °C < −186 °C < −161 °C).

---

## Ejercicio 7 — Ordenar T_eb creciente: CH₄, CH₂O, H₂O

### Paso 1 — Lewis, geometría y polaridad de cada una

| | **CH₄** | **CH₂O** (formaldehído) | **H₂O** |
|---|---|---|---|
| e⁻ de valencia | 4 + 4 = 8 → 4 pares | 4 + 2 + 6 = 12 → 6 pares | 6 + 2 = 8 → 4 pares |
| Central | C | C | O |
| Grupos electrónicos | 4 (4 enlaces) | **3** (2 C–H + **1 C=O**) | 4 (2 enlaces + **2 p.l.**) |
| Clase TRePEV | AB₄ | AB₂C | AB₂E₂ |
| Geometría molecular | **Tetraédrica** | **Plana trigonal** | **Angular** |
| Sustituyentes | 4 iguales (H) | **Distintos** (2 H + 1 O) | 2 iguales, pero **hay pares libres** |
| **μ** | **0 — NO POLAR** | **2,33 D — POLAR** | **1,85 D — POLAR** |

```
        H                    O                     O
        |                    ‖                    / \
    H—— C ——H            C            H     H
        |                  /   \
        H                 H     H            (angular, 104,5°)
    tetraédrica       plana trigonal
      μ = 0             μ ≠ 0                  μ ≠ 0
```

⚠️ En el CH₂O el **doble enlace C=O cuenta como UN solo grupo** electrónico → 3 grupos → plana trigonal, no tetraédrica.

### Paso 2 — ¿Quién hace unión hidrógeno?

$$\text{Unión H} \iff \text{H unido a F, O o N}$$

| | ¿Tiene H? | ¿Sobre qué átomo? | ¿Unión H? |
|---|---|---|---|
| **CH₄** | Sí (4) | **C** ❌ | **NO** |
| **CH₂O** | Sí (2) | **C** ❌ | **NO** ⚠️ |
| **H₂O** | Sí (2) | **O** ✓ | **SÍ** ✓ |

⚠️⚠️ **La trampa principal del ejercicio: el CH₂O tiene oxígeno, pero sus H están sobre el CARBONO.** Tiene **aceptor** (el O con sus pares libres) pero **no tiene dador** → **no hace unión H consigo mismo**. Es el mismo caso que el éter CH₃OCH₃. (Sí hace unión H **con el agua**, y por eso el formol es muy soluble.)

### Paso 3 — Aplicar el método

| | Masa (g/mol) | e⁻ | Interacciones | Fuerza dominante |
|---|---|---|---|---|
| **CH₄** | 16 | 10 | **Sólo London** (débil, pocos e⁻) | London ~5 |
| **CH₂O** | 30 | 16 | **Dipolo–dipolo + London** | dip–dip + London |
| **H₂O** | 18 | 10 | **Unión H + dip–dip + London** | **Unión H ~20** |

- **CH₄ es el más bajo:** es el único **no polar**, y encima el más liviano → sólo London floja.
- **H₂O es el más alto:** es el único con **unión hidrógeno**, la interacción molecular más fuerte (20 kJ/mol), y además forma una **red 3D** (hasta 4 uniones por molécula).
- **CH₂O queda en el medio:** polar (μ = 2,33 D, incluso mayor que el del agua) y más pesado que los dos, pero **sin unión H**. Su dipolo–dipolo no le alcanza para ganarle a la red de puentes del agua.

### ✅ Respuesta

$$\boxed{T_{eb}: \quad \text{CH}_4 \;<\; \text{CH}_2\text{O} \;<\; \text{H}_2\text{O}}$$

$$-161\,°\text{C} \;<\; -19\,°\text{C} \;<\; +100\,°\text{C}$$

📝 **Respuesta tipo parcial**

> El **CH₄** tiene geometría **tetraédrica** con cuatro sustituyentes iguales, por lo que μ = 0: es **no polar** y sus únicas interacciones son las de **London**, además débiles por su baja masa molar (16 g/mol) y su bajo número de electrones. Es el de menor punto de ebullición.
>
> El **CH₂O** tiene geometría **plana trigonal** (el doble enlace C=O cuenta como un solo grupo electrónico) con sustituyentes distintos, por lo que los vectores no se cancelan y la molécula es **polar** (μ = 2,33 D): presenta **dipolo–dipolo y London**. Sin embargo, **no forma uniones hidrógeno consigo misma**, porque si bien posee un oxígeno aceptor, **sus hidrógenos están unidos al carbono** y no al oxígeno: le falta el grupo dador.
>
> El **H₂O** tiene geometría **angular** y es polar, pero además tiene **H unido directamente al O** y pares libres sobre el O, es decir **dador y aceptor a la vez**: forma **uniones hidrógeno**, que son las interacciones intermoleculares más intensas entre moléculas neutras (~20 kJ/mol) y que además generan una red tridimensional de hasta cuatro uniones por molécula. Por eso es el de mayor punto de ebullición, muy por encima de lo que corresponde a su masa molar.
>
> Orden creciente: **CH₄ (−161 °C) < CH₂O (−19 °C) < H₂O (100 °C)**.

---

## Ejercicio 8 — El gráfico de T_eb vs período para los hidruros

> ⭐ **Éste es EL ejercicio integrador de la serie.** Un gráfico como éste sale en el parcial casi seguro.

### El gráfico, leído

```
 100 ┤ H₂O ●
     │      ╲╲
     │ HF ●   ╲╲                                    ● H₂Te
   0 ┤    ╲ ╲   ╲╲                        ● H₂Se  ●╱  HI
     │ NH₃ ●╲ ╲   ●─── H₂S             ●╱ HBr  ●╱  SbH₃
-100 ┤       ╲ ╲ ●─── HCl        ● GeH₄       ●    SnH₄
     │        ●PH₃            ●╱ AsH₃
     │  CH₄ ●╱  ● SiH₄
-200 ┤
     └───┬───────┬───────┬───────┬────
         2       3       4       5     ← PERÍODO
```

**Lo que salta a la vista:** el **grupo 14 (rojo) es una recta que sube parejo**, y los otros tres grupos suben también **pero con el primer punto (período 2) disparado hacia arriba**, fuera de la tendencia.

---

### a) Geometrías moleculares y polaridad de cada familia

| Grupo | Hidruros | e⁻ val. del central | Grupos electrón. | Clase | **Geometría molecular** | **μ** |
|---|---|---|---|---|---|---|
| **14** | CH₄, SiH₄, GeH₄, SnH₄ | 4 | 4 (4 enl. + 0 p.l.) | **AB₄** | **Tetraédrica** | **0 — NO POLARES** |
| **15** | NH₃, PH₃, AsH₃, SbH₃ | 5 | 4 (3 enl. + **1 p.l.**) | **AB₃E** | **Pirámide trigonal** | **≠ 0 — POLARES** |
| **16** | H₂O, H₂S, H₂Se, H₂Te | 6 | 4 (2 enl. + **2 p.l.**) | **AB₂E₂** | **Angular** | **≠ 0 — POLARES** |
| **17** | HF, HCl, HBr, HI | 7 | — (diatómicas) | AB | **Lineal** | **≠ 0 — POLARES** |

**Cómo salen los grupos electrónicos, sin memorizar:** el central aporta *n* e⁻ de valencia (= nº de grupo para representativos), usa uno por cada H y los que le sobran quedan de a pares.

| Grupo | e⁻ val. | H unidos | e⁻ sobrantes | Pares libres |
|---|---|---|---|---|
| 14 | 4 | 4 | 0 | **0** |
| 15 | 5 | 3 | 2 | **1** |
| 16 | 6 | 2 | 4 | **2** |
| 17 | 7 | 1 | 6 | **3** |

Todos tienen **4 grupos electrónicos** (geometría electrónica **tetraédrica**); lo que cambia es cuántos son pares libres, y eso define la geometría **molecular**.

⚠️ **El grupo 14 es el único no polar.** Es la clave de los ítems b), c) y f).

---

### b) Tendencia del grupo 14

**Los valores:** CH₄ **−161** < SiH₄ **−111** < GeH₄ **−88** < SnH₄ **−52**

Sube **monótonamente**, sin ninguna anomalía. Recta limpia.

**Por qué:**

| | CH₄ | SiH₄ | GeH₄ | SnH₄ |
|---|---|---|---|---|
| e⁻ totales | 10 | 18 | 36 | 54 |
| Masa (g/mol) | 16 | 32 | 77 | 123 |
| Tamaño del central | ↑ | ↑ | ↑ | ↑ |
| **α (polarizabilidad)** | **↑ ↑ ↑ ↑** | | | |

Los cuatro son **tetraédricos y no polares** (μ = 0) → la **única** interacción es **London**. Y London depende de α:

$$E_{\text{London}} \propto \alpha_1\alpha_2 \qquad \alpha \uparrow \;\text{con}\; n_{e^-} \uparrow \;\text{y}\; \text{tamaño} \uparrow$$

Al bajar en el grupo, el átomo central es más grande, hay más electrones y están **más alejados del núcleo** (menos atraídos, más difusos) → la nube se deforma con más facilidad → **dipolos instantáneos más grandes** → **London más intensa** → hace falta más energía para separar las moléculas → **T_eb ↑**.

📝 **Respuesta tipo parcial (b)**

> Los hidruros del grupo 14 tienen geometría **tetraédrica** con cuatro sustituyentes iguales, de modo que μ = 0 y **todos son no polares**. Su única interacción intermolecular es la de **London**, cuya intensidad es proporcional a la polarizabilidad α. Al descender en el grupo aumentan el número de electrones y el tamaño del átomo central, los electrones de valencia quedan más alejados del núcleo y la nube electrónica se vuelve **más difusa y más deformable**: α aumenta, las fuerzas de London se intensifican y el punto de ebullición **crece de manera monótona** de CH₄ a SnH₄.

---

### c) Por qué el grupo 14 tiene los T_eb **menores de cada período**

Comparemos dentro del **período 3**, donde las masas son casi iguales:

| Compuesto | Geometría | μ | e⁻ | Interacciones | **T_eb** |
|---|---|---|---|---|---|
| **SiH₄** | Tetraédrica | **0** | 18 | **Sólo London** | **−111** |
| **PH₃** | Pirámide trigonal | ≠ 0 | 18 | dip–dip + London | −87,8 |
| **H₂S** | Angular | ≠ 0 | 18 | dip–dip + London | −60 |
| **HCl** | Lineal | ≠ 0 | 18 | dip–dip + London | −85 |

**Los cuatro tienen 18 electrones** → London prácticamente **igual** en los cuatro. El desempate lo pone la **polaridad**, y el grupo 14 es **el único que no la tiene**.

### ✅ Los hidruros del grupo 14 son los únicos **no polares**, por lo que carecen de interacciones dipolo–dipolo y sólo cuentan con London — la fuerza más débil disponible. Los otros tres grupos suman dipolo–dipolo (y en el período 2, unión H) sobre la misma base de London.

⚠️ Notá que la tendencia **se cumple en todos los períodos**: CH₄ es el más bajo del período 2, SiH₄ del 3, GeH₄ del 4 y SnH₄ del 5. La curva roja va siempre por abajo.

---

### d) ¿La tendencia del grupo 14 es la misma para todos los grupos?

### ✅ **NO.**

| Grupo | ¿Tendencia monótona creciente? |
|---|---|
| **14** | **SÍ** — recta limpia de CH₄ a SnH₄ |
| **15** | **NO** — el NH₃ se sale hacia arriba |
| **16** | **NO** — el H₂O se sale **muchísimo** hacia arriba |
| **17** | **NO** — el HF se sale hacia arriba |

En los grupos 15, 16 y 17 la tendencia creciente **sí se cumple del período 3 en adelante** (PH₃ < AsH₃ < SbH₃ · H₂S < H₂Se < H₂Te · HCl < HBr < HI), pero **el primer miembro rompe el patrón**.

---

### e) ¿Qué diferencia se observa en los otros grupos?

### ✅ Los tres presentan un **pico anómalo en el período 2**

Los hidruros del período 2 (**NH₃, H₂O y HF**) hierven **mucho más alto** de lo que les correspondería por extrapolación de sus grupos:

| Grupo | Hidruro del período 2 | T_eb real | T_eb *esperado* extrapolando | **Anomalía** |
|---|---|---|---|---|
| **16** | **H₂O** | **+100 °C** | ≈ −80 °C | **+180 °C** ⭐ |
| **17** | **HF** | **+19,5 °C** | ≈ −90 °C | **+110 °C** |
| **15** | **NH₃** | **−33 °C** | ≈ −110 °C | **+77 °C** |
| **14** | CH₄ | −161 °C | ≈ −160 °C | **≈ 0** ✓ |

**Y el orden de la anomalía es H₂O > HF > NH₃.** Si la unión H sólo dependiera de la EN, el orden debería seguir a la EN (**F 4,0 > O 3,5 > N 3,0**) y el HF debería ganar. No pasa eso, y la explicación está en el ítem f).

**Comparación directa de lo insólito:** el H₂O (M = 18) hierve **160 °C más alto** que el H₂S (M = 34), que es **el doble de pesado**. Sin la unión H sería imposible.

---

### f) Justificación del comportamiento de los grupos 15 a 17

### ✅ **UNIÓN HIDRÓGENO en el período 2**

$$\boxed{\text{N, O y F son los únicos suficientemente ELECTRONEGATIVOS y CHICOS}}$$

| | EN | Tamaño | ¿Unión H? |
|---|---|---|---|
| **N, O, F** (período 2) | 3,0 · 3,5 · 4,0 — **altísimas** | **Chicos** | **SÍ** ✓ |
| P, S, Cl (período 3) | 2,1 · 2,5 · 3,0 — bajan | Grandes | **NO** ❌ |
| As, Se, Br (período 4) | ↓ | Más grandes | **NO** ❌ |
| Sb, Te, I (período 5) | ↓ | Enormes | **NO** ❌ |

**Los dos requisitos, otra vez:**
1. **EN alta** → el enlace X–H queda muy polarizado, el H queda casi como un protón desnudo.
2. **Átomo chico** → la carga δ⁻ queda **concentrada** y el H se puede acercar mucho (a 0,175 nm en el agua, contra 0,101 nm del enlace O–H).

El **Cl tiene EN = 3,0, igual que el N**, y aun así el HCl **no** hace unión H: falla el requisito 2. La carga negativa se le dispersa en un átomo mucho más voluminoso.

**Entonces el comportamiento se explica en dos regímenes:**

| Régimen | Quiénes | Qué manda | Tendencia |
|---|---|---|---|
| **Período 2** | NH₃, H₂O, HF | **UNIÓN H** (~20 kJ/mol) — vence a todo | **Pico anómalo** hacia arriba |
| **Períodos 3, 4, 5** | PH₃…SbH₃ · H₂S…H₂Te · HCl…HI | **LONDON** (α crece con el tamaño) | Creciente, como el grupo 14 |

### ⭐ Por qué H₂O > HF > NH₃ (y no F > O > N como la EN)

Lo que decide no es sólo la **fuerza** de cada unión H, sino **cuántas uniones H por molécula** se pueden formar. Y para eso hace falta que el nº de **dadores** (H sobre F/O/N) y de **aceptores** (pares libres) esté **balanceado**:

| | Dadores (H) | Aceptores (pares libres) | **Uniones H efectivas por molécula** | T_eb |
|---|---|---|---|---|
| **H₂O** | **2** | **2** | **2 — PERFECTAMENTE BALANCEADO → red 3D** | **100 °C** |
| **HF** | 1 | 3 | **1** — limitado por el **dador** → cadenas zigzag | 19,5 °C |
| **NH₃** | 3 | **1** | **1** — limitado por el **aceptor** | −33 °C |

El agua es el **único** caso en que dadores y aceptores están **igualados**: cada molécula puede formar **4 uniones** (2 como dador + 2 como aceptor), lo que arma una **red tridimensional** en lugar de cadenas. Ésa es la razón de que el agua sea tan anómala — y de que el hielo, con esa red tetraédrica abierta, sea **menos denso** que el agua líquida.

📝 **Respuesta tipo parcial (d, e y f juntas)**

> **No**, la tendencia del grupo 14 no se repite en los demás grupos. En los grupos 15, 16 y 17 el punto de ebullición también aumenta al descender, pero **sólo a partir del período 3**: el primer hidruro de cada uno de esos grupos —**NH₃, H₂O y HF**— presenta un punto de ebullición **anómalamente alto**, muy por encima del que se obtendría extrapolando la tendencia de su propio grupo.
>
> La causa es la **unión hidrógeno**. Sólo el **N, el O y el F** reúnen las dos condiciones necesarias: una **electronegatividad muy alta**, que deja al hidrógeno con una carga parcial positiva grande, y un **tamaño pequeño**, que mantiene la carga negativa concentrada y permite que el hidrógeno se aproxime mucho al par libre del átomo vecino. A partir del período 3 los átomos (P, S, Cl, As, Se, Br…) son demasiado grandes y menos electronegativos, y **no forman uniones hidrógeno**: allí la única contribución adicional es London, que crece con la polarizabilidad, y por eso la tendencia vuelve a ser creciente como en el grupo 14.
>
> El grupo 14 no muestra anomalía porque **ninguno de sus hidruros es polar** ni tiene H unido a F, O o N: todos dependen exclusivamente de London.
>
> La magnitud de la anomalía sigue el orden **H₂O > HF > NH₃**, que no coincide con el de electronegatividad (F > O > N) porque no depende sólo de la fuerza de cada unión sino del **número de uniones por molécula**: el agua es la única que tiene **igual cantidad de dadores (2 H) y de aceptores (2 pares libres)**, lo que le permite formar una **red tridimensional** de hasta cuatro uniones por molécula, mientras que el HF está limitado por sus dadores (1 solo H) y el NH₃ por sus aceptores (1 solo par libre).

---

## Ejercicio 9 — Completar el párrafo del Br₂ vs F₂

### Las respuestas, en orden

| # | Hueco | ✅ Respuesta |
|---|---|---|
| 1 | Config. electrónica externa del F (Z = 9) | **2s² 2p⁵** |
| 2 | Config. electrónica externa del Br (Z = 35) | **4s² 4p⁵** |
| 3 | Las moléculas de Br₂ son ______ polarizables | **MÁS** |
| 4 | …generan fuerzas de London más ______ | **INTENSAS** |
| 5 | …y se requiere ______ energía para separarlas | **MÁS** |

### Verificación de las configuraciones

**Flúor, Z = 9:**
$$1s^2\,2s^2\,2p^5 \quad\Longrightarrow\quad \text{externa (nivel 2): } \boxed{2s^2\,2p^5}$$

**Bromo, Z = 35:**
$$1s^2\,2s^2\,2p^6\,3s^2\,3p^6\,4s^2\,3d^{10}\,4p^5 \;=\; [\text{Ar}]\,4s^2\,3d^{10}\,4p^5$$
$$\Longrightarrow\quad \text{externa (nivel 4): } \boxed{4s^2\,4p^5}$$

⚠️ El **3d¹⁰ NO va en la capa externa**: es un nivel interno ya completo (n = 3, mientras que la capa de valencia es n = 4). Los dos elementos tienen **7 e⁻ de valencia con configuración ns² np⁵** — son del **grupo 17**, por eso su química es parecida y su **estado de agregación** no.

### El párrafo completo

> La configuración electrónica externa del átomo de flúor (Z=9) es **2s² 2p⁵**, mientras que la del átomo de bromo (Z=35) es **4s² 4p⁵**. En la molécula de bromo los electrones de valencia están más alejados del núcleo que en la de flúor. Por consiguiente, la nube electrónica de la molécula de bromo es más difusa y está menos atraída por los núcleos que la de flúor. Las moléculas de bromo son **MÁS** polarizables que las de flúor, generan fuerzas de atracción de London más **INTENSAS** y se requiere **MÁS** energía para separarlas. Esto explica por qué a temperatura ambiente, el bromo es líquido mientras que el flúor es un gas.

### La cadena causal completa (memorizala así)

$$\boxed{n \uparrow \;\Rightarrow\; e^- \text{ más lejos} \;\Rightarrow\; \text{nube difusa} \;\Rightarrow\; \alpha \uparrow \;\Rightarrow\; \text{London} \uparrow \;\Rightarrow\; T_{eb} \uparrow \;\Rightarrow\; \text{más condensado}}$$

**Los cuatro halógenos, la serie completa:**

| | e⁻ | Config. externa | α (Å³) | **T_eb (°C)** | **Estado a 25 °C** |
|---|---|---|---|---|---|
| **F₂** | 18 | 2s² 2p⁵ | 1,4 | −188 | **GAS** |
| **Cl₂** | 34 | 3s² 3p⁵ | 4,6 | −34 | **GAS** |
| **Br₂** | 70 | 4s² 4p⁵ | 6,7 | **+59** | **LÍQUIDO** |
| **I₂** | 106 | 5s² 5p⁵ | 10,2 | +184 | **SÓLIDO** |

⚠️ **Los cuatro son igualmente NO POLARES** (ΔEN = 0, moléculas homonucleares). No hay ninguna diferencia de polaridad entre ellos: **todo el efecto es polarizabilidad**. Ésta es la idea que se vuelve a pedir en el Ejercicio 7 de casa.

---

## Ejercicio 10 — Solubilidad

### 🔑 El criterio: *"lo semejante disuelve a lo semejante"*

Y el porqué, que es lo que hay que saber justificar:

```
Disolver = ROMPER interacciones soluto–soluto y solvente–solvente
           + FORMAR interacciones soluto–solvente

Se disuelve  ⟺  lo que se GANA (soluto–solvente)
                 compensa lo que se ROMPE (solvente–solvente)
```

Por eso los solventes con **uniones hidrógeno** (agua) son los más "difíciles": romper su red cuesta 20 kJ/mol por unión, y el soluto tiene que ofrecer algo comparable.

---

### a) ¿El Br₂ será más soluble en C₆H₆ (μ = 0) o en agua?

**Paso 1 — Caracterizar a los tres:**

| | Estructura | μ | e⁻ | Interacciones propias |
|---|---|---|---|---|
| **Br₂** (soluto) | Diatómica homonuclear, ΔEN = 0 | **0 — NO POLAR** | 70 | **Sólo London** (fuerte, muy polarizable) |
| **C₆H₆** (benceno) | Hexágono plano simétrico | **0 — NO POLAR** (dato) | 42 | **Sólo London** |
| **H₂O** | Angular | **1,85 D — POLAR** | 10 | **Unión H** (red 3D) |

**Paso 2 — Balance energético de cada opción:**

| | En **benceno** | En **agua** |
|---|---|---|
| Hay que **romper** | London C₆H₆–C₆H₆ (~5 kJ/mol) | **Unión H H₂O–H₂O (~20 kJ/mol)** |
| Se **gana** (soluto–solvente) | **London Br₂–C₆H₆** (~5 kJ/mol, los dos muy polarizables) | **Dipolo–dipolo inducido** H₂O–Br₂ (**< 1 kJ/mol**) |
| **Balance** | **≈ 0 → SE DISUELVE** ✓ | **Muy desfavorable** ❌ |

### ✅ **Más soluble en C₆H₆ (benceno)**

📝 **Respuesta tipo parcial**

> El **Br₂** es una molécula **diatómica homonuclear**, por lo que ΔEN = 0 y es **no polar**: sus únicas interacciones son las de **London**, y son intensas por su elevada polarizabilidad (70 electrones). El **benceno** también es **no polar** (μ = 0, dato del enunciado) y se mantiene unido igualmente por London.
>
> Al mezclarlos, las interacciones que se rompen (London benceno–benceno) y las que se forman (London Br₂–benceno) son **del mismo tipo y de magnitud comparable**, de modo que el balance energético es favorable y **el Br₂ se disuelve bien**.
>
> En **agua**, en cambio, habría que **romper uniones hidrógeno de unos 20 kJ/mol** para abrir un hueco entre las moléculas de solvente, y a cambio sólo se establecerían interacciones **dipolo–dipolo inducido** (agua polar / bromo no polar) de **menos de 1 kJ/mol**. El balance es netamente desfavorable.
>
> Por lo tanto, el **Br₂ es mucho más soluble en benceno que en agua**, de acuerdo con el criterio de que *lo semejante disuelve a lo semejante*.

> 💡 **Aclaración honesta:** el bromo **algo** se disuelve en agua — el "agua de bromo" es un reactivo de laboratorio (≈ 3,5 g/100 mL). Pero en solventes no polares como el benceno o el CCl₄ su solubilidad es **un orden de magnitud mayor**. La pregunta es comparativa, y la respuesta es inequívoca.

---

### b) ¿El KCl será más soluble en CCl₄ (μ = 0) o en NH₃ líquido?

**Paso 1 — Caracterizar a los tres:**

| | Naturaleza | μ | Interacciones que puede ofrecer |
|---|---|---|---|
| **KCl** (soluto) | ΔEN = \|0,8 − 3,0\| = **2,2 > 1,7 → IÓNICO** | *(no hay molécula)* | Es una **red de K⁺ y Cl⁻**, unida por **ion–ion (250 kJ/mol)** |
| **CCl₄** | Tetraédrica AB₄, sustituyentes iguales | **0 — NO POLAR** (dato) | Sólo **London** → al ion sólo le puede dar **ion–dipolo inducido** (~10) |
| **NH₃ líq.** | Pirámide trigonal AB₃E | **1,47 D — POLAR** | **Ion–dipolo (~15)** + tiene unión H propia |

**Paso 2 — Lo que hace falta:** para disolver un iónico hay que **vencer la energía de red (~250 kJ/mol para el KCl: 715 kJ/mol de energía reticular)**. Eso sólo se logra si el solvente **solvata cada ion**, rodeándolo con muchas moléculas orientadas.

| | En **CCl₄** | En **NH₃ líquido** |
|---|---|---|
| Interacción soluto–solvente | **Ion–dipolo INDUCIDO** (el ion tiene que crearle el dipolo al CCl₄) | **ION–DIPOLO** permanente (~15 kJ/mol × ~6 moléculas por ion) |
| ¿Puede solvatar los iones? | **No** — el CCl₄ no tiene dipolo con qué orientarse | **Sí** — el N (δ⁻) apunta al K⁺, los H (δ⁺) apuntan al Cl⁻ |
| Resultado | **Prácticamente insoluble** ❌ | **Se disuelve** ✓ |

```
   K⁺ solvatado por NH₃:              Cl⁻ solvatado por NH₃:
        H   H                              H
         \ /                               |
          N ── el par libre del N     H ── N ── H
          ↓    (δ-) APUNTA al K⁺           ↓  los H (δ+) APUNTAN al Cl⁻
         K⁺                               Cl⁻
```

### ✅ **Más soluble en NH₃ líquido**

📝 **Respuesta tipo parcial**

> El **KCl** es un compuesto **iónico** (ΔEN = 2,2 > 1,7; metal + no metal): no existe como molécula sino como una **red cristalina de iones K⁺ y Cl⁻** unidos por interacciones **ion–ion**, las más intensas de todas (~250 kJ/mol). Para disolverlo hay que vencer esa energía reticular, y eso sólo es posible si el solvente **solvata los iones**, es decir si puede rodear cada uno con varias moléculas orientadas de manera favorable.
>
> El **NH₃ líquido** es una molécula **polar** (geometría de pirámide trigonal, μ = 1,47 D): puede establecer interacciones **ion–dipolo** (~15 kJ/mol cada una), orientando el par libre del nitrógeno (δ⁻) hacia el catión K⁺ y los hidrógenos (δ⁺) hacia el anión Cl⁻. La suma de varias de estas interacciones por ion permite compensar la energía de red.
>
> El **CCl₄**, en cambio, es **no polar** (geometría tetraédrica con cuatro sustituyentes iguales: los vectores de los enlaces C–Cl se cancelan y μ = 0). Al carecer de dipolo permanente sólo podría ofrecer interacciones **ion–dipolo inducido**, muy débiles e insuficientes para vencer la energía reticular del KCl.
>
> Por lo tanto, el **KCl es mucho más soluble en NH₃ líquido que en CCl₄**.

⚠️ **Ojo con el CCl₄:** tiene cuatro enlaces C–Cl **polares** (ΔEN = 0,5) y aun así la molécula es **no polar**. Es el error más cobrado de toda la serie: **enlace polar ≠ molécula polar**.

---
---

# PARA TRABAJAR FUERA DE CLASE

---

## Ejercicio 1 — Tipos de interacciones posibles

### a) H₂ gaseoso

| | |
|---|---|
| Estructura | Diatómica **homonuclear** H–H |
| ΔEN | **0** → enlace no polar |
| μ | **0 — NO POLAR** |
| e⁻ | **2** (el mínimo posible) |

### ✅ **SÓLO LONDON** — y las más débiles de toda la química

Con apenas 2 electrones, la polarizabilidad del H₂ es mínima: los dipolos instantáneos que se forman son diminutos. Por eso el H₂ tiene el **segundo punto de ebullición más bajo de todas las sustancias** (−253 °C), superado sólo por el He (−269 °C).

### b) Cloruro de potasio sólido

| | |
|---|---|
| ΔEN | \|0,8 − 3,0\| = **2,2 > 1,7** → **IÓNICO** |
| ¿Hay moléculas? | **NO** — red cristalina de K⁺ y Cl⁻ |

### ✅ **ION – ION** (~250 kJ/mol)

$$E \propto \frac{Q_{K^+} \cdot Q_{Cl^-}}{d} = \frac{(+1)(-1)}{d}$$

Red tipo NaCl, cada ion rodeado por 6 del signo opuesto. **T_f = 770 °C.**

### c) Solución acuosa de cloruro de calcio

**Primero, la fórmula:** cloruro de calcio = **CaCl₂** (Ca²⁺ + 2 Cl⁻). Al disolverse: $\text{CaCl}_2 \to \text{Ca}^{2+} + 2\,\text{Cl}^-$

| Par | Interacción |
|---|---|
| H₂O — H₂O | **Unión hidrógeno** |
| **Ca²⁺ — H₂O** y **Cl⁻ — H₂O** | **ION – DIPOLO** ✓ (la que decide) |

### ✅ **ION – DIPOLO** (+ unión H entre las aguas)

⚠️ **El detalle que suma puntos:** el **Ca²⁺ tiene carga 2+**, no 1+. Como

$$E_{\text{ion-dipolo}} \propto \frac{Q \cdot \mu}{d^2}$$

la interacción **Ca²⁺/H₂O es aproximadamente el doble de intensa** que la Na⁺/H₂O a igual distancia. Por eso los cationes divalentes se hidratan más fuerte y arrastran más moléculas de agua en su esfera de hidratación.

### d) Cloruro de hidrógeno gaseoso

| | |
|---|---|
| ΔEN | \|2,1 − 3,0\| = **0,9** → covalente **polar** |
| Geometría | Diatómica → **lineal**, nada que cancele |
| μ | **1,08 D — POLAR** |
| ¿H sobre F, O o N? | **NO** — el H está sobre **Cl** ❌ |

### ✅ **DIPOLO – DIPOLO + LONDON**

⚠️⚠️ **El error clásico: "el HCl hace uniones H porque tiene H y el Cl es electronegativo".** El Cl tiene EN = 3,0 (igual que el N) pero es **demasiado grande**: la carga δ⁻ le queda dispersa. **Sólo F, O y N.**

Y con 18 electrones, **la London del HCl (5 kJ/mol) es más fuerte que su propio dipolo–dipolo (0,6 kJ/mol)**.

### 📊 Resumen del ejercicio 1

| Sistema | Interacción principal | Magnitud |
|---|---|---|
| **a)** H₂ gaseoso | **London** (única, mínima) | ~5 kJ/mol |
| **b)** KCl sólido | **Ion – ion** | ~250 kJ/mol |
| **c)** CaCl₂ (ac) | **Ion – dipolo** (+ unión H del agua) | ~15+ kJ/mol |
| **d)** HCl gaseoso | **Dipolo – dipolo + London** | ~5 kJ/mol |

---

## Ejercicio 2 — H₂S vs H₂O

### a) *"La estructura molecular del ácido sulfhídrico es muy similar a la del agua"*

### ✅ **VERDADERO**

| | **H₂O** | **H₂S** |
|---|---|---|
| Central | O (grupo 16) | S (grupo 16) |
| e⁻ de valencia del central | **6** | **6** |
| e⁻ totales | 6 + 2 = 8 → 4 pares | 6 + 2 = 8 → 4 pares |
| Enlaces | 2 | 2 |
| **Pares libres** | **2** | **2** |
| Grupos electrónicos | **4** | **4** |
| Clase TRePEV | **AB₂E₂** | **AB₂E₂** |
| Geometría **electrónica** | Tetraédrica | Tetraédrica |
| Geometría **molecular** | **ANGULAR** | **ANGULAR** |
| ¿Polar? | **Sí** | **Sí** |

**Son isoestructurales.** Mismo grupo → mismos electrones de valencia → mismo Lewis → misma geometría.

**Las dos diferencias finas** (que conviene mencionar para justificar bien):

| | H₂O | H₂S | Por qué |
|---|---|---|---|
| **Ángulo H–X–H** | **104,5°** | **≈ 92°** | El S es más grande y menos electronegativo: los pares enlazantes quedan **más lejos** del central, se repelen menos entre sí y los pares libres los comprimen más, acercando el ángulo a los 90° de los orbitales p puros |
| **μ** | **1,85 D** | **0,97 D** | ΔEN(O–H) = 1,4 vs ΔEN(S–H) = **0,4** — el enlace S–H es apenas polar |

📝 **Respuesta tipo parcial (a)**

> **Verdadero.** El oxígeno y el azufre pertenecen ambos al **grupo 16** y aportan **6 electrones de valencia**. En los dos casos el átomo central forma **2 enlaces** y conserva **2 pares libres**, es decir **4 grupos electrónicos**: geometría electrónica **tetraédrica** y geometría molecular **angular** (AB₂E₂). Ambas moléculas son además **polares**.
>
> Las diferencias son cuantitativas: el ángulo de enlace es de **104,5° en el H₂O** y de aproximadamente **92° en el H₂S**, porque el mayor tamaño del azufre aleja los pares enlazantes del núcleo central y reduce su repulsión mutua; y el momento dipolar es **1,85 D en el agua** frente a **0,97 D en el H₂S**, consecuencia de que ΔEN(O–H) = 1,4 mientras que ΔEN(S–H) = 0,4.

### b) Entonces, ¿por qué el H₂O es líquido y el H₂S es gas?

**El dato que hace ruido:**

| | Masa molar | e⁻ | **T_eb** | Estado a 25 °C |
|---|---|---|---|---|
| **H₂O** | **18** g/mol | 10 | **+100 °C** | **LÍQUIDO** |
| **H₂S** | **34** g/mol | 18 | **−60 °C** | **GAS** |

El H₂S es **casi el doble de pesado** y tiene **más electrones** → su **London es mayor** que la del agua. Y sin embargo hierve **160 °C más abajo**. Si sólo existiera London, el orden estaría **al revés**.

### ✅ La explicación es la **UNIÓN HIDRÓGENO**

$$\text{EN(O)} = 3{,}5 \;\to\; \text{cumple} \qquad\qquad \text{EN(S)} = 2{,}5 \;\to\; \textbf{NO cumple}$$

| | ΔEN del enlace X–H | ¿δ⁺ grande en el H? | ¿Átomo chico? | **¿Unión H?** |
|---|---|---|---|---|
| **O–H** | **1,4** | **Sí, enorme** | Sí (período 2) | **SÍ** ✓ |
| **S–H** | **0,4** | Casi nada | No (período 3) | **NO** ❌ |

**Las interacciones de cada uno:**

| | Interacciones | Total aproximado |
|---|---|---|
| **H₂O** | **Unión H (~20)** + dip–dip + London (5) | **Alto** — y en **red 3D** |
| **H₂S** | dip–dip (**débil**, μ = 0,97) + London (~5) | Bajo |

Cada molécula de agua forma **hasta 4 uniones hidrógeno** (2 H dadores + 2 pares libres aceptores) → red tridimensional continua. El H₂S **no forma ninguna**.

📝 **Respuesta tipo parcial (b)**

> Aunque el H₂S tiene **mayor masa molar** (34 vs 18 g/mol) y **más electrones** (18 vs 10) que el agua —y por lo tanto **fuerzas de London más intensas**—, el agua es líquida a temperatura ambiente y el sulfuro de hidrógeno es gaseoso. La explicación no está en London sino en la **unión hidrógeno**.
>
> El **oxígeno** tiene una electronegatividad de **3,5** y es un átomo **pequeño**: el enlace O–H está fuertemente polarizado (ΔEN = 1,4), el hidrógeno queda con una carga parcial positiva muy grande y prácticamente desnudo, y el oxígeno vecino ofrece pares libres con carga negativa concentrada. Se cumplen las dos condiciones (dador y aceptor) y el agua forma **uniones hidrógeno de unos 20 kJ/mol**, con **hasta cuatro por molécula**, generando una **red tridimensional**.
>
> El **azufre** tiene electronegatividad **2,5** y es un átomo del período 3, mucho más grande: el enlace S–H es apenas polar (ΔEN = 0,4) y la carga negativa del azufre queda dispersa. **El H₂S no forma uniones hidrógeno**, y sus únicas interacciones son dipolo–dipolo débiles y London.
>
> Por eso el agua requiere mucha más energía para pasar al estado gaseoso (T_eb = 100 °C) que el H₂S (T_eb = −60 °C), pese a ser la molécula más liviana.

---

## Ejercicio 3 — La tabla de estados y puntos de ebullición

> | Compuesto | Estado a 25 °C | T_eb (°C) |
> |---|---|---|
> | CH₄ | Gas | −161 |
> | SiH₄ | Gas | −111 |
> | CCl₄ | **Líquido** | **77** |
> | NH₃ | Gas | −33 |
> | PH₃ | Gas | −87,8 |
> | H₂O | **Líquido** | **100** |

### a) ¿Qué fuerzas presenta cada compuesto puro?

| Compuesto | e⁻ val. central | Grupos (enl. + p.l.) | Clase | Geometría molecular | μ | e⁻ tot. | **Interacciones** |
|---|---|---|---|---|---|---|---|
| **CH₄** | 4 | 4 + 0 | AB₄ | **Tetraédrica** | **0** | 10 | **Sólo London** (débil) |
| **SiH₄** | 4 | 4 + 0 | AB₄ | **Tetraédrica** | **0** | 18 | **Sólo London** |
| **CCl₄** | 4 | 4 + 0 | AB₄ | **Tetraédrica** | **0** ⚠️ | **74** | **Sólo London** (**muy fuerte**) |
| **NH₃** | 5 | 3 + **1** | AB₃E | **Pirámide trigonal** | 1,47 D | 10 | **Unión H** + dip–dip + London |
| **PH₃** | 5 | 3 + **1** | AB₃E | **Pirámide trigonal** | 0,58 D | 18 | dip–dip + London ⚠️ **sin unión H** |
| **H₂O** | 6 | 2 + **2** | AB₂E₂ | **Angular** | 1,85 D | 10 | **Unión H** + dip–dip + London |

⚠️ **El CCl₄ es el caso de estudio de la tabla:** tiene cuatro enlaces C–Cl **polares** (ΔEN = 0,5) y aun así es **no polar**, porque la geometría tetraédrica con cuatro sustituyentes iguales cancela los vectores. **Sólo London** — pero con **74 electrones**, esa London es enorme.

⚠️ **PH₃ vs NH₃:** los dos son piramidales y polares, pero sólo el NH₃ tiene el H sobre un átomo **F/O/N**. En el PH₃ el enlace P–H tiene ΔEN = |2,1 − 2,1| = **0**: es prácticamente **no polar**, y toda la polaridad de la molécula viene del **par libre del P**, no de los enlaces.

📝 **Respuesta tipo parcial (a)**

> **CH₄, SiH₄ y CCl₄** poseen geometría **tetraédrica** con cuatro sustituyentes iguales: los vectores de momento dipolar de los enlaces se cancelan, μ = 0 y las tres son **no polares**. Sus únicas interacciones intermoleculares son las **fuerzas de London**, cuya intensidad crece con el número de electrones: 10 en el CH₄, 18 en el SiH₄ y **74 en el CCl₄**.
>
> **NH₃ y PH₃** poseen geometría de **pirámide trigonal** (AB₃E) y son **polares**, por lo que presentan **dipolo–dipolo y London**. Además, el **NH₃** tiene hidrógenos unidos directamente al **nitrógeno** y un par libre sobre él, de modo que forma **uniones hidrógeno**; el **PH₃ no**, porque el fósforo no reúne las condiciones de electronegatividad y tamaño (de hecho el enlace P–H es prácticamente no polar, ΔEN = 0).
>
> El **H₂O** tiene geometría **angular** (AB₂E₂), es polar y presenta **uniones hidrógeno**, dipolo–dipolo y London.

### b) ¿Cómo se explica que el CCl₄ sea líquido y el CH₄ un gas?

**Los dos son tetraédricos, no polares, y tienen sólo London.** Misma geometría, misma familia, mismo tipo de interacción. Lo único que cambia es **el tamaño**:

| | **CH₄** | **CCl₄** |
|---|---|---|
| Sustituyentes | 4 H (**1 e⁻** cada uno) | 4 Cl (**17 e⁻** cada uno) |
| **e⁻ totales** | **10** | **74** ← ×7,4 |
| Masa molar | 16 g/mol | **154 g/mol** ← ×9,6 |
| Volumen molecular | Chico | Grande |
| **Polarizabilidad α** | Baja | **Muy alta** |
| **London** | Débil | **Muy fuerte** |
| **T_eb** | **−161 °C** → gas | **+77 °C** → **líquido** |

### ✅ La diferencia es exclusivamente la **POLARIZABILIDAD**

Los 74 electrones del CCl₄ están repartidos en un volumen mucho mayor y, sobre todo, los del Cl están **en el nivel n = 3**, lejos de sus núcleos y poco atraídos → nube muy deformable → **dipolos instantáneos grandes** → London intensa.

$$E_{\text{London}} \propto \alpha_1\alpha_2 \qquad \alpha(\text{CCl}_4) \ggg \alpha(\text{CH}_4)$$

⭐ **Y acá está el dato más importante de toda la serie:**

$$\boxed{T_{eb}(\text{CCl}_4) = 77\,°\text{C} \;>\; T_{eb}(\text{CH}_3\text{OH}) = 65\,°\text{C}}$$

El **metanol tiene unión hidrógeno y el CCl₄ no**, y aun así el CCl₄ hierve más alto. **London puede vencer a la unión H si la diferencia de tamaño es suficientemente grande.** Por eso el método dice "unión H → ésa arriba, **a masa molar comparable**". Sin esa aclaración, la regla es falsa.

📝 **Respuesta tipo parcial (b)**

> Tanto el **CH₄** como el **CCl₄** tienen geometría **tetraédrica** con cuatro sustituyentes iguales y son **no polares** (μ = 0): en ambos casos la **única** interacción intermolecular es la de **London**. La diferencia de estado se explica entonces exclusivamente por la **polarizabilidad**.
>
> El CCl₄ tiene **74 electrones** frente a los **10** del CH₄, y una masa molar de 154 g/mol frente a 16 g/mol. Sus electrones están distribuidos en un volumen mucho mayor y, en el caso de los cloros, en el nivel n = 3, alejados de los núcleos y débilmente atraídos: la nube electrónica es **mucho más difusa y deformable**. En consecuencia, los dipolos instantáneos que se generan son mayores y las **fuerzas de London del CCl₄ son mucho más intensas**.
>
> Esas fuerzas alcanzan para mantener las moléculas de CCl₄ unidas a 25 °C (T_eb = 77 °C, **líquido**), mientras que las débiles fuerzas de London del CH₄ no lo logran (T_eb = −161 °C, **gas**).

### c) ¿Cómo se justifica la diferencia entre NH₃ y PH₃? ¿Y entre CH₄, SiH₄ y CCl₄?

**c1) NH₃ (−33 °C) vs PH₃ (−87,8 °C)**

**Lo que hace ruido:** el PH₃ es **el doble de pesado** (34 vs 17 g/mol) y tiene **más electrones** (18 vs 10). Su London es **mayor**. Y aun así hierve **55 °C más abajo**.

| | **NH₃** | **PH₃** |
|---|---|---|
| Geometría | Pirámide trigonal | Pirámide trigonal |
| ΔEN del enlace X–H | \|3,0 − 2,1\| = **0,9** | \|2,1 − 2,1\| = **0** |
| μ molecular | **1,47 D** | **0,58 D** (viene casi todo del par libre) |
| ¿H sobre F/O/N? | **SÍ (N)** ✓ | **NO (P)** ❌ |
| **Unión H** | **SÍ (~20 kJ/mol)** | **NO** |
| e⁻ / London | 10 / débil | 18 / **más fuerte** |
| **T_eb** | **−33 °C** | **−87,8 °C** |

### ✅ Gana la **unión hidrógeno** del NH₃, a pesar de tener London más débil

El N cumple las dos condiciones (EN = 3,0 y átomo chico del período 2); el P no cumple ninguna (EN = 2,1, **igual a la del H**, y átomo grande del período 3). La ganancia de ~20 kJ/mol por unión H supera con creces la ventaja de London del PH₃.

**c2) CH₄ (−161) < SiH₄ (−111) < CCl₄ (77)**

| | CH₄ | SiH₄ | CCl₄ |
|---|---|---|---|
| Geometría | Tetraédrica | Tetraédrica | Tetraédrica |
| μ | **0** | **0** | **0** |
| Interacción | **Sólo London** | **Sólo London** | **Sólo London** |
| **e⁻** | **10** | **18** | **74** |
| Masa (g/mol) | 16 | 32 | 154 |
| **T_eb** | **−161** | **−111** | **+77** |

### ✅ Los tres tienen **exactamente el mismo tipo de interacción**, así que el orden lo decide **sólo la polarizabilidad**

$$\alpha \uparrow \;\text{con}\; n_{e^-} \uparrow \quad\Longrightarrow\quad 10 < 18 < 74 \quad\Longrightarrow\quad T_{eb}: \text{CH}_4 < \text{SiH}_4 < \text{CCl}_4$$

Tendencia **monótona y sin sorpresas** — porque no hay ninguna variable compitiendo.

📝 **Respuesta tipo parcial (c)**

> **NH₃ vs PH₃:** ambos tienen geometría de **pirámide trigonal** y son polares, y el PH₃ es incluso **más pesado** (34 vs 17 g/mol) y tiene **más electrones** (18 vs 10), por lo que sus fuerzas de London son **mayores**. Sin embargo, el **NH₃ hierve 55 °C más alto** porque forma **uniones hidrógeno**: el nitrógeno tiene electronegatividad 3,0 y es un átomo pequeño del período 2, de modo que el enlace N–H está muy polarizado (ΔEN = 0,9) y el nitrógeno aporta además un par libre aceptor. El fósforo, en cambio, tiene electronegatividad **2,1, igual a la del hidrógeno**: el enlace P–H es prácticamente **no polar** y el PH₃ **no forma uniones hidrógeno**. La contribución de la unión H (~20 kJ/mol) supera ampliamente la ventaja del PH₃ en London.
>
> **CH₄, SiH₄ y CCl₄:** los tres son **tetraédricos y no polares**, de modo que su **única** interacción es la de **London** y no hay ningún otro factor en competencia. El orden queda determinado exclusivamente por la **polarizabilidad**, que crece con el número de electrones: **10 (CH₄) < 18 (SiH₄) < 74 (CCl₄)**. De ahí el orden creciente de puntos de ebullición **−161 °C < −111 °C < +77 °C**.

---

## Ejercicio 4 — ¿Br₂ o ICl tiene mayor punto de fusión?

### Paso 1 — Caracterizar las dos

| | **Br₂** | **ICl** |
|---|---|---|
| Tipo | Diatómica **homonuclear** | Diatómica **heteronuclear** |
| ΔEN | \|2,8 − 2,8\| = **0** | \|2,5 − 3,0\| = **0,5** |
| **μ** | **0 — NO POLAR** | **≠ 0 — POLAR** (1,24 D) |
| Masa molar | **159,8** g/mol | **162,4** g/mol |
| **e⁻ totales** | 35 + 35 = **70** | 53 + 17 = **70** |
| Interacciones | **Sólo London** | **Dipolo–dipolo + London** |

### Paso 2 — Aplicar el método

**Paso 5b del método** (¿masas muy distintas? → manda London):

$$\frac{162{,}4}{159{,}8} = 1{,}016 \quad\Rightarrow\quad \textbf{prácticamente idénticas} \qquad n_{e^-}: \; 70 = 70 \quad\Rightarrow\quad \textbf{IDÉNTICOS}$$

**La London es prácticamente la misma en las dos.** El factor London **empata**.

**Paso 5c** (¿masas parecidas? → manda la polaridad): el ICl aporta, **además** de la misma London, interacciones **dipolo–dipolo** que el Br₂ no tiene.

### ✅ Respuesta: **ICl**

$$\boxed{T_f(\text{ICl}) > T_f(\text{Br}_2)}$$

**Verificación con los valores reales:**

| | μ | e⁻ | **T_f (°C)** | **T_eb (°C)** |
|---|---|---|---|---|
| **Br₂** | 0 | 70 | **−7,2** | 59 |
| **ICl** | 1,24 D | 70 | **+27,2** | 97 |

Diferencia de **34 °C** a favor del ICl, con la misma masa y el mismo número de electrones. **Todo el efecto es la polaridad.**

📝 **Respuesta tipo parcial**

> El **Br₂** es una molécula **diatómica homonuclear**: ΔEN = 0 y por lo tanto **no polar** (μ = 0). Su única interacción intermolecular es la de **London**.
>
> El **ICl** es **heteronuclear**: ΔEN = |2,5 − 3,0| = 0,5, por lo que el enlace es polar y, al ser una molécula diatómica, no hay ninguna geometría que cancele ese vector. Es una molécula **polar** y presenta **dipolo–dipolo además de London**.
>
> Ahora bien, las dos moléculas tienen **masas molares prácticamente iguales** (159,8 vs 162,4 g/mol) y **exactamente el mismo número de electrones (70)**, de modo que sus **fuerzas de London son equivalentes** y ese factor no las diferencia.
>
> El desempate lo aporta entonces la **polaridad**: el ICl suma interacciones dipolo–dipolo que el Br₂ no posee, por lo que sus fuerzas intermoleculares totales son mayores y **el ICl tiene mayor punto de fusión** (27 °C frente a −7 °C del Br₂).

⚠️ **Éste es el ejercicio de manual del paso "a masa comparable manda la polaridad".** Compará con el Ejercicio 7 de casa, que es exactamente el caso opuesto (misma polaridad, distinto tamaño).

---

## Ejercicio 5 — Ordenar T_eb creciente: SiH₄, HCl, CaCl₂

### Paso 1 — ⚠️ Separar primero lo iónico de lo molecular

| | Tipo de compuesto | Cómo se ve |
|---|---|---|
| **SiH₄** | **Molecular** covalente | Dos no metales |
| **HCl** | **Molecular** covalente | Dos no metales |
| **CaCl₂** | **IÓNICO** | **Metal + no metal**; ΔEN = \|1,0 − 3,0\| = **2,0 > 1,7** |

**El CaCl₂ se va arriba de una y no hay que compararlo con nada:** no tiene moléculas, es una **red cristalina** unida por interacciones **ion–ion de ~250 kJ/mol**, contra los ~5 kJ/mol de las otras dos. Y el **Ca²⁺ tiene carga 2+**, lo que hace la interacción todavía más intensa ($E \propto Q_1Q_2$).

$$T_{eb}(\text{CaCl}_2) = 1935\,°\text{C} \qquad (T_f = 772\,°\text{C})$$

### Paso 2 — Desempatar las dos moleculares

| | **SiH₄** | **HCl** |
|---|---|---|
| Geometría | **Tetraédrica** (AB₄) | Diatómica **lineal** |
| ΔEN del enlace | \|1,8 − 2,1\| = 0,3 | \|2,1 − 3,0\| = **0,9** |
| ¿Sustituyentes iguales? | Sí (4 H) → **cancelan** | No aplica |
| **μ** | **0 — NO POLAR** | **1,08 D — POLAR** |
| Masa molar | 32,1 g/mol | 36,5 g/mol |
| **e⁻ totales** | **18** | **18** |
| Interacciones | **Sólo London** | **Dipolo–dipolo + London** |
| **T_eb** | **−111 °C** | **−85 °C** |

**Mismo número de electrones (18) y masas parecidas** → London empatada → **desempata la polaridad** → el HCl, que suma dipolo–dipolo, queda arriba.

### ✅ Respuesta

$$\boxed{T_{eb}: \quad \text{SiH}_4 \;<\; \text{HCl} \;\lll\; \text{CaCl}_2}$$

$$-111\,°\text{C} \;<\; -85\,°\text{C} \;\lll\; 1935\,°\text{C}$$

📝 **Respuesta tipo parcial**

> El **CaCl₂** es un compuesto **iónico** (metal + no metal, ΔEN = 2,0 > 1,7): no está formado por moléculas sino por una **red cristalina** de iones Ca²⁺ y Cl⁻ unidos por interacciones **ion–ion**, del orden de **250 kJ/mol** y reforzadas por la carga **2+** del catión. Vaporizarlo exige romper la red completa, por lo que su punto de ebullición (1935 °C) es **varios órdenes de magnitud mayor** que el de los otros dos.
>
> El **SiH₄** y el **HCl** son compuestos **moleculares**. El SiH₄ tiene geometría **tetraédrica** con cuatro sustituyentes iguales: sus vectores de enlace se cancelan, μ = 0 y es **no polar**, por lo que sólo presenta **fuerzas de London**. El **HCl** es una molécula **diatómica polar** (ΔEN = 0,9, μ = 1,08 D) y presenta **dipolo–dipolo además de London**; no forma uniones hidrógeno porque el cloro, aunque electronegativo, es un átomo demasiado grande.
>
> Como ambos tienen **18 electrones** y masas molares similares (32 y 36,5 g/mol), sus fuerzas de London son **comparables** y el factor decisivo es la **polaridad**: el HCl, al sumar interacciones dipolo–dipolo, tiene mayor punto de ebullición.
>
> Orden creciente: **SiH₄ (−111 °C) < HCl (−85 °C) ⋘ CaCl₂ (1935 °C)**.

---

## Ejercicio 6 — Armar compuestos con Br, P, H, C

> **Elementos disponibles:** Br (grupo 17) · P (grupo 15) · H (grupo 1) · C (grupo 14)

### 🔎 Antes de elegir: qué puede ser central

| Elemento | e⁻ val. | Enlaces que forma | ¿Puede ser central? |
|---|---|---|---|
| **C** | 4 | 4 | **Sí** → 4 grupos, 0 p.l. → **tetraédrica** |
| **P** | 5 | 3 | **Sí** → 4 grupos, **1 p.l.** → **pirámide trigonal** |
| **Br** | 7 | 1 | Sólo periférico (en estos compuestos) |
| **H** | 1 | 1 | **Nunca** central |

**La consigna está diseñada así:** si querés **tetraédrica**, el central tiene que ser **C**; si querés **piramidal**, tiene que ser **P**.

---

### a) Geometría molecular **tetraédrica** con **μ = 0**

**Requisitos:** central C (4 grupos, 0 pares libres) **y** los cuatro sustituyentes **iguales**.

### ✅ **CH₄** (metano) — o también **CBr₄** (tetrabromuro de carbono)

```
        H
        |
    H—— C ——H       4 enlaces C–H idénticos, a 109,5°
        |           los 4 vectores μ se cancelan de a pares
        H           →  μ = 0
```

| | CH₄ | CBr₄ |
|---|---|---|
| Clase | AB₄ | AB₄ |
| Geometría | Tetraédrica | Tetraédrica |
| ΔEN de cada enlace | 0,4 | 0,3 |
| **μ molecular** | **0** ✓ | **0** ✓ |

**Justificación:** en una geometría tetraédrica con **cuatro sustituyentes idénticos**, los cuatro vectores de momento dipolar apuntan a los vértices de un tetraedro regular y su **suma vectorial es cero**, sea cual sea la ΔEN de cada enlace.

---

### b) Geometría molecular **tetraédrica** con **μ ≠ 0**

**Requisitos:** central C (para que sea tetraédrica) **pero** con **al menos un sustituyente distinto**.

### ✅ **CH₃Br** (bromometano) — o **CH₂Br₂**, o **CHBr₃**

```
        Br  ← ΔEN(C–Br) = 0,3, vector hacia el Br
        |
    H—— C ——H       3 enlaces C–H (ΔEN 0,4, vector hacia el C)
        |           + 1 enlace C–Br (vector hacia el Br)
        H           →  NO hay simetría  →  μ ≠ 0
```

| | |
|---|---|
| Clase TRePEV | **AB₃C** (3 iguales + 1 distinto) |
| Geometría molecular | **Tetraédrica** ✓ (los 4 grupos son enlaces) |
| Sustituyentes | **Distintos** → no cancelan |
| **μ** | **≠ 0** ✓ (CH₃Br: μ = 1,82 D) |

⚠️ **Punto clave:** la geometría **sigue siendo tetraédrica** aunque los sustituyentes sean distintos. Lo que cambia no es la forma sino la **simetría de los vectores**. Cambiar **un solo** sustituyente en un AB₄ **siempre** rompe la cancelación.

⚠️ **Cuidado con el CH₂Br₂:** también sirve (es tetraédrico y polar), pero **no** vale razonar "dos y dos, se cancelan". Los vectores C–H y C–Br tienen **módulos distintos** y **sentidos opuestos** respecto del C, así que no hay forma de que se anulen.

---

### c) Geometría **piramidal** con fuerzas **dipolo permanente y London**

**Requisitos:** central **P** (3 enlaces + 1 par libre → AB₃E) **y** que **no** haya unión H.

### ✅ **PH₃** (fosfina) — o **PBr₃** (tribromuro de fósforo)

```
         ·· ← par libre del P
         P
       / | \        3 enlaces + 1 par libre = 4 grupos electrónicos
      H  H  H       geometría electrónica: tetraédrica
                    geometría MOLECULAR:  PIRÁMIDE TRIGONAL
                    asimétrica  →  μ ≠ 0
```

| | **PH₃** | **PBr₃** |
|---|---|---|
| e⁻ val. del P | 5 | 5 |
| Grupos | 3 enlaces + **1 par libre** | 3 enlaces + **1 par libre** |
| Clase | **AB₃E** | **AB₃E** |
| Geometría molecular | **Pirámide trigonal** ✓ | **Pirámide trigonal** ✓ |
| **μ** | **0,58 D ≠ 0** ✓ | **0,60 D ≠ 0** ✓ |
| ¿H sobre F/O/N? | **No** (está sobre P) ✓ | No tiene H ✓ |
| **Interacciones** | **Dipolo permanente + London** ✓ | **Dipolo permanente + London** ✓ |

⚠️⚠️ **El detalle que hace correcto al ejercicio:** el enunciado pide dipolo permanente y London — es decir **SIN unión hidrógeno**. El PH₃ cumple porque **el H está unido al P, no a un F/O/N**.

💡 **Fijate en el diseño de la consigna:** te dan **P** y no **N** justamente por eso. Si te hubieran dado N, la respuesta obvia (NH₃) **también tendría unión H** y no serviría para este ítem. El PH₃ es piramidal y polar **pero sin puente H** — la única combinación que cumple exactamente lo pedido.

💡 **De dónde sale la polaridad del PH₃:** el enlace P–H tiene ΔEN = |2,1 − 2,1| = **0**, o sea es **no polar**. Toda la polaridad de la molécula viene del **par libre del fósforo**, que es una zona de alta densidad electrónica (δ⁻) sin nada que la compense del otro lado. Por eso μ = 0,58 D, bastante más chico que el del NH₃ (1,47 D).

### 📊 Resumen del ejercicio 6

| Ítem | Pide | ✅ Respuesta | Clase | Por qué |
|---|---|---|---|---|
| **a)** | Tetraédrica, μ = 0 | **CH₄** (o CBr₄) | AB₄ | 4 sustituyentes **iguales** → cancelan |
| **b)** | Tetraédrica, μ ≠ 0 | **CH₃Br** (o CH₂Br₂, CHBr₃) | AB₃C | Sustituyente **distinto** → no cancela |
| **c)** | Piramidal, dip. perm. + London | **PH₃** (o PBr₃) | AB₃E | Par libre → asimétrica; H sobre P → **sin unión H** |

---

## Ejercicio 7 — Verdadero o Falso: F₂ gas vs I₂ sólido

> *"El hecho de que a temperatura ambiente el F₂ sea un gas y el I₂ un sólido es consecuencia de la diferente polaridad de estas moléculas."*

### ✅ Respuesta: **FALSO**

### Por qué la premisa está mal

$$\Delta EN(\text{F—F}) = |4{,}0 - 4{,}0| = \mathbf{0} \qquad\qquad \Delta EN(\text{I—I}) = |2{,}5 - 2{,}5| = \mathbf{0}$$

**Las dos son moléculas diatómicas HOMONUCLEARES.** Los dos átomos son idénticos, comparten los electrones **exactamente por igual**, no hay ningún δ⁺ ni δ⁻ y por lo tanto:

$$\mu(\text{F}_2) = \mu(\text{I}_2) = \mathbf{0}$$

**No existe "diferente polaridad" entre ellas: las dos son igualmente NO POLARES.** La afirmación se cae por la base — no es que la explicación sea incompleta, es que el hecho que invoca **no existe**.

### La causa real: la POLARIZABILIDAD (α)

| | **F₂** | **I₂** |
|---|---|---|
| μ | **0** | **0** ← *iguales* |
| Z de cada átomo | 9 | 53 |
| **e⁻ totales** | **18** | **106** ← ×5,9 |
| Config. externa | 2s² 2p⁵ (**n = 2**) | 5s² 5p⁵ (**n = 5**) |
| Masa molar | 38 g/mol | **254 g/mol** |
| **α (polarizabilidad)** | 1,4 Å³ | **10,2 Å³** ← ×7,3 |
| **London** | **Débil** | **Muy fuerte** |
| **T_f / T_eb (°C)** | −220 / **−188** | **+114** / +184 |
| **Estado a 25 °C** | **GAS** | **SÓLIDO** |

**La cadena causal:**

$$\boxed{n \uparrow \;\Rightarrow\; e^- \text{ más lejos y menos atraídos} \;\Rightarrow\; \text{nube DIFUSA} \;\Rightarrow\; \alpha \uparrow \;\Rightarrow\; \text{LONDON} \uparrow \;\Rightarrow\; \text{más condensado}}$$

Los electrones de valencia del I están en el **nivel n = 5**, lejísimos del núcleo y muy apantallados; los del F están en **n = 2**, pegados a un núcleo que los sujeta con fuerza. La nube del I₂ se deforma con muchísima facilidad → **dipolos instantáneos grandes** → London intensa.

📝 **Respuesta tipo parcial**

> **FALSO.** La afirmación parte de una premisa incorrecta: **el F₂ y el I₂ no tienen distinta polaridad**. Ambas son moléculas **diatómicas homonucleares**, en las que los dos átomos son idénticos y comparten los electrones por igual: ΔEN = 0 en los dos casos y, en consecuencia, **μ(F₂) = μ(I₂) = 0**. Las dos son igualmente **no polares**.
>
> La diferencia de estado de agregación se debe a la **polarizabilidad (α)**, no a la polaridad. En ambas moléculas la única interacción presente es la de **London**, cuya intensidad es proporcional a α. El I₂ posee **106 electrones** frente a los **18** del F₂, y sus electrones de valencia se encuentran en el nivel **n = 5**, muy alejados del núcleo y fuertemente apantallados, mientras que los del F₂ están en **n = 2**, firmemente retenidos. La nube electrónica del I₂ es por lo tanto **mucho más difusa y deformable**, genera **dipolos instantáneos de mayor magnitud** y da lugar a **fuerzas de London mucho más intensas**.
>
> Por eso se requiere mucha más energía para separar las moléculas de I₂ (T_f = 114 °C, **sólido** a temperatura ambiente) que las de F₂ (T_eb = −188 °C, **gas**).

⚠️ **Comparación con el Ejercicio 4 de casa** — son los dos casos complementarios, y conviene tenerlos juntos:

| | Ej. 4 (Br₂ vs ICl) | Ej. 7 (F₂ vs I₂) |
|---|---|---|
| ¿Qué está **igualado**? | Masa y nº de e⁻ (**London empatada**) | **Polaridad** (las dos μ = 0) |
| ¿Qué **desempata**? | **La POLARIDAD** | **La POLARIZABILIDAD (London)** |
| Gana | **ICl** (polar) | **I₂** (más polarizable) |

---

## Ejercicio 8 — ¿El I₂ es más soluble en agua o en CS₂?

### Paso 1 — Caracterizar a los tres

| | Estructura | Geometría | **μ** | Interacciones |
|---|---|---|---|---|
| **I₂** (soluto) | Diatómica homonuclear, ΔEN = 0 | Lineal | **0 — NO POLAR** | **Sólo London** (muy fuerte, 106 e⁻) |
| **H₂O** | AB₂E₂, 2 enlaces + 2 p.l. | **Angular** | **1,85 D — POLAR** | **Unión H** (red 3D) |
| **CS₂** | AB₂, S=C=S, 2 grupos, 0 p.l. | **LINEAL** | **0 — NO POLAR** | **Sólo London** (38 e⁻) |

⚠️ **El CS₂ hay que analizarlo, no darlo por sabido.** El enunciado no te dice que sea no polar (a diferencia del Ej. 10, donde sí daba μ = 0 para el C₆H₆ y el CCl₄). Hay que sacarlo:

```
    S ══ C ══ S        e⁻ totales = 4 + 6 + 6 = 16 → 8 pares
    ←──     ──→        C central: 2 grupos electrónicos (dos dobles enlaces,
    μ₁         μ₂                  cada uno cuenta como UN grupo), 0 pares libres
                       → AB₂ → LINEAL, ángulo 180°
    ΔEN(C=S) = |2,5 − 2,5| = 0   →  ¡los enlaces ya son NO polares!
    Y aunque lo fueran: geometría lineal simétrica → los vectores se cancelan
                       →  μ = 0  →  NO POLAR
```

**Doble motivo:** el enlace C=S tiene ΔEN = 0 (C e S tienen los dos EN = 2,5) **y** la geometría es lineal simétrica. Es no polar por partida doble.

### Paso 2 — Balance energético de cada opción

| | En **agua** | En **CS₂** |
|---|---|---|
| Hay que **romper** (solvente–solvente) | **Uniones H: ~20 kJ/mol** | London CS₂–CS₂: ~5 kJ/mol |
| Se **forma** (soluto–solvente) | **Dipolo–dipolo inducido: < 1 kJ/mol** | **London I₂–CS₂: ~5 kJ/mol** (los dos muy polarizables) |
| **Balance** | **Pésimo** ❌ | **Favorable** ✓ |
| Resultado | Casi insoluble (≈ 0,3 g/L) | **Muy soluble** (≈ 180 g/L) |

**El razonamiento en una línea:** meter un I₂ entre las aguas obliga a **romper una red de puentes de hidrógeno de 20 kJ/mol** y sólo devuelve **menos de 1 kJ/mol** de dipolo–dipolo inducido. Al agua le conviene muchísimo más quedarse unida a sí misma y **expulsar** al I₂.

### ✅ Respuesta: **más soluble en CS₂**

📝 **Respuesta tipo parcial**

> El **I₂** es una molécula **diatómica homonuclear**: ΔEN = 0 y por lo tanto **no polar** (μ = 0), con interacciones **exclusivamente de London**, muy intensas debido a su elevada polarizabilidad (106 electrones).
>
> El **CS₂** tiene geometría **lineal** (el carbono central presenta 2 grupos electrónicos, ya que cada doble enlace C=S cuenta como uno solo, y ningún par libre). Además, C y S tienen la **misma electronegatividad (2,5)**, de modo que los enlaces ni siquiera son polares. Es una molécula **no polar** cuyas únicas interacciones son las de **London**.
>
> El **agua**, en cambio, es **polar** y forma una **red tridimensional de uniones hidrógeno** de unos 20 kJ/mol.
>
> Aplicando el criterio de que *lo semejante disuelve a lo semejante*: al disolver I₂ en **CS₂** se rompen interacciones de London y se forman interacciones de London **del mismo tipo y magnitud comparable**, con un balance energético favorable. Al intentar disolverlo en **agua** habría que **romper uniones hidrógeno de ~20 kJ/mol** y a cambio sólo se establecerían interacciones **dipolo–dipolo inducido de menos de 1 kJ/mol**, un balance netamente desfavorable.
>
> Por lo tanto, el **I₂ es mucho más soluble en CS₂ que en agua**.

> 💡 **Comprobación de laboratorio:** el I₂ en agua da una solución apenas amarillenta y muy diluida; en CS₂ (o en CCl₄) da una solución **violeta intensa**, característica del I₂ molecular disuelto. Es el experimento de extracción líquido–líquido de la práctica.

---
---

# 📌 Resumen de métodos que usa esta serie

| Método | Dónde se usa |
|---|---|
| **Lewis + TRePEV** para sacar la geometría molecular | Ej. 2, 3, 7, 8a · casa 2, 3, 6 |
| **Contar los pares libres del central** (nº de grupo − nº de enlaces) | Ej. 2 (SeF₄ vs SiF₄) · 8a |
| **μ = 0 ⟺ geometría simétrica Y sustituyentes iguales** | Ej. 2, 3, 6, 7 · casa 3, 6, 7, 8 |
| **⚠️ Enlace polar ≠ molécula polar** | CCl₄, SiCl₄, CBr₄, CS₂ |
| **London está en TODAS** las sustancias moleculares | Ej. 1a |
| **Unión H ⟺ H sobre F, O o N (dador) + F/O/N con par libre (aceptor)** | Ej. 1c, 3, 7, 8f · casa 1d, 2b, 3 |
| **⚠️ El Cl NO hace unión H** aunque tenga EN = 3,0 | Ej. 1c · casa 1d |
| **⚠️ Aceptor sin dador ⇒ no hay unión H consigo mismo** | CH₂O (ej. 7), éter |
| **α ↑ con nº de e⁻ y con el nivel n** | Ej. 6, 9 · casa 3b, 3c, 7 |
| **⚠️ Cuando dan α, usar α y NO el nº de e⁻** | Ej. 6 (CH₄ 10 e⁻ > Ar 18 e⁻) |
| **Método de 5 pasos para ordenar T_eb** | Ej. 6, 7, 8 · casa 3, 4, 5 |
| **Iónico → ion–ion → se va arriba de todo** | Ej. 5d, 5e · casa 1b, 5 |
| **Ion–dipolo = solvatación de iones** | Ej. 5e, 10b · casa 1c |
| **Dipolo–dipolo inducido = no polar en solvente polar** | Ej. 5c, 10a · casa 8 |
| **Criterio de solubilidad: comparar lo que se ROMPE con lo que se GANA** | Ej. 10 · casa 8 |
| **Configuración electrónica externa (el d NO cuenta)** | Ej. 9 |
| **A masa comparable ⇒ manda la POLARIDAD** | casa 4 (Br₂ vs ICl), casa 5 (SiH₄ vs HCl) |
| **A polaridad igual ⇒ manda la POLARIZABILIDAD** | Ej. 9 · casa 7 (F₂ vs I₂), casa 3c |
| **⚠️ London puede vencer a la unión H** si la diferencia de tamaño es grande | casa 3b (CCl₄ 77 °C > CH₃OH 65 °C) |

---

# ⚠️ Los 12 errores que más se cobran en esta serie

| ❌ Error | ✅ Correcto |
|---|---|
| "London sólo actúa entre moléculas no polares" | Actúa en **TODAS**; es la **única** en las no polares |
| Deducir la geometría de la fórmula sin hacer Lewis | **SiF₄ es tetraédrico (AB₄) y SeF₄ es balancín (AB₄E)** — misma fórmula, distinto grupo del central |
| "Los enlaces son polares ⇒ la molécula es polar" | **CCl₄, SiCl₄, CS₂**: enlaces polares, molécula **no polar** por simetría |
| Decir que el **HCl** hace uniones H (Cl tiene EN 3,0) | El Cl es **demasiado grande**: la carga δ⁻ queda dispersa. **Sólo F, O, N** |
| Decir que el **CH₂O** hace unión H consigo mismo (tiene O) | Los H están sobre el **C**: hay **aceptor** pero **no dador** |
| Decir que el **PCl₃** hace unión H (es piramidal como el NH₃) | **No tiene ningún H** |
| Usar el **nº de electrones** cuando el enunciado da la **α** | Ej. 6: **CH₄ (10 e⁻) es MÁS polarizable que Ar (18 e⁻)** |
| Creer que **dipolo–dipolo > London** | **London (5) > dipolo–dipolo (0,6) kJ/mol** |
| "Más pesado ⇒ hierve más alto", sin más | **NH₃ (17 g/mol, −33 °C) > PH₃ (34 g/mol, −87,8 °C)**: gana la unión H |
| "Unión H ⇒ hierve más alto", sin más | **CCl₄ (77 °C) > CH₃OH (65 °C)**: gana London. Vale sólo **a masa comparable** |
| Atribuir la diferencia **F₂ / I₂** a la polaridad | Las **dos tienen μ = 0**. La causa es **α** (18 vs 106 e⁻) |
| Buscar geometría, μ o Lewis molecular de **NaCl, KCl, CaCl₂** | Son **iónicos**: red cristalina, **no hay molécula**. Interacción **ion–ion** |

---

# 🎯 Los 5 casos que hay que tener de memoria

| Caso | Comparación | Quién gana | Por qué |
|---|---|---|---|
| **1** | **H₂O (100) vs H₂S (−60)** | H₂O, siendo **más liviana** | **Unión H** vence a London |
| **2** | **NH₃ (−33) vs PH₃ (−87,8)** | NH₃, siendo **más liviano** | **Unión H** vence a London |
| **3** | **CCl₄ (77) vs CH₃OH (65)** | CCl₄, **sin unión H** | **London** (74 e⁻) vence a la unión H |
| **4** | **ICl (27) vs Br₂ (−7)** — mismos e⁻ | ICl | A London igual, manda la **polaridad** |
| **5** | **I₂ (sólido) vs F₂ (gas)** — μ = 0 en las dos | I₂ | A polaridad igual, manda la **α** |

**Los cinco en una frase:** *primero mirá si hay unión H, después compará tamaños, y sólo si empatan desempatá por polaridad.*

---

## 📌 Fórmulas de la serie

$$E_{\text{ion-ion}} \propto \frac{Q_1Q_2}{d} \quad E_{\text{ion-}\mu} \propto \frac{Q_1\mu_2}{d^2} \quad E_{\mu\text{-}\mu} \propto \frac{\mu_1\mu_2}{d^3} \quad E_{\text{ion-}\alpha} \propto \frac{Q_1\alpha_2}{d^4} \quad E_{\text{London}} \propto \frac{\alpha_1\alpha_2}{d^6}$$

$$\mu_{\text{inducido}} = \alpha \cdot E \qquad\qquad \alpha \uparrow \;\text{con}\; n_{e^-} \uparrow \;\text{y}\; n \uparrow$$

$$\Delta EN = |EN_A - EN_B| \qquad \begin{cases} < 0{,}4 & \text{covalente no polar} \\ 0{,}4 - 1{,}7 & \text{covalente polar} \\ \ge 1{,}7 & \text{iónico} \end{cases}$$

$$\boxed{\text{NO POLAR} \iff \text{geometría SIMÉTRICA \textbf{y} sustituyentes TODOS IGUALES}}$$

$$\boxed{\text{Unión H} \iff \text{H sobre F/O/N (dador)} \;+\; \text{F/O/N con par libre (aceptor)}}$$

$$E_c \; \text{vs} \; E_p \;\Rightarrow\; \begin{cases} E_c > E_p & \text{GAS} \\ E_c \approx E_p & \text{LÍQUIDO} \\ E_c < E_p & \text{SÓLIDO} \end{cases}$$
