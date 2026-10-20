# Changelog

Alle nennenswerten Änderungen an Global Rescue Multiplayer (GR-MP) werden hier festgehalten.
Neueste Version zuerst.

## 0.8.29 — 2026-10-20

Diese Version fasst die interne 0.8.28 und 0.8.29 zusammen.

- **Der Mitspieler kann seine eigene Basis vergrößern.** Vergrößert der Client seine Basis, passiert das jetzt auch beim Host; die Kosten bucht wie üblich der Host von der gemeinsamen Kasse. Kostet die Erweiterung im Spiel nichts (z. B. bei manchen Vorlage- oder Spielstand-Basen), ist sie auch im Mehrspieler kostenlos. Das Vergrößern durch den Host kommt wie bisher beim Mitspieler an.
- **Bekannte Einschränkung: Basis verkleinern ist im Mehrspieler vorerst gesperrt (für beide Spieler).** Nur das Vergrößern wird bisher synchronisiert; ein Verkleinern wird mit einem Hinweis abgelehnt.
- **Automatischer Abgleich während der Sitzung.** Laufen Fahrzeuge oder Einsätze zwischen Host und Mitspieler auseinander, gleicht die Mod das jetzt selbstständig wieder an. Abweichungen bei Gebäuden werden vorerst nur erkannt und im Log vermerkt, noch nicht automatisch repariert.
- **Flüssiger:** Wenn der Mitspieler seine Basis vergrößert oder eine neue gründet, gibt es beim Host keinen kurzen Hänger mehr.
- **Bessere Fehlerberichte:** Das Log nennt bei Einsätzen und Aufgaben jetzt deren Namen — das hilft uns, gemeldete Probleme schneller zu finden.
- **Beta — bekannte Probleme (in Arbeit):** gleichzeitiges Bauen auf **dieselbe Stelle** kollidiert (das Geld wird automatisch erstattet); Basis **verkleinern** ist im Mehrspieler gesperrt (siehe oben).
- Benötigt das aktuelle Spiel-Update (**Game-Build 25930144**). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.29) verwenden**; mit einer älteren Version beim Mitspieler kommt das Vergrößern der Basis nicht an.

## 0.8.27 — 2026-10-19

- **Update-Pflicht nach dem Spiel-Update vom 16.10.: bitte beide Spieler auf 0.8.27 aktualisieren.** Das Spiel-Update (Build 25930144) hat interne Namen geändert, auf die die Mod angewiesen ist. Ältere Mod-Versionen (bis 0.8.26) laufen darauf nur eingeschränkt — u. a. kann der Mitspieler keine Fahrzeuge zu Einsätzen alarmieren. 0.8.27 behebt das.
- **Mitspieler kann wieder Einsätze fahren.** Fahrzeuge des Mitspielers lassen sich wieder zu Einsätzen alarmieren.
- **Forschung funktioniert wieder korrekt.** Durch Forschung freigeschaltete Fahrzeuge kommen beim Mitspieler an; Forschung kaufen bleibt wie bisher Sache des Hosts.
- **Verkehrskontrollen wieder korrekt.** Kontrollen, Verstöße und Bußgelder werden wieder nur beim Host gezählt (keine doppelte Wertung).
- **Weitere Korrekturen für den neuen Spiel-Build:** Abteilungen, Fahrzeugkauf, Abriss-Erstattung und Parkplatz-Zuweisung beim Mitspieler. Außerdem läuft das Übernehmen großer Bauten des Mitspielers noch etwas flüssiger.
- **Beta — bekannte Probleme (in Arbeit):** gleichzeitiges Bauen auf **dieselbe Stelle** kollidiert (das Geld wird automatisch erstattet); das **Vergrößern der Basis durch den Client** wird noch nicht synchronisiert.
- Benötigt das aktuelle Spiel-Update (**Game-Build 25930144**). Protokoll-Version 10 — **beide Spieler müssen dieselbe Mod-Version (0.8.27) verwenden.**

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
