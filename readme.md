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
- [ ] Add LDAP auth system

  
