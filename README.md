# Resumo Lab XP-Cloud-IA (DIO)

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab XP-Cloud-IA na DIO.

## Acordo de Nível de Serviço (SLA)

No laboratório, foi abordado o conceito de Acordo de Nível de Serviço (SLA - Service Level Agreement). O SLA define a disponibilidade esperada de um serviço.

A tabela abaixo demonstra o tempo máximo de inatividade aceitável por semana, mês e ano para diferentes percentuais de SLA:

| SLA     | Tempo de Inatividade / Semana | Tempo de Inatividade / Mês | Tempo de Inatividade / Ano |
|---------|-------------------------------|----------------------------|----------------------------|
| 99%     | 1,68hs                        | 7,2hs                      | 3,65 dias                  |
| 99,9%   | 10,1 min                      | 43,2min                    | 8,77hs                     |
| 99,95%  | 5min                          | 21,6min                    | 4,38hs                     |
| 99,99%  | 1,01min                       | 4,32min                    | 52,56min                   |
| 99,999% | 6seg                          | 25,9seg                    | 5,25min                    |

## Considerações Importantes

Ao criar um serviço na nuvem, é fundamental questionar sua finalidade:
*   É para testes, aprendizado ou para entender como funciona?
*   Ou é um serviço para produção?

Estas perguntas devem ser feitas, pois a resposta impacta diretamente o SLA necessário. Dependendo da necessidade (teste vs. produção), a escolha do SLA afetará os custos e a estratégia de implementação a ser adotada para garantir a disponibilidade adequada. Escolher um SLA mais alto do que o necessário pode gerar custos desnecessários, enquanto um SLA muito baixo para produção pode levar a perdas significativas.
