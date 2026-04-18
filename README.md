# 🎨 ArtCoin

**ArtCoin** é uma prova de conceito (PoC) para uma rede social baseada em "Economia Criativa" e "Mintagem de Valor". Diferente de redes sociais tradicionais onde o valor é medido por "curtidas" gratuitas, no ArtCoin o valor visual e monetário de uma arte é determinado pelo investimento inicial do próprio criador.

## 🚀 Funcionalidades

- **Canvas Studio Integrado:** Ferramenta de desenho responsiva com suporte a touch, paleta de cores e controle de espessura de pincel.
- **Sistema de Economia Virtual:** Carteira digital integrada. Investir moedas nas artes retira do saldo e define o preço de revenda.
- **Algoritmo de Raridade:** As artes ganham efeitos visuais (Glassmorphism, Neon, Pulso) baseados no investimento:
  - ⬜ **Comum:** < 50 moedas
  - 🟦 **Raro:** 50 - 299 moedas
  - 🟪 **Épico:** 300 - 999 moedas
  - 🟨 **Lendário:** 1000+ moedas (Efeito de brilho em CSS)
- **Persistência de Dados (Local):** Utilização do `LocalStorage` do HTML5 para garantir que o saldo e o feed de artes não sejam perdidos ao recarregar a página.

## 🛠️ Tecnologias Utilizadas

- **HTML5** (Semântico e Canvas API)
- **CSS3** (Variáveis, Grid, Flexbox, Animações, Glassmorphism)
- **JavaScript Vanilla (ES6+)** (Orientação a Objetos, Manipulação de DOM, LocalStorage)

## 📱 Como executar

Este projeto não requer um servidor de backend complexo para testes devido à estrutura de persistência local.

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/artcoin.git](https://github.com/SEU_USUARIO/artcoin.git)
