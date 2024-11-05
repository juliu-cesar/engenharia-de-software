# Software

A diferença entre software e um programa é um pouco sutil, mas, em geral, podemos definir que o software é um conceito mais amplo e envolve mais componentes que o definem e o tornam utilizável.

Alguns desses componentes que definem um software são:

1. **Instruções** (programas de computador) que quando executadas fornecem características, funções e desempenho desejado. É o núcleo de qualquer software, e podem ser simples scripts ou complexos sistemas integrados.
2. **Estrutura de dados** que possibilitam aos programas manipular informações adequadamente, como bibliotecas, dependências e arquivos de configuração.
3. **Informação descritiva** tanto na forma impressa quanto na virtual, descrevendo operações e o uso dos programas. O software deve incluir documentação (manuais do usuário, documentação técnica e instruções) que permite aos desenvolvedores e usuários finais entender como utilizar, configurar e resolver problemas com o software.

> Bibliotecas são conjuntos de código reutilizáveis que fornecem funcionalidades específicas ao software

O conjunto dos itens acima é o que diferencia um simples programa de computador de um software. Pois não apenas ele precisa desempenhar as funções que foi programado, como também deve haver uma documentação e instruções de como utilizar-lo.

Um editor de textos, como o **Microsoft Word**, é um software que inclui o programa principal (o editor de textos), bibliotecas (para renderizar fontes, corrigir ortografia), documentação (ajuda do usuário), arquivos de configuração e funcionalidades interativas (barra de ferramentas, formatação). Ele é um exemplo de software de aplicação criado para resolver uma necessidade específica de edição e formatação de texto, com um conjunto robusto de ferramentas para essa finalidade.

## Ciclo de vida de desenvolvimento de software (SDLC)

De acordo com Ian Sommerville são comuns a todos os processos de software os seguintes passos:

1. Especificação
2. Desenvolvimento
3. Validação
4. Evolução

Podemos criar uma analogia com a construção de uma casa, o primeiro passo é identificar as necessidades (especificações) com uma arquiteta ou engenheiro civil que vão juntar todos os requisitos para seguir com o passo da construção (desenvolvimento), onde durante e ao final desse processo sera verificado se o que esta sendo construído esta de acordo com o solicitado (Validação) e apos a finalização e utilização do imóvel, podem haver novas necessidades que exigirão reformas (evolução) além das manutenções ja programadas.

A descrição vista acima é um definição mais genérica sobre o desenvolvimento de de software, porem bastante atual. Porem temos outros ciclos mais clássicos como o seguinte.

### Modelo Cascata (WaterFall)

O ciclo de vida em cascata, também conhecido como modelo Waterfall, é um modelo linear que divide o processo de desenvolvimento de software em etapas sequenciais. A próxima etapa só pode ser iniciada quando a anterior for concluída. 

1. Requisitos: Coleta e análise de requisitos
2. Projeto do Sistema: Projetar o sistema e definir o Design de software
3. Implementação (codificação): Desenvolvimento de software
4. Verificação: Testa-se o software para garantir que ele atenda aos requisitos definidos
5. Manutenção: O software é mantido e atualizado para corrigir problemas ou adicionar novas funcionalidades.

___

O ciclo de vida descrito Por Sommerville é um processo mais dinâmico, permitindo uma abordagem mais flexível e iterativa. Ja o modelo Waterfall tende-se a seguir um ritmo linear e sequencial, o que pode acarretar em perda de tempo em cada etapa, uma vez que algum erro na etapa anterior trave as seguintes.

Porem ambos os modelos convergem no ponto em que o desenvolvimento de software é um presso continuo e que sua capacidade de evoluir e de ser mantido é que garantem o seu sucesso.

### Metodologia Ágil

A metodologia ágil é uma abordagem de desenvolvimento de software que visa tornar o processo **mais flexível, adaptável e orientado a resultados** rápidos e incrementais. Ela foi criada como uma alternativa ao modelo tradicional Waterfall, com o objetivo de melhorar a colaboração entre equipes e acelerar a entrega de software funcional ao cliente. A metodologia ágil é baseada nos princípios descritos no Manifesto Ágil (2001), que prioriza a adaptação constante e a interação com o cliente durante todo o desenvolvimento. O Manifesto Ágil estabelece quatro valores fundamentais:

1. Indivíduos e interações mais que processos e ferramentas:
   - A comunicação entre os membros da equipe é mais valorizada do que o uso estrito de processos formais ou ferramentas.

2. Software em funcionamento mais que documentação abrangente:
   - O foco é entregar software que funcione e agregue valor ao cliente, reduzindo a necessidade de uma documentação exaustiva.

3. Colaboração com o cliente mais que negociação de contratos:
   -  O cliente é parte ativa do processo, permitindo que suas necessidades sejam continuamente incorporadas, e feedbacks sejam rapidamente incorporados.

4. Responder a mudanças mais que seguir um plano:
   - A metodologia ágil aceita que mudanças são inevitáveis e permite a adaptação rápida conforme as necessidades mudam ao longo do desenvolvimento.

Apesar de essa metodologia ser amplamente utilizada em outras áreas, ela se adequou perfeitamente ao desenvolvimento de software, pois se trata de um ambiente em constante mudança, que muitas vezes exige adaptações nos requisitos ao longo do processo.

Além desses valores principais, temos outros princípios que descrevem o processo de forma mais micro.

- Propriedade coletiva
- integração continua
- Planejamento incremental
- Representando do cliente
- Refatoração
- Programação em pares
- Lançamentos pequenos
- projeto simples
- Ritmo sustentável
- Desenvolvimento test first

#### Tipos de metodologia ágil

Metodologia ágil é um conceito que engloba diversas outras metodologias. Cada uma delas possui suas características, benefícios e aplicações ideais, dependendo do tipo de projeto e das necessidades da equipe. Vejamos algumas delas.

1. **Scrum**: é uma das metodologias ágeis mais populares e amplamente adotada, focada em ciclos de trabalho curtos, chamados de **sprints** (geralmente entre duas a quatro semanas). O Scrum divide o desenvolvimento em papéis específicos e estabelece reuniões para organizar o trabalho e manter o alinhamento entre a equipe.

- Papéis:
  - **Product Owner**: responsável por definir e priorizar os requisitos no backlog.
  - **Scrum Master**: garante que a equipe siga as práticas ágeis e ajude a remover impedimentos.
  - **Equipe de Desenvolvimento**: autogerida e responsável pela implementação das tarefas.

- Eventos:
   - **Sprint Planning**: reunião de planejamento no início do sprint para definir as tarefas e metas.
   - **Daily Stand-Up**: reunião diária curta para discutir progresso e desafios.
   - **Sprint Review**: revisão do trabalho realizado ao final do sprint para demonstrar ao Product Owner.
   - **Sprint Retrospective**: reunião de feedback para melhorar processos e ajustar a equipe.

2. **Extreme Programming (XP)**: foca em aumentar a qualidade do software e a capacidade de adaptação da equipe através de práticas técnicas e disciplina. É ideal para projetos com requisitos incertos, que mudam com frequência, e enfatiza boas práticas de desenvolvimento.

- Principais práticas:
   - **Desenvolvimento Iterativo**: semelhante ao Scrum, o desenvolvimento é feito em iterações curtas.
   - **Testes Unitários Contínuos**: o desenvolvimento é acompanhado de testes contínuos para garantir a funcionalidade e reduzir bugs.
   - **Refatoração**: constante melhoria do código para mantê-lo limpo e eficiente.
   - **Programação em Par (Pair Programming)**: dois programadores trabalham juntos no mesmo código para melhorar a qualidade.
   - **Feedback Contínuo do Cliente**: o cliente participa ativamente para ajustar funcionalidades conforme necessário.

1. **Kanban**: é uma metodologia ágil focada na visualização do fluxo de trabalho para melhorar a eficiência e identificar gargalos. Em vez de sprints, como no Scrum, o Kanban prioriza um fluxo contínuo de trabalho, onde novas tarefas são puxadas conforme a equipe termina as tarefas anteriores.

- Principais elementos:
   - **Quadro Kanban**: as tarefas são organizadas em um quadro com colunas que representam o status de cada tarefa, como “A Fazer”, “Em Progresso” e “Concluído”.
   - **Limite de Tarefas em Progresso (WIP)**: define um número máximo de tarefas que podem estar em progresso para evitar sobrecarga.
   - **Revisão Contínua**: as tarefas são ajustadas e revisadas conforme avançam pelo quadro, sem necessidade de pausas formais.

