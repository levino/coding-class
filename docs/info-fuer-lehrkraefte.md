---
sidebar_position: 4
---

# Informationen für Lehrkräfte und Pädagogen

Diese Seite richtet sich an Lehrkräfte, Pädagogen und andere Bildungseinrichtungen, die einen ähnlichen Programmierkurs für Kinder aufsetzen möchten.

## Konzept und Philosophie

### Programmieren, nicht Informatik

**Wichtige Unterscheidung:** Dies ist ein **Programmierkurs**, kein Informatik-Kurs.

**Was wir NICHT machen:**
- Höhere Informatik-Konzepte
- Komplexe Algorithmen (Sortieralgorithmen, Pledge-Algorithmus für Labyrinth-Navigation, etc.)
- Theoretische Computergrundlagen
- Akademische Abstraktion

**Was wir MACHEN:**
- Kinder lernen die **verschiedenen Ebenen der Programmierung**:
  1. **Versionskontrolle** (Git) - Wie verwalte ich meinen Code?
  2. **Markup-Sprachen/Programmiersprachen** (Typst, Markdown, React) - Wie schreibe ich Code?
  3. **Resultierendes Ergebnis** (PDF-Dokument, Webseite) - Was entsteht aus meinem Code?

### Das Problem typischer Programmierkurse

Viele Kinder-Programmierkurse leiden unter einem fundamentalen Problem: **zu hohe Abstraktionsebene**.

**Typisches Szenario:**
- Kinder programmieren in einer speziellen Umgebung (z.B. Scratch auf Schulcomputern)
- Die Ergebnisse existieren nur in dieser geschlossenen Welt
- Kinder können ihre Arbeit NICHT teilen mit:
  - Oma und Opa
  - Freunden auf dem Pausenhof
  - Tante und Onkel
  - Zu Hause auf anderen Geräten

**Das Resultat:**
- Geringe gefühlte Wirksamkeit
- "Was ich mache, ist nicht wirklich real"
- Mangelnde Motivation
- Keine Verbindung zur echten Welt

### Unsere Lösung: Gefühlte Wirksamkeit durch echte Ergebnisse

**Der Schlüssel:** Kinder erstellen Dinge, die **in der echten Welt existieren** und die sie **teilen können**.

**Was normalerweise als "Beiwerk" gilt, ist für uns ESSENTIELL:**

1. **Kompilieren** - Code wird zu einem echten Ergebnis (PDF, Webseite)
2. **Hosting** - Die Webseite ist im Internet verfügbar
3. **Domains** - Eine richtige Adresse (z.B. `max-projekt.de`)
4. **Continuous Deployment** - Änderungen gehen automatisch live
5. **Apps** - Etwas, das man auf dem Handy öffnen kann
6. **Authentifizierung** - "Meine" Inhalte vs. andere Nutzer

**Warum das essentiell ist:**

Diese technischen Details ermöglichen es Kindern:
- Ihre Großeltern die selbst erstellte Webseite zu zeigen
- Freunden den Link zu schicken: "Schau mal, was ich gemacht habe!"
- Zu Hause am Tablet das Ergebnis zu sehen
- Stolz zu sein auf etwas **Echtes**

**Beispiel-Szenario:**

❌ **Typischer Kurs:**
> "Ich habe heute in Scratch ein Spiel programmiert!"
> "Cool, kann ich es sehen?"
> "Nee, geht nur auf dem Computer in der Schule..."

✅ **Unser Kurs:**
> "Ich habe heute eine Webseite über mein Hobby gemacht!"
> "Cool, kann ich es sehen?"
> "Klar! Hier, öffne mal: www.max-fussball.de"

**Der Unterschied:** Im zweiten Fall fühlt das Kind echte Wirksamkeit. Es hat etwas geschaffen, das **real ist**, das **andere sehen können**, das **in der Welt existiert**.

### Direkt zu echten Tools

Dieser Kurs verfolgt einen **radikal anderen Ansatz** als die meisten Kinder-Programmierkurse:

