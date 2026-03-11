# Block 4: BIM I — Daten, AIA, IDS

> **Kontext:** Siehe `00-gesamtkontext.md` für Kursdaten, Lernziele und Constraints.
> Dies ist Block 4 von 7. Erster BIM-Fachblock — Einstieg über Daten und Standards.

---

## Eckdaten

| Feld | Wert |
|---|---|
| **Leitfrage** | *Wer braucht welche Daten wann?* |
| **Position im Kurs** | Block 4 von 7 — BIM-Basiskurs Teil 1 (Daten & Standards) |
| **Dauer** | 180 Minuten (inkl. 15 Min. Pause) |
| **Lernziel-Beitrag** | LZ 4: BIM-Modelle rollenspezifisch lesen / LZ 5: AIA/IDS formulieren und prüfen |
| **Tools** | BIMvision (IFC-Modell betrachten), ggf. IDS-Checker |
| **Vorgänger** | Block 3: KI Vertiefung & Übung |
| **Nachfolger** | Block 5: BIM II — Grundlagen & Modellierung |

---

## Zeitplanung

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Block 3 Recap, Brücke: "Wir können jetzt denken (LEAN) und Werkzeuge einsetzen (KI) — jetzt kommt der Fachinhalt: BIM" |
| 10–40 | **Theorie** | Was ist BIM? Nicht Software, sondern Methode. buildingSMART Foundation: openBIM-Prinzipien. Überblick Dimensionen (3D, 5D, 6D, 7D) |
| 40–70 | **Datenmanagement** | AIA (Auftraggeber-Informationsanforderungen): Wer definiert was? HOAI-Leistungsphasen als Rahmen für Datenanforderungen — welche Phase braucht welche Daten? |
| 70–85 | *Pause* | |
| 85–115 | **Standards** | IDS (Information Delivery Specification): AIA maschinenlesbar machen. Wie funktioniert IDS? Warum reicht eine AIA in Textform nicht? |
| 115–145 | **Praxis** | Datenperspektiven-Übung: Gleiches IFC-Modell, 4 Rollen (Bauherr, Fachplaner, FM-Manager, Bauunternehmer). Gruppen erarbeiten rollenspezifische Datenanforderungen |
| 145–170 | **KI-Exploration** | "Kann KI eine AIA für dieses Projekt generieren?" — Studierende testen, Ergebnis fachlich bewerten |
| 170–180 | **Abschluss** | Zusammenfassung, Ausblick Block 5 |

---

## Inhaltliche Details

### Theorie — Was ist BIM? (10–40 Min.)
- **BIM ≠ Software:** BIM ist eine Methode der Zusammenarbeit, nicht ein Programm
- **buildingSMART Foundation:** openBIM-Prinzipien, offene Standards
- **Dimensionen:** 3D (Modell), 5D (Kosten), 6D (Nachhaltigkeit), 7D (FM/Betrieb) — Überblick, keine Tiefe
- **HOAI/AHO:** Leistungsphasen als natürlicher Rahmen — welche Phase produziert/konsumiert welche Daten?
- **BIM-Einstieg über AIA muss schon in Phase 0 passieren** — nicht erst bei LP3

### Datenmanagement — AIA (40–70 Min.)
- **AIA erklärt:** Was ist eine AIA? Wer erstellt sie? Was steht drin?
- **Datenbedarf entlang HOAI:** Jede Leistungsphase definiert konkrete Arbeitsergebnisse → daraus ergibt sich der Datenbedarf
- **Spannungsfeld-Dreieck (aus Block 1) wieder aufgreifen:** Kosten/Qualität/Termine bestimmen welche Daten wann nötig sind
- **Praxisbeispiel:** Echte AIA (anonymisiert) zeigen — was steht drin, was fehlt typischerweise?

### Standards — IDS (85–115 Min.)
- **IDS erklärt:** Information Delivery Specification — buildingSMART Standard
- **Warum maschinenlesbar?** AIA als Textdokument = Interpretationsspielraum. IDS = eindeutig, prüfbar
- **Wie funktioniert IDS?** Grundstruktur, Anforderungen definieren, automatische Modellprüfung
- **Demo:** IDS-Checker zeigen (falls verfügbar), sonst Prinzip erklären

### Praxis — Datenperspektiven-Übung (115–145 Min.)
- **Gleiches IFC-Modell, 4 Rollen:**
  - Bauherr: Braucht Kostentransparenz, Terminübersicht
  - Fachplaner: Braucht geometrische Details, Schnittstellen
  - FM-Manager: Braucht Wartungsinfos, Raumflächen, technische Anlagen
  - Bauunternehmer: Braucht Mengen, Massen, Ausführungsdetails
- **Aufgabe:** Jede Gruppe erstellt eine Anforderungsliste für "ihre" Rolle
- **Ergebnis:** Konflikte und Überschneidungen sichtbar machen — genau dafür braucht man AIA

### KI-Exploration (145–170 Min.)
- **Aufgabe:** "Kann KI eine AIA für ein Bürogebäude generieren?"
- **LEAN-Filter:** Ist das Ergebnis brauchbar oder Verschwendung?
- **Fachprüfung:** Fehlen Anforderungen? Sind welche falsch?
- **Lehrpunkt:** KI kann eine Rohversion liefern, aber der Fachmann muss prüfen und ergänzen

---

## Inspiration & Ideen

- **AIA als Klammer des Kurses:** Block 4 öffnet die AIA, Block 6 prüft ob sie eingehalten wurde — roter Faden
- **HOAI-Phasen INNERHALB des Blocks:** Nicht als Blockstruktur, aber als Inhalt. "In LP1 brauchen wir X, in LP5 Y"
- **Rollenspiel:** Datenperspektiven-Übung kann auch als Rollenspiel funktionieren — Gruppen verhandeln um Datenanforderungen
- **Echte AIA vs. KI-AIA:** Sirris echte AIA aus einem Projekt neben KI-generierte legen — Unterschiede diskutieren
- **IDS als Brücke zu Block 5:** IDS prüft das Modell automatisch — was wir in Block 5 modellieren, muss Block-4-Anforderungen erfüllen

---

## Vorbereitung Sirri

- [ ] IFC-Modell für Datenperspektiven-Übung auswählen (einfach genug für 4 Rollen)
- [ ] Echte AIA (anonymisiert) als Anschauungsmaterial
- [ ] buildingSMART openBIM-Prinzipien: 3–5 Folien zusammenstellen
- [ ] IDS-Checker: Verfügbarkeit prüfen, ggf. Alternative für Demo
- [ ] HOAI-Leistungsphasen-Übersicht: Welche Phase → welche Daten (Tabelle/Folie)
