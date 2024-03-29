# Login no Sistema

### Objetivo

O objetivo deste documento é fornecer orientações detalhadas para realizar testes manuais do recurso de login do sistema. O teste deve garantir que o login seja executado corretamente e que os usuários possam acessar a página de dashboard conforme esperado.

### Cenários de Teste

| Cenário 1: Login com Sucesso |  |
| ---------------------------- | -- |
| Pré-requisitos | O sistema está acessível e o usuário possui credenciais válidas. |
| Passo 1 | Acesse a página de login do sistema. |
| Passo 2 | Insira um nome de usuário válido e uma senha correta. |
| Passo 3 | Clique no botão de **ENTRAR**. |
| Resultado Esperado | O usuário deve ser redirecionado para a página de dashboard e o título de boas-vindas deve ser exibido corretamente. |

| Critérios de Aceitação | |
|------------------------|-|
| - O login deve ser possível com credenciais válidas. | |
| - O redirecionamento para a página de dashboard deve ocorrer após o login bem-sucedido. | |

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

