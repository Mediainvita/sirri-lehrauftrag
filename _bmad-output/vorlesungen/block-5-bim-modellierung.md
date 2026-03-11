# Block 5: BIM II — Grundlagen & Modellierung

> **Kontext:** Siehe `00-gesamtkontext.md` für Kursdaten, Lernziele und Constraints.
> Dies ist Block 5 von 7. Hands-on BIM — vom Modell verstehen zum Modell erstellen.

---

## Eckdaten

| Feld | Wert |
|---|---|
| **Leitfrage** | *Wie wird aus Zeichnung ein intelligentes Modell?* |
| **Position im Kurs** | Block 5 von 7 — BIM-Basiskurs Teil 2 (Modellierung) |
| **Dauer** | 180 Minuten (inkl. 15 Min. Pause) |
| **Lernziel-Beitrag** | LZ 4: BIM-Modelle rollenspezifisch lesen und anforderungsgerecht erstellen |
| **Tools** | BlenderBIM, IfcOpenShell, BIMvision |
| **Vorgänger** | Block 4: BIM I — Daten, AIA, IDS |
| **Nachfolger** | Block 6: BIM III — Kollaboration & CDE |

---

## Zeitplanung

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

---

## Inhaltliche Details

### Theorie — IFC & Open BIM (10–40 Min.)
- **IFC erklärt:** Industry Foundation Classes — offener, herstellerneutraler Standard
- **Aufbau:** Klassen (IfcWall, IfcDoor, IfcSpace...), Properties (Materialien, Brandschutz, U-Werte...), Relationen (Stockwerk enthält Raum enthält Tür)
- **LOD/LOG:** Level of Development / Level of Geometry — wann ist welcher Detailgrad nötig? Bezug zu AIA aus Block 4
- **Open BIM vs. Closed BIM:** Warum offene Standards wichtig sind — Herstellerunabhängigkeit, Langzeitarchivierung, Interoperabilität

### Demo — BlenderBIM & IfcOpenShell (40–70 Min.)
- **BlenderBIM Live-Modellierung:**
  - Wand erstellen, Eigenschaften zuweisen
  - Decke, Fenster hinzufügen
  - Zeigen: Was macht ein Objekt "intelligent"? (Geometrie + Daten)
- **IfcOpenShell:**
  - IFC-Datei öffnen, Daten auslesen
  - Properties eines Objekts anzeigen — was steckt drin?
  - Fehlende Properties identifizieren

### Praxis — Studierende modellieren (85–125 Min.)
- **Option A:** Einfaches Modell von Grund auf erstellen (Wand + Tür + Fenster + Properties)
- **Option B:** Bestehendes Modell modifizieren (Properties ergänzen, Objekte hinzufügen)
- **Ziel:** Nicht perfekte Modellierung, sondern Verständnis WIE Daten ins Modell kommen
- **Bezug zu Block 4:** Die AIA-Anforderungen aus der Datenperspektiven-Übung — können wir die jetzt im Modell abbilden?

### Vertiefung — Modellprüfung (125–155 Min.)
- **Anforderungsabgleich:** AIA aus Block 4 als Prüfgrundlage — sind alle geforderten Daten im Modell?
- **Kollisionsprüfung Grundlagen:** Was sind Kollisionen? Geometrisch vs. regelbasiert
- **IDS als automatische Prüfung:** Brücke von Block 4 zu Block 5 — IDS prüft ob Modell AIA-konform ist

### KI-Exploration (155–170 Min.)
- **Aufgabe:** "Kann KI fehlende IFC-Properties identifizieren?"
- **Test:** IfcOpenShell-Output an KI geben, nach Lücken fragen lassen
- **LEAN-Filter:** Schneller als manuell? Zuverlässig genug?
- **Studierende schlagen selbst vor:** Wo könnte KI bei der Modellierung noch helfen?

---

## Inspiration & Ideen

- **Open Source als Statement:** BlenderBIM + IfcOpenShell = komplett kostenfrei. Das ist Demokratisierung von BIM — passt zum Kursgedanken
- **IFC-Datei als "digitaler Zwilling light":** Studierende sehen live, dass ein IFC nicht nur Geometrie ist, sondern ein Datenbankcontainer
- **Brücke Block 4 → 5:** Die Anforderungen die Studierende in Block 4 aufgestellt haben, prüfen sie jetzt selbst am Modell. Erleben: AIA-Anforderungen ohne Modellverständnis aufstellen ist halbblind
- **IfcOpenShell als Python-Einstieg:** Für technikaffine Studierende — BIM-Daten mit ein paar Zeilen Code auslesen. Zeigt Automatisierungspotenzial
- **LOD-Diskussion:** "Wie detailliert muss ein Modell in LP2 sein vs. LP5?" — kein eindeutiges Richtig/Falsch, aber klare Konsequenzen bei Über- und Unterspezifikation (LEAN: Überproduktion!)

---

## Vorbereitung Sirri

- [ ] BlenderBIM: Auf Studierenden-Rechnern installierbar? Oder Sirri demonstriert, Studierende folgen an BIMvision?
- [ ] Demo-Modell: Einfaches Gebäude (max. 2 Stockwerke) in BlenderBIM vorbereiten
- [ ] IfcOpenShell: Beispiel-Skript zum Properties-Auslesen vorbereiten
- [ ] Praxis-Aufgabe: Aufgabenblatt mit klarem Ziel (z.B. "Füge diese 5 Properties zur Außenwand hinzu")
- [ ] IFC-Modell mit absichtlichen Lücken: Für Modellprüfungs-Übung
- [ ] Software-Installation: Studierende vorab informieren (BlenderBIM, IfcOpenShell via Moodle)
