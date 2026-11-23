# DH Trompete Game

Game estilo Guitar Hero para aprender os hinos no trompete.

- **Telas:** início, escolha do hino (busca por número/título, com estrelas), configurações e o game.
- **Jogo (simulação do instrumento):** as notas descem em 3 colunas (pistos 1, 2 e 3). Na hora da nota, seus dedos precisam estar na **posição** dela. Não é preciso bater: o jogo reconhece a posição.
  - **Nota solta** (barra larga "SOLTA") = nenhum pisto: tire os dedos da tela.
  - **Nota repetida:** continue segurando o(s) pisto(s); o novo "sopro" é reconhecido sozinho.
  - Ao acertar, a nota toca (som de trompete).
- **Vozes:** soprano, contralto, tenor ou baixo. Tenor e baixo sobem 1 oitava e depois são encaixados no alcance do trompete. As outras vozes tocam sozinhas como acompanhamento (pode desligar).
- **Trompete:** Si♭ (padrão) ou Dó; a digitação usa a tabela do app DigitaHinos Trompete.
- **Modos:** Normal (digitação) e Fácil (basta tocar no tempo). Velocidade do hino de 40% a 120%, tolerância de tempo, velocidade da queda, nomes das notas, ajuste de atraso do som.
- **Teclado (computador):** J K L (ou 1 2 3) = pistos, Esc = pausa.

## Publicar
Suba tudo no GitHub Pages. A cada versão nova, mude `CACHE_NAME` em `sw.js`.
Para o APK: Actions → "Gerar APK" (usa os mesmos *secrets* de assinatura dos outros apps).
Os hinos ficam em `hinos/` (arquivos .mxl + `index.json`).

## Modo Pro (bloqueio)
- Site/PWA e APK: hinos 1–50 grátis, demais 15 s de prévia; Pro por Pix + código na planilha.
- Google Play: hinos 1–10 grátis, demais por anúncio premiado (1 h) ou Pro pela Play.
- Configuração em `pro-config.js`; planilha em `planilha-pro/`; passo a passo da Play em `PUBLICAR-PLAY.md`.
