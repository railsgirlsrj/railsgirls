#Rails Girls Demo App


## *1.* Rails Girls App Tutorial 1

## Geração da aplicação railsgirls (usando RVM)

###*1.* Instala o Ruby
```shell
rvm install 2.2.3 #instala o ruby 2.2.3
rvm use 2.2.3@global #seleciona o gemset global do ruby 2.2.3
gem install bundler #instala o bundler no gemset global
```
###*2.* Gera a aplicação *railsgirls*
```shell
rvm use 2.2.3@railsgirls --create #cria o gemset railsgirls para o ruby 2.2.3 e o seleciona
gem install rails #instala a gem rails nesse gemset
rails new railsgirls #gera uma nova aplicação rails chamada railsgirls
cd railsgirls #entra na pasta da aplicação gerada
echo "2.2.3" > .ruby-version # cria arquivo .ruby-version
echo "railsgirls" > .ruby-gemset # cria arquivo .ruby-gemset
bundle install #instala as dependências da aplicação recém-gerada
```
