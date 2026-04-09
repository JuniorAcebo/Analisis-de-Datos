# 📦 Análisis de un Sistema de Pedidos Internacionales

## Descripción

Este proyecto consiste en el análisis de un dataset de pedidos internacionales compuesto por 13 tablas relacionadas entre sí, que incluyen información sobre clientes, productos, proveedores, inventario, almacenes, pedidos, pagos, envíos y empleados. El objetivo fue unificar e integrar toda esta información dispersa para obtener una visión clara del ciclo completo de compra y venta, apoyando la toma de decisiones estratégicas. El análisis fue realizado el 28 de septiembre de 2025.

## Tecnologías Utilizadas

| Tecnología | Uso |
|---|---|
| Python | Lenguaje principal de análisis |
| Jupyter Notebook | Entorno de desarrollo y documentación |
| Pandas | Manipulación y limpieza de datos |
| NumPy | Operaciones numéricas |
| Matplotlib | Generación de visualizaciones |
| Seaborn | Visualizaciones estadísticas avanzadas |
| SciPy | Función de distribución empírica |
| SQLite | Base de datos `international_orders.sqlite` |

## Dataset

El dataset está compuesto por **13 archivos CSV** y una base de datos SQLite con las siguientes tablas principales:

- Productos (500 registros)
- Categorías de productos (20 registros)
- Proveedores (40 registros)
- Inventario (2.400 registros)
- Almacenes (12 registros)
- Clientes (211 registros)
- Direcciones de clientes (418 registros)
- Pedidos (1.000 registros)
- Elementos del pedido (12.000 líneas)
- Pagos (921 registros)
- Envíos (741 registros)
- Eventos de envío (2.400 registros)
- Empleados (80 registros)

## Habilidades Demostradas

- Integración y limpieza de datos provenientes de múltiples fuentes
- Análisis exploratorio de datos (EDA)
- Generación de visualizaciones: histogramas, diagramas de caja, matrices de correlación, series de tiempo y diagramas de dispersión
- Ingeniería de características y construcción de indicadores de negocio
- Análisis logístico de tiempos de entrega y retrasos
