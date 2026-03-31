# Checklist de Acessibilidade em Design

Lista de verificação para garantir que os componentes e layouts sejam projetados com acessibilidade desde o início.

---

## Cores e Contraste

- [ ] Todos os pares de cor (texto/fundo) foram verificados com uma ferramenta de contraste
- [ ] Texto normal possui contraste mínimo de **4,5:1**
- [ ] Texto grande (≥ 18pt regular ou ≥ 14pt negrito) possui contraste mínimo de **3:1**
- [ ] Elementos gráficos e ícones significativos possuem contraste mínimo de **3:1** em relação ao fundo
- [ ] A paleta de cores foi validada para usuários com daltonismo (protanopia, deuteranopia, tritanopia)
- [ ] Informações não são transmitidas somente por cor (use ícones, rótulos ou padrões adicionais)

## Tipografia

- [ ] O tamanho mínimo de fonte para texto de corpo é **16px**
- [ ] A altura de linha (line-height) é de no mínimo **1,5× o tamanho da fonte** para texto de corpo
- [ ] O espaçamento entre letras e palavras não compromete a legibilidade
- [ ] Não é utilizado texto em imagem para informações essenciais
- [ ] Fonte escolhida tem boa legibilidade (evitar fontes decorativas para textos longos)

## Layout e Espaçamento

- [ ] A hierarquia visual está claramente definida (cabeçalhos, subseções, conteúdo)
- [ ] Áreas clicáveis têm tamanho mínimo de **44×44 px**
- [ ] Espaçamento adequado entre elementos interativos (mínimo de 8px de separação)
- [ ] O layout foi projetado para funcionar em diferentes tamanhos de tela e orientações
- [ ] O design funciona com zoom de até 200% sem perda de conteúdo

## Formulários e Feedbacks

- [ ] Todos os campos de formulário possuem rótulos visíveis (não apenas placeholder)
- [ ] Mensagens de erro são claras, visíveis e próximas ao campo com problema
- [ ] Campos obrigatórios são indicados de forma clara (não somente por cor)
- [ ] Ícones de status (sucesso, erro, alerta) acompanham texto descritivo

## Componentes e Interações

- [ ] Estados dos componentes (hover, foco, ativo, desabilitado) estão visualmente diferenciados
- [ ] O indicador de foco é visível e tem contraste suficiente com o fundo
- [ ] Animações e transições respeitam a preferência `prefers-reduced-motion`
- [ ] Tooltips e popups não bloqueiam conteúdo importante

## Entrega para Desenvolvimento

- [ ] Especificações de acessibilidade estão documentadas nos arquivos de design (Figma, Sketch, etc.)
- [ ] Rótulos acessíveis estão definidos para ícones e elementos sem texto visível
- [ ] Anotações de ordem de leitura do leitor de tela estão incluídas para layouts complexos

---

## Referências

- [Contrast Checker – WebAIM](https://webaim.org/resources/contrastchecker/)
- [Colour Contrast Analyser (ferramenta desktop)](https://www.tpgi.com/color-contrast-checker/)
- [WCAG 2.2 (W3C)](https://www.w3.org/TR/WCAG22/)
