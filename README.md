# 📊 Clasificación de Ingresos con Machine Learning

Este proyecto implementa un sistema de clasificación de ingresos utilizando técnicas de aprendizaje automático. El objetivo es predecir si una persona gana más de \$50K al año, basándose en información demográfica y laboral extraída del censo de 1994.

Se emplea el dataset del **Census Income (también conocido como Adult Dataset)**, procesado con condiciones específicas para asegurar la calidad de los registros:  
`(AAGE > 16) && (AGI > 100) && (AFNLWGT > 1) && (HRSWK > 0)`.

---

## ⚙️ Instalación

1. **Clonar el repositorio**

```bash
git clone https://github.com/tu_usuario/income_classifier.git
cd income_classifier
```

2. **Crear y activar un entorno virtual**

- En **Linux/macOS**:

```bash
pip install virtualenv
python -m venv env
source env/bin/activate
```

- En **Windows**:

```bash
pip install virtualenv
python -m venv env
.\env\Scripts\activate
```

3. **Instalar dependencias**

```bash
pip install jupyter matplotlib numpy pandas scipy scikit-learn seaborn ipykernel
```

---

## 🚀 Ejecución

Abrí Jupyter Notebook y ejecutá el archivo `.ipynb` correspondiente para comenzar a explorar y entrenar el modelo:

```bash
jupyter notebook
```

---

## 📄 Licencia

Este proyecto está licenciado bajo los términos de la **GNU General Public License v3.0 (GPL-3.0)**.  
Podés ver los detalles completos en el archivo `LICENSE`.

---

## ✨ Créditos

Este trabajo se basa en el dataset proporcionado por Ronny Kohavi y Barry Becker:

> **Ron Kohavi**, "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", *Proceedings of the Second International Conference on Knowledge Discovery and Data Mining*, 1996.

Más información sobre el dataset disponible en: [UCI Machine Learning Repository - Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult)