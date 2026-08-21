# Clase 6 — Explicación completa, diapositiva por diapositiva

**Materia:** Química General — ECyT / UNSAM — 2do Cuatrimestre 2026
**Docentes:** Norberto Boggio, Santiago Poklepovich
**Cursada:** Lunes y Miércoles de 18 a 22 hs

**Tema de la clase:** Soluciones · Propiedades de los sistemas materiales · Densidad · Sistemas homogéneos y heterogéneos · Proceso de disolución ("lo semejante disuelve a lo semejante") · Unidades de concentración (%m/m, %m/V, M, x, m, ppm) · Preparación de soluciones · Diluciones · Solubilidad y curvas de solubilidad

Este documento explica las **39 diapositivas** del PDF de la Clase 6:

| Archivo | Diapositivas | Contenido |
|---|---|---|
| `Clase5_NB-2026_Soluciones.pdf` | 39 | Propiedades físicas/químicas y extensivas/intensivas, densidad, sistemas materiales (homogéneo/heterogéneo, sustancia pura/mezcla), definición de solución, proceso de disolución, las unidades de concentración con ejemplos, relaciones útiles (moles, masas, volúmenes, densidades), cómo preparar una solución en el laboratorio, diluciones y la fórmula C₀V₀ = C_F V_F, solubilidad, saturación, curvas de solubilidad y solubilidad de gases |

> ⚠️ **Sobre la numeración.** El archivo del docente se llama `Clase5_...` pero acá va como **Clase 6** porque la clase 5 no se dio (de ahí el nombre de la carpeta, `Clase6(5nohay)`). El PDF original **no se renombra**. Dentro de este apunte lo cito como **P1**, ya que es el único PDF de la clase.

> **De qué se trata esta clase.** Hasta la Clase 4 la materia venía construyendo una cadena: *Lewis → geometría → polaridad → fuerzas intermoleculares → propiedades físicas*. La Clase 6 es el **primer uso cuantitativo** de todo eso.
>
> La pregunta cualitativa *"¿se disuelve?"* ya la sabés contestar (Clase 4 + sección 14 del machete: lo semejante disuelve a lo semejante). Acá aparecen las dos preguntas nuevas:
>
> 1. **¿CUÁNTO hay disuelto?** → unidades de concentración (%m/m, %m/V, M, x, m, ppm)
> 2. **¿CUÁNTO como máximo puede haber?** → solubilidad, saturación, curvas de solubilidad
>
> ⚠️ **Esta clase es de cuentas.** Casi no hay nada para "entender y ya": hay que poder pasar de una unidad de concentración a otra, preparar una solución y resolver una dilución. Es el tipo de ejercicio más mecánico del parcial, y por eso mismo el que más se equivoca por unidades.

> 💡 **Las tres palabras que no hay que confundir nunca en toda la clase:**
>
> | Símbolo | Qué es | También se abrevia |
> |---|---|---|
> | **sto** | **soluto** — la sustancia en MENOR cantidad | st |
> | **sv** | **solvente** — la sustancia en MAYOR cantidad | sv |
> | **sc** | **solución** — soluto + solvente, el sistema completo | sn |
>
> ⚠️ **El error nº 1 de la clase** es dividir por la masa del **solvente** cuando la fórmula pide la de la **solución**, o al revés. De todas las unidades, **sólo la molalidad (m) va sobre el solvente**. Todas las demás van sobre la solución.

---

# PARTE 1 — `Clase5_NB-2026_Soluciones.pdf`

## P1 — pág. 1 · Portada

Portada. Arriba, _ECyT – UNSAM 2do.Cuatri 2026_. Título grande: **SOLUCIONES**. A la izquierda una foto de vasos de precipitados y erlenmeyers con líquidos de colores (violeta, rosa, celeste, rojo, verde, naranja). A la derecha, un esquema con tres lupas rotuladas: **partículas del disolvente**, **partículas del soluto** y **partículas de la disolución**, mostrando cómo al volcar disolvente + soluto en un vaso se obtiene la **disolución**. Abajo, los docentes y el horario.

**Explicación:** el esquema de la derecha es la idea de toda la clase en un dibujo. Antes de mezclar hay **dos poblaciones separadas** de partículas: las del solvente interactuando entre sí y las del soluto interactuando entre sí. Después de mezclar hay **una sola población** donde las partículas de soluto están rodeadas por las de solvente. Eso es exactamente lo que se llama **disolución**, y es lo que va a justificar la regla de "lo semejante disuelve a lo semejante" en la pág. 7.

---

## P1 — pág. 2 · Propiedades de un sistema material

Dos clasificaciones en paralelo, cada una con un diagrama de llaves:

**Clasificación 1:**

| Propiedades | Definición |
|---|---|
| **Físicas** | Se pueden medir y observar **sin que cambie** la composición o identidad de la sustancia |
| **Químicas** | Se producen **con un cambio** en la composición o identidad de la sustancia |

**Clasificación 2:**

| Propiedades | Definición |
|---|---|
| **Extensivas** | **Dependen** de la cantidad de materia considerada |
| **Intensivas** | **NO dependen** de la cantidad de materia considerada |

Abajo: _**Importante: Caracterizan a los materiales!!!!**_ (con una flecha que baja desde "Intensivas").

**Explicación:** esta diapositiva es el andamio conceptual de toda la clase, y es lo que muchas veces se saltea. Prestá atención a **dónde apunta la flecha**: la aclaración "caracterizan a los materiales" sale de **Intensivas**, no de Extensivas. Ése es el punto.

Si te digo "esta muestra pesa 200 g" no te dije **qué es**: 200 g puede ser cualquier cosa. Si te digo "esta muestra tiene densidad 19,3 g/cm³" te dije que **es oro**, sin importar si tengo un gramo o una tonelada. Las propiedades intensivas son las que **identifican** un material; las extensivas sólo dicen cuánto hay.

| Tipo | Ejemplos |
|---|---|
| **Extensivas** | masa, volumen, peso, cantidad de moles, energía total, longitud |
| **Intensivas** | **densidad**, temperatura, punto de fusión, punto de ebullición, color, **concentración**, presión, índice de refracción, **solubilidad** |

⚠️ **El truco que hay que ver:** toda propiedad intensiva se puede construir como el **cociente de dos extensivas**. Densidad = masa/volumen. Concentración = cantidad de soluto/cantidad de solución. Por eso mismo la **concentración es intensiva**: si tomás la mitad de un vaso de agua con azúcar, tenés la mitad de masa y la mitad de volumen, pero **la misma concentración**. Esto va a ser clave en la pág. 4 para definir "homogéneo".

| Combinación | Resultado |
|---|---|
| extensiva / extensiva | **intensiva** (densidad, concentración, molaridad) |
| extensiva, al duplicar la muestra | se duplica |
| intensiva, al duplicar la muestra | **no cambia** |

---

## P1 — pág. 3 · ¿Cómo se mide la densidad (propiedad intensiva) de un material?

Dos columnas: **Sólido regular** (foto de un lingote de oro rectangular) y **Sólido irregular** (foto de una corona de oro). En el centro, recuadrado en rojo:

$$\boxed{\delta = \frac{m}{V}}$$

**Explicación:** la densidad se define igual siempre, pero **cómo medís el volumen** cambia según la forma del cuerpo:

| Caso | Cómo se obtiene V |
|---|---|
| **Sólido regular** (lingote, cubo, cilindro) | Con regla o calibre y la fórmula geométrica: $V = a \cdot b \cdot c$ |
| **Sólido irregular** (corona, piedra, tornillo) | Por **desplazamiento de líquido**: lo sumergís en una probeta con agua y medís cuánto sube el nivel |
| **Líquido** | Probeta, pipeta o matraz aforado, directo |

💡 **Por qué el lingote y la corona:** ésta es la **anécdota de Arquímedes** contada en dos fotos. El rey le pidió comprobar si su corona era de oro macizo o si el orfebre le había mezclado plata, **sin fundirla**. Como la corona es irregular, no se puede medir el volumen con una regla; la salida es medirlo por el agua desplazada. Con m y V calculás δ y lo comparás con el valor tabulado del oro (19,3 g/cm³). Si da menos, está adulterada.

⚠️ **La densidad va a reaparecer todo el tiempo en esta clase** — es el puente obligado entre **masa** y **volumen**. Cada vez que un ejercicio te dé un dato en gramos y te pida un resultado en litros (o al revés), la densidad es la que hace la conversión. Ojo con las unidades:

$$1\ \frac{\text{g}}{\text{cm}^3} = 1\ \frac{\text{g}}{\text{mL}} = 1000\ \frac{\text{kg}}{\text{m}^3} = 1\ \frac{\text{kg}}{\text{L}}$$

Y ojo con el símbolo: acá se usa **δ** (delta), pero en muchos libros es **ρ** (rho) o **d**. Es lo mismo.

---

## P1 — pág. 4 · Tipos de sistemas materiales — homogéneo vs heterogéneo

Diagrama: **Sistema Material** se abre en dos ramas.

| Rama | Definición | Foto |
|---|---|---|
| **Homogéneo** | Las propiedades intensivas son **las mismas** en cualquier porción de sistema considerado | Botella de Fernet Branca |
| **Heterogéneo** | Las propiedades intensivas **cambian** según la porción de sistema considerado | Galletitas con chips de chocolate |

De la rama heterogénea baja una flecha a **Fases**: _Existen límites definidos o superficies de discontinuidad denominados **INTERFACES**_.

**Explicación:** acá se cobra lo de la pág. 2. La definición de homogéneo **no** es "se ve parejo" (eso es apariencia y engaña): es **operativa**. Tomás una porción de acá, medís densidad, color, índice de refracción; tomás otra porción de allá y medís lo mismo. Si los números coinciden, es homogéneo.

- El **fernet** es homogéneo: cualquier sorbo tiene la misma graduación alcohólica y el mismo color. Es una **solución** (alcohol + agua + extractos).
- La **galletita** es heterogénea: si morfás el chip tenés chocolate, si morfás al lado tenés masa. La densidad, el color y el sabor **cambian** según la porción.

**Fase** = cada porción con propiedades intensivas uniformes. La **interfaz** es el límite donde las propiedades saltan de golpe (el borde del chip, la superficie del agua, el borde de una burbuja).

| Concepto | Definición corta |
|---|---|
| **Fase** | Porción homogénea de un sistema, con propiedades intensivas uniformes |
| **Interfaz** | Superficie de discontinuidad que separa dos fases |
| **Sistema homogéneo** | **1 sola fase** |
| **Sistema heterogéneo** | **2 o más fases** → tiene interfaces |

⚠️ **Trampas clásicas:**
- **Fase ≠ componente.** El agua con hielo tiene **1 componente** (H₂O) y **2 fases** (sólida y líquida).
- **Fase ≠ porción física.** Si tirás 20 cubitos en un vaso de agua, no hay 21 fases: hay **2** (todo el hielo es una fase, toda el agua es la otra), porque todos los cubitos tienen las mismas propiedades intensivas.
- La **leche** parece homogénea a ojo pero es heterogénea (emulsión de gotitas de grasa) — se ve al microscopio. La escala importa.

---

## P1 — pág. 5 · Tipos de sistemas materiales — la tabla de doble entrada

Tabla 2×2 con fotos en cada celda:

| | **Sustancia pura** (1 componente) | **Mezcla** (2 o más componentes) |
|---|---|---|
| **Homogéneo** (1 fase) | Vaso con agua | Botella de alcohol etílico (etiqueta "ALCOHOL") |
| **Heterogéneo** (2 o más fases) | Vaso con agua **y cubitos de hielo** | Vaso con agua y aceite · lámpara de lava |

**Explicación:** ésta es **la** diapositiva de la primera parte, y es la que hay que poder reconstruir sola. Cruza **dos criterios independientes** que nada tienen que ver entre sí:

- **¿Cuántos componentes?** (cuántas sustancias químicas distintas) → sustancia pura o mezcla
- **¿Cuántas fases?** (cuántas regiones con propiedades intensivas distintas) → homogéneo o heterogéneo

Las cuatro celdas, con lo que hay que retener de cada una:

| Celda | Ejemplo | Componentes | Fases | Comentario |
|---|---|---|---|---|
| Pura + homogénea | Agua destilada | 1 | 1 | El caso más simple |
| Pura + heterogénea | **Agua + hielo** | **1** | **2** | ⚠️ Un solo componente en dos estados |
| Mezcla + homogénea | **Alcohol comercial** (etanol + agua) | 2 | **1** | ⚠️ **Esto es una SOLUCIÓN** |
| Mezcla + heterogénea | Agua + aceite, lámpara de lava | 2 | 2 | Se ve la interfaz |

⚠️ **La celda "pura + heterogénea" (agua con hielo) es la que rompe la intuición** y por eso es la que se pregunta. Que sea una sola sustancia no te garantiza una sola fase: los cambios de estado generan fases distintas sin cambiar el componente.

💡 **Acá aparece la definición que da nombre a la clase:** la celda **mezcla + homogénea** es exactamente lo que se llama **solución**. La clase entera trata de esa única casilla de la tabla.

La **lámpara de lava** funciona por lo de la pág. 3 y 4 juntas: la cera y el líquido son inmiscibles (heterogéneo) y sus densidades son casi iguales; la lamparita de abajo calienta la cera, la dilata, le baja la densidad y la cera sube. Arriba se enfría, se contrae, se vuelve más densa y baja.

---

## P1 — pág. 6 · Soluciones — la definición

Texto:

> Una **solución** es una **mezcla homogénea** entre dos o más sustancias que **no reaccionan entre sí**.
> El **soluto** es (son) la(s) sustancia(s) presentes en **menor(es) cantidad(es)**.
> El **solvente** es la sustancia presente en **mayor cantidad**.

Y una tabla escaneada:

| Componente 1 | Componente 2 | Estado de la solución resultante | Ejemplos |
|---|---|---|---|
| Gas | Gas | Gas | **Aire** |
| Gas | Líquido | Líquido | Agua gaseosa (CO₂ en agua) |
| Gas | Sólido | Sólido | H₂ gaseoso en paladio |
| Líquido | Líquido | Líquido | Etanol en agua |
| Sólido | Líquido | Líquido | **NaCl en agua** |
| Sólido | Sólido | Sólido | **Bronce (Cu/Zn)**, soldadura (Sn/Pb) |

**Explicación:** desarmá la definición palabra por palabra, porque cada pedazo excluye algo:

| Pedazo | Qué excluye |
|---|---|
| "**mezcla**" | Excluye las **sustancias puras**: hacen falta 2 componentes o más |
| "**homogénea**" | Excluye las mezclas heterogéneas: **1 sola fase**, sin interfaces |
| "**que no reaccionan entre sí**" | Excluye la **reacción química**: los componentes siguen siendo los mismos y se pueden **volver a separar por métodos físicos** (destilar, evaporar) |

⚠️ La cláusula "no reaccionan" es la más fina. Si tirás Na metálico en agua no obtenés una solución de sodio: obtenés NaOH + H₂, que es una **reacción**. El sodio ya no está ahí. En cambio si tirás NaCl, los iones Na⁺ y Cl⁻ siguen ahí, sólo que **solvatados** — y los recuperás evaporando el agua.

⚠️ **Soluto y solvente se definen por CANTIDAD, no por estado.** Nada obliga a que el solvente sea el líquido:

- En el **aire**, el solvente es el **N₂** (78 %) y los solutos son O₂ (21 %), Ar, CO₂.
- En el **bronce**, todo es sólido: el solvente es el Cu y el soluto el Zn. Se llama **aleación**, y es una solución sólida.
- En una solución de HCl al 90 %, el **soluto es el agua**, aunque el agua sea "el solvente universal".

💡 **La tabla muestra que las soluciones existen en los tres estados de agregación.** La única combinación que falta es líquido en gas — una gota de agua en aire no forma solución, forma niebla, que es heterogénea.

📡 **Conexión con Telecomunicaciones:** la fila **"H₂ gaseoso en paladio"** parece un caso exótico y es tecnología pura: el paladio absorbe cientos de veces su volumen de H₂ en los huecos de su red cristalina, y con eso se hacen **sensores de hidrógeno** y purificadores. Y más importante para la carrera: **los semiconductores y la fibra óptica son soluciones sólidas**. El silicio dopado con fósforo o boro es literalmente una solución sólido-en-sólido con concentraciones del orden de **ppm o ppb** (págs. 18 y 19), y esas ppm son las que definen si el material es tipo n o tipo p. La fibra óptica es sílice (SiO₂) dopada con GeO₂ para subirle el índice de refracción al núcleo. Toda la microelectrónica es control fino de concentración.

---

## P1 — pág. 7 · Proceso de disolución — "lo similar disuelve lo similar"

Título recuadrado: **Proceso de disolución**. Debajo, en cursiva: _"lo similar disuelve lo similar"_. Tres preguntas con estructuras dibujadas:

1. **¿El hexano es soluble en CCl₄? ¿Por qué?** — se dibuja el hexano completo (cadena de 6 C con todos sus H) y el CCl₄ (C central tetraédrico con 4 Cl). En violeta: _Ambas son moléculas **no polares**_.
2. **¿La glucosa es soluble en agua?** — se dibuja la glucosa en su forma de anillo (piranosa) con los OH y el CH₂OH, y el agua con sus cargas parciales δ²⁻ sobre el O y δ⁺ sobre cada H. En rojo: _Ambas son moléculas **polares**_.
3. **¿El NaCl es soluble en agua?** — se dibuja la red cristalina del NaCl (esferas verdes y violetas alternadas), rotulando Na⁺ y Cl⁻. **No tiene respuesta escrita.**

Al pie, en cursiva: _Cuando algo se disuelve **cambia la interacción con sí mismo por la interacción con otro**, con lo cual deben de ser similares._

**Explicación:** esta diapositiva es el **enganche directo con la Clase 4**. La frase del pie es la que da el mecanismo, y es mucho más precisa que el eslogan. Disolver es un **balance energético de tres términos**:

$$\underbrace{\text{romper sto—sto}}_{\text{cuesta energía}} + \underbrace{\text{romper sv—sv}}_{\text{cuesta energía}} \longrightarrow \underbrace{\text{formar sto—sv}}_{\text{libera energía}}$$

Se disuelve si lo que **liberás** al formar interacciones soluto–solvente compensa lo que **gastaste** rompiendo las de cada uno consigo mismo. Por eso las fuerzas tienen que ser **del mismo tipo y de magnitud comparable**: si el soluto se mantiene unido con uniones H de 20 kJ/mol y el solvente sólo le puede ofrecer London de 1 kJ/mol, no hay negocio y no se disuelve.

Las tres respuestas:

| Caso | Soluto: fuerza consigo mismo | Solvente: fuerza consigo mismo | Fuerza sto–sv posible | ¿Se disuelve? |
|---|---|---|---|---|
| **Hexano en CCl₄** | London | London | London | ✓ Sí |
| **Glucosa en agua** | Unión H (tiene 5 OH) | Unión H | **Unión H** | ✓ Sí |
| **NaCl en agua** | **Ion–ion** (fortísima, red cristalina) | Unión H | **Ion–dipolo** | ✓ Sí |

💡 **El caso del NaCl es el que el docente deja sin respuesta escrita en la diapositiva** — probablemente porque lo contesta de palabra, y por eso conviene tenerlo claro. Es el más interesante porque **rompe el eslogan**: el NaCl no es "polar", es **iónico**, y el agua no tiene iones. Sin embargo se disuelve, y muy bien. ¿Por qué?

Porque romper la red iónica cuesta muchísimo (la **energía de red** del NaCl es ~787 kJ/mol), pero cada ion queda rodeado por **unas 6 moléculas de agua** orientadas con el dipolo apuntándole, y la interacción **ion–dipolo** es la segunda más fuerte de la tabla de la Clase 4. La suma de todas esas interacciones (la **energía de hidratación**, ~784 kJ/mol para el NaCl) compensa casi exactamente la energía de red. Por eso el NaCl se disuelve, y encima **casi sin cambio de temperatura** (la disolución es apenas endotérmica, ~+4 kJ/mol).

⚠️ Y por eso mismo el **AgCl NO se disuelve** aunque también sea iónico: su energía de red es más grande que lo que el agua le puede devolver. "Iónico" no implica "soluble en agua" automáticamente.

⚠️ **La glucosa es el ejemplo a tener a mano para "polar":** tiene **5 grupos —OH**, todos dadores y aceptores de unión H. Por eso el azúcar se disuelve en agua hasta niveles absurdos — el almíbar es eso.

---

## P1 — pág. 8 · Lo "semejante disuelve a lo semejante" — el experimento del I₂

Título: **Lo "semejante disuelve a lo semejante"**. Arriba a la izquierda, la estructura de Lewis del **I₂**: dos I unidos por un enlace simple, cada uno con **3 pares libres**.

Dos fotos de tubos de ensayo sobre fondo negro:

| Izquierda | Derecha |
|---|---|
| **I₂ en agua NO se disuelve** — el tubo tiene líquido **incoloro/celeste** y un grumo oscuro de I₂ sólido en el fondo, sin disolverse | **I₂ en CCl₄ se disuelve MUY bien!** — el tubo está **violeta/magenta intenso** y homogéneo |

Debajo de cada tubo, la molécula del solvente: el **agua** con δ²⁻ en el O y δ⁺ en los H (polar), y el **CCl₄** tetraédrico (no polar).

Al pie: _Las fuerzas de interacción del soluto deben ser **similares (en magnitud)** a las fuerzas de interacción del solvente._

**Explicación:** el mismo soluto, dos solventes, resultado opuesto. Es el experimento que demuestra que **la solubilidad no es una propiedad del soluto solo**: es una propiedad **del par** soluto–solvente.

| | I₂ (soluto) | H₂O | CCl₄ |
|---|---|---|---|
| **Polaridad** | **No polar** (diatómica homonuclear, μ = 0) | **Polar** (μ = 1,85 D) | **No polar** (tetraédrica simétrica, μ = 0) |
| **Fuerza dominante** | London (¡106 e⁻, muy polarizable!) | **Unión H** | London (74 e⁻) |
| **Con I₂ podría formar** | — | Sólo dipolo–dipolo inducido (débil) | **London ↔ London** ✓ |
| **Resultado** | | ❌ No se disuelve | ✓ Se disuelve muy bien |

El argumento fino: para meter una molécula de I₂ en el agua hay que **abrir un hueco** en la red de uniones hidrógeno, y eso cuesta ~20 kJ/mol por unión rota. Lo único que el I₂ le puede devolver al agua es una interacción **dipolo–dipolo inducido** de menos de 1 kJ/mol. El balance da negativo → no se disuelve. Con el CCl₄ el intercambio es London por London, prácticamente parejo → se disuelve.

⚠️ **El color no es decorativo, es el dato experimental.** El violeta intenso del tubo derecho **es** la prueba de que hay I₂ molecular disuelto: el I₂ absorbe en el verde-amarillo (~520 nm) y transmite el violeta. Si en el tubo izquierdo el líquido queda incoloro, es porque no hay I₂ en solución. **Así se mide una concentración en el laboratorio**: por cuánta luz absorbe la solución (espectrofotometría — ver `Clase1/Clase1-Espectroscopia-Profundizacion.md`).

💡 **Y de yapa:** esto es la base de la **extracción líquido-líquido**. Si tenés I₂ en agua y le agregás CCl₄ (inmiscible con el agua y más denso), el I₂ **migra** a la fase orgánica y te queda todo el violeta abajo. Separás las fases con una ampolla de decantación y listo.

---

## P1 — pág. 9 · Componentes de una solución (sc)

Título recuadrado: **Componentes de una solución (sc)**. Debajo: **Solvente (sv)** en azul **y Soluto (sto)** en rojo.

Tres imágenes:
1. Un matraz aforado con líquido amarillo y una lupa que amplía a nivel molecular: esferas naranjas grandes con H (el solvente) rodeando esferas violetas (el soluto). Rótulos: _Soluto_ / _Solvente_.
2. Un vaso de precipitados con solución y una lupa que muestra **esferas verdes rodeadas de moléculas de agua**.
3. Un esquema con **Na⁺** (amarillo) y **Cl⁻** (celeste), cada uno **rodeado de moléculas de agua orientadas**: los H (δ⁺) apuntando al Cl⁻ y los O (δ⁻) apuntando al Na⁺.

Al pie, la definición general:

$$\text{Concentración} = \frac{\text{Cantidad de Soluto}}{\text{Cantidad de Solución (o solvente)}}$$

**Explicación:** el tercer esquema es **el dibujo que hay que saber hacer en el parcial**: la **solvatación** (o **hidratación**, cuando el solvente es agua). Fijate en la **orientación**, que es lo que se corrige:

| Ion | Qué le apunta | Por qué |
|---|---|---|
| **Na⁺** (catión) | El **O** del agua (δ⁻) | Cargas opuestas se atraen |
| **Cl⁻** (anión) | Los **H** del agua (δ⁺) | Ídem |

Esa capa de moléculas de solvente orientadas alrededor de cada ion se llama **esfera de solvatación**. Es lo que **impide que los iones se vuelvan a juntar** para reformar el cristal: quedan apantallados.

⚠️ **La fórmula del pie tiene un paréntesis que es una bomba: "(o solvente)".** Ahí está el 90 % de los errores de la clase. **Casi todas** las unidades de concentración van sobre la **solución**; **una sola** (la molalidad) va sobre el **solvente**. Tenelo presente desde ahora:

| Unidad | Denominador |
|---|---|
| % m/m, % m/V, % V/V, M, ppm | **SOLUCIÓN** |
| **molalidad (m)** | **SOLVENTE** ⚠️ |
| **fracción molar (x)** | **TOTALES** = n_sto + n_sv (que en moles es lo mismo que la solución) |

💡 Y notá que la definición es **un cociente entre dos cantidades extensivas** → la concentración es **intensiva** (pág. 2). Por eso una gota de la solución tiene la misma concentración que todo el matraz. Eso es exactamente lo que hace que las diluciones de la pág. 28 funcionen.

---

## P1 — pág. 10 · Componentes de una solución — la escala cualitativa

Texto: _Las propiedades de una solución dependen de la proporción de soluto que contengan. **Cualitativamente** hablamos de soluciones:_

| Tipo | Definición | Ejemplo del docente |
|---|---|---|
| ➢ **Diluidas** | poca proporción de soluto | Una taza de té con **½ cucharadita** de azúcar |
| ➢ **Concentradas** | bastante proporción de soluto | Una taza de té con **4 cucharaditas** de azúcar |
| ➢ **Saturadas** | **no admiten** mayor proporción de soluto | Una taza de té con **140 cucharaditas** de azúcar |

**Explicación:** ésta es la escala **cualitativa**, es decir, sin números. Sirve para hablar, no para calcular — de ahí que la palabra "Cualitativamente" esté en rojo en la diapositiva.

Lo importante es que **"diluida" y "concentrada" son relativas** (no hay un número que separe una de otra: depende de con qué compares), pero **"saturada" es absoluta**: es un límite físico real, medible y tabulado, que depende del par soluto–solvente y de la temperatura. Ese límite tiene nombre propio y es el tema de las págs. 30 a 38: se llama **solubilidad**.

⚠️ El ejemplo de las 140 cucharaditas es literal, no una exageración: la solubilidad de la sacarosa en agua a temperatura ambiente es del orden de 2 g por gramo de agua. En una taza de 200 mL entran unos 400 g de azúcar, que son efectivamente unas 100–140 cucharaditas. A partir de ahí, todo lo que agregues **se va al fondo sin disolverse**.

| Escala | Es | Depende de |
|---|---|---|
| Diluida / concentrada | **Relativa**, cualitativa | Con qué la compares |
| **Saturada** | **Absoluta**, medible | Soluto, solvente y **temperatura** |

---

## P1 — pág. 11 · Concentración — la escala visual

Diapositiva sin título, sólo imágenes. Arriba a la izquierda, una **foto real de laboratorio**: una gradilla con 8 tubos de ensayo con soluciones de color magenta en intensidad creciente, un erlenmeyer con la solución concentrada y una piseta azul. En diagonal, en rojo grande: **CONCENTRACIÓN**.

Abajo, un esquema de 7 tubos dibujados: el primero casi transparente, y van pasando por rosa pálido, rosa, rojo, hasta rojo intenso. Dos flechas:

`←  Más diluída` · `Más concentrada  →`

**Explicación:** es la traducción visual de la pág. 10 y sirve de puente a la parte cuantitativa. La idea es que **la concentración es un continuo**: no hay tres cajones (diluida / concentrada / saturada), hay un eje sobre el que la solución se mueve.

💡 **Y hay un dato técnico escondido:** que el color se intensifique de manera regular con la concentración no es casualidad — es la **ley de Lambert-Beer**. La absorbancia es proporcional a la concentración:

$$A = \varepsilon \cdot \ell \cdot c$$

donde ε es el coeficiente de absorción molar del soluto, ℓ el camino óptico (el ancho del tubo) y c la concentración. Ésta es la razón práctica por la que en el laboratorio se prepara una **serie de diluciones** como la de la foto: se mide la absorbancia de cada una, se arma la **curva de calibración** A vs c, y con eso se determina la concentración de una muestra desconocida midiéndole el color. La pág. 27 muestra cómo se preparan esas diluciones.

📡 Es exactamente el mismo principio que la **atenuación en fibra óptica**: la potencia decae exponencialmente con la longitud del medio, y la ley de Beer es la versión logarítmica de eso. Los dB/km de una fibra son primos hermanos de la absorbancia.

---

## P1 — pág. 12 · Concentración — la lista de las unidades

Título recuadrado: **Concentración**. Debajo, la definición general:

$$\text{Concentración} = \frac{\text{Cantidad de Soluto}}{\text{Cantidad de Solución (o solvente)}}$$

Y la lista numerada:

1. **% m/m**
2. **% m/V**
3. **Molaridad (M)**
4. **% V/V**
5. **Fracción molar (x)**
6. **Molalidad (m)**
7. **Partes por millón (ppm)**

**Explicación:** ésta es la **hoja de ruta de las próximas ocho diapositivas**. Todas las unidades son el mismo cociente; lo único que cambia es **en qué unidad mido el numerador y en qué unidad mido el denominador**. Nada más. Si tenés eso claro, no hay nada que memorizar mal:

| # | Unidad | Numerador (soluto) | Denominador | Factor |
|---|---|---|---|---|
| 1 | **% m/m** | masa | masa de **solución** | × 100 |
| 2 | **% m/V** | masa (g) | volumen de **solución** (cm³) | × 100 |
| 3 | **M** (molaridad) | **moles** | volumen de **solución** (L) | — |
| 4 | **% V/V** | volumen | volumen de **solución** | × 100 |
| 5 | **x** (fracción molar) | **moles** | **moles totales** | — (queda entre 0 y 1) |
| 6 | **m** (molalidad) | **moles** | masa de **SOLVENTE** (kg) ⚠️ | — |
| 7 | **ppm** | masa (mg) | masa de **solución** (mg) | × 10⁶ |

⚠️ **Ojo con el orden del PDF:** la lista dice 1) %m/m, 2) %m/V, 3) M, 4) %V/V… pero **las diapositivas siguientes no van en ese orden**. El orden real en el que se explican es: %m/m (pág. 13) → **fracción molar** (pág. 14) → %m/V (pág. 15) → Molaridad (pág. 16) → Molalidad (pág. 17) → ppm (págs. 18 y 19).

⚠️⚠️ **Y el % V/V nunca se explica en una diapositiva propia.** Está en la lista pero el deck no tiene la fórmula. Por si sale, es la análoga obvia y se usa para soluciones líquido-en-líquido (las bebidas alcohólicas se rotulan así):

$$\% V/V = \frac{V_{sto}}{V_{sc}} \cdot 100$$

Un fernet de 39° es 39 % V/V: 39 mL de etanol cada 100 mL de bebida. ⚠️ Y acá pega fuerte lo de la pág. 20: **los volúmenes no son aditivos**, así que el denominador es el volumen **medido** de la solución, no la suma de los volúmenes que mezclaste.

💡 **Cómo elegir cuál usar, en la práctica:**

| Situación | Unidad natural |
|---|---|
| Reacciones químicas (necesitás moles) | **M** (molaridad) |
| Un rótulo comercial de un sólido en líquido | % m/m o % m/V |
| Contaminantes, dopantes, trazas | **ppm / ppb** |
| Propiedades coligativas (ascenso ebulloscópico, etc.) | **m** (molalidad) y **x** |
| Bebidas alcohólicas | % V/V |

---

## P1 — pág. 13 · % m/m: porcentaje masa en masa

Título recuadrado: **% m/m: porcentaje masa en masa**.

**Masa de soluto (en gramos) cada 100 g de solución.**

$$\boxed{\% \, m/m = \frac{m_{sto}}{m_{sc}} \cdot 100}$$

_No es necesario expresarla siempre en gramos, pero siempre la masa de soluto y la de la solución deben estar en las **MISMAS UNIDADES**!!_

**Ejemplo:** una solución acuosa de HCl contiene 0,5 g de **soluto** (HCl) por cada 100 g de **solución**, y otra contiene 0,5 kg de **soluto** por cada 100 kg de **solución**. ¿Son de igual concentración?

$$\% m/m = \frac{0,5\ \cancel{g}}{100\ \cancel{g}} \cdot 100 = 0,5 \qquad\qquad \% m/m = \frac{0,5\ \cancel{kg}}{100\ \cancel{kg}} \cdot 100 = 0,5$$

**Explicación:** la unidad más simple y la más robusta de todas. El ejemplo está puesto para mostrar **por qué**: el porcentaje masa en masa es **adimensional**, porque arriba y abajo se cancelan las unidades. Sí: en las dos soluciones hay mil veces más HCl en una que en otra en términos **absolutos**, pero la **proporción** es idéntica, y la concentración es una proporción. **Las dos son 0,5 % m/m.**

⚠️ **Lo único que hay que respetar es que arriba y abajo estén en la MISMA unidad.** g/g, kg/kg, mg/mg, toneladas/toneladas: da igual. Lo que **no** podés hacer es g arriba y kg abajo sin convertir.

⚠️ **El denominador es la masa de SOLUCIÓN, no la de solvente.** Si el problema te dice "se disuelven 20 g de sal en 80 g de agua", la masa de solución es **20 + 80 = 100 g** (las masas **sí** son aditivas, pág. 20), así que es 20 % m/m — **no** 20/80 = 25 %.

💡 **Ventaja del % m/m sobre todos los demás:** es la **única unidad que no depende de la temperatura**. La masa no se dilata; el volumen sí. Por eso la molaridad de una solución cambia si la calentás (el volumen aumenta, los moles no) pero el % m/m no. Y por eso los reactivos comerciales vienen rotulados en % m/m (el HCl concentrado es 37 % m/m, el H₂SO₄ es 98 % m/m).

📝 **Cómo se lee un rótulo comercial:** "HCl 37 % m/m, δ = 1,19 g/mL" quiere decir que en 100 g de esa botella hay 37 g de HCl puro y 63 g de agua. Para pasarlo a molaridad hacen falta las dos cosas (el %, para saber cuánto soluto, y la δ, para pasar masa de solución a volumen). Es el ejercicio clásico:

$$M = \frac{\%m/m \cdot \delta_{sc} \cdot 10}{Mr_{sto}} = \frac{37 \cdot 1{,}19 \cdot 10}{36{,}5} \approx 12{,}1\ \text{M}$$

(el "10" sale de pasar g/mL a g/L y dividir por 100 del porcentaje).

---

## P1 — pág. 14 · Fracción molar

Título recuadrado: **Fracción molar**.

_La fracción molar de soluto expresa la cantidad de moles de soluto por moles totales (soluto + solvente):_

$$\boxed{\chi_{st} = \frac{n_{sto}}{(n_{sto} + n_{sv})}}$$

_Fracción molar siempre está acotada entre 0 y 1_ ( $0 < \chi_{st} < 1$ )

_De la misma manera se puede expresar la fracción molar de solvente como la cantidad de moles de solvente por moles totales:_

$$\boxed{\chi_{sv} = \frac{n_{sv}}{(n_{sto} + n_{sv})}}$$

**Explicación:** la fracción molar cuenta **partículas**, no masa ni volumen. Es la única unidad de la lista que es una fracción "honesta" en el sentido matemático: no lleva ni ×100 ni ×10⁶, y por construcción está entre 0 y 1.

⚠️ **La propiedad que se pregunta y que no está escrita en la diapositiva:** la suma de todas las fracciones molares de un sistema vale exactamente 1.

$$\boxed{\chi_{sto} + \chi_{sv} = 1} \qquad \text{y en general} \qquad \sum_i \chi_i = 1$$

Es inmediato de ver: sumás las dos fórmulas y el numerador te queda igual al denominador. En la práctica esto es **un regalo**: si te piden las dos y calculaste una, la otra sale restando. Y sirve como **control de errores**: si te dan tres fracciones molares y no suman 1, algo está mal.

⚠️ **La trampa de la fracción molar:** hay que pasar **todo a moles primero**, incluida el agua. El error clásico es olvidarse de que el solvente también tiene moles:

$$n_{sv} = \frac{m_{sv}}{Mr_{sv}} \qquad\text{con}\qquad Mr(\text{H}_2\text{O}) = 18\ \text{g/mol}$$

📝 **Ejemplo mental para fijarlo:** 1 mol de glucosa (180 g) en 1 L de agua (1000 g = **55,6 mol**).

$$\chi_{glu} = \frac{1}{1 + 55{,}6} = 0{,}0177 \qquad \chi_{H_2O} = \frac{55{,}6}{56{,}6} = 0{,}982$$

Y suman 1 ✓. Fijate qué chica queda la fracción molar del soluto: **el agua aporta muchísimos moles** porque su masa molar es muy baja. Ése es el número que sorprende: 1 L de agua son 55,6 mol.

💡 **Para qué sirve:** la fracción molar es la unidad natural de las **propiedades coligativas** (ley de Raoult: la presión de vapor de una solución es $P = \chi_{sv} \cdot P^0_{sv}$) y de las **mezclas de gases** (ley de Dalton: la presión parcial de cada gas es $p_i = \chi_i \cdot P_{total}$). En el aire, χ(N₂) = 0,78 y χ(O₂) = 0,21.

---

## P1 — pág. 15 · % m/V: porcentaje masa en volumen

Título recuadrado: **% m/V: porcentaje masa en volumen**.

_Se expresa como la masa de soluto (en gramos) por 100 cm³ de solución._

$$\boxed{\% \, m/V = \frac{m_{sto}\ (g)}{V_{sc}\ (cm^3)} \cdot 100}$$

_Tener en cuenta que 1 cm³ es igual a 1 mL, por lo tanto el volumen de la solución puede ser expresado en **centímetros cúbicos (o mililitros)**._

**Ejemplo:** Expresar la concentración en %m/V de una solución acuosa de HCl que contiene 1,5 g de soluto (HCl) por cada 75 cm³ de solución.

$$\% m/V = \frac{1{,}5\ g}{75\ cm^3} = 0{,}02\ ^g/_{cm^3}$$

**Explicación:** a diferencia del % m/m, acá las unidades **NO se cancelan**: arriba hay masa y abajo volumen. Por eso el % m/V **sí** exige unidades fijas: **gramos arriba, cm³ (= mL) abajo**. No es negociable, porque el "100" de la fórmula ya asume esas unidades.

⚠️⚠️ **CUIDADO: hay un error en el ejemplo de la diapositiva.** La fórmula del recuadro tiene el **×100**, pero en la cuenta del ejemplo **se lo olvidaron**. El resultado que muestra (0,02 g/cm³) es sólo el cociente m/V, sin el ×100. La cuenta correcta es:

$$\% m/V = \frac{1{,}5\ g}{75\ cm^3} \cdot 100 = \boxed{2\ \%\ m/V}$$

Y tiene sentido: 1,5 g en 75 cm³ es lo mismo que **2 g en 100 cm³**, y el % m/V se define justamente como los gramos que hay cada 100 cm³. Que el resultado esté escrito en "g/cm³" es la pista de que quedó a mitad de camino: **un porcentaje es adimensional**, no puede tener unidades de densidad. Si en el parcial te sale un %m/V con unidades, revisá la cuenta.

⚠️ **No confundas % m/V con densidad**, aunque las dos sean masa/volumen:

| | Numerador | Denominador |
|---|---|---|
| **δ de la solución** | masa de **TODA** la solución | volumen de la solución |
| **% m/V** | masa del **SOLUTO** solo | volumen de la solución (× 100) |

💡 **Dónde se usa en la vida real:** es la unidad de la **medicina y la farmacia**. El suero fisiológico es **NaCl 0,9 % m/V** (0,9 g de NaCl cada 100 mL de solución). El suero glucosado es **glucosa 5 % m/V**. Cada vez que veas un rótulo de un medicamento inyectable, está en % m/V, porque en el hospital se mide **volumen** (con una jeringa) y se necesita saber la **masa** de droga administrada.

---

## P1 — pág. 16 · Molaridad

Título recuadrado: **Molaridad**.

_Se expresa como moles de soluto por litro de solución._

$$\boxed{M = \frac{n_{sto}}{V_{sc}\ (L)}}$$

_V_sn(L) el volumen de la solución se expresa en **litros**._
_La unidad es **Molar**, se abrevia **M** y equivale a mol/L ó mol L⁻¹._

**Ejemplo:** ¿Cuál es la concentración molar de una solución acuosa de HCl que contiene 0,5 moles de soluto (HCl) por cada 0,2 litros de solución?

$$M = \frac{0{,}5\ mol}{0{,}2\ L} = 2{,}5\ M = 2{,}5\ ^{mol}/_L = 2{,}5\ mol\ L^{-1}$$

**Explicación:** **ésta es LA unidad de concentración de la química.** Si tuvieras que quedarte con una sola, es ésta, y es la que va a aparecer en todos los ejercicios de reacciones, estequiometría, pH y equilibrio. La razón es que **arriba hay moles**: y los moles son la moneda con la que se cuentan las reacciones químicas. Un balanceo te dice "1 mol de A reacciona con 2 de B", nunca "12 g de A con 8 g de B".

⚠️ **Las tres cosas que hay que respetar, siempre:**

| Requisito | Por qué |
|---|---|
| **Moles** arriba, no gramos | Si te dan gramos, convertís: $n = m / Mr$ |
| **LITROS** abajo, no mL | Si te dan mL, dividís por 1000. ⚠️ Éste es el error más frecuente de la clase |
| Volumen de **SOLUCIÓN**, no de solvente | Los volúmenes no son aditivos (pág. 20) |

💡 **La fórmula que en la práctica usás más que la propia definición** es la despejada, porque el 90 % de los ejercicios te piden cuánto pesar (pág. 22) o cuánto volumen tomar:

$$\boxed{n_{sto} = M \cdot V_{sc}(L)} \qquad\qquad \boxed{m_{sto} = M \cdot V_{sc}(L) \cdot Mr_{sto}}$$

Ésa segunda es la fórmula de la pág. 22, ya armada de una sola vez.

⚠️ **La debilidad de la molaridad: DEPENDE DE LA TEMPERATURA.** El volumen de la solución se dilata al calentarse, los moles no cambian, entonces M baja. Es chico el efecto (~0,02 % por °C en agua) pero conceptualmente importante, y es la razón por la que existe la molalidad de la pág. 17 y por la que los reactivos comerciales se rotulan en % m/m.

⚠️ **Molaridad ≠ molalidad.** Se escriben casi igual (**M** vs **m**) y es el error de notación clásico. En soluciones acuosas **diluidas** los números salen parecidos (porque 1 L de solución ≈ 1 kg de solvente), y eso te puede hacer creer que son lo mismo. **No lo son.**

---

## P1 — pág. 17 · Molalidad

Título recuadrado: **Molalidad**.

_Se expresa como moles de soluto por Kg de solvente._

$$\boxed{m = \frac{n_{sto}}{m_{sv}\ (kg)}}$$

_La masa de **solvente** debe expresarse en **kilogramos**._
_La unidad es **molal**, se abrevia **m** y equivale a mol/kg ó mol kg⁻¹._

**Ejemplo:** ¿Cuál es la concentración molal de una solución acuosa de HCl que contiene 0,5 moles de soluto (HCl) en 1 kg de solvente?

$$m = \frac{0{,}5\ mol}{1\ kg} = 0{,}5\ mol\ kg^{-1} = 0{,}5\ ^{mol}/_{kg}$$

**Explicación:** ⚠️⚠️ **ÉSTA es la única unidad de toda la clase cuyo denominador es el SOLVENTE y no la solución.** Marcala, subrayala, ponele un post-it. Es la trampa más segura del parcial: te dan un ejercicio de molalidad, usás la masa de la solución en lugar de la del solvente, y el resultado da parecido (por eso no te das cuenta) pero está mal.

$$m = \frac{n_{sto}}{m_{\mathbf{SOLVENTE}}(kg)} \qquad \text{NO} \qquad \frac{n_{sto}}{m_{solución}}$$

**¿Y para qué existe, si la molaridad es más cómoda?** Por exactamente el problema de la pág. 16: la molaridad depende de la temperatura y la molalidad **no**, porque **las dos cantidades que la definen (moles y masa) son independientes de T**. Si calentás la solución, la molaridad baja y la molalidad queda igual.

| | Molaridad **M** | Molalidad **m** |
|---|---|---|
| Fórmula | n_sto / V_sc(L) | n_sto / m_sv(**kg**) |
| Denominador | **Solución**, en volumen | **Solvente**, en masa |
| ¿Depende de T? | **SÍ** (el volumen se dilata) | **NO** |
| Se usa para | Reacciones, estequiometría, pH | **Propiedades coligativas** |
| Unidad | mol/L | mol/kg |

