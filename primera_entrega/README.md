# 📊 Material de Primera Evaluación - Proyecto Geoinformática

## 📁 Contenido de esta carpeta

Este directorio contiene todos los materiales necesarios para la **primera evaluación del proyecto semestral** del curso de Geoinformática.

### 📄 Documentos disponibles:

1. **📘 `guia_primera_entrega.tex`** - Guía completa de evaluación (LaTeX)
   - Descripción detallada de requisitos
   - Objetivos y componentes de evaluación
   - Fechas importantes
   - Recursos de apoyo

2. **📊 `rubrica_evaluacion.md`** - Rúbrica de evaluación detallada
   - Distribución de puntajes (100 puntos)
   - Criterios específicos por componente
   - Escala de conversión a notas
   - Bonificaciones posibles

3. **📝 `plantilla_informe.tex`** - Plantilla LaTeX para el informe
   - Estructura completa predefinida
   - Secciones requeridas
   - Formato profesional
   - Ejemplos de código y tablas

4. **✅ `checklist_estudiantes.md`** - Checklist de entregables
   - Lista verificable de todos los requisitos
   - Timeline recomendado
   - Errores comunes a evitar
   - Tips para mejor nota

---

## 🎯 Resumen de la Evaluación

### Componentes y ponderaciones:

| Componente | Peso | Descripción |
|------------|------|-------------|
| **Informe Técnico** | 40% | 15-20 páginas con análisis completo |
| **Presentación Oral** | 25% | 15 min exposición + 5 min preguntas |
| **Código y Reproducibilidad** | 20% | GitHub con código documentado |
| **Visualizaciones** | 10% | Mínimo 3 mapas + 5 gráficos + 1 interactivo |
| **Trabajo en Equipo** | 5% | Evidencia de colaboración |

### Requisitos mínimos:

✔️ **Informe:** 15-20 páginas en PDF (LaTeX o Markdown)
✔️ **Código:** Repositorio GitHub público y documentado
✔️ **Datos:** Fuentes identificadas y datos descargados
✔️ **Análisis:** EDA completo + análisis espacial básico
✔️ **Visualizaciones:** 3 mapas + 5 gráficos + 1 interactivo
✔️ **Marco teórico:** Mínimo 10 referencias bibliográficas

---

## 📅 Fechas Importantes

- **📢 Publicación de guía:** Hoy
- **📚 Período de consultas:** Próximas 2 semanas
- **📤 Entrega de informe y código:** [2 semanas desde hoy]
- **🎤 Presentaciones:** Semana siguiente a la entrega
- **📝 Retroalimentación:** 1 semana después de presentaciones

---

## 💻 Cómo usar estos materiales

### Para compilar la guía en LaTeX:
```bash
pdflatex guia_primera_entrega.tex
```

### Para usar la plantilla de informe:
1. Copiar `plantilla_informe.tex` a su proyecto
2. Modificar con su información
3. Completar cada sección
4. Compilar a PDF

### Para el checklist:
1. Imprimir o copiar `checklist_estudiantes.md`
2. Marcar items completados
3. Usar como verificación final antes de entregar

---

## 🚀 Quick Start para Estudiantes

### Paso 1: Preparar repositorio
```bash
# Crear repositorio para el proyecto
mkdir proyecto-geo-[nombres]
cd proyecto-geo-[nombres]
git init

# Crear estructura básica
mkdir -p data/{raw,processed}
mkdir -p notebooks
mkdir -p src
mkdir -p outputs/{figures,maps}
mkdir -p docs

# Copiar plantilla
cp /ruta/a/plantilla_informe.tex docs/
```

### Paso 2: Configurar ambiente Python
```bash
# Crear ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
# o
venv\Scripts\activate  # Windows

# Instalar librerías básicas
pip install geopandas pandas matplotlib folium jupyter
pip freeze > requirements.txt
```

### Paso 3: Inicializar GitHub
```bash
# Crear README
echo "# Proyecto [Título]" > README.md

# Primer commit
git add .
git commit -m "Initial commit"

# Conectar con GitHub (crear repo primero en github.com)
git remote add origin https://github.com/[usuario]/[proyecto].git
git push -u origin main
```

---

## 📊 Criterios de Excelencia

Para alcanzar nota 6.5-7.0, considerar incluir:

### Elementos técnicos avanzados:
- 🐳 Docker para reproducibilidad completa
- 🔄 CI/CD con GitHub Actions
- 🤖 Análisis de Machine Learning
- 🌍 Integración con Google Earth Engine
- 📡 Datos en tiempo real o APIs

### Visualizaciones destacadas:
- 🗺️ Dashboard web interactivo (Streamlit)
- 📈 Más de 5 mapas temáticos profesionales
- 🎬 Animaciones temporales
- 🏔️ Visualizaciones 3D

### Documentación superior:
- 📚 Documentación tipo Sphinx
- 🎥 Video tutorial del proyecto
- 📖 Jupyter Book
- ✍️ Blog post explicativo

---

## ❓ Preguntas Frecuentes

### ¿Puedo cambiar el enfoque del proyecto?
Sí, pero debe justificarse claramente en el informe. Esta evaluación es precisamente para detectar si se necesitan ajustes.

### ¿Qué pasa si mis datos no están completos?
Mostrar avance con los datos disponibles y explicar el plan para obtener los faltantes.

### ¿El código debe estar 100% terminado?
No, se espera un 40-50% de avance del proyecto total, pero debe ser funcional y estar bien documentado.

### ¿Cómo se evalúa el trabajo en equipo?
A través de los commits de GitHub, la división del trabajo en el informe, y la participación en la presentación.

---

## 🆘 Soporte y Ayuda

### Contacto:
- **📧 Email:** francisco.parra@usach.cl
- **🕐 Horarios consulta:** Martes y Jueves después de clase
- **💬 Teams:** Previa coordinación

### Recursos adicionales:
- [Documentación GeoPandas](https://geopandas.org)
- [Tutorial Folium](https://python-visualization.github.io/folium/)
- [PySAL para análisis espacial](https://pysal.org)
- [Overleaf para LaTeX](https://www.overleaf.com)

---

## ⚠️ Recordatorios Importantes

1. **No dejar para último momento** - El análisis espacial requiere tiempo
2. **Probar reproducibilidad** - Verificar que el código funciona en ambiente limpio
3. **Commits frecuentes** - Evidenciar trabajo continuo de ambos integrantes
4. **Elementos cartográficos** - Todos los mapas necesitan: título, leyenda, escala, norte, fuente
5. **Respaldo** - Mantener copias de seguridad de todo

---

## 📝 Notas para el Profesor

### Para evaluar:
- Usar `rubrica_evaluacion.md` como guía de puntajes
- Verificar reproducibilidad clonando repositorios
- Tomar notas durante presentaciones para retroalimentación

### Penalizaciones automáticas:
- -10 puntos por día de atraso
- -5 puntos si falta algún integrante a presentación
- -10 puntos si no hay datos reales
- Nota 1.0 por plagio detectado

---

*Última actualización: [Fecha]*
*Prof. Francisco Parra O. - Geoinformática USACH*