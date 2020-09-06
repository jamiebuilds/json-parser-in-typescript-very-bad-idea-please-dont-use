# `json-parser-in-typescript-very-bad-idea-please-dont-use`

> JSON Parser written entirely in TypeScript's type system

```ts
import type { ParseJson } from "json-parser-in-typescript-very-bad-idea-please-dont-use"

type Person = ParseJson<'{ "name": "Jamie Kyle", "twitter": "https://twitter.com/buildsghost" }'>
// {
//   "name": "Jamie Kyle",
//   "twitter": "https://twitter.com/buildsghost"
// }
```

[Follow me nerds](https://twitter.com/buildsghost)
