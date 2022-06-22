<h1>Desenvolvimento Ágil Limpo - De volta às Origens</h1>
<h2>Autor: Robert C. Martin</h2>
<img alt="Requisitos" height="400" width="300" align="center" src="https://github.com/Marilainny/Livros/blob/main/Imagem/Desenvolvimento-agil-limpo.png">

<ol>
    <li><strong>Pessoas e interações</strong>, em detrimento de processos e ferramentas.</li>
    <li><strong>Validação do software</strong>, em vez de uma documentação exaustiva e longa</li>
    <li><strong>Colaboração com o cliente</strong>, em detrimento da negociação de contrato.</li>
    <li><strong>Resposta à mudança</strong>, em vez de seguir um plano cegamente.</li>
</ol>

<p>Qual é a primeira coisa que você sabe a respeito de um projeto? Antes de saber o nome dele ou qualquer um dos requisitos, há um dado que precede todos os demais. O Prazo, é claro. E uma vez que ele é escolhido, é congelado. Nem adianta tentar negociar O Prazo porque ele foi escolhido por boas razões comerciais.</p>

<p>Ao mesmo tempo, os requisitos estão em constante movimento e nunca podem ser congelados. Isso ocorre porque os clientes não sabem realmente o que querem. Eles meio que sabem qual problema querem resolver, mas traduzir isso em forma de requisitos de um sistema nunca é uma coisa simples.</p>

<p>Desse modo, os requisitos estão sendo constantemente reavaliados e repensados. Adiciona-se novas funcionalidades. Remove-se as funcionalidades antigas. A interface do usuário altera o formulário semanalmente, se não todos os dias.</p>

<p>Este é o mundo de uma equipe de desenvolvimento de software. É um mundo em que os prazos são congelados e os requisitos constantemente mudam. E, de alguma forma, nesse contexto, a equipe de desenvolvimento deve fazer com que o projeto tenha um bom resultado.</p>

<p>Ao analisar o código e compará-lo com o design, percebemos que devíamos estar fumando alguma coisa bem forte quando criamos esse design, pois claramente o código não está nada parecido com aqueles diagramas belos e elegantes que desenhamos. No entanto, não temos tempo para nos preocupar com isso, porque estamos correndo contra o relógio e as horas extras só aumentam.</p>

<p>O problema da ideia do Método Cascata é que ela faz todo o sentido. Primeiro, analisamos o problema, então projetamos a solução e depois implementamos o design. Simples. Direto. Óbvio. E errado.</p>

<h2>ITERAÇÃO ZERO</h2>
<p>A primeira iteração, às vezes conhecida como Iteração Zero, é usada para gerar uma pequena lista de funcionalidades, chamadas histórias. Falaremos mais a respeito nos próximos capítulos. Por ora, pense nelas como funcionalidades que precisam ser desenvolvidas. A Iteração Zero também é utilizada para definir o ambiente de desenvolvimento, estimar as histórias e traçar o planejamento inicial. </p>

<p>A metodologia ágil é saber, o mais cedo possível, o quanto estamos ferrados. O motivo pelo qual queremos saber isso o quanto antes é para que possamos gerenciar a situação.</p>

<p>A Lei de Brooks 22 postula: Adicionar pessoas a um projeto de software atrasado resulta em um atraso ainda maior.Espero que saiba que direi que isso tudo será em vão. Fazer as coisas malfeitas não o faz avançar mais rápido, o faz avançar mais devagar. Essa é a lição que você aprende depois de trabalhar como programador durante vinte ou trinta anos. Não existe essa coisa de código sujo ser rápido. Qualquer código sujo é lento.</p>

<h2>VALOR DE NEGÓCIO AGREGADO</h2>
<p>Sendo assim, a partir de agora, no  início de cada iteração, perguntaremos às partes interessadas quais funcionalidades serão implementadas na sequência. A XP é a mais bem definida, a mais completa e a menos confusa.     Praticamente todos os outros processos ágeis são um subconjunto ou uma variação da XP.</p>

