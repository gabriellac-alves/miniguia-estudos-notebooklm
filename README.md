# 🐍 Miniguia de Estudos de Python com NotebookLM

## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte de um desafio prático na plataforma da DIO (Digital Innovation One). O objetivo principal é explorar o uso da Inteligência Artificial como uma ferramenta de aprendizagem ativa, utilizando o **NotebookLM** da Google para estruturar, revisar e consolidar meus estudos na linguagem Python.

Escolhi Python por ser uma linguagem extremamente versátil e que estou aprendendo atualmente para evoluir na área de programação e tecnologia. Durante o projeto, utilizei a IA de forma estratégica para resumir conteúdos complexos, explicar conceitos fundamentais, gerar exemplos práticos e criar um material sólido de revisão.

---

## 🎯 Objetivos
* 🚀 **Aprimorar conhecimentos:** Fortalecer minha base lógica e sintática em Python.
* 🤖 **Uso estratégico de IA:** Aprender a extrair o melhor de ferramentas baseadas em IA generativa voltadas para o estudo.
* 🗂️ **Organização ágil:** Centralizar e estruturar conteúdos de forma prática e produtiva.
* ✍️ **Material de Revisão:** Criar resumos estruturados e um glossário de fácil consulta para o dia a dia.
* 🛠️ **Engenharia de Prompts:** Testar e documentar diferentes variações de perguntas no NotebookLM.

---

## 🧠 Sobre o NotebookLM
O NotebookLM é uma ferramenta experimental da Google que funciona como um assistente de pesquisa virtual alimentado por Inteligência Artificial. Diferente de outros chats de IA tradicionais, ele foca estritamente nos documentos que o usuário envia (fontes), o que reduz drasticamente as chances de alucinações e garante respostas altamente personalizadas e fundamentadas.

**Principais recursos explorados:**
* Geração de resumos automáticos a partir de ementas e documentações.
* Respostas a perguntas complexas contextualizadas com os materiais de estudo.
* Criação de notas explicativas e correlações entre diferentes fontes.
* Organização de anotações soltas em guias de estudo estruturados.

---

## 📚 Fontes Utilizadas
Para alimentar o NotebookLM com dados confiáveis e de alta qualidade, selecionei documentações e ementas de cursos de referência no mercado:

