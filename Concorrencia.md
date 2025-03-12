&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Conversando com minha amiga Milena, percebi que não sabia explicar o que era "Concurrent Programming". A tradução direta soava estranha: "Programação concorrente"—seria um programa para disputar eleições? Concursos de beleza? Se estivermos falando de código bonito, eu certamente perderia essa competição.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Percebi que precisava estudar mais. Passei alguns dias imerso em livros, mas não antes de gastar uns bons 40 minutos apenas tentando traduzir "Concurrent Programming":

<ul>
  <li>Programação concorrente - Já discutimos essa opção um tanto esquisita...;</li>
  <li>Programação multitarefa - Que porcaria foi essa, ChatGPT?!;</li>
  <li>Execução simultânea de tarefas - Parece longo, mas algo chamou minha atenção.;</li>
</ul>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Simultânea. Essa palavra captura bem a imagem que me vem à mente ao pensar em Concurrent Programming. Então, temos nossa tradução quase ideal: "Programação Simultânea".

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Afinal, quem nunca se perguntou como o computador consegue fazer tantas coisas ao mesmo tempo? Um jogo online, um podcast de informações pseudocientíficas duvidosas, uma animação de fundo no estilo Windows Media Player antigo... e ainda manter o relógio no horário? Essas máquinas são incríveis!

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Antes de partir para explicações técnicas, vamos a uma analogia. Imagine uma lanchonete: a Lanchonete da Dona Eliana. Como ainda não contratou funcionários, ela cuida de tudo sozinha:

<ul>
  <li>Anotar os pedidos;</li>
  <li>Receber os pagamentos;</li>
  <li>Grelhar as carnes;</li>
  <li>Tostar os pães;</li>
  <li>Fritar as batatas;</li>
  <li>Montar os hambúrgueres;</li>
  <li>Entregar os pedidos;</li>
  <li>Limpar as mesas.</li>
</ul>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;No início, com apenas cinco clientes fiéis, Dona Eliana conseguia manter tudo em ordem. Para esses clientes, parecia que tudo funcionava perfeitamente: nenhum pedido atrasava, a casa estava sempre limpa e o lanche sempre no ponto certo. Mas um dia, uma influencer local descobriu sua lanchonete. No sábado seguinte, 30 novos clientes apareceram, e o caos se instalou: pedidos atrasados, troco errado, carnes queimadas, batatas cruas, mesas sujas. No fim do dia, ficou claro que ela precisava de ajuda. Mas essa história fica para depois.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Podemos pensar no nosso computador como a lanchonete da Dona Eliana. Quem usou um PC nos anos 90 (ou herdou uma máquina velha de um irmão mais velho ou do escritório do pai) sabe o que acontece ao abrir Paint, Paciência Spider e Windows Media Player ao mesmo tempo: tudo fica lento. Para os leitores da Geração Z, isso equivale a travar o computador com seis abas do Chrome abertas, enquanto você tenta acertar seu headshot no Valorant ouvindo a última da Billie Eilish no Spotify.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Antes do primeiro processador dual-core da Intel, em 2005, vivíamos em um mundo onde os processadores tinham apenas uma unidade de processamento e na falsa ilusão de que tudo ocorria simultaneamente. Na verdade, essa impressão vem da nossa percepção limitada do tempo. Para nós, um segundo é pouco. Para um computador, é tempo suficiente para executar bilhões de operações. Assim, essa máquina mágica nos dá a ilusão da simultaneidade.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Digamos que, em um segundo, ele gaste um milhão de operações para atualizar o relógio. Ainda assim, dentro desse mesmo segundo, restam 999 milhões de operações livres para processar todas as outras tarefas que estamos executando. Para nós, tudo parece ocorrer harmoniosamente, assim como os primeiros clientes da lanchonete acreditavam que Dona Eliana conseguia lidar perfeitamente com todas as tarefas. Mas, à medida que a carga de trabalho aumenta—abrindo novos programas, rodando múltiplas tarefas—começamos a perceber que essa ilusão de simultaneidade começa a ruir. Isso acontece porque o processador enfrenta o mesmo problema da Dona Eliana: tenta fazer muitas tarefas ao “mesmo tempo”, mas tem limitações.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E então, voltamos à nossa tradução: "Programação Simultânea". Parece enganosa agora que sabemos a verdade, não? Afinal, o processador não está realmente fazendo tudo ao mesmo tempo, mas sim alternando entre tarefas de forma extremamente rápida, criando essa ilusão. Talvez. Mas, no fim das contas, ao escrever um programa concorrente, buscamos exatamente isso: organizar e otimizar as execuções para que o processador possa lidar eficientemente com todas as tarefas, assim como Dona Eliana tentava manter tudo sob controle sem deixar nada para trás.
