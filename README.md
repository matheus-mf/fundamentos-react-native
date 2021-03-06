<h1 align="center">Fundamentos do React Native</h1>

É a versão do React para desenvolvimento móvel. O React Native é multiplataforma, consiste no desenvolvimento de um
único código-fonte que será executado em diferentes dispositivos, como iOS e Android, também é possível fazer
manipulação de elementos dentro em cada plataforma. Ele converte o código JavaScript desenvolvido para a interface
nativa da plataforma, mas não faz toda a transpilação do código, ele injeta uma dependência chamada JavaScriptCore em
dispositivos móveis que permite que eles entendam JavaScript.

## Arquitetura

![Arquitetura do react native](.github/arquitetura-react-native.png)

[React-Native — Arquitetura e comparações](https://medium.com/datainfo/react-native-arquitetura-e-compara%C3%A7%C3%B5es-1663f77e0a57)

## Sintaxe

![Sintaxe de componentes do react native](.github/sintaxe-componentes-react-native.png)

A forma de criar componentes é semelhante ao desenvolvimento web ReactJS. Porem HTML não é usado, mas sim componentes do
próprio React Native.

![Sintaxe de Style do react native](.github/sintaxe-style-react-native.png)

Nem um elemento no React Native não tem estilização própria.

## Configuração do Ambiente React Native

[Ambiente React Native](https://react-native.rocketseat.dev/)

## Componentes do React Native

Os [componentes](https://reactnative.dev/docs/components-and-apis) do React Native não possuem valor semântico
(significado) e também não possuem estilização própria.

![Diferenças do ReactJS](.github/diferencas-do-reactjs.png)

- Por padrão todos os componentes do React Native possuem `display: flex`.
- Dentro do React Native não existe herança de estilos.


## Conexão com API

- iOS com Emulador: `http://localhost`
- iOS com físico: `http://<IP da maquina>`
- Android com Emulador: `http://localhost` precisa roda `adb reverse tcp:<PORT> tcp:<PORT>`
- Android com Emulador: `http://10.0.2.2` quando estiver usando o emulador do Android Studio
- Android com Emulador: `http://10.0.2.2` quando estiver usando o emulador do Genymotion
- Android com físico: `http://<IP da maquina>`

