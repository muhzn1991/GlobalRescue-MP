# Global Rescue Multiplayer (GR-MP)

Koop-Multiplayer-Mod für **Global Rescue**. Zwei Spieler spielen gemeinsam in einer Welt: zusammen bauen, Einsätze fahren und die Wache managen. Ein Spieler ist **Host**, der andere **Client**. Der Host ist dabei für Einsätze und Geld maßgeblich (host-autoritativ), damit beide Seiten denselben Spielstand sehen.

> **Beta.** Bisher mit zwei Spielern getestet. Es können Fehler auftreten — Bugreports sind willkommen (siehe unten).

## Installation

1. Das Release-Zip herunterladen (siehe [Releases](https://github.com/muhzn1991/GlobalRescue-MP/releases)).
2. In das **Spielverzeichnis** von Global Rescue entpacken (dort, wo die Spiel-Programmdatei liegt).
3. Spiel normal starten — **fertig**.

**BepInEx ist im Zip enthalten** (Version 5.4.23) — keine separate Installation nötig.

**Beide Spieler müssen exakt dieselbe Mod-Version verwenden.** Unterschiedliche Versionen können sich nicht verbinden.

**Kompatibilität:** aktuelles Spiel-Content-Update, **Game-Build 25882902** → Mod **v0.8.25**. Die ältere **v0.8.5** war für die vorherige Spielversion (Build 24991330) und funktioniert seit dem Content-Update **nicht mehr** (deprecated). Immer die neueste Version aus den [Releases](https://github.com/muhzn1991/GlobalRescue-MP/releases) verwenden.

## Verbindung

- Der **Host** startet eine Sitzung aus dem laufenden Spiel heraus.
- Der **Client** tritt der Sitzung bei und erhält den Spielstand des Hosts übertragen.

Die genauen Schritte stehen in der dem Release beiliegenden Kurzanleitung.

## Mehr Wachen-Typen von Anfang an (optional)

Standardmäßig startet ihr nur mit der Fachrichtung, mit der der geladene Spielstand begonnen hat. Der **Host** kann weitere Wachen-Typen von Anfang an **kostenlos** freischalten.

Die Konfigurationsdatei `BepInEx/config/globalmp.spectator.cfg` wird von BepInEx erst beim **ersten Spielstart mit installiertem Mod** angelegt. Also zuerst die Mod installieren, das Spiel einmal starten und wieder beenden — danach ist die Datei da und kann bearbeitet werden.

Dort im Abschnitt `[Gr27]` die Zeile `StartDepartments` setzen, z. B.:

```
StartDepartments = Rescue,Police
```

- Gültige Werte (kommagetrennt): `Police`, `Swat`, `FireDepartment`, `Rescue`.
- Leer (Standard) = keine zusätzliche Fachrichtung.
- Diese Einstellung macht nur der **Host**; die Freischaltung gilt für **beide** Spieler (der Shop des Clients öffnet sich, sobald der Host sie spiegelt).
- Jede so freigeschaltete Fachrichtung erhöht zusätzlich das Basen-Limit um **+1**.

## Bekannte Einschränkungen

- Beta-Stand; getestet mit zwei Spielern.
- Der Host bleibt für Einsätze und Geld die maßgebliche Seite.

## Fehler melden

- Nutze die [Issues](https://github.com/muhzn1991/GlobalRescue-MP/issues) (Vorlage „Bug Report").
- **Logs:** `BepInEx/LogOutput.log` auf **beiden** Seiten. Die Datei wird **bei jedem Spielstart überschrieben** — bitte **vor einem Neustart sichern** und beide Logs an den Bugreport anhängen.

---

## English summary

**Global Rescue Multiplayer (GR-MP)** is a cooperative multiplayer mod for *Global Rescue*. Two players share one world — build together, run missions, manage the station. One player **hosts**, the other **joins** as a client; the host is authoritative for missions and money so both sides stay in sync.

**Install:** download the release zip and unzip it into the game directory (where the game executable lives), then launch the game — done. **BepInEx is bundled in the zip** (5.4.23), no separate install needed. Both players must run the **exact same mod version**. Requires the **current game content update (build 25882902)** → mod **v0.8.25**; the older **v0.8.5** was for the previous game version (build 24991330) and no longer works since the content update (deprecated). Always use the latest [release](https://github.com/muhzn1991/GlobalRescue-MP/releases).

**More station types from the start (optional):** the **host** can unlock extra department types for free at session start. BepInEx only writes `BepInEx/config/globalmp.spectator.cfg` on the **first launch with the mod installed**, so install the mod, start the game once and quit, then edit it: in section `[Gr27]`, set `StartDepartments` to a comma list of `Police`, `Swat`, `FireDepartment`, `Rescue` (e.g. `StartDepartments = Rescue,Police`; empty = none). It applies to **both** players, and each unlock also raises the base limit by **+1**.

**Connect:** the host starts a session in-game; the client joins and receives the host's save.

**Beta** — tested with two players; expect rough edges. Report bugs via [Issues](https://github.com/muhzn1991/GlobalRescue-MP/issues). Logs live at `BepInEx/LogOutput.log` on **both** sides and are **overwritten on every launch — save them before restarting** and attach both.

---

Lizenz: MIT (nur der Mod — das Spiel Global Rescue gehört seinen Entwicklern). Siehe [LICENSE](LICENSE).
