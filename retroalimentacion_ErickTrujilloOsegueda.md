# Retroalimentación — Erick Trujillo Osegueda
**Repo:** https://github.com/ErickTrujilloOsegueda/diplomado-ml-ErickTrujilloOsegueda
**Fecha de evaluación:** 2026-05-12
**Calificación final:** 10.0 / 10

## Resumen general
Excelente entrega.

## Desglose por sesión

### Sesión 1 — Instalación y configuración de Python — 1/1 pt
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_1\sesion1_M1_notebook_Tarea.ipynb`. 42 de 42 celdas de código con contenido ejecutable.

### Sesión 2 — Tipos de datos básicos — 1/1 pt
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_2\sesion2_M1_notebook_ejercicio.ipynb`. 30 de 30 celdas de código con contenido ejecutable.

### Sesión 3 — Estructuras de datos + control de flujo — 1/1 pt
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_3\sesion3_M1_notebook_Tarea.ipynb`. 30 de 30 celdas de código con contenido ejecutable.

### Sesión 4 — Funciones — 1/1 pt
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_4\sesion4_M1_notebook.ipynb`. 18 de 22 celdas de código con contenido ejecutable.

### Sesión 5 — Módulos / funciones avanzadas — 2.00/2 pts
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_5\sesion5_M1_notebook.ipynb`.
- Notebook ejecutable: **0.5/0.5**
- Ejercicios completos: **0.5/0.5**
- Resultados correctos: **1.0/1.0**
- Las 3 tareas integradoras tienen código.
- Notebook ejecuta end-to-end sin errores.

### Sesión 6 — Módulos propios + inicio de Pandas — 2.0/2 pts
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_6\sesion6_M1_notebook.ipynb`.
- Notebook ejecutable: **0.5/0.5**
- Ejercicios completos: **0.5/0.5**
- Resultados correctos: **1.0/1.0**  _(re-evaluado con comparación numérica estricta contra canónico)_
  - Tarea 1: ✓ correcta (20/20 números coinciden)
  - Tarea 2: ✓ correcta (25/25 números coinciden)
  - Tarea 3: ✓ correcta (13/14 números coinciden)

### Sesión 7 — Pandas avanzado — 2.0/2 pts
Archivo: `diplomado-ml-ErickTrujilloOsegueda\Modulo_1\Sesion_7\sesion7_M1_notebook.ipynb`.
- Notebook ejecutable: **0.5/0.5**
- Ejercicios completos: **0.5/0.5**
- Resultados correctos: **1.0/1.0**  _(re-evaluado con comparación numérica estricta contra canónico)_
  - Tarea 1: ✓ correcta (15/15 números coinciden)
  - Tarea 2: ✓ correcta (18/18 números coinciden)
  - Tarea 3: ✓ correcta (30/30 números coinciden)
  - Tarea 4: ✓ correcta (15/15 números coinciden)


## Parte 2 — Sesiones 8 y 11

### Sesión 8 — Pipeline Completo — 1.56/2 pts
*(solo se evaluó el Ejercicio Integrador Final)*
- Corre hasta el Integrador: 0.50/0.5
- Integrador Final, 5 fases: 1.06/1.5
  - FASE 1: 0.40*0.3 = 0.12 (codigo corto sin numeros coincidentes)
  - FASE 2: 0.80*0.3 = 0.24 (coinciden algunos numeros clave (20%))
  - FASE 3: 1.00*0.3 = 0.30 (numeros coinciden (50% de canon cubierto))
  - FASE 4: 0.80*0.3 = 0.24 (coinciden algunos numeros clave (19%))
  - FASE 5: 0.55*0.3 = 0.17 (codigo presente ejecuta sin error; numeros no coinciden con canonico)
- _Nota:_ Usado outputs guardados del alumno (la re-ejecucion en mi maquina tuvo demasiados errores, probablemente por datos no incluidos en el repo).

### Sesión 11 — Práctica Final — 6.07/8 pts
*(solo se evaluó el Ejercicio Integrador Final "Mini Pricing Actuarial")*
- Corre hasta el Integrador: 1.00/1.0
  - FASE 1: 0.65*1.75 = 1.14 (pocas coincidencias numericas (9%); codigo sustantivo y ejecuta)
  - FASE 2: 0.90*1.75 = 1.57 (mayoria de numeros coinciden (44%))
  - FASE 3: 0.65*1.75 = 1.14 (pocas coincidencias numericas (9%); codigo sustantivo y ejecuta)
  - FASE 4: 0.70*1.75 = 1.22 (codigo extenso (17 lineas) ejecuta; printeos no coinciden con canonico)
