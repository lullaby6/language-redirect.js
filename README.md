# language-redirect.js

A lightweight and easy-to-use js library to redirection for support differents languages

## Installation

### CDN

Include this tag in your html ```head```

```html
<script src='https://cdn.jsdelivr.net/gh/lullaby6/language-redirect.js/language-redirect.cdn.js'></script>
```

or <a href="https://cdn.jsdelivr.net/gh/lullaby6/language-redirect.js/language-redirect.cdn.js" target="_blank">Download</a>

## Usage

### in HTML

In your script tag you can use the ```data-language-redirect``` attribute for config the redirects easly

```html
<script
    src='https://cdn.jsdelivr.net/gh/lullaby6/language-redirect.js/language-redirect.cdn.js'
    data-language-redirect='{ "es": "/es/about.html" }'
></script>
```

### in JavaScript

Also you can use the ```languageRedirect``` function to config the redirects via JavaScript

```js
languageRedirect({
    es: '/es/index.html'
});
```