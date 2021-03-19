Custom Dither

![Custom Dither](custom-dither.png)

Génère un tramage depuis une valeur d'entrée et un motif.

| ![Custom Dither Sample](custom-dither-sample.png)            |
| :----------------------------------------------------------- |
| haut: valeur d'entrée, bas: tramage avec un motif de bruit bleu |





Entrées

|                |                                                              |
| -------------- | ------------------------------------------------------------ |
| In             | *Float*: Valeur d'entrée                                     |
| Dither Pattern | *Texture Object*: Texture de tramage (canal rouge)           |
| Use Custom UV  | *Bool*: Utiliser ou non des coordonées UV personalisées pour appliquer le tramage (coordonées par défaut : screen space) |
| Custom UV      | *Vector2*: Coordonées de tramage personalisées               |

Sorties

|          |                           |
| -------- | ------------------------- |
| Out      | *Float*: Tramage          |
| Mask 0-1 | *Bool*: Masque du tramage |

