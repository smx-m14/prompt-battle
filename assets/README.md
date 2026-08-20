# Imatges locals

Cada modalitat té la seva carpeta: `monuments`, `dishes`, `objects` i `artworks`.

El joc sempre intenta primer carregar el fitxer assignat a cada carta. Si encara no hi és, mostra el `fallback.svg` de la mateixa carpeta, de manera que mai no fa peticions a internet ni deixa una ronda buida.

Per substituir una reserva per una fotografia o reproducció, desa el fitxer amb el mateix nom que figura a `GAME_MODES` dins d'`index.html`. Les miniatures que ja s'hi han descarregat provenen de Wikimedia/Wikipedia; abans de publicar o redistribuir el joc, revisa la llicència i l'atribució de cada obra.
