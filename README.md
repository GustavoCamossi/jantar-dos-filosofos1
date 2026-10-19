# O Jantar dos Filósofos

Jogo interativo para ensinar **deadlock** na disciplina de Sistemas Operacionais (Aula 6).
Cinco filósofos (Sócrates, Platão, Aristóteles, Hipátia e Descartes) disputam cinco hashis
e mostram, ao vivo, como surgem as quatro condições de Coffman.

**Jogar online:** https://SEU-USUARIO.github.io/jantar-dos-filosofos/

## Modos

- **Aula guiada:** 20 passos que acompanham os slides da aula, com perguntas para a turma.
  Avance com as setas do teclado ou com o passador de slides.
- **O sistema escalona:** a simulação roda sozinha e pausa para explicar cada condição de Coffman que aparece.
- **Você escalona:** cada clique executa o próximo passo de um filósofo. Missão: travar o jantar em 5 cliques.

## Estratégias

| Estratégia | Condição de Coffman quebrada |
|---|---|
| Ingênua (esquerdo, depois direito) | nenhuma: pode dar deadlock |
| Solta e repete | retenção e espera (risco de livelock) |
| Ordem crescente | espera circular |
| No máximo 4 à mesa | espera circular |
| Os dois ou nenhum | retenção e espera |

## Como usar

Basta abrir o `index.html` em qualquer navegador. Não precisa instalar nada.

---
Material didático da disciplina de Sistemas Operacionais. Problema proposto por Dijkstra e
reformulado por Hoare; condições de Coffman (1971); código no estilo de Tanenbaum.
