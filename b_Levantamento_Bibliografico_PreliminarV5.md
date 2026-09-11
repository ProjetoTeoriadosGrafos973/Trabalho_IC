# Etapa (b) — Levantamento Bibliográfico

> **Como preencher:** este documento deve ser preenchido **em conjunto pelo grupo**, mas com registro individualizado da contribuição de cada integrante em cada passo. Substitua os campos entre `[ ]` pelas informações do seu grupo. Não apague as instruções em itálico — elas ajudam na avaliação do orientador.

---

## 1. Identificação do Grupo

| Campo | Informação |
|---|---|
| Curso / Disciplina | `Ciência da Computação / Computabilidade e Complexidade de Algoritmos` |
| Projeto de Pesquisa / IC | `Para revisão bibliográfica` |
| Orientador(a) | `Andrea Ono Sakai` |
| Data de entrega desta etapa | `12/09/2026` |
| Integrantes do grupo | `Enrico Ricardo de Souza Prado, Gabriel Andrade de Faria, Gabriel Santos da Silva, Gabrielle dos Santos Carmo, Gustavo de Faria, Maria Beatriz Santos Carvalho` |
| Tema (da etapa "a") | `Complexidade e eficiência energética de algoritmos de alocação de máquinas virtuais em data centers` |

---

## FASE 1 — Planejamento da Busca

### Passo 1 — Pergunta de pesquisa e palavras-chave

**1.1 Problema/pergunta de pesquisa (versão de trabalho)**
*Ainda não precisa ser a versão final (isso vem na etapa "c"), mas deve orientar a busca desta fase.*

> `Como a literatura relaciona a complexidade dos algoritmos de alocação de máquinas virtuais à eficiência energética de data centers?`

**1.2 Conceitos-chave e sinônimos**
*Liste os conceitos centrais da pergunta e seus sinônimos, em português e inglês.*

| Conceito-chave | Sinônimos / termos relacionados (PT) | Sinônimos / termos relacionados (EN) |
|---|---|---|
| `Complexidade` | `Complexidade de algoritmo/ Tempo de complexidade` | `Algorithmic complexity/ Time Complexity` |
| `Carbono` | `Pegada de Carbono` | `Carbon footprint` |
| `Máquina` | `Máquina Virtual` | `Virtual Machine` |
| `Eficiência` | `Eficiência Computacional/ Custo computacional` | `Computational Efficiency/ Computacional cost` |
| `Computação` | `Computação Verde` | `Green computing` |
| `Dados` | `Centro de dados/ Consolidação de Servidores` | `Data Center/ Server Consolidation` |

*Responsável por este passo: `Maria Beatriz/ Gustavo de Faria`*

---

### Passo 2 — Strings de busca

*Combine os termos do passo 1 com operadores booleanos (`AND`, `OR`, `NOT`). Use aspas para termos compostos e truncamento (`*`) quando a base permitir.*

| Nº | String de busca | Base(s) em que será usada | Elaborada por |
|---|---|---|---|
| 1 | `("Algorithmic complexity" OR "Time Complexity") AND ("Computational Efficiency" OR "Computational Cost")` | `SBC (Sociedade Brasileira de Computação)` | `Maria Beatriz` |
| 2 | `("Virtual Machine" OR "Virtual Machines") AND ("Energy Efficiency" OR "Energy Consumption")` | `ACM Digital Library` | `Enrico Ricardo` |
| 3 | `("Virtual Machine" OR "VM allocation") AND ("Data center" OR "Cloud computing")` | `ACM Digital Library` | `Gustavo de Faria` |

---

### Passo 3 — Bases de dados escolhidas

*Selecione de 2 a 4 bases relevantes ao tema. Registre a justificativa — isso vai para a seção de metodologia do artigo/relatório de IC.*

