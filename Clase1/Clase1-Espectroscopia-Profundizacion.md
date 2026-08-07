# Clase 1 — Profundización: Espectroscopía, saltos electrónicos y por qué cada átomo tiene su espectro

**Materia:** Química General — ECyT / UNSAM — 2do Cuatrimestre 2026
**Tema:** ampliación del punto de la Clase 1 sobre **espectros de emisión** (absorción/emisión electrónica).

> Este archivo NO es un apunte de diapositivas. Es una **profundización** sobre un solo tema de la Clase 1: qué pasa realmente cuando un átomo emite luz, por qué cada elemento emite colores distintos, y cómo se mide eso. Está armado a partir de una charla de preguntas y respuestas, reordenado por temas. Lo que en el machete entra en dos renglones, acá está desarrollado hasta el fondo.

---

## 0. El punto de partida (lo que ya sabías)

Un **espectro de emisión** aparece así:

1. Un átomo recibe energía y queda **excitado**: uno o más electrones saltan a niveles de energía más altos.
2. Casi al instante, esos electrones **caen** a niveles más bajos.
3. Al caer, el átomo **libera** la energía sobrante en forma de **luz** (un fotón).

Y la observación clave de la Clase 1: **cada elemento emite su propio conjunto de colores** (su propio espectro), y eso se usa como "huella digital" para identificarlo. La pregunta de fondo de todo este documento es **por qué** esa huella es distinta para cada átomo, y **cómo** se mide.

---

## 1. ¿El fotón "se crea de la nada"?

Sí, el fotón **se crea en el instante de la caída** — pero no viola nada, porque **no sale de la nada: sale de energía**.

- Cuando el electrón está en un nivel alto ($n=3$), el sistema átomo+electrón tiene **más energía**.
- Cuando cae a un nivel más bajo ($n=2$), el sistema tiene **menos energía**.
- Esa diferencia de energía **no puede desaparecer** (principio de conservación de la energía). Se transforma en una **partícula de luz**: el fotón.

⚠️ **Idea importante:** el fotón **no estaba escondido** adentro del átomo esperando salir. Se **crea** en el momento exacto de la transición, con una energía igual a la diferencia entre los dos niveles:

$$\boxed{E_{\text{fotón}} = E_{\text{alto}} - E_{\text{bajo}} = \Delta E = h\nu = \frac{hc}{\lambda}}$$

Es el mismo tipo de proceso que en una lámpara: entra energía eléctrica, salen fotones. La luz no estaba "guardada" en el cable.

> La emisión de luz por caída de un electrón se llama **emisión espontánea**. Existe también la **emisión estimulada** (un fotón que pasa "gatilla" la caída y sale un fotón clonado) — ése es el principio del **láser** y de los amplificadores de fibra óptica. Guardá esto para Telecomunicaciones.

---

## 2. ¿Qué son en serio los "niveles de energía" $n=1, n=2, n=3$?

Acá está la parte que más confunde. Vamos por capas.

### 2.1 Son estados de energía permitidos (la escalera)

Un electrón atado a un núcleo **no puede tener cualquier energía**. Sólo puede tener ciertos valores **permitidos**, como los escalones de una escalera:

- Podés estar parado en el escalón 1 ($n=1$) o en el 2 ($n=2$).
- **No podés flotar entre el escalón 1 y el 2.** No existe el "$n=1{,}5$".

| Nivel | Nombre | Qué es |
|---|---|---|
| $n=1$ | **Estado fundamental** | El más cercano al núcleo, el de **menor energía**. El electrón está lo más fuertemente atado posible. |
| $n=2, 3, 4…$ | **Estados excitados** | El electrón tiene **más energía** y está, en promedio, **más lejos** del núcleo. |

### 2.2 Cada nivel es una nube de probabilidad (orbital), no una órbita

Ojo con la imagen del "sistema solar" (el electrón dando vueltas como un planeta): **eso es el modelo de Bohr, y está obsoleto**. En el modelo cuántico actual (el que se usa), cada nivel define un **orbital**: una **región del espacio donde es muy probable encontrar al electrón** (~90% de probabilidad).

- En $n=1$: nube esférica chica y compacta, pegada al núcleo.
- En $n=2$: nube más grande, con formas nuevas posibles (esferas más grandes o lóbulos tipo mancuerna).
- En $n=3$: aún más extendida y con más subestructuras.

### 2.3 🔑 Los niveles SON la configuración electrónica ($1s^2, 2s^2, 2p^6…$)

**Sí. Exactamente eso.** Los "niveles de energía" de los que veníamos hablando son la **configuración electrónica** que viste en la Clase 1. Se lee así:

$$\underbrace{3}_{\text{nivel } n}\;\underbrace{p}_{\text{subnivel (forma)}}\!{}^{\overbrace{6}^{\text{n° de electrones}}}$$

| Parte | Qué es | Determina |
|---|---|---|
| **Número** (1, 2, 3…) | Número cuántico principal **$n$** = la "capa" | La **energía** / distancia al núcleo |
| **Letra** (s, p, d, f) | El **subnivel** u orbital | La **forma** de la nube (s = esfera, p = mancuerna…) |
| **Superíndice** (², ⁶…) | Cuántos electrones hay ahí | — |

⚠️ Detalle fino que resuelve tu confusión: **un mismo nivel $n$ tiene varios subniveles con energías algo distintas.** El nivel $n=3$ no es un solo escalón: son varios escalones juntos ($3s$, $3p$, $3d$). Por eso el "salto" no es sólo "de $n=3$ a $n=2$", sino más precisamente de un **subnivel** a otro (por ejemplo $3p \to 2s$).

---

## 3. La energía es DISCRETA, no continua

Una corrección de vocabulario que importa: la energía de los electrones en el átomo **sí es discreta** (está **cuantizada**). Lo que **no** es, es **continua**.

- **Discreta / cuantizada** = por escalones, valores separados y fijos. ✅ Así es.
- **Continua** = una rampa lisa donde vale cualquier valor intermedio. ❌ No es así.

Por eso los espectros son **rayas separadas** (líneas) y no un arcoíris continuo: el átomo sólo puede emitir los "saltos" que su escalera permite, y nada en el medio.

---

## 4. ⭐ Por qué el espectro cambia de un átomo a otro

Ésta era **tu pregunta central**: si en el hidrógeno el electrón cae de $n=3$ a $n=2$ y en el hierro también cae de $n=3$ a $n=2$, ¿por qué dan colores distintos?

Porque **la "altura de los escalones" es distinta en cada elemento**. Un salto $n=3 \to n=2$ **no libera la misma energía** en el hidrógeno que en el hierro o el sodio. Hay dos motivos:

### A. La carga del núcleo ($Z$, número de protones)

El electrón se queda cerca del núcleo por la **atracción electrostática** del núcleo positivo. Cuantos más protones, **más fuerte tira** el núcleo, y más **separados y profundos** quedan los niveles de energía.

- Hidrógeno: **1 protón** ($Z=1$).
- Hierro: **26 protones** ($Z=26$).

Para un átomo **hidrogenoide** (un solo electrón, como H, He⁺, Li²⁺), la energía de cada nivel es exactamente:

$$\boxed{E_n = -13{,}6\ \text{eV} \cdot \frac{Z^2}{n^2}}$$

Fijate que depende de $Z^2$. Como está al cuadrado, la separación entre niveles **crece muy rápido** con el número de protones → el mismo salto $n=3\to n=2$ da un fotón mucho más energético (y de otro color, incluso ultravioleta) en un átomo más pesado.

⚠️ **Cuidado (esto el material típico lo dice mal):** esa fórmula $E_n = -13{,}6\,Z^2/n^2$ **sólo vale exacto para átomos de UN solo electrón** (hidrogenoides). Para el hierro (26 electrones) **no** se aplica directamente, por lo que viene ahora:

### B. Apantallamiento y repulsión entre electrones

En átomos con **muchos electrones** (polielectrónicos) pasan dos cosas que el hidrógeno no tiene:

1. **Apantallamiento:** los electrones internos se meten entre el núcleo y los externos, y **"tapan" (escudan) parte de la carga** del núcleo. El electrón externo no siente los 26 protones completos del hierro, sino una **carga nuclear efectiva $Z_{\text{ef}}$** menor.
2. **Repulsión electrón-electrón:** los electrones se empujan entre sí. Esto **rompe la degeneración**: dentro de un mismo nivel $n$, los subniveles $s, p, d, f$ dejan de tener la misma energía y se separan (por eso $E_s < E_p < E_d < E_f$ dentro de una capa).

**Conclusión:** cada elemento termina con un **conjunto de niveles y subniveles único e irrepetible** — una escalera propia, distinta a la de todos los demás. Por eso:

> Un salto "equivalente" ($n=3\to n=2$) libera **energías distintas en cada elemento** → **fotones de distinto color** → **cada átomo tiene su espectro característico**. Esa es la huella digital.

### Ejemplo concreto: el sodio (Na, 11 electrones)

