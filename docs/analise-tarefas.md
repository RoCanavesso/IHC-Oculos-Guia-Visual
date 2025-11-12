# Análise de Tarefas

## 1. HTA (Hierarchical Task Analysis)

A análise HTA representa a sequência hierárquica de ações que o usuário realiza ao **navegar no site do acessório assistivo** — desde o acesso inicial até a conclusão da compra ou contato com o suporte.  
O objetivo é identificar **os pontos críticos de interação** e garantir que cada etapa seja acessível para pessoas com deficiência visual.

<img width="1368" height="799" alt="image" src="https://github.com/user-attachments/assets/b0c889f6-6af5-43a2-a19a-df0dbe816943" />

<table border="1" cellspacing="0" cellpadding="6">
 <tr>
  <th>Objetivos / Operações</th>
  <th>Problemas e Recomendações</th>
 </tr>

 <tr>
  <td>0. Navegar no site para conhecer e adquirir o acessório assistivo</td>
  <td>
   Input: Acesso inicial ao site via navegador e uso opcional de leitor de tela. <br>
   Feedback: O site deve emitir respostas auditivas e visuais para cada interação do usuário. <br>
   Plano: O usuário realiza a navegação sequencial pelas seções principais até obter as informações e concluir a compra. <br>
   Recomendação: Estrutura simples, menus acessíveis e atalhos de teclado para navegação inclusiva.
  </td>
 </tr>

 <tr>
  <td>1. Acessar o site</td>
  <td>
   Input: Endereço digitado no navegador. <br>
   Feedback: Página inicial confirmada por mensagem sonora e visual. <br>
   Recomendação: Garantir carregamento rápido e compatibilidade com leitores de tela.
  </td>
 </tr>

 <tr>
  <td>2. Explorar a página inicial</td>
  <td>
   Input: Seleção de menus principais. <br>
   Feedback: Confirmação sonora ou destaque visual. <br>
   Recomendação: Legibilidade, contraste elevado e botões claros.
  </td>
 </tr>

 <tr>
  <td>3. Conhecer o funcionamento do produto</td>
  <td>
   Input: Seleção da aba “Como Funciona”. <br>
   Feedback: Vídeo narrado e descrição em áudio. <br>
   Recomendação: Incluir legendas e narração sincronizada.
  </td>
 </tr>

 <tr>
  <td>4. Avaliar opiniões e benefícios</td>
  <td>
   Input: Acesso à aba “Depoimentos”. <br>
   Feedback: Reprodução de áudios e exibição de textos curtos. <br>
   Recomendação: Tornar os depoimentos acessíveis em áudio e texto.
  </td>
 </tr>

 <tr>
  <td>5. Iniciar o processo de compra</td>
  <td>
   Input: Preenchimento do formulário. <br>
   Feedback: Mensagens auditivas e visuais confirmando cada etapa. <br>
   Recomendação: Suporte total a teclado e leitores de tela.
  </td>
 </tr>

 <tr>
  <td>6. Contatar o suporte</td>
  <td>
   Input: Escolha do canal (chat, e-mail, formulário). <br>
   Feedback: Resposta automática de confirmação sonora. <br>
   Recomendação: Chat acessível com comandos de voz opcionais.
  </td>
 </tr>

 <tr>
  <td>7. Encerrar a sessão</td>
  <td>
   Input: Fechar navegador ou voltar à página inicial. <br>
   Feedback: Salvar preferências (contraste, idioma, etc). <br>
   Recomendação: Permitir encerramento seguro e em conformidade com a LGPD.
  </td>
 </tr>
</table>

> **Resumo:**  
> O HTA evidenciou que a maior carga cognitiva está nas etapas de **formulários e feedbacks**, onde o usuário precisa ter **respostas auditivas e visuais claras** para se sentir confiante na navegação.

---

## 2. GOMS (Goals, Operators, Methods, Selection Rules)

O modelo GOMS descreve as **ações cognitivas e motoras** realizadas por usuários com e sem deficiência visual ao explorar o site.  
Ele ajuda a entender como **cada método varia conforme o perfil do usuário** (uso de voz, teclado ou mouse).


Goal 0: Navegar no site para conhecer e adquirir o acessório assistivo
- Method 0.1: Acessar o site e explorar suas seções até concluir uma compra.
(SEL.RULE: O usuário deseja conhecer o produto e adquiri-lo.)
  - OP.0.1.1: Abrir o navegador.
  - OP.0.1.2: Digitar o endereço do site ou acessá-lo por link.
  - OP.0.1.3: Ativar o leitor de tela, se necessário.
  - OP.0.1.4: Navegar pelos menus principais (Início, Como Funciona, Depoimentos, Comprar Agora).
  - OP.0.1.5: Seguir o fluxo de informações até o processo de compra.

