# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1. Salvando o Verde é uma ONG criada em 2017 pela bióloga Eva Carvalho juntamente ao seu marido José de Souza. A organização nasceu pelo desejo de Eva em tornar sua formação e área de pesquisa ainda mais ativa dentro do meio científico, proporcionando ações concretas e agregando pessoas dispostas a sua missão de preservação ambiental. Desde antes de sua fundação, Eva já procurava voluntários interessados em colaborar com os objetivos da instituição. Diversas campanhas foram realizadas através das redes sociais e a ONG é cada vez mais ativa nesse canal de comunicação. Eva entende que a população e os formadores de opinião têm um papel fundamental no convencimento das autoridades, de forma a garantirem o acesso de todos aos serviços de saneamento básico. É tanto que a na fundação da instituição essa ideia está expressa na visão da ONG, que tem como princípio informar as pessoas para promover a mudança. As mídias são parte essencial do trabalho pois expõe ao público os importantes serviços prestados para essa nobre causa. Muito ligada ao meio digital, porém pouco entendida sobre o assunto, Eva busca meios mais fáceis e intuitivos de obter informações a respeito do serviço de saneamento das cidades em que a ONG atua. Segundo ela, o acesso fácil a esses dados são parte chave dos planos de ação, facilitando a cobrança das empresas prestadoras de serviços ligados ao tratamento de esgoto e possibilitando a mobilização de pessoas em prol de exigir mudanças. A ONG ainda participa ativamente junto aos órgãos licenciadores e tem a EVA como conselheira nos Conselhos de Política Ambiental, que são órgãos colegiados que deliberam em nível estadual sobre as políticas de meio ambiente, concedem licenciamento ambiental aos empreendimentos, dentre outros.

2. Eliana tem 26 anos, é casada, mãe de família, possui uma renda equivalente a um salário mínimo, não possui plano de saúde, paga seus impostos e reside em uma área irregular de uma capital, localizada na região Sudeste do país. Na região onde mora, os esgotos não são coletados, nem tratados, além da falta de abastecimento de água, que é conseguida através de furtos, por meios de ligações clandestinas. Partindo destes pressupostos, devida à falta de informação, a devida importância para tal, e quão sérios são os impactos causados em sua vida, advindos destes fatores, Eliana não compreende que, como cidadã, o acesso ao saneamento básico é um direito seu, garantido por lei e o mesmo deve ser cobrado dos governantes responsáveis pelo seu município.

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|ONG                 | Visualizar informações             | Direcionar planos de ação              |
|Cidadão Comum       | Visualizar informações             | Direcionar planos de ação              |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

1. Eu como responsável por uma ONG atuante na área de saneamento básico quero/preciso visualizar informações a respeito da situação da coleta e tratamento de esgoto nas cidades de atuação da minha instituição para direcionar os planos de ação e ajudar mais ativamente na preservação ambiental.

1. Eu como responsável por uma ONG atuante na área de saneamento básico quero/preciso de acesso rápido aos dados do tratamento de esgoto, da eficiência do tratamento e da qualidade da água dos cursos d’água onde são lançados os efluentes tratados nas cidades de atuação da minha instituição para que em uma reunião de licenciamento de um empreendimento possa analisar com agilidade a situação dos empreendimentos de esgotamento sanitário, poder questionar o empreendedor quanto a esses dados e tomar decisões acertadas.

1. Eu como responsável por uma ONG atuante na área de saneamento básico quero/preciso ter acesso material didático sobre o esgotamento sanitário para repassar em palestras sobre saneamento a real situação do saneamento nas cidades em que a minha instituição atua.


> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

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
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
