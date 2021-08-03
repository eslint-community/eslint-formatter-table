# eslint-formatter-table

> ESLint’s official `table` formatter, extracted from ESLint 7

This formatter has been removed from ESLint 8 so it lives as a standalone module here.

**Warning:** This module is not maintained. If you're an ESLint contributor or dependable open-sourcerer, open an issue here and I'll pass you this repo and npm name. You can also ping me on Twitter [@fregante](https://twitter.com/fregante)

## Install

```sh
npm install --save-dev eslint-formatter-table
```

## Usage

More information about formatters can be found on https://eslint.org/docs/user-guide/formatters/

```
eslint --format table
```

## Example output

```
/var/lib/jenkins/workspace/Releases/eslint Release/eslint/fullOfProblems.js

║ Line     │ Column   │ Type     │ Message                                                │ Rule ID              ║
╟──────────┼──────────┼──────────┼────────────────────────────────────────────────────────┼──────────────────────╢
║ 1        │ 10       │ error    │ 'addOne' is defined but never used.                    │ no-unused-vars       ║
║ 2        │ 9        │ error    │ Use the isNaN function to compare with NaN.            │ use-isnan            ║
║ 3        │ 16       │ error    │ Unexpected space before unary operator '++'.           │ space-unary-ops      ║
║ 3        │ 20       │ warning  │ Missing semicolon.                                     │ semi                 ║
║ 4        │ 12       │ warning  │ Unnecessary 'else' after 'return'.                     │ no-else-return       ║
║ 5        │ 1        │ warning  │ Expected indentation of 8 spaces but found 6.          │ indent               ║
║ 5        │ 7        │ error    │ Function 'addOne' expected a return value.             │ consistent-return    ║
║ 5        │ 13       │ warning  │ Missing semicolon.                                     │ semi                 ║
║ 7        │ 2        │ error    │ Unnecessary semicolon.                                 │ no-extra-semi        ║

╔════════════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║ 5 Errors                                                                                                       ║
╟────────────────────────────────────────────────────────────────────────────────────────────────────────────────╢
║ 4 Warnings                                                                                                     ║
╚════════════════════════════════════════════════════════════════════════════════════════════════════════════════╝
```

## Links

- [Other official ESLint formatters as standalone modules](https://github.com/fregante/eslint-formatters)

