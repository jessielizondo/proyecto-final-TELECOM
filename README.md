# Proyecto Final — Notebook Integrado

Este repositorio contiene un **notebook integrado** que combina:
- **Parte 1 — Preprocesamiento** (`ProyectoFINAL_Pt1.ipynb`)
- **Parte 2 — Modelado y Evaluación** (`ProyectoFINAL_COMPLETO.ipynb`)

El resultado final está en: **`ProyectoFINAL_Integrado.ipynb`**

---

## 🧭 Estructura
```
.
├── ProyectoFINAL_Integrado.ipynb        # Cuaderno integrado (ejecutar en orden)
├── ProyectoFINAL_Pt1.ipynb           # Original parte 1 (referencia)
├── ProyectoFINAL_COMPLETO.ipynb           # Original parte 2 (referencia)
├── requirements.txt          # Dependencias mínimas inferidas
├── .gitignore                # Ignorar artefactos y entornos
└── README.md                 # Este archivo
```

> Tip: Los datos locales se recomiendan bajo `./data/` (ya está ignorado por Git).

---

## ⚙️ Requisitos
- Python 3.10+ (recomendado)
- Entorno conda o venv (por ejemplo, `conda create -n data_env python=3.10`)

Instala dependencias mínimas:
```bash
pip install -r requirements.txt
```
> Si tu proyecto usa paquetes adicionales, agrégalos a `requirements.txt` según sea necesario.

---

## 🏃 Cómo reproducir
1. Clona este repositorio o descarga los archivos.
2. Activa tu entorno (ej. `conda activate data_env`).
3. Abre JupyterLab/Notebook y ejecuta **`ProyectoFINAL_Integrado.ipynb`** de arriba hacia abajo.

> Todas las salidas fueron limpiadas para facilitar una ejecución fresca.

---

## 📊 Resultados & Métricas
Incluye aquí un breve resumen de las métricas clave (ejemplos):
- ROC‑AUC: `...`
- F1 / Accuracy: `...`
- SMAPE / RMSE (si aplica): `...`

> Puedes editar esta sección tras volver a ejecutar el cuaderno integrado.

---

## 🗂️ Datos
Describe la(s) fuente(s) de datos, licencia y cualquier paso de obtención/limpieza relevante.

---

## 🧪 Estructura del flujo (sugerido)
1. **Carga de datos**
2. **Preprocesamiento** (limpieza, imputación, encoding, escalado)
3. **EDA** (análisis exploratorio)
4. **Modelado** (entrenamiento y validación)
5. **Evaluación** (métricas, curvas, tablas comparativas)
6. **Conclusiones** y **trabajo futuro**

---

## ✍️ Autoría
- Jessica Elizondo Treviño

