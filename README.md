# loader-css
La propriété animation en CSS est utilisée pour définir une animation en liant une animation définie avec @keyframes à un élément spécifique. L'expression spin 1s linear infinite que vous avez vue dans l'exemple CSS signifie :

spin: C'est le nom de l'animation, correspondant au nom spécifié dans @keyframes.

1s: La durée de l'animation. Dans cet exemple, l'animation spin durera 1 seconde pour effectuer une rotation complète (360 degrés).

linear: La fonction de temporisation. Dans ce cas, la fonction de temporisation est linéaire, ce qui signifie que la vitesse de l'animation reste constante tout au long de son exécution.

infinite: Indique que l'animation doit se répéter indéfiniment.

Dans l'exemple complet que j'ai fourni, l'animation spin est définie avec @keyframes pour effectuer une rotation complète (de 0 à 360 degrés) à travers la propriété transform: rotate() à chaque étape. Lorsque vous appliquez cette animation à l'élément .loader, cela crée l'effet de rotation continue du loader.
