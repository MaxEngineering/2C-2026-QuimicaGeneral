# Clase 4 — Profundización: la CLASIFICACIÓN de las interacciones intermoleculares

**Materia:** Química General — ECyT / UNSAM — 2do Cuatrimestre 2026
**Tema:** Por qué hay "4 tipos" de interacciones y al mismo tiempo "6 interacciones", y cómo encajan unas dentro de otras

> ⚠️ **Esto NO es un apunte de diapositivas.** El apunte diapo por diapo de la Clase 4 está en [`Clase4-Explicacion-Completa.md`](Clase4-Explicacion-Completa.md).
>
> Este archivo desarrolla **un solo tema**: la **estructura de la clasificación**. El material de la cátedra tiene todos los ingredientes (las familias están en las págs. 2 y 3, la matriz en la pág. 4, la tabla de magnitudes en la P2 — pág. 19), pero **nunca dice explícitamente que son dos niveles distintos de clasificación**. Las diapositivas presentan las 4 familias, después arrancan a explicar las interacciones una por una, y el que escucha queda con la sensación de que hay dos listas que no cierran entre sí.
>
> Acá se ordena eso.

---

## 0. La duda que lo originó

> *"Las uniones intermoleculares, ¿cuáles hay? Tipo hay cuatro, pero después están tipo ion-dipolo, dipolo-dipolo, eso no entiendo, es como que muchos tipos de uniones pueden resultar en electrostáticas."*

**La observación del final es CORRECTA, y es exactamente la clave.** Sí: varias interacciones distintas caen dentro de "electrostáticas". Eso no es un error de la clasificación ni una confusión tuya — **es cómo está armada la clasificación**.

Lo que hay que corregir es una sola cosa: **las "cuatro" no son cuatro interacciones**. Son cuatro **categorías**. Y las interacciones concretas son **seis**, repartidas dentro de esas cuatro categorías.

| | Nombre | Qué es | Cuántas |
|---|---|---|---|
| **Nivel 1** | **FAMILIAS** | Categorías. Agrupan según **un criterio** | **4** |
| **Nivel 2** | **INTERACCIONES** | Las que realmente existen y actúan | **6** |

⚠️ **De dónde sale la confusión:** las diapositivas 2 y 3 dan el nivel 1 (las 4 familias), y desde la pág. 5 en adelante desarrollan el nivel 2 (las interacciones, una por diapositiva). Nunca se dice "ahora bajamos un nivel". Entonces parece que hay dos listas distintas y contradictorias, cuando en realidad **una está adentro de la otra**.

---

## 1. Antes de todo: INTER ≠ INTRA (el chequeo previo)

Antes de clasificar nada, hay que estar seguros de qué se está clasificando. Ninguna de estas 6 es un **enlace químico**.

| | Qué une | Magnitud | Se rompe al |
|---|---|---|---|
| **INTRAmolecular** = **enlace** | Átomos **dentro** de una molécula | **150–1000 kJ/mol** | Hacer una **reacción química** |
| **INTERmolecular** = **interacción** | Moléculas **entre sí** | **< 1 – 250 kJ/mol** | **Fundir / hervir** |

⚠️ **La palabra "unión" de la pregunta es peligrosa.** En castellano "unión" se usa para las dos cosas ("unión química" = enlace, "unión hidrógeno" = interacción intermolecular). Cuando hablamos de estas 6, el término correcto es **interacción**, no unión ni enlace. La única que se llama tradicionalmente "unión" es la unión hidrógeno, y **no es un enlace**: es una interacción (~20 kJ/mol, contra ~460 de un enlace O—H).

---

## 2. El nivel de abajo: los 3 personajes

Todo el sistema se construye de un solo catálogo. Hay **exactamente tres tipos de participante** posible, y esto sale directo de la Clase 3 (¿es un ion? ¿es polar? ¿es no polar?):

| Personaje | Símbolo | Qué tiene | Ejemplos |
|---|---|---|---|
| **Ion** (atómico o poliatómico) | **Q** | Carga **neta entera** | Na⁺, Cl⁻, **SO₄²⁻**, **NH₄⁺** |
| **Molécula polar** | **μ** | Dipolo **permanente** | H₂O, HCl, NH₃, CH₃OH |
| **Molécula no polar** | **α** | **Nada**, hasta que se lo inducen | Cl₂, I₂, CCl₄, CO₂, Ar |

