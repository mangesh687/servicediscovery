# servicediscovery
 only 2 dependency 
1)cloude bootstrap 
2)eureka server 

change application.proprties 
eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false
eureka.instance.hostname=localhost
server.port=8000

and @enableEurekaServer

run application 
localhost:8080
