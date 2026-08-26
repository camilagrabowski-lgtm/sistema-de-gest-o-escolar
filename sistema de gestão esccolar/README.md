# Sistema de Gestão Escolar

## Sistema para gerenciar funcionários, cursos e matrículas

1. Quem vai utilizar o sistema (usuários)?
Funcionários.

2. Quais os tipos de usuários e o que cada tipo consegue fazer?
-Colaboradores: Cadastrar alunos, cadastrar cursos, listar alunos, listar cursos, excluir alunos, excluir cursos, desmatricular alunos dos cursos e atualizir os próprios dados.
-Admin: Todas as funções acima, mais: cadastrar outros funcionários, listar utros funcionários, editar dados dos outros funconário e excluir outros funcionários.

3. Quais informações iremos armanezar?
Funcionários: nome, CPF, e-mail, telefone, senha, endereço, data de nascimento e cargo.
Alunos: nome, CPF, data de nascimento, telefone, cursos e e-mail.
Cursos: nome, descrição, duração, carga horária e professor responsável.
Matrículas: quais alunos estão cadastrados em quais cursos.

4. Quais regras ou restrições são necessárias?
Apenas usuários autorizados podem alterar ou excluir informações.
O CPF deve ser único para cada aluno e funcionário e e-mail.
Um aluno não pode possuir duas matrículas ativas no mesmo curso e período.
Não ser possível realizar matrícula em um curso que esteja inativo.
Nome, e-mail, cargo, cpf, senha, carga horária, matrícula são dados obrigatórios.
O sistema deve validar as informações.

## PROBLEMA:
- Esses sistema é direcionado a funcionários de escolas.
- Permite cadastrar, editar, limitar e deletar alunos, cursos, matrículas e funcionários.

## MODELO DO NEGÓCIO:
![Business Model Canvas](images/business-model-canvas.png)


## REQUISITOS:
1. Requesitos Funcionais:
  - Cadastrar alunos
  - Cadastrar funcionários 
  - Cadastrar cursos
  - Listar alunos
  - Listar cursos
  - Listar funcionários
  - Mostrar os dados do aluno
  - Mostrar os dados do funcionário
  - Mostrar os dados do curso
  - Realizar as matrículas
  - Editar os dados do alunos
  - Editar os dados do funcionários
  - Editar os dados do curso
  - Excluir os alunos
  - Excluir os funcionários
  - Excluir os cursos 
  - Excluir as matrículas

  - O sistema deve permitir realizar login
  - O sistema deve permitir o usuário a sair da conta
  - O sistema deve permitir alterar os dados do próprio usuário
  - O sistema deve permitir pesquisar alunos
  - O sistema deve permitir pesquisar os cursos
  - o sistema deve permitir cancelar uma matrícula
  - O sistema deve permitir filtrar os alunos por curso
  - O sistema deve permitir filtrar os funcionários por curso
  - O sistema deve permitir vizualizar a quantidade de alunos cadastrados
  - O sistema deve permitr vizualizar a quantidade de matrículas realizadas
  - O sistema deve permitir consultar o histórico de matrículas do aluno
  - O sistema deve permitir consultar os alunos matriculados em um curso
  - O sistema deve permitir consultar os cursos em que um aluno está matriculado
  - O sistema deve permitir selecionar o período da matrícula
  - O sistema deve selecionar o prefessor responsável pelo curso
  - O sistema deve permitir alterar a situação de um curso
  - O sistema deve permitir cancelar uma matrícula
  - O sistema deve permitir alterar a senha do usuário
  - O sistema deve permitir ordenar a lista de alunos
  - O sistema deve permitir ordenar a lista de cursos
  - O sistema deve permitir ordenar a lista de funcionários
  - O sistema deve permitir buscar uma matrícula específica
  - O sistema deve permitir visualizar a data de uma matrícula
  - O sistema deve permitir visualizar a situação do curso
  - O sistema deve permitir visualizar o professor responsável pelo curso
  - O sistema deve permitir visualizar a descrição do curso
  - O sistema deve permitir visualizar a duração do curso
  - O sistema deve permitir visualizar a carga horária do curso.
  - O sistema deve permitir consultar os dados de contato de um aluno.



2. Requisitos Não Funcionais:
  - Autenticação
  - Interface com navegação padronizada e consistente entre as telas
  - Interface responsiva e adaptativa a diversas resoluções de tela e disposistivos diferentes, como computador, celular e tablet
  - Interface deve ser compativel com os principais navegadores web
  - Criptografar as senhas antes de salvá-las no banco de dados
  - 
