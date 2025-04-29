# Projeto AIRDATA

**Artificial Intelligence for Aviation Data Analysis.**

---

## Descritivo
---

O projeto AIRDATA envolve o desenvolvimento de um sistema de armazenamento e análise de dados para o setor de aviação brasileiro, focado na aviação civil, fundamentado em técnicas de IA. Este sistema integrará e aprimorará dados provenientes de múltiplas bases do setor aeronáutico, incluindo dados oriundos da ANAC, SAC e DECEA, complementados por dados de trajetória do OpenSky. A plataforma utilizará algoritmos de IA para melhorar a qualidade das informações, reduzindo erros e inconsistências nos dados, o que permitirá automatizar e aprimorar o cálculo dos indicadores estabelecidos pelo GANP, GASP e PAN, por exemplo.

O AIRDATA implementará técnicas de análise preditiva e prescritiva baseadas em ML, visando à identificação de tendências e padrões anômalos no sistema de aviação civil. Por exemplo, o sistema será capaz de identificar desvios significativos de trajetórias em relação às rotas padrão estabelecidas, correlacionando possíveis fatores causais, como condições meteorológicas, restrições operacionais ou outros eventos relevantes. Além disso, a plataforma permitirá analisar o impacto em cascata de atrasos na rede de transporte aéreo, identificando como perturbações em determinados aeroportos podem afetar sistemicamente a malha aérea nacional.

A arquitetura do sistema será projetada para ser flexível e escalável, possibilitando a incorporação de novas bases de dados e a contínua evolução dos indicadores. Isso garantirá que o setor de aviação brasileiro permaneça alinhado com as mais recentes práticas de análise de dados, promovendo uma tomada de decisão mais informada e eficiente em todos os níveis. Como produtos finais, o projeto disponibilizará uma ferramenta web para consulta de eventos aeronáuticos, permitindo também o download de dados em XLS ou CSV, e uma plataforma experimental com chatbot baseado em IA generativa para análises complexas do setor.

Por fim, é importante destacar que o projeto enfrenta desafios técnicos importantes. O primeiro refere-se à harmonização temporal das diferentes bases de dados, garantindo a correta correlação entre eventos aeronáuticos registrados em diferentes sistemas. Além disso, existem complexidades inerentes à estimativa precisa dos indicadores, como por exemplo os do GANP e GASP, que demandarão o desenvolvimento de metodologias de processamento e análise de dados para assegurar resultados confiáveis e aderentes aos padrões internacionais. No contexto da implementação dos chatbots, a utilização de modelos de IA generativa open source apresenta desafios próprios, como possíveis limitações na precisão e contextualização das respostas durante as fases iniciais do projeto, demandando um processo iterativo de refinamento e ajuste dos modelos. Outros desafios incluem a necessidade de lidar com bases de dados que podem apresentar informações ausentes ou divergentes entre si, garantir que os diferentes sistemas existentes consigam efetivamente trocar informações entre si, e desenvolver métodos para verificar se as previsões e análises geradas pelo sistema estão realmente adequadas e confiáveis.

---

## Atividades
---

**A1: Análise e Mapeamento das Bases de Dados**

**1. Levantamento de Requisitos e Entendimento do Domínio**

- Realizar entrevistas com especialistas e stakeholders chave da ANAC, DECEA e SAC  
- Identificar requisitos específicos de cada órgão para o uso dos dados  
- Mapear os processos atuais de coleta e análise de dados  
- Documentar casos de uso prioritários  

**2. Análise Técnica das Bases**

- Identificar e analisar as estruturas de dados de cada base selecionada  
- Documentar os formatos, padrões e protocolos utilizados  
- Avaliar a qualidade e completude dos dados existentes  
- Identificar possíveis inconsistências entre as bases  

**3. Mapeamento para Integração**

- Mapear as informações relevantes para integração  
- Estabelecer correlações entre as diferentes bases de dados  
- Identificar campos chave para relacionamento entre as bases  
- Documentar regras de negócio específicas para tratamento dos dados  

**4. Análise dos Dados de Trajetória**

- Analisar e estruturar os dados de trajetória do OpenSky  
- Identificar padrões de formato e frequência das informações  
- Estabelecer critérios para validação dos dados de trajetória  
- Definir metodologia para correlação com outras bases  



**A2: Desenvolvimento do Sistema de Integração**

**1. Projeto da Arquitetura**

- Definir a arquitetura do sistema  
- Especificar os componentes de integração e armazenamento  
- Estabelecer os requisitos de segurança e escalabilidade  
- Documentar a arquitetura proposta  

**2. Desenvolvimento da Infraestrutura**

- Implementar a infraestrutura de armazenamento  
- Desenvolver os mecanismos de ingestão de dados  
- Criar as interfaces de conexão com as bases  
- Implementar o sistema de processamento dos dados do OpenSky  

**3. Implementação dos Mecanismos de Integração**

- Desenvolver os processos de Extração, Transformação e Carga (ETL)  
- Implementar regras de negócio para harmonização dos dados  
- Criar mecanismos de validação e qualidade dos dados  
- Desenvolver rotinas de atualização e sincronização  



**A3: Implementação de Algoritmos de IA para Enriquecimento e Validação de Dados**

**1. Desenvolvimento de Algoritmos de Validação**

- Implementar modelos para detecção de inconsistências  
- Desenvolver algoritmos para validação cruzada  
- Criar mecanismos de verificação de completude  
- Implementar rotinas de qualidade dos dados  

**2. Implementação de Módulos de Enriquecimento**

