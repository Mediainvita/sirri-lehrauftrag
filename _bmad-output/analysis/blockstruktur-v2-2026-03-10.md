---
version: 2
date: 2026-03-10
status: draft
basis: brainstorming-session-2026-03-04.md + Transkript Sirri-Lehrplan-Next-10-03-2026
changes_from_v1:
  - HOAI-Phasen nicht mehr Blockstruktur, sondern Inhalt innerhalb Blöcke
  - Thematische Blöcke statt phasenorientierte
  - LEAN + KI früh (Block 2+3), BIM ab Block 4
  - Lernziel 4 (Systembrüche zwischen HOAI-Phasen) entfernt
  - Prüfung separat (nicht Teil eines Blocks)
  - Gastvorträge nicht eingeplant (Sirri entscheidet situativ)
  - BIM-Blöcke 4-6 orientiert an buildingSMART Basiskurs
---

# Blockstruktur v2 — Lehrauftrag "Digitalisierung in der Bau- und Immobilienwirtschaft"

**Dozent:** Sirri El Jundi
**Zielgruppe:** Bauingenieure & Wirtschaftsingenieure, 6. Semester
**Format:** 7 Doppelblöcke (alle 14 Tage, je ~180 Min.)
**Prüfung:** Separat, mündlich, 15 Min., ~30 Fragen
**Lernplattform:** Moodle

## Gesamtübersicht

| Block | Thema | Leitfrage | Tools | KI-Rolle |
|---|---|---|---|---|
| 1 | Warum digitalisieren? | *Wann lohnt es sich — und wann nicht?* | BIMvision | — |
| 2 | LEAN + KI Einstieg | *Richtig denken + richtig einsetzen* | ChatGPT/Claude | Live-Demo + Übung |
| 3 | KI Vertiefung & Übung | *LEAN+KI kombiniert anwenden* | ChatGPT/Claude + Material | Sirri-Übung A/B/C/D |
| 4 | BIM I: Daten, AIA, IDS | *Wer braucht welche Daten wann?* | BIMvision, IDS-Checker | AIA generieren |
| 5 | BIM II: Modellierung | *Wie wird aus Zeichnung ein intelligentes Modell?* | BlenderBIM, IfcOpenShell | IFC-Properties prüfen |
| 6 | BIM III: Kollaboration & CDE | *Wie arbeiten viele Beteiligte an einem Modell?* | Catenda, BIMvision | BCF/Kollision mit KI |
| 7 | Synthese & Ausblick | *Was haben wir gelernt — was kommt als Nächstes?* | — | Reflexion |

**Durchgehende Haltungen (kein eigener Block):** Change Management, Pfadfinder-Pädagogik, iteratives Denken

---

## Block 1: Warum digitalisieren?

*Leitfrage: "Wann lohnt es sich — und wann nicht?"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–15 | **Vorstellung** | Vorstellungsrunde, Kursablauf, Erwartungen, Pfadfinder-Motto vorstellen |
| 15–45 | **Theorie** | Digitalisierung in der Bauwirtschaft: Status quo, Zahlen, typische Probleme. Wo steht die Branche wirklich? |
| 45–75 | **Konzept** | Kosten-Nutzen-Abwägung: Ab wann schafft Digitalisierung Mehrwert? Spannungsfeld-Dreieck (Kosten/Qualität/Termine). Hype-Check: Marketing vs. Realität |
| 75–90 | *Pause* | |
| 90–130 | **Vertiefung** | Perspektivwechsel: Bauherr, Planer, Ausführender, Betreiber — wer profitiert wie von Digitalisierung? Change Management als durchgehende Haltung einführen |
| 130–165 | **Praxis** | Diskussion/Gruppenarbeit: Studierende bewerten ein konkretes Szenario — digitalisieren ja/nein? Begründung mit Kosten-Nutzen |
| 165–180 | **Abschluss** | Zusammenfassung, Ausblick Block 2, Moodle-Materialien |

**Tools:** BIMvision (kurze IFC-Demo zum Einstieg — "so sieht ein digitales Gebäude aus")

---

## Block 2: LEAN + KI Einstieg

