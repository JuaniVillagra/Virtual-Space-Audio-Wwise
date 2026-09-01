# 🔊 Virtual Space Audio — Wwise & Unity

> Proyecto académico de diseño e implementación de audio interactivo
> para un espacio virtual utilizando Wwise y Unity.

## 🎧 Sobre el proyecto

Proyecto centrado en el diseño e implementación de audio interactivo
dentro de un espacio virtual, utilizando Wwise como herramienta
principal de diseño y gestión de audio e integrándolo con Unity.

El objetivo fue crear una experiencia sonora dinámica y espacializada,
vinculando diferentes elementos del entorno con sistemas de audio
interactivo.

## 🛠️ Tecnologías

- Unity
- Wwise
- C#
- Reaper
- Git / GitHub

## 👨‍💻 Trabajo realizado

- Integración de Wwise con Unity para implementar y controlar el audio
  interactivo dentro del entorno virtual.
- Implementación de eventos de audio asociados a diferentes
  interacciones del jugador.
- Diseño y organización de contenido sonoro mediante diferentes tipos
  de Containers.
- Implementación de audio espacializado y posicionamiento 3D de
  diferentes fuentes sonoras.
- Diseño de efectos de sonido mediante múltiples capas y grabaciones
  Foley.
- Implementación de sistemas de música interactiva mediante
  remezcla vertical.

## 🔊 Implementación de Audio

### Events

Implementación de eventos de audio en Wwise para controlar la
reproducción de sonidos a partir de diferentes interacciones dentro
del entorno virtual.

Se utilizaron eventos asociados a acciones del jugador, incluyendo
interacciones mediante Click Mouse y Trigger/Collider.

### Containers

Se utilizaron diferentes tipos de Containers para organizar y
controlar el contenido sonoro:

- **Blend Container:** utilizado para combinar diferentes capas de
  sonido ambiental y generar un ambiente dinámico.
- **Random Container:** utilizado para reproducir diferentes
  variaciones de efectos de sonido, evitando una repetición constante
  de la misma muestra.
- **Music Playlist Container:** utilizado para organizar las
  composiciones musicales y controlar su reproducción.

### Audio 3D

Implementación de espacialización y posicionamiento 3D de diferentes
fuentes sonoras dentro del entorno virtual.

Los sonidos fueron ubicados en objetos del escenario para generar una
percepción de dirección y distancia, modificando su comportamiento
según la posición del jugador.

### 🎵 Música interactiva

Implementación de un sistema de **remezcla vertical** para adaptar la
música según el recorrido y las decisiones del jugador.

El sistema utiliza diferentes capas musicales que se combinan
dinámicamente para modificar la composición durante la experiencia.

### 🎙️ Diseño de SFX

Diseño de efectos de sonido mediante múltiples capas y grabaciones
Foley, trabajando posteriormente el procesamiento y la mezcla de los
elementos sonoros.

## 📚 Documentación

- 📄 [Documentación del proyecto](Informe_Virtual_Space_Audio_WWhise.pdf)

## ▶️ Requisitos

- Unity: version 2023.2.22f1.
- Wwise: versión 2023.1.16.
