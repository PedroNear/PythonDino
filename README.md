# Fase 1: Análise

 Problema selecionado e definido claramente: O projeto visa criar um jogo educativo baseado na história de Guido van Rossum, criador da linguagem Python. O jogo segue a mecânica do famoso "T-Rex" do Google, onde o jogador deve pular obstáculos enquanto acumula pontos. Além disso, há um modo multijogador para disputas ou estudo em grupo.
 Compreensão aprofundada da natureza e desafios do problema: O principal desafio do projeto é integrar a mecânica de jogo simples e divertida com a transmissão de conteúdo educativo, mantendo a história e os obstáculos representativos da vida e contribuições de Guido van Rossum e do Python.
 Modelo matemático ou teórico desenvolvido para representar o problema: O modelo matemático inclui a definição da física do jogo (movimento, colisões, pontuação), além de uma estrutura para a integração de eventos históricos e obstáculos, com variação conforme o nível de dificuldade.

# Fase 2: Planejamento

 # Objetivos do algoritmo definidos com clareza:

 O jogo deve permitir ao jogador pular obstáculos enquanto aprende sobre Guido van Rossum e a criação do Python. O objetivo é atingir uma pontuação alta, com níveis de dificuldade variados e a opção de jogar sozinho ou com um amigo.

 # Métricas para avaliação de eficiência do algoritmo estabelecidas:

 A eficiência será avaliada com base na fluidez do jogo (taxa de quadros por segundo), tempos de resposta para ações do jogador e o uso de recursos do sistema (CPU e memória), especialmente em modos multiplayer.

 Estratégia geral de resolução do problema proposta:
 Utilização de uma engine como Pygame ou Unity para implementar a física do jogo, os obstáculos, e a história. O design do código foi baseado em modularidade, permitindo a criação de níveis e obstáculos diferentes conforme a história de Guido van Rossum é explorada.

 # Subproblemas identificados e divididos, se aplicável:

-Criação de obstáculos e mecanismos de colisão.
-Implementação da física de movimento para o pulo.
-Integração dos eventos históricos e exibição de informações sobre Guido.
-Implementação dos modos de jogo (sozinho e multiplayer).
-Desenvolvimento da interface gráfica (menus e navegação).
 
Estrutura geral do algoritmo esboçada: O algoritmo principal envolve um loop que verifica o movimento do personagem, colisões com obstáculos, atualiza a pontuação e integra a narrativa. O fluxo do jogo inclui a tela inicial, escolha de modos, a mecânica de pulo e mudança de níveis conforme a pontuação.

 Casos limite ou situações especiais identificados: Testes para garantir que o jogo funcione corretamente em dispositivos de diferentes capacidades, além de garantir que o jogo seja justo mesmo em modos multiplayer, com a sincronização das pontuações.

 Análise teórica realizada para verificar a correção do algoritmo: A análise teórica focou na lógica da física do jogo, o algoritmo de geração de obstáculos, a sincronização das interações no modo multiplayer, e a forma como a narrativa histórica é introduzida sem interromper a fluidez do jogo.

# Fase 3: Desenho

 Análise de complexidade realizada para avaliar a eficiência teórica do algoritmo: A análise envolveu avaliar a complexidade do algoritmo de movimento e colisões, considerando que o jogo deve ser executado com eficiência em tempo real sem comprometer o desempenho. A complexidade de tempo foi considerada na geração de obstáculos aleatórios e na atualização das pontuações.

 Pontos críticos do algoritmo identificados para otimização, se necessário: A otimização se concentrou na renderização de obstáculos e na física de colisões, garantindo que o jogo mantivesse um bom desempenho mesmo com a presença de múltiplos obstáculos e jogadores em modo local multiplayer.

# Fase 4: Programação e Teste

 Algoritmo traduzido com precisão em código de programação: O algoritmo foi implementado utilizando Python e Pygame, com a tradução fiel dos conceitos de física do jogo, pontuação e narrativa histórica.
 Código de programação escrito de forma clara e organizada: O código foi estruturado em módulos, com funções separadas para a física do jogo, gerenciamento da pontuação, exibição da história e implementação do multiplayer. Comentários e documentação foram incluídos para clareza.

 Testes rigorosos realizados em uma variedade de casos de teste: Foram realizados testes para verificar a estabilidade do jogo, incluindo testes de colisões, pulo, modos de jogo (sozinho e multiplayer) e desempenho em diferentes dispositivos.

 Casos limite e situações especiais testados: Foram testados cenários como falhas contínuas no pulo, variações na velocidade do jogo conforme o nível, e como o sistema se comporta com múltiplos jogadores.

 Erros e problemas durante o teste de programa identificados e corrigidos: Todos os bugs relacionados a falhas na detecção de colisões, dificuldades no modo multiplayer e problemas com a sincronização das pontuações foram corrigidos.

Documentação e Avaliação do Projeto

 Documentação completa, incluindo especificação do algoritmo e análise de complexidade: A documentação final inclui uma descrição detalhada do algoritmo, a análise de complexidade (tempo e espaço), a descrição dos modos de jogo e dos obstáculos, e a forma como a narrativa de Guido van Rossum foi integrada.

 Documentação revisada para clareza e rigor técnico: A documentação foi revisada para garantir que todos os aspectos técnicos do jogo fossem explicados de forma clara e acessível, com ênfase na implementação dos algoritmos principais e nas decisões de design.

 Avaliação da eficácia do algoritmo em termos de tempo de execução, uso de recursos e precisão na resolução do problema: A eficácia do algoritmo foi avaliada positivamente, com o jogo apresentando bom desempenho em diferentes plataformas e oferecendo uma experiência fluida e educativa. A pontuação e o movimento dos personagens estavam corretos.

 Avaliação da colaboração da equipe e cumprimento dos prazos: A equipe trabalhou de forma colaborativa e eficiente, cumprindo os prazos estipulados e integrando as diferentes partes do jogo conforme planejado.
Apresentação e Conclusão do Projeto

 Apresentação do projeto preparada com informações claras e objetivas: A apresentação incluiu uma explicação da mecânica do jogo, a importância da narrativa histórica sobre Guido van Rossum, e como os diferentes modos de jogo e personagens foram integrados.

 Conclusões do projeto destacando os resultados e aprendizados: O projeto foi concluído com sucesso, atingindo os objetivos de criar um jogo educativo e divertido. Aprendemos a equilibrar a jogabilidade com o conteúdo informativo, proporcionando uma experiência envolvente.

 Discussão sobre o projeto e respostas a perguntas da audiência: A apresentação final incluiu uma sessão de perguntas e respostas, onde discutimos as escolhas de design, os desafios enfrentados e as possíveis melhorias para versões futuras do jogo.





 # Pré-requisitos 
 * **Python** Recomenda-se versão 3.13
 * **pygame** Biblioteca para criação de jogos em Python. Use 'pip install pygame' 
