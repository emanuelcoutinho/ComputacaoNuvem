# Prática 10

## Amazon RDS

Data de criação: 31/05/2022

Autor: [Emanuel Coutinho](https://github.com/emanuelcoutinho)

## Objetivo
Explorar o Amazon RDS

## Instruções de Envio

Crie uma pasta no GITHUB chamada **Praticas de Laboratorio** e inclua um arquivo **PDF** ou usando a sintaxe da linguagem **MarkDown** de nome **Pratica10** com as questões a seguir e as respectivas respostas.

## Atividades Iniciais

1. Inicie o ambiente prático do **Módulo 8: Bancos de dados** ou acesse sua conta particular (com adaptações no roteiro).

## Questão 1

- Acesse o Amazon RDS 
- **Criar banco de dados**
- Selecione o mecanismo **MySQL**
- Em **Disponibilidade e durabilidade** selecione **Cluster de banco de dados Multi-AZ - Novo**
- Em **Configurações** inclua uma senha e confirme a senha
- No final, clique em **Criar banco de dados**

- Selecione o mecanismo **PostgreSQL**
- Em **Disponibilidade e durabilidade** selecione **Instância de banco de dados única**
- Em **Configurações** inclua uma senha e confirme a senha
- No final, clique em **Criar banco de dados**
- Relate o ocorrido
- Em **Configuração da instância** selecione **Classes com capacidade de intermitência (inclui classes t)**
- Expanda **Configuração adicional** e desmarque **Habilitar backups automatizados** e **Habilitar monitoramento avançado**
- No final, clique em **Criar banco de dados**
- Relate o ocorrido
- Registre e analise os custos totais
- Comente sobre o custo dos dois banco de dados

- Para o banco de dados **PostgreSQL**, acesse a aba **Monitoramento** e analise os gráficos
- Para o banco de dados **MySQL**, instância principal, acesse a aba **Monitoramento** e analise os gráficos
 
- Na lista de banco de dados, selecione o banco de dados criado por último
- No menu **Ações**, clique em **Excluir**
- Relate o ocorrido
- No menu **Modificar** e desabilite a opção **Proteção contra exclusão**
- Selecione **Aplicar imediatamente**
- Confirme
- Selecione o banco de dados modificado e no menu **Ações**, clique em **Excluir** 
- Desmarque **Create final snapshot?**
- Marque a opção **I acknowledge that upon instance deletion, automated backups, including system snapshots and point-in-time recovery, will no longer be available**
- Confirme a exclusão

- Na lista de banco de dados, selecione o banco de dados criado inicialmente
- No menu **Ações**, clique em **Excluir**
- Relate o ocorrido
- No menu **Modificar** e desabilite a opção **Proteção contra exclusão**
- Selecione **Aplicar imediatamente**
- Confirme
- Selecione o banco de dados modificado e no menu **Ações**, clique em **Excluir** 
- Em **Create final snapshot?** selecione **No**
- Marque a opção **I acknowledge that upon cluster deletion, automated backups, including system snapshots and point-in-time recovery, will no longer be available.**
- Confirme a exclusão