*Leitfrage: "Richtig denken (LEAN) + richtig einsetzen (KI)"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Block 1 Recap, Brücke: "Wir wissen jetzt WARUM — jetzt lernen wir WIE wir denken und arbeiten" |
| 10–50 | **LEAN Theorie** | 7+1 Verschwendungsarten (Muda) mit Bau-Beispielen. Kernprinzip: Erst Prozess verstehen, dann digitalisieren. Wer das nicht tut, digitalisiert den Müll |
| 50–75 | **LEAN Übung** | Szenario: Planungsänderung LP3→LP5 per E-Mail-Kette. Gruppen identifizieren Verschwendungsarten |
| 75–90 | *Pause* | |
| 90–110 | **KI-Kompass** | Framework einführen: (1) Was will ich erreichen? (2) Welche Info brauche ich? (3) Welches Tool? (4) Stimmt das Ergebnis? |
| 110–140 | **Live-Demo** | Sirri löst ein BIM-Fachproblem mit KI (z.B. Leistungsbeschreibung Fassade). Schritt für Schritt am KI-Kompass entlang. Fehler zeigen, Ergebnis fachlich prüfen |
| 140–170 | **Praxis** | Studierende prompten selbst (ähnliche Aufgabe, andere Parameter). Ergebnisse vergleichen: Wer hatte den besten Prompt? Wo hat KI Unsinn erzählt? |
| 170–180 | **Brücke** | LEAN-Filter auf KI anwenden: "War dieser KI-Einsatz Mehrwert oder Verschwendung?" Ausblick Block 3 |

**Tools:** ChatGPT / Claude (Studierende nutzen eigene Accounts)

---

## Block 3: KI Vertiefung & Übung

*Leitfrage: "LEAN + KI kombiniert anwenden und üben"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Block 2 Recap, KI-Kompass + LEAN kurz auffrischen |
| 10–40 | **Theorie** | LEAN+KI Kombi-Methode: LEAN identifiziert das Problem, KI-Kompass strukturiert die Lösung. Parallelen explizit machen. Halluzinationen bei Normen/Standards als bekanntes Risiko |
| 40–50 | **Stationen-Briefing** | 4 Stationen erklären, Gruppen einteilen |
| 50–75 | **Sirri-Übung A** | Station A — Inhalt und Aufgabe von Sirri |
| 75–90 | *Pause* | |
| 90–115 | **Sirri-Übung B** | Station B — Inhalt und Aufgabe von Sirri |
| 115–140 | **Sirri-Übung C** | Station C — Inhalt und Aufgabe von Sirri |
| 140–160 | **Sirri-Übung D** | Station D — Inhalt und Aufgabe von Sirri |
| 160–180 | **Reflexion** | Was hat funktioniert, was nicht? Gemeinsam 3 Regeln für KI-Einsatz im Kurs aufstellen. Diese gelten ab jetzt |

**Tools:** ChatGPT / Claude + fachspezifische Materialien je Station

---

## Block 4: BIM I — Daten, AIA, IDS

*Leitfrage: "Wer braucht welche Daten wann?"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Block 3 Recap, Brücke: "Wir können jetzt denken (LEAN) und Werkzeuge einsetzen (KI) — jetzt kommt der Fachinhalt: BIM" |
| 10–40 | **Theorie** | Was ist BIM? Nicht Software, sondern Methode. buildingSMART Foundation: openBIM-Prinzipien. Überblick Dimensionen (3D, 4D, 5D, 6D, 7D) |
| 40–70 | **Datenmanagement** | AIA (Auftraggeber-Informationsanforderungen): Wer definiert was? HOAI-Leistungsphasen als Rahmen für Datenanforderungen — welche Phase braucht welche Daten? |
| 70–85 | *Pause* | |
| 85–115 | **Standards** | IDS (Information Delivery Specification): AIA maschinenlesbar machen. Wie funktioniert IDS? Warum reicht eine AIA in Textform nicht? |
| 115–145 | **Praxis** | Datenperspektiven-Übung: Gleiches IFC-Modell, 4 Rollen (Bauherr, Fachplaner, FM-Manager, Bauunternehmer). Gruppen erarbeiten rollenspezifische Datenanforderungen |
| 145–170 | **KI-Exploration** | "Kann KI eine AIA für dieses Projekt generieren?" — Studierende testen, Ergebnis fachlich bewerten |
| 170–180 | **Abschluss** | Zusammenfassung, Ausblick Block 5 |

**Tools:** BIMvision (IFC-Modell betrachten), ggf. IDS-Checker

---

## Block 5: BIM II — Grundlagen & Modellierung

*Leitfrage: "Wie wird aus Zeichnung ein intelligentes Modell?"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Block 4 Recap, Brücke: "Wir wissen was wir brauchen (AIA/IDS) — jetzt lernen wir wie ein Modell entsteht" |
| 10–40 | **Theorie** | IFC als offener Standard: Was steckt drin? Klassen, Properties, Relationen. LOD/LOG: Wann ist ein Modell "fertig genug"? Open BIM vs. Closed BIM |
| 40–70 | **Demo** | BlenderBIM: Sirri zeigt Modellaufbau. Wand, Decke, Fenster — wie werden Objekte intelligent? IfcOpenShell: Modelldaten auslesen, Properties prüfen |
| 70–85 | *Pause* | |
| 85–125 | **Praxis** | Studierende arbeiten mit BlenderBIM: Einfaches Modell erstellen oder bestehendes Modell modifizieren. Ziel: Verstehen wie Daten ins Modell kommen |
| 125–155 | **Vertiefung** | Modellprüfung: Entspricht das Modell den Anforderungen aus der AIA (Block 4)? Kollisionsprüfung Grundlagen. IDS als automatische Prüfung |
| 155–170 | **KI-Exploration** | "Kann KI IFC-Properties prüfen oder fehlende Attribute identifizieren?" — Test mit IfcOpenShell + KI |
| 170–180 | **Abschluss** | Zusammenfassung, Ausblick Block 6 |

