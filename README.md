# 🌐 Proyecto Colaborativo — Uso y Tratamiento de la información (Datos)

### Bootcamp Desarrollo Web — Actividad de Colaboración en GitHub

---

## 🧠 Objetivo General

Desarrollar una **página web estática (HTML + CSS)** en equipos, aplicando buenas prácticas de **colaboración con GitHub**.  
El sitio abordará los **5 Pilares del Ciclo de Vida del Dato**, cada uno desarrollado por un equipo diferente.

---

## 🚀 Objetivos de Aprendizaje

- Utilizar **HTML y CSS** para crear estructuras y estilos coherentes
- Trabajar en **ramas (branches)** e implementar cambios mediante **pull requests (PR)**
- Organizar tareas en **GitHub Projects** e issues asignadas por equipo
- Comprender y comunicar los fundamentos del **Ciclo de Vida del Dato** en el contexto de Data Science

---

## 🏗️ Estructura del Proyecto

```
/
├── .github/                     # Configuración de GitHub
├── assets/                      # Recursos compartidos como imágenes
│   ├── data-analysis/
│   ├── data-cleaning/
│   ├── data-origin/
│   ├── deployment/
│   └── strategic-direction/
├── examples/                    # Ejemplos de referencia
│   ├── alanTuring.png
│   ├── aristoteles.png
│   ├── georgeBoole.png
│   ├── examples.html
│   └── examples.css
├── data-analysis/               # Equipo 3: Análisis & Modelado
│   ├── data-analysis.html
│   └── data-analysis.css
├── data-cleaning/               # Equipo 2: Limpieza & Transformación
│   ├── data-cleaning.html
│   └── data-cleaning.css
├── data-origin/                 # Equipo 1: Origen & Captura de Datos
│   ├── data-origin.html
│   └── data-origin.css
├── deployment/                  # Equipo 4: Despliegue & Monitorización
│   ├── deployment.html
│   └── deployment.css
├── strategic-direction/         # Equipo 5: Impacto & Dirección Estratégica
│   ├── strategic-direction.html
│   └── strategic-direction.css
├── globals.css                  # Estilos base compartidos
├── index.html                   # Página principal
├── script.js                    
└── README.md                   
```

---

## 🧩 Temas Asignados por Equipo

### **1️⃣ Origen & Captura de Datos**
- Fuentes estructuradas (BBDD, APIs, ERP) y no estructuradas (logs, sensores, redes sociales)
- Estrategias de recolección e ingestión
- Data Governance
- Metadatos y procedencia

### **2️⃣ Limpieza & Transformación**
- Data Wrangling y calidad de datos
- Manejo de valores nulos y outliers
- ETL/ELT y pipelines
- Feature Engineering

### **3️⃣ Análisis & Modelado**
- Estadística descriptiva y visualización
- Machine Learning (supervisado y no supervisado)
- Experimentación y validación
- Segmentación y patrones ocultos

### **4️⃣ Despliegue & Monitorización**
- Puesta en producción de modelos (MLOps)
- Dashboards y reporting automatizado
- Sistemas de recomendación en tiempo real
- Monitorización y mantenimiento

### **5️⃣ Impacto & Dirección Estratégica**
- Storytelling con datos para la toma de decisiones
- ROI e impacto en negocio
- Retroalimentación y mejora continua
- Ética, privacidad y gobierno de datos

---

## 🧭 Instrucciones de Trabajo en GitHub

### 1️⃣ Clonar el repositorio base

```bash
git clone https://github.com/[nombre-organizacion]/hello_world_from_pr.git
hello_world_from_pr
```

### 2️⃣ Crear una tarea general por equipo

Esto lo harán creando la tarea que les ha tocado

### 3️⃣ Crear subtareas

Dentro de la tarea general deben crear sub-tareas de los subtemas que les ha tocado

### 4️⃣ Crear una rama de la tarea general y de las subtareas

Esto lo harán a partir de los issues(tareas) que han creado en el tablero del projects

### 5️⃣ Crear o editar su carpeta asignada

- Añadir su HTML y CSS dentro de la carpeta correspondiente
- Mantener coherencia visual con los estilos globales (`globals.css`)

### 6️⃣ Unir lo hecho en las ramas de las subtareas en la rama general de la tarea

Esto lo harán para verificar que funciona correctamente haciendo merge, y luego subiremos los cambios usando:

```bash
git add .
git commit -m "Equipo 2: sección Limpieza & Transformación"
git push origin feature/limpieza-transformacion
```

### 7️⃣ hacemos merge en la rama develop

Aquí es donde probamos nuestros cambios junto con los de nuestros compañeros en la rama develop

### 8️⃣ Crear un Pull Request

Desde GitHub:
1. Abrir un PR desde su rama hacia `main`
2. Asignar como revisores a los instructores
3. Esperar aprobación antes de fusionar

---

## 🗂️ GitHub Project & Issues

- Cada equipo tendrá **issues asignadas** con las tareas específicas (diseño, contenido, revisión, media, etc.)
- Se usará **GitHub Projects** para seguir el progreso (To Do / In Progress / Done)
- Cada issue debe asociarse a una rama y un PR

---

## 🧑‍💻 Reglas de Colaboración

- ❌ No editar archivos fuera de la carpeta asignada sin autorización
- ✅ Mantener un estilo visual coherente (tipografía, paleta y estructura)
- ⏰ Respetar los tiempos de entrega y revisiones de PR
- 📝 Documentar cambios relevantes en los commits

---

## 🎯 Entregable Final

Una web estática navegable con un acordeón principal (`index.html`) que mostrará las secciones creadas por cada equipo.

**El sitio será evaluado por:**
- Estructura y organización del código
- Uso correcto de Git y GitHub (ramas, PR, issues)
- Estética visual y coherencia entre secciones
- Claridad y precisión del contenido técnico

---

## 📚 Recursos Adicionales

- [Documentación de Git](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
