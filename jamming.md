# Jamming

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Vorbereitungen

1. Mit welcher Technologie möchte ich das Spiel entwickeln?
2. Wie möchte ich Dinge im Spiel darstellen?
3. Wie soll sich das Spiel anhören?
4. Wie sieht die Interaktion des Spielers mit dem Spiel aus?

## 1. Technologie

Ich würde empfehlen, eine Technologie zu wählen, bei der es bereits Erfahrungen oder Vorlieben gibt. Sei es die Programmiersprache, genutzte Editoren oder auch Projekt- oder Codestrukturen bzw. Architekturen in welchen man sich wohl fühlt. Ich werd hier einfach mal versuchen eine möglichst breit gefächerte Liste zu erstellen und die Komplexität (K) vs Mächtigkeit (M) auf einer Skala von 1-5 einzuschätzen.

Interessante Fragen:

* Möchte ich beim Entwickeln hauptsächlich mit Code arbeiten?
* Welche Sprache bzw Programmierparadigmen finde ich sympathisch?
* Auf welcher Plattform kann/will ich entwickeln und auf welchen soll gespielt werden können?

Vorschläge:

1. [Construct](https://www.scirra.com/) & [GameMaker](http://www.yoyogames.com/)
	* Hab ich mal zusammengefasst. Versuchen eine Komplettlösung anzubieten. Scripten ist möglich (Construct Javascript und GameMaker GML), es wird aber eher mittels Klickibunti gearbeitet. Entwicklung ist auf Windows, bauen gibts mehrere Ziele.
	* K: 3 vs M: 4
2. [Visionair](http://www.visionaire-studio.net/cms/adventure-game-engine.html)
	* Spricht Lua. Versucht auch eine Komplettlösung an zu bieten, hat aber einen klaren Fokus auf Point and Click spiele. Entwicklung auf Windows Bauen für Windows.
	* K: 3 vs M: 3
3. [AGM](http://www.adventuregamestudio.co.uk/)
	* Spricht AGSScript. Ähnliches Konzept wie Visionair mit dem Unterschied, das mit etwas mühe eine Entwicklung und Ausführung auf [Linux](http://www.adventuregamestudio.co.uk/wiki/GNU/Linux) möglich ist.
	* K: 3 vs M: 3
4. [Monogames](http://www.monogame.net/)
	* Spricht C#. Andere Sprache denkbar, da es auf Mono-Plattform läuft. Ist eine FOSS weiterentwicklung des von Microsoft eingestellten XNA Frameworks. Plattformübergreifendes Entwickeln und Bauen möglich.
	* K: 4 vs M: 5
5. [jMonkey](http://jmonkeyengine.org)
	* Spricht Java. Bringt einen Editor als auch eine Verwaltung der Assets. Darstellung in 3D. Unterstütz Ton. Plattformübergreifend Entwickeln als auch Bauen möglich (sogar Web (per Applet aber wer will das schon =P)).
	* K: 4 vs M: 5
6. [Blender](http://www.blender.org/)
	* Spricht Python. Unterstütz aber auch eine 'grafische Programmierung'. Blender ist haupsächlich ein 3D Modellierer, unterstütz aber auch viele Funktionen die eine Spieleentwicklung möglich machen.
	* K: 4 vs M: 5
7. [Unity](http://unity3d.com/)
	* Spricht C#. Bringt einen Editor, Asset Verwaltung und einen 'Shop', in welchem fertige benutzbare Assets zu finden sind. Darstellung in 3D. Unterstützt Ton. Beschränkt Plattform übergreifende Entwicklung
	  (nur Windows & Max) und so ziemlich alles an Zielen fürs Bauen (sogar Web (sortof)).
	* K: 4 vs M: 5
8. [Löve2D](https://love2d.org/)
	* Spricht Lua. Bringt nichts ausser einer Laufzeitgebung. Darstellung in 2D. Plattformübergreifendes Entwickeln als auch Bauen möglich (leider kein Web).
	* K: 2 vs M: 4
9. [SFML](http://www.sfml-dev.org/)
	* Spricht nativ C++, hat aber recht viele [Bindungen](http://www.sfml-dev.org/download/bindings.php). Bringt nur die Bibliothek mit. Plattformübergreifend Entwickeln und auch Bauen.
	* K: 4 vs M: 4
10. [MelonJS](http://melonjs.org/)
	* Spricht Javascript. Bringt eine Biblithek mit um per HTML5 & Canvas Dinge
	  im Browser zu tun. Schöne Integration des [Tiled](http://www.mapeditor.org/)Mapeditors. Überall entwickeln auf dem ein Browser läuft. Gilt auch fürs Bauen bzw. Ausführen.
	* K: 2 vs M: 4
11. [LibGDX](http://libgdx.badlogicgames.com/)
	* Spricht Java. Bringt ein umfangreiches Framework und einige Tools um zb ein Projekt zu erstellen. Plattformübergreifendes Entwickeln und Bauen (auch Web und Android) ohne viel an der Codebase zu schrauben.
	* K: 4 vs M: 5
12. [No Nonsense](https://non-dev.github.io/)
	* Spricht Java und Lua. Basiert zum Großteil auf LibGDX Tech. Will eine einfache und Schnell zugängliche Plattform für Spieleentwicklung bieten.
	* K: 3 vs M: 5

Weitere interessante Ressourcen:

* [Mod DB](http://www.moddb.com/engines)
* [Wiki Engine Liste](https://en.wikipedia.org/wiki/List_of_game_engines)

## 2. Darstellung

Interessante Fragen und Stichworte:

* Welche Ästhetik soll mein Spiel haben? (Minimal, Überzeichnet, Hyperreal)
* Welche Dimensionen soll das Spiel haben? (2D, 2.5D, 3D)
* Wie ist mein Blick auf die Darstellung? (Perspektive, Orthogonalität, Isometrie)
* Möchte ich Animationen? (Rigging, Spritesheets)
* Wie möchte ich meine Welt darstellen? (Tiles, Hexagons, 3D)

Vorschläge:

1. [GIMP](http://www.gimp.org/) & [Photoshop](https://www.adobe.com/products/photoshop.html)
	* Zeichen, Animieren und Bearbeiten auf Basis von Bitmaps.
2. [Inkscape](https://inkscape.org/) & [Illustrator](https://www.adobe.com/products/illustrator.html)
	* Zeichnen, Animieren und Bearbeiten auf Basis von Vektorgraphiken.
3. [Blender](http://www.blender.org/) & [Cinema4D](http://www.maxon.net/products/cinema-4d-studio/who-should-use-it.html) & [Maja](http://www.autodesk.com/products/maya/overview)
	* Modellieren, Animieren und Bearbeiten auf Basis von 3D Modellen und Texturen.
4. [Tiled](http://www.mapeditor.org/)
	* Mapeditor um 2D kachelbasierte Karten zu erstellen.

## 3. Ton

Interessante Fragen und Stichworte:

* Welchen Musikstil möchte ich?
* Welche Art von Effekte will ich untermalen?

Vorschläge:

1. [Audacity](http://audacity.sourceforge.net/)
	* Erstellen und Bearbeiten von Ton und Musik.
2. [Freesound](http://freesound.org/)
	* Große Datenbank mit meist frei zur Verfügung stehenden Tönen und Musikstücken.

## 4. Interaktion

Interessante Fragen und Stichworte:

* Auf welchen Plattformen soll gespielt werden?
* Welche Eingabegeräte der Plattform möchte ich nutzen?
* Wieviel Eingabe ist nötig um mit dem Spiel zu interagieren?
