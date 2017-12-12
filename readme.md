
```
## Motivation
As companies grow, it becomes difficult to manage and communicate the knowledge across different departments, Opus acts as a single source of truth; a go-to place for the employees to get knowledge. It gives enterprises the power to create anything and everything; from meeting notes, project plans, product requirements, technical documentations, orchestrate processes, work-flows and more. 

There are spaces for every team, department or major project. Then employees can create, organize and share knowledge inside their relevant teams and keep work organized. There is a structured hierarchy and powerful search engine to find what you need quickly and easily. Apart from that, templates help creating documents without any hassle and there is PDF and Office Docs generation for the ease of sharing.

## Features

* Create manage Wikis (group of knowledge pages)
* Create nested pages inside wikis
* Manage wikis and pages by spaces and tags
* Invite employees by email
* Powerful ACL to assign different roles and permissions to employees.
* Slack notifications for the wiki updates
* Mark wikis and pages as favorite
* Watch wiki/pages to get notified
* In-app notifications
* Discussions using comments
* Create reusable page templates
* Search across the knowledge base

## Requirements

* PHP 7.0+
* MySQL 5+

## Installation

- Clone the repository
  ```bash
  git clone https://github.com/sokollikaj18/km.git
  ```
- Create `.env` using `.env.dist` and populate the relevant information
- Install the dependencies
  ```bash
  composer install
  ```
- Open the project directory and run the below
  ```bash
  php artisan migrate
  ``` 
- Generate an application key
  ```bash
  php artisan key:generate
  ```
- Run the database seeder
  ```bash
  php artisan db:seed
  ```

## Todo

- [ ] Responsive

  
