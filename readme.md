# 🌐 Bedrock AI Simulation Suite — Proyecto Final de IA Generativa

## 📘 Descripción general

Este proyecto implementa una suite completa de simulaciones inspiradas en las capacidades de Amazon Bedrock, utilizando únicamente herramientas locales como Groq, LangChain y Python, sin coste y sin dependencias de AWS.

El objetivo es demostrar cómo se pueden recrear flujos avanzados de IA generativa y automatización de datos mediante técnicas modernas:

- Ingeniería de indicaciones

- Caché de respuestas

- Evaluación automática y con modelo juez

- Recuperación aumentada (RAG)

- Procesamiento multimedia simulado

- Enrutamiento inteligente de modelos

Este proyecto sirve como ejercicio final integrador del curso, mostrando un flujo de IA completo, modular y escalable.

---

## 🧩 Objetivos del proyecto

- Simular las capacidades principales de Amazon Bedrock sin utilizar AWS.

- Construir un flujo de IA generativa completo y profesional.

- Integrar técnicas avanzadas: caché, evaluación, RAG, multimedia y enrutamiento.

- Proveer un ejemplo realista para portafolios profesionales y repositorios técnicos.  

---

## 🧠 Arquitectura del proyecto

El proyecto sigue una estructura modular inspirada en flujos de producción reales:

| Módulo | Descripción |
|-------|--------------|
| **Prompt Engineering** | Definición de roles, ejemplos y formato para guiar el modelo. |
| **Caching Engine** | Sistema de caché local para reducir tokens y acelerar respuestas. |
| **Evaluation Suite** | Métricas automáticas, modelo juez y evaluación humana simulada. |
| **RAG Engine** | Recuperación de documentos y generación contextual. |
| **Media Automation** | Transcripción, resumen, detección de logotipos y etiquetas IAB. |
| **Smart Routing** | Selección dinámica de modelos según complejidad del prompt. |

---

## 📊 Principales funcionalidades

- Transcripción simulada de contenido multimedia.

- Resumen automático de texto y audio.

- Detección simulada de logotipos en vídeo.

- Clasificación IAB para etiquetado de contenido.

- Evaluación automática (coherencia, claridad, longitud).

- Evaluación con modelo juez usando Groq.

- RAG básico con recuperación y generación contextual.

- Caché de respuestas con reducción de tokens simulada.

- Enrutamiento inteligente entre modelos según complejidad.

---

## 🧰 Herramientas utilizadas

- Python (Groq, LangChain, Pydantic)

- Jupyter Notebook

- GitHub (control de versiones y documentación)

---

## 📁 Estructura del repositorio

bedrock-ai-simulation-suite/

├─ notebooks/

│  └─ bedrock-ai-simulation-suite.ipynb

│

├─ src/

│  ├─ caching_engine.py

│  ├─ evaluation_suite.py

│  ├─ rag_engine.py

│  ├─ media_automation.py

│  └─ routing_engine.py

│

├─ docs/

│  └─ architecture_diagram.png

│

├─ .gitignore

├─ license

├─ readme.md

└─ requirements.txt

---

## 📈 Resultados visuales

El notebook incluye:

- Ejemplos de transcripción y resumen

- Resultados de detección de logotipos

- Etiquetas IAB generadas

- Métricas de evaluación automática

- Puntuación del modelo juez

- Recuperación y generación RAG

- Comparación de tokens con y sin caché

- Selección dinámica de modelos

---

## 💡 Conclusiones

- Es posible simular capacidades avanzadas de Amazon Bedrock sin utilizar AWS.

- Groq + LangChain permiten construir flujos de IA generativa completos y eficientes.

- La arquitectura modular facilita la escalabilidad y reutilización del código.

- Este proyecto demuestra dominio técnico en IA generativa, automatización y diseño de pipelines.

---

## 🏁 Autor

Proyecto desarrollado por Rebeca Soto como parte de su portafolio profesional de IA generativa, automatización de datos y arquitectura de sistemas de inteligencia artificial.

📅 Agosto 2026  

📍 Mijas, Andalucía, España

---

## 🪄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  

Consulta el archivo `LICENSE` para más detalles.
