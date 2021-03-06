[![Codacy Badge](https://app.codacy.com/project/badge/Grade/45cb0bd1447d4158942191c7a7e8e05f)](https://www.codacy.com/gh/dnb-hugo/textlint-config/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=dnb-hugo/textlint-config&amp;utm_campaign=Badge_Grade)

## DNB-Hugo / textlint-config

This is a textlint preset used across David's Neighbour's (DNB) projects.

You probably won’t need this ;)

### Installation

```shell script
npm install -D dnb-hugo/textlint-config-dnb
```

### Configuration

Put the following into `.textlintrc.js` in the root of your project.

```js
const defaultTextlintConfig = require('@dnb-hugo/textlint-config-dnb');
module.exports = defaultTextlintConfig;
```

### All configuration packages

| Package | Notes |
|---|---|
| [browserslist-config](https://github.com/dnb-hugo/browserslist-config) | [Browserslist](https://github.com/browserslist/browserslist) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
| [commitlint-config](https://github.com/dnb-hugo/commitlint-config) | [Commitlint](https://github.com/conventional-changelog/commitlint) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
| [eslint-config](https://github.com/dnb-hugo/eslint-config) | [ESLint](https://github.com/eslint/eslint) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
| [remark-config](https://github.com/dnb-hugo/remark-config) | [Remark](https://github.com/remarkjs/remark-lint) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
| [standard-version-config](https://github.com/dnb-hugo/standard-version-config) | [Standard Version](https://github.com/conventional-changelog/standard-version) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
| [stylelint-config](https://github.com/dnb-hugo/stylelint-config) | [Stylelint](https://github.com/stylelint/stylelint) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
| [textlint-config](https://github.com/dnb-hugo/textlint-config) | [Textlint](https://github.com/textlint/textlint) configuration used in [dnb-hugo](https://github.com/dnb-hugo) projects. |
