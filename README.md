# PoolAimOverlay

Aplicativo Android simples com mira visual flutuante transparente e controles de ângulo/comprimento. Não lê a tela do jogo, não altera o jogo e não automatiza tacadas.

## Gerar APK pelo GitHub (celular)
1. Crie um repositório GitHub vazio chamado `PoolAimOverlay`.
2. Envie todos os arquivos desta pasta para a raiz do repositório, mantendo a pasta `.github/workflows`.
3. Abra a aba **Actions** e execute **Build PoolAimOverlay APK** (ou aguarde o build após enviar para `main`).
4. Abra a execução concluída e baixe o artefato `PoolAimOverlay-debug`.
5. Extraia o ZIP do artefato e instale `app-debug.apk`.

## Uso
1. Abra Pool Aim Overlay.
2. Toque em **ATIVAR MIRA E ABRIR JOGO**.
3. Na tela de permissão do Android, permita **Exibir sobre outros apps** e volte ao aplicativo.
4. A mira e o painel flutuante devem aparecer ao abrir o 8 Ball Pool. Use Ângulo +/- e Mira +/-; **Ocultar** alterna a linha e **Fechar** encerra a sobreposição.

O identificador de pacote esperado do jogo é `com.miniclip.eightballpool`. Se a versão instalada usar outro identificador ou o jogo não for encontrado, abra o jogo manualmente após ativar a mira.
