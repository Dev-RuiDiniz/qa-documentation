# 🧩 Casos de Teste – BDD

## Cenário 1 — Login bem-sucedido
```gherkin
Funcionalidade: Login de Usuário
  Cenário: Login com credenciais válidas
    Dado que o usuário está na tela de login
    Quando ele digita um e-mail e senha válidos
    E clica em “Entrar”
    Então o sistema deve autenticar e redirecionar para o dashboard
