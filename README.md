# Dracima Mahjong - Tile Sets

Version 0.1.0 · Daniel Brune und ChatGPT/Codex (KI-Unterstützung)

Drei importierbare Kartenstapel mit jeweils 144 Mahjong-Steinen: 108 Zahlensteine,
28 Ehrensteine und 8 Bonussteine. Die WebP-Grafiken sind KI-generiert.

1. ZIP entpacken und den enthaltenen Ordner `dracima-mahjong` in
   `Data/modules/` des Foundry-Benutzerdatenordners kopieren. Bei einem Hostingdienst
   mit ZIP-Upload dessen Upload-Funktion verwenden.
2. Foundry neu starten, die gewünschte Welt öffnen und **Dracima Mahjong - Tile Sets** aktivieren.
3. **Dracima-Mahjong · Drei Spielsteinsätze** öffnen und den gewünschten Satz
   in die Kartenverwaltung ziehen oder per Kontextmenü importieren.

Die Steine verwenden Foundrys native Kartenverwaltung. Das Modul enthält
keine Mahjong-Regeln, keine automatische Spielwand und keine TavernGames-Abhängigkeit.
Es verändert vorhandene Weltstapel nicht.

Foundry V14 ist die Zielversion. Das Archiv und das native Kompendium wurden
technisch geprüft. Ein Live-Test in Foundry steht aus. Es gibt keine obere Versionsgrenze.

## Metadaten

`data/catalog.json` enthält 42 Motivkennungen und 144 Instanzkennungen.
Die drei Varianten verwenden dieselben Kennungen. Jede Variante ordnet ihren
Motiven WebP-Pfade relativ zum Modulordner zu. Vier Exemplare teilen sich je
ein Motivbild; Bonusmotive kommen je einmal vor. Die Foundry-Karten haben
ergänzende Angaben im Namensraum `flags.dracima-mahjong`.
Bei aktiviertem Modul ist der Katalog über
`modules/dracima-mahjong/data/catalog.json` abrufbar.

## Herkunft und Weitergabe

Die Grafiken stammen aus den drei Dracima-Mahjong-Bildsätzen. Dieses Paket
wurde für Daniels Nutzung erstellt. Eine öffentliche Weitergabelizenz
ist in dieser Ausgabe nicht festgelegt.

Foundry-Referenzen: https://foundryvtt.com/article/module-development/
und https://foundryvtt.com/api/v14/classes/foundry.documents.Cards.html