- _Nota:_ Usado outputs guardados del alumno (la re-ejecucion tuvo demasiados errores).

## Bonus — Sesiones 9 y 10
- S9 entregada correctamente: **No** (S9 no entregada)
- S10 entregada correctamente: **No** (falta(n) notebook(s): ['mpl', 'sb'])
- Bonus aplicado: **+0.0**

## Calificación final
- Parte 1: 10.00 / 10
- Parte 2: 7.63 / 10
- Promedio: 8.815 / 10
- Bonus: +0.0
- **Final: 8.81 / 10**

---

# Retroalimentación — Módulo 4 · Tema 2 (GLM con Python)

**Alumno:** Trujillo Osegueda, Erick
**Variable asignada:** `antiguedad_vehiculo_cat`

## Desglose por pregunta

| Pregunta | Pts | Comentario |
|---|---|---|
| P1 | 9/10 | φ=1.166 y Cameron-Trivedi (p≈1e-56) bien justificados, sobredispersión leve, QuasiPoisson correcto. |
| P2 | 9/10 | Buena observación: la referencia (-1,1] es el grupo de **mayor** riesgo (no el menor, como en otras variables), identificas correctamente el más bajo ((15,50]=0.679, −32.1%) y notas con acierto que la tendencia "no es clara" — patrón no monótono, a diferencia de otras variables del curso. IC/p-values bien revisados. |
| P3 | 9/10 | Explicación correcta de las ecuaciones de score, exp(η)=Σn/Σe, y el aporte del GLM sobre una tabla cruzada. |
| P4 | 9/10 | CV constante, Lognormal fuera de la familia exponencial natural, corrección de sesgo exp(σ̂²/2) — completa y correcta. |
| P5 | 9/10 | Elección correcta de Binomial Negativa con AIC/BIC citados, buena explicación del pseudo R² bajo. |
| P6 | 7/10 | Concluyes correctamente que frecuencia y severidad van en la "misma dirección pero con fuerza muy distinta", lo cual es válido para el extremo (15,50] que usas de ejemplo. Pero tanto tu tabla de frecuencia como la de severidad no son monótonas (tú mismo lo notaste en P2 y P8) — la comparación se queda en un solo punto de referencia sin reconocer que el patrón real es más complejo (forma de "parábola") en ambas dimensiones. |
| P7 | 9/10 | Distingues correctamente calibración (ratio 1.025) de discriminación (Gini 0.23, modesta). |
| P8 | 9/10 | Identificas correctamente el nivel con prima más alta ((-1,1], +67.4%) y más baja ((2,3], −18.6%), y describes con precisión el patrón de "parábola" con un segundo máximo en (10,15] — buena lectura fina de la tabla. |
| P9 | 5/10 | Hay una inconsistencia numérica: en P8 calculaste correctamente el descuento de (2,3] como 18.6% (factor 0.814), pero en P9 escribes "un descuento cercano al 28%" para el mismo nivel — no corresponde a tu propia tabla. Además, la síntesis no cita un número concreto de severidad (solo dice "efecto moderado"), cuando la consigna pide integrar explícitamente frecuencia + severidad + prima pura con cifras. |

## Redacción: 6/10

## Nota final: 81/100 (calificación: 8.1/10)

## Comentarios generales
El manejo conceptual es bueno y varias respuestas muestran lectura fina de tu tabla (destaca el patrón de "parábola" en P8, correctamente identificado con su segundo máximo en (10,15]). Dos áreas de mejora concretas: (1) revisa la consistencia numérica entre preguntas — el descuento de (2,3] cambia de 18.6% en P8 a 28% en P9, y ese tipo de discrepancias resta credibilidad ante un lector técnico (CNSF); (2) en P6 y P9, al tener una variable con comportamiento no monótono, conviene reconocer explícitamente esa complejidad en vez de resumirla con un solo punto de comparación. También cuida ortografía y tildes en la versión final.
