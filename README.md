# RolIA

Application de bureau pour meneurs de jeu (D&D 5e, Pathfinder 2e, L’Appel de Cthulhu 7e) : une équipe d’agents IA construit la campagne avec toi, répond aux questions de règles en citant tes livres, propose des suites à la table, dessine les plans et tient la chronologie. Tu valides chaque élément.

Ce dépôt ne contient que les installeurs publiés : télécharge la dernière version dans **[Releases](../../releases/latest)**. RolIA installé (Windows, Linux AppImage) y cherche lui-même ses mises à jour.

## Installer RolIA

**Windows** : télécharge `RolIA-…-win-x64.exe` et lance-le. L’installeur n’est pas signé : si Windows affiche « Windows a protégé votre ordinateur », clique « Informations complémentaires », puis « Exécuter quand même ».

**Linux** : `RolIA-…-linux-x86_64.AppImage` (conseillé, il se met à jour tout seul) : `chmod +x RolIA-*.AppImage`, puis lance-le (sur Ubuntu 24.04 et plus récent, installe `libfuse2t64` s’il ne démarre pas). Ou `RolIA-…-linux-amd64.deb` : `sudo apt install ./RolIA-*.deb`.

**macOS** : pas encore publié.

Ensuite : Réglages › Accès à l’IA, puis la rubrique **Guide** dans l’application.

## Documentation

Le **[wiki](../../wiki)** explique tout :

- [Installation](../../wiki/Installation) et [Premiers pas](../../wiki/Premiers-pas) ;
- la liste des [Fonctionnalités](../../wiki/Fonctionnalités) ;
- une page par rubrique : agents, propositions, canon, frise, personnages, cartes, mode table, images avec ComfyUI, connecteur Claude Desktop ;
- le [Dépannage](../../wiki/Dépannage) ;
- l’[Historique des versions](../../wiki/Historique-des-versions).
