## `@modernpoacher/data-type`

# Data Type

### Import `Collections`

```bash
mongoimport --collection=Collections --db=$DATABASE --file=collections.json --username=$USERNAME --password=$PASSWORD --authenticationDatabase=$AUTHENTICATION_DATABASE
```

### Import `Members`

```bash
mongoimport --collection=Members --db=$DATABASE --file=members.json --username=$USERNAME --password=$PASSWORD --authenticationDatabase=$AUTHENTICATION_DATABASE
```

### Import `Evaluations`

```bash
mongoimport --collection=Evaluations --db=$DATABASE --file=evaluations.json --username=$USERNAME --password=$PASSWORD --authenticationDatabase=$AUTHENTICATION_DATABASE
```

### Export `Collections`

```bash
mongoexport --collection=Collections --db=$DATABASE --out=collections.json --username=$USERNAME --password=$PASSWORD --authenticationDatabase=$AUTHENTICATION_DATABASE
```

### Export `Members`

```bash
mongoexport --collection=Members --db=$DATABASE --out=members.json --username=$USERNAME --password=$PASSWORD --authenticationDatabase=$AUTHENTICATION_DATABASE
```

### Export `Evaluations`

```bash
mongoexport --collection=Evaluations --db=$DATABASE --out=evaluations.json --username=$USERNAME --password=$PASSWORD --authenticationDatabase=$AUTHENTICATION_DATABASE
```
