Bestanden

Voor deze opdracht worden de volgende bestanden gebruikt:

treinverstoringen.ipynb - Jupyter Notebook met de volledige analyse.

Dataset.csv - de originele dataset met treinverstoringen.

prepared_train_disruptions.csv - de voorbereide dataset die gebruikt wordt voor het model.

Python-versie

Controleer in Jupyter welke Python-versie je gebruikt met:

import sys
print(sys.version)

Vul daarna hier jouw exacte versie in:

Python [vul hier jouw versie in]

Benodigde packages

De volgende packages zijn nodig:

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter

Installeren kan met:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Notebook starten

Zet treinverstoringen.ipynb en Dataset.csv in dezelfde map.

Start Jupyter Notebook of JupyterLab.

Open treinverstoringen.ipynb.

Voer alle cellen van boven naar beneden uit.

Controleer of alle cellen zonder fouten worden uitgevoerd.

Tijdens het uitvoeren wordt prepared_train_disruptions.csv aangemaakt.

Reproduceerbaarheid

In het notebook wordt random_state = 42 gebruikt. Hierdoor zijn de train-testverdeling en andere willekeurige stappen opnieuw uit te voeren met dezelfde instellingen.

Het notebook gebruikt relatieve bestandspaden. Hierdoor hoeft het bestand niet op een vaste plek op de computer te staan.

Een beperking is dat andere Python- of packageversies kleine verschillen in resultaten kunnen geven. Ook moet dezelfde ruwe dataset worden gebruikt om dezelfde analyse opnieuw uit te voeren.
