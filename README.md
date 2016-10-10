# FLO-BUBBLES

flo-bubbles est un element polymer qui d'animter ses enfants avec un effet de rotation.

**Flo-bubbles en action**

Animation en cours :
![roration_pending](/uploads/3b638672bd23e37a96426e644a69f717/roration_pending.png)

Animation fini:
![rotation_fini](/uploads/d2c144d978b0256a31c8cab5f705500f/rotation_fini.png)

## Attributes disponibles

- **startDeg:** Integer - deg pour lequel l'animation commence, par défault 0
- **nbSteps:** Integer - Nombre d'étape entre chaque enfant, par défault 0
- **duration:** Integer - Durée de l'animation en seconde (cf: animation-duration)
- **direction:** normal|revert - Direction de l'animation (cf: animation-direction)
- **chronological:** normal|revert - Normal étant le sens des aiguilles d'une montre, par défault normal
- **elevation:** Boolean - Active l'effet d'élévation lors de l'animation
- **animate:** Boolean - A chaque fois que cet attribute est ajouté a l'element l'animation se lance