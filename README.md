# 🏪 Alura Store — Análisis de Rendimiento por Sucursal

> Challenge de Data Science | Alura LATAM

---

## 📋 Descripción del Proyecto

Este proyecto realiza un **análisis exploratorio de datos (EDA)** sobre las cuatro sucursales de **Alura Store** con el objetivo de evaluar su rendimiento comercial, logístico y de satisfacción al cliente. El análisis busca identificar qué tienda debería considerarse para cierre o venta, basándose en datos concretos.

---

## 🎯 Objetivo

Evaluar el rendimiento de cada sucursal de Alura Store y emitir una recomendación fundamentada en datos sobre cuál debería cerrarse o venderse.

---

## 📁 Estructura del Proyecto
```
Alura_store_challenge/
│
├── CHALLENGE_ALURA_STOREpynb.ipynb  # Notebook principal con el análisis completo
└── README.md
```

---

## 🗃️ Dataset

- **Fuente:** [Alura Cursos — GitHub](https://github.com/alura-es-cursos/challenge1-data-science-latam)
- **Formato:** 4 archivos CSV (uno por tienda)
- **Tiendas analizadas:** Tienda 1, Tienda 2, Tienda 3, Tienda 4

### Variables del Dataset

| Variable | Descripción |
|---|---|
| `Producto` | Nombre del producto vendido |
| `Categoría del Producto` | Categoría a la que pertenece el producto |
| `Precio` | Precio de venta del producto |
| `Costo de envío` | Costo logístico asociado al envío |
| `Calificación` | Puntuación de satisfacción del cliente (0–5) |

---

## 🔍 Análisis Realizado

### 1. 💰 Facturación por Tienda
Suma total de ingresos por precio de productos vendidos en cada sucursal.

### 2. 📦 Ventas por Categoría
Conteo de productos vendidos por categoría en cada tienda, identificando las categorías más y menos demandadas.

### 3. ⭐ Calificación Promedio
Promedio de la satisfacción de los clientes por tienda, en escala de 0 a 5.

### 4. 🏆 Productos Más y Menos Vendidos
Identificación de los productos con mayor y menor volumen de ventas en cada sucursal.

### 5. 🚚 Costo Promedio de Envío
Costo logístico promedio por tienda, analizado en relación con el volumen de facturación.

---

## 📊 Resultados

### Facturación y Costos de Envío

| Tienda | Facturación | Costo Promedio de Envío |
|---|---|---|
| Tienda 1 | $1,150,880,400 ⬆️ más alta | $26,018.61 ⬆️ más alto |
| Tienda 2 | $1,116,343,500 | $25,216.24 |
| Tienda 3 | $1,098,019,600 | $24,805.68 |
| Tienda 4 | $1,038,375,700 ⬇️ más baja | $23,472.48 ⬇️ más bajo |

> Se observa correlación directa entre facturación y costo de envío: mayor volumen de ventas implica mayor costo logístico.

### Visualizaciones Generadas
- 📊 Gráfico de barras: Facturación por tienda
- 📈 Gráfico de líneas: Nivel de satisfacción de clientes por tienda
- 📊 Gráfico de barras horizontales: Costos promedio de envío

---

## 💡 Conclusión y Recomendación

Tras el análisis de facturación, satisfacción, categorías de productos y costos logísticos, se concluye que la **Tienda 4** es la candidata recomendada para cierre o venta, al presentar:

- La **facturación más baja** de las cuatro sucursales
- El **menor volumen de ventas** en categorías clave
- Una relación costo-ingreso menos favorable comparada con el resto

---

## 🛠️ Tecnologías Utilizadas

- **Python 3**
- **Pandas** — Carga y análisis de datos
- **Matplotlib** — Visualizaciones
- **Google Colab** — Entorno de ejecución

---

## ▶️ Cómo Ejecutar

Abre el notebook directamente en Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luceroabanto04-commits/Alura_store_challenge/blob/main/CHALLENGE_ALURA_STOREpynb.ipynb)

Los datasets se cargan automáticamente desde GitHub, no necesitas descargar nada.

---

## 👩‍💻 Autora

**Lucero Abanto**  
Challenge Data Science — Alura LATAM
