# Modelos de IA e o Processo de Treinamento
Você já explorou como as ferramentas de IA são alimentadas por modelos de IA. Nesta leitura, você obterá uma compreensão mais profunda de como os modelos de IA são desenvolvidos. Você descobrirá o processo iterativo que os designers e engenheiros de IA usam para treinar modelos de IA a partir de dados, garantindo que as ferramentas de IA funcionem de forma confiável. Aprender mais sobre o funcionamento interno das ferramentas de IA o ajudará a discuti-las com mais precisão e confiança.

## Ferramentas de IA e Modelos de IA

Termos como ferramentas de IA e modelos de IA podem ser confusos porque soam semelhantes, mas se referem a coisas diferentes. Lembre-se de que **uma ferramenta de IA** é um software avançado por IA que pode automatizar ou auxiliar os usuários em várias tarefas. **Um modelo de IA** é um programa de computador treinado em conjuntos de dados para reconhecer padrões e executar tarefas específicas.

Para ilustrar essa relação, considere um carro e seu motor.

![Um carro e seu motor](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/lA5V2JCqQXSYQC-slVQavg_9ec158c797d84a22b87343a6766f06f1_LBQy6QWE3Y_RJbkWomQVAgkJYvqn2DtndQDx0fZJFqWFLv6MsC7oIZyC2wr7dgKmqgoXDR8s88a2HcWOHiAd3NhEV7gB7Mq4pCwG4DTvd_AXhhkuzfCd5udFXeoct2IU14nftHYI00QptOdDgyf2n6E6xxj4HZ4l_gm1dOu319GpozR6Ythznn-XpKX7nRI?expiry=1743897600000&hmac=GbNeDOXJeA9qhOffwfQD4eQRhl8JhGlYA6gbJiUX268)

### Um Carro como Metáfora

- **Ferramenta de IA**: O carro, com sua interface amigável, como um volante e um painel, representa a ferramenta de IA. Essa ferramenta ajuda você a chegar ao seu destino, que pode ser uma tarefa concluída ou um resultado desejado. Assim como os engenheiros de automóveis projetam diferentes recursos para várias necessidades, os designers e engenheiros de IA criam ferramentas de IA com funcionalidades específicas para sua finalidade.
- **Modelo de IA**: Sob o capô, por assim dizer, está o modelo de IA. Esse mecanismo invisível processa as informações que você fornece, como sua entrada em um software de edição de fotos, e permite que a ferramenta de IA funcione.

Da mesma forma que escolhemos carros com base em sua finalidade, como um sedã para dirigir no dia a dia ou uma caminhonete para transportar cargas pesadas, as ferramentas de IA são desenvolvidas para uma ampla gama de aplicações. Existem ferramentas de IA para gerar diferentes textos criativos, imagens, vídeos ou até mesmo escrever códigos de computador. E, independentemente da função específica da ferramenta de IA, é o modelo de IA subjacente que faz o trabalho pesado, potencializando os recursos da ferramenta.

> **Observação**: Algumas ferramentas de IA utilizam vários modelos de IA, trabalhando juntos como uma "família", para obter mais flexibilidade e realizar uma gama maior de tarefas. Cada modelo da família pode ser especializado em uma subtarefa específica, contribuindo, em última instância, para a funcionalidade geral da ferramenta de IA. Você explorará esses tipos de ferramentas multimodais mais adiante neste curso.

## O Processo de Treinamento de Modelos de IA

Os designers e engenheiros de IA desenvolvem modelos de IA por meio de um processo chamado **treinamento**. Veja a seguir um exemplo das etapas típicas que um designer pode seguir nesse processo, neste caso, para criar um modelo que preveja chuvas:

### 1. Definir o Problema a Ser Resolvido

Os designers e engenheiros de IA querem prever a chuva para ajudar as pessoas a se manterem secas durante o trajeto de ida e volta para o trabalho. Eles começam considerando os recursos e as limitações da IA antes de identificar uma solução de IA.

### 2. Coletar Dados Relevantes para Treinar o Modelo

Os designers e engenheiros de IA coletam dados históricos dos dias em que choveu e dos dias em que não choveu nos últimos 50 anos.

### 3. Preparar os Dados para o Treinamento

Os designers e engenheiros de dados de IA preparam os dados rotulando recursos importantes, como temperatura externa, umidade e pressão do ar, e, em seguida, observando se choveu. Também é comum separar os dados em dois conjuntos distintos: um conjunto de treinamento e um conjunto de validação para teste posterior.

### 4. Treinar o Modelo

Os designers e engenheiros de IA aplicam programas de aprendizado de máquina (ML) aos dados de treinamento preparados. Os programas de ML analisam os dados e começam a aprender a reconhecer padrões que indicam a probabilidade de chuva, como a combinação de altas temperaturas, baixa pressão do ar e alta umidade.

### 5. Avaliação do Modelo

Os designers e engenheiros de IA usam o conjunto de validação que prepararam anteriormente para avaliar a capacidade do modelo de prever chuvas de forma precisa e confiável. A análise do desempenho de um modelo pode revelar possíveis problemas que afetam o modelo, como dados de treinamento insuficientes ou tendenciosos. Se houver algum problema, os projetistas e engenheiros de IA poderão revisitar uma etapa anterior desse processo para tentar uma abordagem diferente. Quando o modelo tiver um bom desempenho com seu conjunto de validação, o processo continua na próxima etapa.

### 6. Implantar o Modelo

Quando os designers e engenheiros de IA estão satisfeitos com o desempenho do modelo, eles o implantam em uma ferramenta de IA - ajudando as pessoas da cidade a se manterem secas no caminho para o trabalho!

### O Processo Iterativo

O treinamento do modelo é um processo iterativo. Os designers e engenheiros de IA podem repetir cada etapa quantas vezes forem necessárias e fazer ajustes até criar o melhor modelo possível.

Mas o processo não termina na implantação. Quando os usuários interagem com um modelo em situações práticas, o modelo pode ser exposto a novos desafios. Os designers e engenheiros de IA devem monitorar e coletar feedback continuamente sobre seus modelos, garantindo que eles continuem a ter um desempenho confiável e identificando áreas para melhoria. É esse processo iterativo de refinamento contínuo que torna os modelos de IA precisos e versáteis, o que, em última instância, leva a ferramentas de IA eficazes e confiáveis. Quando você entende como os modelos de IA são desenvolvidos, pode tomar decisões informadas sobre quando e como usar uma ferramenta de IA para atingir seus objetivos.
