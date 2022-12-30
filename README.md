# Machine Learning

<div align="justify">

Nesse repositório estarei postando sobre Machine Learning, serão abordados os tipos de Machine Learning bem como os principais algoritmos dessa área, com a utilização da linguagem Python.

# Breve resumo sobre Machine Learning

## O que é Machine Learning?
Segundo IBM (2020), Machine Learning ou Aprendizado de Máquina é é um ramo da inteligência artificial (IA) e da ciência da computação que se concentra no uso de dados e algoritmos para imitar a maneira como os humanos aprendem, melhorando gradualmente sua precisão. Por meio do uso de métodos estatísticos, os algoritmos de Machine Learning são treinados para fazer classificações ou previsões, revelando os principais insights em projetos de mineração de dados.

## Machine Learning x Inteligência Artificial
De acordo com SAS, enquanto a inteligência artificial (IA) pode ser definida, de modo amplo, como a ciência capaz de mimetizar as habilidades humanas, o machine learning é uma vertente específica da IA que treina máquinas para aprender com dados. 

## Casos de uso de Machine Learning do mundo real
- **Reconhecimento de fala**: também é conhecido como reconhecimento automático de fala (ASR), reconhecimento de fala por computador ou fala para texto, e é um recurso que usa o processamento de linguagem natural (PNL) para processar a fala humana em um formato escrito. Muitos dispositivos móveis incorporam reconhecimento de voz em seus sistemas para realizar pesquisas por voz, por exemplo, Siri, ou fornecer mais acessibilidade para mensagens de texto.
- **Atendimento ao cliente**: os robôs de chat on-line estão substituindo os agentes humanos ao longo da jornada do cliente. Eles respondem às perguntas mais frequentes (FAQs) sobre tópicos, como envio, ou fornecem aconselhamento personalizado, venda cruzada de produtos ou sugestões de tamanhos para os usuários, mudando a maneira como pensamos sobre o envolvimento do cliente em sites e plataformas de mídia social. Os exemplos incluem robôs de sistema de mensagens em sites de comércio eletrônico com agentes virtuais, aplicativos de mensagens, como Slack e Facebook Messenger, e tarefas geralmente realizadas por assistentes virtuais e assistentes de voz.
- **Visão computacional**: esta tecnologia de IA permite que computadores e sistemas derivem informações significativas de imagens digitais, vídeos e outras entradas visuais e, com base nessas entradas, ela pode agir. Essa capacidade de fornecer recomendações o distingue das tarefas de reconhecimento de imagem. Impulsionada por redes neurais convolucionais, a visão computacional tem aplicações na marcação de fotos nas mídias sociais, imagens radiológicas na assistência médica e carros autônomos no mercado automotivo.
- **Mecanismos de recomendação**: usando dados de comportamento de consumo anterior, os algoritmos de IA podem ajudar a descobrir tendências de dados que podem ser usados para desenvolver estratégias de vendas cruzadas mais eficazes. Isso é usado para fazer recomendações complementares relevantes aos clientes durante o processo de finalização da compra para varejistas on-line.