Configuración fundamental: $1s^2\,2s^2\,2p^6\,3s^1$. El electrón "de afuera" está en $3s$.

1. Le das energía (llama, chispa) → el electrón salta de $3s$ a $3p$: queda $…3p^1$ (sodio excitado).
2. $3p$ no es estable → el electrón cae de vuelta: $3p \to 3s$.
3. La diferencia exacta de energía entre $3p$ y $3s$ **en el sodio** sale como un fotón de **589 nm = luz amarilla**.

Ése es el amarillo de las **lámparas de sodio** de la calle, y el que ves si tirás **sal de cocina al fuego**. Ese número (589 nm) es del sodio y de nadie más.

---

## 5. ¿A qué nivel sube el electrón cuando lo excitás?

Tu pregunta: estando en $1s^1$, ¿sube a $2s$, a $2p$, a $3p$…? ¿Al de al lado o a cualquiera?

**A cualquiera al que la energía le alcance.** No está obligado a subir un solo escalón. La regla es que la energía entregada **coincida exactamente** con la diferencia entre el nivel donde está y un nivel permitido:

| Energía que le das | A dónde va |
|---|---|
| Poca (la justa para $n=1\to n=2$) | Sube a $n=2$ |
| Más (la justa para $n=1\to n=3$) | Sube directo a $n=3$ |
| Mucha | Salta directo a $n=6$, $n=7$… de un solo tiro |
| **Más de 13,6 eV** (en el H) | El electrón **se va del átomo** → **ionización** |

⚠️ **No sube a un nivel "a medias".** Si la energía no coincide con ningún salto permitido, no sube (ver sección 8).

### Regla de selección (por qué desde $1s$ tiende a ir a un $p$)

Cuando la excitación es por **un fotón de luz**, la mecánica cuántica exige que el subnivel cambie en **$\Delta \ell = \pm 1$**: de $s$ tiene que ir a $p$, de $p$ a $s$ o $d$, etc. Por eso desde $1s$ un fotón lo manda preferentemente a un subnivel **$p$** ($2p, 3p, 4p…$), no a otro $s$.

Pero si la excitación es por **choque** (calor, colisión con otro electrón), esa regla no aplica y puede terminar en **cualquier** subnivel ($2s$, $3s$, $3d$…).

---

## 6. ¿Cómo baja? ¿De a un escalón o de varios?

Cuando el electrón está arriba (digamos en $n=4$), puede bajar de **dos formas**:

### Opción A — Caída directa (un solo salto grande)

Cae de $n=4$ directo al fundamental $n=1$ **de una**:
$$n=4 \longrightarrow n=1 \quad\Rightarrow\quad \text{un solo fotón muy energético (UV)}$$

### Opción B — Caída en cascada (en escalones)

Hace paradas intermedias, y **emite un fotón en cada escalón**:
$$n=4 \to n=2 \;(\text{fotón turquesa, visible}) \quad\text{y luego}\quad n=2 \to n=1 \;(\text{fotón UV})$$

Un mismo átomo, en una misma "bajada", puede soltar **varios fotones** distintos si baja en cascada. Cuál camino toma es cuestión de probabilidad.

---

## 7. Las familias de saltos del hidrógeno (series espectrales)

Todos los saltos del hidrógeno se agrupan en **familias**, según a qué nivel **caen** (el nivel de llegada define la familia):

| Serie | Cae a… | Región del espectro | ¿Se ve a ojo? |
|---|---|---|---|
| **Lyman** | $n=1$ | Ultravioleta (UV) | No |
| **Balmer** | $n=2$ | **Visible** | **Sí** ✅ |
| **Paschen** | $n=3$ | Infrarrojo (IR) | No |
| Brackett | $n=4$ | Infrarrojo lejano | No |

La única serie que cae en el **visible** es la de **Balmer** (llegada a $n=2$) — por eso es la famosa, es la que ves como líneas de colores en un tubo de hidrógeno:

| Salto | λ (nm) | ΔE (eV) | Color | Nombre |
|---|---|---|---|---|
| $n=3 \to 2$ | 656 | 1,89 | **Rojo** | Hα |
| $n=4 \to 2$ | 486 | 2,55 | **Turquesa / cian** | Hβ |
| $n=5 \to 2$ | 434 | 2,86 | **Azul-violeta** | Hγ |
| $n=6 \to 2$ | 410 | 3,02 | **Violeta** | Hδ |

Fijate que confirma lo que intuías: **$n=3\to 2$ da rojo** y **$n=4\to 2$ da turquesa**. Cuanto más arriba arranca la caída (a $n=2$), **más energía** libera → color más hacia el azul/violeta → hasta que pasa al UV.

