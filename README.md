# Eurobot 2027 - STAR UMA

Este repositorio actúa como el punto central de coordinación y gestión para el desarrollo del robot participante en Eurobot 2027. Aquí no se aloja código fuente, sino la estructura del proyecto y los enlaces a los distintos sub-dominios.

## 📌 Gestión del Proyecto

Todo el seguimiento de tareas, asignación de responsabilidades y estado actual del desarrollo se gestiona a través de nuestro tablero global:
* [Tablero Kanban Global de Eurobot 2027](enlace_al_project_de_github)

## 🚀 Guía de Inicio Rápido (Full Stack)

Si eres un gestor o un desarrollador que necesita acceso a todo el ecosistema (Hardware, Software, Firmware y Docs), sigue estos pasos:

1. **Prerrequisitos**: Instala la herramienta `vcstool` (estándar en ROS 2):
   ```bash
   sudo apt pull python3-vcstool
   ```

2. **Clonar y Desplegar**:
   ```bash
   # 1. Clona el repositorio central
   git clone https://github.com/star-uma/eurobot2027.git
   cd eurobot2027

   # 2. Importa todos los sub-repositorios en la carpeta raíz
   vcs import .. < eurobot2027_full.repos
   ```

3. **Mantenerse actualizado**: Para descargar los últimos cambios de todos los repositorios a la vez:
   ```bash
   vcs pull ..
   ```

---

## 🏗️ Arquitectura de Repositorios

El proyecto está dividido de forma modular para aislar entornos y facilitar el trabajo en paralelo de las distintas disciplinas:

### ⚙️ Hardware y Mecánica
Contiene todos los modelos 3D, ensamblajes, esquemas electrónicos y PCBs.
* [eurobot2027_hardware_mecanica](https://github.com/star-uma/eurobot2027_hardware_mecanica.git) - CAD y piezas estructurales.
* [eurobot2027_hardware_electronica](https://github.com/star-uma/eurobot2027_hardware_electronica.git) - Placas, ruteo y listas de materiales.

### 💻 Software y Control (ROS 2)
El ecosistema de software está distribuido. Para instalar el robot completo, dirígete al meta-repositorio de software.
* [eurobot2027_software](https://github.com/star-uma/eurobot2027_software.git) - **Meta-repositorio (Inicio rápido e instalación).**
* [eurobot2027_software_vision](https://github.com/star-uma/eurobot2027_software_vision.git) - Paquetes de visión artificial.
* [eurobot2027_software_control](https://github.com/star-uma/eurobot2027_software_control.git) - Nodos de control y navegación.
* [eurobot2027_software_simulacion](https://github.com/star-uma/eurobot2027_software_simulacion.git) - Entornos virtuales y modelo URDF en Gazebo.
* [eurobot2027_firmware_esp32](https://github.com/star-uma/eurobot2027_software_firmware_esp32.git) - Código de bajo nivel para microcontroladores.

### 📚 Documentación
Manuales generales, normativas del equipo y archivos de referencia.
* [eurobot2027_documentacion](https://github.com/star-uma/eurobot2027_documentacion.git) - Reglamentos, arquitectura general y guías de onboarding.

---
*Para nuevos miembros: Por favor, dirígete al repositorio de Documentación y lee la guía de Onboarding antes de solicitar acceso a los repositorios de código o diseño.*
