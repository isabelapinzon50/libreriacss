# libreriacss
Ejemplo lo hice con NES.css

Página de ejemplo que fue hecha con la librería CSS NES.css, que le da a la página web el estilo de un videojuego de 8 bits.

Librería

Nombre: NES.css. Página y demo: https://nostalgic-css.github.io/NES.css/ Repositorio: https://github.com/nostalgic-css/NES.css

Cómo se instala

No hay que descargar nada. Se agregan dos líneas link dentro del head del HTML: la primera trae la fuente pixel Press Start 2P que recomienda la librería (https://fonts.googleapis.com/css?family=Press+Start+2P) y la segunda es la librería en sí (https://unpkg.com/nes.css@2.3.0/css/nes.min.css).

Cómo la usé

NES.css funciona con clases: se escribe un elemento HTML normal, se le pone la clase y la librería le da el estilo. En index.html usé nes-container with-title para las cajas con título (is-dark la pone oscura); nes-btn para los botones, con is-primary, is-success, is-warning e is-error para los colores; nes-input y nes-checkbox para el formulario; nes-balloon para el globo de diálogo y nes-mario para el personaje, nes-progress para las barras y nes-icon con heart, star, coin y trophy para los iconos. En estilo.css solo puse el fondo, la fuente y los márgenes. Todo lo demás lo hace la librería.
