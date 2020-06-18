# API sous Node.js
Basé sur un fichier JSON, ce script en Express charge les données en mémoire et vous les mets à disposition.

## Script
- npm run start

## Usages
- url : localhost:9000

### Routes & méthodes
Les routes disponibles de l'API :

#### en GET :
- /api/peoples = pour lister les contacts
- /api/peoples/random = afficher un contact aléatoire
- /api/peoples/:id = afficher un contact précis
- /api/peoples/skill/:skill = lister les contact filtré sur un métier
#### en POST :
- /api/peoples = création d'un contact
#### en PUT :
- /api/peoples/:id = éditer un contact
#### en DELETE :
- /api/peoples/:id = suppression d'un contact