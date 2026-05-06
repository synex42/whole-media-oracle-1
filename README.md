# WHOLE MEDIA(?) ORACLE

Live version oft the Oracle (via GitHub pages)
https://synex42.github.io/whole-media-oracle-1/

Welcome to the Whole Media(?) Oracle, which allows you to encounter the digitized content of the Whole Earth Catalogue. 

## BACKGROUND

Developed during the Environmental Data, Media and the Humanities-Hackathon, 15 -17 April 2026 in Potsdam, organised by the  [network of digital humanities of Potsdam University]([https://www.uni-potsdam.de/de/digital-humanities]) in collaboration with Camille Belmin, Aristide Curtelin, Marie Grau, Juliane Mueller, Sybille Neumeyer, Reto Riggs, Birgit Schneider, Julien Schuh, Anne-Violaine Szabados, Silvan auf der Maur, Evi Zemanek, Mela Zuljevic

## TECHNICAL SETUP

The Whole Media Oracle is a single-file web application built entirely in HTML, CSS and JavaScript — no frameworks, no libraries, no server-side code. Everything runs in the browser.
The only file the browser executes is index.html. All content — questions, lenses, prisms, images and text fragments — is loaded dynamically from plain text and image files at runtime.

To run the project locally, a minimal local server is required so the browser can load the data files. The simplest way is Python's built-in server: cd /path/to/your/oracle/folder
python3 -m http.server 8080
Then open http://localhost:8080 in a browser.

To run it online, the project is hosted via GitHub Pages, which serves the files directly from the repository. No backend or database is needed.

## BUILDING /DEVELOPING

The entire application is contained in index.html. It is structured in three parts:

HTML — defines the screens
CSS — all visual styling, typography, layout and transitions
JavaScript — all logic: data loading, SVG rendering, interaction, text search, collage generation
