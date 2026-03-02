#  Análisis de Tiendas — AluraStore Latam

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=flat&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completado-success?style=flat)

---

##  Descripción del Proyecto

Este proyecto consiste en un **análisis exploratorio de datos (EDA)** aplicado al portafolio comercial del Sr. Juan, compuesto por cuatro tiendas de retail. El objetivo principal es evaluar el desempeño de cada tienda a través de métricas clave de negocio y emitir una **recomendación estratégica fundamentada en datos** sobre cuál tienda debería venderse.

El análisis abarca un total de **~9.435 transacciones** distribuidas entre las cuatro tiendas, evaluando las siguientes dimensiones:

-  **Ingresos totales** generados por cada tienda
-  **Categorías de productos** más y menos vendidas
-  **Calificaciones promedio** de satisfacción del cliente
-  **Productos** con mayor y menor rotación de ventas
-  **Costo promedio de envío** por tienda

Al final del análisis, se elaboró un **informe de conclusiones** con la recomendación de vender la **Tienda 4**, sustentada en evidencia cuantitativa extraída de los datos.

---

## 🛠️ Tecnologías Utilizadas

| Herramienta | Uso |
|-------------|-----|
| **Python 3.10+** | Lenguaje principal del análisis |
| **Pandas** | Manipulación y análisis de datos |
| **Matplotlib** | Visualización de datos y gráficos |
| **Google Colab** | Entorno de ejecución del notebook |

---

##  Estructura del Proyecto

```
 Challengue-tienda-de-cadena/
├──  AluraStore_Analisis.ipynb   # Notebook principal con todo el análisis
└──   README.md                   # Este archivo

```

---

##  Cómo Ejecutar el Proyecto

1. Abre el notebook directamente en **Google Colab**:
   - Ve a [colab.research.google.com](https://colab.research.google.com)
   - Selecciona **Archivo → Abrir notebook → GitHub o subir archivo**
   - Carga el archivo `AluraStore_Analisis.ipynb`

2. Ejecuta las celdas en orden secuencial con `Shift + Enter` o usa **Entorno de ejecución → Ejecutar todo**.

3. Los datos se cargan directamente desde URLs públicas, por lo que **no se requiere descarga adicional de archivos**.

---

##  Resultados Principales

| Tienda | Ingreso Total | Rating Prom. | Costo Envío Prom. |
|--------|--------------|-------------|-------------------|
| Tienda 1 | $1.150.880.400 | 3.98 | $26.019 |
| Tienda 2 | $1.116.343.500 | 4.04 | $25.216 |
| Tienda 3 | $1.098.019.600 | 4.05 | $24.806 |
| **Tienda 4** | **$1.038.375.700** | 4.00 | **$23.459** |

>  **Conclusión:** Se recomienda vender la **Tienda 4** por presentar el menor ingreso total del portafolio, el peor desempeño en categorías estratégicas como Electrodomésticos e Instrumentos musicales, y por no lograr convertir su ventaja logística (menor costo de envío) en mayores ventas.

---

##  Juan Camilo Mantilla Ramirez

Desarrollado como parte del challenge de análisis de datos de **Alura Latam**.
