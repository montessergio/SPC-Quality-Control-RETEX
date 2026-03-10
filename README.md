### Sistema de Control Estadístico de Procesos (SPC) - Proyecto RETEX 🧶
Este repositorio contiene un sistema de monitoreo de calidad desarrollado en Power BI para la empresa textil RETEX. El proyecto aplica metodologías de Control Estadístico de Procesos (SPC) para garantizar la estabilidad y capacidad en la producción de pacas de fibra.

<img width="1373" height="771" alt="image" src="https://github.com/user-attachments/assets/19a9ee55-3164-4b73-878e-614f66325218" />

**📊 Descripción del Dashboard**
El dashboard integra tres niveles de análisis crítico para la toma de decisiones:
1. Control de Atributos (Gráfico p)
Monitoreo de la pureza de la fibra, detectando variaciones fuera de los límites de control establecidos.
2. Control de Variables (Gráficos X¯-R)
Seguimiento del peso promedio de las pacas y su variabilidad interna para asegurar la precisión del pesaje.
3. Análisis de Capacidad
Evaluación de los índices Cp y Cpk para determinar si el proceso cumple con las especificaciones del cliente (98).

**🚀 Indicadores Clave de Desempeño (KPIs)**
Basado en el análisis de 30 lotes de producción, se obtuvieron los siguientes resultados de capacidad:
•	Media del Proceso (μ): 98.2%
•	Desviación Estándar (σ): 0.5%
•	Índice Cp: 1,33
o	Indica que el proceso tiene el potencial de cumplir con las especificaciones.
•	Índice Cpk: 1,20
o	Indica que el proceso es capaz, aunque presenta un ligero sesgo hacia el límite superior.

**🛠️ Herramientas Utilizadas**
•	Power BI Escritorio: Modelado de datos, creación de medidas DAX y visualización dinámica.
•	Excel: Fuente de datos y estructuración de parámetros de control.
•	Estadística Industrial: Cálculo de límites de control (LCS, LCI) y análisis de capacidad del proceso.
________________________________________
📂 Estructura del Repositorio
Para facilitar la revisión, los archivos se encuentran organizados de la siguiente manera:
├── Retex.pbix # Archivo fuente del dashboard interactivo en Power BI ├── Retex.xlsx # Base de datos con mediciones de peso y pureza ├── Retex.pdf # Reporte técnico final con análisis detallado └── README.md # Documentación principal del proyecto
