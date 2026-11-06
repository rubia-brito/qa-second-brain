# 🧠 QA Second Brain — Especialista em Testes de Software

## 📌 Sobre o projeto

Este projeto consiste na criação de um segundo cérebro especializado em QA (Quality Assurance) e Testes de Software, utilizando o Google NotebookLM como ferramenta de apoio aos estudos.

O objetivo é reunir fontes confiáveis, organizar conhecimentos técnicos e desenvolver um ambiente de aprendizagem que auxilie na compreensão dos fundamentos de qualidade, técnicas de teste, testes de API e automação com C# e .NET.

O projeto foi desenvolvido como parte de um desafio prático da DIO, com foco em pesquisa, curadoria de conteúdo, validação de informações e aplicação de inteligência artificial nos estudos.

## 🎯 Objetivo

Criar um assistente de estudos especializado em QA e Testes de Software, capaz de:

- Explicar conceitos técnicos de maneira didática.
- Auxiliar na elaboração e análise de casos de teste.
- Apresentar exemplos práticos.
- Apoiar os estudos de testes manuais e automatizados.
- Aprofundar conhecimentos em testes de API com Postman.
- Apoiar a aprendizagem de testes unitários e de integração com C#/.NET.
- Utilizar fontes confiáveis e apresentar referências nas respostas.
- Identificar limitações das fontes e evitar informações sem fundamentação.

## 📚 Conteúdos abordados

O segundo cérebro foi organizado em cinco áreas principais:

1. **Fundamentos de QA:** qualidade de software, conceitos de erro, defeito e falha.
2. **Testes de Software:** testes manuais, automatizados, unitários e de integração.
3. **Técnicas de Teste:** caixa-preta, particionamento de equivalência e análise de valor-limite.
4. **Testes de API:** Postman, requisições HTTP, variáveis e validação de respostas.
5. **Automação de Testes:** C#, .NET, xUnit, MSTest e TDD.

## 🔎 Fontes de pesquisa

Foram selecionadas fontes de referência técnica e educacional, priorizando documentação oficial e materiais reconhecidos na área de testes de software.

| Fonte | Conteúdo | Justificativa |
|---|---|---|
| ISTQB CTFL 4.0 — versão em português | Fundamentos e princípios de teste | Referência internacional para conhecimentos de testes de software. |
| Microsoft Learn — Testes em .NET | Testes automatizados com .NET | Documentação oficial da Microsoft. |
| Postman Learning Center | Testes e scripts de API | Documentação oficial da ferramenta Postman. |
| Mestre QA — Revisando CTFL: Fundamentos de Teste | Fundamentos de testes | Material educacional complementar. |
| Many - QA — Testes de API com Postman | Testes de API | Tutorial prático complementar. |

### Pesquisa complementar

Durante a validação, foi identificada uma lacuna nas fontes originais sobre a precedência das variáveis do Postman.

Para complementar o conhecimento, foi realizada uma pesquisa adicional utilizando a documentação oficial do Postman sobre escopos de variáveis.

A hierarquia identificada, da maior para a menor precedência, foi:

1. Local (Local)
2. Dados (Data)
3. Ambiente (Environment)
4. Coleção (Collection)
5. Global (Global)

Essa pesquisa complementar foi incorporada ao notebook, mantendo a distinção entre as fontes originais e o conteúdo pesquisado posteriormente.

## ⚙️ Configuração do NotebookLM

O notebook recebeu instruções para atuar como um especialista em QA e Testes de Software.

As orientações definidas incluem:

- Priorizar as fontes adicionadas ao notebook.
- Apresentar citações para fundamentar as respostas.
- Explicar conceitos com exemplos práticos.
- Não inventar informações.
- Informar quando determinado assunto não estiver contemplado nas fontes.
- Incentivar o desenvolvimento do raciocínio crítico.

## 🧪 Perguntas e testes de validação

Foram realizadas cinco atividades de validação para verificar a qualidade das respostas, a utilização das fontes e a capacidade de identificar limitações do conhecimento disponível.

### Teste 1 — Erro, defeito e falha

**Objetivo:** verificar a compreensão dos conceitos fundamentais de teste.

Foi solicitado que o NotebookLM explicasse a diferença entre erro, defeito e falha, utilizando um exemplo de uma loja virtual.

**Resultado:** resposta validada. O exemplo demonstrou a relação entre erro humano, defeito no código e falha observada durante a execução.

### Teste 2 — Sete princípios de teste

**Objetivo:** verificar o conhecimento dos princípios fundamentais de teste do ISTQB.

**Resultado:** os sete princípios foram identificados e explicados corretamente, com exemplos práticos.

### Teste 3 — Precedência de variáveis no Postman

**Objetivo:** verificar a capacidade de reconhecer limitações das fontes.

**Resultado:** inicialmente, o NotebookLM informou que as fontes disponíveis não apresentavam a informação específica. Após pesquisa complementar na documentação oficial do Postman, apresentou a hierarquia correta de precedência das variáveis.

Esse teste demonstrou a importância de não aceitar respostas sem fundamentação e de complementar as fontes quando necessário.

### Teste 4 — Testes unitários em C#/.NET

**Objetivo:** avaliar explicações sobre testes unitários, testes de integração, padrão Arrange-Act-Assert, xUnit, MSTest e execução com `dotnet test`.

**Resultado:** resposta validada, com exemplos práticos em C# e observações técnicas complementares.

### Teste 5 — Comparação entre xUnit e MSTest

**Objetivo:** compreender as diferenças entre os frameworks de testes automatizados.

Foram abordados:

- `[TestClass]`, `[TestMethod]`, `[Fact]` e `[Theory]`.
- `[DataRow]` e `[InlineData]`.
- Inicialização e finalização dos testes.
- `IClassFixture<T>` e mecanismos de ciclo de vida.
- `Assert.AreEqual` e `Assert.Equal`.
- Exemplos de testes para uma classe Calculadora.

**Resultado:** conteúdo complementado e validado tecnicamente, com apoio externo devido a um problema na cópia da resposta original do NotebookLM.

## 📦 Materiais produzidos

### 🧠 Mapa mental — QA e Testes de Software

O mapa mental apresenta visualmente os principais conceitos estudados e a organização dos conhecimentos abordados no projeto.

![Mapa mental de QA e Testes de Software](materiais/mapa-mental-qa-testes.png)

### 📖 Guia de estudos de QA

Material de apoio desenvolvido para organizar os conteúdos e orientar o aprofundamento dos estudos.

📥 **[Visualizar ou baixar o Guia de Estudos de QA (PDF)](materiais/guia-de-estudos-qa.pdf)**

## 📁 Estrutura do repositório

```text
qa-second-brain/
│
├── README.md
│
├── fontes/
│   └── referencias.md
│
├── materiais/
│   ├── mapa-mental-qa-testes.png
│   └── guia-de-estudos-qa.pdf
│
└── evidencias/
    ├── 1.png
    ├── 2.png
    ├── 3.png
    ├── 4.png
    ├── 5.png
    ├── 6.png
    ├── 7.png
    ├── 8.png
    ├── 9.png
    ├── 10.png
    ├── 11.png
    ├── 12.png
    ├── 13.png
    └── notebook-chat-xunit-mstest.png
```

A pasta `fontes` contém as referências utilizadas na pesquisa.

A pasta `materiais` reúne o mapa mental e o guia de estudos produzidos durante o desafio.

A pasta `evidencias` reúne as capturas de tela que documentam as atividades e validações realizadas durante o desenvolvimento do projeto.

## 🔗 Acesso ao NotebookLM

**Notebook:** QA — Segundo Cérebro: Especialista em Testes de Software.

📚 **[Acessar o segundo cérebro no NotebookLM](https://notebook.google.com/notebook/16bb2800-64fb-4710-8e58-d312c685f4c4)**

## 🛠️ Tecnologias e ferramentas

- Google NotebookLM
- GitHub
- ISTQB
- Postman
- C#
- .NET
- xUnit
- MSTest
- TDD

## 💡 Aprendizados

O desenvolvimento deste projeto proporcionou a oportunidade de:

- Praticar pesquisa e curadoria de fontes técnicas.
- Utilizar inteligência artificial como ferramenta de aprendizagem.
- Avaliar respostas geradas por IA com senso crítico.
- Identificar lacunas de informação e buscar documentação oficial.
- Aprofundar conhecimentos em QA e automação de testes.
- Organizar conteúdos técnicos em um ambiente de consulta.
- Aplicar conhecimentos de testes de software em exemplos práticos.

## 👩‍💻 Autora

**Rúbia Brito**

Estudante de Análise e Desenvolvimento de Sistemas, com interesse em QA, Testes de Software, automação com C#/.NET e qualidade de software.

- GitHub: [rubia-brito](https://github.com/rubia-brito)
- LinkedIn: [rubia-brito-dev](https://linkedin.com/in/rubia-brito-dev)

---

**Projeto desenvolvido para fins educacionais como parte de um desafio prático da DIO.**
