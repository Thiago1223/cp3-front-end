# 🖱️ Click Zone — E-commerce de Mouses Gamer Logitech

Site de uma loja fictícia de mouses gamer Logitech, desenvolvido para o Checkpoint 3 de Front-End da FIAP.

🔗 Deploy: [Site Hospedado](#)

## 📋 Índice

- [Sobre o projeto](#-sobre-o-projeto)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Estrutura de pastas](#-estrutura-de-pastas)
- [Style Guide](#-style-guide)
- [Design System](#-design-system)
- [Como executar](#-como-executar)
- [Autor](#-autor)

## 📖 Sobre o projeto

Página única com menu, quatro seções e rodapé, feita com HTML e CSS puros. O destaque da loja é o Logitech G502 X Plus, e a página também lista outros cinco modelos da linha G.

Seções da página:

- **Início:** banner com o produto em destaque, preço e botões de compra
- **Produtos:** cards com seis mouses, descrição curta e preço
- **Tecnologia:** diferenciais do G502 X Plus
- **Vantagens:** frete, parcelamento, devolução e atendimento

As imagens são fotos de produto da Logitech, recortadas e ajustadas para o projeto. Preços e condições de compra são fictícios.

## 🚀 Tecnologias utilizadas

- HTML5
- CSS3 (Flexbox)
- Google Fonts — Chakra Petch e Barlow
- Font Awesome — ícones

## 📁 Estrutura de pastas

```
Projeto/
├── css/
│   └── style.css
├── imagens/
│   ├── g203.png
│   ├── g305.png
│   ├── g502x.png
│   ├── g502x-lightspeed.png
│   ├── g502x-plus.png
│   ├── g502x-plus-branco.png
│   └── superlight-2.png
├── index.html
├── integrantes.txt
└── README.md
```

## 🎨 Style Guide

### Cores

| Nome | Hex | Onde é usada |
|------|-----|--------------|
| Preto | `#14171c` | Cabeçalho, banner, rodapé e botões escuros |
| Grafite | `#202832` | Fundo da seção de tecnologia |
| Cinza | `#dbdbdb` | Fundo da seção de produtos, bordas e textos sobre fundo escuro |
| Cinza azulado | `#3a4452` | Fundo das imagens dos cards |
| Azul | `#00b8fc` | Botão principal, ícones de tecnologia e destaque do logo |
| Azul escuro | `#0079a8` | Ícones sobre fundo claro |
| Texto | `#191919` | Texto corrido sobre fundo claro |
| Branco | `#ffffff` | Títulos sobre fundo escuro, cards e seção de vantagens |

As seções alternam entre fundo escuro e claro: Início (preto), Produtos (cinza), Tecnologia (grafite) e Vantagens (branco). O azul é usado só em ações e destaques.

### Tipografia

| Uso | Fonte | Peso | Tamanho |
|-----|-------|------|---------|
| Título do banner | Chakra Petch | 600 | 64px |
| Título de seção | Chakra Petch | 600 | 40px |
| Preço do banner | Chakra Petch | 700 | 40px |
| Preço do card | Chakra Petch | 700 | 26px |
| Título de card | Chakra Petch | 700 | 22px |
| Título de item (tecnologia e vantagens) | Chakra Petch | 700 | 20px |
| Texto do banner | Barlow | 400 | 20px |
| Texto corrido | Barlow | 400 | 16px |
| Descrição do card | Barlow | 400 | 15px |

### Ícones

Biblioteca Font Awesome. Ícones usados: `computer-mouse`, `cart-shopping`, `cart-plus`, `bullseye`, `bolt`, `wifi`, `lightbulb`, `truck-fast`, `credit-card`, `rotate-left`, `headset`, `instagram`, `facebook` e `youtube`.

## 🧩 Design System

### Botões

| Classe | Aparência | Uso |
|--------|-----------|-----|
| `botao botao--azul` | Fundo azul, texto preto | Ação principal (Comprar agora) |
| `botao botao--borda` | Borda cinza, texto branco | Ação secundária sobre fundo escuro (Ver detalhes) |
| `botao botao--escuro` | Fundo preto, texto branco | Adicionar ao carrinho nos cards |

Todos têm borda arredondada de 30px, padding de 14px por 32px e fonte Barlow 600.

### Componentes

| Componente | Classe | Descrição |
|------------|--------|-----------|
| Card de produto | `container-cards__card` | Imagem, nome, descrição, preço e botão. Largura de 260px |
| Item de tecnologia | `container-tech__item` | Ícone em quadrado azul, título e texto |
| Item de vantagem | `container-vantagens__item` | Ícone, título e texto dentro de caixa com borda cinza |
| Título de seção | `titulo-secao` | Chakra Petch 40px, centralizado |

### Espaçamentos

| Valor | Onde é usado |
|-------|--------------|
| 8px | Entre ícone e texto em botões e links |
| 12px | Entre elementos dentro de itens de vantagem |
| 16px | Entre elementos de um mesmo grupo |
| 24px | Padding interno dos cards e entre botões do banner |
| 32px | Entre itens da seção de vantagens |
| 40px | Entre os cards de produto |
| 70px | Padding das seções, do cabeçalho e do rodapé |

### Bordas

| Valor | Onde é usado |
|-------|--------------|
| `0 40px 0 40px` | Cards de produto e itens de vantagem |
| `0 16px 0 16px` | Ícones da seção de tecnologia |
| `30px` | Botões |

### Layout

Todo o posicionamento usa Flexbox: seções em coluna ou linha, cards com `flex-wrap` para quebrar de linha conforme a largura da tela e `gap` para o espaçamento entre elementos.

## ⚙️ Como executar

```bash
# Clone este repositório
git clone <link-do-repositório>

# Acesse a pasta do projeto
cd Projeto
```

Abra o arquivo `index.html` no navegador. Não precisa instalar nada, mas é preciso estar conectado à internet para carregar as fontes e os ícones.

## 👤 Autor

Thiago Freitas Vilariço - RM 576212

[GitHub](https://github.com/Thiago1223)