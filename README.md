# ProjetoTrabalhodeGraduacao1

# Tema: Aplicação Web/Mobile para E-commerce.

# 1.Introdução
O advento da tecnologia e sua crescente evolução tem influenciado cada vez mais na maneira como as pessoas se socializam nos meios digitais, a maneira como interagem, trocam experiências, produtos e serviços.

Resultante dessa transformação tecnológica temos o E-commerce (Comércio Eletrônico), uma modalidade de transações feitas por meio digitais, através de computadores, tablets, smartphones. Sendo o tipo mais comum de comércio eletrônico as lojas virtuais.

Conforme Mauricio Salvador, presidente da ABComm: Associação Brasileira de Comércio Eletrônico e Membro do Conselho da Ecommerce Foundation publicou em seu livro “Gerente de E-commerce”, o comércio eletrônico como conhecemos surgiu nos Estados Unidos e se popularizou nos anos 90, devido as facilidades de acesso à internet que a população norte-americana começou a ter na época. Já havia uma cultura de compras a distância surgida em meados dos anos 40 através dos “Catálogos Sears”. Um fator que contribuiu para a expansão deste cenário foi o telefone, pois os lares norte-americanos já contavam com esse recurso.
No Brasil, a história do e-commerce é relativamente recente, possuindo aproximadamente duas décadas de existência. Ela vem acompanhando e se desenvolvendo juntamente com desenvolvimento da Internet.

Considera-se, ainda que não haja registros oficiais, a Booknet como uma das primeiras lojas virtuais no Brasil. Foi uma loja online de livros fundada por Jack London por volta de 1995 e que posteriormente, no ano de 1999 viria a ser adquirida e renomeada para Submarino, que por sua vez se uniu à Americanas.com, originando o Grupo B2W.

Conforme o decorrer do tempo o faturamento do e-commerce, bem como o número de consumidores tem aumentado significativamente, não somente no Brasil, mas no mundo todo.

Segundo estudos mais recentes publicados pela UNCTAD (Conferência das Nações Unidas sobre Comércio e Desenvolvimento) em um evento anual (eWeek), mostram que as vendas do E-commerce no mundo atingiram o patamar de 25.6 trilhões de dólares em 2018. Um crescimento de 8% em relação ao ano anterior.

A ABComm teve a oportunidade de participar das últimas duas edições do evento na qual de acordo com análise do grupo estima-se que com relação as vendas para o e-commerce que inclui vendas B2B (bussiness-to-bussinnes) e B2C (bussinnes-to-consumer), elas foram responsáveis por 30% do produto interno bruto global do ano.

## 1.1. Objetivo do Trabalho
O objetivo do trabalho é desenvolver uma aplicação web/ mobile que se configure como um e-commerce através da utilização de tecnologias responsivas.

## 1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir: No Capítulo 2 é feita a fundamentação das tecnologias... O Capítulo 3 apresenta o desenvolvimento da solução... No Capítulo 4 são apresentados os resultados ... O Capítulo 5 apresenta as considerações finais deste trabalho a partir da análise dos resultados obtidos...

# 2.Fundamentação Técnica
Este capítulo apresentará os requisitos da aplicação levantados junto ao cliente para que suas necessidades sejam satisfeitas e as tecnologias que compreenderão uma proposta de solução.

## 2.1 Levantamento de Requisitos do Usuário
Sistema no qual seja possível cadastrar usuários e seus dados pessoais para que os mesmos possam interagir com as mais diversas funcionalidades da aplicação e estarem realizando a compra e encomenda dos pratos.
Deverá ser possível também realizar os cadastros dos pratos bem como os insumos necessários para o seu preparo.
Manter um registro e histórico de vendas dos pratos.
A aplicação também deverá suportar transações financeiras para que a compra dos pratos seja possível e facilite a interação do usuário com a empresa.
A aplicação também deverá conter uma agenda com um cronograma dos pedidos e entregas que serão realizados para auxiliar o chef no preparo e organização da rotina de trabalho.

## 2.2 Tecnologias utilizadas e justificativas
Na composição e desenvolvimento do projeto serão implementadas tecnologias como: Javascript, React, React Native, Node.Js, MySQL.

### 2.2.1 Javascript
O JavaScript é uma linguagem de programação de alto-nível criada em 1995 por Brendan Eich.
Será adotada da implementação por permitir a criação de páginas web com vários elementos de alto nível. Possuir uma curva de aprendizado dinâmica. Permitir a criação de aplicações híbridas através de seus frameworks, ou seja, possibilita a compatibilidade com vários navegadores e plataformas, viabilizando a abrangência de um grande público em conformidade com os requisitos definidos pelo cliente. Mais rápido e mais leve que outras linguagens de programação.

