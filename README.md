# On Track
This project project is meant to be a project tracker with built in functionality for a kanban board (glorified todo list), a notes section, and possibly a sources/references section.

*The Problem:*
Many students struggle to find a method of taking notes that allows them to keep an easily accessible record/log of all their findings in one place. Many differing tools are often strung together in order to fill this, rather than there just being one. It also provides a way for them to track their progress as they progress.

*The Purpose:*
It is primarilly designed to fulfill a note taking functionality for students having to write research papers. The kanban board will allow them to keep track of what they need to do. The notes can literally contain an essay as they write it, and lastly the references section will allow them to add their sources to the board as well.

*The Target Audience:*
The primary target audience is university students. However, it will also have potential applications for other positions such as reserch assistants, general project management in multiple sectors, etc.


## Plan of Action
### MVP (minimum viable product)
The following table contains the most needed features for the app to function well, while prioritising the needs of the Target Audience.

|Feature                  |Relevance to Problem    |Extra Info                            |
|:-----------------------:|:----------------------:|:------------------------------------:|
|User registration & login|Privacy of students work|Pertinant to issues such as plagarism |
|User can view tasks board|Allows User to see complete vs incomplete tasks|               |
|User can add tasks       |Allows user to create list of needed tasks to complete|        |
|User can delete tasks    |Allows user to remove un-needed tasks|                         |
|User can add notes to project|Ensuring they are able to keep track of ideas|             |
|User can update notes & tasks|Meaning they can add and remove information as needed|     |
|User can write essay     |So that their essay is kept with the rest of their project|    |
|Owners can delete project board|Keeps their workspace clean once a subject is complete|  |


### Additional Features
The following table contains a list of additional features for future iterations of the app. These will either be coded as 'should haves', 'could haves', or 'wont haves' once the relevant issues are created.

|Feature                        |Relevance                                         |Extra Info                                                                  |
|:-----------------------------:|:------------------------------------------------:|:--------------------------------------------------------------------------:|
|User can login with socials    |This makes it easier for students to access       |Likely to be 'wont have' and reserved for future iteration                  |
|User can add editors to project|As may be required for group projects             |Should be able to utilise the built in group model of django to achieve this|
|Editors can add project tasks  |Allows group to contribute to project direction   |                                                                            |
|Editors can update tasks status|Allows group to update current progress of project|Probably a 'could have'                                                     |
|Users can update task status by dragging task to relevant section|Increases responsiveness|Essentially mimmiking github's project board                        |
|List of owned projects is sortable by title|Increases convenience for students to find specific subject notes|Probably 'could have'                            |
|Filter tasks by status         |Making them more accessible                       |                                                                            |
|Filter projects by Editor names|for better access to group work                   |                                                                            |




- User registration and login will be needed to ensure the privacy of each indivudials work.
- creation of multiple project workspaces.
- ability to create tasks, so that students may keep track of what they have done and what still needs doing.
- task content, so that tasks can be expanded on to clarify short check points for group projects.
- Creation of notes so that students can make notes on their project as they go.
- Creation of essay, so students can type out their essay and have it remain tied to their projects workspace.



(not technically MVP)
- ability for project creator to add authorised editors so that groups can have access to the same workspace.