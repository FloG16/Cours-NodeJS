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





-- WIKIPEDIA --

Node.js est une plateforme logicielle libre en JavaScript, orientée vers les applications réseau événementielles hautement concurrentes qui doivent pouvoir monter en charge.

Elle utilise la machine virtuelle V8, la librairie libuv pour sa boucle d'évènements, et implémente sous licence MIT les spécifications CommonJS.

Parmi les modules natifs de Node.js, on retrouve http qui permet le développement de serveur HTTP. Il est donc possible de se passer de serveurs web tels que Nginx 
ou Apache lors du déploiement de sites et d'applications web développés avec Node.js.

Concrètement, Node.js est un environnement bas niveau permettant l’exécution de JavaScript côté serveur.

Node.js est utilisé notamment comme plateforme de serveur Web, elle est utilisée par Groupon3, Vivaldi, SAP4, LinkedIn5,6, Microsoft7,8, Yahoo!9, Walmart10, Rakuten, Sage et PayPal11,12. 
