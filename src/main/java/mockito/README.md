http://www.martinfowler.com/bliki/TestDouble.html

1. Dummy: This is an object that is used only for the code to compile—
it doesn't have any business logic (for example, an object passed as a parameter 
to a method)
2. Fake: This is an object that has an implementation but it's not production ready 
(for example, using an in-memory database instead of communicating with a 
standalone one) 
3. Stub: This is an object that has predefined answers to method executions 
made during the test 
4. Mock: This is an object that has predefined answers to method executions 
made during the test and has recorded expectations of these executions 
5. Spy: These are objects that are similar to stubs, but they additionally 
record how  they were executed (for example, a service that holds a record 
of the number of  sent messages)
 