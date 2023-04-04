# Missão

Sistema ERP web que possua dashboards de atendimentos de chamados internos e externos baseado no sistema de tickets separados por departamentos e módulos.


## Requisitos Funcionais

-   RF-1: O sistema deve definir SLA (documento que define as diretrizes operacionais, normas, procedimentos e métricas que devem ser seguidas por sua equipe de suporte, a fim de garantir o nível de satisfação dos clientes ideal) para cada tipo de chamado. (requisito normal)
-   RF-2: O sistema deve apresentar uma área de avaliação do serviço. (requisito normal)
-   RF-3: O sistema deve permitir que o chamado seja alterado mesmo após ele estar em andamento, como mudança de departamento do chamado. (requisito normal)
-   RF-4: O sistema deve possuir um prazo (timeout) para o chamado continuar aberto. (requisito normal)
-   RF-5: O sistema deve permitir que os chamados possam ser reabertos. (requisito normal)
-   RF-6: O sistema deve possuir um dashboard para cada departamento. a quantidade de chamados abertos para o departamento. As seguintes informações: status de chamados, fluxos de chamados, não necessariamente os fechados, mas devem aparecer em buscas e quantos chamados fechados no dia.  (requisito normal)
-   RF-7: O sistema deve possuir uma área para chamados internos para a equipe de ti. (requisito normal)
-   RF-8: O sistema deve verificar se o chamado pode ser visualizado pelos diferentes departamentos, interno (restrito) e externo (geral). (requisito normal) 
-   RF-9: O sistema deve classificar cada chamado, como aberto, pendente ou expirado. (requisito normal)
-   RF-10: Não deve ser necessária a autenticação para a abertura de um chamado. (requisito normal)
-   RF-11: O sistema deve armazenar os dados dos chamados, como nome, número de celular, departamento (pode ser alterado), técnico, e exibir no dashboard. (requisito normal)
-   RF-12: O sistema deve ter acessibilidade para deficientes visuais. (requisito excitante)
-   RF-13: O sistema deve possuir um cargo de administrador por meio de um sistema de autenticação com um cadastro restrito para ele. (requisito normal)
-   RF-14: O sistema deve criar usuários como cliente dentro do sistema e classificá-los como cliente, podendo apenas ver seus chamados existentes. (requisito esperado)


## Requisitos Não Funcionais

-   Disponibilidade:
    -   DS-1: Quando o servidor ficar indisponível deve haver retorno (timeout). (requisito normal)
-   Eficiência:
    -   EF-1: O sistema deve suportar até 7 usuários simultâneos. (requisito normal)
-   Flexibilidade:
    -   IF-1: O sistema não possui identidade visual fixa, porém a logo é azul, podendo criar paleta de cor. (requisito esperado)

# 5W2H

Perguntas | Definições
--------------------------------|------------------------------------------------------------
 Quem? | Qualquer usuário que deseja abrir um chamado, tanto funcionários quanto clientes da empresa
 O que? | Sistema Web para realização de chamados internos e externos.
 Quando?| O projeto deverá ser finalizado até o fim do 1° semestre de 2023.
 Onde? | Sistema implementado na Web, com aplicações funcionais em desktop e mobile.
 Por que? | Necessidade de gerenciamento de atendimentos.
 Quanto? | Sem orçamento determinado no momento.
 Como? |O sistema será desenvolvido com as linguagens HTML, CSS e JavaScript, e será utilizado por meio de uma interface web para chamados internos e externos.
 Para que? |Gerenciamento de demanda por meio de chamados internos e externos.


