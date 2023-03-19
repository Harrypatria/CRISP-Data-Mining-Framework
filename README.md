## CRISP-Data-Mining-Framework

### Key Actions to Consider to improve CRISP-DM Data Science Projects
 
With this in mind, when using CRISP-DM for data science projects, teams should consider the following items to help ensure a successful project:

- 1. Define a team process
The team process should define how the team communicates, prioritizes tasks and “loops back” to previous project phases.
Some argue that CRISP-DM suffers from the same weaknesses of waterfall frameworks, and encumbers rapid iteration (since CRISP-DM has a heavy on documentation; for example, CRISP-DM calls for 12 reports prior to data collection). This is a good example of why a data science project should not be thought of as a waterfall effort.
Some teams ignore the document aspect of CRISP-DM, but if this is done, there needs to be other mechanisms for the team to communicate and prioritize work. Hence, perhaps the largest drawback when using CRISP-DM is that it doesn’t really focus on how should the team collaborate, communicate, and effectively prioritize potential tasks? Teams can leverage the CRISP-DM phases, and then use a framework such as Scrum, Kanban or Data Driven Scrum to prioritize potential tasks.

- 2. Ensure multiple experiments 
When using the CRISP-DM framework, it should also be clear how the team will repeat / iterate through the life cycle multiple times within a project. For example, after exploring some data and deploying an analysis, additional data might be added to the analysis.
While it’s important to do multiple iterations, each team needs to determine how this would actually work for their project. So, the team needs to think through how iterations are defined and then evaluated (such as Scrum’s time boxed sprints, Data Driven Scrum’s functional iterations or Kanban’s focus on minimizing flow but not specific iterations).  For example, here is one way to merge CRSIP-DM and Scrum.

- 3. Define team roles  
CRISP-DM does not include the concept of roles (nor a team). Roles can include stakeholders / product owners (to ensure the insight is actionable). See 10 reasons why you might need a product owner / product manager for some reasons why this is so important.
In addition, there might need to be a team member more focused on process (in other words, a process master) or on an aspect of the analysis (such as data engineering). See the discussion on 8 roles in a data science team for more on the need for roles in a data science project.

- 4. Ensure actionable insight 
How does the team ensure actionable insight? If the team does not focus in the stakeholders / product owners (which is possible within the CRISP-DM construct), there is the risk that there will be interesting insights, but that those insights will not be actionable.

5. Define the subitems within each phase
Finally, the six phases of a project are fairly high level. There are many potential subtasks within each phase of the project. The team needs to be clear how those tasks (within a phase) are defined, and how to ensure tasks will not be forgotten. Many have defined lists of tasks for each phase. Others have addressed these concerns by also defining additional high level phases (e.g., Microsoft’s TDSP)
For example, some tasks that should be explicitly discussed include:
How/where does the team talk about potential bias (in the data or the machine learning algorithm) or if model transparency is required
How should missing data been handled
How to determine the appropriate level of accuracy for the business problem (sometimes, data scientists love to improve a model by 0.5% – without knowing the business value of that improvement)
How does the team know the results are valid (i.e., there was no error during the analysis)
If the model will be deployed in a production environment, how often will it need to be updated 
 