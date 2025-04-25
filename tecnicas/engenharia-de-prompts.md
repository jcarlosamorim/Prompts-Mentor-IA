# Técnicas de Engenharia de Prompts

A engenharia de prompts é a prática de criar instruções eficazes para modelos de linguagem. Esta página apresenta técnicas fundamentais para melhorar suas interações com IAs.

## Princípios Básicos

### Seja Específico e Claro

Quanto mais específico for seu prompt, melhores serão os resultados. Evite instruções vagas ou ambíguas.

**Exemplo fraco**: "Escreva sobre cães."
**Exemplo forte**: "Escreva um artigo de 500 palavras sobre as raças de cães mais adequadas para apartamentos, incluindo suas necessidades de exercício e temperamento."

### Forneça Contexto

Inclua informações de fundo relevantes para que a IA compreenda melhor o que você precisa.

**Exemplo fraco**: "Como posso resolver este problema?"
**Exemplo forte**: "Sou professor de matemática do ensino médio. Como posso explicar o teorema de Pitágoras para alunos com dificuldades em geometria básica?"

### Use Exemplos (Few-shot Learning)

Fornecer exemplos do tipo de resposta que você espera pode ajudar a IA a entender melhor seu pedido.

**Exemplo**:
```
Converta estas frases para um tom mais formal:

Informal: "E aí, pessoal! Beleza?"
Formal: "Prezados senhores, como estão todos?"

Informal: "Manda a grana até amanhã, tá?"
Formal:
```

### Role Prompting

Atribua um papel ou persona específica à IA para obter respostas mais direcionadas.

**Exemplo**: "Você é um especialista em física quântica explicando conceitos para um estudante do ensino médio. Explique o princípio da incerteza de Heisenberg em termos simples."

## Técnicas Avançadas

### Chain-of-Thought (Cadeia de Pensamento)

Instrua a IA a mostrar seu raciocínio passo a passo, o que geralmente leva a respostas mais precisas para problemas complexos.

**Exemplo**: "Resolva este problema de probabilidade passo a passo, explicando seu raciocínio em cada etapa: Em um baralho de 52 cartas, qual é a probabilidade de tirar um ás seguido por uma carta de copas?"

### Estruturação com Marcadores

Use marcadores XML ou delimitadores para estruturar partes diferentes do seu prompt.

**Exemplo**:
```
<contexto>
Estou planejando uma viagem para Portugal em julho por 10 dias.
</contexto>

<objetivo>
Criar um roteiro detalhado incluindo atrações turísticas, 
sugestões de hospedagem e opções gastronômicas.
</objetivo>

<formato>
Organize o roteiro por dia, com uma estimativa de tempo 
para cada atividade e custos aproximados.
</formato>
```

### Prompts Reflexivos

Peça à IA para avaliar suas próprias respostas ou considerar diferentes perspectivas.

**Exemplo**: "Explique os prós e contras da energia nuclear. Depois de listar os argumentos, avalie criticamente sua própria resposta e identifique possíveis vieses ou informações omitidas."

## Considerações Importantes

### Iteração e Refinamento

A engenharia de prompts eficaz geralmente requer várias tentativas. Se a resposta não for satisfatória, refine seu prompt e tente novamente.

### Limitações do Modelo

Compreenda que mesmo os melhores prompts têm limitações baseadas nas capacidades do modelo subjacente. Algumas tarefas podem ser fundamentalmente difíceis para IAs atuais.

### Ética e Responsabilidade

Crie prompts que incentivem respostas éticas, precisas e úteis. Evite instruções que possam levar a conteúdo prejudicial ou enganoso.

## Recursos Adicionais

- [Learn Prompting](https://learnprompting.org/) - Um guia abrangente sobre engenharia de prompts
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Exemplos e guias para trabalhar com modelos de linguagem
- [Prompt Engineering Guide](https://www.promptingguide.ai/) - Técnicas avançadas de engenharia de prompts

---

Este guia será expandido constantemente com novas técnicas e exemplos. Contribuições são bem-vindas!
