# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Mostra o estado atual das suas alterações.

**Quando usar / observação:**

O tempo todo, principalmente antes de adicionar ou commitar arquivos.

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra linha por linha do que alterou nos arquivos que ainda não foram preparados para commit.

**Quando usar / observação:**

Antes de usar o git add, para revisar o código modificado no momento.

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Envia um arquivo modificado para a área de preparação, marcando-o para entrar no próximo salvamento.

**Quando usar / observação:**

Sempre que terminar uma alteração em um arquivo e quiser incluí-lo no commit.

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Mostra as alterações exatas linha por linha dos arquivos que já estão na área de preparação.

**Quando usar / observação:**

Depois do git add e antes do git commit, para checar o que realmente será salvo.

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Remove um arquivo da área de preparação, sem apagar o código que você escreveu.

**Quando usar / observação:**

Quando você usou o git add por engano e não quer incluir aquele arquivo no próximo commit.

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Salva definitivamente um ponto na história do projeto com as alterações preparadas e uma mensagem explicativa.

**Quando usar / observação:**

Quando concluir uma tarefa e quiser registrar esse progresso no histórico.

---

## Checklist deste arquivo

- [X] 1. `git status`
- [X] 2. `git diff`
- [X] 3. `git add [arquivo]`
- [X] 4. `git diff --staged`
- [X] 5. `git reset [arquivo]`
- [X] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