<ol>
    <li><strong>O Planejamento do Jogo</strong> é uma prática que desempenha o papel fundamental desse círculo. Ele nos informa como dividir um projeto em funcionalidades, histórias e tarefas. Fornece orientação para a estimativa, a priorização e o cronograma dessas funcionalidades, histórias e tarefas.</li>
    <li><strong>As Pequenas Versões</strong>orientam a equipe a trabalhar em pedaços pequenos.</li>
    <li><strong>Os Testes de Aceitação</strong>estipulam a definição de “concluído” para as funcionalidades, histórias e tarefas. Ele mostra à equipe como determinar critérios de conclusão inequívocos.</li>
    <li><strong>A Equipe como um Todo</strong> passa a noção de que uma equipe de desenvolvimento de software é constituída por muitas atribuições diferentes, incluindo programadores, testadores e gerentes, que trabalham juntos para atingir o mesmo objetivo.</li>
</ol>

<p>O círculo no meio do Ciclo de Vida apresenta as práticas orientadas à equipe. Essas práticas fornecem o framework e os princípios por meio dos quais a equipe de desenvolvimento se comunica e se gerencia.</p>

<ol>
    <li><strong>O Ritmo Sustentável</strong>é a prática que impede que uma equipe de desenvolvimento esgote todas as suas funcionalidades rapidamente e perca o fôlego antes da linha de chegada.</li>
    <li><strong>A Propriedade Coletiva</strong>assegura que a equipe não divida o projeto em um conjunto de silos de conhecimento.</li>
    <li><strong>A Integração Contínua</strong>mantém a equipe com foco em fechar o ciclo de feedback com frequência o bastante, a fim de saber o andamento das coisas o tempo todo.</li>
    <li><strong>O Uso de Metáforas</strong>s é a prática que cria e promove a terminologia e para que todos da equipe e da empresa falem a mesma língua com o objetivo de se comunicar a respeito do sistema.</li>
</ol>

<p>O círculo mais interno do Ciclo de Vida representa as práticas técnicas que orientam e restringem os programadores a fim de garantir a mais alta qualidade técnica.</p>

<ol>
    <li><strong>A Programação em Dupla</strong>é a prática que promove o conhecimento compartilhado entre a equipe técnica, analisando e colaborando em um nível que resulta em inovação e precisão.</li>
    <li><strong>O Design Simples</strong>é a prática que guia a equipe para evitar desperdício de esforço.</li>
    <li><strong>A Refatoração</strong>incentiva a melhoria contínua e o refinamento de todos os produtos de trabalho.</li>
    <li><strong>O Desenvolvimento Orientado a Testes</strong>é a segurança que a equipe técnica usa com o objetivo de avançar rapidamente, mantendo a mais alta qualidade.</li>
</ol>

<p>Essas práticas estão em conformidade com os objetivos do Manifesto Ágil no mínimo das seguintes maneiras:</p>
<ol>
    <li><strong>Pessoas e interações,</strong>em detrimento de processos e ferramentas.</li>
    <li><strong>A Equipe como um Todo,</strong>Uso de Metáforas, Propriedade Coletiva, Programação em Dupla e Ritmo Sustentável.</li>
    <li><strong>Validação do software,</strong>em vez de uma documentação exaustiva e longa.</li>
    <li><strong>Testes de Aceitação,</strong>Desenvolvimento Orientado a Testes, Design Simples, Refatoração e Integração Contínua.</li>
    <li><strong>Colaboração com o cliente,</strong>em detrimento da negociação de contrato.</li>
    <li><strong>Pequenas Versões,</strong>Planejamento do Jogo, Testes de Aceitação e Uso de Metáforas.</li>
    <li><strong>Resposta à mudança,</strong>em vez de seguir cegamente um plano.</li>
    <li><strong>Pequenas Versões,</strong>Planejamento do Jogo, Ritmo Sustentável, Desenvolvimento Orientado a Testes, Refatoração e Testes de Aceitação.</li>
