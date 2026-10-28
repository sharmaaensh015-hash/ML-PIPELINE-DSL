# MLPipe Studio: End-to-End Compiler for ML Pipelines

A small DSL (`.mlp`) and an in-browser compiler. Leakage is a **compile error**.

Phases: Lexer -> Parser (AST) -> Loop unrolling -> Semantic/type check -> Leakage analysis -> scikit-learn codegen.

Open `index.html` (no build step). Hosted via GitHub Pages.

## Deploy
Upload all files to the repo root, then Settings > Pages > Deploy from branch `main` / root.

## Files
- `index.html`: the whole compiler and Studio UI
- `examples/*.mlp`: sample programs (valid, leakage error, type errors, syntax error)