| Base de dados | Por que foi escolhida | Responsável pela busca nesta base |
|---|---|---|
| `SBC (Sociedade Brasileira de Computação)` | `Escolhemos essa base por que identificamos alguns artigos científicos brasileiros que apresentam relação direta com o tema da nossa Iniciação Científica` | `Maria Beatriz` |
| `ACM Digital Library` | `Base especializada em computação, com trabalhos relacionados a máquinas virtuais, computação em nuvem, data centers e eficiência energética.` | `Enrico Ricardo` |
| `ACM Digital Library` | `Escolhido com base no tema central de Virtualização de maquinas em data center com avaliação dos algoritimos e estrategias sugeridos First Fit, First Fit Decreasing, Best Fit, Best Fit Decreasing, base de dados para acesso de artigos e estudos em outras linguas` | ` Gustavo de Faria ` |

---

### Passo 4 — Critérios de inclusão e exclusão

**Critérios de inclusão:**
- `Artigos publicados nos últimos 5-12 anos`
- `Trabalhos relacionados à área de computação`
- `Português/inglês`
- `Disponíveis na íntegra`
- `Foco centralizado no tema`
- `Aprovação do Grupo`

**Critérios de exclusão:**
- `Artigos que ampliam o escopo definido para a pesquisa`
- `Trabalhos duplicados`
- `Artigos fora do escopo do tema`
- `Não revisados por pares`
- `Com um periodo maior que 12 anos de publicação`


*Definidos em conjunto por: `Maria Beatriz/ Gustavo de Faria / Gabriel S.`*

---

## FASE 2 — Execução da Busca e Triagem

### Passo 5 — Execução das buscas e registro dos resultados

*Anote quantos resultados cada string trouxe em cada base (útil para o fluxograma tipo PRISMA, se o projeto exigir). Exporte as referências (BibTeX, RIS, CSV) para um gerenciador de referências.*

| Base | String usada (nº) | Data da busca | Nº de resultados | Executada por |
|---|---|---|---|---|
| `ACADEMIA` | `1` | `30/05/2026` | `560` | `Maria Beatriz` |
| `ACM Digital Library` | `2` | `07/09/2026` | `1.505` | `Enrico Ricardo` |
| `ACM Digital Library` | `3` | `07/09/2026` | `6.035` | `Gustavo de Faria` |

**Total de resultados brutos (soma de todas as buscas):** `8.100`

**Gerenciador de referências utilizado:** `Zotero`
**Formato de exportação:** `BibTeX`

---

### Passo 6 — Triagem por título e resumo (1ª filtragem)

*Leia apenas título e resumo de cada resultado. Classifique: incluir / excluir / dúvida. Remova duplicatas entre bases.*

| Item de controle | Quantidade |
|---|---|
| Total de resultados antes da triagem | `48` |
| Duplicatas removidas | `7` |
| Classificados como "Incluir" | `25` |
| Classificados como "Excluir" | `5` |
| Classificados como "Dúvida" | `11` |

*A triagem detalhada, artigo por artigo, deve ser registrada na planilha de controle do projeto (aba "Triagem de Artigos"). Aqui, registre apenas o resumo quantitativo.*

**Como as dúvidas foram resolvidas?** *(ex.: discussão em grupo, consulta ao orientador)*
`Discussão em grupo (o tempo todo da elaboração estavamos discutindo o projeto de forma online e simultânea o que facilitou bastante)`

*Responsável(is) por esta triagem: `Gabrielle dos Santos Carmo`*

---

### Passo 7 — Triagem por leitura completa (2ª filtragem)

*Para os artigos que passaram na primeira filtragem, leia introdução e conclusão. Aplique os critérios de inclusão/exclusão (passo 4) de forma mais rigorosa.*

| Item de controle | Quantidade |
|---|---|
| Total de artigos que entraram nesta filtragem | `25` |
| Aprovados (conjunto definitivo para fichamento) | `20` |
| Excluídos nesta etapa | `5` |

