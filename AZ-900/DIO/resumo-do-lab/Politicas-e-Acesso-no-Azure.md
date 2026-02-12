# Gerenciando Politicas em Acessos Azure
Os custos de operar no Azure variam conforme a atividade e frequência de uso, mas há maneiras de estimar e otimizar os custos no Azure.

### Microsoft Purview
Microsoft Purview é uma família de soluções de governança, risco e conformidade de dados que ajuda você a obter uma única exibição unificada em seus dados. O Microsoft Purview coleta informações sobre seus dados locais, multinuvem e software como serviço.
Duas áreas de solução principais compreendem o Microsoft Purview:
- ***Risco e Conformidade*** - Microsoft Teams, OneDrive e Exchange são apenas alguns dos serviços do Microsoft 365 que o Microsoft Purview usa para ajudar a gerenciar e monitorar seus dados.
- ***Governança de Dados Unificada*** - O Microsoft Purview tem soluções robustas e unificadas de governança de dados que ajudam a gerenciar seus dados locais, multinuvem e de software como serviço.
Há muitas formas de utilizar essas ferramentas para obter a estimativa mais ***próxima*** da realidade possivel.

### Azure Policy
O Azure Policy é um serviço do Azure que permite criar, atribuir e gerenciar políticas que controlam ou auditam os recursos.
Essas políticas impõem regras diferentes sobre as configurações dos recursos, de modo que essas configurações permaneçam em conformidade com os padrões corporativos.
As Políticas do Azure podem ser definidas em cada nível, permitindo que você defina políticas em um recurso específico, um grupo de recursos, uma assinatura e assim por diante. Além disso, as Políticas do Azure são herdadas, portanto, se você definir uma política em um nível superior, ela será aplicada automaticamente a todos os agrupamentos que se enquadram no pai. Por exemplo, se você definir um Azure Policy em um grupo de recursos, todos os recursos criados nesse grupo de recursos receberão automaticamente a mesma política.
Entre outras possibilidades.

### Bloqueios de Recursos
Um bloqueio de recurso impede que os recursos sejam excluídos ou alterados acidentalmente.
Há dois tipos de bloqueios de recursos:
- Um que impede que os usuários excluam -  significa que os usuários autorizados ainda poderão ler e modificar um recurso, mas não poderão excluir o recurso.
- Um que impede que os usuários alterem ou excluam um recurso - significa que os usuários autorizados poderão ler um recurso, mas não poderão excluir ou atualizar o recurso.
