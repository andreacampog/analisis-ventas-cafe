🍵 Proyecto: Análisis de Ventas de un Café ☕️

✨ Descripción

Este proyecto se enfoca en analizar los datos de ventas de un café utilizando Python y bibliotecas populares como pandas, matplotlib y numpy. El objetivo principal es realizar limpieza de datos y un análisis exploratorio de datos (EDA) para obtener insights valiosos sobre el negocio. 📊💡

Los datos utilizados provienen de Kaggle.

🚀 Estructura del Proyecto

📂 analisis-ventas-cafe/├── 📁 data/ → Contiene los archivos de datos originales y limpios 📂.│   ├── dirty_cafe_sales.csv → Archivo de datos originales sin limpiar.│   ├── clean_cafe_sales.csv → Archivo de datos después de la limpieza.├── 📁 imagenes/ → Almacena los gráficos generados durante el análisis 📊.├── 📄 ventas-cafe.ipynb → Notebook con todo el análisis paso a paso.├── 📄 README.md → Documentación del proyecto 📃.├── 📄 LICENSE → Licencia del repositorio 🔖.

📦 Instalación y Configuración del Entorno

Para ejecutar el análisis en tu máquina, se recomienda crear un entorno virtual con conda y asegurarse de instalar las dependencias necesarias.

1️⃣ Crear el entorno con conda:

conda create --name cafe-ventas python=3.9

2️⃣ Activar el entorno:

conda activate cafe-ventas

3️⃣ Instalar las bibliotecas necesarias:

pip install pandas matplotlib numpy jupyter

4️⃣ Abrir el Jupyter Notebook:

jupyter notebook

🔍 Pasos Realizados

1️⃣ Carga y Exploración de Datos 📥

Inspección inicial para detectar problemas de formato, valores nulos o inconsistencias.

Análisis de tipos de datos y necesidad de transformaciones.

2️⃣ Limpieza de Datos 🧹

Corrección de valores incorrectos o inconsistentes (ej. "ERROR", "UNKNOWN").

Eliminación de duplicados y manejo adecuado de valores nulos.

Conversión de tipos de datos (fechas, valores numéricos, etc.).

Creación del archivo clean_cafe_sales.csv con los datos procesados.

3️⃣ Análisis Exploratorio de Datos (EDA) 📊

Patrones de ventas: Identificación de los productos más vendidos. 🍰🥤

Ingresos: Evaluación por ubicación y métodos de pago. 💳💸

Tendencias temporales: Ventas por día de la semana y mes del año. 📅

Distribución del ticket promedio y su variación en el tiempo.

Rentabilidad de productos: Análisis de ingresos generados por categoría.

4️⃣ Visualización de Datos 📈

Gráficos de barras y circulares para representar patrones clave.

Boxplots para analizar distribuciones de ventas y ticket promedio.

Uso de colores y diseños adecuados para mejorar la interpretación.

🛠️ Herramientas Utilizadas

🐍 Python

🧑‍💻 Pandas

📊 Matplotlib

🔢 Numpy

📌 Cómo Usar este Proyecto

1️⃣ Clona este repositorio:

git clone https://github.com/andreacampog/analisis-ventas-cafe.git

2️⃣ Abre ventas-cafe.ipynb en Jupyter Notebook o Google Colab.3️⃣ Sigue el análisis paso a paso o ejecuta las celdas para generar los gráficos.

🌟 ¡Gracias por revisar este proyecto! 🎉