🔑 **α (polarizabilidad)** no es una carga: es la **facilidad con la que la nube electrónica se deja deformar**. Es lo único que tiene para ofrecer una molécula no polar.

---

## 3. La matriz: de donde salen las 6 (y por qué no puede haber más)

Una interacción intermolecular es **siempre entre dos participantes**. Combinás de a dos los tres personajes y no queda nada afuera:

| | **Ion (Q)** | **Polar (μ)** | **No polar (α)** |
|---|---|---|---|
| **Ion (Q)** | ① ion–ion | ② ion–dipolo | ③ ion–dip. inducido |
| **Polar (μ)** | — | ④ dipolo–dipolo | ⑤ dipolo–dip. inducido |
| **No polar (α)** | — | — | ⑥ **London** |

Es una matriz 3×3 y sólo importa el triángulo superior (la interacción A–B es la misma que B–A), así que:

$$\text{combinaciones} = \frac{3 \times 3 + 3}{2} = \boxed{6}$$

🔑 **Y de yapa, la matriz te da gratis de qué depende cada una.** Cada interacción es el **producto de lo que aporta cada participante**:

| # | Interacción | Depende de | Alcance |
|---|---|---|---|
| ① | ion–ion | $Q_1 Q_2$ | $1/d$ |
| ② | ion–dipolo | $Q_1 \mu_2$ | $1/d^2$ |
| ③ | ion–dipolo inducido | $Q_1 \alpha_2$ | $1/d^4$ |
| ④ | dipolo–dipolo | $\mu_1 \mu_2$ | $1/d^3$ |
| ⑤ | dipolo–dipolo inducido | $\mu_1 \alpha_2$ | — |
| ⑥ | London | $\alpha_1 \alpha_2$ | **$1/d^6$** |

⚠️ **No hay que memorizar esa columna.** Se deduce: mirás quiénes participan y multiplicás sus símbolos. Si es ion con polar → $Q\mu$. Si es no polar con no polar → $\alpha\alpha$. Listo.

---

## 4. El nivel de arriba: el ÚNICO criterio que define las 4 familias

Acá está el corazón del asunto. Las 4 familias responden a **una sola pregunta**:

> ### ¿Quién trajo la carga puesta?

| Familia | Participante 1 | Participante 2 | Palabra clave |
|---|---|---|---|
| **ELECTROSTÁTICAS** | ya tiene carga o dipolo **permanente** | **también** | los dos ✓ |
| **INDUCTIVAS** | ya tiene carga o dipolo | **no tiene → se lo INDUCEN** | **"inducir"** |
| **DISPERSIVAS** | no tiene | no tiene → **los dos son INSTANTÁNEOS** | **"instantáneo"** |
| **UNIÓN H** | *(caso especial — sección 6)* | | |

Eso es todo el criterio. No hay un segundo criterio escondido.

Y fijate que las definiciones textuales del docente dicen exactamente esto, sólo que en prosa:

> **Electrostáticas:** interacciones entre **especies cargadas** (iones atómicos o moleculares) **o con una distribución asimétrica de carga** (moléculas polares).
>
> **Inductivas:** la presencia de un ion o dipolo puede **inducir** una distribución asimétrica de cargas en una molécula **no-polar**, creando un **dipolo inducido**.
>
> **Dispersión (London):** interacción atractiva entre **dipolos instantáneos**, fluctuaciones en la distribución de carga de un átomo o molécula **no-polar**.

| Lo que dice el docente | Lo que significa en el criterio |
|---|---|
| "especies cargadas **o** con distribución asimétrica" | los dos **ya tienen** algo → **electrostática** |
| "puede **inducir** … creando un dipolo inducido" | uno **se lo crea** al otro → **inductiva** |
| "dipolos **instantáneos**, fluctuaciones" | **ninguno** tiene nada permanente → **dispersiva** |

---

## 5. El mapa completo: cada interacción dentro de su familia

Ahora se cierra todo. Las 6 interacciones repartidas en las familias:

