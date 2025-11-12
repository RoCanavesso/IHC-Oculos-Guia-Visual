# avaliacao heuristica

# Avaliação Heurística

A avaliação heurística foi conduzida com base nas **dez heurísticas de usabilidade de Jakob Nielsen (1994)**, com o objetivo de identificar problemas de interface e oportunidades de melhoria no site do **Acessório Guia Visual**.

Participaram da avaliação três avaliadores (alunos da disciplina de IHC), que analisaram as páginas *Início*, *Como Funciona*, *Sobre Nós*, *Depoimentos* e *Contato*.  
A escala de severidade utilizada varia de **0 (não é problema)** a **4 (problema crítico)**.

---

## 1. Conjunto de Heurísticas de Nielsen (1994)

| Nº | Heurística | Descrição resumida |
|----|-------------|--------------------|
| 1 | Visibilidade do status do sistema | O sistema deve manter o usuário informado sobre o que está acontecendo, com feedback adequado e em tempo razoável. |
| 2 | Compatibilidade entre sistema e mundo real | A interface deve usar linguagem e conceitos familiares ao usuário. |
| 3 | Controle e liberdade do usuário | O usuário deve poder desfazer ações e navegar livremente. |
| 4 | Consistência e padrões | Termos e elementos visuais devem seguir convenções conhecidas. |
| 5 | Prevenção de erros | A interface deve evitar situações que levem o usuário ao erro. |
| 6 | Reconhecimento em vez de memorização | O sistema deve reduzir a carga de memória do usuário. |
| 7 | Flexibilidade e eficiência de uso | O sistema deve atender tanto usuários iniciantes quanto experientes. |
| 8 | Estética e design minimalista | O conteúdo deve ser relevante e o layout, limpo. |
| 9 | Ajudar usuários a reconhecer, diagnosticar e corrigir erros | As mensagens de erro devem ser claras e informativas. |
| 10 | Ajuda e documentação | A interface deve oferecer ajuda acessível e objetiva. |

---

## 2. Resultados da Avaliação Heurística

| Nº | Heurística violada | Problema identificado | Severidade (0–4) | Sugestão de melhoria |
|----|--------------------|------------------------|-------------------|----------------------|
| 1 | Visibilidade do status do sistema | Após o envio do formulário de contato, o site não exibe mensagem de confirmação. | 3 | Adicionar mensagem “Mensagem enviada com sucesso” ou mudar o botão para “Enviado”. |
| 2 | Compatibilidade entre sistema e mundo real | O texto “Fale conosco” aparece como “Envie feedback”, o que pode confundir usuários. | 2 | Usar linguagem mais natural e próxima do público-alvo. |
| 3 | Controle e liberdade do usuário | Não há botão claro de “voltar” ou “início” em todas as páginas. | 3 | Incluir botão “Voltar à página inicial” no menu fixo. |
| 4 | Consistência e padrões | Alguns ícones (microfone, olho) não possuem legenda visível. | 2 | Adicionar texto alternativo (alt/title) para ícones. |
| 5 | Prevenção de erros | Campos do formulário permitem envio sem preenchimento. | 4 | Implementar validação obrigatória dos campos. |
| 6 | Reconhecimento em vez de memorização | A seção “Como Funciona” usa termos técnicos como “YOLOv8” sem explicação. | 2 | Incluir descrições simples dos termos técnicos. |
| 7 | Flexibilidade e eficiência de uso | Não há atalhos de teclado nem suporte total a leitores de tela. | 3 | Adicionar navegação por tabulação e teclas de atalho (AcessKey). |
| 8 | Estética e design minimalista | Contraste entre texto branco e fundo azul claro é baixo. | 2 | Aumentar contraste de acordo com as diretrizes WCAG. |
| 9 | Ajuda a reconhecer e corrigir erros | Mensagens de erro genéricas (“Erro ao enviar”) não orientam o usuário. | 3 | Especificar o erro e sugerir ação (“Verifique conexão e tente novamente”). |
| 10 | Ajuda e documentação | Falta seção sobre como usar o site com leitor de tela. | 2 | Criar página “Acessibilidade” com instruções. |

---

## 3. Grau de Severidade dos Problemas de Usabilidade

| Grau | Tipo | Descrição |
|------|------|-----------|
| 0 | Sem importância | Não afeta a operação da interface. |
| 1 | Cosmético | Não há necessidade imediata de correção. |
| 2 | Simples | Problema de baixa prioridade (pode ser reparado). |
| 3 | Grave | Problema de alta prioridade (deve ser reparado). |
| 4 | Catastrófico | Muito grave, deve ser resolvido imediatamente. |

---

## 4. Síntese dos Resultados

| Nível de Severidade | Quantidade de Problemas | Percentual aproximado |
|----------------------|------------------------|------------------------|
| Críticos (4) | 1 | 10% |
| Graves (3) | 4 | 40% |
| Médios (2) | 4 | 40% |
| Leves (1–0) | 0 | 0% |

---

## 5. Conclusões e Ações Corretivas

A inspeção demonstrou que o site possui boa estrutura geral e conteúdo consistente, porém há **pontos de atenção na acessibilidade e no feedback ao usuário**, especialmente no uso de mensagens sonoras e visuais.

| Prioridade | Ação proposta | Responsável | Status |
|-------------|---------------|--------------|---------|
| Alta | Implementar validação no formulário de contato | Lucas | Pendente |
| Alta | Exibir mensagem de confirmação após envio | Rômulo | Pendente |
| Média | Aumentar contraste e revisar ícones | Equipe | Em andamento |
| Média | Adicionar página “Acessibilidade” | Rômulo | Planejado |
| Baixa | Revisar termos técnicos e descrições | Lucas | Concluído |

Essas melhorias visam otimizar a usabilidade, reduzir erros e aumentar a confiança do usuário durante o uso do sistema.

---

## 6. Heurísticas Não Violadas (Boas Práticas Observadas)

Durante a análise, também foram identificados aspectos positivos da interface que seguem corretamente as heurísticas de Nielsen.

| Heurística | Boa prática observada | Justificativa |
|-------------|----------------------|----------------|
| Estética e design minimalista | A página inicial apresenta layout limpo, ícones bem distribuídos e foco no conteúdo essencial. | Mantém clareza e reduz sobrecarga cognitiva, facilitando a navegação. |
| Compatibilidade entre sistema e mundo real | O site utiliza linguagem simples e próxima do usuário. | A comunicação direta melhora a compreensão e a sensação de familiaridade. |
| Consistência e padrões | O design das seções segue a mesma estrutura de cores e títulos. | Garante previsibilidade e facilita o aprendizado de uso. |

---

## 7. Considerações Finais

A avaliação heurística demonstrou que o sistema se encontra em estágio avançado de desenvolvimento, apresentando interface funcional e visual agradável.  
Contudo, há oportunidades de aprimoramento para atingir **níveis ideais de acessibilidade e usabilidade**, especialmente para o público com deficiência visual.

Essas melhorias serão aplicadas antes da **avaliação observacional com usuários reais**, finalizando o ciclo de Engenharia de Usabilidade do projeto.
