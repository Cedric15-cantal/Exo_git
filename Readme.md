# Exercices test

**Connaissace des outils Git et de la consultation web via GitHub**

*C'est un vrai début qui fait mal à la tête pour un lundi matin...*

Exemple d'inscription de ligne de commande bash:
```bash
osm2pgsql -c -r pbf -m -s -S /usr/share/osm2pgsql/default.style -C 5000 -d myosm -U postgres -H localhost -P 5432 -W /mnt/c/ms4w/tmp/auvergne-latest.osm.pbf
```
Exemple d'inscription de ligne de commande sql :
```sql
ALTER TABLE osm_polygon 
    ALTER COLUMN way TYPE geometry(polygon,3857) USING ST_SetSRID(way, 3857);
```

Exemple de liste :
* GitHub
* Gitlab

___
## Pour une pause bien méritée savourez un morceau de tomme de Salers, authentique et persillée...

![Tomme de Salers](.\170-Capture-salers.jpg)

[Pour en savoir plus](https://www.aop-salers.com/)