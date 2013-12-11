#Chuchu blog
Blog de ejemplo empleando el tutorial de Padrino para familiarizarme con la forma de trabajar del framework.

##Pasos que he seguido
- Instalar la gema padrino (también puedes crear un Gemfile y realizar un bundle install):

        $ gem install padrino

- Crear el proyecto con el siguiente comando:

        $ bundle exec padrino g project chuchu_blog -t rspec -e haml -c sass -s jquery -d datamapper -b

##Instrucciones para ejecutar en local
1. Clona este repositorio para tener el código

        $ git@github.com:DavidHerBet/Padrino-ChuchuBlog.git

2. Instala las gemas correspondientes sin el entorno de producción:

        $ bundle install --without production

3. Ejecuta el programa mediante padrino:

        $ padrino start

4. Abre el navegador y ve al puerto 3000 para ver la aplicación:

        http://localhost:3000/

##Autor
David Hernández Bethencourt
