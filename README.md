# Portfolio
Sou Enrico Damasceno, estudante de Sistemas e Mídias Digitais e adepto a programação. Estou me aprofundando em Python e PHP, mas já tive contato com Java, HTML, CSS, JavaScript, Kotlin, entre outros. Também sou interessado em inteligência artificial e cibersegurança.



## Contato:

**E-mail 1: pedroenrico03@outlook.com.br**

**LinkedIn: [https://www.linkedin.com/in/enrico-damasceno/](https://www.linkedin.com/in/enrico-damasceno/)**

Segue abaixo uma demonstração dos meus projetos mais recentes:

## P1: Sistema para administração de uma escola

Sistema terminal para administração de uma escola por coordenadores e professores, que permite a visualização e resposta de atividades por parte dos alunos e emissão de boletins para alunos e responsáveis.

### Diagrama de classes:

![image](https://github.com/enricodamasceno/Portfolio/assets/118639665/e163d4d9-a17c-4f1b-92d1-d07c880088b9)

Neste sistema, a classe _Usuario_, herdada pelas classes Coordenador, Professor, Responsável e Aluno, é uma classe abastrata que define o ambiente que será acessado. Polimorfismo é utilizado para realizar o login a partir de diferentes classes (upcasting). 

Pode ser utilizado para cadastrar atividades, respondê-las, alterar, excluir, atribuir notas, criar e alterar turmas, emitir relatórios, entre outros dependendo do ambiente acessado.

Um aluno está associado a uma turma, que possui atividades criadas pelo professor, estas podem ser respondidas pelo aluno e às respostas são atribuídas notas (que dependem dos alunos). O projeto une polimorfismo, abstração e o que mais é interessante à POO para um sistema simples que futuramente pode ser evoluído com a adição de um front-end e vinculação a um banco de dados.

https://github.com/enricodamasceno/Portfolio/assets/118639665/364ffdb4-441c-41c3-b78f-0be4f4f959dc

Repositório do projeto: https://github.com/enricodamasceno/Projeto-Escola

## P2: Automação - Alimentando um sistema web com dados de uma planilha excel

Recentemente, no meu trabalho, fui encarregado de transferir dados de uma planilha excel para um sistema web usando um método arcaico de cadastrar itens, digitar, salvar e repetir o processo inúmeras vezes, o que talvez me tomasse uma semana de trabalho. Para agilizar, criei um script em Python utilizando Selenium e um WebDriver para interagir com a página automáticamente. Usei Pandas para ler a planilha. Após algumas horas de pesquisa, consegui um código que funcionasse perfeitamente e terminasse todo o serviço enquanto eu conferia os dados.

![image](https://github.com/enricodamasceno/Portfolio/assets/118639665/0566721d-3db4-4693-af85-d47135daf60f)

Não posso divulgar o código por completo pois o mesmo foi feito adequadamente para o sistema em questão (e inclui dados pessoais), mas vou deixar um link para um repositório público que omite esses dados, apenas para constar.

Repositório do projeto: https://github.com/enricodamasceno/script-excel-automatico-publico

## Eu também estive estudando...
 - Machine Learning A-Z: AI, Python & R + ChatGPT Prize [2024]: https://www.udemy.com/course/machinelearning/
 - Laravel 8 from scratch: https://laracasts.com/series/laravel-8-from-scratch
