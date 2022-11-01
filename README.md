# Spring-Data-JPA-with-Hibernate-Part-3
# Spring-Data-JPA-with-Hibernate-Part-3


Which method on the session object can be used to remove an object from the cache?
   for level 1 caching to work, we need to mark it with @Transactional from spring package,
	 Spring creates level 1 caching for the Spring session associated with the transaction and for it to work we need to mark it with this annotation.
  Evict method is used on the session object to remove an object from the cache.


What does @transactional annotation do?
@Transactional annotation is used
	when you want the certain method/class(=all methods inside) to be executed in a transaction
  At a high level, Spring creates proxies for all the classes annotated with @Transactional, either on the class or on any of the methods. The proxy allows the framework to inject transactional logic before and after the running method, mainly for starting and committing the transaction.
