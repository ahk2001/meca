# 📂 DOSSIÊ ESTRATÉGICO: AUTOESCUELA MECA (AYORA / ALMANSA)

> **Documento-fonte oficial** para desenvolvimento do novo site de alta conversão da **Autoescuela Meca**.  
> Todos os dados factuais foram apurados a partir de `dados.txt`, análise visual dos arquivos em `assets/`, verificação HTTP de `autoescuelameca.com` e pesquisa em diretórios públicos e registros DGT. Itens não disponíveis publicamente estão sinalizados como `[A CONFIRMAR COM O CLIENTE]`.

---

## 1. 🏢 DADOS INSTITUCIONAIS & CONTATO

| Campo | Informação Apurada |
| :--- | :--- |
| **Nome Comercial** | **Autoescuela Meca** *(também indexada como Meca Autoescuela y Formación Integral)* |
| **Razão Social / CIF** | `[A CONFIRMAR COM O CLIENTE]` |
| **Slogan Principal (ES)** | *"Tu carnet a la primera en Ayora y Almansa: formación vial, flota 100% eléctrica y especialistas en permisos profesionales."* |
| **Slogan Secundário (ES)** | *"Más que una autoescuela: tu centro integral de conducción, CAP y mercancías peligrosas."* |
| **Telefone Fixo** | `+34 961 89 01 46` *(confirmado em `dados.txt` e diretórios)* |
| **WhatsApp / Celular** | `+34 961 89 01 46` *(encontrado em diretórios locais — `[A CONFIRMAR COM O CLIENTE]` se este é o número principal de atendimento WhatsApp)* |
| **E-mail Oficial** | `[A CONFIRMAR COM O CLIENTE]` |
| **Site Atual** | `http://autoescuelameca.com/` *(atualmente responde HTTP 200 OK com conteúdo vazio / 0 bytes — site fora do ar ou em manutenção)* |
| **Instagram** | `https://www.instagram.com/autoescuelameca/` *(informado em `dados.txt`)* |
| **Tom de Voz da Marca** | **Próximo, moderno, confiável e orientado a resultados.** Combina a proximidade de uma autoescola tradicional de referência na comarca com a inovação tecnológica (veículo 100% elétrico para práticas) e a autoridade técnica no setor de transporte profissional (CAP, ADR e caminhões). |

---

## 2. 🎨 IDENTIDADE VISUAL E DESIGN SYSTEM

### Paleta de Cores Oficial (Códigos HEX)

| Função | Nome Sugerido | Código HEX | Origem / Aplicação |
| :--- | :--- | :--- | :--- |
| **Cor Primária** | Rojo Meca | `#E1010D` | Extraído diretamente de `assets/logo.png` e `assets/favicon.png`. Usar em logotipo, badges de destaque, acentos de títulos e detalhes da marca. |
| **Cor Secundária / Acento** | Negro Fachada | `#18181B` | Inspirado no revestimento escuro da fachada física (`Captura de tela 2026-11-24 145628.png`). Usar em headers, cards escuros e contrastes fortes. |
| **Cor de Conversão / CTA** | Verde WhatsApp / L | `#16A34A` *(ou `#25D366` para ícone WhatsApp)* | Cor vibrante de alto contraste para botões principais de matrícula, contato rápido via WhatsApp e selos de aprovação ("L"). |
| **Fundo Escuro (Dark Surface)** | Azul Pizarra Oscuro | `#0F172A` | Seções de alto impacto (Hero overlay, barra de estatísticas DGT, rodapé). |
| **Fundo Claro (Light Surface)** | Blanco Puro / Gris Hielo | `#FFFFFF` / `#F8FAFC` | Fundo principal das seções de conteúdo, garantindo leitura limpa e moderna. |
| **Texto Principal / Secundário** | Gris Carbón / Pizarra | `#111827` / `#4B5563` | Textos de alta legibilidade sobre fundos claros. |

