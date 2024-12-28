# Cache Strategies

## Introduction

Catching is a technique used to improve the performance of websites or Applications. Catching is like a temporary storage that stores the previously accessed data or repeatedly accessed data by using that data it delivers the content more quickly without fetching the data from the database recursively.

### Benefits of catching:

- One main benefit of catching is that it improves performance.

- it decreases the load on the server.

- it improves the user experience.

## Catch Strategies:

### Catch Aside:

In this strategy, when data is required for the application, the first checks in the catch. if data is not present in the catch then check in the database and add to the catch for the feature reference.

### Write Through:

In this strategy, the data is written in both catch and database at the same time. if any data is updated it also updates the both catch and database at a time. So in this strategy write operations become slow.

### Write Behind:

In this strategy, the data is first written in the catch and then updated in the database.so it improves written operations it also has chances of causing data inconsistency.it needs to be properly managed.

### Read Through:

In this strategy, the catch is used as a primary database. if any application requests the data it first checks in the catch and then if data is not found it checks on the database. then it stores the data in the catch for the feature use.

## References:

- https://www.youtube.com/watch?v=2zIFUqTx_TU
- https://medium.com/@mmoshikoo/cache-strategies-996e91c80303
