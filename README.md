# 📱 iPhone Customer Sentiment Dashboard (2023–2024)

Análisis de más de **3,000 reseñas de clientes en Amazon** para entender cómo perciben distintos modelos de iPhone alrededor del mundo.  
Este proyecto combina **Python**, **limpieza y transformación de datos**, y un dashboard interactivo en **Looker Studio**.

---

## 📌 Objetivo del proyecto

- Identificar patrones de sentimiento (positivo, neutro, negativo).  
- Comparar modelos, colores y capacidades de almacenamiento.  
- Analizar variaciones por país.  
- Observar el comportamiento del rating a lo largo del tiempo.  
- Construir un dashboard claro, estético y funcional para análisis rápido.

---

## 🧼 Limpieza y preparación de los datos

El dataset original fue procesado en Python:

- Conversión de fechas a formato `datetime`.  
- Limpieza de nombres de color y extracción de atributos.  
- Conversión de variables a tipos adecuados.  
- Clasificación de sentimiento (Positivo / Neutro / Negativo) basada en `ratingScore`.  
- Exportación final a `.csv` para uso en BI.

Archivos incluidos:

dataset/
└── iphone_reviews_clean.csv


---

## 📊 Dashboard en Looker Studio

🔗 **Dashboard completo:**  
_Agrega aquí el enlace una vez que lo publiques_

El dashboard se compone de:

### ⭐ KPI principales
- Promedio de rating  
- % de reseñas positivas  
- % de reseñas neutras  
- % de reseñas negativas  
- Total de reseñas  

### 🌈 Sentimiento por color y almacenamiento
Barras apiladas que resaltan cómo cambia la percepción según el color o la capacidad del modelo.

### 📱 Ratings por modelo
Comparación visual clara entre los modelos más populares.

### 🌍 Reseñas por país
Distribución geográfica del volumen de reseñas.

### 📈 Tendencia del rating a lo largo del tiempo
Gráfica temporal para identificar variaciones estacionales o por lanzamiento.


---

## 💡 Principales hallazgos

- Más del **67%** de las reseñas son positivas.  
- Los modelos **iPhone 13 y iPhone 15** muestran las mejores evaluaciones.  
- La variante de **128GB** concentra la mayor cantidad de comentarios.  
- El color **Midnight** y **Blue** dominan en volumen de reseñas.  
- El rating mensual se mantiene estable entre **3.7 y 4.0** durante 2023–2024.

---

## 🛠️ Tecnologías utilizadas

- Python (Pandas, Jupyter Notebook)  
- Looker Studio  
- GitHub  
- CSV / DataFrames  

---

## ✨ Sobre el proyecto

Este dashboard es una muestra de:

- Diseño BI moderno  
- Limpieza y preparación de datos reales  
- Análisis exploratorio orientado a negocio  
- Creación de visualizaciones claras y ejecutivas  
- Buenas prácticas en documentación y estructura de repositorio  

---

## 👤 Autor  

GitHub: LuisT0
LinkedIn: Luis Antonio Torres Villalobos
