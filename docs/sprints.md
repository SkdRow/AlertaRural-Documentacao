# *Sprints*

Conforme acordado entre os membros da equipe, cada fase ser� composta por um ou mais ciclos (*sprints* em Scrum) que estipula um conjunto de atividades a ser desempenhada em determinado per�odo limitado.  

Cada ciclo ser� gerenciado com o quadro Kanban.

## Inicia��o

| Descri��o | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- |
| Identificar os *stakeholders* e os meios para contat�-los | Primeira | 1 |
| Definir quais ser�o as t�cnicas para o levantamento de requisitos | Primeira | 1 |
| Classificar o dom�nio do problema e o objetivo do projeto | Primeira | 1 |
| Identificar quais par�metros para especificar os requisitos | Segunda | 2 |
| Definir os crit�rios de valida��o para os requisitos | Segunda | 2 |
| Levantar os requisitos | Terceira | 14 |
| Criar o Lean Inception com o mapa de empatia | Terceira | 5 |
| Modelagem conceitual (utilizando UML) | Quarta | 7 |
| Validar os requisitos | Quarta | 3 |

## Elabora��o

| Descri��o | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- |
| Estimar o tempo necess�rio para cada atividade utilizando Planning Poker | Primeira | 1 |
| Utilizar o resultado para preencher a Rede de Atividades | Primeira | 1 |
| Calcular o caminho cr�tico | Segunda | 1 |
| Identificar os riscos do projeto e reduz�-los ou elimin�-los | Segunda | 3 |
| Definir m�tricas para avaliar a qualidade do processo | Segunda | 2 |
| Criar os diagramas de projeto UML | Terceira | 10 |
| Definir a arquitetura | Quarta | 20 |
| Planejar os testes para cada funcionalidade e os testes de regress�o | Quarta | 4 |
| Criar uma estrat�gia para persistir os dados | Quinta | 3 |
| Criar um plano para seguran�a | Quinta | 6 |

## Implementa��o

Estas sprints est�o intimamente ligadas com cada requisito funciona.

Os par�metros do *Lean Inception* ser�o acrescentados aos requisitos de implementa��o, por�m estar�o localizadas no quadro Kanban.

| Descri��o | Escopo | Estabilidade | Funcional / N�o-Funcional | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- | ------- | ------- | ------- |
| O sistema deve cadastrar o usu�rio, requisitando pelo nome completo, cpf, data de nascimento, e-mail e senha | Cadastro | Alguns dados talvez sejam retirados ou acrescentados | Funcional | Primeira | 14
| O sistema deve enviar as informa��es do cadastro para o cliente | Cadastro | Est�vel | Funcional | Primeira | 5
| O sistema deve exigir que o usu�rio envie pelo menos 1 documento com foto para comprova��o | Cadastro | Est�vel | Funcional | Primeira | 4 |
| O sistema deve fornecer um conjunto finito de gravidades (grave, mediano e leve) para os alertas a serem enviados | Alertas | A quantidade de alerta pode sofrer altera��es, pois o cliente pode requisitar por um refinamento ou adi��o | Funcional | Segunda | 5 |
| O sistema n�o deve permitir a altera��o do nome dado � gravidade | Alertas | Est�vel | Funcional | Segunda | 1 |
| O sistema deve notificar o usu�rio se o alerta foi enviado ou n�o | Notifica��o | Est�vel | Funcional | Terceira | 4 |

## Implanta��o

| Descri��o | *Sprint* | Tempo estimado (dias) |
| ----------- | -------- | ------- |