**Statt:**
- Scratch, Blockly und andere visuelle Programmierumgebungen
- Vereinfachte "Kinder-Tools"
- Schrittweise Einführung über Jahre hinweg

**Nutzen wir:**
- Git & GitHub - echte Versionskontrolle
- VS Code - professionelle IDE
- Typst - moderne Markup-Sprache
- Später: React, Astro - moderne Web-Technologien

### Warum dieser Ansatz?

**Das Problem der "Scratch-Falle":**
- Kinder verbringen Jahre mit visuellen Block-Systemen
- Der Sprung zu echtem Code ist riesig und frustrierend
- Viele geben auf, weil sie "wieder von vorne anfangen" müssen
- Verschwendete Zeit - nichts davon ist auf echte Entwicklung übertragbar

**Unser Ansatz:**
- Kinder lernen von Anfang an die richtigen Tools
- Die Lernkurve ist anfangs steiler, aber **alles Gelernte ist sofort wertvoll**
- Kinder entwickeln echte, übertragbare Fähigkeiten
- Nach 6-12 Monaten können sie bereits mit professionellen Tools arbeiten

## Warum Git?

Git ist das wichtigste Tool in der modernen Softwareentwicklung. Hier sind die Gründe, warum wir es **von Anfang an** einsetzen:

### 1. Versionskontrolle verstehen

Kinder lernen früh:
- Wie man Änderungen verfolgt
- Wie man zu früheren Versionen zurückkehrt
- Wie man mit anderen zusammenarbeitet
- Wie man Konflikte löst

**Pädagogischer Wert:**
- Fehler sind nicht schlimm - man kann immer zurück
- Experimentieren wird gefördert
- Verantwortung für eigene Änderungen

### 2. Asynchrone Kommunikation

Über GitHub Issues und Discussions lernen Kinder:
- Probleme klar zu beschreiben
- Screenshots und Beispiele bereitzustellen
- Feedback konstruktiv zu geben und anzunehmen
- Schriftliche Kommunikation in technischen Kontexten

### 3. Portfolio aufbauen

Ab dem ersten Tag erstellen Kinder ein **nachweisbares Portfolio**:
- Alle Projekte sind auf GitHub sichtbar
- Commit-Historie zeigt kontinuierliches Lernen
- Später für Bewerbungen wertvoll

### 4. Professionelle Arbeitsweise

Kinder lernen den **echten Workflow** von Entwicklern:
```bash
git add .
git commit -m "Add feature X"
git push
```

Dies sind die gleichen Befehle, die sie später als professionelle Entwickler verwenden werden.

## Warum Typst?

Typst ist mehr als nur ein "Word-Ersatz" - es ist ein pädagogisches Werkzeug mit vielen Vorteilen.

### 1. Markup-Sprachen verstehen

Kinder lernen das fundamentale Konzept von **Markup-Sprachen**:
- Inhalt und Darstellung trennen
- Code schreiben, um Output zu generieren
- Deklarative Programmierung

**Übertragbar auf:**
- HTML/CSS (Web-Entwicklung)
- Markdown (überall verwendet)
- LaTeX (Wissenschaft)
- XML/JSON (Datenformate)

### 2. Versionskontrolle für Dokumente

Anders als Word-Dateien:
- Typst-Dateien sind **reiner Text**
- Perfekt für Git geeignet
- Änderungen sind nachvollziehbar
- Kollaboration ohne Versionschaos

### 3. Programmierbare Dokumente

Kinder entdecken, dass man Dokumente **programmieren** kann:
```typst
#let title = "Mein Projekt"
#let author = "Max Mustermann"

#align(center)[
  #text(24pt)[*#title*]
  #v(1em)
  von #author
]
```

Dies öffnet die Tür zu:
- Variablen und Funktionen
- Loops und Conditionals
- Automatisierung

### 4. Ästhetik und Professionalität

