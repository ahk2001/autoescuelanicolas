# 📂 DOSSIÊ ESTRATÉGICO: AUTOESCUELA NICOLÁS

> **Fonte única de verdade** para o desenvolvimento do novo site institucional e de alta conversão da **Autoescuela Nicolás** (Valência, Espanha).  
> Todos os dados abaixo foram levantados a partir de `dados.txt`, da pasta `assets/`, do site oficial (`https://autoescuelanicolas.es/`) e de registros públicos verificados. Informações não confirmadas publicamente estão marcadas como `[A CONFIRMAR COM O CLIENTE]`.

---

## 1. 🏢 DADOS INSTITUCIONAIS & CONTATO

| Campo | Informação Verificada |
| :--- | :--- |
| **Nome Comercial** | Autoescuela Nicolás |
| **Razão Social** | AUTOESCUELA NICOLÁS S.L. |
| **CIF / NIF** | `B96356381` |
| **Ano de Fundação** | `1967` (mais de 50 anos de trajetória em Valência) |
| **Afiliação / Rede** | Centro de formación asociado a **AVAE** (Asociación Valenciana de Autoescuelas) |
| **Slogan Principal (ES)** | *"Desde 1967 enseñando a conducir. Tu autoescuela en Valencia"* |
| **Slogan Secundário (ES)** | *"La Calidad nos MUEVE"* |
| **WhatsApp Oficial** | `+34 661 30 77 97` (`https://wa.me/34661307797`) |
| **Telefone Fixo Principal** | `+34 963 77 08 43` |
| **Telefone Secundário** | `+34 963 77 08 03` *(registrado na Política de Privacidade)* |
| **E-mail Principal** | `infoautoescuelanicolas@gmail.com` |
| **Site Atual** | `https://autoescuelanicolas.es/` |
| **Facebook Oficial** | [Autoescuela Nicolás (Facebook)](https://www.facebook.com/people/Autoescuela-Nicol%C3%A1s/100054481629220/) |
| **Instagram** | `[A CONFIRMAR COM O CLIENTE]` *(não localizado em `dados.txt`, no site oficial nem em buscas públicas)* |

### Tom de Voz da Marca
- **Perfil:** Familiar, próximo, experiente e acolhedor (*cercano, familiar y profesional*).
- **Posicionamento:** Tradição de mais de cinco décadas passando de pais para filhos no bairro de Jesús/Patraix, unida à paciência dos instrutores, acompanhamento individualizado e recursos digitais modernos (plataforma de test online).
- **Copy de referência (ES):**
  - *Headline:* **"Más de 50 años enseñando a conducir en Valencia"**
  - *Subheadline:* **"Desde 1967 formamos conductores seguros con un trato cercano, profesores pacientes y metodología adaptada a tu ritmo."**

---

## 2. 🎨 IDENTIDADE VISUAL E DESIGN SYSTEM

### Paleta de Cores Extraída (`logo.png` + `autoescuelanicolas.es`)

| Função | Cor | Código HEX | Origem / Uso Recomendado |
| :--- | :--- | :--- | :--- |
| **Primária (Marca / Logo)** | Vermelho Nicolás | `#F20002` | Cor dominante extraída do logotipo oficial (`assets/logo.png`). Uso em destaques principais, logomarca e acentos de marca. |
| **Primária Institucional (Site)** | Vermelho Escuro | `#C60B0B` | Variável `--nv-primary-accent` do site atual. Ideal para estados `:hover`, faixas institucionais e cabeçalhos de destaque. |
| **Secundária / Rede AVAE** | Verde AVAE | `#088C37` | Presente nos selos da rede AVAE e sinalização dos veículos (`homedesktop.png`). Ideal para badges de certificação, selos de confiança e cursos profissionais. |
| **Conversão / WhatsApp** | Verde WhatsApp | `#25D366` | Cor oficial do botão flutuante de WhatsApp do site atual (`qlwapp`). Uso exclusivo em botões de contato rápido via WhatsApp. |
| **CTA Secundário / Acento** | Vermelho Vivo | `#E3270A` | Botões de matrícula e chamadas para ação principais sobre fundo claro ou escuro. |
| **Fundo Escuro (Dark Surface)** | Grafite Profundo | `#14171C` | Variável `--nv-dark-bg` do site atual. Ideal para Header/Footer, seção do logotipo (garante contraste para o aro branco) e blocos de autoridade. |
| **Fundo Claro (Light Surface)** | Branco Puro / Cinza Suave | `#FFFFFF` / `#EDEDED` | Variáveis `--nv-site-bg` e `--nv-light-bg`. Fundos principais das seções de conteúdo e cards. |
| **Texto Principal** | Preto Carvão | `#020202` | Variável `--nv-text-color`. Leitura de alta legibilidade sobre fundos claros. |

### Tipografia Recomendada
- **Fonte Principal (Site Oficial):** `Poppins` (pesos `400`, `600`, `700` via Google Fonts — já utilizada no site atual).
- **Títulos (Headings):** `Poppins` Bold/SemiBold (`600`–`700`), transmitindo clareza, modernidade e autoridade.
- **Corpo de Texto (Body):** `Poppins` Regular (`400`) ou `Inter` Regular (`400`), garantindo leitura confortável em desktop e mobile.

### Mapeamento de Imagens (`assets/`)

| Arquivo (Caminho Relativo) | Descrição Visual | Uso Recomendado no Novo Site |
| :--- | :--- | :--- |
| `assets/logo.png` | Logotipo oficial: volante estilizado em branco/transparente com `"N"` central e `"NICOLAS"` curvo em vermelho (`#F20002`). **Atenção:** o texto superior *"AUTO ESCUELA - SEGUROS"* e o aro do volante são brancos, exigindo fundo escuro (`#14171C`) ou ajuste de contraste. | Header, Footer e Favicon/Marca d'água. |
| `assets/homedesktop.png` | Foto em alta resolução (paisagem) da placa luminosa de teto do carro da autoescola (*AVAE AUTOESCUELA / NICOLAS / L PRACTICAS*) com iluminação dourada ao pôr do sol. | **Hero Section (Desktop)** — imagem principal de impacto. |
| `assets/homemobile.png` | Versão vertical (retrato) da mesma cena da placa luminosa de teto do carro de práticas. | **Hero Section (Mobile)** — responsividade otimizada para telas verticais. |
| `assets/Imagen81-1-1024x785.png` | Foto real da fachada da autoescola na Av. de Gaspar Aguilar, 65 com letreiro *"CENTRO DE FORMACION VIAL AUTO ESCUELAS NICOLAS"* sobre composição gráfica vermelha e escura. | Seção **Sobre Nós / Nuestra Historia** ou **Sede Física**. |
| `assets/Imagen89-899x1024.png` | Colagem vertical com 5 imagens: 2 fotos de alunas sorridentes junto ao carro AVAE Nicolás, 1 foto da fachada com carro de práticas estacionado e 2 fotos reais da sala de aula teórica/multimídia (cadeiras vermelhas e computadores de test). | Seção **Instalaciones y Flota / Aula Multimedia** (ou desmembramento para galeria). |

---

## 3. 📍 SEDE FÍSICA, LOCALIZAÇÃO E HORÁRIOS

- **Endereço Completo:** Avenida de Gaspar Aguilar, 65, Bajo, 46017 Valencia, Provincia de Valencia, España *(Zona Jesús / Patraix)*.
- **Coordenadas Geográficas:** `39.45479, -0.391289`
- **Link Direto do Google Maps:** [Abrir en Google Maps](https://www.google.com/maps/place/Autoescuela+Nicol%C3%A1s/@39.4572845,-0.404623,15z/data=!4m10!1m2!2m1!1sautoescuela!3m6!1s0xd604f3d2aa811c9:0x66cbfd379a353ab2!8m2!3d39.45479!4d-0.391289!15sCgthdXRvZXNjdWVsYVoNIgthdXRvZXNjdWVsYZIBDmRyaXZpbmdfc2Nob29smgEjQ2haRFNVaE5NRzluUzBWSlEwRm5UVVJuYVdOaE1FNW5FQUXgAQD6AQQIABBH!16s%2Fg%2F1tfjgwf7?entry=ttu&g_ep=EgoyMDI2MTEyMi4wIKXMDSoASAFQAw%3D%3D)
- **Link Curto Oficial (`maps.app.goo.gl`):** `[A CONFIRMAR COM O CLIENTE]`

### Horários Oficiais de Funcionamento (Secretaria)
*Extraído diretamente da página `/contacto/` do site oficial:*
- **Lunes a Viernes (Segunda a Sexta):** `09:30 – 13:00` e `15:30 – 21:00`
- **Sábados y Domingos:** Cerrado (Fechado)

---

## 4. 🚗 CATÁLOGO EXAUSTIVO DE SERVIÇOS E CURSOS

### A. Permisos Particulares
- **Permiso B (Coche) — Especialidade Principal:**
  - *Título sugerido (ES):* **Permiso B – Carnet de Coche**
  - *O que inclui:* Formación teórica presencial en aula equipada, plataforma de **Test Online** ilimitados desde cualquier dispositivo, seguimiento personalizado, horarios flexibles y clases prácticas con vehículos nuevos por zonas de examen de Valencia.
  - *Modalidade Automático (Permiso B Automático):* `[A CONFIRMAR COM O CLIENTE]` *(não especificado no site atual)*.
- **Permisos de Moto (Centro de Formación AVAE):**
  - **Permiso AM** (Ciclomotores)
  - **Permiso A1** (Motocicletas hasta 125 cc)
  - **Permiso A2** (Motocicletas hasta 35 kW)
  - **Curso A** (Motocicletas sin límite de cilindrada, para titulares de A2)
  - *Pista própria homologada de treino:* `[A CONFIRMAR COM O CLIENTE]` *(as páginas de moto no site atual redirecionam para as fichas da rede AVAE; confirmar se as práticas de circuito fechado são realizadas em pista própria da AVAE em Valência)*.

### B. Cursos Oficiais DGT
- **Curso de Recuperación de Puntos DGT** *(listado na página inicial como curso em colaboração com AVAE)*:
  - *Recuperación Parcial de Puntos (12 horas):* `[A CONFIRMAR COM O CLIENTE — confirmar calendário e se há turmas presenciais na sede ou via centro AVAE]`
  - *Recuperación Total / Pérdida de Vigencia (24 horas):* `[A CONFIRMAR COM O CLIENTE]`

### C. Permisos Profesionales & Transporte (Centro de Formación AVAE)
Listados oficialmente na página `/permisos-profesionales/` do site:
- **Permiso C:** Camiones rígidos.
- **Permiso C+E:** Tráiler / Camiones articulados y trenes de carretera.
- **Permiso B+E y D+E:** Conjuntos con remolque.
- **Permiso D:** Autobuses / Transporte de viajeros.
- **CAP (Certificado de Aptitud Profesional):**
  - *CAP Inicial* (Mercancías y Viajeros)
  - *Formación Continua CAP (Renovación cada 5 años)*
- **Permiso ADR:** Transporte de Mercancías Peligrosas.
- **Permiso TMC:** Curso específico listado na página profissional (`avae.es/permisos-y-cursos/permiso-tmc/`).
- **Curso de Carretillero:** Manejo de carretillas elevadoras (listado na página inicial).
- **Tacógrafo Digital:** `[A CONFIRMAR COM O CLIENTE]` *(não listado separadamente no site)*.

### D. Credenciamentos & Formação Bonificada
- **Centro LABORA (cursos subvencionados / bolsa de empleo):** `[A CONFIRMAR COM O CLIENTE]` *(não consta menção no site oficial)*.
- **Formación Bonificada FUNDAE (para empresas e trabalhadores):** `[A CONFIRMAR COM O CLIENTE]` *(não consta menção no site oficial)*.

---

## 5. 💰 ESTRUTURA COMERCIAL E TARIFAS

O site oficial informa *"Los precios más competitivos"*, porém **não publica valores numéricos fechados** online, trabalhando com atendimento personalizado.

| Item | Valor / Status |
| :--- | :--- |
| **Matrícula Permiso B** | `A consultar vía WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Aulas Práticas Avulsas** | `A consultar vía WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Pacotes / Bonos de Prácticas** | `A consultar vía WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Taxas Oficiais DGT (Examen)** | `A consultar vía WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Modalidades de Pagamento** | `[A CONFIRMAR COM O CLIENTE]` *(ex.: tarjeta, efectivo, Bizum, pago fraccionado)* |

---

## 6. ⭐ PROVA SOCIAL, REPUTAÇÃO E DEPOIMENTOS

- **Nota Média:** **4,6 / 5 estrellas** *(verificada em diretórios públicos com base em 27 avaliações registradas no Trustlocal; contagem exata atualizada no Google Maps: `[A CONFIRMAR COM O CLIENTE]`)*.
- **Taxa de Aprovados DGT (Referência Pública):** ~52%–53% de aprovação acumulada no Permiso B segundo portais de estatísticas DGT.
- **Membros da Equipe Mais Elogiados Nominalmente:**
  - **Rubén** *(Professor de aulas práticas — elogiado pela paciência e por ajudar alunos a aprovar de primeira mesmo com prazos apertados)*
  - **Eva** *(Professora — elogiada pelo trato próximo e apoio constante)*
  - **Nico** *(Atendimento / Direção — elogiado pela simpatia e disponibilidade para resolver dúvidas)*

### Depoimentos Reais de Alunos (Espanhol da Espanha)

1. **Rakel** *(publicado no site oficial)*:
   > *"Mejor autoescuela imposible de encontrar recomiendo a 100×100 los profes que decir de ellos lo mejor de lo mejor."*

2. **Jose** *(publicado no site oficial)*:
   > *"La autoescuela de toda una vida….mi padre ,yo…y mi hijo. Los tres nos hemos sacado el carnet aquí….gracias"*

3. **Wendy** *(publicado no site oficial)*:
   > *"Una maravilla de profesor. Tanto para las clases teóricas como las prácticas. Excelente autoescuela!!!"*

4. **Alumno (Reseña pública sobre el profe Rubén)** *(registrado em diretório do setor)*:
   > *"Como los tiempos eran muy justos, hicieron todo lo posible para que pudiera examinarme antes de que mi teórico caducara. Sin duda, el profe Rubén ha jugado un papel clave: gracias a su enseñanza y paciencia, ¡aprobé a la primera!"*

---

## 7. 📲 ARQUITETURA DE CONVERSÃO & LINKS DE WHATSAPP

Todos os links utilizam o número oficial verificado `+34 661 30 77 97` (`34661307797`) com mensagens pré-configuradas em Castellano:

1. **Matrícula Geral — Permiso B (Coche):**
   - *Texto (ES):* `¡Hola! Me gustaría recibir información sobre precios y horarios para matricularme en el Permiso B (coche) en Autoescuela Nicolás.`
   - *Link:* `https://wa.me/34661307797?text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20recibir%20informaci%C3%B3n%20sobre%20precios%20y%20horarios%20para%20matricularme%20en%20el%20Permiso%20B%20(coche)%20en%20Autoescuela%20Nicol%C3%A1s.`

2. **Curso de Recuperación de Puntos DGT:**
   - *Texto (ES):* `¡Hola! Quiero información sobre las próximas fechas y precios del curso de Recuperación de Puntos DGT.`
   - *Link:* `https://wa.me/34661307797?text=%C2%A1Hola!%20Quiero%20informaci%C3%B3n%20sobre%20las%20pr%C3%B3ximas%20fechas%20y%20precios%20del%20curso%20de%20Recuperaci%C3%B3n%20de%20Puntos%20DGT.`

3. **Cursos Profesionales (CAP / Camión / ADR / Moto):**
   - *Texto (ES):* `¡Hola! Estoy interesado en los permisos profesionales o cursos (CAP / Camión C / C+E / D / ADR / Moto). ¿Podrían informarme?`
   - *Link:* `https://wa.me/34661307797?text=%C2%A1Hola!%20Estoy%20interesado%20en%20los%20permisos%20profesionales%20o%20cursos%20(CAP%20%2F%20Cami%C3%B3n%20C%20%2F%20C%2BE%20%2F%20D%20%2F%20ADR%20%2F%20Moto).%20%C2%BFPodr%C3%ADan%20informarme%3F`

4. **Clases Prácticas Sueltas o de Reciclaje:**
   - *Texto (ES):* `¡Hola! Quisiera consultar disponibilidad y tarifas para dar clases prácticas sueltas o de reciclaje.`
   - *Link:* `https://wa.me/34661307797?text=%C2%A1Hola!%20Quisiera%20consultar%20disponibilidad%20y%20tarifas%20para%20dar%20clases%20pr%C3%A1cticas%20sueltas%20o%20de%20reciclaje.`

---

## 8. 📐 DIRETRIZES RECOMENDADAS PARA A CRIAÇÃO DO SITE

### Proposta Única de Valor (UVP)
> *"La autoescuela de confianza en Valencia desde 1967: tres generaciones aprobando con un trato familiar, profesores pacientes (Rubén, Eva y Nico), test online 24/7 y el respaldo de AVAE para todos los permisos de moto y transporte profesional."*

### Ordem Recomendada de Seções na Página Inicial (Foco em Conversão)
1. **Header Fixo (Fundo Escuro `#14171C`):** Logotipo (`assets/logo.png`), menu enxuto (*Inicio, Permiso B, Motos, Profesionales, Contacto*), botão de acesso rápido ao **Portal del Alumno** e CTA verde WhatsApp.
2. **Hero Section (Acima da dobra):** Imagem `homedesktop.png` (desktop) / `homemobile.png` (mobile) com overlay escuro para contraste, badge *"Desde 1967 en Valencia · 4,6★ en Google"*, Headline forte para o **Permiso B**, e dois CTAs: *"Quiero matricularme por WhatsApp"* e *"Ver permisos"*.
3. **Barra de Diferenciais (Trust Bar):** 4 pilares reais: `+50 años de experiencia` | `Teórica presencial + Test Online` | `Vehículos nuevos y rutas de examen` | `Centro asociado AVAE`.
4. **Destaque Principal — Permiso B (Coche):** Explicação clara do método individualizado, requisitos básicos e CTA direto para o WhatsApp de matrícula.
5. **Catálogo Completo de Permisos y Cursos (Cards):**
   - Card 1: **Permisos de Moto** (`AM, A1, A2, Curso A`)
   - Card 2: **Permisos Profesionales y Transporte** (`C, C+E, D, B+E, D+E, CAP, ADR, TMC, Carretillero`)
   - Card 3: **Recuperación de Puntos DGT**
6. **Prueba Social (Reseñas Reales):** Nota `4,6/5` + os 4 depoimentos reais de **Rakel, Jose, Wendy** e do aluno do **profe Rubén**, destacando a continuidade familiar e a paciência da equipe.
7. **Nuestra Autoescuela e Instalaciones:** História desde 1967 + fotos da fachada (`Imagen81-1-1024x785.png`) e da sala multimídia (`Imagen89-899x1024.png`).
8. **Localización, Horarios y Contacto:** Mapa incorporado (Av. de Gaspar Aguilar, 65, 46017 Valencia), horário comercial (`09:30–13:00` / `15:30–21:00`), telefone fixo e botão flutuante de WhatsApp.
9. **Footer Institucional:** Dados legais obrigatórios em Espanha (`AUTOESCUELA NICOLÁS S.L. · CIF B96356381`), links de *Aviso Legal, Política de Privacidad, Política de Cookies* e Facebook oficial.
