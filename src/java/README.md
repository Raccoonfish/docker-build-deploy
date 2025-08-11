Java-приложение запускается на порту 8080:8080 (с параметрами JAVA_OPTS), 9404:9404 с метриками Jmx exporter  


Запуск приложения осуществляется с помощью команд:   
docker build -t java_app:v1.2.3 .  
docker run -d -p 8080:8080 -p 9404:9404 --name my_java_app java_app:v1.2.3  
