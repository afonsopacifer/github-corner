# &lt;github-corner&gt;

[![Dependency Status](https://www.versioneye.com/user/projects/575910ef7757a0004a1de85d/badge.svg?style=flat)](https://www.versioneye.com/user/projects/575910ef7757a0004a1de85d)

> :octocat: A Polymer element for github corner.


## Demo

[Check it live!](http://afonsopacifer.github.io/github-corner/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install github-corner/github-corner --save
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/github-corner/github-corner.html">
```

3. Start using it!

```html
<github-corner></github-corner>
```

## Attributes

Attribute  | Type        | Default             | Description
---        | ---         | ---                 | ---
`color` | *String*   | `#fff`             | Sets the corner color.
`fill`   | *String*    | `#000`    | Sets the octocat color.
`url`     | *String*    | `#`   | Defines the destination url.

**Example:**

```html
<github-corner fill="#92e600" color="#fff" url="my-url"></github-corner>
```

## Development

1. Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
$ [sudo] npm install -g bower polymer-cli
```

2. Install local dependencies:

```sh
$ bower install
```

3. Start the development server on http://localhost:8080/:

```sh
$ polyserve
```

**View docs:**<br>
http://localhost:8080/components/github-corner/

**View demo:**<br>
http://localhost:8080/components/github-corner/demo/

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing
Find on our [issues](https://github.com/afonsopacifer/github-corner/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/afonsopacifer/github-corner/blob/master/CONTRIBUTING.md).

## History
See [Releases](https://github.com/afonsopacifer/github-corner/releases) for detailed changelog.

## License
[MIT License](https://github.com/afonsopacifer/github-corner/blob/master/LICENSE.md) © [Afonso Pacifer](http://afonsopacifer.com/)
