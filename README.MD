# Archivos del Proyecto Perceptron

## 📁 ClassPerceptron.py

**Propósito**: Implementa el clasificador Perceptron con capacidades de visualización.

**Características principales**:
- Implementa el algoritmo de aprendizaje del Perceptron
- Incluye visualización en tiempo real del proceso de entrenamiento
- Soporta personalización de parámetros de aprendizaje (tasa de aprendizaje, iteraciones)
- Permite controlar la aleatoriedad mediante semilla
- Proporciona métodos para predicción y cálculo de probabilidades

## 📁 grafica.py

**Propósito**: Funciones auxiliares para visualización gráfica.

**Características principales**:
- Visualiza puntos de datos en 2D con colores según su clase
- Dibuja la recta de decisión del perceptron durante el entrenamiento
- Actualización en tiempo real de la gráfica
- Soporta personalización de títulos de ejes
- Diseñado específicamente para trabajar con datos bidimensionales

## 📁 PlotRegiones.py

**Propósito**: Visualización de regiones de decisión del clasificador.

**Características principales**:
- Genera mapas de colores para las regiones de clasificación
- Crea superficies de decisión para clasificadores binarios
- Visualiza ejemplos de cada clase con marcadores diferenciados
- Soporta resolución configurable para el mapa de decisiones
- Proporciona una representación visual clara del comportamiento del clasificador

## 🔗 Relación entre archivos

Los tres archivos trabajan conjuntamente:
- `ClassPerceptron.py` implementa el algoritmo principal
- `grafica.py` proporciona visualización durante el entrenamiento
- `PlotRegiones.py` ofrece visualización post-entrenamiento de las regiones de decisión

Juntos forman un sistema completo para implementar, entrenar y visualizar el comportamiento de un perceptron en problemas de clasificación bidimensional.
