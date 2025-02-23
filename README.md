# Juego de Memoria - Encuentra las Parejas

## Descripción

Este proyecto es un juego de memoria interactivo en el que el jugador debe emparejar cartas iguales. El juego está desarrollado utilizando tecnologías web como HTML, CSS y JavaScript, y hace uso de una API REST pública para obtener las cartas del mazo.

### Características

- **Animación de Cartas:** Las cartas se voltean con una animación suave cuando el usuario las selecciona.
- **Temporizador:** Un temporizador registra el tiempo que tarda el jugador en completar el juego.
- **Contador de Intentos:** Se cuenta el número de intentos que realiza el jugador para emparejar todas las cartas.
- **Tabla de Líderes (Leaderboard):** Se muestra un ranking con los mejores resultados, ordenados por el menor número de intentos y el tiempo.
- **Pistas:** El jugador puede solicitar una pista que muestra todas las cartas durante 3 segundos.
- **Sonidos Interactivos:** Se reproducen sonidos diferentes para acciones como voltear cartas, acertar un par, cometer un error y ganar el juego.

---

## Tecnologías Utilizadas

- **HTML:** Estructura y contenido del juego.
- **CSS:** Estilización y diseño visual del juego, incluyendo animaciones.
- **JavaScript:** Lógica del juego, manejo de eventos y comunicación con la API REST.
- **API Deck of Cards:** Se utiliza para obtener cartas aleatorias.

---

## Cómo Jugar

1. Haz clic en "Iniciar Juego" para comenzar una nueva partida.
2. Las cartas se mostrarán durante 3 segundos al inicio para que puedas memorizarlas.
3. Selecciona dos cartas para intentar emparejarlas.
4. Si aciertas, las cartas permanecerán descubiertas.
5. Si fallas, las cartas se voltearán de nuevo y se reproducirá un sonido de error.
6. Usa el botón "Pista" para ver todas las cartas durante 3 segundos.
7. El juego termina cuando hayas emparejado todas las cartas.
8. Si tu resultado es mejor que los anteriores, tu puntuación aparecerá en la tabla de líderes.

---

## Leaderboard

El leaderboard muestra los 5 mejores resultados en términos de intentos y tiempo. Los datos se guardan localmente mediante `localStorage`, por lo que se mantienen al recargar la página.

---

## Efectos de Sonido

- **Voltear carta:** Reproduce un sonido cuando seleccionas una carta.
- **Acierto:** Reproduce un sonido al emparejar dos cartas correctamente.
- **Error:** Reproduce un sonido al fallar al emparejar dos cartas.
- **Victoria:** Reproduce un sonido especial cuando completas el juego.

---

## API Utilizada

Se ha utilizado la API pública "Deck of Cards" para obtener cartas aleatorias.

- **URL Base:** https://deckofcardsapi.com
- **Endpoint utilizado:** `/api/deck/new/shuffle/?deck_count=1` y `/api/deck/{deck_id}/draw/?count=8`

---

## Instalación y Ejecución

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador.
3. Disfruta del juego.

---

## Próximas Mejoras

- Añadir diferentes niveles de dificultad.
- Implementar un modo multijugador.
- Incluir más efectos visuales y de sonido.

---

## Contribución

Si deseas contribuir a este proyecto, no dudes en hacer un fork del repositorio y enviar tus mejoras mediante pull requests.

---

¡Gracias por jugar y que disfrutes encontrando las parejas!