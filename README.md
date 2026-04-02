# La Caja de Pandora

> **⚠️ ¡¡ Cuidado con Abrir la Caja de Pandora !! ⚠️**

## 📖 Sobre el Proyecto

**La Caja de Pandora** es un entorno de entrenamiento en ciberseguridad gamificado tipo *Capture The Flag* (CTF). Este proyecto ha sido desarrollado como Trabajo Fin de Grado (TFG) para el Grado en Ingeniería de la Ciberseguridad de la Universidad Rey Juan Carlos (URJC).

El objetivo principal del proyecto es reducir la brecha existente entre la teoría académica y la práctica profesional, ofreciendo una experiencia de aprendizaje inmersiva que fusiona desafíos técnicos avanzados con una narrativa cohesiva de espionaje industrial basada en el "Proyecto Tártaro-81". A diferencia de los entornos de entrenamiento tradicionales con retos aislados, esta máquina simula un sistema "vivo" y comprometido.

## 🎯 Desafíos y Tecnologías

Los participantes deben ejecutar un ciclo completo de auditoría técnica y análisis forense. El entorno está diseñado alineado con tácticas del marco MITRE ATT&CK, cubriendo las siguientes disciplinas:

* **Enumeración y Acceso Inicial:** Reconocimiento de servicios e ingeniería inversa de documentos ofimáticos (* Spearphishing*) con macros maliciosas.
* **Evasión de Defensas:** Manipulación temporal del sistema (*Timestomping*) para eludir controles de acceso lógicos.
* **Forense y Esteganografía Multimedia:** Análisis de canales de datos ocultos en espectrogramas de audio, metadatos y fotogramas de vídeo.
* **Criptografía y Escalada de Privilegios:** Explotación de binarios SUID mediante ataques de colisión de hashes matemáticos e identificación de canales de Mando y Control (C2).

**Infraestructura como Código (IaC):** Todo el entorno virtual ha sido orquestado y provisionado de forma automatizada mediante Vagrant y Bash.

## 🚀 Cómo Empezar (Despliegue)

Puedes desplegar la infraestructura de "La Caja de Pandora" utilizando cualquiera de las siguientes opciones:

* **Opción A - Máquina Virtual (OVA):** Lista para importar y jugar directamente.
    👉 [Enlace a la OVA](https://drive.google.com/file/d/147NTLGTGJdeslHjhHYT7yX2x9rR7O0YX/view?usp=sharing)
* **Opción B - Despliegue Manual (Carpeta Vagrant):** Para aprovisionar el entorno desde cero e inspeccionar la orquestación.
    👉 [Enlace a la Carpeta Vagrant](https://drive.google.com/file/d/15GIlAJ-b0XUTZCxqzvPTeO9B7UBvhrw6/view?usp=sharing)

## 📂 Contenido del Repositorio

* `README.md`: Este documento introductorio.
* `TFG_GICIB___Luis_Ortiz.pdf`: Memoria exhaustiva del Trabajo Fin de Grado. En este documento se detalla toda la filosofía de diseño y la arquitectura de la infraestructura. Además, cuenta con un apéndice final que incluye un *Walkthrough* (Guía de Resolución) paso a paso, por si te quedas atascado durante la intrusión.

## 👨‍💻 Autor

* **Autor:** Luis Ortiz Fernández
* **Tutor:** Raúl Martín Santamaría
