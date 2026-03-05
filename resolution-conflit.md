# Processus de résolution du conflit d'évolution hybride
1. Création d'une branche `feature` et modification de la ligne 1 du [README.md](cci:7://file:///home/arkansky/Documents/14_ValorisationDonneeMeteo/README.md:0:0-0:0).
2. Retour sur la branche `main` et modification différente de la ligne 1 du [README.md](cci:7://file:///home/arkansky/Documents/14_ValorisationDonneeMeteo/README.md:0:0-0:0).
3. Lancement de `git merge feature` depuis `main`, causant un "Merge conflict".
4. Ouverture de [README.md](cci:7://file:///home/arkansky/Documents/14_ValorisationDonneeMeteo/README.md:0:0-0:0), suppression manuelle des balises de conflit (`<<<<<<<`, `=======`, `>>>>>>>`).
5. Choix de la chaîne finale indiquant un conflit résolu.
6. Validation par un `git add README.md` suivi d'un `git commit -S` de merge.
