# desafio-cypress-QA

1- Descompactar o arquivo desafio-cypress-qa.zip
2- abrir o visual studio code direto pela pasta (irá carregar os arquivos da automação)
3- certifique-se que tenha o node.js instalado (pelo menos a versão 20.19), caso não tenha, instale
4- abrir o terminal do VS code e instalar as dependências do cypress (npm install cypress@14.1.0 -D) versão 14.1.0 é recomendada
5- para rodar os testes abra o cypress (npx cypress open) e execute o E2E testing ( Specs / Login )

Lista de cenários automatizados

Dentro do arquivo Login.cy existem 3 cenários de teste de login com 1 caso de teste cada. Escolhi 
a feature de login por ser algo mais repetitivo numa visão de usuário e essencial para o funcionamento
de qualquer aplicação.

1- Login de usuário com sucesso (valida se o usuário consegue fazer o login corretamente)
2- Erro - usuário inválido (Não faz o login como esperado, validando a mensagem de alerta para e-mail incorreto)
3- Erro - Senha inválida (Não faz o login, validando a mensagem de alerta para senha incorreta)
