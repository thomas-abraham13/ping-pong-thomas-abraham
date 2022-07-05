# ping-pong-thomas-abraham

Step 1: cd into the **complete** directory

Step 2: Run the following command in a powershell terminal window: ./gradlew bootRun

Similar Output should be visible:

Avilable Beans:
application
beanNameHandlerMapping
defaultServletHandlerMapping
dispatcherServlet
embeddedServletContainerCustomizerBeanPostProcessor
handlerExceptionResolver
helloController
httpRequestHandlerAdapter
messageSource
mvcContentNegotiationManager
mvcConversionService

Step 3: Run the following curl service on a seperate command prompt terminal: $ curl localhost:8080/ping
