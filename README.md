# Portuguese Translations for React Admin v3

Portuguese translations for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST services.

## Installation

```sh
yarn add ra3-language-portuguese
```

## Usage

```js
import portugueseMessages from 'ra3-language-portuguese'
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'pt-br': portugueseMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="pt-br" i18nProvider={i18nProvider}>
  ...
</Admin>
```

This project was forked and adapted from original's [aor-language-portugues](https://github.com/movibe/aor-language-portugues) project
## License
This translation is licensed under the [MIT Licence](LICENSE)