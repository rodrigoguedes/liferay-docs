# Business Logic with Service Builder [](id=business-logic-with-service-builder)

Once you've
[defined your application's entities](/develop/tutorials/-/knowledge_base/7-1/defining-an-object-relational-map-with-service-builder)
and
[ran Service Builder](/develop/tutorials/-/knowledge_base/7-1/running-service-builder)
to generate your service and persistence layers, you can begin adding business
logic. Each entity generated by Service Builder contains a model implementation,
local service implementation, and optionally a remote service implementation
class. Your application's business logic can be implemented in these classes.
The generated service layer contains default methods for CRUD operations, but
often times it's necessary to implement additional methods. Once you've added
your business logic, running Service Builder again regenerates your
application's interfaces and makes your new logic available for invocation.

In this section of tutorials, you'll learn about creating and invoking your
application's local services, finding and invoking Liferay's services, and
customizing Liferay services.
