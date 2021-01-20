# admin-panel-server

Server application for [admin panel client](https://github.com/fsefidabi/admin-panel-client.git) which is built with strapi.

#### Quick Start:

Use below commands to start vue app on port `1337`.
```
git clone https://github.com/fsefidabi/admin-panel-server.git
npm i
npm run build
```
This server uses MongoDB as the database to store content. Ensure that mongo database is running as a 
background service on your system.
In case you don't have mongodb, you can install it [directly](https://docs.mongodb.com/manual/installation/) or run it as a [docker container](https://hub.docker.com/_/mongo).

After running mongodb in background, you can start server.
```
npm start
```

Application is running on `http://localhost:1337`

To use this admin panel you should also clone and run the [client side application](https://github.com/fsefidabi/admin-panel-client.git).