___

Embora não seja obrigatório seguir uma única metodologia, é importante escolher aquela que melhor se adequa às necessidades do projeto O Scrum e XP são ideais para equipes de desenvolvimento focadas em melhorias contínuas e entregas iterativas, enquanto Kanban funciona melhor para equipes que precisam de um fluxo de trabalho contínuo e flexível. 

> Existem também outra metodologias como o Lean Software Development, Feature-Driven Development (FDD) e Dynamic Systems Development Method (DSDM).

### Tipos de Software

Abaixo temos alguma formas de classificar um software:

- **Software de Sistema**: Inclui o sistema operacional (como Windows, macOS, Linux). Ele cria a fundação para outros softwares operarem.

- **Software Utilitário**: são uteis ao funcionamento do computador/sistema operacional. Fornecem ao usuário ferramentas para corrigir falhas de processamento, organização de discos e gerenciamento de memoria.

- **Software de Aplicação**: Projetado para o usuário final, atende a uma necessidade ou atividade específica, como navegadores de internet, aplicativos de escritório (Word, Excel) e softwares empresariais (ERP, CRM).

- **Software de Programação e Desenvolvimento**: Ferramentas usadas por programadores para criar, depurar e manter outros softwares, como IDEs (ambientes de desenvolvimento integrados), depuradores, compiladores e sistemas de controle de versão.

## Programa

Um programa de computador é uma sequência de instruções escritas em uma linguagem de programação, que, quando executadas, realizam uma tarefa ou conjunto de tarefas específicas. Cada programa é projetado para resolver um problema ou fornecer uma funcionalidade, sendo o elemento central no funcionamento de qualquer software.

Principais características de um programa de computador:

- **Código Executável**: é composto por um conjunto de comandos e instruções que o computador segue para realizar operações. Este código pode ser **compilado** (convertido em linguagem de máquina) ou **interpretado** (executado linha a linha por um interpretador).

- **Unidade Funcional Específica**: geralmente tem uma única função ou um objetivo específico. Por exemplo, uma calculadora, um conversor de unidades, ou um script que automatiza uma tarefa.

- **Dependência de Execução**: Um programa, por si só, precisa de um ambiente de execução para funcionar, como o sistema operacional ou um interpretador, mas pode existir de forma isolada, sem necessidade de interfaces, documentação, ou integração com outros sistemas.

- **Simplicidade Estrutural**: Programas são, muitas vezes, mais simples e diretos. Um script em Python, por exemplo, pode ser um programa simples com um único propósito: acessar uma API para buscar dados e imprimi-los no console.

