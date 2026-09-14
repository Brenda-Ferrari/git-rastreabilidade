# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

Remove o arquivo do controle de versão do Git e também o deleta da sua pasta local.

**Quando usar / observação:**

Quando você quiser apagar um arquivo permanentemente do projeto e garantir que essa remoção seja registrada no próximo commit.

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

Remove o arquivo do controle de versão do Git, mas mantém o arquivo intacto no seu computador.

**Quando usar / observação:**

Quando você adicionou ao Git um arquivo que não deveria ser monitorado e agora quer parar de rastreá-lo no Git sem perdê-lo da sua máquina.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

Renomeia ou move um arquivo de pasta e já deixa essa alteração preparada para o próximo commit.

**Quando usar / observação:**

Sempre que precisar mudar o nome de um arquivo ou movê-lo de diretório dentro do projeto.

---

## Checklist deste arquivo

- [X] 1. `git rm [arquivo]`
- [X] 2. `git rm --cached [arquivo]`
- [X] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
