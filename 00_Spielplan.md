# SILESMON – Spielplan

Alles, was für das Spiel beschlossen ist. Wird laufend ergänzt.

## Technik
- Echtes 3D im Browser (Three.js), eine einzige HTML-Datei, Ziel 60 FPS in voller Handy-Auflösung bis 1080p.
- Hauptmenü hochkant, das Spiel selbst nur quer.
- Steuerung: Joystick links, Knöpfe rechts.
- Kein Ladebildschirm, kein „Tippe zum Starten".
- Hauptmenü ab V1.16: Cover mit eingebautem Silesmon-Logo, Knöpfe darunter. Ab V1.17 immer über die volle Breite; auf kurzen Handys stehen die Knöpfe in einer Reihe.
- Vollbild beim ersten Tipp im Hauptmenü, dazu ein kleiner Vollbild-Knopf oben rechts im Spiel.

## Geschichte
- Siles lebt im kleinen Bergdorf Wiesengrund (Name vorläufig).
- Nach einem Sturm findet er draußen im Wald ein verletztes Adlerküken: **Brisko**. Er rettet es, die beiden werden beste Freunde.
- Im Dorf gibt es eine kleine **Krankenstation** mit einer **Heilerin**. Sie verarztet Brisko, erklärt die Pflege und gibt den ersten Silpod. Einen Professor gibt es nicht.
- Später kommen Städte mit richtigen Krankenhäusern. Erst wird das Dorf fertig gebaut.

## Brisko
- Als Baby sitzt er auf Siles' Schulter.
- Er wird älter und wächst, bis er größer ist als Siles. Flugtiere sind immer größer als der Charakter.
- Fliegen muss er erst lernen: durch Kämpfe gegen andere Gegner. Danach kann man auf ihm fliegen.

## Tiere und Silpod
- Wilde Tiere leben in den Wäldern ums Dorf. Man sieht sie in der Natur, manche sind neugierig, manche scheu.
- Gezähmte Tiere wohnen in einem **Silpod**.
- Nur **ein** Tier begleitet dich (läuft mit oder fliegt mit, wenn es ein Vogel ist). Der Rest ist im Silpod. Man kann auch ganz allein laufen.
- Höchstens **10 Tiere** im ganzen Spiel. Ersetzen ist immer möglich, weil später neue Tiere dazukommen.
- Silpod gewinnt man durch Kämpfe gegen Gegner. Ohne leeren Silpod kann man kein neues Tier zähmen.
- Zähmen geht nach einem gewonnenen Kampf. (Offen: einfache Chance oder Vertrauensleiste.)

## Gegner
- Fremde mit eigenen Tieren, die neben ihnen herlaufen. Sie heißen nicht „Trainer" (Vorschlag: **Wanderer**; die vier besonderen: **Hüter**).
- Sie haben kleine Hütten. Betritt man den Bereich einer Hütte, kommt der Herausforderer mit seinem Tier.
- Mit einem Baby-Tier wird man nicht herausgefordert. Erst mit einem ausgewachsenen Tier auf gleicher Stärke.
- Nach dem Kampf wird man Freunde oder verschafft sich Respekt.

## Kampf
- Rundenbasiert, Menü: Kampf, Team, Beutel, Flucht.
- Typen im Kreis (Vorschlag): Wasser > Feuer > Pflanze > Erde > Luft > Wasser.
- Jedes Tier beherrscht eine eigene Spezialattacke (Vorschläge):

| Tier | Typ | Spezialattacke |
|---|---|---|
| Glutli (Igel) | Feuer | Glutrolle |
| Rubbo (Tapir) | Feuer | Hitzeschnauben |
| Wellino (Waschbär) | Wasser | Wirbelwäsche |
| Azuri (Hirschkalb) | Wasser | Quellsprung |
| Sprossi (Eule) | Pflanze | Schlummerlaub |
| Mooshi (Hamster) | Pflanze | Blattschild |
| Flaumi (Schaf) | Luft | Wattewolke |
| Brisko (Adler) | Luft | Sturzflug (als Küken: Piepser) |
| Kristo (Dachs) | Erde | Kristallstoß |
| Schuppo (Schuppentier) | Erde | Panzerkugel |

- Verletzte Tiere heilt man in der Krankenstation.

## Reihenfolge
1. Das Dorf – **gebaut, Stand V1.15**: Häuser, Siles (mit Skelett), Laubbäume und Tannen aus eigenen 3D-Modellen, drehbare Kamera, Heilerin noch als Bild-Figur
2. Der Wald und die Rettung von Brisko
3. Krankenstation mit Heilerin, erster Silpod
4. Wilde Tiere im Wald
5. Kampf
6. Zähmen mit Silpod
7. Wanderer und ihre Hütten
8. Speichern
9. Brisko wächst, erstes Gebiet mit Hüter, später Fliegen und Städte

## Eigene 3D-Modelle
- Häuser, Bäume und später Figuren kommen als GLB-Dateien (aus einem Bild erzeugt) und liegen in `10_3D_Modelle`.
- Alle Häuser sollen im selben Stil sein.
- Siles: `10_3D_Modelle/Siles_mit_Skelett_Gehen_Rennen.glb` (Meshy, Mixamo-Skelett, Animationen Walking und Running). Eine eigene Steh-Animation (Idle) fehlt; ab V1.16 wird eine ruhige Stehhaltung aus dem Gehen erzeugt (Beine gerade, leichtes Atmen, Kopf schaut sich um).
- Laubbaum: Meshy-Modell „Whimsywood Tree". Das Original hat 3,5 Mio. Dreiecke und 109 MB und ist zu groß für GitHub; im Spiel steckt eine stark vereinfachte Fassung (ca. 2.900 Dreiecke).
- Wichtig für neue Modelle: mit wenig Dreiecken exportieren (Häuser unter 15.000, Bäume unter 3.000).
- Tanne: `10_3D_Modelle/Tanne.glb` (Meshy „Whimsical Evergreen", 362.000 Dreiecke).
- Beide Bäume stecken vereinfacht im Spiel (ca. 5.000 bzw. 2.900 Dreiecke); die Farben sind dabei von der Textur auf die Form übertragen.
- Noch offen: Brunnen, Heilerin, Brisko.

## Figuren
- Im Spiel stehen vorerst die Figuren aus den Figurenblättern als aufgestellte Bilder (vorne, seitlich, hinten). Richtige 3D-Figuren mit Skelett können sie später ersetzen.
- Die Heilerin nutzt vorläufig das Figurenblatt `05_Trainer/3_Trainer_Pflanze.jpg` (Mädchen mit Zopf).
- Stil der Welt: Bilderbuch-Dorf wie im Vorlagenbild `09_Vorlagen/Haus_Vorlage_Bilderbuchstil.jpg`: zweistöckige Fachwerkhäuser, farbiger Putz, gelbe Fensterrahmen, Rundbogentüren, Balkone, weiße Lattenzäune, Trittsteine, Sonnenblumen.
- Regeln für Monster: kein Feuer, keine Tropfen, keine Wolke über dem Kopf, nichts in der Hand.
