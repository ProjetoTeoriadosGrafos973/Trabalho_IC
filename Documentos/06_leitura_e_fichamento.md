# Etapa 6 Leitura e fichamento

## Identificação do artigo - Artigo 1

- Referência completa: `[HINZ, Mauro; MIERS, Charles C.; PILLON, Maurício A.; KOSLOVSKI, Guilherme P.. Um Modelo de Custo para Nuvens IaaS baseado no Consumo de Energia de Máquinas Virtuais. In: SIMPÓSIO BRASILEIRO DE SISTEMAS DE INFORMAÇÃO (SBSI), 12., 2016, Florianópolis. Anais [...]. Porto Alegre: Sociedade Brasileira de Computação, 2016. p. 136-143. ISSN 3086-4836.]`
- DOI ou URL: `[https://doi.org/10.5753/sbsi.2016.5955]`
- Base de origem: `[SBC Open Library]`
- Leitor responsável: `[Gabrielle Carmo]`
- Data da leitura: `[09/10/2026]`

## Fichamento

### Problema investigado

`[O artigo trata da dificuldade de medir e cobrar pelo gasto de energia de máquinas virtuais em ambientes de nuvem IaaS. Em geral, os modelos de cobrança focam só no uso de recursos como CPU e memória, mas não mostram quanto de energia cada VM realmente consome, o que dificulta criar estratégias para economizar energia nos data centers.]`

### Objetivo do estudo

`[O objetivo dos autores é criar um modelo de custo para nuvens IaaS que consiga estimar o consumo de energia de cada máquina virtual de forma individual. Com isso, eles querem ajudar tanto na gestão dos custos quanto no desenvolvimento de estratégias mais eficientes para reduzir o consumo de eletricidade.]`

### Método utilizado

`[Os autores montaram um modelo analítico que relaciona o uso dos recursos físicos do servidor com o comportamento e o tempo de execução de cada VM. Eles analisaram como a carga de trabalho de uma máquina virtual se traduz no gasto real de energia do servidor onde ela está alocada.]`

### Contexto, amostra ou dados

`[O estudo se passa no contexto da eficiência energética em computação em nuvem, mais especificamente em infraestrutura como serviço (IaaS). Para testar e validar a ideia, eles usaram cenários com máquinas virtuais rodando em servidores e mediram o consumo com base na intensidade do uso desses servidores.]`

### Principais resultados

`[O trabalho mostra que dá sim para associar o consumo de energia diretamente ao uso que cada máquina virtual faz dos recursos do servidor. O modelo proposto conseguiu mapear essa relação de forma mais justa e precisa, servindo como uma ferramenta útil para evitar desperdícios e calcular melhor os custos de operação.]`

### Limitações apresentadas

`[O artigo deixa transparecer que medir esse consumo em tempo real em data centers muito grandes e com hardwares variados ainda é um desafio. Além disso, por se basear em um modelo analítico, a aplicação em ambientes reais com cargas de trabalho mutáveis e imprevisíveis exige ajustes e validações mais complexas.]`

### Contribuição para o nosso artigo

`[Esse artigo ajuda bastante a nossa pesquisa porque mostra exatamente como calcular e entender o gasto de energia de uma VM. Como o nosso tema envolve a complexidade e a eficiência energética dos algoritmos de alocação, entender esse modelo de consumo nos dá uma base bem sólida para avaliar se os algoritmos estão realmente alocando as VMs de forma eficiente e econômica.]`

### Comentário crítico

`[O grande ponto positivo do trabalho é conseguir isolar e medir o custo de energia de cada máquina virtual, algo que muitos sistemas de gestão ignoram. Por outro lado, como é um modelo mais analítico, seria interessante ver como ele se comporta em um data center comercial de grande escala com cargas muito oscilantes. Mesmo assim, é uma leitura muito boa para embasar a parte de métricas de energia do nosso trabalho.]`

### Citação literal opcional

> `[“O modelo proposto visa estimar o consumo de energia associado às máquinas virtuais, permitindo uma melhor contabilização dos custos em ambientes de nuvem IaaS.”]`

