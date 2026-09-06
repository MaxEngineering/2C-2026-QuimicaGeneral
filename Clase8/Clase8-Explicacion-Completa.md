# Clase 8 — Explicación completa, diapositiva por diapositiva

**Materia:** Química General — ECyT / UNSAM — 2do Cuatrimestre 2026
**Docentes:** Norberto Boggio, Santiago Poklepovich
**Cursada:** Lunes y Miércoles de 18 a 22 hs

**Tema de la clase:** Gases ideales (presión, leyes de Boyle, Charles, Gay-Lussac y Avogadro, PV = nRT, densidad y masa molar de un gas, mezclas y presiones parciales — ley de Dalton) · Estequiometría (ecuación química, balanceo, cálculos estequiométricos, reactivo limitante, rendimiento porcentual y pureza)

Este documento explica las **63 diapositivas** de los 4 PDFs de la Clase 8:

| Cito como | Archivo | Diapos | Contenido |
|---|---|---|---|
| **P1** | `Clase6_NB-2026_GasesIdeales.pdf` | 25 | Estados de agregación y cambios de estado · el aire como mezcla · presión y presión atmosférica · CNPT y unidades · leyes de Boyle-Mariotte, Charles, Gay-Lussac y Avogadro · PV = nRT · postulados del gas ideal · ley combinada · densidad y masa molar de un gas · mezclas de gases, fracción molar y **ley de Dalton** |
| **P2** | `Clase 7 _parte 1_NB_Estequio2026.pdf` | 13 | Qué es una reacción química · la ecuación química · ley de conservación de la masa · coeficientes estequiométricos · balanceo a **ojímetro** y **método algebraico** · símbolos de estado · lectura micro y macroscópica de una ecuación · tipos de reacciones |
| **P3** | `Clase 7 _parte 2_NB.pdf` | 13 | Problema 1 (combustión de metilamina) · qué es la estequiometría · **diagrama "todos los caminos conducen al mol"** · Problema 2 (NCl₃ + H₂O) partes a, b y c · el paso a paso de un cálculo estequiométrico |
| **P4** | `Clase 7 _parte 3_NB.pdf` | 12 | **Reactivo limitante y en exceso** · cómo identificarlo · cuánto sobra del que está en exceso · **rendimiento porcentual** · **pureza de reactivos** |

> ⚠️ **Sobre la numeración de los archivos.** Los PDFs del docente se llaman `Clase6_...` y `Clase 7 _parte N...`, pero van acá como **Clase 8**. El corrimiento viene de que **la clase 5 no se dio** (por eso la carpeta `Clase6(5nohay)`) y de que la **Clase 7 fue continuación de Soluciones**, sin material nuevo. Los PDFs originales **no se renombran**. Dentro de este apunte los cito como **P1 a P4** en el orden en que se dieron.

> **De qué se trata esta clase.** Son **dos temas**, y no es casualidad que vayan juntos.
>
> 1. **Gases** cierra la cadena de estados de agregación: la Clase 4 te dijo *cuándo* algo es gas (E_c > E_p); ahora aparece la ecuación que describe *cómo se comporta* ese gas: $PV = nRT$.
> 2. **Estequiometría** es el tema que unifica TODO lo cuantitativo de la materia. La pregunta ya no es "¿cuánto hay?" (Clase 6, soluciones) sino **"¿cuánto se forma / cuánto se consume?"**.
>
> El puente entre los dos es **el mol**. Un gas te da moles vía $n = PV/RT$; una solución te da moles vía $n = M\cdot V$; un sólido te da moles vía $n = m/Mr$. Y una vez que tenés moles, la **ecuación balanceada** te lleva a cualquier otro moles de la reacción. Ése es literalmente el mensaje de la diapositiva P3 — pág. 2: **"todos los caminos conducen al mol"**.
>
> ⚠️ **Esta clase es de cuentas puras.** No hay casi nada conceptual para "entender y ya". Lo que hay que poder hacer solo, sin mirar: balancear, pasar cualquier dato a moles, aplicar la regla de tres de los coeficientes, y volver a la unidad que te piden.

> 💡 **El vocabulario nuevo, todo junto (no confundirlos nunca):**
>
> | Término | Qué es |
> |---|---|
> | **Coeficiente estequiométrico** | El número **grande adelante** de la fórmula (2 NaOH). Se puede cambiar al balancear |
> | **Subíndice** | El número **chiquito abajo** dentro de la fórmula (H₂O). ⚠️ **NUNCA se toca** — cambiarlo cambia la sustancia |
> | **Reactivo limitante (RL)** | El que se **consume del todo** y fija cuánto producto se forma |
> | **Reactivo en exceso** | El que **sobra**. Queda junto al producto al final |
> | **Rendimiento teórico** | Lo que sale **en el papel**, suponiendo que reacciona todo el RL |
> | **Rendimiento real** | Lo que se **midió en el laboratorio**. Siempre ≤ teórico |
> | **Pureza** | Qué fracción de lo que pesaste es realmente el reactivo (el resto son impurezas que **no reaccionan**) |

---
---

# PARTE 1 — `Clase6_NB-2026_GasesIdeales.pdf` (25 diapositivas)

## P1 — pág. 1 · Portada: Gases — Las leyes de los gases

**Qué se ve:** portada con el encabezado *ECyT – UNSAM 2do. Cuatri 2026*, el título **Gases / Las leyes de los gases**, los docentes (Norberto Boggio, Santiago Poklepovich) y el horario. A la derecha, una **hoja de estampillas filatélicas** titulada "LEYES DE LOS GASES IDEALES", con un recuadro por ley: Boyle-Mariotte ($P_1V_1 = P_2V_2$, T y n constantes), Charles ($V_1/T_1 = V_2/T_2$, P y n constantes), Gay-Lussac ($P_1/T_1 = P_2/T_2$, V y n constantes), Avogadro ($V_1/n_1 = V_2/n_2$, P y T constantes), Ley combinada ($P_1V_1/T_1 = P_2V_2/T_2$, n constante), Ecuación de los gases ideales ($PV = nRT$, con $R = 8{,}314472\ \text{J/mol·K}$) y Ley de Dalton de las presiones parciales ($P_{total} = P_A + P_B + P_C + \dots$, $P_A = X_A\cdot P_{total}$).

**Explicación:** esa hoja de estampillas es, en los hechos, **el resumen de toda la parte de gases**. Si la mirás con atención, ya tenés las siete fórmulas de la clase. Fijate el patrón: **cada ley fija dos variables y relaciona las otras dos**. Boyle fija T y n; Charles fija P y n; Gay-Lussac fija V y n; Avogadro fija P y T. Las cuatro son casos particulares de una sola ecuación general, $PV = nRT$, que es a la que hay que llegar.

---

## P1 — pág. 2 · Estados de agregación de la materia

**Qué se ve:** tres fotos de **balones de vidrio con bromo** en los tres estados, y debajo de cada uno un círculo con el modelo de partículas ampliado.

| Foto | Qué se ve macroscópicamente | Modelo de partículas |
|---|---|---|
| **GAS** | balón lleno de vapor pardo-rojizo, uniforme | pocas partículas, muy separadas, con **estelas** (se mueven rápido) |
| **LÍQUIDO** | líquido oscuro acumulado en el fondo, con superficie plana | partículas juntas pero **desordenadas**, apoyadas unas sobre otras |
| **SÓLIDO** | sólido naranja congelado en el fondo del balón, sobre un baño frío | partículas **ordenadas y empaquetadas**, sin estelas |

**Explicación:** esto es exactamente la Clase 4 (interacciones + $E_c$ vs $E_p$), pero visto con la sustancia real. El bromo es cómodo para mostrarlo porque tiene el punto de ebullición cerca de la temperatura ambiente (Br₂ hierve a 59 °C), así que con un mechero y un baño frío recorrés los tres estados de **la misma sustancia**.

⚠️ **Punto clave que suele preguntarse:** entre los tres balones **no cambió la sustancia** — sigue siendo Br₂, con su mismo enlace covalente interno. Lo único que cambió es la **energía cinética** de las moléculas frente a las **fuerzas de London** entre ellas. Los cambios de estado son **físicos**, no químicos: no se rompe ningún enlace intramolecular.

---

## P1 — pág. 3 · Los tres estados, esquema de partículas

**Qué se ve:** tres erlenmeyers tapados, cada uno con una lupa que amplía el contenido:

- **(a) Solid** — un cubito violeta en el fondo; ampliado: red **cúbica ordenada** de esferas.
- **(b) Liquid** — líquido azul que ocupa el fondo con superficie definida; ampliado: esferas **juntas pero desordenadas**.
- **(c) Gas** — el frasco parece vacío (verde tenue); ampliado: esferas **muy separadas** con estelas de movimiento.

**Explicación:** es la versión esquemática de la diapositiva anterior, y lo que hay que leer son las **tres propiedades que definen el estado gaseoso** y que después justifican los postulados del gas ideal:

| | Sólido | Líquido | Gas |
|---|---|---|---|
| **Forma propia** | ✓ sí | ❌ no (toma la del recipiente) | ❌ no |
| **Volumen propio** | ✓ sí | ✓ sí | ❌ **no: ocupa TODO el recipiente** |
| **Compresible** | ❌ prácticamente no | ❌ prácticamente no | ✓ **muchísimo** |
| **Distancia entre partículas** | ≈ el tamaño de la partícula | ≈ el tamaño de la partícula | **≫ el tamaño de la partícula** |

⚠️ El líquido **sí** tiene volumen propio (por eso tiene superficie plana y no llena el frasco); el gas **no**. Ésa es la diferencia operativa entre (b) y (c), y es la razón de que para un gas siempre valga "$V$ = el volumen del recipiente".

---

## P1 — pág. 4 · Cambios de estado

**Qué se ve:** un esquema con los tres estados en fila (sólido a la izquierda como red ordenada, líquido en el medio como aglomerado desordenado, gas a la derecha como partículas dispersas con estela) y **seis flechas** rotuladas. Las **rojas** van hacia la derecha (absorben energía) y las **azules** hacia la izquierda (liberan energía):

```
                        SUBLIMACIÓN  (S → G)
              ┌──────────────────────────────────────►
              │      FUSIÓN            EVAPORACIÓN
   SÓLIDO ────┼──────────────►  LÍQUIDO ──────────────►  GAS
              │  ◄──────────────       ◄──────────────
              │   SOLIDIFICACIÓN        CONDENSACIÓN
              └◄─────────────────────────────────────
                        DEPOSICIÓN  (G → S)
```

**Explicación:** los nombres hay que sabérselos en las dos direcciones, porque en el parcial los piden cruzados.

| Cambio | Nombre | ¿Energía? |
|---|---|---|
| Sólido → Líquido | **Fusión** | absorbe (endotérmico) |
| Líquido → Sólido | **Solidificación** (o congelación) | libera (exotérmico) |
| Líquido → Gas | **Evaporación** o **vaporización** | absorbe |
| Gas → Líquido | **Condensación** | libera |
| Sólido → Gas (directo) | **Sublimación** | absorbe |
| Gas → Sólido (directo) | **Deposición** (o sublimación inversa) | libera |

**Lo que el docente da por sabido:** las flechas rojas van en el sentido de **aumentar la energía cinética** ($E_c \uparrow$, es decir calentar) y las azules en el de **disminuirla** (enfriar). Enganchá con la Clase 4: al calentar, $E_c$ crece hasta superar la $E_p$ de las fuerzas intermoleculares, y las partículas se sueltan.

📝 **Ejemplos concretos:** la naftalina y el hielo seco (CO₂ sólido) **subliman** a presión ambiente; la escarcha en el vidrio del auto en invierno se forma por **deposición** del vapor de agua.

---

## P1 — pág. 5 · El aire es una mezcla de gases

**Qué se ve:** dos gráficos de torta 3D. El primero, rotulado **Aire**: Nitrógeno 78,08 %, Oxígeno 20,95 %, y un gajo separado "Resto: 0,97 %". Una flecha lleva ese gajo al segundo gráfico (**Resto**), donde se ve Argón 0,93 %, CO₂ 0,03 % y "Otros: 0,035 %". Y de "Otros" sale una flecha roja a una tabla:

| Componente | % |
|---|---|
| Neón | 0,0018 % |
| Helio | 0,0005 % |
| CH₄ | 0,00017 % |
| H₂ | 0,00006 % |
| N₂O | 0,00003 % |
| Xenón | 0,000009 % |
| Ozono | 0,000004 % |
| CₙHₘFₓCl_y | 0,00000001 % |

**Explicación:** esta diapositiva parece de cultura general, pero está puesta acá **para preparar la ley de Dalton** (P1 — pág. 25). El mensaje es: el aire que respirás **no es un gas, es una mezcla**, y cada componente contribuye a la presión total en proporción a **cuánto hay de él**.

**Lo que el docente da por sabido:** para gases, ese "%" es en realidad **% en volumen**, y por la ley de Avogadro (volúmenes iguales ⇒ igual número de partículas) **el % en volumen es igual al % en moles**. O sea:

$$\chi_{N_2} = 0{,}7808 \qquad \chi_{O_2} = 0{,}2095 \qquad \chi_{Ar} = 0{,}0093$$

Y entonces, a 1 atm de presión total: $P_{O_2} = 0{,}2095 \times 1\ \text{atm} = \mathbf{0{,}21\ atm}$. Ése es exactamente el dato que se usa en los ejercicios de presión parcial.

⚠️ **Ojo con el CO₂:** 0,03 % parece nada, y sin embargo es el que gobierna el efecto invernadero. La cantidad no dice nada sobre la importancia.

---

## P1 — pág. 6 · Presión de un gas

**Qué se ve:** tres dibujos arriba a la izquierda: un cubo transparente con partículas grises rebotando (rotulado "Partículas" y "Contenedor"); y dos recuadros verdes, uno con partículas trazando trayectorias contra las paredes y otro con **flechas rojas apuntando hacia afuera** desde el centro (marcado "P"). A la derecha, la cadena:

> Presión que ejerce el gas ⬇ **Choques de las partículas con las paredes del recipiente**

Debajo, en negrita: *"A mayor frecuencia de choques (mayor energía cinética de las partículas), mayor será la presión ejercida por el gas"*. Y las fórmulas:

$$\boxed{P = \frac{F}{A}} \qquad [F] = \text{N (Newton)} \qquad [A] = \text{m}^2 \qquad 1\ \text{Pa} = 1\ \text{N/m}^2$$

**Unidades de P:** atm, mmHg, Pa, bar.

**Explicación:** ésta es **la definición microscópica de presión**, y es la que hay que saber explicar con palabras en el parcial. La presión de un gas **no** es una propiedad misteriosa: es el resultado de que **miles de millones de partículas chocan contra las paredes por segundo**, y cada choque transmite un impulso. Muchos choques pequeñitos, promediados, dan una fuerza constante repartida sobre el área ⇒ una presión.

**De acá salen, sin fórmulas, las tres leyes de gases:**

| Si… | ¿Por qué cambia la presión? | Ley |
|---|---|---|
| **achico el volumen** (mismo n, misma T) | las partículas tienen menos camino que recorrer ⇒ chocan **más seguido** ⇒ P ↑ | **Boyle** |
| **subo la temperatura** (mismo n, mismo V) | las partículas van **más rápido** ⇒ chocan más seguido **y más fuerte** ⇒ P ↑ | **Gay-Lussac** |
| **agrego más gas** (mismo V, misma T) | hay **más partículas** chocando ⇒ P ↑ | (Avogadro) |

⚠️ Fijate que la presión depende de **la frecuencia y la energía de los choques**, no de qué gas sea. Por eso, en el modelo ideal, **1 mol de H₂ y 1 mol de Xe hacen exactamente la misma presión** en el mismo V y T, aunque el Xe pese 65 veces más.

---

## P1 — pág. 7 · Presión atmosférica (columna de aire)

**Qué se ve:** una imagen de la Tierra desde el espacio (se distingue Sudamérica) con una **columna de aire prismática de 1 m² de sección** que baja desde la atmósfera hasta la superficie. Rótulos: "Columna de aire de 1 m² de sección", "Fuerza gravitacional" (flecha verde hacia abajo) y "Presión en la superficie" (flecha amarilla). A la derecha: *"Es la fuerza (o peso) que ejerce la masa de una columna de aire de 1 m² de sección sobre la tierra"*, con $P = F/A$.

**Explicación:** la presión atmosférica es un caso particular de $P = F/A$ donde la fuerza es literalmente **el peso del aire que tenés encima**. La columna de 1 m² de sección que llega hasta el borde de la atmósfera pesa unos **10.300 kg** — o sea, tenés unas 10 toneladas de aire apoyadas sobre cada metro cuadrado.

**Hagamos la cuenta que el docente saltea:**

$$P = \frac{F}{A} = \frac{m\,g}{A} = \frac{10.300\ \text{kg} \times 9{,}8\ \text{m/s}^2}{1\ \text{m}^2} \approx 1{,}01\times10^5\ \text{Pa} = \mathbf{1\ atm}$$

Y ahí está de dónde sale el valor de 1 atm ≈ 101.325 Pa.

⚠️ **La pregunta obvia:** ¿por qué no te aplasta? Porque la presión actúa **en todas direcciones por igual** (mirá las flechas rojas de la diapositiva anterior) y tu cuerpo tiene la misma presión adentro. Lo que sentís no es la presión sino los **desequilibrios** de presión (te destapás los oídos en el avión).

---

## P1 — pág. 8 · De qué depende la presión atmosférica con la altura

**Qué se ve:** un paisaje con árboles a la izquierda, una montaña a la derecha y, en el medio, una **columna vertical transparente llena de puntos rojos** (moléculas de aire). Los puntos están **muy juntos abajo y cada vez más separados arriba**. Dos llaves marcan dos alturas: la de abajo (nivel del suelo) con el texto *"Estas moléculas contribuyen a la presión a esta altura"* abarcando **toda** la columna; y la de arriba (a la altura de la cima) con el mismo texto pero abarcando **sólo el tramo superior**.

**Explicación:** ésta es la explicación visual de por qué **la presión baja con la altura**. A una altura dada, la presión la producen **únicamente las moléculas que están por encima**. Al nivel del mar tenés toda la atmósfera arriba; en la cima de la montaña, sólo una parte.

Y el gradiente de densidad (puntos apretados abajo, dispersos arriba) es consecuencia de lo mismo: el aire de abajo está **comprimido por el peso del de arriba**. Es Boyle actuando por gravedad.

📡 **Conexión con Telecomunicaciones:** esta variación de densidad con la altura es la razón física de que el **índice de refracción del aire disminuya con la altura**, y por eso las ondas de radio (y la luz) se **curvan levemente hacia abajo** al propagarse cerca de la superficie. Ese efecto (*k-factor* ≈ 4/3 en enlaces de microondas) hace que el **horizonte de radio sea ~15 % más lejano que el horizonte óptico** — es un dato que se usa para calcular la altura de las torres en un radioenlace. También explica los **conductos troposféricos**, en los que una inversión de temperatura atrapa la señal y la propaga cientos de kilómetros de más.

---

## P1 — pág. 9 · Presión atmosférica — Torricelli y el barómetro

**Qué se ve:** el título, un recuadro con *"Es la presión que ejerce el aire sobre la Tierra"*, el retrato de **Torricelli (1608-1674)** y, a la derecha, el esquema del **barómetro**: un tubo vertical cerrado arriba con **vacío** en la parte superior, lleno de **mercurio** hasta una altura marcada **76 cm**, con el extremo abierto sumergido en una cubeta de mercurio. Flechas rosas hacia abajo sobre la superficie de la cubeta rotuladas "Presión atmosférica" y una flecha amarilla hacia arriba dentro del tubo.

Dos recuadros de texto:
- *"La P_atm es la presión que soporta una columna de mercurio de 760 mm de altura, 0 ºC y a nivel del mar."*
- *"1 mmHg es la presión ejercida por una columna de mercurio de 1 mm de altura. 1 mmHg = 1 torr. **1 atm = 760 mmHg = 101325 Pa**"*

**Explicación:** el experimento de Torricelli (1643) es cómo se **midió** por primera vez la presión atmosférica. Llenás un tubo de mercurio, lo das vuelta sobre una cubeta, y el mercurio **baja hasta que se equilibra**: el peso de la columna que queda iguala a la presión que el aire hace sobre la superficie de la cubeta. Esa altura de equilibrio es **760 mm al nivel del mar**.

**Lo que hay que entender (y suelen preguntar):** el espacio de arriba del tubo es **vacío** (vacío de Torricelli). Si no lo fuera, habría gas empujando hacia abajo y la columna no llegaría a 760 mm. Y la altura **no depende del diámetro del tubo**: un tubo el doble de ancho tiene el doble de peso de mercurio pero también el doble de área, y $P = F/A$ queda igual.

⚠️ **Por qué mercurio y no agua:** el mercurio tiene δ = 13,6 g/cm³. Con agua (δ = 1) la columna tendría que medir $760 \times 13{,}6 = \mathbf{10.336\ mm} \approx 10{,}3\ \text{m}$. Un barómetro de agua sería un tubo de más de 10 metros. Ése es también el límite físico de una bomba de succión: **no podés chupar agua desde más de ~10 m de profundidad**, por más buena que sea la bomba.

