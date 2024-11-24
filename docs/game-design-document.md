# Game Design Document
## Die Asche von Valdorin

**Version:** 1.0
**Stand:** Dezember 2024

---

## 1. Übersicht

| Attribut | Wert |
|----------|------|
| **Genre** | Narratives Action-RPG |
| **Perspektive** | Third-Person |
| **Plattformen** | PC, PS5, Xbox Series X |
| **Spielzeit** | 40-60 Stunden (Hauptstory + Sidequests) |
| **Zielgruppe** | 18+ (Mature Themes) |

### Elevator Pitch

*Du bist das Kind eines Gottes, der sich selbst zum Gefängnis machte. Jetzt bröckeln die Ketten. Finde deinen Vater. Entscheide, was mit der Dunkelheit geschieht. Und lebe mit den Konsequenzen.*

---

## 2. Core Pillars

### 2.1 Konsequenzen, nicht Karma

- Keine "guten" oder "bösen" Punkte
- Entscheidungen haben narrative Konsequenzen, keine Spielmechanik-Strafen
- NPCs erinnern sich – und reagieren
- Auch "falsche" Entscheidungen können zu interessanten Ergebnissen führen

### 2.2 Companions als Menschen

- Jeder Begleiter hat eigene Ziele, die mit deinen kollidieren können
- Vertrauen muss verdient werden – und kann verloren gehen
- Keine Geschenk-Mechanik – Beziehungen wachsen durch Taten und Gespräche
- Companions können sterben, verraten, oder sich für dich opfern

### 2.3 Macht hat einen Preis

- Das Magiesystem ist narrativ verankert
- Übernutzung führt zu physischen/psychischen Veränderungen
- Der Spieler formt seinen Charakter – buchstäblich

---

## 3. Gameplay-Systeme

### 3.1 Kampfsystem

**Inspiration:** Souls-lite trifft The Witcher

| Element | Beschreibung |
|---------|--------------|
| **Grundmechanik** | Stamina-basiert, präzises Timing |
| **Schwierigkeit** | Fordernd, aber fair. Kein "Git Gud"-Gatekeeping. |
| **Magie** | Drei aktive Mächte, dynamisch einsetzbar |
| **Companions** | KI-gesteuert mit taktischen Befehlen |

### 3.2 Das Macht-System

Der Spieler kann maximal **drei Mächte** gleichzeitig tragen.

**Entwicklung durch Anwendung:**
- Keine Skillpunkte
- Mächte entwickeln sich basierend auf Nutzungsart
- Jede Macht hat drei Entwicklungspfade

**Beispiel: Wille**

```
              HERRSCHAFT
             /
WILLE ----  BOLLWERK
             \
              EINSICHT
```

| Nutzungsart | Entwicklung |
|-------------|-------------|
| Feinde dominieren | Herrschaft – Mächtig, aber gefürchtet |
| Verbündete schützen | Bollwerk – Defensiv, vertrauenswürdig |
| Gedanken lesen | Einsicht – Subtil, allwissend |

**Konsequenzen:**

| Macht | Übernutzung führt zu... |
|-------|------------------------|
| Schatten | Farbsehen verschwindet, Tageslicht schmerzt |
| Feuer | Berührung wird heiß, Umarmungen unmöglich |
| Wille | Gedanken anderer werden hörbar (ungewollt) |
| Leben | Körper altert/verjüngt sich unvorhersehbar |

### 3.3 Vertrauens-System

Jeder Companion hat einen Vertrauens-Wert:

```
MISSTRAUEN → WACHSAM → NEUTRAL → VERBUNDEN → UNERSCHÜTTERLICH
```

**Beeinflusst durch:**
- Story-Entscheidungen
- Dialoge
- Wie der Spieler andere Companions behandelt
- Ob der Spieler Versprechen hält

**Auswirkungen:**
- Neue Dialog-Optionen
- Persönliche Quests werden freigeschaltet
- Romanzen werden möglich
- Einfluss auf Akt 3/4-Ereignisse

---

## 4. Narrative Struktur

### 4.1 Akt-Struktur