| Familia | # | Interacción | Participantes | **kJ/mol** |
|---|---|---|---|---|
| **ELECTROSTÁTICAS** (3) | ① | **ion – ion** | Q + Q | **250** |
| | ② | **ion – dipolo** | Q + μ | **15** |
| | ④ | **dipolo – dipolo** | μ + μ | **0,6** |
| **INDUCTIVAS** (2) | ③ | **ion – dipolo inducido** | Q + α | **10** |
| | ⑤ | **dipolo – dipolo inducido** | μ + α | **< 1** |
| **DISPERSIVAS** (1) | ⑥ | **London** | α + α | **5** |
| **UNIÓN H** | — | *(dipolo–dipolo anómalo)* | μ + μ, con F/O/N | **20** |

$$\boxed{3 + 2 + 1 = 6 \text{ interacciones} \quad \text{repartidas en } 3 \text{ familias} + 1 \text{ caso especial}}$$

✅ **Entonces la respuesta directa a la pregunta original:** sí, **tres** interacciones distintas son "electrostáticas" (ion–ion, ion–dipolo y dipolo–dipolo). No son alternativas a las cuatro familias: son el **contenido** de una de ellas.

💡 **Cómo leer los nombres, que es la mejor ayuda-memoria que hay.** El nombre de cada interacción **te dice quiénes participan y en qué familia está**:

| Si el nombre… | Entonces… |
|---|---|
| **NO** dice "inducido" en ninguna parte | Los dos ya tenían → **ELECTROSTÁTICA** |
| Dice "**inducido**" | Uno no tenía → **INDUCTIVA** |
| Se llama "**London**" o "dispersión" | Ninguno tenía → **DISPERSIVA** |

Fijate que no hace falta memorizar la tabla: "ion–dipolo **inducido**" tiene la palabra inducido, entonces es inductiva. "ion–dipolo" no la tiene, entonces es electrostática. Los nombres están bien puestos.

---

## 6. ⚠️ La excepción: por qué la unión H se saca de las electrostáticas

Ésta es la que rompe la prolijidad del sistema, y es **la razón principal de la confusión original**.

**Estrictamente, la unión hidrógeno ES un dipolo–dipolo.** Los dos participantes tienen dipolo permanente (agua con agua, por ejemplo), así que por el criterio de la sección 4 **debería estar adentro de electrostáticas**, en la casilla ④. No es una casilla nueva de la matriz.

**¿Por qué se le da familia propia entonces?** Por una sola razón, y es **cuantitativa, no conceptual**:

$$\frac{\text{unión H}}{\text{dipolo–dipolo común}} = \frac{20\ \text{kJ/mol}}{0{,}6\ \text{kJ/mol}} \approx \mathbf{33\times}$$

Es **33 veces más fuerte** que un dipolo–dipolo normal. Tratarla como "un dipolo–dipolo más" haría que se predijeran mal casi todas las propiedades del agua. Se la separa porque **se comporta distinto**, no porque sea un mecanismo distinto.

**Los tres motivos de que sea tan anómala** (los tres tienen que darse juntos):

| # | Motivo | Detalle |
|---|---|---|
| ① | **ΔEN enorme** | O—H = 1,4 · F—H = 1,9 → dipolo de enlace muy grande |
| ② | **El H no tiene electrones internos** | Es el único átomo así. Al ceder densidad queda un **protón casi desnudo**: carga muy concentrada y el vecino se le puede acercar muchísimo |
| ③ | **Hay un par libre esperando** | Y en una **dirección definida** → la interacción es **direccional**, no isotrópica como las demás |

⚠️ **El punto ③ es una diferencia cualitativa real**, y es el mejor argumento a favor de darle familia propia: la unión H **tiene dirección**. Un dipolo–dipolo común atrae desde cualquier lado; la unión H sólo funciona si el H apunta al par libre. Eso es lo que permite que el hielo forme una **red tetraédrica abierta** (y por lo tanto que flote) y que el ADN tenga apareamiento **específico** A–T / G–C. Ninguna otra interacción de la lista hace geometría.

### 📊 Por eso la tabla de magnitudes tiene 7 filas y la matriz 6 casillas

Éste es el detalle numérico que más desconcierta al comparar las dos tablas de la clase:

| Tabla | Cuántas entradas | Por qué |
|---|---|---|
| **Matriz 3×3** (pág. 4) | **6** | Las combinaciones de personajes. Las que existen |
| **Tabla de magnitudes** (P2 — pág. 19) | **7** | Las 6 **+ la unión H**, que se lista aparte por su magnitud |

**La fila extra no es una interacción nueva: es la casilla ④ desdoblada** en "dipolo–dipolo común" (0,6) y "dipolo–dipolo con FON = unión H" (20).

