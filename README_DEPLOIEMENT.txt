G10 TRANSPORTS — V11.3 FIREBASE

Fichiers à publier à la racine GitHub Pages :
- index.html
- admin.html
- exploitation.html
- chauffeur.html
- dashboard.html

Codes de démonstration :
- Administration : 1234
- Chef d’exploitation : 2345
- Espace chauffeur : 1111
- Direction : 9999

Nouveautés V11.3 :
- Connexion chauffeur = statut En service
- Bandeau Bus 1 à 6 avec statut visible en temps réel
- Départ et arrivée confirmés puis verrouillés
- Statut En route vers la destination
- Déclaration et clôture d’incident avec heure de reprise
- Fin de service à la place de Clôturer tournée
- Rapport Firestore distinct par trajet
- Basculement automatique vers l’axe retour
- Suppression du bouton Changer bus
- Réinitialisation complète conservée

MISE À JOUR V11.5 — PRÉSENTATION ACCORDÉON PAR RÔLE
- Au départ, aucun Bus 1 à Bus 6 n'est affiché dans l'accueil général.
- Chauffeur : la flotte apparaît sous « Espace chauffeur » seulement après connexion au bus avec le PIN.
- Chef d'exploitation : la flotte apparaît sous « Chef d'exploitation » après connexion.
- Direction : tous les menus restent visibles, les six bus apparaissent sous « Espace chauffeur » et « Direction » reste le dernier onglet.
- Administration : aucun bandeau Bus 1 à Bus 6 n'est affiché.
- Les six bus restent affichés dans les espaces autorisés; seuls les bus connectés affichent un statut.


MISE À JOUR V11.5 — CODES COULEURS DES STATUTS
- En service : dégradé orangé vers vert (conservé)
- En route : dégradé orangé vers jaune, sans fond bleu
- Incident : dégradé orangé vers violet
- Arrivé : dégradé orangé vers gris
- Les cartes de tournée en cours utilisent aussi une teinte orangée claire au lieu du bleu

V11.6 — Sécurisation des affectations
- Un bus déjà affecté à un autre groupe ne peut plus être repris silencieusement.
- Un bus En service, En route, en incident ou arrivé est verrouillé jusqu’à la fin de service.
- Les bus indisponibles sont désactivés dans les listes d’affectation.
- Un message explicite s’affiche en cas de tentative interdite.
