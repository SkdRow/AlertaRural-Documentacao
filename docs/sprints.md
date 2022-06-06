# *Sprints*

Conforme acordado entre os membros da equipe, cada fase será composta por um ou mais ciclos (*sprints* em Scrum) que estipula um conjunto de atividades a ser desempenhada em determinado período limitado.  

Cada ciclo será gerenciado com o quadro Kanban.

## Iniciação

| Descrição | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- |
| Identificar os *stakeholders* e os meios para contatá-los | Primeira | 1 |
| Definir quais serão as técnicas para o levantamento de requisitos | Primeira | 1 |
| Classificar o domínio do problema e o objetivo do projeto | Primeira | 1 |
| Identificar quais parâmetros para especificar os requisitos | Segunda | 2 |
| Definir os critérios de validação para os requisitos | Segunda | 2 |
| Levantar os requisitos | Terceira | 14 |
| Criar o Lean Inception com o mapa de empatia | Terceira | 5 |
| Modelagem conceitual (utilizando UML) | Quarta | 7 |
| Validar os requisitos | Quarta | 3 |

## Elaboração

| Descrição | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- |
| Estimar o tempo necessário para cada atividade utilizando Planning Poker | Primeira | 1 |
| Utilizar o resultado para preencher a Rede de Atividades | Primeira | 1 |
| Calcular o caminho crítico | Segunda | 1 |
| Identificar os riscos do projeto e reduzí-los ou eliminá-los | Segunda | 3 |
| Definir métricas para avaliar a qualidade do processo | Segunda | 2 |
| Criar os diagramas de projeto UML | Terceira | 10 |
| Definir a arquitetura | Quarta | 20 |
| Planejar os testes para cada funcionalidade e os testes de regressão | Quarta | 4 |
| Criar uma estratégia para persistir os dados | Quinta | 3 |
| Criar um plano para segurança | Quinta | 6 |

## Implementação

Estas sprints estão intimamente ligadas com cada requisito funciona.

Os parâmetros do *Lean Inception* serão acrescentados aos requisitos de implementação, porém estarão localizadas no quadro Kanban.

| Descrição | Escopo | Estabilidade | Funcional / Não-Funcional | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- | ------- | ------- | ------- |
| O sistema deve cadastrar o usuário, requisitando pelo nome completo, cpf, data de nascimento, e-mail e senha | Cadastro | Alguns dados talvez sejam retirados ou acrescentados | Funcional | Primeira | 14
| O sistema deve enviar as informações do cadastro para o cliente | Cadastro | Estável | Funcional | Primeira | 5
| O sistema deve exigir que o usuário envie pelo menos 1 documento com foto para comprovação | Cadastro | Estável | Funcional | Primeira | 4 |
| O sistema deve fornecer um conjunto finito de gravidades (grave, mediano e leve) para os alertas a serem enviados | Alertas | A quantidade de alerta pode sofrer alterações, pois o cliente pode requisitar por um refinamento ou adição | Funcional | Segunda | 5 |
| O sistema não deve permitir a alteração do nome dado à gravidade | Alertas | Estável | Funcional | Segunda | 1 |
| O sistema deve notificar o usuário se o alerta foi enviado ou não | Notificação | Estável | Funcional | Terceira | 4 |

## Implantação

| Descrição | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- |