---

## 7. Un problema aparte: "van der Waals" y el ion–ion

Dos aclaraciones de vocabulario que suelen sumar confusión encima de la confusión.

### 7.1 "Fuerzas de van der Waals" tiene dos significados

| Uso | Qué abarca |
|---|---|
| **Estricto** (los libros) | Las **tres débiles**: Keesom (dipolo–dipolo) + Debye (inductivas) + **London** (dispersivas) |
| **Como lo usa el docente** | Sinónimo de **London** |

⚠️ En el parcial, usalo como lo usa la cátedra: **van der Waals = London**. Pero si en un libro lees "fuerzas de van der Waals" abarcando dipolo–dipolo, no es un error del libro.

💡 Notá qué queda **afuera** del sentido estricto: **ion–ion** y **unión H**. Justamente las dos más fuertes (250 y 20). No es casualidad — ver abajo.

### 7.2 El ion–ion es medio tramposo

⚠️ **La interacción ion–ion, en un cristal iónico, ES el enlace iónico.** No es realmente una fuerza "entre moléculas", porque **en un compuesto iónico no hay moléculas**: hay una red cristalina de iones (el NaCl es una *unidad fórmula*, no una molécula — ver la sección 7 del machete).

Por eso su magnitud (250 kJ/mol) se le escapa a las demás por un factor 10–400 y ya pisa el rango de los enlaces (150–1000). Está en la tabla de interacciones intermoleculares porque **se compara con las otras y porque aparece en solución** (un Na⁺ interactuando con un Cl⁻ en agua sí es una interacción entre especies separadas), pero conceptualmente vive en la frontera.

🔑 **La consecuencia útil:** por eso **todos los compuestos iónicos son sólidos a temperatura ambiente**, sin excepción práctica. No existe ningún compuesto iónico gaseoso a 25 °C.

---

## 8. Cómo se usa esto en el parcial

La clasificación no es decorativa: es el paso 6 de la ruta de estudio de la materia. El algoritmo:

```
1. ¿QUÉ ES cada participante?     → ion (Q) / polar (μ) / no polar (α)
      (esto sale de la Clase 3: Lewis → TRePEV → μ)
2. Buscar la casilla en la MATRIZ  → sale el nombre de la interacción
3. El nombre te da la FAMILIA      → ¿dice "inducido"? ¿dice "London"?
4. ¿Hay H unido a F, O o N,
   y un F/O/N con par libre?       → SÍ: además hay UNIÓN H (y manda)
5. Buscar la MAGNITUD en la tabla  → con eso ordenás T_eb, T_f, solubilidad
```

⚠️ **Lo que se pregunta casi siempre no es "clasificá", es "ordená".** Y ahí lo que importa es la **magnitud**, no la familia. La familia sirve para **razonar** y para las preguntas teóricas textuales; el número es el que resuelve el ejercicio.

**El orden de magnitudes, que es lo que hay que tener de memoria:**

$$\text{ion–ion} \; (250) \;\gg\; \text{unión H} \; (20) \;>\; \text{ion–dip} \; (15) \;>\; \text{ion–dip.ind} \; (10) \;>\; \boxed{\text{London} \; (5) \;>\; \text{dip–dip} \; (0{,}6)} \;>\; \text{dip–dip.ind} \; (<1)$$

⚠️⚠️ **El recuadro es la trampa nº 1 de la Clase 4: London (5) es MÁS FUERTE que dipolo–dipolo (0,6).** Es contraintuitivo (uno esperaría que un dipolo permanente le gane a uno instantáneo) y es la clave de media práctica. Por eso el **HI (menos polar) hierve más alto que el HCl (más polar)**: el HI tiene muchos más electrones y gana London.

---

## 9. Contraejemplos y trampas de la clasificación

Éstos son los casos que confirman que entendiste la estructura y no memorizaste la tabla.

