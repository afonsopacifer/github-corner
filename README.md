# &lt;github-corner&gt;

> <:octocat:/> A Polymer 2.0 element for github corner.

[![Travis CI Status](https://travis-ci.org/afonsopacifer/github-corner.svg?branch=master)](https://travis-ci.org/afonsopacifer/github-corner)
[![bower](https://img.shields.io/bower/v/github-corner.svg)](https://www.npmjs.com/package/github-corner)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/afonsopacifer/github-corner)

## How to install and use

1 - Install the element using [Bower](http://bower.io/):

```sh
bower install github-corner --save
```

2 -  Import the element:

```html
<link rel="import" href="bower_components/github-corner/github-corner.html">
```

3 - Start using it!

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="github-corner.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<github-corner href="https://github.com/afonsopacifer/github-corner"></github-corner>
```

## Properties

Property  | Type        | Default   | Description
:---      |:---         |:---       |:---
`href`    | *String*    | `#`       | Hyperlink reference
`target`    | *String*    | `_blank`       | [Anchor tag target](https://www.w3schools.com/tags/att_a_target.asp)

## Styling

The following custom properties and mixins are available for styling:

Custom property             | Default  | Description
:---                        |:---      |:---
--github-corner-background | #24292E  | Background color
--github-corner-color  | #ffffff     | Octocats color
--github-corner-size        | 80px     | Badge size
--github-corner-z-index       | 1     | z-index

## Browser Support

Using the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs):

 ![Chrome](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/chrome/chrome_48x48.png) | ![Opera](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/opera/opera_48x48.png) | ![Firefox](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/firefox/firefox_48x48.png) | ![Safari](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/safari/safari_48x48.png) |![IE](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |  ![Edge](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/edge/edge_48x48.png) |
:---: | :---: | :---: | :---: | :---: | :---: |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | 11+ | Latest ✔

## Development

1 - Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
npm install -g bower polymer-cli
```

2 - Install local dependencies:

```sh
bower install
```

3 - Start the development server:

```sh
polymer serve --open
```

## Tests

### Linting

Linting with polylint:

```sh
polymer lint
```

Linting with eslint:

```sh
npm install -g eslint
npm install -g eslint-plugin-html

eslint *.html
```

### Unit tests

Run tests:

```sh
polymer test --skip-plugin sauce
```

**Quick tip**: To run the [selenium driver for safari](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-safari-driver), you need follow [some instructions](https://webkit.org/blog/6900/webdriver-support-in-safari-10/).

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [issues](https://github.com/afonsopacifer/github-corner/issues/) the next steps of the project ;)

Want to contribute? [Follow these recommendations](https://github.com/afonsopacifer/github-corner/blob/master/CONTRIBUTING.md).

## History

See [Releases](https://github.com/afonsopacifer/github-corner/releases) for detailed changelog.

## License

[MIT License](https://github.com/afonsopacifer/github-corner/blob/master/LICENSE.md) © [Afonso Pacifer](http://afonsopacifer.github.io/)
