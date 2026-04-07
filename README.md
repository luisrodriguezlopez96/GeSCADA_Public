<div align="center">

# ⚡ GeSCADA
### Suite de Ingeniería para WinCC

**Automatización inteligente del flujo TIA Portal → WinCC**

*Centro de mando para ingenieros de automatización: elimina la creación manual de archivos,*
*asegura la integridad de los datos y ofrece herramientas de diagnóstico avanzadas.*

[![Estado](https://img.shields.io/badge/Estado-Activo-brightgreen?style=for-the-badge)](https://github.com/luisrodriguezlopez96/GeSCADA_Public)
[![Plataforma](https://img.shields.io/badge/Plataforma-WinCC%20V8.1-blue?style=for-the-badge&logo=siemens)](https://github.com/luisrodriguezlopez96/GeSCADA_Public)
[![TIA Portal](https://img.shields.io/badge/TIA%20Portal-Compatible-orange?style=for-the-badge)](https://github.com/luisrodriguezlopez96/GeSCADA_Public)
[![Web](https://img.shields.io/badge/Web-Live-blueviolet?style=for-the-badge)](https://luisrodriguezlopez96.github.io/GeSCADA_Public/)

</div>

---

## 🏭 Origen del Proyecto

**Construido en producción, no en un laboratorio.**

GeSCADA nació durante proyectos reales de automatización SCADA. Después de horas y horas mapeando SCADA en mi trabajo en **Clauger**, empecé a ver siempre los mismos cuellos de botella: exportabas el Excel de TIA Portal, procesabas miles de variables a mano, calculabas offsets de memoria, configurabas alarmas una a una y generabas la preconfiguración gráfica de decenas de equipos — copiando y pegando, uno por uno.

Lo que empezó como hojas de cálculo para acelerar el proceso, acabó convirtiéndose en una aplicación completa. Porque los Excel también tenían límites.

Hoy GeSCADA automatiza el flujo completo: importa y mapea el proyecto desde TIA Portal, genera automáticamente la preconfiguración gráfica y las estructuras de variables de cada equipo, gestiona las alarmas con detección de cambios entre revisiones y produce toda la infraestructura operativa del SCADA.

---

## 🛠️ Módulos de la Suite

GeSCADA se compone de 7 módulos técnicos diseñados para cubrir todo el ciclo de vida de la ingeniería SCADA:

### 1. 🔍 Mapeador WinCC

Motor de ingesta que convierte el Excel de TIA Portal en una estructura limpia y validada para WinCC. Detecta automáticamente las estructuras de variables, resuelve los offsets de memoria DB y normaliza los nombres de los tags — sin intervención manual, sin errores de tipado. Es la fuente de verdad para el resto de la suite.

### 2. 📋 Data Hub (Visor de Tags)

Auditoría completa del proyecto SCADA en una interfaz tipo Excel. Muestra en tiempo real el estado de todas las variables, detecta inconsistencias — huérfanas, duplicadas, historizadas — y emite un score de calidad del proyecto. Exportable directamente a WinCC o Excel.

### 3. 🔧 Compresores 2.0

Generador especializado para compresores — los equipos con mayor densidad de variables en una instalación frigorífica. Analiza el mapeado TIA, valida la existencia de cada variable en tiempo real y genera en bloque: la preconfiguración gráfica de cada equipo, las estructuras de variables listas para importar en WinCC y sus variables base asociadas.

### 4. ❄️ Generador de Servicios de Frío

Detecta automáticamente los espacios refrigerados del proyecto — cámaras, salas, túneles — identificando estructuras de variables repetidas en el mapeado TIA. Por cada uno genera: la preconfiguración gráfica con autoajuste de rango de temperatura, las estructuras de variables listas para importar en WinCC y sus variables base. Todo en bloque, sin configuración manual.

### 5. 📈 Generador de Gráficos Automático

Analiza el mapeado de variables del proyecto y detecta automáticamente los elementos comunes de la instalación: bombas, separadores, condensadores y otros equipos auxiliares. Localiza las variables necesarias para cada uno y genera en bloque la preconfiguración gráfica lista para WinCC — sin tocar un archivo a mano.

### 6. 🚨 Gestor de Alarmas

Gestiona el ciclo de vida de las alarmas del proyecto. Compara revisiones en tiempo real, detecta qué alarmas son nuevas, modificadas o eliminadas, y gestiona automáticamente el Bit-Swapping de Siemens — una de las fuentes de error más comunes en proyectos WinCC a gran escala.

### 7. ⚙️ Scripts de Sistema

Genera la infraestructura operativa del SCADA: scripts de arranque y cierre ordenado del Runtime, rutinas de backup automatizadas y tareas programadas de Windows — todo configurable y repetible entre instalaciones.

---

## 🚀 Roadmap 2026

- ✅ **v2.0.1 (Actual):** Servicios de Frío, Validación TIA, Hotfixes de robustez.
- ⏳ **v2.1 (En curso):** Logging estructurado y suite de tests automatizados.
- 🔭 **v2.2 (Planificado):** Integración nativa con Git para control de versiones de proyectos WinCC.
- 🔌 **v2.3 (Exploración):** Nuevas integraciones con entornos de programación de otras marcas comerciales de PLC, más allá de TIA Portal.

---

## 🌍 Landing Page

Puedes ver la presentación visual completa en:
👉 **[luisrodriguezlopez96.github.io/GeSCADA_Public/](https://luisrodriguezlopez96.github.io/GeSCADA_Public/)**

---

## ℹ️ Sobre este repositorio

Este repositorio es la **presentación pública** de GeSCADA. El código fuente es propietario. El objetivo es documentar las capacidades técnicas y el valor que aporta a la ingeniería de automatización industrial.

<div align="center">

**¿Interesado en saber más?**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Contactar-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/luisrodriguezlopez96)
[![GitHub](https://img.shields.io/badge/GitHub-luisrodriguezlopez96-181717?style=for-the-badge&logo=github)](https://github.com/luisrodriguezlopez96)

</div>
