Instalação dos servidores, banco de dados e load balancer nas instâncias:


1. Primeiramente devemos usar ssh para entrar na main e à partir dela podemos usar ssh novamente para entrar em cada uma das vm nas quais iremos instalar as aplicações:

   ```
   ssh cloud@10.103.0.34
   ```
2. Em seguida vamos entrar na máquina virtual onde vamos instalar o banco de dados.
   Para relembrar o endereço dessa máquina podemos acessar o dashboard da openstack:

   - Basta acessar http://localhost:8080/horizon/project/instances/ e inserir o usuário "admin"
     e a senha obtida por meio do comando
   - ```
     juju run --unit keystone/leader leader-get admin_passwd
     ```

     Utilizando a máquina virtual

   ```
   ssh 
   ```
