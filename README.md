# Painel Administrativo React (Customizado)

Este é um painel administrativo construído com **React** e **Tailwind CSS**

| Home | 
|-------|
| ![Home](/1.png)

## 🔑 Autenticação Simulada

O formulário de login está configurado para aceitar apenas um conjunto de credenciais específicas para simulação de autenticação:

- **Email:** `admin@example.com`  
- **Senha:** `123456`

Caso os dados estejam corretos, o usuário é redirecionado para a página inicial (`/`). Se estiverem incorretos, é exibida uma mensagem de erro.

---

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router DOM](https://reactrouter.com/en/main) (v6+)

---

## 📂 Estrutura do Projeto

```bash
src/
├── components/
│   ├── form/
│   │   ├── Label.tsx
│   │   └── input/
│   │       └── InputField.tsx
│   ├── icons/
│   │   ├── EyeIcon.tsx
│   │   └── EyeCloseIcon.tsx
│   └── ui/
│       └── button/
│           └── Button.tsx
├── pages/
│   └── SignInForm.tsx
├── App.tsx
└── main.tsx

---


## 📦 Instalação

Clone o repositório e instale as dependências:

git clone https://github.com/Ferrozo/Dashboard-Teste-Pratico
cd Dashboard-Teste-Pratico

npm install
npm run dev
