# @plurnk/plurnk-mimetypes-grammar-elixir

Pre-built `tree-sitter-elixir` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-elixir
```

## what's in here

- **`elixir.wasm`** — pre-built from the pinned upstream [tree-sitter-elixir](https://github.com/elixir-lang/tree-sitter-elixir) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `elixir.wasm` is built from the upstream tree-sitter-elixir grammar; see the pinned commit for that project's attribution.
