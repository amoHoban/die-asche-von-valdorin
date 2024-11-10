# Das Macht-System
## Mechanik & Narrative Integration

---

## Grundprinzipien

### 1. Keine Skillpunkte

Traditionelle RPGs: "Du hast 3 Punkte. Wohin damit?"

**Die Asche von Valdorin:** Deine Macht formt sich nach dem, wie du sie nutzt. Die Wahl passiert nicht im Menü – sie passiert im Spiel.

### 2. Macht verändert dich

Magie ist keine Ressource. Sie ist eine Beziehung. Und wie jede Beziehung verändert sie beide Seiten.

### 3. Drei Mächte, unendliche Kombinationen

Der Held kann maximal drei aktive Mächte tragen. Mehr können gefunden werden – aber nur getauscht, nicht gestapelt.

---

## Die sieben Mächte

### Primäre Mächte (früh verfügbar)

| Macht | Ursprünglicher Träger | Domäne |
|-------|----------------------|--------|
| **Wille** | Aldric der Graue | Geist, Telekinese, Kontrolle |
| **Leben** | Seraphina | Heilung, Gift, Körper |
| **Schatten** | Malachar | Dunkelheit, Angst, Unsichtbarkeit |

### Sekundäre Mächte (später findbar)

| Macht | Ursprünglicher Träger | Domäne |
|-------|----------------------|--------|
| **Feuer** | Brennan der Rote | Zerstörung, Reinigung |
| **Zeit** | Isolde | Reflexe, Vorahnung |
| **Stein** | Korvac | Verteidigung, Erde |
| **Stimme** | Lyanna | Überzeugung, Illusion |

---

## Entwicklungs-System

### Wie es funktioniert

Jede Macht hat drei Entwicklungspfade. Der Pfad wird durch Nutzung bestimmt – nicht durch explizite Wahl.

```
                    HERRSCHAFT (Dominanz)
                   /
WILLE (Start) ----  BOLLWERK (Schutz)
                   \
                    EINSICHT (Wissen)
```

### Tracking-System (intern)

Das Spiel trackt unsichtbar, wie der Spieler jede Macht einsetzt:

```python
# Pseudo-Code für das Tracking
macht_nutzung = {
    "wille": {
        "offensiv": 0,      # Feinde dominieren, Willen brechen
        "defensiv": 0,      # Verbündete schützen, Angriffe abwehren
        "subtil": 0         # Gedanken lesen, Wahrheiten suchen
    }
}

# Bei Schwellenwert → Entwicklung
if macht_nutzung["wille"]["offensiv"] > SCHWELLE:
    entwickle_zu("herrschaft")
```

### Die Entwicklungen im Detail

#### WILLE

| Pfad | Nutzungsart | Fähigkeiten | Narrativer Effekt |
|------|-------------|-------------|-------------------|
| **Herrschaft** | Dominieren, Zwingen | Gedankenkontrolle, Massenlähmung | NPCs fürchten dich |
| **Bollwerk** | Schützen, Abwehren | Mentaler Schild, Teamschutz | NPCs vertrauen dir |
| **Einsicht** | Lesen, Verstehen | Gedankenlesen, Vorahnung | NPCs finden dich unheimlich |

#### LEBEN

| Pfad | Nutzungsart | Fähigkeiten | Narrativer Effekt |
|------|-------------|-------------|-------------------|
| **Heiler** | Nur Heilung | Mächtige Regeneration | Als Heiliger verehrt |
| **Nekromant** | Manipulation, Kontrolle | Untote erschaffen, Gift | Als unnatürlich gefürchtet |
| **Balance** | Beides gleichmäßig | Vielseitig, weniger mächtig | Respektiert, nicht gefürchtet |

#### SCHATTEN

