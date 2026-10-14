# Changelog

Alle nennenswerten Änderungen an Global Rescue Multiplayer (GR-MP) werden hier festgehalten.
Neueste Version zuerst.

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
