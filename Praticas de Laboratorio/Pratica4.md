# Prática 04

## Regiões e Zonas de Disponibilidade da Amazon

Data de criação: 16/04/2022

Autor: [Emanuel Coutinho](https://github.com/emanuelcoutinho)

## Objetivo
Explorar o Console de Gerenciamento da AWS.
Conhecer mais sobre as regiões e zonas de disponibilidade da Amazon.

## Instruções de Envio

Crie uma pasta no GITHUB chamada **Praticas de Laboratorio** e inclua um arquivo **PDF** ou usando a sintaxe da linguagem **MarkDown** de nome **Pratica04** com as questões a seguir e as respectivas respostas.

## Questão 01

Inicie o ambiente prático do **Sandbox** e conecte-se ao **Console de Gerenciamento da AWS**.

Clique no menu **Serviços**.

1. Observe como os serviços são agrupados em categorias de serviço. Por exemplo, o serviço EC2 aparece na categoria Compute service (Serviço de computação).
   - Em qual categoria de serviço o serviço IAM aparece? 
   - Em qual categoria de serviço o serviço RDS aparece?
   - Em qual categoria de serviço o serviço AWS Cost Explorer aparece?
   - Em qual categoria de serviço o serviço CloudWatch aparece?
   - Em qual categoria de serviço o serviço VPC aparece?

2. Clique no serviço **VPC**. Observe que o menu suspenso no canto superior direito exibe uma região da AWS (por exemplo, ele pode exibir o Norte da Virgínia). 
   - Clique no menu **Região** e alterne para uma região diferente. Por exemplo, escolha EU (London).
   - O que acontece ao alterar a região?

3. Clique em **Subnets** (no lado esquerdo da tela). A região possui algumas sub-redes. 
   - Clique na caixa ao lado de uma das sub-redes. Observe que a metade inferior da tela agora exibe detalhes sobre essa sub-rede. 
   - Para cada sub-rede selecionada, existe a informação do nível da região ou da zona de disponibilidade?
   - Liste para cada sub-rede a zona de disponibilidade.

4. Clique em **Your VPCs**.
   - Quantas VPCs existem?
   - Para cada sub-VPC selecionada, existe a informação do nível da região ou da zona de disponibilidade?
<!--
   - Quais serviços são globais em vez de regionais? Verifique o Amazon EC2, o IAM, o Lambda e o Route 53.
-->

5. Clique em **EC2**.
   - Quantas instâncias existem?
   - Para cada instância selecionada, existe a informação do nível da região ou da zona de disponibilidade?
   - Liste para cada instância a região.





