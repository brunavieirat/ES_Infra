# ES_Infra

Repositório dedicado às aulas de Infra e Cloud do MBA de Engenharia de Software da Impacta

Exercio 1 - Subir uma Maquina Virtual com MYSQL instalado utilizando VAGRANT . Ser acessivel pela porta 3306.

/_Criando a Tabela no MYSQL _/
CREATE TABLE Exercicio1
-> (
-> ID MEDIUMINT NOT NULL AUTO_INCREMENT,
-> AULA varchar(20),
-> STATUS varchar(10),
-> PRIMARY KEY (ID_TESTE)
-> )

/_ Resultado após inserção de 1 registro _/
mysql> select \* from Exercicio1;
+----------+------+--------+
| ID_TESTE | AULA | STATUS |
+----------+------+--------+
| 1 | 1 | 1 |
+----------+------+--------+
1 row in set (0.00 sec)
