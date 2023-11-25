<h1 align="center">Avaliação Coding Tank</h1>
<h2 align="center">Instruções importantes</h2>
<p>Crie um notebook intitulado seu_nome_completo.ipynb (com o seu nome completo) e responda às perguntas justificando sua resposta em todos os casos.</p>
<p>As alternativas corretas devem ser indicadas e justificadas. Nas questões que pedem que um código seja escrito, inclua o código bem como comentários explicando seu raciocínio.</p>
<p>Nesta avaliação serão considerados apenas soluções que utilizem os conteúdos ensinados em aula. Não use conteúdo extra, mesmo que saiba resolver!</p>
<p>Boa avaliação!</p>
<p>1) Considere o seguinte trecho de código, parte de um sistema de entrega de alimentos por aplicativo:</p>
<pre>
i = input('Digite o número da casa: ')
</pre>
<p>Caso o usuário digite na caixa de texto de entrada o valor 142, qual será o tipo de dado da variável i?</p>
<pre>
  a) int
</pre>
<pre>
  b) str
</pre>
<pre>
  c) float
</pre>
<pre>
  d) bool
</pre>
<pre>
  e) list
</pre>
<p>2) Você precisa implementar um código em Python que calcula o preço total de uma compra, dado o preço unitário de um dado produto (armazenado na variável preco) e a quantidade de unidades compradas (armazenado na variável quantidade). Assuma que temos apenas um único produto comprado. Assinale a alternativa que corretamente implementa este procedimento:</p>
<pre>
a) preco_total = quantidade *= preco
</pre>
<pre>
b) preco_total = quantidade * preco
</pre>
<pre>
c) preco_total = quantidade += preco
</pre>
<pre>
d) preco_total = quantidade / preco
</pre>
<pre>
e) nda
</pre>
<p>3) Na variável restaurantes_ano temos uma lista de listas, em que cada elemento é uma lista de dois elementos, em que o primeiro é o nome de um restaurante cadastrado na plataforma de delivery, e o segundo é o ano em que o cadastro foi realizado. Você deseja criar uma nova lista de listas, em que cada elemento é uma lista de dois elementos, sendo o primeiro o nome do restaurante (como é na lista original), e o segundo é o número de anos em que o restaurante está cadastrado na plataforma (considere que o ano atual é 2023). Qual das alternativas a seguir corretamente completa o trecho de código iniciado abaixo, para corretamente construir a lista desejada?</p>
<pre>
restaurantes_idade = []

for lista in restaurantes_ano:
#o código da alternativa correta deve vir aqui

</pre>
<p>Ao revisar este código, qual das alternativas a seguir produz o mesmo resultado?</p>
<pre>
a) restaurantes_idade.append([lista[0], lista[1] - 2023])
</pre>
<pre>
b) restaurantes_idade.append([lista[1], 2023 - lista[0]])
</pre>
<pre>
c) restaurantes_idade.append([lista[1], lista[0] - 2023])
</pre>
<pre>
d) restaurantes_idade.append([lista, 2023 - lista])
</pre>
<pre>
e) restaurantes_idade.append([lista[0], 2023 - lista[1]])
</pre>
<p>4) Queremos criar uma lista para armazenar os preços dos produtos de determinado restaurante. Em qual das opções abaixo a variável precos_produtos não é uma lista?</p>
<pre>
a) precos_produtos = []
</pre>
<pre>
b) precos_produtos = list("1 2 3 4")
</pre>
<pre>
c) precos_produtos = (1, 1.5, 3.8)
</pre>
<pre>
d) precos_produtos = [1, 2, 3, 4]
</pre>
<pre>
e) precos_produtos = list()
</pre>
<p>5) Quando determinado entregador de um serviço de delivery atinge 100 entregas feitas, ele recebe uma gratificação, indicando que ele subiu de nível na plataforma de entregas. Enquanto este número não é alcançado, uma mensagem indicando quantas entregas ainda faltam é exibida na tela. Para implementar esta lógica, você começou criando o seguinte código:</p>
<pre>
num_entregas = 0
nivel = 0

while (num_entregas < 100):

    print(f"Faltam {100 - num_entregas} entregas para você mudar de nível!")

    # código da alternativa correta aqui

print("\nVocê atingiu o próximo nível!")
nivel = 1
</pre>
<p>Assinale a alternativa que corretamente implementa a lógica desejada, substituindo o comentário no código acima:</p>
<pre>
a) num_entregas += 1
</pre>
<pre>
b) num_entregas = 100 - num_entregas
</pre>
<pre>
c) num_entregas -= 1
</pre>
<pre>
d) num_entregas = 100 + num_entregas
</pre>
<pre>
e) num_entregas += 100
</pre>
<p>6) Em um aplicativo de delivery, é muito importante que as entregas sejam feitas no menor tempo possível, para maior satisfação dos clientes. Pensando nisso, uma importante componente do sistema informacional de entregas deve calcular qual é o tempo estimado de entrega de um pedido, com base na distância entre o restaurante e o destino, e assumindo que o entregador viaja a uma velocidade constante de 50 km/h. Faça um código em Python que calcule o tempo de entrega em minutos, completando o template de código a seguir, na qual a distância em km deve ser informada pelo usuário:</p>
<pre>
velocidade = 50

