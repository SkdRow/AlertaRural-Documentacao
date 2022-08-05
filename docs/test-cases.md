# Casos de Teste

## 1 Cadastro

* Campos obrigat�rios:
  * Nome completo
  * Senha
* Campos opcionais:
  * E-mail

| Entrada | Resultado esperado | Resultado obtido |
| --------- | --------- | --------- |
| Nome sem o sobrenome | Bloquear e requisitar por mais um nome | |
| Nome completo | Prosseguir | |
| E-mail inv�lido | Bloquear e requisitar por um e-mail v�lido | |
| E-mail j� cadastrado no sistema | Bloquear e requisitar por outro e-mail | |
| Senha com menos de 8 d�gitos | Bloquear o cadastro e requisitar por uma nova senha, informando o motivo | |
| Senha com somente letras | Bloquear o cadastro e requisitar por uma nova senha | |
| Senha com apenas espa�os | Bloquear o cadastro e requisitar por uma nova senha | |
| Senha com apenas n�meros | Bloquear o cadastro e requisitar por uma nova senha | |
| Senha ultrapassando o limite de caracteres previamente estipulado | N�o permitir o envio da requisi��o ao servidor | |
| Pelo menos um documento com foto foi requisitado? | Sim | |

## 2 Alerta

| Entrada | Resultado esperado | Resultado obtido |
| --------- | --------- | --------- |
| Quantos passos s�o necess�rios at� o envio? | 2 | |
| Quantas gravidades est�o dispon�veis? | 3 | |
| Quanto tempo levou para o alerta ser enviado e recebido na central? | m�ximo de 2 segundos | |
| As informa��es b�sicas (nome, localiza��o, etc..) foram enviadas sem serem pedidas explicitamente? | Sim | |
| Como o alerta mais grave � exibido para o gestor? | Em vermelho, efeitos sonoros e o mais chamativo poss�vel | |
| Como o alerta mais grave � exibido para os moradores rurais das proximidades? | Notifica��o por push | |
| O que � exibido para os moradores das proximidades? | Localiza��o e gravidade do alerta | |
| Os alertas com gravidade m�dia ou abaixo foram exibidos para os moradores das proximidades? | Sim | |
| Quais meios de seguran�a foram estabelecidos para que o morador rural conseguisse enviar o alerta? | Biometria e/ou an�lise da retina | |
| � poss�vel que o gestor envie um alerta? | N�o | |
|  | | |

## 3 Relat�rio

| Entrada | Resultado esperado |
| --------- | --------- |
|  | |

### 3.1 Usu�rios

| Entrada | Resultado esperado |
| --------- | --------- |
| | |

### 3.2 Alertas

| Entrada | Resultado esperado |
| --------- | --------- |
| | |

#### 3.2.1 Gestor

| Entrada | Resultado esperado |
| --------- | --------- |
| | |

#### 3.2.2 Morador rural

| Entrada | Resultado esperado |
| --------- | --------- |
| | |
