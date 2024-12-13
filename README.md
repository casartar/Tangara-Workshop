# Tangara-Workshop


## Kosten
Der Workshop kostet 100€. Am liebsten in Bar im Notfall per Paypal.
## Voraussetzung
Erfahung mit dem SMD-Bestücken von Platinen oder gute Augen, eine ruhige Hand und Geduld. 
## Mitbringen
- Zwingend
    - Laptop/Tablet/Smartphone zum ansehen der Anleitung
    - SD-Karte
- Optional
    - Außensechskant 3mm (z. B. https://www.amazon.de/dp/B001553QW8)
    - Torx T5 (z. B. https://www.amazon.de/dp/B0B61C6YSX)
    - Pinzette
    - Kopfhörer mit 3,5 mm Klinke
    - Kopfhörer mit Bluetooth

## Anleitung

### Schritt 1 - Bestücken der Top-Seite des mainboards
Als erstes musst du die Datei [mainboard.html](mainboard.html) aus diesem Repository herunterladen und im Browser öffnen. Die Datei (ibom) enthält eine Liste der Bauteile, die du bestücken musst und zeigt an, wo diese auf der Platine hingehören. Du musst als erstes die Top-Seite auswählen, indem du oben rechts den Button mit "F" auswählst.

Nun wird die Topseite mit Lötpaste versehen, indem diese mit Hilfe der Lötschablone aufgerakelt wird.
Gehe hierzu zur Rakelstation dort bekommst du deine Mainboard-Platine.

**Bitte beachte, dass wir bleihaltige Lötpaste verwenden, weshalb du darauf achten solltest, in den Pausen immer deine Hände zu waschen, bevor du etwas isst oder trinkst.**

Ist die Platine mit Lötpaste versehen, bekommst du eine Sortierbox mit den Bauteilen für beide Seiten der Mainboard Platine. Diese Bauteile musst du entsprechend der ibom mit Hilfe der Pinzette bestücken. Die Bauteile in der Sortierbox sind in der gleichen Reihenfolge angeordnet wie in der ibom.

Bitte beachte, dass L1 und L2 das gleiche Bauteil sind. Keine Ahnung warum es zwei Zeilen in der ibom gibt.

Bist du fertig mit dem Bestücken begib dich vorsichtig mit deiner Platine zur Backstation. Achte darauf, dass du nicht auf die Oberseite greifst und Teile verschiebst. Hier kommt die Platine zum ersten Mal in den Ofen.

### Schritt 2 - Pause
Mache eine kleine Pause während der Ofen seinen Job erledigt. Es wird noch anstrengend genug. Das war erst der Anfang. Lauf eine Runde. Wasche deine Hände und trink einen Schluck Wasser, streck deinen Rücken, was auch immer dir hilft :)

### Schritt 3 - Bestücken der Bottom-Seite des mainboards
Schalte die ibom für die Unterseite um, indem du oben rechts den Button "B" auswählst.

Gehe zur Rakelstation hier wird die Unterseite mit Lötpaste versehen.

Die Bauteile für die Unterseite sind ebenfalls in der ersten Sortierbox.

Setze die Platine in die Bestückungshilfe. Ansonsten verfahre wie zuvor.

Bitte beachte, dass es zwei Zeilen für 10k Widerstände gibt. Es handelt sich aber um das gleiche Bauteil.

Achte bei den Schaltern sw1 und sw2 darauf, dass sie korrekt, gerade und so weit hinten wie möglich platziert sind.

J1 und J2 sind THT Bauteile und werden nach dem Backen mit dem Lötkolben festgelötet, also nicht wundern wenn du dafür noch keine Teile hast.

Bist du fertig mit dem Bestücken begib dich vorsichtig mit deiner Platine zur Backstation. Hier kommt die Platine zum zweiten Mal in den Ofen.

### Schritt 4 - Pause
Mache eine kleine Pause während der Ofen seinen Job erledigt. Es ist noch ein gutes Stück. Siehe Pause 1.

### Schritt 5 - Festlöten des Akku-Steckers und der Audio-Buchse
Löte mit dem Lötkolben den Akku-Stecker J7 und die Audio-Buchse J1 fest.

### Schritt 6 - Festlöten des Akku-Steckers und der Audio-Buchse
Begibt dich mit dem fertigen Mainboard zur Rework-Station. Dort wird geprüft, ob es Kurzschlüsse gibt und diese werden ggf. beseitigt. 

### Schritt 7 - Bestücken der Bottom-Seite der faceplate
Lade die Datei [faceplate.html](faceplate.html) aus diesem Repository herunterladen und öffne sie im Browser. Schalte die ibom für die Unterseite um, indem du oben rechts den Button "B" auswählst.

Gehe zur Rakelstation dort bekommst du deine Faceplate-Platine. Hier wird die Unterseite mit Lötpaste versehen.

Du bekommst eine weitere Sortierbox mit allen restlichen Teilen die du noch benötigtst.

Verfahre wie zuvor.

Bist du fertig mit dem Bestücken begib dich vorsichtig mit deiner Platine zur Backstation. Hier wird zum dritten Mal gebacken.

### Schritt 7 - Pause
Mache eine kleine Pause während der Ofen seinen Job erledigt. Der Bestückungspart ist fast geschafft.

### Schritt 8 - Festlöten des Vibrationsmotors
Der Vibrationsmotor sollte sich in der Sortierbox befinden. Löte diesen an die beiden Pads die mit "Haptics" beschriftet sind. Rot an + und Schwarz an -.

### Schritt 9 - Festlöten des Displayes auf der Top-Seite der Faceplate
Setze die Platine in die Bestückungshilfe.
Löte mit dem Lötkolben das Display fest.
Achte sehr gründlich darauf, dass die kontakte des Kables bündig mit den Kupferbahnen auf der Platine sind. Der orangene Teil des Kables sollte nahezu Bündig mit dem Rand der Platine sein.

![](Pictures/Display_02.jpg)

### Schritt 10 - Programmieren

Gehe zur Programmierstation dort werden die Controller mit Firmware versorgt.
Gehe danach zur Teststation, dort wird deine Platine getestet.

### Schritt 11 - Mechanischer zusammenbau
Wenn alles funktioniert bekommst die mechanischen Teile und den Akku.

Gehe zu deinem Platz zurück und breite die mechanischen Teile vor dir aus.
Du solltest nun folgende Teile vor dir haben:

4x Schrauben M2 kurz
4x Schrauben M2 lang
4x Distanzhülsen
1x Gehäuse Vorderseite
1x Gehäuse Rückseite
1x Touchwheel
1x Faceplate
1x Mainboard
1x Akku
1x Halterahmen für den Akku
2x Druckknöpfe
1x Schiebeschalter
1x Abdeckung für die SD Karte
1x Displayabdeckung

![](Pictures/Teilesliste_01.jpg)

Schraube als erstes die langen Schrauben von unten in das Gehäuse für die Rückseite.
![](Pictures/Schritt1.jpg)

Platziere nun den Halterahmen für den Akku wie im Bild abgebildet. Auf der linken Seite des Bildes befindet sich die Öffnung für die Buttons.
![](Pictures/Schritt2.jpg)

Platziere nun den Akku wie im Bild.
![](Pictures/Schritt3.jpg)


