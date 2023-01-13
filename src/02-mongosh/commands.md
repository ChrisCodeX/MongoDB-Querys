## Connect to container
```sh
docker-compose exec mongodb bash
```

## Connect with mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

## Commands in mongosh
```sh
show dbs
show collections
```
```
use("my_store")
db.products.find()
```
