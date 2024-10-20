# Seja bem-vindo ao aplicativo "Video&Video" 👋

Versão adicional do aplicativo [Video&Video](https://github.com/RTVidal/teste-rpc) com ajustes e melhorias implementadas após a data de disponibilização do projeto. Versão em repositório separado a fim de não alterar o código-fonte do repositório original após o período estabelecido para desenvolvimento no documento de especificação do projeto.

## Alterações em relação à versão original:

- Posts fixos com vídeos variados
- Vídeos de posts fixos com thumbnails com imagens ao invés de apenas cores
- Implementação de controle para não permitir a execução simultânea de dois ou mais vídeos, evitando lentidão, travamentos e crashs
- Implementação de controle para encerrar execução de vídeo ao sair do componente
- Correção de bug de cor da estrutura de abas da home onde, caso dispositivo em modo escuro, a opção selecionada não ficava visível
- Melhor organização do código-fonte

Projeto [Expo](https://expo.dev) criado com [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

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

Opção 3: Instalar diretamente a apk gerada via **eas build** e disponibilizada no ambiente **expo.dev**

Disponível em [https://expo.dev/accounts/rafaelvidal/projects/teste-rpc-2/builds/8319e475-8032-4261-8b22-7cc69edb534a](https://expo.dev/accounts/rafaelvidal/projects/teste-rpc-2/builds/8319e475-8032-4261-8b22-7cc69edb534a)

## Observações gerais

Devido à limitações de dispositivos para desenvolvimento e testes, o projeto foi desenvolvido com foco em ambiente Android

O aplicativo possui um módulo interno simulando uma api, dispensando conexão com a internet.

Em caso de dúvidas, é possível entrar em contato através do email **rafaelvidal4@gmail.com**.
