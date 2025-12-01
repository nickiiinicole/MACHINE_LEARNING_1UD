# 📈 GUÍA MAESTRA: INTERPRETACIÓN DE GRÁFICOS (PLANTILLAS)

---

## 1. HISTOGRAMA (Distribución Numérica)
*Para ver la forma, el centro y la dispersión de una variable numérica (ej: Salario, Edad).*

### 📋 Plantilla de Interpretación
> "La distribución de la variable **[NOMBRE_VARIABLE]** no es simétrica, presentando un claro **sesgo positivo (hacia la derecha)**.
>
> La mayor parte de los datos se concentran en el rango de **[VALOR_MIN]** a **[VALOR_MAX]**, situándose la moda en torno a **[VALOR_PICO]**. Observamos una **cola larga** hacia la derecha debido a la presencia de valores inusualmente altos."

* **Variaciones:**
    * *Si es simétrica:* "Presenta una distribución **normal (forma de campana)** centrada en la media."
    * *Si hay dos picos:* "Observamos una distribución **bimodal**, lo que sugiere la existencia de dos subgrupos diferenciados."

---

## 2. SCATTER PLOT (Dispersión - Relación)
*Para ver si dos variables numéricas están relacionadas (ej: Edad vs Salario).*

### 📋 Plantilla de Interpretación
> "Se observa una **correlación [POSITIVA / NEGATIVA]** entre **[VARIABLE_EJE_X]** y **[VARIABLE_EJE_Y]**.
>
> A medida que aumenta **[VARIABLE_EJE_X]**, **[VARIABLE_EJE_Y]** tiende a **[AUMENTAR / DISMINUIR]**. La relación parece ser **[FUERTE / MODERADA / DÉBIL]** dado que los puntos están **[MUY AGRUPADOS / DISPERSOS]** formando una tendencia lineal."

* **Variaciones:**
    * *Si no hay relación:* "No se observa ninguna correlación clara entre las variables; los puntos forman una nube dispersa sin tendencia aparente."

---

## 3. BAR PLOT (Gráfico de Barras)
*Para comparar cantidades entre categorías (ej: Nivel de Estudios).*

### 📋 Plantilla de Interpretación
> "En el análisis de la variable **[NOMBRE_VARIABLE]**, observamos que la categoría **[CATEGORÍA_MÁS_ALTA]** es la predominante (la moda), seguida por **[SEGUNDA_CATEGORÍA]**.
>
> Existe un **desbalance de clases significativo**, ya que la categoría mayoritaria representa una proporción mucho mayor que la categoría **[CATEGORÍA_MENOS_REPRESENTADA]**, lo cual podría sesgar el modelo si no se trata adecuadamente."

---

## 4. BOXPLOT (Caja y Bigotes)
*Para detectar Outliers y ver dónde está la mediana.*

### 📋 Plantilla de Interpretación
> "El diagrama de caja muestra que la **mediana** de **[NOMBRE_VARIABLE]** se sitúa aproximadamente en **[VALOR_MEDIANA]**.
>
> El 50% central de los datos (rango intercuartílico) está comprendido entre **[VALOR_Q1]** y **[VALOR_Q3]**. Destaca la presencia de numerosos **valores atípicos (outliers)** en la parte **[SUPERIOR / INFERIOR]** del gráfico, que superan el valor de **[VALOR_DEL_BIGOTE]**."

---

## 5. MATRIZ DE CORRELACIÓN (Heatmap)
*Para ver relaciones entre todas las variables numéricas a la vez.*

### 📋 Plantilla de Interpretación
> "El mapa de calor revela una **fuerte correlación positiva (>[0.8])** entre las variables **[VAR_A]** y **[VAR_B]**, lo que indica un posible problema de **multicolinealidad** (redundancia).
>
>