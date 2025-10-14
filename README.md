
# Proyecto de Videojuego

Este proyecto es un videojuego desarrollado en Unity con enfoque en aprendizaje práctico.  
El objetivo principal es implementar un personaje controlable, animaciones, recolección de objetos, un sistema de sonido y un menú interactivo.

---

##  Características principales
- Control de personaje con **Input System** (moverse, rotar, saltar).
- Sistema de **animaciones** (caminar, saltar).
- Efectos de **sonido** para pasos, salto y recolección de objetos.
- Objetos **coleccionables** que desaparecen al tocarlos y reproducen un audio.
- Menú principal con **botones interactivos** (Start, Options, Exit).

---

##  Tutoriales (proceso de desarrollo)

1. **Lección 1 El Control del Jugador**
   
Objetivo: Entender y comprender sobre coliciones, movimiento de personaje y camara
Documentacion: https://docs.google.com/document/d/17GhWPvg9m5N8NOr1JjQTFEEwiwraO8nh/edit?usp=drive_link&ouid=105520291992609403609&rtpof=true&sd=true
Video demostrativo: https://drive.google.com/file/d/1X3r73pwAXmXPdpKGwytD4hU-ssHnW_rh/view?usp=drive_link
archivo package: https://drive.google.com/file/d/1af-AxgdbNx7UfmRs6Y4_WzT_JYRQey-W/view?usp=drive_link


   
##  Practicas (proceso de desarrollo)

Practica 01

Practica 02
<img width="1214" height="684" alt="Captura2" src="https://github.com/user-attachments/assets/5122b5ad-7db3-4b91-b5b6-ebaa1e59ebe6" />

Objetivo: Animar un persoaje dentro de unity usando modelo, rig y animaciones provenientes de mixamo
Documentacion: https://drive.google.com/file/d/1b_1PV6rCMY4_XTCXiLGxGBrcudcFOkI6/view?usp=drive_link
Video demostrativo: https://drive.google.com/file/d/1TieiqmMRpeAmGs0E6FwfuzUww57KlB-w/view?usp=drive_link

Practica 03

<img width="542" height="306" alt="image" src="https://github.com/user-attachments/assets/51c987c4-0286-4c4d-8acc-b4c703057aa1" />


Objetivo: Crear un menu interactivo
Documentacion: https://docs.google.com/document/d/1O5dUwhWRA6sA626mP2FwNq19qmoxUrCf/edit?usp=drive_link&ouid=105520291992609403609&rtpof=true&sd=true
Video demostrativo: https://drive.google.com/file/d/1Qxb9T2IfdG0tX_56TiVerKQWZXbesu3R/view?usp=drive_link
---

##  Lecciones aprendidas

- **Animaciones:**  
  Usar Trigger en lugar de Bool evita bucles innecesarios, especialmente en animaciones como el salto.
  La configuración de transiciones en el Animator es esencial para una experiencia fluida.

- **Sonido:**  
  El componente AudioSource facilita la integración de sonidos en Unity.
Es recomendable desactivar Play On Awake para evitar sonidos no deseados al iniciar la escena.

Controlar los métodos Play(), Pause() y Stop() según el contexto de uso.

- **UI en Unity:**  
  Los menús se construyen fácilmente con el sistema de Canvas y Buttons.
  Los eventos OnClick() permiten vincular acciones del código sin necesidad de escribir lógica adicional.  

- **Escenas:**  
  Separar la Main Menu Scene de la Game Scene mejora la organización y facilita las transiciones.

- **Buenas prácticas:**  
  Nombrar parámetros de animación de forma clara: IsJumping, Speed, Jump, etc.
  Centralizar la lógica del personaje en un único script (PlayerController).
  Documentar cada paso del desarrollo para mantener el control y facilitar el seguimiento del proyecto.

---

##  Licencia
Este proyecto está disponible bajo la licencia Creative Commons CC-BY.
Puedes usarlo, modificarlo y compartirlo, siempre y cuando otorgues el crédito correspondiente al autor original.
---
 Proyecto documentado con lecciones y aprendizajes prácticos.  
