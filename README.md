# TelecomX_LATAM

## Descripción:
En este proyecto se recopilaron, procesaron y analizaron los datos de un archivo en formato JSON que contiene información sobre deserción de clientes de la empresa TelecomX_LATAM. Utilizando Python y sus principales bibliotecas se extrajo información que nos permita comprender los factores con mayor influencia el la deserción de los clientes. A partir del análisis realizado, se hicieron recomendaciones para el desarrollo de estrategias que reduzcan el número de cancelaciones de la empresa TelecomX_LATAM y para contribuir a que el equipo de Data Science pueda avanzar en modelos predictivos.

## Tabla de contenidos del proyecto:
1. Extracción.
2. Transformación.
3. Carga y Análisis.
   * Distribución de cancelaciones.
   * Distribución por género.
   * Distribución de cancelaciones por edad.
   * Distribución de cancelaciones por tipo de contrato.
   * Distribución de cancelaciones por método de pago.
   * Distribución de cancelaciones por tipo de servicio de internet.
   * Distribución de cancelaciones por tipo de facturación.
   * Distribución de cancelaciones por costo mensual.
   * Distribución de cancelaciones por tipo de contrato.
4. Informe Final.
   * Introducción.
   * Limpieza y tratamiento de datos.
   * Conclusiones e insights.
   * Recomendaciones estratégicas.

## Principales librerías utilizadas:
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Plotly.

## Hallazgos:
* Cancelación por tipo de contrato: Como podemos ver, los clientes con contratos mes a mes representan un riesgo considerablemente mayor de cancelación (23.54%) VS los clientes con contratos a uno (2.36%) o dos años (0.68%).
<img width="800" height="500" alt="imagen" src="https://github.com/user-attachments/assets/81503a3b-cf73-46ae-aa73-2f6cf98783fc" />

* Cancelación por tipo de servicio de internet: La gráfica muestra que los clientes con internet de Fibra óptica tienen una deserción mayor (18.44%) en comparación a aquellos con DSL (6.53%) o a aquellos que no tienen servicio de internet con la empresa (1.61%)
<img width="800" height="500" alt="imagen" src="https://github.com/user-attachments/assets/85eecd8f-474c-4dcd-a8bc-39fa7407a48f" />

* Cancelación por costo mensual: Los clientes que pagan costos mensuales más elevados son aquellos que terminan cancelando sus servicios.
<img width="540" height="394" alt="imagen" src="https://github.com/user-attachments/assets/19316961-e61a-4cbb-b470-0cd8bf87e588" />

* Estos factores, aunados a las cancelaciones por tipos de facturación, método de pago y método de facturación se traducen en cancelaciones tempranas por parte de los clientes.

## Recomendaciones hechas:
* Migración a contratos de uno o 2 años.
* Incentivar los pagos automáticos.
* Mejora en la calidad de servicios y atención a cliente.
* Desarrollo de modelos predictivos.

## Autor:
Oscar Hernández Hernández
Data Scientist en desarrollo.
Proyecto desarrollado como parte de la formación en Data Science de Alura LATAM y ORACLE.
