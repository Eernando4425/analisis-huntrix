# Análisis de Variables: Riqueza Léxica (Volumen y Diversidad)
**Rama:** linguistica-complejidad
**Analista:** [fernando]

---

## 1. Definición de las Variables

### Variable A: Conteo Total de Palabras (Tokens)
* **Valor en "Huntrix":** [INSERTAR VALOR, ej: 350]
* **Unidad de medida:** Cantidad (Número entero)
* **Qué mide:** La longitud total del contenido lírico, sumando todas las palabras pronunciadas, incluyendo repeticiones. Indica la "magnitud" del mensaje verbal en la canción.

### Variable B: Conteo de Palabras Únicas (Types)
* **Valor en "Huntrix":** [INSERTAR VALOR, ej: 120]
* **Unidad de medida:** Cantidad (Número entero)
* **Qué mide:** El tamaño del vocabulario real utilizado, contando cada palabra diferente una sola vez (sin importar cuántas veces se repita). Indica la diversidad léxica y la creatividad del compositor.

---

## 2. Relación y Comparabilidad

### ¿Cuál es la característica común?
Ambas variables miden la **Densidad de Información**. Juntas se utilizan para calcular la relación "Type-Token Ratio" (TTR), que es una métrica estándar en lingüística computacional para determinar si un texto es simple y repetitivo o complejo y rico.

### Similitudes
* Ambas son métricas **cuantitativas absolutas** (son números enteros exactos extraídos del texto).
* Ambas excluyen elementos no verbales (como los solos de guitarra o silencios).
* Ambas requieren un proceso de "tokenización" (separar el texto en unidades individuales) para ser calculadas.

### ¿Por qué son medibles y comparables?
Son medibles mediante herramientas de procesamiento de texto que cuentan cadenas de caracteres separadas por espacios. Son comparables porque al dividir B entre A (Únicas / Totales) obtenemos un porcentaje de repetitividad: una canción con muchas palabras totales pero pocas únicas es muy repetitiva (ideal para marketing/pop), mientras que valores cercanos entre sí indican una narrativa densa.

---

## 3. Historial de Pasos (Log de Trabajo)
Para asegurar la transparencia del proceso, documentamos los pasos seguidos:

1.  **Extracción:** Se tomó la letra completa de "Huntrix" y se convirtió todo el texto a minúsculas para evitar duplicados por mayúsculas.
2.  **Verificación:** Se eliminaron signos de puntuación (comas, puntos) para que no afectaran el conteo.
3.  **Análisis:**
    * Se realizó el conteo bruto de todas las palabras (Variable A).
    * Se filtró la lista para dejar solo una instancia de cada palabra y se contaron (Variable B).
4.  **Creación de Rama:** Se creó la rama `linguistica-complejidad` en el repositorio.
5.  **Commit:** Se subió este archivo documentando la diversidad del vocabulario.
