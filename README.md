# Análisis de Clientes y Consumo - ConnectaTel

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) y una segmentación estratégica de la base de clientes de ConnectaTel, traduciendo variables de consumo (llamadas, minutos y mensajes) en insights de negocio accionables.

## 📊 Dataset Utilizado
## 📊 Datasets Utilizados en el Proyecto

Para el desarrollo de este análisis se utilizaron e integraron los siguientes tres conjuntos de datos:

| **`plans.csv`** | Información sobre las tarifas y planes actuales ofrecidos a los usuarios. | Precio, minutos incluidos, GB incluidos, costo por consumo extra. |
| **`users_latam.csv`** | Registro detallado con la información demográfica de los clientes. | `user_id`, `age` (edad), `city` (ciudad), `reg_date` (fecha de registro), `plan` contratado. |
| **`usage.csv`** | Detalle del consumo real de los usuarios en la plataforma. | `id`, `user_id`, `duration` (duración de llamadas), `length` (longitud de mensajes), `type`. |

## 🛠️ Etapas del Análisis
1. **Limpieza y Preparación:** Identificación y tratamiento de datos nulos o inconsistentes.
2. **Análisis Estadístico:** Evaluación de la distribución de los consumos mediante `.describe()`.
3. **Análisis de Outliers:** Identificación de patrones de uso extremo y justificación de negocio para su permanencia.
4. **Segmentación de Clientes:** Clasificación en grupos de uso (*Bajo uso*, *Uso medio*, *Alto uso*) aplicando lógica condicional en Pandas.
5. **Conclusiones Ejecutivas:** Elaboración de recomendaciones comerciales para stakeholders.

## 🚀 Cómo ejecutar el notebook
1. Descarga el archivo `.ipynb` de este repositorio.
2. Súbelo a Google Colab o abre tu entorno local de Jupyter Notebook.
3. Asegúrate de cargar el archivo `usage.csv` en el mismo directorio antes de ejecutar las celdas.
