# 🏥 Simulador Interactivo de Riesgo de Lesiones Deportivas - UCEBOL

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-Educativa-blue?style=for-the-badge)](#)

Este repositorio contiene el código fuente de una aplicación web interactiva desarrollada para la **Universidad Cristiana de Bolivia (UCEBOL)**. La herramienta permite evaluar y visualizar en tiempo real el riesgo de lesiones en miembros superiores y columna vertebral para tres disciplinas deportivas: **Voleibol, Balonmano y Jiu-Jitsu**.

Diseñado como material de apoyo para la asignatura de **Anatomía**, este proyecto combina principios de biomecánica, epidemiología deportiva y diseño web moderno para fomentar la prevención y el acondicionamiento físico seguro en deportistas universitarios y competitivos.

---

## ✨ Características Principales

- 🏐 **Perfiles Multideportivos**: Lógica y datos específicos para los mecanismos de lesión en Voleibol, Balonmano y Jiu-Jitsu.
- 🎛️ **Variables Ajustables**: Controles interactivos para modificar horas de entrenamiento, nivel de experiencia, calidad del calentamiento, tipo de superficie, uso de protección y supervisión técnica.
- 📊 **Cálculo de Riesgo en Tiempo Real**: Algoritmo en JavaScript que pondera factores agudos y de sobreuso para generar un índice de riesgo dinámico (0 a 100).
- 🦴 **Visualización Anatómica SVG**: Representación gráfica del cuerpo humano con marcadores animados que resaltan las zonas corporales con mayor vulnerabilidad (hombro, muñeca, codo, columna lumbar/cervical, clavícula).
- 📱 **Generador de Código QR**: Permite exportar y compartir los resultados de la simulación escaneando un código QR dinámico generado en el cliente.
- 📚 **Contenido Educativo Integral**: Pestañas dedicadas a lesiones frecuentes, protocolos de prevención y referencias científicas con contexto epidemiológico de Bolivia (ej. datos de los Juegos Plurinacionales y factores de altitud).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica, accesibilidad y metadatos optimizados.
- **CSS3**: Diseño moderno, responsivo y accesible utilizando variables CSS (`:root`), Flexbox, CSS Grid, *backdrop-filter* y animaciones suaves. Tipografías: *Inter*, *Instrument Serif* y *JetBrains Mono*.
- **JavaScript (Vanilla)**: Lógica de simulación, manipulación del DOM, generación de SVG dinámico y un algoritmo de generación de códigos QR integrado (sin dependencias externas ni librerías de terceros).

---

## 📂 Estructura del Sitio

1. **Simulador**: Panel principal de interacción, ajuste de variables y visualización de resultados en vivo.
2. **Lesiones**: Ficha clínica detallada de las patologías y fracturas más comunes por disciplina deportiva.
3. **Prevención**: Protocolos de acondicionamiento, fortalecimiento y recomendaciones científicas (Protocolo UCEBOL).
4. **Referencias**: Fuentes bibliográficas de medicina deportiva y datos epidemiológicos nacionales.

---

## 🚀 Cómo Ejecutar el Proyecto

Este proyecto es completamente *frontend* y **no requiere** instalación de dependencias, Node.js ni servidores backend.

1. Clona o descarga este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/simulador-lesiones-ucebol.git
