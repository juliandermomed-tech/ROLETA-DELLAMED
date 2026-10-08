# Roleta Dellamed — painel de pedidos

`index.html` é o painel. Ele lê a planilha "Controle Roleta Dellamed — Pedidos" publicada na Web
ao abrir, a cada 5 minutos e no botão "Atualizar agora". O link fica na linha `const CSV_URL=...`.

Os pedidos precisam ficar na aba publicada, com o cabeçalho
`#, Situação, Data, Cliente, UTM/Marketplace, Pagamento, Envio, Total (R$), Cupom`.
Enquanto a planilha estiver vazia, o painel mostra os pedidos dos CSVs de 28/09.

## Publicar no GitHub Pages
Envie os arquivos para a raiz do repositório e vá em
Settings → Pages → Source: "Deploy from a branch" → branch `main`, pasta `/ (root)` → Save.

Atenção: o painel e o CSV publicado mostram nomes de clientes a quem tiver o link.
