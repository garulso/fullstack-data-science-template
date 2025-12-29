# 🚀 Full-Stack Data Science Plan  
*Un camino estructurado de 12 semanas para dominar Ciencia de Datos, Ingeniería de Datos y MLOps.*

> ✦ Autor: **Raúl Silva Orellana**  
> ✦ Estado: 🟢 Semana 1 completada | Próxima: Semana 2 (Estadística + Visualización)

---

## 📁 Estructura del repositorio

## Estructura del repositorio

```text
proyecto-titanic/
  data/
    raw/                 # Datos sin modificar
    processed/           # Datos limpios, listos para modelar
  notebooks/             # Notebooks Jupyter por semana
  src/                   # Código modular reutilizable (Python)
  docs/                  # Notas, planificacion, reflexiones tecnicas
  models/                # Modelos entrenados (.pkl, .joblib, .pt)
  reports/               # Figuras, dashboards, informes finales
```

---

## 📊 Semana 1: Entorno + Exploración Titanic  
✅ **Logros**:  
- Entorno reproducible con `conda`  
- Carga y exploración de [Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- Visualización de patrones clave (género, clase, edad)  
- Limpieza básica: imputación de `Age` con mediana  
- Dataset limpio guardado en `data/processed/titanic_clean.csv`

📈 **Hallazgos principales**:  
- Supervivencia: 74% de mujeres vs 19% de hombres  
- Clase 1: 63% supervivencia vs 24% en clase 3  
- Tarifas extremas: hasta \$512 (posiblemente suites)

🔧 **Próximos pasos (Semana 2)**:  
- Estadística descriptiva formal (cuartiles, varianza)  
- Detección rigurosa de outliers (IQR rule)  
- Visualización avanzada con `seaborn`

---

## ▶️ Cómo ejecutar

```bash
# 1. Clonar repo
git clone https://github.com/tu-usuario/fullstack-data-science-template.git

# 2. Crear entorno
conda env create -f environment.yml
conda activate data-science-101

# 3. Abrir notebooks
jupyter notebook
```


