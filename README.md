📊 Telecom X: Análisis de Evasión de Clientes (Churn)
📝 Descripción del Proyecto
Este proyecto aborda uno de los desafíos más críticos en el sector de las telecomunicaciones: la evasión de clientes (Churn). A través de un análisis exploratorio de datos (EDA) sobre la base de datos de Telecom X, se identificaron patrones de comportamiento que llevan a los usuarios a cancelar sus servicios.

El objetivo principal es transformar datos crudos en insights accionables que permitan al equipo de marketing y fidelización reducir la tasa de abandono, la cual se sitúa actualmente en un 25.7%.

🛠️ Tecnologías y Librerías
Python 3.x

Pandas & NumPy: Procesamiento y limpieza de datos JSON anidados.

Matplotlib & Seaborn: Visualización de datos estadística y comparativa.

Google Colab: Entorno de desarrollo.

🔍 Hallazgos Principales (Insights)

1. Perfil de Riesgo: La Fibra Óptica
A pesar de ser un servicio premium, los clientes de Fibra Óptica presentan una tasa de evasión significativamente mayor que los de DSL. El análisis de densidad muestra que los clientes que pagan entre $70 y $110 USD son los más propensos a irse.

2. El Contrato "Mes a Mes"
Existe una correlación directa entre el tipo de contrato y la fuga. Los contratos mensuales tienen una barrera de salida casi inexistente, concentrando la mayoría de las cancelaciones.

3. Fricción en Métodos de Pago
Los usuarios que utilizan Electronic Check (método manual) tienen una tasa de abandono mucho más alta que aquellos con pagos automáticos. Cada factura manual es una oportunidad para que el cliente revalúe su contrato.

📁 Estructura del Repositorio
Analisis_Evasion_TelecomX.ipynb: Notebook principal con todo el proceso de ETL y EDA.

README.md: Descripción del proyecto.

TelecomX_Data.json: Dataset original (o enlace a la fuente).

🚀 Cómo Ejecutar este Proyecto
Clona el repositorio:

Bash

git clone https://github.com/tu-usuario/telecom-x-churn.git
Instala las dependencias necesarias:

Bash

pip install pandas numpy matplotlib seaborn
Abre el archivo .ipynb en Jupyter Notebook o Google Colab.

Ejecuta todas las celdas para visualizar los gráficos y el informe final.

💡 Recomendaciones Estratégicas
Para mitigar la evasión, se recomienda a Telecom X:

Fomentar la Automatización: Ofrecer beneficios a clientes que cambien a pagos automáticos.

Incentivar la Permanencia: Crear promociones para migrar a clientes "Mes a Mes" hacia contratos anuales.

Onboarding Crítico: Implementar campañas de éxito del cliente durante los primeros 6 meses, que es donde ocurre el mayor volumen de fugas.

👩‍💻 Autor
Tu Nombre - LinkedIn - Portfolio
