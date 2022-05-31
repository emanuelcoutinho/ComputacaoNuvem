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

4. Na linha de comando, utilize o comando **aws configure** para configurar o ambiente. Por exemplo:
	
        $ aws configure
        AWS Access Key ID [None]: AKIAIOSHJKNN7EXAMPLE
        AWS Secret Access Key [None]: wJaopXUtnFEMI/K876GG/bPxRhagEXAMPLEKEY
        Default region name [None]: us-west-2
        Default output format [None]: json

5. Teste com o comando **aws ec2 describe-instances**.

5. Se não funcionar, edite o arquivo **credentials** na pasta **.aws** do usuário. Essas informações podem ser obtidas nas credenciais do sandbox, em **Detalhes > Show > AWS CLI:**. Basta copiar para o arquivo. O conteúdo será semelhante a:
	
        [default]
        aws_access_key_id=ASIJHG4T7E411127A4UZP2
        aws_secret_access_key=3pCQoCQqaLrmhh6GMK1zHVFTHCFDDlhToqZnoLxnz/n
        aws_session_token=L876FwoGZ87aYXdzEHYaDFzzaE44aaaygNAhKy8KSK/AfUdqqAcD18OcgDyDXasdfghj4NnLDlxQPov5abciMMWUGLrH7gdsXy4xiLEL5Q62o+sFXUmMPDGaYQPcVGo5tendqqAcD1OOedqqAcD1oUNQU3A11hsss7ODRELbp0Ch4BzW6jJOD6r1+dxsYVNttN43gWsNSXLvcg/8aX6w0ASF765SKEwttttttthOd3wscIDFEsDzbda8FkdLH/D4t7KMs6vKGep6K3NRzP+q8nZdqqAcD1zuTESKj6IKKbvuZMGMi0qGdY7049ygxi27gyHKJkniPkdqqAcD1PvknlKUUIA9YnRbY8

**OBS:** Nunca exponha suas credenciais de acesso!!! A credencial acima é um exemplo falsificado, só para ilustrar.

## Questão 01 - Amazon EC2

[Documentação do comando describe-instances](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/describe-instances.html)

Crie algumas máquinas virtuais para o exercicio.

Com linhas de comando execute 10 comandos para testar o EC2. Comandos para listar dados das máquinas virtuais, listar em formatos diferentes, usar filtros, criar, interromper, finalizar, etc.

Mostre cada comando e o resultado (texto ou imagens).

## Questão 02 - Amazon S3

[Documentação do comando s3](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/index.html)

Com linhas de comando execute 10 comandos para testar o S3. Comandos para listar buckets, arquivos dos buckets, copiar, mover, apagar arquivos, apagar bucket, etc.

Mostre cada comando e o resultado (texto ou imagens).



