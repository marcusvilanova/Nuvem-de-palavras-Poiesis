# Painel de avaliações com nuvem de palavras

Painel em uma única página HTML para acompanhar avaliações de atividades: lê uma planilha do Google publicada em CSV, mostra a distribuição das notas e gera uma nuvem com as palavras mais frequentes nos comentários.

## O que o painel faz

- Carrega os dados direto de uma planilha publicada (`sheetUrl` na configuração), sem servidor.
- Filtros por unidade, período, nota mínima e palavra-chave.
- Gráfico de notas com Chart.js.
- Nuvem de palavras com wordcloud2.js, descartando palavras sem significado (artigos, preposições e verbos auxiliares em português).

## Como usar

1. Publique a planilha de avaliações no Google Sheets como CSV (Arquivo → Compartilhar → Publicar na Web).
2. Troque `SEU_ID_DA_PLANILHA` em `config.sheetUrl` pelo endereço publicado.
3. Abra `index.html` no navegador ou publique a pasta em qualquer hospedagem estática.

## Stack

HTML · JavaScript · Bootstrap · Chart.js · wordcloud2.js