</ol>

<h2>MELHORIA CONTÍNUA</h2>
<p>Os usuários, clientes e gerentes esperam a melhoria contínua e regular. Eles esperam que os problemas iniciais desapareçam e que o sistema melhore cada vez mais com o tempo. As práticas ágeis de Programação em Dupla, TDD, Refatoração e Design Simples são extremamente compatíveis com essa expectativa. Você consegue limpar o código usando as práticas ágeis de Refatoração, Programação em Dupla e Design Simples com o objetivo de melhorar o sistema.</p>

<h2>A QA NÃO DEVE ENCONTRAR NADA</h2>
<p>A QA não deve encontrar falhas no sistema. Ao executar os testes em QA, tudo deve funcionar conforme o necessário. As práticas ágeis de Testes de Aceitação, TDD e Integração Contínua são compatíveis com essa expectativa.</p>

<h2>AUTOMAÇÃO DE TESTES</h2>
<p>Os testes manuais sempre são eliminados. Qualquer teste que possa ser automatizado de maneira viável deve ser automatizado.</p>

<p>Embora seja importante se empenhar a fim de encontrar soluções para os problemas, espero que diga “não” quando nenhuma solução puder ser encontrada. Você precisa perceber que foi contratado mais por sua habilidade de dizer “não” do que por sua habilidade programar. Espero que, não importa quanta pressão exista em relação ao cronograma, não importa quantos gerentes exijam resultados, você diga “não” quando a resposta realmente for “não”. </p>

<h2>DECLARAÇÃO DE DIREITOS DO CLIENTE</h2>
<ol>
    <li>Você tem direito a um planejamento geral e de saber o que pode ser realizado, quando e a que preço.</li>
    <li>Você tem o direito de agregar o máximo de valor possível a cada iteração.</li>
    <li>Você tem o direito de ver o progresso da implementação de um sistema que comprovadamente funcione por meio de testes reproduzíveis determinados por você.</li>
    <li>Você tem o direito de mudar de ideia, substituir a funcionalidade e alterar as prioridades sem pagar custos exorbitantes.</li>
    <li>Você tem o direito de ser informado sobre mudanças no cronograma e estimativa a tempo de escolher como reduzir o escopo a fim de cumprir uma data exigida. Você pode cancelar as coisas a qualquer momento e ficar com um sistema funcional útil que reflita o investimento até aquela data.</li>
</ol>

<h2>DECLARAÇÃO DE DIREITOS DO DESENVOLVEDOR</h2>
<p>A declaração de direitos do desenvolvedor inclui:</p>
<ol>
    <li>Você tem o direito de saber o que é necessário por meio de declarações de prioridade transparentes.</li>
    <li>Você tem o direito de desenvolver trabalhos da mais alta qualidade o tempo todo.</li>
    <li>Você tem o direito de solicitar e receber ajuda de colegas, gerentes e clientes.</li>
    <li>Você tem o direito de efetuar e atualizar suas próprias estimativas.</li>
    <li>Você tem o direito de aceitar suas responsabilidades em vez de ter alguém que lhes atribua.</li>
</ol>
<p>Note que os clientes não têm o direito de exigir conformidade em  relação ao cronograma. O direito dos clientes se limita ao gerenciamento do cronograma no que diz respeito à mudança do escopo. A coisa fundamental que esse direito concede é saber que o cronograma está em risco, de modo que possa ser gerenciado em tempo hábil.</p>

<p>A empresa não tem o direito de exigir que os desenvolvedores reduzam custos ou realizem um trabalho de baixa qualidade. Ou, dito de outro modo, ela não tem o direito de obrigar os desenvolvedores a arruinar sua reputação ou violar sua ética profissional.</p>

