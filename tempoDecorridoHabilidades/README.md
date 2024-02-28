<h1>. Introdução</h1>
A funcionalidade de atualização dinâmica do tempo de habilidades é uma maneira eficiente de mostrar aos usuários quanto tempo se passou desde o início de uma habilidade ou experiência específica. Isso é feito de forma dinâmica, ou seja, o tempo é atualizado automaticamente em tempo real sem a necessidade de recarregar a página.

<h2>Requisitos</h2>
Antes de usar este recurso, certifique-se de ter:

Uma página da web onde deseja exibir o tempo decorrido das habilidades.
Elementos HTML com a classe .tempo-habilidades onde o tempo decorrido será mostrado.
O atributo data-start-date definido em cada elemento com a data de início da habilidade.

<h2>Como Integrar o Script</h2>
Para integrar o script em sua página da web, siga estas etapas:

Copie o código do script fornecido abaixo:
javascript
Copy code
// Cole aqui o código do script
Cole o código no arquivo JavaScript de sua página da web, preferencialmente antes do fechamento da tag </body>.

Certifique-se de que os elementos HTML onde deseja mostrar o tempo decorrido tenham a classe .tempo-habilidades e o atributo data-start-date definido com a data de início da habilidade.

<h2>Uso</h2>
Após integrar o script em sua página, o tempo decorrido das habilidades será atualizado dinamicamente. Não é necessário nenhum esforço adicional. A funcionalidade atualiza o tempo automaticamente a cada segundo.

<h2>Exemplo</h2>
Veja um exemplo simples de como os elementos HTML podem ser configurados para usar a funcionalidade:

html

<p>Sua habilidade em JavaScript: <span class="tempo-habilidades" data-start-date="2020-01-01">Carregando...</span></p>
Neste exemplo, o tempo decorrido desde o início da habilidade será exibido dentro do elemento <span> com a classe .tempo-habilidades. Certifique-se de substituir a data de exemplo (2020-01-01) pela data de início real da habilidade.
