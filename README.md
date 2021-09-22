# Compteur-Decompteur
Création d'un compteur décompteur en HDL.

L'objectif est de créer un compteur décompteur qui s'actionne à l'aide d'un bouton, qui passe d'un mode à l'autre grâce à un bouton Mode et qui peut être remis à 0 grâce à un bouton de remise à 0.
La valeur maximale du compteur est <strong>999</strong> et minimal <strong>0</strong>.
Lorsqu'une valeur limite est atteinte le compteur doit être bloqué et une led est allumé pour indiqué que le compteur est bloqué tant qu'il n'y a pas eu une remise à 0.
<br>
Le tout est affiché à l'utilisateur à l'aide de trois afficheur 7 segments.
<br><br>
<strong>Il faut donc avoir 2 boutons et un switch :</strong>
<ul><li>Btn qui permet d'incrémenter ou de décrémenter le compteur en fonction du mode</li>
  <li>SWHMode qui permet de changer de mode</li>
  <li>Btn0 qui permet de remettre le compteur à 0</li></ul>
<br>
<strong>Deux LED sont utilisées :</strong>
<ul><li>Indication sur le mode</li>
  <li>Indication sur le dépassement d'une limite</li></ul>

![image](https://user-images.githubusercontent.com/85016008/134306870-9b0f9aef-dbfe-4d34-b992-048537a01b3b.png)

