#Site Layout

The purpose of this article is to serve as a guide to the structure of MCDI's JIRA installation, with notes on best-practice for future structural modifications.

##General Structure

MCDI's JIRA installation has been designed from the ground up to mirror the best-practice concepts for structural organization as outlined by Atlassian, in an effort to ensure that their system documentation is maximally compatible with our own.  In light of that fact, an effort has been made to include links to relevant articles within the Atlassian knowledge-base for further reading where possible.

[You can view an overview of JIRA Core's structure here](https://confluence.atlassian.com/jiracoreserver072/what-makes-up-jira-core-829092409.html)

###Categories
Categories are collections of projects which share a common attribute.   As an example, the category

**"MCDI Operations"**
would contain projects like

* HR
* IT
* Finance
* Business Development
* International Division General Management

and the category **"MCDI Projects"**
would contain projects like

* ZICORE
* MalariaCare
* Benin ARM3

Giving projects a parent category designation allows for more precise sectioning of structure, allowing for the support of a diverse range of BUs within a single application.

-----

###Projects
Projects are roughly analogous to "Departments" or "Business Functions" within the application context.  Projects serve as "buckets" for issues (see below).  Each project has a long-form name, like

* Business Development
* Finance
* Benin ARM3

and a short-form name ("slug") like

* BD
* FIN
* BARM3

The long-form name is utilized primarily for navigation within the UI, whereas the slug is used primarily for referencing issues.

-----

###Issues
The most basic "work packet" in JIRA is the issue.  There are multiple types of issues, which all serve different functions, outlined below.  

When an issue is created, it is assigned a unique identifier comprised of the slug of the parent project and the index of the issue within the project context, i.e.

* HR-1
* BARM3-14
* ZICORE-9
```ruby
    Power Tip: simply typing the identifier of an issue within a comment or description field will generate
    an interactive link to that issue.
```

####Components

In contrast to SharePoint, "Component" is a predefined keyword within JIRA which is utilized for the subdivision of issues within a project.  This is most useful in projects which interact with many other projects, such as Finance and HR, but also has a place in smaller projects as a tool for indicating "categories of work."  By way of example, take a look at the currently configured components within the HR project:

![layout_1](img/layout/layout_1.PNG)

This change makes it unnecessary to create "subsites" for things like Finance and HR within each project.  

"Epics" (discussed below) take the place of SharePoint components.

####Epics

An epic captures a large body of work. It is essentially a large issue that can be broken down into a number of smaller issues.  Within the context of MCDI's installation, epics are roughly analogous to "Components" as previously defined within SharePoint.  However, as discussed above, it is important to make a distinction between components and epics.

Stories

Subtasks
