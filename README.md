# Secure-Highway-Toll-System

in This project, we design a distributed and concurrent system for a Secure Highway Toll System. 

we begin by breaking down the project to subproblems, then studing the problem in an indepth format to recognise related patterns and sequences. next we generalise the problem to genrate a general solution and the draw charts that would guide our algoritm design. 
a) Developed a software system context class model depicted on a class diagram showing how the system interfaces to the external environment.
b) Developed a static model showing the entity classes in the system, attributes of the classes, and the relationships between them.
c) Developed interaction diagrams (one for each use case), using sequence diagrams, depicting the sequence of interactions among the objects participating in each use case.
d) For use cases involving entering and leaving the highway, we showed the statechart as well as the interaction diagram for each use case. 
e) Developed message sequence descriptions, describing the object interactions on each interaction diagram depicted in (c) above.
f) Developed an integrated communication diagram(s) showing all the objects and message
interfaces in the system.

PROBLEM DESCRIPTION FOR THE HIGHWAY TOLL SYSTEM:

A major metropolitan region has with a series of toll roads. Each toll road has a series of
fixed checkpoints consisting of one or more tollbooths, which serve as collection points for the toll fees. Customers who use the toll road may pay the tolls by using a transponder placed in their vehicle or by paying with cash or with credit cards at selected tollbooths.
Customers wishing to use automated transponders purchase these transponders through the
regional toll center. This regional center maintains customer accounts in a database including
owner and vehicle information, account balance, and history. Customer purchasing a transponder
must pay ahead for toll fees by credit card. Customers are notified by email or postal mail when
the accounts are running low and if the account is out of funds. Accounts are reduced by the toll
amount incurred at the end of each trip. The toll amount to be paid depends on the length of the
trip and category of the vehicle.
For access onto the toll highway, there are two kinds of toll booth.
1. High-Speed - Transponder only with no barrier.
2. Ticket issuing booth with barrier. The driver presses a button to receive the ticket.
To leave the toll highway, there are two kinds of toll booth.
1. High-Speed - Transponder only with no barrier.
2. Human operated full service booth (transponder, credit card, pay by cash) with barrier.
All tollbooths consist of an operational light to indicate whether the tollbooth is available for use;
a vehicle-approaching sensor (placed 50 feet in front of the tollbooth); a vehicle-passed sensor; a
traffic light to indicate whether the vehicle has been authorized to pass through the tollbooth; a
transponder sensor; a camera; and an alarm. Additionally, all tollbooths other than the high-speed / transponder-only lanes contain a vehicle barrier that is raised and lowered to enforce payment.
Exit tollbooths also have a display to indicate the required toll. Full service tollbooths have a card
reader device, which can read both tollbooth issued tickets and credit cards, as well as an operator
who collects the appropriate toll and authorizes a car to pass. After the driver inserts the ticket into
the card reader, the entry point and toll amount (which are read off the ticket) will be displayed on
the operator’s display. (Note that transponders may be used in any tollbooth.)
