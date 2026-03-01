# 🧠 Page Replace OS Simulator v3.5

Un simulador avanzado e interactivo de gestión de memoria virtual diseñado para visualizar, auditar y comparar algoritmos de reemplazo de páginas en tiempo real.

![Preview](https://img.shields.io/badge/Versi%C3%B3n-3.5-6366f1) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat&logo=javascript&logoColor=black) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

## 🚀 Características Principales

- **8 Algoritmos de Reemplazo**: FIFO, Óptimo (MIN), LRU, LFU, MFU, Reloj (Clock), Segunda Oportunidad y NRU.
- **📟 Kernel Event Monitor**: Registro en tiempo real de eventos de bajo nivel (Acceso MMU, Interrupción #14, Context Switch).
- **⚠️ Detector de Anomalía de Belady**: Monitoreo automático que identifica incrementos contra-intuitivos en fallos al aumentar la RAM.
- **⚡ Visualización Dinámica**: Animaciones de pulsación neón para fallos y destellos esmeralda para aciertos.
- **📊 Reporte Global de Métricas**: Comparativa de Hit Ratio, Total de Fallos y tiempos de ejecución.
- **🛠️ Simulación de Bits R|M**: Soporte para bits de Referencia y Modificado (Dirty bit) para algoritmos avanzados.

## 📂 Estructura del Proyecto

- `simulador_paginacion.html`: Aplicación principal (SPA) con motor de renderizado y lógica de algoritmos.
- `informe_tecnico_simulador.html`: Documentación técnica detallada sobre la arquitectura y teoría de SO.
- `README.md`: Este archivo guía.

## 🛠️ Cómo Utilizar

1. **Abrir el simulador**: Simplemente arrastra `simulador_paginacion.html` a cualquier navegador web moderno.
2. **Configurar parámetros**:
   - Ingresa el número de **Marcos** (RAM física).
   - Define la **Cadena de Referencia** (páginas solicitadas por la CPU).
   - (Opcional) Define los bits de escritura para el algoritmo NRU.
3. **Iniciar**: Haz clic en "Iniciar Simulación" o "Comparar Todos".
4. **Auditar**: Observa el **Kernel Event Monitor** en la parte inferior para entender las decisiones internas del OS.

## 🏗️ Detalles Técnicos

- **Arquitectura**: Single Page Application sin dependencias externas (Portabilidad Total).
- **Diseño**: Glassmorphism con Dark Mode premium.
- **Motor**: Algoritmos de complejidad lineal optimizados en JavaScript.

---
**Autor:** Cesar Andersson Saire Hancco | **Cód:** 141158  
Universidad Nacional de San Antonio Abad del Cusco (UNSAAC)  
*Ingeniería de Sistemas - Sistemas Operativos I*
