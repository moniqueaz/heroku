# heroku
Passo a passo para subir seu projeto react no Heroku


Lnk de referencia para iniciar a documentação
-https://hackernoon.com/properly-deploy-your-react-app-to-heroku-c1a13f5f978c


### Deploy using Hiroku Git

Install the Heroku CLI
Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login
Clone the repository
Use Git to clone github-search-teste's source code to your local machine.

$ heroku git:clone -a github-search-teste
$ cd github-search-teste
Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master

### Heroku CLI

-https://devcenter.heroku.com/articles/heroku-cli