### 2.2.2 React 
Desenvolvido e lançado pelo Facebook em 2013 como uma ferramenta de código aberto. Hoje o React é a biblioteca mais popular do JavaScript por ter uma série de vantagens em sua utilização para a criação de web apps. Voltada para a parte de view das aplicações, as tecnologias que a implementam costumam ser de fácil utilização e criam uma interface eficiente para o usuário.
Essa tecnologia também permite o reaproveitamento de componentes e código.

### 2.2.3 React Native
Lançado pelo facebook em 2015 o React Native é um framework baseado no React, para a criação e desenvolvimento mobile, voltado tanto para Android quanto para IOS, utilizando o JavaScript.
Os motivos para a sua adesão se assemelham aos das tecnologias já mencionadas anteriormente. Sendo eles: Rápida curva de aprendizagem, com um código legível e de fácil compreensão. Viabilidade e agilidade no ciclo de desenvolvimento pois grande parte do código é reaproveitado.

### 2.2.4 Node.js
Node.js poder ser compreendido como um ambiente de execução javascript server-side. Ele possibilita a criação de aplicações standalone em uma máquina, eliminando a dependência do browser para a execução. Dentre as vantagens que motivam sua adoção estão a sua alta capacidade de escala. Flexibilidade, possui o NPM (node package manager), um poderoso gerenciador de pacotes para fazer integração com banco de dados. Leveza, pois subir uma aplicação implementando o Node.js não exige muitos recursos computacionais. Viabiliza o deploy se utilizado em conjunto com outras ferramentas como o Docker, pois há um ganho de velocidade na replicação das máquinas, algo importante para ambientes escaláveis.

### 2.2.5 MySQL
Desenvolvido por uma empresa sueca chamada MySQL AB em 1994, o MySQL caracteriza-se como um Banco de Dados relacional. Dentre os motivos que impulsionam sua adoção estão o fato de ser uma ferramenta de código aberto. Compatibilidade com diversas plataformas. Garante um alto desempenho e velocidade além de cumprir com requisitos de segurança, onde recursos de verificação e criptografia de senhas estão disponíveis.

# 3. Desenvolvimento
Este capítulo compreenderá os conceitos acerca do desenvolvimento da aplicação.

## 3.1 Arquitetura do Sistema
Formulado por Trygve Reenskaug em 1979 a arquitetura Model-view-controller (MVC) pode ser caracterizada como um padrão de arquitetura de software popular no desenvolvimento web. Seu princípio consiste na divisão da aplicação em 3 camadas (Model-view-controller), interconectadas entre si. Esse padrão de arquitetura permite a separação da interface do usuário das regras de negócio, o que traz uma series de benefícios, como: reutilização de código e facilidade na manutenção.
O Model é a camada responsável pelo acesso e manipulação dos dados da aplicação, nela estão as funções de consultas a base de dados.
A View é a interface que será apresentada ao usuário, contém os arquivos de formatação da página.
O Controller, faz a comunicação entre o Model e o View. Ele recebe as requisições dos usuários, utiliza a camada Model para obter os dados e posteriormente utiliza a View para renderizar a saída das informações para os mesmos.


# Referências

https://blog.betrybe.com/desenvolvimento-web/aplicacoes-web/
https://tegra.com.br/aplicacoes-web/
https://www.diegomacedo.com.br/entendendo-as-aplicacoes-web/
https://www.impacta.com.br/blog/desenvolvimento-de-aplicacoes-web-tire-suas-duvidas-sobre-o-assunto/
https://www.ecommercebrasil.com.br/noticias/e-commerce-futuro-tecnologia-dados/
https://www.significados.com.br/e-commerce/
https://www.traycorp.com.br/conteudo/evolucao-do-ecommerce/
https://www.senior.com.br/blog/tecnologia-transformacao-e-o-futuro-do-e-commerce-no-brasil

https://www.comschool.com.br/n/ecommerce-no-mundo#:~:text=Crescimento%20do%20E-commerce%20no%20mundo%20atinge%20U%24%2025.6,mais%20de%201.4%20bilh%C3%A3o%20pessoas%20compraram%20pela%20Internet.
https://news.comschool.com.br/a-historia-do-e-commerce-no-brasil/#:~:text=%20A%20Hist%C3%B3ria%20do%20e-commerce%20no%20Brasil%20,2007%20come%C3%A7a%20a%20descentraliza%C3%A7%C3%A3o%20do%20e-commerce...%20More%20

https://neilpatel.com/br/blog/e-commerce-no-brasil/
https://abcomm.org/institucional/
O que é JavaScript (hostinger.com.br)
O Que é React e Como Funciona? - Guia para Iniciantes (hostinger.com.br)
O que é React Native? | Brasil Code |
Node.js - O que é, como funciona e quais as vantagens (opus-software.com.br)
O Que É MySQL - Um Guia Para Iniciantes (hostinger.com.br)
MVC - O padrão de arquitetura de software (oficinadanet.com.br)

