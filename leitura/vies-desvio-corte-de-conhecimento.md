# Viés, Desvio e Corte de Conhecimento
Uma compreensão completa dos conceitos de IA responsável — como viés, desvio e corte de conhecimento — pode ajudá-lo a usar a IA de forma mais ética e com maior responsabilidade. Nesta leitura, você aprenderá a usar as ferramentas de IA de forma responsável e a entender as implicações de resultados injustos ou imprecisos.

## Danos e Vieses

O envolvimento com a IA de forma responsável exige o conhecimento de seus vieses inerentes. **Viés de dados** são circunstâncias em que erros sistêmicos ou preconceitos levam a informações injustas ou imprecisas, resultando em resultados tendenciosos. Usar a IA de forma responsável e estar ciente dos possíveis vieses da IA pode ajudá-lo a evitar esses tipos de danos.

![Diagrama ilustrando a parcialidade em um modelo de IA](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/AwPyZByATKiHLkEcQxeJoA_d428399738fa4e36b5d72593c5fd2cf1_control-panel.png?expiry=1744329600000&hmac=eottoEAWkbYFwQO9FivLERXPAuYzwXXKin46unke-d8)

Os resultados tendenciosos podem causar muitos tipos de danos às pessoas e à sociedade, incluindo:

### Danos Alocativos

Transgressão que ocorre quando o uso ou o comportamento de um sistema de IA retém oportunidades, recursos ou informações em domínios que afetam o bem-estar de uma pessoa.

**Exemplo**: Se um gerente de propriedade de um complexo de apartamentos usasse uma ferramenta de IA que realizasse verificações de antecedentes para selecionar candidaturas de possíveis inquilinos, a ferramenta de IA poderia identificar erroneamente um candidato e considerá-lo um risco devido a uma baixa pontuação de crédito. O apartamento poderia ser negado a ele e ele perderia a taxa de inscrição.

**Como mitigar**: Avalie todo o conteúdo gerado por IA antes de incorporá-lo ao seu trabalho ou compartilhá-lo com alguém. Situações como a do exemplo podem ser evitadas com a verificação dupla dos resultados da IA em relação a outras fontes.

### Prejuízo à Qualidade do Serviço

Uma circunstância em que as ferramentas de IA não funcionam tão bem para determinados grupos de pessoas com base em sua identidade.

**Exemplo**: Quando a tecnologia de reconhecimento de fala foi desenvolvida pela primeira vez, os dados de treinamento não tinham muitos exemplos de padrões de fala exibidos por pessoas com deficiência, de modo que os dispositivos muitas vezes tinham dificuldades para analisar esse tipo de fala.

**Como mitigar**: Especifique a diversidade adicionando linguagem inclusiva ao seu prompt. Se uma ferramenta de IA generativa não considerar determinados grupos ou identidades, como pessoas com deficiência, resolva esse problema ao iterar o prompt.

### Danos à Representação

O reforço de uma ferramenta de IA da subordinação de grupos sociais com base em suas identidades.

**Exemplo**: Quando a tecnologia de tradução foi desenvolvida pela primeira vez, certos resultados apresentavam uma inclinação imprecisa para o masculino ou feminino. Por exemplo, ao gerar uma tradução para palavras como "nurse" (enfermeira) e "beautiful" (bonita), a tradução seria feminina. Quando palavras como "doctor" (médico) e "strong" (forte) eram usadas como entrada, a tradução ficava masculina.

**Como mitigar**: Questione as suposições. Se uma ferramenta de IA generativa fornecer uma resposta tendenciosa, por exemplo, com uma inclinação para o masculino ou feminino em seu resultado, identifique e resolva o problema ao iterar em seu prompt e peça à ferramenta para corrigir a tendência.

### Danos ao Sistema Social

Efeitos sociais em nível macro que ampliam as disparidades existentes de classe, poder ou privilégio, ou causam danos físicos, como resultado do desenvolvimento ou uso de ferramentas de IA.

**Exemplo**: Deepfakes indesejados, que são fotos ou vídeos falsos gerados por IA de pessoas reais dizendo ou fazendo coisas que elas não disseram ou fizeram, podem ser um exemplo de dano ao sistema social.

**Como mitigar**: Verifique os fatos e faça referências cruzadas dos resultados. Algumas ferramentas de IA generativa têm recursos que fornecem fontes de onde as informações foram encontradas. Também é possível verificar um resultado usando um mecanismo de busca para confirmar as informações ou pedindo ajuda a um especialista. A execução de um prompt em dois ou mais recursos ajuda a identificar possíveis resultados imprecisos.

### Danos Interpessoais

O uso da tecnologia para criar uma desvantagem para determinadas pessoas que afeta negativamente seus relacionamentos com os outros ou causa uma perda do senso de identidade e agência.

**Exemplo**: Se alguém pudesse assumir o controle de um dispositivo doméstico em seu apartamento anterior para pregar uma peça indesejada em seu antigo colega de quarto, essas ações poderiam resultar em uma perda do senso de identidade e agência da pessoa afetada pela peça.

**Como mitigar**: Considere os efeitos do uso da IA e sempre use seu bom senso e suas habilidades de pensamento crítico. Pergunte a si mesmo se a IA é adequada ou não para a tarefa em que está trabalhando. Como qualquer tecnologia, a IA pode ser tanto benéfica quanto prejudicial, dependendo de como é usada. Em última análise, é responsabilidade do usuário certificar-se de que não causará danos ao usar a IA.

## Desvio Versus Corte de Conhecimento

![Metáfora visual para o desvio de IA](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/SEkW1KvWTVuwhmV67prTTw_c50a47d412d049d289827be29e8fa1f1_maze.png?expiry=1744329600000&hmac=Ql2M9GIFRwLN6SU-05ind5SGL1XNCJyathCGFuUe6Z0)

Outro fenômeno que pode causar resultados injustos ou imprecisos é a **deriva**. Drift é o declínio na precisão das previsões de um modelo de IA devido a mudanças ao longo do tempo que não se refletem nos dados de treinamento. Isso é comumente causado pelo **corte de conhecimento**, o conceito de que um modelo é treinado em um ponto específico no tempo e, portanto, não tem nenhum conhecimento de eventos ou informações após essa data.

**Exemplo**: Um designer de moda pode querer acompanhar as tendências de gastos antes de criar uma nova coleção. Se ele usar um modelo que foi treinado pela última vez com base nas tendências da moda e nos hábitos de consumo de 2015, o modelo poderá não produzir resultados úteis porque esses dois fatores provavelmente mudaram com o tempo. É muito provável que as preferências dos consumidores em 2015 sejam diferentes das tendências atuais. Em outras palavras, as previsões do modelo passaram de precisas no momento do treinamento para menos precisas nos dias de hoje devido, em parte, ao corte de conhecimento do modelo.

Vários outros fatores podem causar desvios, tornando um modelo de IA menos confiável. **Viéses de novos dados** podem contribuir para a deriva. Mudanças na maneira como as pessoas se comportam e usam a tecnologia, ou mesmo grandes eventos no mundo, podem afetar um modelo, tornando-o menos confiável. Para manter um modelo de IA funcionando bem, é importante monitorar regularmente seu desempenho e lidar com os pontos de corte de conhecimento usando uma abordagem humana no circuito.