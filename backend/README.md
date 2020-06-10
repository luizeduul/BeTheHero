<h1 align="center">Instruções de uso para o backend</h1>
 
<p>Feito isso você irá precisar instalar as dependencias do projeto</p>
<p>Abra a pasta do projeto BeTheHero, abra a pasta backend no terminal</p>

<p>Faça a instalação das dependencias do projeto. Com yarn ou npm. 
 
## yarn -> yarn install 
  
<p>ou</p> 
    
## npm -> npm install
  
<p>Após completar toda a instalação, execute o comando: </p>
<p><strong>yarn start</strong> -> para rodar o script de desenvolvimento.</p>
<p>**Se ocorrer algum erro do nodemon não estar instalado, faça a instalação com yarn add nodemon -D</p>

<p>Também será necessário rodar as migrations para criar as tabelas da base de dados com o comando <strong> yarn knex:migrate </strong></p>
<p>Mais informações consulte a documentação do knexJS <a href="http://knexjs.org/" target="_blank" rel="noopener noreferrer">Clicando aqui</a></p>
   
<p>Para fazer o teste da api, utilize o insomnia que exportei um arquivo das rotas, está na raiz da pasta backend</p>
    
<p>Abra o insomnia, application -> Preferences -> Data -> Import Data -> Import from file -> selecione o arquivo e clique em import, pronto, irá importar as rotas prontas para usar no insomnia, só necessário colocar os dados de acordo com a ação que queira executar</p>
