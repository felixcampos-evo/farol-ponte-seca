# Farol Ponta Seca — projeto Android

Este projeto empacota o jogo HTML original em um aplicativo Android nativo usando WebView local. O jogo roda sem internet e abre em tela cheia.

## Gerar e instalar o APK
1. Instale o Android Studio (versão recente) e o Android SDK Platform 35.
2. Abra esta pasta (`FarolPontaSecaAndroid`) no Android Studio.
3. Aguarde a sincronização do Gradle e aceite a instalação dos componentes solicitados.
4. Conecte um celular Android com depuração USB ativada ou use um emulador.
5. Selecione **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. O APK de teste será gerado em `app/build/outputs/apk/debug/app-debug.apk`.
7. Transfira o APK para o celular e abra-o para instalar (talvez seja necessário permitir a instalação para esse app de arquivos).

## Observações
- Nome exibido: Farol Ponta Seca.
- Identificador inicial: `com.farolpontaseca.game`.
- Orientação: paisagem, adequada ao enquadramento do jogo.
- O HTML original está em `app/src/main/assets/index.html`.
- Este é um projeto-fonte Android pronto para abrir e compilar no Android Studio; não é ainda um APK assinado nem uma publicação na Play Store.
