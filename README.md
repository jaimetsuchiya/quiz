# Objetivo
Oferecer uma ferramenta pedagógica formativa e avaliativa para promoção de desenvolvimento das habilidades do aluno de acordo com a proposta do professor.

# Caraterísticas Técnicas
* Vue
* API AspNet .Core
* Banco de Dados Relacional - mysql
* Redis  (Controle de Sessao e Cache da Partida)
* Multi Idiomas
* WCAG 2.1

# Perfis disponíveis

## Aluno
* Login via rede social
* Solicitar complemento com numero de matrícula e instituicao de ensino
* Listar partidas disponiveis apos logon (historico de participacoes, partidas aguardando inicio) -
* Listar premiacoes
* Listar ranking por escola/matéria/global
* Compartilhar resultado nas redes sociais
	
## Professor
### Cadastro de Salas (Criar, alterar, ativar, desativar, adicionar alunos, remover alunos)
* Seleção da Instituição de Ensino
* Descrição da Sala
* Nivel da Sala
* Materia
	
### Partidas
* Criacao de Sala (Nome, Questionario(s) Associado(s), Numero de questoes, Numero Maximo de Participantes, Numero Minimo de Participantes, Agendamento de Sessao - Inicio e termino, )
* Monitoramento de salas (Salas Fechadas, Salas Abertas Aguardando Participantes, Salas Encerradas)
* Controle de Atividade da sala (Inicio do Jogo, Visualizacao dos Participantes)
* Visualizacao de Resultados em Salas Encerradas
* Exportar Resultados (pdf, csv)
* Necessario controle de matricula (sim ou nao)
* Matriculas associadas
* Permite pular questao para responder no final
* Tempo máximo da Partida
* Tempo total da Partida

### Materia

### Questionario
* Matéria Associada
* Nome
* Nivel
* Adicionar Questáo
* Remover Questáo

### Questoes
* Titulo
* Tags
* Tipo de Opcoes (Imagens, Texto, Vídeo)
* Resposta Correta
* Opcoes de Resposta: (Imagens, Texto, Vídeo)
* Pontos da Questão
* Tempo máximo (obs: caso a questão ou as opções baseiem-se em vídeo, o tempo máximo deve contemplar a soma da duração dos vídeos apresentados)
   
## Administrador da Instituicao de Ensino 
* Manutenção dos dados da instituição
* Visualização das Salas associadas
* Criação de partidas Inter-Salas (Mesmo funcionamento para os alunos, com exceção de que a cada questão respondida, um score da sala será atualizado e exibido ao lado do board da questão.)
* A apuração dos resultados tb muda, pois leva em consideração o resultado coletivo e não o individual
		
## Administrador do sistema