Typst generiert **schöne PDFs**:
- Professionelles Layout
- Mathematische Formeln
- Diagramme und Grafiken
- Kinder sind stolz auf ihre Ergebnisse

## Warum KEINE Microsoft Office Produkte?

Diese Empfehlung mag kontrovers erscheinen, aber sie ist gut begründet:

### 1. Proprietäre Software

Microsoft Office ist:
- Kostenpflichtig (in der Vollversion)
- Nicht frei verfügbar
- An ein Unternehmen gebunden
- Nicht transparent (Closed Source)

**Alternative Philosophie:**
- Open Source bevorzugen
- Plattformunabhängige Lösungen
- Transparenz und Kontrolle
- Community-getrieben

### 2. Veraltetes Paradigma

Word, Excel, PowerPoint basieren auf einem **veralteten Arbeitsmodell**:
- WYSIWYG (What You See Is What You Get)
- Manuelle Formatierung
- Binäre Dateiformate
- Keine Versionskontrolle

**Moderne Arbeitsweise:**
- Inhalt und Darstellung trennen
- Automatisierung
- Textbasierte Formate
- Git-Integration

### 3. Vendor Lock-in vermeiden

Kinder an Microsoft zu gewöhnen bedeutet:
- Abhängigkeit von einem Anbieter
- Kostenpflichtige Software wird "normal"
- Schwieriger Wechsel zu Alternativen später
- Eingeschränkte Kreativität

### 4. Zukunftsorientierung

Die Arbeitswelt bewegt sich weg von Office:
- Entwickler nutzen Markdown, nicht Word
- Daten werden in JSON/YAML gespeichert, nicht Excel
- Präsentationen werden mit Code erstellt (reveal.js, etc.)
- Kollaboration passiert über Git, nicht per Email mit Anhängen

## Alternativen zu Microsoft Office im Kurs

### Statt Word → Typst / Markdown

**Typst:**
- Schöne Dokumente mit Code
- PDF-Export
- Versionskontrollierbar
- Programmierbar

**Markdown:**
- Einfach zu lernen
- Überall verwendet (GitHub, Blogs, Dokumentation)
- Leichtgewichtig
- Fokus auf Inhalt

### Statt Excel → CSV / JSON / YAML

**CSV:**
- Textbasiert
- In jedem Tool öffenbar
- Mit Git versionierbar
- Programmatisch verarbeitbar

**JSON/YAML:**
- Strukturierte Daten
- Maschinenlesbar
- In jeder Programmiersprache nutzbar
- APIs verwenden JSON

### Statt PowerPoint → reveal.js / Markdown

**reveal.js:**
- Präsentationen mit HTML/JavaScript
- Versionskontrollierbar
- Schöne Animationen
- Code-Beispiele direkt einbettbar

**Markdown-basierte Lösungen:**
- Marp
- Slidev
- Pitch

## Praktische Umsetzung

### Kursstruktur

**Phase 1: Grundlagen (2-3 Monate)**
1. Git & GitHub Setup
2. VS Code kennenlernen
3. Typst-Projekte erstellen
4. Issues und Discussions nutzen

**Phase 2: Web-Entwicklung (variabel)**
1. Markdown
2. JSON/YAML
3. React
4. Astro

### Die Ebenen der Programmierung im Kurs

Ein zentrales Konzept dieses Kurses ist, dass Kinder die **verschiedenen Ebenen** verstehen lernen, die zusammenwirken:

**Ebene 1: Versionskontrolle (Git)**
- Wo speichere ich meinen Code?
- Wie verfolge ich Änderungen?
- Wie teile ich mit anderen?

**Ebene 2: Code schreiben (Typst, Markdown, React)**
- Wie drücke ich aus, was ich möchte?
- Welche Syntax verwende ich?
- Wie strukturiere ich meinen Code?

**Ebene 3: Kompilierung/Build**
- Wie wird aus meinem Code ein Ergebnis?
- Was passiert im Hintergrund?
- Warum sieht das Ergebnis so aus?

