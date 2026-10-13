# transferencia-octo

Pacote de transferência do time Octo para outro PC.

## Conteúdo

- `opencode/agents/` — agentes OpenCode do time Octo:
  - `octo.md`
  - `planner.md`
  - `explorer.md`
  - `coder.md`
  - `reviewer.md`
  - `search.md`
- `maestri/Octo.maestripartitura` — snapshot (backup) da partitura Octo.

## Como usar

1. **Agentes OpenCode**: copie os arquivos de `opencode/agents/` para
   `~/.config/opencode/agents/` no outro PC (no Windows:
   `C:\Users\<usuario>\.config\opencode\agents\`).
2. **Partitura**: mantenha `maestri/Octo.maestripartitura` como backup bruto.

## Ressalvas

- O snapshot da partitura é um **backup bruto**: contém IDs internos e `notes`
  referentes ao ambiente de origem. Ele **não** é um formato de import/export
  documentado.
- **Não** afirmamos que a restauração ou importação da partitura funciona. O CLI
  do Maestri não documenta esse fluxo, então trate o arquivo apenas como cópia de
  segurança.
- Este pacote contém somente os 6 role files listados acima; nenhum outro role
  file foi incluído.
