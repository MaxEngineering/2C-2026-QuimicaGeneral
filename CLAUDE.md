# CLAUDE.md — Química General (ECyT / UNSAM · 2C 2026)

Repositorio de apuntes de **Química General**, Ingeniería en Telecomunicaciones, UNSAM.
Docentes: Norberto Boggio y Santiago Poklepovich. Cursada: Lunes y Miércoles 18–22 hs.

Este archivo documenta **cómo se procesan las clases**. Cuando se agregue una clase nueva, seguir este procedimiento tal cual para que todo el repo quede uniforme.

---

## 📁 Estructura del repo

```
2C-2026-QuimicaGeneral/
├── CLAUDE.md                              ← este archivo
├── MACHETE.md                             ← resumen operativo de TODA la materia
├── README.md
├── Clase1/
│   ├── P1-Clase1_p1_d1-20_NB2026.pdf      ← PDFs originales del docente
│   ├── P2-Clase1-p1_d21-38_NB2026.pdf
│   ├── P3-Clase1_parte2-NB2026.pdf
│   └── Clase1-Explicacion-Completa.md     ← explicación diapo por diapo
├── Clase2/
│   ├── P1-Clase 2_NB2026_UnionesQuimicas.pdf
│   ├── P2-(serie 2) Estructuras de Lewis y cargas formales.pdf
│   ├── P3-Estructuras _resonancia _ej.pdf
│   └── Clase2-Explicacion-Completa.md     ← (pendiente)
└── Practica/
    ├── SERIE 1_2C_2026.pdf
    └── SERIE 2_2C_2026.pdf
```

**Convención de nombres:**
- Los PDFs vienen numerados `P1-`, `P2-`, `P3-`… en el orden en que se dan en clase.
- El apunte generado se llama siempre **`ClaseN/ClaseN-Explicacion-Completa.md`**.
- El machete es único y vive en la raíz: **`MACHETE.md`**.

---

## 🔧 Cómo leer los PDFs (importante)

⚠️ **El tool `Read` NO puede abrir PDFs en esta máquina** — falla con `pdftoppm is not installed` (no hay poppler-utils instalado).

Y como las diapositivas son **mayormente imágenes, diagramas, estructuras químicas y tablas**, extraer sólo el texto pierde la mitad del contenido. **Hay que VER las diapositivas.**

### Procedimiento

**1. Renderizar las páginas a PNG** con PyMuPDF (`fitz`), que sí está instalado:

```bash
python -c "
import fitz, os
out = r'<SCRATCHPAD>/img'
os.makedirs(out, exist_ok=True)
files = {'A':'ClaseN/P1-....pdf', 'B':'ClaseN/P2-....pdf', 'C':'ClaseN/P3-....pdf'}
for k, f in files.items():
    d = fitz.open(f)
    print(k, f, d.page_count)
    for i, p in enumerate(d):
        p.get_pixmap(dpi=80).save(os.path.join(out, f'{k}_{i+1:02d}.png'))
"
```

- **80 dpi alcanza** para leer todo el texto de las diapositivas sin gastar contexto de más.
- Usar prefijos de letra (`A_`, `B_`, `C_`) para no mezclar PDFs.
- Guardar en el **scratchpad de la sesión**, no en el repo.

**2. Leer las imágenes con `Read`**, en tandas de **~10 llamadas en paralelo** en un mismo mensaje. Hay que mirar **todas** las páginas, sin saltear ninguna.

**3. (Opcional) Texto plano de apoyo:** `pdftotext` existe en `/mingw64/bin`. Sirve para copiar textos largos con exactitud, pero **no reemplaza** ver las imágenes:

```bash
pdftotext -layout -enc UTF-8 "archivo.pdf" salida.txt   # separa páginas con \f
```

---

## 📄 Cómo escribir el `ClaseN-Explicacion-Completa.md`

**Objetivo:** que alguien que faltó a la clase pueda entender **absolutamente todo** leyendo sólo ese archivo, sin abrir los PDFs.

### Estructura del archivo

```markdown
# Clase N — Explicación completa, diapositiva por diapositiva

**Materia:** Química General — ECyT / UNSAM — 2do Cuatrimestre 2026
**Docentes:** ...
**Tema de la clase:** ...

Tabla con los PDFs, cuántas diapositivas tiene cada uno y qué contiene.

---
# PARTE 1 — `nombre-exacto-del-archivo.pdf`

## P1 — pág. 1 · Título de la diapositiva
[qué se ve]
**Explicación:** [por qué]

## P1 — pág. 2 · ...
...

---
# PARTE 2 — `...`
...

---
# Resumen de la Clase N en una página
[tablas de síntesis, fórmulas, reglas]
```

### Reglas de contenido

| Regla | Detalle |
|---|---|
| **Una sección por diapositiva** | Sin excepción. Encabezado `## P<n> — pág. <n> · <Título>` |
| **Numerar por PDF** | La numeración arranca de 1 en cada PDF (`P1 — pág. 1`, `P2 — pág. 1`), como pidió el usuario |
| **Transcribir lo que se VE** | Diagramas, fotos, tablas, esquemas, fórmulas, rótulos. Si hay una foto, describirla. Si hay un esquema, redibujarlo en markdown/ASCII |
| **Después explicar** | Bloque **`**Explicación:**`** con el *por qué*: qué significa, para qué sirve, cómo se conecta con lo anterior |
| **Agregar lo que el docente da por sabido** | Cuentas intermedias, unidades, conversiones, el motivo físico detrás de una regla |
| **Marcar las diapositivas "Para ver en casa…"** | Aclarar que son de repaso, pero explicarlas igual (entran) |
| **Agrupar sólo cuando corresponde** | Si varias diapositivas son pasos de un mismo desarrollo (ej. las 10 del Bromo), darles cada una su encabezado pero cerrar con una **explicación conjunta** |
| **Cerrar con un resumen** | Sección final con las fórmulas, reglas y tablas de la clase |

