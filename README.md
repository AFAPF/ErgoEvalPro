ErgoEval Pro – Bilan fonctionnel numérique pour enfants Dys
ErgoEval Pro est un outil libre et gratuit destiné aux ergothérapeutes, psychologues, enseignants spécialisés et parents. Il permet d’évaluer l’impact de l’utilisation d’un ordinateur chez les enfants présentant des troubles « dys » (dyslexie, dyspraxie, dyscalculie, troubles mixtes). Le logiciel est entièrement exécutable dans un navigateur web, sans installation, et conserve les données localement.

🧠 Fonctionnalités principales
14 épreuves interactives couvrant :

Pointage de cibles (dextérité souris/écran tactile)

Glisser-déposer (coordination œil-main)

Double-clic / clic droit (utilisation des périphériques)

Dictée de nombres (transcodage audio → écrit)

Calcul mental (nombres entiers, niveau CE2-CM2)

Résolution de problèmes (petits énoncés mathématiques)

Copie de texte (saisie clavier avec comptage mots/minutes et erreurs)

Barrage visuel (attention sélective)

Assemblage de formes (reproduction de figures géométriques)

Tracé de précision (suivi d’un chemin, détection des sorties)

Points à relier (planification visuo-spatiale)

Perception visuelle (discrimination d’images)

Trail Making (flexibilité cognitive, alternance chiffres/lettres)

Mémorisation visuelle (mémoire à court terme)

Modes de passation :

Évaluation : notée, enregistre les résultats pour le rapport.

Entraînement : permet à l’enfant de comprendre la consigne sans stress, non enregistré.

Saisie papier : pour chaque épreuve, l’ergothérapeute peut entrer manuellement les performances obtenues sur papier afin de comparer les deux modalités.

Rapport détaillé :

Notes sur 10 par épreuve.

Notes moyennes par catégorie (Logique, Calcul, Frappe clavier, Visuo-spatiale, Mémoire).

Graphique radar des compétences.

Comparaison numérique / papier.

Préconisations personnalisées selon les difficultés détectées.

Questionnaire de ressenti (😊 😐 😞) après chaque épreuve.

Paramètres d’accessibilité :

Thème clair / sombre.

Choix de police (OpenDyslexic incluse).

Réglage de la taille du texte.

Activation/désactivation des retours sonores.

Sauvegarde locale :

Toutes les données (profils, sessions, scores, sentiments) sont stockées dans le localStorage du navigateur. Aucune connexion Internet n’est requise après le chargement initial (hors CDN Chart.js).



🚀 Utilisation
Téléchargez le fichier ergoeval.html (ou clonez ce dépôt).

Ouvrez-le dans un navigateur récent (Chrome, Firefox, Edge). Aucune installation nécessaire.

Créez un profil pour l’enfant (nom, âge, groupe de trouble).

Accédez aux épreuves, choisissez le mode (évaluation, entraînement, saisie papier).

Une fois plusieurs épreuves réalisées, consultez le Rapport détaillé pour analyser les résultats et obtenir des recommandations.

🛠️ Technologies utilisées
HTML5, CSS3, JavaScript (ES6) – vanilla, sans framework.

Chart.js (chargé via CDN) pour les graphiques radar.

LocalStorage pour la persistance des données.

Synthèse vocale native (Web Speech API) pour la dictée de nombres.

📂 Structure du projet
Le projet est contenu dans un seul fichier index.html (ou ergoeval.html). Il n’y a pas de build, de dépendances serveur, ni de dossier node_modules. Vous pouvez le servir directement avec n’importe quel serveur web statique ou simplement l’ouvrir en local.

text
.
└── index.html
⚠️ Limitations
Les données étant stockées dans le localStorage, elles sont propres à chaque navigateur et à chaque ordinateur. Il n’y a pas de synchronisation multi‑poste.

Certaines épreuves (tracé, pointage) sont optimisées pour écran tactile mais offrent une meilleure expérience avec une souris.

La synthèse vocale (dictée) nécessite un navigateur compatible (Chrome, Edge, Firefox). Un fallback visuel est prévu.

Les scores et préconisations sont indicatifs et ne remplacent pas une évaluation clinique complète.

🤝 Contribution
Les contributions sont les bienvenues ! Idées d’améliorations :

Ajouter un backend pour centraliser les données.

Permettre l’export PDF du rapport.

Ajouter de nouvelles épreuves (Go/No-Go amélioré, dictée vocale).

Traduire l’interface en d’autres langues.

Ajouter des tests automatisés.

Pour proposer des modifications :

Forkez le projet.

Créez une branche (feature/ma-fonctionnalité).

Committez vos changements.

Ouvrez une Pull Request.

📝 Licence
Ce logiciel est distribué sous licence MIT. Vous êtes libre de l’utiliser, le modifier, le distribuer, y compris à des fins commerciales, tant que vous conservez la mention de copyright et la licence.

✨ Remerciements
Chart.js pour la bibliothèque de graphiques.

La communauté des ergothérapeutes pour leurs retours et idées.

Tous les enfants et familles qui ont testé l’outil.
