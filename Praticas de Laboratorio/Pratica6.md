# Prática 06

## Linha de Comando

Data de criação: 01/05/2022

Autor: [Emanuel Coutinho](https://github.com/emanuelcoutinho)

## Objetivo
Explorar a linha de comando para operações na Amazon AWS.

## Instruções de Envio

Crie uma pasta no GITHUB chamada **Praticas de Laboratorio** e inclua um arquivo **PDF** ou usando a sintaxe da linguagem **MarkDown** de nome **Pratica06** com as questões a seguir e as respectivas respostas.

## Atividades Iniciais

1. Inicie o ambiente prático do **Sandbox** ou acesse sua conta particular.

2. Instale a interface de linha de comando da Amazon AWS [CLI](https://aws.amazon.com/pt/cli/)

3. Acesse as credenciais da AWS para obter os valores da **SecretKey**, **Region** e **AccessKey**.

4. Na linha de comando, utilize o comando **aws configure** para configurar o ambiente.

Por exemplo:
	
	$ aws configure
	AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
	AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
	Default region name [None]: us-west-2
	Default output format [None]: json

5. Teste com o comando **aws ec2 describe-instances**.

5. Se não funcionar, edite o arquivo **credentials** na pasta **.aws** do usuário. O conteúdo será semelhante a:
	
[default]
	aws_access_key_id=ASIA4T7E453B27Y4UZP2
	aws_secret_access_key=3pCQoCQqaLrmhh6GMK1zDCZLZilhToqZnoLxnz/n
aws_session_token=FwoGZ87aYXdzEHYaDFzzaE44ygNAhKy8KSK/AfUdqqAcD18OcgDyDXRz/vGYw4NnLDlxQPov5DmzhZPhaIGiMMWUGLrH7gdsXy4xiLEL5Q62o+sFXUmMPDGaYQPcVGo5tendqqAcD1OOedqqAcD1oUNQU3A11h7ODRELbp0Ch4BzW6jJOD6r1+dxsYVNttN43gWsNSXLvcg/8aX6w0ASF765SKEw7Ob0/oJznjhOd3wscIDFEsDzbda8FkdLH/D4t7KMs6vKGep6K3NRzP+q8nZdqqAcD1zuTESKj6IKKbvuZMGMi0qGdY7049ygxi27gyHKJkniPkdqqAcD1PvknlKUUIA9YnReFvjZmR0B0/M+bY=


Essas informações podem ser obtidas no sandbox nas credenciais, em **Detalhes > Show > AWS CLI:**. Basta copiar para o arquivo.


## Questão 01 - Amazon EC2

Com linhas de comando:

1. Crie algumas máquinas virtuais na Amazon EC2
2. Liste todas com alguns filtros
3. Inicialize
4. Pare
5. Re-inicialize
6. Liste todas
7. Termine

## Questão 02 - Amazon S3

Com linhas de comando:

1. Crie um bucket na Amazon S3
2. Liste o conteúdo
3. Adicione arquivos
4. Liste o conteúdo
5. Copie arquivos
6. Mova arquivos
7. Liste o conteúdo
8. Faça o download de arquivos do bucket
9. Apague o bucket





