# kabug-rb
Repositório do proejto Kabug com Cucumber, Capybara e Ruby

## Como execuar o projeto

* importate ter o Ruby instalado (versão 2.5 ou superior)

### Instalar o bundler

`gem install bundler`

### Instalar as dependências do Ruby (projeto)

`bundle install`

### Executar localmente (Maquina)

` bundle exec cucumber `


### Executar no servidor de CI (gernado reports JSON) 

`bundle exec cucumber -p ci `

### Criar imagem do docker usando DockerFile

`docker build -t guivinilincoln/rubyqa . `

#### Fazer um push da img criada

`docker push guivinilincoln/rubyqa `