# Confiancce - Casas de Madeira Pré-fabricadas

Site oficial da **Confiancce Construtora e Ferragem**, especializada em construção de casas de madeira pré-fabricadas em madeira nobre e eucalipto nos estados do Rio Grande do Sul e Santa Catarina.

## 🏠 Sobre o Projeto

Plataforma digital que apresenta modelos de casas, projetos entregues, depoimentos de clientes e facilita o contato para solicitação de orçamentos. O site é otimizado para **SEO Local** e **Answer Engine Optimization (AEO)**.

### Características Principais

- **10 Modelos de Casas** — Araucária, Cambará, Canela, Paineira, Freijó, Grápia, Tauari, Marfim, Cedro, Alecrim
- **Portfolio de Projetos** — 6 projetos entregues em RS e SC
- **7 Avaliações de Clientes** — Reviews 5⭐ estruturadas em Schema.org
- **Bot de Orçamento** — Página dedicada para solicitar cotações
- **Áreas de Atuação** — Autocomplete para cidades RS/SC
- **SEO Otimizado** — Schema.org, robots.txt, sitemap.xml, meta tags

## 📁 Estrutura do Projeto

```
/
├── index.html                      # Página principal
├── bot-orcamento.html              # Página de orçamento
├── robots.txt                      # Guia para crawlers
├── sitemap.xml                     # Mapa do site
├── CNAME                           # Configuração DNS (GitHub Pages)
├── .gitignore                      # Arquivos ignorados no Git
├── README.md                       # Este arquivo
├── github.md                       # Registro de sincronização GitHub
│
├── .github/
│   └── workflows/                  # CI/CD workflows (deploy automático)
│
├── src/                            # Código-fonte adicional
│
└── assets/
    ├── images/                     # Imagens do projeto (45+ arquivos)
    │   ├── logo-confiancce-*.png
    │   ├── carrossel-*.webp        # Carousel hero
    │   ├── araucaria.webp          # Modelos de casas
    │   ├── cambara.webp
    │   ├── canela.webp
    │   ├── [... outros modelos]
    │   ├── card*.webp              # Cards de dicas
    │   └── [... projetos e cidades]
    │
    └── js/
        └── support.js              # Runtime para Design Components
```

## 🚀 Como Usar

### Abrir Localmente

```bash
# Clone o repositório
git clone https://github.com/confiancce/casasconfiancce.com.br.git

# Acesse a pasta
cd casasconfiancce

# Abra no navegador
open index.html
# ou
firefox index.html
```

### Fazer Alterações

1. **Editar conteúdo:** Modifique `index.html` diretamente
2. **Adicionar imagens:** Coloque em `assets/images/` e atualize os caminhos
3. **Alterar scripts:** Modifique `assets/js/support.js`
4. **Atualizar meta tags:** Edite `<head>` no `index.html`

### Deploy

O site está hospedado em **GitHub Pages** e usa o domínio **casasconfiancce.com.br** (configurado em `CNAME`).

**Workflow automático:** Qualquer push em `main` dispara deploy automático via `.github/workflows/`.

## 🔍 SEO & Otimizações

### Meta Tags
- ✅ `og:title`, `og:description`, `og:image` (Open Graph)
- ✅ `twitter:card` (Twitter/X)
- ✅ `canonical` tag
- ✅ `description` (155 caracteres otimizado)
- ✅ `keywords` relevantes para RS/SC

### Schema.org (JSON-LD)
- ✅ `Organization` — Dados da empresa
- ✅ `LocalBusiness` — Informações locais + ratings agregados
- ✅ `FAQPage` — 4 perguntas frequentes
- ✅ `Product` — 10 modelos de casas com preço
- ✅ `BreadcrumbList` — Navegação estruturada
- ✅ `Review` — 7 avaliações de clientes

### Crawlability
- ✅ `robots.txt` — Guia para bots
- ✅ `sitemap.xml` — Mapa com 8+ URLs
- ✅ Estrutura de links internos

### Performance
- ✅ Imagens em `.webp` (compressão moderna)
- ✅ CSS inline (sem bloqueio de renderização)
- ✅ JavaScript assíncrono
- ✅ Viewport meta tag (mobile responsive)

## 📊 Modelos Disponíveis

| Modelo | Quartos | Área | Preço Inicial |
|--------|---------|------|--------------|
| Araucária | 2 | 42m² | R$ 77.900 |
| Grápia | 2 | 42,5m² | R$ 80.900 |
| Alecrim | 2 | 56,25m² | R$ 86.900 |
| Cambará | 2 | 61,75m² | R$ 119.900 |
| Marfim | 2 | 67,5m² | R$ 127.900 |
| Cedro | 3 | 79,75m² | R$ 124.900 |
| Canela | 2 | 73m² | R$ 140.900 |
| Tauari | 3 | 86,5m² | R$ 153.500 |
| Paineira | 3 | 85m² | R$ 169.500 |
| Freijó | 2 | 102,5m² | R$ 190.900 |

## 📍 Áreas de Atuação

- ✅ **Rio Grande do Sul** — Todas as cidades/municípios
- ✅ **Santa Catarina** — Todas as cidades/municípios

Autocomplete interativo com mais de 600 cidades mapeadas.

## 📞 Contato

- **WhatsApp:** [51 99145-7278](https://wa.me/5551991457278)
- **Instagram:** [@confiancce.construtora](https://www.instagram.com/confiancce.construtora)
- **Google Maps:** [Ver avaliações](https://maps.app.goo.gl/gCm6GF1QfCRyrKWN6)

## 🛠️ Stack Técnico

- **Markup:** HTML5 semântico
- **Styling:** CSS inline + media queries
- **Interatividade:** Vanilla JavaScript (ES6+)
- **Componentes:** Design Components (DC) com streaming
- **Otimização:** Schema.org, Open Graph, Twitter Cards
- **Hospedagem:** GitHub Pages
- **Domínio:** GitHub Pages + CNAME

## 📝 Licença

Propriedade intelectual da **Confiancce Construtora e Ferragem**.

---

**Versão:** 1.0.0  
**Última atualização:** 16 de setembro de 2026  
**Mantido por:** Equipe Confiancce