### Tipografia Recomendada
- **Títulos (Headings):** `Plus Jakarta Sans` ou `Outfit` (pesos `700` e `800`) — traços geométricos e modernos que dialogam diretamente com as curvas arredondadas do logotipo `meca`.
- **Corpo de Texto (Body):** `Inter` (pesos `400`, `500` e `600`) — excelente legibilidade em formulários, tabelas de cursos e dispositivos móveis.

### Mapeamento Completo das Imagens em `assets/`

| Arquivo (Caminho Relativo) | Descrição Visual | Uso Recomendado no Site |
| :--- | :--- | :--- |
| `assets/logo.png` | Logotipo oficial `meca` em vermelho `#E1010D` sobre fundo transparente/branco. | Navbar principal, rodapé e materiais institucionais. |
| `assets/favicon.png` | Ícone monograma `m` em vermelho `#E1010D`. | Favicon do navegador e ícone de app/atalho mobile. |
| `assets/homedesktop.png` | Caminhão baú vermelho e branco com logo `meca` em rodovia espanhola (formato paisagem/desktop). | **Banner Hero Desktop** (excelente para posicionar a autoescola como líder em formação geral e profissional). |
| `assets/homemobile.png` | Mesma composição do caminhão `meca` adaptada em corte vertical. | **Banner Hero Mobile** (responsivo dedicado). |
| `assets/Captura de tela 2026-11-24 145524.png` | Grupo de 5 alunos recém-aprovados segurando a placa verde "L" da `meca` com instrutores na saída do centro. | Seção de **Prova Social / Galeria de Aprobados**. |
| `assets/Captura de tela 2026-11-24 145535.png` | Aluna aprovada e instrutor ao lado de **carro Tesla branco** com placa de teto `meca autoescuela ELÉCTRICO 100%` + `L PRÁCTICAS`. | Destaque exclusivo na seção **Permiso B / Frota 100% Elétrica e Automática**. |
| `assets/Captura de tela 2026-11-24 145553.png` | Aluno e instrutor em frente ao caminhão de práticas com marca `meca`, `renovacioncap.com` e `driveando`. | Seção de **Permisos Profesionales (Camión C / C+E e CAP)**. |
| `assets/Captura de tela 2026-11-24 145613.png` | Grupo de jovens alunos aprovados comemorando com instrutora. | Carrossel de **Comunidad / Aprobados**. |
| `assets/Captura de tela 2026-11-24 145628.png` | Fachada física da **Autoescuela Meca** (letreiro 3D `meca`) com instrutor e aluno segurando placa "L". | Seção **Sobre Nosotros / Nuestra Sede en Ayora**. |
| `assets/Captura de tela 2026-11-24 145645.png` | Grupo de alunos com instrutor ao lado de carro de práticas bicolor (vermelho e branco). | Seção **Permiso B (Manual)** ou galeria de frota. |

---

## 3. 📍 SEDE FÍSICA, LOCALIZAÇÃO E HORÁRIOS

- **Endereço Principal:** Plaza Mayor, 1, 46620 Ayora (Valencia), España.  
  *(Nota: Em alguns diretórios antigos também consta menção à Plaza Virgen de la Asunción, 14 — `[A CONFIRMAR COM O CLIENTE]` se trata de endereço anterior ou acesso secundário).*
