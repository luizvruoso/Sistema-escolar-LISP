# Sistema-escolar-LISP
Sistema escolar desenvolvido em LISP, utilizando apenas funções nativas

#Enunciado, trazendo o problema proposto
1. Descrição
Este problema envolve a construção do programa ​Academico.lsp​ que permitirá associar alunos e professores a disciplinas e a partir dessas associações responder a algumas questões. As funções implementar são as seguintes:
(DEFUN MATRICULAR (ALUNOS DISCIPLINAS TURMA BD) ... ) Argumentos​: ALUNOS: Lista contendo nomes de alunos;
Retorna​: Descrição​:
DISCIPLINA: Lista com nomes de disciplinas; TURMA: turma em que os alunos serão matriculados
(apenas uma)
BD: Lista contendo a base de dados.
Nova lista contendo a BD atualizada
Matricula cada um dos alunos na lista ALUNOS em todas as disciplinas da lista DISCIPLINAS, na TURMA indicada.
(DEFUN CANCELAR-MATRíCULA (ALUNOS DISCIPLINAS TURMA BD) ... )
Argumentos​: ...
Retorna​: Descrição​:
Nova lista contendo a BD atualizada
Cancelar a matrícula cada um dos alunos na lista ALUNOS de todas as disciplinas da lista DISCIPLINAS na TURMA indicada. Disciplinas não vinculadas a nenhum professor e sem alunos matriculados devem ser removidas da base.
(DEFUN VINCULAR (PROFESSORES DISCIPLINAS BD) ... ) Argumentos​: ...
Descrição​: Vincular cada um dos professores na lista
PROFESSORES a cada uma das disciplinas na lista
DISCIPLINAS;
Retorna​: Nova lista contendo a BD atualizada
Observações​: Um professor vinculado a um disciplina está apto a ministrá-la.
(DEFUN REMOVER-VINCULO (PROFESSORES DISCIPLINAS BD) ... )
 Argumentos​: ...
Descrição​: Retorna​:
Remover o vínculo de cada um dos professores na lista PROFESSORES a cada uma das disciplinas na lista DISCIPLINAS; Disciplinas não vinculadas a nenhum professor e sem alunos matriculados devem ser removidas da base.
Nova lista contendo a BD atualizada
(DEFUN ALUNOS? (BD) ... )
Argumentos​: .
Retorna​: Lista contendo o nome de todos os alunos
cadastrados.
Observação​:​ ​Um aluno é cadastrado quando é matriculado em
alguma disciplina. Alunos não vinculados a nenhuma disciplina devem ser removidos da base.
(DEFUN PROFESSORES? (BD) ... )
Argumentos​: .
Retorna​: Lista contendo o nome de todos os professores
cadastrados.
Observação​:​ ​Um professor é cadastrado quando é vinculado a
alguma disciplina. Professores não vinculados a nenhuma disciplina devem ser removidos da base.
(DEFUN DISCIPLINAS? (BD) ... )
Argumentos​: .
Retorna​: Lista contendo o nome de todas as disciplinas
cadastradas.
Observação​:​ ​Uma disciplina é cadastrada quando é associada a
algum aluno ou professor. Disciplinas não vinculados a nenhum professor ou aluno devem ser removidas da base.
(DEFUN MATRICULADOS? (DISCIPLINA TURMA BD) ... ) Argumentos​: .
Retorna​: Lista contendo o nome de todos os alunos
matriculados na disciplina DISCIPLINA em uma determinada TURMA.


