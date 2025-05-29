# dbViaCEP
Gestão de scripts para deploy em banco de dados

# Branches principais

main
Guarda somente os scripts efetivamente em produção
Só recebe merges de homolog após homologação completa

homolog
Recebe todos os scripts aprovados em develop para testes de pré-produção
Após validação em ambiente de homologação, é mergeada em main

develop
Ambiente de integração contínua de novos scripts
Recebe merges das feature branches para revisão inicial e QA interna