distancia = # código para receber como input do usuário a distância em km

tempo = # código que implementa a lógica do cálculo do tempo, em minutos

print(f"\nO tempo estimado de entrega é de {tempo} minutos!")
</pre>
<p>Dica: o tempo necessário para percorrer uma dada distância à velocidade constante é dado pelo quociente entre a distância e a velocidade. Atenção às unidades!</p>
<p>7) Em um aplicativo de delivery, é importante que tenhamos um registro de todos os clientes que fazem pedidos em determinado restaurante, para que seja possível enviarmos cupons de desconto para os clientes que mais pedem, por exemplo.</p>
<p>Para começar a prototipar esta funcionalidade no aplicativo, você deve criar um programa em Python que leia diversos números inteiros e insira todos em uma lista (esses números são os identificadores dos clientes). A cada solicitação de número, pergunte ao usuário se deseja inserir outro número: tendo como resposta 'S' para inserir mais um; ou 'N' caso queira terminar. É possível que o mesmo número seja digitado mais de uma vez (isso pode representar o mesmo cliente fazendo mais de um pedido). Após construir a lista, mostre:</p>
<ul>
<li>todos os números digitados na ordem em que foram inseridos</li>
<li>todos os números digitados em ordem crescente</li>
<li>a média destes valores</li>
<li>apenas os números pares</li>
<li>apenas os números ímpares</li>
<li>apenas os números repetidos</li>
</ul>
<p>8) Para que a entrega de alimentos seja feita com qualidade por um serviço de delivery, é muito importante que as caixas de transporte utilizadas por entregadores tenham um revestimento térmico interno, para manter a temperatura dos alimentos. Muitos destes revestimentos são importados de países que utilizam diferentes escalas de temperatura, de modo que as especificações quanto às temperaturas de operação podem gerar confusão.</p>
<p>Pensando nisso, escreva um código em Python que recebe um número (que possa ter casas decimais) e a escala de temperatura em que este valor se encontra e para qual ele deseja converter (Celsius, Kelvin ou Fahrenheit). Tanto na escala em que se encontra quanto para a que deseja converter, utilize as letras iniciais como entrada: Celsius - 'C', Kelvin - 'K' ou Fahrenheit - 'F'.</p>
<p>Seu código deve solicitar ao usuário as informações necessárias para realizar a conversão de temperatura (temperatura, escala_original, escala_convertida), de acordo com o template abaixo.</p>

<pre>
temperatura = #código para receber o valor numérico da temperatura desejada

escala_original = #código para receber a escala original da temperatura informada

escala_convertida = #código para receber a escala para a qual deseja-se converter a temperatura

#implemente abaixo toda a lógica de conversão de temperaturas, bem como as validações necessárias
</pre>

<p>Importante: o programa deve trabalhar apenas com as 3 escalas supracitadas! Então, não deixe de fazer as validações necessárias. Além disso, por definição, não existem temperaturas em Kelvin abaixo de zero (o valor zero pode existir), portanto verifique também esta condição para que sejam feitas conversões válidas!</p>
<p>Dica: as equações de conversão entre as escalas são as seguintes:</p>
<p>Celsius <> Fahrenheit:</p>
<pre>
C/5 = (F - 32)/9
</pre>
<p>Celsius <> Kelvin:</p>
<pre>
C = K - 273
</pre>
<p>Kelvin <> Fahrenheit:</p>
<pre>
(K - 273)/5 = (F - 32)/9
</pre>
<p>9) Um restaurante deseja saber quais são seus produtos mais vendidos em um aplicativo de delivery. Em uma lista, há registrados os nomes dos produtos, na ordem em que eles são vendidos (portanto, há elementos repetidos nesta lista). Faça um programa que exibe na tela cada um dos produtos na lista de input, e a quantidade em que eles foram vendidos (separados por um traço), de modo que teremos uma mensagem em cada linha. Os produtos devem ser exibidos em ordem alfabética.</p>
<p>Ex.: para a lista produtos = ["Hambúrguer", "Fritas", "Fritas", "Refrigerante", "Fritas", "Hambúrguer"]</p>
<p>Devemos ter as seguintes mensagens exibidas na tela:</p>
<pre>
Fritas - 3
Hambúrguer - 2
Refrigerante - 1
</pre>
<p>10) Para bem distribuir os pedidos aos entregadores disponíveis, um aplicativo de delivery usa a seguinte regra:</p>
<ul>
  <li>cada entregador deve entregar, em uma única corrida, no máximo 5 pedidos;</li>
  <li>as casas de destino que serão atribuídas a um mesmo entregador serão todas quelas que estão a um raio de no máximo 10 km do restaurante, respeitando a regra anterior.</li>
</ul>
<p>Considere que como input do problema, recebemos uma lista em que cada elemento armazena a distância (de linha reta) em km entre a casa que fez o respectivo pedido e o restaurante. Faça um código que distribua estes pedidos a um dado entregador, seguindo as regras acima, de modo que a saída deve ser uma lista que contém os índices dos elementos da lista original que farão parte da corrida do entregador - considere que os primeiros elementos da lista têm prioridade.</p>
