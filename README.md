# Lo que dice y lo que hace

Landing de la Segunda evaluación de Elementos de Psicología (FADU-UBA, 2026), Grupo 3.
Una prueba de 30 segundos y cuatro recortes de la entrevista a Diego Villarroel, diseñador UX/UI.

- `index.html`: toda la página (HTML, CSS y JavaScript, sin build ni dependencias que instalar).
- `audio/`: los cuatro recortes de la entrevista (`a.mp3`, `b.mp3`, `c.mp3`, `d.mp3`).
- `vendor/idiomorph.min.js`: librería chica que actualiza la pantalla sin reiniciar las animaciones.

Las tipografías (Saira Extra Condensed, Figtree, IBM Plex Mono) se cargan desde Google Fonts.
Las animaciones de scroll funcionan en Chrome/Edge; en Safari y Firefox la página se ve igual pero sin ese efecto.

## Para verla en local
Abrir una terminal en esta carpeta y correr `python3 -m http.server 8000`, y entrar a http://localhost:8000.
(Si se abre `index.html` con doble clic los audios pueden no sonar, según el navegador.)