**Principais motivos de exclusão nesta filtragem:**
- `Muitos artigos abordavam o mesmo tema, nós priorizamos os estudos mais adequados aos critérios de escolhas`
- `Temas muito abrangentes em relação ao escopo definido`
- `Publicação fora do período estabelecido`

*Responsável(is) por esta triagem: `Maria Beatriz`*

---

## 3. Lista Final de Artigos Selecionados (Conjunto Definitivo)

*Liste aqui os artigos que passaram por todas as filtragens e seguirão para o fichamento (etapa "j"). Referência completa no formato ABNT/APA definido pelo projeto.*

1. `HINZ, Mauro; MIERS, Charles C.; PILLON, Maurício A.; KOSLOVSKI, Guilherme P.. Um Modelo de Custo para Nuvens IaaS baseado no Consumo de Energia de Máquinas Virtuais. In: SIMPÓSIO BRASILEIRO DE SISTEMAS DE INFORMAÇÃO (SBSI), 12. , 2016, Florianópolis. Anais [...]. Porto Alegre: Sociedade Brasileira de Computação, 2016 . p. 136-143. ISSN 3086-4836. DOI: https://doi.org/10.5753/sbsi.2016.5955.`
2. `SEFFRIN, A. Mecanismo para reduzir o desperdício energético na pós-execução de aplicações em GPU. Workshop de Sistemas de Computação Paralela, 2014. p. 1-8. DOI: 10.5753/WSCAD.2014.15005`
3. `FERRAZ, I. Green AI: métricas para eficiência energética e sustentabilidade dos algoritmos de inteligência artificial e data centers. Revista Brasileira de Gestão Ambiental e Sustentabilidade, v. 11, n. 29, p. 1255-1265, 2024. DOI: 10.21438/rbgas(2024)112914.`
4. `FARINDA, Rani; PALITAI, Kanstantsin; POPIOLEK, Krzysztof; SEGANTI, Alessandro. Adaptive Control for Energy Optimization in Data Center. In: ACM INTERNATIONAL CONFERENCE ON SYSTEMS FOR ENERGY-EFFICIENT BUILDINGS, CITIES, AND TRANSPORTATION (BUILDSYS), 13., 2026, New York. New York: Association for Computing Machinery, 2026. p. 240–250. DOI: https://doi.org/10.1145/3744256.3812552.`
5. `AHUJA, Rohit; GARG, Sheetal; SINGH, Raman; PERL, Ivan. Effective Resource Management through VM Allocation in Cloud Data Center. In: INNOVATIONS IN SOFTWARE ENGINEERING CONFERENCE (ISEC), 18., 2025, New York. New York: Association for Computing Machinery, 2025. Article 6, p. 1–6. DOI: https://doi.org/10.1145/3717383.3717385.`
6. `ATMAJA, Subhanjaya Angga; EMANUEL, Andi Wahju Rahardjo; SUYOTO. A Systematic Literature Review on Intelligent Optimization for Virtual Machine Allocation in Cloud Data Centers. In: INTERNATIONAL CONFERENCE ON COMPUTER SCIENCE AND INFORMATION TECHNOLOGY (ICCSIT), 18., 2025, New York. New York: Association for Computing Machinery, 2026. p. 58–68. DOI: https://doi.org/10.1145/3783862.3783871.`
7. `TAN, Mingzhe; CHI, Ce; ZHANG, Jiahao; ZHAO, Shichang; LI, Guangli; LÜ, Shuai. An Energy-aware Virtual Machine Placement Algorithm in Cloud Data Center. In: INTERNATIONAL CONFERENCE ON INTELLIGENT INFORMATION PROCESSING (ICIIP), 2., 2017, New York. New York: Association for Computing Machinery, 2017. Article 1, p. 1–9. DOI: https://doi.org/10.1145/3144789.3144792.`
8. `RJEIB, Hasanein D.; KECSKEMETI, Gabor. VMP-ER: An Efficient Virtual Machine Placement Algorithm for Energy and Resources Optimization in Cloud Data Center. Algorithms, v. 17, n. 7, artigo 295, 2024. DOI: https://doi.org/10.3390/a17070295.`
9. `BAYDOUN, Ali Mohammad; ZEKRI, Ahmed Sherif. Network-, Cost-, and Renewable-Aware Ant Colony Optimization for Energy-Efficient Virtual Machine Placement in Cloud Datacenters. Future Internet, v. 17, n. 6, artigo 261, 2025. DOI: https://doi.org/10.3390/fi17060261.`
10. `AMAHROUCH, Abdelhadi; SAADI, Youssef; EL KAFHALI, Said. Optimizing Energy Efficiency in Cloud Data Centers: A Reinforcement Learning-Based Virtual Machine Placement Strategy. Network, v. 5, n. 2, artigo 17, 2025. DOI: https://doi.org/10.3390/network5020017.`
11. `GOPU, Arunkumar; THIRUGNANASAMBANDAM, Kalaipriyan; RAJAKUMAR, R.; ALGAMHDI, Ahmed Saeed; ALSHAMRANI, Sultan S.; MAHARAJAN, K.; RASHID, Mamoon. Energy-efficient virtual machine placement in distributed cloud using NSGA-III algorithm. Journal of Cloud Computing, v. 12, artigo 124, 2023. DOI: https://doi.org/10.1186/s13677-023-00501-y.`
12. `WEI, Pengcheng; ZENG, Yushan; YAN, Bei; ZHOU, Jiahui; NIKOUGOFTAR, Elaheh. VMP-A3C: Virtual machines placement in cloud computing based on asynchronous advantage actor-critic algorithm. Journal of King Saud University: Computer and Information Sciences, v. 35, artigo 101549, 2023. DOI: https://doi.org/10.1016/j.jksuci.2023.04.002.`
13. `NIKZAD, Badieh; BARZEGAR, Behnam; MOTAMENI, Homayun. SLA-Aware and Energy-Efficient Virtual Machine Placement and Consolidation in Heterogeneous DVFS Enabled Cloud Datacenter. IEEE Access, v. 10, p. 81787–81804, 2022. DOI: https://doi.org/10.1109/ACCESS.2022.3196240.`
14. `BRITO, José Luiz Romero de; MATAI, Patrícia Helena Lara dos Santos; SANTOS, Mario Roberto dos. Data Center e Eficiência Energética. Brazilian Journal of Business, v. 5, n. 2, p. 786-795, 2023. DOI: 10.34140/bjbv5n2-002. Disponível em: https://brazilianjournals.com.br.`
15. `PAIXÃO, Joelson Lopes da; NOGUEIRA, Humberto Alves. Computação Sustentável e Eficiência Energética: fundamentos, estratégias e desafios para infraestruturas digitais ambientalmente responsáveis. Scientia Generalis, Patos de Minas, v. 7, n. 1, p. 273-281, 2026. DOI: 10.22289/sg.V7N1A23. Disponível em: http://scientiageneralis.com.br/index.php/SG/article/view/842.`
16. `REIS, Thiago Nelson Faria dos; TEIXEIRA, Mário Meireles; SOARE NETO, Carlos de Salles. Uma abordagem de redução de energia na computação em nuvem verde. Research, Society and Development, v. 12, n. 7, p. e1812742407, 2023. DOI: 10.33448/rsd-v12i7.42407. Disponível em: https://rsdjournal.org.`
17. `SANTOS, Rômulo Ferreira dos. Sustentabilidade Digital e Eficiência Computacional: novos paradigmas para gestão inteligente de recursos em infraestruturas tecnológicas. Revista Tópicos, v. 14, e783483609, 2026. DOI: 10.70773/revistatopicos/783483609. Disponível em: https://revistatopicos.com.br.`
18. `STACCIARINI, João Henrique Santana; GONÇALVES, Ricardo Junior de Assis Fernandes. Data Centers, Minerais Críticos, Energia e Geopolítica: as bases da Inteligência Artificial. Sociedade & Natureza, Uberlândia, v. 37, n. 1, e77215, 2025. DOI: 10.14393/SN-v37-2025-77215. Disponível em: https://scielo.br.`
19. `MAIA, Luís; CUNHA, Simão; SARAIVA, João. Why Just-In-Time Compilation Matters: Evaluating Runtime and Energy Efficiency. Proceedings of the 19th ACM SIGPLAN International Conference on Software Language Engineering, 2026. DOI: https://doi.org/10.1145/3806383.3815520.`
20. `CUNHA, Simão; SILVA, Luís; SARAIVA, João; FERNANDES, João Paulo. Trading Runtime for Energy Efficiency: Leveraging Power Caps to Save Energy across Programming Languages. Proceedings of the 17th ACM SIGPLAN International Conference on Software Language Engineering, p. 130–142, 2024. DOI: https://doi.org/10.1145/3687997.3695638.`

