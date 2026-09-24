# UXD_BFI Lernbegleiter – Referenz (Anhang) · Version 1.0 · Stand 21.08.2026

Alles hier steht auch im Folienskript; bei Widerspruch gilt das Skript. Diese Datei ist der Stoffstand für den Übungspartner.

## Themenliste des Semesters (mit Lernzielen)

W1 Der Mismatch (LZ 8, 2) · W2 Werkzeuge, nicht Mitleid – Screenreader-Grundkurs, Simulations-Falle (LZ 2) · W3 Ein Gesetz ohne Behörde – BFSG, BITV, EN 301 549, Objektwahl (LZ 1) · W4 Was die KI über Normen weiß – WCAG von innen, Verifikationshandwerk (LZ 1, 4; streichbar) · W5 Was die Maschine findet – Messlogiken, Werkzeugkunde, Dreiklang-Matrix (LZ 4, 3) · W6 Das Tribunal – Fehlalarm/blinder Fleck/echter Treffer, vier Beweisarten (LZ 4, 2) · W7 Methode statt Bauchgefühl – WCAG-EM 2.0, Stichprobe, Kursrubrik (LZ 3, 6) · W8 Prüf-Sprint = Meilenstein 2 (LZ 3, 2, 5) · W9 Die Rangfolge hat einen Preis – drei Achsen, Preis-Satz (LZ 5) · W10 Die Eine-Million-Dollar-Frage – Overlays, KI-Remediation (LZ 4, 8, 6; streichbar) · W11 Konform, aber unbenutzbar – Zweck-Test, Beteiligung, Pflicht-Limitation (LZ 8, 5, 7) · W12 Wer prüft die Prüfer? – Peer-Review, Generalprobe (LZ 6, 7, 4) · W13 und W14 Referate mit Verteidigung (zwei Termine). Geplant sind 14 Wochen; fällt eine Woche aus, entfällt W10 als Präsenztermin, bei zwei Wochen auch W4 (Stoff im Skript). Sind W4 und W10 schon gelaufen, wandert der Stoff des ausgefallenen Termins ins Skript; die beiden Referatstermine bleiben.

## Die acht Lernziele (Kurzform)

LZ 1 Rechtsrahmen auf den Fall anwenden und begründen · LZ 2 Anwendung mit Tastatur, Screenreader, Vergrößerung selbst bedienen und Barrieren protokollieren · LZ 3 systematisch, arbeitsteilig, unter Zeitvorgabe prüfen und belegbar dokumentieren · LZ 4 Befunde automatisierter und KI-gestützter Prüfung beurteilen (Fehlalarm / blinder Fleck / echter Treffer) · LZ 5 Barrieren priorisieren mit benanntem Kriterium und Preis, umsetzbare Vorschläge · LZ 6 fremde Gutachten beurteilen (auch KI-erzeugte) · LZ 7 als Team ein Gutachten erstellen, KI-Nutzung deklarieren, Ergebnisse verteidigen · LZ 8 Normkonformität von tatsächlicher Benutzbarkeit unterscheiden.

## Normstände (mit Datum, Stand 21.08.2026)

- **BFSG:** in Kraft seit 28.06.2025 (Wirtschaft). Kleinstunternehmen-Ausnahme (unter 10 Beschäftigte UND max. 2 Mio. €) nur für Dienstleistungen. Websites/Onlineshops: keine Übergangsfrist. Marktüberwachung: MLBF (Magdeburg, errichtet 26.09.2025).
- **BITV 2.0:** Fassung 2019, öffentliche Stellen des Bundes; verweist dynamisch auf die im EU-Amtsblatt harmonisierte Norm.
- **EN 301 549:** rechtswirksam V3.2.1 (03/2021, bettet WCAG 2.1 ein). Final Draft V4.1.0 (06/2026, verweist auf WCAG 2.2) ist NICHT im Amtsblatt zitiert und damit nicht geltender Maßstab.
- **WCAG 2.2:** W3C Recommendation seit 05.10.2023 (revidierte Fassung 12.12.2024); neun neue Kriterien, 4.1.1 Parsing gestrichen. **WCAG 3.0:** Working Draft (03.03.2026), überwiegend „exploratory", auf Jahre nicht rechtsrelevant.
- **USA:** ADA Title-II-Webregel (WCAG 2.1 AA) – Fristen im April 2026 verschoben (große Träger 26.04.2027).

## Definitionen in der Modulfassung

**Mismatch:** Behinderung entsteht im Zusammentreffen von Person und Gestaltung, nicht in der Person (Holmes 2018); permanent / temporär / situativ. **Accessibility Tree:** die vom Browser aus dem Code abgeleitete Struktur, die assistive Technologien lesen; jedes Bedienelement braucht Name, Rolle, Wert. **Dreiklang:** Fehlalarm (gemeldet, kein Problem) · blinder Fleck (Problem, nicht gemeldet) · echter Treffer. **Vier Beweisarten:** Screenreader-Gegenprobe, DOM-Blick, Normtext, Nutzungskontext; jede übernommene Werkzeug-Meldung trägt einen Beweisvermerk. **Dreiklang-Matrix:** Hand-only / Werkzeug-only / beide. **Drei Prioritäts-Achsen:** Schwere, Betroffenheit, Behebungsaufwand; Nicht-Achsen: Häufigkeit, Technik-Fleiß. **Preis-Satz:** „Platz n bedeutet: X wartet – das trifft Y." **Zweck-Test:** Trägt der Alt-Text (o. Ä.) die Nutzerentscheidung an dieser Stelle – nicht nur die Beschreibung? **Pflicht-Limitation:** „geprüft ohne Beteiligung betroffener Nutzerinnen und Nutzer" steht in jedem Gutachten dieses Kurses.

## Schlüsselzahlen (immer mit Setting zitieren)

Deque 2021: 57,38 % der Barrieren nach Fehlervolumen automatisiert findbar · GDS 2017: bestes kostenloses Tool 41 % der Barrierearten, 29 % fand kein Tool · DWP-Faustregel: „around 40 % of known issues" · arXiv 05/2026: LLM-Erkennung F1 ≈ 0,65, Präzision ≈ 0,5 (Hälfte Fehlalarme im Studien-Setting) · LLM-Remediation: unter 26 % vollständig gelöst, ~30 % unbeabsichtigte Strukturänderungen · WebAIM Million 2026: 95,9 % der Startseiten mit Fehlern, 56,1 Fehler/Seite, ARIA-Paradox (mit ARIA 59,1 Fehler, ohne 42) · FTC gegen accessiBe: 1 Mio. US-$ (Order 01/2025, final 04/2025) · WebAIM Screen Reader Survey #10 (2024): JAWS 40,5 %, NVDA 37,7 %; 91,3 % mobil.

## Prüfungsform

LN – Referat: semesterbegleitendes Team-Gutachten einer realen Anwendung (Meilensteine W5, W8, W11), 20 Min Präsentation plus 10 Min Verteidigung in W13 oder W14. Nachfragen kommen aus dem im Semester gewachsenen Fragenpool; mindestens eine Frage je Team geht an eine benannte Einzelperson entlang der Rollendeklaration. Zwei-Spalten-Regel: LZ 1–7 sind prüfungsrelevant; LZ 8 wird betrieben, aber nicht eigens geprüft.
