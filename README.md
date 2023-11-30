### ![Goju Ryu Karate Reusrath](/Gfx/sglgrkr/GJRKDR_s.jpg)[^1]
### :punch:Trainingskarten Set:martial_arts_uniform:
#### Als LaTeX-Distribution würde ich MiKTeX (https://miktex.org/) empfehlen, da diese relativ schlank bleibt und nicht mit einer so überbordenden Installation daher kommt. Als Editor für die LaTeX-Quelltexte und GUI zur Erstellung der PDF's ist meiner Meinung nach TeXstudio (https://texstudio.org/) sehr gut geeignet, da es unter den gängigen Betriebssystemen  (Windows, macOS und Linux) zur Verfügung steht und kostenlos ist.
#### ~~Als fertige PDFs unter dem Verzeichnis [`/build`](build/) zu finden~~
#### Aufbau
- Ordner
  - [ ] [`/Gfx`](Gfx/) enthält Quellgrafiken [^2]
  - [ ] [`/input`](input/) enthält die Input-Files der übergeordneten LaTeX Dateien
- Dateien
  - [ ] Struktur/Aufbau: die Dateien sind jeweils inkludierend, sprich einzelne Karten enthalten lediglich die Inhalte des jeweiligen Satzes, die Komplettsätze erzeugen jeweilige Einzelkarten über entsprechende Subimporte.
  - [ ] ~~`TrainingsKarte_*.tex` enthält den Quelltext um mit einer passenden LaTeX Distribution die jeweiligen Karten für die entsprechende Graduierung, bzw. Ergänzungen oder Partnerformen, zu erzeugen~~
  - [ ] `Komplettsatz_*.tex` enthält den Quelltext um mit einer passenden LaTeX Distribution den jeweiligen Komplettkartensatz zu erzeugen, jeweils entweder in DIN A4 oder DIN A5. 
  - [ ] `README.md` diese Datei

#### Print / Ausgabe
Die Ausgabe ist für den Ausdruck auf DIN A5 **zweiseitig** im **Querformat** optimiert - die einzelnen Blätter können laminiert werden, oder direkt bei einem passenden Anbieter als Druckexemplar bestellt werden.
  [^1]: :copyright:[SG Langenfeld - Wettkampf - Goju-Ryu Karate Reusrath](https://www.sglangenfeld.de/de/wettkampf/karate-goju-ryu-reusrath/)
  [^2]: :copyright: diverse Copyrights, sind im Literaturverzeichnis am Ende des Komplettsatzes aufgeführt (wip).
