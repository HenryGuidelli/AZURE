# Entendendo sobre Segurança e Identidade na Azure

A segurança no Azure é fundamentada no modelo de responsabilidade compartilhada, utilizando camadas de defesa que abrangem desde a identidade do usuário até a proteção da rede e dos dados.

### Gestão de Identidade e Acesso (Microsoft Entra ID)
O Microsoft Entra ID é o serviço central para controle de quem pode acessar os recursos:
- ***Usuários e Grupos*** - Criação de identidades digitais e organização em grupos para simplificar a atribuição de permissões em escala.
- ***Autenticação Multifator (MFA)*** - Implementação de camadas extras de verificação no painel de Segurança para mitigar riscos de credenciais comprometidas.
- ***Acesso Condicional*** - Definição de políticas baseadas em contexto, como localização, estado do dispositivo ou nível de risco para autorizar o acesso.

### Governança e Controle (RBAC e Policy)
Mecanismos para garantir que as permissões e conformidades sejam respeitadas em todos os níveis:
- ***RBAC (Controle de Acesso Baseado em Funções)*** - Atribuição de funções específicas (Leitor, Colaborador, Proprietário) através do painel de Controle de Acesso (IAM).
- ***Azure Policy*** - Criação de regras para impor restrições automáticas e garantir a conformidade em assinaturas, grupos de recursos ou recursos individuais.

### Proteção de Dados e Segredos
Camadas de blindagem para informações sensíveis e comunicações:
- ***Azure Key Vault*** - Gerenciamento centralizado de chaves de criptografia, segredos (senhas) e certificados, com controle rigoroso de políticas de acesso.
- ***Criptografia*** - Proteção de dados em repouso (armazenamento) e em trânsito (utilizando HTTPS, SSL/TLS ou IPsec).

### Segurança de Rede e Infraestrutura
Controle do tráfego e perímetros de proteção:
- ***Grupos de Segurança de Rede (NSG)*** - Definição de regras de entrada e saída para filtrar o tráfego por portas, endereços IP e protocolos.
- ***Azure Firewall*** - Implementação de filtragem de tráfego avançada para proteção entre redes ou com a internet.

### Monitoramento e Postura de Segurança
Visibilidade operacional e resposta a incidentes:
- ***Microsoft Defender for Cloud*** - Plataforma unificada para monitoramento da postura de segurança, identificação de vulnerabilidades e avaliação de conformidade.
- ***Azure Monitor e Auditoria*** - Configuração de diagnósticos e uso do Log Analytics para rastrear atividades de login e analisar logs de acesso.

---

## Considerações sobre Segurança Zero Trust
A adoção de uma abordagem de **Segurança Zero Trust** é essencial, baseando-se no princípio de nunca confiar e sempre verificar. Isso inclui a realização de auditorias periódicas de permissões, a manutenção de um plano de resposta a incidentes atualizado e o treinamento contínuo das equipes para identificação de ameaças.