💡 **Por eso la molalidad es la unidad de las propiedades coligativas** (ascenso ebulloscópico ΔT_eb = K_e·m y descenso crioscópico ΔT_f = K_f·m): esas fórmulas describen justamente **cambios de temperatura**, así que sería una contradicción usar una concentración que cambia con la temperatura. Es la unidad que aparece cuando se calcula cuánta sal hay que tirar en la ruta para que el hielo no se forme, o el anticongelante del radiador.

📝 **La conversión que se pide:** para pasar de M a m (o al revés) hace falta la **densidad de la solución**, y el paso clave es acordarse de que

$$m_{sv} = m_{sc} - m_{sto}$$

Es decir: masa de solución (que sale de δ y V) **menos** la masa de soluto. Nunca se puede saltear ese paso.

---

## P1 — pág. 18 · Partes por millón (1 de 2) — la definición

Título recuadrado: **Partes por millón**.

_Se puede expresar como masa de soluto (en mg) por cada un millón de mg de solución._

$$\boxed{ppm = \frac{m_{sto}\ (mg)}{m_{sc}\ (mg)} \cdot 1 \times 10^6}$$

_No es necesario expresarla siempre en mg, pero siempre la masa de soluto y la de la solución deben estar en las **MISMAS UNIDADES**!!_

**Ejemplo:** una **solución acuosa de HCl de concentración 100 ppm** contiene
- ✓ 100 **g** de soluto (HCl) por cada 1.000.000 **g** de solución
- ✓ 100 **mg** de soluto (HCl) por cada 1.000.000 **mg** de solución

_Como 1.000.000 mg = 1000 g = 1 kg, otra manera de decirlo es: **100 mg de soluto por cada kg de solución**._

_En general, se usa para soluciones muy diluídas._

**Explicación:** las ppm son **el % m/m con otro factor**. Nada más. El % m/m multiplica por 100 (partes por cien) y las ppm multiplican por 10⁶ (partes por millón). Misma estructura, misma propiedad de "cualquier unidad, siempre que sea la misma arriba y abajo":

$$\boxed{1\ \% = 10\,000\ \text{ppm}} \qquad\qquad \boxed{1\ \text{ppm} = 10^{-4}\ \%}$$

**¿Por qué existen?** Porque para una traza, escribir el porcentaje es incómodo. El plomo en el agua potable tiene un límite de 0,00001 % m/m. Escrito en ppm es **0,1 ppm**, y ese número se lee de un vistazo. Las ppm son puro **maquillaje de escala** para no arrastrar ceros.

La familia completa:

| Unidad | Factor | Equivale a | Dónde se usa |
|---|---|---|---|
| **%** | 10² | 1 parte en 100 | Rótulos comerciales |
| **‰** (por mil) | 10³ | 1 en 1.000 | Alcoholemia, salinidad |
| **ppm** | 10⁶ | 1 en 1.000.000 | Contaminantes, dureza del agua |
| **ppb** | 10⁹ | 1 en 1.000.000.000 | Trazas, dopantes de semiconductores |

💡 **Escala mental para que las ppm signifiquen algo:** 1 ppm es **1 segundo cada 11,5 días**, o **1 mm en 1 km**, o un grano de sal en un kilo de papas fritas. Y 1 ppb es una gota en una pileta olímpica.

📡 **Conexión con Telecomunicaciones (acá las ppm son el corazón del asunto):**
- **Dopaje de semiconductores:** el silicio para chips se dopa con B o P en concentraciones de **0,1 a 100 ppm**. Ese número, y sólo ese número, define si el material es tipo n o tipo p, su resistividad y el comportamiento de la juntura. Un error de un factor 2 en las ppm arruina la oblea.
- **Fibra óptica:** las impurezas de OH⁻ y de metales de transición (Fe, Cu) en la sílice tienen que estar por debajo de **1 ppb**, porque cada ppm de impureza mete atenuación. Que hoy la fibra tenga 0,2 dB/km es un logro de purificación medido en ppb.
- **Osciladores de cuarzo:** la estabilidad de un reloj de cristal se especifica **en ppm** (±20 ppm típico) — mismo lenguaje, otra magnitud.

---

## P1 — pág. 19 · Partes por millón (2 de 2) — el atajo mg/L

Título recuadrado: **Partes por millón**. En rojo: _Como se usa para soluciones **MUY diluidas** (muy poco soluto)…_

$$\delta_{sc} = \frac{m_{sc}}{V_{sc}} \approx \delta_{sv} = \frac{m_{sv}}{V_{sv}}$$

**Ejemplo:** una solución acuosa de HCl de concentración 100 ppm contiene:
- ✓ 100 mg de soluto (HCl) por cada 1.000.000 mg de solución (HCl + H₂O)

$$\delta_{sc} \approx \delta_{sv} \approx 1\ ^g/_{mL}$$

**1.000.000 mg de solución ≈ 1.000.000 mg de solvente ≈ 1.000 mL = 1 L**

$$\boxed{ppm = \frac{m_{sto}\ (mg)}{L}}$$

En rojo: _**Sólo si el solvente es agua y una solución MUY diluida!**_

**Explicación:** ésta es la fórmula que en la práctica usa **todo el mundo** — el rótulo de una botella de agua mineral dice "sodio: 12 mg/L" y eso son 12 ppm. Pero es una **aproximación**, y la diapositiva se toma el trabajo de mostrar de dónde sale. Seguí la cadena:

1. Si la solución es **muy diluida**, hay tan poco soluto que la masa de la solución es casi toda solvente: $m_{sc} \approx m_{sv}$.
2. Entonces la densidad de la solución es casi la del solvente: $\delta_{sc} \approx \delta_{sv}$.
3. Si el solvente es **agua**, esa densidad es **1 g/mL**.
4. Con δ = 1 g/mL, **1.000.000 mg = 1000 g = 1000 mL = 1 L**.
5. El denominador "un millón de mg de solución" se convierte en "**1 litro**", y el ×10⁶ desaparece porque ya está metido en el cambio de unidad.

$$ppm = \frac{m_{sto}(mg)}{m_{sc}(mg)} \cdot 10^6 = \frac{m_{sto}(mg)}{10^6\ mg} \cdot 10^6 = \frac{m_{sto}(mg)}{1\ L}$$

⚠️ **Las DOS condiciones están en rojo en la diapositiva porque las dos hacen falta:**

| Condición | Si no se cumple |
|---|---|
| **El solvente es agua** | Si es etanol (δ = 0,79 g/mL) el paso 3 se cae y el factor cambia |
| **La solución es MUY diluida** | Si está concentrada, $m_{sc} \neq m_{sv}$ y δ_sc ya no es 1 |

Para una solución concentrada hay que volver a la fórmula honesta de la pág. 18 y usar la densidad real de la solución. En un parcial, si te dan la densidad de la solución, es señal de que **quieren** que uses la fórmula completa.

💡 **Reglas de bolsillo que salen de esto:**

$$1\ \text{ppm} \approx 1\ \frac{\text{mg}}{\text{L}} \approx 1\ \frac{\text{mg}}{\text{kg}} \qquad\qquad 1\ \text{ppb} \approx 1\ \frac{\mu\text{g}}{\text{L}}$$

---

## P1 — pág. 20 · ¡Relaciones útiles!

Título recuadrado: **¡Relaciones útiles!** Cuatro bloques:

**➢ Masa y Número de moles**

$$n_{sto} = \frac{m_{sto}}{Mr_{sto}} \qquad n_{sv} = \frac{m_{sv}}{Mr_{sv}} \qquad n_{sto} + n_{sv} = n_{sc} = n_{totales}$$

**➢ Masas**

$$m_{sto} + m_{sv} = m_{sc}$$

(con una flecha roja apuntando a la palabra "Volúmenes" y el texto: **A menos que el problema aclare que sí lo son**)

**➢ Volúmenes**

_¡Los volúmenes **NO son aditivos**, por lo tanto NO puedo calcular el volumen de la solución como la suma de los volúmenes del solvente y el soluto!_

**Ejemplo:** 1 L de H₂O + 1 L de EtOH (alcohol etílico) = **1,93 L** de solución. Ocurrió una **contracción de volumen del 3,5 %**.

**➢ Masa y Volumen**

$$\delta_{sto} = \frac{m_{sto}}{V_{st}} \qquad \delta_{sv} = \frac{m_{sv}}{V_{sv}} \qquad \delta_{sc} = \frac{m_{sc}}{V_{sc}}$$

**Explicación:** **ésta es la diapositiva más importante de toda la clase para resolver ejercicios.** Las fórmulas de concentración son fáciles; lo que realmente cuesta es **conseguir el dato que falta** para poder aplicarlas. Estas cuatro relaciones son las que te dejan moverte entre masa, moles y volumen.

⚠️ **Y el mensaje central es la asimetría, que hay que grabar:**

| Magnitud | ¿Es aditiva? | Regla |
|---|---|---|
| **Masas** | ✓ **SÍ, siempre** | $m_{sto} + m_{sv} = m_{sc}$ |
| **Moles** | ✓ **SÍ, siempre** | $n_{sto} + n_{sv} = n_{totales}$ |
| **Volúmenes** | ❌ **NO** | $V_{sto} + V_{sv} \neq V_{sc}$ |

**¿Por qué las masas sí y los volúmenes no?** Porque la masa está **conservada**: los átomos que pusiste son los que hay, y ninguno desaparece al mezclar (ley de conservación de la masa). El volumen, en cambio, **no es una propiedad conservada**: es el resultado de **cómo se acomodan** las moléculas, y al mezclar dos sustancias las moléculas se reacomodan.

En el caso agua–etanol, las moléculas de etanol se **meten en los huecos** de la red de uniones hidrógeno del agua y forman uniones H nuevas más cortas, con lo cual el conjunto ocupa **menos** lugar que la suma de las partes. De ahí la **contracción del 3,5 %**:

$$\frac{2{,}00 - 1{,}93}{2{,}00} = 0{,}035 = 3{,}5\ \%$$

⚠️ **Consecuencias prácticas que hay que aplicar sin pensarlo:**

1. **Si te dan "X g de soluto en Y g de solvente"** → la masa de solución es **X + Y**, directo.
2. **Si te dan "X g de soluto en Y mL de solvente"** → ⚠️ el volumen de la solución **NO** es Y (ni Y + algo). Sólo lo sabés si el problema te da la **densidad de la solución** o el volumen final medido.
3. **La consigna típica es "se lleva a volumen final de …"** → ése es V_sc, y es un dato experimental, no una suma.
4. **La flecha roja de la diapositiva** avisa que a veces el enunciado dice "suponga volúmenes aditivos". Si lo dice, podés sumar. Si no lo dice, **no**.

💡 **El puente maestro de toda la clase**, la cadena que resuelve casi cualquier ejercicio:

$$V_{sc} \xrightarrow{\ \times\ \delta_{sc}\ } m_{sc} \xrightarrow{\ \times\ \%m/m\ } m_{sto} \xrightarrow{\ \div\ Mr\ } n_{sto} \xrightarrow{\ \div\ V_{sc}(L)\ } M$$

Y para la molalidad, el desvío obligado: $m_{sv} = m_{sc} - m_{sto}$.

---

## P1 — pág. 21 · Cómo preparar una solución — las preguntas

Título recuadrado: **Como preparar una solución**.

En azul: **¿Qué debo saber para preparar una solución?**
- ¿Qué es lo que se quiere disolver? (¿cuál es el soluto?)
- ¿Qué volumen de solución quiero preparar?
- ¿Qué cantidad de soluto tengo que usar?

_Tengo que conocer la **concentración** de la solución que quiero preparar._

**Explicación:** el planteo del problema inverso. Hasta acá venías con una solución hecha y **calculabas** su concentración. Ahora la concentración es **el dato** (la elegís vos) y lo que hay que calcular es **cuánto soluto pesar**.

Fijate en la estructura: hay **tres incógnitas y sólo dos son libres**. Elegís el soluto y elegís el volumen que querés preparar; la concentración deseada te fija la tercera. La ecuación de la molaridad tiene tres variables y con dos siempre sacás la que falta:

$$M = \frac{n}{V} \quad\Longrightarrow\quad \text{con 2 de los 3, sale el tercero}$$

| Sé | Quiero | Cuenta |
|---|---|---|
| M y V | n (y de ahí la masa) | $n = M \cdot V$ ← **el caso de la pág. 22** |
| n y V | M | $M = n / V$ |
| M y n | V | $V = n / M$ |

⚠️ **La pregunta "¿qué volumen de solución quiero preparar?" no es trivial:** el volumen que decidís es el de la **SOLUCIÓN FINAL**, no el de agua que vas a agregar. Eso condiciona todo el procedimiento de la pág. 23 (por eso se usa un matraz aforado y se llena **hasta la marca**, en lugar de medir el agua aparte).

---

## P1 — pág. 22 · Cómo preparar una solución — el ejemplo del CuCl₂

Título recuadrado: **Como preparar una solución**.

**Ejemplo:** Prepare **200 mL** de una solución acuosa de **CuCl₂ 0,50 M**, a partir de la cantidad apropiada de la sal (CuCl₂) y agua.

En el centro, la fórmula $M = \dfrac{n_{sto}}{V_{sc}(L)}$ con tres flechas de colores:
- rojo, hacia la M: **0,5 M = 0,5 mol L⁻¹**
- verde, hacia el V: **200 mL = 0,2 L**
- violeta, hacia n_sto: **?**

Las cuentas:

$$n_{st} = V_{sc} \times M = 0{,}2\ \cancel{L} \times 0{,}5\ \frac{mol}{\cancel{L}} = 0{,}1\ mol$$

En violeta: **¿Pero cuánto tengo que pesar?**

$$n_{st} = \frac{m_{st}}{Mr_{st}} \qquad\Longrightarrow\qquad m_{st} = n_{st} \times Mr_{st} = 0{,}1\ \cancel{mol} \times 135\ \frac{g}{\cancel{mol}} = \mathbf{13{,}5\ g}$$

**Explicación:** **el ejercicio modelo de la clase.** Los dos pasos, en orden, y nunca al revés:

```
PASO 1  ¿Cuántos MOLES necesito?     n = M · V(L)
PASO 2  ¿Cuántos GRAMOS son eso?     m = n · Mr
```

**Paso 0 (el que la diapositiva da por sabido):** las dos conversiones de unidades marcadas con flechas. `200 mL → 0,2 L` (dividir por 1000) es **obligatoria**, porque la molaridad exige litros. Si te olvidás, el resultado te da 1000 veces más grande.

**Y la otra cosa que se da por sabida: de dónde sale el Mr = 135.** Hay que calcularlo con la tabla periódica:

| Átomo | Cantidad | Masa atómica | Aporte |
|---|---|---|---|
| Cu | 1 | 63,5 | 63,5 |
| Cl | 2 | 35,5 | 71,0 |
| | | **Mr(CuCl₂)** | **134,5 ≈ 135 g/mol** |

⚠️ **Cuidado con la fórmula del compuesto**, que es el error más caro: el enunciado dice CuCl**₂** (cloruro de cobre **II**, cúprico). Si escribís CuCl (cloruro cuproso, Mr = 99) te da 9,9 g y está mal. Esto es Nomenclatura pura — ver `Extra/Nomenclatura-Explicacion-Completa.md`.

