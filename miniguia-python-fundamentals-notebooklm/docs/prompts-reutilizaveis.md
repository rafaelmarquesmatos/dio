# Prompts Reutilizáveis — Python Fundamentals na Era da IA (NotebookLM - 20 fontes)

> 10 prompts validados no caderno `Python Programming Fundamentals: Documentation and Video Guide` (print em `../assets/notebooklm-python-fundamentals-overview.png`). Sempre use `Com base EXCLUSIVAMENTE nas fontes do caderno (cite F#)`.

## PR1 — Resumidor por Capítulo
```
Atue como tutor Python iniciante. Com base EXCLUSIVAMENTE em F1 cap.[N] (O tutorial do Python), crie resumo sobre [TÓPICO] com:
- 5 bullets, 1 tabela conceito|exemplo, 1 erro comum, 1 exercício com gabarito. Cite F#.
```

## PR2 — Comparador de Estruturas
```
Com base em F1 cap.5, compare list vs tuple vs dict vs set em tabela:
Estrutura | Mutável | Ordenada | Acesso | Quando usar | Exemplo. Cite F#.
```

## PR3 — Explicador Linha a Linha
```
Explique este código linha a linha para iniciante, com base em F1-F2:
```python
[COLE CÓDIGO]
```
Para cada linha: o que faz + alternativa pythônica se houver. Cite F#.
```

## PR4 — Gerador de Exercícios Progressivos
```
Crie 3 exercícios (fácil → médio → desafio) sobre [TÓPICO] com base em F1/F3.
Para cada: enunciado | dica | gabarito comentado. Cite F#.
```

## PR5 — Revisor de Código (PEP 8 + Docs)
```
Você é revisor sênior Python. Revise este código com base em F1-F2 (e PEP 8 se nas fontes):
```python
[COLE CÓDIGO]
```
Liste: Linha | Regra | Antes | Depois. Cite F#.
```

## PR6 — Vídeo → Notas
```
Com base na transcrição F3 (Python Full Course for free [TIMESTAMP]), gere:
1) Resumo 5 bullets 2) 3 insights que F1 não mostra tão claramente 3) 1 exercício. Cite F3 vs F1.
```

## PR7 — Docs Navigator
```
Quero entender [FUNÇÃO ex: open(), dict.get(), json.load] na doc.
Com base em F1-F2, traga: 1) assinatura+parâmetros 2) 2 exemplos F1 3) 2 armadilhas 4) See also. Cite F#.
```

## PR8 — Plano 7 Dias Fundamentos
```
Com base em F1-F5, crie plano 7 dias Python Fundamentals:
Dia | Objetivo | Fonte (F#+cap/timestamp) | Exercício | Critério de pronto
Inclua 1 dia POO e 1 dia Arquivos/GUI. Cite fontes.
```

## PR9 — Comparador Agentic 2026 (do print: LangGraph vs CrewAI vs AutoGen)
```
Com base EXCLUSIVAMENTE em F14-F18 (Agentic AI Frameworks 2026), compare LangGraph vs CrewAI vs AutoGen em tabela:
Arquitetura | Prós | Contras | Caso ideal | Maturidade produção | Curva para Jr
Cite F# em cada célula. Finalize com recomendação para projeto [PREVISÃO DO TEMPO] com time Jr e justifique "o que NÃO usar”.
```

## PR10 — Trilha Carreira & Portfólio (do print: CV/portfólio/LinkedIn)
```
Com base em F6-F11 (DataCamp, Intuit, Roadmap) + síntese do print (CV/portfólio/LinkedIn para vagas), crie trilha de 3 projetos portfólio para vaga Python Jr na era da IA:
Projeto | Fundamentos usados (POO/arquivos/GUI/API) | Stack | Entregável GitHub | Como descrever no LinkedIn (problema→stack→resultado)
Cite F#. Inclua "Previsão do Tempo" (TXT/JSON/CSV + API) como P1, como sugerido no print.
```

### Bônus — Perguntas literais do print (para testar cicatrizes)
```
# POO
Com base em F1 cap.9, como funciona a Programação Orientada a Objetos no Python? Dê exemplo Conta → ContaCorrente com herança e super(). Cite.

# Arquivos/Dados
Quais bibliotecas de dados são essenciais para trabalhar com IA? Com base em F9-F11, liste em tabela lib|uso|quando usar. Cite.

# Projeto
Quais são os passos para criar o projeto de previsão do tempo? Use F1 (arquivos) + F14-F16 (decisão framework) em roadmap 5 passos. Cite.
```

> **Rotina espaçada:** 1 prompt/dia → Gere `Mapa mental`/`Teste`/`Infográfico` no Estúdio → exporte `Audio Overview` (8 min) para revisão. Salve respostas em `docs/respostas-notebooklm/` se quiser versionar.
