**Pattern Name and classification/type:** INFORMATION OR RESOURCES LIFECYCLE 

**•	Problem:** Situations or projects where it is important to manage the lifecycle of several resources when we need to know in which state every resource is. 

**•	Motivation:** We will use this pattern when it is critical to know the status of the resources or information that we have at our project. One of the most frequent uses of this pattern is the handling of a factory pipeline. The evolution of ideas, costumers or products is usually managed with this pattern. The usage of this pattern will allow the user to know which is the status of each resource at each moment. 

**•	Solution and graphic representation:** Each list represents a different status of the resources, usually disposed linearly ordered (as in a pipeline). In the cards we will represent the ideas, concepts or resources, with the level of detail that we need and with the possibility of attaching images, including descriptions or text fields, etc. Cards will flow through the different lists as they evolve. 

https://github.com/isa-group/board-design-patterns/blob/main/styles-graphic-language-representation/png/information-or-resources-lifecycle-board-design.png 

**•	Examples:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**o	Bike Repair Pipeline**

https://trello.com/b/9clNtU6v/bike-repair-pipeline 

 ![image](https://user-images.githubusercontent.com/47741431/110638241-963ffa80-81ae-11eb-9ac0-1d218fbdf9d2.png)

In this template, as its name indicates, we have the pipeline of a bike repair shop. As we can see in the image, bikes are represetated in cards, where it’s also stored the phone of the bike owner and the description of the bike issue, as information contained in the card. Lists represent the different possible status of the bike through the repair process. Each card will flow generally through all of them, linearly, until they are repaired and the process is completed. 

 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**o	Customer Success Board**

https://trello.com/b/tBR1MPkA/customer-success-board 

 ![image](https://user-images.githubusercontent.com/47741431/110638276-a061f900-81ae-11eb-9a5b-32784af5489a.png)

In this template we have five possible status of the costumers of an enterprise, since they are new clients (first list). In each card we will represent customer related information as for example, customer background, key contacts or contract details. The expected and normal flow is linear, but it’s a bit more free than the previous example, because a card can return from “At Risk/Focus” to “Active Costumers”, for example. 

**•	Related Patterns discussion:**

This pattern follows an idea similar to kanban, but representing information or resources instead of tasks. In kanban, cards flow through the phases or steps that we need for completing the process, while in this case, we usually represent the task that we have to do in the name of the list, and resources flow through them, as in the bike repair shop example. Kanban is more focused on the tasks, while this pattern allows a higher level of detail and amount of information of each resource. 

Regarding to “Assigned information or resources” pattern, we will choose one or another depending on wheter the information flows between lists or not. “Assigned information” focus on the assignment, usually a person or a departmend, while in this pattern we are focusing on the state of each resource. If we want to indicate the assigned person of a card, we will put a label or a comment in the resource card. 
