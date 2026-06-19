#Asistente: Jarvis.

Jarvis es un asistente personal modular ejecutado sobre una Raspberry Pi 4 basado en Ollama, diseñado no solo para ayudarte en tareas cotidianas, sino también para ofrecer una experiencia de interacción más cercana y personalizada.

El sistema permite comunicarse mediante voz y texto, utilizar modelos de inteligencia artificial locales o en la nube, interactuar con dispositivos domóticos y representar visualmente su estado interno a través de un sistema de emociones simuladas en tiempo real.

A diferencia de los asistentes tradicionales, el objetivo principal de Jarvis no es convertirse en otro asistente genérico, sino en una entidad digital con personalidad propia capaz de mantener conversaciones naturales, reaccionar emocionalmente al contexto e incluso enfadarse contigo si decides poner a prueba su paciencia.

Características principales
 - Cambio dinámico de modelos de IA (LLM) directamente desde la interfaz.

 - Compatibilidad con modelos locales y servicios en la nube.

 - Sistema de emociones contextuales con representación visual en tiempo real.

 - Visualización gráfica mediante expresiones, colores y estados emocionales.

 - Interacción por voz utilizando síntesis de voz local.

 - Integración con dispositivos domóticos.

 - Monitorización del estado interno del sistema en tiempo real.

 - Interfaz táctil para el control de aplicaciones y funciones del sistema.

 - Arquitectura modular desacoplada entre lógica e interfaz visual.

 - Sistema de personalidad configurable y comportamiento emocional dinámico.

Jarvis no pretende ser únicamente una herramienta. Su objetivo es convertirse en un compañero digital con el que interactuar de forma natural cada día.

## 1. Diseño Visual e Interfaz de Usuario

* Modelo 3D de Jarvis

Jarvis se representa mediante una calavera 3D (formato .obj) renderizada en tiempo real utilizando caracteres ASCII. Esta decisión no fue únicamente estética; surgió de la propia naturaleza del sistema. Al estar basado en modelos de lenguaje que se comunican principalmente a través de texto, la representación mediante caracteres ASCII me pareció una forma coherente de visualizar la inteligencia artificial.

Además de reforzar la identidad visual del proyecto, este enfoque permite crear una interfaz ligera, fácilmente personalizable y estrechamente ligada a la esencia de Jarvis: una entidad digital construida a partir de texto que cobra vida a través de la interacción con el usuario.

* Sistema de expresiones y emociones

Sistema de Expresiones y Emociones

Jarvis dispone de un sistema emocional configurable diseñado para adaptar el equilibrio entre rendimiento, consumo de recursos y profundidad de interacción. Actualmente existen tres modos de funcionamiento:

OFF. El sistema emocional permanece completamente desactivado. En este modo, Jarvis responde sin procesamiento emocional adicional, priorizando la velocidad de respuesta y reduciendo al mínimo el consumo de recursos del sistema.

LITE. Modo basado en un motor de detección por palabras clave. El sistema analiza determinados términos y expresiones asociadas a estados emocionales (felicidad, tristeza, enfado, miedo, etc.) y utiliza dicha información para modificar la representación visual y el comportamiento general de Jarvis.

Este modo ofrece una respuesta rápida con un impacto mínimo en el rendimiento.

FULL. Modo emocional avanzado. 
Además del motor de palabras clave utilizado en el modo LITE, Jarvis incorpora un segundo proceso denominado BrainEmotion, basado en el mismo modelo de lenguaje utilizado por el sistema principal. Antes de que la consulta llegue al motor conversacional, el mensaje es procesado por este módulo emocional, que analiza:

El mensaje del usuario.
El contexto de la conversación.
La memoria disponible.
El estado actual del sistema.
La personalidad configurada de Jarvis.

Como resultado, se genera un estado emocional contextual que es enviado tanto a la interfaz como al motor principal de conversación.

Gracias a este enfoque, las emociones dejan de depender únicamente de palabras concretas y pasan a surgir del contexto completo de la conversación. La principal desventaja de este modo es el aumento del consumo de recursos y de la latencia, ya que cada interacción requiere una consulta adicional al modelo de lenguaje para calcular el estado emocional antes de generar la respuesta final.

* Interfaz principal
* Chat fullscreen
* Sistema de colores emocionales
* Animaciones y efectos visuales
* Sistema de ventanas y aplicaciones
* Interfaz táctil

---

## 2. Arquitectura del Sistema

* Separación Brain / UI
* Sistema de eventos y comunicación interna
* Gestión de estados
* Integración de modelos IA
* Sistema Local / Cloud
* Motor emocional (BrainEmotion)
* Gestión de memoria y contexto
* Modularidad y escalabilidad

---

## 3. Funcionalidades Principales

* Conversación por voz y texto
* Cambio dinámico de modelos IA
* Sistema emocional contextual
* Síntesis de voz local
* Domótica e integración con hardware
* Gestión de aplicaciones
* Configuración avanzada del sistema
* Monitorización en tiempo real
* Sistema de migración de modelos
* Personalización de Jarvis

---

## 4. Resultado Final

* Objetivos alcanzados
* Rendimiento en Raspberry Pi 4
* Experiencia de usuario
* Comportamiento emocional
* Casos de uso reales
* Evolución del proyecto
* Lecciones aprendidas
* Futuras versiones
