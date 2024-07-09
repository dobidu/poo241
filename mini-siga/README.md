# EXERCÍCIO

## PROGRAMAÇÃO ORIENTADA A OBJETOS

## PROF. CARLOS EDUARDO BATISTA

### REVISÃO DE C E INTRODUÇÃO A OO

**UFPB - 2024.1**

Altere o código "mini-sigaa.c" para complementar a implementação da estrutura `t_turma` e torná-la mais completa. Você deve criar uma nova estrutura `t_professor` para representar um professor e ela deve conter informações como nome, código do departamento e ano de contratação. Em seguida, você deve modificar a estrutura `t_turma` para incluir um ponteiro para um professor (para uma variável do tipo `t_professor`). Isso permitirá que cada turma tenha um professor associado a ela.

Além disso, você deve implementar as seguintes funções para manipular as novas estruturas:

- `cadastra_professor(t_professor *p)`: Esta função deve solicitar ao usuário que digite as informações do professor, como nome, departamento e disciplina lecionada. Em seguida, ela deve armazenar essas informações em uma instância da estrutura `t_professor`.

- `exibe_professor(t_professor *p)`: Esta função deve exibir as informações de um professor, como nome, departamento e disciplina lecionada.

- `associa_professor_turma(t_turma *t, t_professor *p)`: Esta função deve associar um professor a uma turma. Ela deve receber como parâmetros um ponteiro para a estrutura `t_turma` e um ponteiro para a estrutura `t_professor`. Em seguida, ela deve armazenar o ponteiro para o professor na estrutura `t_turma`.

- `calcula_media_cra_turma(t_turma *t)`: Esta função deve calcular e retornar a média do CRA (Coeficiente de Rendimento Acadêmico) dos alunos de uma turma. Ela deve receber como parâmetro um ponteiro para a estrutura `t_turma` e percorrer a lista de alunos para calcular a média do CRA.

Altere também a função que deve exibir as informações de uma turma, incluindo as informações do professor associado a ela.

Na função principal crie pelo menos 2 turmas, com 1 professor diferente e 3 alunos diferentes em cada. Exiba as informações das turmas, incluíndo a média dos CRA dos alunos. 
