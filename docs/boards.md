The purpose of this article is to provide information related to the use of JIRA's Agile Boards function for administrating projects.

##Atlassian Documentation
[You can view an overview of how boards work in JIRA here.](https://confluence.atlassian.com/jirasoftwarecloud/what-is-a-board-764477964.html)

In order to assure that all necessary functions are available, all default boards have been created as [Scrum boards](https://confluence.atlassian.com/jirasoftwarecloud/using-your-scrum-backlog-764478062.html).  

The term "Scrum" refers to a specific kind of [Agile development methodology](https://en.wikipedia.org/wiki/Agile_software_development)- knowledge of Agile development processes is by no means required to use boards, however, if you would like to learn more about Agile concepts, feel free to check out [agilemethodology.org](http://agilemethodology.org).

-----

##A Word of Caution
While _any_ JQL query or [filter](filters.md) can be used to create a board, interacting with multiple projects concurrently within the same board poses some risks to the underlying organization of the system.  

Wherever possible, please refrain from creating new boards on your own.  If you require a custom board, please log a feature request under the [!JIRATEK](http://ec2-54-162-47-42.compute-1.amazonaws.com:8080/projects/JIRATEK/issues/JIRATEK-29?filter=allopenissues) project so that IT can conduct a full review of the potential impact.

-----

##Accessing a Project's Board

To access the Board for a project:

  * Click the "Boards" tile on the top bar, and select your desired board.

![boards_access](img/boards/boards_access.png)

If you do not see the desired board in the "Recent Boards" section, click "View all boards," then click the name of board that you wish to view.

![boards_view_all](img/boards/boards_view_all.png)

-----

##The Backlog Screen

The root screen of the Board function is called the "Backlog."  Before progressing further, please click the "Epics" tab on the left-hand side of the screen.

![boards_backlog](img/boards/boards_backlog.png)

Clicking the "Epics" tab will cause a new pane to slide out from the left-hand side of the screen that contains all of the Epics for the project associated with the board.

![boards_backlog_epics](img/boards/boards_backlog_epics.png)

-----

##Layout

The Backlog screen consists of 4 main regions:

  * Filter Bar
  * Epics Pane
  * Backlog Pane
  * Issue Pane

###Filter Bar

![boards_filter_bar](img/boards/boards_filter_bar.png)

The Filter Bar allows you quick access to search and common filters.

###Epics Pane

![boards_epics_pane](img/boards/boards_epics_pane.png)

The Epics Pane provides a quick view of the epics within the board you are working on.  

Clicking the colored dropdown button within a given Epic card will allow you to perform several potentially useful operations on said Epic, as shown below:

![boards_epics_pane_dropdown](img/boards/boards_epics_pane_dropdown.png)

Clicking the arrow in the top left hand of an Epic's card will reveal a more detailed breakdown of the work contained within that Epic, as shown below:

![boards_epics_pane_caret](img/boards/boards_epics_pane_caret.png)

###Backlog Pane

Blahdeeblah

###Issue Pane

Blahdeeblah

-----

##Common Use Cases

Blahdeeblah

###Adopting an Orphaned Issue

Blahdeeblah

###Project-Level Maintenance

Blahdeeblah

###Rapid Prototyping

Blahdeeblah
