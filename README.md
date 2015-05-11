# Lobbyradar Dumps

Täglich aktualisierte Dumps der Datenbank von [ZDF Lobbyradar](https://www.lobbyradar.de/)

## Import

```
git clone https://github.com/lobbyradar/dumps.git
mongorestore --db lobbyradar --collection entities dumps/entities.bson
mongorestore --db lobbyradar --collection relations dumps/relations.bson
```

## Lizenz

Veröffentlich unter der [Open Data Commons Attribution License (ODC-By) v1.0](http://opendatacommons.org/licenses/by/1.0/).
