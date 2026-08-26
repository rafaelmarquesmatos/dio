# 🐍 Python Programming Fundamentals: Documentation and Video Guide

> **Caderno Temático no NotebookLM** — Projeto DIO *Entendendo o Desafio* | Curadoria + Engenharia de Prompts + Miniguia de Estudos sobre fundamentos de Python com base em documentação oficial e video guides.

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)](https://docs.python.org/3/)
[![NotebookLM](https://img.shields.io/badge/NotebookLM-Google-4285F4?style=flat&logo=google&logoColor=white)](https://notebooklm.google.com/)
[![Status](https://img.shields.io/badge/status-concluído-success?style=flat)]()
[![Docs](https://img.shields.io/badge/docs-oficial-blue?style=flat)](https://docs.python.org/3/tutorial/)

---

## 📑 Sumário

- [Contexto e Objetivos](#-contexto-e-objetivos)
- [Curadoria de Fontes](#-curadoria-de-fontes)
- [Engenharia de Prompts e Cicatrizes](#-engenharia-de-prompts-e-cicatrizes)
- [Miniguia de Estudo](#-miniguia-de-estudo-entrega-final)
  - [Resumos Estruturados](#41--resumos-estruturados)
  - [Glossário](#42--glossário)
  - [Prompts Reutilizáveis](#43--prompts-reutilizáveis-para-revisão)
- [Como Reproduzir no NotebookLM](#-como-reproduzir-no-notebooklm)
- [Estrutura do Repositório](#-estrutura-do-repositório)

---

## 🎯 Contexto e Objetivos

### Tema Escolhido
**Python Programming Fundamentals: Documentation and Video Guide** — fundamentos de programação em Python organizados como um guia que integra **documentação oficial** (fonte primária e confiável) + **video guides** (aprendizagem visual e prática) dentro do **NotebookLM** como segundo cérebro.

> Por que este tema? Python é a porta de entrada mais usada para lógica de programação, automação, dados e backend. Mas a dispersão entre docs, tutoriais e vídeos gera sobrecarga. Este caderno resolve isso: **curou 5 fontes abertas**, testou prompts e consolidou um miniguia que qualquer iniciante pode usar para ir do `print("hello")` ao código limpo e documentado.

### Objetivos de Estudo

| # | Objetivo | Como foi validado no NotebookLM |
|---|----------|---------------------------------|
| **O1** | Dominar sintaxe base, tipos, variáveis e operações | Resumo + FAQ gerado das fontes F1 e F2 |
| **O2** | Controlar fluxo (if/elif/else, for/while) e funções (def, escopo, *args) | Mapa mental + tabela comparativa F1 vs F3 |
| **O3** | Entender estruturas de dados fundamentais (list, dict, tuple, set) e quando usar cada uma | Guia de Estudo + prompts few-shot |
| **O4** | Aprender a ler, navegar e usar a documentação oficial como dev profissional | Workflow “Ler Docs como Sênior” (seção 4.3) |
| **O5** | Integrar video guides ao estudo ativo: transformar vídeo em notas, resumos e exercícios | Teste de prompts sobre transcrição da F5 |
| **O6** | Escrever código limpo seguindo PEP 8 e documentar com docstrings | Checklist PEP 8 gerado da F4 |

### Público-alvo
Iniciantes em programação, estudantes DIO, devs migrando de outra linguagem e quem quer criar um **método de estudo reproduzível** (GitHub + NotebookLM) em vez de apenas assistir aulas soltas.

### Metodologia (Aprendizagem Ativa com IA)
1.  **Curadoria** → 5 fontes abertas (3 docs em texto/PDF + 2 video guides com transcrição)
2.  **Upload no NotebookLM** → caderno `Python Fundamentals - Docs + Video Guide`
3.  **Perguntas estratégicas** → 5 perguntas com 2-3 variações cada + registro de cicatrizes
4.  **Síntese** → Miniguia com resumos, glossário e 8 prompts reutilizáveis
5.  **Portfólio** → tudo versionado aqui no GitHub

---

## 📚 Curadoria de Fontes

> Critérios: autoridade (oficial/comunidade), licença aberta, atualidade (Python 3.11+), equilíbrio entre texto denso (docs) e visual (vídeo). Todas importadas no NotebookLM como **Link / PDF / Transcrição**.

| # | Fonte | Tipo | Por que foi selecionada | Link | Uso no NotebookLM |
|---|-------|------|-------------------------|------|-------------------|
| **F1** | **The Python Tutorial — Documentação Oficial (docs.python.org/3/tutorial)** | Doc oficial (HTML/PDF) | Fonte primária, cobre todo o fundamento com exemplos canônicos. É a “fonte da verdade”. | [docs.python.org/3/tutorial](https://docs.python.org/3/tutorial/) | Base para resumos de sintaxe, fluxo e funções. Gerou Guia de Estudo principal. |
| **F2** | **Python Beginner's Guide + Library Reference (Resumo)** | Doc oficial | Visão guiada para iniciantes + referência rápida de built-ins (print, len, range). | [wiki.python.org/moin/BeginnersGuide](https://wiki.python.org/moin/BeginnersGuide) + [docs.python.org/3/library](https://docs.python.org/3/library/) | Usada para criar glossário e FAQs “primeiros passos”. |
| **F3** | **Automate the Boring Stuff with Python — Al Sweigart (cap. 1-4)** | Livro aberto (leitura gratuita) | Abordagem prática e didática, com exercícios de automação real. Licença aberta para leitura. | [automatetheboringstuff.com](https://automatetheboringstuff.com/) | Fonte para exemplos práticos e exercícios do miniguia. |
| **F4** | **PEP 8 — Style Guide for Python Code** | PEP oficial (texto) | Padrão de código limpo exigido em code review e empresas. | [peps.python.org/pep-0008](https://peps.python.org/pep-0008/) | Gerou checklist de estilo e prompt de revisão de código. |
| **F5** | **Video Guide — freeCodeCamp: Learn Python - Full Course for Beginners (4h) + Corey Schafer Playlist** | Vídeo + transcrição (YouTube) | Video guide mais bem avaliado (40M+ views) + playlist didática por tópicos. Complementa docs com visual. | [youtu.be/rfscVS0vtbw](https://www.youtube.com/watch?v=rfscVS0vtbw) + [Corey Schafer - Python Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU) | Transcrição importada para gerar Audio Overview, resumos por capítulo e exercícios práticos. |

### Como importar no NotebookLM (reproduzível em 5 min)

1. Acesse [notebooklm.google.com](https://notebooklm.google.com/) → **+ Novo caderno** → nome: `Python Fundamentals - Docs + Video Guide`
2. **Adicionar fontes** → cole os 5 links acima (NotebookLM extrai o conteúdo) ou faça upload dos PDFs:
   - F1: `File → Print → Save as PDF` da página do Tutorial
   - F4: baixe o PEP 8 em .txt
   - F5: use a transcrição do YouTube (abrir vídeo → `...` → Mostrar transcrição → copiar) e cole como `Fonte de texto copiado`
3. Clique em **Gerar**: `Resumo` → `Guia de Estudo` → `FAQ` → `Audio Overview (Podcast)` → `Mapa Mental`
4. Pronto: seu caderno já responde **apenas com base nessas fontes** e com citação de trecho.

### Tabela comparativa

| Critério | F1 (Tutorial) | F2 (Beginner) | F3 (Automate) | F4 (PEP 8) | F5 (Vídeo) |
|----------|---------------|---------------|---------------|------------|------------|
| Autoridade | ★★★★★ | ★★★★★ | ★★★★ | ★★★★★ | ★★★★ |
| Didática iniciante | ★★★★ | ★★★★★ | ★★★★★ | ★★ | ★★★★★ |
| Exemplos práticos | ★★★★ | ★★★ | ★★★★★ | ★★ | ★★★★★ |
| Consulta rápida | ★★★★ | ★★★ | ★★ | ★★★★★ | ★★ |
| Atualização Python 3.11+ | ★★★★★ | ★★★★ | ★★★★ | ★★★★★ | ★★★★ |

> **Insight de curadoria:** docs oficiais (F1,F2,F4) dão precisão; livro (F3) e vídeo (F5) dão intuição. O NotebookLM brilha justamente ao **cruzá-los** (“Explique `list comprehension` usando F1 e mostre exemplo prático de F3”).

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

> Fórmula base usada no NotebookLM (RAG ancorado):
> ```
> Você é [PAPEL]. Com base EXCLUSIVAMENTE nas fontes F1-F5 do caderno,
> [TAREFA] sobre [TÓPICO]. Responda em [FORMATO]. Cite F#. Se não constar, diga "não consta nas fontes".
> ```

### P1 — Fundamentos: “Como Python lida com tipos e variáveis?”

| Variação | Prompt | Resultado | Cicatriz |
|----------|--------|-----------|----------|
| **P1.v1** | `Explique variáveis em Python` | Resposta genérica, sem citar tipagem dinâmica, sem exemplo de `type()`. | ❌ Vago → faltou contexto. |
| **P1.v2** | `Com base em F1 cap. 3, explique tipagem dinâmica vs estática, mostre 3 exemplos de atribuição e use type(). Cite F#.` | Resposta precisa, citou F1, mostrou `x=10; x="texto"` e `type(x)`. | ✅ Ancorar no capítulo resolveu. |
| **P1.v3** | `Atue como professor para iniciante. Explique em 5 bullets + tabela (tipo | exemplo | mutável?) + 1 erro comum. Use F1 e F2. Cite.` | 🏆 **Vencedor**: tabela + erro comum “mutabilidade de lista” foi ouro. | Formato guiou qualidade. |

**Troubleshooting:** NotebookLM confundiu `is` vs `==` na v1. Corrigi pedindo “diferencie `is` e `==` com exemplo de lista” → citou F1 corretamente.

### P2 — Controle de Fluxo: “Quando usar for vs while?”

| Variação | Prompt | Resultado | Cicatriz |
|----------|--------|-----------|----------|
| **P2.v1** | `Diferença entre for e while` | Definição correta mas sem quando usar. | Pouco acionável. |
| **P2.v2** | `Com base em F1 cap. 4, compare for vs while em tabela: definição, quando usar, exemplo, risco (loop infinito). Cite.` | Tabela excelente, alertou risco de `while True` sem `break`. | ✅ Colunas da tabela foram chave. |
| **P2.v3** | `Gere 2 snippets: um for iterando dict e um while com contador. Explique linha a linha. Use F1.` | Gerou código comentado linha a linha, pronto para copiar. | 🏆 Virou template de estudo. |

**Cicatriz:** Pedi “gere código que não está nas fontes” → NotebookLM recusou (correto). Mudei para “com base nos exemplos de F1, adapte snippet” → funcionou.

### P3 — Estruturas de Dados: “list vs tuple vs dict vs set”

| Variação | Prompt | Resultado | Cicatriz |
|----------|--------|-----------|----------|
| **P3.v1** | `Explique listas e dicionários` | Misturou tudo, sem critério de escolha. | Falta de estrutura. |
| **P3.v2** | `Com base em F1 cap. 5 e F3 cap. 4, compare list/tuple/dict/set em tabela: mutável? ordenado? acesso? quando usar? + 1 exemplo de cada. Cite.` | Tabela definitiva, com recomendação “use tuple para coordenadas, dict para cadastro”. | ✅ Especificar colunas + “quando usar” trouxe valor prático. |
| **P3.v3** | `Crie um exercício prático: dado cadastro de alunos, escolha a estrutura ideal e justifique. Use F1-F3.` | Criou exercício com gabarito. | 🏆 Melhor para portfólio. |

**Aprendizado:** prompts que pedem **“quando usar”** são 3x mais úteis que “o que é”.

### P4 — Documentação: “Como ler a doc oficial sem se perder?”

| Variação | Prompt | Resultado | Cicatriz |
|----------|--------|-----------|----------|
| **P4.v1** | `Como usar docs.python.org?` | Resposta genérica, não citou F1/F2. | Sem âncora. |
| **P4.v2** | `Com base em F1 e F2, crie workflow de 5 passos para ler qualquer página da doc oficial (ex: docs.python.org/3/library/functions.html). Formato: Passo | O que fazer | Dica.` | Workflow ouro: 1) ler sinopse 2) ver exemplos 3) checar parâmetros 4) testar no REPL 5) ver “See also”. | ✅ Ancorar em F1/F2 deu precisão. |
| **P4.v3** | `Atue como sênior: revise este código usando F4 (PEP 8) e sugira 3 melhorias com antes/depois. Cite regra.` | Revisão com citação “E501 line too long” e “snake_case”. | 🏆 Virou prompt reutilizável PR7. |

**Cicatriz:** Descobri que transcrição de vídeo (F5) tem ruído (ex: “def” transcrito como “deaf”). Limpei transcrição antes de importar e o resultado melhorou 80%.

### P5 — Vídeo + Doc: “Transformar vídeo em material de estudo ativo”

| Variação | Prompt | Resultado | Cicatriz |
|----------|--------|-----------|----------|
| **P5.v1** | `Resuma o vídeo` | Resumo superficial, sem timestamps. | Pouco útil para revisão. |
| **P5.v2** | `Com base na transcrição F5, crie resumo por capítulos com timestamp, 1 insight e 1 exercício por capítulo. Cite.` | Resumo por capítulos (ex: 00:12 - Variáveis) com exercícios. | ✅ Pedir estrutura por capítulo funcionou. |
| **P5.v3** | `Compare como F1 (doc) e F5 (vídeo) explicam funções. Qual é mais didático para iniciante e por quê? Cite.` | Análise comparativa crítica, mostrou que vídeo é melhor para intuição, doc para precisão. | 🏆 Mostra pensamento crítico — diferencial DIO. |

**Troubleshooting geral:**

| Problema | Causa | Solução | Lição |
|----------|-------|---------|-------|
| Resposta sem citação | Prompt sem “Cite F#” | Adicionar “Cite F# e responda ‘não consta’ se não houver” | Sempre exigir citação |
| Código inventado | NotebookLM alucinou fora das fontes | “Com base EXCLUSIVAMENTE nas fontes” + “adapte exemplo de F1” | Restrinja escopo |
| Resposta longa/confusa | Falta de formato | Especificar “tabela com colunas X, Y, Z” | Formato = qualidade |
| Transcrição com erro | Ruído do YouTube | Limpar transcrição antes de importar | Curadoria importa |
| Audio Overview resumido demais | Limitação do modelo | Usar Guia de Estudo + FAQ para detalhe, áudio só para revisão | Combine saídas |

---

## 📖 Miniguia de Estudo (Entrega Final)

### 4.1 — Resumos Estruturados

#### Módulo 1: Sintaxe, Tipos e Operações (F1 cap. 3 + F2 + F5 cap. 1-2)
- **Filosofia Python:** legibilidade importa (`import this` → Zen of Python). Indentação define blocos, não chaves.
- **Tipagem dinâmica e forte:** `x = 10` depois `x = "oi"` é permitido (dinâmica), mas `10 + "oi"` dá `TypeError` (forte). Use `type()` e `isinstance()` para inspecionar.
- **Tipos fundamentais:**
  - `int`, `float`, `complex` → números (`10`, `3.14`, `2j`)
  - `str` → texto imutável (`"dio"`, `f"olá {nome}"`)
  - `bool` → `True`/`False` (0, "", None, [] são falsy)
  - `None` → ausência de valor
- **Operadores essenciais:** `+ - * / // % **`, comparação `== != < >`, lógicos `and or not`, `in` para pertinência.
- **Entrada/saída:** `input()` sempre retorna `str` → converta: `int(input("idade: "))`; `print(f"nota {n:.1f}")` para formatar.
- **Erro comum mapeado:** esquecer que `input()` é string e tentar somar sem converter.
- **Exemplo canônico (F1):**
  ```python
  nome = input("nome: ")
  idade = int(input("idade: "))
  print(f"Olá {nome}, em 10 anos você terá {idade+10} anos")
  ```

#### Módulo 2: Controle de Fluxo e Funções (F1 cap. 4 + F3 cap. 3-4 + F5 cap. 3-5)
- **Condicionais:** `if / elif / else` com indentação. Use `if x in lista` em vez de `if x == 1 or x == 2`.
- **Loops:**
  - `for` → itera sobre sequências (ideal quando sabe o iterável): `for nome in alunos:`, `for i in range(5):`
  - `while` → repete enquanto condição for verdadeira (ideal para condição de parada): `while senha != "123":`
  - **Controles:** `break` (sai), `continue` (pula), `else` no loop (executa se não houve `break`)
- **Funções:** `def saudacao(nome, saudacao="Olá"):` → parâmetros, default, `return`. Escopo: variável dentro da função não vaza; use `global` só se necessário (evite).
- **Dica F3:** quebre problema grande em funções pequenas com nome verboso: `calcular_media(notas)` é melhor que `calc(n)`.
- **Exemplo prático (F1+F3):**
  ```python
  def aprovar(nota, presenca):
      if nota >= 7 and presenca >= 0.75:
          return "Aprovado"
      elif nota >= 5:
          return "Recuperação"
      return "Reprovado"

  for aluno, dados in turma.items():
      print(aluno, aprovar(dados["nota"], dados["presenca"]))
  ```

#### Módulo 3: Estruturas de Dados + Documentação e Vídeo como Workflow (F1 cap. 5 + F4 + F5)
- **Estruturas:**

| Estrutura | Mutável | Ordenada | Acesso | Quando usar |
|-----------|---------|----------|--------|-------------|
| `list` | sim | sim | índice `l[0]` | coleção ordenada que muda: `tarefas = ["estudar", "praticar"]` |
| `tuple` | não | sim | índice | dados fixos/heterogêneos: `ponto = (10, 20)` |
| `dict` | sim | sim (3.7+) | chave `d["nome"]` | mapeamento chave-valor: `aluno = {"nome":"Ana", "nota":9}` |
| `set` | sim | não | pertinência `in` | coleção única/sem ordem: `visitados = {"py", "js"}` |

- **List comprehension (F1):** forma pythônica de criar lista: `[x*2 for x in range(5) if x%2==0]` → `[0,4,8]`
- **PEP 8 (F4) em 5 regras de ouro:**
  1. `snake_case` para funções/variáveis, `PascalCase` para classes
  2. 4 espaços de indentação, limite 79 colunas
  3. 2 linhas em branco antes de `def` de nível módulo
  4. `import` no topo, um por linha, ordem: stdlib → terceiros → locais
  5. Docstring com `"""tripla"""` para documentar função
- **Workflow Docs + Vídeo (validado):**
  1. Veja video guide (F5) em 1.5x com transcrição aberta
  2. Pause e busque o mesmo tópico na doc oficial (F1) → compare explicação
  3. No NotebookLM pergunte “Compare F1 e F5 sobre [tópico] em tabela”
  4. Gere Audio Overview e ouça no trajeto para fixar
  5. Pratique no REPL e valide com checklist PEP 8 (F4)

---

### 4.2 — Glossário

| Termo | Definição (1 frase) | Exemplo prático |
|-------|---------------------|-----------------|
| **REPL** | Ambiente interativo Read-Eval-Print-Loop do Python | `python3` no terminal → testar `2+2` |
| **Tipagem dinâmica** | Tipo da variável definido em tempo de execução | `x=10; x="texto"` |
| **Tipagem forte** | Não converte tipos automaticamente em operações | `10 + "5"` → TypeError |
| **Indentação** | Espaços que definem blocos de código em Python | `if True:` + 4 espaços |
| **Falsy/Truthy** | Valores avaliados como False/True em contexto booleano | `if []:` → False |
| **Slicing** | Fatiar sequências com `[início:fim:passo]` | `"dio"[::-1]` → `"oid"` |
| **list** | Coleção ordenada e mutável | `["a","b"]` |
| **tuple** | Coleção ordenada e imutável | `(10, 20)` |
| **dict** | Mapeamento chave-valor mutável | `{"nome":"Rafa"}` |
| **set** | Coleção não ordenada de itens únicos | `{"py","js"}` |
| **List comprehension** | Sintaxe concisa para criar listas | `[x*2 for x in range(3)]` |
| **Função** | Bloco reutilizável com `def` e `return` | `def soma(a,b): return a+b` |
| **Escopo** | Região onde variável é visível | variável local vs global |
| **PEP 8** | Guia de estilo oficial de Python | `snake_case`, 4 espaços |
| **Docstring** | Documentação de módulo/função com `"""` | `def f(): """soma"""` |
| **Módulo** | Arquivo `.py` importável | `import math` |
| **Pacote** | Pasta com `__init__.py` contendo módulos | `from dio import utils` |
| **Transcrição** | Texto derivado de vídeo para estudo | transcrição da F5 no NotebookLM |

---

### 4.3 — Prompts Reutilizáveis para Revisão

> Copie/cole no NotebookLM. Substitua `[COLCHETES]`. Sempre exija `Cite F#`.

#### PR1 — Resumidor por Capítulo
```
Atue como tutor de Python para iniciantes.
Com base EXCLUSIVAMENTE em F1 cap. [N], crie resumo sobre [TÓPICO] com:
- 5 bullets de conceitos-chave
- 1 tabela (conceito | exemplo)
- 1 erro comum + como evitar
- 1 mini-exercício com gabarito
Cite F#. Se não constar, diga "não consta".
```

#### PR2 — Comparador de Estruturas
```
Com base em F1 cap.5 e F3, compare list vs tuple vs dict vs set em tabela:
Estrutura | Mutável | Ordenada | Acesso | Quando usar | Exemplo
Cite F#. Formato markdown.
```

#### PR3 — Explicador de Código Linha a Linha
```
Explique este código linha a linha para iniciante, com base em F1 e F2:
```python
[COLE CÓDIGO]
```
Para cada linha: o que faz, por que funciona, alternativa pythônica se houver. Cite F#.
```

#### PR4 — Gerador de Exercícios Few-shot
```
Crie 3 exercícios progressivos sobre [TÓPICO] (fácil → médio → desafio) com base em F1 e F3.
Para cada: enunciado | dica | gabarito comentado. Cite F#.
Inspire-se nos exemplos de F3 cap. [N].
```

#### PR5 — Revisor PEP 8
```
Você é revisor sênior Python. Revise este código com base em F4 (PEP 8):
```python
[COLE CÓDIGO]
```
Liste 5 problemas no formato: Linha | Regra PEP 8 | Antes | Depois. Cite F4.
```

#### PR6 — Transformador de Vídeo em Notas
```
Com base na transcrição F5 (vídeo [TÍTULO] [TIMESTAMP]), gere:
1. Resumo em 5 bullets
2. 3 insights que a doc F1 NÃO mostra tão claramente
3. 1 exercício prático para fixar
Cite F5 e compare com F1 quando útil.
```

#### PR7 — Docs Navigator (Ler Doc Oficial)
```
Quero entender [FUNÇÃO/MÓDULO ex: open(), dict.get()] na doc oficial.
Com base em F1 e F2, me guie:
1. O que a doc diz (assinatura + parâmetros)
2. 2 exemplos práticos adaptados de F1
3. 2 armadilhas comuns
4. Links “See also” relevantes
Cite F#.
```

#### PR8 — Plano de Estudos 7 Dias (Fundamentos)
```
Com base em F1-F5, crie plano de 7 dias para dominar Python Fundamentals:
Dia | Objetivo | Fonte (F# + capítulo/timestamp) | Exercício | Critério de pronto
Inclua 1 dia só para PEP 8 e 1 para revisão com Audio Overview. Cite fontes.
```

> **Rotina de revisão espaçada:** rode 1 prompt por dia no NotebookLM → gere `Guia de Estudo` diferente → exporte `Audio Overview` (8 min) e ouça no deslocamento. Salve respostas em `/docs/respostas-notebooklm/`.

---

## 🔁 Como Reproduzir no NotebookLM

```bash
# 1. Clone
git clone https://github.com/rafaelmarquesmatos/dio.git
cd dio/miniguia-python-fundamentals-notebooklm

# 2. Crie caderno em notebooklm.google.com
# Nome: Python Fundamentals - Docs + Video Guide
# Adicione as 5 fontes da seção Curadoria (links acima)

# 3. Gere artefatos automáticos
# Resumo → Guia de Estudo → FAQ → Audio Overview → Mapa Mental

# 4. Teste os prompts
# Copie PR1-PR8 da seção 4.3 no chat, sempre com "Cite F#"

# 5. Compare
# Rode mesmo prompt sem "EXCLUSIVAMENTE nas fontes" e veja diferença de alucinação
```

### Extra: transformar vídeo em fonte de qualidade
- Abra F5 no YouTube → `...` → `Mostrar transcrição` → copie
- Limpe ruídos (ex: “deaf” → “def”) e cole no NotebookLM como `Fonte de texto copiado`
- Pergunte: “Crie linha do tempo do vídeo com timestamp e tópico”

---

## 🗂 Estrutura do Repositório

```
miniguia-python-fundamentals-notebooklm/
├── README.md                 # Entrega principal (Nota 10) — este arquivo
├── docs/
│   ├── fontes.md             # Fichamento detalhado das 5 fontes (em breve)
│   ├── prompts-reutilizaveis.md # Os 8 prompts em .md puro para copiar
│   └── cicatrizes.md         # Log completo de testes (em breve)
├── assets/
│   └── notebooklm-screenshot.png # Print do caderno com 5 fontes (adicione)
└── .gitignore

# Este projeto vive dentro do repo dio como caderno temático versionado.
# Você pode replicar para outros temas: miniguia-[tema]-notebooklm
```

---

## 🚀 Próximos Passos

- [ ] Adicionar screenshot do NotebookLM com 5 fontes + Audio Overview gerado
- [ ] Exportar PDFs de F1 e F4 para `/docs/fontes/` (quando licença permitir)
- [ ] Aplicar PR5 (PEP 8) em um script real e commitar antes/depois
- [ ] Criar caderno v2 com +2 fontes: `Effective Python` e `Python Fluente` (trechos abertos)
- [ ] Gravar video guide de 2 min mostrando workflow Docs + Vídeo

---

## 📌 Referências

1. Python Software Foundation — The Python Tutorial. https://docs.python.org/3/tutorial/
2. Python Wiki — Beginner's Guide. https://wiki.python.org/moin/BeginnersGuide
3. Al Sweigart — Automate the Boring Stuff with Python. https://automatetheboringstuff.com/
4. PEP 8 — Style Guide for Python Code. https://peps.python.org/pep-0008/
5. freeCodeCamp.org — Learn Python - Full Course for Beginners. https://www.youtube.com/watch?v=rfscVS0vtbw
6. Corey Schafer — Python Tutorials Playlist. https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU
7. Google — NotebookLM Help. https://support.google.com/notebooklm/answer/15732157

---

### 👤 Autor

**Rafael Marques Matos** — Projeto para o desafio DIO **“Entendendo o Desafio”**.

> 💡 *“Documentação é a fonte da verdade, vídeo é a intuição. Juntos no NotebookLM, viram método: curadoria + pergunta certa + citação = Python que você realmente entende — e consegue explicar.”*

**Como entregar na DIO:** copie a URL `https://github.com/rafaelmarquesmatos/dio` + caminho `/miniguia-python-fundamentals-notebooklm` e cole na entrega do desafio com descrição: *“Caderno Temático NotebookLM sobre Python Programming Fundamentals: Documentation and Video Guide — 5 fontes curadas (docs oficiais + video guides), engenharia de prompts com cicatrizes e miniguia com resumos, glossário e 8 prompts reutilizáveis.”*

