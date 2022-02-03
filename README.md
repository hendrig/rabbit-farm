# Rabbit Farm

This project is a basic "simulation" of a rabbit farm that I'm using to learn a few concepts.

The goal with this project is to learn:
- Microservices using `C#` and `docker`
- Message Queues with `RabbitMQ`
- NoSQL databases with `MongoDB`
- Front End JS Frameworks with `ReactJS`

## The Farm

This project should have, at the end, the following:

1. A service that represents a rabbit house. The house can have a specific amount of rabbits on it, all of them with the same gender.
2. A service that represents a rabbit reproduction facility. This place is where fertile rabbits need to be sent in order to copulate and generate new rabbits
3. A service that represents a rabbit nursery, where pregnant rabbits goes to give birth to new rabbits
4. A farm management, which can create new houses, reproduction facilities and nurseries

Each service must have its own C# project, unit tests and documentation.

Finally, it must be possible to create a set of containers that can be escalated and destroyed.

This project also expects that all the services use `CQRS` as an architectural pattern for development.

## Disclaimer

It is important to notice that this is a learning project. As I'm writing this words I do not know a bunch of stuff about the subjects I'm proposing to study. I'm creating this project to learn more about it and improve my knowledge about it.

Also, English is not my native language and I do not know how a real "rabbit farm" actually works. Some terms and definitions may sound strange to a native English speaker or a rabbit farm owner.