Página: `[136]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


## Identificação do artigo - Artigo 2

- Referência completa: `[AHUJA, Rohit; GARG, Sheetal; SINGH, Raman; PERL, Ivan. Effective Resource Management through VM Allocation in Cloud Data Center. In: INNOVATIONS IN SOFTWARE ENGINEERING CONFERENCE (ISEC), 18., 2025, New York. New York: Association for Computing Machinery, 2025. Article 6, p. 1–6.]`
- DOI ou URL: `[https://doi.org/10.1145/3717383.3717385]`
- Base de origem: `[ACM Digital Library]`
- Leitor responsável: `[Gabrielle Carmo]`
- Data da leitura: `[10/10/2026]`

## Fichamento

### Problema investigado

`[O artigo aborda a dificuldade de gerenciar os recursos de forma eficiente em data centers na nuvem quando as máquinas virtuais são alocadas sem um planejamento adequado. O problema central é que a má distribuição das VMs gera desperdício de capacidade de hardware, prejudica o desempenho geral do sistema e eleva o consumo de energia dos servidores físicos.]`

### Objetivo do estudo

`[O objetivo dos autores é analisar e propor estratégias eficazes de gerenciamento de recursos focadas na alocação de máquinas virtuais, buscando melhorar a eficiência operacional dos data centers e otimizar o uso da infraestrutura computacional disponível.]`

### Método utilizado

`[Os autores exploraram e avaliaram abordagens voltadas à gestão e alocação de VMs, investigando diferentes políticas de distribuição de cargas de trabalho entre os servidores físicos para entender como otimizar o uso dos recursos e o desempenho global do ambiente de nuvem.]`

### Contexto, amostra ou dados

`[O estudo se insere no contexto de ambientes de computação em nuvem e data centers, onde a escalabilidade e a distribuição inteligente de recursos são essenciais. O trabalho analisa cenários de alocação de VMs para verificar o comportamento do sistema diante de diferentes demandas de processamento e restrições de infraestrutura.]`

### Principais resultados

`[Os resultados indicam que uma alocação bem estruturada de máquinas virtuais melhora de forma significativa o aproveitamento dos recursos dos servidores e reduz ineficiências operacionais. O estudo demonstra que planejar onde cada VM será colocada impacta diretamente na performance do data center e no controle do consumo energético.]`

### Limitações apresentadas

`[O trabalho aponta que equilibrar múltiplos objetivos simultaneamente — como alto desempenho, garantia de qualidade de serviço (QoS) e baixo consumo de energia — continua sendo um desafio complexo. Além disso, a adaptabilidade das políticas de alocação em cenários altamente dinâmicos e imprevisíveis ainda precisa de melhorias contínuas.]`

### Contribuição para o nosso artigo

`[Este artigo é de grande valia para a nossa pesquisa porque reforça a importância de otimizar a alocação de VMs para alcançar uma gestão de recursos eficiente. Como o nosso foco envolve a complexidade e a eficiência energética, o estudo ajuda a fundamentar como a escolha de boas estratégias de alocação reflete diretamente na economia de energia e na melhor utilização do data center.]`

### Comentário crítico

`[O ponto forte do artigo é trazer uma visão atualizada sobre os desafios de gerenciar recursos em nuvem, destacando a importância de otimizar a alocação de VMs. Como ponto de atenção, nota-se que o estudo poderia detalhar ainda mais o impacto computacional e a complexidade de execução das abordagens propostas. No entanto, é uma leitura excelente para amparar a discussão sobre a eficiência de algoritmos de alocação.]`

### Citação literal opcional

> `[“O gerenciamento eficaz de recursos por meio da alocação de VMs é crucial para otimizar o desempenho do data center em nuvem e a eficiência energética.”]`

Página: `[1]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


## Identificação do artigo - Artigo 3

- Referência completa: `[ATMAJA, Subhanjaya Angga; EMANUEL, Andi Wahju Rahardjo; SUYOTO. A Systematic Literature Review on Intelligent Optimization for Virtual Machine Allocation in Cloud Data Centers. In: INTERNATIONAL CONFERENCE ON COMPUTER SCIENCE AND INFORMATION TECHNOLOGY (ICCSIT), 18., 2025, New York. New York: Association for Computing Machinery, 2026. p. 58–68.]`
- DOI ou URL: `[https://doi.org/10.1145/3783862.3783871]`
- Base de origem: `[ACM Digital Library]`
- Leitor responsável: `[Maria Beatriz]`
- Data da leitura: `[08/10/2026]`

## Fichamento

### Problema investigado

`[O estudo investiga as técnicas de alocação de Máquinas Virtuais em data centers, que acabam impactando diretamente a utilização de recursos e a eficiência energética.]`

### Objetivo do estudo

`[O estudo tem como objetivo realizar uma Revisão da Literatura para analisar e avaliar técnicas de otimização inteligente para alocação de máquinas virtuais (VMs) em data centers em nuvem. Com base no escopo do estudo, os objetivos da pesquisa são: Analisar as características dos estudos selecionados, incluindo a distribuição do ano de publicação, o tipo de publicação e os métodos de pesquisa utilizados na otimização da alocação de memória virtual; Classificar e comparar os tipos de algoritmos usados na alocação de máquinas virtuais, como modelos de aprendizado de máquina; Avaliar as principais métricas de desempenho na otimização da alocação de máquinas virtuais, com foco em eficiência energética, utilização de recursos, conformidade e custo-benefício.]`

### Método utilizado

`[Metodologia de Revisão Sistemática da Literatura (RSL) para identificar, avaliar e sintetizar sistematicamente as pesquisas existentes sobre otimização inteligente para alocação de máquinas virtuais (VMs) em data centers de nuvem. Também foi realizada uma busca em diversas bases de dados eletrônicas, incluindo IEEE Xplore, ACM Digital Library, ScienceDirect, SpringerLink e Google Scholar, utilizando palavras-chave predefinidas como "alocação de máquinas virtuais", "otimização inteligente", "gerenciamento de recursos de computação em nuvem".]`

### Contexto, amostra ou dados

`[Foi utilizada uma análise que identificou alguns tópicos como eficiência energética, balanceamento de carga. O foco principal da pesquisa abrange a eficiência do consumo de energia, a alocação de VMs baseada em desempenho, a redução da latência e a melhoria da utilização de recursos.]`

### Principais resultados

`[Os principais resultados que o estudo obteve demonstram que os algoritmos baseados em aprendizado de máquina e modelos matemáticos são as abordagens mais frequentemente utilizadas, representando 25% dos estudos selecionados cada. Técnicas de aprendizado de máquina focam principalmente na previsão da demanda de recursos e na otimização da previsão de carga de trabalho para melhorar a eficiência energética. Métodos de otimização meta-heurística (20%) são amplamente utilizados para aprimorar a eficiência energética, otimizar o posicionamento de máquinas virtuais e reduzir violações de SLA. Também revela que a integração do aprendizado por reforço e de métodos híbridos representa uma direção de pesquisa crescente que pode levar a mecanismos de alocação de máquinas virtuais mais autônomos, escaláveis e energeticamente eficientes em ambientes de nuvem.]`

### Limitações apresentadas

`[Uma das principais limitações do estudo é a falta de padronização nas métricas de avaliação, dificultando a comparação de diferentes abordagens de otimização. Além disso, há a falta de transparência nos modelos de IA, dificultando a compreensão e a confiança na aplicação dos mesmos.]`

### Contribuição para o nosso artigo

`[Esse estudo nos ajuda a identificar os diferentes tipos de algoritmos de alocação de máquinas virtuais e como podemos comparar diferentes métricas de desempenho para análise e estudo. Além disso, permite reconhecer possíveis limitações que podem ocorrer durante o desenvolvimento do artigo.]`

### Comentário crítico

`[O estudo demonstrou ser um grande aliado para o desenvolvimento deste trabalho, uma vez que se trata de uma revisão de literatura, abordagem que também corresponde ao nosso objetivo. Além de analisar os possíveis algoritmos utilizados na implantação de máquinas virtuais (VM) em data centers, o artigo apresentou como outros pesquisadores buscaram compreender a eficiência desses algoritmos e as formas de estruturar sua aplicação para obter melhores resultados.]`

### Citação literal opcional

> `["Traditional VM allocation methods, such as rule-based heuristics and static resource provisioning, have long been used to manage resource allocation in cloud data centers. These approaches, while simple and computationally inexpensive, often struggle to adapt to dynamic workload fluctuations, heterogeneous resource demands, and varying Quality of Service (QoS) requirements."]`

Página: `[59]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


## Identificação do artigo - Artigo 4

- Referência completa: `[RJEIB, Hasanein D.; KECSKEMETI, Gabor. VMP-ER: An Efficient Virtual Machine Placement Algorithm for Energy and Resources Optimization in Cloud Data Center. Algorithms, Basel, v. 17, n. 7, art. 295, 2024.]`
- DOI ou URL: `[https://doi.org/10.3390/a17070295]`
- Base de origem: `[MDPI]`
- Leitor responsável: `[Gabriel Santos da Silva]`
- Data da leitura: `[08/10/2026]`

## Fichamento

### Problema investigado

`[O artigo investiga o problema de posicionamento de máquinas virtuais (VMP, do inglês Virtual Machine Placement) em data centers de nuvem, ou seja, decidir em qual máquina física (PM) cada VM será hospedada. Esse problema é difícil porque os servidores são heterogêneos, os recursos são multidimensionais (CPU, memória etc.) e o ambiente tem grande escala. Uma escolha ruim aumenta o consumo de energia, o desperdício de recursos e as violações de SLA. Os autores tratam o VMP como um problema de bin-packing multiobjetivo, em que as VMs são os itens e os servidores são as caixas, e o objetivo é usar o menor número possível de servidores ligados.]`

### Objetivo do estudo

`[Propor um algoritmo chamado VMP-ER, que reduz o consumo de energia, violações de SLA e o desperdício de recursos ao diminuir o número de PMs ligadas, dar prioridade aos servidores mais eficientes em energia e equilibrar o uso de CPU e memória em cada servidor. Em seguida, comparar o desempenho do VMP-ER com os algoritmos EEVMP e LBMBP.]`

### Método utilizado

`[Os autores propõem uma heurística gulosa, parecida com o Best Fit Decreasing. Primeiro as VMs são ordenadas por demanda de CPU, da maior para a menor. Depois, para cada VM, o algoritmo avalia os servidores ativos que têm recursos suficientes e escolhe o que maximiza uma função de eficiência energética Ee(h). Essa função combina a eficiência de potência do servidor (MIPS por watt), o fator de uso de recursos (1 − Rw), que mede o equilíbrio entre CPU e RAM livres, e o aumento esperado de consumo de energia e de violação de SLA ao hospedar a VM. Se nenhum servidor ativo comporta a VM, o algoritmo liga o servidor inativo com melhor Ee. O modelo de potência é linear em função do uso de CPU. Sobre a complexidade, o artigo informa O(n log n + nm), que se simplifica para O(n²) supondo que existam menos PMs do que VMs. A avaliação foi feita por simulação, com programação em Java.]`

### Contexto, amostra ou dados

`[O estudo simulou um data center heterogêneo com dois tipos de servidores Lenovo (ThinkSystem SD535 V3 e SR850 V3) e cinco tipos de VMs inspirados nas instâncias m5 da Amazon EC2 (de large a 8xlarge), todas com um único núcleo de CPU. Os dados de carga vieram do trace real do PlanetLab. Foram testados cenários de 10 a 200 VMs, e as métricas avaliadas foram número de PMs ativas, consumo de energia (kWh) e desperdício médio de recursos (%). Não houve coleta de dados primários em um ambiente real de nuvem.]`

### Principais resultados

`[O VMP-ER usou menos PMs ativas do que o EEVMP e o LBMBP, e a diferença aumentou com o número de VMs. Com cerca de 200 VMs, o gráfico mostra algo em torno de 90 PMs para o VMP-ER, contra cerca de 96 do LBMBP e 105 do EEVMP. Com poucas VMs o desempenho dos três foi parecido. O consumo de energia também foi menor no VMP-ER: com 200 VMs, ficou perto de 260 kWh, contra cerca de 285 kWh do LBMBP e 310 kWh do EEVMP. Quanto ao desperdício de recursos, o EEVMP piorou com o aumento de VMs, chegando a cerca de 44%. O VMP-ER e o LBMBP ficaram bem mais baixos, e o VMP-ER terminou melhor, com cerca de 18% contra cerca de 19,5% do LBMBP. Com poucas VMs, o LBMBP teve desperdício menor que o VMP-ER. Os autores atribuem os ganhos ao fato de considerar o equilíbrio entre CPU e RAM e de evitar migrações desnecessárias.]`

### Limitações apresentadas

`[Os próprios autores indicam como trabalhos futuros: tratar a seleção de VMs quando uma PM fica sobrecarregada, incluir outros recursos (rede e disco, que não entram no modelo atual, apenas CPU e RAM) e avaliar a proposta em um ambiente de nuvem real, já que os testes foram só simulados. Também há a limitação de que, na comparação com o LBMBP, só foi considerada a fase de posicionamento inicial, sem a fase de migração desse algoritmo.]`

### Contribuição para o nosso artigo

`[O artigo ajuda no nosso tema porque mostra um algoritmo de alocação de VMs modelado como bin-packing, problema NP-difícil resolvido na prática por heurísticas, e apresenta a análise de complexidade do algoritmo (O(n²)), o que conecta com a parte de complexidade do nosso trabalho. Também traz uma revisão de vários algoritmos de VMP, com uma tabela comparando recursos considerados e métricas usadas, e um modelo de potência e de desperdício de recursos que podemos citar ao comparar a eficiência energética das abordagens. Os resultados contra EEVMP e LBMBP servem como exemplo concreto do trade-off entre energia, desperdício de recursos e SLA.]`

### Comentário crítico

`[Forças: O artigo explica bem o problema e usa um exemplo numérico que ajuda a entender a função Ee. A proposta considera juntos eficiência de potência, equilíbrio entre CPU e RAM e SLA, e os ganhos aparecem de forma consistente quando o número de VMs cresce. Fragilidades: A avaliação é apenas simulada, com poucos tipos de servidores e VMs, e só compara dois algoritmos (para o LBMBP, só a fase inicial). O artigo diz reduzir violações de SLA, mas o SLA não é medido nos experimentos. Concordâncias: Concordamos que olhar só a energia não basta e que tratar o problema como bin-packing com uma heurística é coerente para grandes escalas.]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


## Identificação do artigo - Artigo 5

- Referência completa: `[TAN, Mingzhe; CHI, Ce; ZHANG, Jiahao; ZHAO, Shichang; LI, Guangli; LÜ, Shuai. An Energy-aware Virtual Machine Placement Algorithm in Cloud Data Center. In: INTERNATIONAL CONFERENCE ON INTELLIGENT INFORMATION PROCESSING (ICIIP), 2., 2017, New York. New York: Association for Computing Machinery, 2017. Article 1, p. 1–9.]`
- DOI ou URL: `[https://doi.org/10.1145/3144789.3144792]`
- Base de origem: `[ACM Digital Library]`
- Leitor responsável: `[Enrico Ricardo]`
- Data da leitura: `[10/10/2026]`

## Fichamento

### Problema investigado

`[O artigo aborda o alto consumo de energia em data centers de nuvem, causado principalmente pela alocação ineficiente de máquinas virtuais (VMs) nos servidores físicos. Quando as VMs não são bem distribuídas, servidores ociosos ou subutilizados continuam consumindo muita energia, gerando desperdício e custos operacionais elevados.]`

### Objetivo do estudo

`[Propor um algoritmo de posicionamento de máquinas virtuais (Virtual Machine Placement) com foco na eficiência energética, objetivando minimizar a quantidade de servidores físicos ativos e reduzir o consumo elétrico total do data center, sem comprometer os acordos de nível de serviço (SLA).]`

### Método utilizado

`[Os autores propõem uma abordagem heurística focada em otimizar o processo de alocação. O algoritmo avalia os requisitos de capacidade (como CPU e memória) e busca empacotar as VMs no menor número possível de servidores físicos, permitindo que máquinas ociosas sejam desligadas ou colocadas em estado de economia (sleep mode).]`

### Contexto, amostra ou dados

`[O estudo concentra-se no gerenciamento de infraestrutura em nuvem (IaaS). A validação metodológica baseia-se em simulações computacionais, testando diferentes padrões de carga de trabalho para mensurar a redução no consumo de energia frente às métricas de desempenho dos servidores.]`

### Principais resultados

`[O algoritmo de posicionamento proposto demonstra ser capaz de reduzir o consumo de energia de forma considerável quando comparado a métodos tradicionais (como algoritmos First-Fit). Isso é alcançado pela consolidação eficaz das VMs, que diminui o número de servidores ativos simultaneamente e otimiza o uso do hardware.]`

### Limitações apresentadas

`[A principal limitação desse tipo de abordagem reside no fato de que avaliações via simulação podem não capturar por completo a volatilidade, a latência de rede e os picos repentinos de demanda característicos de um data center comercial em larga escala. Adicionalmente, o balanceamento preciso entre economia de energia e garantia de desempenho exige validações práticas contínuas.]`

### Contribuição para o nosso artigo

`[A pesquisa é relevante para o nosso trabalho, pois fornece uma base consolidada sobre a utilização de algoritmos para resolver problemas de alocação de VMs voltados à economia de energia. O texto auxilia na compreensão da relação direta entre o planejamento algorítmico (e sua complexidade) com a eficiência energética das infraestruturas de nuvem.]`

### Comentário crítico

`[O trabalho acerta em tratar a modelagem do posicionamento das VMs como um problema de empacotamento, utilizando uma solução heurística para mitigar um dos maiores custos da nuvem atual: o gasto energético. No entanto, a falta de experimentos com um cluster físico real impede que se meça com precisão o overhead gerado pela própria execução do algoritmo em um ambiente de produção.]`

### Citação literal opcional

> `["Virtual machine placement optimization is a key strategy to solve the energy consumption of cloud computing data centers and improve resource utilization."]`

Página: `[1]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


# Etapa 6 Leitura e fichamento - Artigo 6

## Identificação do artigo

- Referência completa: `[AJMERA, Kashav; TEWARI, Tribhuwan Kumar; SINGH, Vivek Kumar; VIKASH; UPADHYAY, Pawan Kumar. Energy-Aware Dynamic Virtual Machine Scheduling in Cloud Computing: A Survey. In: Proceedings of the 2023 Fifteenth International Conference on Contemporary Computing (IC3-2023). Association for Computing Machinery, New York, NY, USA, 133–141.]`
- DOI ou URL: `[https://dl.acm.org/doi/10.1145/3607947.3607970]`
- Base de origem: `[ACM Digital Library]`
- Leitor responsável: `[Gustavo de Faria]`
- Data da leitura: `[09/10/2026]`

## Fichamento

### Problema investigado

`[O desafio de realizar agendamento dinâmico de máquinas virtuais (VMs) em data centers de computação em nuvem, equilibrando utilização de recursos, consumo de energia e cumprimento de SLAs diante de cargas de trabalho altamente variáveis.]`

### Objetivo do estudo

`[Comparar e revisar técnicas de ponta para agendamento dinâmico de VMs com consciência energética, identificando pontos fortes e fracos das abordagens existentes e fornecendo insights para algoritmos mais eficientes e sustentáveis.]`

### Método utilizado

`[Foi conduzida uma revisão sistemática e comparativa de algoritmos e estratégias de agendamento de VMs, analisando critérios como função objetivo, técnica de agendamento, estratégias de posicionamento e seleção de VMs, além de métodos de detecção de sobrecarga e subcarga.]`

### Contexto, amostra ou dados

`[O estudo se baseia em data centers de nuvem que utilizam virtualização para consolidar recursos. A análise considera diferentes algoritmos publicados na literatura, sem coleta de dados primários, mas com foco em comparação teórica e experimental de técnicas existentes.]`

### Principais resultados

`[O agendamento dinâmico é essencial para reduzir consumo de energia e melhorar eficiência. Técnicas variam em desempenho conforme o cenário de carga. Estratégias de detecção de sobrecarga e subcarga são críticas para evitar violações de SLA. A migração de VMs deve ser minimizada para reduzir custos e manter qualidade de serviço. Nenhuma técnica resolve todos os desafios; há trade-offs entre eficiência energética e desempenho.]`

### Limitações apresentadas

`[O problema é altamente complexo e não existe solução universal. A revisão mostra que muitos algoritmos funcionam bem em cenários específicos, mas não em ambientes heterogêneos e de larga escala. A necessidade de novas pesquisas é destacada para lidar com a crescente demanda e diversidade dos ambientes de nuvem modernos.]`

### Contribuição para o nosso artigo

`[O artigo trata explicitamente da eficiência energética no uso de máquinas virtuais em nuvem, abordando técnicas de agendamento dinâmico que buscam reduzir consumo de energia, otimizar utilização de recursos. Isso se conecta diretamente ao seu tema, pois fornece uma revisão abrangente das estratégias existentes e evidencia os trade-offs entre desempenho e sustentabilidade.]`

### Comentário crítico

`[Forças: O artigo apresenta uma visão sistemática das principais técnicas de agendamento dinâmico de VMs. Destaca a importância da detecção de sobrecarga e subcarga, pontos centrais para eficiência energética. Reforça a relevância da virtualização como ferramenta para consolidação de recursos e redução de desperdício. Fragilidades: A análise é predominantemente teórica e comparativa, sem aplicação prática em um ambiente real de larga escala. Não há proposta de um novo algoritmo, apenas revisão das abordagens existentes. Limitações quanto à heterogeneidade dos servidores e escalabilidade são reconhecidas, mas não solucionadas. Concordâncias: O artigo confirma que a eficiência energética é um desafio central na alocação de VMs, em linha com seu tema. Reconhece a complexidade do problema como combinatório e semelhante ao bin-packing, o que reforça a necessidade de algoritmos sofisticados.]`

### Citação literal opcional

> `["Dynamic virtual machine scheduling is a crucial research area in cloud computing to optimize resource utilization, reduce energy consumption, and ensuring performance and availability by dynamically managing and scheduling virtual machines (VMs) across servers."]`

Página: `[1]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


## Identificação do artigo - Artigo 7

- Referência completa: `[TLILI, Takwa; KRICHEN, Saoussen. Energy-aware metaheuristic for virtual machine placement towards a green cloud computing. In: GENETIC AND EVOLUTIONARY COMPUTATION CONFERENCE COMPANION (GECCO COMPANION), 2023, Lisbon. New York: Association for Computing Machinery, 2023. p. 779–782.]`
- DOI ou URL: `[https://doi.org/10.1145/3583133.3590740]`
- Base de origem: `[ACM Digital Library]`
- Leitor responsável: `[Gabriel Andrade]`
- Data da leitura: `[08/10/2026]`

## Fichamento

### Problema investigado

`[O trabalho foca no desafio do Posicionamento de Máquinas Virtuais (VMP) em servidores físicos dentro de data centers, equilibrando o consumo de energia e o uso de recursos. Por ser um problema complexo e NP-difícil, o desafio é alocar as VMs respeitando os limites de CPU, memória e disco dos servidores, com o objetivo de cortar o consumo elétrico e diminuir as emissões de CO2.]`

### Objetivo do estudo

`[Desenvolver uma meta-heurística focada em eficiência energética para o posicionamento de VMs. O algoritmo busca reduzir o gasto de energia e a pegada de carbono, sem deixar de atender às capacidades dos servidores e às demandas de execução das tarefas dos usuários.]`

### Método utilizado

`[As autoras criaram a Energy-Aware Metaheuristic (EAM), uma solução híbrida que combina Algoritmo Genético com a estratégia Best Fit Decreasing (BFD). A população inicial de soluções é gerada de forma aleatória no simulador CloudSim. A avaliação das soluções é feita por uma função de fitness focada em gastar o mínimo de energia. Além disso, o método usa o Algoritmo de Transferência Cíclica (Cyclic Transfer Algorithm — CTA) para otimizar as respostas.]`

### Contexto, amostra ou dados

`[A pesquisa se insere no cenário de Green Cloud Computing e otimização energética de data centers. Os testes foram rodados no simulador CloudSim, testando vários cenários com quantidades diferentes de servidores, VMs e cloudlets (as tarefas dos usuários). Nas configurações do experimento, usaram população de tamanho 30, cruzamento de ponto único, mutação baseada em BFD e parada por número de iterações.]`

### Principais resultados

`[Os testes trouxeram dados de consumo de energia para diferentes volumes de tarefas e infraestrutura. Na análise das cloudlets, o consumo subiu de 560,6 para 1.244,45 conforme o volume de tarefas aumentava de 300 para 2.000, mostrando claramente o impacto da carga de trabalho no gasto energético. O estudo prova a aplicação prática da EAM, embora o formato das tabelas não permita comprovar, sozinho, que ela é matematicamente superior a outros métodos.]`

### Limitações apresentadas

`[O artigo não apresenta uma seção específica sobre as limitações do estudo. Porém, uma limitação que podemos observar é que os testes foram realizados por meio de simulações no CloudSim, sem demonstrar como o algoritmo se comportaria em um data center real. Além disso, os resultados apresentados não trazem uma comparação quantitativa detalhada com outros algoritmos, o que dificulta avaliar o quanto a EAM consegue melhorar o desempenho em relação a outras soluções.]`

### Contribuição para o nosso artigo

`[O artigo contribui para nossa pesquisa por mostrar como diferentes técnicas podem ser combinadas para distribuir máquinas virtuais entre os servidores de um data center, buscando reduzir o consumo de energia. As autoras utilizam um algoritmo genético junto com o método Best Fit Decreasing, mostrando uma alternativa para resolver um problema considerado NP-difícil. Além disso, o estudo destaca que é importante avaliar não apenas o consumo energético, mas também o tempo de execução e o cumprimento dos acordos de nível de serviço (SLA).]`

### Comentário crítico

`[O ponto forte do artigo é integrar otimização com foco em energia sem ignorar as limitações de recursos e a execução das tarefas. O CloudSim ajuda a manter os testes bem controlados. No entanto, a falta de uma comparação quantitativa direta e detalhada contra outros algoritmos deixa em aberto o quanto a EAM realmente ganha das alternativas. Além disso, apesar de mencionar a complexidade NP-difícil, faltou uma análise mais profunda do tempo de execução da própria proposta.]`

### Citação literal opcional

> `[“Our aim is to reduce the energy consumption and CO2 emission under a set of constraints.”]`

Página: `[779]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.


---


## Identificação do artigo - Artigo 8

- Referência completa: `[TAN, Chun; ZHANG, Jin; LIU, Xianfeng; ZHOU, Zhou; SHEN, Xiuhong. Survey of Virtual Machine Deployment Algorithms in Cloud Data Center. In: INTERNATIONAL CONFERENCE ON FRONTIERS OF ELECTRONICS, INFORMATION AND COMPUTATION TECHNOLOGIES (ICFEICT), 2021, New York. Proceedings [...]. New York: Association for Computing Machinery, 2022. Article 126, p. 1–7.]`
- DOI ou URL: `[https://doi.org/10.1145/3474198.3478183]`
- Base de origem: `[ACM Digital Library]`
- Leitor responsável: `[Gabriel Andrade]`
- Data da leitura: `[08/10/2026]`

## Fichamento

### Problema investigado

`[O artigo aborda o problema da utilização inadequada dos recursos em centros de dados que oferecem serviços de computação em nuvem. Quando os recursos dos servidores não são bem distribuídos, pode ocorrer desperdício de capacidade, aumento do consumo de energia e elevação dos custos operacionais.]`

### Objetivo do estudo

`[O objetivo do estudo é analisar e organizar os principais algoritmos utilizados para distribuir máquinas virtuais em centros de dados na nuvem. Os autores procuram classificar essas soluções de acordo com seus objetivos de otimização e os tipos de algoritmos utilizados, destacando estratégias para reduzir custos, economizar energia, melhorar o desempenho e manter a qualidade dos serviços.]`

### Método utilizado

`[Os autores realizaram um estudo de revisão da literatura, analisando pesquisas anteriores sobre a implantação de máquinas virtuais em ambientes de computação em nuvem. O trabalho compara diferentes estratégias e organiza os algoritmos em categorias, considerando tanto os objetivos que eles procuram alcançar quanto suas características de funcionamento.]`

### Contexto, amostra ou dados

`[O estudo está relacionado aos centros de dados que utilizam computação em nuvem e virtualização para executar aplicações e distribuir recursos computacionais. Como se trata de uma revisão bibliográfica, os autores não trabalham com uma amostra de participantes, mas com pesquisas já publicadas sobre o tema. O artigo apresenta referências a trabalhos anteriores que investigam diferentes estratégias de implantação de máquinas virtuais, incluindo métodos voltados à economia de energia, à redução de custos, ao balanceamento de carga e à qualidade dos serviços.]`

### Principais resultados

`[O estudo mostra que existem diferentes algoritmos capazes de melhorar a distribuição de máquinas virtuais, mas cada um apresenta vantagens de acordo com o objetivo desejado. Algumas estratégias priorizam a redução do consumo de energia, enquanto outras buscam diminuir custos, melhorar o desempenho ou evitar falhas no cumprimento dos acordos de nível de serviço (SLA).]`

### Limitações apresentadas

`[Os autores apontam que a confiabilidade e a tolerância a falhas das máquinas virtuais ainda não recebem a atenção necessária em parte das pesquisas analisadas. Também destacam a falta de métodos de validação e dados padronizados para avaliar as soluções propostas. Essa falta de padronização aparece nas diferenças entre os conjuntos de dados utilizados nos experimentos, nas características das cargas de trabalho das máquinas virtuais e nos objetivos de otimização escolhidos, dificultando uma comparação mais consistente entre os resultados dos diferentes estudos.]`

### Contribuição para o nosso artigo

`[Esse estudo contribui para o nosso artigo porque apresenta diferentes algoritmos usados para distribuir máquinas virtuais nos data centers e mostra como eles podem ajudar a melhorar o uso dos recursos e reduzir o consumo de energia. A partir dele, conseguimos entender que escolher um algoritmo não envolve apenas buscar economia de energia, mas também considerar o desempenho dos servidores e os custos envolvidos. Isso se relaciona diretamente com o nosso tema, pois queremos entender como a complexidade dos algoritmos pode influenciar sua eficiência energética.]`

### Comentário crítico

`[Um ponto positivo do artigo é a maneira como os autores organizam diferentes pesquisas e apresentam os objetivos e as características dos algoritmos, facilitando a compreensão de um assunto que pode parecer complexo para quem está começando a estudar computação em nuvem. Por outro lado, por ser uma revisão da literatura, o trabalho não apresenta um experimento próprio que permita verificar, na prática, qual algoritmo apresenta o melhor resultado em uma situação específica. Além disso, a variedade de métodos e critérios utilizados nas pesquisas analisadas dificulta estabelecer uma comparação direta entre eles. Na minha avaliação, a principal contribuição do artigo é mostrar que não existe uma única solução ideal para todos os cenários, pois a escolha de um algoritmo depende das necessidades de cada ambiente e do equilíbrio entre desempenho, consumo de energia, custos e confiabilidade.]`

### Citação literal opcional

> `["Virtual machine deployment is one of the effective ways to solve the energy consumption of cloud computing data centers and improve the utilization of hardware resources."]`

Página: `[1]`

## Checklist

- [X] O artigo foi lido além do resumo.
- [X] O método e os resultados foram identificados.
- [X] As limitações foram registradas.
- [X] A conexão com o tema foi explicada.
- [X] Toda citação literal contém página.