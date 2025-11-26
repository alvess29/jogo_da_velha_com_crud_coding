------Estrutura do Banco de Dados------

O "banco de dados" é um arquivo JSON chamado partidas.json, com a seguinte estrutura para cada partida:

"id": 1,                  
"nome": "Partida Exemplo",                
"tabuleiro": ["X", "O", "X", " ", "O", " ", " ", " ", "X"],              
"jogador_atual": "O",              
"finalizada": true,             
"vencedor": "X"               

id: Identificador único da partida.                   
nome: Nome dado à partida pelo usuário.                    
tabuleiro: Lista com 9 posições representando o estado atual do tabuleiro.             
jogador_atual: Indica qual jogador fará a próxima jogada ("X" ou "O").               
finalizada: Booleano indicando se a partida terminou.              
vencedor: Indica o vencedor ("X", "O" ou "Empate").              

