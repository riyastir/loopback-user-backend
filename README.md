### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### Mongo Configuration
edit this file /src/datasources/mongodb.datasource.config.json
```
{
  "name": "mongodb",
  "connector": "mongodb",
  "url": "mongodb://admin:password@localhost:27017/users",
  "host": "localhost",
  "port": 27017,
  "user": "admin",
  "password": "password",
  "database": "users",
  "useNewUrlParser": true
}
```
