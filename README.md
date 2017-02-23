# Russian Translations for Admin-on-rest

Russian translations for [admin-on-rest](https://github.com/marmelab/admin-on-rest), the frontend framework for building admin applications on top of REST services.

## Installation

```sh
npm install --save aor-language-russian
```

## Usage

```js
import russianMessages from 'aor-language-russian';

const messages = {
    'ru': russianMessages,
};

<Admin locale="ru" messages={messages}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE.md).