# Exemplos de operações básicas do Git via CLI

## Comandos de uso geral da CLI

- Criar pasta: **mkdir nomepasta**
- Listar conteúdo: **dir**
- Limpar a tela: **cls**
- Entrar na pasta: **cd nomepasta**

## Comandos principais do Git

**Mudar email/usuário de forma global:** `git config --global user.name "Seu nome"` e `git config --global user.email "seuemail@gmail.com"`

***Obs:*** Normalmente estes dados estão relacionados ao usuário/conta do site GitHub.

**Configurar email/usuário:** `git config user.name` e `git config user.email`.

**Inicializar um repositório (executado dentro da pasta):** `git init`.

**Renomear a branch de ***master*** para ***main*****: `git branch nome-branch-atual (master) novo-nome-branch (main)`.

**Vizualizar status atual do repositório:** `git status`.

**Adicionar (Tornar arquivo rastreável) ao monitoramento do git:**  `git add nomearquivo` para uso de ***um unico arquivo*** e `git add .` para adicionar ***todos*** arquvios.

**Fazer commit das alterações:** `git commit -m "sua mensagem sobre a alteração"`.

**Enviar mudanças para o GitHub (Push):** `git push origin main`.

**Adicionar/conectar o repositório remoto ao local:**  `git remote add origin endereço-do-repositório.git`.

**Copiando/baixando um repositório para a máquina remota:** `git clone endereço-do-repositório.git`