Todo esto se puede calcular con una sola fórmula (**Rydberg**), que es la fórmula (2) del machete escrita para el hidrógeno:

$$\frac{1}{\lambda} = R_H\left(\frac{1}{n_{\text{bajo}}^2} - \frac{1}{n_{\text{alto}}^2}\right), \qquad R_H = 1{,}097\times 10^{7}\ \text{m}^{-1}$$

o, en energía, usando $E_n = -13{,}6/n^2$ eV:

$$\Delta E = 13{,}6\ \text{eV}\left(\frac{1}{n_{\text{bajo}}^2} - \frac{1}{n_{\text{alto}}^2}\right)$$

*(Verificación del rojo: $\Delta E = 13{,}6\,(1/4 - 1/9) = 1{,}89$ eV, y $\lambda \approx 1240/1{,}89 \approx 656$ nm ✓.)*

### ¿Por qué en un tubo real veo TODAS las líneas a la vez?

Porque un tubo de hidrógeno no tiene **un** átomo: tiene **billones**. En un instante dado, cada átomo está haciendo un salto distinto:

```
Átomo A:  excitado a n=3  →  cae a n=2  →  fotón ROJO      (656 nm)
Átomo B:  excitado a n=4  →  cae a n=2  →  fotón TURQUESA  (486 nm)
Átomo C:  excitado a n=5  →  cae a n=2  →  fotón AZUL      (434 nm)
Átomo D:  excitado a n=6  →  cae a n=1  →  fotón UV
```

El espectrómetro suma la luz de **todos** los átomos a la vez → ves **todas las líneas simultáneamente**, aunque cada átomo individual sólo hizo uno o dos saltos.

---

## 8. Cómo se mide en la práctica (la espectroscopía en sí)

Respondiendo tu duda de "¿le doy energías específicas una por una para adivinar el átomo?": **no hace falta**. No le vas dando cantidades exactas a ver cuál engancha. El método real es al revés — le das energía a lo bruto y **mirás qué luz devuelve**:

1. **Excitación masiva:** ponés la muestra en una **llama, arco eléctrico, chispa o calor**. Le entrás energía generalizada a millones de átomos.
2. **Promoción:** los electrones absorben energía y suben a niveles excitados variados ($n=2,3,4,5…$).
3. **Decaimiento y emisión:** casi instantáneamente caen y **emiten fotones**, cada uno con la λ exacta de su salto.
4. **Dispersión (el espectrómetro):** la luz emitida pasa por una **rendija** y luego por un **prisma o una red de difracción**, que **separa** la luz en sus longitudes de onda (la "abre" en colores).
5. **Lectura del "código de barras":** un sensor registra **dónde cae cada línea**. Ese patrón de rayas se compara con una base de datos → sabés **qué elemento es**.

> **Entonces:** con **una sola** excitación masiva ya obtenés el espectro completo del elemento. No hace falta ir probando energías de a una. El átomo, por su propia estructura, **sólo** puede emitir sus longitudes de onda permitidas; vos sólo tenés que descomponer esa luz y leer el patrón.

Esto se llama **espectroscopía de emisión**. Existe también la versión "al revés", la **espectroscopía de absorción**: pasás luz blanca (todos los colores) a través de la muestra y el átomo **se come** justo las λ que podría emitir → ves un arcoíris con **rayas negras** en esas posiciones. Es la misma huella, en negativo. (Así se sabe de qué están hechas las estrellas.)

---

## 9. El "salto cuántico": ¿el electrón se teletransporta?

Tu pregunta: cuando sube o baja, ¿está en un instante en un lugar y al instante siguiente en otro, sin pasar por el medio?

**En esencia, sí.** Se llama **salto cuántico** (*quantum leap*), y es de las cosas más raras de la física cuántica:

- El electrón **nunca aparece "a mitad de camino"** entre dos orbitales.
- **No hay una trayectoria** continua que puedas filmar; no existe un punto donde el electrón esté "subiendo por la escalera".
- Deja de estar en el estado $n=1$ y pasa a estar en el estado $n=2$ **sin ocupar las energías intermedias** (que, como vimos, están prohibidas).

**¿Por qué puede hacer eso?** Porque el electrón **no es una bolita** que se mueve. Se comporta como una **función de onda** (una onda de probabilidad, lo que viste como orbital). Cuando cambia de estado, la onda con la forma del nivel viejo se **reconfigura** en la forma del nivel nuevo. No es un objeto viajando por el espacio: es un **estado que cambia**.

