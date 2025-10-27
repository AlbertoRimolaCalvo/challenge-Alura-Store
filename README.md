# challenge-Alura-Store
Análisis de desempeño de las tiendas de Alura Store para identificar cuál debería venderse. Incluye evaluación de ingresos, categorías, calificaciones, costos de envío y análisis geográfico con visualizaciones en Python (Pandas, Matplotlib).

# 🧾 Análisis de Desempeño de Tiendas — Alura Store

## 📘 Propósito del análisis
Este proyecto forma parte del **Challenge Data Science de Alura Latam** y tiene como objetivo apoyar al **Sr. Juan** en la decisión de **qué tienda de la cadena Alura Store debería vender** para iniciar un nuevo emprendimiento.  

A través del análisis exploratorio de datos (EDA), se evaluó el **rendimiento comercial, operativo y geográfico** de cuatro tiendas, con el fin de identificar aquella con menor eficiencia y recomendar una decisión sustentada en datos.

---

## 📊 Análisis y visualizaciones

El notebook incluye distintos pasos de análisis, apoyados con gráficos generados mediante **Pandas** y **Matplotlib**:

### 💰 Ingresos totales por tienda
Compara los ingresos totales generados por cada tienda, identificando la **Tienda 4** como la menos rentable.

> 📈 *Gráfico: Ingresos totales por tienda*

### 🛒 Categorías de productos más vendidas
Las categorías con mayor demanda corresponden a **Muebles** y **Electrónica**, mientras que *Artículos para el hogar* e *Instrumentos musicales* tienen menor rotación.

> 🧩 *Gráfico: Ventas por categoría (comparativo entre tiendas)*

### ⭐ Calificación promedio por tienda
Las calificaciones son similares entre tiendas, destacando la **Tienda 3 (4.05)** como la mejor valorada, y la **Tienda 1 (3.98)** como la menor.

> 🌟 *Gráfico: Valoración promedio por tienda*

### 📦 Productos más y menos vendidos
Se identificaron los productos líderes y de menor salida por tienda.  
Ejemplo:  
- Tienda 1 → *Armario* (más vendido) / *Auriculares con micrófono* (menos vendido)  
- Tienda 4 → *Cama box* (más vendido) / *Guitarra eléctrica* (menos vendido)

> 📊 *Gráfico: Top 5 productos más vendidos y Bottom 5 productos menos vendidos*

### 🚚 Costo de envío promedio
Se observan costos similares entre tiendas, siendo **Tienda 4** la que ofrece el **envío más económico**, aunque sin traducirse en mayor rentabilidad.

> 🟠 *Gráfico: Costo de envío promedio (gráfico de área)*

### 🌍 Análisis geográfico (extra opcional)
Se realizó un análisis geográfico de las ventas a partir de las coordenadas de latitud y longitud.  
Los gráficos muestran una **alta concentración de ventas en Bogotá, Medellín, Cali, Bucaramanga y Cartagena**, con fuerte **superposición entre tiendas**.  
La **Tienda 4** presenta **menor volumen** en casi todas las zonas, evidenciando **canibalización del mercado**.

> 🔹 *Gráfico: Distribución geográfica de ventas por volumen y tienda*  
> 🔹 *Mapa de calor: Densidad total de ventas (todas las tiendas)*

---

## 🧠 Principales insights obtenidos

- **Tienda 4** es la menos rentable en ingresos totales.  
- Tiene calificaciones promedio más bajas que Tienda 2 y 3.  
- Ofrece el costo de envío más bajo, pero **sin impacto positivo en ventas**.  
- Posee menor diversificación en categorías y productos líderes.  
- Presenta **menor penetración geográfica**, con actividad superpuesta a otras tiendas.  

## ✅ **Conclusión:**  
- Se recomienda **vender la Tienda 4**, dado su bajo desempeño financiero, falta de diferenciación y baja presencia en los mercados principales.
