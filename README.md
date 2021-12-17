![Gitflow](https://user-images.githubusercontent.com/50138085/146559960-97c44dc0-8a18-4fc1-a3ea-8f1500558edc.jpg)

## Caracteristique des Branches
### Branche principale
- [x] Master
- [x] Stage
- [x] Develope
### Branche temporaire
- [x] feat-emple
- [x] hotfix-emple
- [x] bugfix-emple
### Avant Pull Request
- Review du code par les autre developpeur
- Squash Merge
- Git CZ: Gestion du changelog
### Regle des commit
 ***Format**:* 
`Type: Sujet`
- feat: "*Ajout d'une nouvelle fonctionalité*"
- fix: "*Correction bug*"
- revert: "*Annulation de commit*"
- docs: "*Docummentation*"
- chore: "*Autre modification*"
#### Sujet
- Moin de 50 caractères
- Verbe imperatif: add, update, remove, change
### Methode de Merge Request
- [x] Methode rebase: approuvé
- [ ] Methode pull rebase et pull: non approuvé

### Detaille des branches
#### Principale

1. **Master:** *Contient le code du produit en production. Tout le code developpé dans d'autre branch seront integré dans Master afin qu'il puisse être publié dans la nouvelle version du produit.*
2. **Staging:** *Contient la même version que master. Les versions du produit en cours d'approbation (hotfix, bug, realese, feature) du code en cours de test peuvent être integrées dans master.*
3. **Develope:** Contient le code en cours de développement pour ce même produit et reste généralement en constante évolution et incrementation.
#### Temporaire
1. **Feature:** *Ce sont des branches créées à partir de la branch Develop pour développer une fonctionnalité spécifique.*
2. **Hotfix:** *Est créée lorsqu'un bug est trouvé dans le Master et doit être corrigé immédiatement.*
3. ***bugfix:*** *Est créée lorsqu'un bug est trouvé dans le Master, qui n'est pas urgent et peut être transfère dans la prochaine version*
**Remarque:**
*Les cycles de vie des branche se termione par la validation des fonctionnalités, des correctif des bug.*

![commiGitflow](https://user-images.githubusercontent.com/50138085/146573809-553bf6be-03df-479e-9511-e7415ca6b39e.jpg)

