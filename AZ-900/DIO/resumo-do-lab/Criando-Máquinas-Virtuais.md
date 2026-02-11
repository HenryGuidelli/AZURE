# Microsoft Azure - Criando Máquinas Virtuais

As configurações de uma VM durante a sua criação, pelo Portal da Azure, são divididas em oito sessões, sendo elas:

### Básico
Na sessão de *Básico* configura-se as opções básicas da VM, como:
- ***Assinatura e Grupo de Recusos*** - Escolhe em qual assinatura e qual grupo de recurso a VM será criada.
- ***Nome da VM*** - VMs têm dois nomes, o nome do recurso do Azure (imutável) e o nome do host (mutável). Quando criados no portal, usam o mesmo nome.
- ***Região e Opções/Disponibilidade de Zona*** - Escolha a região do Azure e Escolha zonas preferenciais.
- ***Imagem e Arquitetura*** - Sistema operacional base para a VM, ARM64 ou X64.
- ***Tamanho*** - Capacidade de processamento, memória e capacidade de armazenamento.
- ***Nome de Usuário e Opções de Entrada/SSH*** - Define-se o nome do usuário padrão da VM e opções de SSH.

### Discos
Na sessão de *Discos* configura-se as opções de armazenamento da VM, como:
- ***Criptografia de Disco de VM;***
- ***Tamanho de Disco do SO;***
- ***Tipo de Disco de SO;***
- Entre outras opções.

### Rede
Na sessão de *Rede* configura-se as opções de rede da VM, como:
- ***Rede Virtual;***
- ***Sub-Rede;***
- ***IP Público***
- Entre outras opções.

## Considerações às demais sessões
As demais sessões da configuração de uma VM no Azure tratam de questões mais voltadas para o gestão, gerenciamennto e monitoramento do recurso, a VM, e sua replicação por meio de automação.
