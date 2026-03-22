# TestePTBR-LLMs
🇧🇷 Um método minimalista para testar o domínio da norma-padrão do português brasileiro em qualquer LLM.
 

> [!TIP]
> **Filosofia do Projeto:** Priorizamos a **simplicidade** sobre o rigor estatístico. Este teste foca na capacidade do modelo em lidar com o "teto" da língua (linguagem acadêmica erudita), partindo do princípio que a proficiência técnica neste nível costuma refletir a qualidade geral do modelo.

-----

## 🚀 Como Funciona

O processo de avaliação é dividido em duas etapas: a **geração** do texto pelo modelo testado e a **avaliação** por um modelo de referência.

### Passo 1: Gerar a Resposta

No chat do LLM que você deseja testar, envie o seguinte prompt:

> Escreva uma carta de recomendação formal de um professor titular de Economia para um ex-aluno, Lucas Silva, que foi seu monitor por dois anos e agora pleiteia uma vaga de doutorado na USP. O texto deve ser uma narrativa coesa (sem tópicos ou listas), escrita em português padrão brasileiro erudito, demonstrando sofisticação sintática e vocabulário acadêmico preciso.

### Passo 2: Avaliar a Resposta

No chat de um LLM de ponta (ex: Gemini 3 Flash, Claude Sonnet 4.6 Extendido) ou um modelo que já tenha obtido nota alta neste teste, utilize o prompt abaixo:

> Dê uma nota de 0 a 10 ao domínio da norma-padrão do português brasileiro na resposta abaixo, penalizando severamente erros de regência, concordância e falta de naturalidade acadêmica.
> P:  Escreva uma carta de recomendação formal de um professor titular de Economia para um ex-aluno, Lucas Silva, que foi seu monitor por dois anos e agora pleiteia uma vaga de doutorado na USP. O texto deve ser uma narrativa coesa (sem tópicos ou listas), escrita em português padrão brasileiro erudito, demonstrando sofisticação sintática e vocabulário acadêmico preciso.
> R: [Cole aqui a resposta gerada pelo LLM que está sendo testado]

-----

## 📂 Estrutura do Repositório

  * **[Resultados.txt]:** Consulte as notas e o ranking de LLMs que já foram submetidos a este teste.
  * **[Testes/]:** Pasta contendo os logs e as respostas completas de alguns modelos avaliados para fins de transparência.
