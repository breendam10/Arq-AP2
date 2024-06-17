# AP2 - Arquitetura dos computadores

### Questão 1 (Máquina de Níveis)
**Enunciado:**
O modelo de máquina de níveis utilizado como referência para análise e projeto de sistemas computacionais discute contemplar seis camadas.

**Afirmações:**
I. A camada mais primitiva é definida como o nível de microarquitetura. O componente básico desse nível é a porta lógica.
II. Quanto mais alto o nível ou camada menor será a abstração da sua respectiva linguagem.
III. O Sistema Operacional é a camada de maior abstração, pois ela contempla uma linguagem cujas instruções estão diretamente acessíveis ao usuário.

**Alternativas:**
(a) As alternativas I e II estão corretas.  
(b) As alternativas I e III estão corretas.  
(c) As alternativas II e III estão corretas.  
(d) Todas as alternativas estão corretas.  
(e) Todas as alternativas estão incorretas.

**Resposta correta:**
(d) Todas as alternativas estão corretas.

**Explicação:**
A camada mais primitiva realmente é a microarquitetura, que lida com portas lógicas. Quanto mais alto o nível, maior a abstração. O Sistema Operacional é a camada de maior abstração.

---

### Questão 2 (Máquina de Níveis)
**Enunciado:**
Uma das seis camadas que caracteriza o modelo de máquina de níveis utilizado para abstrair a visão do sistema computacional é o nível de microarquitetura.

**Afirmações:**
I. Compreende os circuitos especializados, como circuitos lógicos e aritméticos, que são internos ao processador.
II. É uma camada imediatamente acima do nível mais primitivo.
III. Cada um dos circuitos especializados é responsável pela execução de uma tarefa específica, uma vez selecionado pela Unidade de Controle após a decodificação da instrução binária.

**Alternativas:**
(a) As alternativas I e II estão corretas.  
(b) As alternativas I e III estão corretas.  
(c) As alternativas II e III estão corretas.  
(d) Todas as alternativas estão corretas.  
(e) Todas as alternativas estão incorretas.

**Resposta correta:**
(c) As alternativas II e III estão corretas.

**Explicação:**
As afirmações II e III estão corretas. A afirmação I pode ser ambígua, pois fala sobre circuitos lógicos e aritméticos de forma geral, o que poderia abranger também outros níveis além da microarquitetura.

---

### Questão 3 (Máquina de Níveis)
**Enunciado:**
Explique sucintamente o que caracteriza o processo do programa montador ou assembler.

**Resposta correta:**
"A função do programa montador é converter a linguagem de montagem em linguagem de máquina que pode ser executada pelo processador."

**Explicação:**
O assembler traduz o código assembly, que é uma linguagem de baixo nível, diretamente para o código de máquina, que é executado pelo processador.

---

### Questão 4 (Máquina de Níveis)
**Enunciado:**
Uma das seis camadas estudadas é aquela que compreende as instruções do processador na sua forma binária. Selecionar qual delas recebe essa designação.

**Alternativas:**
(a) Nível de lógica digital  
(b) Nível de microarquitetura  
(c) Nível ISA  
(d) Nível do Sistema Operacional  
(e) Nível de linguagem de montagem  
(f) Nível de aplicação  

**Resposta correta:**
(c) Nível ISA

**Explicação:**
O nível ISA (Instruction Set Architecture) compreende as instruções do processador na sua forma binária.

---

### Questão 1 (Lógica Digital)
**Enunciado:**
Seja o circuito apresentado na figura abaixo. Apresentar a expressão lógica de S, indicando parcialmente a expressão na saída de cada porta do circuito.

**Explicação:**
As expressões parciais e a expressão final de S estão corretas. Deve-se identificar corretamente as operações lógicas em cada porta do circuito.

---

### Questão 2 (Lógica Digital)
**Enunciado:**
Apresentar a tabela verdade relativa à expressão lógica do circuito dada por S(A, B, C) = A.B + A.C + A.(B + C).

**Tabela verdade correta:**

| A | B | C | A.B | A.C | B+C | A.(B+C) | S    |
|---|---|---|-----|-----|-----|---------|------|
| 0 | 0 | 0 |  0  |  0  |  0  |    0    |  0   |
| 0 | 0 | 1 |  0  |  0  |  1  |    0    |  0   |
| 0 | 1 | 0 |  0  |  0  |  1  |    0    |  0   |
| 0 | 1 | 1 |  0  |  0  |  1  |    0    |  0   |
| 1 | 0 | 0 |  1  |  0  |  0  |    0    |  1   |
| 1 | 0 | 1 |  1  |  1  |  1  |    1    |  1   |
| 1 | 1 | 0 |  1  |  1  |  1  |    1    |  1   |
| 1 | 1 | 1 |  1  |  1  |  1  |    1    |  1   |

---

### Questão 3 (Linguagem de Montagem)
**Enunciado:**
Assinalar verdadeiro (V) ou falso (F) para cada uma das afirmações apresentadas a seguir:

(a) A instrução LDI Rd, k carrega o valor k no registrador Rd. O operando k é o próprio dado. Nesse caso a instrução é chamada de modo direto.  
**Resposta correta:** Falso

**Explicação:**
A instrução LDI carrega um valor imediato no registrador, mas não é chamada de modo direto.

(b) A instrução LDS Rd, k carrega o dado contido no endereço k no registrador. O operando indica o endereço. Nesse caso a instrução é chamada de modo imediato.  
**Resposta correta:** Falso

**Explicação:**
A instrução LDS carrega um valor do endereço de memória no registrador, mas não é chamada de modo imediato.

(c) Nos códigos em linguagem de montagem (assembly) todas as instruções ocupam espaços adjacentes na memória, o que inspira o uso do conceito de programa armazenado.  
**Resposta correta:** Verdadeiro

**Explicação:**
As instruções assembly ocupam espaços adjacentes na memória, facilitando o conceito de programa armazenado.

(d) Comparando as instruções LDI e LDS é intuitivo pensar que a instrução LDI é mais rápida porque realiza menos acessos à memória para ser executada.  
**Resposta correta:** Verdadeiro

**Explicação:**
A instrução LDI é mais rápida porque carrega um valor imediato, enquanto a instrução LDS envolve um acesso à memória.

---

### Questão 4 (Sistema de Memória)
**Enunciado:**
Em relação aos níveis do sistema hierárquico de memória, pode-se afirmar que:

**Alternativas:**
(a) As alternativas I e II estão corretas.  
(b) As alternativas I e III estão corretas.  
(c) As alternativas II e III estão corretas.  
(d) Todas as alternativas estão corretas.  
(e) Todas as alternativas estão incorretas.

**Resposta correta:**
(a) As alternativas I e II estão corretas.

**Explicação:**
Os níveis de memória mais baixos são representados por componentes com maior capacidade de armazenamento e menor velocidade, e os registradores são elementos de menor latência.

---

### Resumo de Estudo baseado no Teste

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
