# Prompts para Diferentes Finalidades

Lembre-se de que um Modelo de Linguagem Grande (LLM) é um modelo de IA treinado em grandes quantidades de texto para identificar padrões entre palavras, conceitos e frases, de modo que possa gerar respostas a prompts. Como você tem aprendido, uma boa solicitação pode ajudar a orientar um LLM a gerar resultados úteis para tarefas no local de trabalho. Nesta leitura, você explorará melhor como escrever prompts claros e específicos para uma variedade de casos de uso no local de trabalho.

## Casos de Uso

Como explorado anteriormente, você pode usar um LLM no trabalho para ajudar a aumentar sua produtividade e criatividade e concluir qualquer uma dessas tarefas úteis:

- Criação de conteúdo
- Sumarização
- Classificação
- Extração
- Tradução
- Edição
- Solução de problemas

**Observação**: os exemplos a seguir ilustram as práticas recomendadas de solicitação; eles não são modelos exatos a serem copiados para todas as situações. Seus resultados variarão de acordo com vários fatores, inclusive o LLM específico que estiver usando. Lembre-se de avaliar criticamente todos os resultados do LLM e de iterar em seu prompt inicial para obter o resultado mais útil.

### Como Tornar Seus Prompts Mais Eficazes

- **Considere o que você deseja que o LLM produza**. O LLM gerará resultados mais úteis se você incluir uma instrução específica em seu prompt, como criar, resumir, classificar, extrair, traduzir, editar ou resolver.
  
- **Forneça o contexto necessário**. O LLM gerará resultados mais úteis quando você incluir instruções detalhadas, com orientações específicas sobre o estilo ou o formato do resultado desejado.

A seguir, você examinará cada um dos casos de uso descritos anteriormente, considerando um exemplo adicional para cada um deles.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/AYa_4mjQQm-JWJr4v9B6CA_7fe992db0b1f4598a619ebec46e807f1_AI-Readings_Graphics_R-011_2.png?expiry=1744329600000&hmac=CvRXMnAv7-DqFuSSiXJ0TYjJ2L9LkVQZJLW_HgYkX5o)

### Criação de Conteúdo

Independentemente do seu setor, um LLM pode ajudá-lo a criar conteúdo para diversas finalidades, como postagens em blogs, relatórios, descrições de produtos e slogans. Por exemplo, suponha que você esteja trabalhando em uma campanha publicitária para uma nova linha de eletrodomésticos. Você pode pedir a um LLM que o ajude a criar um slogan envolvente para um dos produtos:

> **Prompt**: Aja como se você fosse um profissional de publicidade criativo que pode aplicar o pensamento inovador para desenvolver slogans originais que projetem as qualidades positivas de um produto. Crie um slogan conciso para uma máquina de lavar que deixa as roupas muito limpas, tem 25 configurações e cabe em um espaço pequeno.

O prompt afirma claramente que a tarefa é criar uma tagline original e concisa. Ele também fornece o contexto necessário ao especificar o tom, o estilo e o formato da tagline.

**Dica profissional**: Atribua ao LLM um papel, um trabalho ou uma função para reforçar o propósito do prompt e ajudar a orientar o LLM a produzir resultados úteis.

### Sumarização

Um LLM pode ajudá-lo a resumir muitos tipos de textos: relatórios, pesquisas com clientes, notas de reuniões, e-mails e muito mais. Por exemplo, o prompt a seguir pede que um LLM forneça um resumo de um e-mail longo:

> **Prompt**: O texto a seguir é um e-mail de um fornecedor de software. Resuma seus pontos principais em uma lista com marcadores:

