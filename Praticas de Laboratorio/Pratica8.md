# Prática 08

## Amazon Elastic Beanstalk

Data de criação: 16/05/2022

Autor: [Emanuel Coutinho](https://github.com/emanuelcoutinho)

## Objetivo
Explorar o Amazon Elasntic beanstalk.

## Instruções de Envio

Crie uma pasta no GITHUB chamada **Praticas de Laboratorio** e inclua um arquivo **PDF** ou usando a sintaxe da linguagem **MarkDown** de nome **Pratica08** com as questões a seguir e as respectivas respostas.

## Atividades Iniciais

1. Inicie o ambiente prático do **Sandbox** ou acesse sua conta particular (com adaptações no roteiro).

## Questão 1

Acesse o **Amazon Elastic Beanstalk**

Crie uma aplicação em **Create Application**

Digite um nome para sua aplicação

Selecione como plataforma Python

Deixe selecionado a utilização do aplicativo de exemplo

Clique **Configurar mais opções**

Navegue pela página e verifique as opções disponíveis

Em **Segurança**, **Função de serviço**, selecione **LabRole**

Em **Par de chaves EC2** selecione **vockey**

Em **Perfil de instância do IAM** selecione **LabInstanceProfile**

Clique em **Salvar**

Clique em **Criar aplicativo**

Verifique a tela de logs que surge e informe o tempo total para a a finalização do ambiente (mensagem final de sucesso). Capture esse log. Verifique também quais os serviços da Amazon AWS são utilizados.

Acesse no menu lateral o item **Aplicativos**

Navegue pelas colunas da aplicação criada

Clique no nome do aplicativo criado e verifique que no menu lateral surgiram alguns itens relacionados a ele

Clique no menu lateral em **Versões do aplicativo**

Navegue pelas colunas da tela de versão do aplicativo

Acesse no menu lateral o item **Ambientes**

Navegue pelas colunas do ambiente criado

Acesse a aplicação por sua URL

Clique no nome do ambiente criado e verifique que no menu lateral surgiram alguns itens relacionados a ele

Clique no menu lateral em **Monitoramento** e navegue pela tela dos gráficos

Repita todo o processo para implantantar uma aplicação em Node.js e outra em PHP, utilizando o upload de uma aplicação (use o zip de exemplo da documentação)

Atualize a aplicação em Python (pode usar o arquivo zip da documentação)

Visualize as métricas de monitoramento do ambiente python

Acesse o Amazon EC2 

Verifique a relação das instâncias com o Amazon Elastic Beanstalk

Acesse o Amazon S3

Verifique a relação dos buckets com o Amazon Elastic Beanstalk



