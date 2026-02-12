# Ferramentas de Implantação na Azure
Ferramentas para gerenciar e implantar recursos do Azure.

### Portal do Azure
O portal do Azure é um console unificado baseado na Web que fornece uma alternativa às ferramentas de linha de comando.
O portal do Azure foi projetado para resiliência e disponibilidade contínua. Ele mantém uma presença em todos os datacenter do Azure. Essa configuração torna o portal do Azure resiliente a falhas individuais do datacenter e evita lentidão de rede por estar perto dos usuários. O portal do Azure é atualizado continuamente e não requer tempo de inatividade para atividades de manutenção.

### Azure Cloud Shell
O Azure Cloud Shell é uma ferramenta de shell baseada em navegador que permite criar, configurar e gerenciar recursos do Azure usando um shell. O Azure Cloud Shell dá suporte ao Azure PowerShell e à CLI (Interface de Linha de Comando) do Azure, que é um shell bash.

### Azure PowerShell
O Azure PowerShell é um shell com o qual desenvolvedores, DevOps e profissionais de TI podem executar comandos chamados command-lets (cmdlets). Esses comandos chamam a API REST do Azure para executar tarefas de gerenciamento no Azure.

### Azure CLI
A CLI do Azure é funcionalmente equivalente ao Azure PowerShell, com a principal diferença sendo a sintaxe dos comandos. Embora o Azure PowerShell use comandos do PowerShell, a CLI do Azure usa comandos Bash.
A CLI do Azure oferece os mesmos benefícios de lidar com tarefas discretas ou orquestrar operações complexas por meio do código. Ele também pode ser instalado em plataformas Windows, Linux e Mac, bem como por meio do Azure Cloud Shell.

### Azure Arc
Arc permite estender a conformidade e o monitoramento do Azure para suas configurações híbridas e de várias nuvens. O Azure Arc simplifica a governança e o gerenciamento fornecendo uma plataforma de gerenciamento local e de várias nuvens consistentes.

### Azure Resource Manager - ARM
O ARM (Azure Resource Manager) é o serviço de implantação e gerenciamento do Azure. Ele fornece uma camada de gerenciamento que permite que você crie, atualize e exclua recursos em sua conta do Azure. Sempre que você fizer qualquer coisa com seus recursos do Azure, o ARM estará envolvido.
Quando um usuário envia uma solicitação de qualquer uma das ferramentas, APIs ou SDKs do Azure, o ARM recebe a solicitação. O ARM autentica e autoriza a solicitação. Em seguida, o ARM envia a solicitação para o serviço do Azure, que executa a ação solicitada. Você vê resultados e recursos consistentes em todas as diferentes ferramentas porque todas as solicitações são tratadas por meio da mesma API.







