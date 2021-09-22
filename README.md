# Compteur-Decompteur
Création d'un compteur décompteur en HDL.

L'objectif est de créer un compteur décompteur qui s'actionne à l'aide d'un bouton, qui passe d'un mode à l'autre grâce à un bouton Mode et qui peut être remis à 0 grâce à un bouton de remise à 0.
La valeur maximale du compteur est <strong>999</strong> et minimal <strong>0</strong>.
Lorsqu'une valeur limite est atteinte le compteur doit être bloqué et une led est allumé pour indiqué que le compteur est bloqué tant qu'il n'y a pas eu une remise à 0.
<br>
Le tout est affiché à l'utilisateur à l'aide de trois afficheur 7 segments.
<br><br>
<strong>Il faut donc avoir 3 boutons :</strong>
<ul><li>Btn qui permet d'incrémenter ou de décrémenter le compteur en fonction du mode</li>
  <li>BtnMode qui permet de changer de mode</li>
  <li>Btn0 qui permet de remettre le compteur à 0</li></ul>
![image](https://user-images.githubusercontent.com/85016008/134304252-c41dc0b6-5f1c-4c9f-b456-d62a3b166082.png)
