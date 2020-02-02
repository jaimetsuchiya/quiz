# Objetivo
Oferecer uma ferramenta pedagógica formativa e avaliativa para promoção de desenvolvimento das habilidades do aluno de acordo com a proposta do professor.

# Caraterísticas Técnicas
Angular
API AspNet .Core
Banco de Dados Relacional - mysql
Redis  (Controle de Sessao e Cache da Partida)
Multi Idiomas

# Perfis disponíveis
## Aluno
## Login via rede social
### Solicitar complemento com numero de matrícula e instituicao de ensino
### Listar partidas disponiveis apos logon (historico de participacoes, partidas aguardando inicio) -> Status das Partidas (Nova -> Visível apenas para o professor, Agendada -> Visivel apenas para o professor, 																																Aguardando alunos -> Visivel para todos, ate que o numero minimo de alunos seja alcancado, Aguardando inicio -> Visivel para todos, a partir do numero minimo de alunos, Fechada -> Visivel para todos, até o término da partida (opcional, qdo todos concluem as questoes ou qdo o tempo termina), Aguardando apuracao -> Visivel para todos a partir do fechamento (a partir do encerramento por parte do aluno, ele passa a enxergar este status), Concluda -> partida encerrada, exibe o ranking com as posicoes dos alunos na partida)
### Listar premiacoes
### Listar ranking por escola/matéria/global
### Compartilhar resultado nas redes sociais
	
## Professor
### Sala
#### Manutencao de Sala (Criar, alterar, ativar, desativar, adicionar alunos, remover alunos)
#### Nivel da Sala
#### Materia
	
	
### Partidas
#### Criacao de Sala (Nome, Questionario(s) Associado(s), Numero de questoes, Numero Maximo de Participantes, Numero Minimo de Participantes, Agendamento de Sessao - Inicio e termino, )
#### Monitoramento de salas (Salas Fechadas, Salas Abertas Aguardando Participantes, Salas Encerradas)
#### Controle de Atividade da sala (Inicio do Jogo, Visualizacao dos Participantes)
#### Visualizacao de Resultados em Salas Encerradas
#### Exportar Resultados (pdf, csv)
#### Necessario controle de matricula (sim ou nao)
#### Matriculas associadas
#### Permite pular questao para responder no final
		
### Materia (Tabela de Dominio CRUD)
	
### Questionario
#### Matéria Associada
#### Nome
#### Nivel
#### Questoes
##### Titulo
##### Tags
##### Tipo de Opcoes (Imagens, Texto, Vídeo)
##### Resposta Correta
##### Opcoes de Resposta: (Imagens, Texto, Vídeo)
##### Pontos da Questão
##### Tempo máximo (obs: caso a questão ou as opções baseiem-se em vídeo, o tempo máximo deve contemplar a soma da duração dos vídeos apresentados)

	
	 
   
## Administrador da Instituicao de Ensino 
## Administrador do sistema
