# ExactaSOFT
## Programa para Cadastrar Usuários - Estudo em React App

### Scripts usados

#### Backend

Dentro desse projeto há duas pastas, uma fazendo referencia ao backend e a outra ao frontend.

Entrando no diretório do backendo e usando o terminal, digite:

npm start

Isso faz com que o app responsável pelo backend passe a rodar em listen mode na porta 3001, podendo ser conferido em:

[http://localhost:3001](http://localhost:3001)

#### Frontend

Já para fazer o frontend funcionar é necessário entrar com o terminal na pasta frontend e rodar o mesmo comando:

npm start

Isso faz com que o app responsável pelo frontend passe a rodar na porta 3000, podendo ser conferido em:

[http://localhost:3000](http://localhost:3000)

### Compilando o projeto

Rodando o comando:

npm run build

Esse comando compila o aplicativo para produção na pasta build. Ele agrupa corretamente o React no modo de produção e otimiza a compilação para o melhor desempenho.

A compilação é reduzida e os nomes dos arquivos incluem os hashes.

Seu aplicativo estará pronto para ser implantado!

Consulte a seção sobre [implantação](https://facebook.github.io/create-react-app/docs/deployment) para obter mais informações.

### Encerrando a Build

**Note: esta é uma operação unidirecional. Uma vez que você usar o comando `eject`, você não pode voltar!**

Rodar o comando:

npm run eject

Se você não estiver satisfeito com a ferramenta de compilação e as opções de configuração, você pode `ejetar` a qualquer momento. Este comando removerá a dependência de compilação única do seu projeto.

Em vez disso, ele copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc) diretamente em seu projeto para que você tenha controle total sobre eles. Todos os comandos, exceto `eject`, ainda funcionarão, mas eles apontarão para os scripts copiados para que você possa ajustá-los. Neste ponto você está por conta própria.

Você não precisa usar `eject`. O conjunto de recursos com curadoria é adequado para implantações pequenas e médias, e você não deve se sentir obrigado a usar esse recurso. No entanto, entendemos que essa ferramenta não seria útil se você não pudesse personalizá-la quando estiver pronto para isso.