Goal 1: Acessar o site
- Method 1.A: Utilizar o navegador de internet.
(SEL.RULE: O usuário possui um computador com acesso à internet.)
  - OP.1.A.1: Abrir o navegador.
  - OP.1.A.2: Digitar o endereço do site.
  - OP.1.A.3: Pressionar Enter e aguardar o carregamento da página inicial.
- Method 1.B: Acessar o site por meio de comando de voz.
(SEL.RULE: O usuário é deficiente visual e utiliza assistente de voz.)
  - OP.1.B.1: Dizer “Abrir site do acessório assistivo”.
  - OP.1.B.2: O navegador abre a página automaticamente.

Goal 2: Explorar a página inicial
- Method 2.A: Utilizar a navegação por teclado.
(SEL.RULE: O usuário está usando leitor de tela.)
  - OP.2.A.1: Pressionar Tab para percorrer menus e botões.
  - OP.2.A.2: Ouvir o leitor de tela anunciar os títulos das seções.
  - OP.2.A.3: Pressionar Enter para acessar uma seção.

- Method 2.B: Utilizar o mouse.
(SEL.RULE: O usuário não possui deficiência visual.)
  - OP.2.B.1: Mover o cursor até o menu principal.
  - OP.2.B.2: Clicar na aba desejada.
  - OP.2.B.3: Visualizar a nova página carregada.

Goal 3: Conhecer o funcionamento do produto
- Method 3.A: Ouvir demonstração em áudio.
(SEL.RULE: O usuário é cego ou tem baixa visão.)
        - OP.3.A.1: Clicar ou navegar até “Como Funciona”.
        - OP.3.A.2: O site reproduz automaticamente uma descrição sonora do produto.
        - OP.3.A.3: O usuário ouve explicações sobre sensores e feedback sonoro.

- Method 3.B: Assistir vídeo com legenda e narração.
(SEL.RULE: O usuário tem visão parcial ou total.)
        - OP.3.B.1: Clicar no vídeo demonstrativo.
        - OP.3.B.2: Ativar legendas ou narração opcional.
        - OP.3.B.3: Compreender visualmente o funcionamento do acessório.

Goal 4: Avaliar opiniões e benefícios
- Method 4.A: Ouvir depoimentos em áudio.
(SEL.RULE: O usuário usa leitor de tela.)
        - OP.4.A.1: Navegar até a aba “Depoimentos”.
        - OP.4.A.2: Ouvir relatos de usuários sobre experiências com o produto.
        - OP.4.A.3: Refletir sobre a utilidade do produto.

- Method 4.B: Ler depoimentos em texto.
(SEL.RULE: O usuário não possui deficiência visual.)
        - OP.4.B.1: Rolar a página até a seção de comentários.
        - OP.4.B.2: Ler os relatos e visualizar avaliações com estrelas.

Goal 5: Iniciar o processo de compra
- Method 5.A: Comprar via formulário acessível.
(SEL.RULE: O usuário usa leitor de tela.)
        - OP.5.A.1: Navegar até “Compre Agora”.
        - OP.5.A.2: Preencher formulário com auxílio do leitor de tela.
        - OP.5.A.3: Escolher forma de pagamento.
        - OP.5.A.4: Confirmar compra.
        - OP.5.A.5: Receber feedback auditivo de confirmação.

- Method 5.B: Comprar via navegação tradicional.
(SEL.RULE: O usuário sem deficiência visual usa mouse ou toque.)
        - OP.5.B.1: Clicar em “Compre Agora”.
        - OP.5.B.2: Escolher forma de pagamento.
        - OP.5.B.3: Confirmar e finalizar compra.
        - OP.5.B.4: Receber e-mail de confirmação.

Goal 6: Contatar o suporte
- Method 6.A: Preencher formulário de contato.
(SEL.RULE: O usuário prefere escrita ao chat.)
        - OP.6.A.1: Acessar aba “Fale Conosco”.
        - OP.6.A.2: Preencher campos obrigatórios (nome, e-mail, mensagem).
        - OP.6.A.3: Enviar formulário.
        - OP.6.A.4: Receber mensagem automática de confirmação.

- Method 6.B: Usar comando de voz para contato.
(SEL.RULE: O usuário é deficiente visual total.)
        - OP.6.B.1: Dizer “Abrir suporte”.
        - OP.6.B.2: Ditar mensagem de voz.
        - OP.6.B.3: O sistema confirma envio por áudio.

Goal 7: Encerrar a sessão
- Method 7.A: Fechar navegador manualmente.
(SEL.RULE: O usuário completou a navegação.)
        - OP.7.A.1: Pressionar “Alt + F4” ou clicar em “Fechar”.

- Method 7.B: Encerrar por comando de voz.
(SEL.RULE: O usuário utiliza leitor de tela com assistente ativado.)
        - OP.7.B.1: Dizer “Fechar site”.
        - OP.7.B.2: O navegador encerra automaticamente.