💡 **Las dos cuentas se pueden hacer de una:**

$$\boxed{m_{sto} = M \cdot V_{sc}(L) \cdot Mr_{sto}} \qquad = 0{,}5 \times 0{,}2 \times 135 = 13{,}5\ \text{g}$$

Ésa es la fórmula que conviene tener a mano en el parcial: te da directo **cuánto pesar** a partir de la concentración deseada, el volumen deseado y la masa molar.

📝 **Control de coherencia (hacelo siempre):** 0,5 M significa 0,5 mol por litro, o sea 0,5 × 135 = 67,5 g por litro. Yo quiero 0,2 L, la quinta parte → 67,5/5 = 13,5 g ✓. Si el número que te dio la fórmula no pasa este chequeo mental, revisá las unidades.

---

## P1 — pág. 23 · Cómo preparar una solución — el procedimiento en el laboratorio

Título recuadrado: **Como preparar una solución**. En violeta: _Tengo que pesar 13,5 g de CuCl₂ (cloruro de cobre (II), también llamado cloruro cúprico) y **disolverlo en agua hasta un volumen final de 200 mL**._

Cinco fotos en secuencia, con epígrafes:

| # | Foto | Epígrafe |
|---|---|---|
| 1 | Balanza con polvo celeste en un vidrio de reloj | **Peso 13,5 g de CuCl₂** |
| 2 | Matraz aforado con embudo y el sólido cayendo | **Pongo el sólido en un matraz de 200 mL** |
| 3 | Piseta echando agua por el embudo | **Agrego un poco de agua** |
| 4 | Mano agitando el matraz con líquido azul intenso | **Disuelvo** |
| 5 | Piseta completando el matraz hasta la marca | **Agrego agua hasta el enrase del matraz (200 mL)** |

**Explicación:** el orden de estos cinco pasos **no es arbitrario** y es lo que se pregunta. La clave está en los pasos 3 y 5, que parecen redundantes ("¿por qué agrego agua dos veces?"):

| Paso | Por qué en ese orden |
|---|---|
| 1. Pesar | Sobre vidrio de reloj o papel, nunca directo en la balanza |
| 2. Sólido al matraz | **El sólido va PRIMERO**, con el matraz vacío |
| 3. **Un poco** de agua | Para poder disolver: en el cuello angosto del matraz no se puede agitar |
| 4. **Disolver** | ⚠️ **Antes de enrasar.** Hay que tener todo disuelto |
| 5. Agua **hasta el enrase** | Recién ahora se completa a 200 mL exactos |

⚠️⚠️ **Por qué NO se puede enrasar antes de disolver:** porque los volúmenes **no son aditivos** (pág. 20). Si llenás hasta 200 mL y después el sólido se disuelve, el volumen cambia y ya no tenés 200 mL. Al disolver primero y enrasar al final, garantizás que el volumen **final de la solución** sea exactamente el que querías. Es la aplicación práctica y directa de la pág. 20.

⚠️ **El error clásico que esta secuencia previene:** agregar 13,5 g de CuCl₂ a **200 mL de agua** (medidos aparte). Eso da una solución de **más de 200 mL** y por lo tanto **menos** concentrada que 0,5 M. La consigna es "disolver **hasta** un volumen final de 200 mL", no "en 200 mL de agua". La preposición cambia el resultado.

💡 **Vocabulario de laboratorio:**

| Instrumento | Para qué | Precisión |
|---|---|---|
| **Matraz aforado** | Preparar un volumen **exacto** de solución | ★★★ (una sola marca de enrase) |
| **Pipeta aforada** | Trasvasar un volumen **exacto** | ★★★ |
| **Probeta** | Medir volumen aproximado | ★★ |
| **Vaso de precipitados** | Contener, mezclar | ★ (las marcas son orientativas) |

**Enrasar** = llevar el nivel del líquido exactamente hasta la marca del aforo. El matraz tiene **una sola marca** justamente porque está calibrado para ese único volumen a esa única temperatura (suele decir "20 °C" grabado).

---

## P1 — pág. 24 · Preparación de soluciones — los dos métodos

Título: **Preparación de soluciones**. Dos recuadros con fotos:

| Izquierda | Derecha |
|---|---|
| Tres matraces aforados: uno vacío con un poco de sólido rojo en un vidrio de reloj al lado, uno con líquido rojo a media altura y uno lleno hasta el aforo. Epígrafe: **Como en el ejemplo anterior** | Un vaso de precipitados con líquido sobre una balanza/plancha, una cápsula con sólido verde y un vaso con solución verde. Epígrafe: **Se pesa el soluto y el solvente por separado. Se mezclan hasta disolución del soluto. Conviene medir el volumen de la solución final.** |

**Explicación:** los dos caminos posibles para armar una solución, y **cada uno te da naturalmente una unidad de concentración distinta**. Ésa es la razón de ser de la diapositiva:

| Método | Qué controlás | Unidad que sale sola |
|---|---|---|
| **Volumétrico** (matraz aforado) | Masa de soluto + **volumen final de solución** | **M** y **% m/V** |
| **Gravimétrico** (pesar los dos) | Masa de soluto + **masa de solvente** | **% m/m** y **molalidad** |

⚠️ **Por qué "conviene medir el volumen de la solución final"** en el método gravimétrico: porque si pesaste soluto y solvente, tenés todas las masas (y con eso % m/m, molalidad y fracción molar), pero **NO tenés el volumen** — y no lo podés calcular sumando (pág. 20). Si además querés la molaridad, hay que **medirlo** al final. Con eso obtenés la densidad de la solución y ya podés convertir a cualquier unidad.

💡 **Ventajas y desventajas:**

| | Volumétrico | Gravimétrico |
|---|---|---|
| ✓ Ventaja | Rápido, un solo instrumento, ideal para M | **Más exacto** (pesar es más preciso que medir volumen) e **independiente de T** |
| ❌ Desventaja | Depende de la temperatura del aforo | Necesitás un paso extra si querés la molaridad |

---

## P1 — pág. 25 · Preparación de soluciones a partir de una solución concentrada

Título: **Preparación de soluciones** — en azul: **(A partir de una solución concentrada)**.

Tres dibujos de izquierda a derecha:
1. Una **pipeta** con **propipeta** (la pera roja de tres válvulas) tomando líquido rosa de un recipiente rotulado **Solución madre o solución concentrada**.
2. La pipeta (rotulada "10 mL") **descargando en un matraz** aforado.
3. Una **piseta con solvente** completando el matraz. Texto: _Se agrega agua hasta el enrase, el nivel de líquido (**menisco**) debe estar al mismo nivel que la vista_. Con un detalle ampliado del menisco y un ojo. Rótulo: **Dilución**.

**Explicación:** el **tercer** método de preparación, y en la práctica el más usado de todos: en vez de pesar un sólido, **partís de una solución que ya existe** y le agregás solvente. Se llama **dilución**, y aparece por dos razones muy concretas:

1. Los reactivos vienen **concentrados** de fábrica (el HCl viene 12 M, el H₂SO₄ 18 M). Nadie usa eso directo.
2. Para masas chiquitas, pesar es impreciso. Si necesitás 0,001 g de soluto, no hay balanza que sirva — pero sí podés tomar 1 mL de una solución 1000 veces más concentrada.

**Vocabulario que se pregunta:**

| Término | Qué es |
|---|---|
| **Solución madre** (o stock, o concentrada) | La solución de partida, de concentración conocida |
| **Propipeta** | La pera de goma con válvulas para succionar. ⚠️ **Nunca se pipetea con la boca** |
| **Menisco** | La curva que forma la superficie del líquido en el tubo |
| **Enrase** | Llevar el menisco exactamente a la marca del aforo |

⚠️ **Los dos detalles técnicos del dibujo que se corrigen en el laboratorio:**

1. **"El menisco debe estar al mismo nivel que la vista"** — si mirás desde arriba o desde abajo, la marca y el líquido se te desalinean por perspectiva y el volumen te queda mal. Se llama **error de paralaje** y es sistemático (siempre para el mismo lado). Hay que ponerse a la altura del aforo.
2. **Se enrasa con la parte INFERIOR del menisco** (para líquidos que mojan el vidrio, como el agua, que forman menisco cóncavo). El menisco existe por la tensión superficial: el agua "trepa" por el vidrio porque hace uniones H con los grupos Si—OH de la superficie. Es Clase 4 aplicada.

---

## P1 — pág. 26 · Dilución — el concepto

Título recuadrado: **Dilución**.

_En una dilución **disminuye la concentración de soluto** por agregado de solvente._

Esquema: un vaso rotulado **Concentrada** con **7 puntos rojos** (soluto) y poco líquido. Una flecha curva azul con la leyenda **Agrego solvente** entra al vaso. Una flecha gruesa apunta a un segundo vaso rotulado **Diluida**, con **los mismos 7 puntos rojos** pero **más líquido** y los puntos más separados. Abajo, la referencia: ● **soluto**.

**Explicación:** ⚠️ **Contá los puntos rojos: son 7 en los dos vasos.** Ése es todo el contenido conceptual de la diapositiva, y es la única cosa que hay que entender de las diluciones:

> **Al diluir, la CANTIDAD de soluto NO cambia. Lo único que cambia es el volumen en el que está repartido.**

No agregaste ni saqués soluto: agregaste **solvente**. Los moles de soluto son **exactamente los mismos** antes y después. Lo que baja es la **concentración**, porque el mismo numerador está dividido por un denominador más grande.

| Magnitud | Al diluir |
|---|---|
| **Moles de soluto** | **= IGUAL** ⭐ |
| Masa de soluto | **= IGUAL** |
| Volumen de solución | **AUMENTA** |
| **Concentración** | **BAJA** |
| Moles de solvente | AUMENTA |

De esa única frase sale toda la matemática de la pág. 28. No hace falta memorizar la fórmula: si sabés que los moles se conservan, la fórmula la deducís en el momento.

---

## P1 — pág. 27 · Preparación de diluciones — la serie

Título: **Preparación de d̲i̲luciones** (con el "di" en rojo y subrayado, para marcar la diferencia con la diapositiva 25).

Arriba, los mismos tres dibujos de la pág. 25 (propipeta + pipeta con la solución madre, la pipeta descargando en el matraz, la piseta enrasando con el detalle del menisco).

Abajo, una fila de **8 vasos** con líquido que va del **rojo casi negro** (izquierda) al **rosa pálido casi transparente** (derecha). Rótulo: **Diluciones**.

**Explicación:** la misma técnica de la pág. 25, aplicada **en cadena**: cada dilución se prepara a partir de la anterior. Se llama **dilución seriada**, y es la manera estándar de cubrir varios órdenes de magnitud de concentración con precisión.

💡 **Por qué en serie y no de una:** si querés bajar de 1 M a 10⁻⁶ M en un solo paso, tendrías que medir 1 µL con precisión — imposible con una pipeta común. En cambio, con 6 diluciones 1:10 consecutivas (tomar 1 mL y llevar a 10 mL, seis veces) llegás al mismo lugar usando siempre volúmenes cómodos y medibles.

$$1\ \text{M} \xrightarrow{1:10} 10^{-1} \xrightarrow{1:10} 10^{-2} \xrightarrow{1:10} 10^{-3} \xrightarrow{1:10} 10^{-4} \xrightarrow{1:10} 10^{-5} \xrightarrow{1:10} 10^{-6}\ \text{M}$$

⚠️ **La contra:** los errores se **multiplican**, no se suman. Si cada paso tiene 1 % de error, después de 6 pasos el error acumulado es ~6 %. Por eso conviene usar el mínimo número de pasos posible.

💡 **Para qué se usa la serie de 8 vasos de la foto:** para armar la **curva de calibración** de la que hablábamos en la pág. 11. Preparás 8 patrones de concentración conocida, les medís la absorbancia en el espectrofotómetro, graficás A vs c (que da una recta, por Lambert-Beer), y después medís tu muestra desconocida e interpolás. Es el método cuantitativo estándar de análisis químico.

---

## P1 — pág. 28 · Preparación de diluciones — la fórmula

Título: **Preparación de d̲iluciones**.

Los tres dibujos, ahora **con las variables rotuladas**:
- En la pipeta y la solución madre: **V₀** y **C₀** (en azul)
- En el matraz: **V₀** arriba (lo que se descarga) y **V_F** abajo (el volumen del matraz), en rojo
- En el matraz final: **C_F**, **V_F** (en rojo)

Las ecuaciones:

$$C_0 \cdot V_0 = \text{moles}_{st} \qquad\qquad C_F \cdot V_F = \text{moles}_{st}$$

$$\boxed{C_0 \cdot V_0 = C_F \cdot V_F}$$

Al pie: _Los **moles_st** son los mismos **antes** y **después** de la dilución._

**Explicación:** la deducción está entera en la diapositiva, y por eso conviene aprenderla así en vez de memorizar la fórmula:

1. De la definición de molaridad, $M = n/V$, se despeja $n = M \cdot V$. Aplicado a la solución madre: los moles que **tomo con la pipeta** son $C_0 \cdot V_0$.
2. Esos mismos moles quedan en el matraz final: $n = C_F \cdot V_F$.
3. Como los moles **se conservan** (pág. 26), los dos productos son iguales.

$$\boxed{C_0 V_0 = C_F V_F}$$

⚠️ **Qué es cada V, que es lo que más se confunde:**

| Variable | Qué es |
|---|---|
| **V₀** | El volumen **que tomo con la pipeta** de la solución madre (el "alícuota") |
| **V_F** | El volumen **FINAL total** de la solución diluida (= el volumen del matraz) |
| **NO es** | V_F **no** es el volumen de agua que agregué. El agua agregada es $V_F - V_0$ |

⚠️ **Las unidades pueden ser cualquiera, pero coherentes.** Si C₀ y C_F están en la misma unidad (M, %m/V, ppm, da igual) y V₀ y V_F en la misma unidad (mL, L, da igual), la fórmula funciona. Los factores se cancelan. **Esto es cómodo: no hace falta pasar mL a L en las diluciones.**

💡 **Las tres formas despejadas, que son las tres preguntas posibles:**

$$V_0 = \frac{C_F \cdot V_F}{C_0} \qquad C_F = \frac{C_0 \cdot V_0}{V_F} \qquad V_F = \frac{C_0 \cdot V_0}{C_F}$$

📝 **Ejemplo tipo parcial:** ¿cómo preparo 250 mL de HCl 0,1 M a partir de HCl 2 M?

$$V_0 = \frac{0{,}1\ M \times 250\ mL}{2\ M} = 12{,}5\ \text{mL}$$

→ Tomo **12,5 mL** de la solución 2 M, los pongo en un matraz de 250 mL y **enraso con agua**. (Agregué 237,5 mL de agua, pero ése número no hace falta calcularlo.)

⚠️⚠️ **Regla de seguridad que no está en la diapositiva pero es importante:** para diluir **ácidos concentrados** siempre se agrega **el ácido sobre el agua**, nunca el agua sobre el ácido. La dilución del H₂SO₄ es muy exotérmica y si va al revés puede hervir y salpicar. La regla mnemotécnica es "**el ácido al agua, como el azúcar al café**".

---

## P1 — pág. 29 · Diluciones — la tabla de la notación 1:n