1. **Documentação Oficial do Python 3** *O guia definitivo e oficial sobre a linguagem.* 🔗 [Acessar Documentação Oficial](https://docs.python.org/3/)
   
2. **Curso em Vídeo - Python 3 (Mundo 1)** *Ementa e estrutura didática do professor Gustavo Guanabara, focada em fundamentos e lógica.* 🔗 [Acessar Curso em Vídeo](https://www.cursoemvideo.com/curso/python-3-mundo-1/)
   
3. **W3Schools - Python Tutorial** *Guia prático passo a passo com exemplos e referências rápidas de sintaxe.* 🔗 [Acessar W3Schools Python](https://www.w3schools.com/python/)

---

## ⚙️ Prompts Utilizados e Resultados da IA

### 💬 Prompt 1: Explicação Conceitual
> **User:** *Explique variáveis em Python de forma simples.*

**Resposta da IA:**
> Em Python, você cria uma variável de forma direta, bastando atribuir um valor a ela. Por exemplo, a maneira correta de declarar uma variável chamada `x` que guarda o número `5` é simplesmente escrever: `x = 5`.
>
> Você não precisa utilizar prefixos ou palavras especiais como `var` ou símbolos como `$`. O estudo das variáveis é um dos primeiros passos na programação, sendo o recurso utilizado para tratar dados e realizar contas. Ao aprofundar-se no estudo de variáveis em Python, os principais tópicos abordados incluem:
> * **Nomes de variáveis:** as regras para nomeá-las corretamente.
> * **Atribuição múltipla:** como designar vários valores de uma só vez.
> * **Saída (output):** como exibir os dados que estão armazenados nelas.
> * **Variáveis globais:** como funcionam os limites (escopo) de onde a variável pode ser acessada no seu código.
>
> 💡 *Informação externa às fontes para complementar:* Você pode imaginar uma variável como uma "caixa" etiquetada na memória do computador. Você escreve um nome na etiqueta (por exemplo, `idade`) e guarda um dado dentro da caixa (por exemplo, o número `25`). Assim, sempre que o seu programa precisar desse dado, ele procura pela caixa com a etiqueta `idade`.

---

### 💬 Prompt 2: Resumo Estruturado
> **User:** *Crie um resumo sobre estruturas condicionais em Python.*

**Resposta da IA:**
> As estruturas condicionais em Python são baseadas primariamente no uso de `if...else`. O índice do tutorial do W3Schools divide o aprendizado dessas estruturas nos seguintes componentes principais:
> * **If (Se), Elif (Senão se) e Else (Senão):** Os comandos básicos para a tomada de decisão no código.
> * **Shorthand If:** Uma técnica para escrever a estrutura condicional de forma mais curta, geralmente em uma única linha.
> * **Nested If (If aninhado):** A prática de colocar uma condição dentro de outra.
> * **Logical Operators (Operadores Lógicos):** Utilizados junto com as condições para combinar múltiplos testes (como verificar se duas coisas são verdadeiras ao mesmo tempo).
> * **Pass Statement:** Um comando que diz ao Python para não fazer nada, usado para evitar erros caso uma condição exija um bloco de código que você ainda não escreveu.
> * **Match:** Uma estrutura condicional adicional citada no tutorial, que serve para verificar (ou "casar") padrões de dados.
>
> Além disso, a ementa do "Curso em Vídeo" demonstra que as estruturas condicionais (`if...else`) são usadas para criar lógicas que resolvem problemas práticos, listando exercícios que utilizam condições para: verificar se um número é par ou ímpar, desenvolver um pequeno jogo de adivinhação, criar a lógica de um radar eletrônico e calcular se um ano é bissexto.
>
> 💡 *Informação externa às fontes para complementar:* Você pode imaginar as estruturas condicionais como "encruzilhadas" no seu código, onde o programa faz uma pergunta para saber qual caminho seguir:
> * **if (Se):** O programa testa uma condição. (Ex: A velocidade do carro é maior que 80 km/h?). Se for Verdadeira, ele executa uma ação (Ex: Aplicar multa).
> * **elif (Senão se):** Se a primeira for falsa, ele pode fazer uma nova pergunta. (Ex: A velocidade é exatamente 80 km/h?).
> * **else (Senão):** Se absolutamente todas as condições anteriores forem Falsas, executa a alternativa final. (Ex: Siga a viagem normalmente).

---

### 💬 Prompt 3: Didática para Iniciantes
> **User:** *Explique loops em Python como se eu fosse iniciante.*

**Resposta da IA:**
> O material destaca que os loops são ferramentas essenciais para navegar por coleções de dados, listando a sua aplicação em listas, tuplas, conjuntos (sets) e dicionários.
>
> 💡 *Informação externa às fontes para complementar:* Um loop (ou laço de repetição) é uma forma de fazer o computador repetir uma mesma tarefa várias vezes sem que você precise reescrever o código. Os dois tipos mapeados pelo índice do W3Schools funcionam assim:
> * **For Loop (Laço "Para"):** É ideal para quando você já sabe quantas vezes precisa repetir uma ação ou quer olhar item por item en um grupo de coisas.  
>   *Exemplo da vida real:* "Para cada peça de roupa no cesto, coloque na máquina de lavar." O loop acaba quando o cesto esvaziar.
> * **While Loop (Laço "Enquanto"):** É ideal para quando você não sabe exatamente quantas vezes a repetição vai acontecer, mas sabe que ela deve continuar rodando enquanto uma regra for verdadeira.  
>   *Exemplo da vida real:* "Enquanto o copo não estiver cheio, continue colocando água." Você apenas repete a ação até o copo encher.

---

### 💬 Prompt 4: Criação de Práticas Relacionadas
> **User:** *Crie 3 exercícios simples sobre estruturas condicionais em Python para iniciantes.*

**Resposta da IA:**
> 🧩 **Exercício 1: Par ou Ímpar?**
> * **Objetivo:** Criar um programa que leia um número inteiro digitado pelo usuário e mostre na tela se ele é PAR ou ÍMPAR.
> * **Como resolver:** Você precisará usar matemática básica junto com condições. No Python, é possível descobrir o resto de uma divisão utilizando o operador `%`. Se `numero % 2 == 0`, a condição será verdadeira para números pares. Caso contrário, o número será ímpar.
>
> 🚓 **Exercício 2: Radar Eletrônico**
> * **Objetivo:** Criar um programa que pergunte a velocidade atual de um carro. Se ele ultrapassar 80 km/h, o programa deverá mostrar uma mensagem informando que o motorista foi multado. Caso contrário, deverá exibir: "Boa viagem!".
> * **Como resolver:** Criar uma variável que receba a velocidade do carro e utilizar uma estrutura condicional para verificar se ela ultrapassa o limite permitido com `if velocidade > 80:`.
>
> 🎮 **Exercício 3: Jogo da Adivinhação**
> * **Objetivo:** Fazer o computador “pensar” em um número entre 1 e 5 e pedir para o usuário tentar descobrir qual foi o número escolhido. O programa deverá informar se o jogador venceu ou perdeu.
> * **Como resolver:** Criar uma variável armazenando o número secreto e outra para o palpite do usuário. Depois, utilizar a condição `if palpite == numero_secreto:` para comparar os valores.

---

## 🚨 Dificuldades Encontradas (Troubleshooting)
Durante a construção do caderno e interação com a IA, documentei os seguintes pontos de atenção:

1. **Restrição de Conteúdo das Fontes:** Como os materiais fornecidos eram principalmente ementas, índices de tutoriais e listas de tópicos, o NotebookLM frequentemente apontava que o "detalhamento teórico profundo" não constava diretamente nos textos.
   * *Como contornei:* Aproveitei o recurso de "Informação externa às fontes" gerado de forma segura pela IA para preencher as lacunas conceituais e usei analogias do cotidiano para fixar os conceitos de repetição e escopo.
2. **Necessidade de Contextualização em Códigos:** No início, pedir apenas para "explicar um código" sem passar o bloco de texto gerava respostas genéricas sobre a sintaxe do Python.
   * *Como contornei:* Ajustei o prompt para incluir o código exato colado entre aspas e instruí a IA a mapear especificamente o que as variáveis daquele exemplo faziam na memória.

---

## 📖 Miniguia de Estudo & Entrega Final

### 1. Resumos Estruturados do Assunto
* **Variáveis:** Espaços na memória nomeados de forma direta (ex: `idade = 20`) para armazenar tipos de dados, sem termos adicionais na sintaxe.
* **Estruturas Condicionais:** Blocos de controle (`if`, `elif`, `else`) que criam caminhos lógicos com base em testes booleanos (Verdadeiro/Falso).
* **Loops:** Mecanismos de repetição automatizada. O `for` serve para iterar sobre limites conhecidos ou sequências, enquanto o `while` depende de uma validação lógica contínua para parar.

### 2. Glossário Prático
* **Atribuição (`=`):** Operação de associar um valor a um identificador (variável).
* **Escopo:** Determina a visibilidade e o tempo de vida de uma variável (Global ou Local).
* **If Aninhado:** Uma estrutura de decisão construída dentro do bloco de resposta de outra condição.
* **Shorthand If:** Escrita simplificada de estruturas condicionais em apenas uma única linha para economizar espaço de código.

### 3. Prompts Reutilizáveis para Estudos Futuros
Abaixo, listo prompts otimizados para reutilização no NotebookLM quando novos materiais forem anexados ao caderno:
* *“Com base estritamente nas documentações fornecidas, formule um quiz com 3 questões de múltipla escolha sobre manipulação de variáveis para que eu possa praticar.”*
* *“Atue como um instrutor de programação sênior. Crie uma tabela comparando os cenários ideais de uso de um laço FOR e de um laço WHILE.”*
* *“Analise o exercício prático X citado no material e proponha uma variação dele que exija o uso de um if aninhado.”*

---
🧑‍💻 Desenvolvido por Gabriella Costa para o Desafio de Projeto da DIO.