**Ebene 4: Deployment/Hosting**
- Wie kommt mein Ergebnis ins Internet?
- Wo "lebt" meine Webseite?
- Wie können andere darauf zugreifen?

**Ebene 5: Teilen und Nutzen**
- Wie können andere meine Arbeit sehen?
- Wie funktioniert eine Domain?
- Wie kann ich Zugriff kontrollieren?

**Wichtig:** Diese technischen Details sind KEINE "nice-to-have" Extras, sondern **essentielle Grundlagen** für:
- Gefühlte Wirksamkeit
- Motivation
- Verständnis der echten Welt
- Praktische Anwendbarkeit

### Asynchrones Lernen

Der Kurs ist bewusst **asynchron** aufgebaut:
- Kinder arbeiten in ihrem eigenen Tempo
- Keine festen Deadlines
- Individuelle Unterstützung über GitHub
- Optional: Gruppen-Sessions zum Austausch

**Vorteile:**
- Kein Leistungsdruck
- Jedes Kind kann sein Tempo finden
- Weniger Frustration
- Besseres Verständnis

### Technische Infrastruktur

**Empfohlenes Setup:**
- **Raspberry Pi 500** (~150-200 EUR pro Kind)
  - Komplett-System mit Monitor
  - Linux vorinstalliert
  - Ausreichend für alle Kursinhalte
  - Pädagogisch wertvoll (eigener Computer!)

**Software (alles kostenlos):**
- Linux (Ubuntu, Raspberry Pi OS, etc.)
- VS Code
- Git
- Typst
- Node.js (später)

### Fernbetreuung

**Technischer Support:**
- Fernzugriff auf Schüler-Computer
- Schnelle Problemlösung
- Video-Calls bei Bedarf

**Kommunikation:**
- GitHub Issues für technische Probleme
- GitHub Discussions für allgemeine Fragen
- Asynchrone Kommunikation bevorzugt

## Hilfreiches Material

### Ressourcen für den Kursaufbau

