# Radar de Influência bLOw: dados

Histórico semanal do **Radar de Influência bLOw**, lido pelo dashboard do Radar.

- `semanas/AAAA-MM-DD.json`: a "foto" de cada semana. O nome do arquivo é a segunda-feira da semana.
- `indice.json`: lista das semanas com o resumo de cada uma.

Toda segunda-feira o Radar roda no Mac da Natália, grava a semana nova e envia para cá.
As semanas anteriores **nunca são alteradas**. Se o Radar rodar de novo na mesma semana, só a foto daquela semana é substituída.

Os dados vêm da rota pública do dashboard de influenciadores e **não contêm telefones nem contatos**,
só unidade, @ do Instagram, datas de parceria e situação de uso do cupom.

As semanas com `"origem": "importado"` foram reconstruídas a partir dos relatórios enviados no chat
e não trazem a lista completa de influenciadoras por unidade (`"unidades": null`).