Título: **Diluciones**. Una tabla escaneada, con el encabezado **1000 mL NaOH 0,1 M (M₁)**:

| | |
|---|---|
| **dilución 1:2** (1 L de sc original lo llevo a 2 L totales)<br>M₂ = (0,1)·1/2 = **0,05** | **dilución 1:10** (1 L de sc original lo llevo a 10 L totales)<br>M₂ = (0,1)·1/10 = **0,01** |
| **dilución 1:25** (1 L de sc original lo llevo a 25 L totales)<br>M₂ = (0,1)·1/25 = **0,004** | **dilución 1:50** (1 L de sc original lo llevo a 50 L totales)<br>M₂ = (0,1)·1/50 = **0,002** |

**Explicación:** la **notación de laboratorio** para las diluciones, que es lo único nuevo de esta diapositiva. Es la fórmula de la pág. 28 escrita de otra manera:

$$M_2 = M_1 \cdot \frac{V_1}{V_2} = M_1 \cdot \frac{1}{n} \qquad \text{para una dilución } 1:n$$

⚠️ **La definición exacta de "1:n", que es donde todo el mundo se equivoca.** La diapositiva se toma el trabajo de aclararlo con paréntesis en cada celda, y por algo:

> **1:n significa que 1 volumen de solución original se lleva a n volúmenes TOTALES.**
> **NO** significa "1 volumen de solución + n volúmenes de solvente".

| Notación | Interpretación correcta ✓ | Interpretación incorrecta ❌ |
|---|---|---|
| **1:2** | 1 L original → **2 L totales** (agrego 1 L de agua). Factor **1/2** | 1 L + 2 L = 3 L totales, factor 1/3 |
| **1:10** | 1 L original → **10 L totales** (agrego 9 L). Factor **1/10** | 1 + 10 = 11 |

Con la interpretación correcta, la cuenta es trivial: **el factor de dilución es 1/n**, y la concentración final es la original dividida por n.

| Dilución | Factor | M₂ (de 0,1 M) | Cuántas veces más diluida |
|---|---|---|---|
| 1:2 | 1/2 | 0,05 M | 2× |
| 1:10 | 1/10 | 0,01 M | 10× |
| 1:25 | 1/25 | 0,004 M | 25× |
| 1:50 | 1/50 | 0,002 M | 50× |

💡 **Verificación de las cuentas de la tabla:** 0,1/2 = 0,05 ✓ · 0,1/10 = 0,01 ✓ · 0,1/25 = 0,004 ✓ · 0,1/50 = 0,002 ✓

⚠️ **En diluciones seriadas los factores se MULTIPLICAN:** dos diluciones 1:10 seguidas dan una dilución **1:100** total, no 1:20.

$$C_{final} = C_0 \cdot \frac{1}{n_1} \cdot \frac{1}{n_2} \cdots$$

---

## P1 — pág. 30 · Solubilidad — el experimento

Título recuadrado: **Solubilidad**. _Supongamos que agregamos un **montón** de sal a un vaso con agua…_

Dos fotos rotuladas **Inicial** y **Final**, cada una con una lupa que amplía el fondo del vaso:
- **Inicial:** montón de sal (esferas verdes apiladas) en el fondo, agua alrededor, nada disuelto.
- **Final:** el montón es **más chico** pero **sigue habiendo sólido** en el fondo, y en el agua se ven **iones sueltos rodeados de moléculas de agua** (solvatados).

A la derecha, una cadena de flechas rojas:

_Luego de un tiempo, **no se disuelve más** el NaCl._
↓
_Está en **equilibrio**: solución **saturada**_
↓
_La **concentración** del soluto es la **solubilidad**_

Al pie: **Alta solubilidad ⟷ Alta afinidad soluto-solvente (fuerzas intermoleculares)**

**Explicación:** la definición de solubilidad, construida a partir del experimento. Seguí la cadena, porque cada eslabón es una definición:

1. Agregás mucho soluto. Al principio se disuelve.
2. Llega un momento en que **deja de disolverse** y queda sólido en el fondo.
3. Eso **no** significa que el proceso se detuvo: significa que llegó al **equilibrio**.
4. Una solución en equilibrio con su soluto sin disolver está **saturada**.
5. La concentración de esa solución saturada **es la solubilidad**.

⚠️ **"Equilibrio" es la palabra técnica y no significa "quieto".** A nivel microscópico siguen pasando las dos cosas todo el tiempo:

$$\text{NaCl(s)} \underset{\text{cristalización}}{\overset{\text{disolución}}{\rightleftarrows}} \text{Na}^+_{(ac)} + \text{Cl}^-_{(ac)}$$

Es un **equilibrio dinámico**: los iones se siguen despegando del cristal y otros se siguen pegando, pero **a la misma velocidad**. El resultado neto es cero, y por eso a ojo no pasa nada. Es exactamente la misma idea que la presión de vapor de un líquido.

💡 **La frase del pie es el puente con la Clase 4:** "Alta solubilidad ⟷ alta afinidad soluto-solvente". La solubilidad **no** es un número mágico tabulado: es la manifestación macroscópica y medible de las fuerzas intermoleculares. Cuanto mejor "encajan" las interacciones soluto–solvente (pág. 7), más alto es ese número.

⚠️ **Y ojo con la lupa del "Final":** todavía hay sólido en el fondo. Eso es **la señal de que la solución está saturada**. Si agregás soluto a una solución y **se disuelve**, estaba insaturada. Si **no se disuelve**, estaba saturada. Ése es el test experimental.

---

## P1 — pág. 31 · Solubilidad — la definición y el NaCl

Título recuadrado: **Solubilidad**. La ecuación del equilibrio:

$$\text{NaCl (s)} \xrightleftharpoons[\ ]{\ \text{H}_2\text{O}\ } \text{Na}^+ \text{(ac)} + \text{Cl}^- \text{(ac)}$$

**Solubilidad: Es la máxima concentración de un soluto que puede disolverse en cierto solvente a una determinada temperatura.**

En azul: **¿Cuál es la solubilidad del NaCl en agua?**

| Solubilidad (% m/m) | Temperatura (°C) |
|---|---|
| 35,7 | 0 |
| 36,0 | 20 |
| 36,6 | 40 |
| 37,3 | 60 |
| 38,4 | 80 |
| 39,8 | 100 |

Al pie: _Una mirada microscópica:_ https://phet.colorado.edu/en/simulation/soluble-salts

**Explicación:** la definición formal tiene **tres partes** y ninguna es decorativa:

| Parte de la definición | Por qué está |
|---|---|
| "**máxima** concentración" | Es un **techo**, no una concentración cualquiera. Una solución puede tener cualquier concentración **hasta** la solubilidad |
| "en **cierto** solvente" | Es propiedad **del par**. El I₂ tiene solubilidad ~0 en agua y alta en CCl₄ (pág. 8) |
| "a una **determinada temperatura**" | ⚠️ **Sin la temperatura, el número no significa nada.** Es la variable que manda |

⚠️ **La solubilidad es una CONCENTRACIÓN**, y por lo tanto se puede expresar en cualquiera de las unidades de las págs. 13 a 19. Se estila darla en **g de soluto / 100 g de solvente** (así están todas las curvas de las págs. 32 a 35), pero también aparece en % m/m, en g/L o en molaridad (ahí se llama **solubilidad molar**). Cuando compares dos solubilidades, **asegurate primero de que estén en la misma unidad**.

⚠️ **Un detalle de la tabla:** el encabezado dice "% m/m" pero estos son los valores clásicos de solubilidad del NaCl expresados en **g de NaCl / 100 g de agua** (36 g/100 g de agua a 20 °C). Si fuera % m/m verdadero (masa de soluto sobre masa de **solución**) el número sería 36/(100+36) × 100 ≈ **26,5 %**. Son las dos maneras de decir lo mismo, pero **no dan el mismo número**, y en un ejercicio hay que fijarse cuál te están dando. La pista es el denominador: "cada 100 g de **agua**" vs "cada 100 g de **solución**".

💡 **Lo que hay que leer en la tabla:** la solubilidad del NaCl **sube con la temperatura**, pero **muy poco**: de 35,7 a 39,8 en 100 °C, apenas un 11 % de variación. Guardate este dato, porque en la pág. 34 se pregunta cuál es la sustancia **menos sensible a la temperatura** y la respuesta es justamente el NaCl (su curva es la más chata del gráfico).

📝 Y de acá sale el número práctico: **~36 g de sal por 100 g de agua a temperatura ambiente**. Es decir, en un vaso de 200 mL entran unos 72 g de sal y no más. Es un buen número para tener de referencia.

---

## P1 — pág. 32 · Curvas de solubilidad — el esquema conceptual

Título recuadrado: **Curvas de Solubilidad**. Un gráfico esquemático:

- Eje y: **Solubilidad g / 100 g de agua**
- Eje x: **T (°C)**
- Una curva creciente irregular divide el plano en dos regiones coloreadas:
  - **Arriba de la curva** (rosa): **sobresaturada**
  - **Abajo de la curva** (celeste): **insaturada**
- Una flecha señala la curva misma con el rótulo: **solubilidad**

**Explicación:** ⚠️ **Ésta es la diapositiva que hay que entender de verdad, porque el gráfico es el que sale en el parcial.** El concepto es simple pero hay que verlo bien: **la curva no es una función que dibuja "la solubilidad" y listo — es una FRONTERA que divide el plano en tres lugares distintos.**

| Dónde estás | Cómo se llama | Qué se ve en el vaso |
|---|---|---|
| **DEBAJO** de la curva | **Insaturada** (no saturada) | Todo disuelto, y **admite más** soluto |
| **SOBRE** la curva | **Saturada** | Todo disuelto, pero **no admite más** (equilibrio) |
| **ARRIBA** de la curva | **Sobresaturada** | ⚠️ Estado **inestable**: hay más soluto disuelto del que "debería" |

💡 **Cómo se lee un punto del gráfico:** cada punto es un par (temperatura, cantidad de soluto por 100 g de agua). Ubicás tu punto y ves en qué región cayó. Ése es todo el método.

⚠️ **La región sobresaturada es la interesante y la que se pregunta.** ¿Cómo se llega ahí, si por definición no puede haber más soluto que la solubilidad? Con un truco de temperatura:

1. Preparás una solución **saturada en caliente** (a 80 °C, donde la solubilidad es alta).
2. La **enfriás muy despacio y sin moverla**.
3. La solubilidad baja al bajar T, así que el soluto **debería** precipitar… **pero no lo hace**, porque para formar un cristal hacen falta núcleos de cristalización y sin perturbación no se forman.
4. Quedás con una solución **sobresaturada**: metaestable, "colgada" arriba de la curva.
5. Le tirás un cristalito (o le pegás al vaso) y **precipita todo de golpe**.

Es lo que pasa con la **miel cristalizada**, con los caramelos y con las **bolsitas de calor instantáneo** (acetato de sodio sobresaturado: apretás el clic metálico, nucleás la cristalización y libera calor de golpe).

---

## P1 — pág. 33 · Solubilidad — las tres definiciones textuales

Título recuadrado: **Solubilidad**. Tres viñetas, cada una con su término en color:

- Una **solución saturada** (violeta) contiene la cantidad **máxima** de un soluto que se disolvería en un solvente a una temperatura específica.
- Una **solución no saturada (o insaturada)** (celeste) contiene **menos** soluto que el que puede disolverse a una temperatura específica.
- Una **solución sobresaturada** (magenta) contiene **más** soluto que el que puede haber en una solución saturada a una temperatura específica.

**Explicación:** las **tres definiciones textuales**, que es el formato en el que se piden. Son la versión en palabras del gráfico de la pág. 32:

| Tipo | Relación con la solubilidad (S) | En el gráfico | ¿Estable? | ¿Admite más soluto? |
|---|---|---|---|---|
| **Insaturada** | c **<** S | Debajo de la curva | ✓ Sí | ✓ Sí, se disuelve |
| **Saturada** | c **=** S | Sobre la curva | ✓ Sí (equilibrio) | ❌ No, va al fondo |
| **Sobresaturada** | c **>** S | Arriba de la curva | ❌ **Metaestable** | ❌ No |

⚠️ **Fijate que las tres definiciones terminan con la misma frase: "a una temperatura específica".** No es relleno: **la misma solución puede ser las tres cosas según la temperatura**. Una solución con 100 g de NaNO₃/100 g de agua es:

- **insaturada** a 60 °C (donde S ≈ 126)
- **saturada** a ~34 °C (donde S ≈ 100)
- **sobresaturada** a 20 °C (donde S ≈ 88)

Y no cambió nada de la solución — sólo el termómetro. Por eso no se puede hablar de solubilidad sin dar la temperatura.

⚠️ **Trampa clásica de vocabulario:** "**concentrada**" y "**saturada**" no son sinónimos. Concentrada es cualitativo y relativo (pág. 10); saturada es un límite físico. Una solución de NaCl 1 M es **concentrada** para muchos usos pero está lejísimos de estar **saturada** (que serían ~6,1 M). Y al revés: una solución saturada de AgCl es **saturada** y sin embargo es extremadamente **diluida** (~1,3×10⁻⁵ M), porque el AgCl es casi insoluble.

---

## P1 — pág. 34 · Curvas de solubilidad — el gráfico real y las tres preguntas

Título recuadrado: **Curvas de solubilidad**.

A la izquierda, el **gráfico clásico de curvas de solubilidad**:
- Eje y: **Gramos de soluto / 100 g H₂O**, de 0 a 150
- Eje x: **Temperatura °C**, de 0 a 100
- **Curvas crecientes** (sales): **KI** (naranja, arriba de todo), **NaNO₃** (rojo), **KNO₃** (celeste, la más empinada), **NH₄Cl** (violeta), **KCl** (verde claro), **NaCl** (marrón, casi plana en ~36-40), **KClO₃** (magenta, abajo)
- **Curvas DECRECIENTES**: **HCl** (beige, de ~78 bajando), **NH₃** (azul oscuro, de ~90 bajando), **SO₂** (azul, de ~23 bajando a casi 0)

A la derecha, en azul: _En general la solubilidad de los compuestos iónicos **aumenta con la temperatura**, existen **excepciones**._

Y tres preguntas:
- ➢ **¿Cuál es la excepción?**
- ➢ **¿Qué sustancia es la más sensible a la T?**
- ➢ **¿Qué sustancia es la menos sensible a la T?**

**Explicación:** el gráfico que **hay que saber leer** — es el ejercicio de solubilidad más frecuente. Las tres respuestas:

**➢ ¿Cuál es la excepción?**
Las **curvas que BAJAN**: **NH₃, HCl y SO₂**. ⚠️ Y no es casualidad que sean justo esas tres: **son las únicas GASES de todo el gráfico** (amoníaco, cloruro de hidrógeno y dióxido de azufre son gases a temperatura ambiente). Todas las demás son sales sólidas y todas suben.

Ésa es la regla general que hay que llevarse, y la pág. 36 la desarrolla:

| Tipo de soluto | Solubilidad con T ↑ |
|---|---|
| **Sólidos** (sales iónicas) | **AUMENTA** (casi siempre) |
| **GASES** | **DISMINUYE** (siempre) |

**➢ ¿Qué sustancia es la más sensible a la T?**
El **KNO₃** — es la curva **más empinada** de todas: arranca en ~13 g a 0 °C y llega a ~245 g a 100 °C. Multiplica su solubilidad casi por **20**. "Más sensible a T" = **mayor pendiente**.