| ⚠️ Trampa | ✅ La verdad |
|---|---|
| "Son 4 interacciones" | Son **4 familias** con **6 interacciones** adentro |
| "Ion–dipolo y dipolo–dipolo son familias aparte de las electrostáticas" | **Están ADENTRO** de electrostáticas (junto con ion–ion) |
| "La unión H es una interacción distinta de todas" | Es un **dipolo–dipolo** anómalo (33× más fuerte y **direccional**) |
| "Las electrostáticas son las fuertes y las otras las débiles" | ❌ **Falso.** Dipolo–dipolo (0,6) es **electrostática** y es la más débil de todas junto con dip–dip inducido. **London (5, dispersiva) le gana** |
| "London sólo actúa entre no polares" | Actúa en **TODAS** las sustancias. Es la **única** disponible entre no polares, que es otra cosa |
| "Si una molécula es polar, la interacción es dipolo–dipolo y listo" | También tiene **London** en simultáneo, y **si es grande, London domina** |
| "Un dipolo inducido es un dipolo débil" | Es un dipolo que **no existía**: aparece por el campo y **desaparece** si sacás la fuente |
| "Los iones son átomos" | También son **poliatómicos**: SO₄²⁻, NO₃⁻, NH₄⁺ hacen ion–ion e ion–dipolo igual |
| "El ion–ion es una fuerza intermolecular como las otras" | En un cristal **es el enlace iónico**. Vive en la frontera (250 kJ/mol) |
| Contar la unión H como una 7ª casilla de la matriz | La matriz tiene **6**. La unión H es la casilla ④ **desdoblada** |

### Tres casos resueltos para fijarlo

| Sistema | Personajes | Casilla | Familia | ¿Unión H? |
|---|---|---|---|---|
| **Na⁺ con H₂O** (sal en agua) | Q + μ | ② ion–dipolo | **Electrostática** | No (el Na⁺ no tiene H) |
| **Na⁺ con Cl₂** | Q + α | ③ ion–dip. **inducido** | **Inductiva** | No |
| **H₂O con H₂O** | μ + μ | ④ dipolo–dipolo | Electrostática… | ✅ **SÍ → manda la unión H** |

💡 El tercero muestra por qué la unión H se separa: si la clasificaras sólo como "dipolo–dipolo, 0,6 kJ/mol", predecirías que el agua hierve a temperatura bajo cero. Hierve a 100 °C.

---

## 10. 📡 Conexión con Telecomunicaciones

La familia importa para saber **con qué escala de energía y de distancia** estás tratando, y eso es lo que aparece en los materiales de la carrera:

| Familia | Alcance | Dónde aparece en Telecos |
|---|---|---|
| **Electrostática ion–ion** ($1/d$) | **Largo** | Cerámicas piezoeléctricas y dieléctricos de los capacitores (BaTiO₃): la red iónica es la que da la constante dieléctrica alta |
| **Electrostática dipolo–dipolo** ($1/d^3$) | Medio | La **permitividad** de un dieléctrico y sus **pérdidas** a RF: los dipolos se reorientan con el campo y disipan (por eso el agua calienta en el microondas a 2,45 GHz) |
| **Inductivas** ($1/d^4$) | Corto | La **polarizabilidad electrónica** es literalmente lo que fija el **índice de refracción**: $n^2 \approx 1 + N\alpha/\varepsilon_0$. La α de la sección 2 **es** el parámetro óptico de la fibra |
| **Dispersivas / London** ($1/d^6$) | **Cortísimo** | Adhesión y fricción a escala micro: MEMS, *stiction* en microestructuras, adherencia de películas delgadas |
| **Unión H** (direccional) | Corto y **con dirección** | Los picos de absorción de **OH⁻** en la sílice: son los que meten atenuación en la fibra y definen las **ventanas** de 1310 y 1550 nm |

🔑 **El puente conceptual:** la **polarizabilidad α**, que en esta clase es "lo único que tiene una molécula no polar", es la misma magnitud que en electromagnetismo determina la **permitividad relativa** y por lo tanto el **índice de refracción**. Química y propagación de ondas están mirando el mismo número desde dos lados.

---

## ✅ Ideas clave para llevarte

1. **Son DOS niveles, no dos listas contradictorias.** Arriba **4 familias** (categorías), abajo **6 interacciones** (las que existen). Las 6 viven adentro de las 4.

2. **El criterio único de las familias es "¿quién trajo la carga puesta?".** Los dos ya la tenían → **electrostática**. Uno se la induce al otro → **inductiva**. Ninguno la tenía → **dispersiva**.

3. **Sí, tres interacciones distintas son electrostáticas:** ion–ion, ion–dipolo y dipolo–dipolo. La intuición de la pregunta original era correcta.

