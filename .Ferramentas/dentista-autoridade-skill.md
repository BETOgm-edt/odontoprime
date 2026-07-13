# Skill: Odonto Prime - Site Autoridade

## Visão Geral
Esta skill orienta o assistente de IA na criação e manutenção de um "Site Autoridade" para clínicas odontológicas. O objetivo é desenvolver uma presença digital de altíssimo nível, convertendo visitantes em pacientes, unindo os requisitos específicos do nicho odontológico com as diretrizes avançadas de design da ferramenta **UI/UX Pro Max**.

## Requisitos do Site Autoridade (Checklist)

Sempre que atuar no projeto "Site Autoridade", garanta que as entregas cumpram rigorosamente os 11 pilares abaixo:

1. **Design Exclusivo:** Interface premium, moderna e harmoniosa (utilizando a skill UI/UX Pro Max para cores, tipografia e estilos).
2. **Mobile Perfeito:** Responsividade impecável em todos os dispositivos. Mobile-first na construção do CSS.
3. **SEO:** Meta tags adequadas, hierarquia de headings (H1, H2, H3), alt nas imagens, e estrutura semântica HTML5.
4. **Google Maps:** Integração de iframe do Google Maps na seção de Localização para facilitar a chegada ao consultório.
5. **WhatsApp:** Botões de CTA claros e um botão flutuante persistente integrados diretamente ao WhatsApp da clínica.
6. **Velocidade (Core Web Vitals):** Preload da imagem hero (`<link rel="preload" as="image">`), uso de `fetchpriority="high"` no LCP, `loading="lazy"` abaixo da dobra e dimensões explícitas (`width` e `height`) para prevenir CLS. `<link rel="preconnect">` para fontes/CDNs.
7. **Hospedagem:** Estrutura pronta para deploy "one-click" em plataformas modernas (como Vercel, Netlify ou GitHub Pages).
8. **Analytics:** Código estruturado para fácil inserção de tags do Google Analytics (GA4) e Meta Pixel no `<head>`.
9. **Formulários:** Estrutura pronta para captação de leads, agendamento de consultas ou triagem.
10. **Página Institucional:** Seções bem definidas apresentando a clínica, a equipe, a autoridade do dentista e as avaliações (prova social).
11. **Até 10 Páginas:** Arquitetura planejada para escalar. Pode ser uma One-Page robusta ou um site com páginas separadas para tratamentos específicos.

## Integração com UI/UX Pro Max

Esta skill **DEVE** trabalhar em conjunto com a skill `ui-ux-pro-max`. Durante a geração de código, o assistente deve:

- **Estilo (Domain: style):** Buscar referências de estilo para saúde/clínica (ex: "glassmorphism", "clean", "trustworthy").
- **Cores (Domain: color):** Utilizar paletas de alta conversão (ex: tons de azul confiável, verde esmeralda, branco clínico e cinza escuro para textos).
- **Tipografia (Domain: typography):** Aplicar combinações modernas do Google Fonts (ex: Inter, Outfit, Roboto).
- **UX e Conversão (Domain: landing / ux):** Seguir as melhores práticas de posicionamento de CTAs, contraste e legibilidade para garantir a conversão máxima de pacientes.

## Diretrizes de Implementação

- **Linguagem e Stack:** HTML5, CSS3 Vanilla (ou framework solicitado), JavaScript Vanilla.
- **Estética:** Evite cores genéricas. Use gradientes sutis, sombras suaves (box-shadow) e micro-interações (hover, focus) para encantar o usuário.
- **Imagens (Anti-Duplicação e Prompts):** NUNCA duplique a mesma imagem em seções diferentes do site. Caso falte uma imagem (ex: foto da equipe, novo tratamento), insira um elemento visual de "Placeholder" elegante no HTML e **sempre escreva no chat o Prompt detalhado para geração de IA (Midjourney/DALL-E)**. Assim, o usuário criará a imagem exata e devolverá o link. Foco em sorrisos reais, limpeza e tecnologia clínica.

---
*Para utilizar, o agente deve sempre consultar este checklist antes de validar uma PR ou considerar uma funcionalidade concluída.*
