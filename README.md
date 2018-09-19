# docs

## Organização Recreio Canoas

Com o intuito de gerenciar informações utilizadas em projetos do condomínio, foi criada a organização **Recreio Canoas**, utilizando uma ferramenta  **totalmente gratuita** que gerencia  repositórios de dados acessíveis a todos. Para ter acesso às informações, basta consultar o link:

[https://github.com/recreiocanoas](https://github.com/recreiocanoas)

Para quem não conhece, o **Github** é um site que gerencia a confecção de programas de computador. Com 28 milhões de usuários e 85 milhões de repositórios, é o maior serviço de gerenciamento de código fonte do planeta. Foi comprado recentemente pela Microsoft por $8.5 bilhões de dólares e seu uso permite que pessoas espalhadas por todo o mundo colaborem em projetos de software, em um processo eficiente e versátil. O site dispõe de [mais informações](https://help.github.com/articles/signing-up-for-a-new-github-account/) sobre os tipos de conta de usuário e de organização.

Ocorre que um programa nada mais é que um texto, ou seja, podemos (sub)utilizar o Github para editar apenas textos, imagens e tabelas, como esse que vocês estão lendo. Para atingir nossos objetivos e melhorar o condomínio, não vamos precisar usar todas as funções do Github, apenas de um treinamento simplificado. Com isso, já seremos capazes de criar, debater, alterar e aprovar textos em  diversas pautas simultâneas sobre assuntos diversos que envolvem o nosso dia a dia.

> Nota: O Github é escrito em, inglês. Contudo, utilizando o navegador Chrome, pode-se traduzir o site para português, bastando clicar o botão direito do mouse e selecionar a opção de tradução, como indicada abaixo. A partir daí a navegação é mantida em português, apesar de alguns termos ficarem meio estranhos. A princípio, poderão ser mencionados comandos em inglês, `marcados desta forma` para diferenciar.

![](https://i.imgur.com/m7K6i7w.png)

## Colaboradores

A ideia é convidar os condôminos a se tornarem membros da organização [Recreio Canoas](https://github.com/recreiocanoas).

A razão dessa iniciativa é facilitar a cooperação em projetos do condomínio. Normalmente, a maior dificuldade tem sido reunir as pessoas em um mesmo local, em uma mesma hora. Essa iniciativa irá permitir que você possa dedicar algumas horas para trabalhar conforme sua vontade e disponibilidade, utilizando sua vocação e capacidade para contribuir em projetos diversos do condomínio.

### Convidando pessoas

Podemos convidar qualquer pessoa para se tornar um membro da organização, usando o seu nome de usuário do Github ou endereço de e-mail. Os colaboradores podem incluir membros da organização ou colaboradores externos. 

Um colaborador externo é uma pessoa que tem acesso a um ou mais repositórios de organização, mas não é explicitamente um membro da organização. Um colaborador externo tem acesso apenas aos repositórios a ele permitidos.

### Membro da organização

Neste primeiro momento, todas as informações estarão disponíveis a todos para leitura, pois a opção **gratuita** que estamos usando só permite repositórios públicos. Ou seja, para tomar conhecimento do conteúdo não é necessário ser um membro da organização. Contudo, se você tem interesse em  colaborar na geração de conteúdo do site, por favor procure a administração do condomínio, informe seu  e-mail e receba o convite para se tornar um membro.

A pessoa sendo um membro explícito da organização poderá:

- Alterar o conteúdo publicado
- Criar equipes
- Ver todos os membros e equipes da organização
- Fazer @menção a qualquer time visível
- Ser um mantenedor de equipe

### Organizando membros em equipes

Agrupando membros da organização em equipes pode-se refletir a estrutura de grupos de trabalho e definir mais facilmente as permissões de acesso aos repositórios. Além disso, pessoas com permissões de mantenedor podem adicionar membros da organização à equipe. 

Os membros da organização podem solicitar para participar de qualquer equipe, basta que um responsável pela equipe aprove a solicitação. Existe ainda a facilidade de se fazer @menções para toda a equipe, por exemplo, `@recreiocanoas/consultivo` em qualquer comentário, questão ou solicitação. Desta forma, todos os membros da equipe serão automaticamente notificados.

## Ciclo do Processo

O processo de contribuição dos colaboradores tem por objetivo evoluir os repositórios da Organização Recreio Canoas. Os diversos colaboradores, distribuídos em equipes, podem trabalhar simultaneamente em diversos assuntos de interesse do condomínio. O ciclo do processo pode ser visto no diagrama a seguir.

![Ciclo do Processo](https://i.imgur.com/bXQ6kzv.png)

### REPO

É o repositório propriamente dito. A organização poderá ter vários repositórios, com finalidades diversas, a serem definidas por nós mesmos. Por definição do processo, sempre existirá a versão oficial do repositório em um ramo (`branch`) chamado de mestre (`master`).

O REPO é composto de diversos arquivos texto, por exemplo, o repositório em que estamos agora foi chamado de `docs` e o arquivo chama-se `readme.md`. Basta navegar na organização Recreio Canoas para verificar que, a princípio, foram criados 3 repositórios: **docs**, **radar** e **consultivo**. A ideia preliminar é que eles seriam usados da seguinte forma:

- **docs**: conteria explicações, treinamentos e informações sobre esse processo.
- **radar**: seria um local para os condôminos proporem seus projetos e ideias.
- **consultivo**: seria uma forma de comunicação da administração do condomínio.

Reparem que toda pasta (`folder`) pode ter um arquivo `readme.md` que é renderizado automaticamente pelo Github. Devemos portanto utilizá-lo para facilitar a navegação pelo site.


### RAMO

Suponha agora que seja iniciado um trabalho por uma pessoa ou equipe, com o objetivo de incluir ou alterar as informações contidas em um REPO. Para isso, deverá ser criado um novo RAMO (`branch`) especialmente para a mudança que será realizada. Após as mudanças serem concluídas, a  pessoa e/ou equipe de trabalho deve fazer uma solicitação de pull (`pull request`), quando então será iniciada a avaliação do RAMO de mudança.

A mudança do REPO não é imediata, dando à comunidade a possibilidade de participar da discussão sobre a mudança proposta pelo RAMO (ou `branch`) de mudança. Com isso, dependendo do caso, podem ocorrer diversas situações:

- As mudanças contidas no RAMO são aceitas pela comunidade. Nesse caso, prossegue-se fundindo (`merge`) as alterações propostas, ou seja, as mudanças propostas pelo RAMO se incorporam ao REPO, passando a fazer parte do repositório. No diagrama, completa-se o ciclo azul, onde o REPO é alterado e o RAMO de mudança pode até ser apagado, pois não tem mais utilidade.

- Se a comunidade (ou quem deve aprovar) tem ressalvas sobre as mudanças propostas pelo RAMO, há possibilidade de se questionar, debater e alterar, até que sejam satisfeitos todos os requisitos. Nesse caso, a pessoa ou equipe continua a trabalhar no RAMO. Nada impede que mais pessoas venham a se juntar no esforço de continuar o aprimoramento da mudança. Todo esse debate é realizado no âmbito do `pull request`, pois o Github tem os recursos com essa finalidade.

- Reparem que nesse processo também é perfeitamente **normal** que o RAMO de mudança seja recusado, ou seja, o RAMO de mudança pode ser simplesmente apagado. Nesse caso, é mantido o conteúdo original do REPO, contido no RAMO mestre.

- Aliás, quanto mais cedo for iniciada a solicitação de pull (`pull request`) melhor! Se uma mudança não está indo no caminho certo, é melhor encerrá-la o quanto antes, na tática conhecida  como "kill the baby", em que se evita perder tempo com retrabalhos de grande porte.

- Reparem que no interesse de promover um ambiente aberto e acolhedor, nós, como colaboradores e mantenedores, comprometemo-nos a tornar a participação em nosso projeto e em nossa comunidade uma experiência livre de assédio para todos. Veja um modelo de [Código de Conduta do Pacto de Contribuinte](https://www.contributor-covenant.org/version/1/4/code-of-conduct.html).

### ESTÓRIA

Para organizar o trabalho de um RAMO de mudança, sugere-se utilizar uma sequência de ESTÓRIAS. Cada ESTÓRIA representa uma fração do trabalho, atribuída a um membro ou equipe. Não há comando específico para iniciar uma ESTÓRIA, é um mero artifício para organização do trabalho. 

Veremos mais adiante que você também poderá trabalhar no seu micro local. Ao final de cada ESTÓRIA, pode-se salvar o conteúdo do RAMO no site Github através da operação `push`. Mas o processo simplificado que estamos fazendo agora não irá necessitar do `push`, por enquanto.

Suponha agora que a ESTÓRIA (ou tarefa a ser realizada) implica na alteração do texto de um arquivo do REPO ou na inclusão/exclusão de um arquivo. Afinal, é para isso que esse processo vai servir! Após a alteração, é utilizada a operação `commit` para registrar a mudança.

O Github é um site especializado em registrar mudanças, na forma de `commits`, com um tratamento de primeira classe:

- Dê um **título** ao `commit`, para compor um **histórico** das mudanças realizadas por cada colaborador.
- O `commit` registra as mudanças realizadas, além do título que você usou, a data e autor da mudança.
- De novo, é uma boa prática fazer pequenas mudanças de cada vez, a cada `commit`.
- Pode-se desfazer um `commit`, apesar de esta ser uma operação mais avançada para vermos depois.   

## Abrindo sua conta no GitHub

O GitHub oferece contas gratuitas para usuários e organizações que trabalham em projetos públicos. Dispõe também de contas pagas que oferecem repositórios privados ilimitados. Você **não precisa** de uma conta paga para colaborar com o contúdo de repositórios de uma organização.

Contudo, para participar ativamente na elaboração do conteúdo da organização Recreio Canoas será preciso ter um cadastro no Github. Veremos a seguir como fazer.

### Inscrever-se no serviço gratuito

Vá para a [página de preços](https://github.com/pricing) do GitHub.

- A página informa sobre as diferentes contas e planos que o GitHub oferece.
- Clique em `Inscreva-se em um dos nossos planos gratuitos`.
- Siga as instruções para criar sua conta pessoal.

### Mantenedores da equipe

O proprietário de uma organização pode promover qualquer membro da organização para o mantenedor da equipe de uma ou mais equipes. Clique em [mantenedor de equipe](https://help.github.com/articles/repository-permission-levels-for-an-organization/#team-maintainers "Mantenedores da equipe") para ver mais sobre:

- Alterar o nome e a descrição da equipe
- Alterar a visibilidade da equipe
- Definir a foto do perfil da equipe
- Editar discussões da equipe
- Excluir discussões da equipe
- Adicionar membros da organização à equipe
- Remover membros da organização da equipe
- Promover um membro da equipe existente para o mantenedor da equipe

Se você já abriu sua conta pessoal (e gratuita) no Github, passe para o próximo passo, para iniciar o treinamento rápido e simplificado do fluxo de trabalho que vamos utilizar.