Um programa é a implementação prática de um [algoritmo](#algoritmo) em uma linguagem de programação específica. Enquanto o algoritmo define como resolver um problema, o programa contém o código executável que segue as instruções do algoritmo para que o computador realize essa solução. Mais a frente temo

Alguns exemplos de programas são um script que converte arquivos de um formato para outro ou  um código que envia um e-mail automatizado.

## Sistemas operacionais

Um sistema operacional é um tipo de software de sistema que **gerencia o hardware e os recursos de um computador**, além de fornecer serviços essenciais para a execução de aplicativos. É considerado um software base para o funcionamento do hardware ou parte dele, coordenando e facilitando o uso dos recursos computacionais para que os aplicativos possam funcionar corretamente.

O que diferencia um software de um sistema é que ele pode ser definido como um conjunto de software que interagem entre si para alcançar um determinado objetivo. 

Alguns sistemas operacionais conhecidos são o **Windows**, **MacOS**, **Ubuntu** e **Android**.

Geralmente esse sistemas tem como objetivo facilitar o uso do computador pelo usuário, gerenciando a concorrência de recursos da maquina pelos aplicativos.

#### Outros Tipos de Sistemas

Além dos sistemas operacionais, existem outros tipos de sistemas que desempenham funções específicas dentro de um ambiente de computação.

1. Sistemas Embarcados

Um sistema embarcado é um sistema de computação dedicado a uma função específica dentro de um dispositivo maior.Eles geralmente têm requisitos rigorosos de tempo real, tamanho, consumo de energia e custo. Exemplos de Sistemas Embarcados:

- Sistemas de controle em eletrodomésticos (como micro-ondas e refrigeradores).
- Sistemas de navegação e controle em automóveis.
- Dispositivos médicos (como monitores cardíacos).
- Controles de tráfego em redes ferroviárias.

2. Sistemas Tradutores
   
Sistemas Tradutores, ou sistemas de tradução de linguagem, são softwares que **convertem código escrito em uma linguagem de programação para outra**, geralmente em código de máquina, para que o hardware possa executá-lo. Tipos de Tradutores:

- **Interpretadores**: Executam o código linha por linha, sem pré-compilação. São comuns em linguagens como **Python** e **JavaScript**.
- **Compiladores**: Convertem código-fonte em código de máquina em um único processo antes da execução. Exemplo: GCC (GNU Compiler Collection) para **C** e **C++**.

> Existem também outros tipo mais específicos de sistemas tradutores como os "Assembladores" que traduzem código escrito em linguagem assembly para código binário que o processador pode executar e os "Transcompiladores" que traduzem código-fonte de uma linguagem para outra, como um compilador que converte TypeScript para JavaScript.

Na pratica não é comum encontrar uma linguagem de programação que é completamente interpretada ou compilada, geralmente existe uma mescla desses métodos para atingir um melhor desempenho. Porem por questões de didática utilizamos esses conceitos separados.

## Algoritmo 

"Um algoritmo é uma **sequência de passos ou instruções** bem definidas que visa atingir um objetivo bem definido". (Forbellone, 1999). Os algoritmos formam a base para resolver problemas em várias áreas, incluindo ciência da computação, matemática e até atividades cotidianas. Eles são independentes de linguagem de programação e podem ser expressos em uma variedade de formas, como pseudocódigo, fluxogramas, ou descrição em linguagem natural.

Uma vez desenvolvido um algoritmo para resolver um determinado problema, ele pode ser aplicado independentemente da linguagem de programação escolhida.

Características Principais de um Algoritmo:

- **Precisão**: Cada passo de um algoritmo é bem definido e deve ser seguido exatamente como descrito.
- **Finitude**: Um algoritmo precisa ter um fim; ele deve chegar a uma solução ou conclusão em um número finito de passos.
- **Clareza**: As instruções de um algoritmo devem ser claras e sem ambiguidades, permitindo que sejam executadas exatamente da mesma forma em qualquer contexto.
- **Eficiência**: Algoritmos eficazes são otimizados para uso de tempo e recursos, resolvendo o problema com o mínimo necessário de operações.
- **Independência de Implementação**: Um algoritmo descreve como resolver um problema de forma lógica, mas não depende de uma linguagem de programação específica.

Existem alguns casos e sistemas complexos onde a execução de um programa não segue um algoritmo no sentido clássico. Como por exemplo a diferença entre:

- Programas Determinísticos vs. Programas Não Determinísticos:
  
  - **Determinísticos**: A maioria dos programas baseados em algoritmos são determinísticos, o que significa que, para uma entrada específica, eles sempre produzem a mesma saída, seguindo um caminho fixo de execução.
  
  - **Não Determinísticos**: Alguns programas dependem de entradas variáveis, como dados em tempo real, sensores, ou eventos de rede, que podem causar variações no comportamento e na saída, dificultando a descrição por um algoritmo estrito.
  
Alguns programas que podem ser classificados como não determinísticos são programas baseados em Inteligência artificial, baseados em eventos e sistemas complexos.

### Diferença entre sintaxe e semântica

Em vias de regra a sintaxe é responsável pela estrutura do código, enquanto a semântica se preocupa com o significado ou a lógica da operação.

1. **Sintaxe**: Refere-se às regras de estrutura e forma que definem **como o código deve ser escrito** em uma linguagem de programação. Envolve aspectos como o uso correto de parênteses, vírgulas, operadores e a sequência correta de comandos.
   
  - Exemplo: Em Python, a instrução `print("Olá")` está correta, mas `print(Olá)` gera um erro de sintaxe porque a sintaxe exige que o texto a ser exibido esteja entre aspas.

2. **Semântica**: Refere-se ao **significado do código** ou das instruções, ou seja, o que cada comando realiza. A semântica foca se o código faz o que o programador realmente pretende, independente da correção sintática.
   
  - Exemplo: Se você escreve `total = preço + quantidade`, a sintaxe pode estar correta, mas a semântica pode estar errada, pois provavelmente o usual seria calcular o `total = preço * quantidade`.
