
<img src="img/ifsc-logo.png"
     width="30%"
     style="padding: 10px">

# Regicide Game

# StartUp
* O game Regicide é um jogo coparticipativo, sendo jogado solo ou em grupos de até 4 pessoas;
     * Para uma quantidade de Players finita, é definido um número de cartas para cada player iniciar;
 
          | Players | Numbers of Card | 
          |----------|----------|
          | 1 | 8 | 
          | 2 | 7 | 
          | 3 | 6 | 
          | 4 | 5 | 

* O Regicide pode ser jogado com um baralho tradicional de 4 naipes de 12 cartas de cada Naipe (A,2,3,4,5,6,7,8,9,J,Q,K) ou utilizar o baralho específico do Regicide;
* Cada participante, recebes cartas sortidas de 2 a 9 como suas cartas guerreiras;
* O Jogo consiste em elimiar todas as cartas J, Q, K dos 4 naipes do monte (totalizando 16 cartas), essas cartas são consideras os monstros do Game;

# Como funciona - Cartas Guerreiras (2 a 9)
* Cada carta Guerreira tem associado um valor de ataque e vida igual ao valor da carta;
     * *A*:
          * Vida: 1Pt, Poder de ataque: 1Pt
     * <...>
     * *9*:
          * Vida: 9Pt, Poder de ataque: 9Pt
        
* O Naipe associado a carta, determina um poder extra que a carta tem:
     * Ouros:
          * Permite que se compre um número de cartas igual ao valor da carta, sendo compradas de um por uma por cada player presente em sequência (P1 Compra, P2 Compra ... até atingir o valor nominal).
               * 9 de Ouros: Além de sofrer dano e efetuar ataques, pode comprar 9 cartas do deck, dividindo entre os participantes;             
     * Espadas:
          * Reduz o dano de ataque de um monstro em um valor igual ao da carta.
               *  9 de Espadas: Se receber dano 10, ele consegue abstrair 9 unidades desse dano, aplicando efetivamente 1 de dano ao jogador.
     * Copas:
          * Move cartas do deck de descartes para a taverna de compra.
               *  9 de Copas: Após aplicar o ataque de 9 a um inimigo, move 9 cartas do deck de descartes para a taverna de forma aleatória.               
     * Paus:
          * Aumenta o dano de ataque em duas vezes o valor nominal da carta. 
               *  9 de Paus: Tem dano de ataque final de 9 + 9 = 18
            

# Como funciona - Cartas Nobreza (J, Q, K)
* São as cartas que devem ser derrotadas para ganhar o jogo. Cada carta equivale a um inimigo, cada inimigo possui um valor de dano, defesa e sua imunidade:
     * Valete:
          * Defesa: 20
		  * Ataque: 10        
     * Dama:
          * Defesa: 30
		  * Ataque: 15
     * Rei:
          * Defesa: 40
		  * Ataque: 20
		 
* Inimigos possuem imunidade aos efeitos de seu naipe:
	* Valete de paus é imune ao efeito de paus, logo se um jogador jogar um 9 de paus, o dano que será causado ao inimigo será de apenas 9. O mesmo efeito se aplica às cartas animais. A carta de coringa não é afetada pela imunidade de ouros. 
 
# Como funciona - Cartas Animais (A)
* Cartas animais (companions) são cartas que podem ser jogadas juntas de qualquer outra carta. Possuem valor de 1 e seu dano é somado a qualquer outra carta que você ter jogado junto. Se possuirem naipes diferentes, ambos os efeitos são aplicados:
	* Se for jogado um 8 de diamantes e um ás (companion) de ouros, o jogador vai dar dano de 9 ao inimigo, vai poder previnir 9 de dano e vai poder comprar 9 cartas.
	
