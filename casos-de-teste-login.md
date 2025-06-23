# Casos de Teste – Funcionalidade de Login (SauceDemo)

| ID   | Título do Caso de Teste                  | Pré-condição             | Passos                                                           | Resultado Esperado                                   | Status |
|------|------------------------------------------|---------------------------|------------------------------------------------------------------|------------------------------------------------------|--------|
| CT01 | Login com credenciais válidas            | Site acessível           | 1. Acessar o site SauceDemo<br>2. Preencher usuário "standard_user"<br>3. Preencher senha "secret_sauce"<br>4. Clicar em "Login" | Login bem-sucedido e redirecionamento para página de produtos |        |
| CT02 | Login com usuário inválido               | Site acessível           | 1. Preencher usuário "usuario_invalido"<br>2. Preencher senha "secret_sauce"<br>3. Clicar em "Login" | Mensagem de erro: "Username and password do not match any user in this service" |        |
| CT03 | Login com senha inválida                 | Site acessível           | 1. Preencher usuário "standard_user"<br>2. Preencher senha inválida<br>3. Clicar em "Login" | Mensagem de erro sobre senha incorreta               |        |
| CT04 | Login com campos vazios                  | Site acessível           | 1. Clicar em "Login" sem preencher usuário e senha             | Exibir mensagem de erro de campos obrigatórios       |        |
| CT05 | Login com campo de usuário vazio         | Site acessível           | 1. Deixar campo usuário vazio<br>2. Preencher senha "secret_sauce"<br>3. Clicar em "Login" | Mensagem de erro sobre usuário obrigatório           |        |
| CT06 | Login com campo de senha vazio           | Site acessível           | 1. Preencher usuário "standard_user"<br>2. Deixar campo senha vazio<br>3. Clicar em "Login" | Mensagem de erro sobre senha obrigatória             |        |
| CT07 | Login com usuário bloqueado              | Site acessível           | 1. Preencher usuário "locked_out_user"<br>2. Preencher senha "secret_sauce"<br>3. Clicar em "Login" | Mensagem: "Sorry, this user has been locked out."    |        |
| CT08 | Verificar ocultação da senha             | Site acessível           | 1. Inserir senha no campo password                              | Caracteres devem ser exibidos como pontos ou asteriscos |        |
| CT09 | Verificar redirecionamento correto após login | Site acessível     | 1. Login com usuário "standard_user"<br>2. Senha "secret_sauce" | Usuário é redirecionado para a página `/inventory.html` |        |

