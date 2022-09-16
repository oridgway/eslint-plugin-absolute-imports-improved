# eslint-plugin-absolute-imports-improved

Based on eslint-plugin-absolute-imports with fixes for my specific system namely:
 - Fixes for windows backslashes.
 - Using double quotes rather than single quotes.
 - src paths start with an @ symbol.
 
This probably doesn't belong in npm and you should probably use eslint-plugin-absolute-imports instead.

A (zero-dependency!) eslint plugin that enforces absolute imports on your codebase.

## Prerequisites

You must have a `baseUrl` defined in either `tsconfig.json` or `jsconfig.json`. **This plugin does not currently work with `paths`!**

## Setup

- `npm i --save-dev eslint-plugin-absolute-imports-improved`
- Add `eslint-plugin-absolute-imports-improved` to your eslint `plugins` section
- Add `absolute-imports-improved/only-absolute-imports` to your eslint `rules` section

## License

MIT
