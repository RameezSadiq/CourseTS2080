An actor acts upon the use case.

High level function
User point
Set of actions
Use case diagram shows something that’s observable.
Use case diagram only covers things the user can do/observe/see.

Visualize functional requirements.
A requirement is something that is needed.
A non-functional requirement is something that does not affect the system. Like the colour of a computer.  Functional requirement is that the computer works.
Functional requirements are critical for use case.

The purpose of a use case is to define a piece of coherent behaviour without revealing the internal structure of the subject.
Help visualize the functional requirements of a system. Including the relationship of “actors” to the essential processes, as well as the relationships among different use cases.
It is important to not crowd the use case diagram. Add other information in a different diagram.


System boundary (represented by a rectangle)
Actor Is a role played by an external person or process interacting with a system.
Every business functionality Is a potential use case. The use case should list the discrete business functionality specified in the problem statement.
It just shows functionality of a system, regardless of its structure. How big, or how fast or what it weighs. 
A problem statement is a request someone makes “my system should be able to do this”. You write the requirements and deliver requirements of the function/use cases. Here is what the system should be able to do.
(problem statement aka the problem that needs solving)

-Generalization of an actor means that one actor can inherit the role of the other actor. The descendant has one or more use cases that are specific to that role.

-Associations: A-line between actors and use cases in complex diagrams, it is important to know which actors are associated with which use cases.

-Include: Include relationship represents an invocation of one use case by another use case. From a coding perspective, it is like one function being called by another function.

-Extend: This relationship signifies that the extended use case will work exactly like the base use case, except that some new steps will be inserted in the extended use case.

Extend use case is usually optional and can be triggered conditionally. 
Extended use case should make sense on its own.

when logging in somewhere... verify password is used with include. too login you have to verify the password.
login --<<include>>---->(verify password)

login <--- <<Extend>> ---(Show error message)

    Include is for "need to" whereas extend is for "May"
    
    










