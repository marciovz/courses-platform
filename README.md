# REDUX

## Criando projeto 

```sh
# Criando projeto com vite
npm create vite@latest react-redux-zustand --use-npm
```

## Bibliotecas

```sh
# Instalando a biblioteca do Redux toolkit
npm install @reduxjs/toolkit

# Instalando a biblioteca de integração react-redux
npm install react-redux
```

## Configurando o Tailwind

```sh
# Instalando as bibliotecas
npm install -D tailwindcss postcss autoprefixer

# Iniciando os arquivos de configuração
npx tailwindcss init
```

Arquivo tailwind.config.js

```js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    './src/**/*.tsx',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Arquivo styles/global.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Adicionar as extensões do VScode

```
PostCSS Language Support
csstools
Identifier: csstools.postcss
```

```
Tailwind CSS IntelliSense
tailwind labs
identifier: bradlc.vscode-tailwindcss
```