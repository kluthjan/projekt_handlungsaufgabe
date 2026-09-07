# 🚀 Projekt Handlungsaufgabe: IT-Ausstattung Planungs- & Konstruktionsbüro

> **Kunde:** VektorPlan GmbH (Architektur- und Ingenieurgesellschaft, Düsseldorf)  
> **Auftragnehmer:** NextLevel IT Solutions GmbH (IT-Systemhaus, Köln)  
> **Projektzeitraum:** 46 Arbeitstage (Gesamtdauer nach DIN 69900 Netzplan)  
> **Gesamtangebotssumme:** 67.179,32 € netto (79.943,39 € brutto)  
> **Repository:** [github.com/kluthjan/projekt_handlungsaufgabe](https://github.com/kluthjan/projekt_handlungsaufgabe)

---

## 📌 Inhaltsverzeichnis
1. [Schnellstart & Download-Anleitung für Mitschüler](#-1-schnellstart--download-anleitung-für-mitschüler)
2. [Unser Projektteam & Rollenverteilung](#-2-unser-projektteam--rollenverteilung)
3. [Was haben wir gemacht? – Das Projekt einfach erklärt](#-3-was-haben-wir-gemacht--das-projekt-einfach-erklärt)
4. [Datei-Kompass: Wo finde ich was, wenn der Lehrer fragt?](#-4-datei-kompass-wo-finde-ich-was-wenn-der-lehrer-fragt)
5. [Leitfaden für die 10-Minuten-Abschlusspräsentation](#-5-leitfaden-für-die-10-minuten-abschlusspräsentation)
6. [Prüfer-Spickzettel: Die 6 wichtigsten Lehrerfragen & Antworten](#-6-prüfer-spickzettel-die-6-wichtigsten-lehrerfragen--antworten)

---

## 📥 1. Schnellstart & Download-Anleitung für Mitschüler

Damit jedes Teammitglied alle aktuellen Unterlagen, Excel-Tabellen, Word-Dokumente und die PowerPoint-Präsentation sofort einsatzbereit auf dem eigenen PC hat, gibt es zwei Wege:

### Option A: Über Git (Empfohlen für Updates)
1. Öffne das Terminal (PowerShell oder Eingabeaufforderung / Git Bash).
2. Wechsle in den gewünschten Ordner (z. B. Desktop):
   ```bash
   cd Desktop
   ```
3. Klone das Repository:
   ```bash
   git clone https://github.com/kluthjan/projekt_handlungsaufgabe.git
   ```
4. Wechsle in den Projektordner:
   ```bash
   cd projekt_handlungsaufgabe
   ```
5. **Wichtig vor Unterricht/Präsentation:** Hole dir immer den allerneuesten Stand:
   ```bash
   git pull origin main
   ```

### Option B: Als ZIP-Datei herunterladen (Ohne Git-Installation)
1. Öffne im Browser den Link: [https://github.com/kluthjan/projekt_handlungsaufgabe](https://github.com/kluthjan/projekt_handlungsaufgabe)
2. Klicke oben rechts auf den grünen Button **`Code`** (mit Download-Symbol).
3. Klicke im Menü auf **`Download ZIP`**.
4. Speichere die Datei (z. B. auf dem Desktop) und entpacke die ZIP-Datei per Rechtsklick -> *Alle extrahieren...*.

### 📱 Alle Dokumente direkt im Browser lesbar (PDF-Zwillinge)
Jedes Word-Dokument und die Präsentation liegen nun zusätzlich als **druckfertige PDF-Datei** vor. Auf GitHub könnt ihr einfach auf die PDF-Datei klicken und sie öffnet sich sofort direkt im Browser (kein MS Office erforderlich, ideal auch für Tablets und Smartphones)!

---

## 👥 2. Unser Projektteam & Rollenverteilung

| Teammitglied | Rolle im IT-Systemhaus | Aufgabenbereich & Verantwortung | Präsentations-Folien |
|---|---|---|---|
| **Jan Kluth** | **Projektleiter (PL)** | Gesamtkoordination, Projektorganisation, Ablaufplanung, Moderation | Folien 1 – 4 (Intro, Agenda, Auftrag, Team) |
| **Mathias Vonau** | **Technischer Planer** | Anforderungsanalyse, Lastenheft, Hardware-Konfiguration, Netzwerkkonzept | Folien 5 – 7 (PSP, Netzplan, Lastenheft) |
| **Marian Bolecke** | **Beschaffung & Kalkulation** | Marktrecherche, Nutzwertanalysen, Vorwärtskalkulation, Angebot | Folien 8 – 10 (Produkte, Nutzwertanalyse, Kalkulation) |
| **Siyar** | **Berechnungen & Controlling** | Spezifische Kundenberechnungen (Speicher & Strom), Rollout-Dokumentation | Folien 11 – 13 (Kundenberechnungen, Rollout & Checkliste) |
| **Marco Schmidt** | **Qualitätsmanagement & Recht** | Wareneingang (§ 377 HGB), Mängelrüge, Entsorgung (ElektroG), Lessons Learned | Folien 14 – 16 (Wareneingang, Entsorgung, Lessons Learned) |

---

## 🧠 3. Was haben wir gemacht? – Das Projekt einfach erklärt

### Die Ausgangssituation
Unser Kunde, die **VektorPlan GmbH**, modernisiert ihre Geschäftsräume und benötigt eine moderne IT-Ausstattung für:
- **12 Standard-Büroarbeitsplätze** (Bauleitung, Projektmanagement, Ausschreibung)
- **4 High-End CAD/BIM-Workstations** (3D-Konstruktion, fotorealistisches Rendering)
- **32 ergonomische 27" Monitore** (exakt 2 Monitore pro Arbeitsplatz)
- **1 zentraler A3/A4 Farblaser-Multifunktionsdrucker (MFP)** für die Plotter- und Scanstation
- **Sichere Peripherie & Software:** Verschlüsselte Tastatur-Maus-Sets, externe 1-TB-SSDs, Windows 11 Pro, Microsoft 365, Adobe Acrobat, ESET Endpoint Security.
- **Dienstleistungen:** Vorinstallation im Systemhaus, strukturierte Verkabelung, ergonomische Ausrichtung nach ArbStättV, Funktionstest und Altgeräte-Entsorgung.

### Unsere wichtigsten Entscheidungen & Meilensteine

1. **Strukturierte Planung (Aufgabe 1):**
   - Wir haben einen **Projektstrukturplan (PSP nach DIN 69901)** mit 5 Phasen und exakt 30 Arbeitspaketen aufgebaut.
   - Mit einer **Vorgangsliste (14 Vorgänge)** und dem **DIN 69900 Netzplan** haben wir die exakte Projektdauer berechnet: **46 Arbeitstage**. Der kritische Pfad läuft linear durch alle Hauptvorgänge.

2. **Objektive Produktauswahl durch Nutzwertanalyse (Aufgabe 3):**
   - Statt einfach "irgendwas" zu kaufen, haben wir echte Marktangebote (Lenovo, Dell, HP, EIZO) in einer gewichteten Entscheidungsmatrix (1–10 Punkte) verglichen.
   - **Büro-PC:** Lenovo ThinkCentre M70s Gen 4 (leise, kompakt, 16 GB RAM, zuverlässig).
   - **CAD-Workstation-Sieger:** Lenovo ThinkStation P3 Tower (Nutzwert 8,70). Grund: Die dedizierte NVIDIA RTX 4000 Ada (20 GB VRAM) ist für CAD/BIM-Architektursoftware wie Revit/AutoCAD unschlagbar.
   - **Monitor-Sieger:** Dell UltraSharp U2724D (Nutzwert 9,10). Grund: IPS Black Panel mit 2000:1 Kontrast, 120 Hz, Hardware-Blaulichtfilter (ComfortView Plus) und voller 4-Wege-Ergonomie (Höhe, Pivot, Tilt, Swivel).

3. **Kaufmännische Vorwärtskalkulation (Aufgabe 4):**
   - Beginnend beim Bareinkaufspreis über Bezugskosten (3 %), **Handlungskostenzuschlag (25 %)**, **Gewinnzuschlag (12 %)** und **Kundenskonto (3 %)** haben wir den Listenverkaufspreis kalkuliert.
   - Gesamtangebot: **67.179,32 € netto** (Hardware 44.979,32 €, Software-Abos 16.150,00 €, Services 6.050,00 €).

4. **Spezifische Kundenberechnungen (Aufgabe B):**
   - **Speicherplatzbedarf Fileserver (B.1):** 16 Arbeitsplätze × 350 MiB/Tag × 65 Tage = 364.000 MiB. Durch Binärumrechnung (/ 1024) ergibt das netto 355,47 GiB -> gerundet **356 GiB**. Mit **25 % Puffer** für Lastspitzen empfahl unser Team **445 GiB** (RAID-10 mit Enterprise NVMe-SSDs).
   - **Energiekosten (B.2):** 12 Büro-PCs (je 140 W) + 4 CAD-Workstations (je 320 W) = 2.960 W (2,96 kW). Bei 220 Arbeitstagen à 8,5 Stunden und 0,32 €/kWh ergeben sich **5.535,2 kWh/Jahr** und Stromkosten von exakt **1.771,26 € netto pro Jahr**.

5. **Recht, Netzwerk & Qualitätssicherung (Aufgabe 2, 5, 6 & 7):**
   - **Netzwerkkonzept:** Strukturierte Cat.6a S/FTP-Verkabelung mit VLAN-Segmentierung (VLAN 20 Büro, VLAN 30 CAD, VLAN 40 Drucker, VLAN 50 Storage) und festem IP-Plan.
   - **Wareneingang:** Gemäß **§ 377 HGB** gilt unter Kaufleuten eine unverzügliche Untersuchungs- und Rügepflicht. Wir haben eine Muster-Mängelrüge mit 14-tägiger Frist vorbereitet, um die Genehmigungsfiktion abzuwenden.
   - **Entsorgung:** Der alte Bürodrucker wird nach **ElektroG (Kategorie 6)** entsorgt: Tonerkassetten gehen getrennt ins Recycling, interne Festplatten werden nach **BSI-Standard 3-fach überschrieben**, um Kundendaten zu schützen.
   - **Rollout:** Ausrichtung der 32 Monitore nach **Arbeitsstättenverordnung (ArbStättV)** (50–70 cm Sehabstand, Oberkante auf Augenhöhe, reflexionsfrei).

---

## 🧭 4. Datei-Kompass: Wo finde ich was, wenn der Lehrer fragt?

> 🏆 **WICHTIGSTE DATEI ZUR ABGABE (MASTER-DOKUMENTATION):**  
> Wenn der Lehrer nach der **„Projektdokumentation“** fragt oder ein Gesamtdokument zur Benotung sehen will, legt ihr ihm die Datei  
> 📄 **`docs/Projektdokumentation_Handlungsaufgabe.pdf`** (oder als Word-Datei **`.docx`**) vor!  
> Dieses **16-seitige Hauptdokument** vereint alle Aufgaben (A bis C, B.1/B.2, 1 bis 8) lückenlos mit allen Rechenwegen, Tabellen, Spezifikationen und Rechtsgrundlagen. Alle nachfolgenden Dateien in der Tabelle sind die vertiefenden Detail- und Arbeitsdateien.

| Aufgabe laut Aufgabenstellung | Thema & Inhalt | Dateipfad im Projekt (Word / PDF / Excel) | Wichtigste Kennzahlen / Fakten |
|---|---|---|---|
| ⭐ **GESAMT-DOKUMENTATION** | **Offizieller Projektbericht (16 Seiten)** | **`docs/Projektdokumentation_Handlungsaufgabe.pdf`**<br>`docs/Projektdokumentation_Handlungsaufgabe.docx` | **Komplette Dokumentation aller Aufgaben (A–C, 1–8)**, alle Formeln, Tabellen & Nachweise |
| **Aufgabe A** | Ausgangssituation & Auftrag | `Projekt_Handlungsaufgabe.docx` | 16 Arbeitsplätze (12 Office, 4 CAD), Plotterstation |
| **Aufgabe B.1** | Speicherplatzbedarf Fileserver | `docs/Berechnungen/Speicherplatzberechnung.xlsx`<br>`docs/Berechnungen/Kundenberechnungen_Dokumentation.pdf` | **445 GiB** Quartalsbedarf (356 GiB Netto + 25% Puffer, Teiler 1024) |
| **Aufgabe B.2** | Energiekostenkalkulation | `docs/Berechnungen/Energiekostenkalkulation.xlsx`<br>`docs/Berechnungen/Kundenberechnungen.xlsx` | **1.771,26 €/Jahr** (2,96 kW Gesamtlast, 5.535,2 kWh/a, 0,32 €/kWh) |
| **Aufgabe 1a** | Vorgangsliste (Ablauf & Dauern) | `docs/01_Projektorganisation/Vorgangsliste.xlsx` | 14 Vorgänge im Wasserfallmodell, Zuständigkeiten aller 5 Mitglieder |
| **Aufgabe 1b** | DIN 69900 Netzplan | `docs/01_Projektorganisation/Netzplan.xlsx`<br>`docs/01_Projektorganisation/Netzplan.md` | **46 Tage Projektdauer**, Vorwärts-/Rückwärtsrechnung, Pufferzeiten |
| **Aufgabe 1c** | DIN 69901 Projektstrukturplan | `docs/01_Projektorganisation/Projektstrukturplan.xlsx`<br>`docs/01_Projektorganisation/Projektstrukturplan.md` | **5 Hauptphasen, 30 Arbeitspakete**, objekt-/phasenorientiert |
| **Aufgabe 1d** | Terminplan (Gantt) & Risiken | `docs/01_Projektorganisation/Gantt_Diagramm.xlsx`<br>`docs/01_Projektorganisation/Risikoanalyse.xlsx` | 7 Projektrisiken mit Risikomatrix & Ampelfarben |
| **Aufgabe 2a** | Lastenheft (Soll-Konzept) | `docs/02_Anforderungsanalyse/Lastenheft.pdf`<br>`docs/02_Anforderungsanalyse/Lastenheft.docx` | Vollständige Kundenvorgaben (Hardware, Software, Service, Ergonomie) |
| **Aufgabe 2b** | Netzwerkkonzept & IP-Plan | `docs/02_Anforderungsanalyse/Netzwerkkonzept.pdf`<br>`docs/02_Anforderungsanalyse/Netzwerkkonzept.docx` | **Cat.6a S/FTP, VLAN-Segmentierung (20, 30, 40, 50)**, 48-Port Matrix |
| **Aufgabe 3** | Marktrecherche & Nutzwertanalyse | `docs/03_Marktrecherche/Produktrecherche.xlsx`<br>`docs/03_Marktrecherche/Nutzwertanalyse_Workstations.xlsx`<br>`docs/03_Marktrecherche/Nutzwertanalyse_Monitore.xlsx` | Reale Preise, ThinkStation P3 (8,70 Pkt.) & Dell U2724D (9,10 Pkt.) |
| **Aufgabe 4a** | Kaufmännische Kalkulation | `docs/04_Angebot/Vorwaertskalkulation.xlsx` | Bezugspreis -> HK (25%) -> Gewinn (12%) -> Skonto (3%) |
| **Aufgabe 4b** | Formelles Angebot an Kunden | `docs/04_Angebot/Angebot_VektorPlan.pdf`<br>`docs/04_Angebot/Angebot_VektorPlan.docx` | DIN 5008 Geschäftsbrief, **67.179,32 € netto**, Zahlungsbedingungen |
| **Aufgabe 4c** | Finanzierungsberatung | `docs/04_Angebot/Infoblatt_Leasing_vs_Kauf.pdf`<br>`docs/04_Angebot/Infoblatt_Leasing_vs_Kauf.docx` | CAPEX vs. OPEX, Liquidität, steuerliche Behandlung, AfA |
| **Aufgabe 5a** | Wareneingangsprüfung (§ 377 HGB) | `docs/05_Wareneingang/Wareneingangspruefung.pdf`<br>`docs/05_Wareneingang/Wareneingangspruefung.docx` | **§ 377 HGB**, offene vs. verdeckte Mängel, Genehmigungsfiktion |
| **Aufgabe 5b** | Formelle Mängelrüge an Lieferant | `docs/05_Wareneingang/Maengelruege.pdf`<br>`docs/05_Wareneingang/Maengelruege.docx` | Rechtssichere Rüge Transportschaden & Falschlieferung (14-Tage-Frist) |
| **Aufgabe 6** | Umwelt- & Entsorgungskonzept | `docs/06_Entsorgung/Entsorgungskonzept.pdf`<br>`docs/06_Entsorgung/Entsorgungskonzept.docx` | **ElektroG (Kat. 6)**, BSI-Datenlöschung, Toner-Recycling |
| **Aufgabe 7a** | Inbetriebnahme-Checkliste | `docs/07_Rollout/Checkliste_Inbetriebnahme.pdf`<br>`docs/07_Rollout/Checkliste_Inbetriebnahme.docx` | ArbStättV-Checkliste, Kabelmanagement, Funktionstests vor Ort |
| **Aufgabe 7b** | Abnahme- & Übergabeprotokoll | `docs/07_Rollout/Abnahmeprotokoll.pdf`<br>`docs/07_Rollout/Abnahmeprotokoll.docx` | Rechtskonformes Abnahmeprotokoll nach § 640 BGB |
| **Aufgabe 8a** | Lessons Learned & Reflexion | `docs/08_Projektabschluss/Lessons_Learned.pdf`<br>`docs/08_Projektabschluss/Lessons_Learned.docx` | Soll-Ist-Vergleich (Budget & Zeit eingehalten), Reflexion & Feedback |
| **Aufgabe 8b** | 10-Minuten-Abschlusspräsentation | `docs/08_Projektabschluss/Abschlusspraesentation.pptx`<br>`docs/08_Projektabschluss/Abschlusspraesentation.pdf` | 16 Folien, modernste Master-Folien mit vollen Notizen |
| **Aufgabe 8c** | Gesprächsleitfaden & Skript | `docs/08_Projektabschluss/Gespraechsleitfaden_Praesentation.pdf` | Wortlaut für alle 5 Sprecher in natürlicher Schülersprache |

---

## 🎤 5. Leitfaden für die 10-Minuten-Abschlusspräsentation

Die Präsentation liegt in zwei Formaten vor:  
📁 **`docs/08_Projektabschluss/Abschlusspraesentation.pptx`** (für PowerPoint)  
📄 **`docs/08_Projektabschluss/Abschlusspraesentation.pdf`** (direkt als PDF präsentierbar)  
📄 **Gedruckter Wortlaut-Leitfaden:** `docs/08_Projektabschluss/Gespraechsleitfaden_Praesentation.pdf`

> **Tipp:** In der PowerPoint-Datei hat **jede Folie ein vollständiges Notizfeld** mit dem exakten Sprechtext in natürlicher Schülersprache! Klickt in PowerPoint unten einfach auf *Notizen* oder nutzt die Referentenansicht (`Alt + F5`).

### Ablauf & Zeitplan (Exakt 10 Minuten)

| Sprecher | Folien | Thema | Geplante Zeit |
|---|---|---|---|
| **Jan Kluth** | **Folien 1 – 4** | **Einleitung & Team:** Begrüßung, Agenda, Projektauftrag VektorPlan GmbH, Teamvorstellung & Rollen | 0:00 – 2:00 Min |
| **Mathias Vonau** | **Folien 5 – 7** | **Planung & Technik:** Projektstrukturplan (30 WPs), Vorgangsliste & Netzplan (46 Tage), Lastenheft-Anforderungen | 2:00 – 4:00 Min |
| **Marian Bolecke** | **Folien 8 – 10** | **Beschaffung & Finanzen:** Hardware-Auswahl, Nutzwertanalysen (ThinkStation & Dell), Vorwärtskalkulation & Angebot (67.179 €) | 4:00 – 6:15 Min |
| **Siyar** | **Folien 11 – 13** | **Kundenberechnungen & Montage:** B.1 Speicherplatz (445 GiB) & B.2 Energiekosten (1.771 €/a), Rollout-Ablauf & ArbStättV-Checkliste | 6:15 – 8:00 Min |
| **Marco Schmidt** | **Folien 14 – 16** | **Qualität, Abschluss & Q&A:** § 377 HGB Mängelrüge, ElektroG-Entsorgung, Lessons Learned (Soll-Ist), Dank & Fragenrunde | 8:00 – 10:00 Min |

### 5 goldene Regeln für unseren Auftritt
1. **Nicht von der Folie ablesen:** Die Folien enthalten Schlagworte und KPIs für das Publikum – wir erzählen die Geschichte dazu frei.
2. **Klick-Übergaben laut ankündigen:** Wenn du fertig bist, übergib mit einem freundlichen Satz: *„Damit übergebe ich an unseren Technischen Planer Mathias...“*
3. **Blickkontakt halten:** Schaut abwechselnd den Lehrer und die Mitschüler an.
4. **Auf die Zeit achten:** 10 Minuten vergehen schnell. Wenn jemand etwas länger braucht, fasst der nächste sich etwas kürzer.
5. **Gemeinsam auftreten:** Bei Fragen am Ende darf jedes Teammitglied zu seinem Fachbereich antworten!

---

## 🎯 6. Prüfer-Spickzettel: Die 6 wichtigsten Lehrerfragen & Antworten

Falls der Lehrer oder Prüfungsausschuss tiefer bohrt, habt ihr mit diesen Antworten garantiert die volle Punktzahl:

### Frage 1: „Warum haben Sie bei der Speicherplatzberechnung durch 1024 geteilt und nicht durch 1000?“
> **Antwort:**  
> *„In der IT adressieren Betriebssysteme und Dateisysteme Speicher binär auf Basis von Zweierpotenzen (2^10 = 1024). Deshalb entspricht 1 GiB = 1024 MiB (IEC-Norm). Hätten wir dezimal mit 1000 gerechnet, hätten wir am Ende rund 24 GiB zu wenig physischen Speicherplatz eingeplant, was im Produktivbetrieb zu Engpässen geführt hätte. Zudem haben wir 25 % Puffer für temporäre CAD-Dateien und Spitzenlasten eingerechnet, womit wir exakt auf 445 GiB kommen.“*

### Frage 2: „Wie lange dauert das Projekt und woran erkennen Sie den kritischen Pfad?“
> **Antwort:**  
> *„Das Projekt dauert exakt 46 Arbeitstage. Im Netzplan nach DIN 69900 ist der kritische Pfad die Kette von Vorgängen, bei denen der Gesamtpuffer GP = 0 ist (frühester Anfangszeitpunkt = spätester Anfangszeitpunkt). Eine Verzögerung bei auch nur einem dieser Vorgänge – etwa der Hardware-Lieferung oder der Vorinstallation – verschiebt unmittelbar das gesamte Projektende.“*

### Frage 3: „Warum haben Sie für CAD die Lenovo ThinkStation P3 mit RTX 4000 Ada gewählt und keinen normalen i7-PC?“
> **Antwort:**  
> *„In unserer Nutzwertanalyse hat die ThinkStation P3 mit 8,70 Punkten gewonnen. Architektur- und BIM-Software wie Autodesk Revit oder AutoCAD nutzt hardwarebeschleunigtes 3D-Rendering. Die NVIDIA RTX 4000 Ada bietet 20 GB GDDR6-Grafikspeicher mit ECC-Fehlerkorrektur und zertifizierten ISV-Treibern. Ein Standard-Büro-PC mit integrierter Intel-Grafik würde bei großen CAD-Modellen sofort überhitzen oder abstürzen.“*

### Frage 4: „Was regelt der § 377 HGB und warum ist er für Ihr Systemhaus so wichtig?“
> **Antwort:**  
> *„§ 377 HGB regelt die kaufmännische Rügepflicht bei einem beiderseitigen Handelskauf. NextLevel IT Solutions ist verpflichtet, gelieferte Ware unverzüglich nach Erhalt auf offene Mängel zu prüfen und diese unverzüglich zu rügen. Versäumen wir diese Frist, gilt die Ware gemäß § 377 Abs. 2 HGB als genehmigt, und wir verlieren unsere gesetzlichen Gewährleistungsansprüche gegenüber dem Distributor – wir blieben also auf den Kosten für defekte Geräte sitzen.“*

### Frage 5: „Wie wird der alte Drucker datenschutz- und umweltgerecht entsorgt?“
> **Antwort:**  
> *„Nach dem Elektro- und Elektronikgerätegesetz (ElektroG, Kategorie 6) ist die Entsorgung über den normalen Restmüll streng verboten. Wir bauen vor der Entsorgung die interne Festplatte aus und überschreiben diese nach BSI-Standard dreifach oder übergeben sie zur mechanischen Schredderung nach DIN 66399, damit keine alten Kundenbaudaten rekonstruiert werden können. Tonerkassetten gehen getrennt ins Hersteller-Recycling, und das Restgerät geht an einen zertifizierten Erstbehandlungsbetrieb mit Entsorgungsnachweis.“*

### Frage 6: „Kauf oder Leasing: Was empfehlen Sie dem Kunden?“
> **Antwort:**  
> *„Beides hat Vorteile: Beim Direktkauf (CAPEX) geht das Eigentum sofort über und es fallen keine Zinskosten an, die Geräte werden über 3 Jahre nach AfA abgeschrieben. Für VektorPlan empfehlen wir jedoch IT-Leasing (OPEX), da die monatlichen Raten sofort als Betriebsausgaben steuerlich absetzbar sind, die Liquidität für das Kerngeschäft geschont wird und die Arbeitsplätze nach 3 Jahren unkompliziert gegen moderne Hardware getauscht werden können.“*

---

## 🏆 Viel Erfolg bei der Präsentation!
Das gesamte Projekt ist lückenlos dokumentiert, alle Berechnungen sind formeltechnisch geprüft und die Präsentation ist perfekt vorbereitet. Wir holen uns die 1! 🚀
