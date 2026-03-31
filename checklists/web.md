# Checklist de Acessibilidade Web

Lista de verificação para garantir acessibilidade em interfaces web, com base nas diretrizes WCAG 2.2.

---

## Perceptível

- [ ] Todas as imagens possuem texto alternativo (`alt`) descritivo
- [ ] Imagens decorativas utilizam `alt=""` para serem ignoradas por leitores de tela
- [ ] Vídeos possuem legendas sincronizadas
- [ ] Áudios possuem transcrição textual
- [ ] O contraste entre texto e fundo é de no mínimo **4,5:1** para texto normal e **3:1** para texto grande
- [ ] As informações não são transmitidas somente por cor
- [ ] O layout é responsivo e funciona com zoom de até 400%

## Operável

- [ ] Todos os elementos interativos são acessíveis via teclado
- [ ] Não há armadilhas de foco (o foco pode ser movido para fora de qualquer componente usando o teclado)
- [ ] O foco visível está claramente indicado para todos os elementos interativos
- [ ] Não há conteúdo que pisca mais de 3 vezes por segundo
- [ ] Existe mecanismo para pular blocos de conteúdo repetitivo (ex: link "Ir ao conteúdo principal")
- [ ] O tempo limite pode ser ajustado ou desativado pelo usuário (quando aplicável)
- [ ] Todas as funcionalidades ativadas por movimento podem ser ativadas por componentes de interface

## Compreensível

- [ ] O idioma da página está definido no atributo `lang` do elemento `<html>`
- [ ] Os campos de formulário possuem rótulos (`<label>`) associados corretamente
- [ ] Mensagens de erro são claras e identificam o campo com problema
- [ ] A navegação é consistente em todo o site
- [ ] Componentes com a mesma função têm nomes consistentes
- [ ] Prevenção de erros: formulários críticos permitem revisão, confirmação ou cancelamento antes de envio

## Robusto

- [ ] O HTML é válido e bem formado
- [ ] Componentes de interface possuem nome, função e valor acessíveis via ARIA ou HTML semântico
- [ ] Widgets customizados implementam os padrões ARIA apropriados
- [ ] O site funciona com as principais tecnologias assistivas (leitores de tela, ampliadores de tela)

---

## Referências

- [WCAG 2.2 (W3C)](https://www.w3.org/TR/WCAG22/)
- [WebAIM Checklist](https://webaim.org/standards/wcag/checklist)
