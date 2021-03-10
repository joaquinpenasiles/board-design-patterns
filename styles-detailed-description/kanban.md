Pattern Name and classification/type: KANBAN
•	Problem: Manage tasks, handling how they evolve, and monitor them. We will have a full vision of the tasks that make up a project and we will be able to know at each moment which is the status of each task.
•	Motivation: One of the most frequent uses of this pattern is the collaborative management of the tasks of a project. Depending on the complexity of the tasks, it’s probable that they go through different phases before completing the process. The minimum of this is having three status: “to do”, “doing” and “done”, but there may be intermediate stages, as “design”, “code review” or “testing”.  With a kanban pattern the user will have a global vision of the project, letting the user know how many tasks are in each state. It could be useful for applying effort balancing techniques and reduce bottlenecks, controlling the maximum number of tasks at each phase.
•	Solution and graphic representation: Each list represent a possible status of a task in the context of our problem. We will have as many lists as different phases. Tasks will be represented by cards. Initially, cards are storaged in the first bucket (usually called “to do”) as tasks are storaged in a backlog. Tasks will flow through the buckets as long as they are in progress or finished in real life. Kanban board will represent in this way the status of every task at any given moment.
https://github.com/isa-group/board-design-patterns/blob/main/styles-graphic-language-representation/png/kanban-board-design.png
•	Examples: 
o	Planning Your Day (a Kanban template)
https://trello.com/b/GtSNlyY6/planning-your-day-a-kanban-template
  ![image](https://user-images.githubusercontent.com/47741431/110635413-59becf80-81ab-11eb-998e-40b6c8b11062.png)
In this template we have the minimum expression of a Kanban pattern, with the three basic lists: “to do”, “doing” and “done”, but it adds an extra list as schedule or event index. Introducing this additional list transform our conventional Kanban in a combined pattern with “Categorized Information”.
o	Kanban Template
https://trello.com/b/LGHXvZNL/kanban-template
 ![image](https://user-images.githubusercontent.com/47741431/110635377-50356780-81ab-11eb-9697-cfddfb6e70b0.png)
In this template we have a linear and conventional Kanban pattern, with the peculiarity that it has multiple intermediate phases, as “design”, “code review” or “testing”. Tasks will advance linearly as they go through these states and they complete the whole process.
•	Related Patterns discussion:
Kanban pattern differs from “Assigned Tasks” only in the presence or absence of order between lists. This will make you to choose one or another depending on if you want to have a view of the status of the tasks of the project, or if you prefer to focus on who is the responsible of doing it.
In addition, Kanban differs from “Process Tasks” in the presence or absence of card flow. This means that in the first pattern we will represent the process to know in real time the status of each task, while with the second pattern we will have an static view of the tasks that we should do to complete the process, as in a recipe.
Kanban is usually combined with “Categorized Information” pattern, as shown in “Planning Your Day” template, the first example of this document. It enhances the usability of the pattern, because it adds extra information or some resources of the project, allowing the user to better understand the whole process than if we have only the tasks, without explanation.
