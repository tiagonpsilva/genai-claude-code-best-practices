# 👩‍💻 Uso de Worktrees para Paralelismo

## 🎯 Objetivo

Permitir múltiplas tarefas simultâneas em diferentes branches usando git worktrees e Claude Code.

## Passos

1. Crie worktrees para cada branch: `git worktree add ../feature-x feature-x`
2. Abra uma instância do Claude Code em cada worktree
3. Execute tarefas independentes em paralelo

## Dica

Ideal para grandes refatorações ou desenvolvimento de múltiplas features! 