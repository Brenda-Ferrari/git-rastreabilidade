# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

Exibe o histórico cronológico dos commits do repositório.

**Quando usar / observação:**

Quando você quiser rastrear o que foi feito no projeto, ver quem fez determinado commit ou encontrar o hash de um ponto específico no tempo.

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Exibe o histórico completo de commits de um arquivo específico.

**Quando usar / observação:**

Quando você quiser investigar o que há dentro de um arquivo específico e não quiser perder o rastro do histórico caso ele tenha mudado de nome.

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Mostra as alterações exatas no código que estão no segundo-branch a partir do ponto em que ele se separa do primeiro-branch.

**Quando usar / observação:**

Quando você estiver trabalhando em uma branch de funcionalidade e quiser ver exatamente o que você produziu em relação à branch principal, antes de fazer o merge.

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

Exibe os detalhes completos de um commit específico.

**Quando usar / observação:**

Quando você tiver o hash de um commit e quiser inspecionar exatamente o que foi adicionado ou removido apenas naquela alteração específica.

---

## Checklist deste arquivo

- [X] 1. `git log`
- [X] 2. `git log --follow [arquivo]`
- [X] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [X] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
