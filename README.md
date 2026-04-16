# Claude Code Dark Theme

Um tema escuro para VS Code inspirado no redesign do **Claude Code app** (abril 2025) — com fundos quase-pretos levemente quentes, acentos em terracota/laranja e texto em tons creme.

## Variantes

| Variante | Descrição |
|---|---|
| **Claude Code Dark** | Versão completa com bold em declarações e keywords |
| **Claude Code Dark (No Bold)** | Mesmos tons, sem bold no código |

## Paleta de cores

| Role | Cor |
|---|---|
| Background principal | `#1a1815` |
| Background sidebar / terminal | `#141210` |
| Background mais escuro (activity bar) | `#100e0c` |
| Texto principal | `#e8ddd0` |
| Texto secundário | `#c8bfb4` |
| Acento principal (terracota) | `#c8794a` |
| Strings (verde salva) | `#8aaa78` |
| Funções (dourado) | `#d4aa78` |
| Tipos (verde-cinza) | `#a8c0aa` |
| Números | `#e8a868` |
| Comentários | `#6a6258` (italic) |
| Error | `#c05040` |

## Instalação manual

1. Copie a pasta `claude-code-dark-theme` para `~/.vscode/extensions/`
2. Reinicie o VS Code
3. Abra o Command Palette (`Cmd+Shift+P`) → `Preferences: Color Theme` → selecione **Claude Code Dark**

## Fontes recomendadas

Para uma experiência mais fiel ao app do Claude Code:
- **JetBrains Mono** ou **Fira Code** (monospace com ligatures)
- Tamanho: 13–14px
- Line height: 1.5

```json
{
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "editor.fontSize": 13,
  "editor.lineHeight": 1.5,
  "editor.fontLigatures": true
}
```

## Licença

MIT
