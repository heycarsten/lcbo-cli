# lcbo-cli

:warning: WIP :warning:

A command-line interface for interacting with LCBO API in every possible way.

## Usage

Install via NPM:

```bash
npm i -g lcbo-cli
```

Get a store:

```bash
lcbo get-store 511

{
  "name": "King & Spadina",
  "
```

Change output format:

```bash
lcbo get-products -q 'peller estates' -f csv > peller-estates-products.csv
```

You get the idea.
