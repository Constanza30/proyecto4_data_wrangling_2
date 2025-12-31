# 🛒 Proyecto 4: Análisis de Comportamiento de Compra en Instacart (Python)

## 📌 Descripción
El presente repositorio se enfoca en el análisis del comportamiento de compra de clientes de Instacart mediante limpieza de datos, análisis exploratorio y métricas de recompra.

El objetivo es comprender cómo compran los usuarios, qué productos se repiten con mayor frecuencia y qué patrones de consumo se observan a nivel producto y cliente.

---

## 🎯 Objetivos del análisis
- Analizar cuántos artículos compran los clientes por pedido y su distribución.
- Identificar los productos con mayor frecuencia de recompra.
- Calcular la tasa de repetición:
  - Por producto
  - Por cliente
- Identificar los productos que los clientes agregan primero a sus carritos.
- Extraer conclusiones de negocio basadas en patrones de consumo.

---

## 🧼 Preparación de datos
- Limpieza y validación de datos inconsistentes y valores atípicos.
- Uso de `merge`, `groupby`, `value_counts` y funciones agregadas.
- Creación de métricas de repetición a partir de variables binarias (`reordered`).
- Verificación de distribuciones y coherencia de los datos.

---

## 🔍 Análisis clave
- La mayoría de los pedidos contienen entre 1 y 9 artículos, con una caída exponencial a medida que aumenta el número de productos.
- Los productos más reordenados corresponden principalmente a frutas y vegetales orgánicos.
- Existen productos con altas tasas de recompra, mientras que otros son comprados solo una vez.
- Algunos clientes presentan una alta fidelidad, reordenando hasta el 80–90% de los productos que compran.
- Los artículos añadidos primero al carrito coinciden en gran medida con los productos más populares y reordenados.

---

## 📈 Conclusiones
- Los patrones de recompra reflejan hábitos de consumo recurrentes y preferencia por productos frescos y orgánicos.
- La tasa de repetición es una métrica clave para identificar productos estratégicos y clientes fieles.
- El análisis permite generar insights útiles para:
  - Estrategias de fidelización
  - Optimización de inventario
  - Recomendaciones personalizadas

---

## 🛠️ Tecnologías utilizadas
- Python
- Pandas
- Jupyter Notebook
- Análisis exploratorio de datos (EDA)
- Visualización con Matplotlib
