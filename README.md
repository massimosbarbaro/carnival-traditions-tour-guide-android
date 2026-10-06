# Pust Tour Guide: map guide to the carnival traditions of an Alpine border region

*Guida su mappa alle tradizioni carnevalesche di una regione alpina di confine*

**MIT App Inventor (Android)** · 2022–2023 · version 1.0 (2)  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Pust Tour Guide, built on the Multi Tour Guide engine, presents about thirty villages and towns on both sides of the Italian–Slovenian border where traditional carnival (*pust*) masks and customs survive. The sites are grouped by area on separate maps; for each one the app describes the masks and rites in four languages, shows the distance from the user, opens navigation and links to a web page. A countdown shows the time left to the next carnival.

I designed and programmed this application in 2022–2023. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Countdown to the next carnival on the start screen (countdown extension).
- Maps of the carnival sites grouped by area (`Maps`, `MapsScreen`, `MapsBardo`).
- Description of the masks and customs of each place in Slovene, Italian, English and German (`Pust`).
- Location screens with distances and navigation (`Location`, `LocationScreen`, `LocationBardo`, `Navigate`).
- Photo gallery with the camera (`GalleryScreen`).

## Data

Coordinates and multilingual texts are embedded in the app.

## Technology

MIT App Inventor 2: Map, Marker, LocationSensor, ActivityStarter, Camera, Canvas, ImageSprite, ListView, File, Clock, TextToSpeech, TinyDB; extensions ScaleDetector (MIT) and a countdown extension.

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## Related repositories

- [multilingual-gps-tour-guide-appinventor](https://github.com/massimosbarbaro/multilingual-gps-tour-guide-appinventor)
- [folklore-gps-tour-guide-appinventor](https://github.com/massimosbarbaro/folklore-gps-tour-guide-appinventor)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). Each release is archived on Zenodo with its own DOI.

> Sbarbaro, Massimo. *Pust Tour Guide: map guide to the carnival traditions of an Alpine border region (MIT App Inventor (Android), 2022–2023)*. Software, version 1.0 (2). GitHub: https://github.com/massimosbarbaro/carnival-traditions-tour-guide-appinventor

## License

Released under the [MIT License](LICENSE). © 2022 Massimo Sbarbaro.