**Git:**
- [Pro Git Book](https://git-scm.com/book/de/v2) - Kostenlos, umfassend
- [GitHub Guides](https://guides.github.com/) - Kurze, praktische Anleitungen
- [Learn Git Branching](https://learngitbranching.js.org/?locale=de_DE) - Interaktives Tutorial

**Typst:**
- [Typst Documentation](https://typst.app/docs) - Offizielle Dokumentation
- [Typst Examples](https://typst.app/docs/tutorial) - Tutorial mit Beispielen
- [Typst Universe](https://typst.app/universe) - Templates und Packages

**VS Code:**
- [VS Code Docs](https://code.visualstudio.com/docs) - Offizielle Dokumentation
- [VS Code for Education](https://code.visualstudio.com/learn) - Lern-Ressourcen

### Kursbeispiele und Templates

**Starter-Projekte:**
- Einfaches Typst-Dokument als erste Übung
- Git-Repository-Template für neue Schüler
- Onboarding-Checkliste

**Projekt-Ideen:**
- Persönliche Vorstellung (Typst)
- Dokumentation eines Hobbys
- Kleine Geschichte oder Comic
- Technische Anleitung
- Rezeptsammlung

### Community und Support

**Open Source Philosophie:**
- Alle Kursmaterialien können frei verwendet werden
- Ermutige Schüler, zu Open Source beizutragen
- Zeige, wie echte Entwickler zusammenarbeiten

**Austausch mit anderen Lehrkräften:**
- GitHub Discussions in diesem Repository
- Fragen und Erfahrungen teilen
- Von anderen lernen

## Pädagogische Prinzipien

### 1. Gefühlte Wirksamkeit an erster Stelle

**Das wichtigste Prinzip:** Kinder müssen **fühlen**, dass ihre Arbeit etwas bewirkt.

**Warum das entscheidend ist:**
- Motivation entsteht durch echte Ergebnisse
- "Ich habe etwas erschaffen, das existiert"
- Andere Menschen können meine Arbeit sehen und nutzen
- Stolz und Selbstbewusstsein durch echte Leistung

**Wie wir das umsetzen:**
- Jedes Projekt hat ein **teilbares Ergebnis** (PDF, Webseite, Link)
- Kinder können ihre Arbeit Freunden und Familie zeigen
- Ergebnisse sind auf verschiedenen Geräten zugänglich
- Keine "geschlossene Schulwelt", sondern echte Online-Präsenz

**Konkrete Beispiele:**
- Ein Typst-PDF kann per Email an Oma geschickt werden
- Eine Webseite hat eine echte URL, die auf dem Pausenhof geteilt werden kann
- Ein React-Projekt kann auf dem Handy der Eltern geöffnet werden
- GitHub-Profil zeigt echte Arbeit (wie ein Portfolio)

### 2. Hands-On Learning

Kinder lernen durch **praktisches Tun**:
- Sofort echte Projekte erstellen
- Nicht nur Theorie
- Experimentieren ist erwünscht

### 3. Fehlerkultur

Fehler sind **Teil des Lernprozesses**:
- Git ermöglicht risikofreies Experimentieren
- Fehler können rückgängig gemacht werden
- Fehler sind Lernchancen, keine Misserfolge

### 4. Selbstständigkeit

Kinder lernen, **sich selbst zu helfen**:
- Dokumentation lesen
- Probleme googeln
- Fragen strukturiert stellen
- Issues erstellen

### 5. Echte Tools = Echtes Lernen

Keine "Spielzeug-Tools":
- Gleiche Werkzeuge wie professionelle Entwickler
- Übertragbare Fähigkeiten
- Vorbereitung auf echte Entwicklung

### 6. Individuelles Tempo

Jedes Kind ist anders:
- Keine festen Zeitpläne
- Kein Vergleich mit anderen
- Eigene Projekte und Interessen

## Häufige Bedenken

### "Ist Git nicht zu kompliziert für Kinder?"

**Antwort:** Nein, wenn man es richtig einführt.

Kinder lernen am Anfang nur:
```bash
git add .
git commit -m "Nachricht"
git push
```

Das ist nicht komplizierter als andere Tools. Wichtig:
- Langsam einführen
- Praktisch zeigen, nicht theoretisch erklären
- Fehler sind okay

### "Warum nicht erst Scratch, dann echter Code?"

**Antwort:** Weil das doppelte Arbeit ist.

Die "Scratch-Falle":
- Jahre mit visuellen Tools
- Dann frustrierender Neustart mit echtem Code
- Viele geben auf

Unser Ansatz:
- Einmal richtig lernen
- Alles ist übertragbar
- Kontinuierlicher Fortschritt

### "Ist das nicht zu schwer für Kinder?"

**Antwort:** Nein, aber es erfordert Geduld.

Die Lernkurve ist anfangs steiler, aber:
- Kinder sind erstaunlich lernfähig
- Mit der richtigen Unterstützung schaffen sie es
- Der langfristige Nutzen ist viel größer

### "Was ist mit Kindern, die langsam lernen?"

**Antwort:** Der Kurs passt sich an.

- Kein Zeitdruck
- Kein Leistungsvergleich
- Individuelles Tempo
- Auch langsame Lerner profitieren

## Kontakt und Austausch

Möchtest du einen ähnlichen Kurs aufsetzen? Hast du Fragen oder Anregungen?

**GitHub Discussions:**
- [Diskussionen starten](https://github.com/levino/coding-class/discussions)
- Fragen stellen
- Erfahrungen teilen

**Dieses Repository nutzen:**
- Alle Materialien sind frei verfügbar
- Fork das Repository
- Pass es an deine Bedürfnisse an
- Trage Verbesserungen bei (Pull Requests willkommen!)

---

**Viel Erfolg beim Aufsetzen deines eigenen Kurses! Gemeinsam machen wir Programmieren für Kinder zugänglich. 🚀**
