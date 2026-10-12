# Global Rescue Multiplayer (GR-MP)

Koop-Multiplayer-Mod für **Global Rescue**. Zwei Spieler spielen gemeinsam in einer Welt: zusammen bauen, Einsätze fahren und die Wache managen. Ein Spieler ist **Host**, der andere **Client**. Der Host ist dabei für Einsätze und Geld maßgeblich (host-autoritativ), damit beide Seiten denselben Spielstand sehen.

> **Beta.** Bisher mit zwei Spielern getestet. Es können Fehler auftreten — Bugreports sind willkommen (siehe unten).

## Installation

1. **BepInEx 5.4.23 oder neuer** installieren (Mod-Loader für Unity-Spiele).
2. Das Release-Zip herunterladen (siehe [Releases](https://github.com/muhzn1991/GlobalRescue-MP/releases)) und in das **Spielverzeichnis** von Global Rescue entpacken (dort, wo die Spiel-Programmdatei liegt).
3. **Beide Spieler müssen exakt dieselbe Mod-Version verwenden.** Unterschiedliche Versionen können sich nicht verbinden.

**Kompatibilität:** Game-Build **24991330**.

## Verbindung

- Der **Host** startet eine Sitzung aus dem laufenden Spiel heraus.
- Der **Client** tritt der Sitzung bei und erhält den Spielstand des Hosts übertragen.

Die genauen Schritte stehen in der dem Release beiliegenden Kurzanleitung.

## Bekannte Einschränkungen

- Beta-Stand; getestet mit zwei Spielern.
- Der Host bleibt für Einsätze und Geld die maßgebliche Seite.

## Fehler melden

- Nutze die [Issues](https://github.com/muhzn1991/GlobalRescue-MP/issues) (Vorlage „Bug Report").
- **Logs:** `BepInEx/LogOutput.log` auf **beiden** Seiten. Die Datei wird **bei jedem Spielstart überschrieben** — bitte **vor einem Neustart sichern** und beide Logs an den Bugreport anhängen.

---

## English summary

**Global Rescue Multiplayer (GR-MP)** is a cooperative multiplayer mod for *Global Rescue*. Two players share one world — build together, run missions, manage the station. One player **hosts**, the other **joins** as a client; the host is authoritative for missions and money so both sides stay in sync.

**Install:** BepInEx 5.4.23+, unzip the release into the game directory, and make sure **both players run the exact same mod version**. Compatible with game build **24991330**.

**Connect:** the host starts a session in-game; the client joins and receives the host's save.

**Beta** — tested with two players; expect rough edges. Report bugs via [Issues](https://github.com/muhzn1991/GlobalRescue-MP/issues). Logs live at `BepInEx/LogOutput.log` on **both** sides and are **overwritten on every launch — save them before restarting** and attach both.
