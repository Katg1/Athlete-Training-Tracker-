# Athlete-Training-Tracker-
Check Point 3 - exercise your skills with structured data and use of inheritance.
Part one the thinking : 
Consider a trainer who wants to keep a record of the times and distances her athletes train over the season.  Ultimately we'll work up to a triathlete trainer, whose athletes will be doing at least running, cycling, and swimming. They might be doing weights and other sorts of training too.

What will be your object model for this system? You have one trainer, with multiple athletes. Each athlete can do multiple training runs, and they need to be distinct from each other. The minimum information required of a training run is what time it occurred, and how far it was. (A more realistic training run might also include other features such as particular goals, the route, time-splits and so on. Feel free to think about all of this in the model, but for convenience we will keep the implementation quite simple.)

While the implementation you will have at the end of this two week practical will be able to simplistically track athletes for a triathlete trainer, consider how your design might facilitate (or hinder) further extension of the program to include all the "bells and whistles" of a comprehensive training program. Design for the future!

1) Trainer: The trainer is the top-level entity in the system. It has a name and a list of athletes.

2) Athlete: An athlete is a person who the trainer trains. Each athlete has a name and a list of training sessions.

3) TrainingSession: A training session represents a single training activity of an athlete. It has a date and time when the training session occurred, the distance covered during the training session, and the type of training (running, cycling, swimming, weight training, etc.).

4) Distance: The distance entity represents the distance covered during a training session. It has a value and a unit of measurement (e.g., miles, kilometers, etc.).

5) TrainingType: The training type entity represents the type of training session, such as running, cycling, swimming, weight training, etc. It has a name and possibly other attributes, such as a route or time splits.
