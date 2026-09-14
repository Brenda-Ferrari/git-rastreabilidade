# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

É um arquivo de texto especial onde você lista regras de quais arquivos, pastas ou extensões o Git deve ignorar completamente.

**Quando usar / observação:**

No início do projeto para evitar o envio de arquivos temporários, logs, pastas de dependências, arquivos compilados ou dados sensíveis.

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

Lista no terminal todos os arquivos da sua pasta de trabalho que estão sendo ignorados pelo Git com base nas regras definidas no seu arquivo.

**Quando usar / observação:**

Para verificar se o .gitignore está funcionando corretamente, testar se uma nova regra funcionou ou descobrir por que um arquivo específico não está aparecendo no git status.

---

## Checklist deste arquivo

- [X] 1. Arquivo `.gitignore`
- [X] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
