## Objetivo: 
>**Criar dashboards de atendimentos de chamados internos e externos baseado no sistema de tickets separados por departamentos e modulos.**

# Requisitos funcionais

1. O sistema deve definir **SLA** para cada tipo de chamado. (***requisito normal***)
1. O sistema deve apresentar uma área de avaliação do serviço. (***requisito normal***)
1. Permitir que o chamado seja alterado mesmo após ele estar em andamento, como mudança de departamento do chamado. (***requisito normal***)
1. O sistema deve possuir um prazo(timeout) para o chamado continuar aberto. (***requisito normal***)
1. Os chamados podem ser reabertos. (***requisito normal***)
1. Cada departamento deve possuir seu próprio dashboard (***requisito normal***)
1. O sistema de possuir uma área para chamados internos para a equipe de TI. (***requisito normal***)
1. O sistema deve verificar se o chamado pode ser visualizado pelos diferentes departamentos, interno(restrito) e externo (**geral**). (***requisito normal***)
1. Não possui identidade visual fixa porém a logo é azul, podendo criar paleta de cor. (***requisito esperado***)
1. O sistema deve classificar cada chamado, como aberto, pendente ou expirado. (***requisito normal***)
1. Não é necessaria a autenticação para a abertura de um chamado. (***requisito normal***)
1. A plataforma deve armazenar os dados dos chamados, como nome, numero de cel, departamento (**pode ser alterado**) ,tecnico. (***requisito normal***)
1. Acessibilidade para deficientes visuais. (***requisito excitante***)

# Requisitos não funcionais

### Disponibilidade:
1. Quando o servidor ficar indisponível deve haver retorno (**timeout**). (***requisito normal***)
Eficiência:
1. Deve possuir capacidade para até 7 usuários simultâneos.
### Integridade:
1. Cargo de administrador com sistema de autenticação com um cadastro restrito para ele. (***requisito normal***)
1. Criar usuários como cliente dentro do sistema e classifica-los como cliente, podendo apenas ver seus chamados existentes. (***requisito esperado***)
Interoperabilidade:
1. Usar bpmn para uma melhor visualização do gerenciamento dos processos, diagrama. (***requisito normal***)
### Manutenibilidade:
1. Armazenar os dados dos processos numa planilha excel, pois estão acostumados com o processo manual. (***requisito normal***)
### Portabilidade:
1. Usar alguma biblioteca para ser responsivo para mobile.
