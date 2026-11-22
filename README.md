# Lógica e Técnicas de Programação — Fundamentos e Algoritmos (VisuAlg Web)

## 1. Apresentação e Objetivos do Repositório

Este repositório tem como objetivo central sistematizar, documentar e exemplificar os fundamentos da **Lógica e das Técnicas de Programação**, utilizando a abordagem de pseudocódigo por meio do ambiente **VisuAlg Web**. A proposta consiste em construir um material didático, prático e progressivo, voltado ao desenvolvimento do raciocínio algorítmico antes da transição para linguagens compiladas e fortemente tipadas, como Java e C++.

De modo específico, este projeto busca:

- **Consolidar a modelagem computacional de problemas**, partindo da identificação clara de entrada, processamento e saída de dados (ALÉSSIO, 2017; FORBELLONE; EBERSPACHER, 2005).
- **Estruturar o aprendizado em capítulos modulares e sequenciais**, permitindo que cada conceito (desde variáveis, constantes e operadores até estruturas de dados homogêneas, heterogêneas e sub-rotinas), seja estudado com exemplos comentados e exercícios práticos.
- **Estabelecer rigor conceitual fundamentado na literatura acadêmica**, articulando a escrita de algoritmos em português estruturado às bases teóricas da Ciência da Computação (FORBELLONE; EBERSPACHER, 2005; OLIVEIRA; PEREIRA, 2023).
- **Preparar a base lógica para análise de eficiência e estruturas avançadas**, introduzindo noções de modularização, busca, ordenação e complexidade de algoritmos que servirão de alicerce para implementações futuras em Java e C++ (SILVEIRA, 2015).

---

## 2. Fundamentação Teórica e Argumentação Metodológica

A construção de algoritmos constitui a etapa essencial que antecede a codificação em qualquer linguagem de programação. Segundo Forbellone e Eberspacher (2005), programar exige, primeiramente, compreender o problema e organizar logicamente os passos necessários para transformar dados de entrada em resultados válidos, abstraindo particularidades sintáticas de ferramentas específicas.

Nesse sentido, o uso do pseudocódigo (Portugol) no **VisuAlg Web** justifica-se pedagogicamente por reduzir a barreira inicial da sintaxe em língua inglesa e permitir que o estudante concentre seus esforços na lógica de controle de fluxo, na tipagem de dados e na rastreabilidade da execução (ALÉSSIO, 2017). Conforme destacam Oliveira e Pereira (2023), o domínio consciente sobre a organização dos dados na memória (por meio de variáveis simples, vetores, matrizes e registros) é determinante para o desenvolvimento de soluções escaláveis e bem estruturadas.

Além disso, a progressão até a modularização (procedimentos e funções) e às técnicas clássicas de busca e ordenação prepara o raciocínio para avaliar o desempenho das soluções propostas. Como aponta Silveira (2015), compreender o funcionamento interno dos algoritmos de ordenação e busca permite escolher estratégias computacionais mais eficientes em termos de tempo de execução e consumo de memória, competência indispensável na transição posterior para Java ou C++.

---

## 3. Estrutura de Pastas e Organização em Capítulos

O repositório está organizado em diretórios modulares numerados por capítulos, acompanhados de documentação de apoio:

```text
logica-tecnicas-programacao-visualg/
├── README.md
├── docs/
│   ├── guia-visualg-web.md
│   └── convencoes-algoritmos.md
├── cap-01-fundamentos-e-es/
│   ├── README.md
│   ├── exemplos/
│   └── exercicios/
├── cap-02-estruturas-condicionais/
│   ├── README.md
│   ├── exemplos/
│   └── exercicios/
├── cap-03-estruturas-repeticao/
│   ├── README.md
│   ├── exemplos/
│   └── exercicios/
├── cap-04-vetores-e-matrizes/
│   ├── README.md
│   ├── exemplos/
│   └── exercicios/
├── cap-05-registros-e-estruturas-compostas/
│   ├── README.md
│   ├── exemplos/
│   └── exercicios/
└── cap-06-modularizacao-e-topicos-avancados/
    ├── README.md
    ├── exemplos/
    └── exercicios/
```

### Escopo de Cada Capítulo