<h2>Estimando as Histórias</h2>
<p>Escolhemos uma história do grupo que consideramos de complexidade média. Em seguida, escolhemos um número de pontos para a história. Atribuímos um custo médio. Três é a média caso nossas histórias variem de 1 a 6. A nossa História de Ouro. É o padrão ao qual todas as outras histórias serão comparadas. Digamos que agora temos um grupo de cartões com estimativas que variam de 1 a 6, são uma unidade de esforço estimado, não de tempo real. Elas não são nem uma estimativa de tempo — são uma estimativa de esforço.</p>

<p>existe algo belo nesses valores indefinidos e confusos. Chama-se Lei dos Grandes Números. A função das partes interessadas na IPM é escolher as histórias que serão implementadas pelos programadores e testadores durante a     iteração. Para tal, elas precisam saber quantos pontos da história os programadores acham que conseguem finalizar. Esse cálculo é chamado de velocidade.</p>

<p>As histórias com valor alto, mas com custo baixo, serão elaboradas de imediato. Aquelas que têm valor alto e um custo alto, serão feitas depois. As histórias que têm valor baixo e custo baixo podem ser concluídas algum dia. Aquelas que têm valor baixo, mas um custo alto, nunca serão feitas. Isso se chama cálculo de Retorno sobre o Investimento (ROI).</p>

<h2>HISTÓRIAS</h2>
<p>As histórias seguem um conjunto simples de diretrizes de acordo com o mnemônico INVEST.</p>
<ol>
    <li>I: Independent (Independente): As histórias de usuários são independentes umas das outras. Ou seja, elas não precisam ser implementadas em nenhuma ordem específica.</li>
    <li>N: Negotiable (Negociável): Aqui temos outra razão pela qual não registramos todos os detalhes. Queremos que eles sejam negociáveis entre os desenvolvedores e o negócio.</li>
    <li>V: Valuable (De Valor): A história deve apresentar um valor claro e quantificável para o negócio.</li>
    <li>E: Estimable (Mensurável): Uma história de usuário deve ser concreta o suficiente para permitir que os desenvolvedores a</li>
    <li>S: Small (Pequena): Uma história de usuário não deve ser maior que qualquer coisa que um ou dois desenvolvedores não consigam implementar em uma única iteração.</li>
    <li>T: Testable (Testável): A empresa deve conseguir estruturar testes que comprovem que a história foi concluída.</li>
</ol>

<h2>QA e Testes de Aceitação</h2>
<p>A escrita do Teste de Aceitação deve ser rápida. Esperamos que todos sejam elaborados antes do ponto médio da iteração.  Quando uma história passa no Teste de Aceitação, ela é concluída.</p>

<p>É o básico da teoria de controle: não exerça pressão sobre o que você está calculando. A prática de Pequenas Versões sugere que uma equipe de desenvolvimento libere seu software o mais rápido possível. Os testes são escritos pelos analistas de negócios e pela equipe de QA, antes da primeira metade da iteração em que as histórias que eles
testam devem ser desenvolvidas. Os desenvolvedores integram esses testes ao processo de build contínuo. Esses testes se tornam a Definição de Concluído para as histórias na iteração. Uma história não é especificada até que seu Teste de Aceitação seja escrito.</p>

<p>O pessoal de QA é contratado por sua capacidade de descobrir como quebrar o sistema. São pessoas profundamente técnicas que conseguem prever todas as coisas estranhas e bizarras que os usuários farão no sistema. Elas também conhecem a mente dos programadores e sabem como sondar todas as suas tendências preguiçosas.</p>

<p>Em vez de atuar como testadores no back-end do projeto, eles se tornam especificadores operando no front-end. Isso sobrecarrega, e muito, a equipe de QA. Agora, a QA deve garantir a qualidade instilando-a no início de cada iteração, em vez de identificar a falta de conformidade no final. No entanto, a responsabilidade da equipe de QA não enfraquece de jeito algum; eles determinam se o sistema é implementável.</p>

