| Disciplina | FGA0315 - Qualidade de Software 1    |
| :--------- | :----------------------------------- |
| Turma      | 2025-1 (T02)                         |
| Profa.     | Cristiane Ramos                      |
| Tema       | Abordagens de medição e análise(GQM) |

# GQM - Fase Definição

### Objetivo de negócio do AGROMART:

O AgroMart tem como principal objetivo de negócio facilitar a comercialização de produtos agrícolas, conectando diretamente produtores e consumidores por meio de uma plataforma digital. A proposta é reduzir a dependência de intermediários, permitindo que os produtores tenham maior autonomia e margem de lucro sobre seus produtos, ao mesmo tempo em que os consumidores têm acesso a preços mais competitivos.  
Além disso, o sistema busca oferecer uma interface acessível e fácil de usar, mesmo para usuários com pouca familiaridade com a tecnologia. Isso é essencial para atender o público-alvo do setor agrícola, que muitas vezes não tem experiência com plataformas digitais. A usabilidade, nesse contexto, torna-se um fator estratégico para o sucesso do negócio, garantindo adesão e satisfação dos usuários desde os primeiros acessos.  
Por fim, o AgroMart pretende digitalizar o comércio rural, promovendo o escoamento da produção de forma eficiente e segura, contribuindo para o desenvolvimento econômico local e a modernização do setor agrícola.

## Objetivo de Medição 1: Facilidade de Aprendizado

|                          |                                                                 |
| :----------------------- | :-------------------------------------------------------------- |
| **Analisar**             | A primeira interação dos usuários iniciantes com a plataforma AgroMart.                      |
| **Propósito**            | Compreender o grau de facilidade de aprendizado durante o primeiro uso da plataforma. |
| **Com respeito a**       | Usabilidade — Facilidade de aprendizado.                                       |
| **Do ponto de vista da** | Usuário Iniciante                                               |
| **No contexto de**       | Disciplina de Qualidade de Software                             |

### Questões Objetivo de Medição 1:

**Q1:** A interface do sistema facilita o aprendizado e a familiarização dos novos usuários?  
**Hipótese Q1:** Pelo menos 80% dos usuários iniciantes conseguem utilizar as funcionalidades básicas sem auxílio externo.

**Q2:** O sistema permite que usuários inexperientes realizem suas tarefas iniciais de forma eficiente?  
**Hipótese Q2:** O tempo médio para completar uma tarefa inicial é inferior a 5 minutos.

**Q3:** Qual é a eficácia do sistema no apoio à realização de tarefas por usuários com pouca ou nenhuma experiência prévia?  
**Hipótese Q3:** A taxa de sucesso na conclusão de tarefas básicas é igual ou superior a 85%.

### Métricas

- Taxa de sucesso na realização de tarefas (%);
- Tempo médio por tarefa (em segundos/minutos);
- Número médio de interações por tarefa (cliques/toques);
- Nível de satisfação com a interface;
- Número de erros cometidos por tarefa.

## Objetivo de Medição 2: Eficiência no Uso Contínuo

|                          |                                                        |
| :----------------------- | :----------------------------------------------------- |
| **Analisar**             | O uso recorrente do sistema por usuários familiarizados          |
| **Propósito**            | Avaliar a eficiência do sistema durante o uso contínuo |
| **Com respeito a**       | Usabilidade – Eficiência                               |
| **Do ponto de vista da** | Usuários frequentes                                     |
| **No contexto de**       | Disciplina de Qualidade de Software                    |

### Questões Objetivo de Medição 2:

**Q1:** O sistema permite a realização de tarefas comuns de forma simples e com o mínimo esforço por parte do usuário?  
**Hipótese Q1:** As tarefas rotineiras exigem, no máximo, 5 ações/interações para serem concluídas.

**Q2:** O sistema mantém um desempenho consistente e confiável durante o uso contínuo?
**Hipótese Q2:** O tempo médio de resposta por ação é inferior a 2 segundos.

**Q3:** A navegação no sistema é intuitiva e eficiente para usuários habituais?  
**Hipótese Q3:** Pelo menos 90% dos usuários atribuem nota igual ou superior a 4 (em uma escala de 1 a 5) para a eficiência da navegação.

### Métricas

- Tempo médio de resposta por página (ms);
- Tempo de carregamento (ms);
- Taxa (%) de erro por tarefa;
- Uso de CPU/memória (%) no lado cliente.

## Abstraction Sheet – Objetivo 1: Facilidade de Aprendizado

### Quality Focus

- Taxa de sucesso em tarefas básicas
- Tempo médio para concluir tarefas
- Necessidade de ajuda externa
- Nível de familiaridade tecnológica inicial dos usuários

### Baseline Hypotheses (Estimates)

- 80% dos usuários iniciantes realizam tarefas sem ajuda
- Tempo médio para tarefa básica: até 5 minutos
- Taxa de sucesso ≥ 85%
- Usuários com maior familiaridade tecnológica apresentam desempenho melhor

### Impact of Variation Factors

- Interfaces mais simples e orientadas reduzem o tempo e aumentam o sucesso sem assistência
- O nível inicial de familiaridade tecnológica dos usuários pode impactar significativamente o tempo para aprendizado e a taxa de sucesso
- Métodos claros e consistentes de coleta de dados são essenciais para garantir que as métricas reflitam com precisão os focos de qualidade e hipóteses estabelecidas

## Abstraction Sheet – Objetivo 2: Eficiência no Uso Contínuo

### Quality Focus

- Número de ações por tarefa rotineira
- Tempo de resposta do sistema
- Avaliação subjetiva da fluidez de navegação
- Consistência da interface durante o uso contínuo

### Baseline Hypotheses (Estimates)

- ≤ 5 ações para completar tarefas
- Tempo de resposta ≤ 2 segundos
- ≥ 90% dos usuários avaliam a navegação com nota ≥ 4/5
- Interfaces consistentes facilitam a eficiência do usuário habitual

### Impact of Variation Factors

- Melhor organização e performance aumentam a eficiência percebida e real nas tarefas repetidas
- Variações em dispositivos, qualidade da rede e contexto de uso podem afetar o desempenho do sistema e a percepção do usuário
- A consistência da interface é um fator chave para a manutenção da eficiência em uso contínuo, pois favorece a familiaridade e reduz o esforço cognitivo

## Diagrama

![Objetivos de Medição](img/Diagrama%20GQM.png)

## Tabela de Contribuição

| Matrícula |                Nome                | Contribuição (%) |
| :-------: | :--------------------------------: | :--------------: |
| 221022284 |     Gabriel Henrique R de Lima     |      16,66       |
| 221022319 |   Jéssica Eveline Saraiva Araújo   |      16,66       |
| 221022328 | João Gabriel Gomes Carvalho Soares |      16,66       |
| 211029666 |    Matheus Henrique Dos Santos     |      16,66       |
| 221008605 |   Pedro Gustavo de Souza Santos    |      16,66       |
| 211043763 |       Ruan Sobreira Carvalho       |      16,66       |

## Histórico de Versões

| Versão |                Descrição                |                                                                         Autor                                                                          |    Data    | Revisor | Data de revisão |
| :----: | :-------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------: | :--------: | :-----: | :-------------: |
|  1.0   | Versão inicial dos objetivos de medição | [Gabriel Henrique](https://github.com/gabrielhrlima), [Matheus Henrique](https://github.com/mathonaut), [Pedro Gustavo](https://github.com/PedroGusta) | 21/05/2025 |  [Jéssica Eveline](https://github.com/xzxjesse)     |  27/05/2025               |
