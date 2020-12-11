**Pattern Name and classification/type:** Process Tasks

**Also known as/alias:** -

**Pattern definition:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Overview/Description:** Using this pattern, we will have a list of tasks for completing a whole project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Solution:** We will divide tasks by steps as we separate the steps to follow to make a cooking recipe.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Context/Applicability:** Tasks based projects divided by steps (when we want to determine the tasks of each step).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Motivation (problem):** Representing all the necessary tasks to complete a process structuring them step by step.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Issues/Consequences/resulting context:** With this pattern we are not representing the evolution of the tasks of a project as in kanban. Here we are giving all the steps to follow (tasks) to complete a process but without having a direct relationship with how we are doing those tasks in real life.


**Pattern model:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Graphic representation:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://github.com/isa-group/board-design-patterns/blob/main/styles-graphic-language-representation/process-tasks-board-design.pdf
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Components description:** Cards will represent tasks and lists will represent the different steps in which we divide the whole project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Participants description:** As tasks do not flow between lists, it is not necessary human interaction with the board. We will add tasks one time, and they will not need changes. Furthermore, we can add more cards (or delete one) according to our needs during the process, but it is not allowed to change cards (in this case, we are using this board as a kanban, we are introducing card flow).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**•	Collaboration/behaviour:** Cards will not move between lists, so the only possible change is about adding information to the card (adding labels, tasks or assignments to a task).

**Related Patterns:** -

**Examples/Known uses:** Waterfall engineering process or a recipe.

**Implementation:** Use it like guide with steps to follow, specify the tasks as much as possible (low level description, dividing it as much as possible) and do not skip any task or step for completing the project.

**Instances/Sample code:** https://trello.com/templates/support/building-a-customer-feedback-program-C2ZIBftB
