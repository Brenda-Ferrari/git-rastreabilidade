# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

Baixa todas as atualizações, histórico e branches do repositório remoto para a sua máquina, sem alterar nada nos seus arquivos locais.

**Quando usar / observação:**

Quando você desejar ver o que os seus colegas enviaram para o GitHub sem o risco de alterar ou bagunçar o código que você está escrevendo no momento.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

Junta as alterações de uma branch remota que você baixou previamente na branch local aonde você se encontra.

**Quando usar / observação:**

Após ter executado o git fetch, quando você estiver pronto para mesclar de fato as novidades do servidor no seu código local.

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

Envia os seus commits locais para o repositório remoto na nuvem.

**Quando usar / observação:**

Sempre que você concluir uma tarefa e quiser publicar as alterações no GitHub.

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

Atalho completo que realiza o git fetch (baixa as novidades) e em seguida o git merge (junta com seu código) em um único comando.

**Quando usar / observação:**

No início do dia ou antes de começar uma nova tarefa, para atualizar rapidamente a sua máquina com a versão mais recente do projeto que está no servidor.

---

## Checklist deste arquivo

- [X] 1. `git fetch [nome-remoto]`
- [X] 2. `git merge [nome-remoto]/[branch]`
- [X] 3. `git push [alias] [branch]`
- [X] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
