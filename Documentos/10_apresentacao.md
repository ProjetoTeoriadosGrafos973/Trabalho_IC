# Etapa 10 Preparação da apresentação

## Dados da apresentação

- Título do artigo: `ALGORITMOS DE BAIXA COMPLEXIDADE E A OTIMIZAÇÃO DE MÁQUINAS VIRTUAIS: IMPACTOS NUMÉRICOS E REDUÇÃO DE CO2 E DATA CENTERS`
- Evento ou disciplina: `Computabilidade e Complexidade de Algoritmos`
- Data: `26/10/2026`
- Tempo disponível: `25 min`
- Integrantes: `Enrico Ricardo de Souza Prado, Gabriel Andrade de Faria, Gabriel Santos da Silva, Gabrielle dos Santos Carmo, Gustavo de Faria, Maria Beatriz Santos Carvalho`

## Estrutura

| Parte | Conteúdo principal | Responsável | Tempo |
|---|---|---|---:|
| Abertura | `Contextualização do crescimento do consumo energético em data centers e a problemática do alto consumo em estado ocioso` | `Enrico Ricardo` | `3 min` |
| Objetivos | `Apresentação do problema de pesquisa e do objetivo geral: analisar o equilíbrio entre a complexidade computacional e a eficiência energética na alocação de VMs` | `Gabrielle dos Santos` | `5 min` |
| Metodologia | `Processo de revisão bibliográfica nas bases SBC, ACM Digital Library, IEEE Xplore e Academia.edu` | `Gabriel Santos` | `5 min` |
| Resultados da revisão | `modelos de potência e consumo ocioso (Eixo 1); bin-packing, complexidade $O(n^2)$ e o trade-off entre heurísticas gulosas (BFD, VMP-ER) e meta-heurísticas (GA, ACO) (Eixo 2)` | `Maria Beatriz` | `7 min` |
| Conclusão | `Resposta ao problema de pesquisa, implicações práticas e necessidade de testes em ambientes físicos` | `Gustavo de Faria` | `5 min` |

## Mensagem principal

``Heurísticas gulosas de baixa complexidade ($O(n^2)$) são a solução mais eficiente para alocação de VMs em tempo real. Elas garantem rápida tomada de decisão e desligam servidores ociosos — responsáveis por até 70% do desperdício de energia —, reduzindo emissões de CO₂ sem o alto custo computacional de meta-heurísticas.``

## Perguntas esperadas

1. Pergunta: `Por que utilizar heurísticas $O(n^2)$ em vez de meta-heurísticas como Algoritmos Genéticos (GA)?`  
   Resposta: `Em data centers dinâmicos, meta-heurísticas demoram para convergir. Algoritmos $O(n^2)$ tomam decisões instantâneas e entregam um nível de consolidação energética muito próximo do ideal.`
2. Pergunta: `Como a consolidação de VMs resulta em redução direta de CO₂?`  
   Resposta: `Um servidor ligado em repouso consome cerca de 70% de sua energia máxima. Ao concentrar as VMs e desligar os servidores físicos ociosos, reduz-se o consumo em kWh e a pegada de carbono da matriz elétrica.`
3. Pergunta: `Qual foi a principal limitação do trabalho e o próximo passo?`  
   Resposta: `O estudo baseou-se em revisão bibliográfica. O próximo passo é validar esses algoritmos em um testbed físico com hardware heterogêneo e fluxo de carga real.`

## Checklist

- [X] A apresentação respeita o tempo.
- [X] Os slides possuem pouco texto e boa legibilidade.
- [X] As fontes das imagens e dados foram informadas.
- [X] Todos conhecem o problema, o método e as conclusões.
- [X] O grupo realizou pelo menos um ensaio completo.
- [X] Os integrantes estão preparados para responder perguntas.
