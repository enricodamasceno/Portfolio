# Portfolio
Sou Enrico Damasceno, desenvolvedor back-end e adepto a programação. Estou me aprofundando em Java, PHP e Python, mas já tive contato com HTML, CSS, JavaScript, entre outros. Também sou interessado em inteligência artificial e cibersegurança.

Segue abaixo uma demonstração dos meus projetos mais recentes:

## Projeto: Sistema para administração de uma escola

Sistema terminal para administração de uma escola por coordenadores e professores, que permite a visualização e resposta de atividades por parte dos alunos e emissão de boletins para alunos e responsáveis.

### Diagrama de classes:

![image](https://github.com/enricodamasceno/Portfolio/assets/118639665/e163d4d9-a17c-4f1b-92d1-d07c880088b9)

Neste sistema, a classe _Usuario_, herdada pelas classes Coordenador, Professor, Responsável e Aluno, é uma classe abastrata que define o ambiente que será acessado. Polimorfismo é utilizado para realizar o login a partir de diferentes classes (upcasting). 

Pode ser utilizado para cadastrar atividades, respondê-las, alterar, excluir, atribuir notas, criar e alterar turmas, emitir relatórios, entre outros dependendo do ambiente acessado.

Um aluno está associado a uma turma, que possui atividades criadas pelo professor, estas podem ser respondidas pelo aluno e às respostas são atribuídas notas (que dependem dos alunos). O projeto une polimorfismo, abstração e o que mais é interessante à POO para um sistema simples que futuramente pode ser evoluído com a adição de um front-end e vinculação a um banco de dados.

Repositório do projeto: https://github.com/enricodamasceno/Projeto-Escola
