# Análisis de Finanzas Personales y Presupuesto

Este proyecto es un **dashboard de análisis financiero** creado para evaluar mis finanzas personales con respecto a mis objetivos y presupuesto. El informe se centra en métricas clave como mis ingresos, gastos, utilidad y saldo, proporcionando una visión clara de mi salud financiera.

---

### Metodología del Análisis

Para este informe, se siguieron los pasos del ciclo de vida del análisis de datos utilizando **Power BI**:

1.  **Extracción, Transformación y Carga (ETL):** Los datos de mis transacciones financieras y mis objetivos presupuestarios fueron procesados con **Power Query**. Se crearon relaciones entre los datos para permitir la comparación del rendimiento.
2.  **Modelado de Datos:** Se estableció un modelo de datos robusto con relaciones entre las tablas de datos reales y las de presupuesto, optimizando los cálculos.
3.  **Análisis y DAX:** Se crearon medidas **DAX** clave para calcular el porcentaje de cumplimiento de mis metas y presupuestos, la utilidad y el saldo, permitiendo la comparación directa del rendimiento.

---

### Dashboard y Visualizaciones

El dashboard principal se compone de cuatro tarjetas de indicadores clave de rendimiento (KPIs), diseñadas para ofrecer una visión rápida y clara de mi desempeño financiero.

<img width="748" height="419" alt="image" src="https://github.com/user-attachments/assets/a3b48a1b-75af-4ac7-8d67-f84c002e17a2" />
<img width="816" height="439" alt="image" src="https://github.com/user-attachments/assets/cd77bd1d-75e7-4707-9910-da7859a4f3a0" />
<img width="799" height="413" alt="image" src="https://github.com/user-attachments/assets/aac0af4d-6dec-4156-9720-80c385cf6be8" />
<img width="796" height="415" alt="image" src="https://github.com/user-attachments/assets/16dfc052-87e2-44ba-bca3-be432421d052" />
<img width="799" height="413" alt="image" src="https://github.com/user-attachments/assets/5d8df4b0-306e-4003-8f20-694ce04529a1" />
<img width="796" height="417" alt="image" src="https://github.com/user-attachments/assets/4392cddf-ca01-4c88-ad29-b8a5c0635e48" />
<img width="797" height="415" alt="image" src="https://github.com/user-attachments/assets/c5bdabfe-6b7f-46fb-9405-2e175275ee9a" />
<img width="801" height="416" alt="image" src="https://github.com/user-attachments/assets/bb5a7926-a4c5-4aab-9a39-bd07221da446" />


* **KPI de Ingresos:** Muestra el rendimiento de mis ingresos reales ($21.183) frente a la meta ($21.000), con un 101% de cumplimiento.
* **KPI de Gastos:** Compara mis gastos reales ($14.599) con el presupuesto ($14.900), con un 98% de cumplimiento, lo que indica un control efectivo de los gastos.
* **KPI de Utilidad:** Muestra que mi utilidad real ($6.584) ha superado la utilidad esperada ($6.100) en un 108%, demostrando una buena rentabilidad personal.
* **KPI de Saldo:** El saldo, que representa el flujo de caja, se encuentra en un estado crítico con un cumplimiento negativo (-51%), lo que sugiere un desafío en el flujo de caja a pesar de los buenos ingresos y la utilidad.

El dashboard también incluye filtros por año y mes, permitiendo un análisis dinámico del desempeño a lo largo del tiempo.

---

### Conclusiones y Recomendaciones

El análisis de estos indicadores revela varias conclusiones importantes para la gestión de mis finanzas personales:

* **Rendimiento Sólido:** Mis ingresos y mi utilidad están superando las expectativas. Esto es una señal de que mis esfuerzos de gestión financiera están dando buenos resultados.
* **Control de Gastos:** He logrado mantener mis gastos por debajo del presupuesto.
* **Alerta de Flujo de Caja:** El saldo negativo es un indicador crítico que requiere una investigación inmediata. Se necesita un análisis más detallado del flujo de caja para identificar las causas subyacentes y tomar medidas correctivas.

---

### Archivos del Proyecto

* **`[reporte-finanzas-personales.pbix](https://app.powerbi.com/groups/me/reports/e1df85b7-5a45-4cd6-91e1-4d18cc44f83d?ctid=312d334d-75c2-4f23-80af-db347d214188&pbi_source=linkShare)`**: El archivo de Power BI con el modelo de datos y el informe interactivo.
* **Aviso**: Los datos utilizados en este proyecto son ficticios y solo tienen fines de demostración. El enfoque principal es mostrar mi proceso de análisis de datos financieros.
