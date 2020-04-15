# degrees

## Project setup
```shell
#restart your terminal after this command completes
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
nvm install $(cat .nvmrc)
```

### Configure Security Settings

1. Open __src > shared > config.js__
2. Replace "enter-value-here" with values from your Okta developer console:

```
// The Issuer URI from your Okta API Authorization Servers:
export const OAUTH_ISSUER = 'enter-value-here';

// From your Okta applications list, or on the "General" tab of a specific application:
export const CLIENT_ID = 'enter-value-here';
```

### Compiles and hot-reloads for development
```shell
npm run serve
```

### Compiles and minifies for production
```shell
npm run build
```

### Lints and fixes files
```shell
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
