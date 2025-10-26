# 🥶 Frost Compressor

FrostCompressor é um aplicativo para Windows que deixa a compressão de vídeos muito simples. Você só abre o programa, escolhe o vídeo e ele faz o resto.

## O que ele oferece

- Visual moderno, sem janelas cheias de botões confusos.
- Detecta automaticamente o tamanho original do vídeo e diz quanto vai ocupar depois.
- Usa a placa de vídeo (NVIDIA ou AMD) para deixar o processo mais rápido.
- Permite reduzir a resolução (1080p, 720p, 480p etc.) e ativar um modo que garante compatibilidade com aparelhos antigos.
- Mostra o progresso em tempo real e abre a pasta final para você assim que terminar.
- Lembra das suas preferências para a próxima vez que você abrir.

## O que vem junto

- `FrostCompressor.exe`: o aplicativo.
- `ffmpeg.exe`: ferramenta usada para analisar e comprimir os vídeos (já incluída, você não precisa baixar nada).

## Como usar

1. Abra o `FrostCompressor.exe`.
2. Clique em **Selecionar vídeo** e escolha o arquivo que deseja comprimir.
3. Aguarde a análise (o app mostra informações de duração, tamanho e resolução).
4. Ajuste o quanto quer reduzir o tamanho usando o controle deslizante (dá para ver a estimativa na hora).
5. Se quiser, marque **Reduzir resolução** e escolha um tamanho menor, ou ative o modo de compatibilidade.
6. Clique em **Comprimir vídeo**, escolha onde salvar e espere terminar. Ao final, é só clicar em **Mostrar na pasta**.

## Problemas comuns

- Se aparecer uma mensagem dizendo que o FFmpeg não foi encontrado: Confira se `ffmpeg.exe` está na mesma pasta do aplicativo.
- Se o vídeo não puder ser analisado: tente outro arquivo ou verifique se ele não está corrompido.
- Se a aceleração por GPU não funcionar: atualize os drivers da placa de vídeo.
