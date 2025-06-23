# ✅ Execução dos Casos de Teste – Login (SauceDemo)

| ID   | Caso de Teste                          | Resultado Esperado                                | Resultado Obtido                                       | Status | Observações                       |
|------|----------------------------------------|---------------------------------------------------|--------------------------------------------------------|--------|----------------------------------|
| CT01 | Login com credenciais válidas          | Redireciona para a página de Produtos                  | Redirecionou corretamente                              | OK     | —                                |
| CT02 | Login com usuário inválido             | Exibe erro de usuário inválido                    | Exibiu mensagem: "Username and password do not match" | OK     | —                                |
| CT03 | Login com senha inválida               | Exibe erro de senha incorreta                     | Exibiu mensagem de erro                                | OK     | —                                |
| CT04 | Campos vazios                          | Exibe mensagem de campos obrigatórios             | Exibiu erro corretamente                               | OK     | —                                |
| CT05 | Campo usuário vazio                    | Mensagem sobre campo obrigatório                  | Exibiu mensagem correta                                | OK     | —                                |
| CT06 | Campo senha vazio                      | Mensagem sobre campo obrigatório                  | Exibiu mensagem correta                                | OK     | —                                |
| CT07 | Usuário bloqueado                      | Mensagem: “Sorry, this user has been locked out.” | Exibiu exatamente essa mensagem                        | OK     | —                                |
| CT08 | Ocultação da senha                     | Senha aparece como pontos/asteriscos              | Senha oculta corretamente                              | OK     | —                                |
| CT09 | Redirecionamento correto após login    | URL deve ser `/inventory.html`                    | Redirecionou corretamente                              | OK     | —                                |

