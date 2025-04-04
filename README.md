# Selección de Medicamento con Árboles de Decisión

## Objetivo  
Desarrollar un modelo de clasificación utilizando árboles de decisión para predecir el medicamento más adecuado para un paciente, con base en variables como edad, sexo, presión arterial, colesterol y tasa de sodio/potasio.

---

## Tabla de Contenidos
- [Introducción](#introducción)  
- [Fuentes de Datos](#fuentes-de-datos)  
- [Procesamiento y Análisis](#procesamiento-y-análisis)  
- [Modelado con Árbol de Decisión](#modelado-con-árbol-de-decisión)  
- [Evaluación del Modelo](#evaluación-del-modelo)  
- [Visualización del Árbol](#visualización-del-árbol)  
- [Requisitos](#requisitos)  
- [Uso](#uso)  
- [Contribuciones](#contribuciones)  
- [Autor](#autor)  

---

## Introducción  
Este proyecto utiliza árboles de decisión para clasificar medicamentos basados en las características clínicas de los pacientes. Se exploran distintos criterios de impureza como Gini y Entropía, además de ajustar la profundidad del árbol para optimizar el modelo.

---

## Fuentes de Datos  
- **Archivo Utilizado:** `drug200.csv`  
- **Fuente:** Datos ficticios o académicos para propósitos de enseñanza de clasificación.  
- Atributos utilizados:
  - Edad
  - Sexo
  - Presión arterial (BP)
  - Colesterol
  - Relación Sodio/Potasio
  - Medicamento prescrito (variable objetivo)

---

## Procesamiento y Análisis  
- Limpieza de datos: codificación de variables categóricas.
- División del dataset en entrenamiento y prueba.
- Visualización exploratoria de la distribución de clases.

---

## Modelado con Árbol de Decisión  
Se implementa un modelo `DecisionTreeClassifier` de `scikit-learn` con los siguientes enfoques:
- Criterios de evaluación: Gini vs Entropía.
- Ajuste de hiperparámetros como `max_depth` para evitar sobreajuste.

---

## Evaluación del Modelo  
- Precisión del modelo en entrenamiento y prueba.
- Matriz de confusión para evaluar el desempeño por clase.
- Reporte de métricas como accuracy, precision, recall y F1-score.

---

## Visualización del Árbol  
- Se representa gráficamente el árbol entrenado para facilitar la interpretación del modelo y entender cómo se toman las decisiones.
![image](https://github.com/user-attachments/assets/ec11c424-1d73-43b9-88eb-01d128e35363)

---

## Requisitos  
Para ejecutar el notebook, asegúrate de tener instalado:

- Python 3.x  
- Jupyter Notebook o Jupyter Lab  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

Instalación rápida:
```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

---

## Uso  
1. Clona este repositorio:
```bash
git clone https://github.com/tu_usuario/seleccion-medicamento.git
```
2. Abre el notebook:
```bash
jupyter notebook "Seleccion de medicamento-tree.ipynb"
```
3. Ejecuta las celdas en orden para entrenar el modelo y visualizar los resultados.

---

## Contribuciones  
¿Te gustaría agregar validación cruzada, otros clasificadores o análisis complementarios?  
¡Tu aporte es bienvenido! Abre un issue o envía un pull request.

---

## Autor  
**José Eduardo Saucedo Martínez**  
