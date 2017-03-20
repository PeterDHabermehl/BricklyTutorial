# Kap. 2: Erfahrungsstufe 1

## 2.i Hallo Welt

Es ist, neben einer Reihe praktischer Erwägungen, die z.B. [hier in der Wikipedia](https://de.wikipedia.org/wiki/Hallo-Welt-Programm)
erläutert werden, eine schöne Tradition, den Einstieg in eine neue Programmiersprache mit einem Gruß an die Außenwelt zu beginnen.
Der Zweck der Aufgabe ist es, ein lauffähiges Programm zu erstellen und somit die wichtigsten Grundregeln der Programmiersprache kennenzulernen.

### Die Aufgabe selbst ist simpel:

Erstelle ein Brickly-Programm, daß "Hallo Welt!" ausgibt.

### Lösungshilfe

Du brauchst genau zwei Bausteine:

- Den Programmkopf

   Der blaue Programmkopf ist schon beim Start vorhanden. Mit ihm beginnt das Brickly-Programm
- Den "gib aus"-Baustein.
    
    Er kann verschiedenste Informationen ausgeben und ist in seiner einfachsten Form direkt für eine Textausgabe eingestellt.

Setze die Bausteine passend zusammen und gib einen Text Deiner Wahl ein (es muß ja nicht immer "Hallo Welt!" sein).

Wenn Du fertig bist, drücke auf den "Los"-Knopf. Falls alles klappt, sollte Dein Text jetzt auf der Anzeige des TXT und in dem blauen Feld am rechten Bildschirmrand erscheinen.

Herzlichen Glückwunsch, Du hast Dein erstes TXT-Brickly-Programm erstellt.

### Beispiellösung

Einen Lösungsvorschlag findest Du hier: [Tu_01_01](/img/Tu_01_01.png)

Für diese Aufgabe gibt es kein herunterladbares Beispielprogramm.

***

## 2.ii Spot an

Nachdem Du jetzt mit Brickly eine erste Botschaft ausgegeben hast, folgt gleich noch ein ganz großer Schritt.
Der TXT soll ja auch dazu dienen, fischertechnik-Modelle zu steuern. Und damit fangen wir jetzt an!

## 2.ii.a An und aus

Zunächst wollen wir ausprobieren, wie ein Ausgang des TXT ein- und ausgeschaltet wird.

### Die Aufgabe

Erstelle ein Brickly-Programm, daß eine an Ausgang O1 angeschlossene Lampe ein- und wieder ausschaltet.

### Das Modell

Das fischertechnik-Modell zu dieser Aufgabe ist recht überschaubar. Du benötigst eine fischertechik-Lampe im Leuchtstein und ein zweiadriges Kabel mit Steckern.
Natürlich kannst Du noch eine bunte Leuchtkappe auf die Lampe setzen - das bleibt Dir überlassen.
Verbinde das Kabel mit dem Leuchtstein und dem TXT. Am TXT steckst Du den roten Stecker in den *Ausgang O1*, den grünen Stecker an einen der mit Masse (auf dem Kopf stehendes "T") gekennzeichneten Anschlüsse der Zähler 1-4 (C1-C4).
Fallst Du statt einer Glühbirne eine LED verwendest, achte auf die richtige Polung am Leuchtstein!
![Im_HW_01_02_i01.png](/img/Im_HW_01_02_i01.png)

### Lösungshilfe

Neben dem bereits bekannten blauen Programmkopf brauchst Du:
- Den "schalte Ausgang"-Block

    Er schaltet Ausgänge. Du brauchst ihn zweimal, einmal zum ein- und einmal zum ausschalten.

Und damit die Lampe nicht sofort wieder ausgeht, muß das Programm zwischen Ein- und Ausschalten eine Pause machen.
Dazu verwendest Du den
- "warte"-Block

    Er sorgt dafür, daß der Programmablauf für die angegebene Sekundenzahl angehalten wird.

Denk darüber nach, was wann geschehen soll, und bringe die Bausteine dann in die passende Reihenfolge.
Ein Klick auf "Los" zeigt Dir, ob alles richtig ist.

### Beispiellösung
[Hier](/img/Tu_01_02.png) ist eine Lösung zu finden.

Für diese Aufgabe gibt es kein herunterladbares Beispielprogramm.

***

## 2.ii.b Disco

Jetzt soll es ein bisschen bunter werden. Der TXT hat ja insgesamt 8 Ausgänge, so daß wir noch weitere Lampen anschließen und steuern können.

### Die Aufgabe

Nachdem Du eine Lampe ein- und ausgeschaltet hast, wird es Dir sicher nicht schwerfallen, auch mehrere Lampen zu schalten. Deshalb lernen wir jetzt gleich noch einen neuen Baustein kennen, die "wiederhole"-Schleife. In diesen Baustein können weitere Bausteine eingefügt werden, die dann endlos immer wieder abgearbeitet werden, denn wir wollen ein Lauflicht mit drei Lampen bauen, die nacheinander ein- und wieder ausgeschaltet werden, und das solange, bis wir das Programm wieder stoppen.

### Lösungshilfe

An Bausteinen brauchst Du:
- Den blauen Programmkopf
- Den "schalte Ausgang"-Block
- Den "warte"-Block
- Den "wiederhole"-Block

Überleg Dir genau, welche Befehle in welcher Reihenfolge ausgeführt werden müssen, z.B.
- Lampe 1 an
- warten
- Lampe 1 aus
usw.

Du brauchst verschiedene Bausteine mehrfach, damit das Programm funktioniert.

Viel Erfolg :-)

### Beispiellösung

[Hier](/img/Tu_01_02b.png) ist ein Lösungsvorschlag.

Es gibt kein herunterladbares Beispielprogramm für diese Aufgabe.

***


