# Casos de Teste

## 1 Cadastro

* Pré-condições
  * O usuário deve estar na tela de cadastro, com ou sem um usuário previamente criado.
* Campos obrigatórios:
  * Nome completo
  * Senha
* Campos opcionais:
  * E-mail

| ID | Entrada | Resultado esperado | Resultado obtido |
| -- | ------- | ------------------ | ---------------- |
| CC1 | Nome sem o sobrenome | Bloquear e requisitar por mais um nome | |
| CC2 | Nome completo | Prosseguir | |
| CC3 | E-mail inválido | Bloquear e requisitar por um e-mail válido | |
| CC4 | E-mail já cadastrado no sistema | Bloquear e requisitar por outro e-mail | |
| CC5 | Senha com menos de 8 dígitos | Bloquear o cadastro e requisitar por uma nova senha, informando o motivo | |
| CC6 | Senha com somente letras | Bloquear o cadastro e requisitar por uma nova senha | |
| CC7 | Senha com apenas espaços | Bloquear o cadastro e requisitar por uma nova senha | |
| CC8 | Senha com apenas números | Bloquear o cadastro e requisitar por uma nova senha | |
| CC9 | Senha ultrapassando o limite de caracteres previamente estipulado | Não permitir o envio da requisição ao servidor | |
| CC10 | Pelo menos um documento com foto foi requisitado? | Sim | |

## 2 Alerta

* Pré-condições
  * O usuário deve estar dentro no sistema com a tela de envio do alerta selecionada.
* Campos obrigatórios:
  * Gravidade do alerta
  * Senha
* Campos opcionais:
  * E-mail

| ID | Entrada | Resultado esperado | Resultado obtido |
| -- | ------- | ------------------ | ---------------- |
| CA1 | Quantos passos são necessários até o envio? | 2 | |
| CA2 | Quantas gravidades estão disponíveis? | 3 | |
| CA3 | Quanto tempo levou para o alerta ser enviado e recebido na central? | máximo de 2 segundos | |
| CA4 | As informações básicas (nome, localização, etc..) foram enviadas sem serem pedidas explicitamente? | Sim | |
| CA5 | Como o alerta mais grave é exibido para o gestor? | Em vermelho, efeitos sonoros e o mais chamativo possível | |
| CA6 | Como o alerta mais grave é exibido para os moradores rurais das proximidades? | Notificação por push | |
| CA7 | O que é exibido para os moradores das proximidades? | Localização e gravidade do alerta | |
| CA8 | Os alertas com gravidade média ou abaixo foram exibidos para os moradores das proximidades? | Sim | |
| CA9 | Quais meios de segurança foram estabelecidos para que o morador rural conseguisse enviar o alerta? | Biometria e/ou análise da retina | |
| CA10 | É possível que o gestor envie um alerta? | Não | |

## 3 Relatórios

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
