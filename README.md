# NotebookLM Bridge for Claude Code

> Acesse o NotebookLM diretamente pelo Claude Code via MCP

## Link de Acesso

**GitHub Pages (link publico):**  
https://paulacunhaadv7-cmd.github.io/notebooklm-claude-bridge

**NotebookLM direto:**  
https://notebooklm.google.com

---

## Como usar no Claude Code

### 1. Clone o repositorio

```bash
git clone https://github.com/paulacunhaadv7-cmd/notebooklm-claude-bridge
cd notebooklm-claude-bridge
```

### 2. Configure o MCP no Claude Code

Adicione ao arquivo `~/.claude/claude_desktop_config.json` (ou `claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "notebooklm": {
      "command": "node",
      "args": ["caminho/para/notebooklm-claude-bridge/server.js"],
      "env": {
        "NOTEBOOKLM_URL": "https://notebooklm.google.com"
      }
    }
  }
}
```

### 3. Acesse pelo link gerado

Apos configurar, acesse:

- **GitHub Pages:** https://paulacunhaadv7-cmd.github.io/notebooklm-claude-bridge
- **NotebookLM:** https://notebooklm.google.com

---

## Estrutura do Projeto

```
notebooklm-claude-bridge/
|-- index.html       # Pagina de acesso com link para o NotebookLM
|-- README.md        # Documentacao
```

---

## Tecnologias

- HTML/CSS (GitHub Pages)
- MCP (Model Context Protocol) para Claude Code
- NotebookLM (Google)

---

*Criado para integrar o NotebookLM com o Claude Code*
