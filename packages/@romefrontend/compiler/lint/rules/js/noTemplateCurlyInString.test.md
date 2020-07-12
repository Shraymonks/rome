# `noTemplateCurlyInString.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/compiler/lint/rules/js/noTemplateCurlyInString.test.ts --update-snapshots` to update.

## `no template curly in string`

### `0`

```

 unknown:2:18 lint/js/noTemplateCurlyInString ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ This string contains an unexpected template string expression.

    1 │ const user = "Faustina";
  > 2 │ const helloUser = "Hello, \${user}!";
      │                   ^^^^^^^^^^^^^^^^^^

  ℹ Using template string expressions in regular strings is usually a typo.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
const user = "Faustina";
const helloUser = "Hello, ${user}!";

```