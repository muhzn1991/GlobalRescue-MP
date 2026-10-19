# Changelog

Alle nennenswerten Änderungen an Global Rescue Multiplayer (GR-MP) werden hier festgehalten.
Neueste Version zuerst.

## 0.8.26 — 2026-10-19

- **0.8.25-Mitspieler: bitte unbedingt auf 0.8.26 aktualisieren.** Ein Mitspieler, der auf 0.8.25 bleibt, behält bei sich lokal eigene „Phantom-Absperrungen", die beim Host gar nicht existieren. Erst das Update auf **0.8.26** entfernt diese. Am besten fahren wie immer **beide Spieler dieselbe Version**.
- **Großeinsatz-Absperrungen sind wieder nur beim Host.** Straßensperrungen bei einem Großeinsatz plant jetzt wieder **nur der Host**; der Knopf „Straßensperrung planen" ist beim Mitspieler nicht mehr vorhanden. Die vom Host gesetzten Absperrungen (Pfosten/Band) sieht der Mitspieler weiterhin ganz normal.
- **Einheiten fahren nach dem Schichtende eines Großeinsatzes wieder heim.** Nach dem Ende eines Großeinsatzes (z. B. Stadtfest) kehren die Fahrzeuge des Mitspielers jetzt wieder zur Wache zurück, statt an der Einsatzstelle stehen zu bleiben.
- **Beta — bekannte Probleme (in Arbeit):** gleichzeitiges Bauen auf **dieselbe Stelle** kollidiert (das Geld wird automatisch erstattet); das **Vergrößern der Basis durch den Client** wird noch nicht synchronisiert.
- Benötigt weiterhin das aktuelle Spiel-Content-Update (Game-Build 25882902). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.26) verwenden.**

## 0.8.25 — 2026-10-19

- **Fahrzeug-Besatzung wird beim Mitspieler wieder stabil angezeigt.** Welche Mitarbeiter einem Fahrzeug zugeteilt sind, zeigt der Mitspieler jetzt wieder direkt und zuverlässig an (wie in früheren Versionen). Dazu weitere interne Stabilitäts-Korrekturen.
- **Großeinsätze (Beta, in Arbeit):** An der Darstellung und Bedienung der Großeinsatz-**Absperrungen** beim Mitspieler wird weiter gearbeitet (u. a. der Knopf „Straßensperrung planen"). Diese Punkte sind **noch nicht abschließend getestet** — bitte als Beta betrachten.
- **Beta — bekannte Probleme (in Arbeit):** gleichzeitiges Bauen auf **dieselbe Stelle** kollidiert (das Geld wird automatisch erstattet); das **Vergrößern der Basis durch den Client** wird noch nicht synchronisiert.
- Benötigt weiterhin das aktuelle Spiel-Content-Update (Game-Build 25882902). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.25) verwenden.**

## 0.8.20 — 2026-10-14

- **Leistung: flüssigeres Bauen und Umbauen von Basen beim Mitspieler.** Große Räume oder Flächen, die der Host baut, wurden beim Mitspieler bisher in einem Rutsch übernommen und verursachten kurze Standbilder. Das wird jetzt über mehrere Einzelbilder verteilt und läuft spürbar glatter. Dazu weitere interne Stabilitäts-Korrekturen.
- **Beta — bekannte Probleme (in Arbeit):** gleichzeitiges Bauen auf **dieselbe Stelle** kollidiert (das Geld wird automatisch erstattet); das **Vergrößern der Basis durch den Client** wird noch nicht synchronisiert.
- Benötigt weiterhin das aktuelle Spiel-Content-Update (Game-Build 25882902). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.20) verwenden.**

## 0.8.19 — 2026-10-14

