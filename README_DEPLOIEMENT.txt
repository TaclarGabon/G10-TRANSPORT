G10 TRANSPORTS — V11 FIREBASE
================================

FICHIERS
- index.html : application complète
- admin.html : lien direct Administration
- exploitation.html : lien direct Chef d'exploitation
- chauffeur.html : lien direct Espace chauffeur
- dashboard.html : lien direct Tableau de bord / Direction

CODES DE TEST
- Administration : 1234
- Chef d'exploitation : 2345
- Espace chauffeur : 1111
- Tableau de bord / Direction : 9999

Le code 9999 est un code maître dans le même onglet : après ouverture du Tableau de bord, les autres modules s'ouvrent sans redemander de code durant cette session.

FIREBASE
Projet : taclar-52e72
Collection : G10_transport
Document partagé : state

La V11 synchronise en temps réel :
- groupes chauffeur / aide chauffeur
- tarifs et axes
- capacités et affectations des bus
- places vendues et recettes
- statuts Chargement / En route / Arrivé / Clôturé
- rapport journalier

DÉPLOIEMENT GITHUB
1. Décompresser ce ZIP.
2. Ouvrir le dépôt GitHub G10-TRANSPORT.
3. Add file > Upload files.
4. Déposer les 5 fichiers extraits, pas le ZIP.
5. Commit changes.
6. GitHub Pages étant déjà activé, attendre 1 à 3 minutes.

LIENS APRÈS DÉPLOIEMENT
- Accueil : https://taclargabon.github.io/G10-TRANSPORT/
- Admin : https://taclargabon.github.io/G10-TRANSPORT/admin.html
- Exploitation : https://taclargabon.github.io/G10-TRANSPORT/exploitation.html
- Chauffeur : https://taclargabon.github.io/G10-TRANSPORT/chauffeur.html
- Direction : https://taclargabon.github.io/G10-TRANSPORT/dashboard.html

IMPORTANT
Les règles Firestore sont ouvertes pour le test pilote. Avant une diffusion publique durable, activer Firebase Authentication et resserrer les règles.