<p>A equipe de QA escreve os Testes de Aceitação das histórias em uma iteração.É função dos programadores executar os testes. É função dos programadores assegurar que o código deles seja aprovado em todos os testes. Na realidade, os programadores automatizarão esse processo por meio da configuração de um servidor de build contínuo. Esse servidor
simplesmente executará todos os testes no sistema, incluindo todos os unitários e todos os de aceitação, sempre que um programador fizer check-in em um módulo.</p>

<p>Ninguém é dono do código em um projeto ágil. O código pertence à equipe como um todo. Qualquer membro da equipe pode verificar e melhorar qualquer módulo do projeto a qualquer momento. O código pertence coletivamente à equipe inteira. Quando uma equipe usa a prática da Propriedade Coletiva, o conhecimento é distribuído entre todos. Cada membro da equipe compreende melhor os limites entre os módulos e o modo geral como o sistema funciona. Isso melhora radicalmente a capacidade da equipe de se comunicar e tomar decisões.</p>

<p>O build contínuo nunca deve quebrar. Cada programador executa todos os Testes de Aceitação e todos os testes unitários antes de realizar o check-in do código. Um build quebrado é uma Situação de Grande Impacto. Quero que todos os programadores parem o que estão fazendo e se reúnam a fim de verificar o que está acontecendo. O mantra da equipe deve ser O Build Nunca Quebra.</p>

<h2>REUNIÕES DIÁRIAS</h2>
<p>A ideia básica é que os membros da equipe fiquem de pé em um círculo e respondam às seguintes perguntas:
<li>O que fiz desde a última reunião?</li>
<li>O que farei até a próxima reunião?</li>
<li>Existe algum impedimento em meu caminho?</li>
<li>A quem você diria “obrigado”?</li> 
É uma pequena forma de agradecer a alguém que o ajudou, ou que fez algo que você acredita merecer reconhecimento.
Isso é tudo. Sem discussão. Sem formalidades. Sem explicações aprofundadas.</p>

<h2>DESENVOLVIMENTO ORIENTADO A TESTES</h2>
<p>Sem o TDD, a Refatoração, o Design Simples e, sim, até mesmo sem a Programação em Dupla, a agilidade se torna uma sombra inexpressiva e estéril do que deveria ser.</p>

<p>O Desenvolvimento Orientado a Testes é a prática correspondente para os programadores. Todo comportamento exigido é inserido duas vezes: uma vez como teste e depois como código de produção, para que o teste seja aprovado. As duas entradas são complementares, assim como os ativos são complementares aos passivos e ações. Quando executadas juntas, as duas entradas geram zero como resultado: zero falhas nos testes.</p>

<h2>AS TRÊS REGRAS DO TDD</h2>
<p>O TDD pode ser descrito em três regras simples:
    <li>Não escreva nenhum código de produção antes de elaborar um teste que falhou devido à falta desse mesmo código.</li>
    <li>Não escreva mais testes do que o suficiente para identificação da falha — e falhas na compilação ainda contam como falhas.</li>
    <li>Não escreva mais códigos de produção do que o suficiente para passar nos testes.</li>
</p>

<p>Queremos criar uma suíte de testes automatizados que nos informem que é seguro fazer o deploy do sistema. A refatoração é a prática de melhorar a estrutura do código sem alterar o comportamento, conforme definido pelos testes. Dito de outro modo, fazemos alterações nos nomes, nas classes, nas funções e nas expressões sem quebrar nenhum dos testes. Melhoramos a estrutura do sistema sem interferir no comportamento. Para refatorar o código sem medo, precisamos de uma suíte de testes que nos passe bastante confiança de que não estaremos quebrando nada.</p>

<p>O processo de refatoração está intimamente relacionado com as Três Regras do TDD e é conhecido como ciclo Vermelho/Verde/Refatore. A ideia aqui é que escrever um código que funcione e escrever um código que seja limpo são duas dimensões separadas da programação.</p>

