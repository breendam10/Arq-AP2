# AP2 - Arquitetura dos computadores

Vamos analisar o conteúdo das questões e verificar as respostas, corrigindo-as se necessário, e depois faremos um resumo de estudo.

### Imagem 1
#### Questão 3
**Enunciado:**
Explique sucintamente o que caracteriza o processo do programa montador ou assembler.

**Resposta fornecida:**
"A função do programa montador é converter a linguagem de montagem em linguagem de máquina que pode ser executada pelo processador."

**Correção:**
A explicação está correta. O assembler traduz o código assembly, que é uma linguagem de baixo nível, diretamente para o código de máquina, que é executado pelo processador.

#### Questão 4
**Enunciado:**
Uma das seis camadas estudadas é aquela que compreende as instruções do processador na sua forma binária. Selecionar qual delas recebe essa designação.

**Alternativas:**
(a) Nível de lógica digital
(b) Nível de microarquitetura
(c) Nível ISA
(d) Nível do Sistema Operacional
(e) Nível de linguagem de montagem
(f) Nível de aplicação

**Resposta marcada:**
(c) Nível ISA

**Comentário:**
A resposta está correta. O nível ISA (Instruction Set Architecture) compreende as instruções do processador na sua forma binária.

#### Questão 1 (Lógica Digital)
**Enunciado:**
Seja o circuito apresentado na figura abaixo. Apresentar a expressão lógica de S, indicando parcialmente a expressão na saída de cada porta do circuito.

**Análise da expressão lógica:**
As expressões parciais estão corretas. A expressão final de S também está correta.

### Imagem 2
#### Questão 1
**Enunciado:**
Apresentar a tabela verdade relativa à expressão lógica do circuito dada por S(A, B, C) = A.B + A.C + A.(B + C).

**Tabela verdade fornecida:**
A tabela fornecida está incorreta.

**Correção:**
A tabela verdade correta deve ser:

| A | B | C | A.B | A.C | B+C | A.(B+C) | S    |
|---|---|---|-----|-----|-----|---------|------|
| 0 | 0 | 0 |  0  |  0  |  0  |    0    |  0   |
| 0 | 0 | 1 |  0  |  0  |  1  |    0    |  0   |
| 0 | 1 | 0 |  0  |  0  |  1  |    0    |  0   |
| 0 | 1 | 1 |  0  |  0  |  1  |    0    |  0   |
| 1 | 0 | 0 |  0  |  1  |  0  |    0    |  1   |
| 1 | 0 | 1 |  1  |  1  |  1  |    1    |  1   |
| 1 | 1 | 0 |  1  |  1  |  1  |    1    |  1   |
| 1 | 1 | 1 |  1  |  1  |  1  |    1    |  1   |

### Imagem 3
#### Questão 3 (Linguagem de Montagem)
**Enunciado:**
Assinalar verdadeiro (V) ou falso (F) para cada uma das afirmações apresentadas a seguir:

(a) A instrução LDI Rd, k carrega o valor k no registrador Rd. O operando k é o próprio dado. Nesse caso a instrução é chamada de modo direto.
**Resposta: Falso (correta)**

(b) A instrução LDS Rd, k carrega o dado contido no endereço k no registrador. O operando indica o endereço. Nesse caso a instrução é chamada de modo imediato.
**Resposta: Falso (correta)**

(c) Nos códigos em linguagem de montagem (assembly) todas as instruções ocupam espaços adjacentes na memória, o que inspira o uso do conceito de programa armazenado.
**Resposta: Verdadeiro (correta)**

(d) Comparando as instruções LDI e LDS é intuitivo pensar que a instrução LDI é mais rápida porque realiza menos acessos à memória para ser executada.
**Resposta: Verdadeiro (correta)**

### Imagem 4
#### Questão 4 (Sistema de Memória)
**Enunciado:**
Em relação aos níveis do sistema hierárquico de memória, pode-se afirmar que:

**Alternativas:**
(a) As alternativas I e II estão corretas.
(b) As alternativas I e III estão corretas.
(c) As alternativas II e III estão corretas.
(d) Todas as alternativas estão corretas.
(e) Todas as alternativas estão incorretas.

**Resposta marcada:**
(a) As alternativas I e II estão corretas.

**Comentário:**
A resposta está correta. Os níveis de memória mais baixos são representados por componentes com maior capacidade de armazenamento e menor velocidade, e os registradores são elementos de menor latência.

### Resumo de Estudo

#### 1. Montador (Assembler)
- O montador traduz código assembly (baixo nível) para código de máquina (executável pelo processador).

#### 2. Níveis de Máquina
- **Nível ISA:** Compreende as instruções do processador na forma binária.

#### 3. Lógica Digital
- Para resolver circuitos lógicos, identifique as expressões de saída de cada porta e a expressão lógica final.
- **Tabela Verdade:** Utilize para verificar todas as possíveis combinações de entradas e saídas.

#### 4. Linguagem de Montagem
- **LDI (Load Immediate):** Carrega um valor imediato no registrador.
- **LDS (Load Direct):** Carrega um valor do endereço de memória no registrador.
- As instruções assembly ocupam espaços adjacentes na memória.

#### 5. Sistema de Memória
- **Hierarquia de Memória:** Níveis mais baixos têm maior capacidade e menor velocidade.
- **Registradores:** Elementos com menor latência, ocupam o topo da pirâmide de memória.
- **Memória de Trabalho:** Posicionada intermediariamente na hierarquia.

Este resumo deve fornecer uma base sólida para estudar os conceitos abordados nas questões. Se precisar de mais detalhes sobre algum tópico específico, sinta-se à vontade para perguntar!
