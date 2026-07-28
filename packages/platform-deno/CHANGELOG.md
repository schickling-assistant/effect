# @effect/platform-deno

## 4.0.0-beta.103

### Patch Changes

- [#6685](https://github.com/Effect-TS/effect/pull/6685) [`45e7810`](https://github.com/Effect-TS/effect/commit/45e78108823d24abe075cfb69a75733223960573) Thanks @tim-smart! - Add `DenoHttpClient`, re-exporting `effect/unstable/http/FetchHttpClient`

  Deno's `fetch` is spec-compliant, so the core fetch-based `HttpClient` works on Deno unmodified. This module mirrors `BunHttpClient` so the platform packages expose a consistent surface.

- [#6412](https://github.com/Effect-TS/effect/pull/6412) [`ec656dc`](https://github.com/Effect-TS/effect/commit/ec656dccf17cfdf0be4152e042c56f7a21f169ac) Thanks @lishaduck! - Add Deno platform integrations for paths, runtime execution, workers, and Web Storage.

- [#6684](https://github.com/Effect-TS/effect/pull/6684) [`dbd6ea4`](https://github.com/Effect-TS/effect/commit/dbd6ea4ef6f78f41070d57bd9a5bfa2699df268d) Thanks @tim-smart! - Add a Deno Web Crypto implementation of the `Crypto` service.

- Updated dependencies [[`205ebc7`](https://github.com/Effect-TS/effect/commit/205ebc776062012581e98fced7ced19adfc44ee7), [`ed0ebf8`](https://github.com/Effect-TS/effect/commit/ed0ebf8e5c864d46fed1f232e99c0e680f10a58f), [`a3fd084`](https://github.com/Effect-TS/effect/commit/a3fd08482157bd78b089f77c7b173d54ef68b5cd), [`ee29ddf`](https://github.com/Effect-TS/effect/commit/ee29ddf862c3723ad466abc93ab6f6fe723b2319), [`1747440`](https://github.com/Effect-TS/effect/commit/1747440de9a51a56ed3660da748cc01b256adce7), [`9800e3a`](https://github.com/Effect-TS/effect/commit/9800e3acc8f36530f671bc8b91558cb112f449a7), [`cc27b19`](https://github.com/Effect-TS/effect/commit/cc27b194b9d13fa3a66ab037e853fca9d41700ff), [`0a532e5`](https://github.com/Effect-TS/effect/commit/0a532e503f165fdea485a5343fc2f420917e8376)]:
  - effect@4.0.0-beta.103
