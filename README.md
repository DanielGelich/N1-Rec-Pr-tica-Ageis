# N1-Rec-Pr-tica-Ageis

Prova refeita !

1a - User Stories são descrições simples de requisitos em desenvolvimento ágil de
software, focadas no usuário. Elas comunicam necessidades, priorizam funcionalidades e
facilitam estimativas e planejamento.

1b - “Como um cliente interessado em comprar produtos no e-commerce, eu quero ter a
capacidade de pesquisar produtos pelo nome, para encontrar rapidamente os itens
desejados.”

  ● O campo de pesquisa deve aceitar texto livre para inserir o nome do produto.
  ● A pesquisa deve ser iniciada automaticamente à medida que o usuário digita.

1c - “Como um cliente que gosta de explorar ofertas, eu quero receber recomendações
personalizadas de produtos relacionados enquanto navego pelo e-commerce, para
encontrar itens complementares ou de interesse.”

  ● As recomendações devem ser exibidas na página de detalhes do produto, abaixo
das informações do produto visualizado.
  ● Cada recomendação deve incluir uma imagem, nome e preço do produto.

“Como um administrador do e-commerce, eu quero ter a capacidade de gerenciar
facilmente o catálogo de produtos, para adicionar, editar ou remover produtos de forma
eficiente.”

  ● Deve ser possível adicionar novos produtos ao catálogo, inserindo informações
como nome, descrição, preço e imagem.
  ● Os produtos existentes devem ser editáveis, permitindo a atualização de
informações, como preço e descrição.

1d -

  ● Deve ser possível selecionar o mês e o ano para os quais o relatório deve ser
gerado.
  ● O sistema deve calcular automaticamente os dados de vendas mensais com base
nas transações registradas no período selecionado.

2a
@Test
  public void testStringInvertWithEmptyString() {
    String input = "";
    String result = StringUtil.string_invert(input);
    assertEquals("", result);
  }
  
2b
@Test
  public void testStringInvertWithSingleCharacter() {
    String input = "a";
    String result = StringUtil.string_invert(input);
    assertEquals("a", result);
  }
  
2c
@Test
  public void testStringInvertWithMultipleCharacters() {
    String input = "Hello";
    String result = StringUtil.string_invert(input);
    assertEquals("olleH", result);
  }
  
3a
  public static int contarCaracteres(String str) {
    return str.length();
  }

3b
@Test
  public void testContarCaracteresComStringVazia() {
    String input = "";
    int resultado = StringUtil.contarCaracteres(input);
    assertEquals(0, resultado);
  }

Ativ. Recuperação !

1.1 - C) Escrever o teste, executar o teste, escrever o código, executar o teste novamente, refatorar e, por fim, integrar o código ao repositório principal.

1.2 - O modelo do TDD é baseado em escrever testes iniciais, onde eles irão falhar a primeiro momento e então escrever o codigo para que ele passe nos testes que foram definidos, executar os testes até que o código passe por todos eles e seja aceito para ai então que os código seja refatorado para um código mais solido e organizado para emfim integra-lo ao repositório princinpal.

2.1 - A partir do momento que a Epic esteja definida, seria organizado uma reunião para todos os presentes, pensarem como um cliente e cada um dar a sua UserStory para então ter uma certeza melhor sobre como seria uma visão de uso sobre o código e o desenvolvimento dele.

Epic: Desenvolver um sistema de gerenciamento de tarefas.

User Stories:

Como um usuário, quero poder criar uma nova tarefa com um título e uma descrição.
Como um usuário, quero poder atribuir uma prioridade a uma tarefa (alta, média ou baixa).
Como um usuário, quero ser capaz de definir uma data de vencimento para uma tarefa.
Como um usuário, quero poder marcar uma tarefa como concluída.
Como um usuário, quero ver uma lista de todas as tarefas pendentes.
Como um usuário, quero ser notificado por e-mail quando uma tarefa estiver prestes a vencer.

2.2 - Os critérios de aceitação para uma história de usuário são declarações que descrevem condições específicas que devem ser atendidas para que um objeto seja considerado completo. É importante garantir um entendimento comum dos requisitos, estabelecer critérios objetivos de desempenho, facilitar a comunicação da equipe, permitir a geração automatizada de testes, definir restrições de escopo e melhorar a qualidade do desenvolvimento. Em outras palavras, os critérios de aceitação desempenham um papel crítico no desenvolvimento ágil, impulsionando a entrega de recursos que atendem às expectativas do cliente e às capacidades da equipe.

3.1 - Um teste unitário é uma verificação detalhada e independente de unidades de código, como funções ou classes, para garantir seu correto funcionamento. Seu principal objetivo é identificar erros no nível mais granular possível, permitindo correções rápidas e melhorando a qualidade e a confiabilidade do software.

3.2 - O "mocking" em testes unitários é a técnica de criar substitutos controlados para partes do sistema real durante os testes, permitindo isolar a unidade de código em teste e verificar sua lógica interna de forma eficaz. Isso simplifica a criação de testes independentes e confiáveis, independentemente do ambiente externo.

4.1 - A refatoração no XP (Desenvolvimento Extremo) é a prática de aprimorar constantemente o código sem alterar seu comportamento externo. Isso promove a simplicidade, a comunicação eficaz, a entrega incremental e a adaptação às mudanças. Os desenvolvedores refatoram regularmente para manter o código limpo e adaptável, garantindo qualidade e agilidade no desenvolvimento de software.

4.2 - A "programação em pares" é uma prática na qual dois programadores trabalham juntos em um único computador. Um escreve o código, enquanto o outro revisa em tempo real. Isso melhora a qualidade, a criatividade, a produtividade e a transferência de conhecimento, reduz erros e interrupções, resultando em um desenvolvimento de software mais eficiente e robusto.

4.3 - No XP (Desenvolvimento Extremo), o TDD (Test-Driven Development) é aplicado escrevendo testes automatizados antes de escrever o código de produção. Os testes devem inicialmente falhar, garantindo que os requisitos sejam claros. Em seguida, é implementada a funcionalidade mínima necessária para fazer os testes passarem. Depois, o código é refatorado e o ciclo continua em pequenas iterações. Isso garante que o código seja testado abrangentemente, promove desenvolvimento incremental e melhora a qualidade do software, contribuindo para a entrega contínua e eficaz de funcionalidades.

5.1 - Usaria o tempo médio em desenvolvimento, a qualidade do código, o peso da task e o tempo médio para resolução de problemas.

5.2 - Histórias de usuários e épicos são ferramentas que facilitam a comunicação entre desenvolvedores e partes interessadas não técnicas. Ele usa uma linguagem acessível, concentra-se no valor do usuário e é apresentado visualmente para uma compreensão e priorização transparentes. A entrega incremental e o feedback contínuo facilitam a adaptação às mudanças nos requisitos. Estas ferramentas promovem a compreensão mútua, o alinhamento de objetivos e processos de desenvolvimento transparentes e colaborativos.
