# Atividade Prática - HTML Semântico, Validação W3C e Estilização Básica

Repositório criado para a entrega da atividade prática da disciplina de **LIMA (Linguagem de Marcação)**, focada no desenvolvimento da landing page da **PixelGear eSports Store**, aplicando conceitos fundamentais do HTML5, metadados, formatação semântica, integração de mídias/links, estilização com CSS externo e validação pelo W3C.

---

## 🎯 Objetivo da Atividade

Desenvolver e consolidar a habilidade de compreender e aplicar os fundamentos básicos do HTML5 e CSS3. A atividade abrange desde a estruturação inicial da página com metadados essenciais para SEO e responsividade até a organização semântica do conteúdo (apresentação de produtos, especificações técnicas e promoções), exibição e dimensionamento proporcional de imagens, links de contato direto, aplicação do visual escuro (*Dark Mode*) e validação do código segundo os padrões do W3C.

---

## 📄 Conteúdo da Página (`index.html` e `style.css`)

O projeto consiste na página de lançamento da loja **PixelGear eSports Store**, contendo:

- **Estrutura Fundamental e Metadados (`<head>`):** Configuração de codificação (`UTF-8`), viewport responsiva, metatags de SEO (descrição, palavras-chave e autor) e vinculação ao arquivo de estilos externo.
- **Cabeçalho Principal (`<header>`):** Apresentação da marca *PixelGear eSports* e slogan institucional centralizados via CSS.
- **Navegação Principal (`<nav>`):** Menu estruturado com links de ancoragem interna (`#sobre`, `#destaques`, `#produtos`, `#contato`) para fácil rolagem da página.
- **Conteúdo Principal (`<main>`):** 
  - **Seção Sobre Nós (`<section id="sobre">`):** Apresentação da missão e foco da loja em hardware de alta performance.
  - **Destaque da Semana (`<section id="destaques">`):** Apresentação do PC Beast Edition v2.0 com especificações técnicas completas, suporte a Overclock, preço promocional em destaque e imagem descritiva do produto.
  - **Periférico em Destaque (`<section id="produtos">`):** Apresentação do Headset Kraken Surround 7.1 detalhando drivers de 50mm, microfone retrátil, preço em oferta e imagem do periférico.
  - **Linhas Divisórias (`<hr>`):** Separação visual e temática entre as seções e os produtos do catálogo.
- **Mídias e Acessibilidade (`<img>`):** Inserção das imagens dos produtos com o atributo `alt` preenchido adequadamente para leitores de tela e dimensionamento proporcional via CSS (`max-width: 180px`, `height: auto`).
- **Links de Contato Direto (`<a>`):** 
  - Protocolo `mailto:` para envio direto de e-mail de suporte.
  - Integração com a API do WhatsApp (`https://api.whatsapp.com/send`) com parâmetro de mensagem pré-formatada e abertura em nova aba (`target="_blank"`).
- **Formatação Semântica de Texto:** Uso de tags como `<strong>` e `<b>` para destaques, `<em>` e `<i>` para termos técnicos em inglês (*Ray Tracing*, *cable management*), `<del>` para preços antigos e `<sup>`/`<sub>` para versões e especificações.
- **Estilização Externa (`style.css`):** Definição da tipografia em Arial, tamanho proporcional de fontes, alinhamento centralizado de títulos/preços, formatação de imagens e aplicação do tema escuro (*Dark Mode*) sem o uso de tags depreciadas como `<center>`.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica, elementos de imagem, hiperlinks dinâmicos (`mailto:`, API do WhatsApp), metadados de SEO/responsividade e tags de formatação textual.
- **CSS3:** Estilização externa para controle de tipografia (Arial), alinhamento de texto, dimensões e bordas de imagens (`.product-img`) e visual escuro.
- **W3C Markup Validation Service:** Validação da sintaxe e conformidade com os padrões da web.

---

## 👩‍💻 Autora

**Heloísa Gonçalves Silva**