**➢ ¿Qué sustancia es la menos sensible a la T?**
El **NaCl** — es la curva **más chata** (la marrón): de 35,7 a 39,8 en todo el rango, apenas +11 %. Es exactamente la tabla de la pág. 31. (El KClO₃ y el NaNO₃ también son suaves en parte del rango, pero el NaCl es el caso emblemático de curva plana.)

⚠️ **La palabra clave para contestar estas preguntas es PENDIENTE, no altura.** El KI está arriba de todo (es el más soluble en términos absolutos) pero **no** es el más sensible: su curva es bastante paralela. "Sensible a T" es cuánto **cambia**, no cuánto **vale**.

💡 **Por qué los sólidos suben y los gases bajan:** disolver un sólido suele ser **endotérmico** (hay que gastar energía para romper la red cristalina), y calentar favorece los procesos endotérmicos. Disolver un gas, en cambio, es **exotérmico** (las moléculas de gas pasan de moverse libres a quedar atrapadas por el solvente, liberando energía), así que calentar lo **desfavorece**. Es el principio de Le Chatelier.

---

## P1 — pág. 35 · Curvas de solubilidad — el ejercicio resuelto del NaNO₃

Misma gráfica que la pág. 34, ahora **con marcas de lectura**: líneas punteadas de colores y círculos que marcan puntos sobre la curva del **NaNO₃** (roja), y flechas gruesas en el eje x a 20 °C (roja), 30 °C (azul) y 60 °C (verde).

_Veamos NaNO₃:_

| Pregunta | Respuesta en la diapositiva |
|---|---|
| ¿Cuál es su solubilidad a **20°** y a **60°**? | (círculo rojo, en rojo arriba) **Solubilidad: ≈ 88 g / 100 g H₂O** |
| ¿Qué pasa si intentamos disolver **130 g a 30°**? | (en azul) **Se disolverían ≈98 g y quedarían sin disolverse 32 g** |
| ¿Y a **80°**? | (sin respuesta escrita) |
| A **60°**: ¿cuánto NaNO₃ se disuelve en **278 g de agua**? | (en verde) **A 60 °C se disuelven ≈126 g en 100 g de agua: hacemos regla de 3** |

Y la regla de tres planteada:

```
100 g agua  ⟶  126 g de NaNO₃
278 g agua  ⟶  X  g de NaNO₃
```

**Explicación:** los **tres tipos de ejercicio** de curvas de solubilidad, en una sola diapositiva. Vale la pena resolverlos completos, porque la diapositiva deja algunos a medias.

**① Lectura directa: la solubilidad a una T dada.**
Subís vertical desde la temperatura hasta cruzar la curva, y ahí leés horizontal en el eje y.

| T | Solubilidad del NaNO₃ |
|---|---|
| 20 °C | **≈ 88 g / 100 g H₂O** |
| 30 °C | ≈ 98 g / 100 g H₂O |
| 60 °C | **≈ 126 g / 100 g H₂O** |
| 80 °C | ≈ 148 g / 100 g H₂O |

**② ¿Se disuelve todo? El ejercicio de saturación.** *"¿Qué pasa si intento disolver 130 g a 30 °C?"*

El método, siempre igual:

```
1. Leo la solubilidad S a esa temperatura
2. La escalo a la cantidad de agua que tengo (regla de 3)
3. Comparo con lo que quiero disolver:
      cantidad ≤ S  →  se disuelve TODO (insaturada o saturada justo)
      cantidad >  S  →  se disuelve S, y el resto (cantidad − S) queda en el fondo
```

A 30 °C, S ≈ 98 g/100 g de agua. Quiero meter 130 g en 100 g de agua:

$$130 - 98 = \boxed{32\ \text{g quedan sin disolver}}$$

y la solución queda **saturada** con 98 g disueltos. ✓ Coincide con la diapositiva.

**③ ¿Y a 80 °C?** — ésta es la que quedó **sin contestar** en la diapositiva. A 80 °C la curva del NaNO₃ está en ≈148 g/100 g de agua, y 130 < 148, entonces:

$$\boxed{\text{a 80 °C se disuelven los 130 g: no queda nada en el fondo}}$$

y la solución está **insaturada**. 💡 Ésta es la moraleja de las dos preguntas juntas: **el mismo sistema (130 g en 100 g de agua) es saturado con precipitado a 30 °C e insaturado a 80 °C.** La temperatura es la que decide.

**④ Escalar a otra cantidad de solvente: la regla de tres.** *"A 60 °C, ¿cuánto NaNO₃ se disuelve en 278 g de agua?"*

⚠️ Acá está el detalle que más se olvida: **las curvas están dadas por 100 g de agua**, así que si el problema te da otra cantidad de solvente hay que **escalar**. La diapositiva plantea la regla de tres pero **no da el resultado**. Terminala:

$$X = \frac{278\ \cancel{g\ agua} \times 126\ g\ \text{NaNO}_3}{100\ \cancel{g\ agua}} = \boxed{350{,}3\ \text{g de NaNO}_3}$$

⚠️ **Y ojo si el enunciado te da mL de agua en lugar de gramos:** hay que pasar primero con la densidad (pág. 3). Es exactamente lo que hacen las págs. 37 y 38.

---

## P1 — pág. 36 · Solubilidad de gases

Título recuadrado: **Solubilidad de gases**. Un gráfico:
- Eje y: **Solubilidad (mM)**, de 0 a ~2,5
- Eje x: **Temperatura °C**, de 0 a 50
- En el medio, grande: **GASES**
- Cuatro curvas, **todas DECRECIENTES**: **CH₄** (rojo, la más alta, de ~2,4 a ~1,0), **O₂** (verde, de ~2,1 a ~0,95), **CO** (azul oscuro, de ~1,4 a ~0,75), **He** (naranja, la más baja y casi plana en ~0,4)

A la derecha: **¿La gaseosa conserva mejor el gas, en la heladera o afuera?**

Y en azul, la conclusión: ➢ **La solubilidad de los gases DISMINUYE con el aumento de la temperatura**

**Explicación:** el gráfico de la "excepción" que la pág. 34 anticipaba, ahora con gases puros. **Todas las curvas bajan, sin excepción.**

**➢ La respuesta a la pregunta: en la HELADERA.** Cuanto más frío, más gas queda disuelto. Si dejás la gaseosa al sol, el CO₂ se escapa de la solución y se te queda sin gas.

⚠️ **Y hay una segunda razón, aún más importante, que el gráfico no muestra: la PRESIÓN.** La solubilidad de un gas depende de dos variables, no de una:

$$\boxed{S_{gas} = k_H \cdot P_{gas}} \qquad \text{(ley de Henry)}$$

La solubilidad de un gas es **proporcional a su presión parcial** sobre el líquido. Por eso:

| Acción | Qué pasa |
|---|---|
| **Abrir la botella** | Cae la presión de CO₂ → cae la solubilidad → **burbujea** |
| **Dejarla abierta** | Se sigue escapando hasta equilibrar con el aire → se "queda sin gas" |
| **Calentarla** | Baja k_H → baja la solubilidad → se escapa más rápido |
| **Enfriarla y taparla** | Máxima solubilidad → conserva el gas |

💡 **Por qué los gases se comportan al revés que los sólidos** (el argumento de la pág. 34, aplicado): un gas disuelto **pierde libertad** (pasa de moverse suelto a estar rodeado y frenado por el solvente). Es un proceso **exotérmico** y con **caída de entropía**. Calentar le da energía cinética a las moléculas para escapar de la solución. Con un sólido pasa lo contrario: partís de una red rígida y el soluto **gana** libertad al disolverse.

💡 **El orden de las curvas también dice algo:** el **He** es el menos soluble y el más chato porque es un átomo chiquito, no polar y con sólo 2 electrones → **polarizabilidad mínima** → interacciones de London casi nulas con el agua. El **CH₄** es el más soluble de los cuatro porque es más grande y más polarizable. Es la tabla de London de la Clase 4 apareciendo en un gráfico de solubilidad.

⚠️ **Aplicaciones que valen la pena conocer:**
- **Buceo:** a 30 m de profundidad la presión es 4 atm, y se disuelve 4 veces más N₂ en la sangre. Si subís rápido, la presión cae de golpe, el N₂ burbujea en los vasos y eso es el **síndrome de descompresión**.
- **Contaminación térmica:** una central que devuelve agua caliente a un río le baja el O₂ disuelto y asfixia a los peces. Es el mismo gráfico, curva verde.
- **Cerveza y champagne**: mismo principio que la gaseosa. Fría y cerrada.

---

## P1 — pág. 37 · Ejemplo de solubilidad — el AgNO₃ que se disuelve todo

Título recuadrado: **Ejemplo de solubilidad**.

_¿Si la solubilidad del nitrato de plata (AgNO₃) en agua, a 18 °C, es de **211,60 g / 100 g de agua**. Si se colocan **423,20 g** de AgNO₃ en **300 mL de agua**, se disolverá todo el AgNO₃?_

$$\text{AgNO}_3\text{(s)} \xrightleftharpoons[\ ]{\ \text{H}_2\text{O}\ } \text{Ag}^+\text{(ac)} + \text{NO}_3^-\text{(ac)}$$

$$\delta_{H_2O}(18\ °C) = 0{,}99868\ \frac{g}{mL} \qquad\longrightarrow\qquad 300\ \text{mL} = 299{,}604\ \text{g}$$

_Si se pueden disolver **211,60 g** de AgNO₃ en 100 g de agua, en **299,604 g** de agua se pueden disolver **633,96 g**._

_Se tienen **423,20 g** en 300 mL de agua._

En verde grande: **¡Está todo disuelto!**

**Explicación:** el ejercicio completo de solubilidad, con **el paso que el enunciado esconde**: los datos vienen en **unidades distintas**. La solubilidad está por 100 **g** de agua y el enunciado te da 300 **mL** de agua. **Hay que convertir**, y para eso hace falta la densidad — que aparece con 5 cifras significativas justamente para eso.

**El método, paso a paso:**

**Paso 1 — Pasar el solvente a gramos** (con la densidad de la pág. 3):

$$m_{H_2O} = V \cdot \delta = 300\ \cancel{mL} \times 0{,}99868\ \frac{g}{\cancel{mL}} = 299{,}604\ \text{g}$$

**Paso 2 — Escalar la solubilidad a esa cantidad de agua** (regla de 3, como en la pág. 35):

$$\frac{211{,}60\ \text{g AgNO}_3}{100\ \text{g H}_2\text{O}} = \frac{X}{299{,}604\ \text{g H}_2\text{O}} \quad\Longrightarrow\quad X = 211{,}60 \times 2{,}99604 = 633{,}96\ \text{g}$$

Eso es el **máximo** que se puede disolver en esa agua a 18 °C.

**Paso 3 — Comparar:**

$$423{,}20\ \text{g (lo que tengo)} \ \ <\ \ 633{,}96\ \text{g (el máximo)} \quad\Longrightarrow\quad \textbf{se disuelve TODO}$$

Y la solución queda **insaturada** (podría admitir 633,96 − 423,20 = 210,76 g más).

⚠️ **Por qué la densidad del agua está dada con 5 decimales y a 18 °C:** porque la densidad del agua **cambia con la temperatura**, y el enunciado quiere ser prolijo. En la práctica 0,99868 ≈ 1, y usando δ = 1 g/mL te habría dado 634,8 g en vez de 633,96 — la misma conclusión. 💡 **En un parcial, si no te dan la densidad del agua, usá 1 g/mL y aclarálo.** Pero si te la dan, usala: te la dieron por algo.

💡 **Notá que 423,20 = 2 × 211,60** exactamente. No es casualidad: el enunciado está armado para que puedas comparar de una sin calculadora. Si tuvieras 200 g de agua, 423,20 g sería **justo** el doble del máximo y estaría saturada al borde. Como tenés ~300 g de agua, hay lugar de sobra.

---

## P1 — pág. 38 · Otro ejemplo de solubilidad — el AgNO₃ que NO se disuelve todo

Título recuadrado: **Otro ejemplo de solubilidad**. **Idéntico** al anterior salvo un número:

_¿Si la solubilidad del nitrato de plata (AgNO₃) en agua, a 18 °C, es de 211,60 g / 100 g de agua. Si se colocan **823,2 g** de AgNO₃ en 300 mL de agua, se disolverá todo el AgNO₃?_

Misma ecuación de equilibrio, misma densidad, mismo cálculo:

$$\delta_{H_2O}(18\ °C) = 0{,}99868\ \frac{g}{mL} \longrightarrow 300\ \text{mL} = 299{,}604\ \text{g}$$

_Si se pueden disolver 211,60 g de AgNO₃ en 100 g de agua, en 299,604 g de agua se pueden disolver **633,96 g**._

_Se tienen **823,20 g** en 300 mL de agua._

En verde grande: **Se disolvieron 633,96 g y 189,24 g quedaron sin disolver**

**Explicación:** **el mismo ejercicio con el otro resultado posible.** Los pasos 1 y 2 son idénticos (mismo solvente, misma temperatura, misma solubilidad → mismo máximo de **633,96 g**). Lo único que cambia es el paso 3:

$$823{,}20\ \text{g (lo que tengo)} \ \ >\ \ 633{,}96\ \text{g (el máximo)} \quad\Longrightarrow\quad \textbf{NO se disuelve todo}$$

Y entonces hay que dar **las dos cantidades**, que es lo que se corrige:

| | Cantidad |
|---|---|
| Se **disuelve** (= el máximo, la solución queda **saturada**) | **633,96 g** |
| Queda **sin disolver** en el fondo (precipitado) | $823{,}20 - 633{,}96 = \mathbf{189{,}24\ g}$ |

⚠️ **La cuenta que hay que acordarse de hacer es la resta.** El error clásico es contestar "no, no se disuelve todo" y quedarse ahí. La consigna implícita siempre es **cuánto** se disuelve y **cuánto** queda.

💡 **El par de diapositivas 37–38 es el ejercicio modelo, presentado con las dos respuestas posibles.** Vale la pena quedarse con el método unificado, que sirve para los dos casos:

```
MÉTODO — "¿se disuelve todo?"
────────────────────────────────────────────────
1. Pasar el SOLVENTE a gramos (δ, si viene en mL)
2. Escalar la solubilidad a ESA cantidad de solvente:
        máx = S × (m_solvente / 100)
3. Comparar con lo que quiero disolver:
        ≤ máx  →  se disuelve TODO           → insaturada (o saturada justo)
        >  máx →  se disuelve "máx"          → SATURADA + precipitado
                  precipitado = cantidad − máx
```

⚠️ **Y el chequeo conceptual:** cuando queda precipitado, la solución **está saturada** — no "sobresaturada". La sobresaturación es el estado metaestable de la pág. 32, que se consigue enfriando con cuidado, no tirando soluto de más. Si tirás soluto de más, el exceso **se va al fondo** y arriba te queda una solución **saturada**.

---

## P1 — pág. 39 · Bibliografía

Lista de libros:

- **Temas de química General**, Angelini, Baumgartner, Benitez, Bulwik, Crubellati, Landau, Lastres Flores, Pouchan, Servant, Sileo. EUDEBA, 1994.
- **Chemistry.** Housecroft, Constable. Pearson, Prentice Hall, 2006.
- **Química, la ciencia central.** Brown, Le May, Bursten. Pearson, Prentice Hall, 2003.
- **Shriver and Atkins Inorganic Chemistry.** Atkins, Overton, Rourke, Weller, Armstrong. W. H. Freeman and Company, 2010.
- **Chemical Bonding and Molecular Geometry - From Lewis to Electron Densities.** Gillespie, Oxford, 2001.

**Explicación:** la misma bibliografía de todas las clases. Para **este** tema en particular, los dos que sirven de verdad son:

- **Temas de Química General (EUDEBA)** — es el libro de la cátedra, en castellano, y tiene los ejercicios de concentración y solubilidad en el formato exacto en el que se piden acá.
- **Brown / Le May, "Química, la ciencia central"** — el capítulo de Propiedades de las Soluciones tiene las curvas de solubilidad, la ley de Henry y las propiedades coligativas muy bien explicadas, con muchísimos ejercicios resueltos.

Los de Atkins y Gillespie son de estructura y enlace: sirvieron para las Clases 2 y 3, no para ésta.

---

---

# Resumen de la Clase 6 en una página

## 1. Sistemas materiales — el árbol completo

| Criterio | Opciones |
|---|---|
| **Propiedades** | **Físicas** (no cambia la identidad) / **Químicas** (sí cambia) |
| **Propiedades** | **Extensivas** (dependen de la cantidad) / **Intensivas** (no dependen → **caracterizan**) |
| **Fases** | **Homogéneo** (1 fase) / **Heterogéneo** (≥ 2 fases, con **interfaces**) |
| **Componentes** | **Sustancia pura** (1) / **Mezcla** (≥ 2) |

$$\boxed{\delta = \frac{m}{V}} \qquad 1\ \tfrac{g}{cm^3} = 1\ \tfrac{g}{mL} = 1\ \tfrac{kg}{L} = 1000\ \tfrac{kg}{m^3}$$

**La tabla de doble entrada (reconstruila de memoria):**

| | Sustancia pura | Mezcla |
|---|---|---|
| **Homogéneo** | Agua destilada | **Alcohol + agua ⟵ SOLUCIÓN** |
| **Heterogéneo** | **Agua + hielo** (1 componente, 2 fases) | Agua + aceite |

## 2. Solución — definición

> **Mezcla HOMOGÉNEA de 2 o más sustancias que NO reaccionan entre sí.**
> **Soluto (sto)** = el de MENOR cantidad · **Solvente (sv)** = el de MAYOR cantidad · **Solución (sc)** = el todo

Existen en los 3 estados: aire (gas), NaCl(ac) (líquido), bronce (sólido = **aleación**).

## 3. ⭐ LAS UNIDADES DE CONCENTRACIÓN — la tabla que hay que saber

| Unidad | Fórmula | Denominador | Unidades obligadas |
|---|---|---|---|
| **% m/m** | $\dfrac{m_{sto}}{m_{sc}}\cdot 100$ | Solución | Las mismas arriba y abajo |
| **% m/V** | $\dfrac{m_{sto}}{V_{sc}}\cdot 100$ | Solución | **g** y **cm³ (= mL)** |
| **% V/V** | $\dfrac{V_{sto}}{V_{sc}}\cdot 100$ | Solución | Las mismas |
| **M** (molar) | $\dfrac{n_{sto}}{V_{sc}}$ | Solución | mol y **LITROS** |
| **m** (molal) | $\dfrac{n_{sto}}{m_{sv}}$ | ⚠️ **SOLVENTE** | mol y **kg** |
| **x** (fracción molar) | $\dfrac{n_{sto}}{n_{sto}+n_{sv}}$ | Totales | mol (queda entre 0 y 1) |
| **ppm** | $\dfrac{m_{sto}}{m_{sc}}\cdot 10^6$ | Solución | Las mismas |

$$\boxed{\chi_{sto} + \chi_{sv} = 1} \qquad\qquad \boxed{1\ \% = 10\,000\ \text{ppm}}$$

$$\boxed{ppm \approx \frac{mg_{sto}}{L}} \quad \text{⚠️ SÓLO si el solvente es agua y está MUY diluida}$$

⚠️ **M vs m:** la molaridad **depende de T** (el volumen se dilata), la molalidad **no**. La molalidad es la de las **propiedades coligativas**.

## 4. ⭐ RELACIONES ÚTILES — sin esto no se resuelve nada

$$n = \frac{m}{Mr} \qquad\qquad \delta = \frac{m}{V}$$

| Magnitud | ¿Aditiva? |
|---|---|
| **Masas** | ✓ $m_{sto} + m_{sv} = m_{sc}$ |
| **Moles** | ✓ $n_{sto} + n_{sv} = n_{tot}$ |
| **Volúmenes** | ❌ **NO** — $V_{sto} + V_{sv} \neq V_{sc}$ (salvo que el problema lo aclare) |

**Ejemplo:** 1 L H₂O + 1 L EtOH = **1,93 L** → contracción del **3,5 %**.

**El puente maestro (la cadena que resuelve todo):**

$$V_{sc} \xrightarrow{\times \delta_{sc}} m_{sc} \xrightarrow{\times \%m/m} m_{sto} \xrightarrow{\div Mr} n_{sto} \xrightarrow{\div V_{sc}(L)} M$$

Y para la molalidad, el desvío obligado: $\ m_{sv} = m_{sc} - m_{sto}$

**Conversión de rótulo comercial a molaridad:**

$$\boxed{M = \frac{\%m/m \cdot \delta_{sc}\left(\tfrac{g}{mL}\right) \cdot 10}{Mr_{sto}}}$$

## 5. 🔑 MÉTODO — preparar una solución desde el sólido

```
1. n_sto = M · V_sc(L)                  ⚠️ V en LITROS
2. m_sto = n_sto · Mr                   ⚠️ Mr de la fórmula CORRECTA
   (todo junto:  m_sto = M · V(L) · Mr)
3. En el laboratorio, EN ESTE ORDEN:
   pesar → sólido al matraz → poco agua → DISOLVER → enrasar al aforo
```

⚠️ **Se disuelve ANTES de enrasar**, porque los volúmenes no son aditivos.
⚠️ "Disolver **hasta** 200 mL de solución" ≠ "disolver **en** 200 mL de agua".

**Ejemplo modelo:** 200 mL de CuCl₂ 0,50 M → n = 0,2 × 0,5 = 0,1 mol → m = 0,1 × 135 = **13,5 g**

## 6. 🔑 MÉTODO — diluciones

$$\boxed{C_0 \cdot V_0 = C_F \cdot V_F} \qquad\text{porque}\qquad \boxed{\text{los MOLES de soluto NO cambian}}$$

| Variable | Qué es |
|---|---|
| **V₀** | El volumen **tomado con la pipeta** de la solución madre |
| **V_F** | El volumen **FINAL TOTAL** (el del matraz), **NO** el agua agregada |
| Agua agregada | $V_F - V_0$ |

⚠️ Las unidades **se cancelan**: cualquier concentración y cualquier volumen, siempre que sean coherentes. **No hace falta pasar mL a L.**

$$V_0 = \frac{C_F V_F}{C_0} \qquad C_F = \frac{C_0 V_0}{V_F} \qquad V_F = \frac{C_0 V_0}{C_F}$$

**Notación 1:n** → **1 volumen original llevado a n volúmenes TOTALES**:

$$M_2 = M_1 \cdot \frac{1}{n}$$

| 1:2 | 1:10 | 1:25 | 1:50 |
|---|---|---|---|
| ÷2 | ÷10 | ÷25 | ÷50 |

⚠️ 1:10 **no** es "1 parte + 10 partes de agua" (eso sería 1:11). ⚠️ En serie, los factores se **multiplican** (dos 1:10 = 1:100).

## 7. Solubilidad

> **Solubilidad** = la **máxima** concentración de un soluto que puede disolverse en **cierto** solvente a una **determinada temperatura**.

Se suele dar en **g de soluto / 100 g de solvente**. Es un **equilibrio dinámico**:

$$\text{NaCl(s)} \rightleftarrows \text{Na}^+_{(ac)} + \text{Cl}^-_{(ac)}$$

| Tipo | Relación | En el gráfico | Estable |
|---|---|---|---|
| **Insaturada** | c **<** S | **Debajo** de la curva | ✓ |
| **Saturada** | c **=** S | **Sobre** la curva | ✓ (equilibrio) |
| **Sobresaturada** | c **>** S | **Arriba** de la curva | ❌ metaestable |

**Efecto de la temperatura:**

| Soluto | Solubilidad con T ↑ | Por qué |
|---|---|---|
| **Sólidos** (sales iónicas) | **AUMENTA** (casi siempre) | Disolver es endotérmico |
| **GASES** | **DISMINUYE** (siempre) | Disolver es exotérmico |

**Del gráfico de curvas (se pregunta):**

| Pregunta | Respuesta | Criterio |
|---|---|---|
| ¿La excepción? | **NH₃, HCl, SO₂** — los **gases**, bajan | La curva **baja** |
| ¿La más sensible a T? | **KNO₃** | Mayor **PENDIENTE** |
| ¿La menos sensible a T? | **NaCl** (35,7 → 39,8) | Curva **plana** |

⚠️ "Sensible a T" = **pendiente**, no altura. El KI es el más soluble pero no el más sensible.

**Ley de Henry (gases):** $S_{gas} = k_H \cdot P_{gas}$ → la gaseosa se conserva **fría y cerrada**.

## 8. 🔑 MÉTODO — "¿se disuelve todo?"

```
1. Pasar el SOLVENTE a gramos     (con δ, si viene en mL)
2. Escalar la solubilidad:          máx = S × (m_solvente / 100)
3. Comparar:
      cantidad ≤ máx  →  se disuelve TODO          → insaturada
      cantidad >  máx →  se disuelve "máx"         → SATURADA + precipitado
                         precipitado = cantidad − máx    ⚠️ ¡hacer la resta!
```

**Ejemplo resuelto (AgNO₃, S = 211,60 g/100 g H₂O a 18 °C, 300 mL de agua):**

| Paso | Cuenta |
|---|---|
| 1. Solvente a gramos | 300 mL × 0,99868 g/mL = **299,604 g** |
| 2. Máximo | 211,60 × 2,99604 = **633,96 g** |
| 3a. Con **423,20 g** | 423,20 < 633,96 → **se disuelve todo** (insaturada) |
| 3b. Con **823,20 g** | 823,20 > 633,96 → se disuelven **633,96 g**, quedan **189,24 g** sin disolver |

## 9. ⚠️ Errores típicos de esta clase

| ❌ Error | ✅ Correcto |
|---|---|
| Usar la masa de **solvente** en el % m/m | El denominador es la **solución**: $m_{sc} = m_{sto} + m_{sv}$ |
| Usar la masa de **solución** en la **molalidad** | La molalidad es **la única** que va sobre el **SOLVENTE** |
| Dejar el volumen en **mL** en la molaridad | La molaridad exige **LITROS** |
| Sumar volúmenes: $V_{sto} + V_{sv} = V_{sc}$ | **Los volúmenes NO son aditivos** (1 L + 1 L de EtOH = 1,93 L) |
| Enrasar el matraz **antes** de disolver | **Disolver primero**, enrasar al final |
| "Disolver en 200 mL de agua" = "hasta 200 mL de solución" | Son **distintas**: la segunda fija el volumen **final** |
| Interpretar 1:10 como "1 parte + 10 de agua" | **1 llevado a 10 TOTALES** → factor 1/10 |
| Sumar factores en diluciones seriadas | Se **multiplican**: dos 1:10 = **1:100** |
| Olvidarse el **×100** en el %m/V | Un porcentaje es **adimensional** — si te queda con unidades, falta el ×100 ⚠️ *(la pág. 15 del PDF tiene este error)* |
| Confundir **M** (molar) con **m** (molal) | Denominadores distintos: solución/L vs solvente/kg |
| Olvidar los moles del **solvente** en la fracción molar | 1 L de agua = **55,6 mol**, no es despreciable |
| Decir que **concentrada = saturada** | Concentrada es **relativo**; saturada es un **límite físico** |
| Que la solubilidad de **todo** sube con T | Los **gases BAJAN** siempre (NH₃, HCl, SO₂ en el gráfico) |
| Contestar "más sensible a T" mirando la **altura** | Se mira la **PENDIENTE**. KI es el más soluble; KNO₃ el más sensible |
| Decir "no se disuelve todo" y no hacer la resta | Hay que dar **cuánto se disuelve** y **cuánto precipita** |
| Usar la solubilidad "por 100 g" sin **escalarla** | Regla de 3 con la cantidad real de solvente |
| Decir que **agua + hielo** es homogéneo | **1 componente pero 2 FASES** → heterogéneo |
| Decir que la **masa** caracteriza un material | Es **extensiva**. Las **intensivas** (δ, T_f, concentración) caracterizan |
| Aplicar $ppm = mg/L$ a una solución concentrada | Sólo vale si el solvente es **agua** y está **MUY diluida** |
| Usar la fórmula de dilución con **V₀ = agua agregada** | V₀ es lo **tomado con la pipeta**; el agua es $V_F - V_0$ |

---

## 📌 Fórmulas de la Clase 6

$$\delta = \frac{m}{V} \qquad n = \frac{m}{Mr} \qquad m_{sto} + m_{sv} = m_{sc} \qquad V_{sto} + V_{sv} \neq V_{sc}$$

$$\%m/m = \frac{m_{sto}}{m_{sc}}100 \qquad \%m/V = \frac{m_{sto}(g)}{V_{sc}(cm^3)}100 \qquad \%V/V = \frac{V_{sto}}{V_{sc}}100$$

$$M = \frac{n_{sto}}{V_{sc}(L)} \qquad m = \frac{n_{sto}}{m_{sv}(kg)} \qquad \chi_{sto} = \frac{n_{sto}}{n_{sto}+n_{sv}} \qquad \chi_{sto} + \chi_{sv} = 1$$

$$ppm = \frac{m_{sto}(mg)}{m_{sc}(mg)}10^6 \qquad ppm \underset{\text{agua, diluida}}{\approx} \frac{m_{sto}(mg)}{L} \qquad 1\% = 10^4\ ppm$$

$$m_{sto} = M \cdot V_{sc}(L) \cdot Mr_{sto} \qquad M = \frac{\%m/m \cdot \delta_{sc} \cdot 10}{Mr_{sto}}$$

$$\boxed{C_0 V_0 = C_F V_F} \qquad M_2 = M_1 \cdot \frac{1}{n} \ \ (\text{dilución } 1{:}n)$$

$$\text{máx disuelto} = S \cdot \frac{m_{sv}}{100} \qquad \text{precipitado} = \text{cantidad} - \text{máx}$$

$$S_{gas} = k_H \cdot P_{gas} \quad (\text{Henry}) \qquad A = \varepsilon \cdot \ell \cdot c \quad (\text{Lambert-Beer})$$

---

⬅️ **Viene de:** [`Clase4/Clase4-Explicacion-Completa.md`](../Clase4/Clase4-Explicacion-Completa.md) — Interacciones intermoleculares (de ahí sale el "lo semejante disuelve a lo semejante" de las págs. 7 y 8).
📋 **Machete:** secciones 15 a 18 de [`MACHETE.md`](../MACHETE.md).
