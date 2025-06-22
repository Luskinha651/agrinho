# agrinho
Agrinho é o maior programa de responsabilidade social do Sistema FAEP, resultado da parceria entre o SENAR-PR, FAEP, o governo do Estado do Paraná, mediante as Secretarias de Estado da Educação e do Esporte, da Agricultura e do Abastecimento, da Justiça, Família e Trabalho e do Desenvolvimento Sustentável e do Turismo, bem como com a colaboração das Prefeituras municipais e diversas empresas e instituições públicas e privadas.

O Programa completa 26 anos de trabalhos no Paraná. Concebido em 1995, foi à campo em 1996, levando às escolas da rede pública de ensino uma proposta pedagógica baseada em visão complexa, na inter e transdisciplinaridade e na pedagogia da pesquisa. Anualmente, o programa envolve a participação de aproximadamente 800 mil crianças e mais de 50 mil professores da educação infantil, do ensino fundamental e da educação especial, estando presente em todos os municípios do Estado.

Conceito e Narrativa
O jogo conta a história de Morgana, uma jovem do campo que viaja para a cidade. O tema central, evidente nos diálogos e objetivos, é a conexão entre o mundo rural e o urbano. Morgana não está apenas explorando, mas também aprendendo, superando desafios e provando que esses dois mundos podem coexistir e se complementar. A narrativa progride através de missões, diálogos com personagens e cutscenes que marcam os momentos-chave da jornada.

Arquitetura Principal: A Máquina de Estados
O coração do seu jogo é uma máquina de estados, controlada pela variável global estadoJogo. Essa abordagem é excelente para organizar um projeto com múltiplas telas e funcionalidades. O loop principal (draw()) usa uma estrutura switch para determinar o que deve ser desenhado e atualizado a cada momento, seja o menu, a cena rural, a cidade, um minigame ou uma tela de créditos.

Estados principais:
menu, creditos, guia: Telas estáticas com botões para navegação.
jogando: A cena inicial no campo, onde a aventura começa.
cidade e cidade_2: As cenas urbanas, com novos NPCs e desafios.
missoes: Uma sobreposição que exibe o quadro de missões.
cutscene_final, cutscene_retorno_campo: Cenas cinematográficas não interativas que movem a história.
fim_de_jogo: A tela final que conclui a jornada de Morgana.

#Agrinho2025
