# 📘 Comandos Git mais utilizados

Este documento reúne os principais comandos Git usados no dia a dia de desenvolvimento, com explicações simples e exemplos diretos.

---

## 📥 Baixar atualizações do repositório remoto (sem alterar seu código local)
```bash
git fetch
```
> Baixa atualizações do repositório remoto (novas branches, commits etc), **sem alterar sua branch atual**.

---

## 🔄 Atualizar seu código local com as mudanças remotas
```bash
git pull
```
> Faz `fetch` + `merge`. Atualiza sua branch atual com as alterações do repositório remoto.

---

## 📤 Enviar seu código local para o repositório remoto
```bash
git push
```
> Envia seus commits locais para o repositório remoto (como o GitHub).

---

## 📁 Inicializar um repositório Git no projeto
```bash
git init
```
> Cria um repositório Git vazio na pasta atual.

---

## 📌 Verificar o status dos arquivos (modificados, não versionados, etc)
```bash
git status
```
> Mostra os arquivos que foram alterados, adicionados ou removidos.

---

## ➕ Adicionar arquivos ao stage (preparar para commit)
```bash
git add .
```
> Adiciona **todos os arquivos modificados** ao stage.

```bash
git add nome-do-arquivo.ext
```
> Adiciona um arquivo específico ao stage.

---

## ✅ Criar um commit com uma mensagem
```bash
git commit -m "Mensagem do commit"
```
> Salva as alterações adicionadas com uma mensagem descritiva.

---

## 🌿 Criar uma nova branch
```bash
git checkout -b nome-da-branch
```
> Cria e muda para uma nova branch.

---

## 🔄 Trocar de branch
```bash
git checkout nome-da-branch
```
> Troca para uma branch existente.

---

## 🔍 Ver todas as branches locais
```bash
git branch
```

---

## 🧑‍💻 Mesclar uma branch com a atual
```bash
git merge nome-da-branch
```
> Aplica as mudanças de outra branch na branch atual.

---

## 🔗 Adicionar o repositório remoto
```bash
git remote add origin https://github.com/usuario/repositorio.git
```
> Conecta seu projeto local a um repositório remoto (GitHub, GitLab, etc).

---

## ⬆️ Subir uma branch nova para o repositório remoto
```bash
git push -u origin nome-da-branch
```
> Envia a branch local para o repositório remoto e cria o link entre eles.

---

## 🔙 Ver o histórico de commits
```bash
git log
```

---

## 🗑️ Desfazer alterações locais em um arquivo (sem apagar o commit)
```bash
git checkout -- nome-do-arquivo.ext
```

---

## ⚠️ Clonar um repositório remoto
```bash
git clone https://github.com/usuario/repositorio.git
```
> Faz o download de um repositório remoto para seu computador.

---

## 🧽 Remover um arquivo do stage
```bash
git reset nome-do-arquivo.ext
```

---

## 🧯 Desfazer último commit (mantendo as alterações)
```bash
git reset --soft HEAD~1
```

---

## 🔒 Ver quem é você no Git
```bash
git config user.name
git config user.email
```

---

## ✏️ Configurar seu nome e e-mail no Git
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

---

> 📝 **Dica:** Sempre crie commits pequenos e com mensagens claras. Isso ajuda na organização e no trabalho em equipe.
