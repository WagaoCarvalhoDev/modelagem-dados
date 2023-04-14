# Apresentação:

• Banco de Dados para Gerenciamento de uma faculdade.

Objetivo do Banco de Dados:

• Realizar controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar e turmas.

# Fases do projeto:

• Levantamento dos requisitos
• Identificação de Entidades e Relacionamentos
• Modelo E-R (Entidade-relacionamento)
• Diagrama E-R
• Dicionário de Dados
• Normalização
• implementação
• Testes Básicos

# Levantamento dos requisitos

• Regras de negócio
• Verificar elementos que possam ser transformados em categorias ou classes.

# Identificação de Entidades e Relacionamentos:

• Aluno, professor, disciplina, curso, departamento.

Entidades e Relacionamentos:

• Aluno está matriculado em curso
• Aluno cursa disciplina
• Aluno realizou disciplina
• Disciplina pertence ao cusro
• Professor ministra disciplina
• Professor pertence a departamento
• Departamento é responsável por disciplina
• Departamento controla curso
• Disciplina pode depender de outras disciplinas

Atributos:

• Nº da matrícula
• Nome
• Endereço
  • Rua
  • Nº
  • Bairro
  • CEP
  • Cidade
  • Estado
• Código do curso 

Professor:

• Código Professor
• Nome
• Sobrenome
• Código de Departamento

Disciplina:

• Código Disciplina
• Nome
• Descrição curricular
• Código de Departamento
• Nº de alunos

Curso:

• Código Curso
• Nome
• Código de Departamento

Departamento:

• Código Departamento
• Nome Departamento

Aluno:

• Nº da matrícula
• Nome
• Endereço
• Código do curso
• Telefone







