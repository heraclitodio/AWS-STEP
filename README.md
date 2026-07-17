"# AWS-STEP" 


AWS Step Functuion serve como uma ferramenta para orquestar fluxos de trabalho na amazon, com ele é possível gerar uma infraestrutura com drag and drop de componentes da aws. É possivel colocar triggers, timers, validadores de fluxo para direcionar o fluxo que os dados seguirão

O step function consegue criar os s3, lambda, ecs, etc, que ele precisar para seguir o fluxo ou ele pode usar recursos que já foram criados antes

O step funciont permite definir a customização dos componentes, permitindo alterar o nome, o repositório, opções de log, editar o código do lambda

Por detrás o step function está rodando scripts do cloud formation para setar a arquitetura do projeto