## Métodos de Machine Learning
- **Supervisionado**: também conhecido como machine learning supervisionado, é definido pelo uso de conjuntos de dados rotulados para treinar algoritmos que classificam dados ou preveem resultados com precisão. O algoritmo de aprendizado recebe um conjunto de entradas junto com as saídas corretas correspondentes, e aprende ao comparar a saída real com as saídas corretas para encontrar erros. O aprendizado supervisionado ajuda as organizações a resolver uma variedade de problemas do mundo real em grande escala, como a classificação de spam em uma pasta separada da sua caixa de entrada, além disso o aprendizado supervisionado é comumente empregado em aplicações nas quais dados históricos preveem eventos futuros prováveis. Por exemplo, ele pode antecipar quando transações via cartão de crédito são passíveis de fraude ou qual segurado tende a reivindicar sua apólice. Alguns métodos usados na aprendizagem supervisionada incluem redes neurais, naïve bayes, regressão linear, regressão logística, floresta aleatória, máquina de vetores de suporte (SVM).
- **Não supervisionado**: também conhecido como machine learning não supervisionado, usa algoritmos de machine learning para analisar e agrupar conjuntos de dados não rotulados. Esses algoritmos descobrem padrões ocultos ou agrupamentos de dados sem a necessidade de intervenção humana. Sua capacidade de descobrir semelhanças e diferenças nas informações torna a solução ideal para análise exploratória de dados, estratégias de vendas cruzadas, segmentação de clientes, imagem e reconhecimento de padrões. Também é usado para reduzir o número de recursos em um modelo por meio do processo de redução de dimensionalidade, a análise de componente principal (PCA) e a decomposição de valor singular (SVD) são duas abordagens comuns para isso. Outros algoritmos usados no aprendizado não supervisionado incluem redes neurais, armazenamento em cluster de k-médias, métodos de armazenamento em cluster probabilístico e muito mais.
- **Semissupervisionado**: é utilizado para as mesmas aplicações que o aprendizado supervisionado. Mas este aqui manipula tanto dados rotulados quanto não-rotulados para treinamento – normalmente uma pequena quantidade de dados rotulados com uma grande quantidade de dados não-rotulados (porque dados sem rótulos são mais baratos e demandam menos esforços para serem adquiridos). Esse tipo de aprendizado pode ser empregado com métodos como classificação, regressão e previsão. O aprendizado semi-supervisionado é útil quando o custo associado à rotulação é muito alto para possibilitar um processo de treinamento totalmente rotulado. Exemplos básicos incluem a identificação do rosto de uma pessoa em uma webcam.
- **Aprendizagem por reforço**: é normalmente utilizado em robótica, jogos e navegação. Com ele, o algoritmo descobre através de testes do tipo 'tentativa e erro' quais ações rendem as maiores recompensas. Este tipo de aprendizado possui três componentes principais: o agente (o aprendiz ou tomador de decisão), o ambiente (tudo com que o agente interage) e ações (o que o agente pode fazer). O objetivo é que o agente escolha ações que maximizem a recompensa esperada em um período de tempo determinado. O agente atingirá o objetivo muito mais rápido se seguir uma boa política. Então o foco do aprendizado por reforço é descobrir a melhor política.

## Dados de treino x Dados de teste
- **Dados de treino**: dados de treino são os dados que serão apresentados ao algoritmo de machine learning para criação do modelo. Estes dados costumam representar cerca de 70% da totalidade dos dados.
- **Dados de teste**: são os dados que serão apresentados ao modelo após a sua criação, simulando previsões reais que o modelo realizará, permitindo assim que o desempenho real seja verificado. Estes dados costumam representar cerca de 30% da totalidade dos dados.

Se o modelo conseguir fazer previsões corretas sobre os dados de teste, significa que o modelo está funcionando bem. Esses dados de teste também são dados históricos, ou seja, já estão classificados, então basta comparar as previsões do modelo com as respectivas classificações para ver se ele acertou ou errou nas suas previsões.
 
## Técnicas de Machine Learning
- **Classificação**: na classificação, o objetivo é identificar a qual categoria determinada imagem ou conjunto de dados pertence. Em outras palavras, escolher dentre uma lista pré-definida de possibilidades se uma imagem diz respeito à categoria gato ou cachorro, como no exemplo. Os problemas de classificação são aqueles onde se busca encontrar uma classe, dentro das possibilidades limitadas existentes. Esta classe pode ser se um aluno foi aprovado ou reprovado, se uma pessoa possui uma doença ou não, dentre outras tantas possibilidades, sendo que nestes casos ou a previsão será uma ou outra.
- **Regressão**: neste caso, procura-se estimar um valor numérico e não uma categoria ou rótulo. Pode ser utilizada para estimar a precificação de um produto, por exemplo.
- **Clusterização**: clusterizar nada mais é do que agrupar. Logo, o objetivo desse tipo de algoritmo é agrupar dados semelhantes. Por exemplo, consumidores que possuem o mesmo perfil ou fotos que contêm a mesma pessoa, similar ao que ocorre no Google Fotos.

## Principais algoritmos de Machine Learning
- **KNN**
- **Regressão Linear**
- **Regressão Logística**
- **Decision Trees**  
- **Random Forest**
- **Naives Bayes** 
- **PCA**
- **Perceptron**
- **SVM**
- **K-Means**  
</div>