<ol>
    <li>Primeiro, escreva um teste que falhe.</li>
    <li>Depois, faça com que o teste passe.</li> 
    <li>Em seguida, limpe o código.</li>
    <li> Volte para a primeira etapa.</li>
</ol>

<p>Primeiro nos concentramos em fazer com que o código funcione. Em seguida, depois que estiver funcionando, com a aprovação dos testes, limpamos o código. A refatoração é um processo contínuo, e não um processo executado de forma planejada. A refatoração faz parte da nossa abordagem diária para escrever o software.</p>

<h2>DESIGN SIMPLES</h2>
<p>A prática do Design Simples é um dos objetivos da Refatoração. É a prática de escrever apenas o código necessário com uma estrutura que o deixe mais simples, menor e mais expressivo. As regras de Kent Beck para o Design Simples são:</p>

<ol>
    <li>Execute todos os testes.</li>
    <li>Expresse a intenção.</li>
    <li>Elimine a duplicação.</li>
    <li>Reduza os elementos.</li>
</ol>

<p>A regra 1 fala por si só. O código deve ser executado e passar em todos os testes; ele deve funcionar.</p>

<p>A regra 2 afirma que, depois que o código é escrito para funcionar, ele deve ser expressivo. Deve revelar a intenção do programador, ter legibilidade e ser autodescritivo. É aqui que aplicamos muitas das refatorações mais simples e superficiais. Dividimos também as funções grandes em funções menores, nomeando-as de um jeito melhor.</p>

<p>A regra 3 alega que, depois de o código estar o mais descritivo e expressivo possível, procuramos eliminar quaisquer que sejam as duplicações nele. Não queremos que ele informe a mesma coisa mais de uma vez. Durante essa atividade, as refatorações são geralmente mais complicadas. Algumas vezes, para eliminar a duplicação, basta apontar o código duplicado para uma função e chamá-la a partir de diversos lugares. Outras vezes, exige soluções mais interessantes, como o Design Patterns: 4 Template Method, Strategy, Decorator ou Visitor.</p>

<p>A regra 4 mostra que, uma vez eliminada a duplicação, devemos nos esforçar para reduzir o número de elementos estruturais, como classes, funções, variáveis etc. O objetivo do Design Simples é fazer com que a magnitude do design
do código seja a menor possível.</p>

<h2>PROGRAMAÇÃO EM DUPLA</h2>
<p>A programação em dupla é quando duas pessoas trabalham em estreita colaboração em um único problema de código. A dupla pode trabalhar junto na mesma estação de trabalho, compartilhando a tela, o teclado e o mouse. Ou pode trabalhar em duas estações de trabalho conectadas, desde que vejam e operem o mesmo código.</p>

<p>Às vezes, os programadores que adotam a programação em dupla desempenham papéis distintos. Talvez um seja o piloto e o outro o copiloto. O piloto assume o teclado e o mouse; o copiloto realiza predições e faz recomendações. Na maior parte das vezes, no entanto, não existem papéis. Os programadores assumem a mesma função, compartilhando o mouse e o teclado de forma colaborativa.</p>

<p>A programação em dupla é, sem dúvidas, a melhor forma de compartilhar o conhecimento entre os membros da equipe e evitar a formação de silos de conhecimento. Deste modo assegura que ninguém na equipe seja insubstituível.</p>

<h2>COMUNICAÇÃO</h2>
<p>Valorizamos a comunicação direta e frequente que permeie os canais comunicativos. Os membros da equipe ágil querem conversar uns com os outros. Os programadores, os clientes, os testadores e os gerentes querem se sentar próximos e interagir com frequência, e não apenas no contexto das reuniões. Não somente via e-mails, bate-papo e relatórios. Ao contrário, eles valorizam conversas presenciais, informais e interpessoais.</p>

<p>Praticamente todas as disciplinas ágeis que estudamos são orientadas a fornecer feedback rápido às pessoas que tomam decisões importantes. As práticas Planejamento do Jogo, Refatoração, Desenvolvimento Orientado a Testes, Integração Contínua, Pequenas Versões, Propriedade Coletiva, Equipe como um Todo etc. maximizam a frequência e a quantidade de feedback.</p> 

