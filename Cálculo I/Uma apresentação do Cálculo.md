# O que é Cálculo ?

No nosso cotidiano, tudo está em constante mudança: temperaturas variam, populações crescem, objetos se movem. Essas transformações podem ser descritas matematicamente por meio de **funções**, que associam grandezas a valores numéricos.

O **Cálculo** é o ramo da matemática que busca compreender e mensurar tanto as **variações instantâneas** dessas funções quanto o **acúmulo contínuo** dessas variações.

Enquanto a matemática elementar trabalha, em grande parte, com equações discretas e situações estáticas, o cálculo se dedica a questões mais profundas:

- O que acontece quando analisamos variações **infinitamente pequenas**?
- Como o acúmulo de infinitésimas parcelas pode resultar em um valor finito e significativo?
- De que maneira conseguimos descrever, com precisão, processos contínuos que nunca param de mudar?

Em essência, o cálculo é a **teoria do infinitesimal**: ele estuda o comportamento das funções em situações de mudança contínua. Dessa forma, ele nos permite traduzir o “quase nada” — variações imperceptíveis isoladamente — em resultados concretos quando considerados em conjunto.

> “Como vários nadas podem formar algo ?” — Autor desconhecido

# Uma breve história do Cálculo
## O problema da área

O cálculo, diferentemente da ordem que se ensina, começou a ser descoberto/desenvolvido pelo cálculo integral, pois segundo registros os primeiros problemas envolviam o cálculo de áreas, volumes e comprimento de arcos.

Os gregos sabiam calcular a área de qualquer polígono, porém era difícil calcular área de objetos que tinham curvas, porém eles tinham um método que é conhecido como “método da exaustão”.

Um exemplo clássico, citado por **James Stewart**, é o seguinte:
![[aprox_area.png]]O método consiste em aproximar uma figura curva (como um círculo) por **polígonos inscritos ou circunscritos**. À medida que o número de lados $n$ do polígono aumenta, a área do polígono se aproxima cada vez mais da área do círculo. Em termos matemáticos:

$$ \lim_{n \to \infty} A_n = \text{Área do círculo} $$

Sendo assim, dado um polígono qualquer de **$n$** lados, a medida que $n$ cresce, a área sobre o círculo se aproxima cada vez mais. Sendo assim podemos considerar que à medida que $n$ **tende a crescer em direção ao infinito** o erro do cálculo da área **tende a diminuir para zero** se igualando com a área do círculo.

Apesar desse método conhecido pelos gregos, o estudo do problema da área datam já de muitos anos, segundo fontes, o primeiro registro de uma estimativa, datado aproximadamente em 1890 a.C., é conhecido como **Papiro Matématico de Golenischev**, em homenagem ao primeiro proprietário não-egípcio, o egiptólogo **Vladimir Semenovich Golenischev**.
![[papiro_de_moscou.jpg]]
O problema tratava-se de calcular a área da superfície de um cesto que utilizava de uma técnica semelhante ao de uma integração, além desse problema no papiro se encontram outros 25 problemas matemáticos, onde entre um deles envolve o cálculo de um volume de tronco de pirâmide. Hoje em dia esse registro se encontra em exposição no **Museu Estatal Pushkin de Belas Artes**, em Moscou.

Ao longo dos anos houveram inúmeras aproximações e estudos para resolver esses problemas, alguns até mais modernos que são datados um pouco antes da invenção concreta do cálculo.

**Jonhann Kepler (1571-1630)**, utilizou do método da exaustão para a sua segunda lei do movimento planetário, e também para calcular o volume de um barril de vinho. A história do barril é dita até mais interessante que a da sua segunda lei, a história diz que Kepler havia comprado um barril de vinho para comemorar o seu casamento e o mesmo acabou se irritando com a forma que o comerciante media o volume do barril.

Kepler estudou afundo sobre o assunto, ao ponto de escrever um livro sobre o cálculo de volumes e áreas com esse tipo de problema, o livro publicado em 1615 se chama **Nova Stereometria doliorum vinariorum** ou **Nova geometria sólida de barris de vinho**.
![[nova_stereometria.jpg]]
O livro possui uma versão digitalizada e está disponível gratuitamente no [Internet Archive](https://archive.org/details/den-kbd-pil-21009000066F-001/mode/2up).

> _"Ele pensou no volume do barril, à maneira de muitos outros corpos, como sendo composto de numerosas camadas e, fazendo variá-las adequadamente, determinou a soma dos volumes das camadas, cada uma das quais sendo considerada um cilindro."_ — Felix Klein

## O problema da tangente

A formalização da derivação surgiu com mais clareza apenas em anos mais recentes, porém a sua ideia já datava desde a Grécia antiga, o problema era relativamente simples de se imaginar, mas não tão simples de se resolver, calcular a reta tangente à um curva qualquer, essa ideia simples foi poderosa o suficiente para calcular o máximo e mínimo de funções utilizadas pelos gregos.

Novamente Kepler aparece na história, dessa vez o mesmo notou que os incrementos de  uma função tornam-se **infinitesimais** quando o ponto se aproxima de um ponto de máximo ou mínimo, ou seja, a medida que uma função vai se aproximando de seu valor máximo, o seu valor é incrementado com uma **taxa de variação que tende a diminuir cada vez mais**, ficando tão pequenas que **se aproximam de zero**.
![[ilustracao_derivada.png]]
## A ponte entre os mundos