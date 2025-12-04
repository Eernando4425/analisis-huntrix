# Análisis de Variables: Perfil Emocional (Valencia y Energía)
**Rama:** emocion-sentimiento
**Analista:** [fernando]

---

## 1. Definición de las Variables

### Variable A: Valencia Musical
* **Valor en "Huntrix":** [INSERTAR VALOR, ej: 0.45 o 4.5]
* **Unidad de medida:** Escala decimal (0.0 a 1.0) o Escala (1 a 10)
* **Qué mide:** Describe la "positividad" musical que transmite el track. Los valores altos indican un sonido alegre, eufórico o feliz; los valores bajos indican un sonido triste, deprimente o enojado.

### Variable B: Nivel de Energía
* **Valor en "Huntrix":** [INSERTAR VALOR, ej: 0.80 o 8.0]
* **Unidad de medida:** Escala decimal (0.0 a 1.0) o Escala (1 a 10)
* **Qué mide:** Representa una medida perceptual de intensidad y actividad. Se basa en el rango dinámico, el volumen percibido, el timbre y la velocidad de ataque. Un valor alto se siente rápido y ruidoso; un valor bajo se siente tranquilo.

---

## 2. Relación y Comparabilidad

### ¿Cuál es la característica común?
Ambas variables son **psicoacústicas**. Juntas forman el "Modelo Circunflejo de la Emoción" (Circumplex Model): la Valencia actúa como el eje X (tipo de emoción) y la Energía como el eje Y (intensidad de esa emoción). Son necesarias ambas para definir si una canción es "feliz y tranquila" o "triste y agresiva".

### Similitudes
* Ambas se calculan mediante algoritmos de análisis de señal de audio (no dependen de leer la letra, sino de "escuchar" la onda sonora).
* Ambas suelen representarse en escalas normalizadas (del 0 al 1 o del 1 al 100) para facilitar su comparación entre miles de canciones.
* Ambas afectan directamente el estado de ánimo del oyente.

### ¿Por qué son medibles y comparables?
Son medibles porque se extraen de parámetros técnicos objetivos del audio (como la entropía espectral y la densidad de percusión). Son comparables porque nos permiten situar la canción de "Huntrix" en un mapa emocional frente a otras canciones del mismo género, determinando si es más "oscura" o más "enérgica" que el promedio.

---

## 3. Historial de Pasos (Log de Trabajo)
Para asegurar la transparencia del proceso, documentamos los pasos seguidos:

1.  **Extracción:** Se consultó la base de datos "Huntrix" y se aislaron las columnas de métricas emocionales.
2.  **Verificación:** Se validó que los valores numéricos estuvieran dentro de la escala establecida (ej. que no hubiera un 11 en una escala de 10).
3.  **Análisis:** Se correlacionó la Valencia con la Energía para determinar el cuadrante emocional de la canción.
4.  **Creación de Rama:** Se creó la rama `emocion-sentimiento` en el repositorio remoto.
5.  **Commit:** Se subió este archivo `ANALISIS_VARIABLES.md` detallando la relación entre felicidad e intensidad.
