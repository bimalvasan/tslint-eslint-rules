<!-- Start:AutoDoc:: Modify `src/readme/rules.ts` and run `gulp readme` to update block -->
## no-multi-spaces (ESLint: [no-multi-spaces](http://eslint.org/docs/rules/no-multi-spaces))

disallow use of multiple spaces

### Usage

```json
"no-multi-spaces": [
    true,
    {
      "exceptions": { "PropertyAssignment": false, "OtherException": "true|false" }
    }
  ]
```

<!-- End:AutoDoc -->

### Note

The following are the exceptions available and their defaults

- `VariableDeclaration: false`
- `PropertyAssignment: true`
- `BinaryExpression: false`
