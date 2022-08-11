Problemas encontrados no decorrer do curso:

- Ao iniciar o banco de testes com o arquivo data.sql para popular inicialmente, estava gerando o erro: Table "TB_PRODUCT" not found (this database is empty).

Solução: passar a propriedade spring.jpa.defer-datasource-initialization=true no arquivo application-test.properties.