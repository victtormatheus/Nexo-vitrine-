# Nexo — vitrine de produtos

Este é um site estático inicial para a vitrine Nexo. Ele mantém o mesmo endereço quando você atualiza os arquivos do mesmo site no Netlify.

## Arquivos
- `index.html`: visual da vitrine.
- `products.json`: catálogo de produtos.

## Como cadastrar produtos
Edite `products.json` seguindo este formato:

```json
{
  "products": [
    {
      "name": "Nome do produto",
      "description": "Descrição curta, se quiser",
      "price": "R$ 49,90",
      "image": "https://endereco-publico-da-imagem.jpg",
      "url": "https://link-original-do-produto"
    }
  ]
}
```

Use uma URL pública direta para a imagem. Não use links de login nem links temporários de arquivos privados.

## Atualizações e limitações
Esta versão não tem painel de administração nem banco de dados. Para publicar produtos novos, é preciso atualizar `products.json` no repositório e deixar o Netlify publicar a atualização. O endereço do site permanece o mesmo se você atualizar o site já existente, em vez de criar outro site.
