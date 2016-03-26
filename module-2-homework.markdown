## Week 1

##### Ongoing
  * Reverse-engineer one of your favorite websites to practice your HTML/CSS skills.
  * [CSS Zen Garden](http://www.csszengarden.com/)
  * Experiment with [Bootstrap](http://getbootstrap.com/).

##### Day 1
  * Finish styling TaskManager using Bootstrap `layout.erb`, `index.erb`, `show.erb`, `new.erb`, and `dashboard.erb`. [Here](https://gist.github.com/rwarbelow/da3ef21480b704305e68) is how to add a layout.erb file with a <%= yield %>.
  * Research: What is CRUD (in the programming sense of the word)? What CRUD functionality do we have in TaskManager already and what are we missing? What routes/views/methods would we need to add in order to have full CRUD functionality?

##### Day 2
  * CRUD either Skill Inventory or Robot World. Instructions are at the bottom of [this file](https://github.com/turingschool/lesson_plans/blob/master/ruby_02-web_applications_with_ruby/crud_sinatra.markdown).

##### Day 3
  * Continue working on Skill Inventory or Robot World. Add model and feature tests using Capybara that hit the routes in your controller. Timebox this to <= 2 hours.
  * Work through the [Fundamental SQL](http://tutorials.jumpstartlab.com/topics/sql/fundamental_sql.html) tutorial in preparation for tomorrow. This should take approximately 40 minutes. Come with questions.

##### Day 4
  * Transform Skill Inventory or Robot World to use Sequel & Sqlite3. You'll continue working on this over the weekend. Submit the link to your repo **updated for 1602 after merging request at the link** [here](https://github.com/turingschool/ruby-submissions/pull/1490) no later than Sunday at 8pm.
  * [Watch Sharif Ramadan's intro to 1NF, 2NF and 3NF databases. They're only about 4 minutes each.](https://www.youtube.com/watch?v=K7vzLrGCV50&list=PLQ9AAKW8HuJ5m0rmHKL88ZyjOIKejvrj0) intro to database normalization video.
  * Suggested reading about database normailization:
    *  [DevShed - An Introduction to Database Normalization](http://www.devshed.com/c/a/mysql/an-introduction-to-database-normalization/)
    *  [Mike Hillyer's Blog Post - intro to database normalization](http://mikehillyer.com/articles/an-introduction-to-database-normalization/)


##### Day 5 & Weekend
  * Continue transforming Skill Inventory or Robot World to use Sequel & Sqlite3.
  * Suggested: Read the [Learn SQL the Hard Way](http://sql.learncodethehardway.org/book/) book.
  *  * [Watch Sharif Ramadan's intro to 1NF, 2NF and 3NF databases. They're only about 4 minutes each.](https://www.youtube.com/watch?v=K7vzLrGCV50&list=PLQ9AAKW8HuJ5m0rmHKL88ZyjOIKejvrj0) intro to database normalization video.
  * Suggested reading about database normailization:
    *  [DevShed - An Introduction to Database Normalization](http://www.devshed.com/c/a/mysql/an-introduction-to-database-normalization/)
    *  [Mike Hillyer's Blog Post - intro to database normalization](http://mikehillyer.com/articles/an-introduction-to-database-normalization/)

## Week 2

##### Day 1
  * [ActiveRecord Practice and Set Up TrafficSpy](https://github.com/turingschool/challenges/blob/master/active_record_and_database_design.markdown)

##### Day 2
  * Continue working on Traffic Spy

##### Day 3
  * Continue working on Traffic Spy

##### Day 4 & Weekend
  * Continue working on Traffic Spy

## Week 3

##### Day 1
  * Complete the [routes and controllers](https://github.com/turingschool/challenges/blob/master/routes_controllers_rails.markdown) homework.
  * Complete Challenge #2 from [Schema Practice](https://gist.github.com/rwarbelow/80417edbcc42578cb56a). 

##### Day 2
  * [Form and Route Helpers](https://github.com/turingschool/challenges/blob/master/form_route_helpers_rails.markdown)
  * Complete Challenge #3 from [Schema Practice](https://gist.github.com/rwarbelow/80417edbcc42578cb56a). 

##### Day 3
  * Continue working on [Blogger](http://tutorials.jumpstartlab.com/projects/blogger.html)
  * Complete Challenge #4 from [Schema Practice](https://gist.github.com/rwarbelow/80417edbcc42578cb56a). 

##### Day 4 & Weekend
  * [MixMaster](https://github.com/turingschool/lesson_plans/blob/master/ruby_02-web_applications_with_ruby/mix_master). Submit your Mix Master repo and sha of the commit for the checkpoint that's due to [this repo](https://github.com/turingschool/ruby-submissions/blob/master/1508/contact_manager.yml).
  * Complete Challenge #5 from [Schema Practice](https://gist.github.com/rwarbelow/80417edbcc42578cb56a). 

## Week 4

##### Day 1

* Complete the [Sessions, Cookies, and Flashes](https://gist.github.com/rwarbelow/21a7596df9cdb551bb85) homework. 

##### Day 2
  * Authentication in ToolChest: Add functionality so that a user has many tools and a tool belongs to a user. A user can login and logout. A logged-in user can only see his/her tools.
  * Modify your `most_recent_tool` helper method to return that specific user's most recent tool added. 
  * Add a belongs-to/has-many association between `tool` and `category`. You **do not** need to create CRUD functionality for categories so long as categories can be created from `rails c` and the form to create a new tool allows the user to select a category. You will need to do some Googling in order to figure out how to insert a select dropdown into a form. 

##### Day 3

User: 
 * can view index and show page for tools that belong to self
 * cannot update users besides self
 * cannot create see or update other users tools
 * can see a category show page with all associated tools
 * cannot create, update, or delete categories

Admin: 
 * can create, update, read, and delete tools. When creating a tool they must assign it to a default user. 
 * cannot update users besides self
 * can CRUD categories

* Experimenting with APIs: Work through [this tutorial and workshop](https://github.com/turingschool/lesson_plans/blob/master/ruby_02-web_applications_with_ruby/exploring_apis.markdown) which will prepare you for extensions in your Rails Mini-Project and Little Shop. 

##### Day 4
  * [Rails Mini-Project](https://github.com/turingschool/challenges/blob/master/rails-mini-project.markdown)

##### Day 5 & Weekend
  * [Rails Mini-Project](https://github.com/turingschool/challenges/blob/master/rails-mini-project.markdown)
  * Read [this Git article](http://nvie.com/posts/a-successful-git-branching-model/) in preparation for starting Little Shop. 

## Week 5

##### Day 1
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

##### Day 2
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)
 
##### Day 3
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

##### Day 4
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

##### Day 5 & Weekend
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

## Week 6

##### Day 1
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

##### Day 2
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

##### Day 3
  * [Little Shop](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

##### Day 4
  * Demo night!

##### Day 5 & Weekend
  * Enjoy your intermission week!
