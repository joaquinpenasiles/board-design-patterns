# A Catalogue of Patterns for Board-based Tools

Board-based software tools for managing collaborative work (e.g. Trello or Microsoft Planner) are highly configurable information systems. Their structure is based on boards that contain cards organized in lists. This structure allows users to organize a wide variety of formal or informal information and work processes in a very flexible way. However, this flexibility means that in every situation the user is required to make decisions to design a new board from scratch, which is not a straightforward task, specially if performed by non-technical users. 

We have carried out a study following an inductive approach consisting of analyzing 91 Trello board designs from board [templates proposed by Trello users](https://trello.com/templates), which cover a wide variety of domains and use cases. From this analysis we characterize the following 8 patterns that are commonly used in board designs and are applicable to all board-based tools:

- [Information or resources lifecycle](/styles-detailed-description/information-lifecycle.md)
- [Ordered Information](/styles-detailed-description/ordered-information.md)
- [Kanban](/styles-detailed-description/kanban.md)
- [Process Tasks](/styles-detailed-description/process-tasks.md)
- [Assigned Information](/styles-detailed-description/assigned-information.md)
- [Categorized Information](/styles-detailed-description/categorized-information.md)
- [Assigned Tasks](/styles-detailed-description/assigned-tasks.md)
- [Categorized Tasks](/styles-detailed-description/categorized-tasks.md)

## About the analysis performed

For the sake of the verifiability of the analysis performed, the sources used for the analysis and its details are also available at this repository:

1. [trello-scrapping.csv](/trello-scrapping.csv): In this csv file you can find the actual scrapping of www.trello.com/templates on the date that the paper was submitted (4th December 2020). This scrapping returns the whole list of templates that can be used in the cited workstream collaborative tool. The 91 templates analyzed by us in the paper were obtained with a similar scrapping about a year before (February 2019 approximately). In this file you can take a look at the actual 230 templates created in Trello (including the previous 91), with their names, link and description among other elements. We have added two new columns to the scrapping (these columns aren't obtained of the scrapping) in which we have clasified the templates in their corresponding pattern, as we did in "trello templates clasification.xlsx" only with the first 91 templates for writing the paper. In these two columns we separate between the 91 templates considered in the paper (previously clasified and isolated in "trello templates clasification.xlsx") and the new templates obtained in the second scrape after submitting the paper.

2. [trello templates clasification.xlsx](/trello_templates_classification.xlsx): This file contains the clasification of the 91 analyzed Trello templates divided in three sheets. The first one show the raw clasification, with one row for each template and an "X" in the column of the pattern(s) in which it is classified. In the other sheets there are both summary tables in which you can clearly see the distribution of templates in our proposed patterns (how many templates are there for each pattern?) and the multiple pattern combinations (when a template contains more than one pattern). 
