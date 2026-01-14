# Análisis de Negocio: Optimización de Marketing para Showz

Este repositorio contiene un análisis exhaustivo enfocado en la optimización de los gastos de marketing para **Showz**, una empresa dedicada a la venta de entradas de eventos. A través de un análisis de datos basado en cohortes y métricas de negocio, se busca identificar patrones de comportamiento y rentabilidad de los usuarios.

## Objetivo del Proyecto

En este análisis, el objetivo es determinar la eficiencia de las inversiones en marketing mediante la investigación de:
* El comportamiento de uso del servicio por parte de los clientes.
* El ciclo de compra (cuándo inician su primera compra).
* La rentabilidad por cliente (**LTV** - Customer Lifetime Value).
* El punto de equilibrio entre los ingresos y los costos de adquisición (**CAC** - Customer Acquisition Cost).

## Datos Utilizados

El análisis se basa en tres conjuntos de datos clave del periodo 2017-2018:
1.  **Visitas**: Registros detallados de sesiones en el servidor (dispositivo, fuente de tráfico, tiempos de inicio y fin).
2.  **Pedidos**: Historial de transacciones realizadas por los usuarios.
3.  **Gastos**: Estadísticas de inversión en marketing desglosadas por fuente y fecha.

## Resumen del Análisis

El proyecto sigue una estructura lógica de análisis de datos:
*   **Procesamiento de Datos**: Limpieza, conversión de tipos y optimización de memoria.
*   **Análisis Exploratorio (EDA)**: Análisis de usuarios activos (DAU, WAU, MAU) y métricas de retención.
*   **Cálculo de Métricas**:
    *   Generación de ingresos por cohorte.
    *   Cálculo de CAC por fuente.
    *   Análisis de ROI/ROMI para determinar la eficacia de cada canal.

## Conclusiones Principales

A lo largo de la investigación, se han identificado canales de marketing con diferentes niveles de efectividad, observando en qué momento las cohortes comienzan a ser rentables para el negocio y recomendando ajustes en la distribución del presupuesto para maximizar el retorno de inversión.

---

### Tecnologías Utilizadas
*   Python 3.x
*   Pandas (Análisis y manipulación de datos)
*   Matplotlib & Seaborn (Visualización)
*   Análisis de Cohortes (Cálculo de LTV y Retención)
