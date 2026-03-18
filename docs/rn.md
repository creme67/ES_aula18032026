# Regras de Negócio – Sistema FitPass Gym Management

## RN01 — Bloqueio por inadimplência
Alunos com mensalidade vencida há mais de 5 dias não podem entrar na academia.

## RN02 — Limite de vagas
Cada aula possui número máximo de alunos; ao atingir o limite, novos agendamentos devem ser bloqueados.

## RN03 — Cancelamento de agendamento
O aluno pode cancelar uma reserva até 1 hora antes do início da aula.

## RN04 — Pagamento parcial
Não é permitido pagamento parcial da mensalidade; o valor deve ser integral.

## RN05 — Avaliação física
Uma avaliação física só pode ser realizada se o aluno estiver ativo e regular.

## RN06 — Acesso restrito por perfil
Cada perfil possui permissão específica:
- Recepcionista: matrículas e pagamentos  
- Instrutor: aulas e avaliações  
- Gerente: relatórios e configuração de planos  

## RN07 — Atualização automática da regularidade
Ao registrar um pagamento, o sistema deve atualizar imediatamente a situação do aluno.
