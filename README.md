# Autoescuela Nicolás — Valencia (España)

Site institucional oficial da **Autoescuela Nicolás** (**AUTOESCUELA NICOLÁS S.L.** · CIF `B96356381`), centro de formação vial fundado em **1967** e associado à rede **AVAE** em Valência.

## 📍 Sede & Contato
- **Endereço:** Av. de Gaspar Aguilar, 65, Bajo, 46017 Valencia, España
- **Telefones:** +34 963 77 08 43 / +34 963 77 08 03
- **WhatsApp:** +34 661 30 77 97
- **E-mail:** `infoautoescuelanicolas@gmail.com`
- **Horário:** Segunda a Sexta, `09:30 – 13:00` e `15:30 – 21:00`

## 📁 Estrutura do Projeto
```text
├── .github/         # Workflows de deploy contínuo (GitHub Pages)
├── assets/          # Logotipo oficial e fotografias reais da autoescola
├── docs/            # Dossiê estratégico e documentação de levantamento
├── index.html       # Landing page estática HTML5/CSS3/JS autocontida
├── robots.txt       # Diretrizes de indexação SEO
├── sitemap.xml      # Mapa XML para mecanismos de busca
└── vercel.json      # Headers de segurança HTTP e cache de assets
```

## 🔒 Segurança & Performance
- **HTML/CSS/JS estático puro** sem dependências externas pesadas ou segredos expostos.
- **Headers de segurança** configurados em `vercel.json` (`HSTS`, `X-Frame-Options`, `X-Content-Type-Options`, `Referrer-Policy`, `Permissions-Policy`).
- **Cache imutável** configurado para `/assets/`.
