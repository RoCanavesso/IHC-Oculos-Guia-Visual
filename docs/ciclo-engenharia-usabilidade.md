# Ciclo da Engenharia de Usabilidade

## 1) Características da Plataforma

| **Item** | **Descrição** | **Justificativa** |
|-----------|----------------|-------------------|
| **Software** | Website desenvolvido em **HTML5**, **CSS3**, **JavaScript** e **framework React** | Essas tecnologias permitem criar um site moderno, responsivo e acessível, essencial para pessoas com baixa visão como Mariana. |
| **Backend** | Desenvolvido em **Node.js**, integrado a banco de dados | Permite armazenar formulários, pedidos e feedbacks, além de manter o site leve e rápido mesmo em dispositivos móveis. |
| **Hardware** | Compatível com **computadores, notebooks, tablets e smartphones** | Mariana utiliza tanto o notebook quanto o celular; portanto, a responsividade garante acessibilidade em ambos os contextos. |
| **Sistema Operacional** | Compatível com **Windows, Android, iOS e macOS** | Mariana usa diferentes dispositivos no dia a dia, e o site precisa funcionar de forma estável em todos. |
| **Capacidade de acessibilidade digital** | Compatível com **modos de alto contraste, leitores de tela e ampliação de fonte** | Essencial para usuários com baixa visão, oferecendo leitura visual ampliada e suporte auditivo. |
| **Capacidade multimídia** | Suporte a **vídeos explicativos com legendas ampliadas** e **descrições em áudio** | Mariana busca compreender o funcionamento do produto em situações reais, portanto vídeos acessíveis são fundamentais. |
| **Capacidade de escalabilidade** | **Hospedagem em nuvem** e suporte a picos de acesso | Garante estabilidade e bom desempenho mesmo com alta demanda simultânea. |
| **Restrição técnica 1** | Alguns navegadores limitam **ajustes automáticos de contraste** | Pode exigir configuração manual do contraste pelo usuário. |
| **Restrição técnica 2** | Dependência de **conexão constante com a internet** | Impede o uso offline, o que pode ser um obstáculo em locais com sinal fraco. |
| **Restrição técnica 3** | **Imagens e vídeos em alta resolução** podem ter carregamento lento em conexões móveis | Justifica a implementação de versões otimizadas para dispositivos com baixa largura de banda. |

---

## 2) Princípios Gerais de Projeto

### **Ambiente de uso**

**Mariana Ribeiro:**  
Como Mariana possui baixa visão, o ambiente ideal para uso do site deve possuir boa iluminação e ausência de reflexos na tela, facilitando a leitura visual com zoom.  
Ela costuma acessar o site pelo notebook em casa ou pelo celular durante os deslocamentos, sempre utilizando modo de contraste alto e aumento de fonte.  
O site precisa ser limpo, objetivo e com ícones bem visíveis, evitando sobrecarga de informações.  
Deve oferecer descrições de imagens, textos explicativos curtos e vídeos com legendas ampliadas para garantir compreensão total do conteúdo.

---

### **Contextos sociais, econômicos e culturais**

**Mariana Ribeiro:**  
Mariana faz parte de um grupo social e acadêmico que valoriza a inclusão digital e a acessibilidade na educação.  
Seu contexto econômico é de uma estudante universitária que depende de tecnologias gratuitas ou de baixo custo.  
Culturalmente, ela vive em um ambiente em que o uso de tecnologias assistivas é crescente, mas ainda enfrenta barreiras de acessibilidade nos meios digitais.  
Portanto, o site deve refletir empatia, clareza e simplicidade, apresentando informações que reforcem a independência e autonomia da usuária.

---

### **Informações a serem armazenadas antes da interação**

**Mariana Ribeiro:**  
Antes de iniciar a navegação, o sistema deve armazenar as preferências de acessibilidade de Mariana, como o modo de contraste alto, o nível de zoom aplicado e o idioma de exibição.  
Essas configurações devem ser salvas para que o site mantenha o mesmo padrão visual em acessos futuros.  
Além disso, podem ser armazenadas informações básicas, como localização aproximada (para cálculo de frete) e histórico de navegação, caso Mariana queira retornar a uma seção específica.  
Todos esses dados devem respeitar as normas da **LGPD**, garantindo segurança e privacidade das informações.

