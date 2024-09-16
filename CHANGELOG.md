# CHANGELOG

## _2.0.0_

-   **BREAKING**: Removed `"pluginSearchDirs": ["."]` in svelte parsing to [make it more friendly](https://github.com/sveltejs/prettier-plugin-svelte?tab=readme-ov-file#setup) with Prettier 3. This gets rid of this warning when using prettier 3:

```
[warn] Ignored unknown option { pluginSearchDirs: ["."] }
```

> Note that if you are using Prettier 2, please use version 1 of this prettier-config package.

## _1.0.2_

-   Added `"parser": "svelte"` for parsing svelte files

## _1.0.1_

-   Use `overrides` for svelte parsing

## _1.0.0_ Initial release.
