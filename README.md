### ![Goju Ryu Karate Reusrath](/Gfx/sglgrkr/GJRKDR_s.jpg)[^1]
### :punch:Trainingskarten Set:martial_arts_uniform:
#### Als fertige PDFs unter dem Verzeichnis [`/build`](build/) zu finden
#### Aufbau
- Ordner
  - [ ] [`/build`](build/) enthält erzeugte PDF Dateien und ein gezipptes Komplettarchiv
  - [ ] [`/Gfx`](Gfx/) enthält Quellgrafiken [^2]
  - [ ] [`/input`](input/) enthält die Input-Files der übergeordneten LaTeX Dateien
  - [ ] [`/zip_sources`](zip_sources/) enthält alle Quelltextdateien als ZIP
- Dateien
  - [ ] Struktur/Aufbau: die Dateien sind jeweils inkludierend, sprich einzelne Karten enthalten lediglich die Inhalte des jeweiligen Satzes, die Komplettsätze erzeugen jeweilige Einzelkarten über entsprechende Subimporte.
  - [ ] `TrainingsKarte_*.tex` enthält den Quelltext um mit einer passenden LaTeX Distribution die jeweiligen Karten für die entsprechende Graduierung, bzw. Ergänzungen oder Partnerformen, zu erzeugen
  - [ ] `Komplettsatz_*.tex` enthält den Quelltext um mit einer passenden LaTeX Distribution den jeweiligen Komplettkartensatz zu erzeugen, jeweils entweder in DIN A4 oder DIN A5. 
  - [ ] `Goju_Ryu_Reusrath.txss2` Session für TexStudio
  - [ ] `Goju_Ryu_Reusrath_WIN.txsprofile` Profil für TexStudio (Windows)
  - [ ] `README.md` diese Datei
  
  [^1]: :copyright:[SG Langenfeld - Wettkampf - Goju-Ryu Karate Reusrath](https://www.sglangenfeld.de/de/wettkampf/karate-goju-ryu-reusrath/)
  [^2]: :copyright: diverse Copyrights, sind im Literaturverzeichnis am Ende des Komplettsatzes aufgeführt (wip).
