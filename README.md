# TP de méthodes variationnelles (IMA203)

Le but du TP est d’explorer les méthodes variationnelles pour la restauration des images. On rappelle que les méthodes variationnelles consistent à trouver une image de bonne qualité à partir de données dégradées. Pour cela, on exprime l’image de bonne qualité comme celle qui minimise une énergie (parfois appelée "fonctionnelle") souvent constituée de deux termes. Un terme d’attache aux données qui exprime le fait que l’image reconstruite doit bien expliquer l’observation. L’autre terme est dit "de régularité" et il permet d’introduire une connaissance a priori sur les images. Essentiellement, il s’agit d’exprimer le fait que les images naturelles varient peu si on les compare au bruit.

Dans une première partie nous nous attacherons à étudier l’influence des différents termes d’attache aux données et de régularité sur le résultat d’une restauration variationnelle. La recherche du bon compromis passe par ce que l’on appelle "paramètre de régularisation". Pour cette première étude nous utiliserons comme énergie de régularité, une énergie quadratique.

Dans la seconde partie, nous introduisons une énergie appelée variation totale, qui bien que très proche de l’énergie quadratique, donne de meilleurs résultats. Cependant, nous verrons que sa minimisation d’un point de vue numérique pose certains problèmes. Et nous donnerons une méthode adaptées à cette énergie de régularité dans le cas du débruitage (méthode de projection de Chambolle).

Enfin, vous comparerez qualitativement les deux approches.
