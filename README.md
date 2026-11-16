# Würzenbach 56 · Wohnung 1 · 3D-Rundgang

Interaktiver 3D-Rundgang durch die **Gartenwohnung (Wohnung 1, EG, 4.5 Zimmer, 141.5 m²)** an der Würzenbachstrasse 56 in Luzern.
Die Tour läuft direkt im Browser, es ist keine Installation nötig. Alles steckt in einer einzigen Datei (`index.html`, three.js ist eingebettet).

**Tour öffnen:** siehe Link im Repository-Beschreibungsfeld (GitHub Pages), oder `index.html` herunterladen und im Browser öffnen.

## Bedienung

| Aktion | Steuerung |
|---|---|
| Gehen | `W` `A` `S` `D` oder Pfeiltasten |
| Umsehen | Maus (einmal ins Bild klicken) |
| Schneller gehen | `Shift` |
| Türen öffnen/schliessen | `E` (auch die Schiebetüren zum Sitzplatz) |
| Dollhouse-Ansicht (Dach ab) | `T` oder Knopf oben rechts |
| Tag/Abend | `L` |
| Sonnenstand (Datum und Uhrzeit) | Knopf «Sun study», Zeit mit `[` `]`, Datum mit `-` `=` |
| Zu einem Raum springen | Knöpfe rechts oder Tasten `1`–`9` |
| Maus loslassen | `Esc` |

### Auf dem Handy oder Tablet

Die Seite erkennt Touchgeräte automatisch und blendet Bedienelemente ein:

| Aktion | Touch |
|---|---|
| Gehen | Joystick unten links |
| Umsehen | irgendwo auf dem Bild wischen |
| Schneller gehen | Knopf «Run» |
| Türen öffnen/schliessen | Knopf «Door» (erscheint in der Nähe einer Tür) |
| Dollhouse-Ansicht | Knopf «Dollhouse» oben rechts |
| Raum anspringen, Tag/Abend, Vollbild | Knopf «Menu» |

Im Dollhouse: ein Finger = drehen, zwei Finger = zoomen und verschieben, doppelt tippen = dort hinstellen.
Zum Testen am Computer kann `?touch=1` an die Adresse angehängt werden (`?touch=0` schaltet die Touch-Bedienung aus).

In der Dollhouse-Ansicht am Computer: ziehen = drehen, Rechtsklick-Ziehen = verschieben, Mausrad = zoomen, Doppelklick auf einen Raum = dort hinstellen.
«Plan overlay» legt die Linien des Originalgrundrisses über das 3D-Modell, um die Übereinstimmung zu prüfen.

## Sonnenstand und Schattenwurf («Sun study»)

Der Knopf «Sun study» öffnet zwei Regler für Datum und Uhrzeit (Luzern, 2026, Sommer- und Winterzeit berücksichtigt). Die Sonne steht dann wirklich dort, wo sie zu dieser Zeit steht, und wirft Schatten durch Fenster, Wände und Dach. Angezeigt werden Sonnenhöhe, Himmelsrichtung, Sonnenauf- und -untergang sowie der Anteil der Terrasse, der direkte Sonne bekommt. Die Schnellwahl springt auf den 21. März, 21. Juni und 21. Dezember, «Play the day» lässt den Tag ablaufen. Am besten wirkt das in der Dollhouse-Ansicht.

Grenzen: Berücksichtigt sind nur die modellierten Bauteile der Wohnung, die Bäume und Hecken. Obergeschosse und Nachbarbauten fehlen im Plan. Mit «Upper floors cast shade (assumed)» lässt sich ein unsichtbarer Block aus zwei Geschossen über der Wohnung zuschalten. Das ist eine Annahme und kein Planinhalt, also keine verbindliche Aussage über die Besonnung.

## Layout-Varianten

Die Tour kennt drei Varianten, im Menü rechts unter «Layout variant» umschaltbar (die Seite lädt dabei neu):

| Variante | Inhalt |
|---|---|
| **Variante 2 (Standard)** | Die Wand zwischen Bad und Ankleide ist um etwa 0,6 m Richtung Ankleide verschoben, das Bad ist rund 8,4 m² gross. Das WC (Reduit 2) neben der Ankleide entfällt samt Tür, die Ankleide reicht dafür bis nach hinten und hat nur noch auf einer Seite Schränke. |
| **Variante 1** | Grundriss genau wie im Plan (Adresszusatz `?variant=1`). |
| **Variante 3** | Wie Variante 2, aber im Masterbad mit offener Walk-in-Dusche ganz beim Lavabo (nur eine Glaswand dazwischen) und einer leicht schräg gestellten Badewanne (`?variant=3`). |

## Einrichtung

Die Wohnung ist vollständig möbliert im Stil **Nordic Light**: gebleichte Eiche, heller Terrazzo, weisse Küche, schwarze Metallteile, Leinen und Wolle in Salbei und Taubenblau. Dazu gehören Teppiche, Bilder, Lampen, Vorhänge, ein gedeckter Esstisch, gemachte Betten und eine Küche mit Steinplatte. Im Reduit 1 steht eine Waschnische mit anthrazitfarbener Waschmaschine und Trockner an der Rückwand, Arbeitsplatte, Eichenregalen mit LED-Licht und Metro-Fliesen.

Holzmaserung, Terrazzo und Stoffe (Leinen, Wolle, Leder) sind im Browser berechnet, es werden keine Bilddateien nachgeladen.

## Grundlage und Annahmen

- Wände, Türen, Fenster und Raumgrössen sind aus dem Vermarktungsplan (Baueingabe, Stand 06.08.2026) übernommen und massstäblich.
- Im Plan nicht bemasst und daher angenommen: Türhöhe 2.20 m, Fensterbrüstung 0.90 m, bodentiefe Glasschiebetüren zum Sitzplatz, Höhe der Stufe zwischen Korridor und Wohnen/Essen/Küche (14 cm, abgeleitet aus den Raumhöhen 3.14 m / 3.28 m).
- Möblierung (Lage und Grösse aus dem Plan), Materialien, Farben und Beleuchtung sind ein Gestaltungsvorschlag.
- Eingang, Treppenhaus und Lift sowie die Obergeschosse sind nicht modelliert. Der Garten ist nur so weit dargestellt, wie ihn der Plan zeigt.

> Alle Angaben, Pläne und Darstellungen sind unverbindlich und dienen nur der Veranschaulichung. Flächenangaben sind Circa-Angaben, Änderungen bleiben bis Bauvollendung vorbehalten.
