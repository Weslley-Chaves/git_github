# 📘 Comandos Git Essenciais

Este repositório foi criado para praticar o uso do **Git** e do **GitHub**.
Abaixo está uma lista dos comandos mais utilizados e suas respectivas funcionalidades.

---

## 🚀 Iniciando um Repositório
- `git init` → Inicializa um novo repositório Git na pasta atual.
- `git clone <url>` → Clona um repositório remoto para a máquina local.

---

## 📂 Gerenciamento de Arquivos
- `git status` → Mostra o estado atual dos arquivos (modificados, prontos para commit etc.).
- `git add <arquivo>` → Adiciona um arquivo específico à área de preparação (*staging area*).
- `git add .` → Adiciona **todos** os arquivos modificados.
- `git rm <arquivo>` → Remove um arquivo do repositório.

---

## 💾 Salvando Alterações
- `git commit -m "mensagem"` → Salva as alterações adicionadas ao repositório com uma mensagem.
- `git log` → Mostra o histórico de commits.
- `git diff` → Mostra as diferenças entre arquivos modificados e o último commit.

---

## 🔄 Conexão com Repositórios Remotos
- `git remote -v` → Lista os repositórios remotos configurados.
- `git remote add origin <url>` → Adiciona um repositório remoto chamado `origin`.
- `git remote set-url origin <url>` → Altera a URL do repositório remoto.

---

## ⬆️ Enviando e Baixando Alterações
- `git push origin main` → Envia as alterações locais para a branch `main` no remoto.
- `git pull origin main` → Atualiza o repositório local com as mudanças do remoto.
- `git fetch` → Busca alterações do remoto sem mesclar automaticamente.

---

## 🌿 Trabalhando com Branches
- `git branch` → Lista as branches existentes.
- `git branch -M main` → Renomeia a branch atual para `main`.
- `git checkout <branch>` → Troca para a branch indicada.
- `git checkout -b <nova-branch>` → Cria e troca para uma nova branch.
- `git merge <branch>` → Mescla a branch indicada na branch atual.

---

## 🧹 Outros Comandos Úteis
- `git restore <arquivo>` → Restaura a versão mais recente de um arquivo.
- `git reset --hard <commit>` → Volta o repositório para um commit específico (⚠️ destrutivo).
- `git clean -fd` → Remove arquivos não versionados (⚠️ cuidado).

---

## 📚 Referências
- [Documentação Oficial do Git](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)

