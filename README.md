<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Execute in development

1. Clone the repository
2. Execute
```
yarn install
```
3. Have installed Nest CLI
```
npm i -g @nestjs/cli
```

4. Raise the DB
```
docker-compose up -d

```
5. Clone the file ```.env.template``` and rename the copy to ```.env```

6. Fill the envrionment variables defined in ```.env```

7. Start the app in development
```
nest start --watch
``` 
8. Rebuild the DB with the data of the seed
```
http://localhost:3000/api/v2/seed
```

## Stack used
* MongoDB
* Nest