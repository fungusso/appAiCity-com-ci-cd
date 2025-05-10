
Este é um projeto Expo criado com create-expo-app.

## inicio

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

Na saída, você encontrará opções para abrir o aplicativo em um

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), 


## CI/CD com Codemagic

Este projeto utiliza Codemagic para a esteira CI/CD com os seguintes passos:

1. Instalação de dependências
2. Lint com ESLint
3. Testes unitários com Jest
4. Build Android simulado (pode ser ajustado para builds reais)
5. Publicação de APK como artefato

### Comandos úteis

```bash
npm install        # instala dependências
npm run lint       # executa eslint
npm test           # executa testes unitários
npm run build-android  # simula build do APK
```
