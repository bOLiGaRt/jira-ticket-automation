# jira-ticket-automation
¡Automated! creation of jira ticktes using templates for each Jira project

Introduction

In the context of agile software development processes, the use of standardised tickets has proven to be an effective means of optimising the development process and increasing the quality of results. optimise the development process and increase the quality of the results. By using such tickets, we can work together more efficiently work together more efficiently, set priorities and organise our work transparently. A proven framework that can help to create high-quality tickets is the tickets is the INVEST method.

Efficient collaboration: Using well-structured and standardised tickets allows us to work together more efficiently. Each ticket contains clear information about the requirements, scope and objectives. This makes it easier for us to understand what is at stake and to work accordingly. This promotes smooth communication and collaboration, which ultimately leads to faster and more efficient development. development. Prioritisation, transparency and traceability: Standardised tickets allow our product managers and us as a development team to clearly define priorities. clearly define priorities. This makes it possible to identify and prioritise the most important tasks to ensure that the most valuable features are developed first. features are developed first.

NVEST method for increasing quality: The INVEST method is a framework for creating high-quality tickets. It stands forIndependent, Negotiable, Valuable, Estimable, Small and Testable.Through theapplication of the INVEST principles, tickets are better structured and deliver clearly defined results.Independent ensures that tickets are self-containedare self-contained and have no dependencies on other tickets.Negotiable allows the scope and details of the ticket to be negotiated.ticket.Valuable ensures that each ticket delivers clear added value for stakeholders and fulfils their needs.Estimable enables aEstimable enables a realistic assessment of the effort required to realise a ticket, which enables better planning and resource allocation.Small aimsSmall aims to split tickets into small, manageable tasks to ensure faster development and easier traceability.Testable ensures that the results of a ticket can be reviewed and tested to ensure that they meet the requirements.meet the requirements.By applying the INVEST method, tickets become higher quality, easier to understand and enable more efficient
development

# Creation
To create Jira ticket templates using javascript code, you need the following information in advance:

Extract the project specification: PROJECT BRIEF (example: )https://jira.schlesinger.pro//rest/api/latest/project/ https://jira.schlesinger.pro//rest/api/latest/project/XXX

Necessary information:
pid
issuetype(s)
priority
customfield(s)
...

The following Jira interface is used:
secure/CreateIssueDetails!init.jspa
