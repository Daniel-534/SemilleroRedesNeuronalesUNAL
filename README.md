<<<<<<< HEAD
# 🌟 Instella: Modelos de Lenguaje Totalmente Abiertos con Rendimiento Estelar

> **Proyecto del Semillero AtarraIA – Universidad Nacional de Colombia, Sede Medellín**  
> Repositorio colaborativo para la exposición del paper:  
> **["Instella: Fully Open Language Models with Stellar Performance"](https://arxiv.org/abs/2511.10628)**  
> Autores: Jiang Liu et al. (AMD, 2025)

---

## 📌 Objetivo

Este repositorio tiene como fin **comprender, explicar y demostrar** los aportes clave del modelo **Instella**, una familia de **modelos de lenguaje totalmente abiertos** (fully open) de 3 mil millones de parámetros. La exposición está dirigida a la **comunidad universitaria** y busca equilibrar:

- Una **introducción divulgativa** accesible para estudiantes de distintas disciplinas.
- Una **explicación técnica rigurosa** para quienes tienen formación en ciencias de la computación, IA o matemáticas.
- **Ejemplos prácticos en Python** que ilustren el uso de Instella y sus variantes.

---

## 🔍 ¿Qué hace especial a Instella?

A diferencia de muchos modelos de lenguaje populares (como Llama o Gemma), **Instella no solo libera los pesos** del modelo, sino **todo el proceso de entrenamiento**:

- ✅ **Código fuente completo**  
- ✅ **Recetas de datos** (qué y cómo se usó para entrenar)  
- ✅ **Scripts de preprocesamiento**  
- ✅ **Configuraciones de optimización y evaluación**

Esto lo convierte en un **referente de reproducibilidad científica** en el campo de los LLMs.

Además, Instella incluye **tres variantes especializadas**:
- **Instella-3B**: modelo base instrucción-sintonizado.
- **Instella-Long**: soporta hasta **128K tokens** de contexto.
- **Instella-Math**: optimizado para **razonamiento matemático** mediante **refuerzo (GRPO)**.

> *"La transparencia y la competitividad no son mutuamente excluyentes."*  
> — Equipo de Instella, AMD

---

## 🧪 Contenido del repositorio

Este proyecto está organizado en dos pilares complementarios:

### 📊 Notebooks de Python (`/notebooks`)
- `01_instella_inferencia_basica.ipynb`: Carga y ejecución del modelo Instella en CPU/GPU con `transformers`.
- `02_instella_long_context.ipynb`: Demostración del manejo de contextos largos (hasta 128K tokens).
- `03_instella_math_ejemplos.ipynb`: Razonamiento matemático con Instella-Math y comparación contra otros modelos.
- `04_evaluacion_benchmarks.ipynb`: Reproducción parcial de benchmarks como GSM8K o MMLU (si el hardware lo permite).

> **💡 Nota**: Los notebooks están diseñados para ser ejecutables incluso en hardware modesto (ej. CPU + cuantización 4-bit con `bitsandbytes` o `llama.cpp`).

### 📝 Presentación Beamer (`/beamer`)
- `instella_exposicion.tex`: Archivo fuente de la presentación en LaTeX (clase `beamer`).
- `figuras/`: Diagramas, gráficas del paper y esquemas propios.
- `bibliografia.bib`: Referencias BibTeX citadas en la exposición.

---

## 🚀 Cómo contribuir (para colaboradores)

Este repositorio está pensado para **trabajo asincrónico** entre dos o más personas. Asegúrate de:

1. **Crear una rama** antes de modificar:
   ```bash
   git checkout -b nombre/nueva-seccion
=======
# Exposición en el Semillero de Redes Neuronales de la Universidad Nacional de Colombia

Se construirá la exposición sobre el artículo de investigacioń [Instella: Fully Open Language Models with Stellar Performance](https://arxiv.org/abs/2511.10628) publicado el 13 de Noviembre de 2025

---


>>>>>>> 4898808f0943fab052e7dce78ac442d6abe133b6
