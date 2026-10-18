# Pool Aim Overlay Smart (Flutter/Dart)

Projeto original de referência para uma ferramenta visual de mira com recorte geométrico dentro de uma mesa calibrada.

## O que está incluído
- Interface Flutter com ajuste de ângulo, comprimento, cor e número de reflexões.
- Calibração manual de quatro cantos.
- Motor geométrico em Dart com recorte estrito dentro de um quadrilátero (inclui mesa em perspectiva); se a origem estiver fora da mesa, não desenha a linha.
- Reflexões opcionais nas bordas.
- Testes unitários para o motor geométrico.

## Limitação importante
Este ZIP é o **código-fonte**, não um APK já compilado. A tela de calibração é uma prévia local; a integração real como janela Android sobre outros apps precisa ser conectada a um plugin de overlay compatível com a versão Flutter/Android escolhida e testada no aparelho. O projeto não acessa nem modifica a memória do 8 Ball Pool e não detecta automaticamente a mesa. Calibre os quatro cantos manualmente.

## Compilar
1. Instale Flutter SDK em um computador ou use um ambiente de build em nuvem que suporte Flutter.
2. Extraia o ZIP e abra a pasta `PoolAimOverlaySmart`.
3. Execute `flutter pub get`.
4. Execute `flutter test`.
5. Execute `flutter run` para testar.
6. Para gerar APK: `flutter build apk --debug`.
7. O APK, se a compilação terminar com sucesso, ficará em `build/app/outputs/flutter-apk/app-debug.apk`.

Para compilar apenas pelo celular, configure um workflow de GitHub Actions com Flutter instalado. A geração do APK não foi executada neste ambiente.
