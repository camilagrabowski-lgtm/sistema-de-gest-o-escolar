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