# Bruno Tavares | Psicólogo Clínico (CRP 15/6694)

Landing page institucional desenvolvida para o Psicólogo Clínico **Bruno Tavares**, com foco em atendimento psicológico online fundamentado na Terapia Cognitivo-Comportamental (TCC) e Avaliação Psicológica.

Este projeto foi desenvolvido como parte do **Projeto de Extensão Curricular (PEC)** do curso de Sistemas de Informação (4º período - CESMAC).

## Acesso Online (Deploy)

O site está hospedado e disponibilizado publicamente através do **Cloudflare Pages**:

- **Link de Acesso:** [Acesse o site aqui](https://SEU-PROJETO.pages.dev) *(substitua pelo link gerado após o deploy)*

## Sobre o Projeto

A página foi projetada com uma identidade visual acolhedora em tons de verde sálvia (`#6a8570`) harmonizada com a marca do profissional, aplicando efeitos modernos de *glassmorphism*, tipografia editorial (`Cormorant Garamond` e `Plus Jakarta Sans`) e foco em conversão ética e acessibilidade.

### Principais Funcionalidades

* **Cabeçalho Fixo Responsivo:** Barra de navegação com redução dinâmica da logo durante a rolagem e menu gaveta (*drawer*) adaptado para dispositivos móveis.
* **Apresentação Institucional & Sobre Mim:** Exposição da formação, registro profissional (`CRP 15/6694`), metodologia de trabalho e disponibilidade de vagas por valor social.
* **Seção Educacional sobre TCC:** Explicação visual da tríade cognitiva (Pensamentos, Emoções e Comportamentos) e dos pilares da abordagem baseada em evidências.
* **Catálogo de Serviços:** Detalhamento das frentes de atuação (Psicoterapia Online, Psicodiagnóstico, Orientação Profissional e de Carreira, Recrutamento e Seleção, e Supervisão em Testes Psicológicos).
* **FAQ Interativo (Acordeão):** Respostas às dúvidas mais frequentes sobre duração, frequência, sigilo profissional e funcionamento das sessões online, com suporte a atributos de acessibilidade (`aria-expanded`).
* **Agendamento Direto via WhatsApp:** Botões de chamada para ação (CTAs) e botão flutuante que geram mensagens personalizadas automaticamente conforme o serviço selecionado pelo visitante.
* **Animações de Rolagem:** Transições suaves de entrada utilizando a API nativa `IntersectionObserver`.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica, metadados de SEO e Open Graph.
* **CSS3:** Variáveis customizadas (`:root`), CSS Grid, Flexbox, `backdrop-filter` (*glassmorphism*) e design responsivo (*mobile-first* / *breakpoints*).
* **JavaScript (ES6+):** Manipulação do DOM, controle do menu mobile, lógica do acordeão do FAQ, integração dinâmica com a API do WhatsApp (`wa.me`) e animações via `IntersectionObserver`.
* **Cloudflare Pages:** Hospedagem estática e entrega contínua (CI/CD) integrada ao GitHub.

## Estrutura de Pastas

```text
├── assets/
│   ├── FotoHero.jpeg
│   ├── FotoSobre.jpeg
│   └── LogoVerde.jpeg
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── index.html
└── README.md
```

## Como Executar Localmente

Como o projeto é estático e não depende de pacotes externos ou etapa de *build*, basta servir os arquivos localmente:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/GuiT0rres/NOME-DO-SEU-REPO.git
   cd NOME-DO-SEU-REPO
   ```

2. **Inicie um servidor local:**
   * **Via Python:**
     ```bash
     python3 -m http.server 8080
     ```
     Acesse `http://localhost:8080` no navegador.
   * **Via VS Code:** Utilize a extensão **Live Server** clicando em *Go Live* no arquivo `index.html`.

## Desenvolvedores

* **Guilherme Torres** — [@GuiT0rres](https://github.com/GuiT0rres)
* **Leonardo Vasconcelos** — [@Lao-00](https://github.com/Lao-00)

---

*Desenvolvido em conformidade com as diretrizes de comunicação e o Código de Ética Profissional do Psicólogo (CFP).*