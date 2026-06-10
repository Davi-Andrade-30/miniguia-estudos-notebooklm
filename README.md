# Guia de Estudos com NotebookLM: Finanças e Investimentos para Iniciantes 

Este repositório foi criado para o desafio de projeto da plataforma DIO. A ideia aqui foi rodar um estudo ativo usando o **Google NotebookLM** para organizar e mastigar conceitos do mercado financeiro, testando diferentes formas de interagir com a IA para extrair o melhor conteúdo possível.

---

## 1. O que eu quis resolver (Contexto e Objetivos)

### Contexto:
O mundo das finanças e investimentos é cheio de sopa de letrinhas (Selic, CDI, IPCA) e conceitos que parecem distantes da realidade de quem está começando. Criei esse caderno temático para centralizar o básico de economia e entender de verdade como e onde colocar o dinheiro para render com segurança.

### Meus Objetivos de Estudo:
* **Geral:** Entender a diferença real (e prática) entre Renda Fixa e Renda Variável.
* **Específico 1:** Sacar como funciona o tripé dos investimentos: Risco, Retorno e Liquidez.
* **Específico 2:** Mapear o que desconta do meu rendimento (como inflação e impostos) no curto prazo.

---

## 2. Fontes que usei (Curadoria)

Para não deixar a IA inventar moda ou "alucinar", alimentei o NotebookLM com **4 fontes oficiais e diretas ao ponto**:

1. **B3 (Bolsa de Valores):** *Guia de Renda Fixa para Iniciantes* (Conceitos sobre títulos públicos e privados).
2. **Banco Central do Brasil:** *Caderno de Educação Financeira* (Planejamento e gestão de riscos).
3. **CVM (Comissão de Valores Mobiliários):** *Como Funciona a Renda Variável e as Ações* (Focado em volatilidade e renda variável).
4. **ANBIMA:** *Princípios Básicos de Economia e Finanças* (Manual didático explicativo sobre Selic, CDI e IPCA).

---

## 3. Testes de Prompt e Ajustes no Caminho (Troubleshooting)

Aqui está o que deu certo e o que deu errado na hora de conversar com o NotebookLM:

### Teste 1: Pergunta Direta (Zero-shot)
* **Prompt que mandei:** `"O que é Renda Fixa e quais são os principais títulos?"`
* **O que a IA respondeu:** Listou Tesouro Direto, CDB e LCI/LCA certinho. Mas o texto ficou gigante, muito teórico e chato de ler.
* **Onde travou:** Faltou didática. Mandar uma pergunta muito direta faz a IA responder como um dicionário técnico, o que não ajuda quem está aprendendo.

### Teste 2: Mudando o Papel (Role Prompting + Exemplo)
* **Prompt que mandei:** `"Atue como um professor de finanças para iniciantes. Explique a diferença entre Renda Fixa e Renda Variável usando uma metáfora simples do dia a dia (tipo aluguel de imóvel versus ser sócio de um comércio). Deixe a resposta curta, com a metáfora em destaque e feche com tópicos."`
* **O que a IA respondeu:** Aqui o jogo mudou. Ela comparou a estabilidade da Renda Fixa com o recebimento de um aluguel garantido todo mês, e o risco da Renda Variável com o lucro oscilante de uma loja. Ficou muito mais fácil de entender.

### Teste 3: Fazendo a IA pensar passo a passo (Chain of Thought)
* **Prompt que mandei:** `"Um investidor iniciante tem R$ 5.000,00 e quer aplicar essa grana em um lugar onde ele não corra o risco de perder o dinheiro principal, porque vai precisar dele daqui a 6 meses. Pense passo a passo sobre qual categoria de investimento atende a esse perfil e me explique a sua lógica antes de dar a resposta final."`
* **O que a IA respondeu:** O modelo quebrou o problema em etapas: primeiro isolou o prazo (6 meses é curto prazo, então Renda Variável tá fora pela oscilação), depois olhou a segurança (risco baixo) e concluiu que a melhor saída seria um título de Renda Fixa pós-fixado com liquidez diária (tipo Tesouro Selic ou CDB 100% CDI). Ver a IA "pensando" ajuda muito a validar a decisão.

---

## 4. O Guia Consolidado (Entrega Final)

### A. Resumos Diretos
* **Renda Fixa:** É basicamente você emprestar dinheiro para um banco ou para o governo em troca de juros. Você já sabe (ou tem uma boa ideia de) como o dinheiro vai render desde o começo. É o lugar certo para colocar a reserva de emergência.
* **Renda Variável:** É quando você compra uma parte de um negócio (como ações ou fundos imobiliários). Não tem garantia nenhuma de ganho: se a empresa for bem, você lucra (via dividendos ou valorização); se for mal, você pode perder dinheiro. Foco total no longo prazo.

### B. Mini Glossário
* **Liquidez:** O quão rápido você consegue pegar o seu investimento e transformar em dinheiro na conta sem perder valor no resgate.
* **Volatilidade:** O famoso "sobe e desce" do mercado. É a frequência com que o preço de um ativo muda todo dia.
* **CDI:** A taxa de juros que os bancos cobram entre si. Ela anda colada com a Selic e serve de meta para os investimentos de Renda Fixa (ex: "esse CDB paga 100% do CDI").
* **IPCA:** É o índice oficial da inflação. Seu investimento precisa render mais que o IPCA para o seu dinheiro não perder poder de compra.

### C. Prompts que deixei prontos para revisar depois
Dá para copiar e colar esses comandos direto no chat do NotebookLM para estudar depois:
1. `"Gere uma tabela comparativa mostrando o desconto de Imposto de Renda e IOF para resgates de Renda Fixa antes e depois de 30 dias."`
2. `"Com base nos arquivos que te passei, crie um quiz de 3 perguntas de múltipla escolha sobre Risco, Retorno e Liquidez. Só me dê o gabarito quando eu pedir."`
3. `"Qual é a diferença real de risco entre investir em um CDB de banco menor e investir no Tesouro Direto?"`

---

## Minha Visão sobre a Ferramenta
O NotebookLM quebra um galho enorme porque você consegue travar o contexto dele nos teus arquivos. Como ele bota as referências com links clicáveis direto no parágrafo do PDF, você não precisa ficar com medo de a IA inventar dados. No fim das contas, sabendo estruturar o prompt e usando o comando certo para cada situação, dá para acelerar o aprendizado de qualquer assunto complexo.
