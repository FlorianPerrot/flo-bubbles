# FLO-BUBBLES

flo-bubbles est un element polymer qui anime ses enfants avec un effet de rotation.

**Flo-bubbles en action**

demo: http://site-labs.florian-perrot.fr/demo/flo-bubbles.html

## Attributs disponibles

- **startDeg:** Integer - deg pour lequel l'animation commence, par défault 0
- **nbSteps:** Integer - Nombre d'étape entre chaque enfant, par défault 0
- **duration:** Integer - Durée de l'animation en seconde (cf: animation-duration)
- **direction:** normal|revert - Direction de l'animation (cf: animation-direction)
- **chronological:** normal|revert - Normal étant le sens des aiguilles d'une montre, par défault normal
- **elevation:** Boolean - Active l'effet d'élévation lors de l'animation
- **animate:** Boolean - A chaque fois que cet attribute est ajouté a l'element l'animation se lance
- **responsive-width & responsive-height:** Integer - Resolution pour laquelle le composant doit etre desactive