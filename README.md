# SANKHÉ TRANSFERT — espace de publication des mises à jour

Ce dépôt héberge les métadonnées et les paquets de mise à jour Windows de SANKHÉ TRANSFERT.

## Structure
- `releases/latest.json` : manifeste consulté par le logiciel.
- `docs/RELEASE-CHECKLIST.md` : contrôles obligatoires avant publication.
- `README.md` : instructions générales.

## Important
Le manifeste initial est désactivé. Il ne signale aucune mise à jour tant qu'un paquet Windows réel n'a pas été compilé, testé et publié.

Ne publiez jamais :
- une base SQLite réelle ou une sauvegarde client ;
- des jetons WhatsApp, mots de passe ou autres secrets ;
- un paquet qui n'a pas été testé sur une copie de la base.

Un hash SHA-256 permet de vérifier l'intégrité du téléchargement, mais ne suffit pas à prouver l'identité de l'éditeur. Avant l'activation en production, le programme de mise à jour devra aussi vérifier une signature numérique ou une autre preuve d'authenticité forte.
