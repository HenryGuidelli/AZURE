# Construindo Arquiteturas no Azure

A estruturação de um ambiente no Azure exige uma progressão lógica de etapas, garantindo que a base de rede e segurança suporte adequadamente os serviços de computação e dados. As fases principais são:

### Estruturação e Governança
Nesta fase, estabelece-se a base lógica para o recebimento dos recursos:
- ***Planejamento de Arquitetura*** - Definição dos serviços necessários e requisitos de alta disponibilidade baseados no Azure Well-Architected Framework.
- ***Grupo de Recursos*** - Criação do contêiner lógico para agrupar recursos relacionados, facilitando a gestão de faturamento e o ciclo de vida dos componentes.
- ***Região*** - Seleção da localidade geográfica para reduzir latência e otimizar a conformidade dos dados.

### Conectividade e Redes
Configuração do ambiente de rede que permitirá a comunicação isolada entre serviços:
- ***Rede Virtual (VNet)*** - Definição do espaço de endereçamento IP e segmentação em sub-redes.
- ***Grupos de Segurança de Rede (NSG)*** - Implementação de regras de firewall para controle de tráfego de entrada e saída por portas, protocolos e IPs.
- ***Balanceamento de Carga*** - Configuração de balanceadores públicos ou internos para distribuição de tráfego entre instâncias de computação.



### Provisionamento de Recursos
Implementação dos ativos de computação e persistência de dados:
- ***Máquinas Virtuais (VMs)*** - Seleção de sistema operacional, tamanho de hardware e associação obrigatória à rede virtual.
- ***Serviços de Banco de Dados*** - Provisionamento de instâncias (SQL, MySQL ou Cosmos DB) com configurações de escalabilidade e segurança de rede.

### Proteção e Monitoramento
Garantia da continuidade de negócio e visibilidade operacional:
- ***Backup e Redundância*** - Ativação de backups automáticos e replicação geográfica para resiliência contra falhas regionais.
- ***Monitoramento e Alertas*** - Configuração de logs de diagnóstico e métricas de desempenho (CPU, memória e disco) via Azure Monitor.

---

## Considerações sobre Otimização Contínua
A gestão da infraestrutura após o provisionamento envolve o uso do **Azure Cost Management** para controle de gastos e o **Azure Automation** para automação de tarefas. A revisão periódica das regras de segurança e permissões de acesso é essencial para manter a integridade do ambiente conforme a infraestrutura escala.
