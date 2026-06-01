# PROJETS DE STAGE 
## Projet 1 
### Plateforme de Gestion des Incidents Informatiques (Help Desk / Support IT)
**Contexte :**
Une entreprise possède plusieurs ordinateurs, imprimantes, routeurs et utilisateurs. Lorsqu'un problème survient, les employés doivent le signaler au service informatique.

**Partie Informatique de Gestion**

Développer une application Web avec Laravel + React permettant :

- Authentification
- Création de tickets d'incident
- Suivi des demandes
- Affectation des interventions
- Historique des réparations
- Tableau de bord statistique
- Rapports PDF 

**Exemple**

"Mon ordinateur ne se connecte plus au réseau."

L'utilisateur crée un ticket et le technicien le traite.

**Partie Réseau / Support**

Dans Cisco Packet Tracer :

- Création de l'infrastructure réseau
- Configuration des VLAN
- Configuration DHCP
- Configuration DNS
- Détection et résolution des pannes
- Simulation de problèmes réseau

**Ce qui impressionne le jury** 

Vous montrez :
- Une vraie application métier.
- Un vrai réseau d'entreprise.
- Une interaction entre les deux. 

## Projet 2
### Plateforme de Gestion Scolaire + Infrastructure Réseau d'École 

**Concept**

Une école béninoise veut se digitaliser. Vous construisez le système d'information, concevez et simulez le réseau qui le fait tourner. Le rendu final est un produit complet et déployable. 

**Application Web (React + Laravel)**

- Authentification par rôle (Directeur, Enseignant, Parent, Élève)
- Gestion des élèves, classes, matières, enseignants
- Saisie et calcul automatique des notes + bulletins PDF
- Suivi des absences et retards
- Module de paiement des frais de scolarité + reçus
- Tableau de bord statistiques (taux de réussite, recettes...) 

**Infrastructure Réseau (Packet Tracer)**

- Topologie complète : Salle informatique / Administration / Direction / Salle des profs
- VLAN par département (chaque zone isolée)
- Serveur DHCP pour attribution automatique des IP
- DNS local pointant vers ton application Laravel
- ACL (listes de contrôle d'accès) pour sécuriser les zones
- Simulation de connexion internet via un FAI 

**Rendu final**

Application web fonctionnelle + fichier .pkt avec réseau simulé + rapport commun expliquant comment les deux s'articulent. 

## Projet 3 
### Système de Gestion de Cybercafé + Réseau du Cybercafé 

**Concept** 

Le cybercafé est l'endroit où gestion et réseau se confondent naturellement. C'est le projet le plus cohérent techniquement pour votre binôme car les deux filières sont indissociables dans ce contexte.

**Application Web (React + Laravel)**

- Dashboard caissier : ouverture/fermeture de session par poste
- Timer en temps réel par poste (minutage automatique)
- Calcul automatique du montant à payer selon la durée
- Caisse du jour : recettes, nombre de clients, heures de pointe
- Gestion des abonnements clients (forfaits heure/semaine/mois)
- Rapports journaliers et export PDF/Excel

**Infrastructure Réseau (Packet Tracer)**

- Topologie du cybercafé : postes clients, poste caissier, routeur, switch
- Séparation réseau clients / réseau caissier (VLAN)
- DHCP pour les postes clients
- Simulation d'un portail captif (accès conditionné à une session active)
- Filtrage de contenu (ACL pour bloquer certains sites)
- Connexion au FAI et gestion de la bande passante 

**Rendu final**

Application de gestion fonctionnelle + réseau Packet Tracer du cybercafé + rapport commun + présentation de la démo complète