# 📝 Notas Semana 1 — Lunes

## 🔍 Hallazgos clave:
- Total registros: 891
- Variables numéricas principales: `Age`, `Fare`, `SibSp`, `Parch`
- Variables categóricas: `Survived`, `Pclass`, `Sex`, `Embarked`
- Valores nulos significativos en: `Age` (~20%), `Cabin` (~77%), `Embarked` (2 filas)

## ❓ Preguntas para investigar:
- ¿Por qué `Cabin` tiene tantos nulos? ¿Se puede imputar?
- ¿Cómo afecta `Pclass` a la supervivencia?
- ¿Hay sesgo de género? (`Sex` vs `Survived`)

## ✅ Avances:
- [x] Entorno conda activado  
- [x] Dataset cargado  
- [x] Exploración básica completada  
- [x] Notas documentadas

## 📊 Hallazgos visuales (miércoles):
- Las mujeres tuvieron mayor tasa de supervivencia.
- Edad: mediana ~28 años; algunos outliers >65 años.
- Clase 1: mayor edad promedio y mayor supervivencia.
- `Fare` y `Pclass` correlación ≈ -0.55 → coherente (clase alta = mayor tarifa).

## 🧹 Limpieza (miércoles):
- Nulos: `Age` → imputado con mediana (28.0 años)
- Outliers en `Fare`: tarifas >300 (posiblemente suites/camarotes privados)
- Dataset limpio guardado en `data/processed/titanic_clean.csv`

## 🤔 Reflexión docente:
- ¿Es correcto usar la mediana para `Age`? ¿Qué pasa si hay diferencias por género/clase?
- Los outliers en `Fare` no son errores: reflejan realidad histórica (clase alta pagó mucho más).

