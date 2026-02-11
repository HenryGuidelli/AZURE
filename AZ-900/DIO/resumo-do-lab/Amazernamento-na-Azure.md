# Dominando o Armazenamento na Azure

As contas de armazenamento no Azure fornecem um espaço de nome exclusivo para seus dados, integrando diferentes tipos de serviços e níveis de redundância para garantir a durabilidade e disponibilidade das informações.

### Configuração da Conta de Armazenamento
Nesta sessão, definem-se os parâmetros fundamentais de desempenho e resiliência:
- ***Informações Básicas*** - Definição da assinatura, grupo de recursos e nome exclusivo da conta (3-24 caracteres, apenas minúsculas e números).
- ***Desempenho e Tipo de Conta*** - Escolha entre Padrão ou Premium, utilizando preferencialmente o tipo "General Purpose v2".
- ***Replicação e Redundância*** - Seleção entre LRS (local), GRS (geográfica) ou ZRS (por zona) para proteção contra falhas.
- ***Segurança Avançada*** - Ativação de transferência segura (HTTPS), Large File Shares e Hierarchical Namespace para Data Lake Gen2.

### Serviços de Armazenamento
Configuração dos modelos de dados específicos dentro da mesma conta:
- ***Blobs (Containers)*** - Armazenamento de objetos não estruturados com definição de nível de acesso (Privado ou Público).
- ***Arquivos (File Shares)*** - Compartilhamento de arquivos gerenciado via protocolo SMB, montável em VMs ou servidores locais.
- ***Tabelas (Tables)*** - Armazenamento NoSQL de chave-valor para dados estruturados não relacionais.
- ***Filas (Queues)*** - Serviço de mensagens para armazenamento e recuperação de grandes volumes de mensagens, facilitando o desacoplamento de aplicações.

### Rede e Segurança de Dados
Definição de perímetros de proteção e integridade:
- ***Conectividade*** - Configuração de Pontos de Extremidade Públicos ou Privados e regras de Firewall em Redes Virtuais.
- ***Criptografia*** - Ativação de criptografia de dados em repouso e gerenciamento de chaves.

### Migração e Gerenciamento
Processos para movimentação de dados e sustentação do ambiente:
- ***Migração*** - Utilização do Azure Migrate para projetos estruturados e AzCopy para transferência rápida de dados via linha de comando.
- ***Monitoramento e Alertas*** - Uso do Azure Monitor para acompanhar capacidade, latência e configurar notificações de falhas.
- ***Backup e Recuperação*** - Implementação do Azure Backup e Geo-Redundância para garantir a recuperação em cenários de desastres regionais.

---

## Considerações sobre Governança de Dados
A gestão eficiente do armazenamento no Azure requer a revisão periódica das camadas de acesso (Frequente, Esparsa ou de Arquivo) para otimização de custos. O uso de ferramentas como o Azure Storage Explorer é recomendado para a administração visual e direta dos dados armazenados em Containers e File Shares.
