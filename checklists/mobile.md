# Checklist de Acessibilidade Mobile

Lista de verificação para garantir acessibilidade em aplicativos móveis (iOS e Android).

---

## Elementos de Interface

- [ ] Todos os elementos interativos possuem rótulo acessível (content description / accessibilityLabel)
- [ ] Elementos decorativos estão marcados como decorativos para serem ignorados por leitores de tela
- [ ] Botões e áreas de toque têm tamanho mínimo de **44×44 pt (iOS)** ou **48×48 dp (Android)**
- [ ] Elementos interativos próximos possuem espaçamento adequado para evitar toques acidentais
- [ ] Ícones acompanham texto ou possuem rótulo acessível

## Contraste e Cores

- [ ] O contraste entre texto e fundo é de no mínimo **4,5:1** para texto normal e **3:1** para texto grande
- [ ] As informações não são transmitidas somente por cor
- [ ] O app funciona corretamente no modo de alto contraste do sistema

## Navegação e Foco

- [ ] A ordem de foco do leitor de tela é lógica e consistente com o layout visual
- [ ] Modais e diálogos capturam o foco ao abrir e restauram o foco ao fechar
- [ ] Gestos customizados têm alternativas acessíveis
- [ ] O app suporta navegação por teclado externo (Bluetooth)

## Texto e Conteúdo

- [ ] O tamanho de fonte respeita as configurações de acessibilidade do sistema (Dynamic Type / Font Scale)
- [ ] O conteúdo não é truncado de forma inacessível quando o tamanho de fonte aumenta
- [ ] Vídeos possuem legendas; áudios possuem transcrição
- [ ] Animações e conteúdos em movimento podem ser pausados ou desativados

## Leitores de Tela

- [ ] O app foi testado com VoiceOver (iOS) e TalkBack (Android)
- [ ] Notificações e alertas são anunciados pelos leitores de tela
- [ ] Mensagens de erro são lidas pelo leitor de tela imediatamente após ocorrer
- [ ] Atualizações dinâmicas de conteúdo utilizam regiões ao vivo (`accessibilityLiveRegion` / `UIAccessibilityPostNotification`)

---

## Referências

- [Diretrizes de Acessibilidade do iOS (Apple)](https://developer.apple.com/accessibility/)
- [Diretrizes de Acessibilidade do Android (Google)](https://developer.android.com/guide/topics/ui/accessibility)
- [WCAG 2.2 - Critérios Aplicáveis a Mobile (W3C)](https://www.w3.org/TR/WCAG22/)
