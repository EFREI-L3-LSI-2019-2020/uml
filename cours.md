# Introduction au modèle en V

## Approche de développement logiciel

- Approche systèmique
  - Séparer les données de traitement
    - 3 niveaux d'abstractions
      - Conceptuel
      - Logique
      - Physique
- Approche itérative (objet)

Cahier des charges -> Analyse -> Modèle conceptuel

- Diagramme de classe unifié *(Approche objet)*
- MCD + MCT *(Approche systémique)*

Modèle conceptuel -> Conception -> Modèle logique

- Diagramme de classe complet
- MLD + MOT *(Merise)*
  
Modèle logique -> Implémentation -> Modèle physique

- Code source
- *(Merise)*
  - MPD
  - MPT

Modèle physique -> Qualification

- Tests unitaires
- Tests d'intégrations

Tests -> Recette -> Serveur de recette -> Mise en production -> Serveur de production -> Maintenance -> Corrections -> Itérations / Incrémentation

## Analyse du cahier des charges

1. Glossaire
2. Modèle de cas d'utilisation
   - Use case *(Quoi ?)*
     - Inclusion
     - Extension
     - Généralisation / Spécialisation
   - Actors *(Qui ?)*
     - Lien communication
     - Lien généralisation / spécialisation
   - Lien Actors / Use case
     - Unidirectionnel
     - Bidirectionnel

Analyse des cas d'utilisations :

- Description textuelle
- Identifier les types de classes participantes :
  - Boundry class : Interface : Package view
  - Control class : Controle : Package Entity
  - Entity class : Entity : Model
- Diagrammes d'interaction :
  - Diagramme de séquence
  - Diagramme de communication
- Diagramme de classe : Description de la structure du système