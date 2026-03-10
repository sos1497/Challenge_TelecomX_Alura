# Challenge_TelecomX_Alura

🎯 Objetivo del Proyecto
Este proyecto forma parte de un desafío de Alura Latam, donde asumí el rol de Analista de Datos para la empresa "Telecom X". El objetivo principal fue identificar por qué el 25.7% de los clientes están cancelando sus servicios y proponer estrategias basadas en datos para mejorar la retención.

🛠️ Tecnologías Utilizadas
Lenguaje: Python 

Librerías: Pandas, NumPy, Matplotlib y Seaborn.

Entorno: Google Colab.

🧹 Proceso de Data Wrangling
El dataset presentaba retos estructurales importantes que fueron resueltos mediante:

Normalización de JSON: Desanidado de variables complejas en un DataFrame plano.

Limpieza de Datos: Tratamiento de valores nulos y eliminación de ruido estadístico (valores inconsistentes).

Feature Engineering: Creación de variables como Cargos_Diarios y Evasion_Binario para profundizar en el análisis financiero.

📈 Hallazgos Clave (Insights)
El Riesgo del "Mes a Mes": Los clientes con contratos mensuales son el grupo con mayor tasa de fuga.

Pérdida de Alto Valor: Los Boxplots demostraron que los clientes que evaden suelen ser los que tienen cargos mensuales más altos (rango $70 - $100).

La Ventana de Lealtad: La mayor densidad de cancelaciones ocurre antes de los primeros 12 meses de permanencia.

Falla en Fibra Óptica: Se detectó una correlación inesperada de bajas en usuarios de Fibra Óptica, sugiriendo problemas de precio o calidad técnica.
