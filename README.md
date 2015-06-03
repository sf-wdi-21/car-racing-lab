# Car Race
Fill `lib` with code to build a car race.

You should have:

- a Car class that can accelerate to a certain speed
- a Race class that when instantiated instantiates two cars and accelerates each to a random speed between 0-100
- an instance method on the Race class called `winner` that returns the winning car (determined by a greater speed)
- an instance method on the Race class called `loser` that returns the losing car (determined by a lesser speed)

At the end, you should be able to do:

```ruby
race = Race.new
race.winner
# => <Car ...>
race.loser
# => <Car ...>
```
