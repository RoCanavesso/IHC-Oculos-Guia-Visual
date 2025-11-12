# Modelo Conceitual

## 1. Cenário de Interação

### **Perguntas de Cenário**
1. Quem pode/deve acessar o site e utilizar as ferramentas de acessibilidade disponíveis?  
2. Quando os usuários costumam acessar o site (busca de informações, curiosidade, intenção de compra)?  
3. Quem fornece os conteúdos e descrições acessíveis (equipe técnica, marketing, especialistas em acessibilidade)?  
4. Quais informações devem ser disponibilizadas para garantir compreensão e confiança sobre o produto?  
5. Quantas etapas envolvem o processo de navegação e compra no site?  
6. Quem pode supervisionar a experiência e propor melhorias de acessibilidade?  
7. Que dados são necessários para o cadastro dos usuários interessados (nome, e-mail, tipo de deficiência visual)?  
8. Como o sistema coleta e armazena as preferências de acessibilidade (voz, contraste, tamanho de fonte)?  
9. De quem depende a conclusão da compra ou do cadastro (usuário, sistema, equipe de suporte)?  
10. De que informações os usuários precisam para confirmar o sucesso da interação (feedback sonoro, confirmação visual, e-mail)?  
11. Como o sistema pode adaptar automaticamente suas configurações de acordo com o tipo de deficiência visual detectada?  
12. Em que pontos a interação pode ser mais eficiente (uso de atalhos por voz, descrição automática de imagens, formulários reduzidos)?  
13. Como o usuário pode entrar em contato com a equipe de suporte (telefone acessível, formulário por voz, chat com assistente)?  
14. Quem precisa ser notificado ao final de uma compra ou cadastro (usuário, equipe técnica, suporte ao cliente)?  

---

### **Cenário**
Pessoas com deficiência visual enfrentam dificuldades em encontrar e compreender informações sobre tecnologias assistivas de forma autônoma.  
O desafio é oferecer uma plataforma acessível, com linguagem inclusiva e navegação adaptável, para que tanto usuários com deficiência visual quanto seus familiares possam conhecer e adquirir o produto com facilidade.

**João Alves, 32 anos**, acessa o site utilizando um leitor de tela em seu computador. Assim que entra na página inicial, o sistema reconhece automaticamente o uso do leitor e ativa o modo acessível, priorizando o conteúdo em áudio e simplificando a navegação por comandos de voz.  
O site inicia com uma introdução sonora clara:  
> “Bem-vindo! Este acessório foi desenvolvido para aumentar a autonomia e segurança de pessoas com deficiência visual. Deseja ouvir uma descrição detalhada de como ele funciona?”

João responde com comando de voz e ouve uma explicação sobre as funcionalidades — como o sistema de detecção de obstáculos e os alertas sonoros personalizados. Ele também acessa a seção de demonstração em áudio com exemplos práticos do uso cotidiano.

Enquanto isso, **Mariana Ribeiro, 24 anos**, acessa o site pelo notebook da faculdade.  
Como tem baixa visão, o sistema detecta automaticamente o modo de alto contraste e aumenta o tamanho das fontes, garantindo conforto visual.  
Mariana lê detalhadamente a seção “Como funciona” e assiste aos vídeos com legendas ampliadas. Ao final, preenche um formulário para solicitar uma demonstração gratuita, utilizando o recurso de preenchimento automático.

Por fim, **Ricardo Silva, 56 anos**, acessa o site pelo celular para comprar o produto para o filho.  
Ele encontra facilmente o botão “Adquirir agora”, com linguagem simples e instruções objetivas.  
O sistema simplifica a compra em três etapas curtas e envia confirmação por e-mail e áudio após o pagamento.

> **Resultado:** Cada ator interage com o sistema conforme suas necessidades específicas, com fluidez e sem barreiras, cumprindo os princípios de design universal e acessibilidade digital.

---

## 2. Design Centrado na Comunicação

