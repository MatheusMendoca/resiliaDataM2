#  Programadores Cariocas | Data Analytics | Senac - Resilia

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1000&color=F2F71B&random=false&height=93&lines=Projeto+em+grupo+-+Modulo+2;Banco+de+dados+da+Resilia;Moderniza%C3%A7%C3%A3o+do+Processo+de+;Armazenamento+e+Gerenciamento" alt="Typing SVG" /></a>

## Objetivo :bulb:
Este projeto visa modernizar o processo de armazenamento e gerenciamento de dados do braço de ensino da Resilia, substituindo as planilhas por um sistema de banco de dados relacional. A seguir, detalharemos as etapas e entregáveis conforme solicitado.

### 1. Representação das Entidades, Atributos e Relacionamentos:
  - 1.1. **Entidade: Facilitador**
      - Atributos: idFacilitador (Chave Primária), nome, disciplina, especialização. <br>
  - 1.2. **Entidade: Módulo**
      - Atributos: idModulo (Chave Primária), numero, data_inicio, data_fim, ementa, idFacilitador (Chave Estrangeira referenciando Facilitador).<br>
  - 1.3. **Entidade: Turma**
      - Atributos: idTurma (Chave Primária), turno, sala, capacidade, semestre, idModulo (Chave Estrangeira referenciando Módulo).<br>
  - 1.4. **Entidade: Aluno**
      - Atributos: idAluno (Chave Primária), nome, data_nascimento, telefone, email, cpf, cep, cidade, estado.<br>
  - 1.5. **Entidade: Matrícula**
      - Atributos: idTurma (Chave Estrangeira referencia Turma), idAluno (Chave Estrangeira referencia Aluno), status_matricula, <br>
  - 1.6. **Entidade: Curso**
      - Atributos: idCurso (Chave Primária), matriz_curricular, duração, idTurma (Chave Estrangeira referencia Turma), idAluno (Chave Estrangeira referencia Aluno).<br>
  - 1.7. **Entidade: Grade Curricular**
      - Atributos: idCurso (Chave Estrangeira referencia Curso), idModulo (Chave Estrangeira referencia Modulo), quantidade.<br>
