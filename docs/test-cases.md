# Casos de Teste

## 1 Cadastro

* Campos obrigatórios:
  * Nome completo
  * Senha
* Campos opcionais:
  * E-mail

| Entrada | Resultado esperado | Resultado obtido |
| --------- | --------- | --------- |
| Nome sem o sobrenome | Bloquear e requisitar por mais um nome | |
| Nome completo | Prosseguir | |
| E-mail inválido | Bloquear e requisitar por um e-mail válido | |
| E-mail já cadastrado no sistema | Bloquear e requisitar por outro e-mail | |
| Senha com menos de 8 dígitos | Bloquear o cadastro e requisitar por uma nova senha, informando o motivo | |
| Senha com somente letras | Bloquear o cadastro e requisitar por uma nova senha | |
| Senha com apenas espaços | Bloquear o cadastro e requisitar por uma nova senha | |
| Senha com apenas números | Bloquear o cadastro e requisitar por uma nova senha | |
| Senha ultrapassando o limite de caracteres previamente estipulado | Não permitir o envio da requisição ao servidor | |
| Pelo menos um documento com foto foi requisitado? | Sim | |

## 2 Alerta

| Entrada | Resultado esperado | Resultado obtido |
| --------- | --------- | --------- |
| Quantos passos são necessários até o envio? | 2 | |
| Quantas gravidades estão disponíveis? | 3 | |
| Quanto tempo levou para o alerta ser enviado e recebido na central? | máximo de 2 segundos | |
| As informações básicas (nome, localização, etc..) foram enviadas sem serem pedidas explicitamente? | Sim | |
| Como o alerta mais grave é exibido para o gestor? | Em vermelho, efeitos sonoros e o mais chamativo possível | |
| Como o alerta mais grave é exibido para os moradores rurais das proximidades? | Notificação por push | |
| O que é exibido para os moradores das proximidades? | Localização e gravidade do alerta | |
| Os alertas com gravidade média ou abaixo foram exibidos para os moradores das proximidades? | Sim | |
| Quais meios de segurança foram estabelecidos para que o morador rural conseguisse enviar o alerta? | Biometria e/ou análise da retina | |
| É possível que o gestor envie um alerta? | Não | |
|  | | |

## 3 Relatório

| Entrada | Resultado esperado |
| --------- | --------- |
|  | |

### 3.1 Usuários

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
