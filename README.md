# 🎰 Ruleta Multiplayer Realtime

Una plataforma web interactiva y dinámica diseñada para tomar decisiones, realizar sorteos o jugar de manera conjunta y 100% sincronizada en tiempo real. Olvídate de compartir pantalla o de aplicaciones donde cada usuario ve un resultado diferente; este producto une a las personas en una única sala virtual donde la emoción del giro se vive al unísono.

---

## 🎯 ¿Qué es este producto?

**Ruleta Multiplayer** es una herramienta recreativa y de toma de decisiones colectivas en la que un administrador (*Host*) puede crear salas de juego personalizadas mediante códigos únicos de acceso rápido. El producto destaca por su fluidez técnica, su transparencia matemática y una interfaz responsiva de estética nocturna (*Dark Mode*) con detalles neón, ideal para comunidades de jugadores, creadores de contenido, dinámicas de grupo o decisiones rápidas entre amigos.

---

## ✨ Características Principales

### 🔄 Sincronización Absoluta Multijugador
Gracias a una arquitectura conectada en tiempo real, cada milisegundo de animación, el frenado de la rueda, las explosiones de confeti y el veredicto final se replican exactamente igual en las pantallas de todos los participantes conectados, sin importar si acceden desde un ordenador o un dispositivo móvil.

### 👑 Gestión de Roles Inteligente
- **El Creador (Host):** Tiene el control total del Tablero de Mandos. Puede añadir opciones sobre la marcha, asignar colores personalizados, eliminar alternativas y accionar el botón de giro.
- **Los Invitados (Espectadores):** Visualizan el listado de participantes activos, chatean indirectamente viendo las actualizaciones de la sala y experimentan la emoción del giro de forma pasiva pero integrada.

### 📍 Puntero Físico y Transparencia Visual
A diferencia de otras ruletas virtuales donde el ganador aparece simplemente en un cartel de texto de forma arbitraria, este producto cuenta con un **puntero estático superior (flecha rosa neón)**. El motor físico de deceleración está calibrado de forma milimétrica con la geometría del círculo; la cuña que se detiene físicamente bajo la punta de la flecha es, con total precisión, el resultado que proclama el sistema.

### 🎨 Accesibilidad y Contraste Inteligente (Algoritmo YIQ)
El producto autoajusta su diseño para garantizar la máxima legibilidad:
- Si el administrador crea una opción con un fondo muy claro o blanco puro, el sistema detecta el brillo en tiempo real y **cambia automáticamente el color del texto a negro** tanto en la cuña del lienzo como en el banner superior de victoria.
- Las opciones oscuras mantienen su texto en blanco de alto contraste, logrando una estética limpia y legible sin importar las combinaciones de colores elegidas.

### 🎉 Experiencia Inmersiva y Gamificación
- **Efecto de Inercia (*Ease-Out*):** La ruleta imita el comportamiento de una rueda física pesada, comenzando rápido y perdiendo velocidad gradualmente para generar suspense.
- **Feedback Dinámico:** El puntero superior vibra y late de forma activa mientras la ruleta está en movimiento.
- **Celebración Colectiva:** Al detenerse la rueda, el sistema bloquea los controles temporalmente y detona una lluvia de confeti en las pantallas de todos los usuarios de la sala para celebrar el resultado.

---

## 💎 Valor Añadido del Diseño

- **Arquitectura Segura:** El producto restringe las peticiones del servidor para responder exclusivamente desde entornos autorizados, bloqueando cualquier intento de manipulación externa del código de la sala.
- **Cero Elementos de Distracción:** Interfaz limpia, enfocada en el juego, libre de publicidad pesada y optimizada para un rendimiento fluido de 60 FPS en el renderizado del lienzo (*Canvas*).

---

## ✒️ Diseñado por **PollitoScripts**
Desarrollado con pasión por **PollitoScripts**. Una solución moderna para digitalizar los clásicos sorteos de la forma más transparente, justa y divertida posible. ¡Crea tu sala, comparte el código y que decida la suerte! 🚀🎰
