# Data Structures — Estudo e Revisão

Repositório com atividades da disciplina de Estrutura de Dados I (MATA40) da UFBA.
Objetivo atual: revisar os conceitos e, ao longo da revisão, renomear variáveis
com nomes pouco óbvios para nomes que façam sentido, arquivo por arquivo.

## Ordem de estudo (roteiro)

1. **Listas** — `Codigos variados/lista_estatica.py`, `Codigos variados/lista_encadeada`
2. **Pilhas e Filas** — `Prova 2/Fila Pilha/pilha.py`, `Prova 2/Fila Pilha/fila.py`
3. **Árvores e Heap** — `Prova 2/Árvore Heap/arvore.py`, `arvore2.py`, `heap.py`
4. **Aplicações (Prova 2)** — Notação Polonesa Inversa, Escalonador de Processos,
   Ancestral Comum, Ordenação com Árvores (pasta `Prova 2/Soluçoes`)
5. **Prova 1 (revisão geral)** — gerenciador de memória, detector de plágio, etc.
   (`Prova_1/Questao_A.py` a `Questao_F.py`)

## Progresso

- [x] Lista encadeada simples (`Codigos variados/lista_encadeada`) — conceito revisado
      e variáveis renomeadas (`v`→`valor`, `n`→`novo_no`, `l`→`lista`, `temp`→`atual`).
      Testado com `python3 lista_encadeada`, saída confirmada. Também revisamos conceitos
      de OOP no código (classe/objeto, encapsulamento, `__init__`, `self`, composição
      entre `No` e `Lista`, delegação entre os dois métodos `imprimir`).
      Pendente: indicar exercícios de fixação sobre lista encadeada.
- [ ] Lista estática
- [ ] Pilha
- [ ] Fila
- [ ] Árvore binária
- [ ] Heap
- [ ] Aplicações da Prova 2
- [ ] Revisão da Prova 1

## Convenções de nomenclatura adotadas

- Nó de estrutura: `no`, `novo_no`, `atual` (para ponteiro de percurso)
- Estruturas: nome descritivo da própria estrutura (`lista`, `pilha`, `fila`, `arvore`)
- Evitar nomes de uma letra, exceto índices de laço simples (`i`, `j`)
