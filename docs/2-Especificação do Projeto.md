# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto


## Personas

1. Salvando o Verde é uma ONG criada em 2017 pela bióloga Eva Carvalho juntamente ao seu marido José de Souza. A organização nasceu pelo desejo de Eva em tornar sua formação e área de pesquisa ainda mais ativa dentro do meio científico, proporcionando ações concretas e agregando pessoas dispostas a sua missão de preservação ambiental. Desde antes de sua fundação, Eva já procurava voluntários interessados em colaborar com os objetivos da instituição. Diversas campanhas foram realizadas através das redes sociais e a ONG é cada vez mais ativa nesse canal de comunicação. Eva entende que a população e os formadores de opinião têm um papel fundamental no convencimento das autoridades, de forma a garantirem o acesso de todos aos serviços de saneamento básico. É tanto que a na fundação da instituição essa ideia está expressa na visão da ONG, que tem como princípio informar as pessoas para promover a mudança. As mídias são parte essencial do trabalho pois expõe ao público os importantes serviços prestados para essa nobre causa. Muito ligada ao meio digital, porém pouco entendida sobre o assunto, Eva busca meios mais fáceis e intuitivos de obter informações a respeito do serviço de saneamento das cidades em que a ONG atua. Segundo ela, o acesso fácil a esses dados são parte chave dos planos de ação, facilitando a cobrança das empresas prestadoras de serviços ligados ao tratamento de esgoto e possibilitando a mobilização de pessoas em prol de exigir mudanças. A ONG ainda participa ativamente junto aos órgãos licenciadores e tem a EVA como conselheira nos Conselhos de Política Ambiental, que são órgãos colegiados que deliberam em nível estadual sobre as políticas de meio ambiente, concedem licenciamento ambiental aos empreendimentos, dentre outros.

2. Franciso tem 26 anos, é casado, pai de família, possui uma renda equivalente a três salário mínimos, possui plano de saúde, paga seus impostos e reside na zona leste de Belo Horizonte, capital de Minas Gerais, localizada na região Sudeste do país. Na região onde mora, existe o acesso ao saneamento básico, porém, existe a  necessidade de informações mais claras e consolidadas, relativas ao saneamento básico, quais são os seus direitos como cidadão e quais os órgãos compententes responsáveis por tais questões, para que, se necessário, cobranças e medidas sejam solicitadas.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--|--|--|
|ONG                 | Visualizar informações de investimento em infraestrutura de esgoto | Direcionar planos de ação e elaborar projetos de lei   |
|Cidadão Comum       | Encontrar informações sobre saneamento básico e direitos constitucionais sobre tal | Cobrar providências de Órgãos competentes |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-------------------------|----|
|RF-001| O sistema deve permitar a consulta, alterações e exclusão de dados pessoais do usuário | ALTA | 
|RF-002| O sistema deve permitir realizar a validação do usuário através de um e-mail de confirmação | ALTA |
|RF-003| Deve ser possível ao usuário solicitar a redefinição de sua senha, informando o e-mail cadastrado | ALTA |
|RF-004| Consulta de gráficos, relatórios entre outros, sobre saneamento básico | ALTA |
|RF-005| Consulta de informações sobre Órgãos Competentes: Prefeituras - São Paulo - SP: http://www.capital.sp.gov.br/ Belo Horizonte - MG: https://prefeitura.pbh.gov.br/ Rio de Janeiro - RJ: https://prefeitura.rio/ Vitória - ES: https://www.vitoria.es.gov.br/ |ALTA|


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003| O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com O.S. Windows, Linux e macOS | ALTA |
|RNF-004| O sistema deve respeitar o tempo máximo de 160 segundos durante processamentos | MEDIA |
|RNF-005| A interface deve ser agradável e de fácil utilização | ALTA 
|RNF-006| O sistema deve ter uma boa usabilidade | MEDIA |
|RNF-007| Bloquear novo cadastro do usuário caso já exista algum registrado com o mesmo e-mail e login informado | ALTA |
|RFN-008| As imagens submetidas no sistema deverão estar em um nos formatos jpg, jpeg, png, bmp ou gif | MEDIA |
|RNF-009| O sistema deverá ser desenvolvido na linguagem C# | ALTA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| O projeto precisa de um banco de dados                |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
