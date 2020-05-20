## MockServer 

MockServer (https://www.mock-server.com/) has been set up to mock several service calls, such as Decisioning Service and Finstats Transactions Service. 

Configuring a mock-server instance 

To configure a mock-server instance, a series of PUT request will be performed when executing the configure.js script, that script will determine where the mock-server instance is located by reading the following two environment variables: 

MOCKSERVER_HOST MOCKSERVER_PORT 

you can also create a file named .env on the root folder of the project containing some like this: 

MOCKSERVER_HOST=localhost MOCKSERVER_PORT=1080 







