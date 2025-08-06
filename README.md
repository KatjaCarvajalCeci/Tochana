# 📊 Análisis de la demanda de talles y comportamiento de compra por provincias - Tochana

## 🗓 Fecha
**Marzo-Julio 2025**

## 👩‍🎓 Autora
**Carvajal Ceci, Katja**

---

## 📚 Dataset
- **Ventas Tochana (MercadoLibre):** junio 2023 a junio 2024  
- **Clientes del sitio web:** desde inicio de venta online (2021) hasta abril 2025

---

## 🏷 Origen de los datos
La información utilizada en este análisis proviene de:
- **MercadoLibre:** ventas de la marca argentina de indumentaria femenina **Tochana**, reconocida por ofrecer una amplia curva de talles (del M al 5XL) y cubrir un segmento poco explorado en el mercado local.
- **Sitio web Tochana:** base de datos de contactos y localidades de los compradores históricos.

El análisis abarca exclusivamente transacciones dentro del territorio argentino.

---

## ❓ Preguntas de interés
- ¿Cuál es el talle más vendido a nivel nacional?
- ¿Existen diferencias significativas en la venta de talles grandes (2XL, 3XL, 4XL y 5XL) y pequeños (M, L, XL)?
- ¿Qué provincias presentan la mayor cantidad de ventas?
- ¿Las zonas con más ventas también tienen mayores ingresos totales?
- ¿Hay diferencias en la demanda de talles grandes o pequeños según la provincia?
- ¿Dónde se observa la mayor fidelidad de los clientes (frecuencia de compra alta)?
- ¿Qué diferencias hay entre las zonas con mayores ventas en la web y en MercadoLibre?

---

## 💡 Hipótesis
✅ **Preferencia por talles grandes:**  
Dada la limitada oferta de talles grandes en el mercado y la propuesta de Tochana, se espera que los talles 2XL, 3XL, 4XL y 5XL sean los más demandados, frente a los talles más pequeños que compiten con mayor cantidad de marcas.

✅ **Variación regional:**  
Variación regional de la demanda: Se espera que la demanda de los productos de la marca Tochana en las provincias del interior muestren mayores tasas de fidelidad por menor competencia local


---

## 🔍 Insights principales
👍 **1. Alta fidelidad en ciertas provincias**  
Se identificaron Tucumán, Neuquén, Santa Cruz, Misiones y Mendoza como provincias donde los clientes realizan compras con mayor frecuencia. Esto sugiere oportunidades para expandir el mercado hacia nuevos compradores en esas zonas, aprovechando la base ya fidelizada.

👍 **2. Provincias con alta frecuencia ≠ mayores ingresos totales**  
Buenos Aires y CABA concentran los ingresos totales más altos, pero no la frecuencia promedio de compra. Esto revela un potencial para estrategias de recompra y fidelización que incrementen el ticket recurrente.

👍 **3. Fuerte preferencia por talles grandes**  
Los talles más vendidos son los grandes (2XL, 3XL, 4XL, 5XL). Es un dato crucial para orientar la producción, ajustar el inventario y enfocar campañas publicitarias.

---
🔹 **Modelos de Aprendizaje No Supervisado**

Se aplicaron técnicas de clustering (K-Means y Clustering Jerárquico) con el objetivo de segmentar clientes según variables clave como:

Frecuencia de compra

Ticket promedio

Talles adquiridos

Estas segmentaciones permitieron identificar grupos con comportamientos de compra similares y revelar oportunidades de negocio, como la demanda de talles grandes o la fidelidad en ciertas provincias.

🔹 **Modelos de Aprendizaje Supervisado**
Se implementó un modelo de árbol de decisión para clasificar clientes como valiosos o no valiosos, en función de:

Frecuencia de compra

Ticket promedio

Para mejorar la capacidad predictiva del modelo, se utilizó validación cruzada (5-fold) y se optimizaron los hiperparámetros con GridSearchCV.
El resultado fue un modelo interpretable, con buen rendimiento, que permite anticipar qué clientes tienen mayor potencial económico.

---

## 🚀 Cómo abrir el análisis
📔 Podés explorar el notebook directamente en Google Colab haciendo clic en el siguiente botón:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KatjaCarvajalCeci/ProyectoDS_Parte2_CarvajalCeciKatja/blob/main/tochana_analisis.ipynb)

---

✍️ _Análisis realizado por **Katja Carvajal Ceci**, Julio 2025._
