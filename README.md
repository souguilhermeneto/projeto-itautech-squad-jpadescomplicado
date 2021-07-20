Link do github:

https://github.com/souguilhermeneto/projeto-itautech-squad-jpadescomplicado.git

Considerações:

Este projeto representa a execução de uma API e para esta utilizamos os objetivos:

Construir uma API Spring BOOT que possua 04 endpoints principais:
● Recuperação de todas as contas bancárias;
● Recuperação de detalhes de uma conta bancária (inclusive dados do seu titular);
● recuperação de todos os clientes;
● Recuperação de detalhe de apenas um cliente da lista.

introduzimos as especificações:

Tecnologias:

Banco de Dados: MySQL
API: SpringBoot
Liguagem de programação: JAVA


Modelagem de Dados:
Todo cliente possui os seguintes dados para serem cadastrados
● codigo interno
● nome
● cpf
● telefone
● email

Toda conta bancária possui os seguintes dados
● numero
● agência
● tipo da conta (0 - conta corrente, 1 - poupança, 2 - investimento)
● saldo
● titular da conta

Após start da aplicação, a pagina home com o link relatado a seguir, contém os seguintes endpoints:

link home: http://localhost:8080/

● /contas
● /contas {id}
● /clientes
● /clientes {id}


