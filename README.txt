-Éste proyecto está enfocado a realizar una comparación entre los campeones mas utiliados en el videojuego de league
 of legens, analizando cuáles forman el top 10 en el modo de competición de SoloQ.

-Para ello se ha ultilizado 2 fuentes de datos diferentes, con la finalidad de compararlas entre ellos y ver 
  si se corroboraba que tras la ultima actualización, esos son los campeones mas fuertes y por  ello ultilizados 
  en el modo competitivo.

     1º En primer lugar se ha extraido una tabla con los datos de los matchups de esta temporada en la cual nos venían
     datos varios, sobre la cantidad de muertes conseguidas, asistencias, y eliminaciones sufridas, los cuales eran 
     irrelevantes junto a otros, por lo que se ha procedido a su limpieza utilizando la librería de Pandas.

     2º En segundo lugar una vez conseguidos los datos que se querían de esa tabla, (campeones, y winratios), se 
     ha buscado una segunda fuente de información que nos corroborase las conclusiones obtenidas a raíz de la primera.
     Para ello se ha utilizado una pagina con datos del LoL, en la que usando Web Scraping, se ha llegado a la 
     conclusión de que existía cierta discordancia entre los datos de una fuente y otra.

     3º El tercer y último paso, se ha procedido a realizar una visualización de las conclusiones obtenidas 
     para poder ralizar una comparación de los datos visualmente.

-La conclusión final de éste proyecto es que existe cierta discordancia entre unas fuentes de datos y otras
debido a las constantes actualizaciones del juego en las que se buffan o nerfean diferentes componentes de éste.