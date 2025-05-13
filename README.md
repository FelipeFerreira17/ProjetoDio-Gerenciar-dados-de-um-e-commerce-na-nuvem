# Gerenciar-dados-de-um-e-commerce-na-nuvemProjetoDIO
Desafio de projeto da DIO sobre gerenciar dados de um e-commerce na nuvem.

O projeto é de desenvolver uma solução para armazenar e gerenciar dados em um e-commerce na nuvem com foco em escalabilidade, segurança e eficiência.

##Primeiros passos.
Aqui é onde criamos um grupo de recursos.

No portal do Azure vá em Resource groups e crie um.


##Criação do Azure SQL

No portal do Azure, vá no seu grupo de recursos criados e aperte em create

Selecione o Azure Database.

Lá criaremos um single database.

Iremos criar no modo Serverless.

![2025-05-10](https://github.com/user-attachments/assets/6272e739-84db-4277-be9c-6ab0a88f8d36)

![2025-05-10 (5)](https://github.com/user-attachments/assets/35709231-d4e9-4ad8-99a7-aaa5b96ad48e)

##Criação do Storage Account

###Nessa etapa criaremos o Storage para armazenar as imagens.

Vá em storage account e crie uma conta de armazenamento.

Com o Storage criado, crie um container blob e dê um nome a ele.

Com o Azure SQL e o Storage criados devemos ter a seguinte estrutura:

![2025-05-10 (1)](https://github.com/user-attachments/assets/4df7ae9e-e1b6-4515-a9d2-ae8a0f24db48)

##Trabalhar no código para gerar uma interface de e-commerce

###Nessa etapa vamos trabalhar no código fornecido pelo professor da DIO para criar a interface, podendo assim fazer o cadastro dos produtos.

Imagem da parte do código

![2025-05-13 (2)](https://github.com/user-attachments/assets/4c0902f7-09cc-4870-a862-dc5ead2e090d)

O código completo está no [GitHub da DIO](https://github.com/digitalinnovationone/Microsoft_Application_Platform/tree/main/Labs/Lab01)



