Challenge-Alura-Store
<h1 align="center"> Challenge-Alura-Store </h1>  

# 🏪 Análisis de Ventas — *Alura Store*

![Python](https://img.shields.io/badge/Python-3.12.12-blue?logo=python)
![Status](https://img.shields.io/badge/Estado-Finalizado-success)
![Made with](https://img.shields.io/badge/Hecho%20con-Pandas%20|%20Matplotlib%20|%20Geopandas-blueviolet)

---

## 📋 Tabla de contenidos
1. [📖 Descripción](#-descripción)
2. [🏁 Estado del proyecto](#-estado-del-proyecto)
3. [⚙️ Desarrollo del proyecto](#️-desarrollo-del-proyecto)
4. [✅ Tecnologías utilizadas](#-tecnologías-utilizadas)
5. [📊 Resultados destacados](#-resultados-destacados)
6. [📈 Conclusiones](#-conclusiones)
7. [👤 Autor](#-autor)

---

## 📖 Descripción
Durante este desafío se analizaron datos de **ventas, rendimiento y reseñas** de las cuatro tiendas de *Alura Store*.  
El objetivo fue ayudar al **Sr. Juan** a determinar **cuál es la tienda menos eficiente**, basándose en un análisis integral de indicadores comerciales, logísticos y de satisfacción del cliente.

---

## 🏁 Estado del proyecto
:checkered_flag: **Proyecto finalizado** :checkered_flag:

---

## ⚙️ Desarrollo del proyecto

1. **Recolección y preparación de datos:**  
   Se importaron los archivos de ventas de las cuatro tiendas junto con las librerías necesarias para el análisis.

2. **Análisis exploratorio (EDA):**  
   Se inspeccionaron los DataFrames de cada tienda para comprender la estructura y consistencia de los datos.

3. **Análisis de facturación:**  
   Se calculó el **ingreso total por tienda** mediante una función y se representó con un **gráfico de barras** comparativo.

4. **Análisis de ventas por categoría:**  
   Se ordenaron las categorías de productos según las ventas y se utilizaron **gráficos de torta** para visualizar la distribución.

5. **Evaluación de la calificación del cliente:**  
   Se calculó la **calificación promedio** por tienda y se representó mediante **gráficos de dispersión**, observando la variabilidad entre sucursales.

6. **Productos más y menos vendidos:**  
   Se identificó el **Top 3** de productos más y menos demandados mediante funciones específicas, visualizados con **gráficos de barras horizontales**.

7. **Costo de envío:**  
   Se determinó el **costo de envío promedio** por tienda y se representó con un **histograma** para evaluar la distribución de costos.

8. **Desempeño geográfico:**  
   Usando **coordenadas geográficas (latitud y longitud)**, se generaron **mapas de calor** con `geopandas`, `contextily` y `numpy`, para visualizar los ingresos y calificaciones por zona.

9. **Normalización y puntuación final:**  
   Se aplicó una **normalización** de datos y se definieron **ponderaciones** para cada criterio. Finalmente, se calculó una **puntuación global** para identificar la tienda menos eficiente.

10. **Conclusiones finales:**  
    Se exponen las recomendaciones basadas en los análisis anteriores, justificando **qué tienda debería vender el Sr. Juan** para iniciar su nuevo emprendimiento.

---

## ✅ Tecnologías utilizadas

### 💬 Lenguaje
- **Python**

### 📚 Librerías principales
- `pandas`
- `numpy`
- `matplotlib`
- `geopandas`
- `contextily`
- `ctypes`

### 🧩 Entorno de desarrollo
- **Google Colab**

---

## 📊 Resultados destacados

- <img width="756" height="549" alt="grafico_ingresos_ventas" src="https://github.com/user-attachments/assets/f5f74ce8-7502-48f1-a353-b176d355e9e2" />
- <img width="1004" height="1089" alt="heatmap_tienda1" src="https://github.com/user-attachments/assets/21b14d54-b135-433f-9de7-caceeb1f90ca" />
- <img width="1193" height="808" alt="Histograma_costo_envio" src="https://github.com/user-attachments/assets/b4c79909-99aa-4a48-bd88-4bb9254cdf59" />

---

## 📈 Conclusiones
- **Tienda 4** presentó el menor desempeño global tras evaluar los ingresos, calificaciones, diversidad de ventas y costos logísticos.  
- Se recomienda priorizar la venta de esta sucursal para optimizar la rentabilidad general de la empresa.  
- Las demás tiendas demostraron **mayor estabilidad comercial y satisfacción del cliente**.

---

## 👤 Autor
**[Jonathan Marino](https://github.com/JonathanMarino)**  
📅 Año: 2025  
📍 Proyecto educativo — *Análisis de datos con Python*  

