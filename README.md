# Kosha Jira Connector

![Jira](images/jira-logo.png)

Jira is a project management tool used for tracking and managing projects, tasks, and teams. Jira is also used by software teams to track bug reporting, feature requests, and retrospective data.   

The Kosha Jira connector enables you to perform REST API operations from the Kafka API in your Kosha workflow or custom application. Using the Kosha Jira connector, you can directly access the Jira platform to:

* Create, update, or delete filters
* Create or edit issues, individually or in bulk
* Assign an issue to a user 
* Send notifications about an issue
* Configure issue fields
* Search, get, create, delete, and change issue statuses

## Useful Actions

You can use the Kosha Jira connector to manage issues, filters, and users. 

Refer to the Kosha Jira connector [API specification](openapi.json) for details. 

### Issues

In Jira, you track items of work in issues. They can be categorized as tasks, bugs, epic, stories, and subtasks. Use the Jira API to 
manage issues, including:

* Creating or editing issues, individually or in bulk
* Deleting issues
* Assigning issues to users
* Sending notifications about issues
* Transitioning issues

### Filters

Filters in Jira are saved issue searches that you can share with members of your project. Use the Jira API to manage filters, including:

* Getting, creating, updating, or deleting filters
* Configuring filter columns
* Setting favorite filters

### Projects

In Jira, a project is a collection of issues teams use to coordinate the development of products, track projects, and more. Use the Jira API to manage projects, including:

* Creating, updating, and deleting project categories
* Creating, updating, and deleting project components
* Creating, updating, and deleting project roles
* Getting a list of features for a project and modifying the state of the features

### Users

A user is any individual who you provide access to your Jira instance.  Use the Jira API to manage users, including:

* Getting, creating, and deleting users 
* Getting a list of groups a user belongs to
* Getting a list of user account IDs for a list of usernames or user keys

## Authentication

To authenticate when provisioning the Kosha Jira connector, you need your:

* Jira server username
* Jira server password
* Jira server domain name

