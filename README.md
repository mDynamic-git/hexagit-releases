# Hexagit Desktop — versions

Paquets d'**Hexagit Desktop** (Massive Dynamic) pour Windows, macOS et Linux, et flux de mise à jour automatique.

- Versions : onglet *Releases*. Les versions « bêta » (préliminaires) précèdent la recette.
- `appcast.xml` : flux lu par Hexagit Desktop pour proposer les mises à jour. Il est signé (Ed25519,
  `appcast.xml.signature`), et chaque paquet l'est aussi. Hexagit refuse un flux ou un paquet dont la signature ne
  correspond pas.

Ce dépôt ne contient que les paquets publiés par l'intégration continue. Le code d'Hexagit n'est pas ici.
