# 🛍️ Análisis de Datos - Alura Store Latam

## 📌 Descripción
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre las ventas de Alura Store, una empresa que busca expandirse en América Latina. El objetivo es evaluar el desempeño de cuatro tiendas basándose en KPIs clave y recomendar cuál vender para invertir en un nuevo negocio.

## 🎯 Objetivos del Análisis
- **Facturación total**: ¿Cuál tienda vende más?
- **Categorías más populares**: ¿Qué productos se venden más en cada tienda?
- **Clasificación promedio de clientes**: ¿Cuál es la evaluación promedio de cada tienda?
- **Productos más y menos vendidos**: ¿Cuáles son los productos con mejor y peor desempeño por tienda?
- **Costo promedio de envío**: ¿Cuál es el costo medio de envío por tienda?

Basado en estos datos, se recomienda vender la tienda con peor rendimiento general.

## 📊 Resultados Principales
- **Facturación total**: Tienda 4 tiene la menor facturación ($1,038,375,700).
- **Clasificación promedio**: Tienda 1 tiene la peor evaluación (3.98/5).
- **Costo de envío promedio**: Tienda 4 tiene el costo más bajo ($23,459.46).
- **Recomendación**: Vender la Tienda 4 para reinvertir en otras tiendas o un nuevo negocio.

## 🛠️ Tecnologías Utilizadas
- **Python**: Lenguaje principal.
- **Pandas**: Manipulación y análisis de datos.
- **NumPy**: Cálculos numéricos.
- **Matplotlib**: Gráficos básicos.
- **Seaborn**: Gráficos estadísticos.

## 📁 Estructura del Proyecto
```
Alura_Store/
├── Alura_Store.ipynb    # Notebook principal con el análisis
├── tienda_1.csv         # Datos de ventas de la Tienda 1
├── tienda_2.csv         # Datos de ventas de la Tienda 2
├── tienda_3.csv         # Datos de ventas de la Tienda 3
├── tienda_4.csv         # Datos de ventas de la Tienda 4
├── requirements.txt     # Dependencias del proyecto
└── README.md            # Este archivo
```

## 🚀 Cómo Ejecutar el Proyecto
1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/Alura_Store.git
   cd Alura_Store
   ```

2. **Instala las dependencias**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecuta el notebook**:
   - Abre `Alura_Store.ipynb` en Jupyter Notebook, VS Code o Google Colab.
   - Ejecuta todas las celdas para ver los análisis y gráficos.

## 📈 Datos
Los datos provienen de cuatro archivos CSV con información de ventas, incluyendo producto, categoría, precio, costo de envío, fecha, vendedor, ubicación, calificación, método de pago, etc.

## 🤝 Contribuciones
Si quieres contribuir, abre un issue o pull request en GitHub.

## 📄 Licencia
Este proyecto es para fines educativos. Los datos son ficticios.

## 👤 Autor
- Edwin (o tu nombre) - Análisis realizado como parte del desafío Alura Store.