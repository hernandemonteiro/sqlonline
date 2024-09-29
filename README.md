# SQL Online IDE

Essa é uma plataforma onde podemos rodar nossos códigos SQL online e testar conhecimentos,
a ferramenta pode ser acessada, através do link abaixo:

[https://sqliteonline.com/](https://sqliteonline.com/)


## Notas

para retornar um texto com a consulta podemos usar:

SELECT UPPER(' pessoa colaboradora ' || nome || ' de CPF ' || cpf || ' possui o seguinte endereço: '
            || endereco) AS texto
            FROM Colaboradores;

Essa query retorna uma coluna texto com a busca concatenada no formato que pedimos e com o Texto em maiusculo,
podemos usar o texto em minusculo com a função LOWER ou não usar função de string;
