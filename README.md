# Compiladores — TP2

Repositório de exemplo contendo um analisador léxico em Rust.

Pré-requisitos
- Rust e Cargo instalados (https://www.rust-lang.org/tools/install).

Build
1. Abra um terminal na pasta do projeto `tp2`:

```bash
cd "c:\Users\livia\Desktop\2026.1\compiladores\tp2"
```

2. Compile com:

```bash
cargo build --release
```

Execução
- Há um arquivo de exemplo `sample.src`. Para rodar o analisador léxico e imprimir tokens:

```bash
cargo run -- sample.src
```

Notas
- O projeto depende da crate `regex` (declarada em `Cargo.toml`).
- O binário lê o caminho do arquivo de entrada via `args[1]` e imprime cada `Token` com `Debug`.

Contribuição
- Já foi feito push deste diretório para o remoto: https://github.com/Theotherlinus/compiladores-.git
