# MATA61 - Compiladores
## Material da disciplina

+ [Programa da disciplina](../master/MATA61-Compiladores-20122.pdf)
+ 20201 - Turma 01. [Google classroom](https://classroom.google.com/c/Mzk4MjUwNTM3MDZa) - Código da Turma **01**: yvwdlbx
+ 20201 - Turma 02. [Google classroom](https://classroom.google.com/c/Mzk4MjUwNTM3MjJa) - Código da Turma **02**: vqron7y

---
## Objetivos

- Parte teórica: Entender os conceitos fundamentais envolvidos na implementação de linguagens de programação;
- Parte prática: Implementar um compilador aplicando as técnicas de análise e síntese/geração de código.

## Plano de Aulas

### Visão Geral

- Visao geral da disciplina e conceitos básicos
- Introdução a Traducao de Programas
- Papel do Compilador/Interpretador, Conceitos Basicos
- Estrutura e fases de um compilador

### Análise Léxica

- Conceitos de analise lexica
- Exemplos envolvendo analise lexica
- Linguagens regulares
- Exemplos de especificacao lexica
- Especificacao de lexemas/tokens em linguagem de programacao
- Automato Finito
- Mapeando expressoes regulares em automatos finitos
- Implementacao de automatos finitos
- Exemplos de codigos de implementacao

### Análise Sintática

- Conceitos gerais
- Gramaticas livre de contexto
- Derivacoes
- Ambiguidade
- Representacao abstrata/compacta da arvore sintatica
- Analise Sintatica: Top-Down
- Algoritmo recursivo descendente
- Limitacao do parser recursivo descendente
- Problema da recursao a esquerda
- Parser preditivo LL(1)
- Conjunto First
- Conjunto Follow
- Construcao tabela do parser LL(1)
- Analise Sintatica: Bottom-Up
- Estrategia de Parser Shift-reduce
- Conceito de Handle
- Reconhecimento de um Handle
- Reconhecimento de Prefixos Viaveis
- Parser SLR ("Simple LR")
- Exemplo de funcionamento do parser SLR
- Melhorias para o parser SLR
- LR(1), LALR(1) parsers
- Geradores de analisadores sintaticos

### Análise Semântica

- Escopo e Tabela de simbolos
- Checagem de tipos
- Ambientes de tipos
- Implementacao de checagem de tipos


### Ambientes de Execução

- Ambiente de execução
- Ativacoes
- Registros de Ativacao
- Variaveis Globais e Heap

### Geração de Código

- Geração de código
- Maquinas de Pilha
- Linguagem MIPS assembly
- Implementação usando Máquina de Pilha
- Modelos de Geração de Código

### Otimização de Código: Local
- Codigo Intermediario
- Tecnicas de otimizacao local
- Otimizacao "peephole"

### Otimização de Código: Global 
- Analise Data flow
- Propagação global de constantes
- Analise Liveness

### Alocação de Registradores
 - Hierarquia de memoria
 - Definição do Problema
 - Método de Coloração em grafos
 - Técnica de Spilling

### Gerenciamento Automático de Memória
- Definição do Problema
- Técnica Mark and Sweep
- Técnica Stop and Copy
- Técnica Reference Counting

## Projeto Prático
Projetar e implementar um compilador (incluindo Analisador Léxico, Analisador Sintático,  Analisador Semântico e Gerador de Código) para uma linguagem simples procedimental. 

## Avaliação
- 30% Primeira prova (individual)
- 30% Segunda prova (individual)
- 40% Trabalhos práticos (individual ou em dupla)

## Provas/trabalhos

- Trabalho 1: Analisador Léxico
- Trabalho 2: Analisador Sintático
- Prova 1: Análise Léxica, Análise Sintática (Top-down e Bottom-up), Análise Semântica (Escopo e Tipos)
- Trabalho 3: Analisador Semântico
- Prova 2: Ambiente de execução, Geração de Código, Alocação de registradores, Gerenciamento Automático de Memória
- Trabalho 4 (final): Gerador de Código

Como regra geral, não serão avaliados trabalhos entregues fora do prazo. Qualquer dificuldade ou dúvida, entre em contato com a professora.

## Livro para leitura/consulta (opcional)

Livro do "Dragão": Aho, Lam, Sethi, and Ullman. Compiladores: princípios, técnicas e ferramentas. 2a edição, Addison-Wesley, 2008.

- Analise Léxica e Automatos Finitos.
Seções de Capítulos: 3.1, 3.3, 3.4, 3.6, 3.7, 3.8
- Analise Sintática.
Seções de Capítulos: 4.1-4.6, 4.8.1, 4.8.2
- Analise Semântica e Tipos.
Seções de Capítulos: 5.1-5.3 6.3, 6.5
- Ambiente de Execução e Geração de Código.
Seções de Capítulos: 6.2, 7.1-7.4, 8.1-8.3, 8.6
- Otimização de codigo.
Seções de Capítulos: 8.5, 8.7, 9.1-9.4
- Alocação de registradores e Gerenciamento automático de memória.
Seções de Capítulos: 8.8, e 7.5-7.7

## Links
### Cursos online 

+ [Compilers - Universidade de Stanford](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=Compilers) 

### Sobre markdown

+ [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
+ [The Ultimate Guide to Markdown](https://blog.ghost.org/markdown/)
+ [Markdown and including multiple files](https://stackoverflow.com/questions/4779582/markdown-and-including-multiple-files)

### Sobre github 

+ [Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)
+ [Try Git](https://try.github.io/levels/1/challenges/1)
