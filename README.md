### Material de Estudo para Prova

### Arquitetura de Computadores: Máquina de Níveis (Formulário 5)

#### Conceitos Básicos
1. **Modelo de Máquina de Níveis**:
   - **Hierarquia**: O modelo de seis níveis organiza a arquitetura de computadores em diferentes camadas de abstração, indo da lógica digital até o nível do sistema operacional e aplicações.

2. **Nível de Lógica Digital**:
   - **Componente básico**: Porta lógica, que realiza operações fundamentais como AND, OR, NOT.

3. **Portas Lógicas**:
   - **Porta AND**: A saída será 1 se todas as entradas forem 1.
   - **Porta OR**: A saída será 1 se pelo menos uma das entradas for 1.
   - **Porta NOT**: Inverte o valor da entrada.

4. **Unidade Lógica e Aritmética (ULA)**:
   - **Nível de microarquitetura**: Onde estão circuitos como somadores binários.
   
5. **Níveis do Modelo de 6 Níveis**:
   - **Nível 0 a Nível 5**: Cada nível representa uma camada de abstração diferente, com funções específicas para cada um.

6. **Set de Instruções do Processador**:
   - **Formas de representação**: Binária e simbólica (hexadecimal, por exemplo).
   - **Opcode**: Código de operação utilizado para identificar instruções.

7. **Programas em Linguagem de Máquina**:
   - **Modelo de Von Neumann**: Instruções e dados armazenados em memória.
   - **Conversão de Código**: Utilização de técnicas como compilação, interpretação e montagem para converter linguagens de alto nível em linguagem de máquina.

---

### Sistemas Digitais: Lógica e Portas Lógicas (Formulário 6)

#### Proposições Lógicas
1. **Definição**:
   - **Proposição Lógica**: Uma declaração que pode ser verdadeira ou falsa.

2. **Valores Lógicos**:
   - **Sistemas Digitais**: Utilizam valores binários (0 e 1) para representar estados lógicos.

3. **Operações Lógicas**:
   - **Disjunção (OR)**: Verdadeira se pelo menos uma proposição for verdadeira.
   - **Conjunção (AND)**: Verdadeira se ambas as proposições forem verdadeiras.
   - **Negação (NOT)**: Inverte o valor lógico da proposição.
   - **Tabela Verdade**: Ferramenta para analisar todas as combinações possíveis de valores lógicos.

4. **Portas Lógicas**:
   - **AND, OR, NOT, NAND, NOR**: Implementam operações lógicas básicas em sistemas digitais.

5. **Combinações de Variáveis Lógicas**:
   - **Função Lógica X(p, q, r, s)**: Número de combinações possíveis de variáveis lógicas independentes (2^n).

6. **Expressões Lógicas**:
   - **Simplificação e Avaliação**: Determinação do valor lógico de expressões complexas a partir de proposições simples.

---

### Sistemas de Memória (Formulário 7)

#### Hierarquia de Memória
1. **Níveis de Memória**:
   - **Registradores**: Alta velocidade, baixa capacidade, latência mínima.
   - **Cache**: Memória intermediária entre CPU e RAM, reduz latência.
   - **RAM**: Memória principal, acessada diretamente pela CPU.
   - **Disco Rígido**: Alta capacidade, baixa velocidade.

2. **Características das Memórias**:
   - **Memória Volátil**: Perde dados quando o sistema é desligado (ex: RAM).
   - **Memória Não-Volátil**: Retém dados sem energia (ex: SSD, HDD).
   - **Memória de Acesso Aleatório (RAM)**: Permite acesso rápido a qualquer posição de memória.
   - **Memória Estática (SRAM)** vs. **Memória Dinâmica (DRAM)**: SRAM é mais rápida e cara, DRAM é mais lenta e barata.

3. **Tempo de Acesso e Ciclo de Memória**:
   - **Tempo de Acesso**: Tempo necessário para acessar uma célula de memória.
   - **Ciclo de Memória**: Tempo total para completar uma operação de leitura/escrita.

4. **Vazão (Throughput)**:
   - **Capacidade de Transmissão**: Quantidade de dados transmitidos por unidade de tempo, dependendo da largura do barramento e tempo de ciclo.

5. **Memória Cache**:
   - **Princípio de Localidade**: Utilização de cache melhora desempenho ao explorar a localidade temporal e espacial dos dados.
   - **Taxa de Acerto (Hit Rate)**: Percentual de acessos à memória que são satisfeitos pela cache.

6. **Desempenho do Sistema**:
   - **Tempo Médio de Execução**: Calculado considerando tempos de acesso à memória e instruções do programa.
   - **Impacto da Cache**: Significativa redução do tempo de execução ao aumentar a taxa de acerto da cache.

---

### Resumo e Preparação para a Prova

#### Revisão Geral
1. **Modelo de Máquina de Níveis**:
   - Estude as funções e características de cada nível.
   - Compreenda como os níveis se inter-relacionam e contribuem para o desempenho do sistema.

2. **Lógica Digital**:
   - Pratique a simplificação de expressões lógicas.
   - Entenda o funcionamento de portas lógicas e suas combinações.

3. **Memória Computacional**:
   - Conheça a hierarquia de memória e as características de cada tipo.
   - Pratique cálculos relacionados a tempo de acesso, ciclo de memória e vazão.

#### Exercícios Práticos
1. **Desenhar Circuitos Lógicos**:
   - Projete e analise circuitos utilizando portas AND, OR, NOT, NAND, NOR.
   
2. **Tabela Verdade**:
   - Construa tabelas verdade para expressões lógicas complexas.

3. **Problemas de Desempenho de Memória**:
   - Resolva problemas que envolvem cálculos de tempo de acesso e ciclo de memória.
   - Calcule a eficiência da memória cache em diferentes cenários.

Com esta revisão e prática, você estará bem preparado para a prova. Boa sorte!
