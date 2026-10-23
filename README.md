# tsc02
Repositório da Turma TSC02 — prática de Git e GitHub com 20 alunos.

## Regras gerais

1. **Clone**: cada aluno clona o repositório usando o **VS Code** (já integrado ao GitHub).
2. **Comandos**: todos usam os comandos básicos (`push`, `pull`, `fetch`, `diff`, `merge`, `branch`...), mas **um de cada vez**, de forma cadenciada.
3. **Pasta própria**: cada aluno trabalha **somente** dentro da sua pasta (`Aluno_01` ... `Aluno_20`). Não altere pastas de colegas, salvo quando a etapa pedir.
4. **Sinal verde**: ninguém atualiza (`pull`/`fetch`) o repositório até o colega da vez dar o sinal verde verbalmente na sala.

## Estrutura

Cada pasta `Aluno_NN/` contém um `index.html` com uma mensagem de boas-vindas **fixa**:
"Bom Dia, Sou Aluno_01, hoje é dia 22/10/2026 e são 09:32".

## Etapas

### Etapa 1 — Valores fixos para variáveis (um por vez)
1. O Aluno_01 troca os valores fixos (nome, data, hora) por variáveis (JavaScript), um valor por vez.
2. Visualiza o resultado localmente, faz `commit`, `pull` e `push`.
3. Dá o sinal verde; os demais fazem `fetch`/`pull` e veem a alteração.
4. Repete-se até o Aluno_20.

### Etapa 2 — Projeto de um colega
Todos entram no projeto de um aluno e, simultaneamente, cada um cria um arquivo HTML simples apenas com seu nome. Testar como na etapa anterior.

### Etapa 3 — Mesmo arquivo, linhas diferentes
Todos editam o mesmo arquivo de um mesmo aluno; cada um adiciona uma linha:
- Linha 1 — Nome do Aluno_01 + algo
- Linha 2 — Nome do Aluno_02 + algo
- ... até a linha 20.

Atualização: metade da sala de uma vez, depois a outra metade um por vez, para comparar. Sempre aguardando o sinal verde.

### Etapa 4 — Fork
Cada aluno faz um **fork**, cria um arquivo e exclui outro no seu fork. Dá o sinal verde para os demais verificarem que apenas o seu fork mudou. Depois todos repetem, um por vez.

### Etapa 5 — Merge
Camada de `merge`, seguindo os mesmos princípios.

### Etapa 6 — Branches
Camada de `branch`, seguindo os mesmos princípios.