**Tools:** BlenderBIM, IfcOpenShell, BIMvision

---

## Block 6: BIM III — Kollaboration & CDE

*Leitfrage: "Wie arbeiten viele Beteiligte an einem Modell?"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Block 5 Recap, Brücke: "Ein Modell alleine ist Insellösung — jetzt wird zusammengearbeitet" |
| 10–40 | **Theorie** | CDE-Konzept: Gemeinsame Datenumgebung als Nervensystem. Warum E-Mail+Server nicht reicht (LEAN: Verschwendung!). BCF-Issues: Kommunikation im Modellkontext |
| 40–70 | **Demo** | Catenda: IFC hochladen, navigieren, BCF-Issue anlegen, Modellversionen vergleichen. Reale Arbeitsumgebung zeigen |
| 70–85 | *Pause* | |
| 85–120 | **Praxis** | Übergabe-Simulation: Gruppe A erstellt/bearbeitet Modell (LP2), übergibt ohne Rückfragen an Gruppe B (LP5). Was fehlt? Was ist falsch dokumentiert? Wo entstehen Kosten? |
| 120–150 | **Vertiefung** | Koordination: Wie laufen Fachmodelle zusammen? Rollen und Verantwortlichkeiten in der BIM-Kollaboration. Kollaboration als Kompetenz (Change Management) |
| 150–170 | **KI-Exploration** | "Kann KI ein Meeting-Protokoll in BCF-Issues übersetzen?" oder "Kann KI Kollisionsergebnisse priorisieren?" |
| 170–180 | **Abschluss** | Zusammenfassung, Ausblick Block 7 |

**Tools:** Catenda, BIMvision

---

## Block 7: Synthese & Ausblick

*Leitfrage: "Was haben wir gelernt — und was kommt als Nächstes?"*

| Zeit | Phase | Inhalt |
|---|---|---|
| 0–10 | **Rückblick** | Gesamter Kurs Recap: Block 1→6 in 5 Minuten |
| 10–40 | **Integration** | Roter Faden sichtbar machen: LEAN als Denkweise → KI als Werkzeug → BIM als Methode → Kollaboration als Kompetenz. Wie hängt alles zusammen? |
| 40–70 | **Ausblick** | Wohin geht die Reise? Digital Twins, Materialpassport, Circular Economy, Automatisierung. Was davon ist in 5 Jahren Alltag, was bleibt Vision? |
| 70–85 | *Pause* | |
| 85–120 | **Reflexion** | Offene Diskussion: Was war überraschend? Wo hat sich eure Meinung geändert? Was nehmt ihr mit in die Praxis? KI-Regeln aus Block 3 revisieren — gelten sie noch? |
| 120–155 | **Prüfungsvorbereitung** | Überblick Prüfungsformat (mündlich, 15 Min., ~30 Fragen). Beispielfragen durchgehen. Offene Fragen klären |
| 155–175 | **Kursabschluss** | Feedback-Runde, Pfadfinder-Motto revisited: "Welche Landmarks kennt ihr jetzt, die ihr vorher nicht kanntet?" |
| 175–180 | **Ende** | Verabschiedung |

**Tools:** —

---

## Lernziele (aktualisiert)

1. Digitalisierungsentscheidungen wirtschaftlich bewerten (Kosten-Nutzen, Schwelle)
2. Prozesse auf Verschwendung analysieren — LEAN als Digitalisierungskompass
3. KI-Tools kontextbezogen evaluieren und anwenden (KI-Kompass)
4. BIM-Modelle rollenspezifisch lesen und anforderungsgerecht erstellen
5. Informationsanforderungen (AIA/IDS) formulieren und prüfen
6. In einer CDE kollaborativ arbeiten und Übergaben strukturieren

*Entfernt: "Systembrüche zwischen HOAI-Phasen erkennen, benennen und vermeiden" (ehemals Lernziel 4)*

---

## Offene Punkte

- ⚠️ Materialpassport/Rückbau: Ausblick Block 7 oder raus?
- ⚠️ Sirri-Übungen A–D für Block 3: Sirri gestaltet selbst
- ⚠️ Prüfungsfragen: ~30 Fragen aus allen 7 Blöcken erstellen
