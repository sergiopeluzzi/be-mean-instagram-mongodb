# MongoDB - Aula 01 - Exercício
autor: Sergio Peluzzi


## Importando restaurantes

```
$ mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
2016-06-10T16:12:36.560-0400    connected to: localhost
2016-06-10T16:12:36.561-0400    dropping: be-mean.restaurantes
2016-06-10T16:12:38.609-0400    imported 25359 documents

```

## Coontando restaurantes

```
db.restaurantes.find({}).count()
25359
```