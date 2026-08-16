# PsicoTemplate — Site para Psicologia & Terapia Online

Template acolhedor e profissional para psicólogos, clínicas de terapia e atendimento psicológico presencial ou online.

**Nicho:** Psicologia / Terapia / Saúde Mental

**Estilo visual:** Acolhedor, natural, suave — paleta de verdes e tons terrosos (#3A5A40, #A3B18A, #DAD7CD), tipografia Lora (serif) + Inter (sans), design limpo e minimalista.

**Objetivo do template:** Transmitir confiança e acolhimento, apresentar especialidades, demonstrar o processo terapêutico, oferecer atendimento online e captar leads.

---

# Público Ideal

Psicólogos clínicos, psicoterapeutas, clínicas de psicologia, coaches com formação em psicologia, profissionais com CRP ativo.

**Exemplos:**
- Psicólogo clínico com consultório presencial em [CIDADE]
- Psicóloga que atende online (nacional e internacional)
- Clínica de psicologia com múltiplos profissionais
- Terapeuta especializado em ansiedade, TCC ou psicanálise

**Quando NÃO utilizar:**
- Psiquiatras ou médicos (nicho diferente, regulamentação diferente)
- Coach sem formação em psicologia (não pode usar CRP)
- Profissionais que não possuem registro profissional ativo
- Aplicativos ou plataformas digitais de terapia

---

# Estrutura do Site

1. **Header** — Nav fixa com logo e links âncora
2. **Hero** — Título, CTA, número do CRP e imagem acolhedora
3. **Sobre / Diferenciais** — 3 cards com os principais diferenciais do atendimento
4. **Especialidades** — 6 cards com as áreas de atuação
5. **Processo** — Timeline vertical de 4 passos (como funciona a terapia)
6. **Atendimento Online** — Seção dedicada com depoimento e CTA
7. **FAQ** — 4 perguntas com elementos `<details>` nativos do HTML
8. **Contato** — Formulário + informações (telefone, email, endereço, mapa)
9. **Rodapé** — 3 colunas com logo, links, contato e CRP

---

# Elementos Obrigatórios para Personalização

- Logo (nome no header/footer)
- Nome do profissional ou clínica
- Slogan
- CRP (registro profissional)
- Paleta de cores (CSS variables)
- Fontes
- Imagens (hero, atendimento online)
- Ícones (SVG inline)
- Telefone
- Email
- Endereço
- Cidade
- Redes sociais
- SEO (title, description, keywords, OG)
- Mapa (Google Maps embed)
- Formulário (action)
- FAQ

---

# Textos

Substitua todos os `[COLCHETES]` no arquivo `index.html`:

**Identidade:**
- `[NOME DA EMPRESA]`
- `[SLOGAN]`
- `[DESCRICAO DA EMPRESA]`
- `[CIDADE]`

**Hero:**
- `[NÚMERO DO CRP]`

**Diferenciais:**
- `[DIFERENCIAL 1]` a `[DIFERENCIAL 3]`
- `[DESCRICAO DO DIFERENCIAL 1]` a `[DESCRICAO DO DIFERENCIAL 3]`

**Especialidades:**
- `[ESPECIALIDADE 1]` a `[ESPECIALIDADE 6]`
- `[DESCRICAO ESPECIALIDADE 1]` a `[DESCRICAO ESPECIALIDADE 6]`

**Processo:**
- `[ETAPA 1]` a `[ETAPA 4]` (títulos)
- `[DESCRICAO ETAPA 1]` a `[DESCRICAO ETAPA 4]` (descrições)

**Atendimento Online:**
- `[DEPOIMENTO DO CLIENTE]`
- `[NOME DO CLIENTE]`
- `[ANO] (paciente desde)`

**FAQ:**
- `[PERGUNTA 1]` a `[PERGUNTA 4]`
- `[RESPOSTA 1]` a `[RESPOSTA 4]`

**Contato:**
- `[TELEFONE]`
- `[EMAIL]`
- `[ENDEREÇO]`
- `[CIDADE/ESTADO]`

**Rodapé:**
- `CRP [NÚMERO]`

**URLs:**
- `[URL_DA_IMAGEM_OG]`
- `[URL_DO_FORMULARIO]`

---

# Imagens

| Uso | Atual | Tipo ideal | Resolução |
|-----|-------|------------|-----------|
| Hero | `via.placeholder.com/600x750` | Foto do profissional ou imagem acolhedora (natureza, sala de terapia) | 600x750 |
| Atendimento Online | (dentro da seção) | Imagem que remeta a atendimento remoto | 600x400 |

**Sugestões:** Use fotos reais do consultório, do profissional ou imagens que transmitam calma e acolhimento (natureza, plantas, luz natural). Evite imagens muito genéricas de banco de imagens.

⚠️ **Atenção:** O placeholder atual (`via.placeholder.com`) pode estar fora do ar. Substitua imediatamente por uma imagem real.

---

# Componentes Personalizáveis

- **Cards de Diferenciais** — 3 cards com ícone, título e descrição. Pode alterar textos e ícones.
- **Cards de Especialidades** — 6 cards com ícone decorativo, título e descrição. Reordenável.
- **Timeline de Processo** — 4 etapas verticais numeradas. Pode alterar título e descrição.
- **FAQ** — Usa `<details>` nativo do HTML (sem JavaScript). Pode adicionar ou remover perguntas.
- **Atendimento Online** — Seção com depoimento e CTA. Pode alterar depoimento e nome do cliente.
- **Formulário de Contato** — É o único template que já possui `action` e `method="POST"` configurados (com placeholder). Campos: nome, email, telefone, mensagem.

---

# SEO

- **Título:** `[NOME DA EMPRESA] | Psicologia em [CIDADE] e Online`
- **Meta Description:** `[DESCRICAO DA EMPRESA]` com cidade e serviços
- **Keywords:** termos de psicologia + `[CIDADE]`
- **Open Graph:** title, description, type (`website`), image
- **Twitter Card:** Não implementado — recomenda-se adicionar
- **Schema.org:** Não implementado — recomenda-se adicionar `Psychologist` ou `Physician` JSON-LD
- **Favicon:** Não há — recomenda-se adicionar

---

# Identidade Visual

Todas as cores são controladas via CSS custom properties no `:root`:

```css
--color-primary: #3A5A40;        /* Verde profundo */
--color-primary-hover: #344B39;
--color-secondary: #DAD7CD;      /* Neutro natural */
--color-accent: #A3B18A;         /* Verde claro */
--color-bg: #F8F9FA;             /* Fundo claro */
--color-surface: #FFFFFF;
--color-text-primary: #2B2D33;
--color-text-secondary: #6C757D;
--color-border: #E9ECEF;
```

**Fontes:**
- Títulos: `Lora` (Google Fonts) — serifa elegante que transmite confiança
- Corpo: `Inter` (Google Fonts) — sans-serif limpa e legível

**Tipografia fluida:** Todos os `--fs-*` usam `clamp()` para responsividade nativa (sem breakpoints manuais).

---

# Partes que NÃO devem ser alteradas

- Estrutura e ordem das seções (9 seções)
- Timeline vertical do processo (4 etapas numeradas)
- Sistema de FAQ com `<details>` nativo HTML
- Header fixo com 72px de altura
- Tipografia fluida com `clamp()`
- Cards de especialidades (6 cards no grid)
- Seção de atendimento online (depoimento + CTA)
- Responsividade nativa (sem breakpoints — usa clamp)
- Fluxo de navegação (âncoras com smooth scroll)

---

# Checklist para Personalização

- [ ] Inserir logo (nome no header/footer)
- [ ] Alterar nome do profissional ou clínica
- [ ] Atualizar slogan
- [ ] Definir paleta de cores (CSS variables)
- [ ] Inserir número do CRP (hero + footer)
- [ ] Substituir imagem do hero
- [ ] Preencher 3 diferenciais
- [ ] Preencher 6 especialidades
- [ ] Descrever o processo terapêutico (4 etapas)
- [ ] Escrever depoimento da seção "Atendimento Online"
- [ ] Responder FAQ (4 perguntas)
- [ ] Atualizar contatos (telefone, email, endereço)
- [ ] Inserir mapa (Google Maps embed)
- [ ] Configurar formulário (action real)
- [ ] Atualizar SEO (title, description, keywords, OG)
- [ ] Adicionar favicon
- [ ] Adicionar Open Graph image
- [ ] Adicionar Twitter Cards
- [ ] Adicionar Schema.org (Psychologist)
- [ ] Inserir links reais das redes sociais
- [ ] Revisar links internos (âncoras)
- [ ] Revisar mobile
- [ ] Revisar performance
- [ ] Revisar acessibilidade

---

# Tempo estimado

- **IA ou desenvolvedor experiente:** 20–40 minutos
- **Iniciante:** 1–2 horas

---

# Observações

- Este é o **template mais simples e leve** da coleção — ideal para profissionais individuais que querem um site rápido e funcional.
- O FAQ usa `<details>` e `<summary>` nativos do HTML — não precisa de JavaScript para funcionar. Totalmente acessível por padrão.
- O formulário é o **único** entre os templates que já possui `action` e `method="POST"` definidos. Apenas troque `[URL_DO_FORMULARIO]` pela URL de envio real (Formspree, SheetMonkey, etc.).
- A tipografia fluida com `clamp()` elimina a necessidade de múltiplos breakpoints para textos.
- O placeholder de imagem (`via.placeholder.com`) está em um domínio que pode estar offline — substitua por uma imagem real o mais rápido possível.
- Considere adicionar um botão de WhatsApp flutuante (não incluso) para facilitar o contato rápido.
- O mapa usa iframe do Google Maps — gere um embed real e substitua o placeholder.
- É recomendado adicionar Schema.org do tipo `Psychologist` para melhorar o SEO local.
- A paleta de verdes transmite calma e segurança — cores ideais para o nicho de saúde mental. Evite cores muito frias ou vibrantes.
- Para atendimento exclusivamente online, mantenha o foco na seção "Atendimento Online" e ajuste o endereço para "Online (Brasil e Exterior)".
