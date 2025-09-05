## 🔹 Clasificador K-Nearest Neighbors (KNN)

El **K-Nearest Neighbors (KNN)** es un algoritmo de aprendizaje supervisado utilizado principalmente para **clasificación** y, en algunos casos, para **regresión**.  
Su funcionamiento es simple pero poderoso: para clasificar un nuevo dato, el algoritmo busca los **k vecinos más cercanos** en el conjunto de entrenamiento y asigna la clase más frecuente entre ellos.

### 🔑 Características principales
- **No paramétrico**: no hace suposiciones sobre la distribución de los datos.  
- **Basado en distancia**: comúnmente se usa la distancia **euclidiana**, aunque también se aplican Manhattan, Minkowski, etc.  
- **Hiperparámetro k**:
  - Valores pequeños de *k* → modelo sensible al ruido (*sobreajuste*).  
  - Valores grandes de *k* → fronteras de decisión demasiado suaves (*subajuste*).  

### ✅ Ventajas
- Fácil de implementar y comprender.  
- Puede aplicarse en clasificación multiclase.  
- No requiere una fase de entrenamiento compleja.  

### ⚠️ Desventajas
- Costoso en cómputo para grandes volúmenes de datos.  
- Sensible a la escala de las variables → requiere **normalización o estandarización**.  
- Depende mucho de la elección de *k* y de la métrica de distancia.  

### 📊 Aplicaciones comunes
- Reconocimiento de imágenes y patrones.  
- Sistemas de recomendación.  
- Detección de anomalías.  
- Clasificación de texto. 