| **Tópico** | **Falas e Signos** |
|-------------|---------------------|
| **Acessar o site** | **U:** Quero conhecer o acessório assistivo.<br>**D:** Deseja ativar o modo de acessibilidade (leitor de tela, alto contraste, texto ampliado)?<br>**U:** Sim, ativar leitor de tela.<br>**D:** Modo leitor de tela ativado. Você pode navegar por voz ou teclado. |
| **> Página inicial** | **D:** Este é o acessório assistivo inteligente, acoplável a qualquer óculos, que ajuda na identificação de objetos e pessoas via visão computacional.<br>**U:** Quero saber como funciona.<br>**D:** Redirecionando para a seção “Como funciona”. |
| **> Seção "Como funciona"** | **D:** O acessório usa duas câmeras e visão computacional para detectar obstáculos e enviar alertas sonoros.<br>**U:** Há exemplos de uso?<br>**D:** Sim, deseja ouvir o áudio ou assistir ao vídeo?<br>**U:** Áudio, por favor.<br>**D:** Reproduzindo áudio explicativo. |
| **> Benefícios** | **U:** Quais os principais benefícios?<br>**D:** Autonomia, segurança e inclusão. Pode ser usado por pessoas com deficiência visual ou familiares.<br>**U:** Posso testar o produto?<br>**D:** Sim, deseja acessar o formulário de demonstração? |
| **> Solicitar demonstração** | **U:** Quero solicitar.<br>**D:** Informe nome, e-mail e cidade.<br>**U:** Nome: João Alves, e-mail: joaomassoterapeuta@gmail.com, cidade: São Paulo.<br>**D:** Formulário enviado. Você receberá confirmação em até 24h. |
| **> Realizar compra** | **U:** Quero comprar.<br>**D:** Redirecionando para a página de compra segura.<br>**U:** Parcelar em 6 vezes.<br>**D:** Pagamento configurado, confirmar?<br>**U:** Sim.<br>**D:** Compra concluída. Manual acessível enviado. |
| **> Suporte** | **U:** Tenho dúvidas sobre a configuração.<br>**D:** Deseja ouvir o guia em áudio, texto ampliado ou vídeo?<br>**U:** Áudio.<br>**D:** Reproduzindo tutorial sonoro “Como configurar o acessório assistivo”. |
| **> Encerrar** | **U:** Quero sair.<br>**D:** Deseja avaliar sua experiência?<br>**U:** Sim.<br>**D:** Avaliação concluída. Obrigado pela visita! |

---

## 3. Mapa de Objetivos

| **Tipo de Objetivo** | **Formulação (Usuário)** |
|------------------------|--------------------------|
| **Final** | Quer utilizar o site para conhecer, compreender e adquirir o acessório assistivo que aumenta a autonomia e segurança de pessoas com deficiência visual. |
| **Instrumental** | Quer navegar de forma acessível e intuitiva, usando leitores de tela, contraste e áudio-descrição para entender o funcionamento do produto. |
| **Instrumental Direto** | Quer acessar as seções “Como funciona”, “Benefícios”, “Demonstração” e “Comprar” para obter informações e decidir pela compra. |
| **Instrumental Indireto** | Quer acompanhar depoimentos e avaliações para confirmar a confiabilidade do produto e recomendá-lo a outros usuários. |

---

## 4. Esquema Conceitual de Signos — Conteúdo

| **Signo** | **Origem** | **Observações** |
|------------|-------------|-----------------|
| **Modo de acessibilidade** | Domínio | Permite alternar entre leitor de tela, alto contraste e texto ampliado, garantindo inclusão. |
| **Seção “Como funciona”** | Domínio | Apresenta o funcionamento do acessório com imagens, vídeos e descrições em áudio. |
| **Formulário de demonstração** | Domínio | Coleta dados de interessados e envia confirmação por e-mail acessível. |
| **Área de compra** | Domínio | Permite adquirir o produto com opções de parcelamento e feedback auditivo/visual. |
| **Suporte e tutoriais** | Domínio | Oferece guias em texto ampliado, vídeos legendados e tutoriais em áudio. |

---

## 5. Esquema Conceitual de Signos — Prevenção e Recuperação de Rupturas

| **Signo** | **Prevenção** | **Recuperação** |
|------------|---------------|-----------------|
| **Modo de acessibilidade** | PP + AL: opção visível e sonora no topo; ativação imediata ao primeiro acesso. | RA: se o usuário não escolher um modo, o sistema ativa o padrão “leitor de tela”. |
| **Formulário de demonstração** | PP: campos obrigatórios com mensagens de voz e texto de aviso. | RA: mensagens sonoras e visuais em caso de erro, permitindo reenvio. |
| **Área de compra** | PP + AL: etapas guiadas por áudio e texto; botões com contraste e feedback auditivo. | RA: se houver falha, o sistema salva o progresso e reabre a transação. |
| **Suporte e tutoriais** | PP: acessível por comando de voz e menu principal. | RA: redirecionamento automático para suporte via e-mail se o tutorial não resolver. |
| **Feedback geral do sistema** | PP + AL: confirmações multimodais (texto, som, vibração) a cada ação. | RA: repetição automática do feedback se o usuário não interagir em 10 segundos. |

---

> **Conclusão:**  
> O modelo conceitual define como o sistema deve **comunicar-se com usuários com diferentes graus de deficiência visual**, prevenindo falhas de comunicação e garantindo que **cada interação seja clara, acessível e multimodal**.
