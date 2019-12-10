# Emmmail

**Emmmailjml** est un starter-kit qui aide à l'intégration d'emails responsifs.

Il est construit sur **[MJML](https://mjml.io/)**.

## Installation

```
git clone git@github.com:hellodeloo/emmmailjml.git
```

```
cd emmmail
yarn install
```

## Utilisation

**Renommez** `config-sample.js` en `config.js` puis **personnalisez** les variables de `folder`, `email`, `conn`, `smtp`.

**Développez** dans le dossier "src" et lancer la commande `yarn dev` qui se chargera de:

- Lancer le BrowserSync
- Optimiser les images
- Placer l'ensemble dans le répertoire "dist"

**Hébergez** sur ftp avec `yarn deploy`

**Envoyez** un email test avec `yarn send`

Puis **générez le livrable** zippé avec `yarn build`
