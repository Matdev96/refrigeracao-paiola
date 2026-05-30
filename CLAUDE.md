# Refrigeração Paiola — CLAUDE.md

## Sobre o Projeto

Site institucional / landing page para a **Refrigeração Paiola**, empresa de assistência técnica com mais de 20 anos de atuação na Região do ABC (SP). O site substitui a versão anterior em WordPress por uma solução em HTML/CSS/JS puro — sem framework, sem dependências de build.

## Dados do Cliente

- **Empresa:** Refrigeração Paiola
- **CNPJ:** 14.337.508/0001-94
- **Telefone:** (11) 4453-3168
- **WhatsApp:** https://wa.me/551144533168
- **Site atual (WordPress):** https://refrigeracaopaiola.com.br
- **Horário:** Seg–Sex, 08:00–12:00 e 13:30–18:00 (exceto feriados)
- **Cobertura:** Santo André, São Bernardo do Campo, São Caetano do Sul, Diadema, Mauá, Ribeirão Pires, Rio Grande da Serra

## Serviços

1. Ar Condicionado — instalação, manutenção, higienização, recarga de gás
2. Refrigeração — geladeiras, freezers, expositores comerciais
3. Lava-Seca e Lavadoras — instalação e assistência técnica multimarcas

## Marcas Atendidas

Samsung (especialista), LG, Brastemp, Consul, Electrolux, Midea, GE, Springer

## Stack Técnica

- **HTML5** semântico (único arquivo `index.html`)
- **CSS3** em `styles.css` com variáveis CSS, Grid e Flexbox
- **Sem framework** — JavaScript vanilla para interatividade
- **Fontes:** Google Fonts (Space Grotesk, IBM Plex Sans, Archivo, Sora)
- **Hospedagem prevista:** substituição do WordPress existente

## Paleta de Cores (Identidade Visual)

| Nome | Hex |
|------|-----|
| Midnight navy | `#010f64` |
| Deep navy | `#081c9a` |
| Ocean blue | `#025d9d` |
| Electric blue (CTA) | `#0022ff` |
| Sky blue (highlights escuros) | `#008ff4` |
| Light periwinkle | `#bdd4eb` |
| Branco | `#ffffff` |

**Regra de contraste:** `#0022ff` com texto branco em fundos claros; `#008ff4` como destaque em fundos escuros (hero, footer, seção de marcas).

## Estrutura de Arquivos

```
/
├── index.html          # Página única (single-page)
├── styles.css          # Todo o CSS do projeto
├── CLAUDE.md           # Este arquivo
└── screenshots/        # Assets e referências visuais
    └── logotipo fundo transparente PNG.png
```

## Seções da Página (Ordem)

1. Header sticky com logo + nav + CTA WhatsApp
2. Hero — headline orientada à dor, CTAs, chips de confiança
3. Trust Strip — stats (+20 anos, 7 cidades, peças originais) + marcas
4. Serviços — 3 cards (Ar-condicionado, Refrigeração, Lava-seca)
5. Diferenciais — pilares de confiança
6. Quem Somos — história da empresa
7. Cobertura — cidades atendidas
8. FAQ — dúvidas frequentes
9. CTA Final — conversão WhatsApp + telefone
10. Footer — contato, links, horário, CNPJ

## Logo

- Arquivo local: `screenshots/logotipo fundo transparente PNG.png`
- URL WordPress: `https://refrigeracaopaiola.com.br/wp-content/uploads/2026/04/Logo-Paiola-Sem-fundo-1.png`
- Fundo transparente (PNG). Usar em header e footer.

## Notas de Desenvolvimento

- WhatsApp sempre com mensagem pré-preenchida: `?text=Olá%2C%20quero%20fazer%20um%20orçamento.`
- Número formatado: `tel:551144533168` (com DDI 55)
- O logo no header deve funcionar sobre fundo claro (header é branco translúcido) — usar versão colorida do logo
- Manter acessibilidade: `aria-label` nos ícones, contraste WCAG AA mínimo