> **Texto**:
> 
> Espero que você esteja bem. Foi um prazer conversar com você na conferência da semana passada.
> 
> Continuando com mais detalhes sobre nossos planos de preços. Nossa assinatura de nível bronze lhe dá acesso a três de nossos produtos de software mais populares, bem como a vídeos de treinamento para esses produtos. Se você tiver necessidades adicionais de software, poderá fazer a assinatura no nível prata. Esse nível permite que você escolha dois produtos de software adicionais, com vídeos de treinamento sobre esses produtos, além de oferecer suporte 24 horas para qualquer dificuldade que você encontrar ao usar os produtos. Por fim, nossa associação de nível ouro lhe dá acesso a todos os nossos dez produtos de software. Você recebe treinamento para todos os dez produtos, bem como suporte 24 horas por dia, e também é o primeiro a desfrutar de quaisquer adições beta aos nossos produtos.
> 
> Entre em contato comigo para saber o preço do nível de seu interesse. Oferecemos assinaturas mensais e uma taxa reduzida para uma assinatura anual.

O prompt começa com um contexto útil sobre o e-mail relevante. Em seguida, ele afirma claramente que a tarefa é resumir os pontos principais do e-mail. Por fim, especifica que o resultado deve ser formatado como uma lista com marcadores.

**Observação**: esteja ciente de que, às vezes, os LLMs podem ter alucinações ou produzir resultados de IA que não são verdadeiros. Nesse caso, o LLM pode adicionar detalhes ao resumo que não estão incluídos no e-mail de origem. Sempre avalie a precisão dos resultados do LLM antes de usá-los.

### Classificação

A classificação de textos é outra aplicação comum dos LLMs no local de trabalho. Um LLM pode ajudá-lo a classificar e-mails de Atendimento ao Cliente em categorias com base no conteúdo do e-mail, categorizar conteúdo em posts de mídia social e analisar o sentimento ou a sensação do feedback do cliente. O prompt a seguir pede que um LLM analise o sentimento em uma avaliação de cliente:

> **Prompt**: Leia estas avaliações de clientes e diga-me se o sentimento das avaliações é positivo, negativo ou neutro.

> **Comentários**:
> - Comentário do cliente: Não sei por onde começar. Tínhamos reservas para as 7:00, mas nos sentaram às 7:45. Depois, ninguém veio à nossa mesa por pelo menos 30 minutos. Nosso aperitivo e prato principal estavam medíocres. Adorei a sobremesa, mas isso não foi suficiente para mudar nossa experiência.
> - Opinião do cliente: Eu adoro esse restaurante. A comida é deliciosa e o atendimento é excelente.

O prompt começa declarando claramente que a tarefa é analisar o sentimento de uma avaliação de cliente e, em seguida, especifica as opções: positiva, negativa ou neutra. Em seguida, o prompt inclui as avaliações relevantes sob o rótulo "Avaliação do cliente".

### Extração

Você também pode usar um LLM para extração de dados do texto e transformá-los em um formato estruturado que seja mais fácil de entender, conhecido como extração. Por exemplo, este prompt solicita que um LLM analise uma publicação de blog e extraia informações sobre os produtos mencionados na publicação.

> **Prompt**: Leia a publicação do blog abaixo e extraia todas as referências a itens de vestuário que posso comprar e quanto custa cada item. Crie uma lista com marcadores somente com esses itens.

> **Postagem de blog**:
> 
> Olá a todos, quero compartilhar o que estou usando no campus neste outono. Se vou sair à noite, prefiro o jeans com ourela crua (US$ 150) e o suéter de cashmere com gola redonda (US$ 250). Para um visual mais casual, gosto do moletom de lã (US$ 99) e da calça de moletom de lã (US$ 129). Também adoro todas as cores das meias listradas (US$ 15). Elas combinam bem com os jeans e os suéteres.

O prompt começa declarando claramente que a tarefa é extrair todos os itens de vestuário mencionados no blog com seus respectivos preços. Em seguida, o prompt especifica que o formato do resultado deve ser uma lista com marcadores dos itens. Por fim, a solicitação inclui o blog relevante.

### Tradução

Você pode aproveitar um LLM para traduzir textos entre diferentes idiomas muito rapidamente. Por exemplo, o prompt a seguir solicita que um LLM ajude a traduzir descrições de produtos do inglês para o espanhol:

> **Prompt**: Traduza as descrições de nossos produtos do inglês para o espanhol. Mantenha a mesma estrutura e o tom casual usados na versão em inglês na tradução para o espanhol.

> **Descrições de produtos**:
> - Bicicleta: Não importa se você está explorando as ruas da cidade ou os caminhos da floresta, nossa bicicleta elegante e durável tem tudo isso.
> - Patins: Entre no verão em grande estilo com nossos patins suaves e elegantes.

O prompt começa declarando claramente que a tarefa é traduzir as descrições dos produtos do inglês para o espanhol. Ele também especifica que as traduções para o espanhol devem manter uma estrutura e um tom semelhantes aos dos originais em inglês. Finalmente, cada exemplo contém um rótulo que introduz a Descrição do produto: "Bicycle" (Bicicleta) e "Rollerblades" (Patins). Esse formato indica que o LLM deve apresentar o resultado em uma forma semelhante.

**Observação**: como prática recomendada, confirme se as traduções do LLM são precisas fazendo uma verificação cruzada com outra ferramenta de tradução.

### Edição

Você também pode usar um LLM para editar e reescrever textos. O LLM pode ajudar a mudar o tom do texto, de formal para casual, ou fazer uma verificação gramatical. Por exemplo, o prompt a seguir pede que um LLM ajude a editar um relatório técnico para que ele seja menos jargônico e mais fácil de ser entendido pelas partes interessadas:

> **Prompt**: Edite a linguagem do parágrafo a seguir para que seja fácil para o público em geral entender. Use vocabulário e estruturas gramaticais mais simples, mas mantenha as mesmas ideias.

> **Texto**:
> A seleção do local para expansão é um processo complexo e multifacetado. O local do lado oeste oferece várias vantagens, incluindo zoneamento para uso industrial e acesso direto a uma grande rodovia e a uma ferrovia. No entanto, o local também está localizado em uma jurisdição com um processo de licenciamento complexo e demorado, e sua distância de zonas residenciais pode exigir salários mais altos para atrair trabalhadores.

O prompt começa declarando claramente que a tarefa é editar o texto para facilitar a compreensão de um público geral. Em seguida, o prompt especifica que o vocabulário e a gramática do texto devem ser simplificados, enquanto o conteúdo principal deve permanecer o mesmo. Por fim, ele inclui o parágrafo relevante.

### Solução de Problemas

Outro caso de uso é a solução de problemas. Você pode usar um LLM para gerar soluções para uma variedade de desafios no local de trabalho, desde a análise de dados de vendas até o planejamento de um evento. Por exemplo, o prompt a seguir pede que um LLM ajude a organizar um programa para uma organização sem fins lucrativos:

> **Prompt**: Estamos realizando um programa comunitário para ensinar habilidades de jardinagem às crianças. O programa vai de 1º de junho a 15 de agosto. Queremos que as crianças sejam capazes de cultivar plantas que estarão prontas para a colheita quando o programa terminar. Primeiro, identifique uma lista de 10 plantas que podem ser plantadas e cultivadas nesse período de tempo. Inclua fontes que comprovem o tempo de colheita de cada planta.

> Queremos que as crianças cultivem três plantas. Essas plantas devem ser tão diferentes umas das outras quanto possível. Portanto, em seguida, escolha três plantas da lista que proporcionarão essa variedade às crianças.

O prompt começa com um contexto útil sobre o programa, como seu objetivo principal e a linha do tempo. Em seguida, o prompt divide o problema em duas etapas principais: Primeiro, identificar uma lista de 10 plantas que se encaixem no cronograma e, segundo, escolher três plantas da lista que sejam diferentes umas das outras. O prompt também pede que o LLM inclua fontes para a lista de 10 plantas. Pedir ao LLM que cite suas fontes no resultado ajuda a verificar a precisão das informações usadas para resolver o problema.