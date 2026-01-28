# SchemaShift

TypeScript schema migration CLI. Convert between Zod, Yup, Joi, io-ts, and Valibot with AST-based transformations.

## Install

```bash
npm install -g schemashift-cli
```

## Usage

```bash
# Analyze schemas in your project
schemashift analyze ./src

# Migrate Yup to Zod
schemashift migrate ./src --from yup --to zod

# Preview changes first
schemashift migrate ./src --from yup --to zod --dry-run
```

## Links

- [Documentation](https://schemashift.qwady.app/docs)
- [npm](https://www.npmjs.com/package/schemashift)
- [Pricing](https://schemashift.qwady.app)

## License

MIT