```
PROLOG
  │
  ▼
AKT 1 ─────┬───────┬───────┐
           │       │       │
         Pfad A  Pfad B  Pfad C
           │       │       │
           └───────┴───────┘
                   │
                   ▼
               AKT 2
                   │
                   ▼
               AKT 3
                   │
                   ▼
               AKT 4
                   │
        ┌────┬────┼────┬────┐
        ▼    ▼    ▼    ▼    ▼
       [A]  [B]  [C]  [D]  [E]

       5 verschiedene Enden
```

### 4.2 Branching

- **Akt 1:** Drei komplett unterschiedliche Pfade (6-8h Spielzeit)
- **Akt 2:** Pfade konvergieren, aber mit unterschiedlichen Voraussetzungen
- **Akt 3:** Companion-Schicksale werden entschieden
- **Akt 4:** Finale Entscheidungen, 5 mögliche Enden

### 4.3 Die Enden

| Ende | Voraussetzung | Ton |
|------|---------------|-----|
| **Das Opfer** | Standard | Tragisch, aber würdevoll |
| **Der dunkle Aufstieg** | Viele dunkle Entscheidungen | Düster |
| **Pyrrhus** | Zwergenwaffe finden | Bittersüß |
| **Die Erlösung** | Alle Erhabenen retten | Hoffnungsvoll |
| **Der Fall** | Alle Companions verloren | Katastrophal |

---

## 5. Welt-Design

### 5.1 Regionen

| Region | Volk | Atmosphäre |
|--------|------|------------|
| **Valdorin (Kaiserreich)** | Menschen | Gotisch, prunkvoll, korrupt |
| **Aelindor (Elfenwald)** | Elfen | Melancholisch, verblassende Schönheit |
| **Karak Dum** | Zwerge | Industriell, tiefe Dunkelheit |
| **Die Steppen** | Orks | Weite, Freiheit, Vergänglichkeit |
| **Die Leere** | — | Surreal, bedrohlich, endlos |

### 5.2 Level-Design-Philosophie

- Keine offene Welt um der offenen Welt willen
- Hub-basiert mit dichten, detaillierten Gebieten
- Jeder Ort erzählt eine Geschichte – auch ohne NPCs
- Shortcuts und Geheimnisse belohnen Erkundung

---

## 6. Audio & Musik

### 6.1 Musikalische Identität

- Orchester-Basis mit regionalen Instrumenten
- Leitmotive für Charaktere und Orte
- Dynamische Musik, die auf Kampf/Story reagiert

### 6.2 Voice Acting

- Vollständige Vertonung aller Dialoge
- Companions haben Banter während Exploration
- Der Held hat eine Stimme (keine stumme Protagonisten)

---

## 7. Technische Ziele

| Bereich | Ziel |
|---------|------|
| **Engine** | Unreal Engine 5 |
| **Grafik** | Realistisch mit stilisierten Elementen |
| **Performance** | 60 FPS auf Current-Gen Konsolen |
| **Ladezeiten** | Minimiert durch Streaming |

---

## 8. Monetarisierung

- **Vollpreis-Titel** (kein F2P, keine Lootboxen)
- **Story-DLCs** geplant (keine abgeschnittenen Inhalte)
- **Keine Mikrotransaktionen**

---

## 9. Inspiration & Differenzierung

### Was wir übernehmen:

| Spiel | Element |
|-------|---------|
| **The Witcher 3** | Graue Moral, lebendige Companions |
| **Mass Effect** | Beziehungen mit Konsequenzen |
| **Dark Souls** | Atmosphäre, Worldbuilding durch Details |
| **Dragon Age** | Companion-Dynamik, Origin-Stories |

### Was uns unterscheidet:

- **Macht-Entwicklung durch Nutzung** – keine Skillpunkte
- **Echte Konsequenzen** – Companions können WIRKLICH sterben/verraten
- **Kein Karma-System** – die Welt reagiert, aber urteilt nicht
- **Verzweigte erste Akte** – drei komplett unterschiedliche Erfahrungen

---

## 10. Risiken & Mitigation

| Risiko | Mitigation |
|--------|------------|
| Branching zu komplex | Klare Konvergenz-Punkte, wiederverwendbare Assets |
| Companion-Balance | Modulares Design, jeder ist "optional" |
| Zu düster | Humor durch Borin/Kraak, Momente der Hoffnung |
| Schwierigkeitsgrad | Optionale Accessibility-Features |

---

*Dieses Dokument ist ein lebendes Dokument und wird während der Entwicklung aktualisiert.*
