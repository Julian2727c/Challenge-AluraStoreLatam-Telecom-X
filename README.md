🚀 Telecom Churn Insight: Análisis de Evasión de Clientes
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</p>

📌 Resumen del Proyecto
Este proyecto analiza el comportamiento de los clientes de una empresa de telecomunicaciones para predecir y entender la evasión (Churn). Transformamos datos complejos de una API en estrategias de negocio accionables.

🛠️ El Pipeline de Datos
Haz clic en los apartados para ver los detalles técnicos de cada fase:

<details>
<summary><b>1. Extracción y Limpieza (ETL) 📥</b></summary>

Desafío: Los datos venían en un JSON con estructuras anidadas.

Solución: Implementamos pd.json_normalize() para aplanar la información y generar un DataFrame de 21 columnas limpias.

Conversión: Transformamos TotalCharges de texto a float, manejando valores nulos con errors='coerce'.

</details>

<details>
<summary><b>2. Ingeniería de Variables ⚙️</b></summary>

Cuentas Diarias: Creamos una nueva métrica para entender el gasto diario del cliente.

Estandarización: Tradujimos todo el dataset al español para facilitar la comunicación con stakeholders no técnicos.

Binarios: Convertimos columnas de "Sí/No" en 1/0 para habilitar el análisis matemático.

</details>

<details>
<summary><b>3. Análisis Visual (EDA) 📊</b></summary>

Heatmaps: Para encontrar qué variables "mueven la aguja" del Churn.

Boxplots: Para comparar el gasto de los que se van vs. los que se quedan.

</details>

