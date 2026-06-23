# 7Safe MedTech - Site Institucional

Site institucional estatico da **7Safe MedTech**.

Dominio oficial: https://www.7safe.com.br/

O posicionamento deste site e institucional/investidores: plataforma medtech, ativos proprios, propriedade intelectual, portfolio, parcerias estrategicas e escala B2B. Informacoes especificas do SWB ficam concentradas no site proprio do produto.

Produto SWB: https://www.swbbrasil.com.br/

## Estrutura

```text
7safe-site/
├── .github/workflows/pages.yml  # Deploy automatico no GitHub Pages
├── .nojekyll                    # Evita processamento Jekyll no Pages
├── assets/
│   ├── icon-*.png               # Favicons e icones PWA
│   └── preview/                 # Midias usadas pela pagina oficial
├── index.html                   # Pagina oficial
├── package.json                 # Scripts locais
├── site.webmanifest             # Manifest PWA
└── README.md
```

## Rodar Localmente

```bash
npm run dev
```

Depois acesse:

```text
http://localhost:8000
```

## Deploy

O deploy esta configurado por GitHub Actions em `.github/workflows/pages.yml`. Cada push na branch `main` publica o conteudo estatico da raiz do repositorio.

No GitHub, a origem do Pages deve estar configurada como:

```text
Settings -> Pages -> Source -> GitHub Actions
```

## Contato

- E-mail: atendimento@swbbrasil.com.br
- WhatsApp: +55 11 94739-1805
- LinkedIn: https://linkedin.com/company/7safe-brasil
- Site: https://www.7safe.com.br/

© 7Safe MedTech.
