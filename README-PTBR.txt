MEU TRAILER — PROJETO ANDROID OFFLINE

Este projeto empacota a tela e as funções do Meu Trailer dentro do próprio APK.
O aplicativo abre a página local file:///android_asset/www/index.html.
Não usa Cloudflare, hospedagem, Firebase ou conexão com a internet.

DADOS:
- Os dados ficam no armazenamento local do WebView (localStorage) de cada aparelho.
- Cada celular terá seus próprios produtos, vendas, estoque e caixa.
- Não há sincronização entre aparelhos.
- Exporte backups pelo menu Configurações do aplicativo.

COMPILAÇÃO PELO CELULAR (GitHub Actions):
1. Extraia este ZIP.
2. Crie um repositório no GitHub pelo navegador do celular.
3. Envie todos os arquivos e pastas deste projeto para a raiz do repositório.
4. Abra a aba Actions do repositório.
5. Se solicitado, habilite GitHub Actions.
6. Execute "Build Meu Trailer APK" (Run workflow) ou aguarde a compilação após enviar os arquivos.
7. Quando terminar, abra a execução concluída, vá em Artifacts e baixe "Meu-Trailer-APK".
8. Extraia o arquivo baixado e instale app-debug.apk no Android.

IMPORTANTE:
- Este ZIP é o projeto-fonte pronto para compilação, NÃO é um APK já compilado.
- A compilação é feita nos servidores do GitHub Actions; não exige computador, mas exige conta GitHub e internet durante a compilação/baixar o APK.
- Depois de instalado, o app abre os arquivos incluídos no APK e funciona sem internet.
- A compilação debug é assinada para teste. Se for publicar futuramente na Play Store, será necessária uma assinatura de lançamento própria.
- O lembrete de reservas da versão web verifica a cada 15 segundos enquanto o app está aberto. Alarmes com o app fechado ainda não são garantidos nesta versão.
