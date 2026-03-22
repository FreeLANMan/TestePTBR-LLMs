# TestePTBR-LLMs
Método simples para testar o domínio da língua portuguesa do Brasil em qualquer LLM.

Atenção:
Esse teste não visa ter máxima precisão (Um LLM que tira nota 8 não é muito diferente de um LLM que tira nota 9), mas permite saber rapidamente o nível aproximado de domínio em português do Brasil de qualquer LLM.

Como usar:
No chat do LLM que você quer testar coloque o prompt:
Escreva uma carta de recomendação formal de um professor titular de Economia para um ex-aluno, Lucas Silva, que foi seu monitor por dois anos e agora pleiteia uma vaga de doutorado na USP. O texto deve ser uma narrativa coesa (sem tópicos ou listas), escrita em português padrão brasileiro erudito, demonstrando sofisticação sintática e vocabulário acadêmico preciso.

No chat do LLM que vai avaliar (use um LLM de ponta ou um com nota alta neste teste) o LLM que está sendo testado, coloque este prompt:
Dê uma nota de 0 a 10 ao domínio da norma-padrão do português brasileiro na resposta abaixo, penalizando severamente erros de regência, concordância e falta de naturalidade acadêmica.
P: Escreva uma carta de recomendação formal de um professor titular de Economia para um ex-aluno, Lucas Silva, que foi seu monitor por dois anos e agora pleiteia uma vaga de doutorado na USP. O texto deve ser uma narrativa coesa (sem tópicos ou listas), escrita em português padrão brasileiro erudito, demonstrando sofisticação sintática e vocabulário acadêmico preciso.
R: 
[adicione aqui a resposta do LLM que está sendo testado.]

Veja arquivo Resultados para consultar as notas de LLMs já avaliados.

Veja pasta Testes para consultar o resultado dos testes de alguns LLMs.
