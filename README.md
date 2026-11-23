# DigitaHinos Game (Trompete)

Game estilo Guitar Hero para aprender os hinos no trompete.

- **Telas:** início, escolha do hino (busca por número/título, com estrelas), configurações e o game.
- **Jogo:** as notas descem em 3 colunas (pistos 1, 2 e 3). Nota que usa dois ou três pistos aparece em várias colunas ligadas; nota larga ("ABERTO") = nenhum pisto, toque na barra ABERTO. Ao acertar, a nota toca (som de trompete).
- **Vozes:** soprano, contralto, tenor ou baixo. Tenor e baixo sobem 1 oitava e depois são encaixados no alcance do trompete (mesma regra do DigitaHinos Trompete). As outras vozes tocam sozinhas como acompanhamento (pode desligar).
- **Trompete:** Si♭ (padrão) ou Dó; a digitação usa a mesma tabela do app DigitaHinos Trompete.
- **Modos:** Normal (precisa da digitação certa) e Fácil (basta tocar no tempo). Velocidade do hino de 40% a 120%, tolerância de tempo, velocidade da queda, nomes das notas (Dó Ré Mi ou C D E), ajuste de atraso do som.
- **Teclado (computador):** J K L (ou 1 2 3) = pistos, Espaço = aberto, Esc = pausa.

## Publicar
Suba tudo no GitHub Pages. A cada versão nova, mude `CACHE_NAME` em `sw.js`.
Para o APK: Actions → "Gerar APK" (mesmo fluxo dos outros apps; usa os mesmos *secrets* de assinatura).
Os hinos ficam em `hinos/` (arquivos .mxl + `index.json`).
