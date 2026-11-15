# RPH Carrera 2.0

Modo carrera de futbolista en español, ejecutado directamente en el navegador.

## Cómo jugar

1. Abre `index.html` desde el repositorio o publica el proyecto con GitHub Pages siguiendo las instrucciones de abajo.
2. Crea tu futbolista, elige una de las posiciones disponibles, nacionalidad, edad inicial (15+) y club.
3. Juega los partidos con decisiones interactivas o usa la simulación rápida.
4. Entrena atributos, gestiona tu energía, revisa ofertas de fichaje y sigue tu carrera internacional.
5. Guarda tu progreso o exporta un archivo JSON como copia de seguridad.

## Funciones incluidas

- Carrera de club con los 20 clubes del proyecto y dos divisiones.
- Creación de futbolista con edades desde 15 años y las posiciones disponibles en el selector.
- Partidos interactivos y simulación rápida.
- Entrenamiento y mejora de atributos.
- Mercado de fichajes con ofertas y cambios de club.
- Clasificación, calendario, ascensos y descensos.
- Carrera con selección nacional, clasificatorias y torneos continentales y mundiales.
- Gala de premios, nominaciones, podios y palmarés histórico.
- Gestión de energía, lesiones, tarjetas amarillas, acumulación de amarillas y suspensiones.
- Guardado automático en el navegador, botón de guardado manual, carga, exportación e importación de partidas JSON.

## Guardados

El guardado automático se almacena en el almacenamiento local del navegador en el que juegas. Si borras los datos del sitio, cambias de navegador o de dispositivo, ese guardado local no se transfiere. Para conservar tu carrera, usa **Exportar partida** y guarda el archivo JSON. En otro navegador o dispositivo, abre el juego y usa **Importar partida**.

## Publicación

El proyecto está preparado como una página estática. Para publicarlo con GitHub Pages, entra en **Settings → Pages**, selecciona la rama `main` y la carpeta `/ (root)`, y guarda los cambios.

## Dependencias

El juego carga Tailwind CSS, Google Fonts, Font Awesome y Tone.js desde CDNs; por eso necesita conexión a Internet para cargar todas las dependencias externas.

## Estado del proyecto

Esta versión incorpora las funciones indicadas arriba. Es un simulador de carrera ficticio: resultados, premios, clubes y progresión se generan dentro del juego y no representan datos oficiales ni resultados reales.
