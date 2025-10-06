# Ondas Eletromagnéticas

As ondas eletromagnéticas são utilizadas em muitas aplicações como forma de transportar sinais, como áudio, vídeo ou dados por meio de cabos de fibra óptica, porém o que veremos aqui serão aquelas que se propagam no interior dos materiais, alguns exemplos desses comportamentos são as vibrações dos átomos da rede cristalina e o movimento dos elétrons nos sólidos.

Obviamente há vários outros tipo de fenômenos físicos que se propagam por meio das ondas eletromagnéticas que logo mais serão abordados mais a frente.

---
## A quantificação dos fótons

No fim do século XX, os cientistas perceberam que as ondas eletromagnéticas se comportavam de forma semelhante a partículas. **Heinrich Hertz (1857-1894)**, confirmou a existência de ondas eletromagnéticas e a teoria de Maxwell. Numa de suas experiências, foi observado que uma descarga elétrica entre dois eletrodos ocorria mais facilmente quando uma luz ultravioleta era incidida sobre os eletrodos.

**Philipp Lenard (1862-1947)**, foi quem percebeu a luz ultravioleta facilitava a emissão de elétrons, que logo mais tarde seria conhecido como **efeito fotoelétrico**. A física clássica não era capaz de explicar o efeito fotoelétrico, dessa forma **Albert Eistein (1879–1955)**, utilizando das ideias de **Max Planck (1858-1947)** sobre quantização conseguiu desvendar o mistério.

Anos mais tardes as teorias de Eistein, que lhe renderam um prêmio nobel, foram posteriormente explicadas de forma coerente pela teoria quântica de campos. O impacto mais importante dessa descoberta é que a onda eletromagnética é **quantizada em energia**, ou seja, existe uma frequência $v$ tal que para todos os valores de energia ela só pode ser gerada como múltiplos dessa frequência a partir da fórmula $nhv$, sendo $h$ a constante de Planck ($h = 6,6262 \cdot 10^{-34}J.s$).

Para Eistein a onda viajava em pacotes chamados fótons, quando a onda possuía uma alta energia a quantidade de fótons era tão grande que não ficava tão perceptível a discretização da energia e por isso poderia ser descrito pela física clássica, onde a equação que relaciona a energia com a frequência da onda é dada por:
$$
E = h \cdot f
$$
Onde $h$ é a constante de Planck e $f$ a frequência da onda.

---
## O elétron como onda

Assim como a onda foi teorizada como partícula, o mesmo aconteceu no caminho contrário para o elétron, **Louis de Broglie (1892-1987)** foi o responsável por teorizar que o elétron também se comportava como onda, uma teoria que lhe rendeu um prêmio nobel em 1929 quando foi comprovado experimentalmente.

A energia de um elétron o mesmo para a energia de uma onda, e para calcular o seu comprimento de onda temos a seguinte relação:
$$
\lambda_{elétron}= \frac{h}{m \cdot v} \space ou \space \frac{h}{p}
$$
Onde $p$ é o momentum do elétron, ou seja, sabendo a massa e a velocidade do elétron é possível achar o comprimento de onda do elétron. Isso não é só válido para o elétron, mas para qualquer objeto feito de matéria. O motivo de não conseguimos perceber os efeitos que ocorrem em ondas eletromagnéticas normais é exemplificado a seguir.

Dado que um objeto de massa $m = 1,0kg$ e velocidade $v = 100m/s$ então o comprimento de onda correspondente é:
$$
\lambda = \frac{h}{p} = \frac{h}{m \cdot v} = \frac{6,6 \cdot 10^{-34}}{100} = 6,6 \cdot 10^{-36}m
$$
Essa escala de tamanho é tão pequena que para nós é completamente imperceptível, agora porém imagine que um elétron tem energia cinética $T = 100eV$, assim o comprimento de onda correspondente é:
$$
\lambda=\frac{h}{p}=\frac{h}{\sqrt{2mT}}\approx 1,2\cdot10^{-10}=1,2Å
$$
Ou seja, o elétron se comportar como onda possui um impacto muito grande na escala dos átomos, uma vez que $2,65Å$ é correspondente ao raio covalente de átomo de Césio $(Cs)$.

Para descrever as características de um elétron de forma quantitativa fazemos isso através de uma **função de onda** $Ψ$. Esse elétron possui momentum $p$ bem definido e por isso possui uma **incerteza** na sua posição. A fórmula utilizada para descrever o elétron é:
$$
Ψ(r,t)=A\cdot cos(k\cdot r - wt)
$$
Onde $k={2\pi}/{\lambda_{elétron}}$.

---
## Elétron Livre

Partículas cujo movimento é limitado em uma região do espaço só podem ocupar estados estacionários de energia discreta, ou seja, tem **energia quantizada**. Por isso os níveis de energia dos elétrons são 1s, 2s, 2p, 3s, etc. 

O elétron mais externo vê um potencial muito forte que o impede de se aproximar, mas ao mesmo tempo o impede de se afastar completamente, porém apesar dessa região limitada ele é livre, pois não possui forças externas atuando sobre ele, possuindo um potencial $V = 0$ dentro da sua região limitada.

Como a partícula é livre ela se move com velocidade constante e dessa forma relacionando o momentum da partícula com sua energia cinética temos:
$$
E = \frac{p^2}{2m} = \frac{\hbar^2k²}{2m}
$$
Onde $k=2\pi/\lambda$ é o vetor de onda. Dessa forma a energia fica definida como uma parábola que nem na figura abaixo.
![[eletron_livre_vetor.png]]
Porém, como dito anteriormente os elétrons estão confinados a uma região limitada do espaço o que significa que possuem um valor discreto de energia, sendo assim:
![[eletron_confinado_vetor.png]]
Ou seja, a fórmula da energia dado por um elétron confinado a uma região limitada é:
$$
E_n=\frac{\hbar²\pi²}{2mL²}\cdot n², n \in \mathbb{N}
$$
Onde $n$ é o **número quântico**, pois corresponde a **valores quantizados** de energia, já que o elétron não pode assumir um valor qualquer de energia.