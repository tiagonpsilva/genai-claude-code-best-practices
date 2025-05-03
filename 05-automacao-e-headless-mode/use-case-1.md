# 👩‍💻 Automação de Triagem de Issues

## 🎯 Objetivo

Usar o modo headless do Claude Code para rotular e priorizar issues automaticamente em um repositório.

## Exemplo de Comando

```sh
claude -p "Analise a issue #123 e sugira um label de prioridade." --output-format stream-json
```

## Dica

Integre esse comando em um workflow de CI para triagem automática de novas issues! 