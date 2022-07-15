<p align="center">
  <a href="https://cdn.itwcreativeworks.com/assets/sniips/images/logo/sniips-brandmark-black-x.svg">
    <img src="https://cdn.itwcreativeworks.com/assets/sniips/images/logo/sniips-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/sniips/sniips.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/sniips.svg">
  <img src="https://img.shields.io/bundlephobia/min/sniips.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/sniips/sniips.svg">
  <img src="https://img.shields.io/npm/dm/sniips.svg">
  <img src="https://img.shields.io/node/v/sniips.svg">
  <img src="https://img.shields.io/website/https/sniips.com.svg">
  <img src="https://img.shields.io/github/license/sniips/sniips.svg">
  <img src="https://img.shields.io/github/contributors/sniips/sniips.svg">
  <img src="https://img.shields.io/github/last-commit/sniips/sniips.svg">
  <br>
  <br>
  <a href="https://sniips.com">Site</a> | <a href="https://www.npmjs.com/package/sniips">NPM Module</a> | <a href="https://github.com/sniips/sniips">GitHub Repo</a>
  <br>
  <br>
  <strong>sniips</strong> is the official npm module of <a href="https://sniips.com">Sniips</a>, a free app for creating custom text snippets that you can access on all of your devices!
</p>

## Sniips Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## Features
* Getting proxy lists

### Getting an API key
You can use so much of `sniips` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a Sniips account](https://sniips.com/authentication/signup).

## Install Sniips
### Install via npm
Install with npm if you plan to use `sniips` in a Node project or in the browser.
```shell
npm install sniips
```
If you plan to use `sniips` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const sniips = new (require('sniips'))({
  // Not required, but having one removes limits (get your key at https://sniips.com).
  apiKey: 'api_test_key'
});
```

### Install via CDN
Install with CDN if you plan to use Sniips only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/sniips@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var sniips = new Sniips({
    // Not required, but having one removes limits (get your key at https://sniips.com).
    apiKey: 'api_test_Key'
  });
</script>
```

### Use without installation
You can use `sniips` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## Using Sniips
After you have followed the install step, you can start using `sniips` to create custom text snippets that you can access on all of your devices

For a more in-depth documentation of this library and the Sniips service, please visit the official Sniips website.

## Use without installation
### Use Sniips with `curl`
```shell
# Standard
curl -X POST https://api.sniips.com
```

## What Can Sniips do?
Sniips is a free text snippet manager that lets you [create custom text snippets](https://sniips.com) that you can access on all of your devices!

## Final Words
If you are still having difficulty, we would love for you to post
a question to [the Sniips issues page](https://github.com/sniips/sniips/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
