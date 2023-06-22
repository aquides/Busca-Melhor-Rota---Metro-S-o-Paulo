# Busca-Melhor-Rota---Metro-S-o-Paulo

### by - Arquimedes Aquides

# Rede de transporte metropolitano SP
O projeto deste módulo consiste em modelar a rede de transporte metropolitano de SP como um grafo.

A rede a ser implementada é a que está neste arquivo. O arquivo pdf está também na pasta do projeto!

O arquivo metroetrem_sp_comlinks.csv contém grande parte (se não todas) as estações da rede. Pode ser que algumas estejam faltando -- neste caso, vocês podem adicionar as estações que estão faltando ao arquivo.

Este arquivo está sendo disponibilizado para auxiliar vocês. Mas os grupos são inteiramente livres para coletar dados de qualquer outra forma (com webscraping, por exemplo). Fiquem à vontade!

Independente da forma como os dados forem coletados, uma coisa será super necessária: estruturar os dados de maneira adequada para que eles possam servir de input para o networkx para a montagem do grafo, de maneira automática. Não é proibido, mas eu desencorajo fortemente que vocês construam o grafo manualmente com o .add_edge(). A ideia é que vocês construam o grafo usando programação, a partir da leitura e estruturação dos dados no arquivo! Vocês são livres em como farão isso, pesquisem e usem a criatividade!

## Requisitos:

Estruturação dos dados para que eles sejam usados na construção do grafo;
Um grafo completo para toda a rede de transporte metropolitano de SP;
Uma função que encontre o melhor caminho entre dois nós;
Uma função que descreva a rota do melhor caminho entre dois nós;
Uma interface de navegação para interação com usuário;
Opcionais:

Captura dos dados por webscraping ou outra ferramenta;
Atribuição de pesos às conexões do grafo (tempo entre estações, distância, etc);
Visualização do grafo.
Esclarecimento
Professor para falar a verdade eu não consegui criar um formato descente de algoritmo de recomendação de caminhos. Embora eu tenha me virado com o grafo eu copiei algumas partes do processo de recomendação

Quanto ao Dataset que o Sr. disponibilizou, buscando resolver o problema que eu tinha resolvi usar o Google Sheets para a criação de alguns tratamentos como a enumeração de cada estação, se ela possibilita baldeações e algumas limpezas como a substituição de ',' por '.'. O motivo de não fazer em python foi por questão de conveniencia nesse cenário

Por fim, os gráficos que utilizei foram basicamente uma cópia de um projeto que de EDA que realizei anteriormente á respeito do setor imobiliário, por eu não ter conseguido o resultado que queria na busca pelo caminho mais curto resolvi dar uma "embelezada" no projeto. Esse projeto de conclusão de módulo irei adicionar ao meu GitHub juntamento com outros notebooks de versões inicias

Obrigado pela atenção!