### Estilo

- **Español rioplatense**, tuteo con voseo ("fijate", "hacé la cuenta", "prestá atención"). Es como habla el usuario.
- **Directo y sin relleno.** Nada de "es importante destacar que…". Ir al grano.
- **Fórmulas en LaTeX** (`$$...$$` para display, `$...$` inline). Las fórmulas centrales van en `\boxed{}`.
- **Tablas de markdown** para todo lo que sea comparativo o enumerable. Son lo más útil para estudiar.
- **Negrita** para términos técnicos la primera vez que aparecen y para definiciones.
- **⚠️** para trampas, excepciones y errores frecuentes.
- **✓ / ❌** para marcar lo correcto y lo incorrecto en comparaciones.
- Marcar explícitamente **qué se pregunta en el parcial** cuando se nota que algo es evaluable ("esta tabla hay que poder reconstruirla sola").
- Conectar con **Ingeniería en Telecomunicaciones** cuando venga a cuento (ej.: el espectro EM y la fibra óptica, los semiconductores). Sin forzarlo.

---

## 📋 Cómo actualizar el `MACHETE.md`

**Después de terminar el apunte de la clase, SIEMPRE actualizar el machete.** No es opcional: el machete es el archivo que se usa para estudiar y rendir.

### Qué es el machete

Un **resumen operativo de toda la materia**: sólo lo que hace falta para **resolver ejercicios**. Nada de historia narrada, nada de explicaciones largas. Fórmulas, tablas, métodos paso a paso y ejemplos resueltos.

> **Regla de oro:** el apunte de clase explica **por qué**. El machete dice **cómo se hace**.

### Qué SÍ va al machete

- **Fórmulas** y constantes
- **Tablas de referencia** (números cuánticos, capacidades, geometrías, grupos)
- **Métodos paso a paso** numerados (configuración electrónica, Lewis, TRePEV)
- **Ejemplos resueltos** cortos, en formato tabla
- **Reglas y excepciones** (octeto, Hund, Pauli, deficientes, expandidos)
- **Errores típicos** → agregar filas a la tabla de la sección 11
- **Definiciones** que se piden textuales

### Qué NO va al machete

- Contexto histórico narrado (va sólo como tabla comprimida en la sección 12)
- Explicaciones de "por qué es así" (eso queda en el apunte de clase)
- Diapositivas de repaso, videos, links
- Cualquier cosa que no se use para resolver un ejercicio

### Procedimiento

1. **Leer el `MACHETE.md` actual** antes de tocarlo.
2. Ver qué secciones existentes se **amplían** con la clase nueva (ej.: una clase sobre polaridad amplía la sección de TRePEV).
3. Agregar **secciones nuevas numeradas** al final del bloque temático que corresponda, **antes** de las secciones 11 (Errores típicos) y 12 (Histórico), que van siempre últimas.
4. **Actualizar el índice** del principio.
5. **Agregar filas** a la tabla de "Errores típicos" con las trampas nuevas.
6. **Agregar las fórmulas nuevas** al bloque final "📌 Fórmulas — todas juntas".
7. Actualizar la línea de **"Contenido actual:"** del encabezado con la clase agregada.

### Secciones fijas del machete

Estas dos van **siempre al final**, en este orden:

- **11. Errores típicos** — tabla ❌ Error / ✅ Correcto
- **12. Modelos atómicos — línea histórica** — tabla comprimida

Y el archivo cierra con **📌 Fórmulas — todas juntas**.

---

## ✅ Checklist para una clase nueva

```
[ ] 1. Renderizar TODOS los PDFs de la clase a PNG (PyMuPDF, 80 dpi, scratchpad)
[ ] 2. Leer TODAS las páginas con Read, en tandas de ~10 en paralelo
[ ] 3. Escribir ClaseN/ClaseN-Explicacion-Completa.md
       [ ] Encabezado con tabla de PDFs y cantidad de diapositivas
       [ ] Una sección por diapositiva: qué se ve + Explicación
       [ ] Resumen final de la clase
[ ] 4. Leer el MACHETE.md actual
[ ] 5. Agregar al machete lo operativo de la clase nueva
       [ ] Secciones nuevas (antes de la 11)
       [ ] Índice actualizado
       [ ] Errores típicos ampliados
       [ ] Fórmulas nuevas en el bloque final
       [ ] Línea "Contenido actual:" actualizada
[ ] 6. Verificar que la cantidad de secciones == cantidad de diapositivas
```

---

## 📌 Notas

- **No commitear sin que el usuario lo pida.**
- Los PDFs originales **no se tocan ni se renombran**.
- Las imágenes renderizadas van al **scratchpad**, nunca al repo.
- Las series de práctica (`Practica/`) todavía no están procesadas. Si en algún momento se hacen, el criterio es el mismo: un `.md` por serie con los ejercicios resueltos y explicados, y los métodos que salgan de ahí al machete.
