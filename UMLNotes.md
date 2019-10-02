# UML Notes

## Class

* Accessibility
  * "-" Private
  * "+" Public
  * "#" Protected
  * "~" Package-Private
* Relationships: ![img](https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Uml_classes_en.svg/1280px-Uml_classes_en.svg.png)
* NOTE: To Show abstract classes we can place the name in italics or enclosed in <<>>
  * (ex) *AbstractClass* or <<AbstractClass>>
* Multiplicity
  * 1 ~ denotes there is only 1 of that object being used
  * 0..1 ~ denotes zero to one
  * n ~ specific number $n \in \mathbf N$
  * 0..* ~ denotes "zero to many"
  * 1..* ~ denotes from "one to many"
  * m..n ~ denotes a specific number range
* Example: ![img](https://upload.wikimedia.org/wikipedia/commons/d/d6/Uml_diagram2.png)

## Sequence

* Message: Show the information being sent between objects
* Return Message: when an object sends a message back (to the actor)
* Alternative Frame: symbolizes the choice between two or more message sequences
* Activation Boxes: Show when, and for how long objects are active
* Sequence Example(s): ![img](https://i.pinimg.com/originals/1b/89/5f/1b895f2591cc045e404a8438cea82798.png)

![SequenceExample](C:\Users\simon\Pictures\Education\SequenceExample.png)

