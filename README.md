------*Documentação do Sistema: Jogo da Velha com CRUD*------


------*Sobre o Sistema*------

O Jogo da Velha com CRUD é uma aplicação de terminal desenvolvida em Python que permite aos usuários jogar partidas de Jogo da Velha (Tic-Tac-Toe) e gerenciar essas partidas através de operações CRUD (Criar, Listar, Atualizar/Jogar e Deletar). O sistema armazena as partidas em um arquivo JSON, possibilitando que o usuário continue jogos em andamento, visualize o histórico de partidas e exclua jogos antigos.

------*Requisitos para Rodar o Sistema*------

Python 3.x instalado na máquina.                                   
Sistema operacional: Windows, Linux ou MacOS.                                   

------*Funcionalidades*------

Criar nova partida: Inicia e salva uma nova partida de Jogo da Velha.                          
Listar partidas: Exibe todas as partidas salvas, mostrando status (em andamento/finalizada) e vencedor.                   
Jogar/Continuar partida: Permite continuar uma partida em andamento até sua finalização.                
Deletar partida: Remove uma partida específica do histórico.             
Persistência: Todas as partidas são salvas em um arquivo JSON, permitindo retomar jogos mesmo após fechar o programa.                     

------*Descrição*------

O sistema apresenta um menu interativo no terminal, onde o usuário pode escolher entre criar, listar, jogar/continuar ou deletar partidas. Cada partida possui um identificador único, nome, estado do tabuleiro, jogador atual, status de finalização e vencedor. O fluxo do jogo segue as regras tradicionais do Jogo da Velha.

------*Estrutura do Banco de Dados*------

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

------*Tecnologias Usadas*------

Linguagem: Python 3.x                
Bibliotecas:                   
json (padrão)                     
os (padrão)                       
Persistência: Arquivo JSON (partidas.json)                       
Interface: Terminal/Console                       

------*Membros da Equipe*------

Ivan Roberto Gomes Alves Dos Santos                          
Taywan Francisco De Lima Otaviano           
