_Published language_ is a domain model accessible by all bounded contexts. For example, this can be a standard format such as EDIFACT for transactions between companies. But it is also possible to define a data structure that is only used inside a company and published, for example, in Wiki.

### Example

These models can be used together. The [[Open Host Service pattern]] can use _published language_ for communication. For example, the order process might accept orders from external clients. Providing a specific interface for each external client is a lot of effort, so there is a generic open host service and a published language for orders. Each external client can use this interface to submit orders to the bounded context order process.

#software_development #software_architecture #DDD_patterns 
#PublishedLanguagePattern

Источник: (https://www.educative.io/module/lesson/introduction-to-microservices/RMGONYmMJvO#The-customer/supplier-pattern)