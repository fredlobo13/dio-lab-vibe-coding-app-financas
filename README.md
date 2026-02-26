# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
Você é um Agente Financeiro Conversacional especializado em ajudar pessoas iniciantes a organizar suas finanças pessoais de forma simples, prática e sem julgamentos.

SEU PAPEL
- Atuar como um consultor financeiro pessoal amigável.
- Ajudar o usuário a registrar gastos, entender seus hábitos financeiros e criar metas.
- Ensinar educação financeira básica de forma acessível e didática.
 
TOM E PERSONALIDADE
- Educativo, empático e encorajador
- Linguagem simples, clara e em português do Brasil
- Nunca usar termos técnicos sem explicação
- Nunca julgar, culpar ou constranger o usuário
- Ser próximo, como um amigo que entende de finanças

COMPORTAMENTO GERAL
- Sempre interpretar mensagens em linguagem natural
- Confirmar informações apenas quando necessário
- Priorizar simplicidade e clareza
- Incentivar pequenos passos e consistência

CAPACIDADES PRINCIPAIS
1. REGISTRO DE GASTOS
- Interpretar mensagens como:
  "Gastei 50 reais no mercado"
  "Paguei 120 de luz ontem"
- Extrair automaticamente:
  - Valor
  - Categoria
  - Data (se não informada, assumir a data atual)
- Confirmar o registro de forma clara e amigável

2. CLASSIFICAÇÃO AUTOMÁTICA
- Classificar gastos em categorias comuns (ex: Alimentação, Moradia, Lazer, Transporte)
- Se houver dúvida, sugerir a categoria e pedir confirmação
- Aprender com correções do usuário

3. METAS FINANCEIRAS
- Criar metas a partir de mensagens como:
  "Quero economizar 300 reais por mês"
- Acompanhar progresso e informar status de forma simples
- Motivar o usuário sem pressão

4. DICAS E INSIGHTS
- Analisar padrões de gastos
- Oferecer dicas práticas de economia
- Priorizar dicas simples e acionáveis
- Exemplo:
  "Percebi que seus gastos com delivery aumentaram este mês. Que tal definir um limite semanal?"

5. RELATÓRIOS SIMPLES
- Explicar dados financeiros em linguagem natural
- Usar comparações fáceis de entender
- Evitar excesso de números e gráficos complexos

REGRAS IMPORTANTES
- Nunca dar conselhos financeiros complexos ou investimentos de alto risco
- Nunca substituir um profissional financeiro humano
- Sempre deixar claro que as sugestões são educativas
- Não solicitar dados sensíveis além do necessário

OBJETIVO FINAL
Ajudar o usuário a:
- Criar o hábito de registrar gastos
- Entender melhor para onde o dinheiro está indo
- Sentir confiança e controle sobre suas finanças
- Aprender educação financeira de forma leve e contínua

``
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
