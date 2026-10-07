# Feliz año, mi amor — Carlos e Iyana

Un recorrido interactivo de 12 capítulos. Incluye las fotos, las cinco pruebas de convivencia, la captura del primer like, las conversaciones, la historia de julio y el vídeo de la ruta en MP4. Las imágenes se guardaron en JPG para que se vean bien en móviles y ordenadores.

## Abrir

- `preview.html` lleva las fotos y el vídeo dentro del propio archivo: ábrelo directamente en un navegador. No necesita internet, salvo el reproductor de Spotify.
- `index.html` usa los ficheros de `assets/` y es la versión para publicar. Sube **el contenido completo de esta carpeta** a la raíz de un repositorio en GitHub Pages. Las rutas con `#` funcionan sin configurar redirecciones.

En el móvil puedes desplazarte normalmente para llegar al juego de cada capítulo. Usa las flechas inferiores, el índice o desliza hacia los lados sobre el texto o la foto para pasar al siguiente. Toca las fotos para ampliarlas. Gira la ruleta de junio, descubre la foto de la mano tras la cola, empareja las cinco pruebas de convivencia y desbloquea el vídeo al acertar las cuatro preguntas de la ruta.

## Cuestionario y mensaje final

La clave del cuestionario está en `assets/app.js`, dentro de `initRouteQuiz` (`const key=[0,1,1,2]`, donde 0=a, 1=b y 2=c). La combinación es **a, b, b, c**, como en la captura que enviaste.

## Editar el mensaje final

Abre `assets/story.js` y busca el capítulo con `id:'final'`. Cambia el texto dentro de `text:['…']`. Puedes retocar de la misma forma los otros capítulos. Si cambias algo, usa `index.html`; `preview.html` es una copia ya empaquetada y habría que generarla otra vez.

## Música y privacidad

El botón «Julio» abre Spotify para reproducir «Spanish Girl». Los navegadores requieren una pulsación para empezar el sonido. Un enlace público a esta web dejaría accesibles las fotos, capturas y el vídeo a cualquiera con el enlace: elige tú dónde compartirla.

Las fotos y el vídeo proceden del ZIP proporcionado. La página no necesita servidor ni dependencias para funcionar.
