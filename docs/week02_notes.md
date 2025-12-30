# 📝 Notas Semana 2 — Lunes

## 🔢 Hallazgos estadísticos:
- **Asimetría en `Fare`**: media (32.2) > mediana (14.5) → distribución sesgada derecha (pocos pagaron mucho).
- **Edad por clase**: Clase 1 (39 años) > Clase 3 (25 años) → posible sesgo en análisis si no se controla.
- **IQR para `Age`**: [21, 39] → 50% de pasajeros entre 21 y 39 años.

## 🤔 Reflexión docente/investigador:
- ¿Es válido eliminar outliers en `Fare`? No: reflejan realidad (clase alta). Mejor: transformar (log) o segmentar.
- La mediana es más robusta que la media para `Age` (menos sensible a ancianos).
- En modelado: `Pclass` debe incluirse como feature o como grupo para imputar `Age`.

## ✅ Checklist:
- [x] Estadísticas univariadas calculadas  
- [x] Comparación por grupos (Pclass, Survived)  
- [x] Cuartiles e IQR para Age/Fare  
- [x] Interpretación documentada