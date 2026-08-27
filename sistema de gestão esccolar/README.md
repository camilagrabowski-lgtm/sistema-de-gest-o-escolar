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
  - Login de usuários 
  - Buscar aluno pelo nome
  - Buscar aluno pelo CPF 
  - Buscar funcionário pelo nome 
  - Buscar funcionários pelo CPF
  - Mostrar os cursos em que cada aluno está matrículado
  - Mostrar os alunos que estão matrículados em cada curso

2. Requisitos Não Funcionais:
  - Autenticação
  - Interface com navegação padronizada e consistente entre as telas
  - Interface responsiva e adaptativa a diversas resoluções de tela e disposistivos diferentes, como computador, celular e tablet
  - Interface deve ser compativel com os principais navegadores web
  - Criptografar as senhas antes de salvá-las no banco de dados
  - Disponível durante todo o horário de funcionamento da instituição
  - Restringir acesso pelo tipo de usuário

## REGRAS DE NEGÓCIO
  - CPF de cada aluno deve ser único
  - CPF de cada funcionário deve ser único
  - Email de cada funcionário deve ser único
  - A matrícula de cada aluno deve ser única 
  - Nome de cada curso deve ser único
  - Impedir exclusão de cursos que tenham alunos matrículados
  - Impedir exclusão de alunos que estejam matrículados em 1 ou mais cursos
  