# Como funciona - Cartas Coringas (JOKER)
* Cartas coringa estão disponíveis somente no modo solo, o qual o jogador pode ativar seu efeito a qualquer momento. Quando ativado, a mão atual é descarta e em seguida o jogador deve comprar 9 cartas. O tipo de vitória muda conforme o número de coringas usados:
	* Nenhum coringa utilizado: Vitória de Ouro.
	* Um coringa utilizado: Vitória de Prata.
	* Dois coringas utilizados: Vitória de Bronze.
	
# Etapas de uma Rodada 
* O jogo possui 4 etapas que se repetem sequencialmente:
	* Etapa 1: Jogar uma carta ou passar a vez:
		* O jogador deve escolher uma carta da sua mão para ser jogado no campo. O jogador possui a opção de passar a vez e não jogar carta alguma.
	* Etapa 2: Ativar o poder da carta:
		* O poder das cartas é ativado e seu efeito é resolvido. Se o jogadaor 1 jogar um 9 de paus, 18 é o dano que deve ser aplicado na próxima etapa.
	* Etapa 3: Dar dano ao inimigo e verificar se ele foi derrotado:
		* O dano da etapa 2 é aplicado ao inimigo é verificado se o inimigo foi derrotado. Se inimigo for derrotada a próxima rodada começa na etapa 1 iniciando no inimigo, se não foi derrotado, o jogo passa para a etapa 4.
	* Etapa 4: Sofrer dano do inimigo:
		* O jogador que sofrer dano de um inimigo deve descartar cartas de modo que a soma dos valores das cartas seja igual ao dano que ele sofreu do inimigo. Se um jogador sofrer 13 de dano, uma possível combinação para descartar de cartas é um 9 de qualquer naipe e um 4 de qualquer naipe. Todos os jogadors perdem se qualquer jogador não puder descartar cartas suficientes.

* Após o primeiro jogador realizar as quatro etapas, começa a etapa 1 do segundo jogador. 

# Comunicação entre Jogadores
* Jogadores não podem comunicar a outros jogadores qualquer informação sobre o conteúdo de sua mão. Somente informações disponíveis a todos como por exemplo: vida do inimigo, quantidade de cartas compradas, quantidade de cartas na mão ou quantidade de cartas na taverna. Logo após um Coringa ser jogado, todo tipo de comunicação é permitida até que se inicie a próxima etapa do jogador atual.

# Fim de Jogo
* O jogo se encerra quando todos os inimigos forem derrotados ou quando um jogador não consegue descartar a quantidade de cartas necessárias após sofrer dano. Se um jogador perder, todos perdem.

# Regras Adicionais:
* Comprando um inimigo derrotado:
	* Se dano exato for causado a um inimigo, ao invés desta carta ser removida do jogo, ela é colocada no topo da taverna. Se um inimigo com 9 de vida sofrer 9 de dano, ele é colocado no topo da taverna. A rodada do próximo jogado começa normalmente.
* Efeito do Ouros:
	* Cartas compradas ao resolver o efeito de ouros são realizadas a partir do topo da taverna. Um a um, cada jogador compra uma carta começando pelo jogador que jogo o ouros e em sentido horário, compram até satisfazerem o valor da carta jogado ou atingirem o limite da mão.
* Efeito do Copas:
	* As cartas da pilha de descarte são embaralhadas e então o número de cartas que satisfaz o valor do copas jogado é colocado no fundo da taverna. Um 9 de copas embaralha toda a pilha de descartes e então 9 cartas aleatórias são colocados no fundo da taverna.

https://www.regicidegame.com/

> Repositório destinado para o desenvolvimento do projeto final da discipliana PRG203405 - Programação orienta a objeto. 
> 
> Alunos: 
> Vilian Nicoladeli Esmeraldino
> Rafael Aquino de Meireles
> Professor: Hugo Marcondes


<p align=center><strong>SUMÁRIO</strong></p>

[**1. ANÁLISE ORIENTADA A OBJETO**](./analise.md)<br>
[**2. PROJETO ORIENTADO A OBJETO**](./projeto.md)<br>
[**3. IMPLEMENTAÇÃO (C++)**](./implementacao.md)<br>
[**4. TESTES**](./testes.md)<br>