- Desenvolver algoritmos para correlação de eventos  
- Criar modelos para preenchimento de dados ausentes  
- Implementar técnicas de normalização e padronização  
- Desenvolver métricas de confiabilidade  

**3. Desenvolvimento do Protótipo de Consultas**

- Implementar interface de busca por voos  
- Desenvolver visualização integrada de eventos  
- Criar módulos de análise temporal  
- Implementar funcionalidades de exportação de dados  



**A4: Implementação dos Indicadores por meio de IA – Fase 1**

**1. Análise e Seleção de Indicadores**

- Realizar workshops com stakeholders  
- Mapear fontes de dados necessárias  
- Documentar metodologias de cálculo  
- Definir critérios de validação dos resultados  

**2. Desenvolvimento dos Módulos de Cálculo**

- Implementar algoritmos de cálculo  
- Desenvolver rotinas de validação  
- Criar interfaces de visualização  
- Implementar funcionalidades de exportação  

**3. Validação e Testes**

- Realizar testes com dados históricos  
- Validar resultados com especialistas  
- Implementar ajustes e correções  
- Documentar os resultados  



**A5: Implementação dos Indicadores por meio de IA – Fase 2**

**1. Análise dos Indicadores Complementares**

- Nova rodada de workshops  
- Avaliar lições aprendidas da Fase 1  
- Mapear requisitos dos novos indicadores  
- Definir cronograma de implementação  

**2. Desenvolvimento e Integração**

- Implementar algoritmos para novos indicadores  
- Integrar com módulos da Fase 1  
- Desenvolver interfaces adicionais  
- Implementar funcionalidades de análise cruzada  

**3. Validação e Documentação**

- Realizar testes integrados  
- Validar com stakeholders  
- Documentar metodologias e resultados  
- Elaborar manuais de utilização  



**A6: Testes, Validação e Documentação Final**

**1. Testes Integrados**

- Testes de integração do sistema completo  
- Validação da qualidade dos dados  
- Verificação da precisão dos indicadores  
- Avaliação do desempenho em diferentes cenários  

**2. Validação com Especialistas**

- Workshops de validação com especialistas  
- Testes dos indicadores GANP, GASP e PAN  
- Validação de funcionalidades de análise preditiva  
- Avaliação da usabilidade das interfaces  

**3. Documentação e Treinamento**

- Elaboração da documentação técnica  
- Manuais de usuário e guias operacionais  
- Material de treinamento para diferentes perfis  
- Procedimentos de manutenção e atualização  

---

## Produtos

---

**Produto PI: Relatório de Análise e Mapeamento das Bases de Dados**

Relatório com análise das entrevistas com stakeholders, requisitos identificados, mapeamento técnico das bases (SISCEAB, ANAC, SAC, OpenSky), avaliação de qualidade, propostas de integração e recomendações técnicas.

**Produto PII: Sistema de Integração de Dados**

Sistema integrado com infraestrutura de armazenamento, componentes de ETL, interfaces para o OpenSky, mecanismos de padronização e validação. Inclui documentação técnica.

**Produto PIII: Sistema de Enriquecimento de Dados e Protótipo de Consultas**

Algoritmos de enriquecimento e validação, com visualização integrada de eventos e consultas por voo. Protótipo com análise temporal e funcionalidades de exportação.

**Produto PIV: Sistema de Indicadores – Módulo Inicial**

Módulo com primeiros indicadores priorizados, interfaces de visualização e relatórios automáticos. Inclui documentação das metodologias e validações.

**Produto PV: Sistema de Indicadores – Módulo Complementar**

Conjunto complementar de indicadores, com funcionalidades de análise cruzada. Documentação completa e integração com o módulo inicial.

**Produto PVI: Relatório de Validação e Resultados**

Resultados dos testes e validações com especialistas. Inclui análise de desempenho, precisão dos indicadores e recomendações para evolução futura.

**Produto PVII: Documentação Técnica e Material de Treinamento**

Documentação completa do sistema AIRDATA, manuais, guias de uso, material de capacitação e manutenção.

---

## Cronograma Físico

---

A presente Etapa terá duração de **36 meses**, com cronograma de execução das Atividades e entrega dos Produtos conforme planejado.



| Atividade/Produto| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 |
|------------------|---|---|---|---|---|---|---|---|---|----|----|----|----|----|----|----|----|-----|
| A1               | * | * | * | * |   |   |   |   |   |    |    |    |    |    |    |    |    |     |
| **PI**           |   |   |   | ■ |   |   |   |   |   |    |    |    |    |    |    |    |    |     |
| A2               |   |   |   | * | * | * | * | * | * |    |    |    |    |    |    |    |    |     |
| **PII**          |   |   |   |   |   |   |   |   | ■ |    |    |    |    |    |    |    |    |     |
| A3               |   |   |   |   |   |   |   |   | * | *  | *  | *  | *  |  * | *  | *  |  * | *   |
| **PIII**         |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    | ■   |


| Atividade/Produto| 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 | 34 | 35 | 36 |
|------------------|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| A4               | *  | *  | *  | *  | *  | *  | *  |    |    |    |    |    |    |    |    |    |    |    |
| **PIV**          |    |    |    |    |    |    | ■  |    |    |    |    |    |    |    |    |    |    |    |
| A5               |    |    |    |    |    |    | *  | *  | *  | *  | *  | *  | *  |    |    |    |    |    |
| **PV**           |    |    |    |    |    |    |    |    |    |    |    |    | ■  |    |    |    |    |    |
| A6               |    |    |    |    |    |    |    |    |    |    |    |    | *  | *  | *  | *  | *  | *  |
| **PVI**          |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    | ■  |
| **PVII**         |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    | ■  |



