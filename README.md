# Casa da Música

Site de uma loja de instrumentos musicais fictícia, criado como projeto de portfólio por **Thyego**. O visitante conhece a loja, explora as categorias, vê os instrumentos em destaque e monta um carrinho de compras.

**Acesse:** [thyego17.github.io/Casa-da-Musica](https://thyego17.github.io/Casa-da-Musica/)

## Funcionalidades

- **Categorias com fotos:** oito categorias de instrumentos e equipamentos, com imagens em preto e branco que ganham cor ao passar o mouse.
- **Instrumentos em destaque:** cinco produtos com descrição e preço, cada um com botão "Adicionar".
- **Carrinho funcional:** o contador no cabeçalho é atualizado a cada item, e uma janela permite aumentar ou diminuir as quantidades e ver o total.
- **Finalização de demonstração:** o botão "Finalizar pedido" avisa que nenhum pedido é enviado de verdade.
- **Contato rápido:** botões de telefone, e-mail e mapa.

## Categorias

Guitarras, Baixos, Baterias, Teclados, Microfones, Amplificadores, Equipamentos de áudio e Clássicos.

## Instrumentos em destaque

| Produto | Preço |
| --- | --- |
| Guitarra Elétrica | R$ 1.599,90 |
| Baixo Elétrico | R$ 1.899,90 |
| Bateria Acústica | R$ 3.499,90 |
| Teclado Digital | R$ 2.299,90 |
| Amplificador | R$ 1.299,90 |

## Tecnologias

- HTML5 semântico, incluindo o elemento `<dialog>` para a janela do carrinho
- CSS3 (Grid, Flexbox, variáveis CSS e animações)
- JavaScript puro, sem bibliotecas
- Fontes [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) e [Jost](https://fonts.google.com/specimen/Jost), via Google Fonts

## Design

- Visual elegante e sombrio, com fundo vinho escuro, acento em dourado envelhecido e detalhes em vermelho.
- Tipografia serifada em destaque e rótulos em caixa-alta espaçada.
- Layout responsivo, pensado primeiro para o celular.
- Foco visível, HTML semântico e respeito à preferência de movimento reduzido.

## Estrutura

```
Casa-da-Musica/
├── index.html
├── README.md
├── guitarra.jpg
├── baixo.jpg
├── bateria.jpg
├── teclado.jpg
├── microfone.jpg
├── amplificador.jpg
├── audio.jpg
└── classicos.jpg
```

O site está em um único arquivo, com CSS e JavaScript incorporados. As imagens precisam ficar na mesma pasta do `index.html`.

## Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/thyego17/Casa-da-Musica.git
   ```
2. Abra o `index.html` no navegador.

Não é necessário instalar nada.

## Como personalizar

Tudo fica no `index.html`:

- **Produtos em destaque:** altere a lista `P` no início do script, no formato `["Nome", "Descrição", preço]`.
- **Categorias:** edite os itens da seção "Encontre o seu som". Cada um tem imagem, nome e descrição. Para trocar uma foto, substitua o arquivo ou mude o nome em `src`.
- **Contato:** troque o telefone no link `tel:`, o e-mail no link `mailto:` e o endereço na seção de contato. No botão de mapa, ajuste o endereço dentro do link do Google Maps.
- **Cores:** edite as variáveis em `:root`, no início do `<style>`.

## Observações

Este é um projeto de demonstração. Nome, endereço, telefone, e-mail e preços são fictícios. O carrinho funciona apenas enquanto a página está aberta, e nenhum dado é salvo nem enviado.

## Autor

**Thyego**

- Portfólio: [thyego17.github.io/Portif-lio](https://thyego17.github.io/Portif-lio/)
- GitHub: [@thyego17](https://github.com/thyego17)
