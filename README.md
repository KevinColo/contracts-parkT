# ParkT
***Un système de reservation de parking intelligent décentralisé réalisé avec Truffle et Solidity***


## Tools Required:

Avant de cloner le repository, assurez-vous d'avoir installé :

* Solidity
* Ganache
* Truffle
* Node Package Manager
* Node.js
* MetaMask

## Fonctionnalitées (init):
1    - Propriétaire de Parking enregistre un parking slot (ID 1, adresse, disponibilté, commodité)
     - Parking ID-1 disponible

2    - Conducteur reserve 1 parking (transaction => validée)
     - Parking ID-1 indisponible

3    - Conducteur libère la place de Parking
     - Mise à jour de la réputation du Parking
     - Mise à jour de la réputation du Conducteur
     - Mise à jour de la disponibilité de la place (IOT + réservé ou non reservé)

## Running the dapp:

Une fois le repo cloné :
	
	npm install

Pour installer les dépendances.

Ensuite, déplacez-vous dans le répertoire client. Dans votre terminal/ligne de commande, exécutez :

	truffle test
	
To be continue ...
