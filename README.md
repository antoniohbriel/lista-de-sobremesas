# 🛒 Sistema de Carrinho de Compras Dinâmico

Este projeto é um sistema de carrinho de compras desenvolvido com foco em interatividade e atualização dinâmica de conteúdo, utilizando HTML, CSS e JavaScript. Os dados dos produtos são carregados a partir de um arquivo `data.json`, permitindo uma renderização dinâmica no front-end.

## ✨ Funcionalidades Principais

### 📦 Renderização Dinâmica de Produtos
- Os produtos disponíveis são carregados diretamente do arquivo `data.json`.
- A renderização no HTML é feita dinamicamente, sem a necessidade de recarregar a página.
- Cada produto exibe nome, imagem, preço e botão para adicionar ao carrinho.

### ➕➖ Adição e Remoção de Itens
- É possível **adicionar** produtos ao carrinho com um clique.
- Os itens podem ser **removidos** individualmente do carrinho a qualquer momento.

### 🔢 Controle de Quantidade
- Os usuários podem **aumentar ou diminuir a quantidade** de cada item no carrinho usando botões de incremento e decremento.
- A quantidade mínima é 1 unidade por item.

### 💰 Cálculo de Valores
- O sistema **calcula automaticamente o subtotal** de cada produto com base na quantidade selecionada.
- O **valor total da compra** é atualizado em tempo real conforme os produtos são adicionados, removidos ou alterados.