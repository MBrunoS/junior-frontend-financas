# Publicação dos checkpoints

Os manifestos `frontend.json` e `backend.json` definem os pares obrigatórios de
checkpoints. Ao extrair cada projeto para seu repositório oficial:

1. `sprint-N-start` deve conter o resultado verde da sprint anterior e somente o
   scaffold necessário para iniciar a próxima;
2. `sprint-N-solution` deve conter todos os critérios obrigatórios daquela sprint;
3. ambos devem ser tags anotadas e publicados como releases com os mesmos nomes;
4. a release `start` não pode conter a solução escondida em outra pasta;
5. a release `solution` deve registrar lint, testes e build executados;
6. correções posteriores recebem sufixo de patch, como `sprint-4-solution.1`, sem
   mover silenciosamente uma tag já usada por alunos.

Os manifestos fazem parte deste repositório para que a navegação do curso e os
repositórios distribuíveis compartilhem os mesmos nomes e resultados esperados.
