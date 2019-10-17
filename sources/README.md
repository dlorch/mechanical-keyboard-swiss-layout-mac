Quelldatei für das WASD-Layout
==============================

Voraussetzungen
---------------

* Vektorgrafikprogramm wie [Inkscape]
* Schriftart "Vagabond"
* [svgo] (SVG Optimizer) Kommandozeilenprogramm

Vorlage
-------

Meine Vorlage [wasd-inkscape-105-8.16.2019-chde-mac.svg](wasd-inkscape-105-8.16.2019-chde-mac.svg) wurde auf
Basis der Vorlage von [WASD Keyboards] erstellt.

Quelle für diverse Symbole unter "Danksagung". Symbole für
"Mission Control" und "Launchpad" habe ich selbst gezeichnet.

Druckdatei erstellen
--------------------

Um die Datei für den Druck vorzubereiten, müssen alle Schriftarten in Pfade umgewandelt werden. Dazu muss der ganze Text markiert werden und dann mit
`Pfad > Objekt in Pfad umwandeln` die Umwandlung vorgenommen werden.

Als zweiten Schritt empfiehlt es sich mit einem Werkzeug wie [svgo] die Datei
zu minifizieren. Damit konnte ich die Druckdatei von rund 50 MB auf ein halbes MB
reduzieren.

Danksagung
----------

* [aasmith/mac-was-keyboard] für die Symbole für "Helligkeit", "Lautstärke" und die Medientasten
* Font Awesome für das Symbol [angle-up]

[aasmith/mac-was-keyboard]: https://github.com/aasmith/mac-wasd-keyboard
[angle-up]: https://fontawesome.com/icons/angle-up?style=solid
[Inkscape]: https://inkscape.org/
[svgo]: https://github.com/svg/svgo
[WASD Keyboards]: http://www.wasdkeyboards.com
