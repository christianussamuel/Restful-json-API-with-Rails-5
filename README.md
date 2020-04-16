# Restful-json-API-with-Rails-5
 built a traditional server-rendered web application with Rails
 
 Using postgre on the db
 add this line on your config/database.yml
 
 ![database.yml](https://github.com/christianussamuel/Restful-json-API-with-Rails-5/blob/master/image.PNG)
 
 change the default gem'sqlite3'
into __gem'pg'__ on your Gemfile

Use https://httpie.org/ as the client and run the server on your registered port
for example, my port was :4000

run __$rails s -p 4000__

add the request on your __httpie__
using the method __$http _request_:_port_/_path___
![img](https://github.com/christianussamuel/Restful-json-API-with-Rails-5/blob/master/image2.PNG)

check on your __localhost:_port___
and you will see the result on your /_todos_ path
![img2](https://github.com/christianussamuel/Restful-json-API-with-Rails-5/blob/master/image3.PNG)

