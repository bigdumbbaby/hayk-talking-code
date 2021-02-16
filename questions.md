## What does it mean for a method to "return" a value? (Jack Hubert)

## What is the difference between a procedure, a function, and a method? (Arielle Ross)

## What's the difference between a hash and an array? (Gerald Bivens)

## What's the difference between a hash and an object? (Grant Hesketh)

## When should you use map? Select? Reduce? Find? (Jeff Golden)

## What's the difference between a class and an instance of a class? (Mary Beth Ingram)

## What's the difference between an instance method and a class method? (Brett Needham) 

## What is a gem? Gemfile? Gemfile.lock? (Kat Leight)

## What is a one to many relationship? Many to many? (Colton O'Connor)
A one to many relationship (abriviated as 1:N) is a relationship between two entites, in most case classes. It is designed so that one class refers to only one instance of the other, but each instance of the other refers to many instances of the first. An example would be that an owner can have many dogs, but a dog can have only one owner.

## How does a database relate 2 tables? (Luke Thinnes)

## What does "single source of truth" mean in terms of related objects? (Ryan Choe)

## What is the purpose of the environment.rb file? (Jack Hubert)

## What does an ORM do? (Arielle Ross)

## What is an API? (Gerald Bivens)

## What is semantic HTML? (Grant Hesketh)

## What is the DOM? (Jeff Golden)

## Describe the HTTP Request/Response cycle (Mary Beth Ingram)

## What's the difference between the web and the internet? (Brett Needham) 

## What is a computer virus? (Kat Leight)

## What is validation, where can it occur, and what purpose does it serve? (Colton O'Connor)

Validation is in place so to ensure the correct data is recieved inorder to operate within the database. This can be done on the frontend (through form validation) or backend (through strong params). An example of validation would be that, in order to make a post action to the database, the client must provide an email with a "@flatiron.com" URL, or else the POST request won't execute.

## What is an event? (Luke Thinnes)

## What is event bubbling? (Ryan Choe)

## What is referential transparency? (Jack Hubert)

## What are the 4 pillars of OOP? (Arielle Ross)

## What are some tenets of functional programming? (Gerald Bivens)

## What's the difference between authentication and authorization? (Grant Hesketh)

## How do you avoid storing plain-text passwords? (Jeff Golden)

## What is serialization? (Mary Beth Ingram)

## Describe the MVC architecture pattern (Brett Needham) 

## What is Big O? (Kat Leight)

## What is a closure? (Colton O'Connor)

The concept that an inner function can access varible in an outer function once the outer function has executed. Example of this in JavaScript is 

``` 
cont num = 1
function addNumber(number){
  return number + num
}

addNumber(10)
``` 

## What is CORS? (Luke Thinnes)

## What's the semantic difference between PUT and PATCH? (Ryan Choe)

## What is DRY?

