# Restful Routing

## Introduction
* Define Rest and explain WHY it matters
* List all 7 Restful routes
* Show example of Restful routing in practise

# Blog Index
* Setup the Blog App
* Create the Blog model
* Add INDEX route and template
* Add Simple Nav Bar

# Basic Layout
* Add Header and Footer Partials
* Include Semantic UI
* Add Simple Nav

# Putting the C in CRUD
* Add NEW route
* Add NEW template
* Add CREATE route
* Add CREATE template

# SHOWtime
* Add Show route
* Add Show template
* Add links to show page
* Style show template

# Edit/Update
* Add Edit Route
* Add Edit form
* Add Update Route
* Add Update form
* Add Method-Override

# Destroyyy
* Add Destroy Route
* Add Edit and Destroy Links

# Final Updates
* Sanitize blog body
* Style Index
* Update REST Table

Rest - a mapping between HTTP routes and CRUD

BLOG (Used SEMANTIC is another framework just like bootstrap)

CREATE
READ    /allBlogs
UPDATE  /updateBlog/:id
DESTROY /destroyBlog/:id



Name        Path           HTTP verb    Purpose
Index      /dogs           Get          List all dogs     
New        /dogs/new       Get          Show a new dog form
Create     /dogs           POST         Create a new dog,then redirect somewhere
Show       /dogs/:id       GET          Show info about one specific dog
Edit       /dogs/:id/edit  GET          Show edit form for one dog 
Update     /dogs/:id       PUT          Update a particular dog, then redirect somewhere
Destroy    /dogs/:id       DELETE       Delete a particular dog, then redirect somewhere
