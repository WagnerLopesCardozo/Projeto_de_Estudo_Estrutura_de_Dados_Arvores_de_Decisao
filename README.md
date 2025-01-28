# Projeto_de_Estudo_Estrutura_de_Dados_Arvores_de_Decisao
## <p align="justify">Este repositório é parte de um projeto de estudo de estrutura de dados Árvores de Decisão pesquisadas em Ciência de Dados e Ciência da Computação. Tem como objetivo implementar estas estruturas na linguagem de programação Python estudando a dinâmica de funcionamento e comportamento assintótico Big (O) destas estruturas.</p>

![image](https://github.com/user-attachments/assets/309469e9-4971-4ac5-b65a-8ea20db1ca6e)

# Breve Introdução à Estrutura de Dados Árvores de Decisão

<p align="justify">
As árvores de decisão são estruturas de dados amplamente utilizadas em Ciência da Computação e Ciência de Dados, com aplicação predominante em problemas de classificação, regressão e tomada de decisão hierárquica. Essa estrutura é composta por nós que representam condições ou variáveis de entrada, ramificações que simbolizam as possíveis decisões ou divisões baseadas nas condições, e folhas que representam os resultados finais. A simplicidade interpretativa e a capacidade de modelar decisões complexas tornam as árvores de decisão fundamentais em algoritmos supervisionados e métodos de aprendizado de máquina.</p>


<p align="justify">Entre os principais algoritmos de construção de árvores de decisão destacam-se o ID3 (Iterative Dichotomiser 3), o C4.5 e sua evolução, o algoritmo CART (Classification and Regression Tree). O ID3 utiliza o ganho de informação como métrica para selecionar atributos que melhor dividem os dados, enquanto o C4.5 aprimora o ID3 ao lidar com dados contínuos, dados ausentes e podas automáticas da árvore. Por outro lado, o algoritmo CART constrói árvores binárias, podendo ser utilizado tanto para tarefas de classificação quanto de regressão, e emprega a impureza de Gini ou o erro quadrático médio como critério de divisão. Além disso, métodos como Random Forests e Gradient Boosted Trees constroem conjuntos de árvores, combinando suas decisões para aumentar a robustez e a precisão.</p>


<p align="justify">A análise de algoritmos para árvores de decisão é fundamental para garantir a eficiência em diferentes contextos de aplicação. A construção de uma árvore de decisão envolve a avaliação de todos os atributos em cada nó, o que afeta o tempo de processamento. O tempo de treinamento de uma árvore pode variar de 𝑂 ( 𝑛 ⋅ 𝑚 ⋅ log (𝑛)), onde 𝑛 é o número de exemplos e 𝑚 é o número de atributos, até 𝑂 ( 𝑛^2 ⋅ 𝑚), dependendo do critério de divisão utilizado e da implementação. Durante a inferência, o tempo de classificação de um único exemplo é proporcional à profundidade da árvore, geralmente 𝑂 ( log (𝑛)) em árvores balanceadas.</p>


<p align="justify">O espaço de memória necessário para armazenar árvores de decisão depende diretamente do número de nós da árvore, que pode variar conforme a complexidade dos dados e a profundidade máxima permitida. Em sua forma básica, uma árvore de decisão requer 𝑂 (𝑛 ⋅ 𝑚) para armazenar os dados e 𝑂 (𝑘), onde 𝑘 é o número de nós. Estratégias de otimização, como poda (pruning), podem reduzir significativamente o tamanho da árvore ao eliminar nós irrelevantes, melhorando a interpretabilidade e reduzindo o risco de overfitting, além de minimizar o uso de memória.</p>


<p align="justify">A implementação de árvores de decisão em Python é amplamente facilitada por bibliotecas como Scikit-learn, que oferece ferramentas otimizadas para construção e uso de modelos baseados em árvores. No entanto, a implementação manual dessas estruturas é uma prática recomendada para compreender os fundamentos teóricos. Por exemplo, um algoritmo básico de construção de uma árvore pode ser implementado utilizando listas encadeadas ou dicionários para representar os nós, enquanto métricas como ganho de informação ou impureza de Gini podem ser calculadas utilizando bibliotecas numéricas como NumPy. Essa abordagem não apenas reforça a teoria, mas também permite ajustes e personalizações para problemas específicos.</p>


<p align="justify">Existem outras variantes de árvores utilizadas em Ciência da Computação que desempenham papéis específicos e relevantes em diversas aplicações. Árvores TRIE são úteis para o armazenamento eficiente de strings e suporte a operações de busca por prefixo, enquanto árvores PATRICIA são uma forma otimizada de TRIE para minimizar o uso de memória. Árvores B e suas variantes, como B+, são amplamente empregadas em sistemas de banco de dados e armazenamento em disco devido à sua eficiência na busca e inserção em dados de grande escala. Já as árvores Treap combinam as propriedades de árvores binárias de busca e heaps, oferecendo balanceamento probabilístico. Estruturas como Hash Tree são utilizadas em bancos de dados distribuídos para autenticação de dados, e Merkle Trees têm aplicação em blockchain, garantindo integridade e verificação de grandes conjuntos de dados. Cada uma dessas árvores foi projetada com propósitos específicos, tornando-as indispensáveis em seus respectivos domínios.</p>


<p align="justify">A otimização dos algoritmos de árvores de decisão pode ser alcançada por meio de estratégias como restrição da profundidade máxima, controle do número mínimo de amostras por folha e implementação de técnicas paralelas para avaliação de atributos. Além disso, estruturas de dados eficientes, como heaps e arrays, podem ser utilizadas para acelerar operações repetitivas. Bibliotecas especializadas em Python, como XGBoost e LightGBM, empregam essas técnicas avançadas para alcançar desempenho superior em aplicações de larga escala.</p>


<p align="justify">Portanto, as árvores de decisão e suas variantes são ferramentas essenciais para modelagem e resolução de problemas computacionais complexos. A análise rigorosa de sua eficiência em termos de tempo e memória, associada à implementação cuidadosa em Python, possibilita o desenvolvimento de soluções otimizadas e adaptadas a diferentes cenários. Com a evolução dos desafios computacionais, o estudo detalhado dessas estruturas continuará sendo um componente vital no avanço de áreas como ciência de dados, aprendizado de máquina e sistemas computacionais.</p>

## Referência Bibliográfica

* CORMEM, T. H., LEISERSON C. E., RIVEST R. L., STEIN C., Algoritmos Teoria e Prática – Gen LTC, 3ª Edição, 2012, ISBN-13: 978-8535236996
