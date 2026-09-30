# 🎨 Arte Acessível — Guia do Repositório e do Dia a Dia

> Projeto de Extensão da **UNICAMP** focado na inclusão cultural através de audiodescrições de obras de arte para pessoas cegas ou com baixa visão.

---

## 🔰 Bem-vindo(a)! Novo(a) no GitHub? Comece por aqui!

Se este é o teu primeiro projeto a utilizar Git e GitHub, não te preocupes! Este repositório foi estruturado para ser simples e seguro de utilizar. 

### O que é este repositório?
Este espaço é o **centro do nosso código-fonte**. Aqui guardamos o histórico de alterações do aplicativo, gerimos as tarefas do grupo e garantimos que o trabalho de todos se junta de forma organizada.

---

## 🧠 Conceitos Básicos que Precisas de Saber

Para trabalhar na equipa, só precisas de entender estes 4 conceitos do dia a dia:

1. **`main` (Ramo Principal):** É onde mora a versão do código que funciona de forma estável. **Ninguém programa diretamente na `main`**.
2. **Branch (Ramo de Trabalho):** É uma cópia da `main` onde trabalhas na tua funcionalidade de forma isolada, sem correr o risco de estragar o código dos teus colegas.
3. **Commit:** É como um "salvamento" das tuas alterações de código, acompanhado por uma mensagem que explica o que fizeste.
4. **Pull Request (PR):** É um pedido que fazes à equipa a dizer: *"Terminei a minha tarefa nesta branch. Alguém pode rever o meu código para podermos juntá-lo à `main`?"*.

---

## 🔄 Fluxo de Trabalho Passo a Passo (O teu Dia a Dia)

Sempre que fores programar uma nova funcionalidade ou corrigir algo, segue esta sequência de passos no teu computador:

[1. Pega na Tarefa] ──> [2. Cria a tua Branch] ──> [3. Programa e faz Commit] ──> [4. Abre um Pull Request] ──> [5. Revisa e faz Merge] ──> [6. Código na Main!]

### Passo 1: Escolhe a tua tarefa
* Acede à aba **Projects** no nosso GitHub.
* Escolhe um cartão da coluna **Todo** (A Fazer) e arrasta-o para **In Progress** (Em Progresso).
* *Regra da equipa:* Pega em apenas **1 tarefa de cada vez**.

### Passo 2: Cria a tua branch local no computador
Abre o terminal do teu computador e atualiza o código antes de começar:
```bash
# 1. Garante que estás na main
git checkout main

# 2. Descarrega as últimas atualizações da equipa
git pull

# 3. Cria e entra na tua nova branch (dá-lhe um nome claro)
git checkout -b feature/nome-da-tua-tarefa
