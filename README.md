# Seja bem-vindo ao aplicativo "Video&Video" 👋

Aplicativo desenvolvido com o objetivo de estudar funcionalidades das versões mais recentes de React Native e Expo, focando em funcionalidades navegação, gerenciamento de sessão, upload de vídeo, gravação com câmera, play em vídeo e armazenamento de arquivos.

## Instalar e executar o aplicativo

Após o downlod do repositório, executar os seguintes comandos para rodar o projeto localmente em um emulador ou dispositivo android conectado

Opção 1: Gerar build localmente

1. Instalar dependências

   ```bash
   npm install
   ```

2. Gerar um build local

   ```bash
   npx expo run:android
   ```

3. Iniciar o aplicativo e o servidor de desenvolvimento

   ```bash
    npx expo start
   ```

4. Seguir as instruções do prompt para atualizar o aplicativo no dispositivo

Opção 2: Gerar build via **eas**

1. Instalar dependências

   ```bash
   npm install
   ```

2. Gerar um build

   ```bash
   eas build --platform android --profile development
   ```

3. Iniciar o aplicativo e o servidor de desenvolvimento

   ```bash
    npx expo start
   ```

4. Seguir as instruções do prompt para atualizar o aplicativo no dispositivo

## Observações gerais

Devido à limitações de dispositivos para desenvolvimento e testes, o projeto foi desenvolvido com foco em ambiente Android.

O aplicativo possui um módulo interno simulando uma api, dispensando conexão com a internet.
