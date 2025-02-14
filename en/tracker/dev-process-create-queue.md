# Creating a queue for a development team

Each team has an established routine for work planning, issue execution, and product version release. If you need {{ tracker-name }} to set up a familiar workflow for the team, use an [issue queue](queue-intro.md). A queue is an area shared by related issues being worked on under a single product or pipeline.

We recommend that you create an independent queue for each of your development teams. If you want to split your work into flows, you can create several queues. For example, if you have several working groups in your team that are focused on independent sets of issues, you can create a separate queue for each such group.

To create a queue for a development team:


1. If your organization doesn't work in {{ tracker-name }}, [connect the service](enable-tracker.md).

1. Make sure all members of the development team have [full access to {{ tracker-name }}](access.md).


1. [Create a queue of issues.](manager/create-queue.md) Select a queue [template](manager/workflows.md) with statuses and issue types that are best suited to your workflow:

   - <q>Basic development model</q>: This template contains issue types and statuses that are most commonly used when developing programs and apps. A [simple issue board](#board_types) is created when you select this template.

   - <q>Software development as a service</q>: This template provides an issue type called <q>Project</q> and a status that lets you coordinate approval of your performance with the client.

   - <q>Scrum</q>: This template is suitable for teams that work with [Scrum]({{ link-wiki-scrum }}). A [<q>Scrum</q> issue board](manager/agile.md#sec_boards.md) is created when you select this template.

   - <q>Kanban</q>: This template is suitable for teams that work with [Kanban]({{ link-wiki-kanban }}). A [simple <q>Kanban</q> issue board](manager/agile.md#sec_boards.md) is created when you select this template.

   {% note info %}

   If you selected a queue template without an associated issue board, you can [create one later](manager/create-agile-board.md).

   {% endnote %}

1. If you want to change the list of issue statuses available to your queue, go to the queue settings, simply copy the [basic workflow](manager/add-workflow.md) and [edit it](manager/workflow-status-edit.md).

1. Add the employees who will be working on your product to your [queue team](manager/queue-team.md).

1. You can also configure access [rights to issues within the queue](manager/queue-access.md) if needed. For example, you can restrict certain groups of users from creating or viewing issues in the queue.