- **Großeinsätze (R73): bessere Darstellung beim Mitspieler.** Bei den **Absperrungen** eines Großeinsatzes erscheinen die roten Markierungen „wo absperren“ jetzt schon **während der Planung**, und das **Absperr-Fahrzeug fährt beim Mitspieler sichtbar zur Sperrstelle**, statt in der Basis zu stehen. Zusätzlich sind **Ruckler in der Endphase** eines Großeinsatzes beim Mitspieler behoben.
- **Basis: Löschen und Straßen-Anbindung werden synchronisiert.** Das **Löschen einer Basis** wird jetzt zum Mitspieler übertragen, und die **Straße einer neu gegründeten Basis** erscheint wieder auf beiden Seiten.
- Benötigt weiterhin das aktuelle Spiel-Content-Update (Game-Build 25882902). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.19) verwenden.**

## 0.8.18 — 2026-10-14

- **Leistungs-Hotfix (R72):** Beim Anklicken von Fahrzeugen entstand ein Schwall an Besatzungs-Updates, der den Host kurz einfrieren ließ und beim Mitspieler sekündliche Ruckler verursachte. Das ist behoben — Besatzungs-Änderungen werden gebündelt und sparsamer übertragen.
- Hinweis: Besatzungs-Änderungen (zuweisen/freigeben) erscheinen beim Mitspieler jetzt bis **~1,5 s verzögert** (bewusst, gegen den Update-Schwall).
- Benötigt weiterhin das aktuelle Spiel-Content-Update (Game-Build 25882902). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.18) verwenden.**

## 0.8.17 — 2026-10-14

- **Angepasst an das aktuelle Spiel-Content-Update (Game-Build 25882902).** Diese Version benötigt das aktuelle Update von Global Rescue. Die alte Version 0.8.5 war für die vorherige Spielversion und funktioniert seit dem Content-Update **nicht mehr** — bitte auf 0.8.17 aktualisieren.
- Seit 0.8.5 zahlreiche Stabilitäts- und Synchronisations-Verbesserungen (Bauen/Abriss, Einsätze, Crew, Kredite, Blitzer/Großeinsätze u. a.).
- **Beta — bekannte Probleme (in Arbeit):** gelegentliche Mikroruckler im Multiplayer; gleichzeitiges Bauen auf **dieselbe Stelle** kollidiert (das Geld wird automatisch erstattet); das **Vergrößern der Basis durch den Client** wird noch nicht synchronisiert.
- Hinweis: Protokoll-Version 10. **Beide Spieler müssen dieselbe Mod-Version (0.8.17) verwenden.**

## 0.8.5 — 2026-10-12

- **Verkehrs-, Geschwindigkeits- und Alkoholkontrollen** werden jetzt zwischen Host und Mitspieler synchronisiert — beide sehen dieselben laufenden Kontrollen, und die Zähler (geprüft / Verstöße / Bußgelder) gleichen sich ab.
- Hinweis: Protokoll-Version 9. **0.8.5 ist nicht mit 0.8.4 oder älter kompatibel** — ein älterer Mitspieler kann sich nicht verbinden, **beide müssen auf 0.8.5 aktualisieren**.

## 0.8.4 — 2026-10-12

- Die Freischaltung „Einsatzgebiet vergrößern" (zusätzliche Karten-Kacheln) kommt jetzt **live beim Mitspieler** an — beide sehen dasselbe erweiterte Einsatzgebiet.
- Hinweis: Protokoll-Version 8. 0.8.4 ist mit 0.8.3 kompatibel, aber **nicht** mit 0.8.2 oder älter — beide Spieler müssen mindestens auf 0.8.3 aktualisieren.

## 0.8.0 — 2026-10-12

Erste öffentliche Version.

- Koop-Multiplayer für zwei Spieler: gemeinsam eine Welt spielen — zusammen bauen, Einsätze fahren und die Wache managen.
- Ein Spieler ist Host (maßgeblich für Einsätze und Geld), der andere tritt als Client bei und erhält den Spielstand des Hosts.
- Installation und Download: siehe [Releases](https://github.com/muhzn1991/GlobalRescue-MP/releases) und die README.
