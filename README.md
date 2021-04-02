![PrimeFaces icon](https://www.primefaces.org/wp-content/uploads/2016/10/prime_logo_new.png)


This is a sample maven project to reproduce this issue: https://github.com/primefaces/primefaces/issues/7193

You can execute the sample with <strong>mvn jetty:run</strong> command and hit http://localhost:8080/primefaces-test to run the page.

Per default the application uses Mojarra 2.2.x. 
You can also use other versions with the available maven profiles: myfaces22, myfaces23, mojarra23

`mvn clean jetty:run -Pmyfaces22`

`mvn clean jetty:run -Pmyfaces23`

`mvn clean jetty:run -Pmojarra22`

`mvn clean jetty:run -Pmojarra23`
