# Diagrama-Resilia-PJT-individual-04

--> Existem outras entidades além dessas três?
      sim, professor, módulos, aulas.

--> Quais são os principais campos e tipos? 
      campos: cursos, módulos, aulas, turmas, professores, alunos.
      tipos: var, char, int. 

--> Como essas entidades estão relacionadas? 
      cursos-módulos (1, n)
      módulos-cursos (1, n)
      cursos-turmas (1, n)
      turmas-alunos (n, n)
      professores-turmas (1, n)
      professores-alunos (n, n)
