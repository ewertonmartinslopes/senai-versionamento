# 📌Trabalho do curso de Full Stack pra treinar git e git hub.
Guia de Versionamento de Código com Git e GitHub
Um guia prático e objetivo sobre conceitos, comandos e boas práticas de controle de versão utilizando Git e GitHub.

---

## 🎯 Objetivo

Este repositório reúne os principais conceitos e anotações sobre versionamento. O objetivo é servir como um guia de referência rápida para o dia a dia de desenvolvimento.

---

## 🧠 Conceitos Fundamentais

* **Versionamento de Código:** Prática de registrar as alterações feitas em um código ao longo do tempo, permitindo resgatar versões anteriores e trabalhar em equipe sem sobresscrever o trabalho alheio.
* **Git:** Sistema de controle de versão distribuído (DVCS) local.
* **GitHub:** Plataforma baseada em nuvem para hospedagem e colaboração em repositórios Git.
* **Commits:** Registros "salvos" (snapshots) das alterações no repositório.
* **Branches (Ramos):** Linhas de desenvolvimento independentes que permitem isolar novas funcionalidades ou correções de bugs.

---

## 🚀 Comandos Principais

### 1. Configuração Inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"

# Iniciar um repositório local
git init
# Verificar o status dos arquivos

git status

# Adicionar arquivos à área de staging
git add .

# Criar um commit com mensagem explicativa
git commit -m "feat: mensagem clara do que foi alterado"

# Vincular o repositório local ao GitHub
git remote add origin [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)

# Enviar as alterações para o repositório remoto
git push -u origin main ou master

# Atualizar o repositório local com as alterações do remoto
git pull origin main ou master

# Criar e alternar para uma nova branch
git checkout -b feature1

# Alternar para uma branch existente
git checkout main ou master

# Unir alterações de outra branch para a branch atual
git merge feature1
