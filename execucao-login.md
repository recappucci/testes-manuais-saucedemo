# ✅ Execução dos Casos de Teste – Login (SauceDemo)

| ID   | Caso de Teste                          | Resultado Esperado                                | Resultado Obtido                                       | Status | Observações                       |
|------|----------------------------------------|---------------------------------------------------|--------------------------------------------------------|--------|----------------------------------|
| CT01 | Login com credenciais válidas          | Login bem-sucedido e redirecionamento para página de produtos                  | Login realizado e redirecionado corretamente                              | OK     | —                                |
| CT02 | Login com usuário inválido             | Mensagem de erro: "Username and password do not match any user in this service"                    | Exibiu mensagem de erro corretamente | OK     | —                                |
| CT03 | Login com senha inválida               | Mensagem de erro sobre senha incorreta                     | Exibiu mensagem de erro                                | OK     | —                                |
| CT04 | Campos vazios                          | Exibe mensagem de campos obrigatórios             | Não exibiu mensagem correta                               | NOK     | —                                |
| CT05 | Campo usuário vazio                    | Mensagem de erro sobre usuário obrigatório                  | Exibiu mensagem correta                                | OK     | —                                |
| CT06 | Campo senha vazio                      | Mensagem sobre campo obrigatório                  | Exibiu mensagem correta                                | OK     | —                                |
| CT07 | Usuário bloqueado                      | Mensagem: “Sorry, this user has been locked out.” | Exibiu exatamente essa mensagem                        | OK     | —                                |
| CT08 | Ocultação da senha                     | Senha aparece como pontos/asteriscos              | Senha oculta corretamente                              | OK     | —                                |
| CT09 | Redirecionamento correto após login    | URL deve ser `/inventory.html`                    | Redirecionou corretamente                              | OK     | —                                |