### 🔑 La tabla de conversiones — hay que saberla de memoria

$$\boxed{1\ \text{atm} = 760\ \text{mmHg} = 760\ \text{Torr} = 101.325\ \text{Pa} = 1{,}013\times10^5\ \text{Pa} = 1013\ \text{hPa} = 1{,}013\ \text{bar}}$$

---

## P1 — pág. 10 · La presión disminuye con la altura (ejemplo numérico)

**Qué se ve:** un dibujo en perspectiva de una ladera. Abajo, al borde del agua, un **barómetro marcando 1 atm**. Arriba, en la meseta, otro **barómetro marcando 0,83 atm**. Una flecha amarilla vertical indica la diferencia de altura: **1500 m**.

**Explicación:** es el número concreto de lo que explicaba la pág. 8. Subir 1500 m te baja la presión un **17 %**.

**Regla práctica útil:** cerca del nivel del mar la presión cae aproximadamente **1 mmHg cada 11 metros** (o ~12 hPa cada 100 m).

**Consecuencia que conviene tener a mano:** como el agua hierve cuando su presión de vapor iguala a la presión externa, **a menor presión, menor temperatura de ebullición**.

| Lugar | Altura | P (atm) | T de ebullición del agua |
|---|---|---|---|
| Nivel del mar | 0 m | 1,00 | **100 °C** |
| Córdoba, sierras | ~1500 m | 0,83 | ~95 °C |
| La Paz, Bolivia | ~3600 m | 0,64 | **~87 °C** |
| Cima del Everest | 8848 m | 0,31 | ~70 °C |

Por eso en altura los fideos tardan más: el agua hierve, sí, pero **a menos temperatura**, y la cocción depende de la temperatura, no del burbujeo.

---

## P1 — pág. 11 · CNPT y unidades

**Qué se ve:** tres bloques recuadrados.

> **CNPT (condiciones normales de presión y temperatura)**
> presión = **1 atm** · temperatura = **273 K**

> **Condiciones ambientales de presión y temperatura**
> presión = **1 atm** · temperatura = **298 K**

> **Unidades Presión y Temperatura**
> $1\ \text{atm} \equiv 760\ \text{mmHg} \equiv 760\ \text{Torr} \equiv 1{,}013\cdot10^5\ \text{Pa} \equiv 1013\ \text{hPa}$
> $T(K) = 273{,}15 + T(°C)$

**Explicación:** ⚠️ **Esta diapositiva es de memorizar tal cual.** Los enunciados de los ejercicios dicen "en CNPT" y esperan que completes P y T vos.

| Condición | P | T (K) | T (°C) |
|---|---|---|---|
| **CNPT** (normales) | 1 atm | **273 K** | 0 °C |
| **Ambientales** | 1 atm | **298 K** | 25 °C |

**Lo que el docente da por sabido — el volumen molar:** de $PV = nRT$ con n = 1 mol,

$$V_m^{CNPT} = \frac{nRT}{P} = \frac{1\times0{,}082\times273}{1} = \mathbf{22{,}4\ L/mol} \qquad V_m^{amb} = \frac{1\times0{,}082\times298}{1} = \mathbf{24{,}4\ L/mol}$$

⚠️ **El error más frecuente de todo el tema:** usar **22,4 L/mol a 25 °C**. Los 22,4 L valen **sólo en CNPT** (0 °C y 1 atm). A temperatura ambiente son 24,4 L. Si el enunciado no dice CNPT, **no uses 22,4** — usá $PV = nRT$.

⚠️ **Segundo error clásico:** meter °C en la ecuación de gases. **La temperatura SIEMPRE va en KELVIN.** Si en tu cuenta aparece un T negativo o un cero, seguro te olvidaste de convertir. (La presión y el volumen pueden ir en cualquier unidad *coherente con R*; la temperatura no tiene esa libertad, porque el cero de la escala Celsius es arbitrario y el de la Kelvin no.)

---

## P1 — pág. 12 · Leyes de los gases (diapositiva divisoria)

**Qué se ve:** una diapositiva casi vacía, con el título en verde: **Leyes de los gases**.

**Explicación:** es una separadora. Marca el pasaje de la parte descriptiva (qué es un gas, qué es la presión) a la parte **cuantitativa**: las cuatro leyes históricas que después se van a fundir en $PV = nRT$.

**Cómo conviene organizarlas mentalmente antes de arrancar** — cada ley deja **dos** variables fijas:

| Ley | Fija | Relaciona | Tipo | Fórmula |
|---|---|---|---|---|
| **Boyle-Mariotte** | n, T | P y V | inversa | $P_1V_1 = P_2V_2$ |
| **Charles** | n, P | V y T | directa | $V_1/T_1 = V_2/T_2$ |
| **Gay-Lussac** | n, V | P y T | directa | $P_1/T_1 = P_2/T_2$ |
| **Avogadro** | P, T | V y n | directa | $V_1/n_1 = V_2/n_2$ |

---

## P1 — pág. 13 · Ley de Boyle-Mariotte: relación entre presión y volumen

**Qué se ve:** arriba a la izquierda, dos cilindros con pistón: el primero con V₁ = 1,0 L y P₁ = 100 mmHg y pocas partículas rebotando; el segundo, con una flecha blanca que empuja el pistón hacia abajo, con V₂ = 0,5 L y P₂ = 200 mmHg y las mismas partículas más apretadas. Arriba a la derecha, los retratos de **Robert Boyle (1627-1691)** y **Edme Mariotte (1620-1684)**, y el rótulo **"A temperatura constante"** con:

$$P \propto \frac{1}{V} \qquad P = \frac{k}{V} \qquad PV = k$$

Abajo, dos gráficos. El de la izquierda, **Presión (atm) vs Volumen (L)**: una **hipérbola** descendente, con tres cilindros dibujados encima mostrando cómo, al agregar pesas (4,0 atm / 2,0 atm / 1,0 atm), el gas se comprime. El de la derecha, **Presión (atm) vs 1/V (1/L)**: una **recta** que pasa por el origen. Y recuadrado en naranja:

$$\boxed{P_1V_1 = P_2V_2 = k} \qquad \text{(si T es constante y la cantidad de gas no cambia)}$$

**Explicación:** apretás el gas a la mitad del volumen ⇒ la presión se duplica. Fijate los números del dibujo: 1,0 L a 100 mmHg pasa a 0,5 L a 200 mmHg. El producto $PV$ vale 100 en los dos casos.

**Por qué (con el modelo de la pág. 6):** al achicar el volumen, las partículas siguen con la misma velocidad (T constante ⇒ misma $E_c$) pero tienen **menos distancia hasta la pared**, así que chocan **más veces por segundo**. Más frecuencia de choques ⇒ más presión.

⚠️ **Los dos gráficos son la misma ley y los dos se preguntan.** Es el truco típico de "linealizar":

| Gráfico | Forma | Por qué |
|---|---|---|
| **P vs V** | hipérbola ($P = k/V$) | relación **inversa** |
| **P vs 1/V** | **recta por el origen**, pendiente = k | si llamás $x = 1/V$, queda $P = k\cdot x$ |

Si te dan una tabla de datos y te preguntan "¿cumple Boyle?", la forma correcta de contestar es **multiplicar P por V en cada fila y ver si da constante** (o graficar P contra 1/V y ver si da recta).

📝 **Ejemplo típico:** un gas ocupa 2,5 L a 1 atm. ¿Qué volumen ocupa a 3 atm (misma T)?
$$V_2 = \frac{P_1V_1}{P_2} = \frac{1 \times 2{,}5}{3} = \mathbf{0{,}83\ L}$$

---

## P1 — pág. 14 · Ley de Charles: relación entre temperatura y volumen

**Qué se ve:** el retrato de **Alexandre Charles (1746-1823)**. A la izquierda, en un recuadro rosa vertical: **"Presión Constante!"**. En el centro, un gráfico de **Volumen (ml) vs Temperatura (°C)**: una **recta roja creciente** que, extrapolada con línea punteada, corta el eje horizontal cerca de −273 °C. Sobre la recta hay dos cilindros con pistón: uno a ~−100 °C con V ≈ 30 mL y las partículas quietas y juntas, y otro a ~+70 °C con V ≈ 60 mL, el pistón más arriba y las partículas con estelas; abajo de este último, un mechero encendido. A la derecha, tres recuadros anaranjados:

$$V \propto T \qquad V = k_c\,T \qquad \frac{V}{T} = k_c$$

**Explicación:** **a presión constante**, calentar un gas lo dilata, y de manera **proporcional**. Es el globo que se infla si lo dejás al sol, o el que se arruga si lo metés en la heladera.

**Por qué:** al calentar, las partículas van más rápido y golpearían más fuerte el pistón. Pero el pistón **se puede mover** (P constante), así que en vez de aumentar la presión, **el gas se expande** hasta que la frecuencia de choques vuelve a compensar el peso del pistón.

⚠️ **La forma útil de la ley:**

$$\boxed{\frac{V_1}{T_1} = \frac{V_2}{T_2}} \qquad \text{con } T \text{ en KELVIN}$$

**El detalle que se pregunta:** en el gráfico, la recta **NO pasa por el origen** — porque el eje está en **°C**. Si volvés a graficar con el eje en **kelvin**, sí pasa por el origen, y ahí $V/T$ es realmente constante. Ésa es la razón profunda de que las leyes de gases exijan kelvin: **la proporcionalidad directa sólo existe en una escala absoluta**.

📝 **Ejemplo:** un globo de 2,0 L a 27 °C se lleva a 87 °C, a presión constante.
$$T_1 = 300\ K,\quad T_2 = 360\ K \quad\Rightarrow\quad V_2 = V_1\frac{T_2}{T_1} = 2{,}0\times\frac{360}{300} = \mathbf{2{,}4\ L}$$
⚠️ Si hubieras hecho $2{,}0 \times 87/27 = 6{,}4$ L, el resultado sería **tres veces más grande** y absurdo. Ése es el precio de no pasar a kelvin.

---

## P1 — pág. 15 · Ley de Gay-Lussac: relación entre presión y temperatura

**Qué se ve:** el retrato de **Joseph Gay-Lussac (1778-1850)**. Un recuadro verde: **"Volumen Constante!"**. Un gráfico de **Presión vs Temperatura** con una **recta creciente** que, extrapolada en punteado rojo, corta el eje de temperatura en un valor **circulado en rojo: −273,15 ºC**. Sobre la recta hay dos recipientes cerrados (V = constante) calentados por mecheros, con termómetros rojos: en T₁ la presión es P₁ y en T₂ (más caliente) es P₂ > P₁. El eje vertical marca P₀ en el punto de corte. A la derecha, tres recuadros verdes:

$$P \propto T \qquad P = k_g T \qquad \frac{P}{T} = k_c$$

Y un óvalo rojo abajo: **"Kelvin descubre el cero, surgen los °K"**.

**Explicación:** **a volumen constante**, calentar un gas **aumenta su presión**. Es la ley del recipiente rígido: la olla a presión, el aerosol al sol, la cubierta del auto después de andar en la ruta.

**Por qué:** más temperatura ⇒ más $E_c$ ⇒ las partículas chocan **más seguido y más fuerte** contra las paredes. Y como las paredes no ceden (V fijo), toda esa energía se traduce en **presión**.

$$\boxed{\frac{P_1}{T_1} = \frac{P_2}{T_2}} \qquad \text{con } T \text{ en KELVIN}$$

⚠️ **Advertencia práctica (y ejemplo típico de parcial):** nunca tires un aerosol al fuego. Un envase a 2 atm y 25 °C, llevado a 400 °C:
$$P_2 = P_1\frac{T_2}{T_1} = 2 \times \frac{673}{298} = \mathbf{4{,}5\ atm}$$
Más del doble. Por eso explotan.

**El punto histórico importante:** la extrapolación de la recta hasta P = 0 da **−273,15 °C para cualquier gas**. Ése es el descubrimiento fuerte: no importa qué gas uses, todas las rectas cortan en el mismo punto. Ese punto es el **cero absoluto**, y sugiere que existe una temperatura mínima donde el movimiento (y por lo tanto la presión) se anula.

---

## P1 — pág. 16 · La escala de temperatura absoluta — Kelvin

**Qué se ve:** el retrato de **Lord Kelvin (1824-1907), matemático y físico**. Un recuadro verde: *"Identificó a 273,15 K como el cero absoluto, teóricamente la temperatura más baja que se puede alcanzar"*. A la derecha, un gráfico de **V (mL) vs t (°C)** con **cuatro rectas** (P₁, P₂, P₃, P₄, de mayor a menor pendiente), cada una dibujada llena en el rango medido y **punteada en la extrapolación**; las cuatro convergen en un mismo punto sobre el eje horizontal, marcado con una flecha: **−273,15 °C**. Abajo, recuadrada:

$$\frac{°C}{5} = \frac{°K - 273}{5} = \frac{°F - 32}{9}$$

**Explicación:** ésta es la diapositiva que justifica **por qué existe la escala Kelvin**. Cuatro presiones distintas, cuatro rectas distintas, y sin embargo **todas apuntan al mismo cero**. Eso no puede ser casualidad: es una propiedad de la materia, no del experimento.

**Qué significa el cero absoluto:** es la temperatura a la cual, extrapolando, el volumen (y la presión) de un gas ideal **se anularían**. Físicamente: **energía cinética de traslación mínima**. No se puede alcanzar (tercer principio de la termodinámica), pero se llegó a menos de una milmillonésima de kelvin en laboratorio.

⚠️ **La fórmula de la diapositiva tiene una errata de tipeo:** la conversión correcta es

$$\frac{°C}{5} = \frac{K - 273{,}15}{5} = \frac{°F - 32}{9} \qquad\Longrightarrow\qquad \boxed{T(K) = T(°C) + 273{,}15} \qquad \boxed{T(°F) = \tfrac{9}{5}T(°C) + 32}$$

**Notación:** hoy se escribe **K**, no "°K" — el grado se eliminó en 1967 justamente porque el kelvin es una escala **absoluta**, no relativa a un punto arbitrario.

| Referencia | K | °C |
|---|---|---|
| Cero absoluto | 0 | −273,15 |
| Fusión del hielo | 273,15 | 0 |
| Ambiente | 298,15 | 25 |
| Ebullición del agua | 373,15 | 100 |

---

## P1 — pág. 17 · Leyes de los gases — el triángulo P, V, T

**Qué se ve:** un esquema circular con tres esferas de colores: **P** (roja, arriba a la izquierda), **V** (verde, arriba a la derecha) y **T** (naranja, abajo). Flechas curvas las conectan de a pares, y cada arco tiene su ley:

- P ↔ V (arriba): **Ley de Boyle** — $P_1V_1 = P_2V_2$
- V ↔ T (derecha): **Ley de Charles** — $V_1/T_1 = V_2/T_2$
- T ↔ P (izquierda): **Ley de Gay-Lussac** — $P_1/T_1 = P_2/T_2$
- En el centro: **Ley Combinada de los gases** — $\dfrac{P_1V_1}{T_1} = \dfrac{P_2V_2}{T_2}$

Abajo, recuadrado en azul: **"NO Cambia la Cantidad de Gas!"**

**Explicación:** ⚠️ **Esta diapositiva es LA que hay que poder redibujar de memoria.** Resume las tres leyes de dos variables y la que las une.

**Cómo se usa en la práctica — la regla operativa:**

$$\boxed{\frac{P_1V_1}{T_1} = \frac{P_2V_2}{T_2}} \qquad \text{(n constante)}$$

y **tachás la variable que no cambia**:

| Si el problema dice… | Tachás | Queda |
|---|---|---|
| "a temperatura constante" | T | $P_1V_1 = P_2V_2$ (Boyle) |
| "a presión constante" | P | $V_1/T_1 = V_2/T_2$ (Charles) |
| "en un recipiente rígido" / "a volumen constante" | V | $P_1/T_1 = P_2/T_2$ (Gay-Lussac) |
| nada constante | — | la combinada entera |

💡 **No hace falta memorizar las tres por separado: memorizá la combinada y tachá.** Es menos para acordarse y no te podés equivocar de fórmula.

⚠️ **La aclaración de abajo es la condición de validez:** todo esto vale **sólo si no entra ni sale gas**. Si el problema abre una válvula, pincha el globo o mezcla dos gases, **la ley combinada NO sirve** — hay que ir a $PV = nRT$ con la n que corresponda.

---

## P1 — pág. 18 · Ley de Avogadro: relación entre el volumen y la cantidad

**Qué se ve:** el retrato de **Amadeo Avogadro (1776-1856)**. En el centro, arriba, **"A P y T constantes"**, y cuatro matraces idénticos de colores distintos (rojo, azul, verde, violeta), cada uno rotulado **22,4 L** y con su contenido: **1 mol H₂**, **1 mol N₂**, **1 mol Cl₂**, **1 mol I₂**. A la derecha: *"A la misma T y P, volúmenes iguales de gases distintos contienen el mismo número de partículas (átomos o moléculas)"*. Abajo a la izquierda, recuadrado en celeste:

$$V \propto n \qquad V = k'''\,n \qquad \text{(a P y T ctes)}$$

**Explicación:** ésta es **la ley menos intuitiva y la más importante de las cuatro**, porque es la que conecta el mundo de los gases con el mundo del mol.

**Lo que dice:** 1 mol de H₂ (Mr = 2) y 1 mol de I₂ (Mr = 254) ocupan **exactamente el mismo volumen** en las mismas condiciones, aunque el segundo pese **127 veces más**. El volumen de un gas **no depende de qué gas es**, sólo de **cuántas partículas hay**.

**Por qué:** porque en un gas las partículas están **tan separadas** que su tamaño propio es despreciable frente al espacio vacío. El volumen que ocupa un gas es esencialmente **el espacio entre las partículas**, no el de las partículas.

$$\boxed{\frac{V_1}{n_1} = \frac{V_2}{n_2}} \qquad\qquad \boxed{V_m = 22{,}4\ \text{L/mol en CNPT}}$$

⚠️ **La consecuencia más usada en los ejercicios:** para gases en las mismas P y T, **la relación de volúmenes ES la relación de moles**. O sea que en una reacción entre gases, **los coeficientes estequiométricos también valen como relación de volúmenes**:

$$\text{N}_2 + 3\,\text{H}_2 \to 2\,\text{NH}_3 \qquad \Longrightarrow \qquad 1\ \text{L de N}_2 + 3\ \text{L de H}_2 \to 2\ \text{L de NH}_3$$

Eso vale **sólo para gases**. Para líquidos y sólidos, ni se te ocurra.

💡 Y de acá también sale que la **fracción molar = fracción en volumen** para gases, que es lo que usamos en la pág. 5 con la composición del aire.

---

## P1 — pág. 19 · Ley de los gases ideales

**Qué se ve:** las tres proporcionalidades listadas:

| Ley | Relación | Condición |
|---|---|---|
| Ley de Boyle-Mariotte | $P \propto \dfrac{1}{V}$ | (a n y T constantes) |
| Ley de Charles | $V \propto T$ | (a n y P constantes) |
| Ley de Avogadro | $V \propto n$ | (a P y T constantes) |

Y abajo, dos recuadros verdes:

$$V \propto \frac{nT}{P} = R\frac{nT}{P} \qquad\qquad \boxed{\mathbf{PV = nRT}}$$

Al costado, el cálculo de R con la palabra **CNPT**:

$$R = \frac{1\ \text{atm} \times 22{,}4\ \text{L}}{1\ \text{mol} \times 273{,}15\ \text{K}} = 0{,}082\ \frac{\text{atm·L}}{\text{K·mol}}$$

**Explicación:** ⚠️ **Ésta es LA fórmula de la parte de gases.** Todo lo anterior se juntó acá.

**Cómo se arma (el razonamiento, que a veces se pide):** si $V \propto 1/P$, $V \propto T$ y $V \propto n$, entonces las tres juntas dan $V \propto nT/P$. Convertir una proporcionalidad en igualdad requiere una constante, y esa constante es **R**. Reordenando: $PV = nRT$.

**De dónde sale el valor de R:** no es un número mágico, es el resultado de **medir** que 1 mol de cualquier gas ocupa 22,4 L en CNPT y despejar. Por eso R se llama **constante universal de los gases**: da igual el gas.

### 🔑 Los valores de R (y cuándo usar cada uno)

| Valor de R | Unidades | Cuándo |
|---|---|---|
| **0,082** | atm·L / (K·mol) | ⭐ **el que se usa en esta materia** (P en atm, V en litros) |
| 8,314 | J / (K·mol) | cuando hay energía de por medio (P en Pa, V en m³) |
| 62,4 | mmHg·L / (K·mol) | si la presión viene en mmHg y no querés convertir |

⚠️ **La regla de oro:** *R fija las unidades de todo lo demás*. Si usás **R = 0,082**, entonces **P va en atm, V en litros, T en kelvin y n en moles. Sin excepciones.** El 90 % de los errores en este tema son de unidades, no de concepto.

📝 **Ejemplo:** ¿cuántos moles de gas hay en un tubo de 5,0 L a 3,0 atm y 27 °C?
$$n = \frac{PV}{RT} = \frac{3{,}0 \times 5{,}0}{0{,}082 \times 300} = \frac{15}{24{,}6} = \mathbf{0{,}61\ mol}$$

---

## P1 — pág. 20 · Gases Ideales — los postulados

**Qué se ve:** el título recuadrado **Gases Ideales**, la ecuación $PV = nRT$ en un recuadro verde, y cuatro viñetas:

> ➢ Los átomos o moléculas de gas **ocupan todo el volumen del recipiente**.
> ➢ Los átomos o moléculas de gas **se mueven en forma aleatoria**.
> ➢ **No existen interacción** entre los átomos o moléculas de gas.
> ➢ **El gas se puede comprimir.**

**Explicación:** ésta es la letra chica del modelo: **las condiciones bajo las cuales $PV = nRT$ es cierta**. Y es lo que hace "ideal" al gas ideal.

| Postulado | Qué significa realmente | Qué implica |
|---|---|---|
| **Ocupan todo el volumen** | el gas no tiene volumen propio | V en la fórmula = **volumen del recipiente** |
| **Movimiento aleatorio** | sin direcciones privilegiadas | la presión es **igual en todas las paredes** |
| **No hay interacciones** | ni atracción ni repulsión entre partículas | ⭐ **el postulado clave** |
| **Se puede comprimir** | el volumen propio de las partículas es despreciable | las partículas son **puntos** |

⭐ **El tercer postulado es el que conecta con la Clase 4.** "No hay interacciones" quiere decir **no hay fuerzas intermoleculares**: ni London, ni dipolo-dipolo, ni puente de hidrógeno. Es exactamente la condición $E_c \ggg E_p$ que definía el estado gaseoso.

⚠️ **Y por eso el gas ideal NO existe.** Todo gas real tiene *algo* de fuerzas de London (todo tiene electrones). El modelo ideal es una **aproximación**, y funciona bien cuando:

| Condición | Por qué |
|---|---|
| **Presión baja** (≈ 1 atm o menos) | las partículas están lejos ⇒ las fuerzas (que caen como $1/d^6$) son despreciables |
| **Temperatura alta** | $E_c$ es tan grande que las atracciones no alcanzan a frenar nada |
| **Gas poco polar y liviano** (He, H₂, N₂, O₂) | poca α, poco μ ⇒ pocas interacciones |

Y **falla** cuando: presión muy alta (las partículas se tocan y su volumen propio deja de ser despreciable), temperatura baja (cerca de condensar) o gases muy polares (H₂O, NH₃, HF: hacen **puente de hidrógeno** incluso en fase gaseosa).

💡 **Pregunta de parcial típica:** *"¿Qué gas se aparta más del comportamiento ideal: He, N₂ o NH₃?"* → **NH₃**, porque es polar y hace puente de hidrógeno (viola el postulado de "no interacciones"). El **He** es el más ideal de todos: monoatómico, chiquito y con la polarizabilidad más baja de la tabla.

---

## P1 — pág. 21 · Cuando hay cambios simultáneos de P, V, T

**Qué se ve:** el título, $PV = nRT$ en grande, y debajo la deducción:

$$R = \frac{P_1V_1}{nT_1} \qquad \text{y} \qquad R = \frac{P_2V_2}{nT_2} \qquad\Longrightarrow\qquad \boxed{\frac{P_1V_1}{T_1} = \frac{P_2V_2}{T_2}}$$

**Explicación:** es la **demostración de la ley combinada** que apareció en el centro del triángulo de la pág. 17. El razonamiento es elegante y conviene entenderlo, porque es de una línea: **R es una constante y n no cambia**, así que $PV/(nT)$ vale lo mismo antes y después. Igualás las dos expresiones, se te va la n, y queda la combinada.

⚠️ **La condición escondida es la n:** para que se cancele, la cantidad de gas tiene que ser **la misma en los dos estados**. Si el enunciado dice "se agrega gas", "se abre la válvula", "se deja escapar la mitad", la n cambia y **hay que usar $PV = nRT$ de los dos lados por separado**.

💡 **Truco para no confundirse nunca:** poné todo lo del estado 1 de un lado y todo lo del estado 2 del otro, y despejá al final. Nunca despejes primero.

📝 **Ejemplo:** un globo sonda tiene 10 L a 1 atm y 300 K en el suelo. A 10 km de altura la presión es 0,26 atm y la temperatura 230 K. ¿Qué volumen tiene?
$$V_2 = V_1 \cdot \frac{P_1}{P_2}\cdot\frac{T_2}{T_1} = 10 \times \frac{1}{0{,}26} \times \frac{230}{300} = \mathbf{29{,}5\ L}$$
El globo casi se triplica: la caída de presión lo expande mucho más de lo que el frío lo contrae. Por eso los globos meteorológicos se largan **medio vacíos** — si los inflaras del todo, reventarían a los pocos kilómetros.

---

## P1 — pág. 22 · Determinación de densidades y masas molares con la ecuación de gas ideal

**Qué se ve:** dos deducciones en paralelo. Arriba:

$$PV = nRT \quad\text{y}\quad n = \frac{m}{Mr} \qquad\Longrightarrow\qquad \boxed{Mr = \frac{mRT}{PV}}$$

Abajo:

$$PV = nRT \quad\text{y}\quad n = \frac{m}{Mr} \quad\text{y}\quad \rho = \frac{m}{V} \qquad\Longrightarrow\qquad \boxed{\rho = \frac{P\,Mr}{RT}}$$

**Explicación:** estas dos fórmulas son **derivadas**, no hay que memorizarlas: salen de reemplazar $n = m/Mr$ en $PV = nRT$. Pero conviene tenerlas a mano porque aparecen mucho.

**Cómo se deducen, paso a paso:**

$$PV = \frac{m}{Mr}RT \;\Longrightarrow\; Mr = \frac{mRT}{PV} \qquad\text{y dividiendo por } V:\quad P = \frac{m}{V}\cdot\frac{RT}{Mr} = \rho\frac{RT}{Mr} \;\Longrightarrow\; \rho = \frac{P\,Mr}{RT}$$

**Para qué sirve cada una:**

| Fórmula | Para qué | Dato experimental |
|---|---|---|
| $Mr = \dfrac{mRT}{PV}$ | **identificar un gas desconocido** | pesás una masa conocida y medís P, V, T |
| $\rho = \dfrac{P\,Mr}{RT}$ | calcular la densidad de un gas | conocés el gas y las condiciones |

⚠️ **Tres cosas que hay que leer en $\rho = P\,Mr/RT$:**

1. **La densidad de un gas es proporcional a su masa molar.** Por eso el CO₂ (44) "cae" y el He (4) "flota" en aire (Mr promedio ≈ 29).
2. **Es proporcional a la presión** e **inversamente proporcional a la temperatura**. Por eso el aire caliente sube (globos aerostáticos) y por eso la densidad del aire cae con la altura.
3. ⚠️ **La densidad de un gas NO es una constante de la sustancia.** La del agua líquida sí (1,00 g/cm³ y listo), pero la de un gas **depende de P y T** y hay que calcularla cada vez. Esto contradice el reflejo que traés de la Clase 6.

📝 **Ejemplo — densidad del aire en CNPT:** con Mr ≈ 29 g/mol,
$$\rho = \frac{1 \times 29}{0{,}082 \times 273} = \mathbf{1{,}30\ g/L} = 1{,}30\times10^{-3}\ \text{g/cm}^3$$
Casi **800 veces menos denso que el agua**. Ése es el orden de magnitud que separa un gas de un líquido, y es la razón de que un gas sea tan compresible.

📝 **Ejemplo — identificar un gas:** 0,75 g de un gas ocupan 0,50 L a 1,0 atm y 300 K.
$$Mr = \frac{mRT}{PV} = \frac{0{,}75 \times 0{,}082 \times 300}{1{,}0 \times 0{,}50} = \mathbf{36{,}9\ g/mol}$$
→ es **Ar** (39,9) o, más probable por el redondeo, **HCl** (36,5).

---

## P1 — pág. 23 · Mezcla de gases (planteo)

**Qué se ve:** el título recuadrado **Mezcla de gases** y la pregunta: *"¿Cómo se comporta una mezcla de n_A moles de N₂ y n_B moles de O₂?"*. Abajo, tres dibujos: a la izquierda, un cilindro con tapa y **partículas azules** (rotulado P) con la leyenda **"P_T = ?"**; en el centro, otro cilindro con **partículas rojas** (rotulado P); y abajo a la derecha, la operación gráfica: *cilindro con partículas azules* **+** *cilindro con partículas rojas* **⟶** *cilindro con ambas mezcladas*.

**Explicación:** es el planteo del problema. Tenés dos gases distintos que no reaccionan entre sí, cada uno con su propia presión, y los juntás en el mismo recipiente. **¿Cuánto da la presión total?**

**La respuesta intuitiva, antes de la fórmula:** volvé a la pág. 6. La presión son **choques contra las paredes**. Si ahora hay dos tipos de partículas chocando, la pared recibe los choques de las azules **más** los de las rojas. Y como (postulado del gas ideal) **las partículas no interactúan entre sí**, cada gas se comporta como si el otro **no existiera**. Por lo tanto las presiones simplemente **se suman**.

⚠️ **La condición "que no reaccionan entre sí" es esencial.** Si mezclás H₂ y O₂ y prenden, la cantidad de moles cambia y todo esto se cae. Dalton vale para mezclas **inertes**.

---

## P1 — pág. 24 · Mezcla de gases — la deducción

**Qué se ve:** la misma pregunta arriba, un cilindro con partículas azules y rojas mezcladas a la derecha, y toda la deducción:

$$PV = nRT \qquad\qquad PV = (n_A + n_B)RT$$

$$\left.\begin{array}{l} P_AV = n_ART \\[2pt] P_BV = n_BRT \end{array}\right\} \text{Presión de cada gas si estuviese solo}$$

$$P = P_B + P_A \qquad\qquad \frac{P_A}{P} = \frac{n_ART}{(n_A+n_B)RT} = X_A$$

$$\text{Presión parcial · Ley de Dalton} \qquad \boxed{P_A = P\,X_A}$$

(con el retrato de Dalton abajo)

**Explicación:** ⚠️ **Esta diapositiva es la que hay que saber reproducir.** Es corta y es todo lo que se necesita para resolver cualquier ejercicio de mezcla de gases.

**Paso por paso:**

1. **Para la mezcla completa:** los moles totales son $n_A + n_B$, así que $PV = (n_A + n_B)RT$.
2. **Definición de presión parcial:** $P_A$ es la presión que haría el gas A **si estuviera solo** en el mismo recipiente, a la misma T: $P_AV = n_ART$.
3. **Sumando (2) para A y B:** $(P_A + P_B)V = (n_A + n_B)RT = PV$ ⇒ $\boxed{P = P_A + P_B}$
4. **Dividiendo (2) por (1):** se cancelan V, R y T, y queda $\dfrac{P_A}{P} = \dfrac{n_A}{n_A + n_B} = \chi_A$ ⇒ $\boxed{P_A = \chi_A \cdot P}$

### 🔑 Las tres fórmulas de una mezcla de gases

$$\boxed{P_{total} = \sum P_i = P_A + P_B + \dots} \qquad \boxed{P_i = \chi_i \cdot P_{total}} \qquad \boxed{\chi_i = \frac{n_i}{n_{total}} \quad\text{y}\quad \sum \chi_i = 1}$$

💡 **La fracción molar $\chi$ ya la viste en la Clase 6** (unidades de concentración). Es la misma definición, sólo que aplicada a un gas. Y es **adimensional** y va **de 0 a 1**, nunca en %.

📝 **Ejemplo:** en un recipiente hay 2,0 mol de N₂ y 3,0 mol de O₂, y la presión total es 5,0 atm.
$$\chi_{N_2} = \frac{2}{5} = 0{,}40 \;\Rightarrow\; P_{N_2} = 0{,}40 \times 5{,}0 = \mathbf{2{,}0\ atm}$$
$$\chi_{O_2} = \frac{3}{5} = 0{,}60 \;\Rightarrow\; P_{O_2} = 0{,}60 \times 5{,}0 = \mathbf{3{,}0\ atm}$$
Verificación: 2,0 + 3,0 = 5,0 atm ✓

---

## P1 — pág. 25 · Ley de Dalton de las presiones parciales

**Qué se ve:** el retrato de **John Dalton** y dos bloques de texto:

> *"La presión total de una mezcla de gases (que no reaccionan entre sí) es igual a la suma de las presiones parciales de todos los gases presentes"* **(1803)**

> *"La presión parcial de un gas en una mezcla es la presión que ejercería ese gas si estuviera **SOLO** en el recipiente"*

**Explicación:** es el enunciado formal de lo que se dedujo en la diapositiva anterior. ⚠️ **Las dos definiciones se piden textuales**, así que conviene poder escribirlas.

**Las dos palabras que no pueden faltar en la definición de presión parcial:** *"si estuviera **SOLO**"* (por eso está en rojo en la diapositiva) y *"**en el mismo recipiente y a la misma temperatura**"*.

**Y en la ley de Dalton:** *"que **no reaccionan** entre sí"*.

**Por qué funciona (la explicación conceptual que da puntos):** porque en un gas ideal **las partículas no interactúan** (postulado 3 de la pág. 20). Cada gas "no se entera" de que hay otro. Entonces cada uno hace su presión de manera independiente y las presiones se suman sin más.

💡 **Dato histórico útil:** es **el mismo Dalton** de la teoría atómica de 1803 (sección 23 del machete). Llegó a esta ley justamente **estudiando la humedad del aire**, y le sirvió como argumento a favor de que la materia es corpuscular.

📡 **Conexión con Telecomunicaciones:** las presiones parciales son la magnitud de control en la **fabricación de fibra óptica y de semiconductores**. En el proceso **MCVD** de fabricación de una preforma de fibra, se hacen circular SiCl₄ y GeCl₄ gaseosos por un tubo de sílice, y **la presión parcial de GeCl₄ define el perfil de índice de refracción** del núcleo de la fibra. En un reactor de deposición de capa (CVD/PECVD) o en un sputtering de aluminio para pistas de un chip, lo que se especifica no es "la presión" sino **la presión parcial de cada gas**, medida en mTorr, y de eso depende la composición de la película. La ley de Dalton es literalmente la ecuación de la receta.

---
---

# PARTE 2 — `Clase 7 _parte 1_NB_Estequio2026.pdf` (13 diapositivas)

## P2 — pág. 1 · Portada: Estequiometría — Ecuaciones Químicas

**Qué se ve:** portada con *ECyT – UNSAM 2do. Cuatri 2026*, el título **Estequiometría / Ecuaciones Químicas**, los docentes y el horario. A la derecha, una foto de un **mechero con llama azul** con dos círculos ampliados: el de la izquierda rotulado **"Reactants"** (moléculas rojas de O₂ y una blanca-gris de CH₄) y el de la derecha **"Products"** (moléculas de CO₂ y H₂O).

**Explicación:** la imagen es la combustión del metano vista por dentro, y ya anticipa la idea central del tema: **los átomos que entran son exactamente los mismos que salen, sólo que reordenados**. Contá los átomos en los dos círculos y te va a dar igual.

**De dónde viene la palabra:** *stoicheion* (elemento) + *metron* (medida) = **"la medida de los elementos"**. Es la contabilidad de la química.

---

## P2 — pág. 2 · ¿Qué es una reacción química?

**Qué se ve:** la definición: *"Las reacciones químicas son procesos que transforman una o más substancias llamadas **reactivos** en otras substancias llamadas **productos**"*. Debajo, dos recuadros unidos por una flecha:

```
┌─────────────────────┐        ┌─────────────────────┐
│     REACTIVOS       │───────►│     PRODUCTOS       │
│ Sustancias de       │        │ Sustancias          │
│ Partida             │        │ Formadas            │
└─────────────────────┘        └─────────────────────┘
```

**Explicación:** definición corta pero con dos cosas importantes.

1. **"Transforman"** — se rompen y se forman **enlaces**. Ésta es la diferencia con un cambio físico (fusión, disolución), donde los enlaces internos quedan intactos.
2. **La flecha no es un "igual".** Va en un solo sentido: reactivos ⟶ productos. Se lee **"da"** o **"produce"**, nunca "es igual a".

⚠️ **Cambio físico vs cambio químico** — es una distinción que se pregunta:

| | Cambio **físico** | Cambio **químico** |
|---|---|---|
| ¿Se rompen enlaces internos? | ❌ no | ✓ **sí** |
| ¿Cambia la sustancia? | ❌ no | ✓ **sí** |
| Ejemplos | fundir hielo, disolver sal, evaporar alcohol | quemar metano, oxidar hierro, neutralizar un ácido |
| ¿Es reversible fácil? | generalmente sí | generalmente no |

📝 Disolver NaCl en agua es **físico** (el NaCl sigue siendo NaCl, sólo se separaron los iones; evaporás y lo recuperás). Electrolizar esa solución es **químico** (aparecen Cl₂ y H₂, sustancias nuevas).

---

## P2 — pág. 3 · La ecuación química (sin balancear)

**Qué se ve:** el título **LA ECUACIÓN QUÍMICA** y el subtítulo *"Poniendo en forma simbólica una reacción química"*. Después, la misma reacción escrita en **tres niveles de abstracción sucesivos**:

1. **REACTIVOS** ⟶ **PRODUCTOS** (sustancias de partida ⟶ sustancias formadas)
2. **SODIO + AGUA** ⟶ **HIDRÓXIDO DE SODIO + HIDRÓGENO** (en palabras)
3. Con un cartel rosa **"USANDO FÓRMULAS"**: $\text{Na} + \text{H}_2\text{O} \longrightarrow \text{NaOH} + \text{H}_2$

Arriba a la derecha hay una foto de un **vaso de precipitados con agua** (el experimento real). A la izquierda, un recuadro: *"No se puede crear ni destruir la materia…. Solo se combina de forma distinta"*. Y a la derecha, la tabla de recuento:

| ELEMENTO | # EN REACTIVOS | # EN PRODUCTOS |
|---|---|---|
| Na | 1 | 1 |
| O | 1 | 1 |
| **H** | **2** | **3** |

**Explicación:** el recorrido de tres pasos (palabras → fórmulas → recuento) es el método para plantear cualquier ecuación.

**El punto de la diapositiva es la última fila de la tabla:** hay **2 H a la izquierda y 3 a la derecha** (2 del H₂O contra 1 del NaOH + 2 del H₂). **La ecuación NO está balanceada**, y por lo tanto **está mal escrita**: viola la ley de conservación de la masa. Un átomo de hidrógeno no puede aparecer de la nada.

⚠️ **Cómo se cuentan los átomos** (lo que se da por sabido y es donde más se equivoca la gente):

$$\underbrace{2\ \text{NaOH}}_{2\ \text{Na},\ 2\ \text{O},\ 2\ \text{H}} \qquad \underbrace{\text{Ca(NO}_3)_2}_{1\ \text{Ca},\ 2\ \text{N},\ 6\ \text{O}} \qquad \underbrace{3\ \text{Al}_2(\text{SO}_4)_3}_{6\ \text{Al},\ 9\ \text{S},\ 36\ \text{O}}$$

El **coeficiente multiplica a TODA la fórmula**; el **subíndice de afuera del paréntesis multiplica a todo lo de adentro**. En $\text{Al}_2(\text{SO}_4)_3$: el O son $4 \times 3 = 12$, y con el coeficiente 3 son $12 \times 3 = 36$.

---

## P2 — pág. 4 · La ecuación química (balanceada)

**Qué se ve:** la misma estructura, pero ahora con **dos** ecuaciones una debajo de la otra:

$$\text{Na} + \text{H}_2\text{O} \longrightarrow \text{NaOH} + \text{H}_2$$
$$\mathbf{2}\,\text{Na} + \mathbf{2}\,\text{H}_2\text{O} \longrightarrow \mathbf{2}\,\text{NaOH} + \text{H}_2$$

(los coeficientes **2** en rojo). A la izquierda aparecen dibujadas **dos moléculas de agua** en forma angular (H–O–H), una arriba de la otra. Y la tabla, ahora con todo igual:

| ELEMENTO | # EN REACTIVOS | # EN PRODUCTOS |
|---|---|---|
| Na | 2 | 2 |
| O | 2 | 2 |
| H | 4 | 4 |
| **TOTAL** | **4** | **4** |

**Explicación:** ahí está balanceada. Verificalo vos:

- **Reactivos:** 2 Na · 2 H₂O → 2 Na, 4 H, 2 O
- **Productos:** 2 NaOH (2 Na, 2 O, 2 H) + H₂ (2 H) → 2 Na, 4 H, 2 O ✓

⚠️ **La regla que nunca hay que violar, y que es EL error del tema:**

| ❌ Mal | ✅ Bien |
|---|---|
| Cambiar $\text{H}_2\text{O}$ por $\text{H}_3\text{O}$ para que cierre el H | Poner un **coeficiente**: $2\,\text{H}_2\text{O}$ |
| Tocar los **subíndices** | Tocar sólo los **coeficientes** |

**Por qué:** el subíndice **define la sustancia**. Si cambiás H₂O por H₂O₂ ya no tenés agua, tenés agua oxigenada — otro compuesto, con otras propiedades. Balancear es **ajustar cuántas moléculas de cada cosa participan**, no inventar sustancias nuevas.

💡 **Las dos moléculas de agua dibujadas a la izquierda** están ahí justamente para eso: el "2" significa **dos moléculas de agua completas**, no una molécula modificada.

---

## P2 — pág. 5 · Coeficientes estequiométricos y ley de conservación de la masa

**Qué se ve:** la misma pantalla, pero ahora los coeficientes están **circulados** (los tres "2" y el H₂, cuyo coeficiente 1 no se escribe pero está circulado igual), y de cada círculo sale una línea que converge en un recuadro gris: **COEFICIENTES ESTEQUIOMÉTRICOS**. A la izquierda, un cartel rosa **BALANCEANDO** y una estrella gris con **"Ley de conservación de la masa"**. Abajo, en rojo: *"Mismo número de átomos de cada elemento en ambos lados de la ecuación"*, y en azul el recuento total: **2 Na + 4 H + 2 O**.

**Explicación:** acá se le pone nombre a todo.

### 🔑 Las definiciones

| Término | Definición |
|---|---|
| **Coeficiente estequiométrico** | El número que va **adelante** de cada fórmula e indica cuántas unidades (moléculas o moles) de esa sustancia participan |
| **Balancear** | Ajustar los coeficientes hasta que haya **el mismo número de átomos de cada elemento** de los dos lados |
| **Ley de conservación de la masa** (Lavoisier, 1789) | En una reacción química, **la masa total se conserva**: "nada se crea, nada se destruye, todo se transforma" |

⚠️ **Detalles de escritura que se corrigen en el parcial:**

1. El coeficiente **1 no se escribe** (se escribe H₂, no 1 H₂), pero **cuenta**.
2. Los coeficientes deben ser los **enteros más chicos posibles**. $4\,\text{Na} + 4\,\text{H}_2\text{O} \to 4\,\text{NaOH} + 2\,\text{H}_2$ está balanceada pero **mal presentada**: hay que dividir todo por 2.
3. Sólo se admiten **fraccionarios como paso intermedio** (ver P3 — pág. 1), nunca como respuesta final.

💡 **La conservación es de ÁTOMOS, no de moléculas.** En este ejemplo entran 4 moléculas (2 Na + 2 H₂O) y salen 3 (2 NaOH + 1 H₂). El número de moléculas cambió; el número de átomos de cada elemento, no. Por eso "2 Na + 4 H + 2 O" está escrito abajo: ése es el inventario de átomos, y es lo único que tiene que cerrar.

⚠️ Y como los átomos se conservan, **la masa se conserva**. Verificalo: reactivos $2(23) + 2(18) = 82$ g; productos $2(40) + 2 = 82$ g ✓

---

## P2 — pág. 6 · Reactivos → Productos (con modelos moleculares)

**Qué se ve:** dos ejemplos con modelos de esferas.

**Primero:** una esfera gris (C) **+** dos esferas rojas unidas (O₂) ⟶ una molécula lineal roja-gris-roja (CO₂).

$$\text{C}_{(s)} + \text{O}_{2(g)} \longrightarrow \text{CO}_{2(g)}$$

*carbón + oxígeno ⟶ dióxido de carbono*

| Reactivos | Productos |
|---|---|
| 1 átomo de carbón | 1 átomo de carbón |
| 2 átomos de oxígeno | 2 átomos de oxígeno |

**Segundo:** dos moléculas de H₂ (esferas celestes de a pares) **+** una de O₂ ⟶ dos moléculas angulares de agua.

$$2\,\text{H}_{2(g)} + \text{O}_{2(g)} \longrightarrow 2\,\text{H}_2\text{O}_{(l)}$$

| Reactivos | Productos |
|---|---|
| 4 átomos de hidrógeno | 4 átomos de hidrógeno |
| 2 átomos de oxígeno | 2 átomos de oxígeno |

**Explicación:** el primer ejemplo **ya viene balanceado sin hacer nada** (1 C y 2 O de cada lado); el segundo **necesitó los coeficientes 2**. La diapositiva los pone juntos para mostrar que balancear no siempre hace falta, pero **siempre hay que verificar**.

**Lo importante son los dibujos:** fijate que en los productos **no aparece ninguna esfera nueva y no desaparece ninguna**. Las mismas 4 celestes y las mismas 2 rojas de la izquierda están a la derecha, sólo que **reagrupadas**. Ésa es la imagen mental correcta de una reacción química: **una redistribución de átomos**, no una creación.

⚠️ **Los elementos diatómicos** — hay que saberlos de memoria, porque escribir "O" en vez de "O₂" arruina cualquier balanceo:

$$\boxed{\text{H}_2 \quad \text{N}_2 \quad \text{O}_2 \quad \text{F}_2 \quad \text{Cl}_2 \quad \text{Br}_2 \quad \text{I}_2}$$

(Los cinco últimos son "los halógenos + N + O + H". Regla mnemotécnica habitual: **"Have No Fear Of Ice Cold Beer"** — H, N, F, O, I, Cl, Br.)

---

## P2 — pág. 7 · ¿Cómo balancear una reacción química?

**Qué se ve:** el título y dos viñetas:

> • **Ojímetro** (tabla)
> • **Método algebraico** (cuando las cosas se ponen complicadas)

**Explicación:** son los dos métodos de la materia, y el criterio para elegir es simple:

| Método | Cuándo | Ventaja | Desventaja |
|---|---|---|---|
| **Ojímetro** (tanteo) | reacciones simples, ≤ 4-5 especies | rapidísimo si sale | podés quedarte trabado dando vueltas |
| **Algebraico** | reacciones complicadas, muchos elementos, combustiones raras | **siempre funciona** | más lento, hay que resolver un sistema |

💡 **Recomendación práctica:** empezá siempre por ojímetro. Si en un minuto no sale, pasate al algebraico sin dudarlo — es el método que **no puede fallar**, y en el parcial no conviene pelearse con el tanteo.

---

## P2 — pág. 8 · Formas de balancear — Ojímetro

**Qué se ve:** el título **Formas de balancear** con la viñeta **Ojímetro**, y la reacción:

$$\text{P}_4 + \text{O}_2 \longrightarrow \text{P}_2\text{O}_3$$

Después, dos pasos:

> 1) *¿La reacción está balanceada?* **NO!!!!**
> 2) *Balanceo a ojímetro….*
> *"Si tengo 4 átomos de P en reactivos…. Para tener 4 átomos de P en productos agrego el coeficiente estequiométrico 2"*

$$\text{P}_4 + \mathbf{3}\,\text{O}_2 \longrightarrow \mathbf{2}\,\text{P}_2\text{O}_3$$

*(con el 4 circulado en verde, el 3 en azul y el 2 en rojo)*

> *"Ahora me quedan 2×3 = 6 átomos de O en productos… necesito 6 átomos de O en reactivos….. Agrego el coeficiente estequiométrico 3"*

Y abajo, la pregunta: *"¿Cuáles son las diferencias entre ⭕ y ⭕?"* (un círculo rojo y uno verde, comparando el **coeficiente** con el **subíndice**).

**Explicación:** el ojímetro tiene un orden y conviene seguirlo:

### 🔑 El método del ojímetro, paso a paso

1. **Elegí el elemento que aparezca en MENOS lugares** (idealmente en una sola sustancia de cada lado) y que tenga el subíndice más grande. Acá: el **P**, que sólo está en P₄ y P₂O₃.
2. **Balanceá ese elemento** con coeficientes. 4 P a la izquierda ⇒ necesito 4 a la derecha ⇒ como P₂O₃ trae 2 P, pongo **2 P₂O₃**.
3. **Pasá al siguiente elemento**, arrastrando lo que ya fijaste. Con 2 P₂O₃ tengo $2 \times 3 = 6$ O a la derecha ⇒ como O₂ trae 2 O, pongo **3 O₂**.
4. **Dejá para el final** al elemento que aparece en más compuestos (típicamente el **O** o el **H**).
5. **Verificá todo de nuevo**, elemento por elemento.

**Verificación final:**

| Elemento | Reactivos | Productos |
|---|---|---|
| P | 4 (de P₄) | 2 × 2 = 4 ✓ |
| O | 3 × 2 = 6 | 2 × 3 = 6 ✓ |

⚠️ **La pregunta del final de la diapositiva es la trampa clásica del tema:**

| | **Coeficiente** (el círculo rojo) | **Subíndice** (el círculo verde) |
|---|---|---|
| Dónde va | **adelante** de la fórmula: $\mathbf{2}\,\text{P}_2\text{O}_3$ | **abajo y adentro**: $\text{P}_2\text{O}_3$ |
| Qué indica | **cuántas unidades** de esa sustancia hay | **cuántos átomos** hay **dentro** de una unidad |
| ¿Se puede cambiar al balancear? | ✓ **SÍ, es lo único que se toca** | ❌ **NUNCA — define la sustancia** |
| Si lo cambio… | tengo más o menos cantidad de lo mismo | **tengo otra sustancia distinta** |

---

## P2 — pág. 9 · Formas de balancear — Método algebraico (primer intento)

**Qué se ve:** el título y la reacción sin balancear:

$$\text{FeS} + \text{O}_2 \longrightarrow \text{Fe}_2\text{O}_3 + \text{SO}_2$$

Debajo, la misma con letras (en rojo):

$$a\,\text{FeS} + b\,\text{O}_2 \longrightarrow c\,\text{Fe}_2\text{O}_3 + d\,\text{SO}_2$$

Tres recuadros con las ecuaciones de balance, y debajo de cada uno una flecha con el resultado:

| Recuadro | Ecuación | Resultado |
|---|---|---|
| **Átomos de Fe** | $1 \times a = 2 \times c$ | $a = 2$ |
| **Átomos de S** | $1 \times a = 1 \times d$ | $d = 2$ |
| **Átomos de O** | $2 \times b = 3 \times c + 2 \times d$ | $b = 7/2$ |

A la derecha: *"Supongo **c = 1** y con esa suposición calculo el resto…."*. Abajo: *"No todos son enteros….encuentro cómo hacerlos enteros…. **Multiplico todos por 2**"*, y el resultado final en rojo:

$$\mathbf{4}\,\text{FeS} + \mathbf{7}\,\text{O}_2 \longrightarrow \mathbf{2}\,\text{Fe}_2\text{O}_3 + \mathbf{4}\,\text{SO}_2$$

**Explicación:** ⚠️ **Éste es el método que hay que dominar sí o sí**, porque es el que sirve siempre.

### 🔑 El método algebraico, paso a paso

1. **Poné una letra como coeficiente de cada sustancia** (a, b, c, d…).
2. **Escribí una ecuación por elemento**: (átomos de ese elemento a la izquierda) = (a la derecha). Cada ecuación tiene la forma *coeficiente × subíndice = coeficiente × subíndice*.
3. **Elegí una letra y asignale el valor 1** (o el que te convenga). Es legítimo porque el sistema es **indeterminado**: tiene infinitas soluciones proporcionales entre sí, y a nosotros nos interesa **la relación**, no los valores absolutos.
4. **Resolvé el resto** en función de esa suposición.
5. **Si quedan fracciones, multiplicá TODO** por el denominador común hasta que sean enteros.
6. **Verificá.**

**Las cuentas de esta diapositiva, en detalle:**

- Supongo $c = 1$.
- **Fe:** $a = 2c = 2 \times 1 = \mathbf{2}$
- **S:** $d = a = \mathbf{2}$
- **O:** $2b = 3c + 2d = 3(1) + 2(2) = 7 \Rightarrow b = \mathbf{7/2}$
- Quedó $b$ fraccionario ⇒ **multiplico los cuatro por 2**: $a=4$, $b=7$, $c=2$, $d=4$.

**Verificación final:**

| Elemento | Reactivos | Productos |
|---|---|---|
| Fe | 4 (de 4 FeS) | 2 × 2 = 4 ✓ |
| S | 4 (de 4 FeS) | 4 (de 4 SO₂) ✓ |
| O | 7 × 2 = 14 | 2×3 + 4×2 = 6 + 8 = 14 ✓ |

💡 **Cómo elegir qué letra igualar a 1:** conviene la de **la sustancia más complicada** (la que tiene más subíndices distintos) o la que aparece en más ecuaciones. Acá, poner $c = 1$ en Fe₂O₃ resolvió a y d de una.

---

## P2 — pág. 10 · Método algebraico (segundo intento: suponiendo c = 2)

**Qué se ve:** exactamente la misma diapositiva anterior, pero ahora aparece arriba también la ecuación **ya balanceada** ($4\,\text{FeS} + 7\,\text{O}_2 \to 2\,\text{Fe}_2\text{O}_3 + 4\,\text{SO}_2$), la suposición dice *"Supongo **c = 2**"* y los resultados debajo de los recuadros son directamente $a = \mathbf{4}$, $d = \mathbf{4}$, $b = \mathbf{7}$ (todos en rojo, todos enteros).

**Explicación:** es la misma cuenta pero con una suposición más astuta. Con $c = 2$:

- **Fe:** $a = 2c = 4$
- **S:** $d = a = 4$
- **O:** $2b = 3(2) + 2(4) = 6 + 8 = 14 \Rightarrow b = 7$

**Todos enteros de una, sin tener que multiplicar al final.**

💡 **La moraleja de poner las dos diapositivas juntas:** la suposición inicial **no cambia el resultado**, sólo cuánto trabajo te da. Si elegís bien, te ahorrás el paso de "multiplicar todo". Si elegís mal, igual llegás — sólo tenés que hacer una multiplicación extra.

⚠️ **Y el corolario tranquilizador:** **no hay una manera "incorrecta" de empezar**. El método algebraico no se equivoca; a lo sumo te hace trabajar un poco más. Por eso es el método seguro para el parcial.

**Truco para elegir bien:** mirá el subíndice más grande que aparece en la sustancia que vas a igualar. Si Fe₂O₃ tiene un 2 y un 3, probá con $c = 2$ o $c = 1$; si te da fracción con denominador 2, ya sabés que multiplicando por 2 se arregla.

---

## P2 — pág. 11 · La ecuación química: símbolos de estado e interpretación

**Qué se ve:** el título, un cartel gris **ECUACIÓN BALANCEADA** con:

$$2\,\text{Na} + 2\,\text{H}_2\text{O} \longrightarrow 2\,\text{NaOH} + \text{H}_2$$

Después: *"la ecuación química es usual indicar además **el estado físico** de cada uno de los reactivos y productos que intervienen en la reacción"*, y la tabla:

> **Símbolos de Estado**
> **(s)** Sólido
> **(l)** Líquido
> **(g)** Gaseoso
> **(ac)** Solución acuosa

Y en un recuadro azul, la ecuación completa:

$$\boxed{2\,\text{Na}_{(s)} + 2\,\text{H}_2\text{O}_{(l)} \longrightarrow 2\,\text{NaOH}_{(ac)} + \text{H}_{2(g)}}$$

Abajo: *"¿Cómo se interpreta esta ecuación?"* con dos lecturas:

> ➢ Cuando **2 átomos** de Na reaccionan con **2 moléculas** de H₂O, se producen **2 unidades fórmula** de NaOH y **una molécula** de H₂
> ➢ Cuando **2 moles** de átomos de Na reacciona con **2 moles** de moléculas de H₂O, se producen **2 moles** de unidades fórmula de NaOH y **1 mol** de moléculas de H₂

**Explicación:** dos cosas nuevas y las dos entran.

**1) Los símbolos de estado.** Van entre paréntesis, en subíndice, después de cada fórmula. ⚠️ **En esta materia se piden** — el "paso 1" del método de cálculo estequiométrico (P3 — pág. 4) dice literalmente *"escribir la reacción química (fórmulas **y estados de agregación**)"*.

| Símbolo | Significa | Cómo saberlo |
|---|---|---|
| **(s)** | sólido | metales, sales sólidas, precipitados |
| **(l)** | líquido | el agua pura, el Br₂, el Hg |
| **(g)** | gaseoso | O₂, N₂, H₂, CO₂, NH₃, HCl puro |
| **(ac)** | en solución acuosa | ácidos, bases y sales **disueltos en agua** |

⚠️ **No confundir (l) con (ac).** $\text{H}_2\text{O}_{(l)}$ es agua líquida pura; $\text{NaOH}_{(ac)}$ es hidróxido de sodio **disuelto en agua** (o sea: iones Na⁺ y OH⁻ rodeados de moléculas de agua). El (ac) implica que hay agua aunque no la escribas.

**2) La doble lectura de una ecuación.** ⭐ **Éste es el concepto más importante de toda la clase**, y es el que habilita todos los cálculos.

| Lectura | Escala | "2 Na" significa |
|---|---|---|
| **Microscópica** | partículas individuales | **2 átomos** de Na |
| **Macroscópica** | laboratorio | **2 moles** de átomos de Na = $2 \times 6{,}022\times10^{23}$ átomos = 46 g |

Las dos lecturas son válidas porque **multiplicar todo por el mismo número (N_A) no cambia las proporciones**. Y como en el laboratorio no podés contar átomos pero sí podés **pesar**, la lectura útil es la macroscópica.

⚠️ **Vocabulario preciso** (la diapositiva lo cuida y en el parcial también):

| Tipo de sustancia | Se dice | Ejemplo |
|---|---|---|
| Elemento monoatómico | **átomos** | Na, Fe, He |
| Compuesto covalente | **moléculas** | H₂O, H₂, NH₃ |
| Compuesto iónico | **unidades fórmula** | NaOH, NaCl, CaCO₃ |

(No existe "una molécula de NaCl": un cristal de NaCl es una red, no moléculas sueltas. Por eso se dice **unidad fórmula**.)

---

## P2 — pág. 12 · Ejemplo: la síntesis de amoníaco

**Qué se ve:** un recuadro amarillo con la reacción y los modelos moleculares:

$$\text{N}_{2(g)} + 3\,\text{H}_{2(g)} \longrightarrow 2\,\text{NH}_{3(g)}$$

Dibujado: **una molécula azul de N₂** (dos esferas azules unidas) **+** **tres moléculas blancas de H₂** ⟶ **dos moléculas de NH₃** (una esfera azul con tres blancas alrededor). Y abajo, la tabla de las dos "recetas":

| | N₂ | + | H₂ | ⟶ | NH₃ |
|---|---|---|---|---|---|
| **"Receta microscópica"** | 1 molécula | + | 3 moléculas | ⟶ | 2 moléculas |
| **"Receta macroscópica"** | 1 mol | + | 3 mol | ⟶ | 2 mol |

**Explicación:** es la doble lectura de la diapositiva anterior aplicada a la reacción más importante de la industria química: **la síntesis de amoníaco (proceso Haber-Bosch)**, con la que se fabrican los fertilizantes que alimentan a la mitad del planeta.

**La palabra "receta" está muy bien elegida:** una ecuación balanceada es literalmente **una receta de cocina en proporciones**. Dice "1 de esto por cada 3 de aquello". No dice cuánto tenés que hacer — eso lo elegís vos — pero sí **en qué proporción**.

### 🔑 Las relaciones estequiométricas que se leen de esta ecuación

$$\frac{1\ \text{mol N}_2}{3\ \text{mol H}_2} \qquad \frac{1\ \text{mol N}_2}{2\ \text{mol NH}_3} \qquad \frac{3\ \text{mol H}_2}{2\ \text{mol NH}_3}$$

Cada una se puede usar al derecho o al revés. **Ésos son los factores de conversión de todo cálculo estequiométrico.**

⚠️ **Fijate que el número de moléculas NO se conserva:** entran 4 (1 + 3) y salen 2. **Lo que se conserva son los átomos**: 2 N y 6 H de cada lado.

⚠️ **Y el volumen tampoco se conserva** (para gases, en las mismas P y T): entran 4 volúmenes y salen 2. Por la ley de Avogadro, esta reacción **reduce el volumen a la mitad** — lo cual, dicho sea de paso, es la razón de que el proceso Haber-Bosch se haga a **200-400 atm**: la alta presión desplaza el equilibrio hacia el lado de menos moléculas.

---

## P2 — pág. 13 · Algunos tipos de reacciones

**Qué se ve:** cuatro categorías, cada una con su ejemplo:

> **Reacciones de combustión**
> $\text{CH}_{4(g)} + 2\,\text{O}_{2(g)} \to \text{CO}_{2(g)} + 2\,\text{H}_2\text{O}_{(g)}$
>
> **Reacciones ácido-base** *(más adelante en esta materia)*
> $\text{HCl}_{(ac)} + \text{NaOH}_{(ac)} \to \text{NaCl}_{(ac)} + \text{H}_2\text{O}_{(l)}$
>
> **Reacciones óxido-reducción** *(más adelante en otra materia)*
> $\text{Zn}_{(s)} + \text{Cu}^{2+}_{(ac)} \to \text{Cu}_{(s)} + \text{Zn}^{2+}_{(ac)}$
>
> **Reacciones de precipitación, complejación…..**

**Explicación:** es un mapa de lo que viene. De estas cuatro, **la única que hay que saber resolver ahora es la combustión**, porque es la que aparece en los ejercicios de balanceo de esta clase.

### 🔑 Combustión — la que sí entra ahora

Una **combustión** es la reacción de algo con **O₂**. La regla que hay que memorizar es **qué productos da cada elemento**:

| Si el combustible tiene… | El producto es… |
|---|---|
| **C** | **CO₂** (combustión completa) o CO (incompleta) |
| **H** | **H₂O** |
| **N** | **N₂** (así lo define este curso — ver P3 pág. 1) |
| **S** | **SO₂** |

$$\boxed{\text{C}_x\text{H}_y + \text{O}_2 \longrightarrow x\,\text{CO}_2 + \tfrac{y}{2}\,\text{H}_2\text{O}}$$

📝 Verificá el metano de la diapositiva: $\text{CH}_4 + 2\,\text{O}_2 \to \text{CO}_2 + 2\,\text{H}_2\text{O}$ — C: 1=1 ✓ · H: 4=4 ✓ · O: 4 = 2+2 ✓

⚠️ **Combustión completa vs incompleta:**

| | Condición | Producto del C |
|---|---|---|
| **Completa** | O₂ **en exceso** | **CO₂** |
| **Incompleta** | O₂ **insuficiente** | **CO** (monóxido, tóxico) o **C** (hollín) |

Ésa es la razón química de que un calefactor mal ventilado sea peligroso: sin suficiente O₂, la combustión del gas produce **CO**, que es inodoro y se une a la hemoglobina 200 veces mejor que el O₂.

💡 **Las otras tres, en una línea cada una** (para reconocerlas, no para resolverlas todavía):

| Tipo | Qué pasa | Se ve en |
|---|---|---|
| **Ácido-base** | un ácido + una base dan **sal + agua** (neutralización) | más adelante en esta materia |
| **Redox** | hay **transferencia de electrones** (cambian los números de oxidación) | otra materia |
| **Precipitación** | dos soluciones dan un **sólido insoluble** que cae | Clase 6, sección de solubilidad |

---

# PARTE 3 — `Clase 7 _parte 2_NB.pdf` (13 diapositivas)

## P3 — pág. 1 · Problema 1 — combustión de la metilamina

**Qué se ve:** el título **Problema 1** y el enunciado: *"La combustión de compuestos que contienen C, N, e H da lugar a la formación de N₂, CO₂ y H₂O gaseosos. Escriba la ecuación balanceada para la combustión de: a) Metilamina (CH₅N) gaseosa"*. Y la resolución:

$$2\,\text{CH}_5\text{N} + \tfrac{9}{2}\,\text{O}_2 \longrightarrow \text{N}_2 + 2\,\text{CO}_2 + 5\,\text{H}_2\text{O}$$

*Multiplico por 2:*

$$\boxed{4\,\text{CH}_5\text{N} + 9\,\text{O}_2 \longrightarrow 2\,\text{N}_2 + 4\,\text{CO}_2 + 10\,\text{H}_2\text{O}}$$

(el resultado final va recuadrado en naranja)

**Explicación:** primer ejercicio completo de balanceo, y trae dos cosas nuevas.

**1) El enunciado te dice los productos.** *"da lugar a la formación de N₂, CO₂ y H₂O"*. En una combustión con N, el nitrógeno sale como **N₂** (no como NO ni NO₂). Eso es una **convención del curso** y viene dada en el enunciado — no la inventes vos.

**2) Se usa un coeficiente fraccionario como paso intermedio.** El 9/2 aparece porque el O es el último elemento que se balancea y la cuenta no da entera. Después se multiplica todo por 2 y listo.

**La resolución completa, paso a paso** (hagámosla por ojímetro, que acá sale rápido):

$$\text{CH}_5\text{N} + \text{O}_2 \longrightarrow \text{N}_2 + \text{CO}_2 + \text{H}_2\text{O}$$

| Paso | Qué balanceo | Cómo |
|---|---|---|
| 1 | **N** | El N₂ trae 2 N, así que necesito **2 CH₅N** |
| 2 | **C** | 2 CH₅N traen 2 C ⇒ **2 CO₂** |
| 3 | **H** | 2 CH₅N traen 10 H ⇒ como H₂O trae 2, van **5 H₂O** |
| 4 | **O** (último) | Derecha: $2(2) + 5(1) = 9$ O ⇒ izquierda necesito 9 O ⇒ como O₂ trae 2, va **9/2 O₂** |
| 5 | **Enteros** | Multiplico los cinco coeficientes **por 2** |

**Verificación final** de $4\,\text{CH}_5\text{N} + 9\,\text{O}_2 \to 2\,\text{N}_2 + 4\,\text{CO}_2 + 10\,\text{H}_2\text{O}$:

| Elemento | Reactivos | Productos |
|---|---|---|
| C | 4 | 4 ✓ |
| H | 4 × 5 = 20 | 10 × 2 = 20 ✓ |
| N | 4 | 2 × 2 = 4 ✓ |
| O | 9 × 2 = 18 | 4×2 + 10×1 = 8 + 10 = 18 ✓ |

💡 **La regla de oro del balanceo de combustiones:** balanceá en el orden **C → H → O** (y si hay N o S, empezá por ellos). **El oxígeno SIEMPRE va último**, porque aparece en casi todos los productos y balancearlo primero te obliga a rehacer todo.

⚠️ **Sobre los fraccionarios:** son legítimos **como paso intermedio** y muchas veces son inevitables cuando el O₂ tiene que aportar un número impar de átomos. Pero la respuesta final **se entrega con enteros mínimos**. Si dejás el 9/2 en el parcial, te lo marcan.

---

## P3 — pág. 2 · Cálculos estequiométricos — ¿qué es la estequiometría?

**Qué se ve:** el título **CÁLCULOS ESTEQUIOMÉTRICOS** y la pregunta *"¿Qué es la estequiometría de una reacción?"*. En un recuadro violeta:

> *"SON RELACIONES QUE VINCULAN LAS **CANTIDADES** DE REACTIVOS CONSUMIDOS Y DE PRODUCTOS FORMADOS EN UNA REACCIÓN QUÍMICA"*

Debajo: *"LA PIEZA CLAVE EN CUALQUIER CÁLCULO ESTEQUIOMÉTRICO ES"* ⟶ recuadro violeta: **LA ECUACIÓN QUÍMICA BALANCEADA**. Y: *"Relaciones entre los moles"*.

A la derecha, una figura en forma de **Y** con tres brazos que convergen en una esfera naranja central rotulada **MOLE**: arriba un globo ("Volume of gas (STP)", conectado por "22,4 L / 1,00 mol"), abajo a la izquierda una balanza con una muestra ("Mass", conectada por "molar mass / 1,00 mol") y abajo a la derecha un cristal de partículas ("Representative particles", conectado por "6,02 × 10²³ partículas / 1,00 mol").

Al pie, en itálica: ***"TODOS LOS CAMINOS CONDUCEN AL MOL"***.

**Explicación:** ⭐ **Ésta es la diapositiva conceptual más importante de toda la clase.** Si te quedás con una sola idea, que sea ésta.

**Las dos afirmaciones que hay que entender:**

**1) "La pieza clave es la ecuación química BALANCEADA."** Sin balancear, no hay cálculo posible. Los coeficientes **son** las relaciones. Por eso el paso 2 del método (P3 — pág. 4) es balancear, y no se puede saltear.

**2) "Todos los caminos conducen al mol."** La estequiometría relaciona **moles con moles**, nunca gramos con gramos ni litros con litros. Entonces cualquier problema tiene la misma forma:

```
      DATO                                    RESPUESTA
   (en la unidad                             (en la unidad
   que te dieron)                            que te piden)
        │                                          ▲
        │  convertir                    convertir  │
        ▼                                          │
     MOLES de A ────────────────────────────►  MOLES de B
                  COEFICIENTES de la ecuación
                       (regla de tres)
```

⚠️ **El error conceptual más grave del tema** es intentar hacer la regla de tres **directamente con los gramos**. Los coeficientes son **relaciones de MOLES**, no de masas. Sólo se pueden usar sobre moles.

$$\text{N}_2 + 3\,\text{H}_2 \to 2\,\text{NH}_3$$

| ❌ Mal | ✅ Bien |
|---|---|
| "1 g de N₂ reacciona con 3 g de H₂" | 1 **mol** de N₂ (28 g) reacciona con 3 **mol** de H₂ (6 g) |

**Los tres puentes al mol** (los tres brazos de la Y) — hay que tenerlos memorizados:

$$\boxed{n = \frac{m}{Mr}} \qquad \boxed{n = \frac{V_{gas}}{22{,}4\ \text{L}}\ \text{(sólo en CNPT)}} \qquad \boxed{n = \frac{N_{partículas}}{6{,}022\times10^{23}}}$$

---

## P3 — pág. 3 · Diagrama de estequiometría

**Qué se ve:** el diagrama completo del método, con dos mitades simétricas. A la izquierda, en **verde**, la columna **"Conocida — Sustancia A"**; a la derecha, en **azul**, la columna **"Desconocida — Sustancia B"**. En cada mitad hay un círculo central **Mol** con tres círculos satélite conectados por flechas de doble sentido, y cada flecha rotulada con su factor de conversión:

| Satélite | Factor de conversión |
|---|---|
| **Masa** | 1 mol = masa molar (g) |
| **Volumen** (gases) | 1 mol = 22,4 L a TPN |
| **Partículas** | 1 mol = 6,022 × 10²³ partículas (átomos o moléculas) |

Y en el centro, la flecha que une **Mol (A)** ⟷ **Mol (B)**, rotulada: ***"Usar coeficientes de la reacción química balanceada"***.

**Explicación:** ⭐ **Ésta es la diapositiva que hay que poder redibujar de memoria en el parcial.** Es el mapa completo de cualquier problema de estequiometría.

### 🔑 Cómo se lee el diagrama

```
   SUSTANCIA A (la que te dan)              SUSTANCIA B (la que te piden)

   Masa (g)                                            Masa (g)
      ▲                                                    ▲
      │ ÷ Mr        (÷ o ×)                        × Mr     │
      ▼                                                    ▼
   Volumen ◄──► [ MOL A ] ══════════════════► [ MOL B ] ◄──► Volumen
   (gas)    ÷22,4     ▲     COEFICIENTES              ▲   ×22,4
                      │     (regla de tres)           │
                      ▼                               ▼
                 Partículas                      Partículas
                    ÷ N_A                          × N_A
```

**La estructura de TODO problema de estequiometría es siempre la misma, y son tres movimientos:**

| Movimiento | Qué hacés | Herramienta |
|---|---|---|
| **1. Bajar al mol** (izquierda) | convertir el dato que te dieron a moles de A | Mr, 22,4 L, N_A, PV = nRT, M·V |
| **2. Cruzar** (centro) | pasar de moles de A a moles de B | ⭐ **los COEFICIENTES de la ecuación balanceada** |
| **3. Subir del mol** (derecha) | convertir moles de B a la unidad que te piden | la misma herramienta, al revés |

⚠️ **El paso del centro es el ÚNICO que usa la ecuación química.** Los de los costados son conversiones de unidades que ya sabías desde la Clase 6. Por eso, si te trabás, preguntate: *"¿ya estoy en moles? ¿ya usé los coeficientes?"*.

⚠️ **"22,4 L a TPN"** es lo mismo que CNPT (0 °C, 1 atm) — TPN = temperatura y presión normales. **Si el problema no está en CNPT, ese brazo del diagrama se reemplaza por $n = PV/RT$.**

💡 **Los brazos que la diapositiva no dibuja pero que también existen** (y que vienen de la Clase 6 y de P1):

| Si el dato viene como… | El puente al mol es… |
|---|---|
| volumen de un gas fuera de CNPT | $n = \dfrac{PV}{RT}$ |
| volumen de una solución + molaridad | $n = M \cdot V_{(L)}$ |
| volumen de un líquido + densidad | $m = \delta V$, después $n = m/Mr$ |
| % m/m + masa de solución | $m_{sto} = \%\cdot m_{sc}/100$, después $n = m/Mr$ |

---

## P3 — pág. 4 · La relación estequiométrica del amoníaco

**Qué se ve:** arriba, un recorte del diagrama anterior (los dos círculos **Mol** unidos por la flecha "Usar coeficientes de la reacción química balanceada"). Debajo, en un recuadro:

$$\text{N}_2(g) + 3\,\text{H}_2(g) \longrightarrow 2\,\text{NH}_3(g)$$

Y las equivalencias con el símbolo ≙ ("equivale estequiométricamente a"):

$$1\ \text{mol N}_2 \;\hat{=}\; 3\ \text{mol H}_2 \qquad\qquad 1\ \text{mol N}_2 \;\hat{=}\; 2\ \text{mol NH}_3$$

A la derecha:

> *Cuando 1 mol de N₂ reacciona,*
> *— se consumen **3 moles** de H₂*
> *— se forman **2 moles** de NH₃*
>
> *Cualquier cantidad de N₂ o de H₂ que reaccione de acuerdo a esta reacción, **lo hará respetando estas relaciones estequiométricas***

Abajo a la izquierda, un esquema con tres cubos: **"Moles of A"** (rojo) → una esfera naranja **"Mole ratio"** → **"Moles of B"** (verde), todo bajo el rótulo **"Reaction stoichiometry"**.

**Explicación:** es el paso del centro del diagrama, explicado con detalle.

**El símbolo ≙ es importante y es raro:** no significa "igual" (obvio: 1 mol de N₂ no *es* 3 moles de H₂). Significa **"equivale estequiométricamente"**: cada vez que desaparece 1 mol de N₂, desaparecen 3 de H₂. Es una **relación de consumo**, no una igualdad.

**La frase clave está en la última línea:** *"cualquier cantidad… lo hará respetando estas relaciones"*. Ésa es la razón por la que la regla de tres funciona: **la proporción es fija**, no importa la escala. Si reaccionan 0,5 mol de N₂, se consumen 1,5 de H₂; si reaccionan 7,3, se consumen 21,9.

### 🔑 Cómo se escribe la regla de tres (el formato del docente)

Se plantea **siempre igual**, poniendo arriba lo que dice la ecuación y abajo lo que tenés:

```
Lo que dice la ECUACIÓN:      1 mol N₂  ────────  3 mol H₂
Lo que tengo / quiero:        0,5 mol N₂ ───────      x
```

$$x = \frac{0{,}5 \times 3}{1} = 1{,}5\ \text{mol H}_2$$

💡 **Consejo para no equivocarse nunca:** escribí siempre las **unidades completas con el nombre de la sustancia** ("3 mol de H₂", no "3 mol"). El 90 % de los errores en estequiometría son de **haber puesto el coeficiente de la sustancia equivocada**, y escribir el nombre te lo hace evidente.

---

## P3 — pág. 5 · Problema 2 — enunciado (primera parte, fuera de guía)

**Qué se ve:** el título **Problema 2 (primera parte fuera de guía)** y el enunciado:

> *"El gas tricloruro de nitrógeno (NCl₃) reacciona con agua líquida para dar amoníaco y HClO (g), el componente activo de la lavandina."*
>
> **a-1)** *Si quiero producir 1,9 moles de HClO ¿cuánto debería agregar de NCl₃ (suponga exceso de agua)?*
>
> **a-2)** *Si pongo a reaccionar 8 moles de NCl₃ con exceso de agua ¿Cuántos moles obtendría de ambos productos?*

**Explicación:** el problema que va a atravesar el resto de la clase — se resuelve en pedazos a lo largo de P3 y P4. Vale la pena tener claro desde el principio de qué se trata.

**Cómo se arma la ecuación desde el texto** (esto es el "paso 1" y hay que poder hacerlo solo):

| El enunciado dice… | Se traduce en… |
|---|---|
| "el gas tricloruro de nitrógeno (NCl₃)" | $\text{NCl}_{3(g)}$ — reactivo |
| "reacciona con agua líquida" | $\text{H}_2\text{O}_{(l)}$ — reactivo |
| "para dar amoníaco" | $\text{NH}_{3(g)}$ — producto |
| "y HClO (g)" | $\text{HClO}_{(g)}$ — producto |

$$\text{NCl}_{3(g)} + \text{H}_2\text{O}_{(l)} \longrightarrow \text{NH}_{3(g)} + \text{HClO}_{(g)}$$

⚠️ **Fijate la frase "suponga exceso de agua"**. Es una **muletilla técnica** que aparece muchísimo, y significa: *"hay tanta agua que nunca se va a acabar, así que no la tengas en cuenta como limitante"*. Con esa aclaración, el problema se resuelve **usando sólo el NCl₃**. Cuando la aclaración **no** está, hay que verificar cuál es el reactivo limitante (que es exactamente lo que va a pasar en P4 — pág. 4).

📝 **Dato de color:** el HClO (ácido hipocloroso) es efectivamente el principio activo de la lavandina. La lavandina comercial es NaClO en agua, y en solución da HClO, que es el que oxida y desinfecta.

---

## P3 — pág. 6 · Paso a paso en cálculos estequiométricos (pasos 1 y 2)

**Qué se ve:** el título en rojo **Paso a paso en cálculos estequiométricos** y sólo dos ítems (el resto de la diapositiva está en blanco):

> 1- Escribir la reacción química (fórmulas y estados de agregación)
> 2- Balancear la reacción química.

**Explicación:** el docente **construye el método de a poco** a lo largo de la clase: primero estos dos pasos, después (pág. 8) le agrega el 3 y el 4, y en P4 — pág. 5 le agrega el reactivo limitante. Por eso la diapositiva está medio vacía: es a propósito.

**Lo importante de los dos primeros pasos:**

**Paso 1 — Escribir la reacción.** Traducir el texto a fórmulas. Es donde hace falta la **nomenclatura** (Extra/`Nomenclatura-Explicacion-Completa.md`): si el enunciado dice "carbonato de calcio" tenés que saber escribir CaCO₃.

⚠️ **Los estados de agregación se piden**, no son opcionales en este curso.

**Paso 2 — Balancear.** Con ojímetro o con el método algebraico. ⭐ **Sin esto, todo lo que sigue está mal**, porque los coeficientes son los factores de conversión del paso central.

💡 **Regla práctica que vale la pena adoptar:** **balanceá SIEMPRE, aunque la ecuación te la den escrita en el enunciado.** Muchas veces te la dan sin balancear justamente para ver si lo verificás.

---

## P3 — pág. 7 · Problema 2 — la ecuación balanceada

**Qué se ve:** el mismo enunciado del Problema 2, ahora con la consigna **a)** *"Escriba la ecuación balanceada para esta reacción"* resuelta en dos líneas:

$$\text{NCl}_3\,(g) + \text{H}_2\text{O}\,(l) \longrightarrow \text{NH}_3\,(g) + \text{HClO}\,(g)$$
$$\boxed{\text{NCl}_3\,(g) + 3\,\text{H}_2\text{O}\,(l) \longrightarrow \text{NH}_3\,(g) + 3\,\text{HClO}\,(g)}$$

Y debajo vuelven a aparecer las consignas a-1) y a-2).

**Explicación:** el balanceo, paso a paso (por ojímetro):

| Paso | Elemento | Razonamiento |
|---|---|---|
| 1 | **N** | 1 a cada lado ✓ ya está |
| 2 | **Cl** | 3 en el NCl₃ ⇒ como HClO trae 1 Cl, van **3 HClO** |
| 3 | **O** | 3 O en los 3 HClO ⇒ como H₂O trae 1 O, van **3 H₂O** |
| 4 | **H** (verificación) | Izquierda: 3 H₂O = 6 H. Derecha: NH₃ (3 H) + 3 HClO (3 H) = 6 H ✓ |

**Verificación completa:**

| Elemento | Reactivos | Productos |
|---|---|---|
| N | 1 | 1 ✓ |
| Cl | 3 | 3 ✓ |
| H | 3 × 2 = 6 | 3 + 3 = 6 ✓ |
| O | 3 | 3 ✓ |

### 🔑 Las relaciones estequiométricas de esta reacción (se van a usar todo el resto de la clase)

$$1\ \text{NCl}_3 \;\hat{=}\; 3\ \text{H}_2\text{O} \qquad 1\ \text{NCl}_3 \;\hat{=}\; 1\ \text{NH}_3 \qquad 1\ \text{NCl}_3 \;\hat{=}\; 3\ \text{HClO} \qquad 3\ \text{H}_2\text{O} \;\hat{=}\; 1\ \text{NH}_3$$

💡 Fijate que la relación **NCl₃ : NH₃ es 1 : 1**. Eso va a simplificar varias cuentas más adelante (P3 — pág. 13).

---

## P3 — pág. 8 · Paso a paso (ahora con los pasos 3 y 4)

**Qué se ve:** la misma diapositiva del método, ahora con cuatro pasos:

> 1- Escribir la reacción química (fórmulas y estados de agregación)
> 2- Balancear la reacción química.
> 3- **Convertir a moles** la información tanto de reactivos como de productos
> 4- **Utilizar la información de las relaciones estequiométricas** brindada en la ecuación química (coeficientes) para calcular lo que nos piden.

**Explicación:** ahí está el método completo (por ahora — en P4 le falta todavía el reactivo limitante). Los pasos 3 y 4 son exactamente los dos movimientos del diagrama de la pág. 3.

### 🔑 El método de 4 pasos (versión "con exceso" o "cantidades estequiométricas")

| Paso | Qué hacés | Herramienta |
|---|---|---|
| **1** | Escribir la reacción con fórmulas y estados | nomenclatura |
| **2** | **Balancear** | ojímetro / algebraico |
| **3** | **Todo a moles** | $n = m/Mr$ · $n = PV/RT$ · $n = M\cdot V$ · $n = V/22{,}4$ |
| **4** | Regla de tres con los **coeficientes** | la ecuación balanceada |
| *(+5)* | *Volver a la unidad que te piden* | la inversa del paso 3 |

⚠️ **El paso 3 dice "tanto de reactivos como de productos"** — o sea, si el dato que te dan es un **producto** (como en a-1: "quiero producir 1,9 moles de HClO"), también hay que pasarlo a moles. **El método funciona igual en las dos direcciones**: de reactivo a producto o de producto a reactivo.

💡 **El paso que la diapositiva no numera pero siempre está:** después del paso 4 tenés moles de lo que te piden, y casi siempre te lo piden **en gramos, en litros o en molaridad**. Ese "paso 5" de volver a subir del mol es donde más se olvida la gente.

---

## P3 — pág. 9 · Problema 2 a-1) — resolución

**Qué se ve:** en un recuadro, la consigna **a-1)** *"Si quiero producir 1,9 moles de HClO ¿cuánto debería agregar de NCl₃ (suponga exceso de agua)?"*. Debajo, la ecuación balanceada y el razonamiento en voz alta:

> *"¿Qué dice la ecuación química?????"* → **COEFICIENTES!!!!**
> *"La ecuación dice que para producir 3 moles de HClO **necesitaría** 1 mol de NCl₃"*
>
> *"¿Qué es lo que pide el problema?????"*
> *"Lo que realmente quiero es averiguar cuánto **necesito** de reactivo si quiero producir 1,9 moles de HClO"*

Y la regla de tres:

```
3 moles de HClO   ─────────►  1 mol de NCl₃
1,9 moles de HClO ─────────►       X
```

$$X = \mathbf{0{,}633\ moles\ de\ NCl_3}$$

**Explicación:** la cuenta explícita:

$$X = \frac{1{,}9\ \text{mol HClO} \times 1\ \text{mol NCl}_3}{3\ \text{mol HClO}} = \frac{1{,}9}{3} = 0{,}6333 \approx \mathbf{0{,}633\ mol\ de\ NCl}_3$$

**Por qué es el ejemplo más simple posible:** el dato ya viene **en moles**, así que el paso 3 (convertir a moles) no hay que hacerlo. Sólo hay que cruzar con los coeficientes.

⚠️ **El razonamiento en voz alta del docente vale la pena imitarlo en el parcial**, porque es literalmente el orden en que hay que pensar:

1. **¿Qué dice la ecuación?** → los coeficientes: 1 NCl₃ ≙ 3 HClO
2. **¿Qué me piden?** → moles de NCl₃, sabiendo moles de HClO
3. **Regla de tres.**

💡 **Verificación de sentido común (hacela siempre):** para hacer 3 moles de HClO necesito 1 de NCl₃, o sea que necesito **menos NCl₃ que HClO**. Como quiero 1,9 de HClO, la respuesta tiene que ser **menor a 1,9**. Y 0,633 < 1,9 ✓ Si te hubiera dado 5,7 (multiplicando en vez de dividir), el número te avisaba solo.

**Y a-2), que la diapositiva no resuelve** (queda como ejercicio; conviene hacerla):

> *Si pongo a reaccionar 8 moles de NCl₃ con exceso de agua, ¿cuántos moles obtendría de ambos productos?*

Con los coeficientes 1 NCl₃ ≙ 1 NH₃ y 1 NCl₃ ≙ 3 HClO:

$$n_{NH_3} = 8 \times \frac{1}{1} = \mathbf{8\ mol\ de\ NH_3} \qquad\qquad n_{HClO} = 8 \times \frac{3}{1} = \mathbf{24\ mol\ de\ HClO}$$

---

## P3 — pág. 10 · Cálculos estequiométricos (los dos esquemas de conversión)

**Qué se ve:** dos esquemas de cubos apilados, uno arriba a la izquierda y otro abajo a la derecha, ambos con la misma estructura.

**Esquema 1 (sustancias puras):**

```
   Moles of A ──[ Mole ratio ]──► Moles of B          ("Reaction stoichiometry")
       ▲                              │
   [Molar mass of A]           [Molar mass of B]
       │                              ▼
    Mass of A                     Mass of B
```

**Esquema 2 (soluciones):**

```
   Moles of A ──[ Mole ratio ]──► Moles of B
       ▲                              │
  [Molarity of A]              [Molarity of B]
       │                              ▼
 Volume of A solution         Volume of B solution
```

**Explicación:** son **el mismo diagrama de la pág. 3 pero especializado**, uno para cuando trabajás con masas y otro para cuando trabajás con soluciones.

**Lo que hay que leer:** la estructura **no cambia nunca**. Siempre es *bajar al mol → cruzar con la relación molar → subir del mol*. Lo único que cambia es **qué escalera usás para bajar y subir**:

| Si el dato es… | La escalera es… | Fórmula |
|---|---|---|
| una **masa** | la masa molar | $n = m/Mr$ |
| un **volumen de solución** | la molaridad | $n = M\cdot V_{(L)}$ |
| un **volumen de gas** | 22,4 L/mol o PV = nRT | $n = V/22{,}4$ o $n = PV/RT$ |
| un **número de partículas** | Avogadro | $n = N/N_A$ |

⚠️ **El "Mole ratio" del centro es SIEMPRE lo mismo:** los coeficientes de la ecuación balanceada. Da igual que trabajes con sólidos, gases o soluciones — **ese paso no cambia nunca**.

💡 **Por eso la estequiometría es "fácil" una vez que la agarrás:** es un solo método, con un solo paso propio (el del centro), y todo el resto son conversiones de unidades que ya sabías desde la Clase 6.

---

## P3 — pág. 11 · Sustancias puras y soluciones — el mapa de conversiones

**Qué se ve:** dos bloques con diagramas de flujo.

**Bloque 1 — Sustancias puras:**

```
  ┌──────────────┐   × g/cm³      ┌──────────┐    × mol/g      ┌───────┐
  │ Volumen, cm³ │───────────────►│ Masa, g  │────────────────►│ Moles │
  └──────┬───────┘  usar densidad └──────────┘  usar Masa molar└───────┘
         │
         │  PV = nRT            "Si es un gas .. ley de gases ideales"
         ▼
     ┌───────┐
     │ Moles │
     └───────┘
```

**Bloque 2 — Soluciones:**

```
  ┌───────────────┐   M, %m/V, %m/m   ┌───────┐   PV = nRT   ┌────────────────────┐
  │ Concentración │──────────────────►│ Moles │◄─────────────│ Presiones parciales│
  └───────────────┘                   └───────┘              └────────────────────┘
```

**Explicación:** ⭐ **Ésta es LA diapositiva que une toda la materia**, y por eso está puesta justo en el medio de la clase. Es el inventario completo de **todos los caminos que llevan al mol**, y todos ya los viste antes:

| Camino | De dónde viene | Fórmula |
|---|---|---|
| Volumen de líquido → masa | **Clase 6** (densidad) | $m = \delta \cdot V$ |
| Masa → moles | **Clase 1** (masa molar) | $n = m/Mr$ |
| Volumen de gas → moles | **P1 de esta clase** | $n = PV/RT$ |
| Concentración → moles | **Clase 6** (M, %m/V, %m/m) | $n = M\cdot V$ · $n = \frac{\%m/V \cdot V}{100\,Mr}$ |
| Presión parcial → moles | **P1 de esta clase** (Dalton) | $n_i = P_iV/RT$ |

⚠️ **Fijate el detalle de la flecha vertical del primer bloque:** si te dan un **volumen**, hay **dos caminos distintos** según el estado:

| Si es un… | Camino |
|---|---|
| **líquido o sólido** | volumen ⟶ (× densidad) ⟶ masa ⟶ (÷ Mr) ⟶ **moles** |
| **gas** | volumen ⟶ (PV = nRT) ⟶ **moles**, directo |

**⚠️ NUNCA le apliques la densidad a un gas para pasar a moles.** Para un gas tenés la ecuación de estado, que es directa y exacta. (Y además la densidad de un gas depende de P y T, así que ni siquiera es un dato fijo — ver P1 pág. 22.)

💡 **Éste es el diagrama que hay que tener en la cabeza cuando leés un enunciado.** Leé el dato, identificá en qué "caja" está, y buscá la flecha que lo lleva a "Moles". A partir de ahí, la estequiometría es siempre igual.

---

## P3 — pág. 12 · Problema 2 b) — desde un volumen de agua

**Qué se ve:** el enunciado del Problema 2 (segunda parte), la ecuación balanceada y la consigna:

> **b)** *¿Cuántos moles de amoníaco se pueden producir a partir de 275 mL de agua y cantidades estequiométricas de NCl₃? (δ H₂O = 1 g/cm³)*

Y la resolución:

$$275\ \text{mL agua} = 275\ \text{g agua}$$

$$\text{Moles}_{(H_2O)} = \frac{m_{(H_2O)}}{Mr_{(H_2O)}} = \frac{275\ \text{g}}{18\ \text{g/mol}} = 15{,}27\ \text{moles H}_2\text{O}$$

```
3 moles de agua      ──producirán──►  1 mol de NH₃
15,27 moles de agua  ─────────────►       x
```

$$\mathbf{X = 5{,}09\ moles\ de\ NH_3}$$

**Explicación:** primer problema donde hay que **usar el diagrama completo**: el dato viene como volumen de líquido, así que hay que bajar dos escalones (volumen → masa → moles) antes de cruzar.

**Paso por paso:**

**1) Volumen → masa** (usando la densidad, que el enunciado te da):

$$m = \delta \cdot V = 1{,}00\ \tfrac{\text{g}}{\text{cm}^3} \times 275\ \text{cm}^3 = 275\ \text{g}$$

⚠️ **1 mL = 1 cm³.** Y con δ = 1 g/cm³ los números coinciden, pero **la conversión igual hay que escribirla**: si la densidad fuera 0,8, no coincidirían.

**2) Masa → moles:**

$$n = \frac{m}{Mr} = \frac{275\ \text{g}}{18\ \text{g/mol}} = 15{,}28\ \text{mol de H}_2\text{O}$$

(la diapositiva redondea a 15,27 — con Mr = 18,0 da 15,28; con Mr = 18,02 da 15,26. Es lo mismo.)

**3) Cruzar con los coeficientes** (3 H₂O ≙ 1 NH₃):

$$n_{NH_3} = \frac{15{,}27 \times 1}{3} = \mathbf{5{,}09\ mol\ de\ NH_3}$$

⚠️ **La expresión "cantidades estequiométricas de NCl₃"** significa: *hay exactamente el NCl₃ necesario, ni más ni menos*. O sea, **el agua es la que manda** y no hay que preocuparse por el limitante (los dos se acaban a la vez).

💡 **Verificación de sentido común:** hacen falta 3 moles de agua por cada mol de NH₃, así que la respuesta tiene que ser **la tercera parte** de los moles de agua. $15{,}27/3 = 5{,}09$ ✓

📝 **Si te pidieran la masa de amoníaco** (el "paso 5" que acá no piden): $m = n\cdot Mr = 5{,}09 \times 17 = \mathbf{86{,}5\ g\ de\ NH_3}$

---

## P3 — pág. 13 · Problema 2 c) — de masa a masa (el problema completo)

**Qué se ve:** la ecuación balanceada arriba y la consigna:

> **c)** *¿Qué masa de tricloruro de nitrógeno se necesita para producir 14,8 g de amoníaco?*

Resuelto en tres pasos numerados:

> **1- ¿Cuántos moles de amoníaco habría que producir?**
> $\text{Moles amoníaco} = \dfrac{\text{masa amoníaco}}{Mr\ \text{amoníaco}} = \dfrac{14{,}8\ \text{g}}{17\ \text{g/mol}} = 0{,}87$ moles de amoníaco
>
> **2- ¿Cuántos moles necesito de NCl₃ para producir 0,87 moles de amoníaco?**
> ```
> 1 mol de amoníaco       ──────  1 mol de tricloruro de nitrógeno
> 0,87 moles de amoníaco  ──────       X
> ```
> $X = 0{,}87$ moles de NCl₃
>
> **3- ¿Qué masa corresponde a los 0,87 moles que necesito de NCl₃?**
> $\text{Masa NCl}_3 = \text{moles NCl}_3 \times Mr\ \text{NCl}_3 = 0{,}87 \times 120{,}5\ \text{g/mol} = \mathbf{104{,}83\ g\ de\ NCl_3}$

**Explicación:** ⭐ **Éste es el problema tipo completo — de masa a masa — y es el modelo de lo que se toma en el parcial.** Fijate que los tres pasos numerados son exactamente los tres movimientos del diagrama de la pág. 3.

```
  14,8 g NH₃  ──(÷ 17)──►  0,87 mol NH₃  ──(coef 1:1)──►  0,87 mol NCl₃  ──(× 120,5)──►  104,83 g NCl₃
   [DATO]         paso 1        [MOL]          paso 2          [MOL]           paso 3        [RESPUESTA]
```

**Las cuentas, con los Mr calculados:**

| Sustancia | Mr | Cómo se calcula |
|---|---|---|
| **NH₃** | **17 g/mol** | $14 + 3(1) = 17$ |
| **NCl₃** | **120,5 g/mol** | $14 + 3(35{,}5) = 14 + 106{,}5 = 120{,}5$ |

$$n_{NH_3} = \frac{14{,}8}{17} = 0{,}8706 \approx 0{,}87\ \text{mol}$$
$$n_{NCl_3} = 0{,}87 \times \frac{1}{1} = 0{,}87\ \text{mol}$$
$$m_{NCl_3} = 0{,}87 \times 120{,}5 = \mathbf{104{,}8\ g}$$

⚠️ **El paso 2 fue trivial porque la relación es 1:1**, pero **no dejes de escribirlo**. Si la relación hubiera sido 1:3, saltear el paso te habría dado un error del 300 %. Escribí siempre la regla de tres, aunque el coeficiente sea 1.

⚠️ **El error clásico de este problema** sería hacer $14{,}8 \times 120{,}5/17$ mentalmente sin darse cuenta de que ahí van dos conversiones y un cruce. Da lo mismo por casualidad (porque la relación molar es 1:1), pero **con cualquier otro coeficiente daría mal**.

💡 **Guardá estos números**, porque el mismo problema vuelve dos veces más en P4:
- **104,83 g de NCl₃** → es la masa que se pone a reaccionar en P4 — pág. 11
- **14,8 g de NH₃** → es el **rendimiento teórico**, contra el que se va a comparar el real (13 g)

---

# PARTE 4 — `Clase 7 _parte 3_NB.pdf` (12 diapositivas)

## P4 — pág. 1 · Abandonando el mundo ideal — reactivo limitante y en exceso

**Qué se ve:** el título en dos líneas: **ABANDONANDO EL MUNDO IDEAL** / *Reactivo limitante – Reactivo en exceso*. Dos definiciones recuadradas:

> **Reactivo limitante** → *"Es el reactivo que gobierna la máxima cantidad de producto que puede obtenerse y **se consume completamente**."*
>
> **Reactivo en exceso** → *"Los demás reactivos están en exceso. Finalizada la reacción **quedan junto al producto**."*

Abajo, el famoso dibujo de los panchos: una columna de **5 salchichas**, otra de **4 panes**, una flecha, y como resultado **4 panchos armados + 1 salchicha suelta**. Rótulos: *panes → Reactivo limitante* · *panchos → Rendimiento teórico* · *salchicha suelta → Reactivo en exceso*.

**Explicación:** ⭐ **La analogía del pancho es la mejor manera de entender el tema y conviene usarla mentalmente siempre.**

$$1\ \text{salchicha} + 1\ \text{pan} \longrightarrow 1\ \text{pancho}$$

Tenés 5 salchichas y 4 panes. **¿Cuántos panchos hacés?** Cuatro. **¿Qué te sobra?** Una salchicha.

| En la analogía | En química |
|---|---|
| Los **panes** (se acaban primero) | **Reactivo limitante** |
| Las **salchichas** (sobra una) | **Reactivo en exceso** |
| Los **4 panchos** | **Rendimiento teórico** |
| La **salchicha suelta** al final | El exceso que **queda sin reaccionar** |

⚠️ **La cosa fundamental que hay que entender:** la cantidad de producto la fija **el que se acaba primero**, no el que hay más. Y "el que se acaba primero" **no es necesariamente el que está en menor cantidad** — depende también de **los coeficientes** (si la receta pidiera 2 panes por pancho, con 4 panes harías sólo 2).

**Por qué el título dice "abandonando el mundo ideal":** hasta acá todos los problemas decían "con exceso de agua" o "cantidades estequiométricas". En el laboratorio de verdad eso casi nunca pasa: ponés lo que tenés, y sobra algo. Las tres diapositivas que siguen a este bloque (limitante, rendimiento, pureza) son **las tres correcciones al mundo ideal**:

| Corrección | Pregunta que responde |
|---|---|
| **Reactivo limitante** | ¿Cuál de los reactivos manda? |
| **Rendimiento %** | ¿Obtuve todo lo que la teoría decía? |
| **Pureza** | ¿Lo que pesé era todo reactivo? |

💡 **Por qué en la industria se pone algo en exceso a propósito:** porque el reactivo caro conviene consumirlo **del todo**, y para eso se pone barato en exceso. En Haber-Bosch, por ejemplo, se trabaja con exceso de N₂ (que sale del aire, gratis) para aprovechar mejor el H₂ (que es caro de producir).

---

## P4 — pág. 2 · Reactivo limitante — Fe + S

**Qué se ve:** el título y la reacción $\text{Fe} + \text{S} \longrightarrow \text{FeS}$. Debajo, **dos filas de recuadros** (antes ⟶ después):

**Fila de arriba — "Cantidades estequiométricas":** a la izquierda, 5 esferas amarillas (S) y 5 marrones (Fe) sueltas; a la derecha, **5 pares amarillo-marrón unidos** y nada suelto.

**Fila de abajo — "Reactivo limitante":** a la izquierda, 5 esferas amarillas (S) y sólo 3 marrones (Fe); a la derecha, **3 pares unidos + 2 esferas amarillas sueltas**.

Referencias a la derecha: **S = 🟡 exceso** · **Fe = 🟤 limitante**.

**Explicación:** es la versión química del dibujo del pancho, y muestra **los dos escenarios posibles**:

| Escenario | Qué pasa | Al final queda |
|---|---|---|
| **Cantidades estequiométricas** (fila de arriba) | los dos se acaban **exactamente a la vez** | sólo producto, nada sin reaccionar |
| **Un reactivo limitante** (fila de abajo) | uno se acaba antes | producto **+ el sobrante del que estaba en exceso** |

⚠️ **La reacción es 1:1** ($\text{Fe} + \text{S} \to \text{FeS}$), así que acá sí vale el atajo de "el que hay menos es el limitante". **Con cualquier otro coeficiente ese atajo NO sirve** y hay que hacer la cuenta.

📝 **La reacción es real y es un clásico de laboratorio:** limadura de hierro + azufre en polvo, calentados, dan sulfuro de hierro(II). Se usa para ilustrar la diferencia entre **mezcla** (antes de calentar: podés separar el hierro con un imán) y **compuesto** (después: el FeS ya no es magnético y no se separa más).

💡 **Fijate el detalle del dibujo de abajo:** las 2 esferas amarillas que sobran **siguen ahí al final**, mezcladas con el producto. Eso es lo que dice la definición: *"finalizada la reacción quedan junto al producto"*. Y es la razón de que en la industria haya que **purificar** lo que sale del reactor.

---

## P4 — pág. 3 · ¿Cómo identificar al reactivo limitante?

**Qué se ve:** el título y tres pasos:

> 1) **Convertir a moles** las masas de todos los reactivos.
> 2) **Elegir un reactivo y calcular la cantidad que se necesita del otro** reactivo según la relación estequiométrica de la reacción.
> 3) Si la cantidad calculada es **menor** que la que se tiene realmente, el segundo reactivo está **en exceso** y por ende, **el primero es el limitante**.

**Explicación:** ⭐ **Éste es el método que hay que saber, y es el método "tengo vs necesito".**

### 🔑 El método "TENGO vs NECESITO"

```
1. Pasá TODO a moles.
2. Elegí UNO de los reactivos (cualquiera) y preguntate:
   "para que reaccione TODO éste, ¿cuánto NECESITO del otro?"
3. Compará:
     ¿NECESITO ≤ TENGO?  →  me alcanza  →  el que elegí es el LIMITANTE
     ¿NECESITO > TENGO?  →  no me alcanza →  el OTRO es el limitante
```

⚠️ **La lógica del paso 3, dicha con palabras** (que es donde la gente se marea): si para consumir todo el reactivo A necesito **menos** B del que tengo, entonces **me sobra B** ⇒ **B está en exceso** ⇒ **A es el limitante**, porque A se va a acabar primero.

💡 **Da igual con cuál empieces.** Si elegís "mal", la conclusión sale igual, sólo que invertida. Es el mismo caso que con la suposición del método algebraico: no hay forma de arrancar mal.

**Un método alternativo que a mucha gente le sale más fácil** (y da lo mismo): **dividí los moles de cada reactivo por su coeficiente**. El que dé **el número más chico es el limitante**.

$$\text{Limitante} = \min\left(\frac{n_A}{a},\ \frac{n_B}{b}\right)$$

📝 Con $2\,\text{Na} + \text{Cl}_2 \to 2\,\text{NaCl}$ y 2,17 mol de Na con 0,70 mol de Cl₂:

$$\frac{n_{Na}}{2} = \frac{2{,}17}{2} = 1{,}085 \qquad \frac{n_{Cl_2}}{1} = \frac{0{,}70}{1} = 0{,}70 \;\longleftarrow\ \textbf{más chico} \Rightarrow \textbf{Cl}_2\textbf{ es el limitante}$$

⚠️ **El error más común de todo el tema:** decir que el limitante es *"el que está en menor cantidad"*. **NO.** En el ejemplo de arriba hay 2,17 mol de Na y sólo 0,70 de Cl₂ y sí, el Cl₂ es el limitante — pero eso pasó de casualidad. Cambiá los coeficientes a $\text{Na} + 4\,\text{Cl}_2$ y el limitante pasa a ser el Na, aunque haya más moles. **Hay que hacer la cuenta.**

---

## P4 — pág. 4 · Aplicación al Problema 2 — ¿cuál es el limitante?

**Qué se ve:** la ecuación balanceada arriba y la consigna:

> *Si pongo a reaccionar los 0,87 moles de NCl₃ con 275 ml de agua, ¿cuál sería el reactivo limitante?*
> *¿Cuánto de amoníaco produciría?* **14,8 g de amoníaco** (en rojo)

Y el desarrollo:

> *275 ml de agua eran 15,27 moles de agua…*
>
> ```
> Para que reaccionen  1 mol de NCl₃    necesitaría   3 moles de agua
> Pero en realidad tengo 0,87 mol de NCl₃              X
> ```
> **X = 2,61 moles de agua**
>
> *"Para que reaccionen los 0,87 moles de NCl₃ necesitaría entonces 2,61 moles de agua…. Pero tengo 15,27 moles de agua…. **Tengo más agua de la que necesitaría** para que reaccione todo el NCl₃…"*
>
> **Reactivo limitante = NCl₃**

**Explicación:** el método "tengo vs necesito" aplicado, reutilizando los números de P3 (0,87 mol de NCl₃ de la pág. 13 y 15,27 mol de agua de la pág. 12).

**La cuenta:**

$$\text{NECESITO de agua} = 0{,}87\ \text{mol NCl}_3 \times \frac{3\ \text{mol H}_2\text{O}}{1\ \text{mol NCl}_3} = \mathbf{2{,}61\ mol\ de\ H_2O}$$

**La comparación:**

| | Moles |
|---|---|
| **NECESITO** de agua | 2,61 |
| **TENGO** de agua | 15,27 |

$$2{,}61 < 15{,}27 \quad\Longrightarrow\quad \text{me SOBRA agua} \quad\Longrightarrow\quad \boxed{\text{el agua está en EXCESO, el NCl}_3\text{ es el LIMITANTE}}$$

**Verificación con el método alternativo:**

$$\frac{n_{NCl_3}}{1} = \frac{0{,}87}{1} = 0{,}87 \;\longleftarrow\ \textbf{menor} \qquad \frac{n_{H_2O}}{3} = \frac{15{,}27}{3} = 5{,}09$$

⇒ NCl₃ limitante ✓ (mismo resultado)

**Y la respuesta a "¿cuánto de amoníaco produciría?":** como la relación NCl₃ : NH₃ es 1:1, y el limitante es el NCl₃ con 0,87 mol:

$$n_{NH_3} = 0{,}87\ \text{mol} \quad\Longrightarrow\quad m = 0{,}87 \times 17 = \mathbf{14{,}8\ g\ de\ NH_3}$$

⚠️ **Fijate el punto pedagógico de la diapositiva:** en P3 — pág. 12 se había calculado que con las 15,27 mol de agua se podían producir **5,09 mol de NH₃**. Ahora, con el limitante real, salen **0,87 mol**. La diferencia es enorme, y es exactamente el error que se comete si **calculás con el reactivo equivocado**.

$$\text{Si calculás con el que está en exceso} \;\Rightarrow\; \text{te da 6 veces de más}$$

⭐ **Ésa es la razón de ser de todo el tema:** ⚠️ **TODAS las reglas de tres se hacen a partir del REACTIVO LIMITANTE.** El que está en exceso no se usa nunca para calcular productos.

---

## P4 — pág. 5 · Paso a paso (versión final, con el reactivo limitante)

**Qué se ve:** la diapositiva del método, ahora completa con cinco pasos:

> 1- Escribir la reacción química (fórmulas y estados de agregación)
> 2- Balancear la reacción química.
> 3- Convertir a moles la información tanto de reactivos como de productos
> **4- Decidir cuál es el reactivo limitante.**
> 5- Utilizar la información de las relaciones estequiométricas brindada en la ecuación química (coeficientes) para calcular lo que nos piden **teniendo en cuenta al reactivo limitante. (todas las reglas de tres se harán a partir del RL)**

**Explicación:** ⭐ **Ésta es la versión definitiva del método y es la que hay que aplicar en el parcial.** Comparada con la de P3 — pág. 8, se le insertó **el paso 4** y se le agregó la aclaración al paso 5.

### 🔑 EL MÉTODO COMPLETO — 5 pasos

| Paso | Qué hacés | Herramienta | ⚠️ |
|---|---|---|---|
| **1** | Escribir la reacción con fórmulas y **estados de agregación** | nomenclatura | los (s)/(l)/(g)/(ac) se piden |
| **2** | **Balancear** | ojímetro / algebraico | sin esto todo lo demás está mal |
| **3** | **Todo a moles** | $m/Mr$ · $PV/RT$ · $M\cdot V$ · $N/N_A$ | los tres brazos del diagrama |
| **4** | **Decidir el limitante** | "tengo vs necesito" o $n_i/\text{coef}_i$ mínimo | **sólo si te dan cantidades de MÁS DE UN reactivo** |
| **5** | Regla de tres **desde el limitante** | los coeficientes | ⭐ **todas las reglas de tres desde el RL** |
| *(6)* | Volver a la unidad que te piden | la inversa del paso 3 | el paso que más se olvida |

⚠️ **Cuándo hay que hacer el paso 4 y cuándo no:**

| El enunciado dice… | ¿Hay que buscar el limitante? |
|---|---|
| "con **exceso** de agua" | ❌ **no** — te lo están diciendo: el otro es el limitante |
| "en **cantidades estequiométricas**" | ❌ **no** — se acaban a la vez |
| te da **cantidad de un solo reactivo** | ❌ **no** — ése es el limitante por defecto |
| te da **cantidades de dos o más reactivos** | ✓ **SÍ, obligatorio** |

💡 **La regla mental de un renglón:** *si el enunciado te da dos números de reactivos, es porque quiere que busques el limitante.* Nunca te dan un dato de más porque sí.

---

## P4 — pág. 6 · Reactivo limitante y en exceso — el esquema "Tengo / Necesito"

**Qué se ve:** la reacción escrita en grande con los datos debajo de cada especie:

$$2\,\text{Na} + \text{Cl}_2 \longrightarrow 2\,\text{NaCl}$$
$$\ \ 50\ \text{g} \qquad\ 50\ \text{g} \qquad\quad x\ \text{g}$$

Flechas hacia abajo rotuladas **/ 23 g/mol** y **/ 71 g/mol**, que llevan a dos recuadros celestes:

| | Na | Cl₂ |
|---|---|---|
| **"Tengo"** | **2,17 mol** | **0,70 mol** |
| **"Necesito"** | **1,40 mol** (recuadro rosa) | |

Una flecha va del recuadro de Cl₂ (0,70 mol) al recuadro rosa de "Necesito" del Na. Rótulos: **exceso** debajo del Na, **Reactivo limitante** debajo del Cl₂. Y a la derecha, la regla de tres:

```
1 mol Cl₂    ────  2 moles de Na
0,7 mol Cl₂  ────       X
```

**Explicación:** ⭐ **Éste es el formato de resolución que conviene copiar tal cual en el parcial.** El esquema "Tengo / Necesito" escrito debajo de la ecuación es visual, ordenado y no deja lugar a confusión.

**Las cuentas:**

**Paso 3 — a moles:**

$$n_{Na} = \frac{50\ \text{g}}{23\ \text{g/mol}} = 2{,}17\ \text{mol} \qquad\qquad n_{Cl_2} = \frac{50\ \text{g}}{71\ \text{g/mol}} = 0{,}704\ \text{mol}$$

(Mr del Cl₂ = 2 × 35,5 = **71 g/mol** — ⚠️ es diatómico, no 35,5)

**Paso 4 — el limitante.** Elijo el Cl₂ y me pregunto cuánto Na necesito:

$$\text{NECESITO de Na} = 0{,}704 \times \frac{2\ \text{mol Na}}{1\ \text{mol Cl}_2} = \mathbf{1{,}40\ mol\ de\ Na}$$

$$\underbrace{1{,}40}_{\text{necesito}} \;<\; \underbrace{2{,}17}_{\text{tengo}} \quad\Longrightarrow\quad \text{sobra Na} \quad\Longrightarrow\quad \boxed{\text{Na en EXCESO · Cl}_2\text{ LIMITANTE}}$$

⚠️ **Éste es el caso que desmiente el atajo del "hay menos gramos":** ¡hay **50 g de cada uno**! Los gramos son idénticos. Lo que decide es la combinación de **masa molar** y **coeficiente**.

💡 **Por qué el Cl₂ resulta limitante aunque haya la misma masa:** el Cl₂ pesa **3 veces más por mol** (71 vs 23), así que en 50 g hay **muchos menos moles**. Y encima la receta pide **2 de Na por cada 1 de Cl₂**. Los dos factores juegan en la misma dirección.

---

## P4 — pág. 7 · Cuánto producto se forma

**Qué se ve:** la misma diapositiva, ahora completada del lado del producto. Aparece un recuadro gris con **82,4 g NaCl** arriba de la "x g", una flecha hacia arriba rotulada **× 58,5 g/mol** que sale de otro recuadro gris con **1,40 mol**, y una flecha que va del **0,70 mol de Cl₂** (el limitante) hacia ese 1,40 mol. La regla de tres de la derecha ahora dice:

```
1 mol Cl₂    ────  2 moles de NaCl
0,7 mol Cl₂  ────       X
```

**Explicación:** el paso 5 del método, hecho **desde el limitante**.

$$n_{NaCl} = 0{,}704\ \text{mol Cl}_2 \times \frac{2\ \text{mol NaCl}}{1\ \text{mol Cl}_2} = \mathbf{1{,}41\ mol\ de\ NaCl}$$

$$m_{NaCl} = 1{,}41\ \text{mol} \times 58{,}5\ \tfrac{\text{g}}{\text{mol}} = \mathbf{82{,}4\ g\ de\ NaCl}$$

(Mr NaCl = 23 + 35,5 = 58,5 g/mol)

⚠️ **La flecha del esquema es lo más importante de la diapositiva:** sale del **0,70 mol de Cl₂**, no del 2,17 de Na. **Todas las reglas de tres arrancan en el limitante.**

💡 **Verificación por conservación de la masa** (una comprobación que siempre conviene hacer y que da puntos):

| | Masa |
|---|---|
| Cl₂ consumido (todo) | 50,0 g |
| Na consumido | 1,41 mol × 23 = 32,4 g |
| **Total consumido** | **82,4 g** |
| **NaCl formado** | **82,4 g** ✓ |
| Na sobrante | 50,0 − 32,4 = 17,6 g |
| **Masa total al final** | 82,4 + 17,6 = **100,0 g** = los 50 + 50 iniciales ✓ |

**La masa se conserva perfectamente.** Si al hacer un problema de limitante los números no cierran así, algo está mal.

---

## P4 — pág. 8 · Cómo calcular lo que sobra del reactivo en exceso

**Qué se ve:** el título *"¿Cómo calcular el reactivo en exceso… mejor dicho lo que no reacciona?"* y la reacción con los rótulos **exceso** (sobre el Na) y **limitante** (sobre el Cl₂), y debajo de cada uno la cantidad final:

$$\underset{?\ \text{g}}{2\,\text{Na}} + \underset{\mathbf{0\ g}}{\text{Cl}_2} \longrightarrow \underset{1{,}4\ \text{moles} = 82{,}4\ \text{g NaCl}}{2\,\text{NaCl}}$$

Y el razonamiento:

> *"Se consumió todo el Cl₂ …"*
>
> *Para producir 1,4 moles de NaCl → Se consumió **1,4 moles de Na = 32,4 g de Na***
>
> *"El resto de Na quedará en exceso"*
>
> $$50{,}0\ \text{g} \;-\; 32{,}4\ \text{g} \;=\; \mathbf{17{,}6\ g\ Na}$$
> *(total)      (usado)      ("exceso")*

**Explicación:** ésta es la segunda pregunta clásica de los problemas de limitante: **"¿cuánto queda sin reaccionar?"**.

### 🔑 El método para calcular el sobrante

```
1. El LIMITANTE queda en 0 (se consumió TODO, por definición).
2. Calculá cuánto del EXCESO se consumió → regla de tres desde el LIMITANTE.
3. SOBRANTE = lo que tenía − lo que se consumió.
```

$$\boxed{m_{sobrante} = m_{inicial} - m_{consumida}}$$

**Las cuentas de la diapositiva:**

$$n_{Na\ consumido} = 0{,}704\ \text{mol Cl}_2 \times \frac{2\ \text{mol Na}}{1\ \text{mol Cl}_2} = 1{,}41\ \text{mol}$$
$$m_{Na\ consumido} = 1{,}41 \times 23 = 32{,}4\ \text{g}$$
$$m_{Na\ sobrante} = 50{,}0 - 32{,}4 = \mathbf{17{,}6\ g\ de\ Na}$$

⚠️ **Los dos errores típicos:**

| ❌ Error | ✅ Correcto |
|---|---|
| Restar **moles menos gramos** | Restá **en la misma unidad**: gramos con gramos o moles con moles |
| Restar los moles del limitante a los del exceso ($2{,}17 - 0{,}70$) | Hay que pasar por la **relación estequiométrica**: $2{,}17 - 1{,}41 = 0{,}76$ mol |

💡 **La otra manera de decir lo mismo, en moles:**

$$n_{Na\ sobrante} = 2{,}17 - 1{,}41 = 0{,}76\ \text{mol} \quad\Rightarrow\quad m = 0{,}76 \times 23 = \mathbf{17{,}5\ g} \ ✓$$

(la diferencia con 17,6 es sólo redondeo)

💡 **La aclaración del título es buena y conviene tenerla presente:** *"el reactivo en exceso… mejor dicho lo que no reacciona"*. **"Exceso" tiene dos sentidos** y se confunden:

| "Exceso" como… | Significa |
|---|---|
| **el reactivo** en exceso | la sustancia que sobra (el Na) |
| **la cantidad** en exceso | los gramos que quedan sin reaccionar (17,6 g) |

Si el enunciado pregunta *"¿cuál está en exceso?"* la respuesta es **"el Na"**; si pregunta *"¿cuánto queda en exceso?"* la respuesta es **"17,6 g"**.

---

## P4 — pág. 9 · Abandonando el mundo ideal — rendimiento porcentual

**Qué se ve:** el título **ABANDONANDO EL MUNDO IDEAL** / *Rendimiento porcentual de una reacción*, y el texto:

> *"No siempre puede obtenerse la cantidad máxima de producto a partir de una cantidad determinada de reactivo."*
>
> *en la práctica* → **R ⟶ P** (con una flecha punteada que se desvía hacia **P'**)
> • **Reacciones competitivas**
> • **Reacciones incompletas (equilibrio químico)** → **R ⇄ P** (doble flecha)

Y en un recuadro violeta:

$$\boxed{\text{Rendimiento Porcentual} = \frac{\text{Cantidad real obtenida (masa/moles)}}{\text{Cantidad teórica (masa/moles)}} \times 100\ \%}$$

**Explicación:** la segunda corrección al mundo ideal. Hasta acá, todos los cálculos suponían que **el limitante reacciona al 100 %**. En la realidad casi nunca pasa, y la diapositiva da **las dos razones**:

| Razón | Qué pasa | Esquema |
|---|---|---|
| **Reacciones competitivas** | parte del reactivo se va por **otro camino** y da un producto distinto (P') | R ⟶ P, con una rama a P' |
| **Reacciones incompletas** | la reacción **no llega hasta el final**: se establece un **equilibrio** en el que reactivos y productos coexisten | R ⇄ P (doble flecha) |

**Lo que la diapositiva no dice pero también cuenta** (y a veces se pregunta): **pérdidas de manipulación**. Filtrar, trasvasar, secar y purificar siempre pierde algo de producto. En el laboratorio real ésa suele ser la razón principal de un rendimiento del 85 % en vez del 100 %.

⚠️ **La doble flecha ⇄ es notación nueva y significa "reacción reversible":** los productos vuelven a dar reactivos, y el sistema se estaciona en un punto intermedio. Es el tema de **equilibrio químico**, que viene más adelante en la materia.

$$\boxed{\eta\ \% = \frac{\text{real}}{\text{teórico}} \times 100}$$

⚠️ **Se puede calcular con masas o con moles, pero las DOS cantidades tienen que estar en la misma unidad.** No mezcles gramos de uno con moles del otro.

⚠️ **El rendimiento NUNCA puede dar más de 100 %.** Si te da 105 %, hay un error: o calculaste mal el teórico, o el producto que pesaste estaba **húmedo o impuro**.

---

## P4 — pág. 10 · Rendimiento porcentual — de dónde sale cada número

**Qué se ve:** la misma fórmula recuadrada, pero ahora con dos flechas azules que apuntan al numerador y al denominador:

> ↑ (al numerador, "Cantidad real obtenida") — **"Medida en el laboratorio"**
> ↓ (al denominador, "Cantidad teórica") — **"Calculada en el papel… lo que estuvimos haciendo hasta ahora"**

**Explicación:** ⭐ **Esta diapositiva existe sólo para aclarar de dónde sale cada número, y es exactamente donde se traba la gente.**

| Término | Cómo se obtiene | Quién lo da |
|---|---|---|
| **Cantidad teórica** (denominador) | **la calculás vos** con los 5 pasos del método, desde el limitante | tu resolución |
| **Cantidad real** (numerador) | **te la dan en el enunciado** — es un dato experimental | el problema |

⚠️ **Nunca vas a poder "calcular" la cantidad real.** Es un dato de medición. Si un problema te pide el rendimiento, **fijate que el enunciado te tiene que estar dando dos cantidades del producto** — o una del producto y una del reactivo.

### 🔑 Los tres tipos de ejercicio de rendimiento

Como la fórmula tiene tres variables, hay tres versiones del problema:

| Te dan | Te piden | Cómo |
|---|---|---|
| real + los reactivos | **el rendimiento** | calculás el teórico y dividís |
| el rendimiento + los reactivos | **la cantidad real** | $\text{real} = \text{teórico} \times \dfrac{\eta}{100}$ |
| el rendimiento + la cantidad real deseada | **cuánto reactivo poner** | $\text{teórico} = \dfrac{\text{real}}{\eta/100}$, y de ahí para atrás |

⚠️ **El tercer caso es el más traicionero** y es muy de parcial: *"¿cuánto reactivo hay que cargar para obtener 100 g de producto si el rendimiento es del 80 %?"*. Hay que **dividir por 0,80** (o sea, **poner de más**), no multiplicar. Si multiplicás obtenés 80 g en vez de 100.

$$\text{teórico} = \frac{100}{0{,}80} = 125\ \text{g} \quad\text{(hay que apuntar a 125 g teóricos para sacar 100 reales)}$$

---

## P4 — pág. 11 · Rendimiento aplicado al Problema 2

**Qué se ve:** el título *"¿Se acuerdan de este problema?"*, la ecuación balanceada, y el enunciado:

> *Si puse a reaccionar **104,87 g** de tricloruro de nitrógeno con exceso de agua, y obtengo luego de purificar los productos **13 g de amoníaco**. ¿Cuál es el rendimiento de la reacción?*
>
> *Para los que no recuerdan, los 104,87 g de NCl₃ los habíamos calculado teóricamente para obtener **14,8 g de amoníaco (cantidad teórica)**, pero en realidad obtuvimos menos de lo que esperábamos, **13 g (cantidad real)**, entonces…*

$$\text{Rendimiento (\%)} = \frac{\text{masa real}}{\text{masa teórica}} \times 100 = \frac{13\ \text{g}}{14{,}8\ \text{g}} \times 100 = \mathbf{87{,}8\ \%}$$

**Explicación:** cierra el Problema 2 que venía desde P3 — pág. 5, y es el ejemplo del **primer tipo** de ejercicio de rendimiento.

**De dónde sale cada número:**

| Número | Origen |
|---|---|
| **104,87 g de NCl₃** | calculado en **P3 — pág. 13** |
| **14,8 g de NH₃ (teórico)** | era el punto de partida de P3 — pág. 13, y se reconfirmó en P4 — pág. 4 |
| **13 g de NH₃ (real)** | **dato del enunciado** — lo pesaron en el laboratorio |

$$\eta = \frac{13}{14{,}8} \times 100 = 87{,}8\ \%$$

⚠️ **La frase "luego de purificar los productos" es la que justifica el rendimiento menor a 100 %.** Purificar siempre pierde producto.

💡 **Un rendimiento del 87,8 % es muy bueno para una reacción de laboratorio.** En síntesis orgánica multi-paso, un 60-70 % por etapa se considera aceptable — y ahí está el problema de las síntesis largas: **los rendimientos se multiplican**. Cinco pasos al 80 % dan $0{,}8^5 = 0{,}33$, o sea **33 % global**.

📝 **La variante del problema que conviene practicar** (segundo tipo): *"si el rendimiento es del 87,8 %, ¿cuánto NH₃ obtendría partiendo de 200 g de NCl₃?"*

$$n_{NCl_3} = \frac{200}{120{,}5} = 1{,}66\ \text{mol} \;\xrightarrow{1:1}\; 1{,}66\ \text{mol NH}_3 \;\Rightarrow\; m_{teórica} = 1{,}66 \times 17 = 28{,}2\ \text{g}$$
$$m_{real} = 28{,}2 \times 0{,}878 = \mathbf{24{,}8\ g\ de\ NH_3}$$

---

## P4 — pág. 12 · Abandonando el mundo ideal — pureza de reactivos

**Qué se ve:** el título **ABANDONANDO EL MUNDO IDEAL** / *Pureza de reactivos*, y el texto:

> *"En la práctica, los reactivos pueden no ser 100 % puros. Poseen algún porcentaje de impurezas. Esto debe tenerse en cuenta al hacer cálculos estequiométricos, **descontando la masa de impurezas**, las cuales **no darán el producto** de la reacción."*

En un recuadro violeta:

$$\boxed{\text{Pureza \% Reactivo} = \frac{\text{masa de reactivo}}{\text{masa reactivo} + \text{masa impureza}} \times 100\ \%}$$

Y abajo: *"90 % de pureza significa que en 100 g de la mezcla impura habrá 90 g del reactivo"* · *"**Similar a % m/m**"*.

**Explicación:** la tercera y última corrección al mundo ideal. Cuando comprás un reactivo comercial, la etiqueta dice por ejemplo *"CaCO₃ 92 %"*: de cada 100 g del frasco, sólo 92 g son CaCO₃; los otros 8 g son arena, humedad u otras sales.

⚠️ **La clave está en la frase "las cuales no darán el producto":** las impurezas **no reaccionan**. Son masa muerta. Si las metés en el cálculo estequiométrico, te va a dar producto de más.

### 🔑 Cómo se usa la pureza

$$\boxed{m_{reactivo\ puro} = m_{muestra} \times \frac{\text{pureza \%}}{100}}$$

**El paso de la pureza va SIEMPRE al principio**, antes de convertir a moles:

```
masa de la MUESTRA impura
        │  × (pureza / 100)      ⬅️ el paso nuevo
        ▼
masa de REACTIVO puro
        │  ÷ Mr
        ▼
      MOLES  ──── (y de acá, el método de siempre)
```

**El denominador de la fórmula es la clave:** *"masa reactivo + masa impureza"* es **la masa total de la muestra**, o sea lo que pesás en la balanza. Por eso el docente aclara **"similar a % m/m"**: es exactamente la misma estructura que la Clase 6, con el reactivo haciendo de soluto y la muestra de "solución".

$$\%m/m = \frac{m_{sto}}{m_{sc}}\cdot 100 \qquad\longleftrightarrow\qquad \text{pureza \%} = \frac{m_{puro}}{m_{muestra}}\cdot 100$$

📝 **Ejemplo:** se hacen reaccionar **50 g de caliza al 80 % de CaCO₃**. ¿Cuántos moles de CaCO₃ reaccionan?

$$m_{CaCO_3} = 50 \times \frac{80}{100} = 40\ \text{g} \qquad n = \frac{40}{100} = \mathbf{0{,}40\ mol}$$

⚠️ Si hubieras usado los 50 g sin descontar, te habría dado 0,50 mol: **un 25 % de más**.

⚠️ **El problema inverso también se toma:** *"¿cuánta caliza al 80 % hay que pesar para tener 40 g de CaCO₃?"* → hay que **dividir**: $40 / 0{,}80 = \mathbf{50\ g}$. Como con el rendimiento, la dirección de la cuenta cambia.

### 🔑 Las tres correcciones al mundo ideal, juntas y en orden

⭐ **En un problema completo de parcial pueden aparecer las tres a la vez, y hay un orden:**

```
  masa de MUESTRA impura
         │  × pureza/100        ①  PUREZA (al principio)
         ▼
  masa de reactivo PURO ──► moles ──► ② LIMITANTE (si hay 2 reactivos)
                                             │
                                             │ coeficientes
                                             ▼
                                   moles de producto TEÓRICO
                                             │  × η/100    ③  RENDIMIENTO (al final)
                                             ▼
                                     producto REAL
```

| Corrección | Dónde se aplica | Efecto |
|---|---|---|
| ① **Pureza** | sobre el **reactivo**, al principio | reduce el reactivo disponible |
| ② **Limitante** | al elegir con cuál calcular | define quién manda |
| ③ **Rendimiento** | sobre el **producto**, al final | reduce lo que realmente obtenés |

⚠️ **Las tres van en direcciones distintas y no se pueden intercambiar de lugar.** La pureza corrige la **entrada**, el rendimiento corrige la **salida**.

📡 **Conexión con Telecomunicaciones:** la **pureza de reactivos** es *la* magnitud crítica de la industria de semiconductores y de fibra óptica. El silicio de grado electrónico se especifica en **9N (99,9999999 %)** — nueve nueves — porque una impureza de una parte por mil millones ya modifica la conductividad del material. Y en la **fibra óptica**, la atenuación pasó de 1000 dB/km en los años 60 a **0,2 dB/km** hoy casi exclusivamente por eliminar impurezas: los iones de hierro y cobre absorbían luz, y el **OH⁻** residual generaba el famoso "pico de agua" en 1383 nm que inutilizaba toda una banda de trabajo. La fibra moderna *low water peak* existe porque se aprendió a bajar el OH⁻ a menos de 1 ppb. En términos de esta diapositiva: **un 99,9999 % de pureza no alcanzaba**.
---
---

# Resumen de la Clase 8 en una página

## 🌬️ BLOQUE A — GASES

### Presión

$$P = \frac{F}{A} \qquad\qquad \boxed{1\ \text{atm} = 760\ \text{mmHg} = 760\ \text{Torr} = 101.325\ \text{Pa} = 1013\ \text{hPa} = 1{,}013\ \text{bar}}$$

$$\boxed{T(K) = T(°C) + 273{,}15}$$

**Definición conceptual:** la presión de un gas es el efecto promedio de los **choques de las partículas contra las paredes**. Más frecuencia o más energía de choque ⇒ más presión.

| Condición | P | T |
|---|---|---|
| **CNPT** (= TPN, normales) | 1 atm | **273 K** (0 °C) |
| **Ambientales** | 1 atm | 298 K (25 °C) |

$$V_m^{CNPT} = \mathbf{22{,}4\ L/mol} \qquad V_m^{25°C} = 24{,}4\ \text{L/mol}$$

### Las cuatro leyes

| Ley | Fija | Fórmula | Relación |
|---|---|---|---|
| **Boyle-Mariotte** | n, T | $P_1V_1 = P_2V_2$ | inversa |
| **Charles** | n, P | $\dfrac{V_1}{T_1} = \dfrac{V_2}{T_2}$ | directa |
| **Gay-Lussac** | n, V | $\dfrac{P_1}{T_1} = \dfrac{P_2}{T_2}$ | directa |
| **Avogadro** | P, T | $\dfrac{V_1}{n_1} = \dfrac{V_2}{n_2}$ | directa |
| **Combinada** | n | $\boxed{\dfrac{P_1V_1}{T_1} = \dfrac{P_2V_2}{T_2}}$ | — |

💡 **Memorizá sólo la combinada y tachá la variable que no cambia.**

### La ecuación de estado

$$\boxed{PV = nRT} \qquad\qquad R = 0{,}082\ \frac{\text{atm·L}}{\text{K·mol}} = 8{,}314\ \frac{\text{J}}{\text{K·mol}}$$

⚠️ **Con R = 0,082 ⇒ P en atm, V en litros, T en KELVIN, n en moles.**

**Derivadas (salen de reemplazar $n = m/Mr$):**

$$\boxed{Mr = \frac{mRT}{PV}} \qquad\qquad \boxed{\rho = \frac{P\,Mr}{RT}}$$

⚠️ **La densidad de un gas NO es constante:** depende de P y T. La de un líquido sí.

### Los 4 postulados del gas ideal

1. Las partículas **ocupan todo el volumen** del recipiente.
2. Se mueven en forma **aleatoria**.
3. ⭐ **NO hay interacciones** entre ellas (ni London, ni dipolo-dipolo, ni puente de H).
4. El gas **se puede comprimir** (el volumen propio de las partículas es despreciable).

| El modelo funciona bien si… | Falla si… |
|---|---|
| P baja (≈1 atm), T alta, gas liviano y no polar (He, H₂, N₂) | P muy alta, T baja (cerca de condensar), gas polar (H₂O, NH₃, HF) |

### Mezclas de gases — Ley de Dalton

$$\boxed{P_{total} = \sum P_i} \qquad \boxed{P_i = \chi_i \cdot P_{total}} \qquad \boxed{\chi_i = \frac{n_i}{n_{total}}} \qquad \sum\chi_i = 1$$

> **Presión parcial:** la presión que ejercería ese gas **si estuviera SOLO** en el mismo recipiente y a la misma temperatura.
> **Ley de Dalton:** la presión total de una mezcla de gases **que no reaccionan entre sí** es la suma de las presiones parciales.

💡 Para gases: **% en volumen = % en moles = fracción molar**. (Aire: $\chi_{N_2} = 0{,}78$, $\chi_{O_2} = 0{,}21$, $\chi_{Ar} = 0{,}009$.)

---

## ⚗️ BLOQUE B — ESTEQUIOMETRÍA

### La ecuación química

| Término | Qué es | ¿Se toca al balancear? |
|---|---|---|
| **Coeficiente** | número **adelante** de la fórmula: **2** NaOH | ✓ **SÍ** — es lo único que se toca |
| **Subíndice** | número **abajo**, dentro: H**₂**O | ❌ **NUNCA** — define la sustancia |

**Símbolos de estado:** **(s)** sólido · **(l)** líquido · **(g)** gaseoso · **(ac)** solución acuosa

**Doble lectura:** "2 Na" = 2 **átomos** (micro) = 2 **moles** (macro).
**Vocabulario:** átomos (elementos) · moléculas (covalentes) · **unidades fórmula** (iónicos).

**Diatómicos (de memoria):** $\text{H}_2\ \text{N}_2\ \text{O}_2\ \text{F}_2\ \text{Cl}_2\ \text{Br}_2\ \text{I}_2$

### Balanceo — los dos métodos

**① Ojímetro:** empezá por el elemento que aparece en **menos lugares**; dejá el **O y el H para el final**; verificá.

**② Algebraico (el que nunca falla):**
1. Poné letras (a, b, c, d) como coeficientes.
2. Una **ecuación por elemento**: átomos izquierda = átomos derecha.
3. **Suponé una letra = 1** (o 2) y despejá el resto.
4. Si hay fracciones, **multiplicá todo** por el denominador.
5. Verificá.

**Combustión:** C ⟶ **CO₂** · H ⟶ **H₂O** · N ⟶ **N₂** · S ⟶ **SO₂**. Balanceá **C → H → O**, el O siempre último. Los fraccionarios valen **como paso intermedio**, no como respuesta.

### ⭐ El diagrama — TODOS LOS CAMINOS CONDUCEN AL MOL

```
    DATO de A                                        RESPUESTA de B
        │                                                  ▲
        │  bajar al mol                      subir del mol │
        ▼                                                  │
    MOLES de A ════════════════════════════════════►  MOLES de B
                    COEFICIENTES de la ecuación
                      balanceada (regla de tres)
```

**Los puentes al mol:**

$$n = \frac{m}{Mr} \qquad n = \frac{V_{gas}}{22{,}4}\ \text{(CNPT)} \qquad n = \frac{PV}{RT} \qquad n = M\cdot V_{(L)} \qquad n = \frac{N}{N_A}$$

⚠️ **Los coeficientes relacionan MOLES, nunca gramos.**
⚠️ Volumen de **líquido** ⟶ usá la **densidad**. Volumen de **gas** ⟶ usá **PV = nRT** (nunca densidad).

### ⭐ EL MÉTODO DE 5 PASOS

| # | Paso | Herramienta |
|---|---|---|
| **1** | Escribir la reacción (fórmulas **+ estados de agregación**) | nomenclatura |
| **2** | **Balancear** | ojímetro / algebraico |
| **3** | **Todo a moles** | $m/Mr$ · $PV/RT$ · $M\cdot V$ · $N/N_A$ |
| **4** | **Decidir el reactivo limitante** | "tengo vs necesito" |
| **5** | Regla de tres **desde el limitante** | los coeficientes |
| *(6)* | Volver a la unidad pedida | la inversa del paso 3 |

**¿Hay que buscar el limitante?**

| El enunciado dice… | ¿Paso 4? |
|---|---|
| "con **exceso** de…" / "cantidades **estequiométricas**" / da **un solo** reactivo | ❌ no |
| da cantidades de **dos o más reactivos** | ✓ **sí, obligatorio** |

### Reactivo limitante

> **Limitante:** el que **se consume completamente** y **gobierna la máxima cantidad de producto**.
> **En exceso:** los demás. Al final **quedan junto al producto**.

**Método "TENGO vs NECESITO":**
1. Todo a moles.
2. Elegí un reactivo: *"para consumirlo todo, ¿cuánto NECESITO del otro?"*
3. **NECESITO < TENGO** ⇒ me sobra el otro ⇒ **el que elegí es el limitante**.

**Atajo equivalente:**

$$\boxed{\text{Limitante} = \text{el de } \min\left(\frac{n_i}{\text{coef}_i}\right)}$$

⚠️ **NO es "el que está en menor cantidad".** Hay que hacer la cuenta: dependen la masa molar **y** el coeficiente.

**Cuánto sobra del que está en exceso:**

$$\boxed{m_{sobrante} = m_{inicial} - m_{consumida}} \qquad\text{(la consumida se calcula DESDE el limitante)}$$

⚠️ El limitante queda en **0**. Y la masa total se conserva: verificalo siempre.

### Las tres correcciones al mundo ideal

$$\boxed{\eta\ \% = \frac{\text{cantidad REAL (medida en el lab)}}{\text{cantidad TEÓRICA (calculada en el papel)}} \times 100}$$

$$\boxed{\text{pureza \%} = \frac{m_{reactivo}}{m_{reactivo} + m_{impureza}} \times 100} \qquad\Longrightarrow\qquad \boxed{m_{puro} = m_{muestra}\times\frac{\text{pureza}}{100}}$$

**El orden en que se aplican:**

```
  MUESTRA impura ──①PUREZA──► reactivo puro ──► moles ──②LIMITANTE──►
  ──► moles de producto TEÓRICO ──③RENDIMIENTO──► producto REAL
```

| Corrección | Corrige | Cuándo | Si te piden ir al revés |
|---|---|---|---|
| **① Pureza** | la **entrada** | al principio | **dividí** por pureza/100 |
| **② Limitante** | quién manda | al elegir | — |
| **③ Rendimiento** | la **salida** | al final | **dividí** por η/100 |

⚠️ El rendimiento **nunca supera el 100 %**. Si te da más, el producto estaba húmedo o el teórico está mal calculado.
⚠️ La cantidad **real** es siempre un **dato del enunciado**; la **teórica** la calculás vos.

---

## 📌 Fórmulas de la Clase 8 — todas juntas

$$P = \frac{F}{A} \qquad 1\ \text{atm} = 760\ \text{mmHg} = 760\ \text{Torr} = 101.325\ \text{Pa} \qquad T(K) = T(°C) + 273{,}15$$

$$P_1V_1 = P_2V_2 \qquad \frac{V_1}{T_1} = \frac{V_2}{T_2} \qquad \frac{P_1}{T_1} = \frac{P_2}{T_2} \qquad \frac{V_1}{n_1} = \frac{V_2}{n_2} \qquad \frac{P_1V_1}{T_1} = \frac{P_2V_2}{T_2}$$

$$\boxed{PV = nRT} \qquad R = 0{,}082\ \frac{\text{atm·L}}{\text{K·mol}} \qquad V_m^{CNPT} = 22{,}4\ \text{L/mol}$$

$$Mr = \frac{mRT}{PV} \qquad \rho = \frac{P\,Mr}{RT} \qquad n_{gas} = \frac{PV}{RT}$$

$$P_{total} = \sum P_i \qquad P_i = \chi_i P_{total} \qquad \chi_i = \frac{n_i}{n_{total}} \qquad \sum\chi_i = 1$$

$$n = \frac{m}{Mr} \qquad n = \frac{V_{CNPT}}{22{,}4} \qquad n = M\cdot V_{(L)} \qquad n = \frac{N}{N_A}$$

$$\frac{n_A}{\text{coef}_A} = \frac{n_B}{\text{coef}_B} \quad\text{(relación estequiométrica)} \qquad \text{Limitante} = \min\left(\frac{n_i}{\text{coef}_i}\right)$$

$$m_{sobrante} = m_{inicial} - m_{consumida} \qquad \eta\% = \frac{\text{real}}{\text{teórico}}\times100 \qquad m_{puro} = m_{muestra}\cdot\frac{\text{pureza}}{100}$$

---

## ⚠️ Los errores típicos de esta clase

| ❌ Error | ✅ Correcto |
|---|---|
| Meter la temperatura en **°C** en una ley de gases | **SIEMPRE en KELVIN** |
| Usar **22,4 L/mol a 25 °C** | 22,4 L vale **sólo en CNPT** (0 °C). A 25 °C son **24,4 L**. Si no dice CNPT, usá $PV = nRT$ |
| Cambiar un **subíndice** para balancear | Se tocan **sólo los coeficientes** — el subíndice define la sustancia |
| Escribir **O** en vez de **O₂** (o Cl en vez de Cl₂) | Los **diatómicos**: H₂ N₂ O₂ F₂ Cl₂ Br₂ I₂ |
| Hacer la regla de tres **con los gramos** | Los coeficientes son relaciones de **MOLES**. Bajá al mol primero |
| Decir que el limitante es **"el que está en menor cantidad"** | Hay que dividir por el **coeficiente**: $\min(n_i/\text{coef}_i)$ |
| Calcular el producto a partir del reactivo **en exceso** | ⭐ **Todas** las reglas de tres se hacen desde el **LIMITANTE** |
| Calcular el sobrante como $n_{exceso} - n_{limitante}$ | Hay que pasar por la relación estequiométrica: $n_{exceso} - n_{consumido}$ |
| Dar un rendimiento **mayor a 100 %** | Imposible: revisá el teórico, o el producto estaba húmedo/impuro |
| **Multiplicar** por el rendimiento cuando te piden cuánto reactivo cargar | Ahí se **DIVIDE**: $\text{teórico} = \text{real}/(\eta/100)$ |
| Meter la masa de la **muestra impura** en el cálculo | Descontá las impurezas **primero**: $m_{puro} = m_{muestra}\cdot\text{pureza}/100$ |
| Usar la **densidad** para pasar un gas a moles | Para gases: $n = PV/RT$. La densidad de un gas depende de P y T |
| Dejar un coeficiente **fraccionario** (9/2) en la respuesta | Vale como paso intermedio; la respuesta va con **enteros mínimos** |
| Olvidar los **estados de agregación** | El paso 1 del método los pide: (s), (l), (g), (ac) |
| Aplicar la **ley combinada** cuando cambia la cantidad de gas | La combinada exige **n constante**. Si entra o sale gas, usá $PV = nRT$ de los dos lados |

---

## 🔗 Cómo se conecta con lo anterior

| Viene de… | Se usa acá para… |
|---|---|
| **Clase 1** — masa molar, N_A | bajar del gramo al mol (paso 3) |
| **Clase 4** — $E_c$ vs $E_p$, London | entender el postulado 3 del gas ideal y por qué los gases reales se desvían |
| **Clase 6** — densidad, M, %m/m, %m/V | los caminos "concentración ⟶ moles" y "volumen ⟶ masa" |
| **Nomenclatura** (`Extra/`) | escribir las fórmulas a partir del enunciado (paso 1) |

**Y hacia adelante:** las reacciones **ácido-base** (que vienen en esta materia) son estequiometría pura aplicada a soluciones; el **equilibrio químico** es la explicación de por qué el rendimiento no llega a 100 %.
