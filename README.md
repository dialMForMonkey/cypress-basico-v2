cy-data-test
Projeto de amostra para demonstrar um cy.dataTestcomando personalizado Cypress.

Pré requisitos
É necessário ter o Node.js e o npm instalados para executar este projeto.

Usei as versões v16.13.2e 8.1.2do Node.js e npm, respectivamente. Sugiro que você use as mesmas versões ou versões posteriores.

Instalação
Execute npm install(ou npm ipara a versão curta) para instalar as dependências dev.

Testes
Nota: Antes de executar os testes, faça uma cópia do cypress.env.example.json arquivo como cypress.env.json, que no mundo real você atualizaria com credenciais válidas.

O cypress.env.jsonarquivo está incluído .gitignoree você está seguro de que as informações confidenciais não serão versionadas.

Run npm test(ou npm tpara a versão curta) para executar o teste no modo headless.

Ou, corra npm run cy:openpara abrir o Cypress no modo interativo.