4. **Las 6 salen de una matriz 3×3**, combinando de a dos los tres personajes: **ion (Q)**, **polar (μ)**, **no polar (α)**. No puede haber una séptima.

5. **El nombre te dice la familia.** ¿Dice "inducido"? Inductiva. ¿Dice London? Dispersiva. ¿No dice ninguna de las dos? Electrostática. No hay que memorizar el reparto.

6. **La unión H es un dipolo–dipolo con esteroides**, no una casilla nueva. Se le da familia propia porque es **33× más fuerte** y porque es la **única direccional** (y de ahí el hielo que flota y el ADN que aparea).

7. **Familia ≠ magnitud.** La familia electrostática contiene la más fuerte (ion–ion, 250) **y** la más débil (dipolo–dipolo, 0,6). No se puede deducir la fuerza de la familia.

8. **London (5) > dipolo–dipolo (0,6).** La trampa nº 1 de la clase. Una dispersiva le gana a una electrostática.

9. **El ion–ion es tramposo:** en un cristal es directamente el **enlace iónico**. Por eso su magnitud pisa el rango de los enlaces.

10. **Para ordenar T_eb / T_f / solubilidad usás la MAGNITUD, no la familia.** La familia es para razonar y para las preguntas teóricas textuales.

---

## 📌 Resumen operativo

**Los 3 personajes → la matriz → las 6 interacciones:**

| | Ion (Q) | Polar (μ) | No polar (α) |
|---|---|---|---|
| **Ion (Q)** | ion–ion | ion–dipolo | ion–dip. ind. |
| **Polar (μ)** | — | dipolo–dipolo (**+ unión H**) | dipolo–dip. ind. |
| **No polar (α)** | — | — | **London** |

**El reparto en familias (3 + 2 + 1 = 6):**

| Familia | Criterio | Interacciones | kJ/mol |
|---|---|---|---|
| **Electrostáticas** | los **dos** ya tienen | ion–ion · ion–dipolo · dipolo–dipolo | 250 · 15 · 0,6 |
| **Inductivas** | uno **induce** al otro | ion–dip. inducido · dipolo–dip. inducido | 10 · < 1 |
| **Dispersivas** | ninguno tiene (**instantáneos**) | **London** | 5 |
| **Unión H** | dipolo–dipolo **con FON**, direccional | *(subcaso de dipolo–dipolo)* | **20** |

**El orden de magnitudes (de memoria):**

$$\text{ion–ion}\,(250) \gg \text{unión H}\,(20) > \text{ion–dip}\,(15) > \text{ion–dip.ind}\,(10) > \boxed{\text{London}\,(5) > \text{dip–dip}\,(0{,}6)} > \text{dip–dip.ind}\,(<1)$$

**De qué depende cada una (se deduce del nombre, no se memoriza):**

$$E_{Q\text{-}Q} \propto \frac{Q_1Q_2}{d} \quad E_{Q\text{-}\mu} \propto \frac{Q_1\mu_2}{d^2} \quad E_{\mu\text{-}\mu} \propto \frac{\mu_1\mu_2}{d^3} \quad E_{Q\text{-}\alpha} \propto \frac{Q_1\alpha_2}{d^4} \quad E_{\text{London}} \propto \frac{\alpha_1\alpha_2}{d^6}$$

**Unión H — los dos requisitos:**

$$\boxed{\text{Unión H} \iff \begin{cases} \text{un } \mathbf{H} \text{ unido a } \mathbf{F,\,O,\,N} & \text{(DADOR)} \\ \text{un } \mathbf{F,\,O,\,N} \text{ con } \mathbf{par\ libre} & \text{(ACEPTOR)} \end{cases}}$$

**Referencias de escala:** agitación térmica a 25 °C (RT) ≈ **2,5 kJ/mol** · enlace covalente **150–1000 kJ/mol**

---

📖 **Apunte de la clase:** [`Clase4-Explicacion-Completa.md`](Clase4-Explicacion-Completa.md)
📋 **Machete:** sección **12** (Interacciones intermoleculares)
⬅️ **Requisito previo:** [`Clase3-Explicacion-Completa.md`](../Clase3/Clase3-Explicacion-Completa.md) — para saber si una molécula es polar o no
➡️ **Se aplica en:** [`Clase6(5nohay)/Clase6-Explicacion-Completa.md`](../Clase6(5nohay)/Clase6-Explicacion-Completa.md) — solubilidad y soluciones
