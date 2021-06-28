# express_examples
Node Express Examples 


### environment
- Node v15.14.0
- mysql 5.8


### install
```sh
git clone https://github.com/asj214/express_examples.git

cd express_examples

nvm use v15.14.0

npm install

npm install -g sequelize-cli
```


### sequlize command
- make migrations (create table): sequelize-cli model:generate --name Post --attributes title:string,body:text --underscored
- make migrations (add column): sequelize-cli migration:generate --name add_column_posts
- migrate: sequelize-cli db:migrate

sequelize-cli --h