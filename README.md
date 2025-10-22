# Proyecto de Videojuego - Jose Angel Rangel Rico

Este proyecto es un videojuego desarrollado en Unity con un enfoque en aprendizaje práctico. El objetivo principal es implementar un personaje controlable, animaciones, recolección de objetos, un sistema de sonido y un menú interactivo.

---

## Características principales

- **Control de personaje** con **Input System** (moverse, rotar, saltar).
- **Sistema de animaciones** (caminar, saltar).
- **Efectos de sonido** para pasos, salto y recolección de objetos.
- **Objetos coleccionables** que desaparecen al tocarlos y reproducen un audio.
- **Menú principal** con **botones interactivos** (Start, Options, Exit).

---

## Tutoriales (Proceso de desarrollo)

### 1. Lección 1: El Control del Jugador
- **Objetivo:** Entender y comprender sobre colisiones, movimiento de personaje y cámara.
- **Documentación:** [Enlace a la documentación](https://docs.google.com/document/d/17GhWPvg9m5N8NOr1JjQTFEEwiwraO8nh/edit?usp=drive_link&ouid=105520291992609403609&rtpof=true&sd=true)
- **Video demostrativo:** [Ver video](https://drive.google.com/file/d/1X3r73pwAXmXPdpKGwytD4hU-ssHnW_rh/view?usp=drive_link)
- **Archivo package:** [Descargar archivo](https://drive.google.com/file/d/1af-AxgdbNx7UfmRs6Y4_WzT_JYRQey-W/view?usp=drive_link)

### 2. Lección 2: Jugabilidad Básica
- **Objetivo:** Entender y comprender sobre colisiones, movimiento de personaje y cámara.
- **Documentación:** [Enlace a la documentación](https://docs.google.com/document/d/1RfeEr7dKQnGUsnZhdImbyx5YqDPeFNh7/edit?usp=drive_link&ouid=105520291992609403609&rtpof=true&sd=true)
- **Video demostrativo:** [Ver video](https://drive.google.com/file/d/1S0vvtZ8yx5avQodd_8Qc9wErtajQZ_zU/view?usp=drive_link)
- **Archivo package:** [Descargar archivo](https://drive.google.com/file/d/1ais7ye__7KD_znU0bbOBizssO4faBlfC/view?usp=drive_link)


### 3. Lección 3: Sonidos y Efectos
- **Objetivo:** Entender y comprender sobre colisiones, movimiento de personaje y cámara.
- **Documentación:** [Enlace a la documentación](https://docs.google.com/document/d/1o_94rTe5hDPtQswZPT9Q4wfIXhqbUH8A/edit?usp=drive_link&ouid=105520291992609403609&rtpof=true&sd=true)
- **Video demostrativo:** [Ver video](https://drive.google.com/file/d/1S0vvtZ8yx5avQodd_8Qc9wErtajQZ_zU/view?usp=drive_link)
- **Archivo package:** [Descargar archivo](https://drive.google.com/file/d/1nzYCCm93aTQPjclelh-tL3r2zs5o3AOd/view?usp=drive_link)
---

## Prácticas (Proceso de desarrollo)

### Práctica 01

**[Descripción de la práctica 1]**  


---

### Práctica 02


- **Objetivo:** Animar un personaje dentro de Unity usando modelo, rig y animaciones provenientes de Mixamo.
- **Documentación:** [Enlace a la documentación](https://drive.google.com/file/d/1b_1PV6rCMY4_XTCXiLGxGBrcudcFOkI6/view?usp=drive_link)
- **Video demostrativo:** [Ver video](https://drive.google.com/file/d/1TieiqmMRpeAmGs0E6FwfuzUww57KlB-w/view?usp=drive_link)

---

### Práctica 03



- **Objetivo:** Crear un menú interactivo.
- **Documentación:** [Enlace a la documentación](https://docs.google.com/document/d/1O5dUwhWRA6sA626mP2FwNq19qmoxUrCf/edit?usp=drive_link&ouid=105520291992609403609&rtpof=true&sd=true)
- **Video demostrativo:** [Ver video](https://drive.google.com/file/d/1Qxb9T2IfdG0tX_56TiVerKQWZXbesu3R/view?usp=drive_link)

---

## Lecciones aprendidas

### Animaciones
- Usar **Trigger** en lugar de **Bool** evita bucles innecesarios, especialmente en animaciones como el salto.
- La configuración de **transiciones** en el **Animator** es esencial para una experiencia fluida.

### Sonido
- El componente **AudioSource** facilita la integración de sonidos en Unity.
- Es recomendable desactivar **Play On Awake** para evitar sonidos no deseados al iniciar la escena.
- Controlar los métodos **Play()**, **Pause()** y **Stop()** según el contexto de uso.

### UI en Unity
- Los menús se construyen fácilmente con el sistema de **Canvas** y **Buttons**.
- Los eventos **OnClick()** permiten vincular acciones del código sin necesidad de escribir lógica adicional.

### Escenas
- Separar la **Main Menu Scene** de la **Game Scene** mejora la organización y facilita las transiciones.

### Buenas prácticas
- Nombrar parámetros de animación de forma clara: `IsJumping`, `Speed`, `Jump`, etc.
- Centralizar la lógica del personaje en un único script (**PlayerController**).
- Documentar cada paso del desarrollo para mantener el control y facilitar el seguimiento del proyecto.

---

## Licencia

Este proyecto está disponible bajo la licencia **Creative Commons CC-BY**.  
Puedes usarlo, modificarlo y compartirlo, siempre y cuando otorgues el crédito correspondiente al autor original.

---

Proyecto documentado con lecciones y aprendizajes prácticos.
