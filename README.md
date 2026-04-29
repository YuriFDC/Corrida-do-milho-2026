# 🌽 Corrida do Milho 2026 — Landing Page

Case de portfólio: landing page para um evento de corrida de rua em Patos de Minas, MG. O projeto foi desenvolvido com foco em **conversão mobile** — onde a maioria dos acessos de eventos esportivos acontece.

🔗 **[Ver demo ao vivo](https://corrida-do-milho-2026.vercel.app)**

---

## 📱 Sobre o projeto

A proposta foi criar uma landing page moderna e orientada à conversão, pensando no usuário que acessa pelo celular, muitas vezes em movimento. Cada decisão de layout foi feita para reduzir fricção e direcionar o clique para a inscrição.

O desenvolvimento partiu de um wireframe próprio e evoluiu para uma versão **mobile-first** completa, sem uso de frameworks CSS ou JavaScript externos.

---

## ✨ Destaques técnicos

- **Mobile-first** — estrutura pensada de 320px para cima, com breakpoints em 600px e 960px
- **Sticky CTA** — botão "Garantir Vaga" fixado no rodapé da tela no mobile, sempre visível durante a rolagem
- **Tipografia fluida** — uso de `clamp()` em todas as fontes e espaçamentos para adaptação suave entre tamanhos de tela
- **Hierarquia visual forte** — "MILHO" em escala maior que o restante do título, criando um ponto focal imediato
- **Zero dependências** — HTML e CSS puros, sem frameworks, sem bibliotecas JS
- **Performance** — imagens com `loading="lazy"`, fontes com `preconnect`, CSS otimizado

---

## 🎨 Decisões de design

### Paleta — Verde limão `#CCFF00` sobre fundo escuro

O verde limão foi escolhido por carregar múltiplas referências ao mesmo tempo: remete à energia do esporte, à identidade visual do milho (produto símbolo de Patos de Minas) e ao movimento — sem perder a modernidade. Sobre fundo escuro (`#0A0A0A`), o contraste é máximo e o resultado lembra a estética de marcas fitness e eventos de corrida de alto nível como a Adidas Running e a Nike Run Club.

### Tipografia — Righteous + Barlow Condensed

A **Righteous** foi escolhida para os títulos por ter uma personalidade forte e geométrica que comunica velocidade e impacto — sem precisar gritar. É uma fonte que chama atenção em frações de segundo, essencial para uma landing page onde o usuário decide em menos de 3 segundos se vai continuar rolando. A **Barlow Condensed** complementa com legibilidade e eficiência em espaços pequenos, ideal para labels, badges e informações secundárias no mobile.

---

## 🛠 Tecnologias

- HTML5 semântico
- CSS3 (Flexbox, Grid, Custom Properties, clamp())
- Google Fonts (Righteous, Barlow Condensed, Barlow)
- Deploy via Vercel

---

## 📂 Estrutura

```
corrida-do-milho-2026/
├── index.html       # Página principal (tudo em um único arquivo)
└── README.md
```

---

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/YuriFDC/corrida-do-milho-2026.git

# Abra o arquivo no navegador
open index.html
```

Não há dependências ou build step — basta abrir o arquivo.

---

## 👤 Autor

Feito por **[YuriFDC](https://github.com/YuriFDC)**

---

*Projeto fictício desenvolvido para fins de portfólio.*
