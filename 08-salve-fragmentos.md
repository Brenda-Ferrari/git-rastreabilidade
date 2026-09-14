# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

Salva temporariamente as alterações locais não salvas em uma "gaveta" e limpa sua pasta de trabalho, voltando o código ao estado do último commit.

**Quando usar / observação:**

Quando você estiver no meio de um trabalho e precisar mudar de branch para corrigir um bug urgente.

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

Retira as alterações salvas do topo da pilha e as reaplica no seu código de trabalho atual, apagando esse item da gaveta do stash.

**Quando usar / observação:**

Quando você voltar para a branch em que estava trabalhando e quiser restaurar o código que tinha guardado temporariamente com o git stash.

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

Exibe uma lista com todos os rascunhos que você tem armazenados na pilha do stash.

**Quando usar / observação:**

Quando você tiver executado o git stash várias vezes e precisar verificar quais stashes estão guardados antes de aplicar um deles.

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

Exclui permanentemente um rascunho específico guardado no stash (remove o mais recente se nenhum for especificado).

**Quando usar / observação:**

Quando você constatar que as alterações salvas em um determinado stash não são mais necessárias e quiser limpar a pilha para liberar espaço.

---

## Checklist deste arquivo

- [X] 1. `git stash`
- [X] 2. `git stash pop`
- [X] 3. `git stash list`
- [X] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
