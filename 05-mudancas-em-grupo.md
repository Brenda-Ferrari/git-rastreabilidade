# 05. Mudanças em grupo

> Nomeie uma série de commits e combine os esforços completos.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)

---

## Comandos desta seção (5)

### 1. `git branch`

```bash
git branch
```

**O que faz:**

Lista todas as branches locais do projeto e indica em qual você está atualmente.

**Quando usar / observação:**

Quando quiser saber quais branches existem na sua máquina ou confirmar em qual delas você está trabalhando.

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**

Cria uma nova branch com o nome especificado, apontando para o commit onde você está no momento, mas sem mudar para ela.

**Quando usar / observação:**

Quando você quiser apenas preparar/criar uma nova linha de trabalho sem começar a mexer nela imediatamente.

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

Cria a nova branch e muda para ela no mesmo instante.

**Quando usar / observação:**

Sempre que for iniciar uma nova tarefa e quiser começar a trabalhar nela imediatamente.

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

Junta o histórico da branch especificada dentro da branch em que você está posicionado agora.

**Quando usar / observação:**

Quando a funcionalidade desenvolvida em uma branch estiver concluída e você quiser trazê-la para a branch principal.

---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**

Deleta a branch local informada. O Git só permite apagar se ela já tiver sido totalmente mesclada.

**Quando usar / observação:**

Para manter o projeto limpo, apagando branches temporárias de tarefas que você já concluiu e uniu à branch principal.

---

## Checklist deste arquivo

- [X] 1. `git branch`
- [X] 2. `git branch [nome-do-branch]`
- [X] 3. `git switch -c [nome-do-branch]`
- [X] 4. `git merge [nome-do-branch]`
- [X] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
