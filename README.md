
le menu de navigation

Code
Demandes de tirage
Actions
Feuille de route publique GitHub

Licence
 Licence CC-BY-4.0
 0 étoiles
 926 fourchettes
 0 je regarde
 2 succursales
 0 balises
 Activité
Dépôt public · Forked de github/roadmap
baron1145/feuille de route
Cette branche est à jour avecgithub/feuille de route : principal.
Dossiers et fichiers
Nom	
Dernier commit
michellemerrill
michellemerrill
l'année dernière
Histoire
.github/ ISSUE_TEMPLATE
il y a 3 ans
CODE_OF_CONDUCT.md
il y a 4 ans
LICENCE
il y a 4 ans
LISEZMOI.md
l'année dernière
SÉCURITÉ.md
il y a 4 ans
Navigation dans les fichiers du référentiel
LISEZMOI
Code de conduite
Feuille de route publique GitHub
❇️ Consultez la feuille de route officielle du produit public GitHub 1

Notre feuille de route produit vous permet d'en savoir plus sur les fonctionnalités sur lesquelles nous travaillons, à quel stade elles se trouvent et quand nous prévoyons de vous les proposer. Vous avez des questions ou des commentaires sur les éléments de la feuille de route ? Partagez vos commentaires via les discussions de commentaires publics sur GitHub .

Le référentiel de feuille de route sert à communiquer la feuille de route de GitHub. Les problèmes existants sont actuellement en lecture seule et nous verrouillons les conversations au fur et à mesure que nous commençons. Des limites d'interaction sont également en place pour garantir que les problèmes proviennent de GitHub. Nous prévoyons de modifier le format de la feuille de route elle-même et nous voyons la possibilité de nous engager davantage dans des discussions sur l'avenir des produits et fonctionnalités de GitHub. Si vous avez des commentaires sur ce référentiel de feuilles de route lui-même, par exemple sur la façon dont les problèmes sont présentés, faites-le-nous savoir via des commentaires généraux dans les discussions de commentaires publics sur GitHub .

Guide de la feuille de route
Chaque élément de la feuille de route est un problème, avec une étiquette qui indique chacun des éléments suivants :

Une phase de publication qui décrit la prochaine phase attendue de l'élément de feuille de route. Voir ci-dessous pour un guide des phases de publication.

Une zone de fonctionnalités qui indique la zone du produit à laquelle appartient l'article. Pour une liste des domaines de produits actuels, voir ci-dessous.

Caractéristique qui indique la fonctionnalité ou le produit auquel appartient l'élément. Pour une liste des fonctionnalités actuelles, voir ci-dessous.

Une ou plusieurs étiquettes de SKU de produit indiquant dans quels SKU de produit nous prévoyons que la fonctionnalité soit disponible. Pour une liste des SKU de produits actuels, voir ci-dessous.

Un ou plusieurs modèles de déploiement (cloud, serveur et/ou ae). Sauf indication contraire, les fonctionnalités seront généralement disponibles dans le Cloud en premier, puis sur le serveur et le GHAE au moment ou peu après GA.

Une fois qu'une fonctionnalité est livrée, l' étiquette expédiée sera appliquée au problème de la feuille de route et le problème sera clôturé avec un commentaire renvoyant vers la publication du journal des modifications concernée .

Phases de publication
Les phases de publication indiquent les étapes par lesquelles passe le produit ou la fonctionnalité, depuis les premiers tests jusqu'à la disponibilité générale.

alpha : principalement destiné aux tests et aux commentaires.
Disponibilité limitée, nécessite un accord préalable à la publication. Fonctionnalités encore en cours de développement et sujettes à changement. Pas destiné à une utilisation en production, et aucune documentation, SLA ou support n'est fourni.

version bêta : disponible publiquement en capacité complète ou limitée.
Fonctionnalités pour la plupart complètes et documentées. Calendrier et exigences pour l’AG généralement publiés. Aucun SLA ni support fourni.

ga : généralement disponible pour tous les clients.
Prêt pour une utilisation en production avec les obligations de SLA et de support technique associées. Environ 1 à 2 trimestres de la version bêta.

Certaines de nos fonctionnalités peuvent en être encore au stade exploratoire et n’avoir aucun délai disponible. Ceux-ci sont inclus dans la feuille de route uniquement pour les premiers commentaires. Ceux-ci sont marqués comme suit :

