# Pool Aim Overlay (Android)

Aplicativo Android nativo de mira visual manual para treino. Não lê a tela do jogo, não automatiza tacadas e não interage com contas.

## Abrir e gerar APK
1. Instale o Android Studio em um computador.
2. Abra a pasta `PoolAimOverlay` no Android Studio.
3. Aguarde a sincronização do Gradle.
4. Use **Build > Build APK(s)**.
5. O APK de depuração ficará em `app/build/outputs/apk/debug/app-debug.apk`.
6. Instale no Android e abra **Pool Aim Overlay**.
7. Toque em **Permitir sobreposição**, habilite a permissão nas configurações do Android e volte ao app.
8. Toque em **Iniciar mira flutuante**. Depois abra o 8 Ball Pool.

## Controles
- Arraste o círculo verde para reposicionar a origem.
- Arraste o marcador vermelho para mudar ângulo e comprimento.
- Use as barras do painel para ajustes finos.
- Arraste o título do painel para movê-lo.
- Ocultar mira ou fechar encerra a camada visual.

A sobreposição depende da permissão do Android e pode variar conforme o fabricante e as políticas do jogo. A linha é uma referência visual, não uma previsão precisa da física do jogo.
