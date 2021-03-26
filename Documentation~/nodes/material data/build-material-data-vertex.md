Build Material Data Vertex

![](build-material-data-vertex.png)

Stocke les données des sommets de maillage d'un matériel dans un connexion unique.

| ![](material-data-vertex-flow-sample.png)      |
| ---------------------------------------------- |
| Exemple de flux d'utilisation du material data |

| ![](material-data-vertex-flow-sample-result.png) |
| ------------------------------------------------ |
| Résultat                                         |

Entrées

|                 |                      |
| --------------- | -------------------- |
| Vertex Position | *Vector 3*: Position |
| Vertex Normal   | *Vector 3*: Normale  |
| Vertex Tangent  | *Vector 3*: Tangente |

Sorties

|                      |                                                              |
| -------------------- | ------------------------------------------------------------ |
| Material Data VERTEX | *Matrix 3x3*: Connexion unique contenant toutes les informations en entrée |

