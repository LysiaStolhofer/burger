# Eat-Da-Burger :hamburger:

_Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat._

------------------------------------------------------------------------------------------------------------------------------------
* Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a _Devour it!_ button. When the user clicks it, the burger will move to the right side of the page.

* The app will store every burger in a database, whether devoured or not.
------------------------------------------------------------------------------------------------------------------------------------
## Features :computer:

- HTML
- MySQL
- Node JS
- Handlebars
- ORM
- CSS

It follows the MVC design pattern; with Node and MySQL to query and route data in my app, and Handlebars to generate the HTML.

-----------------------------------------------------------------------------------------------------------------------------------
## Burger Structure

- :file_folder: config
  - :page_facing_up: connection.js
  - :page_facing_up: db.config.js
  - :page_facing_up: orm.js
- :file_folder: controller
  - :page_facing_up: burgers_controller.js
- :file_folder: db
  - :page_facing_up: schema.sql
  - :page_facing_up: seeds.sql
- :file_folder: models
  - :page_facing_up: burger.js
- :file_folder: public
  - :file_folder: assets
    - :file_folder: css
      - :page_facing_up: burger_style.css
    - :file_folder: img
      - :page_facing_up: bg.jpg
      - :page_facing_up: blackwhite.png
      - :star: burger-icon-png-13.jpg
- :file_folder: view
  - :file_folder: layouts
    - :page_facing_up: main.handlebars
  - :page_facing_up: index.handlebars
- :page_facing_up: .gitignore
- :page_facing_up: README.md
- :page_facing_up: package-lock.json
- :page_facing_up: package.
- :page_facing_up: server.js
--------------------------------------------------------------------------------------------------------------------------------
:earth_americas: https://frozen-cove-06891.herokuapp.com/

Guten Appetit! (means: 'Enjoy!')
