G10 Transport - V10

Contenu :
- index.html : application complète

Déploiement GitHub Pages :
1. Créer un dépôt GitHub.
2. Ajouter index.html à la racine.
3. Dans Settings > Pages, choisir la branche main et le dossier /root.
4. Ouvrir l'URL GitHub Pages générée.

Déploiement Firebase Hosting :
1. Installer Firebase CLI.
2. Exécuter firebase login.
3. Exécuter firebase init hosting.
4. Choisir ce dossier comme dossier public ou copier index.html dans le dossier public choisi.
5. Exécuter firebase deploy.

Codes d'accès de démo :
- Administration : 1234
- Chef d'exploitation : 2345
- Espace chauffeur : 1111
- Tableau de bord : 9999

Important :
Cette version utilise le stockage local du navigateur. Chaque appareil ou navigateur garde ses propres données.
Pour un essai multi-utilisateur réellement synchronisé entre plusieurs personnes, il faudra connecter l'application à Firebase Authentication et Firestore.
