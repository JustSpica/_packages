# Personal ESLint configuration

## 📚 Descrição

Esse é um simples pacote de configurações para o ESLint com diversos plugins para o React focados em produtividade, performance e acessibilidade. 

## 🌟 O que está incluso no pacote ?

- [X] Configuração base Standard
- [X] React plugin
- [X] React Hooks plugin
- [X] JSX a11y plugin
- [X] Prettier

## 🚪 Como fazer a instalação

Instalando as dependências:
```bash
# usando npm. 
npm i eslint @spica-dev/eslint-config -D

# usando pnpm. 
pnpm i eslint @spica-dev/eslint-config -D
```

Dentro do arquivo `.eslintrc.json` extenda o pacote com a sua configuração:
```
{
  "extends": "@spica-dev/eslint-config/react"
}
```

Feito de 💖 por Guilherme Spica Luiz 👋 [De uma olhada em meu Linkedin](https://www.linkedin.com/in/guilhermespicaluiz)