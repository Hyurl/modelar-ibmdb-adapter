# Modelar-Postgres-Adapter

**This is an adapter for [Modelar](http://modelar.hyurl.com) to connect**
**DB2 database.**

## How To Use

```javascript
const { DB } = require("modelar");
const IbmdbAdapter = require("./");

DB.setAdapter("ibmdb", IbmdbAdapter).init({
    type: "ibmdb",
    database: "SAMPLE",
    host: "127.0.0.1",
    port: 50000,
    user: "db2admin",
    password: "******"
});
```