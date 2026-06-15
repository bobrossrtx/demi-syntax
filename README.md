# DemiSyntax — VSCode Syntax Highlighting for Demi DASM

Syntax highlighting for the **DASM** assembly language — the ISA-level language of the Demi virtual machine and native code assembler.

## Features

- **Full DASM syntax highlighting** — VM instructions, native x86/x64 instructions, FPU instructions
- **Register coloring** — 64-bit, 32-bit, 16-bit, 8-bit, VM, FPU, and segment registers
- **Directive highlighting** — `.section`, `.org`, `.global`, `.test`, `.macro`, `.irp`, and more
- **String and number detection** — hex (`0xFF`), decimal, binary, quoted strings
- **Comment support** — `;` line comments and `#` alternate comments
- **Bracket matching** and auto-closing pairs
- **Code folding** via `; region` / `; endregion`

## File Support

Files with the `.asm` extension are automatically recognized as DASM.

## Installing

```bash
# Link or copy to VSCode extensions:
cp -r DemiSyntax ~/.vscode/extensions/demi-syntax-0.1.0
```

## Next: Demi High-Level Language

Support for the Demi higher-level language (`.demi`, `.d`) is planned.

## License

MIT — Copyright (c) 2025 Nous Research
