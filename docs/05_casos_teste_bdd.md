# 🧩 Casos de Teste – BDD

## Cenário 1 — Login bem-sucedido
```gherkin
Funcionalidade: Login de Usuário
  Cenário: Login com credenciais válidas
    Dado que o usuário está na tela de login
    Quando ele digita um e-mail e senha válidos
    E clica em “Entrar”
    Então o sistema deve autenticar e redirecionar para o dashboard


## Cenário 2 - Login inválido
```gherkin
Funcionalidade: Login de Usuário
  Cenário: Login com credenciais inválidas
    Dado que o usuário está na tela de login
    Quando ele insere uma senha incorreta
    Então o sistema deve exibir a mensagem "Credenciais inválidas"
