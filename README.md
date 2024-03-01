<h3 align="center">Plataforma SaaS de IA para Imagens</h3>

<div align="center">
  Construa este projeto passo a passo com nosso tutorial detalhado no <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> no YouTube. Junte-se à família JSM!
</div>

## 📋 Índice

1. [Introdução](#introdução)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Funcionalidades](#funcionalidades)
4. [Quick Start](#quick-start)


## <a name="introdução">Introdução 🤖</a>

Uma plataforma SaaS de imagem com IA que oferece processamento avançado, pagamento seguro e muito mais.

## <a name="tecnologias-utilizadas">Tecnologias Utilizadas ⚙️</a>

- Next.js
- TypeScript
- MongoDB
- Clerk
- Cloudinary
- Stripe
- Shadcn
- TailwindCSS

## <a name="funcionalidades">Funcionalidades 🔋</a>

- Autenticação segura
- Exibição de imagens da comunidade
- Pesquisa avançada de imagens
- Restauração, recoloração e remoção de objetos
- Download e detalhes de imagens transformadas
- Sistema de créditos e perfil do usuário
- UI/UX responsiva

## <a name="quick-start">Quick Start 🤸</a>

Siga estes passos para configurar o projeto localmente em sua máquina.

1. **Pré-requisitos:**

   - [Git](https://git-scm.com/)
   - [Node.js](https://nodejs.org/en)
   - [npm](https://www.npmjs.com/)

2. **Clonando o Repositório:**

   ```bash
   git clone https://github.com/adrianhajdin/imaginify.git
   cd imaginify

   ```

3. **Instalação**
   ```bash
   npm install

4. **Configurando Variáveis de Ambiente:**

Crie um arquivo .env.local na raiz do projeto e adicione as variáveis necessárias conforme especificado abaixo.

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Substitua os valores fictícios pelos seus credenciais reais respectivos. Você pode obter esses credenciais se inscrevendo no [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)

**Running the Project**

```bash
npm run dev
```
