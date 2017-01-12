## Description ##
Proof of concept with go and rabbitmq using the most basic working example

http://www.rabbitmq.com/tutorials/tutorial-one-go.html

### prerequisites ###
* docker
* go

#### install and run rabbitmq with docker ####
`$ docker run -d --hostname my-rabbit --name some-rabbit -p 8080:15672 -p 5672:5672 rabbitmq:3-management`


