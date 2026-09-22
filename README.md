# IDPA: Interdisziplinäre Projektarbeiten mit der ZHAW
## Die Brücke zwischen Berufsmaturität und Fachhochschulstudium im Kanton Zürich

In diesem Projekt geht es darum, dass Mitarbeitende der ZHAW in Lehre und/oder Forschung Berufsmaturitäts-Lernende der BM-Ausrichtung TALS (Technik, Architektur, Life Sciences) beim Verfassen ihrer BM-Abschlussarbeit in fachlicher Hinsicht als ZHAW-Coaches unterstützen. Die Hauptbetreuungsperson ist nach wie vor die Lehrperson an der BM-Schule .


# Maschinelles Lernen in der Biomedizin  
Im Rahmen dieses Projekts lernen Sie die Grundlagen von maschinellem Lernen kennen und wie sie in biowissenschaftlichen Datensätzen angewendet werden kann. Sie lernen, wie Clustering, neuronale Netze, Deep Learning funktionieren, und wie man diese mit Beispielen aus der Krebsforschung und aus der Entwicklung von Therapien benutzt, um ein Computerprogramm herzustellen. Sie werden in der Lage sein, das Programm als ein interaktives Werkzeug zu visualisieren, und in die spannende Welt der Data Science einzutauchen. 

## Vorgeschlagener Plan:

### Lernziele:
- wissenschaftliche Literatur lesen und verfolgen 
- erklären, wie ML in der Biomedizin angewandt wird
- sich mit grundlegenden Programmierungs-Werkzeugen und besonders ML vertraut machen
- verstehen, wie genomische LLMs funktionieren und sie benutzen
- Code schreiben oder manupluieren, um einfache Analysen in der Krebsforschung durchzuführen
- Interpretation der Ergebnisse der Datenanalysen
- optional: Erstelle wissenschaftliche Fragen, gestalte einen einfachen Workflow zur Beantwortung dieser Frage und führe selbst Analysen durch

### Genetik
 Hier sind die Literaturprobe zur Genetik:
1) folgende Seiten auf studyflix.de : [Gen](https://studyflix.de/biologie/gen-2599), [Genom](https://studyflix.de/biologie/genom-2645), [Genwirkkette](https://studyflix.de/biologie/genwirkkette-6706), [Proteinbiosynthese](https://studyflix.de/biologie/proteinbiosynthese-2288), [DNA Funktion](https://studyflix.de/biologie/dna-funktion-2601), [Mutation](https://studyflix.de/biologie/mutation-2582), [Mutagene](https://studyflix.de/biologie/mutagene-2574)

### Genomik
 Hier ist ein Notebook zum Verständnis von Genomen :
2) Genomik: Wir werden die Studie von Genomik entdecken, Gene in einem Genom finden, Genteile erkennen. Hier werden wir individuelle Krebsgene studieren: Genfunktionen, wo in der Zelle sie arbeiten, falls sie zu den anderen Genen binden, was für Krankheiten ihre Mutationen verursachen. Letztens werden wir diese Gene und ihre Mutationen in Genen visualisieren. Hier ist der Arbeitslauf: https://github.com/tbilgin/Krebsgenomik/blob/main/Krebsgen_Analyse.md 

### LLM's:

Hier ist eine gute Erklärung zu LLM's, die wir für RNA benutzen. https://www.rouskinlab.com/articles/albatross/ 
Hier ist eine schöne Visualisierung: https://albatrossrna.org 

### genomische LLM's:

Hier sind drei Notebooks im Google Colab. Die werden euch helfen, um über genomische LLM's zu lernen. Please make your own copies and play with the notebooks below.

1) Introduction to Huggingface for genomic LLMs: https://colab.research.google.com/drive/1R5lriN2-NxDpSi5qq8-z3g8Ls5lFFeQh?usp=sharing
2) DNABert foundation model in genomic LLMs: https://colab.research.google.com/drive/1UW7r2PDL9Ijq6D5HTf3exwQmsDsFBcdi?usp=sharing
3) Embeddings and token importance: https://colab.research.google.com/drive/1Bbx9vOIGzAWt2EWuG2QWcgM3-ulljrkp?usp=sharing
   


Bitte erstellen Sie eine Kopie dieses Notizbuchs in Ihrem eigenen Google Drive. Diese Datei kann nicht bearbeitet werden, aber Ihre eigene Datei können Sie bearbeiten. Ich empfehle Ihnen, sich vor dem Start ein Video zur Verwendung von Google Collab anzusehen. Einige praktische Informationen: Jede Zelle enthält entweder einen Code oder einen Text. Bitte führen Sie die Zelle aus, wenn es sich um einen Code handelt. Es ist wichtig, dass Sie jeden Code ausführen, da der Rest des Codes die Ausgabe verwendet. Wie führt man einen Code in diesem Notizbuch aus? Bewegen Sie die Maus vor den Code, es erscheint ein Häkchen. Klicken Sie auf das Häkchen. Es wird grün, sobald der Befehl ausgeführt wurde.


### Klassifizierung von Daten:
Wir werden zunächst Lernalgorithmen anwenden, um Krebsgene anhand der oben aufgeführten Merkmale zu erkennen und anschliessend einen speziellen Fall von Darmkrebsmutationen zu untersuchen, um die tumorbasierten Mutationen zu klassifizieren. Hier ist der [Arbeitslauf](https://colab.research.google.com/github/tbilgin/SURGE/blob/master/MachineLearningBioinfo4B.ipynb). Und hier sind [die Daten](https://github.com/tbilgin/Krebsgenomik/blob/main/patient_data.xlsx). 

