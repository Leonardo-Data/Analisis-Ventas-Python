# 🔍 Proceso de Análisis

1. **Carga de Datos**
   - Se carga el archivo Excel con `pandas.read_excel()`.

2. **Limpieza**
   - Eliminación de duplicados.
   - Eliminación de valores nulos.

3. **Transformación**
   - Extracción de `País` y `Continente` desde la columna `Ubicación`.
   - Creación de columnas `Año` y `Mes` desde la fecha de venta.

4. **Visualizaciones**
   - 📊 **Top 5 Países con Mayor Facturación:** gráfico de barras con valores en millones.
   - 📈 **Ventas Totales Mensuales por Año:** gráfico de líneas comparando cada año.
