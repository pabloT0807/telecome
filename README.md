# telecome

📊 Análisis de Evasión de Clientes (Churn)
📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una empresa de telecomunicaciones para identificar patrones asociados a la evasión de clientes (churn).

A través de un proceso de limpieza de datos, transformación y análisis exploratorio, se buscan insights que ayuden a la empresa a reducir la pérdida de clientes y mejorar sus estrategias de retención.

🎯 Objetivos

Limpiar y preparar los datos para el análisis.

Analizar la distribución de clientes que cancelan y los que permanecen.

Identificar factores asociados al churn.

Generar recomendaciones basadas en datos.

🧰 Tecnologías utilizadas

Python 3

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook / Google Colab

📂 Estructura del proyecto
📁 churn-analysis
│
├── TelecomX_Data.json     # Dataset original
├── churn_analysis.ipynb   # Notebook con el análisis completo
└── README.md              # Descripción del proyecto
⚙️ Instalación y requisitos
1. Clonar el repositorio
git clone https://github.com/tu-usuario/churn-analysis.git
cd churn-analysis
2. Instalar dependencias
pip install pandas numpy matplotlib seaborn
▶️ Ejecución del proyecto

Abrir el notebook:

jupyter notebook churn_analysis.ipynb

Ejecutar las celdas en orden para reproducir el análisis.

🔄 Proceso realizado

Carga de datos desde archivo JSON.

Limpieza y tratamiento de valores nulos e inconsistencias.

Transformación de columnas anidadas.

Creación de la variable Cuentas_Diarias.

Análisis exploratorio:

Distribución de churn.

Churn por variables categóricas.

Churn por variables numéricas.

Generación de conclusiones y recomendaciones.

📊 Principales hallazgos

Los clientes con contratos mensuales presentan mayor tasa de evasión.

Los clientes nuevos tienen mayor probabilidad de cancelar.

Cargos mensuales altos están asociados con mayor churn.

💡 Recomendaciones

Incentivar contratos de mayor duración.

Implementar estrategias de retención en los primeros meses.

Ofrecer planes con mejor relación costo–beneficio.

👤 Autor

Tu nombre
Proyecto de análisis de datos / Data Engineering.

📜 Licencia

Este proyecto se puede utilizar con fines educativos y de aprendizaje.
