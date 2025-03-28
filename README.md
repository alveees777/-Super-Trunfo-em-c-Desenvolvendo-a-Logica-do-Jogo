Os arquivos estão numerados de 1 a 3, pois cada arquivo representa uma atualização subsequente do código. Sendo os nivéis considerados novato, aventureiro e mestre.


Sobre o Jogo
Super Trunfo de Cidades é um jogo de cartas digital onde você cadastra duas cidades e compara seus atributos para determinar qual é a "vencedora" 

-Como Jogar

      Pré-requisitos
      IDE
      Compilador GCC instalado
      Terminal/linha de comando


      Baixe o arquivo e execute em uma IDE com as extensoões nescessarias da linguagem C ou pelo terminal de comando com o GCC instalado.
       
Cadastro das Cartas:

    Você cadastrará duas cidades com seus atributos. 
    Cada cidade pertence a um estado brasileiro.
    O código da cidade deve seguir o padrão (primeira letra do estado + 01-04)
    

Atributos das Cartas:

    População
    Área territorial (km²)
    PIB
    Pontos turísticos
    Densidade populacional (calculada automaticamente)
    PIB per capita (calculado automaticamente)
    Super Poder (pontuação composta calculada automaticamente)

Modo de Jogo:

    Após cadastrar as cidades, escolha um atributo para comparar. 
    A cidade com melhor desempenho no atributo escolhido vence. 
    Para densidade, vence a cidade com menor valor. 
    Para Super Poder, vence a cidade com maior pontuação composta

              === MENU ===
      1-Populacao       2-Area          3-PIB
      4-Pontos Turisticos 5-Densidade   6-PIB per capita  
      7-Super Poder     0-Sair


Exemplo de Partida


    CADASTRO DA PRIMEIRA CARTA
    Estado: São Paulo
    Codigo (S01-S04): S01
    Cidade: São Paulo
    Populacao: 12325232
    Area (km²): 1521.11
    PIB: 500000000000
    Pontos Turisticos: 15

    CADASTRO DA SEGUNDA CARTA
    Estado: Rio de Janeiro
    Codigo (R01-R04): R01
    Cidade: Rio de Janeiro
    Populacao: 6748000
    Area (km²): 1200.25
    PIB: 350000000000
    Pontos Turisticos: 20

          === MENU ===
    1-Populacao 2-Area 3-PIB
    4-Pontos Turisticos 5-Densidade
    6-PIB per capita 7-Super Poder
    0-Sair
      
    Opcao: 1

    POPULACAO:
    São Paulo: 12325232
    Rio de Janeiro: 6748000
    Vencedor: São Paulo

    Continuar? (s/n): s

