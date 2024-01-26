# Analyse du comportement des utilisateurs de l'application mobile

## Description du projet 
Il y a une start-up qui vend des produits alimentaires. Il est nécessaire de comprendre comment les utilisateurs de l'application mobile se comportent. Pour cela, il est important d'analyser l'entonnoir de vente. Il faut savoir comment les utilisateurs parviennent à l'achat, combien d'utilisateurs parviennent à l'achat, et combien restent bloqués aux étapes précédentes, et lesquelles exactement.

Ensuite, il faut étudier les résultats du test A/B. Les designers proposent de changer la police de caractères dans toute l'application.

Il a été convenu de prendre une décision en fonction des résultats du test A/B. Les utilisateurs ont été répartis en 3 groupes : 2 groupes de contrôle avec les anciennes polices de caractères et un groupe expérimental avec les nouvelles polices. Découvrez quelle police de caractères fonctionne le mieux.

La création de deux groupes A au lieu d'un présente certains avantages. Si les deux groupes de contrôle se révèlent identiques, on peut être sûr de la précision du test. Si des différences significatives existent entre les valeurs A et A, cela peut aider à identifier les facteurs ayant conduit à la distorsion des résultats. La comparaison des groupes de contrôle permet également de comprendre combien de temps et de données seront nécessaires pour les tests ultérieurs.

## But de travail 
Analyser le comportement des utilisateurs de l'application mobile.

## Objectifs du projet 
1) Étudier l'entonnoir des ventes.

2) Analyser les résultats du test A/B sur le changement de police.

## Description des données 
Les données sont présentées sous forme de journaux. Chaque entrée dans le journal est une action de l'utilisateur ou un événement.

- *EventName* — nom de l'événement;
- *DeviceIDHash* — identifiant unique de l'utilisateur;
- *EventTimestamp* — l'heure de l'événement;
- *ExpId* — le numéro de l'expérience : 246 et 247 sont les groupes de contrôle, tandis que 248 est le groupe expérimental.



