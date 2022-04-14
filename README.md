# SQL e MySQL

Roda na porta: 165.122.111.11:3306

CRUD

Cada coluna tem(principais items): nome, tipo, tamanho, se aceita NULL, valor padrão, 

Tipos mais comuns: tinyint, int, float, varchar, text, date, time, datetime, timestamp

id->index primary key e autoincrement.

nome->varchar 100

Comandos importantes: select, where, 

## Exemplos de comandos:

SELECT * FROM table nome_da_tabela;

SELECT nome FROM products;

SELECT nome, preço FROM products;

SELECT * FROM products WHERE id_fornecedor = 6;

SELECT * FROM users WHERE name = 'Pedro';

SELECT * FROM products WHERE preco >= 150;

SELECT * FROM products WHERE preco != 150;

SELECT * FROM products WHERE estoque < minestoque;

SELECT * FROM products WHERE preco = 150 AND tamanho = 250;

SELECT * FROM products WHERE preco = 150 OR preco = 250;

SELECT * FROM products WHERE preco > 150 AND preco < 250;

SELECT * FROM users WHERE name LIKE "lhe";

SELECT * FROM users WHERE name LIKE "%a%";

SELECT * FROM fornecedores WHERE id_fornecedor IN (1, 6);

WHERE x BETEWEEN y;

ORDER BY - asc desc

SELECT * FROM produtcs LIMIT 4;

SELECT * FROM produtcs LIMIT 0,4;

SELECT COUNT(*) FROM users;

SELECT COUNT(*) AS contagem FROM users;

SELECT AVG(preco) FROM products;

SELECT SUM(estoque) AS soma FROM products;

SELECT * FROM produtcs GROUP BY id_fornecedor;

(SUBQUERY) e JOIN -> os dois servem para coisas parecidas

INNER JOIN, LEFT JOIN, 

INSERT INTO

UPDATE

DELETE










