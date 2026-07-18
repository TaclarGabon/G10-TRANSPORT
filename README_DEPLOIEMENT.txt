G10 TRANSPORT — VERSION V12.10 FIREBASE

Fichiers à déposer à la racine du dépôt GitHub G10-TRANSPORT :
- index.html
- admin.html
- exploitation.html
- chauffeur.html
- dashboard.html
- README_DEPLOIEMENT.txt

Corrections V12.10 :
- Le chef d’exploitation garde le contrôle du planning aller et retour.
- Le chauffeur peut préparer le retour seulement si aucun retour n’a été programmé.
- Après l’arrivée du trajet retour, le bouton « Clôturer la tournée » archive le rapport puis remet la fiche active à zéro.
- Le bus passe au statut « Disponible » et attend un nouvel axe, une nouvelle date et une nouvelle heure.
- Une simple déconnexion pendant une course conserve les données pour permettre la reprise.
- Après clôture définitive, la reconnexion est bloquée tant que le chef d’exploitation n’a pas programmé une nouvelle course.

Commit conseillé :
Version V12.10 clôture tournée aller retour et remise à zéro

PIN onglets : Administration 1234 | Chef exploitation 2345 | Direction 9999
PIN bus : Bus 1 001 | Bus 2 002 | Bus 3 003 | Bus 4 004 | Bus 5 005 | Bus 6 006
