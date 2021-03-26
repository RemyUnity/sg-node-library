Split Material Data

![](split-material-data.png)

Sépare les données de surface d'un matériel depuis une connexion unique.

| ![](material-data-flow-sample.png)             |
| ---------------------------------------------- |
| Exemple de flux d'utilisation du material data |

| ![](material-data-flow-sample-result.png) |
| ----------------------------------------- |
| Résultat                                  |

Entrées

|               |                                                              |
| ------------- | ------------------------------------------------------------ |
| Material Data | *Matrix 4x4*: Connexion unique contenant les données d'un matériel |

Sorties

|            |                                      |
| ---------- | ------------------------------------ |
| BaseColor  | *Vector 3*: Couleur de base (Albedo) |
| Normal     | *Vector 3*: Normale                  |
| Emission   | *Vector 3*: Couleur d'émission       |
| Specular   | *Vector 3*: Couleur spéculaire       |
| Metallic   | *Float*: Valeur de métalléité [0;1]  |
| Smoothness | *Float*: Valeur de régularité [0;1]  |
| Occlusion  | *Float*: Valeur d'occlusion [0;1]    |
| Alpha      | *Float*: Valeur d'alpha [0;1]        |

