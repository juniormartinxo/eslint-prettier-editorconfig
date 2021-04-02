# Instalar ESLINT + PRETTIER + EDITORCONFIG

## Instalando o ESLINT

npm i eslint -D

### Configurando o ESLINT
> npx eslint --init
√ How would you like to use ESLint? · style       
√ What type of modules does your project use? · esm
√ Which framework does your project use? · react
√ Does your project use TypeScript? · No / Yes
√ Where does your code run? · browser
√ How would you like to define a style for your project? · guide
√ Which style guide do you want to follow? · airbnb
√ What format do you want your config file to be in? · JSON
Checking peerDependencies of eslint-config-airbnb@latest
The config that you've selected requires the following dependencies:
eslint-plugin-react@^7.21.5 eslint-config-airbnb@latest eslint@^5.16.0 || ^6.8.0 || ^7.2.0 eslint-plugin-import@^2.22.1 eslint-plugin-jsx-a11y@^6.4.1 eslint-plugin-react-hooks@^4 || ^3 || ^2.3.0 || ^1.7.0
√ Would you like to install them now with npm? Yes


## Instalando o Prettier
> npm i prettier eslint-config-prettier eslint-plugin-prettier babel-eslint -D