- **Capítulo 01 — Fundamentos e Entrada/Saída (`cap-01-fundamentos-e-es`):** decomposição em entrada, processamento e saída; tipos primitivos (`inteiro`, `real`, `caractere`, `lógico`); variáveis, constantes e operadores.
- **Capítulo 02 — Estruturas Condicionais (`cap-02-estruturas-condicionais`):** desvios simples, compostos, encadeados (`se/entao/senao`) e seleção múltipla (`escolha/caso`).
- **Capítulo 03 — Estruturas de Repetição (`cap-03-estruturas-repeticao`):** laços com teste no início (`enquanto`), teste no final (`repita/ate`) e variável de controle (`para`), além de contadores e acumuladores.
- **Capítulo 04 — Vetores e Matrizes (`cap-04-vetores-e-matrizes`):** estruturas de dados homogêneas unidimensionais e bidimensionais, indexação e percorrimento.
- **Capítulo 05 — Registros e Estruturas Compostas (`cap-05-registros-e-estruturas-compostas`):** estruturas heterogêneas (`registro`), definição de tipos personalizados e vetores de registros.
- **Capítulo 06 — Modularização e Tópicos Avançados (`cap-06-modularizacao-e-topicos-avancados`):** procedimentos, funções, passagem de parâmetros, escopo, recursividade e introdução aos algoritmos de busca, ordenação e análise de complexidade.

---

## 4. Como Utilizar Este Repositório

1. Acesse o ambiente **VisuAlg Web** em seu navegador.
2. Navegue até o diretório do capítulo desejado e consulte o `README.md` local para revisar a síntese teórica.
3. Abra os arquivos da subpasta `exemplos/` para testar e acompanhar o teste de mesa das estruturas apresentadas.
4. Resolva os desafios propostos na subpasta `exercicios/` antes de comparar sua solução com o gabarito comentado.

---

## 5. Referências Bibliográficas (ABNT NBR 6023)

ALÉSSIO, Simone Cristina. **Lógica e técnicas de programação**. Indaial: UNIASSELVI, 2017.

CORMEN, Thomas H. *et al*. **Algoritmos**: teoria e prática. 3. ed. Rio de Janeiro: Elsevier, 2012. 

FORBELLONE, André Luiz Villar; EBERSPACHER, Henri Frederico. **Lógica de programação**: a construção de algoritmos e estruturas de dados. 3. ed. São Paulo: Prentice Hall, 2005.

OLIVEIRA, Pietro Martins de; PEREIRA, Rogério de Leon. **Linguagens de programação e estruturas de dados**. Organização de Tatiana Alencar. Florianópolis: Arqué, 2023.

SILVEIRA, Guilherme. **Algoritmos em Java**: busca, ordenação e análise. São Paulo: Casa do Código, 2015.

## 6. Sobre o Autor

**Daniel Luiz Coelho dos Santos**

Profissional de tecnologia e educador, com formação superior em **Sistemas de Informação** e **Análise e Desenvolvimento de Sistemas** pelo Centro Universitário de Várzea Grande (UNIVAG) e especializações em **Engenharia Web e Governo Eletrônico** (UFMT), **Planejamento Pedagógico**, **Tutoria em EaD e Educação Especial** e **Metodologia de Ensino** pelo Centro Universitário Leonardo da Vinci (UNIASSELVI).

Atua como **Professor Mediador** nos cursos da área de tecnologia da **UNIASSELVI**, oferecendo suporte técnico e orientação acadêmica, além de possuir experiência sólida no desenvolvimento e manutenção de sistemas corporativos em **Java** e aplicações web. Este repositório reúne a sistematização didática de suas práticas de ensino e fundamentação algorítmica.

- **Currículo Lattes:** [lattes.cnpq.br](https://lattes.cnpq.br/9562338405383465)
- **LinkedIn:** [linkedin.com](https://www.linkedin.com/in/danielluizcoelho)
- **GitHub:** [github.com](https://github.com/DanielCSDD/logica-tecnicas-programacao-visualg.git)

## 7. Direitos Autorais e Licença de Uso

Este repositório é protegido por direitos autorais de **Daniel Luiz Coelho dos Santos**. O conteúdo é disponibilizado para **estudo e aprendizado individual**, sendo vedado o uso público, republicação, redistribuição ou finalidade comercial sem consentimento prévio do autor.

Consulte as condições completas no arquivo [LICENSE](LICENSE).
