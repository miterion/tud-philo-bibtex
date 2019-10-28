# Bibtex Stil für Philosophieabgaben

Dieses Paket überschreibt einige Einstellungen des [biblatex-philosophy](https://ctan.org/pkg/biblatex-philosophy) Pakets mit den Vorgaben aus dem Dokument „Hinweise zum Bibliographieren und Zitieren“ aus der Version des Wintersemester 16/17.

## Benutzung
Die `philo.sty` Datei muss in einem für LaTeX auffindbaren Verzeichnis platziert werden. Im einfachsten Fall ist das direkt neben der zu kompilierenden `*.tex` Datei, alternativ kann es auch in einem globalen LaTeX-Pfad abgelegt werden (lassen sich unter Linux mit `kpsepath tex` finden).

Im Dokument wird das Paket dann ganz normal mit `usepackage` geladen. Zitiert wird dann mit dem Kommando `parencite`:

```latex
\usepackage{philo}
[...]

\parencite[Seite 5]{2011apologie}
```