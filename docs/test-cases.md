# Casos de Teste

## 1 Cadastro

* Pr�-condi��es
  * O usu�rio deve estar na tela de cadastro, com ou sem um usu�rio previamente criado.
* Campos obrigat�rios:
  * Nome completo
  * Senha
* Campos opcionais:
  * E-mail

| ID | Entrada | Resultado esperado | Resultado obtido |
| -- | ------- | ------------------ | ---------------- |
| CC1 | Nome sem o sobrenome | Bloquear e requisitar por mais um nome | |
| CC2 | Nome completo | Prosseguir | |
| CC3 | E-mail inv�lido | Bloquear e requisitar por um e-mail v�lido | |
| CC4 | E-mail j� cadastrado no sistema | Bloquear e requisitar por outro e-mail | |
| CC5 | Senha com menos de 8 d�gitos | Bloquear o cadastro e requisitar por uma nova senha, informando o motivo | |
| CC6 | Senha com somente letras | Bloquear o cadastro e requisitar por uma nova senha | |
| CC7 | Senha com apenas espa�os | Bloquear o cadastro e requisitar por uma nova senha | |
| CC8 | Senha com apenas n�meros | Bloquear o cadastro e requisitar por uma nova senha | |
| CC9 | Senha ultrapassando o limite de caracteres previamente estipulado | N�o permitir o envio da requisi��o ao servidor | |
| CC10 | Pelo menos um documento com foto foi requisitado? | Sim | |

## 2 Alerta

* Pr�-condi��es
  * O usu�rio deve estar dentro no sistema com a tela de envio do alerta selecionada.
* Campos obrigat�rios:
  * Gravidade do alerta
  * Senha
* Campos opcionais:
  * E-mail

| ID | Entrada | Resultado esperado | Resultado obtido |
| -- | ------- | ------------------ | ---------------- |
| CA1 | Quantos passos s�o necess�rios at� o envio? | 2 | |
| CA2 | Quantas gravidades est�o dispon�veis? | 3 | |
| CA3 | Quanto tempo levou para o alerta ser enviado e recebido na central? | m�ximo de 2 segundos | |
| CA4 | As informa��es b�sicas (nome, localiza��o, etc..) foram enviadas sem serem pedidas explicitamente? | Sim | |
| CA5 | Como o alerta mais grave � exibido para o gestor? | Em vermelho, efeitos sonoros e o mais chamativo poss�vel | |
| CA6 | Como o alerta mais grave � exibido para os moradores rurais das proximidades? | Notifica��o por push | |
| CA7 | O que � exibido para os moradores das proximidades? | Localiza��o e gravidade do alerta | |
| CA8 | Os alertas com gravidade m�dia ou abaixo foram exibidos para os moradores das proximidades? | Sim | |
| CA9 | Quais meios de seguran�a foram estabelecidos para que o morador rural conseguisse enviar o alerta? | Biometria e/ou an�lise da retina | |
| CA10 | � poss�vel que o gestor envie um alerta? | N�o | |

## 3 Relat�rios

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
