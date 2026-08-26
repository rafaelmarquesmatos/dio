# Prompts Reutilizáveis — Python Fundamentals (NotebookLM)

> Coleção pronta para copiar/colar no NotebookLM. Sempre use com as 5 fontes do caderno e exija `Cite F#`.

## PR1 — Resumidor por Capítulo
```
Atue como tutor de Python para iniciantes.
Com base EXCLUSIVAMENTE em F1 cap. [N], crie resumo sobre [TÓPICO] com:
- 5 bullets de conceitos-chave
- 1 tabela (conceito | exemplo)
- 1 erro comum + como evitar
- 1 mini-exercício com gabarito
Cite F#. Se não constar, diga "não consta".
```

## PR2 — Comparador de Estruturas
```
Com base em F1 cap.5 e F3, compare list vs tuple vs dict vs set em tabela:
Estrutura | Mutável | Ordenada | Acesso | Quando usar | Exemplo
Cite F#. Formato markdown.
```

## PR3 — Explicador de Código Linha a Linha
```
Explique este código linha a linha para iniciante, com base em F1 e F2:
```python
[COLE CÓDIGO]
```
Para cada linha: o que faz, por que funciona, alternativa pythônica se houver. Cite F#.
```

## PR4 — Gerador de Exercícios Few-shot
```
Crie 3 exercícios progressivos sobre [TÓPICO] (fácil → médio → desafio) com base em F1 e F3.
Para cada: enunciado | dica | gabarito comentado. Cite F#.
Inspire-se nos exemplos de F3 cap. [N].
```

## PR5 — Revisor PEP 8
```
Você é revisor sênior Python. Revise este código com base em F4 (PEP 8):
```python
[COLE CÓDIGO]
```
Liste 5 problemas no formato: Linha | Regra PEP 8 | Antes | Depois. Cite F4.
```

## PR6 — Transformador de Vídeo em Notas
```
Com base na transcrição F5 (vídeo [TÍTULO] [TIMESTAMP]), gere:
1. Resumo em 5 bullets
2. 3 insights que a doc F1 NÃO mostra tão claramente
3. 1 exercício prático para fixar
Cite F5 e compare com F1 quando útil.
```

## PR7 — Docs Navigator
```
Quero entender [FUNÇÃO/MÓDULO ex: open(), dict.get()] na doc oficial.
Com base em F1 e F2, me guie:
1. O que a doc diz (assinatura + parâmetros)
2. 2 exemplos práticos adaptados de F1
3. 2 armadilhas comuns
4. Links "See also" relevantes
Cite F#.
```

## PR8 — Plano de Estudos 7 Dias
```
Com base em F1-F5, crie plano de 7 dias para dominar Python Fundamentals:
Dia | Objetivo | Fonte (F# + capítulo/timestamp) | Exercício | Critério de pronto
Inclua 1 dia só para PEP 8 e 1 para revisão com Audio Overview. Cite fontes.
```
