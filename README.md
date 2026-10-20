# REPO projecte-smx2b-2026-2027

Llista de projectes d'SMX2B del curs 2026-2027.

### BoardSinc

###### Context i situació inicial:

La comunitat de wargame (jocs de taula o de miniatures en què dos o més jugadors simulen conflictes militars, batalles històriques o situacions tàctiques i estratègiques) es troba amb diverses dificultats a l'hora de preparar i desenvolupar una partida.

Un dels principals inconvenients d'aquest tipus de jocs és la necessitat de disposar d'un espai físic considerable per representar els escenaris, desplegar les miniatures i gestionar els diferents elements que intervenen en una partida. Això, sumat a la quantitat de material necessari, pot dificultar-ne la pràctica, especialment en entorns domèstics o en espais amb disponibilitat limitada.

A més, la preparació de les partides sovint requereix un temps considerable, tant per al muntatge de l'escenari com per a la configuració de les unitats, la consulta de regles i la gestió dels diferents elements del joc. Aquesta complexitat també representa una barrera d'entrada per als nous jugadors, que poden trobar dificultats a l'hora d'aprendre les mecàniques, comprendre les regles i familiaritzar-se amb les diferents unitats i les seves característiques.

Tot i aquestes dificultats, un dels principals atractius dels wargames és precisament l'experiència física i tàctil que ofereixen. La manipulació de miniatures, el desplegament de les unitats sobre el terreny de joc i l'ús de daus per resoldre les accions formen part essencial de la seva identitat i contribueixen a generar una experiència immersiva, estratègica i social que molts jugadors volen preservar.

En aquest context, BoardSinc sorgeix amb l'objectiu de simplificar i fer més accessible l'experiència dels jocs de wargame, abordant les principals dificultats relacionades amb l'espai necessari, el muntatge i la configuració de les unitats, així com la iniciació de nous jugadors. Tot això, mantenint com a eix central l'ús de miniatures i daus, per preservar al màxim les sensacions, les dinàmiques i l'essència dels jocs de guerra tradicionals.

Així, el projecte busca trobar un equilibri entre la simplificació de la preparació i el desenvolupament de les partides i la conservació de l'experiència física i estratègica que caracteritza aquesta afició.

###### Abast i objectius:

Objectius generals L'objectiu principal de BoardSinc és digitalitzar tots els elements dels jocs de wargame que no siguin miniatures ni daus, amb la finalitat de simplificar i agilitzar el desenvolupament de les partides, reduir l'espai físic necessari i facilitar l'accés a nous jugadors. El projecte busca combinar els avantatges de les eines digitals amb l'experiència física dels jocs de miniatures tradicionals, mantenint la interacció directa amb les miniatures i els daus com a eixos centrals del joc. D'aquesta manera, es pretén reduir la quantitat de material físic necessari i les tasques de gestió associades, sense perdre l'essència tàctica, estratègica i social dels wargames.

###### Objectius específics

Centralitzar els elements del joc: desenvolupar una aplicació, plataforma web o eina digital que permeti reunir en un únic entorn tots els recursos necessaris per jugar, com ara cartes, fitxes (tokens), manuals, taules de referència i altres elements.
Digitalitzar les cartes i els tokens: substituir els components físics de gestió per versions digitals que permetin consultar la informació, gestionar-ne l'estat i accedir-hi de manera ràpida i intuïtiva.
Agilitzar la gestió de les unitats: facilitar la consulta i l'administració de les característiques, habilitats, estadístiques i estats de les diferents unitats durant la partida.
Facilitar l'accés a les regles i als manuals: integrar la documentació i les referències necessàries dins la plataforma per evitar consultes constants a manuals físics i reduir les interrupcions durant el joc.
Simplificar la preparació de les partides: reduir el temps necessari per organitzar els elements, configurar les unitats i preparar els recursos abans de començar a jugar.
Reduir l'espai físic necessari: disminuir la quantitat de material que cal disposar sobre la superfície de joc, mantenint únicament les miniatures, els daus i els elements físics que siguin imprescindibles.
Facilitar la iniciació de nous jugadors: oferir una interfície intuïtiva i una presentació clara de la informació que permetin comprendre les regles i les mecàniques de joc de manera progressiva.
Preservar l'experiència tradicional: mantenir les miniatures i els daus físics com a elements fonamentals, conservant la manipulació, la interacció i les decisions estratègiques pròpies dels wargames.

###### Abast del projecte

BoardSinc inclou el disseny i el desenvolupament d'una eina digital que actuï com a complement dels jocs de wargame tradicionals. Aquesta eina ha de permetre gestionar els diferents elements del joc des d'un únic entorn, facilitant-ne la consulta i l'administració durant totes les fases de la partida.

### HoloTech360


#### MetroCount
Desenvolupament d'una aplicacio per saber la quantitat que tan ple va el metro de Barcelona
 
![Text de prova](/img/metrocount1.jpg)
![Imatge esquema resumit](/img/metrocount2.jpg)

##### Links

[Documentació de la API de TMB "Incluyent autobusos"](https://developer.tmb.cat/api-docs/v1 )

[Més dades per consultar de la API de TMB"](https://developer.tmb.cat/data)


##### Context

La nostra idea és fer-hi en Python una demostració de com es podria fer un comptador de persones en els vagons del metro de Barcelona perquè així a través d'una aplicació es pogués consultar que tan ocupat va el metro i llavors els passatgers poguessin decidir si és convenient entrar o no al vagó

##### Com es fara?

Resumidament, el que teníem pensat nosaltres és implementar uns sensors just a la porta dels vagons del metro perquè així compti les persones que hi passen, la nostra forma que havíem pensat d'implementar els sensors es tractaria de dos sensors, un que s'encarregui de comptar els que entren i l'altre dels que surten, si és possible fer els sensors s'actualitzin de manera ràpida i freqüent (cada 0,5 segons per exemple), i que els infrarojos sàpiguen diferenciar quan passen persones i quan no. <br>

 
(D'Aquest tema s'hi ha en parlaré en un altra secció sobre els que se'ns queda fora de l'abast i quins problemes podrien sorgir)

##### Problemes i fora d'abast

Els problemes d'abast en els quals ens podríem arribar a trobar és la precisió d'aquestes dades, un dels principals reptes d'aquest projecte és que les dades no podran ser 100% precises, ja que podrien sorgir problemes com que hi ha una avalancha de persones que entrin juntes al vagó i que el sensor compta com si hagués entrat una persona, però en realitat hi ha entrat dues o tres persones o inclús més. <br>

També en la part de recollida de dades els repetidors de wifi que hi ha que serveixen per enviar les dades cap al servidor sobre les persones podria fallar per culpa de l'alta demanda de persones que estiguessin utilitzant la xarxa<br>

Per això la nostra visió és fer que les dades siguin aproximades, encara que sempre hi busquem que sigui el més precís possible resulta ser que es una tasca bastant complicada saber amb exactitud la quantitat real dels passatgers, per això la nostra idea és fer una barra amb colors (per exemple de verd a vermell) en la qual hi hagi una fletxa que indiqui que tan ocupat està el tren segons les dades recollides dels sensors.


### PackGo


### RBridge


### Remote-Smart-Plugs
Aquest projecte tracta de endolls inteligents que es conectaran a la xarax i enviaran las seves variables a un servidor on podran ser vists desde una pagina web entrant amb un usuari on podras veure les avriables dels endolls agregats a la compte.

Variables: temperatura, humitat, voltatge, tensió.


### SafeTracking


### WearSafe