> **Matiz honesto (no entra al parcial, pero para que no te mientan):** la transición no es literalmente en "tiempo cero". Tiene una duración finísima pero no nula, y por eso las líneas espectrales tienen un ancho mínimo. Para lo que necesitás en esta materia, la idea correcta es: **el electrón no recorre el espacio intermedio ni pasa por energías intermedias**.

---

## 10. ¿Qué pasa si le doy MÁS energía de la justa?

Tu ejemplo: si para subir necesita 10 y le doy 11, ¿usa 10 y sobra 1? **Depende de cómo le des esa energía.**

### Caso A — La energía viene de un fotón (luz)

Un fotón es un **paquete cerrado**: **o se absorbe entero, o no se absorbe nada**. No existe el "vuelto".

| Le das… | Necesita 10 | Qué pasa |
|---|---|---|
| 9 | falta | El fotón **pasa de largo**, no interactúa. El átomo es **transparente** a esa λ. |
| 10 (exacto) | justo | El fotón se **absorbe entero** y el electrón sube. ✅ |
| 11 | sobra 1 | **No pasa nada.** El átomo **no puede** agarrar 10 y devolver 1. Si 11 no coincide con **ningún** salto permitido, el fotón **pasa de largo**. |

⚠️ **La única excepción es la ionización.** Si le das **más que la energía de arranque** (13,6 eV en el H) para sacar el electrón del átomo, ahí sí: el electrón **se va**, y **el sobrante se lo lleva él como energía cinética** (velocidad). Ej.: si arrancarlo cuesta 13,6 eV y le pegás con un fotón de 20 eV, el electrón sale despedido con $20 - 13{,}6 = 6{,}4$ eV de energía de movimiento. *(Esto es el **efecto fotoeléctrico**, el que le dio el Nobel a Einstein.)*

### Caso B — La energía viene de un choque (calor, colisión con otra partícula)

Acá **sí hay vuelto**. Si otro electrón viene volando con 11 de energía cinética y choca:

- Le entrega **10** al electrón del átomo para que suba.
- **Rebota** y sigue su camino con **1** de energía sobrante.

Porque una partícula con energía cinética **puede entregar sólo una parte** de lo que trae; un fotón, no.

---

## 11. Ideas clave para llevarte

1. El electrón sólo puede tener **energías permitidas** (niveles $n$, cuantizados). Esos niveles **son la configuración electrónica** ($1s, 2s, 2p…$).
2. **Excitar** = subir de nivel (absorbe energía). **Decaer** = bajar (emite un **fotón** que se crea con $E=\Delta E$).
3. La **energía es discreta**, no continua → espectros de **líneas**, no continuos.
4. Cada elemento tiene una **escalera de niveles única** por su **carga nuclear ($Z$)** y su **apantallamiento/repulsión electrónica** → **espectro característico** (huella digital). La fórmula $E_n=-13{,}6\,Z^2/n^2$ **sólo** vale para átomos de 1 electrón.
5. El electrón sube **a cualquier nivel** que la energía permita; con fotón vale la **regla de selección** ($\Delta\ell=\pm1$).
6. Baja **directo o en cascada**; en un gas real, billones de átomos hacen todos los saltos a la vez → **todas las líneas** juntas.
7. **Series del H:** Lyman (→1, UV), **Balmer (→2, visible)**, Paschen (→3, IR).
8. Se **mide** excitando en masa y **descomponiendo la luz** con un prisma/red → se lee el patrón de líneas.
9. El **salto cuántico** no pasa por el espacio ni por energías intermedias: la función de onda se **reconfigura**.
10. Energía de más: con **fotón**, es **todo o nada** (salvo ionización, donde el sobrante va a energía cinética); con **choque**, hay **vuelto**.

---

## 📌 Fórmulas de esta profundización

$$E_{\text{fotón}} = \Delta E = h\nu = \frac{hc}{\lambda} \qquad E_n = -13{,}6\ \text{eV}\cdot\frac{Z^2}{n^2}\ \text{(sólo hidrogenoides)}$$

$$\frac{1}{\lambda} = R_H\left(\frac{1}{n_{\text{bajo}}^2} - \frac{1}{n_{\text{alto}}^2}\right),\quad R_H = 1{,}097\times10^{7}\ \text{m}^{-1} \qquad \Delta E\,[\text{eV}] \approx \frac{1240}{\lambda\,[\text{nm}]}$$

$$E_{\text{fotón (ioniza)}} = E_{\text{ionización}} + E_{\text{cinética del }e^-} \quad\text{(efecto fotoeléctrico)}$$
