# Resumo da Aula 07 — Gerenciamento dos riscos

**Professor:** Prof. Me. Deivison S. Takatu  
**Disciplina:** Gestão de Projetos

## O que é risco

Risco é uma incerteza que, se ocorrer, pode afetar os objetivos do projeto. Pode representar uma ameaça (efeito negativo) ou uma oportunidade (efeito positivo). Um risco ainda não ocorrido é diferente de um problema, que já está acontecendo e exige tratamento imediato.

## Processo de gerenciamento

O gerenciamento começa pelo planejamento de como os riscos serão tratados. Em seguida, a equipe identifica riscos, registra causas e possíveis impactos, avalia probabilidade e consequência, prioriza os itens e define respostas. O registro precisa ser revisto durante o projeto, pois riscos e condições podem mudar.

A análise qualitativa classifica e prioriza riscos com critérios como probabilidade e impacto. Quando existem dados suficientes e a decisão justifica o esforço, a análise quantitativa estima efeitos numéricos sobre os objetivos.

## Respostas

Para ameaças, estratégias possíveis incluem evitar, mitigar, transferir ou aceitar. Para oportunidades, podem ser consideradas estratégias como explorar, aumentar, compartilhar ou aceitar. A resposta deve ter responsável e ações acompanháveis.

Risco residual é o que permanece depois da resposta; risco secundário surge como consequência de uma resposta ou tratamento. Também é necessário planejar contingências e acompanhar sinais que indiquem que um risco pode ocorrer.

## Para lembrar

- Risco pode ser negativo ou positivo e está ligado à incerteza.
- Identificar, avaliar, priorizar e responder são atividades contínuas.
- Probabilidade e impacto ajudam a definir prioridade.
- Cada risco importante precisa de responsável, resposta e acompanhamento.

## Fontes do professor

- Takatu, Deivison S. [Aula 07 — Riscos (PDF)](https://github.com/deivisontakatu/aula-gestao-projetos/blob/main/Aulas/Aula%2007%20-%20Riscos.pdf).
- Takatu, Deivison S. [11 — Gerenciamento dos Riscos do Projeto](https://github.com/deivisontakatu/aula-gestao-projetos/blob/main/11%20-%20Riscos.md).
- Takatu, Deivison S. [Repositório da disciplina](https://github.com/deivisontakatu/aula-gestao-projetos).

## Meu entendimento da aula

Risco não é sinônimo de problema. É um evento incerto que pode afetar objetivos se acontecer; pode representar ameaça ou oportunidade. Gerenciar riscos é agir antes e durante a execução: identificar incertezas, avaliar probabilidade e impacto, priorizar, escolher resposta e observar sinais de mudança. O registro precisa indicar responsável, resposta e condição que exige ação. A análise qualitativa serve para priorizar; a quantitativa é útil quando há dados e a decisão justifica estimar efeitos numéricos (PMI, 2017; Carvalho, 2018).

Uma resposta pode reduzir uma ameaça sem eliminá-la. O que permanece é risco residual; uma ação também pode criar risco secundário. Por isso, acompanhar a eficácia da resposta é parte do processo, e contingências devem estar preparadas para os riscos prioritários.

## Exemplo de aplicação no FieldOps

Um risco para sincronização de inspeções é a perda de dados quando o técnico fica sem conexão ou quando duas alterações chegam ao servidor em sequência. A causa pode envolver conectividade instável, estratégia de conflito ou falha de armazenamento. O impacto inclui retrabalho, dados inconsistentes e perda de confiança dos usuários.

A equipe registra o risco, avalia probabilidade e impacto, define responsável e resposta. Pode mitigar com fila local persistente, identificação de conflitos, testes de reconexão e logs de sincronização. Um risco residual continua existindo, então pode haver procedimento de recuperação e monitoramento de falhas. Uma oportunidade associada seria aproveitar os registros offline para reduzir o tempo de inspeção em locais sem cobertura.

## Referências bibliográficas

- PROJECT MANAGEMENT INSTITUTE. *Um guia do conhecimento em gerenciamento de projetos (Guia PMBOK)*. 6. ed. Newtown Square: PMI, 2017.
- CARVALHO, Fábio Câmara Araújo de. *Gestão de projetos*. 2. ed. São Paulo: Pearson, 2018.
- BUENO, Gislaine. *Gestão de projetos para cybersecurity*. São Paulo: Contentus, 2020.
