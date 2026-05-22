DROP DATABASE JSON_DATABASE;
CREATE DATABASE JSON_DATABASE;
use JSON_DATABASE;

CREATE TABLE dados_json(
    json char(250)
    );
    
 INSERT into dados_json VALUES(
    '{
     "nome":"Jose",
     "sobrenome":"cardoso",
     "idade":25,
     "ID": "001"
     }'
     );
     
     SELECT * FROM dados_json;
     
    CREATE TABLE json_dados(
     teste_json json
        );
        
    INSERT INTO json_dados VALUES(
        '{
        "nome":"Lucas",
        "sobrenome":"Silva",
        "idade":20,
        "ID":"002"
        }'
        );
