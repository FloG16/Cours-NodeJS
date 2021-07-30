# Cours-NodeJS

-- Installer NodeJS

Aller à l'adresse suivante: 
https://nodejs.org/en/
et suivre les instructions.


-- Executer un programme NodeJS

node nom_du_fichier.js


-- Documentation NodeJS

//Site officiel:
https://nodejs.org/en/docs/

//Devdocs:
http://devdocs.io


-- Le gestionnaire de dépendances

//Créer un fichier "package.json" et inclure le contenu suivant:
{
    "name": "monAppli",
    "version": "0.1.0",
    "dependencies": {
        "monmodule": "~0.4"
    }
}
//Les dépendances seront automatiquement mises à jour 
//tant qu'elles sont inférieures à 1.0.0


-- Le gestionnaire de dépendances (création automatique)

//Pour créer le fichier de gestion des dépendances () de manière automatique
//Taper cette commande dans le terminal:
npm init
//Répondre ensuite aux questions sur la configuration du projet
