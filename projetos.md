# Projetos de IA

Executar projetos de IA podem parecer processos "abstratos", difíceis de tangibilizar: São muitas novas tecnologias, um tipo de mercado novo, com profissionais de perfis diferentes. Mas existem metodologias provadas que tornam a execução de projetos de IA mais ciência do que arte (Mas não 100% ;D).

## Metodologias para Projetos de IA

Diversas empresas tem implementado práticas e processos próprios para guiar a execução de seus projetos de IA, e apesar de peculiaridades entre cada tipo de aplicação/metodologia, podemos perceber pontos-chave que costumam ser guias importantes para o sucesso da execução deste tipo de projetos.
Entre algumas das metodologias que tem se provado no mercado estão:

1. Stanford Interactive Loop.
2. MIT 4 Phases
3. University of Pennsylvania's AI G&S Model (Governance and Strategy)
4. IBM Data Science Methodology (John Rollins)
5. CRISP-DM

Cada abordagem apresenta pontos únicos, porém apontam aspectos diferentes da aplicação de projetos de IA, que vão desde uma visão mais estratégica (G&S Model) até detalhes mais técnicos (Stanford Interactive Loop).

### Stanford Interactive Loop
Esta abordagem aponta três etapas para execução de projetos de IA. Foi especificamente criada para projetos de Machine Learning pela equipe liderada por Andrew Ng na Google (Inclusive, equipe esta responsável pelo desenvolvimento do Tensorflow e do Keras). As etapas são:
1. Definir
2. Treinar
3. Avaliar

Estas etapas aparecem de forma sequencial, porém fazem parte de um LOOP, e podem se repetir quantas vezes for necessário durante o ciclo de vida do projeto.

#### Definir
> Esta etapa já considera que as necessidades do projeto foram descritas e documentadas

Aqui, define-se o que a equipe irá construir: 
- Qual a arquitetura?
- Escolhida a técnica, qual modelo vou usar?
- OpenSource ou Proprietário?
- ChatGPT, Llama ou Mistral?
- Rede Neural Convolucional ou Generative Adversarial?
- Florestas Aleatórias ou Reinforcement Learning?

São perguntas que devem ser respondidas durante esta etapa, para que a equipe técnica possa seguir para as proximas etapas.
Uma das questões mais importantes para responder nesta etapa é qual o tipo de abordagem será levada durante o projeto. Exemplos de possíveis técnicas/abordagens:
- Classificação
- Previsão
- Recomendação
- Aprendizagem por Reforço
- Inteligência Generativa

Um cuidado a se tomar é resistir a tentação de aplicar GenAI (Inteligência Generativa), como ChatGPT e afins em TUDO. São ferramentas excelentes que podem ser usadas inclusive como auxiliares durante o projeto, mas não serão, necessariamente, a melhor forma de resolver um problema.

#### Treinar
Uma vez que definidos estão os problemas a resolver e a abordagem a ser tomada, pode-se trabalhar na construção do modelo e na aquisição/tratamento do dados. Nesta etapa é importante levantar toda a massa de dados disponíveis, avaliar quais as features do problema, feature engineering, pre-processamento de dados e alimentar o modelo com o máximo de informação possível. 

**Feature Engineering**: É o processo de seleção, criação e transformação de variáveis (ou "features") que serão usadas para treinar um modelo de machine learning. Esse processo é fundamental, pois a qualidade e a relevância das features influenciam diretamente o desempenho e a precisão do modelo. Com base nos elementos destacados nos post-its, aqui estão algumas das principais etapas e conceitos envolvidos em feature engineering:

1. Entender as Variáveis que Influenciam o Modelo: Antes de treinar um modelo, é essencial identificar quais variáveis realmente afetam o resultado final. Isso envolve uma análise inicial para determinar quais características (features) possuem uma correlação relevante com o que se deseja prever. Essa etapa ajuda a eliminar variáveis irrelevantes e focar naquelas que têm maior impacto, facilitando o aprendizado do modelo.
2. Entender a Relação entre as Features: Não basta apenas selecionar variáveis isoladamente; é importante compreender como elas se relacionam entre si. Algumas variáveis podem ter correlação direta, outras podem representar redundância, e algumas podem ter um efeito combinado que afeta o resultado de forma mais significativa. Analisar essas relações ajuda a evitar multicolinearidade e a melhorar a interpretabilidade do modelo.
3. Coletar Informações Suficientes para Treinar o Modelo: Para que o modelo aprenda de forma eficaz, é necessário coletar dados suficientes e variados para cada uma das variáveis. Dados insuficientes ou pouco variados podem levar a um modelo enviesado ou que não generalize bem em novas situações. Assim, a coleta e o pré-processamento de dados são partes críticas do processo de feature engineering.
4. Data Augmentation (Aumento de Dados): Em alguns casos, pode ser necessário gerar mais dados para enriquecer o conjunto de treinamento, especialmente em áreas como processamento de imagem e NLP (Processamento de Linguagem Natural). O Data Augmentation permite criar variações dos dados existentes, aumentando a diversidade e a quantidade de informações que o modelo pode aprender, melhorando a generalização em cenários reais.

