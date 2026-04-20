# peg ::= mill

Parser infrastructure for the TypeScript stack. Apache 2.0. No VC, no corporate sponsor.

## Projects

- [pegmill](https://github.com/pegmill/pegmill) — PEG parser generator with parametric rules. Drop-in for PEG.js 0.10.0. Ships on npm: `npm install pegmill` (latest: v0.1.3 with TypeScript declarations and esbuild browser bundle).
- [pegmill.github.io](https://pegmill.github.io/) — landing with roadmap and comparison against Outlines, XGrammar, and llama.cpp GBNF.

## Why this exists

Constrained decoding for open-weight LLMs lives in Python (Outlines) or C++ (llama.cpp GBNF; XGrammar ships C++ with JS via emscripten build, no npm package). TypeScript has no equivalent with full PEG expressiveness. Pegmill fills that gap.

## Support

A star helps. A link from your own project docs helps more. [GitHub Sponsors](https://github.com/sponsors/zag) and `zag@cpan.org` for anything bigger.
