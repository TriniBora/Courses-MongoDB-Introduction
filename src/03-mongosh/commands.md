## Connect to container
```sh
docker-compose exec mongodb bash
```

## Connect with mongosh (Atlas)
```sh
mongosh "mongodb+srv://<usuario>:<password>@mongodb101.fl2xhxr.mongodb.net/"
```

## Connect with mongosh (Local)
```sh
mongosh "mongodb://<usuario>:<password>@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

## Show databases
```sh
show dbs
```

## Show collections
```sh
show collections
```

## Use database
```sh
use(dbName)
```

## Find all documents of a collection
```sh
db.collectionName.find()
```

## disconnect
```sh
.exit
```
```sh
exit()
```

