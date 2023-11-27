<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>

<font size="+15"><center>
*&lt;Pizza-Express&gt;*
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Requisitos funcionais e não-funcionais](#requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-de-classes)
- [Diagrama de Componentes](#diagrama-de-componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)


# Autores

*Mateus Mendes Cabral

*Thiago Felipe Garcia

# Descrição do projeto

O projeto tem como objetivo fundamental revitalizar a Pizza-Express, uma rede de fast-food que entrega em casa, na qual, enfrentou recentes desafios devido à perda de 30% do seu rendimento de vendas para um concorrente que garante entrega em apenas 30 minutos. Para solucionar isso e enfrentar a concorrente, a empresa terá dois sistemas de software, sendo eles, um sistema voltado para a melhoria da experiencia do cliente, tornando o processo de pedido e entrega eficiente e mais rapido. O outro sistema buscar ter mais eficiencia nas operações nas lojas da rede.

# Requisitos funcionais e não-funcionais
*Requisitos funcionais:* 1.Sistema de atendimento do pedido: Clientes poderem fazer o pedido online. Sistema identifica a loja Pizza-Express da rede mais proxima a localização do cliente. Sistema calcula o tempo estimado de entrega e exibiro contador ao cliente. Clientes podem rastrear o pedido em tempo real. Sistema deve suportar pagamentos online seguro, garantindo a proteção dos dados financeiros dos clintes. 2.Sistema de suporte as operações: Loja deve receber pedidos da rede de forma eficiente. Sistema monitora os ingredientes dispoiniveis em tempo real e quando necessário da um gatilho no fluxo para que a reposição seja feita. Sistema gera relatórios BI de desempenho das lojas, incluindo métricas de tempo médio de preparação e as notas dadas dos clientes.  
*Requisitos não funcionais:* Quando possivel, sistema deve garantir que a entrega seja feita em menos de 30 minutos. Deve existir uma segurança rigorosa dos dados dos clientes e seus pagamentos, a segurança e privacidade deve estar de acordo com as regulamentações. A interfacer do usuario deve ser intuitiva para facilitar a realização de pedidos, e operação eficiente por parte dos funcionarios. Os sistemas deve estar disponiveis, e preparados com planos de contigencia para lidar com falhas. Por ultimo, a equipe deve trabalhar de forma colaborativa, reconhecendo a importancia crítica do projeto para a empresa permanecer no mercado.

# Diagrama de casos de uso

![Texto](/img/Diagrama%20de%20casos%20de%20uso.jpeg)


# Descrição dos casos de uso

![Texto](/img/Descrição%20casos%20de%20uso%201.jpeg)
![Texto](/img/Descrição%20casos%20de%20uso%202.jpeg)
![Texto](/img/Descrição%20casos%20de%20uso%203.jpeg)
![Texto](/img/Descrição%20casos%20de%20uso%204.jpeg)
![Texto](/img/Descrição%20casos%20de%20uso%205.jpeg)


# Diagrama de sequencia

![Texto](/img/Diagrama%20de%20Sequencia.jpeg)


# Diagrama de classes

![Texto](/img/Diagrama%20de%20Classes.jpeg)

# Diagrama de Componentes

![Texto](/img/Diagrama%20de%20Componentes.jpeg)

# Decisões de arquitetura

*Requisitos de segurança:*
Ao analisar a estrutura do projeto apresentado, chegamos à conclusão que além dos requisitos mínimos e obrigatórios para qualquer tipo de aplicação, identificamos que o sistema deve incluir medidas de proteção específicas nos seguintes recursos:

•	Usuário Unidade Pizza-Express
Tendo em mente que as unidades terão acesso a dados e informações extremamente sensíveis, é explicito que os usuários utilizados possuirão permissões de alto nível dentro do sistema, logo, é fundamental que estes sejam rigorosamente protegidos e blindados contra possíveis ataques e tentativas de invasão.
Também é necessário restringir o acesso de cada usuário, de forma que os colaboradores possuam os poderes pertinentes ao cargo ocupado, como exemplo: gerentes, auxiliares, etc.

•	Escopo de Pagamento
Ao lidar com operações monetárias dentro do sistema, é de extrema importância que o mesmo seja arquitetado para evitar toda e qualquer falha, bem como realizar o devido tratamento destes pagamentos, para que assim o cliente não tenha nenhum prejuízo durante a utilização.

# Diagrama de implantação

![Texto](/img/Diagrama%20de%20implantação.jpeg)