# miniguia-estudos-notebooklm
Um LLM que analisa armas de "Call of Duty" (nesse caso o foco estava apenas armas e em "Black Ops 7", porém é possível avaliar as de outros jogos), que analisa o desempenho e o funcionamento das armas do jogo.

Meu objetivo é criar um assistente que possa te responder qual tipo de arma seria o ideal para o estilo de jogo que o usuário deseja.

Fontes:
https://codmunity.gg/pt/ttk/bo7
https://codmunity.gg/pt/bo7
https://callofduty.fandom.com/wiki/Category:Call_of_Duty:_Black_Ops_7_Attachments
https://www.1v1me.com/blog/black-ops-7-weapon-build-codes-explained
https://timesaver.gg/blog/bo7-best-attachments

# Resumo
Como o projeto limita a poucas fontes, a resposta deixa de dar detalhes muitos específicos.
O Black Ops 7 introduziu mecânicas que aprofundam a personalização e a eficiência competitiva, centradas em três pilares principais:
1. Sistema de Prestígio de Arma e Acessórios Exclusivos
Diferente de títulos anteriores, o Prestígio de Arma agora oferece vantagens tangíveis de jogabilidade em vez de apenas cosméticos
. Ao atingir o nível máximo de uma arma, o jogador pode ativar o Prestígio, ganhando acesso aos Acessórios de Prestígio (Prestige Attachments) no Nível 1
. Esses acessórios alteram fundamentalmente o comportamento da arma, como o "Enhanced Cycle System" do AK-27, que elimina todo o recuo horizontal, ou o "Vital Ace Barrel" do Jäger 45, que permite eliminações com um único tiro na cabeça
.
2. Sistema de Códigos de Build de Arma
Para simplificar o compartilhamento de classes, o jogo utiliza Códigos de Build de Arma, sequências alfanuméricas que representam um setup completo de acessórios
. Os jogadores podem:
Copiar diretamente da Killcam de um oponente
.
Visualizar seu próprio código através de uma etiqueta azul no menu do Armeiro
.
Importar classes sem navegar pelo Armeiro, pressionando o analógico direito (R3) no menu de armamentos
.
3. O Meta e Performance Competitiva
O cenário competitivo atual (Temporada 5) é dominado por armas com baixo TTK (Tempo para Matar) e alta precisão
. A Mammoth (MLS) lidera a taxa de escolha com 16,5% e possui o TTK mais rápido a curta distância (160ms)
. Outras armas de destaque incluem o fuzil de assalto FG42 e a SMG Sturmwolf 45, ambas classificadas como "Absolute Meta" devido à sua versatilidade e facilidade de uso
.
4. Otimização de Progressão (XP)
Para desbloquear acessórios rapidamente, os métodos mais eficazes incluem jogar no modo Hardcore, que facilita medalhas de "Um Tiro, Uma Baixa", e o modo Zombies para os níveis iniciais da arma
. O uso de Scorestreaks não letais (como UAV e Radar) e Granadas de Distração (Decoys) também acelera o ganho de experiência através de bônus de assistência e distração

# Glossário de Conceitos Principais
Acessório de Prestígio (Prestige Attachment): Modificações únicas desbloqueadas após atingir o nível máximo da arma; oferecem bônus de status superiores aos acessórios padrão
.
Código de Build de Arma (Weapon Build Code): Sequência curta de letras e números que carrega instantaneamente todos os acessórios de uma arma específica
.
TTK (Time-to-Kill): "Tempo para Matar"; medida em milissegundos que indica quão rápido uma arma consegue eliminar um oponente com tiros no peito
.
Meta: Abreviação para as táticas ou equipamentos mais eficazes disponíveis no jogo no momento atual (ex: armas com maior taxa de vitória e escolha)
.
Armeiro (Gunsmith): Interface de personalização onde os jogadores equipam acessórios, conferem códigos de build e gerenciam o progresso de prestígio
.
Recuo Horizontal (Horizontal Sway/Recoil): O movimento lateral da arma ao disparar; acessórios como o Ironhold Angled Grip são projetados especificamente para mitigar esse efeito
.
Velocidade de Projétil (Bullet Velocity): A rapidez com que a bala viaja; essencial para combates a longa distância para evitar que o jogador precise compensar o deslocamento do alvo
.
Mobilidade de Disparo (Strafe Speed): A velocidade com que o jogador se move lateralmente enquanto mira; melhorada por acessórios como a coronha Wander-3V


# Exemplos de prompts:
( "=>", seria a resposta do LLM)
.Liste todas as armas do jogo => Nomeia as armas e as separa em classes
.Como copiar uma classe com acessórios => Ensina sobre a função copiar código, para poder importar uma arma que alguém montou
.Crie uma classe de smg com pouco recuo => Recomenda algumas smgs, passando os acessórios necessários para que a arma obtenha pouco recuo, passando ate o código para copiar a classe dentro do jogo de maneira mais rápida
