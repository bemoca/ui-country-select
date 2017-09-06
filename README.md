# Contentful Country Select UI Extension

A country language code select as [Contentful UI Extension](https://www.contentful.com/developers/docs/concepts/uiextensions/).

![figure](https://raw.githubusercontent.com/contentful-developer-relations/ui-country-select/master/demo.gif "Country select Contentful UI Extension demo")

## Installation

```sh
git clone git@github.com:contentful-developer-relations/ui-country-select.git
cd ui-country-select
npm install
```

### Configure

Create a configuration file with your credentials for Contentful.

```sh
cp env.example .env
```

Open `.env` in a editor of your liking and add your Contentful space ID, and management token. [Learn how to obtain a token](https://www.contentful.com/developers/docs/references/authentication/#getting-an-oauth-token).

Load environment variables

```sh
source .env
```

### Create

```sh
npm run create
```

Create task will register the extension in your space on Contentful.

### Update

```sh
npm run update
```

Update task will upload the extension to your space on Contentful.

## License

Copyright &copy; Contentful Developer Relations

Licensed under the [MIT license](https://github.com/contentful/developer-relations/ui-country-select/blob/master/LICENSE).