*(Adicione quantas linhas forem necessárias.)*

---

## 4. Contribuição Individual dos Integrantes

> **Importante:** cada integrante deve descrever, com suas próprias palavras, o que efetivamente fez em cada passo desta etapa. Contribuições genéricas como "ajudei em tudo" não serão aceitas. Use verbos de ação e seja específico (ex.: "executei a busca no IEEE Xplore com a string 2 e obtive 84 resultados; fiz a triagem por título/resumo de 40 desses").

### Integrante 1 — `Maria Beatriz Santos Carvalho`
- **Passo(s) em que atuou:** `Passo 1, 2, 3, 4 , 5, 7`
- **O que fez em cada passo:** `Passo 1: Definiu A problemática do artigo com base da orientação da professora, listou palavras chaves; Passo 2: Inseriu uma string de busca para conectar possíveis artigos de pesquisa; Passo 3: Escolheu uma base de pesquisa para analisar potenciais trabalhos acadêmicos; Passo 4: definiu um critério de inclusão e exclusão para facilitar buscas; Passo 5: Usou uma string para localizar artigos de referência para o projeto, ajustou todas as referências para o bibtex. Passo 7: `
- **Tempo dedicado (aprox.):** `5h`
- **Evidência da contribuição** *(print de busca, planilha de triagem, exportação BibTeX, etc.)*: `Exportação Bibtex`

