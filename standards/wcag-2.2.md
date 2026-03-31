# WCAG 2.2 – Critérios de Sucesso

Este documento apresenta um resumo dos critérios de sucesso do **Web Content Accessibility Guidelines (WCAG) 2.2**, publicado pelo W3C em outubro de 2023.

> 📄 Documento oficial: [https://www.w3.org/TR/WCAG22/](https://www.w3.org/TR/WCAG22/)

Os critérios estão organizados nos quatro princípios fundamentais: **Perceptível, Operável, Compreensível e Robusto (POUR)**.

---

## Níveis de Conformidade

| Nível | Descrição |
|-------|-----------|
| **A** | Nível mínimo – deve ser atendido |
| **AA** | Nível recomendado – padrão da indústria e de muitas regulamentações |
| **AAA** | Nível mais alto – desejável em contextos específicos |

> Nossa organização tem como meta atingir o nível **AA** em todos os produtos digitais.

---

## 1. Perceptível

As informações e componentes da interface devem ser apresentados de forma que os usuários possam percebê-los.

### 1.1 Alternativas em Texto

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [1.1.1 Conteúdo Não Textual](https://www.w3.org/TR/WCAG22/#non-text-content) | A | Todo conteúdo não textual apresentado ao usuário deve ter uma alternativa em texto com a mesma finalidade. |

### 1.2 Mídia Baseada em Tempo

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [1.2.1 Apenas Áudio e Apenas Vídeo (Pré-gravado)](https://www.w3.org/TR/WCAG22/#audio-only-and-video-only-prerecorded) | A | Alternativa em texto ou áudio para conteúdo de vídeo e áudio pré-gravado. |
| [1.2.2 Legendas (Pré-gravado)](https://www.w3.org/TR/WCAG22/#captions-prerecorded) | A | Legendas para todo conteúdo de áudio em mídia sincronizada pré-gravada. |
| [1.2.3 Audiodescrição ou Mídia Alternativa (Pré-gravado)](https://www.w3.org/TR/WCAG22/#audio-description-or-media-alternative-prerecorded) | A | Audiodescrição ou alternativa em texto para vídeo pré-gravado. |
| [1.2.4 Legendas (Ao Vivo)](https://www.w3.org/TR/WCAG22/#captions-live) | AA | Legendas para conteúdo de áudio ao vivo em mídia sincronizada. |
| [1.2.5 Audiodescrição (Pré-gravado)](https://www.w3.org/TR/WCAG22/#audio-description-prerecorded) | AA | Audiodescrição para todo conteúdo de vídeo pré-gravado. |

### 1.3 Adaptável

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [1.3.1 Informações e Relações](https://www.w3.org/TR/WCAG22/#info-and-relationships) | A | Estrutura, apresentação e relações transmitidas visualmente também estão disponíveis para tecnologias assistivas. |
| [1.3.2 Sequência Significativa](https://www.w3.org/TR/WCAG22/#meaningful-sequence) | A | A ordem de leitura do conteúdo é determinável de forma programática quando a ordem afeta o significado. |
| [1.3.3 Características Sensoriais](https://www.w3.org/TR/WCAG22/#sensory-characteristics) | A | Instruções não dependem apenas de características sensoriais (forma, cor, tamanho, posição, orientação ou som). |
| [1.3.4 Orientação](https://www.w3.org/TR/WCAG22/#orientation) | AA | O conteúdo não restringe sua visualização a uma única orientação de tela. |
| [1.3.5 Identificação do Propósito de Entrada](https://www.w3.org/TR/WCAG22/#identify-input-purpose) | AA | O propósito de campos de entrada que coletam informações sobre o usuário pode ser determinado de forma programática. |

### 1.4 Distinguível

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [1.4.1 Uso de Cor](https://www.w3.org/TR/WCAG22/#use-of-color) | A | Cor não é o único meio visual de transmitir informação, indicar ação, solicitar resposta ou distinguir elemento visual. |
| [1.4.2 Controle de Áudio](https://www.w3.org/TR/WCAG22/#audio-control) | A | Áudio reproduzido automaticamente por mais de 3 segundos pode ser pausado, parado ou ajustado. |
| [1.4.3 Contraste (Mínimo)](https://www.w3.org/TR/WCAG22/#contrast-minimum) | AA | Texto tem proporção de contraste de pelo menos **4,5:1** (texto normal) ou **3:1** (texto grande). |
| [1.4.4 Redimensionamento de Texto](https://www.w3.org/TR/WCAG22/#resize-text) | AA | Texto pode ser redimensionado até 200% sem tecnologia assistiva e sem perda de conteúdo ou funcionalidade. |
| [1.4.5 Imagens de Texto](https://www.w3.org/TR/WCAG22/#images-of-text) | AA | Texto é usado para transmitir informação em vez de imagens de texto (exceto quando essencial). |
| [1.4.10 Refluxo](https://www.w3.org/TR/WCAG22/#reflow) | AA | Conteúdo não requer rolagem em duas dimensões para viewport de 320px de largura (zoom de 400%). |
| [1.4.11 Contraste de Componentes Não Textuais](https://www.w3.org/TR/WCAG22/#non-text-contrast) | AA | Contraste mínimo de **3:1** para componentes de interface e informações gráficas. |
| [1.4.12 Espaçamento de Texto](https://www.w3.org/TR/WCAG22/#text-spacing) | AA | Nenhum conteúdo ou funcionalidade é perdido ao aplicar espaçamentos específicos de texto. |
| [1.4.13 Conteúdo em Hover ou Foco](https://www.w3.org/TR/WCAG22/#content-on-hover-or-focus) | AA | Conteúdo adicional exibido em hover/foco é dispensável, pode ser apontado/movido e permanece visível. |

---

## 2. Operável

Os componentes da interface e a navegação devem ser operáveis.

### 2.1 Acessível por Teclado

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [2.1.1 Teclado](https://www.w3.org/TR/WCAG22/#keyboard) | A | Toda funcionalidade está disponível via teclado, sem requerer temporizações específicas. |
| [2.1.2 Sem Bloqueio do Teclado](https://www.w3.org/TR/WCAG22/#no-keyboard-trap) | A | O foco do teclado não fica preso em componentes de página. |
| [2.1.4 Atalhos de Tecla de Caractere](https://www.w3.org/TR/WCAG22/#character-key-shortcuts) | A | Atalhos com tecla de caractere única podem ser desativados, remapeados ou ativados apenas em foco. |

### 2.2 Tempo Suficiente

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [2.2.1 Tempo Ajustável](https://www.w3.org/TR/WCAG22/#timing-adjustable) | A | Limites de tempo podem ser desativados, ajustados ou estendidos. |
| [2.2.2 Pausar, Parar, Ocultar](https://www.w3.org/TR/WCAG22/#pause-stop-hide) | A | Conteúdos em movimento, rolagem ou atualizações automáticas podem ser pausados, parados ou ocultados. |

### 2.3 Convulsões e Reações Físicas

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [2.3.1 Três Flashes ou Abaixo do Limite](https://www.w3.org/TR/WCAG22/#three-flashes-or-below-threshold) | A | As páginas não contêm nada que pisque mais de três vezes por segundo, ou o flash está abaixo dos limites gerais de flash e flash vermelho. |

### 2.4 Navegável

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [2.4.1 Ignorar Blocos](https://www.w3.org/TR/WCAG22/#bypass-blocks) | A | Existe mecanismo para pular blocos de conteúdo repetitivo. |
| [2.4.2 Página com Título](https://www.w3.org/TR/WCAG22/#page-titled) | A | As páginas têm títulos que descrevem seu tópico ou propósito. |
| [2.4.3 Ordem do Foco](https://www.w3.org/TR/WCAG22/#focus-order) | A | Componentes recebem foco em uma ordem que preserva o significado e a operabilidade. |
| [2.4.4 Finalidade do Link (Em Contexto)](https://www.w3.org/TR/WCAG22/#link-purpose-in-context) | A | A finalidade de cada link pode ser determinada pelo texto do link, ou pelo contexto programaticamente determinável. |
| [2.4.5 Várias Formas](https://www.w3.org/TR/WCAG22/#multiple-ways) | AA | Há mais de uma forma de localizar uma página em um conjunto de páginas web. |
| [2.4.6 Cabeçalhos e Rótulos](https://www.w3.org/TR/WCAG22/#headings-and-labels) | AA | Cabeçalhos e rótulos descrevem o tópico ou propósito. |
| [2.4.7 Foco Visível](https://www.w3.org/TR/WCAG22/#focus-visible) | AA | Qualquer componente de interface operável por teclado tem um modo de operação onde o indicador de foco está visível. |
| [2.4.11 Aparência do Foco (Mínimo)](https://www.w3.org/TR/WCAG22/#focus-appearance) | AA | O indicador de foco do teclado tem área mínima e contraste suficientes. *(Novo no WCAG 2.2)* |

### 2.5 Modalidades de Entrada

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [2.5.1 Gestos com o Ponteiro](https://www.w3.org/TR/WCAG22/#pointer-gestures) | A | Funcionalidades que usam gestos multipontos ou baseados em trajetória podem ser operadas com ponteiro único sem gesto. |
| [2.5.2 Cancelamento de Ponteiro](https://www.w3.org/TR/WCAG22/#pointer-cancellation) | A | Funcionalidades ativadas por ponteiro único usam evento de soltar (up) e podem ser canceladas. |
| [2.5.3 Rótulo no Nome](https://www.w3.org/TR/WCAG22/#label-in-name) | A | Para componentes com rótulos de texto visíveis, o nome acessível contém o texto visível. |
| [2.5.4 Ativação por Movimento](https://www.w3.org/TR/WCAG22/#motion-actuation) | A | Funcionalidades ativadas por movimento do dispositivo têm componentes de interface alternativos. |
| [2.5.7 Arrastos](https://www.w3.org/TR/WCAG22/#dragging-movements) | AA | Funcionalidades que usam movimento de arraste têm alternativa de ponteiro único sem arraste. *(Novo no WCAG 2.2)* |
| [2.5.8 Tamanho do Alvo (Mínimo)](https://www.w3.org/TR/WCAG22/#target-size-minimum) | AA | Tamanho mínimo do alvo de ponteiro é **24×24 px**. *(Novo no WCAG 2.2)* |

---

## 3. Compreensível

As informações e a operação da interface devem ser compreensíveis.

### 3.1 Legível

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [3.1.1 Idioma da Página](https://www.w3.org/TR/WCAG22/#language-of-page) | A | O idioma humano padrão de cada página pode ser determinado de forma programática. |
| [3.1.2 Idioma das Partes](https://www.w3.org/TR/WCAG22/#language-of-parts) | AA | O idioma humano de cada passagem ou frase do conteúdo pode ser determinado de forma programática. |

### 3.2 Previsível

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [3.2.1 Em Foco](https://www.w3.org/TR/WCAG22/#on-focus) | A | Receber foco em um componente não inicia automaticamente uma mudança de contexto. |
| [3.2.2 Em Entrada](https://www.w3.org/TR/WCAG22/#on-input) | A | Alterar a configuração de componentes de interface não inicia automaticamente uma mudança de contexto. |
| [3.2.3 Navegação Consistente](https://www.w3.org/TR/WCAG22/#consistent-navigation) | AA | Os mecanismos de navegação repetidos em várias páginas aparecem na mesma ordem relativa. |
| [3.2.4 Identificação Consistente](https://www.w3.org/TR/WCAG22/#consistent-identification) | AA | Componentes com a mesma funcionalidade são identificados de forma consistente. |
| [3.2.6 Ajuda Consistente](https://www.w3.org/TR/WCAG22/#consistent-help) | A | Mecanismos de ajuda aparecem na mesma ordem relativa em todas as páginas. *(Novo no WCAG 2.2)* |

### 3.3 Assistência na Entrada

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [3.3.1 Identificação de Erro](https://www.w3.org/TR/WCAG22/#error-identification) | A | Se um erro de entrada é detectado automaticamente, o item com erro é identificado e o erro é descrito ao usuário em texto. |
| [3.3.2 Rótulos ou Instruções](https://www.w3.org/TR/WCAG22/#labels-or-instructions) | A | Rótulos ou instruções são fornecidos quando o conteúdo requer entrada do usuário. |
| [3.3.3 Sugestão de Erro](https://www.w3.org/TR/WCAG22/#error-suggestion) | AA | Se um erro de entrada é detectado e sugestões de correção são conhecidas, a sugestão é fornecida ao usuário. |
| [3.3.4 Prevenção de Erros (Legal, Financeiro, Dados)](https://www.w3.org/TR/WCAG22/#error-prevention-legal-financial-data) | AA | Para páginas que causam compromissos legais ou transações financeiras, as ações são reversíveis, verificáveis ou confirmáveis. |
| [3.3.7 Entrada Redundante](https://www.w3.org/TR/WCAG22/#redundant-entry) | A | Informações já fornecidas pelo usuário no mesmo processo são preenchidas automaticamente ou disponíveis para seleção. *(Novo no WCAG 2.2)* |
| [3.3.8 Autenticação Acessível (Mínimo)](https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum) | AA | Nenhuma etapa cognitiva é necessária para autenticação, a menos que haja alternativa ou assistência disponível. *(Novo no WCAG 2.2)* |

---

## 4. Robusto

O conteúdo deve ser robusto o suficiente para ser interpretado por uma ampla variedade de agentes de usuário, incluindo tecnologias assistivas.

### 4.1 Compatível

| Critério | Nível | Descrição |
|----------|-------|-----------|
| [4.1.1 Análise](https://www.w3.org/TR/WCAG22/#parsing) | A | *(Obsoleto no WCAG 2.2 — considerado sempre satisfeito ou não aplicável)* |
| [4.1.2 Nome, Função, Valor](https://www.w3.org/TR/WCAG22/#name-role-value) | A | Para todos os componentes de interface, o nome e a função podem ser determinados de forma programática; estados, propriedades e valores podem ser definidos programaticamente. |
| [4.1.3 Mensagens de Status](https://www.w3.org/TR/WCAG22/#status-messages) | AA | Mensagens de status podem ser determinadas de forma programática por meio de função ou propriedades, para que possam ser apresentadas ao usuário por tecnologias assistivas sem receber foco. |

---

## Novidades do WCAG 2.2

Os seguintes critérios foram adicionados no WCAG 2.2 (em relação ao WCAG 2.1):

| Critério | Nível |
|----------|-------|
| [2.4.11 Aparência do Foco (Mínimo)](https://www.w3.org/TR/WCAG22/#focus-appearance) | AA |
| [2.5.7 Arrastos](https://www.w3.org/TR/WCAG22/#dragging-movements) | AA |
| [2.5.8 Tamanho do Alvo (Mínimo)](https://www.w3.org/TR/WCAG22/#target-size-minimum) | AA |
| [3.2.6 Ajuda Consistente](https://www.w3.org/TR/WCAG22/#consistent-help) | A |
| [3.3.7 Entrada Redundante](https://www.w3.org/TR/WCAG22/#redundant-entry) | A |
| [3.3.8 Autenticação Acessível (Mínimo)](https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum) | AA |

> O critério 4.1.1 (Análise) foi marcado como obsoleto no WCAG 2.2.

---

## Referências

- [WCAG 2.2 – Documento Completo (W3C)](https://www.w3.org/TR/WCAG22/)
- [Understanding WCAG 2.2 (W3C)](https://www.w3.org/WAI/WCAG22/Understanding/)
- [WCAG 2.2 Quick Reference (W3C)](https://www.w3.org/WAI/WCAG22/quickref/)
- [Diferenças entre WCAG 2.1 e WCAG 2.2 (W3C)](https://www.w3.org/TR/WCAG22/#new-features-in-wcag-2-2)
