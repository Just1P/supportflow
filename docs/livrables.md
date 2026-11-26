# Livrables SupportFlow — CDA RNCP37873

Passage : 15 février 2027.
Source : dossier individuel de préparation (sections 11, 12 et 13) et guide de rattrapage.

Règle de cohérence : le dossier, le diaporama, le dépôt et l'application racontent exactement le même projet.
Rien n'est écrit dans les documents s'il n'existe pas dans le projet.

## 1. Livrables obligatoires (section 13)

- [ ] Dépôt Git : code complet, README, historique de commits, branches et pull requests
- [ ] Application déployée en HTTPS, avec un compte de démonstration par rôle (USER, TECH, ADMIN)
- [ ] Dossier de projet : chaque compétence C1 à C11 renvoie à une section et à une preuve précise
- [ ] Diaporama de soutenance qui montre les preuves essentielles
- [ ] Vidéo courte de démonstration, en secours si la démo en direct échoue
- [ ] Dossier professionnel mis à jour avec le travail réellement réalisé

## 2. Minimum démontrable par compétence (section 11)

Les compétences marquées ⚠ sont à vigilance renforcée (non acquises en première session).

### C1 — Environnement
- [ ] Dépôt Git complet
- [ ] README d'installation
- [ ] Historique de commits régulier
- [ ] Branches et pull requests
- [ ] Environnement local reproductible
- [ ] Fichier d'exemple des variables d'environnement (`.env.example`)
- [ ] Secrets exclus du dépôt

### C2 — Interfaces
- [ ] Au moins 4 écrans fonctionnels et responsives
- [ ] Au moins un formulaire validé côté client et côté serveur
- [ ] Lien clair entre maquettes et écrans réels
- [ ] Accessibilité de base vérifiée

### C3 — Métier ⚠
- [ ] Service ou couche métier identifiable
- [ ] 3 à 4 règles de gestion dans cette couche
- [ ] Contrôles d'autorisation côté serveur
- [ ] Tests unitaires sur les règles principales

### C4 — Gestion de projet
- [ ] Backlog de user stories
- [ ] Priorisation
- [ ] Tableau Kanban
- [ ] Planning en sprints ou en étapes
- [ ] Workflow Git
- [ ] Bilan : arbitrages, difficultés, fonctionnalités volontairement abandonnées

### C5 — Analyse et maquettes
- [ ] Contexte, acteurs, cas d'utilisation
- [ ] User stories avec critères d'acceptation
- [ ] 4 à 5 wireframes du parcours principal, dont au moins un écran mobile
- [ ] Schéma d'enchaînement des écrans
- [ ] RGPD et accessibilité pris en compte dès la conception

### C6 — Architecture
- [ ] Schéma en couches : présentation, API/contrôleurs, métier, accès aux données, bases
- [ ] Dépendances cohérentes entre les couches
- [ ] Justification de la stack
- [ ] Justification des choix de sécurité

### C7 — Base relationnelle ⚠
- [ ] Schéma de données conçu avant le développement
- [ ] Tables, types, clés primaires et étrangères, relations
- [ ] Contraintes et index
- [ ] Migrations SQL visibles et explicables
- [ ] Seed de données
- [ ] Compte SQL à droits limités
- [ ] Sauvegarde et restauration testées

### C8 — SQL / NoSQL ⚠
- [ ] Accès relationnels sécurisés
- [ ] Au moins une transaction
- [ ] Besoin documentaire / NoSQL justifié et démontré
- [ ] Lecture et écriture filtrées
- [ ] Savoir comparer relationnel et document
- [ ] Savoir expliquer la protection contre les injections

### C9 — Tests
- [ ] Plan de tests
- [ ] Tests unitaires
- [ ] Au moins un test d'intégration
- [ ] Un test E2E du parcours principal
- [ ] Jeu d'essai commenté : attendu / obtenu / analyse
- [ ] Rapport de couverture

### C10 — Déploiement
- [ ] Procédure pas à pas
- [ ] Prérequis
- [ ] Variables d'environnement
- [ ] Migrations
- [ ] Hébergement
- [ ] Gestion des secrets
- [ ] Procédure de retour arrière en cas d'échec

### C11 — DevOps ⚠
- [ ] Pipeline CI/CD : installation, contrôle qualité, tests, build, puis déploiement
- [ ] Contrôle de sécurité des dépendances
- [ ] Logs consultables
- [ ] Savoir expliquer ce qui se passe quand une étape échoue

## 3. Exigences transversales (section 12)

### Sécurité
- [ ] Mots de passe hachés
- [ ] Validation des entrées
- [ ] Autorisations vérifiées côté serveur
- [ ] Sessions / cookies sécurisés
- [ ] Secrets hors du dépôt
- [ ] HTTPS
- [ ] Plusieurs risques OWASP du projet expliqués, avec leur parade

### RGPD
- [ ] Minimisation des données
- [ ] Information de l'utilisateur
- [ ] Politique de confidentialité / mentions utiles
- [ ] Consentement lorsque nécessaire
- [ ] Export des données du compte
- [ ] Suppression des données du compte

### Accessibilité
- [ ] Audit d'au moins 3 pages avec un outil adapté
- [ ] Corrections réellement apportées
- [ ] Lien fait avec le RGAA

### Éco-conception
- [ ] Au moins 5 bonnes pratiques appliquées
- [ ] Une mesure avant / après qui objective les améliorations

## 4. Checklist de la veille du passage (section 9)

- [ ] Projet simple et terminé
- [ ] Réalisé sans IA générative (hors aides validées par le formateur, notées dans le journal)
- [ ] Je comprends tout le code présenté
- [ ] Je sais expliquer le besoin, les maquettes et le périmètre
- [ ] Je sais dessiner mon architecture de mémoire
- [ ] Je sais identifier mes objets et règles métier
- [ ] Je sais expliquer mon modèle relationnel, les clés et les relations
- [ ] Je comprends les requêtes SQL exécutées et le rôle de l'ORM
- [ ] Je sais expliquer l'usage du NoSQL (JSONB)
- [ ] J'ai un plan de tests et je sais lancer plusieurs tests
- [ ] Je sais expliquer mon déploiement et mon pipeline
- [ ] Je sais expliquer les mesures de sécurité principales
- [ ] Je retrouve rapidement chaque preuve dans le projet
- [ ] Mon dossier de projet correspond exactement à ce qui existe
- [ ] Je sais présenter les activités du CDA et leur enchaînement
- [ ] Je réponds à des questions imprévues avec mes propres mots
