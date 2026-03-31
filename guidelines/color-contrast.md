# Diretrizes de Contraste de Cores da Marca

Este documento define as regras de contraste de cores a serem seguidas em todos os produtos digitais da organização, garantindo conformidade com o nível **AA do WCAG 2.2**.

---

## Paleta de Cores da Marca

| Nome          | Hex       | Uso Principal             |
|---------------|-----------|---------------------------|
| Primária      | `#0057A8` | Botões, links, destaques  |
| Primária Escura | `#003D75` | Texto sobre fundo claro   |
| Secundária    | `#FF6B00` | CTAs, alertas             |
| Fundo Claro   | `#FFFFFF` | Fundo padrão de páginas   |
| Fundo Cinza   | `#F5F5F5` | Fundo de seções alternadas|
| Texto Principal | `#1A1A1A` | Corpo de texto            |
| Texto Secundário | `#595959` | Textos de apoio, captions |
| Erro          | `#CC0000` | Mensagens de erro         |
| Sucesso       | `#1B7740` | Mensagens de confirmação  |

---

## Regras de Contraste

### Texto Normal (< 18pt regular ou < 14pt negrito)

Proporção mínima exigida: **4,5:1**

| Combinação                        | Proporção | Status   |
|-----------------------------------|-----------|----------|
| Texto Principal `#1A1A1A` / Branco `#FFFFFF` | 16,1:1 | ✅ Passa |
| Texto Secundário `#595959` / Branco `#FFFFFF` | 7,0:1  | ✅ Passa |
| Primária `#0057A8` / Branco `#FFFFFF`         | 7,2:1  | ✅ Passa |
| Primária Escura `#003D75` / Branco `#FFFFFF`  | 9,9:1  | ✅ Passa |
| Secundária `#FF6B00` / Branco `#FFFFFF`       | 2,9:1  | ❌ Falha – **não usar texto branco sobre laranja** |
| Secundária `#FF6B00` / `#1A1A1A`              | 5,6:1  | ✅ Passa |

### Texto Grande (≥ 18pt regular ou ≥ 14pt negrito)

Proporção mínima exigida: **3:1**

| Combinação                        | Proporção | Status   |
|-----------------------------------|-----------|----------|
| Secundária `#FF6B00` / Branco `#FFFFFF`       | 2,9:1  | ❌ Falha – evitar mesmo em texto grande |
| Primária `#0057A8` / Fundo Cinza `#F5F5F5`    | 6,8:1  | ✅ Passa |

### Elementos Gráficos e Ícones

Proporção mínima exigida: **3:1** em relação ao fundo adjacente.

- Ícones informativos devem sempre ter proporção ≥ 3:1
- Ícones puramente decorativos estão isentos desta exigência

---

## Uso da Cor em Contextos Específicos

### Botões

| Estado    | Texto       | Fundo       | Contraste | Status   |
|-----------|-------------|-------------|-----------|----------|
| Padrão    | `#FFFFFF`   | `#0057A8`   | 7,2:1     | ✅ Passa |
| Hover     | `#FFFFFF`   | `#003D75`   | 9,9:1     | ✅ Passa |
| Desabilitado | `#767676` | `#CCCCCC`  | 4,6:1     | ✅ Passa |

### Links

- Links no corpo do texto devem ser diferenciados da cor de texto por **contraste e sublinhado**.
- Cor padrão de link: `#0057A8` sobre fundo branco (contraste 7,2:1).
- Não utilizar somente cor para diferenciar links de texto corrido.

### Mensagens de Status

| Tipo    | Texto        | Fundo      | Contraste | Status   |
|---------|--------------|------------|-----------|----------|
| Erro    | `#CC0000`    | `#FFFFFF`  | 5,9:1     | ✅ Passa |
| Sucesso | `#1B7740`    | `#FFFFFF`  | 5,1:1     | ✅ Passa |

---

## Ferramentas Recomendadas

- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Colour Contrast Analyser (TPGI)](https://www.tpgi.com/color-contrast-checker/)
- Plugin Figma: [Stark – Contrast & Accessibility Checker](https://www.figma.com/community/plugin/732603254453395948/Stark)

---

## Referências

- [WCAG 2.2 – Critério 1.4.3 Contraste (Mínimo)](https://www.w3.org/TR/WCAG22/#contrast-minimum)
- [WCAG 2.2 – Critério 1.4.6 Contraste (Aprimorado)](https://www.w3.org/TR/WCAG22/#contrast-enhanced)
- [WCAG 2.2 – Critério 1.4.11 Contraste de Componentes Não Textuais](https://www.w3.org/TR/WCAG22/#non-text-contrast)