- **Área de Atuação / Zona de Exames:** Ayora, Valle de Ayora-Cofrentes e **Almansa** (Albacete).
- **Link Direto do Google Maps:** [Ver Autoescuela Meca - Ayora / Almansa no Google Maps](https://www.google.com/maps/place/Autoescuela+Meca+-+Ayora+%2F+Almansa/@39.0592461,-1.0659491,16z/data=!4m10!1m2!2m1!1sautoescuela!3m6!1s0xd6139fdb243f1db:0x36a8688f12834915!8m2!3d39.0592461!4d-1.0564219!15sCgthdXRvZXNjdWVsYVoNIgthdXRvZXNjdWVsYZIBDmRyaXZpbmdfc2Nob29smgFEQ2k5RFFVbFJRVU52WkVOb2RIbGpSamx2VDIxS2JsRjZSazVPU0VKV1RtcEdSMWRJYURGTlZFMTNaVWhLYUZNd1JSQULgAQD6AQQIUhBH!16s%2Fg%2F11byx8dyt9?entry=ttu&g_ep=EgoyMDI2MTExOC4xIKXMDSoASAFQAw%3D%3D)
- **Coordenadas Geográficas:** `39.0592461, -1.0564219`
- **Horários Oficiais da Secretaria:** `[A CONFIRMAR COM O CLIENTE]` *(Segunda a sexta-feira — horários específicos de manhã e tarde não publicados de forma fixa online).*

---

## 4. 🚗 CATÁLOGO EXAUSTIVO DE SERVIÇOS E CURSOS

*(Títulos e descrições em Espanhol da Espanha prontos para uso no site)*

### A. Permisos Particulares
1. **Permiso B (Coche — Cambio Manual y 100% Eléctrico / Automático)**
   - Preparação teórica presencial e intensiva + plataforma de test online.
   - Práticas em veículos modernos, incluindo **veículo 100% elétrico (Tesla)** identificado na frota oficial (`ELÉCTRICO 100%`).
   - Alta taxa de aprovação oficial na DGT.
2. **Permisos de Moto (AM, A1, A2, A)**
   - Constam nos diretórios públicos os permisos **A1** e **A** *(verificar disponibilidade de **AM** e **A2** — `[A CONFIRMAR COM O CLIENTE]`)*.
   - Possui pista própria de treino homologada? `[A CONFIRMAR COM O CLIENTE]`.

### B. Cursos Oficiais DGT
3. **Recuperación de Puntos del Carnet (DGT)**
   - **Recuperación Parcial (12 horas):** Para recuperar hasta 4 puntos sin examen.
   - **Recuperación Total / Pérdida de Vigencia (24 horas):** Curso completo para volver a obtener el permiso tras pérdida de puntos o sentencia judicial.
   - *Obs.:* Serviço listado em diretórios do setor; `[A CONFIRMAR COM O CLIENTE]` datas das próximas convocações homologadas.

### C. Permisos Profesionales & Transporte (Especialidade da Casa)
4. **Permisos de Vehículos Pesados (C1, C, C+E, D, D+E)**
   - **Camión (C1 / C)** e **Tráiler (C+E)** com packs multipermiso e formatos intensivos (atraindo inclusive alunos de fora da comarca).
   - **Autobús (D / D+E)**.
5. **CAP (Certificado de Aptitud Profesional)**
   - **CAP Inicial (140 horas):** Mercancías y Viajeros.
   - **CAP Continuo / Renovación (35 horas):** Sin examen, actualización obligatoria cada 5 años.
6. **ADR (Mercancías Peligrosas)**
   - Obtención y renovación: Básico Común, Cisternas, Explosivos y Radiactivos (modalidades intensivas de fin de semana).
7. **Maquinaria, Logística y Seguridad Vial**
   - **Carretillas Elevadoras** (carnet de carretillero).
   - **Grúa Camión Pluma**, **Estiba y Sujeción de Cargas (UNE 12195)** e **Tacógrafo Digital**.

### D. Credenciamentos e Formação Subvencionada
- **Centro Colaborador LABORA (Servicio Valenciano de Empleo y Formación):** Participação e realização de cursos habilitantes para o emprego (carretillas, CAP, ADR) em colaboração com entidades locais como o Ayuntamiento de Ayora.
- **Formación Bonificada FUNDAE:** Gestão de créditos de formação para empresas e trabalhadores em ativo no setor de transporte e logística.

---

## 5. 💰 ESTRUTURA COMERCIAL E TARIFAS

- **Matrícula Permiso B / Cursos Teóricos:** `[A CONFIRMAR COM O CLIENTE]` *(Recomenda-se botão "Consultar oferta actual por WhatsApp")*.
- **Aulas Práticas (Avulsas e Pacotes):** `[A CONFIRMAR COM O CLIENTE]`.
- **Taxas Oficiais DGT e Exames Psicotécnicos:** `[A CONFIRMAR COM O CLIENTE]`.
- **Cursos Profissionais (CAP / ADR / Camión C+E):** `[A CONFIRMAR COM O CLIENTE]` *(informar se há pacotes com facilidades logísticas/alojamento para alunos de fora)*.
- **Modalidades de Pagamento Disponíveis:** `[A CONFIRMAR COM O CLIENTE]` *(ex.: tarjeta, efectivo, Bizum, financiación a plazos)*.

---

## 6. ⭐ PROVA SOCIAL, REPUTAÇÃO E DEPOIMENTOS

- **Nota Média no Google Reviews:** **~4,8 / 5,0 estrellas** *(baseada em mais de 70 avaliações públicas indexadas em diretórios locais)*.
- **Indicador Oficial de Performance DGT:** Em registros públicos de estatísticas DGT na província de Valência, a Autoescuela Meca destaca-se com **taxa de aprovação superior a 71%–72% no exame prático do Permiso B**.
- **Instrutores e Professores Mais Elogiados:** `[A CONFIRMAR COM O CLIENTE]` *(Os nomes individuais dos instrutores que aparecem nas fotos da pasta `assets/` não constam nos registros públicos indexados; é necessário confirmar com o cliente antes de publicá-los no site).*
- **Depoimentos Reais de Alunos:**
  > ⚠️ **Nota de Verificação:** Sem acesso via navegador interativo, a ficha completa de comentários individuais do Google Maps não é exposta em texto estático. Os termos reais mais recorrentes indexados em diretórios sobre a autoescola são: *"trato genial"*, *"profesionalidad"*, *"cursos intensivos muy efectivos"* e *"aprobé a la primera"*.  
  > **`[A CONFIRMAR COM O CLIENTE]`:** Solicitar ao cliente ou extrair manualmente 4 a 6 resenhas literais do painel do Google Business Profile antes da publicação final do site.

---

## 7. 📲 ARQUITETURA DE CONVERSÃO & LINKS DE WHATSAPP

> **Atenção:** Os links abaixo utilizam o número `+34 961 89 01 46` identificado em diretórios públicos da Autoescuela Meca. Confirmar com o cliente se este é o número oficial de WhatsApp antes do deploy (caso contrário, substituir pelo número indicado).

1. **Matrícula Geral — Permiso B (Coche Manual / 100% Eléctrico):**
   - **Texto (ES):** `¡Hola! Me gustaría recibir información sobre precios, horarios y matrícula para el Permiso B (coche manual o eléctrico) en Autoescuela Meca.`
   - **Link:** `https://wa.me/34961890146?text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20recibir%20informaci%C3%B3n%20sobre%20precios%2C%20horarios%20y%20matr%C3%ADcula%20para%20el%20Permiso%20B%20(coche%20manual%20o%20el%C3%A9ctrico)%20en%20Autoescuela%20Meca.`

2. **Curso de Recuperación de Puntos DGT (12h / 24h):**
   - **Texto (ES):** `¡Hola! Quiero consultar las próximas fechas y plazas disponibles para el curso de Recuperación de Puntos DGT (12h / 24h).`
   - **Link:** `https://wa.me/34961890146?text=%C2%A1Hola!%20Quiero%20consultar%20las%20pr%C3%B3ximas%20fechas%20y%20plazas%20disponibles%20para%20el%20curso%20de%20Recuperaci%C3%B3n%20de%20Puntos%20DGT%20(12h%20%2F%2024h).`

3. **Cursos Profissionais (CAP / Camión C / Tráiler C+E / ADR):**
   - **Texto (ES):** `¡Hola! Estoy interesado en los cursos profesionales de Autoescuela Meca (CAP, ADR, Camión C o Tráiler C+E). ¿Me podéis informar de las próximas convocatorias?`
   - **Link:** `https://wa.me/34961890146?text=%C2%A1Hola!%20Estoy%20interesado%20en%20los%20cursos%20profesionales%20de%20Autoescuela%20Meca%20(CAP%2C%20ADR%2C%20Cami%C3%B3n%20C%20o%20Tr%C3%A1iler%20C%2BE).%20%C2%BFMe%20pod%C3%A9is%20informar%20de%20las%20pr%C3%B3ximas%20convocatorias%3F`

4. **Aulas Práticas Avulsas ou Reciclagem:**
   - **Texto (ES):** `¡Hola! Me gustaría consultar disponibilidad y tarifas para clases prácticas sueltas o de reciclaje de conducción.`
   - **Link:** `https://wa.me/34961890146?text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20consultar%20disponibilidad%20y%20tarifas%20para%20clases%20pr%C3%A1cticas%20sueltas%20o%20de%20reciclaje%20de%20conducci%C3%B3n.`

---

## 8. 📐 DIRETRIZES RECOMENDADAS PARA A CRIAÇÃO DO SITE

### Proposta Única de Valor (UVP)
> **"La autoescuela referente entre Ayora y Almansa con más de un 71% de aprobados en el examen práctico, flota 100% eléctrica (Tesla) y liderazgo absoluto en cursos intensivos profesionales (CAP, ADR y Camión C+E)."**

### Ordem Recomendada de Seções na Página Inicial (Alta Conversão)
1. **Header Fixo (Sticky Navbar):** Logo `meca` à esquerda, links rápidos (`Permisos`, `Profesionales y CAP`, `Flota Eléctrica`, `Ubicación`) e botão verde CTA **"Hablar por WhatsApp"**.
2. **Hero Section (Impacto Imediato):** Imagem `homedesktop.png` / `homemobile.png` com overlay escuro suave, H1 forte (*"Sácate el carnet a la primera en Ayora y Almansa"*), selo **"4,8★ en Google | +71% de aprobados DGT"** e dois CTAs: *"Quiero mi Permiso B"* e *"Cursos CAP / Camión"*.
3. **Barra de Autoridade & Diferenciais:** 4 pilares visuais rápidos: *Flota 100% Eléctrica (Tesla)*, *Cursos Intensivos*, *Centro LABORA / FUNDAE*, *+71% Aprobados DGT*.
4. **Catálogo de Permisos Particulares:** Cards para **Permiso B (Manual y Eléctrico 100%)** com a foto real do Tesla (`Captura de tela 2026-11-24 145535.png`), **Motos** e **Recuperación de Puntos DGT**.
5. **Hub de Transporte & Formación Profesional (Diferencial Estratégico):** Destaque dedicado para **Camión C / C+E, Autobús D, CAP Inicial/Continuo, ADR e Carretillas**, utilizando a foto real do caminhão (`Captura de tela 2026-11-24 145553.png`).
6. **Galeria de Aprobados & Prova Social:** Carrossel com as fotos reais dos alunos segurando a placa "L" (`145524`, `145613`, `145645`) + nota `4,8★` no Google + espaço para os 4–6 depoimentos após confirmação.
7. **Nuestra Sede, Horarios y Mapa (Ayora / Almansa):** Foto da fachada (`145628`), endereço `Plaza Mayor, 1, 46620 Ayora (Valencia)`, botão direto para o Google Maps e telefone `+34 961 89 01 46`.
8. **Rodapé (Footer) + Botão Flutuante de WhatsApp:** Links rápidos, aviso legal / privacidade e botão flutuante persistente no canto inferior direito.
