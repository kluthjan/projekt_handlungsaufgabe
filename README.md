# Projekt Handlungsaufgabe: Ausstattung Planungs- & Konstruktionsbüro

**Kunde:** VektorPlan GmbH (Architektur- und Ingenieurgesellschaft)  
**Auftragnehmer:** NextLevel IT Solutions GmbH  

---

## 👥 Projektteam & Rollenverteilung

| Name | Rolle | Zuständigkeit |
|---|---|---|
| **Jan Kluth** | **Projektleiter** | Gesamtkoordination, Projektorganisation (Aufgabe 1), Abschlusspräsentation (Aufgabe 8) |
| **Mathias Vonau** | Technischer Planer | Anforderungsanalyse & Lastenheft (Aufgabe 2), Rollout & Übergabe (Aufgabe 7) |
| **Marian Bolecke** | Beschaffung & Kalkulation | Marktrecherche & Nutzwertanalysen (Aufgabe 3), Angebotserstellung & Preiskalkulation (Aufgabe 4) |
| **Marco Schmidt** | Qualitätsmanagement | Wareneingangsprüfung & Mängelrüge (Aufgabe 5), Umwelt- & Datenschutzgerechte Entsorgung (Aufgabe 6) |
| **Siyar** | Berechnungen & Dokumentation | Spezifische Kundenberechnungen (Aufgabe B), Projektdokumentation & Qualitätssicherung |

---

## 🗂️ Übersicht der ausgearbeiteten Projektdateien

Alle Aufgaben wurden vollständig gelöst und als professionelle Word-, Excel- und PowerPoint-Dateien bereitgestellt:

```
projekt_handlungsaufgabe/
├── docs/
│   ├── Berechnungen/
│   │   └── Kundenberechnungen.xlsx               # Speicherplatzbedarf (445 GiB) & Energiekosten (1.771,26 €/a)
│   ├── 01_Projektorganisation/
│   │   ├── Vorgangsliste.xlsx                    # 14 Vorgänge nach Wasserfallmodell inkl. Abhängigkeiten & Dauern
│   │   ├── Netzplan.xlsx                         # DIN 69900 Netzplan (reinzellige Excel-Tabelle, B&W + roter kritischer Pfad)
│   │   ├── Netzplan.md                           # Dokumentierter Netzplan mit Knotenzeiten & Formeln
│   │   ├── Projektstrukturplan.xlsx              # DIN 69901 PSP (reinzellige Excel-Tabelle, 5 Säulen, 30 Arbeitspakete)
│   │   ├── Projektstrukturplan.md                # Dokumentierter PSP mit Gliederung & WBS
│   │   ├── Gantt_Diagramm.xlsx                   # Visueller Termin- und Ablaufplan (48 Tage)
│   │   └── Risikoanalyse.xlsx                    # 7 Risiken inkl. Matrix & Ampel-Bewertung
│   ├── 02_Anforderungsanalyse/
│   │   └── Lastenheft.docx                       # Detaillierte Spezifikationen (12 Standard-PCs, 4 CAD, 32 Monitore, MFP, Software)
│   ├── 03_Marktrecherche/
│   │   ├── Produktrecherche.xlsx                 # Reale Marktprodukte mit Preisen (Dell, Lenovo, HP, EIZO etc.)
│   │   ├── Nutzwertanalyse_Workstations.xlsx     # Gewichtete Entscheidungsmatrix (Sieger: Lenovo ThinkStation P3 mit 8,70)
│   │   └── Nutzwertanalyse_Monitore.xlsx         # Gewichtete Entscheidungsmatrix (Sieger: Dell UltraSharp U2724D mit 9,10)
│   ├── 04_Angebot/
│   │   ├── Angebot_VektorPlan.docx               # Formgerechtes kaufmännisches Angebot (DIN 5008)
│   │   ├── Vorwaertskalkulation.xlsx             # Vollständige Vorwärtskalkulation (LEP bis LVP inkl. Handlungskosten & Skonto)
│   │   └── Infoblatt_Leasing_vs_Kauf.docx        # Kunden-Informationsblatt (CAPEX vs. OPEX, Liquidität, Steuern)
│   ├── 05_Wareneingang/
│   │   ├── Wareneingangspruefung.docx            # Leitfaden nach § 377 HGB (offene vs. verdeckte Mängel)
│   │   └── Maengelruege.docx                     # Kaufmännische Mängelrüge an Distributor mit Fristsetzung
│   ├── 06_Entsorgung/
│   │   └── Entsorgungskonzept.docx               # Fachgerechte Entsorgung nach ElektroG, WEEE, Toner- & BSI-Datenlöschung
│   ├── 07_Rollout/
│   │   ├── Checkliste_Inbetriebnahme.docx        # Checkliste vor Ort (Ergonomie ArbStättV, Verkabelung, Funktionstests)
│   │   └── Abnahmeprotokoll.docx                 # Rechtskonformes Abnahme- und Übergabeprotokoll mit Mängelliste
│   └── 08_Projektabschluss/
│       ├── Lessons_Learned.docx                  # Soll-Ist-Vergleich, Selbstreflexion & Handlungsempfehlungen
│       ├── Abschlusspraesentation.pptx           # 16-Folien Abschlusspräsentation mit vollständigen Team-Sprechernotizen
│       ├── Gespraechsleitfaden_Praesentation.pdf # Vollständiger Wortlaut-Leitfaden aufgeteilt auf alle 5 Teammitglieder
│       ├── Projekterklaerung_und_Wissensleitfaden.pdf # Fachwissen, methodische Erklärungen & Vorbereitung für Prüferfragen
│       └── Projektstatus_und_Naechste_Schritte.pdf # Statusübersicht, Rollenmatrix & Checkliste zur Bestnote 1
└── README.md
```

---

## 📊 Kern-Ergebnisse der Kundenberechnungen (Aufgabe B)

1. **Speicherplatzbedarf Fileserver (Quartal / 65 Arbeitstage):**
   - $16 \text{ AP} \times 350\text{ MiB} \times 65\text{ Tage} = 364.000\text{ MiB} \approx 355,47\text{ GiB}$
   - Netto gerundet: **356 GiB**
   - Inkl. 25% Sicherheits- und Pufferzuschlag: **445 GiB**

2. **Jährliche Energiekosten (220 Arbeitstage à 8,5 h, 0,32 €/kWh):**
   - $12 \times 140\text{ W} + 4 \times 320\text{ W} = 2.960\text{ W} = 2,96\text{ kW}$
   - Jährlicher Energieverbrauch: $2,96\text{ kW} \times 220 \times 8,5\text{ h} = 5.535,2\text{ kWh}$
   - Stromkosten: **1.771,26 € pro Jahr**
