Analyse de l’article scientifique 
Document analysé : Scoring System Based on Electrocardiogram Features to Predict the Type of Heart Failure in Patients With Chronic Heart Failure.

<img width="634" height="610" alt="image" src="https://github.com/user-attachments/assets/9e11c035-faa0-4e6f-a7a8-526d5da0c775" /><br>
Sources : tableaux 4, 5 et 8, pages 113 et 115 de la revue.
Vérification des résultats avec les tableaux originaux:<br>
Tableau 5 – Scores attribués aux caractéristiques ECG<br>
<img width="269" height="226" alt="4" src="https://github.com/user-attachments/assets/a938b914-1b85-49ff-a57a-72ebf3a7e8af" /><br>

Paramètre ECG	Score     |  score
LAH                     |	 1
Wide QRS	              |  2             
RBBB	                  |  -1
ST-T changes	          |  1
Prolong QT	            |  2

Tableau 8 – Validation du système de score

<img width="267" height="122" alt="image" src="https://github.com/user-attachments/assets/d4a44239-5553-48aa-a36d-bef041f001e8" /><br>
Score prédit	|  HFrEF (EF ≤ 40%)	| HFpEF (EF > 40%)<br>
HFrEF(+4 à +6)|      	19          | 	1<br>
HFpEF(-1 à +3)|      	6	          |   24<br>

Sensibilité = 19 / (19 + 6) = 76%.<br>
Spécificité = 24 / (24 + 1) = 96%.<br>
Accuracy = (19 + 24) / 50 = 86%.<br>

## Résultats expérimentaux

| Méthode | Jeu de données | Métrique | Résultat | Page |
|---|---|---|---|---|
| Régression logistique | 110 patients | OR – Wide QRS | 12.657 | 4 |
| Régression logistique | 110 patients | OR – QT prolongé | 7.401 | 4 |
| Système de score ECG | 50 patients | Sensibilité | 76% | 6 |
| Système de score ECG | 50 patients | Spécificité | 96% | 6 |
| Système de score ECG | 50 patients | Accuracy | 86% | 6 |




