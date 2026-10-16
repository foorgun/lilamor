# LILA — Tarot & Herzensfragen

Statische One-Page-Landingpage für die spirituelle Beraterin Lila.
Kein Framework, keine Build-Tools — die Dateien können direkt auf jedem
Webspace liegen oder lokal per Doppelklick geöffnet werden.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite: Hero, vier Themen-Sektionen, Trust-Leiste, Abschluss-CTA, Footer |
| `impressum.html` | Impressum (Platzhalter) |
| `datenschutz.html` | Datenschutzerklärung (Platzhalter) |
| `style.css` | gemeinsames Stylesheet, in nummerierte Abschnitte kommentiert |
| `assets/images/` | Hero-Foto und Tarot-Kartenfoto |

## Vor der Live-Schaltung

1. **Impressum und Datenschutzerklärung ausfüllen.** Beide Seiten tragen oben
   ein gelbes Warnbanner und enthalten nur Platzhalter in eckigen Klammern.
   Nach dem Ausfüllen den Banner-Block entfernen (im Code als Kommentar markiert).
2. **Google Fonts** wird derzeit von Googles Servern geladen und überträgt dabei
   die IP-Adresse der Besucher. Datenschutzfreundlicher ist es, die beiden
   Schriften (Cormorant Garamond, Jost) lokal mitzuliefern.
3. **WhatsApp-Nummer** steht an sieben Stellen in `index.html` und einmal im
   Impressum.

Die Texte der Rechtsseiten sind kein Rechtsrat und sollten anwaltlich geprüft werden.

## Texte ändern

Alle Texte stehen in den HTML-Dateien, nicht im Stylesheet. Jede Sektion ist
mit einem Kommentarblock überschrieben.
