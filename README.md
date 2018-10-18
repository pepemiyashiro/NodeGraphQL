# Dependencies

```Bash
$ yarn add express graphql express-graphql sequelize sequelize-cli graphql-sequelize graphql-relay sqlite3
```

Generate Model
```Bash
$ sequelize model:generate --name User --attributes firstName:string,lastName:string,email:string
```

```
$ sequelize db:seed:all
```

```
sequelize seed:generate --name Users
```
