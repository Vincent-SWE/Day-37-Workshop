## Day-37-Workshop

## Server side

### Windows
```
set DO_STORAGE_KEY=
set DO_STORAGE_SECRETKEY=
set DO_STORAGE_ENDPOINT=sgpl.digitaloceanspaces.com
set DO_STORAGE_ENDPOINT_REGION=sgp1
```

```
mvn clean spring-boot:run
```

## Client side
ng serve --proxy-config proxy-config.js


### Railway Deployment
```
ng build
```

copy all the files on the dist folder to the server static folder

