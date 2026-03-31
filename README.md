# Blog Pessoal - João Luciano

Um blog pessoal construído com React + TypeScript + SCSS, utilizando estética Frutiger Aero e hospedado no GitHub Pages. O blog permite que apenas o proprietário crie postagens, enquanto seguidores autenticados com Google podem comentar.

## 🚀 Funcionalidades

- **Autenticação**: Login do proprietário e Google Auth para seguidores
- **Gerenciamento de Posts**: CRUD completo para posts em Markdown
- **Sistema de Comentários**: Moderado com aprovação do proprietário
- **Temas**: Azul, Verde e Branco (Frutiger Aero)
- **Responsivo**: Design adaptável para mobile e desktop
- **Deploy Automático**: GitHub Pages com GitHub Actions

## 🛠️ Tecnologias

- **Frontend**: React 19 + TypeScript + Vite
- **Estilização**: SCSS com estética Frutiger Aero
- **Backend**: Firebase (Auth, Firestore, Storage)
- **Roteamento**: React Router
- **Animações**: Framer Motion
- **Markdown**: React Markdown + Gray Matter

## 📋 Pré-requisitos

- Node.js 18+
- Conta Google (para Firebase)
- Git

## 🎨 Estética Frutiger Aero

O design utiliza os princípios do Frutiger Aero:

- Vidro fosco (backdrop-filter: blur)
- Reflexos sutis
- Bordas arredondadas
- Sombras suaves
- Gradientes suaves

## 🔒 Segurança

- Autenticação obrigatória para comentários
- Moderação de comentários pelo proprietário
- Regras de segurança no Firestore
- Variáveis de ambiente para chaves sensíveis

## 📝 Próximos Passos

- [ ] Implementar dashboard admin para gerenciamento de posts
- [ ] Sistema de notificações para novos comentários
- [ ] Upload de imagens para posts
- [ ] Sistema de categorias/tags
- [ ] PWA (Progressive Web App)
- [ ] SEO otimizado
- [ ] Analytics com Firebase

## 📄 Licença

Este projeto é pessoal e não possui licença específica.
