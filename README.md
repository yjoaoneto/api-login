Um projeto desenvolvido baseado em estudos com canais do youtube como o "Will dev" e "Matheus Battisti - Hora de Codar", meu objetivo é fazer uma aplicação completa para cadastros de gastos e gerenciamento financeiro mensal.

Esse projeto React foi estruturado para gerenciar autenticação de usuários, utilizando Context API e localStorage para salvar o estado de login e registro dos usuários. 
Por se tratar do react 18, utilizei o método createRoot para uma inicialização mais otimizada.

Contexto de Autenticação: Configurado em contexts/auth, ele armazena e gerencia o estado do usuário.
App.js: Configura o provedor de autenticação ao redor das rotas e estilos globais, permitindo que a autenticação seja acessível em toda a aplicação.
useAuth: Simplifica o acesso ao AuthContext para componentes que precisem autenticar ou verificar o estado do usuário.

A parte de cada elemento foi separado em pastas como "Button", "Signin", "Signup",etc, para melhor organização e possível alterações futuras. 

# api-login with yarn
