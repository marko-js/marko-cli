<h1 align="center">
  <!-- Logo -->
  <br/>
  @marko/serve
	<br/>

  <!-- Stability -->
  <a href="https://nodejs.org/api/documentation.html#documentation_stability_index">
    <img src="https://img.shields.io/badge/stability-stable-green.svg" alt="API Stability"/>
  </a>
  <!-- NPM Version -->
  <a href="https://npmjs.org/package/@marko/serve">
    <img src="https://img.shields.io/npm/v/@marko/serve.svg" alt="NPM Version"/>
  </a>
  <!-- Downloads -->
  <a href="https://npmjs.org/package/@marko/serve">
    <img src="https://img.shields.io/npm/dm/@marko/serve.svg" alt="Downloads"/>
  </a>
</h1>

Utility to serve a Marko file

# CLI

## Installation

```terminal
npm install marko-cli
```

## Example

```terminal
marko serve ./page.marko
marko serve ./components/my-component.marko
```

## Options

- `--file -f *`: The marko file to serve
- `--port -p`: The port to serve on
- `--no-browser`: Don't automatically open the browser
- `--verbose`: Show the raw build output
- [node arguments](https://nodejs.org/api/cli.html) are passed to the server process

# API

Do not use the `@marko/serve` package directly. A programatic API is coming soon.