# Eurobot 2027 - [Nombre de la Universidad/Equipo]

Este repositorio actúa como el punto central de coordinación y gestión para el desarrollo del robot participante en Eurobot 2027. Aquí no se aloja código fuente, sino la estructura del proyecto y los enlaces a los distintos sub-dominios.

## 📌 Gestión del Proyecto

Todo el seguimiento de tareas, asignación de responsabilidades y estado actual del desarrollo se gestiona a través de nuestro tablero global:
* [Tablero Kanban Global de Eurobot 2027](enlace_al_project_de_github)

## 🏗️ Arquitectura de Repositorios

El proyecto está dividido de forma modular para aislar entornos y facilitar el trabajo en paralelo de las distintas disciplinas:

### ⚙️ Hardware y Mecánica
Contiene todos los modelos 3D, ensamblajes, esquemas electrónicos y PCBs.
* [eurobot2027_hardware_mecanica](enlace) - CAD y piezas estructurales.
* [eurobot2027_hardware_electronica](enlace) - Placas, ruteo y listas de materiales.

### 💻 Software y Control (ROS 2)
El ecosistema de software está distribuido. Para instalar el robot completo, dirígete al meta-repositorio de software.
* [eurobot2027_software](enlace) - **Meta-repositorio (Inicio rápido e instalación).**
* [eurobot2027_software_vision](enlace) - Paquetes de visión artificial.
* [eurobot2027_software_control](enlace) - Nodos de control y navegación.
* [eurobot2027_software_simulacion](enlace) - Entornos virtuales y modelo URDF en Gazebo.
* [eurobot2027_firmware_esp32](enlace) - Código de bajo nivel para microcontroladores.

### 📚 Documentación
Manuales generales, normativas del equipo y archivos de referencia.
* [eurobot2027_documentacion](enlace) - Reglamentos, arquitectura general y guías de onboarding.

---
*Para nuevos miembros: Por favor, dirígete al repositorio de Documentación y lee la guía de Onboarding antes de solicitar acceso a los repositorios de código o diseño.*
