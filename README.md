# 100 Receitas Naturais — página de vendas + upsell

Página estática de vendas do e-book **100 Receitas Naturais** e página de upsell pós-compra, no mesmo design.

## Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | Página de vendas (oferta principal R$ 19,90) |
| `upsell.html` | Página de upsell pós-compra (componente Cakto, `offer-id` configurado) |
| `assets/styles.css` | Design system compartilhado pelas duas páginas |
| `assets/produto.webp` / `.jpg` | Capa do e-book |

## Links

- Produção: https://receitasnaturais.salevo.site
- Upsell: https://receitasnaturais.salevo.site/upsell.html
- Checkout (Cakto): https://pay.cakto.com.br/6frywru

## Publicação

Site estático: basta enviar os arquivos para o `public_html` do subdomínio. Nenhum build é necessário.

## Observações

- O conteúdo dos e-books **não** é versionado neste repositório (ver `.gitignore`).
- Copy segue as regras de conformidade da oferta: material informativo, sem promessa de tratamento, cura ou resultado em prazo fixo.
