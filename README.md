# RubyOnRailsSidekiq

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o projeto

Exemplo de aplicação para upload de arquivo CSV, deixando a execução em Backgroud job (sidekiq)

# Layout 
![image](https://user-images.githubusercontent.com/47953113/144491628-b35e9b3c-b260-4d2b-bc24-e71d2686ef9b.png)


# Tecnologias utilizadas

- Ruby
- Ruby On Rails
- Sidekiq
- Database Postgres

# Como executar o projeto

Pré-requisitos: Ruby / Ruby On Rails / Postgres

```bash
# clonar repositório
git clone git@github.com:IsraelSantos7792/RubyOnRailsSidekiq.git

# entrar na pasta do projeto front end web
cd RubyOnRailsSidekiq

# instalar dependências ruby
bundle install 

# instalar dependências js
yarn

# criar banco de dados
rails db:create

# criar as tabelas
rails db:migrate

# executar o projeto
rails s

```
A Aplicação estará disponível em http://localhost:3000.

Senha | usuário: admin | password: admin

# Autor

Israel Santos 

https://www.linkedin.com/in/israel-santos-94123915a/
