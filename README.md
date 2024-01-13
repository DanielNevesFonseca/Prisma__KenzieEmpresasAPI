<h1>Kenzie Empresas API</h1>

<p>Para utilização desta API de forma LOCAL você precisa seguir os seguintes passos:</p>

<ol>
  <li>
    Clone este repositório em sua máquina, em uma pasta separada da pasta da entrega;
  </li> 
  <li>
    Acesse o repositório clonado através de um terminal, pode ser o terminal integrado do vsCode ou o terminal do seu computador;
  </li>
  <li>
    Digite o seguinte comando no terminal <code>npm install</code>, isso fará com que todas as dependências do projeto sejam instaladas
  </li>
  <li>
    Digite o comando <code>npm run start</code>, isso criará o arquivo <code>database.db</code> na raiz do seu repositório, em outras palavras, criará o banco de dados da aplicação;
  </li>
  <li>
    Digite o comando <code>npm run build</code>, isso populará o banco de dados, criando o usuário ADM, alguns usuários comuns, os setores(categorias), as empresas e alguns departamentos;
  </li>
  <li>
    Digite o comando <code>npm run dev</code>, isso colocará a API em funcionamento no seguinte endereço: <code>http://localhost:3333</code>
  </li>
  <li>
    Utilize a API normalmente
  </li>
</ol>

<h2>obs. Os passos 3, 4, 5 devem ser executados apenas uma vez!</h2>

<p>
  Caso sua API comece a apresentar comportamentos estranhos, vá até o terminal onde ela está executando e aperte <code>ctrl + C</code>, isso fará com que a API pare de executar, então digite o comando <code>npm run dev</code> novamente e verifique se ela voltou a se comportar normalmente, caso isso não resolva o problema entre em contato com a equipe de ensino.
</p>

<hr/>
<h2>Caso queira testar sua rota em produção siga os seguinte passos: </h2>

<ol>
  <li>
    Faça uma conta, caso não tenha, no render.com. Em seguida faça seu login.
  </li> 
  <li>
    Faça um fork desse projeto no seu perfil. 
  </li> 
   <li>
    Vá até a dashboard da sua conta no render.com e clique no botão (new +) no canto superior direito. Irá abrir um menu, e então clique na opção (web service).
  </li>
   <li>
    Siga com a opção padrão: (Build and deploy from a Git repository) e clique em next.
  </li>
  <li>
    Na aba "Public Git repository" copie e cole o repositório que fez o fork e clique no botão (continue).
  </li>
  <li>
    Abrirá uma aba com as configs iniciais do web service a ser criado. Nomeie-o com um nome coerente. 
  </li>
  <li>
    No campo do "Build Command" digite: npm install && npm run start && npm run build.
  </li>
  <li>
    No campo do "Start Command" digite: npm run dev.
  </li>
  <li>
    Selecione a opção free e crie o serviço. Se tudo ocorrer certo, fará o deploy de sua API automaticamente e te gerar a URL de acesso. 
  </li>
</ol>