No geral, Feature Engineering é um processo iterativo que exige análise e experimentação. Ele visa transformar os dados brutos em informações úteis e de alta qualidade, preparando um conjunto de dados que maximiza o desempenho do modelo e permite uma melhor interpretação e análise de resultados.

**Honeypot Projects**: Durante a execução do projeto pode chegar-se a conclusão que não existem dados o suficiente para treinar os modelos. Para isso, podem ser usados projetos "honeypot", que são iniciativas estratégicas criadas com o objetivo de atrair usuários e gerar interações que possibilitem a coleta de dados relevantes para o desenvolvimento e treinamento de modelos. Esses projetos geralmente têm características específicas que incentivam a participação dos usuários e a captação de informações úteis.
1. Projetos de Curta Duração: Honeypot Projects muitas vezes são desenvolvidos com um tempo de execução limitado, o que cria uma sensação de urgência e motiva a participação imediata dos usuários. Esses projetos temporários podem ser utilizados para reunir rapidamente uma quantidade substancial de dados específicos, permitindo que a empresa colete informações atualizadas em um curto período.
2. Promoções: Campanhas promocionais, como descontos, concursos e prêmios, são frequentemente usadas como incentivo para que os usuários participem desses projetos. A ideia é que as promoções tornem o projeto mais atrativo e aumentem o número de interações, possibilitando a coleta de dados comportamentais e preferências dos usuários de forma mais eficaz.
3. Estratégias de Captação de Dados: O objetivo final dos Honeypot Projects é coletar dados valiosos para treinar e otimizar modelos de machine learning. Esses projetos são estruturados para captar dados variados e ricos em contexto, que podem incluir informações demográficas, comportamentais, de compra, entre outras. Ao utilizar estratégias específicas para coletar esses dados, os Honeypot Projects garantem que a empresa obtenha informações de alta qualidade para alimentar futuros projetos de IA e personalização.

Esses projetos são eficazes porque atraem grande participação dos usuários enquanto oferecem valor em troca, como acesso a ofertas exclusivas ou a possibilidade de ganhar prêmios. No entanto, é essencial que as organizações garantam que esses projetos estejam em conformidade com regulamentações de privacidade e coleta de dados, informando aos usuários sobre o uso das informações coletadas.

#### Avaliar
Desde a implementação, mesmo que ainda muito básica, do primeiro modelo, já é muito importante avaliar o seu funcionamento. Nesta fase, colhe-se feedback sobre o modelo de IA, e como os seus resultados tem se apresentado. Porém nem sempre é possível ter casos de uso reais suficientes para ter um feedback apropriado: Podem ser necessários muitos dados para treinar e avaliar um modelo complexo. Por isso, é comum a utilização de um método chamado **Validação Cruzada (Cross-validation)**, onde mesmo que em posse de um único dataset, podemos treinar e avaliar modelos, e testá-los de forma padronizada, inclusive tendo a possibilidade de comprar diversos modelos ou um unico modelo com diversas configurações de hiperparâmetros.
Para este fim, segue-se as seguintes etapas:

1. Separar o dataset em dois subgrupos: Treinamento e Validação (Geralmente na proporção 80%-20%);
2. Treinar o modelo com o subgrupo de treinamento e verificar a sua performance usando métricas relevantes: Loss, Recall, F1 Score, RMSE, ROC...
3. Aplicar o modelo no subgrupo de validação e analisar as mesmas métricas.

A partir desta avaliação, vai ser possível verificar comportamentos que vão revelar a qualidade do modelo e possíveis problemas como viés ou alta variância. Cada métrica irá revelar algum tipo de informação, e não existe "receita de bolo" aqui: Esta etapa é tanto ciência quanto arte, e depende da visão crítica e treinada de um especialista que irá tomar os insights a partir dos dados e entender quais passos tomar. 
Existem porém certas formas de entender os principais problemas a partir de uma comparação entre as métricas de treinamento e de validação, e para isso vamos ver a performance comparativa em ambos considerando uma métrica de comparação, por exemplo, comparando o Loss (Perda, quanto maior, pior):

