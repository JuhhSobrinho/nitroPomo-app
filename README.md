# nitroPomo-app

Aplicativo mobile feito com React Native e Expo, com o objetivo de apoiar a técnica Pomodoro para gerenciamento de tempo. O projeto está em fase inicial: o código atual ainda é o modelo padrão gerado pelo Expo.

## Funcionalidades

Estado atual do código:

- Tela inicial padrão do Expo, com um texto de exemplo e a barra de status.

Objetivo do projeto (ainda não implementado no código):

- Temporizador no estilo Pomodoro para ciclos de foco e pausa.

## Tecnologias

- React 18.2
- React Native 0.72
- Expo ~49 (com `expo-status-bar`)
- Babel (`babel-preset-expo`)

## Estrutura

```
nitroPomo-app/
├── App.js              # componente principal (tela padrão)
├── app.json            # configuração do Expo (nome, ícones, splash)
├── babel.config.js     # configuração do Babel
├── package.json        # dependências e scripts
└── assets/             # ícones e imagem de splash
```

## Como executar

```bash
npm install
npm start
```

Scripts disponíveis no `package.json`:

- `npm run android`: abre no Android (`expo start --android`).
- `npm run ios`: abre no iOS (`expo start --ios`).
- `npm run web`: abre a versão web (`expo start --web`).

Para testar em um dispositivo físico, use o aplicativo Expo Go, a confirmar.

## Observações

- A funcionalidade de Pomodoro ainda não foi implementada; o `App.js` contém apenas a tela padrão do Expo.
- Não há testes automatizados configurados (a confirmar).
- Versão do Node.js recomendada: a confirmar.

## Autor

Desenvolvido por [Juliano Sobrinho](https://github.com/JuhhSobrinho).
