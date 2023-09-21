## Problema
Considere o estudo de caso a seguir para responder as questões a seguir utilizando análise por pontos de função:

A farmácia XYZ é uma farmácia de pequeno porte, onde trabalham apenas dois funcionários: o próprio farmacêutico e uma funcionária. O controle das atividades realizadas na farmácia é feito de forma manual, o que aumenta as responsabilidades dos funcionários quanto a questão de segurança e integridade das informações.

Nas operações de entrada e saída de material são emitidas notas fiscais, que são os únicos registros disponíveis para se ter noção do que se comprou, o que se tem e o que se vendeu. Contudo, esses dados são insuficientes para o controle efetivo a eventuais falhas humanas que possam ocorrer nesse processo e que significariam uma compra excessiva ou escassez de material, causando prejuízos e até perda de clientes.

Não há necessidade de emitir relatórios muito complexos. O problema maior está na falta de um controle automático de estoque, pois este é feito visualmente, podendo acarretar nas falhas mencionadas. O mesmo acontece com o controle das compras, vendas e demais atividades.

Os remédios comercializados são cadastrados em um catálogo e organizados em ordem alfabética, o qual é fornecido pela Associação Brasileira do Comércio Farmacêutico (ABCFarma). Este catálogo é acessível somente por proprietários de farmácias assinantes da Revista ABCFarma.

Após análise da estrutura do ambiente farmacêutico e do compreendimento dos problemas nele encontrados e apresentados, determinou-se que uma solução seria o desenvolvimento de um sistema que auxiliasse os funcionários em suas atividades de modo que as mais rotineiras fossem feitas automaticamente, garantindo assim, informações concisas e seguras e com velocidade superior àquela que tem sido feita manual e visualmente.

Para determinar o custo total desse sistema, fez-se o seguinte levantamento de funcionalidades/interações do sistema:

a) Funcionalidades:

- Entrada de login;

- Cadastramento de funcionários;

- Cadastramento de clientes;

- Cadastramento de fornecedores;

- Cadastramento de itens comprados;

- Cadastramento de vendas;

- Cadastramento de contas a pagar;

- Busca de medicamentos por nome de referência;

- Busca de medicamentos genéricos;

- Busca de medicamentos por princípio ativo;

- Busca de medicamentos por fornecedor;

- Busca de medicamentos por laboratório;

- Busca de medicamentos por classe terapêutica;

- Busca de dados dos clientes;

- Relatório de clientes;

- Relatório de fornecedores;

- Relatório de funcionários;

- Relatório de contas a pagar;

- Relatório de contas a receber;

- Relatório de estoque.

b) Mensagens que serão emitidas pelo sistema:

- Mensagem de erro para a tela de vendas, caso não seja fornecido o nome do vendedor ou o código do produto e quantidade inválida de itens;

- Mensagem de confirmação de venda;

- Mensagem de confirmação de cancelamento de nota fiscal;

- Mensagem de confirmação de cliente cadastrado;

- Mensagem de confirmação de fornecedor cadastrado;

- Mensagem de confirmação de item cadastrado;

- Mensagem de confirmação de item removido;

- Mensagem de confirmação de funcionário cadastrado;

- Mensagem de erro para cadastramento de itens comprados por fornecedor não cadastrado ou valores negativos;

- Mensagem de login inválido;

c) Arquivos e interfaces:

- Arquivo para a tabela cliente;

- Arquivo para a tabela fornecedor;

- Arquivo para a tabela funcionário;

- Arquivo para a tabela produto;

- Arquivo para a tabela nota fiscal;

- Arquivo para a tabela de forma de pagamento;

- Arquivo para a tabela cargo;

- Uma interface externa para interagir com o sistema ABCFarma.

## Solução
### Análise por Pontos de Função
Para realizar a análise por pontos de função, é necessário identificar os elementos de contagem presentes no estudo de caso fornecido. Os elementos de contagem são: arquivos lógicos internos (ALIs), arquivos de interface externa (AIEs), arquivos de interface de saída (AEOs), campos de dados e transações.

Aqui está uma análise dos elementos de contagem identificados no estudo de caso:

Arquivos Lógicos Internos (ALIs):

Tabela cliente
Tabela fornecedor
Tabela funcionário
Tabela produto
Tabela nota fiscal
Tabela de forma de pagamento
Tabela cargo
Total de ALIs: 7

Arquivos de Interface Externa (AIEs):

Interface externa para interagir com o sistema ABCFarma
Total de AIEs: 1

Arquivos de Interface de Saída (AEOs):

Não foram identificados arquivos de interface de saída no estudo de caso.

Total de AEOs: 0

Campos de Dados:

Os campos de dados não foram especificamente mencionados no estudo de caso, mas podem ser identificados a partir das funcionalidades descritas, como nome, endereço, telefone, etc.

Total de campos de dados: Não especificado

Transações:

As transações podem ser identificadas a partir das funcionalidades descritas no estudo de caso, como entrada de login, cadastramento de funcionários, clientes, fornecedores, etc.

Total de transações: Não especificado

Com base nas informações fornecidas, podemos fazer uma análise preliminar por pontos de função. No entanto, como alguns detalhes não foram especificados no estudo de caso, como o número de campos de dados e transações, a análise final pode variar.

A análise por pontos de função é um método objetivo para medir o tamanho funcional do software, sendo útil para estimativas de custo, produtividade e qualidade. Com os elementos de contagem identificados, é possível realizar o cálculo dos pontos de função utilizando a tabela de complexidade funcional.