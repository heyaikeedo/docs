# Aikeedo Documentation

This documentation is built with Mintlify based on the [Mintlify Starter Kit](https://github.com/mintlify/starter-kit).

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of the documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Changes will be deployed to production automatically after pushing to the default branch.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
