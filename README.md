# Lojia-404
# 📦 Projeto Vue 3 (Vue primeiro, Bootstrap depois)

Este projeto foi criado **inicialmente como um projeto Vue 3 puro**, utilizando Vite. Após a criação do projeto base, o **Bootstrap 5 foi instalado e configurado manualmente** como framework CSS.

---

## 🛠️ Pré-requisitos

Antes de clonar e rodar o projeto, certifique-se de ter instalado:

* **Node.js** (versão LTS recomendada)
* **npm** (vem junto com o Node.js)
* **Git**

Verifique as versões:

```bash
node -v
npm -v
git --version
```

---

## 📥 Clonar o Repositório

Clone o projeto para sua máquina local:

```bash
git clone https://github.com/Developers-4-0-4/project-lojia404.git
```

Entre na pasta do projeto:

```bash
cd lojia-404
```

---

## 📦 Instalar as Dependências

Execute o comando abaixo para instalar todas as dependências do projeto:

```bash
npm install
```

> Este comando instala o Vue, Vite, Bootstrap e todas as dependências necessárias.

---

## ▶️ Rodar o Projeto em Desenvolvimento

Após instalar as dependências, execute:

```bash
npm run dev
```

O projeto será iniciado em modo de desenvolvimento.

Acesse no navegador:

```
http://localhost:5173
```

---

## 🎨 Bootstrap

O Bootstrap foi adicionado **após a criação do projeto Vue**, através do npm, e está configurado no arquivo `src/main.js` ou `src/main.ts`.

Dependências utilizadas:

* `bootstrap`
* `@popperjs/core`

---

## 🏗️ Build para Produção

Para gerar a versão de produção do projeto:

```bash
npm run build
```

Os arquivos finais serão gerados na pasta:

```
dist/
```

---

## 📂 Estrutura Básica do Projeto

```
meu-projeto-vue
├── src
│   ├── assets
│   ├── components
│   ├── App.vue
│   └── main.js
├── index.html
├── package.json
├── vite.config.js
└── README.md
```