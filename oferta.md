## Actions sgh-gerenciamento-broker
| Action | Ainda é necessária? | Está funcionando corretamente? | Possui agendamentos configurados corretamente? |
|---|---|---|---|
| Atualizar parâmetros | :white_check_mark: | :white_check_mark: | **sim** | Verificar possibilidade de unir com list-vault |
| Mover instância para outro grupo | :x: |  | **sim** | Foi desabilitada pois já existe na oferta suporte-oaas |
| Listando Vault | :white_check_mark: | :white_check_mark: | **não** | Verificar possibilidade de unir com atualizar parametros |
| Remove instâncias órfãs de uma action | :x: | :x: | **sim** | Desabilitada pois se utiliza a Remove instâncias órfãs (v2)  |
| Remove instâncias órfãs (v2) | :white_check_mark: | :x: | **sim** | Ambiente de Execução |
| Lista usuários impessoais a desprovisionar | :white_check_mark: | :white_check_mark: | **não** | Ambiente de Execução |
| Remover usuários impessoais inativos | :white_check_mark: | :x: | **não** | Front-end |
| Monitorar versionamento de oferta | :x: | :x: | **não** | Pode ser desabilitada  |
| Revoga requisicoes antigas | :white_check_mark: | :x: | **não** É necessário verificar pq essa oferta é agendada para ocorrer todo dia 13:23 | Não filtra as requisições para verificar se elas tem 7 dias ou mais |
| Sincroniza com S3 | :white_check_mark: | :x: | **não** | Front-end |
| Desprovisiona instâncias de testes | :white_check_mark: | :x: | **não** | Curadoria |
| Desprovisiona ambiente de testes de uma oferta | :white_check_mark: | :x: | **sim** | DevOps/Infra |
| Atualiza Badges | :white_check_mark: | :white_check_mark: | **-** | Observabilidade |