1. Treinamento Alto - Validação Alto: O modelo não conseguiu atingir uma boa performance, indicando que muito provavelmente as features escolhidas não expressam relações interessantes com a varíavel-alvo, ou que o modelo escolhido não é aplicável ao problema. Também podem haver problemas com os hiperparametros escolhidos. Este comportamento aponta **underfitting**, ou **alto viés**.
2. Treinamento Baixo - Validação Alto: O modelo pareceu entender bem as relações entre as características e ter uma performance significativa quando avaliando os dados de treinamento, porém ao aplicar os dados de validação cruzada, a performance decai consideravelmente. Isto aponta **Alta variância**, também chamado de **Overfitting**. Esta característica aponta um modelo que se aproximou demais dos dados de treinamento, perdendo a capacidade de generalizar dados além do treinamento.
3. Treinamento Baixo - Validação Baixo: É um bom indicativo que o modelo tem a capacidade de generalizar e tem uma performance positiva, pois conseguiu aproximar bem os valores do dataset, e também apresenta uma boa capacidade de ter bons resultados com valores fora do dataset.

Existem diversas formas de tratar viés e variância, envolvendo modificar o modelo e seus parâmetros durante o treinamento.

Outro tipo de avaliação interessante usando a metodologia de validação cruzada, é após definido o modelo, realizar diferentes testes com o subgrupo de validação, usando o mesmo modelo porém com diferentes hiperparâmetros, para um ajuste fino do modelo.

Modelos de Inteligência Artificial Generativa, apesar de parecerem semelhantes a "caixas-preta", onde não há acesso aos parametros, projetos que utilizam mesmo LLMs comerciais closed-source, devem estar atentos a usar APIs ou Interfaces que possibilitem a modificação de parametros para customização da solução. Parametros comuns para otimizar LLMs como ChatGPT são Temperatura, Top-K e Top-P, e a seu ajuste fino pode significar a diferença entre um produto bem sucedido e um produto sem aplicação de uso real.

### MIT 4 Phases
O MIT, através do MIT Professional Education, aborda Machine Learning (Uma subcategoria do estudo de IA) como uma ferramenta para a **tomada de decisões**. Esta abordagem pressupõe que os ambientes empresariais hoje produzem uma grande quantidade de dados, e que o uso deste pode ser uma ferramenta excelente para alavancar o processo de tomada de decisões.

Este modelo descreve 4 passos para o uso de IA/ML para tomada de decisões, e esta não está particularmente focada em definir o caráter técnico do projeto, mas em determinar uma divisão clara de seções replicáveis:

1. Compreender os dados: Nesta fase, é importante entender o contexto, problemas e dados disponíveis para análise. Por mais simples que possa parecer, esta etapa é o fundamento de uma aplicação de IA, e realizá-la de forma consciente e efetiva pode garantir um bom resultado.
2. Fazer previsões: Esta fase aponta diretamente o uso de algoritmos de Machine Learning para determinar uma linha de decisão baseada em dados. Modelos como Regressão, Classificação ou Redes Neurais, a escolha do algoritmo dependerá da **compreensão dos dados** e do **contexto**. O tipo de previsão feita pode ser resultar numa análise descritiva, preditiva...
3. Tomar decisões sem certeza absoluta: A partir das previsões e dados analisados, é possível tomar uma decisão, que nas primeiras vezes mais podem parecer "palpites educados" a partir dos dados, porém estarão fundamentados matematicamente e, se os modelos forem treinados e definidos adequadamente, estarão definindo bons parâmetros para a tomada de decisões.
4. Determinar as inferências causais: Esta etapa é única desta abordagem do **MIT**, pois afirma uma necessidade particular de verificar a relação direta entre as causas e efeitos, incluindo aquilo que foi inferido pelo modelo de previsão: Deve-se perguntar, após a tomada de decisões e a análise posterior dos resultados causados pela decisão, se há, de fato, uma relação entre os dados usados para previsão, e os resultados obtidos a partir das decisões tomadas.

#### Relação Estado X Informação 
O **MIT 4 Phases** também utiliza a relação de Estado x Informação para definir quais os tipos de abordagens de Machine Learning podem ser melhor utilizadas para determinados problemas.

O Estado é o ambiente/contexto na qual as previsões serão tomadas. É um ambiente que é fixo, ou muda com pouca frequencia? Um comportamento que se altera a cada década? Talvez mude de ano em ano? Ou talvez um ambiente com variáveis que estão mudando a cada segundo? São perguntas que podem ser feitas para ajudar a definir o **estado** do problema.

A Informação refere-se à disponibilidade e acesso a informações e dados deste contexto. As informações das variáveis que descrevem o ambiente são de fácil acesso? A quantidade de informações é limitada ou só se tem acesso à informações do momento atual?

