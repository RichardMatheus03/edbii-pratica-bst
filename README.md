# Prática — Árvore Binária de Busca (ABB / BST)

Atividade assíncrona de **Estruturas de Dados** (EDB II).

**Aluno:** Richard Matheus Bezerra Ataliba  
**Arquivo principal:** `edbii-pratica-bst.ipynb`

## Conteúdo

| Questão | Tema |
|--------|------|
| Q1 | Implementação completa da `ArvoreBinariaBusca` (inserção/busca/remoção iterativas + percursos) |
| Q2 | Cadastro acadêmico: listagens, trancamentos e análise da forma degenerada |
| Q3 | Agenda de clínica: agendamento sem sobrescrita e consulta por intervalo com poda |
| Q4 | Catálogo de biblioteca: altura, folhas, níveis e carregamento balanceado vs. ordenado |
| Q5 | Backup/restauração: impacto do percurso (pré-ordem vs. em ordem) |

## Como executar

Requisitos: Python 3.10+ e Jupyter (ou apenas o runtime do notebook).

```bash
# Opção 1 — Jupyter Lab / Notebook
jupyter notebook edbii-pratica-bst.ipynb
# depois: Kernel → Restart & Run All

# Opção 2 — linha de comando (gera saídas no próprio .ipynb)
jupyter nbconvert --to notebook --execute --inplace edbii-pratica-bst.ipynb
```

Não são necessárias bibliotecas externas além da biblioteca padrão (`collections.deque` para BFS).

## Restrições da atividade

- Não usar bibliotecas prontas de árvore.
- Não usar `sorted` / `dict` / `set` para *resolver* as questões.
- `adicionar`, `buscar` e `profundidade` são **iterativos** (árvores em fila com milhares de nós).

## Status

Todas as células de teste do notebook passam com ✅ após *Restart & Run All*.
