# UnoparWorkStation
Repositório para ultimo trabalho da Unopar ADS06


1. Controle de Calçado: Neste controle que representa os calçados, é
descrito o nome do calçado, a qual coleção ele pertence, qual o menor
tamanho e o maior tamanho, qual a cor do calçado e o preço de custo.
_________________________________________________________________________
2. Controle de Produção: Neste controle é armazenado as informações
referentes ao lote de produção de calçados como um código de
produção, código do calçado a ser produzido, data de produção,
tamanho do calçado produzido e a quantidade de calçados produzida.
_________________________________________________________________________
3. Controle de Cliente: Neste controle, temos as informações do nosso
cliente como nome do cliente, nome da loja do cliente, endereço do
cliente, CNPJ do cliente, CPF do dono da loja, telefone de contato.
_________________________________________________________________________
4. Controle de Pedido: Neste controle, registramos os dados do pedido do
cliente como o nome do cliente, o produto, o tamanho e a quantidade.
Lembrando que um pedido pode conter diversos produtos, aliás quanto
mais, melhor. Ainda no pedido temos o valor de cada item, um valor
Análise e Desenvolvimento de Sistemas
total por item, um valor prévio da soma de todos os itens, um desconto
e o valor final a ser pago pelo cliente.
_________________________________________________________________________
5. Controle de Entrega dos Pedidos: Neste controle, precisamos associar
os pedidos à entrega dos mesmos até o nosso cliente.
Como regra de negócio, podemos citar as seguintes:
- Inicialmente é feito o cadastro do calçado que será produzido.
- Em seguida, é cadastrado as produções de calçados que ficarão em estoque
para serem vendidas.
- Depois cadastram-se os clientes e os pedidos dos clientes.
- E por último são geradas as ordens de entrega de pedido.
- Um cliente pode fazer diversos pedidos, porém um pedido é de um único
cliente.
- Um pedido pode conter diversos calçados, assim como um calçado pode
estar em diversos pedidos.
- Uma entrega pode conter diversos pedidos, mas um pedido está somente em
uma entrega.


Tarefa 1
- Desenvolver um aplicativo Android para os postos de venda da fábrica de
calçados Flor de Liz, este aplicativo terá como objetivo tornar eficiente a gestão
do negócio. Deverá conter os seguintes requisitos:
 Cadastro de Clientes: deverá permitir a inclusão de novos clientes
atendidos nos postos de vendas, bem como a manutenção do mesmo
(edição dos dados caso necessário)
 Produtos: essa funcionalidade será mais para consulta dos produtos
criados pela fábrica de calçados Flor de Liz, neste caso ele deverá
consumir da base de dados os produtos já existentes, não é necessário
cadastrar novos produtos.
 Emissão de Pedidos: deverá emitir os pedidos feitos em cada posto de
venda.
_________________________________________________________________________
Tarefa 2
- Como nosso aplicativo deverá se interligar com a fábrica para consumir os
dados dos produtos, devemos fazer um levantamento da estrutura de rede necessária
para a utilização do aplicativo nos postos de venda.
Análise e Desenvolvimento de Sistemas
- Fábrica: O que ela precisa ter para que os aplicativos possam consumir dados
e gravarem dados dentro do seu banco de dados?
- Postos de Venda: o que é necessário para que os postos de venda tenham
para se comunicar com a fábrica? Qual os requisitos de segurança que devem ser
tomados?
_________________________________________________________________________
Tarefa 3
- Desenvolver visões gerenciais, gráficos, usando uma ferramenta de Business
Intelligence a partir dos dados gerados pela emissão dos pedidos.
Os relatórios gerenciais, são relatórios que demostram como esta as atividades
da empresa, um exemplo é o relatório de número de pedidos por postos de vendas,
outro exemplo é número de produtos vendidos por mês.
