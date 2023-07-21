# Comando para conectarnos al (contenedor) servicio existente de Mongo con Docker
```docker-compose exec mongodb bash```

# Comando para conectarnos con mongosh
```mongosh "mongodb+srv://usuario:password@mongodb101.xcvopof.mongodb.net/test"```

# Comando para ver bases de datos disponibles
```show dbs```

# Comando para ver colecciones disponibles
```show collections```

# Comando para usar una BD especifica
```use(dbName)```

# Comando para usar una coleccion con Find
```db.collectionName.find()```


# Para conectarse a mongo atlas

## Para desconectarse de la base de datos local o cualquiera utilizan:
```.exit```
```exit()```
## Y luego vuelven a introducir el comando:
```mongosh "[ Atlas url]"```
