---
# === METADATA GLOBAL ===
id: "CO-MAT-11-probabilidad-001"
country: "co"
grado: 11
asignatura: "Matemáticas"
tema: "Probabilidad y Estadística"
protocol_version: "2.1"
total_questions: 7
estado: "published"
creador: "AI-WorldExams"
generation_date: "2025-12-15"

# === LICENSING (NEW v2.1) ===
licenses:
  v1: "CC BY-SA 4.0"
  v2-v7: "CC BY-NC-SA 4.0"

# === SOURCE ATTRIBUTION ===
source: "ICFES Ejemplos Matemáticas (Adaptación)"
source_url: "https://www.icfes.gov.co"
source_license: "CC BY-SA 4.0"
search_query: "preguntas icfes matematicas probabilidad y estadistica grado 11"
original_question: "Cálculo de probabilidad simple con dados/urnas."
original_answer: "Casos favorables / Casos totales."
---

# Pregunta Base: Probabilidad Simple (Urna de Balotas)

> **Fuente:** ICFES Ejemplos Matemáticas (Adaptación)
> **Original:** Problema clásico de extracción aleatoria de elementos de un conjunto finito.

---

## Pregunta 1 (Original - Dificultad 3)

**ID:** `CO-MAT-11-probabilidad-001-v1`

### Enunciado

En una urna hay **10 balotas** del mismo tamaño y peso: **5 rojas**, **3 azules** y **2 verdes**. Si una persona extrae una balota al azar sin mirar, ¿cuál es la probabilidad de que la balota sea **azul**?

### Opciones

- [x] A) 30%
- [ ] B) 3%
- [ ] C) 50%
- [ ] D) 20%

### Explicación Pedagógica

**¿Por qué A es correcta?**
Usamos la Regla de Laplace: $P(A) = \frac{\text{Casos Favorables}}{\text{Casos Totales}}$.
- Casos Totales = $5+3+2 = 10$ balotas.
- Casos Favorables (Azules) = 3 balotas.
- $P(\text{Azul}) = \frac{3}{10} = 0.3$.
- Para porcentaje: $0.3 \times 100\% = 30\%$.

**Competencia evaluada:** Resolución de problemas (Cálculo de probabilidad simple).

---

## Pregunta 2 (Fácil A - Dificultad 1)

**ID:** `CO-MAT-11-probabilidad-001-v2`

### Enunciado

Usando la misma urna (5 rojas, 3 azules, 2 verdes), ¿qué color es **más probable** que salga en una extracción?

### Opciones

- [x] A) Roja.
- [ ] B) Azul.
- [ ] C) Verde.
- [ ] D) Todas tienen la misma probabilidad.

### Explicación Pedagógica

La probabilidad es mayor cuanta mayor cantidad de elementos favorables haya. Como hay más rojas (5) que azules (3) o verdes (2), es más probable sacar una roja.

---

## Pregunta 3 (Fácil B - Dificultad 2)

**ID:** `CO-MAT-11-probabilidad-001-v3`

### Enunciado

Si sacamos todas las balotas verdes de la urna, quedando solo las 5 rojas y las 3 azules (Total = 8). ¿Cuál es la probabilidad de sacar una verde ahora?

### Opciones

- [x] A) 0 (Suceso Imposible).
- [ ] B) 1 (Suceso Seguro).
- [ ] C) 50%.
- [ ] D) 10%.

### Explicación Pedagógica

Si no hay balotas verdes en la urna, la probabilidad de sacar una es **cero**. Es un suceso imposible.

---

## Pregunta 4 (Media A - Dificultad 3)

**ID:** `CO-MAT-11-probabilidad-001-v4`

### Enunciado

Se lanzan **dos monedas** al aire simultáneamente. ¿Cuál es la probabilidad de obtener **dos caras**?

### Opciones

- [x] A) 25% (1/4).
- [ ] B) 50% (1/2).
- [ ] C) 75% (3/4).
- [ ] D) 100% (1).

### Explicación Pedagógica

Espacio muestral: (Cara, Cara), (Cara, Sello), (Sello, Cara), (Sello, Sello). Total = 4 casos posibles.
Caso favorable (Cara, Cara) = 1.
Probabilidad = $1/4 = 0.25 = 25\%$.

---

## Pregunta 5 (Media B - Dificultad 3)

**ID:** `CO-MAT-11-probabilidad-001-v5`

### Enunciado

En un colegio de Bogotá con 100 estudiantes de grado 11, se realiza una encuesta: 60 prefieren el fútbol y 40 el baloncesto. Si se elige un estudiante al azar, la probabilidad de que prefiera baloncesto es:

### Opciones

- [x] A) $\frac{2}{5}$
- [ ] B) $\frac{3}{5}$
- [ ] C) $\frac{1}{2}$
- [ ] D) $\frac{4}{100}$

### Explicación Pedagógica

$P(\text{Baloncesto}) = \frac{40}{100}$.
Simplificando la fracción:
$\frac{40}{100} = \frac{4}{10} = \frac{2}{5}$.

---

## Pregunta 6 (Difícil A - Dificultad 4)

**ID:** `CO-MAT-11-probabilidad-001-v6`

### Enunciado

Volviendo a la urna original (5 rojas, 3 azules, 2 verdes). Si se saca una balota, **no se devuelve a la urna** (sin reposición), y luego se saca una segunda balota. ¿Cuál es la probabilidad de sacar **dos rojas seguidas**?

### Opciones

- [x] A) $\frac{2}{9}$
- [ ] B) $\frac{1}{4}$
- [ ] C) $\frac{1}{2}$
- [ ] D) $\frac{5}{10}$

### Explicación Pedagógica

$P(\text{Roja}_1) = \frac{5}{10} = \frac{1}{2}$.
Al no devolverla, quedan 9 balotas totales y 4 rojas.
$P(\text{Roja}_2 | \text{Roja}_1) = \frac{4}{9}$.
$P(\text{Total}) = P(\text{Roja}_1) \times P(\text{Roja}_2) = \frac{1}{2} \times \frac{4}{9} = \frac{4}{18} = \frac{2}{9}$.

---

## Pregunta 7 (Difícil B - Dificultad 5)

**ID:** `CO-MAT-11-probabilidad-001-v7`

### Enunciado

En una rifa hay 100 boletas numeradas del 00 al 99. Juan compra todas las boletas que terminan en 5. María compra todas las boletas que son múltiplos de 10. ¿Quién tiene mayor probabilidad de ganar?

### Opciones

- [x] A) Ambos tienen la misma probabilidad.
- [ ] B) Juan, porque el 5 es un número de la suerte.
- [ ] C) María, porque hay más múltiplos de 10.
- [ ] D) Ninguno puede ganar.

### Explicación Pedagógica

- Juan: 05, 15, 25, ... 95. Son **10 boletas**. $P = 10/100$.
- María: 00, 10, 20, ... 90. Son **10 boletas**. $P = 10/100$.
Ambos tienen 10 casos favorables de 100 posibles. La probabilidad es idéntica ($10\%$).

---

## 📊 Metadata de Validación

| Campo | Valor |
|-------|-------|
| Total Preguntas | 7 |
| Original (Dificultad 3) | 1 |
| Fácil (Dificultad 1-2) | 2 |
| Media (Dificultad 3) | 2 |
| Difícil (Dificultad 4-5) | 2 |

