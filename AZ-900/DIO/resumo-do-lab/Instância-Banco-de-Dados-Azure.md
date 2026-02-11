# Configurando uma instância de Banco de Dados na Azure

As configurações de uma instância de SQL Database durante a sua criação, pelo Portal do Azure, são divididas em sessões principais, sendo elas:

### Básico
Na sessão de *Básico* configura-se as opções fundamentais do recurso e do servidor:
- ***Assinatura e Grupo de Recursos*** - Escolha da assinatura ativa e do grupo para organizar os recursos.
- ***Detalhes do Banco de Dados*** - Definição de um nome único para a sua base de dados.
- ***Servidor*** - Configuração de um servidor SQL (novo ou existente), definindo nome, localização (região) e credenciais de administrador (login e senha).
- ***Configurar Banco de Dados*** - Escolha da camada de serviço (Basic, Standard, Premium ou Hiperescala) e do modelo de computação (DTU ou vCore).



### Rede
Na sessão de *Rede* configura-se a conectividade e segurança de acesso:
- ***Método de Conectividade*** - Escolha entre Ponto de Extremidade Público (acesso via internet) ou Privado (Rede Virtual Azure).
- ***Regras de Firewall*** - Permissão de acesso ao IP atual do usuário e configuração de regras para IPs externos.

### Segurança
Na sessão de *Segurança* define-se a proteção da identidade e dos dados:
- ***Autenticação*** - Configuração de métodos como SQL Authentication ou Azure Active Directory (AAD).
- ***Microsoft Defender for SQL*** - Ativação de proteção avançada contra ameaças e vulnerabilidades.
- ***Auditoria*** - Configuração de registros para monitorar acessos e mudanças no banco de dados.

### Proteção de Dados
Na sessão de *Proteção de Dados* configura-se a resiliência e backups:
- ***Redundância de Backup*** - Definição entre redundância local ou geo-redundante para garantir a recuperação em caso de falhas regionais.

---

## Considerações às demais sessões
As demais sessões, como **Configurações Adicionais** e **Tags**, tratam de parametrizações de colação (collation), restauração de backups existentes e organização de metadados para faturamento. Após a validação na sessão **Revisar e Criar**, o recurso é provisionado e fica pronto para conexão via ferramentas como SSMS ou Azure Data Studio.