<p>Elas nos permitem identificar com antecedência quando as coisas estão dando errado a fim de corrigi-las e proporcionam amplo entendimento sobre as consequências das decisões anteriores. As equipes ágeis prosperam por meio de feedback. O feedback é o que faz a equipe operar de modo efetivo e o que impulsiona um projeto a um resultado favorável.</p>

<p>Ao reconhecer um problema e silenciosamente permitir que ele afete outra pessoa, você se envolve com a falta de simplicidade e de franqueza. Ao ceder às demandas de um gerente ou cliente sabendo que as consequências serão desastrosas, você está sendo dissimulado.</p>

<p>Adotar o Ciclo de Vida, incluindo, sobretudo, as práticas técnicas. O objetivo é fazer com que a equipe absorva os valores ágeis e ensinar as disciplinas ágeis. O coach representa a consciência da equipe, sempre lembrando as promessas que o pessoal fez e os valores que concordaram em defender.</p>

<h2>FERRAMENTAS DE SOFTWARE</h2>

<p>Os desenvolvedores de software devem dominar uma série de ferramentas essenciais:</p>
<ul>
    <li>Pelo menos uma linguagem de programação e, muitas vezes, mais de uma.</li>
    <li>Um ambiente de desenvolvimento integrado ou editor de texto para programadores (vim, Emacs etc.).</li>
    <li>Vários formatos de dados (JSON, XML, YAML etc.) e linguagens de marcação (incluindo HTML).</li>
    <li>Interação de linha de comando e baseada em script com o sistema operacional.</li>
    <li>Ferramentas de repositório de código (Git. Existe outra opção?).</li>
    <li>Ferramentas de integração/build contínuos (Jenkins, TeamCity, GoCD etc.).</li>
    <li>Ferramentas de deploy/gerenciamento de servidor (Docker, Kubernetes, Ansible, Chef, Puppet etc.).</li>
    <li>Ferramentas de comunicação (e-mail, Slack, o idioma inglês [!]).</li>
    <li>Ferramentas de teste (frameworks de teste de unidade, Cucumber, Selenium etc.).</li>
</ul>

<p>O Manifesto Ágil é um ótimo modelo para coaching e coordenação do trabalho de diversas equipes: “Promova o ambiente e o apoio necessários e confie no trabalho delas.” Para tal, a comunidade ágil instaurou uma série de padrões de escalonamento compatíveis com os valores e os princípios do Manifesto Ágil. Não estou me referindo aos frameworks e sim às práticas individuais a partir das quais todos os frameworks são construídos.</p>

<p>Os princípios SOLID: Embora esses princípios sejam valiosos em qualquer escala, são principalmente úteis para simplificar a coordenação entre equipes, reduzindo radicalmente as dependências.</p>

<p>Histórias pequenas e valiosas de usuário: Histórias pequenas e individualmente entregáveis restringem o escopo das
dependências, simplificando a coordenação entre equipes.</p>

<p>Pequenas versões frequentes: Se essas versões são entregues ao cliente ou não, a prática de ter um produto entregável em todas as equipes envolvidas ajuda a solucionar os problemas de coordenação e arquitetura de modo que a causa-raiz possa ser identificada e tratada.</p>

<p>Integração Contínua: A XP assume uma posição ainda mais forte na integração, exigindo integração em todo o produto após cada check-in.</p>

<p>Design Simples: Essa prática, também conhecida como Design Emergente, é uma das práticas mais difíceis de se aprender e implementar, porque contraria as expectativas. As equipes têm suas dificuldades mesmo quando não precisam se coordenar com outras equipes.</p>

<p>Os desenvolvedores não devem solicitar autorização para escrever os testes. Não devem ter tarefas separadas para os testes unitários ou a refatoração e nem a fim de implementar uma funcionalidade em produção.</p>






