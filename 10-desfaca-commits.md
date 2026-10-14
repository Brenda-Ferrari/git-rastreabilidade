# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

Retorna o projeto para o commit indicado, mantendo as suas alterações salvas no seu disco rígido.

**Quando usar / observação:**

Quando você quiser refazer, organizar ou juntar commits recentes sem perder nenhuma linha do código que escreveu.

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

Apaga definitivamente todas as alterações e commits feitos após o commit especificado, voltando o código e a pasta de trabalho exatamente para o estado dele.

**Quando usar / observação:**

Quando algo deu muito errado no código recente e você quer descartar totalmente as alterações mais recentes para recomeçar do zero a partir de um ponto limpo da história.

---

## Checklist deste arquivo

- [X] 1. `git reset [commit]`
- [X] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