| Pfad | Nutzungsart | Fähigkeiten | Narrativer Effekt |
|------|-------------|-------------|-------------------|
| **Assassine** | Töten aus dem Schatten | Tödliche Strikes, Unsichtbarkeit | Gefürchtet von allen |
| **Beschützer** | Verbündete verbergen | Gruppen-Tarnung, Ablenkung | Beschützer der Schwachen |
| **Albtraum** | Angst und Terror | Psychische Angriffe, Panik | Selbst Verbündete sind nervös |

---

## Der Preis der Macht

### Physische Konsequenzen

| Macht | Übernutzung führt zu... | Gameplay-Effekt |
|-------|------------------------|-----------------|
| **Schatten** | Farbsehen verschwindet | Welt wird grau (visuell) |
| | Tageslicht schmerzt | Debuff bei Tag |
| **Feuer** | Berührung wird heiß | Romantische Szenen ändern sich |
| | Kälteempfindlichkeit | Debuff in kalten Regionen |
| **Wille** | Gedanken hörbar (ungewollt) | Zufällige Gedanken-Einblendungen |
| | Kopfschmerzen in Menschenmengen | Debuff in Städten |
| **Leben** | Unkontrolliertes Altern | Visuell sichtbar |
| **Zeit** | Déjà-vus, Zeitschleifen | Verwirrende aber nützliche Effekte |

### Narrative Konsequenzen

NPCs reagieren auf deine Macht-Entwicklung:

```
[HERRSCHAFT entwickelt]

DORFBEWOHNER: (weicht zurück)
"Der... der Herrscher der Gedanken. Bitte, Herr, wir haben nichts getan."

[HEILER entwickelt]

DORFBEWOHNER: (kniet nieder)
"Der Gesegnete! Bitte, mein Kind ist krank. Könnt Ihr..."

[ALBTRAUM entwickelt]

DORFBEWOHNER: (Panik)
"WACHEN! Der Schattenmann ist hier!"
```

---

## Macht-Wechsel

Mächte können getauscht werden an:

### 1. Orte der Macht

Alte Heiligtümer, verstreut in der Welt. Einmal pro Spielabschnitt nutzbar.

### 2. Durch lebende Erhabene

Seraphina kann Mächte transferieren – wenn sie dem Spieler vertraut.

### 3. Selbst erzwungen

Möglich, aber teuer:
- Kostet **Lebenskraft** (permanenter HP-Verlust) oder
- Kostet **Erinnerungen** (Verlust von Companion-Vertrauen)

---

## Kombinations-Synergie

Bestimmte Macht-Kombinationen haben spezielle Effekte:

| Kombination | Synergie-Effekt |
|-------------|-----------------|
| Wille + Schatten | "Puppenspieler" – Feinde kämpfen gegeneinander |
| Leben + Feuer | "Phönix" – Wiederbelebung nach dem Tod (einmal) |
| Zeit + Wille | "Voraussicht" – Gegner-Züge werden angezeigt |
| Schatten + Stimme | "Doppelgänger" – Perfekte Illusion von dir selbst |

---

## Balance-Überlegungen

### Keine "beste" Kombination

Jede Entwicklung hat Vor- und Nachteile:
- **Herrschaft** ist mächtig, aber NPCs kooperieren schlechter
- **Heiler** ist nützlich, aber defensiv schwächer
- **Assassine** tötet schnell, aber Companions sind nervös

### Respec?

**Nein.** Die Entscheidungen sind permanent – wie im Leben.

Aber: Das Spiel ist so designt, dass jede Kombination das Spiel beenden kann.

---

## Implementation Notes

### UI/UX

- Keine explizite Anzeige des Entwicklungs-Fortschritts
- Spieler bemerkt Entwicklung durch Dialoge und Fähigkeits-Änderungen
- Optionaler "Macht-Status" im Menü für die, die es wissen wollen

### Speichern

- Macht-Status wird kontinuierlich gespeichert
- Kein Ausnutzen durch Speicher-Laden möglich
- "Was getan ist, ist getan"

---

*Dieses System soll Immersion fördern und den Spieler dazu bringen, über seine Handlungen nachzudenken – nicht nur über Optimierung.*