- **Estado Fixo** - **Alta Disponibilidade de Informações**: Nestes casos, o ambiente não muda e as informações são amplamente acessíveis, como dados históricos e bastante informação disponivel. Nestes casos usamos o **Controle Preditivo Baseado em Modelos** (MPC): Utilizando-se de dados passados, definine-se um modelo para realizar previsões.
- **Estado Fixo** - **Baixa Disponibilidade de Informações**: Aqui, o ambiente não muda, porém só se tem informações a cada interação com o ambiente, sem dados históricos por exemplo. Para estes problemas, sugere-se o **multi-armed bandit**: Um algoritmo por reforço que alavanca exploração e explotação, analisando todas as possibilidades e escolhendo (normalmente) a decisão com o melhor resultado previsto.
- **Estado Altamente Dinâmico** - **Alta Disponibilidade de Informações**: Cada interação com o ambiente o modifica, tornando o problema altamente dinâmico, porém existem informações e dados para cada ação e estado possível. Aqui, sugere-se **processo de decisão de Markov**: Um modelo matemático que descreve o ambiente e possíveis ações a partir de uma tabela que vai definir a melhor série de decisões a tomar considerando que suas ações irão interferir no estado futuro do ambiente.
- **Estado Altamente Dinâmico** - **Baixa Disponibilidade de Informações**: Este é o problema mais complexo, onde o estado varia rapidamente, assim como no caso anterior, porém os dados são escassos, e só é possível saber o que está acontecendo no momento presente após interagir com o ambiente, ou tomar uma ação. Este problema sugere o uso de **aprendizagem por reforço**, onde o algoritmo autonomamente aprende a interagir com o ambiente, de forma a ter os melhores resultados possíveis.

### University of Pennsylvania's AI G&S Model
O modelo de Estratégia e Governança de IA proposto pela *University of Pennsylvania* descreve etapas mais técnicas e divide o processo de implementação de projetos de IA em 8 fases claras e bem definidas a partir da sua função operacional, tornando claro quais profissionais e setores devem estar em foco em cada etapa.

1. **Data Acquisition**: Nesta fase, após entendidas as necessidades de negócio, cria-se uma coleção de dados pertinentes ao problema e contexto. Tanto *stakeholders* quanto *cientistas, analista e engenheiros de dados* unem-se neste momento para entender quais dados são importantes, quais estão disponíveis na infraestrutura atual da corporação e quais precisarão ser adquiridos externamente, incluindo os métodos que serão utilizados para adquirir estes dados.
2. **Data Exploration**: Aqui, em posse da massa de dados que será utilizada, explora-se de forma a descobrir relações interessantes e insights. *Analistas e cientistas de dados* são os principais protagonistas nesta etapa, porém é importante que em contato direto com os demais setores possam observar relações e comprovar que fazem sentido ao negócio que apresentam uma relação clara de causalidade.
3. **Data Preparation**: Basicamente *cientistas de dados* irão formatar e padronizar os dados, de forma que sejam possíveis usá-los em modelos de IA. Esta etapa é puramente "mecanica" e exige conhecimento técnico, porém não tem grande impacto quanto ao negócio, porém impacta grandemente a qualidade das etapas técnicas posteriores.
4. **Feature Engineering**: Aqui, a equipe técnica irá desenvolver características que serão *input* para a IA, a partir dos dados preparados. A partir das informações disponíveis e da exploração dos dados, se irá definir aqui quais características serão influentes na saída esperada do modelo, e como ela deve ser inserida. Inclui mais uma análise matemática e estatistica dos dados.
5. **Model Selection**: A partir das informações anteriores, os *cientistas de dados* aqui irão decidir qual modelo será utilizado: Uma regressão linear simples? Talvez um modelo de classificação for regressão logística? Árvores de Decisão? Ou modelos de IA Generativa como uma LLM? Serão perguntas respondidas nesta etapa.
6. **Model Training**: Aqui, o modelo escolhido será treinado com os dados e *features* definidas nas etapas anteriores. Modelos pré-treinados como LLMs podem ser aplicados à fine-tuning ou mesmo treinados caso haja necessidade e estrutura própria para isto.
7. **Hyper Parameter Tuning**: Após treinado o modelo, a partir de benchmarks é possível definir a melhor combinação de hiper-parâmetros para que as respostas tenham a melhor performance possível. LLMs tem hiper-parâmetros tunáveis como Temperatura, Top-P, Top-K, etc.
8. **Predictions**: Aqui serão feitas as previsões do modelo, e as mesmas serão avaliadas. Importante definir métricas e parâmetros de sucesso claros, para que seja possível medir o quanto as previsões feitas pelo modelo serão úteis ao problema/contexto proposto na primeira etapa.

A metodologia proposta pela *University of Pennsylvania* é descrita juntamente com uma série de orientações quanto à governança e estratégia para implementação de projetos de IA, e portanto, não existe fora de um contexto maior, e muitas etapas devem ser observadas mesmo antes de iniciar um projeto de IA, como a estratégia da empresa para estes projetos, e se serão projetos de curto ou longo prazo, como estes projetos devem ser equilibrados dentro de um portfólio de projetos sustentável e preocupações como viéses e ética.

### IBM Data Science Methodology (John Rollins)

