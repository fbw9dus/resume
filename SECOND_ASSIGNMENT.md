# Portfolio-Seite ausbauen
- Bitte beim Arbeiten an der Seite live-server benutzen
### Sass
- Das gesamte CSS der Seite soll in einer SCSS-Datei sein
- Sass-Verschachtelung statt Kinder-Selektoren benutzen
### Bilder
- Für Bilder darf nur Höhe oder nur Breite definiert sein, damit sie ihr ursprüngliches Seitenverhältnis haben.
### Responsive
- Achte darauf, dass die mobile Version bei den folgenden Änderungen nicht negativ beeinflusst wird.
- Verwende den Breakpoint für mittelgroße Geräte aus der [Bootstrap-Dokumentation](https://getbootstrap.com/docs/4.3/layout/overview/#responsive-breakpoints)
  #### Definiere in diesem media query:
  - Hover-Effekte für alle Links
  - Die Links der Hauptnavigation sollen nebeneinander stehen, nicht untereinander
  - Die Links sollen in Großbuchstaben geschrieben sein
  - Verwende eine Maximalbreite für das Haupt-Element der Seite, so dass der Inhalt bei großem Browserfenster nicht zu breit werden kann.
### Skalierung
- Verwende width:100vw und box-sizing:border-box für Elemente, die die ganze Fensterbreite ausfüllen sollen und dieses Verhalten noch nicht durch display:block haben.
- Verwende rem für Container-Größen und Text-Größen
### Code-Qualität
- Keine **hr**-Tags verwenden. Linien müssen mit border definiert sein.
- Keine **br**-Tags verwenden um Elemente untereinander anzuordnen oder um Abstände zu definieren. Für Darstellung untereinander z.B. display:block verwenden. Für Abstände margin oder padding verwenden.
### Bonus
- Definiere den ersten Abschnitt der Seite so, dass er genau die Höhe des Fensters hat. Du kannst dafür **vh** verwenden.
- Um Darstellungsfehler auszuschließen, kannst du dafür ein media query mit Mindesthöhe definieren.
