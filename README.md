# Levantamento-de-requisitos-3
# Aluno: Murilo Santos Souza, Turma C, ADS noturno
# RA: 2038823
# Cenário: Sistema de Gestão de Estoque para uma Loja de Eletrônicos 
# Descrição do Escopo 
Uma loja de eletrônicos está procurando um sistema de gestão de estoque para 
controlar o inventário de produtos em suas lojas físicas e online 
# Necessidades do Software:  
-  Registro de Produtos: O sistema deve permitir o registro de novos produtos, 
incluindo informações como nome, descrição, preço e quantidade em 
estoque. 
- Monitoramento de Estoque: O sistema deve monitorar os níveis de estoque 
de cada produto e emitir alertas quando os estoques estiverem baixos.
- Vendas e Pedidos: O sistema deve registrar vendas e pedidos de produtos, 
atualizando automaticamente os níveis de estoque. 
- Gestão de Fornecedores: O sistema deve manter registros de fornecedores 
de produtos, incluindo informações de contato e histórico de pedidos.
- Relatórios de Desempenho: O sistema deve gerar relatórios sobre o 
desempenho de vendas e o movimento de estoque para ajudar na tomada 
de decisões.
# Métodos Utilizados para a Coleta de Requisitos:
Para garantir que o Sistema de Gestão de Estoque atenda de forma às necessidades da loja de eletrônicos, foi de extrema importância aplicar diversas combinações de métodos de levantamento de requisitos. Estes permitiram entender o cenário atual, identificar problemas nos processos que já existiam e levantar expectativas dos usuários quanto ao novo sistema. Os métodos usados foram:

1. Entrevistas
As entrevistas foram feitas principalmente com os stakeholders da empresa, incluindo o gerente no meio destes, pessoal do estoque, setor de compras, equipe de vendas e membros da equipe de TI. Esse método permitiu a obtenção de  uma visão das atividades rotineiras, dificuldades enfrentadas e necessidades típica de cada área. As entrevistas foram semiestruturadas, dando espaço tanto para perguntas direcionadas quanto para observações espontâneas, melhorando a coleta de informações.

2. Questionários
Foram cirados questionários com perguntas objetivas e abertas, distribuídos entre os funcionários das lojas físicas e da equipe de atendimento online. Esse método permitiu obter uma amostra bem maior de percepções e opiniões sobre os processos atuais de controle de estoque, além de sugestões de melhorias. Os questionários ajudaram a identificar padrões de usabilidade e necessidades comuns entre diferentes áreas e funções da empresa.

3. Observação Direta
Durante o processo de levantamento, foram realizadas visitas às lojas físicas para observar o funcionamento do processo de controle de estoque e atendimento ao cliente em tempo real. A observação direta permitiu identificar aberturas operacionais, como por exemplo: atrasos na reposição de produtos, duplos registros e falhas de comunicação entre os setores. Também foram notadas práticas informais adotadas pelos funcionários que não estavam documentadas, prém poderiam ser formalizadas e otimizadas no novo sistema.

4. Reuniões de Brainstorming
Sessões de brainstorming foram organizadas com representantes de todaas as áreas. Nessas reuniões, os participantes foram incentivados a propor soluções, discutir melhorias e compartilhar suas expectativas em relação ao sistema. Esse método foi útil para promover o Adesão dos usuários e a geração de ideias criativas e inovadoras.

5. Análise de Documentos
Também foi realizada uma análise detalhada de documentos utilizados nos processos atuais, como planilhas de controle de estoque, relatórios de vendas, históricos de pedidos e contratos com fornecedores. Esse método ajudou a mapear o fluxo de trabalho vigente e identificar informações que precisariam ser adicionadas ao novo sistema. Está análise forneceu Materiais importantes para o desenho dos requisitos funcionais.

6. Prototipagem Inicial
Após o levantamento inicial dos requisitos, foram criados protótipos de telas e fluxos de navegação com o objetivo de validar os requisitos com os usuários. Isso possibilitou uma visualização antecipada do sistema, ajudando a refinar funcionalidades, identificar requisitos adicionais e ajustar pontos de uso antes da implementação. Esse processo reduziu ambiguidades e alinhou as expectativas dos stakeholders.

A utilização combinada desses métodos possibilitou um levantamento de requisitos mais completo e alinhado com as verdadeiras necessidades da loja. Além disso, garantiu que os usuários finais também fossem ouvidos, o que forneceu contribuições significativas para a aceitação e sucesso do sistema após sua implementação.
# ✅ Requisitos Funcionais (RF)
RF01 – Cadastro de Produtos:
O sistema deve permitir o cadastro de novos produtos, incluso nome, descrição, código, categoria, preço de venda e quantidade inicial em estoque.

RF02 – Edição e Exclusão de Produtos:
O sistema deve permitir a total edição dos dados de produtos cadastrados e a exclusão caso necessário, desde que o mesmo não esteja vinculado a vendas realizadas.

RF03 – Monitoramento de Estoque:
O sistema deve monitorar automaticamente os níveis de estoque e emitir alertas quando um produto atingir o nível crítico definido.

RF04 – Registro de Vendas:
O sistema deve registrar as vendas realizadas nas lojas físicas e online, atualizando os níveis de estoque automaticamente.

RF05 – Registro de Pedidos a Fornecedores:
O sistema deve permitir o registro de pedidos de reposição de produtos, com possibilidade de acompanhar o status do mesmo.

RF06 – Cadastro e Gestão de Fornecedores:
O sistema deve permitir o cadastro e a manutenção de dados de fornecedores, incluso nome, CNPJ, contato e histórico de pedidos.

RF07 – Relatórios de Vendas:
O sistema deve gerar relatórios periódicos de vendas, por produto, por loja e por período.

RF08 – Relatórios de Movimentação de Estoque:
O sistema deve gerar relatórios detalhados de entradas e saídas de produtos, perdas e transferências entre unidades.

RF09 – Controle de Estoque Multicanal:
O sistema deve permitir o controle de estoque separado por loja física e por canal online.

# ✅ Requisitos Não Funcionais (RNF)
RNF01 – Usabilidade:
A interface do sistema deve ser amigável, com menus intuitivos e linguagem acessível, permitindo o uso por operadores com baixo nível de familiaridade com tecnologia.

RNF02 – Acessibilidade e Responsividade:
O sistema deve ser acessado via navegador e ter design responsivo, adequando-se a diferentes dispositivos (computadores, tablets e smartphones).

RNF03 – Segurança:
O sistema deve implementar autenticação de usuários, com níveis de acesso (administrador, operador, gestor) e criptografia de dados sensíveis de acordo com a LGDP.

RNF04 – Backup e Disponibilidade:
O sistema deve realizar backups automáticos diários em nuvem e garantir funcionamento estável durante o horário comercial.
