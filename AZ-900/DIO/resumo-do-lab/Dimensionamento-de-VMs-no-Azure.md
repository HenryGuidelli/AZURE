# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

O processo de criação e ajuste de Máquinas Virtuais (VMs) no Azure é estruturado para equilibrar desempenho computacional, segurança e controle de custos através das seguintes sessões:

### Básico e Instância
Nesta sessão, definem-se os fundamentos da identidade e localização da VM:
- ***Projeto e Assinatura*** - Seleção da assinatura ativa e do Grupo de Recursos.
- ***Detalhes da VM*** - Definição do nome do recurso e escolha da Região para otimização de latência.
- ***Imagem e SO*** - Escolha do sistema operacional (Windows ou Linux) e da imagem de software base.
- ***Credenciais de Acesso*** - Configuração de autenticação via usuário/senha ou chaves SSH para ambientes Linux.

### Tamanho e Dimensionamento
Configuração da capacidade de processamento e estratégias de escala:
- ***Tipo de Instância*** - Escolha entre tamanhos Gerais, Otimizados para Memória (RAM) ou Otimizados para Computação (CPU).
- ***Escalabilidade Automática (Autoescala)*** - Configuração de regras baseadas em métricas (como CPU > 75%) para ajustar o número de instâncias conforme a demanda.
- ***Dimensionamento Manual*** - Alteração direta do tipo de instância e recursos de hardware conforme a necessidade evolutiva da carga de trabalho.

### Armazenamento e Discos
Definição das unidades de persistência de dados:
- ***Tipos de Disco*** - Seleção entre SSD Premium (alta performance), SSD Padrão (cargas moderadas) ou HDD Padrão (baixo custo).
- ***Discos de Dados*** - Adição de volumes extras para separação de dados de aplicação e backups.

### Rede e Segurança
Configuração da conectividade e proteção perimetral:
- ***Interface de Rede*** - Associação à Rede Virtual (VNet), sub-rede e atribuição de IP Público.
- ***Grupo de Segurança de Rede (NSG)*** - Criação de regras de firewall para limitar o tráfego de entrada (ex: portas RDP 3389 ou SSH 22).
- ***Azure Key Vault*** - Armazenamento seguro de credenciais e segredos da VM.

### Monitoramento e Continuidade
Gestão operacional e resiliência dos dados:
- ***Azure Monitor*** - Rastreamento de métricas de desempenho e configuração de alertas de utilização.
- ***Backup e Recuperação*** - Implementação de políticas de backup automático e planos de retenção para restauração em caso de falhas.

---

## Considerações sobre Gestão e Conectividade
Após o provisionamento via sessão **Revisar e Criar**, a conectividade é estabelecida através do menu "Conectar", utilizando protocolos RDP para sistemas Windows ou SSH para sistemas Linux. A manutenção da eficiência operacional depende da análise contínua de logs de diagnóstico e do ajuste do dimensionamento conforme as métricas de uso real da aplicação.
