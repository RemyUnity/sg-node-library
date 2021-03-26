Split Material Data Vertex

![](split-material-data-vertex.png)

Décompose les données des sommets de maillage d'un matériel depuis un connexion unique.

| ![](material-data-vertex-flow-sample.png)      |
| ---------------------------------------------- |
| Exemple de flux d'utilisation du material data |

| ![](material-data-vertex-flow-sample-result.png) |
| ------------------------------------------------ |
| Résultat                                         |

Entrées

|                      |                                                              |
| -------------------- | ------------------------------------------------------------ |
| Material Data VERTEX | *Matrix 3x3*: Connexion unique contenant toutes les informations des sommets de maillage |

Sorties

|                 |                      |
| --------------- | -------------------- |
| Vertex Position | *Vector 3*: Position |
| Vertex Normal   | *Vector 3*: Normale  |
| Vertex Tangent  | *Vector 3*: Tangente |