---

### **Condições do ambiente durante a interação**

**Mariana Ribeiro:**  
Durante o uso do site, Mariana normalmente estará em casa, estudando ou no intervalo entre aulas, acessando o conteúdo pelo notebook ou celular.  
O ambiente deve ser silencioso e bem iluminado, para que ela consiga visualizar claramente os textos e vídeos.  
O site precisa responder rapidamente aos comandos, evitando transições confusas ou lentas que possam causar perda de foco visual.  
Além disso, deve fornecer feedback visual ampliado (por exemplo, mudança de cor ao clicar em botões) e descrições textuais detalhadas sobre cada funcionalidade.  
O objetivo é garantir autonomia e conforto visual, permitindo que Mariana compreenda todas as informações e execute ações com confiança.

---

## 3) Referências

| **Nome** | **Descrição** | **Importância para o Projeto** | **Link** |
|-----------|----------------|-------------------------------|-----------|
| **WCAG 2.1 (Web Content Accessibility Guidelines)** | Diretrizes internacionais de acessibilidade digital. | Fundamenta o design inclusivo e garante que o site seja acessível a pessoas com baixa visão. | [https://www.w3.org/TR/WCAG21/](https://www.w3.org/TR/WCAG21/) |
| **ISO 9241-210:2019 – Ergonomia da interação humano-sistema** | Norma que define o design centrado no usuário. | Assegura que o site seja desenvolvido considerando as necessidades e limitações reais dos usuários. | [https://www.iso.org/standard/77520.html](https://www.iso.org/standard/77520.html) |
| **Nielsen’s 10 Heuristics for UI Design** | Princípios clássicos de usabilidade para interfaces digitais. | Garante consistência, clareza e feedbacks imediatos — essenciais para pessoas com deficiência visual. | [https://www.nngroup.com/articles/ten-usability-heuristics/](https://www.nngroup.com/articles/ten-usability-heuristics/) |
| **ABNT NBR 17060:2022 – Acessibilidade na Comunicação** | Norma brasileira sobre comunicação acessível. | Garante clareza textual, contraste visual e compreensão do conteúdo em múltiplos formatos. | [https://www.abnt.org.br/](https://www.abnt.org.br/) |
| **NVDA (NonVisual Desktop Access)** | Leitor de tela gratuito para Windows. | Compatibilidade essencial para pessoas com deficiência visual total ou parcial. | [https://www.nvaccess.org/](https://www.nvaccess.org/) |
| **VoiceOver (Apple)** | Sistema de leitura de tela para iOS e macOS. | Assegura acessibilidade para usuários Apple, como Mariana em seu iPhone. | [https://www.apple.com/accessibility/](https://www.apple.com/accessibility/) |

---

## 4) Metas de Usabilidade

### **Qualitativas**
- A interface deve proporcionar uma experiência **intuitiva e acessível**.  
- Os usuários devem se sentir **seguros e independentes** durante a navegação.  
- O site deve ser **compreendido sem necessidade de treinamento prévio**.  
- O conteúdo deve ser apresentado de forma **clara, com contraste e tipografia legível**.

### **Quantitativas**

| **Meta** | **Porcentagem Esperada** | **Justificativa** |
|-----------|--------------------------|-------------------|
| **Facilidade de navegação** | 40% | Usuário deve localizar informações principais (como “Comprar” e “Como Funciona”) em até 3 cliques. |
| **Compreensão do conteúdo** | 30% | O usuário deve compreender as informações exibidas sem auxílio externo. |
| **Satisfação do usuário** | 20% | Medida por questionário pós-uso sobre clareza e conforto visual. |
| **Eficiência de acesso** | 10% | O site deve carregar completamente em até 4 segundos em conexões móveis. |
| **Total** | **100%** |  |

---

> **Conclusão:**  
> O ciclo de engenharia de usabilidade aplicado ao projeto garante que o site atenda aos princípios de **design centrado no usuário** e **acessibilidade digital**, considerando os aspectos técnicos, contextuais e humanos necessários para oferecer uma experiência inclusiva a pessoas com deficiência visual como Mariana Ribeiro.
