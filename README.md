# Sistema-escolar-LISP
Sistema escolar desenvolvido em LISP, utilizando apenas funções nativas

#Enunciado, trazendo o problema proposto
1. Descrição

Este problema envolve a construção do programa ​Academico.lsp​ que permitirá associar alunos e professores a disciplinas e a partir dessas associações responder a algumas questões. As funções implementar são as seguintes


##(DEFUN MATRICULAR (ALUNOS DISCIPLINAS TURMA BD) ... ) 

Argumentos​: ALUNOS: Lista contendo nomes de alunos; DISCIPLINA: Lista com nomes de disciplinas; TURMA: turma em que os alunos serão matriculados (apenas uma); BD: Lista contendo a base de dados.

Retorna​: Nova lista contendo a BD atualizada

Descrição​: Matricula cada um dos alunos na lista ALUNOS em todas as disciplinas da lista DISCIPLINAS, na TURMA indicada.

##(DEFUN CANCELAR-MATRíCULA (ALUNOS DISCIPLINAS TURMA BD) ... )

Argumentos​: ...

Retorna​: Nova lista contendo a BD atualizada

Descrição​: Cancelar a matrícula cada um dos alunos na lista ALUNOS de todas as disciplinas da lista DISCIPLINAS na TURMA indicada. Disciplinas não vinculadas a nenhum professor e sem alunos matriculados devem ser removidas da base.

##(DEFUN VINCULAR (PROFESSORES DISCIPLINAS BD) ... )

Argumentos​: ...

Retorna​: Nova lista contendo a BD atualizada

Descrição​: Cancelar a matrícula cada um dos alunos na lista ALUNOS de todas as disciplinas da lista DISCIPLINAS na TURMA indicada. Disciplinas não vinculadas a nenhum professor e sem alunos matriculados devem ser removidas da base.

Obs:  Um professor vinculado a um disciplina está apto a ministrá-la.


##(DEFUN REMOVER-VINCULO (PROFESSORES DISCIPLINAS BD) ... )

Argumentos​: ...

Retorna​: Nova lista contendo a BD atualizada

Descrição​: Remover o vínculo de cada um dos professores na lista PROFESSORES a cada uma das disciplinas na lista DISCIPLINAS; Disciplinas não vinculadas a nenhum professor e sem alunos matriculados devem ser removidas da base.

##(DEFUN ALUNOS? (BD) ... )

Argumentos​: ...

Retorna​: Lista contendo o nome de todos os alunos
cadastrados.

Obs​: ​Um aluno é cadastrado quando é matriculado em alguma disciplina. Alunos não vinculados a nenhuma disciplina devem ser removidos da base.



##(DEFUN PROFESSORES? (BD) ... )

Argumentos​: ...

Retorna​: Lista contendo o nome de todas as professores cadastradas.

Obs​: ​Um professor é cadastrado quando é vinculado aalguma disciplina. Professores não vinculados a nenhuma disciplina devem ser removidos da base.

##(DEFUN DISCIPLINAS? (BD) ... )

Argumentos​: ...

Retorna​: Lista contendo o nome de todas as disciplinas cadastradas.

Obs​: ​Uma disciplina é cadastrada quando é associada a algum aluno ou professor. Disciplinas não vinculados a nenhum professor ou aluno devem ser removidas da base.

##(DEFUN MATRICULADOS? (DISCIPLINA TURMA BD) ... ) 

Argumentos​: ...

Retorna​: Lista contendo o nome de todos os alunos matriculados na disciplina DISCIPLINA em uma determinada TURMA.

##(DEFUN VINCULADOS? (DISCIPLINA BD) ... )

Argumentos​: ...

Retorna​: Lista contendo o nome de todos os professores vinculados à disciplina DISCIPLINA.

##(DEFUN CURSA? (ALUNO BD) ... )

Argumentos​: ...

Retorna​: Lista contendo o nome de todas as disciplinas cursadas pelo aluno ALUNO.

##(DEFUN MINISTRA? (PROFESSOR BD) ... )

Argumentos​: ...

Retorna​: Lista contendo o nome de todas as disciplinas ministradas pelo professor PROFESSOR.

