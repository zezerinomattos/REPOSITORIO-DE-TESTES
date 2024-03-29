# Login no Sistema

### Objetivo

O objetivo deste documento é fornecer orientações detalhadas para realizar testes manuais no recurso de login do sistema. Estes testes visam garantir que, ao inserir uma senha incorreta, o login seja recusado corretamente, e que os usuários sejam notificados quando seus dados de login estiverem incorretos, assegurando assim a segurança e a eficácia desse processo.

### Cenários de Teste

| Cenário 2: Login com Falha de Senha |  |
| ---------------------------- | -- |
| Pré-requisitos | O sistema está acessível e o usuário possui credenciais válidas. |
| Passo 1 | Acesse a página de login do sistema. |
| Passo 2 | Insira um nome de usuário válido e uma senha incorreta. |
| Passo 3 | Clique no botão de **ENTRAR**. |
| Resultado Esperado | Deve ser exibida uma mensagem de alerta abaixo do campo de senha indicando o erro. ["Ops, seus dados de login estão incorretos!"] |

| Critérios de Aceitação | |
|------------------------|-|
| - O login deve falhar corretamente com credenciais inválidas. | |
| - A mensagem de erro deve ser exibida quando o login falha devido a uma senha incorreta. | |

| Ambiente de Teste | |
|-------------------|-|
| - URL do Sistema: | [Inserir URL aqui] |
| **Credenciais de Teste:** | |
| - Nome de Usuário: | [Inserir nome de usuário de teste aqui] |
| - Senha: | [Inserir senha de teste aqui] |

| Observações | |
|-------------|-|
| - Certifique-se de limpar os cookies e o cache do navegador antes de cada teste. | |
| - Registre cuidadosamente quaisquer problemas encontrados durante os testes, incluindo passos reproduzíveis e capturas de tela, se necessário. | |


