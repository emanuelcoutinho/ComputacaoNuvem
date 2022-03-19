# Atividade 01

## Introdução

Data de criação: 19/03/2022

Original Author(s): [Emanuel Coutinho](https://github.com/emanuelcoutinho)

Contributor(s): [João Marcelo](https://github.com/jmhal)

## Objetivo
Introdução ao Curso e a AWS Academy/Educate.

## Valor

1,0 ponto na 1ª nota.

## Data da Entrega Limite

22/05/2021

=====================


## Overview

In order to achieve the goal of this lab, you will have to go through the following steps:

1. Choose the operating system by selecting the [Amazon Machine Image (AMI)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html).
2. Define the virtual hardware configuration by choosing an [Instance Type](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html).
3. Review the network settings.
4. Review the storage settings.
5. Create tags (optional).
6. Configure the [Security Group](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html) rules (firewall).
7. Launch the instance (choosing or creating an [EC2 key pair](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-key-pairs.html)).

Let's begin!!! Go to [AWS Console](https://console.aws.amazon.com/) and login with your credentials. Click on Services at the top left, then choose EC2 in the Compute section.

![lab-001-scrn-01](images/lab-001-scrn-01.png)

### Step 1 - Choose the AMI
In the EC2 service menu, click on *Launch instance* and select *Launch Instance*.  

![lab-001-scrn-02](images/lab-001-scrn-02.png)

Select *Amazon Linux 2 AMI*. An AMI is a template that contains the software configuration (operating system, application server, and applications) required to launch your instance. In this first lab, we will stick to the x86 architecture.

![lab-001-scrn-03](images/lab-001-scrn-03.png)

### Step 2 - Define the Instance Type
The instance type defines the CPU and memory capacity. It also specifies the storage architecture that the instance will suppport, along with network perfomance available. You can use the suggested free-tier eligible instance type, and then go on to _Next: Configure Instance Details_.

![lab-001-scrn-04](images/lab-001-scrn-04.png)

### Step 3 - Network Settings
Make sure you select the public default subnet and that the *Auto-assign Public IP* setting is enabled for that subnet. You may leave all the other settings with their default values.

![lab-001-scrn-05](images/lab-001-scrn-05.png)

Go on to _Next: Add Storage_.

### Step 4 - Storage Settings
You can accept the default settings which creates an EBS root volume.

![lab-001-scrn-06](images/lab-001-scrn-06.png)

Go on to _Next: Add Tags_.

### Step 5 - Tags
_Tags_ is a way to add textual metadata to AWS Resources to help you manage your cloud environment. For now, you can skip this step.

![lab-001-scrn-07](images/lab-001-scrn-07.png)

Go on to _Next: Configure Security Group_.

### Step 6 - Security Group
The _Security Group_ is a firewall for the instance. Create a new security group named *ssh-access* with a rule that allows SSH from anywhere (or choose *My IP* if you prefer).

![lab-001-scrn-08](images/lab-001-scrn-08.png)

Go on to _Review and Launch_.

### Step 7 - Launch Instance
You can review all the settings until this step in the next screen.

![lab-001-scrn-09](images/lab-001-scrn-09.png)

If everything is Ok, go on to _Launch_. In the new windows, for the key-pair you can create a new key pair (name it lab-001). Download the key pair to your computer (the file will be named *lab-001.pem*).

![lab-001-scrn-10](images/lab-001-scrn-10.png)

You will be forwarded to a new screen with the launch status.

![lab-001-scrn-11](images/lab-001-scrn-11.png)

Go on to _View Instances_ to return to the EC2 Console. There you will a list of existing instances and the new instance you just created.

## Test & Validation

Once your instance is up and running, select it on the EC2 console and click on *Connect*.

![lab-001-scrn-12](images/lab-001-scrn-12.png)

From the new window, copy the example ssh command-line. It will have the following format:

``` bash
$ ssh -i "lab-001.pem" ec2-user@ec2-100-25-181-143.compute-1.amazonaws.com
```

The _ec2-user_ is the default user name in Amazon Linux AMIs. The hostname _ec2-100-25-181-143.compute-1.amazonaws.com_ is the DNS name for your instance that AWS automatically defines. Open a terminal window and move to the folder where you saved the downloaded key file *lab-001.pem*. Change the permissions of the key file:

``` bash
$ chmod 400 lab-001.pem
```
Paste and run the ssh command. You should be able to log into your instance. If you are a Windows user, you can also use Putty to connect. Follow this [link](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html?icmpid=docs_ec2_console) for instructions.

================


Questão 01 - 0,5 Pontos
O objetivo desta primeira questão é configurar o repositório no GitHub que será utilizado para submissão de atividades mais adiante na disciplina. Observe com atenção as regras de nomenclatura do mesmo para facilitar a vida do professor. Lembre que terei que corrigir as atividades de vários estudantes, então quanto mais fácil for para identificar o autor da atividade, mais rápido você obterá o resultado da avaliação.

 Entre no SI3 da disciplina, vá em Turma e depois em Participantes. Veja como está o seu nome.
 Suponha que seu nome esteja como JOÃO MARCELO UCHÔA DE ALENCAR:
 Escolha o primeiro e o segundo nomes, transforme em minúsculo e retire os acentos.
 Anexe a cadeia de caracteres nuvem20211.
 No exemplo, seria joaomarcelonuvem20211.
 Crie um repositório no GitHub privado com o nome definido pelas regras acima e mande um convite de colaboração para o e-mail jmarcelo.alencar@gmail.com.
 ATENÇÃO!!!: Obedeça as regras. Se você não usa seu primeiro ou segundo nome no dia a dia, não importa, para mim o importante é que seja fácil adicionar suas notas no SI3.
Se por acaso o repositório criado não obedecer a nomenclatura acima, não valerá a nota.

Questão 02 - 0,5 Pontos
Vamos começar a disciplina utilizando o conteúdo da AWS Academy. Portanto o aluno deve preencher o cadastro nesta plataforma, já enviado para o e-mail cadastrado no Si3.

No dia 10/05/2021 fiz a requisição de criação de uma turma virtual na plataforma AWS Educate. O pedido ainda está sob revisão, a AWS pede até 7 dias para liberar o acesso. Portanto, até a data final desta atividade você deverá receber um e-mail no endereço cadastrado no SI3 para completar o cadastro. Sua tarefa nesta questão consiste justamente em aceitar o convite e completar o cadastro. Poderei verificar pelo sistema se cada estudante cumpriu essa tarefa.

Caso você não tenha mais acesso ao e-mail cadastrado no SI3, por favor entre em contato o mais rápido possível via Slack para assim que a disciplina for aprovada eu possa cadastrar seu novo endereço.

Para ganhar os 0,5 pontos desta questão, o aluno deve completar o cadastro nos dois ambientes.



