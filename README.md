<h1 align="center">conceitos-nodejs</h1>
<h3 align="center">:rocket: Conceitos do Node.js aplicado no bootcamp GoStack da Rocketseat :rocket:</h3>

<p align="center"></br>&nbsp&nbsp&nbsp&nbsp Aplicação resultante de um desafio proposto pela Rocketseat relacionado à Conceitos do Node.js. Esta Aplicação tem como propósito armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".</p>

<p align="center">&nbsp&nbsp&nbsp&nbsp</br> O Desafio consiste em validar que as rotas criadas na aplicação permitam que o back-end retorne de forma correta as requisições feitas pelo cliente. Para a validação, foram realizados 9 testes, que são eles:</p>

<p><strong></br>1) Seja possível criar um novo repositório:</strong></br>
Para passar neste teste, a aplicação deve permitir que um repositório seja criado, e retorne um json com o projeto criado.</p>

<p><strong>2) Seja possível listar repositórios existentes:</strong></br>
Para passar neste teste, a aplicação deve permitir que seja retornado um array com todos os repositórios que foram criados até o momento.</p>

<p><strong>3) Seja possível atualizar um repositório:</strong></br>
Para passar neste teste, a aplicação deve permitir que sejam alterados apenas os campos url, title e techs.</p>

<p><strong>4) Que NÃO seja possível atualizar repositórios que NÃO existam:</strong></br>
Para passar neste teste, a aplicação deve validar na rota de update se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status 400.</p>

<p><strong>5) Que NÃO seja possível atualizar "likes" de um repositório manualmente:</strong></br>
Para passar neste teste, não pode ser permitido que a rota de update altere diretamente os likes desse repositório, mantendo o mesmo número de likes que o repositório já possuia antes da atualização. Isso porque o único lugar que deve atualizar essa informação é a rota de responsável por aumentar o número de likes.</p>

<p><strong>6) Seja possível deletar um repositório:</strong></br>
Para passar neste teste, deve ser permitido que a rota de delete exclua um projeto, e ao fazer a exclusão, ele retorne uma resposta vazia, com status 204.</p>

<p><strong>7) Que NÃO seja possível deletar repositórios que NÃO existam:</strong></br>
Para passar neste teste, a aplicação deve validar na rota de delete se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status 400.</p>

<p><strong>8) Seja possível dar um "like" para o repositório:</strong></br>
Para passar neste teste, a aplicação deve permitir que um repositório com o id informado possa receber likes. O valor de likes deve ser incrementado em 1 a cada requisição, e como resultado, retornar um json contendo o repositório com o número de likes atualizado.</p>

<p><strong>9) Que Não seja possível dar "like" em respositórios que não existam:</strong></br>
Para passar neste teste, a aplicação deve validar na rota de like se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status 400.</p>

<h3></br><strong>Como realizar o teste:</strong></h3>
<p><strong>...\pastaDoProjeto></strong> yarn test</p> 

