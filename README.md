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
