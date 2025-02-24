# Script SQL para Criação de Tabelas Temporárias
Este script SQL tem como objetivo facilitar a criação de tabelas temporárias no banco de dados, um recurso essencial para a realização de operações e consultas temporárias sem a necessidade de modificar a estrutura permanente do banco. O uso de tabelas temporárias é uma prática recomendada para otimizar processos complexos e garantir que os dados temporários sejam manipulados de forma eficiente.

## O que são Tabelas Temporárias?
As tabelas temporárias são tabelas criadas e usadas apenas durante a sessão ou transação atual. Elas são úteis para armazenar resultados intermediários de consultas, realizar cálculos temporários e manipular dados que não precisam ser persistidos. Quando a sessão ou transação termina, a tabela temporária é automaticamente descartada.

O uso de tabelas temporárias é fundamental no desenvolvimento de consultas SQL complexas, pois permite:

- Armazenar dados intermediários: Ao executar consultas ou operações que envolvem várias etapas de processamento, você pode armazenar dados temporários em uma tabela temporária para facilitar a manipulação e evitar repetições de cálculos.

- Melhorar a performance: Em consultas grandes ou complexas, as tabelas temporárias ajudam a dividir as operações em etapas menores e mais gerenciáveis, podendo melhorar o desempenho, especialmente quando é necessário manipular grandes volumes de dados.

- Evitar mudanças permanentes: Ao usar tabelas temporárias, você não altera permanentemente o banco de dados, mantendo sua integridade intacta, o que é crucial para garantir a consistência dos dados em ambientes de produção.

- Isolar dados temporários: Elas são criadas e descartadas de forma automática, garantindo que você não precise se preocupar com a limpeza de dados temporários após o término de uma operação ou sessão.