### Integrante 2 — `Gustavo de Faria`
- **Passo(s) em que atuou:** `Passo 1, 2, 3, 5`
- **O que fez em cada passo:** `Passo 1: listou palavras chaves; Passo 2: Inseriu uma string de busca para conectar possíveis artigos de pesquisa; Passo 3: Escolheu uma base de pesquisa para analisar potenciais trabalhos acadêmicos; Passo 5: Usou uma string para localizar artigos de referência para o projeto`
- **Tempo dedicado (aprox.):** `5h`
- **Evidência da contribuição:** `exportação BibTeX`

### Integrante 3 — `Gabrielle dos Santos Carmo`
- **Passo(s) em que atuou:** `Passo 6`
- **O que fez em cada passo:** `Passo 6: Definiu quais artigos seriam artigos seriam utilizados, quais possívelmente seriam utulizados e quais seriam descartados, preenchimento do modelo de levantamento bibliográfico`
- **Tempo dedicado (aprox.):** `5h`
- **Evidência da contribuição:**  `exportação BibTex, planilha de triagem`

### Integrante 4 — `Gabriel Santos da Silva`
- **Passo(s) em que atuou:** `Passo 4`
- **O que fez em cada passo:** `Participei da definição dos critérios de inclusão e exclusão dos artigos que seriam utilizados no levantamento bibliográfico, contribuindo para estabelecer os requisitos de seleção dos trabalhos, como período de publicação, relação com a área de Computação, disponibilidade do texto completo e foco no tema da pesquisa. Também contribuí para definir os critérios de exclusão de trabalhos duplicados, fora do escopo da pesquisa, não revisados por pares ou publicados fora do período estabelecido`
- **Tempo dedicado (aprox.):** `5h`
- **Evidência da contribuição:** `Critérios de inclusão e exclusão registrados no documento do grupo, incluindo minha participação na definição dos requisitos utilizados para selecionar os artigos da pesquisa`

