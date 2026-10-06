# 📊 Análisis de Clientes y Consumo - ConnectaTel

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) y una segmentación estratégica de la base de clientes de ConnectaTel, traduciendo variables de consumo (llamadas, minutos y mensajes) en insights de negocio accionables.

---

## 📂 Datasets Utilizados en el Proyecto
Para el desarrollo de este análisis se utilizaron e integraron los siguientes tres conjuntos de datos:

* **`plans.csv`**: Información sobre las tarifas y planes actuales ofrecidos a los usuarios (Precio, minutos incluidos, GB incluidos, costo por consumo extra).
* **`users_latam.csv`**: Registro detallado con la información demográfica de los clientes (`user_id`, edad, ciudad, fecha de registro, plan contratado).
* **`usage.csv`**: Detalle del consumo real de los usuarios en la plataforma (`id`, `user_id`, duración de llamadas, longitud de mensajes, tipo de servicio).

---

## 🛠️ Etapas del Análisis

1. **Limpieza y Preparación:** Identificación y tratamiento de datos nulos o inconsistentes.
2. **Análisis Estadístico:** Evaluación de la distribución de los consumos mediante `.describe()`.
3. **Análisis de Outliers:** Identificación de patrones de uso extremo y justificación de negocio para su permanencia.

---

## 💡 Principales Hallazgos & Insights de Negocio

* **Patrones de Consumo Atípicos:** Se identificaron segmentos de uso extremo (*outliers*) en llamadas y minutos, lo que sugiere clientes con necesidades corporativas o de alto tráfico que actualmente usan planes residenciales.
* **Distribución de Tráfico:** El volumen de datos y minutos consumidos varía de forma significativa entre ciudades, permitiendo focalizar promociones específicas por región.
* **Salud e Integridad de Datos:** Se diagnosticaron y trataron los valores faltantes e inconsistencias sin alterar la distribución general, asegurando la calidad para decisiones comerciales.

---

## 🚀 Recomendaciones Estratégicas para el Negocio

1. **Reestructuración de Oferta de Planes:** Diseñar un plan de nivel intermedio o corporativo para capturar a los usuarios con consumo atípico sin que cancelen su suscripción (*churn*).
2. **Estrategia de Retención Focalizada:** Implementar alertas tempranas de uso para usuarios que están por superar los límites de su plan, ofreciendo un *upsell* personalizado antes de que perciban sobrecostos molestos.
3. **Optimización de Canales:** Concentrar la inversión de marketing en las ciudades de mayor consumo por usuario para maximizar el Retorno de Inversión (ROI).

---

## 💻 Herramientas y Tecnologías
* **Python** (Pandas, NumPy, SciPy)
* **Jupyter Notebook**
* **Estadística Descriptiva & EDA**
