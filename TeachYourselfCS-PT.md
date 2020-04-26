# Ensine a si mesmo ciência da computação

> This document is a Portuguese translation of [TeachYourselfCS](https://teachyourselfcs.com), written by [Ozan Onay](https://twitter.com/oznova_) and [Myles Byrne](https://twitter.com/quackingduck). For more information about this translation, please refer to [the end of this document](#quem-é-o-tradutor).

Se você for um engenheiro autodidata ou graduado de alguma bootcamp, você deve a si mesmo aprender ciência da computação. Felizmente, você pode se dar uma educação de primeira classe sem ter que investir anos e uma pequena fortuna num diploma 💸.

Há muitos recursos por aí, mas alguns são melhores do que outros. Você não precisa de mais uma lista de “200+ cursos online gratuitos”. Você precisa de respostas para essas perguntas:

* **Quais assuntos** você deve aprender, e por quê?
 
*  Qual o **melhor livro ou série de video aulas** para cada assunto?

Esse guia é a nossa tentativa de responder de uma vez por todas essas perguntas.

## TL;DR: (Resumo)

Estude todos os assuntos abaixo, mais ou menos na ordem apresentada, usando ou o livro sugerido ou as video aulas, idealmente os dois. Tente dedicar 100-200 horas de estudo para cada um dos tópicos e revisite os seus favoritos durante a sua carreira 🚀.



| Assunto                                           | Por que estudar?                                                                                                                                | Melhor livro                                               | Melhores videos                       |
|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|-----------------------------------|
| **[Programação](#programação)**                   | Não seja a pessoa que nunca “nunca entendeu de verdade” algo como recursão.                                                                 | _Structure and Interpretation of Computer Programs_     | Brian Harvey Berkeley CS 61A    |
| **[Arquitetura de Computadores](#arquitetura-de-computadores)**  | Se você não tiver um modelo mental sólido de como um computador realmente funciona, todas as suas abstrações de alto nível serão frágeis.           | _Organização e projeto de computadores: a Interface Hardware/software_                      | Berkeley CS 61C                   |
| **[Algoritmos e Estrutura de Dados](#algoritmos-e-estrutura-de-dados)**| Se você não entender como usar as estrutura de dados mais essenciais como pilhas, filas, árvores, e grafos, você não vai conseguir resolver problemas complexos. | _The Algorithm Design Manual_                           | aulas do Steven Skiena          |
| **[Matemática para CC](#matemática-para-ciência-da-computação)**                   | Ciência da computação é basicamente um ramo da matemática aplicada, então aprender matemática te dará uma vantagem competitiva.                                 | _Mathematics for Computer Science_                      | Tom Leighton MIT 6.042J         |
| **[Sistemas Operacionais](#sistemas-operacionais)**   | A maior parte do código que você escreve é processado por um sistema operacional, então é uma boa entender como os dois interagem.                                          | _Operating Systems: Three Easy Pieces_                  | Berkeley CS 162                   |
| **[Redes de Computadores](#redes-de-computadores)**           | A internet aparentemente é importante: descubra como ela funciona e desbloqueie todo o seu potencial                                           | _Redes de Computadores e A Internet - Uma Abordagem Top-Down_              | Stanford CS 144                   |
| **[Bancos de Dados](#banco-de-dados)**                 | Dados são essenciais para a maioria dos programas, mas poucos entendem como bancos de dados realmente funcionam.                                 | _Readings in Database Systems_                          | Joe Hellerstein Berkeley CS 186 |
| **[Linguagens e Compiladores](#linguagens-e-compiladores)**       | Se você entender como linguagens e compiladores funcionam, você vai melhorar sua habilidade de programar e vai aprender linguagens com mais facilidade.               | _Compiladores: Princípios, Técnicas e Ferramentas_           | Curso do Alex Aiken na Lagunita   |
| **[Sistemas Distribuídos](#sistemas-distribuídos)** | Atualmente, a _maioria_ dos sistemas são sistemas distribuídos.                                                   | _Sistemas Distribuídos: Princípios e Paradigmas_ | MIT 6.824                         |
                     

## Por que aprender ciência da computação?

Existem dois tipos de engenheiro de software: Os que entendem ciencia da computacao bem o suficiente para conseguir realizar tarefas desafiadoras e inovadoras, e aqueles que estão familiarizados com as ferramentas e conseguem fazer o suficiente.

Os dois dizem ser engenheiros de software, e os dois começam com salários parecidos no início das carreiras. Mas os engenheiros do tipo 1 crescem e acabam trabalhando em projetos mais gratificantes e bem remunerados, seja em trabalhos comerciais ou em projetos de open-source inovadores, na liderança técnica ou na maior qualidade nas contribuições individuais.

> O sistema global de SMS produz em média 20 bilhões de mensagens por dia. Whatsapp faz 42 bilhões. Com 57 engenheiros. [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)

> — Benedict Evans (@BenedictEvans) [2 de Fervereiro, 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

Engenheiros tipo 1 acham novas maneiras de aprender informática a fundo, seja por meios convencionais ou através do incessante apredizado ao longo de suas carreiras. Engenheiros tipo 2 geralmente ficam no superfície, estudando ferramentas e tecnologias específicas ao invés de fortalecer o seu conhecimento fundamental, apenas melhorando suas habilidades quando novas tecnologias surgem no mercado.

No momento, o número de pessoas entrando na indústria cresce rapidamente, enquanto o número de graduandos de ciência da computação é essencialmente estático. Esse superabastecimento de engenheiros do segundo tipo está começando a reduzir suas oportunidades de emprego, e os deixando de fora dos trabalhos e serviços mais gratificantes da indústria.

> KKKKK a mas eles estavam….[pic.twitter.com/XVNYlXAHar](https://t.co/XVNYlXAHar)

>

> — Jenna Bilotta (@jenna) [4 de Março, 2017](https://twitter.com/jenna/status/838161631662092289)

## Guia dos assuntos

### Programação

A maioria dos cursos universitários de ciência da computação começam com uma introdução a programação. Os melhores cursos não tentam só atender as necessidades dos inexperientes, mas também os que não aprenderam conceitos benéficos e modelos de programação quando aprendendo a programar pela primeira vez.

Nossa recomendação padrão para esse tema é o clássico _Structure and Interpretation of Computer Programs_ (em português: Estrutura e Interpretação de Programas de Computador), que está disponivel online de graça (em inglês), tanto como [livro](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), como também numa série de [video aulas do MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). Mesmo que essas video aulas sejam ótimas, nossa sugestão é: [Brian Harvey’s SICP lectures](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (para o curso 61A na universidade Berkeley). Elas são mais refinadas e melhor direcionadas para novatos do que as do MIT. 

Recomendamos estudar os primeiros três capítulos do SICP, fazendo todos os exercícios. Para prática adicional, faça alguns problemas simples como os achados no [exercism](http://exercism.io) ou no [the huxley](https://www.thehuxley.com/).

Aos que acharem SICP muito dificil, recomendamos: _[How to Design Programs](http://www.htdp.org/)_. Para aqueles que acharam muito fácil: _[Concepts, Techniques, and Models of Computer Programming](https://smile.amazon.com/Concepts-Techniques-Models-Computer-Programming/dp/0262220695/)_.

### Arquitetura de computadores

Arquitetura de computadores é um importante primeiro contato com a computação por baixo da camada de software. Na nossa experiência, é umas das áreas mais negligenciadas por engenheiros de software autodidatas.

_The Elements of Computing Systems_ (Os Elementos de Sistema de Computação), também conhecido como “Nand2Tetris” (do Nand para o Tetris), é um livro ambicioso, que tenta dar ao leitor um entendimento fundamental de como tudo funciona num computador. Cada capítulo gira em torno da construção de uma pequena peça do sistema, desde escrever o funcionamento de portas lógicas em HDL (hardware description language), uma CPU e um assembler, até uma aplicação do tamanho de um jogo de tetris.

Nós recomendamos ler os primeiros seis capítulos do livro, completando os projetos associados a cada um. Você irá desenvolver um entendimento sobre a relação entre a arquitetura de uma máquina e o software que nela roda.

A primeira metade do livro (e todos os projetos e software necessários) estão no [site oficial Nand2Tetris](http://www.nand2tetris.org). Também está disponível como [um curso no Coursera](https://www.coursera.org/learn/build-a-computer).

Na busca pela simplicidade e coesão, Nand2Tetris deixa de ir muito a fundo nos assuntos. Em especial, o pipelining e a hierarquia de memória são dois conceitos muito importantes na arquitetura de computadores modernos, mas os dois não aparecem muito no texto.

Quando você se sentir confortável com o conteúdo do livro, nossa próxima sugestão é o _[Organização e projeto de computadores: a Interface Hardware/software ](hhttps://www.amazon.com.br/Organiza%C3%A7%C3%A3o-Projeto-Computadores-John-Hennessy/dp/8535287930/ref=asc_df_8535287930/?tag=googleshopp00-20&linkCode=df0&hvadid=379765802390&hvpos=&hvnetw=g&hvrand=3048146368676827379&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1001506&hvtargid=pla-812161947068&psc=1)_, um texto excelente. Nem todas as seções são essenciais, sugerimos o seguinte [curso da Berkeley](http://inst.eecs.berkeley.edu/~cs61c/sp15/) para leituras especificas. As anotações e video  aulas estão disponiveis [no Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

[![Elements of Computing Systems](https://teachyourselfcs.com/elements-computing-systems.jpg)](http://www.nand2tetris.org) 

> Hardware é a plataforma
>
> — Mike Acton, Diretor Engenheiro na Insomniac Games
> ([watch his CppCon talk](https://www.youtube.com/watch?v=rX0ItVEVjHc))


### Algoritmos e Estrutura de Dados

Concordamos com o senso comum de que, familiaridade com algoritmos e estrutura de dados são um dos aspectos mais empoderadores da educação de ciência da computação. Essa área também desenvolve a sua capacidade de resolver problemas, uma habilidade que vai ser útil para todas as áreas.

Existem centenas de livros por aí, mas o nosso favorito é o _[The Algorithm Design Manual](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/)_ (Manual de Design de Algoritmos) do Steven Skiena. Ele claramente ama o que ensina, e quer muito te ajudar a entender. Uma mudança que achamos bem vinda, se comparar com os textos mais recomendados do Leiserson, Rivest & Stein, ou Sedgewick. Os dois últimos tendem a ser muito voltados a provas rigorosas para aqueles aprendendo com o objetivo de _resolver problemas_. 

Aos que preferem video aulas, [o Skiena coloca as suas online](https://www.youtube.com/watch?v=A2bFN3MyNDA&list=PLOtl7M3yp-DX32N0fVIyvn7ipWKNGmwpp). Nós também adoramos o o curso do Tim Roughgarden, disponivel na Stanford Lagunita, ou no [on Coursera](https://www.coursera.org/specializations/algorithms). Se você prefere o estilo do Skiena ou do Roughgarden, é uma questão de gosto.

Para prática, nossa abordagem preferida para estudantes resolverem problemas é o [Leetcode](https://leetcode.com). Tende ter problemas interessantes com soluções e discussões decentes. Eles também te ajudam a testar seu progresso utilizando perguntas comuns em entrevistas técnicas das empresas mais competitivas. Recomendamos resolver 100 problemas aleatório como parte do seu estudo.

E por fim, recomendamos _[A Arte de Resolver Problemas](https://www.amazon.com.br/Arte-Resolver-Problemas-G-Polya/dp/8571931364)_ como um excelente guia para resolução geral de problemas; é útil tanto para ciência da computação assim como para matemática. 

[![The Algorithm Design Manual](https://teachyourselfcs.com/skiena.jpg)](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) [![Arte de Resolver Problemas](https://img.wook.pt/images/a-arte-de-resolver-problemas-g-polya/MXwxODA0MDV8MjI4OTczfDEzODM1MjMyMDAwMDA=/250x)](https://www.amazon.com.br/Arte-Resolver-Problemas-G-Polya/dp/8571931364) 

> Eu tenho um método que eu recomendo extensivamente - chamado pense antes de escrever
>
>— Richard Hamming

### Matemática para ciência da computação

De certas formas, ciência da computação é uma ramo da matemática aplicada. Enquanto muitos engenheiros de software tentam, e de certa forma conseguem, ignorar-la, nós te encorajamos aceitá-la. Fazendo isso com sucesso, você irá ganhar uma grande vantagem competitiva sobre os que não. 

A área mais relevante para CC é o que é chamado de “matemática discreta”, onde “discreto” é o oposto de “contínuo”, e é uma coleção de tópicos de matemática aplicada fora do cálculo. Dada essa definição super vaga, não vale a pena estudar tudo relacionado ao tópico. Um guia mais realístico é construir um entendimento útil da lógica, combinatória e probabilidade, teoria dos conjuntos, teoria dos grafos, e um pouco de teoria dos números para criptografia. Algebra linear também é um adicional que vale a pena, dada a sua importância em computação gráfica e machine learning.

Nosso ponto de partida sugerido para matemática discreta são [anotações feitas por László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps) Professor László Lovász fez um ótimo trabalho fazendo o conteúdo acessível e intuitivo, serve como melhor ponto de partida do que textos mais formais. 

Para estudos mais avançados, sugerimos _[Matemática para ciência da computação
](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf)_, as anotações (do tamanho de um livro) para o curso do MIT de mesmo nome. As aulas também estão [disponíveis online de graça](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), e são nossas vídeo aulas recomendadas para matemática discreta.

Para algebra linear, nós sugerimos começar com os videos [A essência da algebra linear](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) uma serie de video aulas incriveis e com legendas disponiveis em portugues. Depois disso use o livro](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/)  do Gilbert Strang e a série de [video aulas](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

> Se você não acredita que a matemática é simples, é só porque você não entende o quão complicada a vida é.
>
>— John von Neumann

### Sistemas Operacionais

_[Operating System Concepts](https://www.amazon.com/dp/1118063333/)_  e _[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)_ são os livros “clássicos” quando se trata de sistemas operacionais. Os dois foram criticados pela sua escrita e estilo, e por ser o tipo de livro que tem 1000 páginas e tem suas edições revisadas depois de alguns anos para que você compre a nova edição.

_Operating Systems: Three Easy Pieces_ é uma boa alternativa que está disponível [online de graça](http://pages.cs.wisc.edu/~remzi/OSTEP/). Nós gostamos da estrutura do livro e achamos que os exercícios valem a pena.

Depois do OSTEP, encorajamos você a explorar as decisões de design de sistemas operacionais específicos, usando os livros do estilo “{nome do SO} internals”, como por exemplo _[Lion's commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)_, _[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)_, e _[Mac OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)_.

Uma ótima maneira de consolidar o seu entendimento é ler o código fonte de um kernel pequeno e adicionar novas funcionalidades. Uma ótima escolha é [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), um porte do unix V6 para ANSI C e x86 mantido para um curso no MIT. OSTEP tem um apêndice de [xv6 labs](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf), cheio de ideias incríveis para possíveis projetos. 

### Redes de Computadores

Já que a maioria da desenvolvimento de software acontece nos servidores e clientes, uma das áreas mais valiosas da ciência da computação são redes de computadores. Nossos alunos autodidatas que estudam redes metodicamente sentem que eles finalmente entendem conceitos, termos e protocolos que estavam ao redor deles por anos.

Nosso livro favorito do assunto é _[CRedes de Computadores e A Internet - Uma Abordagem Top-Down](https://www.saraiva.com.br/redes-de-computadores-e-a-internet-uma-abordagem-top-down-6-ed-2013-8223157/p)_. Os pequenos projetos e exercícios no livro valem muito a pena serem feitos, nós gostamos particularmente do “Wireshark labs”, que [eles deixam online](http://www-net.cs.umass.edu/wireshark-labs/).

Para os que preferem video aulas, sugerimos o curso [_Introduction to Computer Networking ](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about), disponível no MOOC lagunita. 

O estudo de redes se beneficia mais através de grandes projetos do que através de pequenos exercícios. Alguns possíveis projetos são, por exemplo: um server HTTP, ou um chat baseado em UDP, uma [mini stack de TCP](http://jvns.ca/blog/2014/08/12/what-happens-if-you-write-a-tcp-stack-in-python/), um proxy, ou um balanceador de carga, e uma hash table distribuída. 

>Você pode olhar para uma bola de cristal e ver o futuro. O que a internet vai ser no futuro vai ser definido pelo que a sociedade decidir. 
>
>— Bob Kahn

[![Computer Networking: A Top-Down Approach](http://lojasaraiva.vteximg.com.br/arquivos/ids/12105154/1009651669.jpg?v=637142233019400000)](https://www.saraiva.com.br/redes-de-computadores-e-a-internet-uma-abordagem-top-down-6-ed-2013-8223157/p) 

### Banco de Dados

Requer mais esforço aprender sobre sistemas de banco de dados do que a maioria dos outros tópicos. É uma área de estudo ainda muito imatura, com incentivos comerciais muito fortes para manter boas ideias em segredo. E ainda, muitos possíveis autores de livros didáticos preferem se juntar a uma ou criar uma empresa.
 
Dadas a ciscunstâncias nós sugerimos autodidatas ignorarem os livros e comecar com a [CS 186](https://archive.org/details/UCBerkeley_Course_Computer_Science_186), o curso de banco de dados da Berkeley e comecar a ler artigos logo após.

Um artigo em especial vale a pena ser mencionado a novos estudantes, o “[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)” que unicamente dá uma visão abstrata de como sistemas de gerenciamento de banco de dados relacionais (SGBD) funcionam. Isso serve como esqueleto para futuros estudos. 

_Readings in Database Systems_ mais conhecido como [“The Red Book”](http://www.redbook.io/) é uma colecao de artigos compilados e editados por Peter Bailis, Joe Hellerstein e Michael Stonebraker. para os que já progrediram além do nível da CS 186, o Red Book deve ser a sua próxima parada.

Se você insiste em usar um livro introdutório, sugerimos t _[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)_ por Ramakrishnan e Gehrke. Para estudantes mais avançados o clássico _[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)_  vale a pena, mas nós não incentivamos usá-lo como primeiro recurso.

É difícil consolidar os conceitos sem escrever uma quantidade considerável de código. Os alunos do CS 186 adicionaram recursos ao Spark, que é um projeto razoável, mas sugerimos escrever, do zero, um simples sistema de gerenciamento de banco de dados relacional. Não será cheio de recursos, mas será esclarecedor mesmo escrevendo a versão mais rudimentar de cada componente de um SGBD típico.

Por fim, a modelagem de dados é um aspecto negligenciado e mal ensinado sobre o trabalho com bancos de dados. Nosso livro sugerido é o _[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)_.

### Linguagens e Compiladores

A maioria dos programadores aprende linguagens específicas, enquanto a maioria dos cientistas da computação aprendem _sobre_ linguagens. Isso dá ao cientista da computação uma vantagem distinta em relação ao programador, mesmo no domínio da programação! Seu conhecimento é generalizado; eles são capazes de entender o funcionamento de uma nova linguagem mais profunda e rapidamente do que os que aprendem linguagens específicas.

O texto introdutório padrão é o _[Compiladores: Princípios, Técnicas e Ferramentas](https://www.amazon.com.br/Compiladores-princ%C3%ADpios-ferramentas-Alfred-Aho/dp/8588639246)_, comumente chamado de "o Livro do Dragão" (Dragon Book). Infelizmente, ele não foi feito para auto-estudo, mas sim para que os professores escolham conteúdo suficiente para 1-2 semestres de curso. É essencial, então, que você escolha os tópicos a dedo, ou de preferência com a ajuda de um mentor.

Se você optar por usar o Dragon Book para seus estudos, recomendamos seguir alguma série de video aulas para ajudar com a estruturação do aprendizado, depois ir mergulhando mais profundamente no livro conforme necessário. Nossa reocmendação de curso online é [o do Alex Aiken, disponível na plataforma MOOC da Stanford Lagunita](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/about).

Como possivel alternativa ao Dragon Book sugerimos _[Language Implementation Patterns](https://smile.amazon.com/Language-Implementation-Patterns-Domain-Specific-Programming/dp/193435645X/)_ por Terence Parr. Ele é escrito mais diretamente para o engenheiro de software praticante que pretende trabalhar em pequenos projetos de linguagem como como DSLs, o que pode torná-lo mais útil para você. É claro que, para isso, ele sacrifica bastante profundidade. 

Para projetos, sugerimos escrever um compilador para uma linguagem didática simples como COOL, ou para um subconjunto de uma linguagem que lhe interesse. Quem achar esse projeto muito difícil pode começar com o [Make a Lisp](https://github.com/kanaka/mal), que te ajuda em cada etapa do projeto.

[![Compiladores: Princípios, Técnicas e Ferramentas](https://lojasaraiva.vteximg.com.br/arquivos/ids/7461119/522430.jpg?v=637087093968900000)](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811) [![Language Implementation Patterns](https://teachyourselfcs.com/parr.jpg)](https://smile.amazon.com/Language-Implementation-Patterns-Domain-Specific-Programming/dp/193435645X/) 

> Não seja um programador padrão. Construa ferramentas para usuários e outros programadores. Tome nota histórica da indústria têxtil e siderúrgica: você quer construir máquinas e ferramentas, ou quer operar essas máquinas?
>
>— Ras Bodik no início de seu curso de compiladores

### Sistemas Distribuídos

Os computadores têm aumentado em número, e com isso eles também têm _se espalhado_. Enquanto que antigamente empresas adquiriam mainframes cada vez maiores, hoje em dia é típico que mesmo aplicações muito pequenas rodem em várias máquinas. Sistemas distribuídos é o estudo de como raciocinar os trade-offs envolvidos com a execução disso, uma habilidade cada vez mais importante.

Nosso livro sugerido é o _[Sistemas Distribuídos: Princípios e Paradigmas](https://www.amazon.com.br/Sistemas-distribu%C3%ADdos-princ%C3%ADpios-Andrew-Tanenbaum/dp/8576051427)_ de Maarten van Steen e Andrew Tanenbaum. A terceira edição está disponível online de graça, graças à generosidade de seus autores. Como sistemas distribuídos são um campo em constante mudança, nenhum livro didático servirá como guia definitivo, mas esse dá a melhor descrição dos assuntos mais fundamentais e consolidados que já vimos.

Um bom curso que tem alguns vídeos online é [6.824 do MIT](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) (um curso de pós-graduação), mas infelizmente as gravações tem péssima qualidade de audio, e não está claro se as gravações foram autorizadas. *[Atualização @ Mar 2020: [os vídeos da palestra oficial do curso](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) já foram publicados!]*

Não importa a escolha do livro ou de outros recursos, o estudo de sistemas distribuídos _exige_ a leitura de artigos. Uma boa lista pode ser achada aqui [aqui](http://dsrg.pdos.csail.mit.edu/papers/), e te incentivamos a participar do seu [Papers We Love](http://paperswelove.org/) local.

## Perguntas frequentes 

### E quanto a IA/Computação Gráfica/etc?

Nós tentamos limitar nossa lista para tópicos que nós achamos essenciais para todos os engenheiros de software_, independentemente da especialidade. Com essa fundação, você estará numa posição muito melhor para simplesmente usar livros e ler artigos sem precisar de algum tipo de guia. Aqui nossos pontos de partida para essas “eletivas”:


*   Inteligencia artifical: faça [curso introdutório da Berkeley](http://ai.berkeley.edu/). Vendo os vídeos e completando os projetos excelentes de pacman. E use o livro _Artificial Intelligence: A Modern Approach_ por Russell e Norvig.

*   Para machine learning: o curso do Andrew Ng na coursera. Seja paciente, e tenha certeza que você entende os fundamental antes de ir atrás de novos conhecimentos como deep learning. 

*   Para computação gráfica faça o [curso 184 de CC da Berkeley](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) e use [Computer Graphics: Principles and Practice](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) como livro.
 
### Quão rígida é a sequência sugerida?

Realisticamente, todos os assuntos possui um nível significante de conhecimento compartilhado, e se auto referenciam. Por exemplo, a relação entre matemática discreta e algoritmos: Aprender matemática antes te ajudaria a analisar e entender seus algoritmos com mais profundidade, mas aprender os algoritmos servem de grande motivação e familiarização para a matemática discreta. Idealmente, você vai revisitar esses tópicos muitas vezes ao longo da sua carreira.

Sendo assim, nossa sequência sugerida está aí mais para te ajudar a _começar_… se você tiver razões convincentes para escolher outra sequência, só vai. Os pré-requisitos mais significativos, na nossa opinião, são: arquitetura de computadores antes de sistemas operacionais ou banco de dados, e redes de computadores e sistemas operacionais antes de sistemas distribuídos.


### Quem é o público alvo deste guia?

Nós temos em mente que você é um engenheiro de software, graduando de bootcamp ou um estudante de ensino médio precoce, ou um universitário procurando uma educação complementar. A decisão de quando embarcar nessa jornada é inteiramente pessoal, mas a maioria das pessoas tem algum beneficio por ter alguma experiência profissional antes de se aprofundar nos tópicos de ciência da computação. Por exemplo, nós percebemos que estudantes _amam_ aprender sobre banco de dados se eles já trabalharam profissionalmente na área, ou redes de computadores se eles já trabalharam num projeto web ou dois. 

### Como isso se compara ao currículo da Open Source Society ou do freeCodeCamp?

O [OSS guide](https://github.com/open-source-society/computer-science) tem muitos assuntos, sugerem referências inferiores para grande parte, e nao dao nenhum raciocínio ou guia sobre o por quê e quais aspectos dos cursos em particular são valiosos. Nós nos esforçamos para limitar os cursos que você _realmente_ precisa saber e para te ajudar a entender o por quê de cada curso. 

freeCodeCamp foca mais na programação e não na ciência da computação. O por quê de você querer aprender ciencia da computacao veja [acima](#why).

### E a linguagem X?

Aprender uma linguagem em particular, é uma coisa totalmente diferente de aprender sobre uma área da ciência da computação - uma linguagem é muito _mais fácil_, e _menos significativo_.  Se você já é proficiente em algumas linguagens, nós sugerimos seguir o guia e ir colocar o aprendizado de novas linguagens no meio, ou simplesmente deixar para depois. Se você aprendeu programação bem, e especialmente se você aprendeu sobre compiladores, você vai levar não mais de uma semana para aprender os fundamentos de uma nova linguagem. 

### E a tecnologia X que está na moda?

Nenhuma tecnologia é tão importante que aprender a usá-la deve ser parte dos fundamentos da sua educação. Por outro lado, é muito bom que você está animado para aprender essa coisa nova. O truque está em trabalhar de trás para frente da tecnologia em particular até os fundamentos e conceitos, e aprender aquilo bem antes de ver como a sua tecnologia se encaixa no panorama geral. 

### Por que ainda estão recomendo o “dragon book”?

O “Dragon book” ainda é um dos melhores recursos para compiladores. Tem uma má fama, especialmente por colocar muita ênfase em certos tópicos que não são tão importantes hoje em dia. Mas o livro nao foi idealizado para ser lido por completo, mas dar material suficiente para um instrutor conseguir montar um curso. Similarmente, um autodidata pode escolher sua própria aventura com o livro, ou melhor ainda seguir sugestões de professores em seus resumos/guias de leitura.


### Como posso conseguir livros baratos?

Graças a generosidade dos seus autores, muitos dos livros que sugerimos são achados de graça online. Para os que não são, nós sugerimos comprar edições usadas. Como regra geral, se existe varias edições de um livro, é muito provável que as edições mais antigas ainda sejam perfeitamente adequadas. É muito difícil que a nova versão seja 10x melhor que as mais velhas, mesmo que a diferença de preço seja.

### Quem fez isso?

Esse guia foi escrito por [Ozan Onay](https://twitter.com/oznova_) e [Myles Byrne](https://twitter.com/quackingduck), instrutores na [Bradfield School of Computer Science](https://bradfieldcs.com) em São Francisco. É baseado na nossa experiência ensinando os fundamentos da ciência da computação para centenas de engenheiros (muitos autodidatas) ou graduados de bootcamps. Muito obrigado a todos os estudantes pelo feedback contínuo sobre meios para o aprendizado autodidata. Obrigado também a Alek Sharma, Omar Rayward, Ammar Mian and Tyler Bettilyon, pelo feedback sobre o guia.

### Quem é o tradutor?

Iae galera, meu nome é Clemens Schrage, eu sou estudante de ciência de computação da UFAL (Universidade Federal de Alagoas). Se vocês tiverem alguma sugestão pra ajudar na tradução, eu acharia irado, só fazer um pull. Eu realmente não sei escrever direito e isso aqui tá uma bagunça. Espero que eu tenha ajudado quem quer que esteja lendo isso, porque o texto original me ajudou bastante. Abração ae galera. 
