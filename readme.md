# The file

[http://denis.mottet.free.fr/M2R/WORK/DATA/ECGu.txt]
Fichier txt : 
6500 rows x 4 columns

# Indications

The ECG recording equipment manufacturers instructions specify:

- Leads recorded : `I, II, III` 
- Sampling frequency : `1024 Hz` 
- A/D converter gain : `520 µV per unit`

** On a donc trois enregistrements de signaux ECG. Sachant qu'on a une fréquence d'échantillonnage de 1024 Hz ou 1024 s-1, alors il faudrait 1024 échantillons par seconde. On a également un gain de 520 µV qu'il faut multiplier aux données pour que les données brutes soient en unités physiques (microvolts).**

# Low Pass Filter 

Ajout d'un filtre passe bas:
taux_echantillonnage = 1024  Hz
frequence_coupure = 400

## Requirements
- VSCode with the python and jupyter extensions installed (or any other IDE that supports python and jupyter notebooks)