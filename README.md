- Antes de começar
        
    1. Extraia o conteúdo do arquivo exercicio_sql_8e64656a e abra um terminal na pasta criada
    2. Execute o seguinte comando para criar o banco de dados no seu computador:
        
        ```bash
        bash ./create-database
        ```
        
    3. Execute o seguinte comando para conectar-se ao banco de dados:
        
        ```bash
        bash ./connect-database
        ```
        

Depois da última atualização, o sistema não abre mais! 🆘 Sua avó precisa verificar os dados dos clientes de sua loja, mas não consegue de forma alguma!

Ao saber do problema, você decidiu ajudar sua vózinha, fazendo todo o esforço possível para colocar o sistema no ar novamente.

Enquanto tentava levantá-lo, percebeu que o banco de dados ainda estava ativo, então decidiu escrever uma query para obter os dados do cliente.

A tabela `clientes` tem a seguinte estrutura:

- `id`, numérico
- `nome`, string com no máximo 50 caracteres
- `cpf`, string com 11 caracteres
- `numero_compras`, numérico

Busque pelo cliente com CPF `"22883377446"` na tabela `clientes`.