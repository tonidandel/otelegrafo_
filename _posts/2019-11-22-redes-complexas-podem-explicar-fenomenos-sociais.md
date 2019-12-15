---
layout: post
title: A Ciência de Redes pode explicar um "viral"?
categories:
  - Ciência de Redes
comments: true
---

Existe um artigo fenomenal da Nature, de 1999, em que os autores (Barábási et
al) fazem um [mapeamento da Internet](%5Bhttp://barabasi.com/f/65.pdf%5D(http://barabasi.com/f/65.pdf))([^1]) e de outros sistemas de rede do mundo. Neste trabalho eles buscavam encontrar uma métrica para estimar o "tamanho" da web e fizeram uma grande descoberta: a de que embora a rede tenha (agora) cerca de três dêcadas de idade, qualquer página poderia ser alcançada com um total de 19 cliques, mesmo considerando o seu tamanho crescente.

![](https://otelegrafo.com/images/viral.png)

## O que é um fenômeno viral?

A Internet pode ser pensada como um grande conjunto de nós, que são representados pelas páginas, e um conjunto de arcos, que são representados pelos links que ligam uma página às outras. Os autores concluíram que os nós da Internet possuem graus de conectividade baseadas em uma [lei de potência](https://polymer.bu.edu/hes/rp-barabasi12networks.pdf)([^2]), em que a maioria dos nós tem baixa conectividade ao passo que uma minoria tem alta conectividade. Em sistemas desse tipo a distribuição de conectividade dos nós tende a seguir um princípio de “conectividade preferencial” ou *preferential attachment*: quanto maior o número de conexões de um nó, maior a probabilidade que mais nodos se conectem preferencialmente a ele.

Traduzindo: quanto mais páginas um site possui, maiores as chances de outras páginas estarem ligadas a ele. Isto é, as redes, sejam elas físicas, de relacionamento, biológicas, como o sistema imunológico, ou de computadores, seguem um padrão de comportamento parecido, mas não idêntico. Não há nó dominante, embora a rede não seja aleatória. Poucas conexões (*hubs*) mantém a integridade geral da rede.

Por exemplo, em uma rede social "privada", típica da Internet, um exemplo de *hub* principal é o CEO da empresa, que possui. Esse tipo de rede será, então, extremamente hierarquizada, longe de ser um "fórum aberto". Tais configurações permitem que, de certa forma, certos nós da internet não sejam "donos" donos da maior parte das conexões, mas controlam, de certa forma, o acesso à informação contida na rede.

No caso de um fenômeno social, como a [greve dos caminhoneiros](https://pt.wikipedia.org/wiki/Greve_dos_caminhoneiros_no_Brasil_em_2018) que aconteceu no Brasil em 2018 ou a série de [crises](https://www.bbc.com/portuguese/internacional-50386894) que irromperam em diversos países da América Latina do ano de 2019, é possível perceber que movimentos desse tipo tem um comportamento bem similar, sendo descentralizados e não apresentam nós dominantes (lideranças), ainda que algumas poucas conexões mantenham a integridade do movimento.

A diferença agora é justamente a interconectividade entre os nós da rede, facilitada pelas novas tecnologias de comunicação, em que a propagação daquilo daquilo que pode ser chamado de “ondas de influência” se dá como a propagação de uma perturbação em uma rede, o que comumente é chamado de “viral”. Não é preciso que todos os nós estejam conectados a todos, e foi isso que Barábási e outros mostraram no conceito de “conexão preferencial”. Como não há restrição de escala para esse grau
de conectividade, o limite seria aquele em que todos os demais nós conectam-se a um só, o que na realidade não acontece.

Para o caso dos fenômenos de massa, essas redes acabam favorecendo posturas mais condizentes com os anseios e expectativas dos membros daquela rede, em um ambiente em que a comunicação entre as categorias é virtualmente instantânea. Se as pautas mudarem em alguns desses hubs, a propagação segue seu curso de maneira incrivelmente rápida, sem a necessidade de mobilização de entidades ou nós individuais, que neste caso seriam os chamados "líderes" de determinado movimento. De certa forma, fenômeno remonta um pouco do “Efeito Mateus”,  que é baseado na passagem bíblica “Ao que tem, se lhe dará e terá em abundância, e ao que não tem, até o que tem lhe será tirado”, analogia descrita primeiramente por Merton, mas vai muito além disso. Vale saber que os movimentos sociais daqui para frente vão se confundir cada vez mais com a própria dinâmica de uma rede complexa.

[^1]: A-L. Barábási, A. Réka & J. Hawoong. “Diameter of the World-Wide Web”. Nature, Vol 401, set., 1999, p. 130-131.

[^2]: Ver também: A-L. Barabási. “Luck or reason” Nature, vol 489 p.507, 2012.
