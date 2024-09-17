[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Mq6wGbDJ)
# Instructions
This is a game of ✊, ✋, ✌
To make it work, you need to implement the logic by adding some Java classes and use OOP principals
## Add the GameElement Base Class:
This class will have a method compareWith(GameElement other) that each subclass will override.
## Add Subclasses (Rock, Paper, Scissors) that inherit from the above:
Each subclass will inherit from GameElement and implement the compareWith method to define specific interactions.
The return value for compareWith is as follows:
- "It's a tie!" if the elements are the same
- "You Lose!" if the other element beats the one that is implemented
- "You Win!" if the element implemented beats the received item

## Hints
- Use `instanceOf` keyword to compare elements of instances
- Note that the result is case sensitive
  - Can you think on how to make it case insensitive?