### Integrante 5 — `Enrico Ricardo de Souza Prado`
- **Passo(s) em que atuou:** `Passo 2, 3 e 5`
- **O que fez em cada passo:** `Passo 2: Elaborou a String 2, utilizando os termos relacionados a máquinas virtuais e eficiência energética, para localizar trabalhos acadêmicos relacionados ao tema da pesquisa; Passo 3: Selecionou a ACM Digital Library como base de dados, considerando sua relevância para pesquisas na área de computação, máquinas virtuais, computação em nuvem, data centers e eficiência energética; Passo 5: Executou a String 2 na ACM Digital Library e obteve 1.505 resultados.`
- **Tempo dedicado (aprox.):** `6h`
- **Evidência da contribuição:** `exportação BibTex`


*(Copie o bloco acima para cada integrante adicional do grupo.)*

### 4.1 Quadro-resumo de participação por passo

| Passo | Responsável(is) | % estimado de participação de cada um |
|---|---|---|
| 1. Pergunta e palavras-chave | `Maria Beatriz / Gustavo de Faria` | `50% / 50%` |
| 2. Strings de busca | `Maria Beatriz / Enrico Ricardo / Gustavo de Faria` | `33.3% / 33.3% / 33.3%` |
| 3. Bases de dados | `Maria Beatriz / Enrico Ricardo / Gustavo de Faria` | `33.3% / 33.3% / 33.3%` |
| 4. Critérios de inclusão/exclusão | `Maria Beatriz / Gustavo de Faria / Gabriel Santos` | `33.3% / 33.3% / 33.3%` |
| 5. Execução das buscas | `Maria Beatriz / Enrico Ricardo / Gustavo de Faria` | `33.3% / 33.3% / 33.3%` |
| 6. Triagem título/resumo | `Gabrielle Santos` | `100%` |
| 7. Triagem texto completo | `Maria Beatriz` | `100%` |

### 4.2 Quadro-resumo geral de participação na etapa

| Integrante | % estimado de participação total nesta etapa |
|---|---|
| `Maria Beatriz` | `40,5%` |
| `Enrico Ricardo` | `14,3%` |
| `Gustavo de Faria` | `26,2%` |
| `Gabrielle Santos` | `14,3%` |
| `Gabriel Santos da Silva` | `4,7%` |

*A soma das porcentagens deve ser igual a 100%. Divergências de percepção sobre a participação devem ser discutidas em grupo antes do envio — o orientador pode solicitar esclarecimentos individuais em caso de disparidade relevante.*

---

## 5. Checklist Final da Etapa

**Fase 1 — Planejamento**
- [X] Pergunta de pesquisa de trabalho definida
- [X] Conceitos-chave e sinônimos (PT/EN) listados
- [X] Strings de busca elaboradas com operadores booleanos
- [X] Bases de dados escolhidas e justificadas
- [X] Critérios de inclusão e exclusão definidos

**Fase 2 — Execução e triagem**
- [X] Buscas executadas e resultados registrados por base/string
- [X] Referências exportadas para o gerenciador de referências
- [X] Triagem por título/resumo concluída (com duplicatas removidas)
- [X] Triagem por texto completo (introdução/conclusão) concluída
- [X] Conjunto definitivo de artigos para fichamento compilado

**Documentação**
- [X] Contribuição individual de cada integrante registrada por passo
- [X] Quadro-resumo de participação preenchido (soma = 100%)

---


