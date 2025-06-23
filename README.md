# Etude de la productivité des forages de Parakou et Tchaourou
Ce projet vise à analyser la productivité des forages des communes de Parakou et Tchaourou situées dans le Nord du Bénin. Il a été réalisé dans le cadre de mon mémoire de master en hydrogéologie ayant pour titre "Apport de la télédétection et de l'analyse multicritère dans la détermination des zones à forte potentialité en eau souterraine". Le travail a été réalisé en plusieurs étapes :
+ La collecte des données de forages de Parakou et Tchaourou : ces données ont été fournies dans un fichier Excel
+ L'identification des paramètres pertinents pour l'étude : profondeur totale des forages, épaisseur d'altération des forages, épaisseur de socle foré et débit exploitable
+ Le nettoyage des données
+ L'analyse statistique et la visualisation des paramètres considérés pour l'étude
+ L'étude de la relation entre chacun des paramètres profondeur totale, épaisseur d'altération, épaisseur de socle foré et le débit

## Données utilisées
Les données utilisées proviennent d'une base de données des données techniques des forages du Bénin, fournie par la Direction Générale de l'Eau du Bénin. Nous avons considéré les données relevant de notre zone d'étude : les communes de Parakou et Tchaourou. Il s'agit de :
+ Prof_Totale : profondeur totale des forages
+ Prof_Toit : epaisseur d'altération
+ Prof_Mur : Niveau bas du socle
+ Débit_Exploitable : débit utilisé

Etant dans un aquifère de socle cristallin, nous avons considéré que la profondeur du toit de l'aquifère représente l'épaisseur d'altération. Pour déterminer l'épaisseur de socle foré, nous avons réalisé une soustraction entre la profondeur du mur et celle du toit.
![image](https://github.com/user-attachments/assets/c32d7294-0f24-44a9-917b-ec18153554bd)  
Modèle conceptuel de la zone de socle (Wyns et al, 2004)


## Outils utilisés
+ Python (Pandas, Matplotlib, Seaborn)
+ Jupyter Notebook
+ GitHub

