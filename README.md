# Dynamic-Projection-Mapping

Dieses Repository richtet sich an Entwickler:innen, die die Software TouchDesigner nachvollziehen oder anpassen möchten.

Das Projekt zeigt ein dynamisches Projection Mapping auf zwei großen Körperfächern.

## Projektbeschreibung

Projizierte Videosequenzen folgen präzise den Bewegungen einer Performerin und interagieren mit ihr. Als Projektionsfläche dienen zwei überdimensionale Körperfächer, die sich während der Sequenz öffnen und schließen. Das Video folgt präzise sowohl dieser Bewegung als auch der Bewegung der Performerin im Raum.

## Beispiele

- [Zwischenstand](https://vimeo.com/1169113314): In dieser Dokumentation eines Zwischenstadiums folgt das Video den sich öffnenden und schließenden Fächern. Die vertikale Videodatei wird exakt in die Form der beiden Fächer gebogen.
- [Fertiges Projekt](https://vimeo.com/1168796466): Dokumentation des fertigen Projekts. Das Video folgt hier sowohl der Fächerbewegung als auch der Bewegung im Raum.

## Dateien

- `Breathshow.toe` — TouchDesigner-Projektdatei (aktuelle Version)
- `Breathshow.6.toe` — TouchDesigner-Projektdatei (Version 6)
- `setup-guide.md` — Einrichtungsanleitung für Tracking-Bereich

## Technologie

- [TouchDesigner](https://derivative.ca/) 2023.12370 — Echtzeit-Visuals und Projection Mapping
- [Azure Kinect](https://learn.microsoft.com/en-us/azure/kinect-dk/) — Tiefenkamera für Body-Tracking
- Compute Shaders — GPU-basierte Echtzeit-Verarbeitung der Tracking-Daten

## Credits

- **Künstlerin & Konzept:** Maren Strack — [maren-strack.de](http://www.maren-strack.de)
- **Softwareentwicklung:** Sebastian Becking
- **Technische Beratung & Projektkoordination:** [WE ARE VIDEO](https://wearevideo.de) (Christian Gasteiger, Raphael Kurig)

## Förderung

Gefördert vom Ministerium für Wissenschaft, Forschung und Kultur des Land Brandenburg.

## Hinweis zu Videoinhalten

Die Videodateien, die von den TouchDesigner-Projektdateien referenziert werden, sind nicht Teil dieses Repositories und nicht unter der GPL lizenziert. Die Rechte an den Videoinhalten liegen bei der Künstlerin Maren Strack. Die TouchDesigner-Software kann mit eigenen Videodateien betrieben werden.

## Lizenz

Copyright (C) 2025 Maren Strack, Sebastian Becking und WE ARE VIDEO GbR (Christian Gasteiger & Raphael Kurig)

Die Software in diesem Repository steht unter der [GNU General Public License v3.0](LICENSE).
