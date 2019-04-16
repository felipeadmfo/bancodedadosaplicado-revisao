# Criação das Tabelas

Serão criadas três tabelas: Setor, cargo e funcionario.

Cada uma das tabelas possui uma chave primária com prefixo ID seguido do nome da tabela.

Setor: ID_SETOR
Cargo: ID_CARGO
Funcionario: ID_FUNCIONARIO

Na script de criação as colunas que servem de chave primária são acompanhadas da definação "identify", que podemos considerar como “auto increment” no MySQL. Isso indica que a coluna receberá valores sequenciais automáticos.

Na definição, a tabela funcionário é considerada "fraca" em relação a setores e cargos, uma vez que depende delas. 