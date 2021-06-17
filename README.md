### Comandos de Sequelize

sequelize model:generate --name Brand --attributes name:string

sequelize model:generate --name Payment --attributes type:string

sequelize model:generate --name Category --attributes name:string

sequelize model:generate --name Gender --attributes type:string

sequelize model:generate --name Size --attributes name:string

sequelize model:generate --name Role --attributes description:string

sequelize model:generate --name State --attributes description:string

sequelize model:generate --name Address --attributes street:string,number:integer

sequelize model:generate --name User --attributes first_name:string,last_name:string,username:string,email:string,password:string,address_id:integer

sequelize model:generate --name UserHasRole --attributes users_id:integer,roles_id:integer

sequelize model:generate --name Product --attributes name:string,price:decimal,stock:integer,stock_min:integer,stock_max:integer,brands_id:integer

sequelize model:generate --name Image --attributes name:string,url:string,description:string

sequelize model:generate --name Shipping --attributes street:string,number:integer,delivered_date:date

sequelize model:generate --name Order --attributes number:integer,date:date,total:decimal,users_addresses:integer

sequelize model:generate --name OrderDetails --attributes quantity:decimal,subtotal:decimal

npx sequelize db:migrate

### Tobias Crescitelli

