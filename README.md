![alt text](https://github.com/Benriez/caprover-quasar/blob/master/quasar_app.png?raw=true)

# Quasar App + Caprover Template

A Quasar Framework app

## Install the dependencies
```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
npm run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://v2.quasar.dev/quasar-cli/quasar-conf-js).


# Build .tar file
```bash
tar -cvf ./deploy.tar --exclude='*.map' ./captain-definition ./dist/spa/*
```



# Deploy with Caprover
```bash
caprover deploy -t ./deploy.tar
```

See [caprover deploy app](https://caprover.com/docs/recipe-deploy-create-react-app.html).