en conception :
fonctionnalité en phase de découverte. Nous avons décidé de créer cette fonctionnalité, mais nous cherchons encore comment .

exploration :
fonctionnalité à l’étude. Nous envisageons de créer cette fonctionnalité et de recueillir des commentaires à ce sujet.

Phases de sortie - Pour GHES
Certaines fonctionnalités peuvent être marquées d'une étiquette GHES 3.X, ce qui indique que la fonctionnalité sera également disponible pour les clients Github Enterprise Server. Vous trouverez ci-dessous les numéros de version et les trimestres de sortie attendus ( Remarque : ces dates sont susceptibles de changer ).

Dates de sortie des versions GHES :

Numéro de version	Trimestre de sortie	Notes de version
3.5	T2 2022	Notes de version
3.6	T3 2022	Notes de version
3.7	T4 2022	-
3.8	T1 2023	-
Étapes de la feuille de route
La feuille de route est disposée sur un tableau de projet pour donner une idée de l'étendue de chaque élément à l'horizon. Chaque produit ou fonctionnalité est ajouté à une colonne particulière du tableau de projet en fonction du trimestre au cours duquel il est prévu d'être expédié ensuite. Assurez-vous de lire la clause de non-responsabilité ci-dessous, car la feuille de route est susceptible de changer, en particulier plus loin dans la chronologie. Vous trouverez également une colonne exploratoire , qui est utilisée conjointement avec les étiquettes des phases de conception et d'exploration de la version lorsqu'aucun délai n'est encore disponible.

GitHub Enterprise Server propose des versions majeures sur une base trimestrielle et des versions mineures sur une base mensuelle. Une fois que nous saurons quelle version nous proposons une fonctionnalité, nous mettrons à jour le problème pour indiquer cette information.

Domaines de fonctionnalités
Voici une liste de nos domaines de produits actuels :

code : expériences de code (dépôts, demandes d'extraction, résumés)
planification : Outils de planification et de suivi (Problèmes, Projets)
code-to-cloud : DevOps code-to-cloud (actions, packages)
collaboration : fonctionnalités de collaboration (Pages, Wikis, Discussions)
sécurité et conformité : fonctionnalités de sécurité et de conformité du code
admin-server : fonctionnalités d'administration spécifiques à GitHub Enterprise Server
admin-cloud : fonctionnalités d'administration spécifiques à GitHub Cloud
communautés : fonctionnalités communautaires et sociales
écosystème : fonctionnalités de l'écosystème et de l'API
apprentissage : fonctionnalités d'éducation et d'apprentissage
insights : fonctionnalités d'apprentissage continu et d'insights
client-apps : applications client (ordinateur de bureau, mobile)
autre : autres fonctionnalités
Fonctionnalité
Voici une liste de nos fonctionnalités et produits actuels, avec des étiquettes distinctes pour le filtrage :

actions : actions GitHub
documents : Documents GitHub
paquets : paquets GitHub
pages : pages GitHub
D'autres étiquettes seront ajoutées à l'avenir si nécessaire.

SKU du produit
Voici une liste de nos SKU de produits actuels.

all : disponible pour tous les utilisateurs, y compris un niveau gratuit. Différents SKU peuvent avoir différents niveaux de fonctionnalités.
équipe github : équipe GitHub
github entreprise : GitHub Enterprise (Cloud et serveur)
github one : GitHub One (Cloud et serveur)
github AE : GitHub AE (GHAE)
Sécurité avancée de github : GitHub Advanced Security (module complémentaire de GHE)
github insights : GitHub Insights (module complémentaire à GHE)
Laboratoire d'apprentissage github : GitHub Learning Lab (module complémentaire à GHE)
Clause de non-responsabilité
Toute déclaration contenue dans ce référentiel qui n'est pas purement historique est considérée comme une déclaration prospective. Les déclarations prospectives incluses dans ce référentiel sont basées sur les informations dont dispose GitHub à la date à laquelle elles sont faites, et GitHub n'assume aucune obligation de mettre à jour les déclarations prospectives. La feuille de route prospective du produit ne représente pas un engagement, une garantie, une obligation ou une promesse de livrer un produit ou une fonctionnalité, ou de livrer un produit et une fonctionnalité à une date particulière, et est destinée à décrire les plans généraux de développement. Les clients ne doivent pas s’appuyer sur cette feuille de route pour prendre une décision d’achat.
